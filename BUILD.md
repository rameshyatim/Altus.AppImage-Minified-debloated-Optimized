# Build Notes

This project is based on the official Altus AppImage.

The following optimizations were performed:

- Removed bundled Electron.
- Uses the system Electron runtime.
- Removed development files.
- Removed source code.
- Removed node_modules.
- Removed duplicated assets.
- Removed duplicated locale resources.
- Removed documentation and build metadata.
- Kept only runtime resources required for execution.
- Verified functionality after every cleanup step.

The resulting AppImage is approximately 1.1 MiB while preserving the main functionality of the application.
```
