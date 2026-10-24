# vaultearth assets

Files for the game vaultearth that are too large to keep in its source repository. Release builds carry what they need; the game can also fetch these itself.

## Ophane's mind (2B)

| File | Size | SHA-256 |
|---|---|---|
| `ophane-2b-Q4_K_M.gguf` | 1,274,396,288 bytes | `a8c039fbb79f905f998adbaaa9ad3e5c90b039b5abfb68b13358320202c561cb` |

The small language model that gives Ophane, the guide in the explorer's wrist band, her own words. It is part of the game and runs offline on the player's machine. On a graphics card with room for it, the game also fetches a larger mind (Qwen3.5-4B) by itself.

Base model: Qwen3.5-2B (Apache-2.0). See `NOTICE` and `LICENSE`.
