# Landing Page Project

This is a landing page project built with Astro.

## Project Overview

This project aims to create a landing page that will eventually integrate with a login system and a product management solution (like Clerk for authentication and Google Sheets/Airtable for product data).

Currently, this project displays a collection of images located in the `public/` directory.

## Current Setup

*   **Framework:** Astro
*   **Images:** `Desktop - 1.png` to `Desktop - 6.png` are located in `public/` and displayed on the homepage (`/`).

## Commands

All commands are run from the root of the project, from a terminal:

| Command           | Action                                        |
| :---------------- | :-------------------------------------------- |
| `npm install`     | Installs dependencies                         |
| `npm run dev`     | Starts local dev server at `localhost:4321`   |
| `npm run build`   | Build your production site to `./dist/`       |
| `npm run preview` | Preview your build locally, before deploying  |

## Next Steps

We are planning to integrate:
*   **Clerk** for user authentication.
*   **Google Sheets/Airtable** for product data management (accessed via API).