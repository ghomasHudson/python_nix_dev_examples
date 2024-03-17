# Poetry2Nix

This project uses [Poetry2Nix](https://github.com/nix-community/poetry2nix) to manage deps.

## Creating a new project

Copy `flake.nix`, `.envrc` into directory. Run `direnv allow`.

Export existing `requirements.txt` to poetry:

```
poetry export --without-hashes -f requirements.txt -o requirements.txt
```

