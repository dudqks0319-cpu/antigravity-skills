---
name: deployment_helper
description: Helps deploy static websites to Vercel or GitHub Pages. Use this when the user asks to "deploy", "publish", or "put this online".
---

# Deployment Helper Skill

This skill helps you assist the user in deploying their web projects. The user is a non-developer, so prioritize simplicity and automated solutions.

## Strategy

1.  **Identify Project Type**:
    *   **Static HTML**: Files like `index.html`, `style.css`, `script.js` directly in the root.
    *   **Node.js/Framework**: Presence of `package.json`, `vite.config.js`, etc.

2.  **Deployment Options**:

    ### Option A: Vercel (Recommended for ease of use)
    *   **Check**: Is the user logged into Vercel CLI? (`vercel whoami`)
    *   **Action**:
        *   If not logged in, guide them to run `vercel login`.
        *   If logged in, propose running `vercel deploy --prod`.
    *   **Configuration**:
        *   For static sites, usually no config is needed.
        *   If a build command is needed (e.g., Vite), ensure `vercel.json` or project settings match `npm run build` and output directory `dist`.

    ### Option B: GitHub Pages
    *   **Check**: Is it a git repository?
    *   **Action**:
        *   Guide the user to push code to GitHub.
        *   Instruct them to go to Repo Settings -> Pages -> Source -> Select 'main' branch -> Save.

## Instructions for Agent
- **Always** check the build status locally first if it's a framework app (`npm run build`).
- If errors occur, fix them *before* attempting deployment.
- Explain what you are doing in simple terms: "I am sending your files to the Vercel server" instead of "Initiating deployment pipeline".
