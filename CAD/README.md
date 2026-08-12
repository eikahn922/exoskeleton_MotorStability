# CAD

The CAD tree has exactly two project folders and preserves the original testing-to-final progression.

## Folder order

1. [Testing](01%20-%20Testing/README.md) — focused strap-placement concept followed by a full-exoskeleton context check.
2. [Final Implementation](02%20-%20Final%20Implementation/README.md) — selected local attachment and complete-system visualization.

Each focused or full-context folder is self-contained. Components intentionally appear more than once when they were supplied in multiple source packages; this makes every assembly easier to open without searching through a shared dependency folder.

## Packaging decisions

- All four source ZIP archives passed integrity testing before extraction.
- Each extracted package retains its complete component set.
- The ZIPs are not retained because the extracted CAD is easier to review on GitHub.
- Same-named files with different hashes remain distinct because they represent different design states.
- Major assembly filenames were clarified; component and nested-subassembly filenames were preserved to reduce broken SolidWorks references.

See the [source manifest](SOURCE_MANIFEST.md) for the package-to-folder mapping.
