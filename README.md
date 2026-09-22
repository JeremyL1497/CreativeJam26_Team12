# Clock Hit

> A reversed-timeline boss battle.

Built for [Creative Jam 26e edition](https://itch.io/jam/creative-jam-26e-edition) by Team 12.

<img width="630" height="500" alt="Clock Hit Logo" src="https://github.com/user-attachments/assets/6e1ff7bc-1437-413f-8306-5f0198c6d84d" />

🎮 **[Play it on itch.io](https://marceltaveau.itch.io/clockhit)**

## About

Clock Hit is a singleplayer 3D fighting game built around a reversed timeline — you take on a boss battle where time runs backward. Built in Unreal Engine 5.8, no generative AI used in its creation.

- **Genre:** Fighting
- **Platform:** Windows
- **Players:** Singleplayer
- **Engine:** Unreal Engine 5.8

## Controls

| Action | Keyboard / Mouse |
|---|---|
| Move | `W` `A` `S` `D` |
| Dash | `Space` |
| Catch Bullet | `X` or `F` |
| Pause | `Tab` |

## Getting Started

1. Install **Unreal Engine 5.8**.
2. Clone the repo (make sure you have [Git LFS](https://git-lfs.com/) installed — meshes and textures are tracked via LFS).
   ```bash
   git lfs install
   git clone <repo-url>
   ```
3. Open `CreativeJam26_Team12.uproject`. Let the engine generate intermediate/derived-data files on first launch.
4. Press **Play** to launch straight into the default map.

## Project Info

- **Default / startup map:** `Content/Final/FinalCinematique_ForReal`
- **Enabled plugins:** Modeling Tools Editor Mode (editor-only)
- **Rendering:** Lumen (GI + Reflections), Nanite with fallback meshes, hardware ray tracing enabled
- **Audio:** 48kHz sample rate

## Repo Structure Notes

- `Content/Meshes/**` and `Content/Textures/**` are tracked with Git LFS — don't commit large binaries outside these paths without updating `.gitattributes`.
- Standard Unreal ignores are set up in `.gitignore` (Binaries, Intermediate, Saved, DerivedDataCache, etc.) — these regenerate locally and shouldn't be committed.

## Team

- [Marcel Taveau](https://marceltaveau.itch.io/) — Lead Programmer
- [Emma Khoury](https://emma-khoury.itch.io/) — Artist
- [Joseph Lodico](https://josephlodico.itch.io/) — UI Programmer
- [Anthony Vitalei D'Ermes](https://antique7.itch.io/) — Sound Designer / UI Programmer
- [Maxime Laurence](https://maximelaurence.itch.io/) — Artist / Game Designer
- [Jérémy Lachance](https://jeremy-lachance.itch.io/) — Programmer / Artist
- Ayla Keith — Artist / Game Designer

## Credits & Third-Party Assets

No generative AI was used in the making of this game.

<!-- TODO: List any marketplace assets, sound packs, fonts, etc. used, per jam rules -->

## Known Issues

<!-- TODO: Anything jam-judges/players should know about before they play -->
