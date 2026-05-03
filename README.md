![Codex RO Pets banner](assets/readme-banner.png)

# Codex RO Pets

Uma coleção de pets customizados para o Codex, inspirados em criaturas e personagens clássicos do universo de Ragnarok Online.

Cada pet preserva o visual pixel art original em um atlas compatível com o formato de pets do Codex: `pet.json` + `spritesheet.webp`.

## Pets incluídos

| Pet        | Pasta             |
| ---------- | ----------------- |
| Alice      | `pets/alice`      |
| Atroce     | `pets/atroce`     |
| Baphomet   | `pets/baphomet`   |
| Bongun     | `pets/bongun`     |
| Eddga      | `pets/eddga`      |
| Hatii Baby | `pets/hatii-baby` |
| High Orc   | `pets/high-orc`   |
| Kafra 1    | `pets/kafra-1`    |
| Kafra 2    | `pets/kafra-2`    |
| Kafra 3    | `pets/kafra-3`    |
| Kafra 4    | `pets/kafra-4`    |
| Kafra 5    | `pets/kafra-5`    |
| Kafra 6    | `pets/kafra-6`    |
| Myst Case  | `pets/myst-case`  |
| Orc Lord   | `pets/orc-lord`   |
| Peco Peco  | `pets/peco-peco`  |
| Poring     | `pets/poring`     |
| Rocker     | `pets/rocker`     |
| Sohee      | `pets/sohee`      |
| Spore      | `pets/spore`      |
| Valkyrie   | `pets/valkyrie`   |

## Instalação

Copie um pet específico para a pasta de pets do Codex:

```sh
mkdir -p "$HOME/.codex/pets"
cp -R pets/poring "$HOME/.codex/pets/"
```

Ou instale todos:

```sh
mkdir -p "$HOME/.codex/pets"
cp -R pets/* "$HOME/.codex/pets/"
```

Depois, reinicie ou recarregue o Codex para que os pets apareçam na seleção.

## Estrutura

Cada diretório em `pets/` segue este formato:

```text
pets/<pet>/
├── pet.json
└── spritesheet.webp
```

O `spritesheet.webp` usa o atlas padrão dos pets do Codex:

| Propriedade   | Valor                    |
| ------------- | ------------------------ |
| Tamanho total | `1536x1872`              |
| Grade         | `8` colunas x `9` linhas |
| Célula        | `192x208`                |
| Fundo         | Transparente             |

## Observações

Este é um projeto feito por fã e não oficial. Ragnarok Online e marcas relacionadas pertencem aos seus respectivos titulares.
