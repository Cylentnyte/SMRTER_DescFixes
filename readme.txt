Descriptions and Misc. Fix Addon for S.M.R.T.E.R. 0.41

- After multiple account and version issues, I've recompiled the variations into a working package. This is known to work with SMRTER 0.41 and the SMRTER 0.41 Weapons Addon Lite package as of 12/12/17. Ironically this actually fixes a bug that would cause the engine to crash if you used those 2 mods together, so consider this a compatibility fix as well.

Required Mods:

- SMRTER 0.41 (smrtphoneusr)
- SMRTER 0.41 Weapons Addon Lite (smrtphoneusr)

Changes:

- Added descriptions for all armors
- Added descriptions for scopes that didn't have any or were calling strings from inside weapons.ltx file
- Monolith and Duty suits now correctly start with 1 artifact container, not 4
- Edited descriptions for Sunblocker and Caff-pow, assigned inv_name and description variables a string
	to call from st_items_equipment.xml
- Edited inv_name and description variables for these weapons to call variables from st_items_weapons.xml:
	-- w_ak74usnag.ltx
	-- w_fanfal.ltx
	-- w_g36c.ltx
	-- w_g36e.ltx
	-- w_g36k.ltx
	-- w_knife.ltx
	-- w_xm177e2.ltx
- Increased SG-552 damage to properly reflect in-game description
- Edited inv_name and description variables for M16A1 scope and G36e scope and added descriptions
- Edited the following text files for grammar, wrong names, real-life counterparts, and flow:
	-- st_dialog_manager.xml
	-- st_dialogs.xml
	-- st_dialogs_jupiter.xml
	-- st_dialogs_pripyat.xml
	-- st_dialogs_zaton.xml
	-- st_items_artefacts.xml
	-- st_items_equipment.xml
	-- st_items_outfit.xml
	-- st_items_quest.xml
	-- st_items_weapons.xml
- I barely touched the NPC or actor dialogs, it would've taken me far too long in the timeframe I had
- Probably some things I'm forgetting but I think I got the bulk of it

Credits: smrtphoneusr and the others on the S.M.R.T.E.R. team for their mod so far.

Notes: @smrtphoneusr and/or S.M.R.T.E.R. team, you can use my edited files in your mod if you want to.
