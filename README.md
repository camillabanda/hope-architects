# Hope Architects Academy Rebuild

This is the complete source code for the rebuild of **The Hope Architects Academy** website, featuring the new "Blueprint" aesthetic and comprehensive application form.

## Project Structure

- **Framework**: Astro 4.0
- **Styling**: Vanilla CSS (Global variables in `src/styles/global.css`)
- **Assets**: Generated Blueprint background and Brick patterns in `public/images/`.

## Deployment Instructions

### Option 1: Vercel (Recommended)

1.  **Push to GitHub**:
    -   Initialize a repository in this folder.
    -   Commit all files.
    -   Push to a new GitHub repo.
2.  **Connect to Vercel**:
    -   Import the repository.
    -   **IMPORTANT**: If this `hope-architects` folder is inside another repo (like `scratch`), set the **Root Directory** in Vercel settings to `hope-architects`.
    -   Build Command: `npm run build`
    -   Output Directory: `dist`

### Option 2: Local Development

1.  `npm install`
2.  `npm run dev`

## Editing content

-   **Application Deadline**: Updated to **18th December** across all pages.
-   **Colors**: Edit `src/styles/global.css` to tweak the Navy (`#0B162C`) or Neon Orange (`#FF4D00`).
