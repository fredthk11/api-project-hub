# Project Context: API Project Hub

## Project Overview
This repository is a showcase of interactive web applications, organized by category (e.g., `/api/`, `/games/`). 
- **Root `index.html`:** Acts as the master homepage to navigate to different project categories.
- **Category Directories:** Each category (e.g., `api/`, `games/`) contains its own `index.html` dashboard listing projects within that category.

## Technologies
- **Frontend:** HTML5, Vanilla JavaScript (ES6+).
- **Styling:** Tailwind CSS (via CDN).
- **Icons:** FontAwesome 6.
- **Hosting:** GitHub Pages.

## Development Conventions
- **New Projects:** Create a new subdirectory under the relevant category (e.g., `/api/weather` or `/games/tic-tac-toe`). Implement the application with an `index.html` as the main entry point.
- **Navigation:** Update the relevant category's `index.html` dashboard to include a new card pointing to the new project.
- **Local Development:** Use a local server (e.g., VS Code Live Server) to handle `localStorage` and other web API restrictions correctly.

## Building and Running
Since this is a static site project using CDNs:
- **Running:** Simply open the `index.html` file of the desired project in your browser or run a local development server in the root directory.
- **Deployment:** The project is deployed automatically via GitHub Pages.

## Managing API Keys/Secrets
- **Security:** DO NOT commit API keys to this repository. Use environment variables or configuration files that are ignored by git if necessary, though given the nature of the project (static frontend), prefer client-side proxying or proxy-based architecture for production keys if needed. For now, this is a public showcase project.
