# pj-pnpm

pnpm-driven Node language layer for [`kata`](https://github.com/yukimemi/kata).

Sits above [`yukimemi/pj-base`](https://github.com/yukimemi/pj-base)
and below the framework layer (`yukimemi/pj-react-web`, etc.).
Brings the package.json scaffold, TypeScript references-root, the
CI workflow that runs its `lint` / `build` / `test` scripts, the
pnpm-flavoured renri on-add hook, and the shared Node .gitignore
block.

See [`template.toml`](./template.toml) for the file list and merge
modes, and [`AGENTS.md.pnpm`](./AGENTS.md.pnpm) for the layer's
agent guidance (which becomes a marker block in the consuming
repo's `AGENTS.md`).

## License

MIT.
