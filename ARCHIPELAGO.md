# Archipelago fork of RDFM

This is Archipelago Marine Research's fork of [antmicro/rdfm](https://github.com/antmicro/rdfm).

- `main` mirrors upstream exactly.
- `archipelago` is `main` plus our patches. Pushes to it build `rdfm-server` and
  `rdfm-frontend` images (`.github/workflows/build-images.yml`) for our deployment.
- Changes meant for upstream are developed on topic branches cut from `main`, such as
  `azure-blob-driver`.

The patch list, the rebase procedure, and how to retire this fork once upstream has
everything we need are in `docs/rdfm-fork.md` of the private deployment repo
`ArchipelagoMarineResearch/rdfm-iac`.
