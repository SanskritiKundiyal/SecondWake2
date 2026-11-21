# Downloaded assets

- Gem01_Art.glb and Coins_Art.glb, Tomb Chaser 1, Polygonal Mind.
- Pattern_Cube.glb, Crystal Crossroads, Polygonal Mind.

CC0 source collection and release by ToxSam / Polygonal Mind.
https://github.com/ToxSam/cc0-models-Polygonal-Mind
https://github.com/PolygonalMind/initiative-opensource-release

The Quaternius dungeon, player, sentinel, and sorcerer models are from the user's supplied online asset packs. Their original CC0 notices are included in assets/cast and assets/dungeon.

Scanned stone texture and OpenGL normal map
Stone Wall 02, Charlotte Baglioni and Dario Barresi, Poly Haven, CC0.
https://polyhaven.com/a/stone_wall_02

The opening slideshow contains rendered images of the imported scenes. Speech was synthesized locally with eSpeak NG. The audio is intentionally synthetic.

## Audio polish — Kenney, CC0
- Impact Sounds: https://kenney.nl/assets/impact-sounds
- RPG Audio: https://kenney.nl/assets/rpg-audio
- Interface Sounds: https://kenney.nl/assets/interface-sounds
- Distributed subset under assets/audio/foley: concrete footsteps 000–003, generic light impact 001, metal medium impact 001, metal light impact 000, cloth2, knifeSlice, click_001.
- Bytes obtained 21 November 2026 from public mirror https://github.com/Mcamento8/open-game-sfx-index/tree/main/audio; original creator and CC0 license retained here. No generative model used.

## Surface upgrade — Poly Haven, CC0
- Stone Floor by Dimitrios Savva: https://polyhaven.com/a/stone_floor — 1K diffuse, OpenGL normal, roughness. Used on sourced floor meshes.
- Rough Linen by Rico: https://polyhaven.com/a/rough_linen — 1K diffuse. Used on sourced banner meshes.
- Retrieved 21 November 2026 from dl.polyhaven.org. No AI-generated textures.

## Music and ambience — human-authored, CC0
- Whispers in the Fog by Ruhinre (made in Sunvox): https://opengameart.org/content/whispers-in-the-fog — whispers_in_the_fog.ogg, renamed music.ogg. Seamless exploration loop; streamed quietly and raised during combat.
- Dark Cavern Ambient by Paul Wortmann: https://opengameart.org/content/dark-cavern-ambient — dark_cavern_ambient_002.ogg, renamed dungeon.ogg. Continuous ambient loop.
- Retrieved from OpenGameArt's original files 21 November 2026. Runtime gain changes and looping only; no generated replacement tracks.

## Dungeon wall upgrade — Paul Wortmann, CC0
- “3D dungeon modular wall set -1”: https://opengameart.org/content/3d-dungeon-modular-wall-set-1
- Original archive: https://opengameart.org/sites/default/files/dungeon_1_1.zip
- The campaign uses the supplied OBJ masonry wall and included medieval-brick diffuse/normal maps under assets/realism/walls. Source gallery/testing project retained under review/wall-test. Wall collision dimensions are unchanged.
- Source page describes its modified medieval-brick textures as CC0. Specular map is retained as source reference; not incorrectly used as roughness.

## User-supplied character and weapon upgrade
- rogue_all.fbx → assets/supplied/Adventurer.glb: original rig, mesh topology, UVs and weights; imported neutral bind offsets repaired before retargeting existing Quaternius motions. Used as Ivo and, with dark materials, the sorcerer in the rendered opening.
- rogue_free.ma: retained as an inspected Maya ASCII reference, not executed or imported into Godot. The equivalent supplied FBX is the interchange source.
- fbx.zip / paintpoly_humanoid_paladin_knight_female.fbx → Paladin.glb: original armored character, controller bones removed after neutral binding, existing Quaternius sentinel motions adapted. Used as the sentinel.
- sword_08_obj.zip → Sword08.glb: supplied OBJ and original diffuse/metallic/normal TGA maps, resized to1K for runtime. Mounted to animated hand bones with skeleton-unit compensation.
- These uploaded sources did not include animation clips. Motion is adapted from the pre-existing credited Quaternius cast; it is not motion capture.
- The character FBXs contain no embedded texture images. The rogue has fallback leather/cloth/metal materials; its face remains without the intended texture detail. The paladin's referenced texture files were not supplied. Poly Haven linen is used on rogue cloth.
- Uploads free-character-ancient-king.zip and textures_and_weapons.zip were unavailable, and were not read or used. Please provide working copies to finish the intended character materials.
- Author/license details for the user-supplied FBX/OBJ archives were not included. Retain the original download notices and confirm redistribution terms for public submission; no CC0 attribution is invented for these files.

## Courier replacement — EmoPreben, CC0
- “Bald Man - Rigged”, OpenGameArt: https://opengameart.org/content/bald-man-rigged
- Author describes Shapelab sculpting, Substance Painter texturing and a Mixamo rig. Source diffuse/normal maps retained in Courier.glb; existing Quaternius Idle/Walk motion retargeted. Used for Orin in the non-magical reality.

## Opening stills
- Four images rendered directly in Godot from the upgraded game assets, not generated imagery. Staff prop extracted from the credited Quaternius Wizard. The black-clothed sorcerer, death, gemstone revival, wristband trial and Rebound Castle premise are unchanged.
- Voice remains the explicitly synthetic eSpeak placeholder until human WAV files are supplied. See HUMAN_NARRATION_BRIEF.md for the external voice-folder override.

Weapon grip polish uses the supplied character finger bones and the supplied sword mesh. The runtime SkeletonModifier3D closes existing joints; it adds no replacement character geometry, textures or generated animation assets.

The cinematic/rendering polish uses in-engine camera paths, typography, lighting and a small procedural reflection sky. No new external model, image, voice or generated video was added.


## Character surface update — 22 November 2026
Brown Leather by Rob Tuytel, Poly Haven, CC0: https://polyhaven.com/a/brown_leather . Approved 2K diffuse, OpenGL normal and roughness maps are in assets/character_surfaces. Rough Linen: https://polyhaven.com/a/rough_linen , same map types at 2K. Maps downloaded from official dl.polyhaven.org URLs and checked against API MD5 metadata. Clothing now uses these maps; missing original face/armor maps are still fallback surfaces.
