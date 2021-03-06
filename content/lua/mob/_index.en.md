---
title: Mob
menuTitle: Mob
weight: 25
---

## Mob Methods (Lua)
- Mob:[GetName](getname)(); -- string
- Mob:[Depop](depop)(bool start_spawn_timer); -- void
- Mob:[BehindMob](behindmob)(Lua_Mob other, float x, float y); -- bool
- Mob:[SetLevel](setlevel)(number level, bool command); -- void
- Mob:[IsMoving](ismoving)(); -- bool
- Mob:[GotoBind](gotobind)(); -- void
- Mob:[Attack](attack)(Lua_Mob other, number hand, bool from_riposte, bool is_strikethrough, bool is_from_spell, luabind::adl::object opts); -- bool
- Mob:[Damage](damage)(Lua_Mob from, number damage, number spell_id, number attack_skill, bool avoidable, number buffslot, bool buff_tic); -- void
- Mob:[RangedAttack](rangedattack)(Lua_Mob other); -- void
- Mob:[ThrowingAttack](throwingattack)(Lua_Mob other); -- void
- Mob:[Heal](heal)(); -- void
- Mob:[HealDamage](healdamage)(number amount, Lua_Mob other); -- void
- Mob:[GetLevelCon](getlevelcon)(number my, number other); -- number
- Mob:[SetHP](sethp)(number hp); -- void
- Mob:[DoAnim](doanim)(number anim_num, number type, bool ackreq, number filter); -- void
- Mob:[ChangeSize](changesize)(double in_size, bool no_restriction); -- void
- Mob:[RandomizeFeatures](randomizefeatures)(bool send_illusion, bool save_variables); -- void
- Mob:[GMMove](gmmove)(double x, double y, double z, double heading, bool send_update); -- void
- Mob:[TryMoveAlong](trymovealong)(float distance, float angle, bool send); -- void
- Mob:[HasProcs](hasprocs)(); -- bool
- Mob:[IsInvisible](isinvisible)(Lua_Mob other); -- bool
- Mob:[SetInvisible](setinvisible)(number state); -- void
- Mob:[FindBuff](findbuff)(number spell_id); -- bool
- Mob:[FindBuffBySlot](findbuffbyslot)(number slot); -- number
- Mob:[BuffCount](buffcount)(); -- number
- Mob:[FindType](findtype)(number type, bool offensive, number threshold); -- bool
- Mob:[GetBuffSlotFromType](getbuffslotfromtype)(number slot); -- number
- Mob:[GetBaseRace](getbaserace)(); -- number
- Mob:[GetBaseGender](getbasegender)(); -- number
- Mob:[GetDeity](getdeity)(); -- number
- Mob:[GetRace](getrace)(); -- number
- Mob:[GetGender](getgender)(); -- number
- Mob:[GetTexture](gettexture)(); -- number
- Mob:[GetHelmTexture](gethelmtexture)(); -- number
- Mob:[GetHairColor](gethaircolor)(); -- number
- Mob:[GetBeardColor](getbeardcolor)(); -- number
- Mob:[GetHairStyle](gethairstyle)(); -- number
- Mob:[GetLuclinFace](getluclinface)(); -- number
- Mob:[GetDrakkinHeritage](getdrakkinheritage)(); -- number
- Mob:[GetDrakkinTattoo](getdrakkintattoo)(); -- number
- Mob:[GetDrakkinDetails](getdrakkindetails)(); -- number
- Mob:[GetClass](getclass)(); -- number
- Mob:[GetCleanName](getcleanname)(); -- string
- Mob:[GetTarget](gettarget)(); -- unknown - Lua_Mob
- Mob:[SetTarget](settarget)(Lua_Mob t); -- void
- Mob:[GetHPRatio](gethpratio)(); -- number
- Mob:[IsWarriorClass](iswarriorclass)(); -- bool
- Mob:[GetMaxHP](getmaxhp)(); -- number
- Mob:[GetItemStat](getitemstat)(number itemid, const char* identifier); -- number
- Mob:[GetItemHPBonuses](getitemhpbonuses)(); -- number
- Mob:[GetSpellHPBonuses](getspellhpbonuses)(); -- number
- Mob:[GetWalkspeed](getwalkspeed)(); -- number
- Mob:[GetRunspeed](getrunspeed)(); -- number
- Mob:[GetCasterLevel](getcasterlevel)(number spell_id); -- number
- Mob:[GetMaxMana](getmaxmana)(); -- number
- Mob:[GetMana](getmana)(); -- number
- Mob:[SetMana](setmana)(number mana); -- number
- Mob:[GetManaRatio](getmanaratio)(); -- number
- Mob:[GetAC](getac)(); -- number
- Mob:[GetDisplayAC](getdisplayac)(); -- number
- Mob:[GetATK](getatk)(); -- number
- Mob:[GetSTR](getstr)(); -- number
- Mob:[GetSTA](getsta)(); -- number
- Mob:[GetDEX](getdex)(); -- number
- Mob:[GetAGI](getagi)(); -- number
- Mob:[GetINT](getint)(); -- number
- Mob:[GetWIS](getwis)(); -- number
- Mob:[GetCHA](getcha)(); -- number
- Mob:[GetMR](getmr)(); -- number
- Mob:[GetFR](getfr)(); -- number
- Mob:[GetPR](getpr)(); -- number
- Mob:[GetCR](getcr)(); -- number
- Mob:[GetCorruption](getcorruption)(); -- number
- Mob:[GetPhR](getphr)(); -- number
- Mob:[GetMaxSTR](getmaxstr)(); -- number
- Mob:[GetMaxSTA](getmaxsta)(); -- number
- Mob:[GetMaxDEX](getmaxdex)(); -- number
- Mob:[GetMaxAGI](getmaxagi)(); -- number
- Mob:[GetMaxINT](getmaxint)(); -- number
- Mob:[GetMaxWIS](getmaxwis)(); -- number
- Mob:[GetMaxCHA](getmaxcha)(); -- number
- Mob:[ResistSpell](resistspell)(number resist_type, number spell_id, Lua_Mob caster, bool use_resist_override, number resist_override); -- number
- Mob:[GetSpecializeSkillValue](getspecializeskillvalue)(number spell_id); -- number
- Mob:[GetNPCTypeID](getnpctypeid)(); -- number
- Mob:[IsTargeted](istargeted)(); -- bool
- Mob:[GetX](getx)(); -- number
- Mob:[GetY](gety)(); -- number
- Mob:[GetZ](getz)(); -- number
- Mob:[GetHeading](getheading)(); -- number
- Mob:[GetWaypointX](getwaypointx)(); -- number
- Mob:[GetWaypointY](getwaypointy)(); -- number
- Mob:[GetWaypointZ](getwaypointz)(); -- number
- Mob:[GetWaypointH](getwaypointh)(); -- number
- Mob:[GetWaypointPause](getwaypointpause)(); -- number
- Mob:[GetWaypointID](getwaypointid)(); -- number
- Mob:[SetCurrentWP](setcurrentwp)(number wp); -- void
- Mob:[GetSize](getsize)(); -- number
- Mob:[Message](message)(number type, const char *message); -- void
- Mob:[MessageString](messagestring)(number type, number string_id, number distance); -- void
- Mob:[Say](say)(const char* message, number language); -- void
- Mob:[QuestSay](questsay)(Lua_Client client, const char *message, luabind::adl::object opts); -- void
- Mob:[Shout](shout)(const char* message, number language); -- void
- Mob:[Emote](emote)(const char *message); -- void
- Mob:[InterruptSpell](interruptspell)(number spell_id); -- void
- Mob:[CastSpell](castspell)(number spell_id, number target_id, number slot, number cast_time, number mana_cost, number item_slot); -- bool
- Mob:[SpellFinished](spellfinished)(number spell_id, Lua_Mob target, number slot, number mana_used, number inventory_slot, number resist_adjust, bool proc); -- bool
- Mob:[SendBeginCast](sendbegincast)(number spell_id, number cast_time); -- void
- Mob:[SpellEffect](spelleffect)(Lua_Mob caster, number spell_id, double partial); -- void
- Mob:[GetPet](getpet)(); -- unknown - Lua_Mob
- Mob:[GetOwner](getowner)(); -- unknown - Lua_Mob
- Mob:[GetHateList](gethatelist)(); -- unknown - Lua_HateList
- Mob:[GetHateTop](gethatetop)(); -- unknown - Lua_Mob
- Mob:[GetHateDamageTop](gethatedamagetop)(Lua_Mob other); -- unknown - Lua_Mob
- Mob:[GetHateRandom](gethaterandom)(); -- unknown - Lua_Mob
- Mob:[AddToHateList](addtohatelist)(Lua_Mob other, number hate, number damage, bool yell_for_help, bool frenzy, bool buff_tic); -- void
- Mob:[SetHate](sethate)(Lua_Mob other, number hate, number damage); -- void
- Mob:[HalveAggro](halveaggro)(Lua_Mob other); -- void
- Mob:[DoubleAggro](doubleaggro)(Lua_Mob other); -- void
- Mob:[GetHateAmount](gethateamount)(Lua_Mob target, bool is_damage); -- number
- Mob:[GetDamageAmount](getdamageamount)(Lua_Mob target); -- number
- Mob:[WipeHateList](wipehatelist)(); -- void
- Mob:[CheckAggro](checkaggro)(Lua_Mob other); -- bool
- Mob:[Stun](stun)(number duration); -- void
- Mob:[UnStun](unstun)(); -- void
- Mob:[IsStunned](isstunned)(); -- bool
- Mob:[Spin](spin)(); -- void
- Mob:[CanThisClassDoubleAttack](canthisclassdoubleattack)(); -- bool
- Mob:[CanThisClassDualWield](canthisclassdualwield)(); -- bool
- Mob:[CanThisClassRiposte](canthisclassriposte)(); -- bool
- Mob:[CanThisClassDodge](canthisclassdodge)(); -- bool
- Mob:[CanThisClassParry](canthisclassparry)(); -- bool
- Mob:[CanThisClassBlock](canthisclassblock)(); -- bool
- Mob:[SetInvul](setinvul)(bool value); -- void
- Mob:[GetInvul](getinvul)(); -- bool
- Mob:[SetExtraHaste](setextrahaste)(number haste); -- void
- Mob:[GetHaste](gethaste)(); -- number
- Mob:[GetHandToHandDamage](gethandtohanddamage)(); -- number
- Mob:[GetHandToHandDelay](gethandtohanddelay)(); -- number
- Mob:[Mesmerize](mesmerize)(); -- void
- Mob:[IsMezzed](ismezzed)(); -- bool
- Mob:[IsEnraged](isenraged)(); -- bool
- Mob:[GetReverseFactionCon](getreversefactioncon)(Lua_Mob other); -- number
- Mob:[IsAIControlled](isaicontrolled)(); -- bool
- Mob:[GetAggroRange](getaggrorange)(); -- number
- Mob:[GetAssistRange](getassistrange)(); -- number
- Mob:[SetPetOrder](setpetorder)(number order); -- void
- Mob:[GetPetOrder](getpetorder)(); -- number
- Mob:[IsRoamer](isroamer)(); -- bool
- Mob:[IsRooted](isrooted)(); -- bool
- Mob:[IsEngaged](isengaged)(); -- bool
- Mob:[FaceTarget](facetarget)(Lua_Mob target); -- void
- Mob:[SetHeading](setheading)(double in); -- void
- Mob:[CalculateHeadingToTarget](calculateheadingtotarget)(double in_x, double in_y); -- number
- Mob:[RunTo](runto)(double x, double y, double z); -- void
- Mob:[WalkTo](walkto)(double x, double y, double z); -- void
- Mob:[NavigateTo](navigateto)(double x, double y, double z); -- void
- Mob:[StopNavigation](stopnavigation)(); -- void
- Mob:[CalculateDistance](calculatedistance)(double x, double y, double z); -- number
- Mob:[SendTo](sendto)(double x, double y, double z); -- void
- Mob:[SendToFixZ](sendtofixz)(double x, double y, double z); -- void
- Mob:[NPCSpecialAttacks](npcspecialattacks)(const char *parse, number perm, bool reset, bool remove); -- void
- Mob:[GetResist](getresist)(number type); -- number
- Mob:[Charmed](charmed)(); -- bool
- Mob:[CheckAggroAmount](checkaggroamount)(number spell_id, bool is_proc); -- number
- Mob:[CheckHealAggroAmount](checkhealaggroamount)(number spell_id, number heal_possible); -- number
- Mob:[GetAA](getaa)(number id); -- number
- Mob:[GetAAByAAID](getaabyaaid)(number id); -- number
- Mob:[SetAA](setaa)(number rank_id, number new_value, number charges); -- bool
- Mob:[DivineAura](divineaura)(); -- bool
- Mob:[SetOOCRegen](setoocregen)(number regen); -- void
- Mob:[GetEntityVariable](getentityvariable); -- 
- Mob:[SetEntityVariable](setentityvariable)(const char *name, const char *value); -- void
- Mob:[EntityVariableExists](entityvariableexists)(const char *name); -- bool
- Mob:[Signal](signal)(number id); -- void
- Mob:[CombatRange](combatrange)(Lua_Mob other); -- bool
- Mob:[DoSpecialAttackDamage](dospecialattackdamage)(Lua_Mob other, number skill, number max_damage, number min_damage, number hate_override, number reuse_time); -- void
- Mob:[DoThrowingAttackDmg](dothrowingattackdmg)(Lua_Mob other, Lua_ItemInst range_weapon, Lua_Item item, number weapon_damage, number chance_mod); -- void
- Mob:[DoMeleeSkillAttackDmg](domeleeskillattackdmg)(Lua_Mob other, number weapon_damage, number skill, number chance_mod, number focus, bool can_riposte); -- void
- Mob:[DoArcheryAttackDmg](doarcheryattackdmg)(Lua_Mob other, Lua_ItemInst range_weapon, Lua_ItemInst ammo, number weapon_damage, number chance_mod); -- void
- Mob:[CheckLoS](checklos)(Lua_Mob other); -- bool
- Mob:[CheckLoSToLoc](checklostoloc)(double x, double y, double z, double mob_size); -- bool
- Mob:[FindGroundZ](findgroundz)(double x, double y, double z); -- number
- Mob:[ProjectileAnimation](projectileanimation)(Lua_Mob to, number item_id, bool is_arrow, double speed, double angle, double tilt, double arc); -- void
- Mob:[HasNPCSpecialAtk](hasnpcspecialatk)(const char *parse); -- bool
- Mob:[SendAppearanceEffect](sendappearanceeffect)(number parm1, number parm2, number parm3, number parm4, number parm5, Lua_Client specific_target); -- void
- Mob:[SetFlyMode](setflymode)(number in); -- void
- Mob:[SetTexture](settexture)(number in); -- void
- Mob:[SetRace](setrace)(number in); -- void
- Mob:[SetGender](setgender)(number in); -- void
- Mob:[SendIllusionPacket](sendillusionpacket)(luabind::adl::object illusion); -- void
- Mob:[ChangeRace](changerace)(number in); -- void
- Mob:[ChangeGender](changegender)(number in); -- void
- Mob:[ChangeTexture](changetexture)(number in); -- void
- Mob:[ChangeHelmTexture](changehelmtexture)(number in); -- void
- Mob:[ChangeHairColor](changehaircolor)(number in); -- void
- Mob:[ChangeBeardColor](changebeardcolor)(number in); -- void
- Mob:[ChangeHairStyle](changehairstyle)(number in); -- void
- Mob:[ChangeLuclinFace](changeluclinface)(number in); -- void
- Mob:[ChangeDrakkinHeritage](changedrakkinheritage)(number in); -- void
- Mob:[ChangeDrakkinTattoo](changedrakkintattoo)(number in); -- void
- Mob:[ChangeDrakkinDetails](changedrakkindetails)(number in); -- void
- Mob:[CameraEffect](cameraeffect)(number duration, number intensity, Lua_Client c, bool global); -- void
- Mob:[SendSpellEffect](sendspelleffect)(number effect_id, number duration, number finish_delay, bool zone_wide, number unk020, bool perm_effect); -- void
- Mob:[TempName](tempname)(const char *newname); -- void
- Mob:[GetGlobal](getglobal)(const char *varname); -- string
- Mob:[SetGlobal](setglobal)(const char *varname, const char *newvalue, number options, const char *duration, Lua_Mob other); -- void
- Mob:[TarGlobal](targlobal)(const char *varname, const char *value, const char *duration, number npc_id, number char_id, number zone_id); -- void
- Mob:[DelGlobal](delglobal)(const char *varname); -- void
- Mob:[SetSlotTint](setslottint)(number material_slot, number red_tint, number green_tint, number blue_tint); -- void
- Mob:[WearChange](wearchange)(number material_slot, number texture, number color); -- void
- Mob:[DoKnockback](doknockback)(Lua_Mob caster, number pushback, number pushup); -- void
- Mob:[AddNimbusEffect](addnimbuseffect)(number effect_id); -- void
- Mob:[RemoveNimbusEffect](removenimbuseffect)(number effect_id); -- void
- Mob:[IsFeared](isfeared)(); -- bool
- Mob:[IsBlind](isblind)(); -- bool
- Mob:[IsRunning](isrunning)(); -- bool
- Mob:[SetRunning](setrunning)(bool running); -- void
- Mob:[SetBodyType](setbodytype)(number new_body, bool overwrite_orig); -- void
- Mob:[SetTargetable](settargetable)(bool on); -- void
- Mob:[ModSkillDmgTaken](modskilldmgtaken)(number skill, number value); -- void
- Mob:[GetModSkillDmgTaken](getmodskilldmgtaken)(number skill); -- number
- Mob:[GetSkillDmgTaken](getskilldmgtaken)(number skill); -- number
- Mob:[GetFcDamageAmtIncoming](getfcdamageamtincoming)(Lua_Mob caster, number spell_id, bool use_skill, uint16 skill); -- number
- Mob:[GetSkillDmgAmt](getskilldmgamt)(uint16 skill); -- number
- Mob:[SetAllowBeneficial](setallowbeneficial)(bool value); -- void
- Mob:[GetAllowBeneficial](getallowbeneficial)(); -- bool
- Mob:[IsBeneficialAllowed](isbeneficialallowed)(Lua_Mob target); -- bool
- Mob:[ModVulnerability](modvulnerability)(number resist, number value); -- void
- Mob:[GetModVulnerability](getmodvulnerability)(number resist); -- number
- Mob:[SetDisableMelee](setdisablemelee)(bool disable); -- void
- Mob:[IsMeleeDisabled](ismeleedisabled)(); -- bool
- Mob:[SetFlurryChance](setflurrychance)(number value); -- void
- Mob:[GetFlurryChance](getflurrychance)(); -- number
- Mob:[GetSpecialAbility](getspecialability)(number ability); -- number
- Mob:[GetSpecialAbilityParam](getspecialabilityparam)(number ability, number param); -- number
- Mob:[SetSpecialAbility](setspecialability)(number ability, number level); -- void
- Mob:[SetSpecialAbilityParam](setspecialabilityparam)(number ability, number param, number value); -- void
- Mob:[ClearSpecialAbilities](clearspecialabilities)(); -- void
- Mob:[ProcessSpecialAbilities](processspecialabilities)(std::string str); -- void
- Mob:[GetAppearance](getappearance)(); -- number
- Mob:[SetAppearance](setappearance)(number app, bool ignore_self); -- void
- Mob:[SetDestructibleObject](setdestructibleobject)(bool set); -- void
- Mob:[IsImmuneToSpell](isimmunetospell)(number spell_id, Lua_Mob caster); -- bool
- Mob:[BuffFadeBySpellID](bufffadebyspellid)(number spell_id); -- void
- Mob:[BuffFadeByEffect](bufffadebyeffect)(number effect_id, number skipslot); -- void
- Mob:[BuffFadeAll](bufffadeall)(); -- void
- Mob:[BuffFadeBySlot](bufffadebyslot)(number slot, bool recalc_bonuses); -- void
- Mob:[CanBuffStack](canbuffstack)(number spell_id, number caster_level, bool fail_if_overwrite); -- number
- Mob:[SetPseudoRoot](setpseudoroot)(bool in); -- void
- Mob:[SeeInvisible](seeinvisible)(); -- number
- Mob:[SeeInvisibleUndead](seeinvisibleundead)(); -- bool
- Mob:[SeeHide](seehide)(); -- bool
- Mob:[SeeImprovedHide](seeimprovedhide)(); -- bool
- Mob:[IsTargetable](istargetable)(); -- bool
- Mob:[HasShieldEquiped](hasshieldequiped)(); -- bool
- Mob:[HasTwoHandBluntEquiped](hastwohandbluntequiped)(); -- bool
- Mob:[HasTwoHanderEquipped](hastwohanderequipped)(); -- bool
- Mob:[GetHerosForgeModel](getherosforgemodel)(uint8 material_slot); -- number
- Mob:[IsEliteMaterialItem](iselitematerialitem)(uint8 material_slot); -- number
- Mob:[GetBaseSize](getbasesize)(); -- number
- Mob:[HasOwner](hasowner)(); -- bool
- Mob:[IsPet](ispet)(); -- bool
- Mob:[HasPet](haspet)(); -- bool
- Mob:[IsSilenced](issilenced)(); -- bool
- Mob:[IsAmnesiad](isamnesiad)(); -- bool
- Mob:[GetMeleeMitigation](getmeleemitigation)(); -- number
- Mob:[GetWeaponDamageBonus](getweapondamagebonus)(Lua_Item weapon, bool offhand); -- number
- Mob:[GetItemBonuses](getitembonuses)(); -- unknown - Lua_StatBonuses
- Mob:[GetSpellBonuses](getspellbonuses)(); -- unknown - Lua_StatBonuses
- Mob:[GetAABonuses](getaabonuses)(); -- unknown - Lua_StatBonuses
- Mob:[IsAttackAllowed](isattackallowed)(Lua_Mob target, bool isSpellAttack); -- bool
- Mob:[IsCasting](iscasting)(); -- bool
- Mob:[AttackAnimation](attackanimation)(number Hand, Lua_ItemInst weapon); -- number
- Mob:[IsBerserk](isberserk)(); -- bool
- Mob:[TryFinishingBlow](tryfinishingblow)(Lua_Mob defender, number &damage); -- bool
- Mob:[GetBodyType](getbodytype)(); -- number
- Mob:[GetOrigBodyType](getorigbodytype)(); -- number
- Mob:[CheckNumHitsRemaining](checknumhitsremaining)(number type, int32 buff_slot, uint16 spell_id); -- void
