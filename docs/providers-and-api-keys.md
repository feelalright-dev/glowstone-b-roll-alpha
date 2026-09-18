# Providers and API keys

Glowstone B-Roll Alpha has two provider groups: asset providers that help you research media, and model providers that help interpret the script.

## Asset and stock providers

### Pexels

Pexels supports generated searches and automatic fill for images and videos. Get a key from the [Pexels API page](https://www.pexels.com/api/), then add your own Pexels API key in Settings when you want to use it.

### Pixabay

Pixabay supports generated searches and automatic fill for images and videos. Use the [Pixabay API documentation](https://pixabay.com/api/docs/) to access a key, then add your own Pixabay API key in Settings when you want to use it.

### NASA

NASA is a manual, search-first source for images and videos. It does not require an API key and is not included in default automatic fill. Use the manual search controls when you want to browse NASA material.

NASA is a specialty source, not a replacement for a general stock library. Check the source information and any applicable NASA or underlying-media requirements before publishing.

## AI and model providers

### Ollama

Ollama runs on your computer. Start the Ollama server, make sure the model you want is available locally, and point the Alpha at the server URL in Settings.

### LM Studio

LM Studio provides a local OpenAI-compatible model server. Start its server, load a model, and use the server URL and model configured in Settings.

### OpenRouter

OpenRouter is a hosted model provider. Add your own OpenRouter API key and choose a supported model. Your script and segment text are sent to OpenRouter when you analyze with it. Review OpenRouter’s current pricing, privacy, model, and usage terms before use.

## Keeping keys safe

- Use your own provider accounts and keys.
- Enter keys only in the app’s Settings surface.
- Do not put keys in project titles, scripts, screenshots, issue reports, or support logs.
- Treat any copied diagnostic output as sensitive until you have reviewed it.
- If a key may have been exposed, rotate it through the provider.

## Provider responsibility

Glowstone does not grant rights to third-party media. Provider terms, licenses, attribution requirements, rate limits, privacy practices, and usage restrictions remain applicable. You are responsible for checking the current source and license information for every asset you use.
