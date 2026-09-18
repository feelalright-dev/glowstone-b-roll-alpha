# Export workflow

Glowstone B-Roll Alpha produces a reviewed b-roll plan and files that help you continue the edit in another application. It does not render a finished video.

## Available exports

### CSV

The CSV export is a flat shot list that is useful for review, sorting, and spreadsheet workflows.

### JSON

The JSON export preserves structured project and planning data for inspection or later tooling.

### Export package

The package export can include:

- the selected media in a `media/` folder when a downloadable source is available;
- `manifest.json` with package details, source information, and warnings;
- a project shot-list CSV;
- `resolve-timeline.fcpxml` for a Resolve-oriented handoff;
- `premiere-timeline.xml` and `premiere-shotlist.csv` for a Premiere-oriented handoff;
- handoff notes explaining how to use the package and review source/license fields.

The exact contents depend on the selected shots and whether their source files can be downloaded. A provider may reject a download, return a non-downloadable page, or become unavailable. The package records those outcomes instead of guaranteeing that every selected item is present locally.

## Suggested handoff sequence

1. Save the project before exporting.
2. Review the selected shots and their source and license information.
3. Export the package.
4. Open the package manifest and read any warnings.
5. Check the `media/` folder and the source paths in the shot list.
6. Import or open the handoff files in Resolve, Premiere, or another editor.
7. Relink or replace media as needed and finish the edit in that editor.

## Licensing reminder

An exported file is not a blanket license to publish the included media. Verify the provider’s current terms, attribution requirements, restrictions, and the source information recorded in the export before using an asset in a public or commercial project.
