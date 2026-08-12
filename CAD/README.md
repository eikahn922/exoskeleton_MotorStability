# CAD

The CAD tree preserves the original testing-to-final progression while making the correct assemblies easy to locate.

## Folder order

1. [Testing](01%20-%20Testing/README.md) — focused strap-placement concept followed by a full-exoskeleton context check.
2. [Final Implementation](02%20-%20Final%20Implementation/README.md) — selected local attachment and complete-system visualization.
3. [Shared Exoskeleton Components](03%20-%20Shared%20Exoskeleton%20Components/README.md) — unchanged components referenced by multiple source packages.

## Packaging decisions

- All four source ZIP archives passed integrity testing before extraction.
- The ZIPs are not retained because they would duplicate the extracted CAD.
- Exact SHA-256 matches were consolidated rather than stored repeatedly.
- Same-named files with different hashes were retained because they represent different design states.
- Major assembly filenames were clarified; component and nested-subassembly filenames were preserved to reduce broken SolidWorks references.

See the [source manifest](SOURCE_MANIFEST.md) for the complete audit trail.
