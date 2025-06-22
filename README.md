# Slice³

**Explore 2D slices of the 3-sphere (S³) with interactive, SVG-based visualization.**

A project of [Hyxos Media](https://github.com/hyxos), and a core module in the [Shard³](https://github.com/hyxos/shard3) ecosystem.

---

## Overview

**Slice³** is an open-source tool for visualizing and exploring 2D cross-sections (“slices”) of the 3-sphere (S³). Built with Next.js, TypeScript, and SVG, Slice³ provides an interactive platform for mathematicians, educators, and creators interested in higher-dimensional geometry.

## Features

- Render and explore 2D projections of S³ using SVG
- All visual styling is embedded inline—no CSS dependencies
- Responsive, interactive web interface (Next.js, TypeScript)
- Modular architecture ready for integration with Rust/WASM computation
- Download and export SVG slices (PNG export planned)
- Extensible foundation for advanced features and future Shard³ modules

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18+ recommended)
- [Yarn](https://yarnpkg.com/) or [npm](https://www.npmjs.com/)

### Installation

```bash
git clone https://github.com/hyxos/slice3.git
cd slice3
yarn install   # or npm install
```

### Running Locally

```bash
yarn dev    # or npm run dev
```

The app will be available at `http://localhost:3000`.

## Project Structure

```
slice3/
├── public/           # Static assets
├── src/              # App source code (pages, components, logic)
├── lib/              # Internal libraries, SVG logic, and future WASM modules
├── docs/             # Design docs and developer guides
├── README.md
```

## Usage

- Launch the app and explore the default S³ slice.
- Use UI controls to modify, rotate, or change the projection (more features coming soon).
- Download SVG output for use in publications, teaching, or further analysis.

## Roadmap

- [ ] Integrate Rust/WASM computation for advanced projections
- [ ] Add PNG export (via [svg2png-wasm-rs](https://github.com/don-hicks/svg2png-wasm-rs))
- [ ] Enable user authentication and session saving (Supabase)
- [ ] Expand interactive controls and visualization options
- [ ] Documentation and video walkthrough

See the [issues](https://github.com/hyxos/slice3/issues) and [project board](https://github.com/hyxos/slice3/projects/1) for more.

## Contributing

We welcome contributions from developers, mathematicians, and creative coders!  
Please see [CONTRIBUTING.md](./CONTRIBUTING.md) for guidelines.

## License

MIT License  
© Hyxos Media and contributors

## Related Projects

- [Shard³](https://github.com/hyxos/shard3) – Metaproject and ecosystem hub
- [svg2png-wasm-rs](https://github.com/don-hicks/svg2png-wasm-rs) – SVG to PNG conversion utility

## Contact

Questions or ideas?  
Open an [issue](https://github.com/hyxos/slice3/issues) or connect via the [Hyxos organization](https://github.com/hyxos).
