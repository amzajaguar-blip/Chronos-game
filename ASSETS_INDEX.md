# Chronos Adventure — Indice Asset

Tutti gli asset del progetto. Branch: `assets-upload`.

## assets/checkpoints/ — Checkpoint Manus (8 file, via git)

| File | Dimensione |
|---|---|
| CHRONOS_MANUS_ASSETS_CHECKPOINT_20261101_2109.zip | 6 MB |
| CHRONOS_MANUS_ASSETS_CHECKPOINT_20261101_2120.zip | 27 MB |
| CHRONOS_MANUS_ASSETS_CHECKPOINT_20261101_2327_25PN.zip | 37 MB |
| CHRONOS_CHECKPOINT_50PNG_20261102_1258.zip | 75 MB |
| CHRONOS_CHECKPOINT_57PNG_20261102_1738.zip | 81 MB |
| CHRONOS_MANUS_ASSETS_CHECKPOINT_20261101_2254_50PN.zip | 95 MB |
| CHRONOS_MANUS_ASSETS_CHECKPOINT_20261101_2254_50PN(1).zip | 95 MB |
| CHRONOS_MANUS_ASSETS_CHECKPOINT_20261101_2320_55PN.zip | 96 MB |

## GitHub Release `chronos-assets-v1` — File oltre 100 MB (2 file)

Superano il limite git di GitHub, distribuiti come release asset.

| File | Dimensione |
|---|---|
| CHRONOS_MANUS_CHECKPOINT_20261101_1648.1.zip | 130 MB |
| CHRONOS_MANUS_CHECKPOINT_20261101_1750.zip | 161 MB |

Download:
```bash
gh release download chronos-assets-v1 --repo amzajaguar-blip/Chronos-game
```

## assets/characters/ — Reference art personaggi

- `nox e lulu.jpg` — Nox e Lulu
- `ciro.jpg` — Ciro

## Build

- `ChronosShatterPremium_v2_0_0_complete_full.zip` — build completa v2.0.0 (root, su `main`)

## Clonare tutto

```bash
git clone -b assets-upload https://github.com/amzajaguar-blip/Chronos-game.git
cd Chronos-game
gh release download chronos-assets-v1 --dir assets/checkpoints
```
