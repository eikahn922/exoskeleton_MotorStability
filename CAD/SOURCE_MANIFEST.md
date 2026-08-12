# CAD Source Manifest

All four original ZIP archives passed integrity checks before extraction. The CAD directory now contains exactly two top-level project folders: testing and final implementation.

## Package mapping

| Phase | Package | Original ZIP | Primary assembly in repository | CAD files |
|---|---|---|---|---:|
| Testing | Focused strap-placement test | `strapInterfaceTester_ASJ.zip` | `01 - Testing/01 - Focused Strap Placement Test/OPEN - Focused Strap Placement Test.SLDASM` | 4 |
| Testing | Full-exoskeleton test context | `strapTester_fullASM.zip` | `01 - Testing/02 - Full Exoskeleton Test Context/OPEN - Full Exoskeleton Test Context.SLDASM` | 11 |
| Final | Focused motor support | `finalStrapAttachment_ASM.zip` | `02 - Final Implementation/01 - Focused Motor Support/OPEN - Focused Final Motor Support Assembly.SLDASM` | 4 |
| Final | Full-exoskeleton context | `strapInterfaceFinal_fullASM.zip` | `02 - Final Implementation/02 - Full Exoskeleton Context/OPEN FIRST - Final Motor Support in Full Exoskeleton.SLDASM` | 11 |

## Packaging rule

Each repository package mirrors the complete contents of its corresponding source ZIP. Shared parts are intentionally duplicated across focused and full-context folders so each assembly package is self-contained and straightforward to open.

The primary assembly names were clarified for reviewers. Component and nested-subassembly filenames were preserved to reduce the risk of breaking SolidWorks references.

## Important same-name variants

- The testing attachment and strap files differ between the focused and full-context source packages and remain in their respective folders.
- The focused final assembly differs from the nested final subassembly included in the full-context package.
- The `RobStride_STEP.SLDPRT` file differs between the testing and final source packages.

These variants are retained rather than consolidated because they document distinct package states.
