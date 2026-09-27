# BGMI Copy — Unity Android Starter

Original battle-royale style Unity project. It is not a BGMI asset/code clone.

## What is included
- Procedural 3D island/map builder
- Buildings, roads, trees, rocks and loot
- Third-person player controller
- Mobile joystick + look + fire/reload buttons
- Rifle, SMG and shotgun weapon data
- Ammo, reload, recoil, health and armor
- Simple enemy bots (no NavMesh package required)
- Loot pickups
- Vehicle enter/drive/exit prototype
- Air drop/parachute spawn prototype
- Shrinking safe zone + outside-zone damage
- 10-bot match flow
- HUD and main menu hooks

## Open
Use Unity 2022.3 LTS or newer.

1. Open this folder as a Unity project.
2. Open `Assets/Editor/BattleZoneBuilder.cs`.
3. In Unity, use menu: Tools > BattleZone > Build Demo Scene.
4. Save the generated scene as `Assets/Scenes/BattleZone.unity`.
5. Press Play.
6. For Android: File > Build Settings > Android > Switch Platform, then Build.

The builder intentionally uses Unity primitives and generated materials so the project does not depend on paid/external assets.

## Important
This is a complete gameplay prototype/starter, not a finished commercial online multiplayer game. Online matchmaking, anti-cheat, backend accounts, voice chat and production-quality art still need to be added before a Play Store release.


Project display name: BGMI Copy
