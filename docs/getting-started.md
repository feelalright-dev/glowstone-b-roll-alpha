# Getting started

Glowstone B-Roll Alpha takes you from a script to a reviewed visual plan and an editor handoff.

## 1. Download the Alpha

Download the Windows packages from the trusted [Glowstone B-Roll Alpha v0.1.0 GitHub Release](https://github.com/feelalright-dev/glowstone-b-roll-alpha/releases/tag/v0.1.0).

Choose one of the Windows packages:

- [**Installer**](https://github.com/feelalright-dev/glowstone-b-roll-alpha/releases/download/v0.1.0/Glowstone-B-Roll-Alpha-Setup-0.1.0.exe): installs the application and can create a desktop shortcut.
- [**Portable**](https://github.com/feelalright-dev/glowstone-b-roll-alpha/releases/download/v0.1.0/Glowstone-B-Roll-Alpha-Portable-0.1.0.exe): runs from the folder where you place it and does not use an installer.

The Windows build is unsigned, so SmartScreen may show a warning on first launch. Continue only when you trust the source of the file and have checked its published checksum.

## 2. Prepare a model and media providers

Open Settings before your first analysis if you want to use a specific provider.

- Ollama and LM Studio need a local model server running on your computer.
- OpenRouter needs your own API key and sends script and segment text to that hosted provider when you analyze with it.
- Pexels and Pixabay need your own API keys for asset search and automatic fill.
- NASA can be searched manually without an API key.

See [Providers and API keys](providers-and-api-keys.md) for the setup details.

## 3. Create your first project

1. Start Glowstone B-Roll Alpha.
2. Create a new project.
3. Add a project title and paste your narration or script into the script field.
4. Add an optional creative brief if you want to give the analysis more context.
5. Choose the asset providers you want to browse.
6. Save the project.

## 4. Analyze the script

Choose a configured model provider and start analysis. The app divides the script into semantic beats and prepares literal and metaphorical visual query suggestions.

Review the beats and timing. Model suggestions are starting points; correct or refine them when they do not represent the meaning or visual intent of your script.

If a model server is unavailable, the Alpha may fall back to heuristic analysis so the rest of the planning workflow can remain usable. Treat fallback output as a rough starting point and review it carefully.

## 5. Find and review visuals

Use automatic fill with Pexels or Pixabay to populate suggestions for the analyzed beats. You can also browse their results manually.

For NASA, open the manual search path and search for images or videos directly. NASA is a manual, search-first source and is not part of the default automatic-fill flow.

Review the provider, title, source, media type, timing, and licensing information before selecting a shot. Select the media that best serves each beat, rather than accepting every suggestion.

## 6. Export the handoff

When the plan is ready, save the project and choose an export:

- CSV for a simple shot list;
- JSON for structured project data;
- Export package for media, manifests, shot lists, and editor handoff files.

The app is not a video editor. Open or import the exported files in your editor and complete the edit there. See [Export workflow](export-workflow.md).
