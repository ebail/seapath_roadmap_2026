# seapath_roadmap_2026

This repository is used to build mind map of SEAPATH roadmap.
The open-source solution [mermaid cli](https://github.com/mermaid-js/mermaid-cli).

## Build

Run the build script to render every `.mmd` file to PNG, including one PNG
per level-1 section of `roadmap_workshop.mmd`:

```
./build.sh
```

Requires `mmdc` (`npm install -g @mermaid-js/mermaid-cli`).

To build a single file as PDF:

```
mmdc -i roadmap_workshop.mmd -o output.pdf -t neutral
```
