# SchemeSaathi AI

A lightweight, responsive prototype for discovering Indian government schemes. It includes profile-based filtering, plain-language scheme summaries, document checklist prompts, and links to official sources.

## Run in VS Code

1. Open this `outputs` folder in VS Code (`File → Open Folder…`).
2. Open `index.html`.
3. For the simplest option, right-click the file and choose **Open with Live Server** (install the Live Server extension if needed). Or open `index.html` directly in your browser; this prototype has no build step or dependencies.

## Publish to GitHub

Create an empty repository on GitHub, then from this folder run:

```powershell
git init -b main
git add index.html README.md
git commit -m "Build SchemeSaathi scheme discovery prototype"
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```

Replace the remote URL with the repository URL GitHub gives you. Git may ask you to configure your name and email before committing.

## Notes

- Scheme matches are for discovery and are not official eligibility decisions.
- Confirm current requirements and application routes with the linked government source.
- This prototype runs entirely in the browser and does not transmit profile answers.
