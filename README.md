# Glowstone B-Roll Alpha

Glowstone B-Roll Alpha turns a script into semantic beats, visual research, and an editor handoff.

It is a free Windows desktop Alpha for creators and researchers. The workflow is:

`script → semantic beats → visual research → editor handoff`

This repository is a public release and discovery hub. It contains documentation, release notes, and issue intake only. The application source code is private and is not included here.

## Alpha status

Glowstone B-Roll Alpha is proprietary freeware. It is a pre-release application intended for careful real-world use and feedback, not a finished mass-market product.

The app helps you plan and research visuals. It is not a video editor. You review the suggested beats, queries, and media yourself, then finish the project in your editor.

## Current provider boundary

### Asset and stock providers

- **Pexels** supports generated searches and automatic fill. You provide your own Pexels API key.
- **Pixabay** supports generated searches and automatic fill. You provide your own Pixabay API key.
- **NASA** is a manual, search-first source for images and videos. It does not require an API key and is not used by default automatic fill.

### AI and model providers

- **Ollama** connects to a model server running locally on your computer.
- **LM Studio** connects to a local OpenAI-compatible model server.
- **OpenRouter** is an optional hosted model provider. You provide your own API key; your script and segment text are sent to OpenRouter when you analyze with it.

AI analysis and media suggestions are assistance, not a guarantee of factual, visual, or licensing suitability. Review the result before using it.

Third-party providers have their own terms, licenses, attribution requirements, privacy practices, and usage restrictions. You are responsible for checking those requirements before publishing media.

## Downloads

There is no GitHub Release yet. The download entries below are placeholders and must be replaced after the first release exists:

- Installer: **PLACEHOLDER — add the stable latest-release Setup EXE link**
- Portable: **PLACEHOLDER — add the stable latest-release Portable EXE link**

The current Alpha build metadata is version `0.1.0`. Release files are expected to use the names `Glowstone-B-Roll-Alpha-Setup-<version>.exe` and `Glowstone-B-Roll-Alpha-Portable-<version>.exe`.

## Windows note

The Alpha Windows application is unsigned. Windows SmartScreen may show a warning on first launch. Continue only when you obtained the application from a source you trust and the release checksums match.

## Typical workflow

1. Create a project and paste in your script.
2. Analyze it with a local model or OpenRouter.
3. Review the semantic beats and literal or metaphorical query suggestions.
4. Browse Pexels or Pixabay, or search NASA manually.
5. Select and review shots for each beat.
6. Export a CSV, JSON file, or handoff package.
7. Continue the edit in Resolve, Premiere, or another editor.

## Alpha limitations

- This is a planning, search, and export tool, not a video editor.
- Model output can be incomplete, inconsistent, or unsuitable for a particular script.
- Search results and downloaded media need human review.
- Provider availability, API limits, model servers, network conditions, and licensing terms can affect the workflow.
- Longer scripts may be more reliable when divided into manageable projects or sections.

## Documentation

- [Getting started](docs/getting-started.md)
- [Providers and API keys](docs/providers-and-api-keys.md)
- [Export workflow](docs/export-workflow.md)
- [Troubleshooting](docs/troubleshooting.md)
- [Privacy](docs/privacy.md)
- [Support](SUPPORT.md)
- [Security](SECURITY.md)
- [Changelog](CHANGELOG.md)

## Feedback and help

- Feedback: **PLACEHOLDER — add the final feedback link before publication**
- Help and support: **PLACEHOLDER — add the final support link before publication**

For a reproducible bug, use the [bug-report template](.github/ISSUE_TEMPLATE/bug_report.md) once GitHub Issues are enabled. Do not include API keys, private scripts, or other sensitive material.

## Maintainer checklist

Before making this hub public or publishing the first app release:

- Confirm the docs describe the approved, clean Alpha source snapshot and app version `0.1.0`. The source repository remains private.
- Confirm the reviewed proprietary-freeware license is final for the app and its distribution packages.
- Replace every download, feedback, support, and security placeholder.
- Run a final secret and scope scan. This repository must contain docs and release metadata only; no source, package files, local state, build output, or provider keys.
- Create a GitHub Release from a docs-only tag.
- Upload the Setup EXE, Portable EXE, `Quick Start.txt`, `LICENSE.txt`, and `SHA256SUMS.txt` to that GitHub Release. Keep binaries out of this repository.
- Generate checksums from the exact final files and verify them from a clean download.
- Add release notes and known issues.
- Replace the README placeholders with stable latest-release links after the first release exists.

## License

`LICENSE.txt` contains the proprietary freeware notice for the Glowstone B-Roll Alpha application and its distribution packages. No source code or redistribution right is granted by this documentation hub.
