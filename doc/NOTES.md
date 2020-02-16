# Design
- core: only PSL
- pass if modules are missing
- minimize dependencies, code
- test everything
- think about pylint

# Features

## Backwards-compatibility
- aliases
- charts (hbar, vbar, braille)
- minimize modules
- hide modules if not in warning/error state (-a)
- WAL support

## Improvements
- pango output (improve - maybe autodetect? see #531)
- only update specific, affected modules when clicking
- allow handlers to specify whether to update or not (e.g. scroll)