FCNPC Boss
==========

1.0.3
-----

- Internal: Better strcpy function (by ZiGGi)
- Internal: Better GetTickCount overflow fix (by ZiGGi)
- Fixed useFightStyle default value to be conform with FCNPC (true to false)
- Added WOW_GetBossAllowNPCTargets and WOW_SetBossAllowNPCTargets which defaults to false
- Renamed WOW_GetBossNPCID and WOW_GetBossIDFromPlayerID to be conform with samp naming conventions
- Added WOW_GetBossPlayerID which is an alias for WOW_GetBossNPCID
- Added WOW_IsEncounterStarted and WOW_StopEncounter

1.0.2
-----

- Changed default move speed to MOVE_SPEED_AUTO to be conform with FCNPC 1.1.1
- Added individual useMapAndreas setting
- WOW_USE_MAP_ANDREAS is now a global value that determines if MapAndreas is used by any boss
- Refer to the wiki pages for more info
- Updated example scripts to handle the changes
- Updated credits
- Removed colandreas upcoming feature, since it will be implemented in FCNPC 2.0

1.0.1
-----

- Added check to see if MapAndreas was already initialized and don't initialize again when it is
- Added default values for the WOW_SetBoss...Info methods
- Added extra checks to prevent unnecessary FCNPC_GoToPlayer/FCNPC_AimAtPlayer/FCNP_MeleeAttack calls
- Added some extra checks FCNPC_IsSpawned checks
- Changed default speed to be eqaul to -1.0 (see FCNPC 1.1.0)
- Changed default ranged attack delay to be eqaul to -1 (see FCNPC 1.1.0)
- Fixed WOW_SpellToString spell name default color

1.0.0
-----

- Initial stable release