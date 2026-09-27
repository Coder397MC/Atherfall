# Atherfall
# Aetherfall — Echoes of the Sky

A playable, single-player 3D open-world fantasy RPG for the browser. Explore a floating island, free its ancient guardians, awaken three beacons in any order, and face the Hollow Warden.

The complete first chapter includes a continuous explorable island, third-person combat, a keeper NPC, sword and health upgrades, experience levels, 45 collectible shards, healing flasks, a world map with custom waypoints, and a conclusion that lets you keep exploring. Progress is saved automatically in the current browser.

## Play locally

You need **Node.js 20 or newer**. No package installation is needed.

```sh
npm start
```

Open **http://127.0.0.1:4173**. Without npm, use `node scripts/serve.mjs`. Opening `index.html` directly as a file will not work because browsers restrict JavaScript module loading from `file://`.

A modern browser with WebGL 2 and hardware acceleration is required. Desktop keyboard and mouse are recommended. Touch devices receive a movement joystick, camera dragging, and action buttons. Use Pause → Visual quality → Performance on slower devices.

## Controls

| Action | Control |
| --- | --- |
| Move | WASD or arrow keys |
| Orbit camera | Drag with mouse or finger |
| Zoom | Mouse wheel |
| Strike | J, click, or sword button |
| Dodge | Space or dodge button |
| Sprint | Hold Shift |
| Jump | F |
| Interact | E or touch interaction button |
| Healing flask | Q or flask button |
| World map | M or minimap |
| Journal | Tab or journal button |
| Pause | Escape or pause button |

Talk to **Elowen beside the campfire**. Defeat all three guardians at a sanctuary, approach its crystal, then press E. Each beacon restores health, refills flasks, and awards shards. Spend shards with Elowen to improve your sword or maximum health.

Enemies show a red circle before striking. Dodge out of it or time your dodge through the attack. After all three beacons awaken, defeat the Warden at the central gate and return to Elowen to finish the chapter.

Defeat returns you to camp without removing discoveries or upgrades. Pause → Return to camp is available if you get turned around. A new journey replaces the current save after confirmation. Saves are local to the browser and origin; moving from localhost to GitHub Pages starts a separate save.
