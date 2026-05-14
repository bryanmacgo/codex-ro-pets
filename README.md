![Codex RO Pets banner](assets/readme-banner.png)

# Codex RO Pets

A collection of custom Codex pets inspired by classic creatures and characters from the Ragnarok Online universe.

Each pet preserves the original pixel-art look in an atlas compatible with the Codex pet format: `pet.json` + `spritesheet.webp`.

## Included Pets

You can see the list of all enemy sprites at https://www.spriters-resource.com/pc_computer/ragnarokonline/

## Installation

Copy a specific pet into your Codex pets folder:

```sh
mkdir -p "$HOME/.codex/pets"
cp -R pets/poring "$HOME/.codex/pets/"
```

Or install all pets:

```sh
mkdir -p "$HOME/.codex/pets"
cp -R pets/* "$HOME/.codex/pets/"
```

Then restart or reload Codex so the pets appear in the selector.

## Structure

Each directory in `pets/` follows this format:

```text
pets/<pet>/
├── pet.json
└── spritesheet.webp
```

The `spritesheet.webp` file uses the standard Codex pet atlas:

| Property   | Value                  |
| ---------- | ---------------------- |
| Total size | `1536x1872`            |
| Grid       | `8` columns x `9` rows |
| Cell       | `192x208`              |
| Background | Transparent            |

## Notes

This is an unofficial fan-made project. Ragnarok Online and related trademarks belong to their respective owners.
