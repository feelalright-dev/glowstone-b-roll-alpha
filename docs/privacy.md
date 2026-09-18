# Privacy

Glowstone B-Roll Alpha is designed around local-first project storage. Your project database and default exports stay on your Windows computer.

## Local data

The packaged Alpha keeps its local database under:

`%APPDATA%\Glowstone B-Roll Alpha\data\broll-planner-alpha.db`

Package exports are written by default under:

`%USERPROFILE%\Documents\Glowstone B-Roll Alpha Exports`

While the app is running, its local desktop backend listens on `127.0.0.1:5319`. This is a local loopback service used by the desktop application.

## When network requests happen

The Alpha’s external requests are tied to user-initiated model, asset-provider, and export actions. Depending on what you do, this can include:

- sending analysis requests to a local Ollama or LM Studio server;
- sending script and segment text to OpenRouter when you analyze with OpenRouter;
- sending search queries to Pexels, Pixabay, or NASA when you use those provider searches;
- downloading selected media from a provider source when you create an export package;
- opening a provider’s source or download page when you choose that action.

Local model requests go to the local server you configure. Hosted providers and asset services receive requests under their own terms and privacy practices. Glowstone cannot control how a third-party service stores or processes a request after it is sent.

## API keys and project content

Use your own provider keys and keep them private. Do not include them in project text, screenshots, issue reports, or support logs. Review the provider’s current privacy and retention terms before sending sensitive script content to a hosted model or media service.

The app does not turn provider or model suggestions into a guarantee that an asset is safe, accurate, or licensed for your intended use. Review source, license, attribution, and privacy requirements before publication.
