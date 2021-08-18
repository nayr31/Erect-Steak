# Erect Steak

The name of this project is a joke that relates to the H3VR (a game about shooting hotdogs) character "Flaccid Steak".

The changes this character brings:

- Start with a decoy mag (stealth) or a knife (lethal).
- All static guns and grenades are now pools related to what they were before.
- Stinger has been changed to a general rocket launcher pool with reduced cost (3 instead of 4, like the controllable launcher).
- Reduced starting points (3 -> 2)

## More Information

The idea of this character is to only tweak the values, to add more playability.

Starting equipment changes:

- Spawn with a decoy mag or combat knife
  - `DecoyMag` is a custom item that is included within the mod, that can only spawn at the start of the round. It has enhanced thrown properties, making it ideal for distracting sosigs.
  - These starting items were to fix the sometimes annoying starting rounds, while also including some role-play elements
- Inclusion of [cityrobo's RangeFinder mod](https://h3vr.thunderstore.io/package/cityrobo/RangeFinder/) in the rangefinder pool.
  - This means that the vanilla rangefinder can instead spawn as the modded one. Preferably, I would want this modded rangefinder to always spawn, but I know some people would want the vanilla one, so Im leaving it up to chance to be fair.
- The stinger sucks in most environments, giving other launchers a fair chance.

Small QOL improvements:

- Extra panel spawn on first take phase
  - This will ensure options for either the mag upgrader/buyer, or the ammo panel
- Removed recycler from first take phase
- Changed the icon for the battle rifles section to the battle rifle icon and not the bolt-action rifle icon

## Changelog

### 1.0.5

- Changed assault rifle pool generation parameters (should stop only 3 guns from spawning).
- Changed ordinance (stinger) pool to exclude Meat Fortress weapons.
- Changed bolt action icon to be the battle rifle icon, since it makes more sense.
- Added 1 more panel to spawn in the first take phase (1 -> 2). 

### 1.0.4

Fixed decoy mag spawning with guns that didn't have magazines (magazine type was set to `M_None`, seems like those guns use them).

### 1.0.3

- Removed the recycler from the first take phase.
- Changed the always spawning box to either spawn a decoy magazine or a combat knife.
  - The reason behind this change was the overall utility and performance of the box.
  - This also gives some more role-play elements, either lethal or a more stealth approach (you can still knock sosigs out with a magazine, so non-lethal as well).
- Now depends on [OtherLoader](https://h3vr.thunderstore.io/package/devyndamonster/OtherLoader/)

### 1.0.2

- Box now spawns with starting equipment.
- Reduced starting points by 1 (3 -> 2).
- Added compatibility with [cityrobo's RangeFinder mod](https://h3vr.thunderstore.io/package/cityrobo/RangeFinder/).

### 1.0.1

Changed suppressor token cost (4 -> 2).

### 1.0.0

Initial Release.
