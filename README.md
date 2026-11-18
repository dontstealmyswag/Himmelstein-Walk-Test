Himmelstein Walk Test
=====================

This update preserves the existing ForceSniping-removal operations and adds a transform override for `HeroSpawn_Location_Hitman` (entity ID `021b12273dc284dd`).

The new spawn transform is local to the existing `Sniper Nest` parent and is derived from the supplied in-game world position `(-8.1660385, 13.706024, -13.424198)` and heading `-93.00571` degrees. It does not change the parent reference or default-spawn flag.

Deploy with Simple Mod Framework, then fully restart the mission to test the spawn change. Keep the original ZIP as a rollback copy.
