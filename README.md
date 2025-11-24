# Plex - Developer Showcase Platform

A community-driven platform designed to empower early developers and creative coders. Our mission is to provide a space where developers can showcase their creative projects, gain visibility, and build their contribution portfolio.

## Vision

We believe every developer deserves a stage. This platform is built to:

- **Boost Visibility:** Give early-stage developers and creative coders a chance to show their work to the world.
- **Track Growth:** Provide personal profiles with detailed statistics, including project counts, most liked projects, and contribution history.
- **Celebrate Creativity:** Focus on unique, creative, and experimental projects.
- **Open Source Contributions:** Help developers get those first crucial green squares on their contribution graph.

## Features

- **Project Showcase:** A dynamic gallery of community-submitted projects.
- **Developer Profiles:** (Coming Soon) Individual profiles displaying your portfolio, stats, and achievements.
- **Contribution Tracking:** Get recognized for your submissions and code contributions.
- **Interactive UI:** Built with a modern tech stack for a smooth user experience.

## Repository Structure

The project is organized to make contributing easy:

```
Plex/
├── index.html          # Main landing page
├── src/                # Source files (pages, styles)
│   ├── contribute.html # Contribution guide/page
│   ├── projects.html   # Project listing
│   └── ...
├── projects/           # Community projects live here
│   ├── drum-kit/       # Example project
│   ├── To-do-list/     # Example project
│   └── [your-project]/ # Your project goes here!
|
```

## How to Contribute

We welcome projects of all sizes! Whether it's a simple game, a useful tool, or a beautiful UI experiment.

1.  **Fork** this repository.
2.  Create a new folder in the `projects/` directory with your project name (e.g., `projects/my-cool-game/`).
3.  Add your project files (`index.html`, `style.css`, `script.js`, etc.) into that folder.
4.  (Optional) Add a `config.json` or metadata file if required (check `src/contribute.html` for details).
5.  Submit a **Pull Request (PR)**.

Once merged, your project will be live on the platform, and you'll get credit on your profile!

## Local Development

Want to run the platform locally or contribute to the core site?

1.  Clone the repository:
    ```bash
    git clone https://github.com/Harshul23/Plex.git
    ```
2.  Navigate to the project folder:
    ```bash
    cd Plex
    ```
3.  Start a local server:
    - **Python:** `python -m http.server 8000`
    - **Node.js:** `npx serve -p 8000`
    - **VS Code:** Use the "Live Server" extension.
4.  Open `http://localhost:8000` in your browser.

## Technologies Used

- **HTML5**
- **Tailwind CSS**
- **JavaScript** (Vanilla)

## License

This project is open source and available for educational purposes.
