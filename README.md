# Titan Plugins

Community drivers, RIP plugins, and hardware integrations for the Titan Production Suite.

## Plugin Types

- **Hardware Drivers** — Vendor-specific integrations for plotters, cutters, and presses
- **RIP Plugins** — Custom raster image processing pipelines
- **Material Profiles** — Media, ink, and substrate configurations

## Getting Started

```bash
# Clone and build a plugin
git clone https://github.com/263titan/titan-plugins.git
pnpm install
pnpm build
```

## Submit a Plugin

1. Fork this repository
2. Create your plugin under `plugins/<vendor>-<name>/`
3. Open a pull request

## License

MIT
