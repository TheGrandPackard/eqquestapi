---
date: 2020-08-24T16:50:16+02:00
title: Npc
menuTitle: Npc
weight: 25
---

## Npc Methods (Perl)
- $npc->[AI_SetRoambox](ai_setroambox)(float distance, float max_x, float min_x, float max_y, float min_y, [uint32 max_delay = 2500], [uint32 min_delay = 2500])
- $npc->[AddAISpell](addaispell)(int priority, int spell_id, int type, int mana_cost, int recast_delay, int resist_adjust)
- $npc->[AddCash](addcash)(uint16 copper, uint16 silver, uint16 gold, uint16 platinum)
- $npc->[AddDefensiveProc](adddefensiveproc)(int spell_id, int chance)
- $npc->[AddItem](additem)(uint32 item_id, [uint16 charges = 0], [bool equip_item = true], [uint32 aug1 = 0], [uint32 aug2 = 0], [uint32 aug3 = 0], [uint32 aug4 = 0], [uint32 aug5 = 0], [uint32 aug6 = 0])
- $npc->[AddLootTable](addloottable)([uint32 loottable_id])
- $npc->[AddMeleeProc](addmeleeproc)(int spell_id, int chance)
- $npc->[AddRangedProc](addrangedproc)(int spell_id, int chance)
- $npc->[AssignWaypoints](assignwaypoints)(uint32 grid_id)
- $npc->[CalculateNewWaypoint](calculatenewwaypoint)()
- $npc->[ChangeLastName](changelastname)(string name)
- $npc->[CheckNPCFactionAlly](checknpcfactionally)(int32 faction_id)
- $npc->[ClearItemList](clearitemlist)()
- $npc->[ClearLastName](clearlastname)()
- $npc->[CountLoot](countloot)()
- $npc->[DisplayWaypointInfo](displaywaypointinfo)(client* target)
- $npc->[DoClassAttacks](doclassattacks)(mob* target)
- $npc->[GetAccuracyRating](getaccuracyrating)()
- $npc->[GetAttackDelay](getattackdelay)()
- $npc->[GetAttackSpeed](getattackspeed)()
- $npc->[GetAvoidanceyRating](getavoidanceyrating)()
- $npc->[GetCombatState](getcombatstate)()
- $npc->[GetCopper](getcopper)()
- $npc->[GetGold](getgold)()
- $npc->[GetGrid](getgrid)()
- $npc->[GetGuardPointX](getguardpointx)()
- $npc->[GetGuardPointY](getguardpointy)()
- $npc->[GetGuardPointZ](getguardpointz)()
- $npc->[GetLoottableID](getloottableid)()
- $npc->[GetMaxDMG](getmaxdmg)()
- $npc->[GetMaxDamage](getmaxdamage)(uint8 target_level)
- $npc->[GetMaxWp](getmaxwp)()
- $npc->[GetMinDMG](getmindmg)()
- $npc->[GetNPCFactionID](getnpcfactionid)()
- $npc->[GetNPCHate](getnpchate)(mob* entity)
- $npc->[GetNPCSpellsID](getnpcspellsid)()
- $npc->[GetPetSpellID](getpetspellid)()
- $npc->[GetPlatinum](getplatinum)()
- $npc->[GetPrimSkill](getprimskill)()
- $npc->[GetPrimaryFaction](getprimaryfaction)()
- $npc->[GetScore](getscore)()
- $npc->[GetSecSkill](getsecskill)()
- $npc->[GetSilver](getsilver)()
- $npc->[GetSlowMitigation](getslowmitigation)()
- $npc->[GetSp2](getsp2)()
- $npc->[GetSpawnKillCount](getspawnkillcount)()
- $npc->[GetSpawnPointH](getspawnpointh)()
- $npc->[GetSpawnPointID](getspawnpointid)()
- $npc->[GetSpawnPointX](getspawnpointx)()
- $npc->[GetSpawnPointY](getspawnpointy)()
- $npc->[GetSpawnPointZ](getspawnpointz)()
- $npc->[GetSpellFocusDMG](getspellfocusdmg)()
- $npc->[GetSpellFocusHeal](getspellfocusheal)()
- $npc->[GetSwarmOwner](getswarmowner)()
- $npc->[GetSwarmTarget](getswarmtarget)()
- $npc->[GetWaypointMax](getwaypointmax)()
- $npc->[IsAnimal](isanimal)()
- $npc->[IsGuarding](isguarding)()
- $npc->[IsOnHatelist](isonhatelist)(mob* target)
- $npc->[MerchantCloseShop](merchantcloseshop)()
- $npc->[MerchantOpenShop](merchantopenshop)()
- $npc->[ModifyNPCStat](modifynpcstat)(string key, string value)
- $npc->[MoveTo](moveto)(float X, float Y, float Z, [float heading], [bool save_guard_location = false])
- $npc->[NextGuardPosition](nextguardposition)()
- $npc->[PauseWandering](pausewandering)(int pause_time)
- $npc->[PickPocket](pickpocket)(client* thief)
- $npc->[RecalculateSkills](recalculateskills)()
- $npc->[RemoveAISpell](removeaispell)(int spell_id)
- $npc->[RemoveCash](removecash)()
- $npc->[RemoveDefensiveProc](removedefensiveproc)(int spell_id)
- $npc->[RemoveFromHateList](removefromhatelist)(mob* target)
- $npc->[RemoveItem](removeitem)(uint32 item_id, [uint16 quantity = 0], [uint16 slot_id = 0])
- $npc->[RemoveMeleeProc](removemeleeproc)(int spell_id)
- $npc->[RemoveRangedProc](removerangedproc)(int spell_id)
- $npc->[ResumeWandering](resumewandering)()
- $npc->[SaveGuardSpot](saveguardspot)(X, Y, Z, heading)
- $npc->[SetCopper](setcopper)(uint32 copper_amount)
- $npc->[SetGold](setgold)(uint32 gold_amount)
- $npc->[SetGrid](setgrid)(int32 grid_id)
- $npc->[SetNPCFactionID](setnpcfactionid)(int32 faction_id)
- $npc->[SetPetSpellID](setpetspellid)(uint16 amount)
- $npc->[SetPlatinum](setplatinum)(uint32 platinum_amount)
- $npc->[SetPrimSkill](setprimskill)(int skill_id)
- $npc->[SetSaveWaypoint](setsavewaypoint)(uint16 waypoint)
- $npc->[SetSecSkill](setsecskill)(int skill_id)
- $npc->[SetSilver](setsilver)(uint32 silver_amount)
- $npc->[SetSimpleRoamBox](setsimpleroambox)(box_size, move_distance, move_delay)
- $npc->[SetSp2](setsp2)(uint32 set_spawn_group_id)
- $npc->[SetSpellFocusDMG](setspellfocusdmg)(int new_spell_focus_dmg)
- $npc->[SetSpellFocusHeal](setspellfocusheal)(int32 new_spell_focus_heal)
- $npc->[SetSwarmTarget](setswarmtarget)(int target_id)
- $npc->[SetTaunting](settaunting)(bool toggle)
- $npc->[SetWaypointPause](setwaypointpause)()
- $npc->[SignalNPC](signalnpc)(int signal_id)
- $npc->[StartSwarmTimer](startswarmtimer)(uint32 duration)
- $npc->[StopWandering](stopwandering)()
- $npc->[UpdateWaypoint](updatewaypoint)(int wp_index)