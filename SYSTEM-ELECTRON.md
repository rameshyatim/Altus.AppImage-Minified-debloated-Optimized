# Why System Electron?

Traditional Electron AppImages include an entire Electron runtime.

This project removes that dependency and instead launches:

/usr/bin/electron

Advantages

- Smaller downloads
- Faster startup
- Shared runtime
- Distribution security updates

The resulting AppImage is only a launcher plus application resources.
