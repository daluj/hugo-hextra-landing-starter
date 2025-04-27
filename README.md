# Hugo Hextra Landing Page Starter

This project is a Hugo site that:

- Uses **TailwindCSS** for a custom landing page at `/`
- Uses the **Hextra** theme for documentation under `/docs`
- Comes preconfigured with **DevContainers** for VSCode

## Setup

1. Clone the repository
2. Install Node.js dependencies
3. Build TailwindCSS
4. Run Hugo server

### Commands

```bash
git clone <your-repo-url>
cd hugo-hextra-landing-starter
npm install
npm run dev    # For Tailwind watcher
hugo server    # In another terminal
```

Or simply:

```bash
make start
```

(Needs `make` installed.)

## Development with DevContainer

Open this project in VSCode and select "Reopen in Container."

You will get:

- Hugo Extended
- TailwindCSS
- Node.js
- Go environment

## Folder structure

```
content/
layouts/
assets/css/
static/css/
.devcontainer/
```

---
Enjoy building fast websites!