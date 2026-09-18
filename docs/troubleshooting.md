# Troubleshooting

## The app does not launch

- Make sure you obtained the package from a trusted release source.
- If Windows SmartScreen appears, check the source and checksum before continuing.
- If you used the installer, try closing an already-running Alpha window and launching it again.
- If the installer path is not working, try the portable package when it is available.
- Do not delete the local data folder as a first troubleshooting step; it may contain your projects and settings.

## Pexels or Pixabay does not return results

- Confirm that the provider is enabled for the project.
- Check that the correct API key is saved in Settings.
- Make sure the key belongs to the provider you selected.
- Check for provider rate limits or a temporary provider outage.
- Try a shorter manual query or another enabled provider.

## NASA search does not return results

- Use NASA through the manual search path; it is not an automatic-fill provider.
- Try a simpler search phrase.
- Remember that NASA searches can return images and videos, depending on the search and media filter.
- Retry later if the provider is temporarily unavailable.

## Analysis or the model connection fails

- For Ollama, make sure the local server is running and the selected model is available.
- For LM Studio, make sure the local server is running, a model is loaded, and the configured URL is correct.
- For OpenRouter, check the API key, model ID, network connection, and the provider’s current availability.
- Use a supported model selection where possible.
- The Alpha may fall back to heuristic analysis when a model cannot complete the request. Review fallback output carefully.

## The results do not fit the script

Model output and search suggestions need human review. Refine the project brief, inspect the semantic beat, switch between literal and metaphorical queries, try a manual search, or select a different provider result.

## Export does not complete or media is missing

- Save the project and make sure at least the intended shots are selected.
- Check that the export folder is writable and has enough free space.
- Read `manifest.json` and the warnings in the export package.
- A selected source may reject a download or expose only a page URL. Use the source and license fields to find the asset manually or choose another result.
- Check the `media/` folder and the local paths in `premiere-shotlist.csv` before opening the handoff in your editor.

## Where local files are stored

The packaged Alpha keeps its local database under:

`%APPDATA%\Glowstone B-Roll Alpha\data\broll-planner-alpha.db`

Package exports are written by default under:

`%USERPROFILE%\Documents\Glowstone B-Roll Alpha Exports`

## Asking for help

When reporting a reproducible issue, include the Alpha version, Windows version, package type, model/provider used, steps to reproduce, expected outcome, actual outcome, and safe screenshots or logs. Never include API keys, private scripts, access tokens, or unredacted personal data.
