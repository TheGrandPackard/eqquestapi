---
date: 2020-08-24T16:50:16+02:00
title: Stat Bonuses
menuTitle: Stat Bonuses
weight: 25
---

## Stat Bonuses Methods (Lua)
- statbonuses:[GetAC](getac)() const; -- int32
- statbonuses:[GetAGI](getagi)() const; -- int32
- statbonuses:[GetAGICapMod](getagicapmod)() const; -- int32
- statbonuses:[GetAStacker](getastacker)(int idx) const; -- int32
- statbonuses:[GetATK](getatk)() const; -- int32
- statbonuses:[GetAbsorbMagicAtt](getabsorbmagicatt)(int idx) const; -- uint32
- statbonuses:[GetAccuracy](getaccuracy)(int idx) const; -- int32
- statbonuses:[GetAggroRange](getaggrorange)() const; -- float
- statbonuses:[GetAlterNPCLevel](getalternpclevel)() const; -- int32
- statbonuses:[GetAmbidexterity](getambidexterity)() const; -- int32
- statbonuses:[GetAmplification](getamplification)() const; -- uint32
- statbonuses:[GetAntiGate](getantigate)() const; -- bool
- statbonuses:[GetArcheryDamageModifier](getarcherydamagemodifier)() const; -- uint32
- statbonuses:[GetAssassinate](getassassinate)(int idx) const; -- uint32
- statbonuses:[GetAssassinateLevel](getassassinatelevel)(int idx) const; -- uint8
- statbonuses:[GetAssistRange](getassistrange)() const; -- float
- statbonuses:[GetAvoidMeleeChance](getavoidmeleechance)() const; -- int32
- statbonuses:[GetAvoidMeleeChanceEffect](getavoidmeleechanceeffect)() const; -- int32
- statbonuses:[GetBStacker](getbstacker)(int idx) const; -- int32
- statbonuses:[GetBaseMovementSpeed](getbasemovementspeed)() const; -- int8
- statbonuses:[GetBerserkSPA](getberserkspa)() const; -- bool
- statbonuses:[GetBindWound](getbindwound)() const; -- int32
- statbonuses:[GetBlockBehind](getblockbehind)() const; -- int32
- statbonuses:[GetBlockNextSpell](getblocknextspell)() const; -- bool
- statbonuses:[GetBuffSlotIncrease](getbuffslotincrease)() const; -- uint8
- statbonuses:[GetCHA](getcha)() const; -- int32
- statbonuses:[GetCHACapMod](getchacapmod)() const; -- int32
- statbonuses:[GetCR](getcr)() const; -- int32
- statbonuses:[GetCRCapMod](getcrcapmod)() const; -- int32
- statbonuses:[GetCStacker](getcstacker)(int idx) const; -- int32
- statbonuses:[GetChannelChanceItems](getchannelchanceitems)() const; -- int32
- statbonuses:[GetChannelChanceSpells](getchannelchancespells)() const; -- int32
- statbonuses:[GetCharmBreakChance](getcharmbreakchance)() const; -- int32
- statbonuses:[GetClairvoyance](getclairvoyance)() const; -- int32
- statbonuses:[GetCombatStability](getcombatstability)() const; -- int32
- statbonuses:[GetConsumeProjectile](getconsumeprojectile)() const; -- uint8
- statbonuses:[GetCorrup](getcorrup)() const; -- int32
- statbonuses:[GetCorrupCapMod](getcorrupcapmod)() const; -- int32
- statbonuses:[GetCrippBlowChance](getcrippblowchance)() const; -- int32
- statbonuses:[GetCritDmgMod](getcritdmgmod)(int idx) const; -- int32
- statbonuses:[GetCriticalDoTChance](getcriticaldotchance)() const; -- int32
- statbonuses:[GetCriticalDotDecay](getcriticaldotdecay)() const; -- bool
- statbonuses:[GetCriticalHealChance](getcriticalhealchance)() const; -- int32
- statbonuses:[GetCriticalHealDecay](getcriticalhealdecay)() const; -- bool
- statbonuses:[GetCriticalHealOverTime](getcriticalhealovertime)() const; -- int32
- statbonuses:[GetCriticalHitChance](getcriticalhitchance)(int idx) const; -- int32
- statbonuses:[GetCriticalMend](getcriticalmend)() const; -- int8
- statbonuses:[GetCriticalRegenDecay](getcriticalregendecay)() const; -- bool
- statbonuses:[GetCriticalSpellChance](getcriticalspellchance)() const; -- int32
- statbonuses:[GetDEX](getdex)() const; -- int32
- statbonuses:[GetDEXCapMod](getdexcapmod)() const; -- int32
- statbonuses:[GetDR](getdr)() const; -- int32
- statbonuses:[GetDRCapMod](getdrcapmod)() const; -- int32
- statbonuses:[GetDSMitigation](getdsmitigation)() const; -- int32
- statbonuses:[GetDSMitigationOffHand](getdsmitigationoffhand)() const; -- int32
- statbonuses:[GetDStacker](getdstacker)(int idx) const; -- int32
- statbonuses:[GetDamageModifier](getdamagemodifier)(int idx) const; -- int32
- statbonuses:[GetDamageModifier2](getdamagemodifier2)(int idx) const; -- int32
- statbonuses:[GetDamageShield](getdamageshield)() const; -- int
- statbonuses:[GetDamageShieldSpellID](getdamageshieldspellid)() const; -- uint16
- statbonuses:[GetDamageShieldType](getdamageshieldtype)() const; -- int
- statbonuses:[GetDeathSave](getdeathsave)(int idx) const; -- uint32
- statbonuses:[GetDelayDeath](getdelaydeath)() const; -- uint32
- statbonuses:[GetDistanceRemoval](getdistanceremoval)() const; -- bool
- statbonuses:[GetDivineAura](getdivineaura)() const; -- bool
- statbonuses:[GetDivineSaveChance](getdivinesavechance)(int idx) const; -- int32
- statbonuses:[GetDoTShielding](getdotshielding)() const; -- int32
- statbonuses:[GetDodgeChance](getdodgechance)() const; -- int32
- statbonuses:[GetDotCritDmgIncrease](getdotcritdmgincrease)() const; -- int32
- statbonuses:[GetDoubleAttackChance](getdoubleattackchance)() const; -- int32
- statbonuses:[GetDoubleRangedAttack](getdoublerangedattack)() const; -- int32
- statbonuses:[GetDoubleRiposte](getdoubleriposte)() const; -- int32
- statbonuses:[GetDoubleSpecialAttack](getdoublespecialattack)() const; -- int32
- statbonuses:[GetDualWieldChance](getdualwieldchance)() const; -- int32
- statbonuses:[GetEndPercCap](getendperccap)(int idx) const; -- int
- statbonuses:[GetEndurance](getendurance)() const; -- int32
- statbonuses:[GetEnduranceReduction](getendurancereduction)() const; -- int32
- statbonuses:[GetEnduranceRegen](getenduranceregen)() const; -- int32
- statbonuses:[GetExtraAttackChance](getextraattackchance)() const; -- int32
- statbonuses:[GetFR](getfr)() const; -- int32
- statbonuses:[GetFRCapMod](getfrcapmod)() const; -- int32
- statbonuses:[GetFactionModPct](getfactionmodpct)() const; -- int32
- statbonuses:[GetFearless](getfearless)() const; -- bool
- statbonuses:[GetFeignedCastOnChance](getfeignedcastonchance)() const; -- int16
- statbonuses:[GetFinishingBlow](getfinishingblow)(int idx) const; -- int32
- statbonuses:[GetFinishingBlowLvl](getfinishingblowlvl)(int idx) const; -- uint32
- statbonuses:[GetFlurryChance](getflurrychance)() const; -- int32
- statbonuses:[GetFocusEffects](getfocuseffects)(int idx) const; -- uint8
- statbonuses:[GetFocusEffectsWorn](getfocuseffectsworn)(int idx) const; -- int16
- statbonuses:[GetForageAdditionalItems](getforageadditionalitems)() const; -- uint8
- statbonuses:[GetFrenziedDevastation](getfrenzieddevastation)() const; -- int32
- statbonuses:[GetFrontalBackstabChance](getfrontalbackstabchance)() const; -- uint8
- statbonuses:[GetFrontalBackstabMinDmg](getfrontalbackstabmindmg)() const; -- bool
- statbonuses:[GetFrontalStunResist](getfrontalstunresist)() const; -- uint8
- statbonuses:[GetGiveDoubleAttack](getgivedoubleattack)() const; -- uint32
- statbonuses:[GetGiveDoubleRiposte](getgivedoubleriposte)(int idx) const; -- int32
- statbonuses:[GetGivePetGroupTarget](getgivepetgrouptarget)() const; -- bool
- statbonuses:[GetGravityEffect](getgravityeffect)() const; -- int32
- statbonuses:[GetHP](gethp)() const; -- int32
- statbonuses:[GetHPPercCap](gethpperccap)(int idx) const; -- int
- statbonuses:[GetHPRegen](gethpregen)() const; -- int32
- statbonuses:[GetHPToManaConvert](gethptomanaconvert)() const; -- uint32
- statbonuses:[GetHSLevel](gethslevel)(int idx) const; -- uint8
- statbonuses:[GetHeadShot](getheadshot)(int idx) const; -- uint32
- statbonuses:[GetHealAmt](gethealamt)() const; -- int32
- statbonuses:[GetHealRate](gethealrate)() const; -- int32
- statbonuses:[GetHeroicAGI](getheroicagi)() const; -- int32
- statbonuses:[GetHeroicCHA](getheroiccha)() const; -- int32
- statbonuses:[GetHeroicCR](getheroiccr)() const; -- int32
- statbonuses:[GetHeroicCorrup](getheroiccorrup)() const; -- int32
- statbonuses:[GetHeroicDEX](getheroicdex)() const; -- int32
- statbonuses:[GetHeroicDR](getheroicdr)() const; -- int32
- statbonuses:[GetHeroicFR](getheroicfr)() const; -- int32
- statbonuses:[GetHeroicINT](getheroicint)() const; -- int32
- statbonuses:[GetHeroicMR](getheroicmr)() const; -- int32
- statbonuses:[GetHeroicPR](getheroicpr)() const; -- int32
- statbonuses:[GetHeroicSTA](getheroicsta)() const; -- int32
- statbonuses:[GetHeroicSTR](getheroicstr)() const; -- int32
- statbonuses:[GetHeroicWIS](getheroicwis)() const; -- int32
- statbonuses:[GetHitChance](gethitchance)() const; -- int32
- statbonuses:[GetHitChanceEffect](gethitchanceeffect)(int idx) const; -- int32
- statbonuses:[GetHundredHands](gethundredhands)() const; -- int32
- statbonuses:[GetINT](getint)() const; -- int32
- statbonuses:[GetINTCapMod](getintcapmod)() const; -- int32
- statbonuses:[GetIllusionPersistence](getillusionpersistence)() const; -- bool
- statbonuses:[GetImmuneToFlee](getimmunetoflee)() const; -- bool
- statbonuses:[GetImprovedReclaimEnergy](getimprovedreclaimenergy)() const; -- int32
- statbonuses:[GetImprovedTaunt](getimprovedtaunt)(int idx) const; -- int32
- statbonuses:[GetIncreaseBlockChance](getincreaseblockchance)() const; -- int32
- statbonuses:[GetIncreaseChanceMemwipe](getincreasechancememwipe)() const; -- int8
- statbonuses:[GetIncreaseRunSpeedCap](getincreaserunspeedcap)() const; -- uint8
- statbonuses:[GetIsBlind](getisblind)() const; -- bool
- statbonuses:[GetIsFeared](getisfeared)() const; -- bool
- statbonuses:[GetItemATKCap](getitematkcap)() const; -- int32
- statbonuses:[GetItemHPRegenCap](getitemhpregencap)() const; -- int32
- statbonuses:[GetItemManaRegenCap](getitemmanaregencap)() const; -- uint32
- statbonuses:[GetLimitToSkill](getlimittoskill)(int idx) const; -- bool
- statbonuses:[GetMR](getmr)() const; -- int32
- statbonuses:[GetMRCapMod](getmrcapmod)() const; -- int32
- statbonuses:[GetMagicWeapon](getmagicweapon)() const; -- bool
- statbonuses:[GetMana](getmana)() const; -- int32
- statbonuses:[GetManaAbsorbPercentDamage](getmanaabsorbpercentdamage)(int idx) const; -- uint32
- statbonuses:[GetManaPercCap](getmanaperccap)(int idx) const; -- int
- statbonuses:[GetManaRegen](getmanaregen)() const; -- int32
- statbonuses:[GetMasteryofPast](getmasteryofpast)() const; -- uint8
- statbonuses:[GetMaxBindWound](getmaxbindwound)() const; -- int32
- statbonuses:[GetMaxHP](getmaxhp)() const; -- int32
- statbonuses:[GetMaxHPChange](getmaxhpchange)() const; -- int32
- statbonuses:[GetMeleeLifetap](getmeleelifetap)() const; -- int32
- statbonuses:[GetMeleeMitigation](getmeleemitigation)() const; -- int32
- statbonuses:[GetMeleeMitigationEffect](getmeleemitigationeffect)() const; -- int32
- statbonuses:[GetMeleeRune](getmeleerune)(int idx) const; -- uint32
- statbonuses:[GetMeleeSkillCheck](getmeleeskillcheck)() const; -- int32
- statbonuses:[GetMeleeSkillCheckSkill](getmeleeskillcheckskill)() const; -- uint8
- statbonuses:[GetMeleeThresholdGuard](getmeleethresholdguard)(int idx) const; -- uint32
- statbonuses:[GetMetabolism](getmetabolism)() const; -- int32
- statbonuses:[GetMinDamageModifier](getmindamagemodifier)(int idx) const; -- int32
- statbonuses:[GetMitigateDotRune](getmitigatedotrune)(int idx) const; -- uint32
- statbonuses:[GetMitigateMeleeRune](getmitigatemeleerune)(int idx) const; -- uint32
- statbonuses:[GetMitigateSpellRune](getmitigatespellrune)(int idx) const; -- uint32
- statbonuses:[GetNegateAttacks](getnegateattacks)(int idx) const; -- uint32
- statbonuses:[GetNegateEffects](getnegateeffects)() const; -- bool
- statbonuses:[GetNegateIfCombat](getnegateifcombat)() const; -- bool
- statbonuses:[GetNoBreakAESneak](getnobreakaesneak)() const; -- int16
- statbonuses:[GetOffhandRiposteFail](getoffhandripostefail)() const; -- int32
- statbonuses:[GetPC_Pet_Flurry](getpc_pet_flurry)() const; -- uint32
- statbonuses:[GetPC_Pet_Rampage](getpc_pet_rampage)(int idx) const; -- uint32
- statbonuses:[GetPR](getpr)() const; -- int32
- statbonuses:[GetPRCapMod](getprcapmod)() const; -- int32
- statbonuses:[GetPackrat](getpackrat)() const; -- int8
- statbonuses:[GetParryChance](getparrychance)() const; -- int32
- statbonuses:[GetPersistantCasting](getpersistantcasting)() const; -- uint32
- statbonuses:[GetPetAvoidance](getpetavoidance)() const; -- int32
- statbonuses:[GetPetCriticalHit](getpetcriticalhit)() const; -- int32
- statbonuses:[GetPetFlurry](getpetflurry)() const; -- int32
- statbonuses:[GetPetMaxHP](getpetmaxhp)() const; -- int32
- statbonuses:[GetPetMeleeMitigation](getpetmeleemitigation)() const; -- int32
- statbonuses:[GetProcChance](getprocchance)() const; -- int32
- statbonuses:[GetProcChanceSPA](getprocchancespa)() const; -- int32
- statbonuses:[GetRaiseSkillCap](getraiseskillcap)(int idx) const; -- uint32
- statbonuses:[GetReduceFallDamage](getreducefalldamage)() const; -- uint16
- statbonuses:[GetReduceTradeskillFail](getreducetradeskillfail)(int idx) const; -- int32
- statbonuses:[GetResistFearChance](getresistfearchance)() const; -- int32
- statbonuses:[GetResistSpellChance](getresistspellchance)() const; -- int32
- statbonuses:[GetReverseDamageShield](getreversedamageshield)() const; -- int
- statbonuses:[GetReverseDamageShieldSpellID](getreversedamageshieldspellid)() const; -- uint16
- statbonuses:[GetReverseDamageShieldType](getreversedamageshieldtype)() const; -- int
- statbonuses:[GetRiposteChance](getripostechance)() const; -- int32
- statbonuses:[GetRoot](getroot)(int idx) const; -- int8
- statbonuses:[GetRootBreakChance](getrootbreakchance)() const; -- int32
- statbonuses:[GetSEResist](getseresist)(int idx) const; -- int32
- statbonuses:[GetSTA](getsta)() const; -- int32
- statbonuses:[GetSTACapMod](getstacapmod)() const; -- int32
- statbonuses:[GetSTR](getstr)() const; -- int32
- statbonuses:[GetSTRCapMod](getstrcapmod)() const; -- int32
- statbonuses:[GetSalvageChance](getsalvagechance)() const; -- uint8
- statbonuses:[GetSanctuary](getsanctuary)() const; -- bool
- statbonuses:[GetScreech](getscreech)() const; -- int8
- statbonuses:[GetSecondaryDmgInc](getsecondarydmginc)() const; -- bool
- statbonuses:[GetSeeInvis](getseeinvis)() const; -- uint8
- statbonuses:[GetShieldBlock](getshieldblock)() const; -- int32
- statbonuses:[GetShieldEquipDmgMod](getshieldequipdmgmod)() const; -- int32
- statbonuses:[GetShroudofStealth](getshroudofstealth)() const; -- bool
- statbonuses:[GetSkillAttackProc](getskillattackproc)(int idx) const; -- int32
- statbonuses:[GetSkillDamageAmount](getskilldamageamount)(int idx) const; -- int32
- statbonuses:[GetSkillDamageAmount2](getskilldamageamount2)(int idx) const; -- int32
- statbonuses:[GetSkillDmgTaken](getskilldmgtaken)(int idx) const; -- int16
- statbonuses:[GetSkillProc](getskillproc)(int idx) const; -- uint32
- statbonuses:[GetSkillProcSuccess](getskillprocsuccess)(int idx) const; -- uint32
- statbonuses:[GetSkillReuseTime](getskillreusetime)(int idx) const; -- int32
- statbonuses:[GetSlayUndead](getslayundead)(int idx) const; -- int32
- statbonuses:[GetSongRange](getsongrange)() const; -- int32
- statbonuses:[GetSpellCritDmgIncNoStack](getspellcritdmgincnostack)() const; -- int32
- statbonuses:[GetSpellCritDmgIncrease](getspellcritdmgincrease)() const; -- int32
- statbonuses:[GetSpellDamageShield](getspelldamageshield)() const; -- int
- statbonuses:[GetSpellDmg](getspelldmg)() const; -- int32
- statbonuses:[GetSpellOnDeath](getspellondeath)(int idx) const; -- uint32
- statbonuses:[GetSpellOnKill](getspellonkill)(int idx) const; -- uint32
- statbonuses:[GetSpellProcChance](getspellprocchance)() const; -- int32
- statbonuses:[GetSpellShield](getspellshield)() const; -- int
- statbonuses:[GetSpellThresholdGuard](getspellthresholdguard)(int idx) const; -- uint32
- statbonuses:[GetSpellTriggers](getspelltriggers)(int idx) const; -- uint32
- statbonuses:[GetStrikeThrough](getstrikethrough)() const; -- int32
- statbonuses:[GetStunBashChance](getstunbashchance)() const; -- int8
- statbonuses:[GetStunResist](getstunresist)() const; -- int32
- statbonuses:[GetTradeSkillMastery](gettradeskillmastery)() const; -- uint8
- statbonuses:[GetTriggerMeleeThreshold](gettriggermeleethreshold)() const; -- bool
- statbonuses:[GetTriggerOnValueAmount](gettriggeronvalueamount)() const; -- bool
- statbonuses:[GetTriggerSpellThreshold](gettriggerspellthreshold)() const; -- bool
- statbonuses:[GetTripleAttackChance](gettripleattackchance)() const; -- int32
- statbonuses:[GetTripleBackstab](gettriplebackstab)() const; -- uint8
- statbonuses:[GetTwoHandBluntBlock](gettwohandbluntblock)() const; -- int32
- statbonuses:[GetUnfailingDivinity](getunfailingdivinity)() const; -- int32
- statbonuses:[GetVampirism](getvampirism)() const; -- int32
- statbonuses:[GetVoiceGraft](getvoicegraft)() const; -- uint32
- statbonuses:[GetWIS](getwis)() const; -- int32
- statbonuses:[GetWISCapMod](getwiscapmod)() const; -- int32
- statbonuses:[GetXPRateMod](getxpratemod)() const; -- int
- statbonuses:[GetbrassMod](getbrassmod)() const; -- uint32
- statbonuses:[Geteffective_casting_level](geteffective_casting_level)() const; -- int
- statbonuses:[Getextra_xtargets](getextra_xtargets)() const; -- uint16
- statbonuses:[Gethaste](gethaste)() const; -- int32
- statbonuses:[Gethastetype2](gethastetype2)() const; -- int32
- statbonuses:[Gethastetype3](gethastetype3)() const; -- int32
- statbonuses:[Gethatemod](gethatemod)() const; -- int8
- statbonuses:[Getinhibitmelee](getinhibitmelee)() const; -- int32
- statbonuses:[Getmovementspeed](getmovementspeed)() const; -- int
- statbonuses:[GetpercussionMod](getpercussionmod)() const; -- uint32
- statbonuses:[Getreflect_chance](getreflect_chance)() const; -- int
- statbonuses:[GetsingingMod](getsingingmod)() const; -- uint32
- statbonuses:[Getskillmod](getskillmod)(int idx) const; -- int32
- statbonuses:[Getskillmodmax](getskillmodmax)(int idx) const; -- int32
- statbonuses:[GetsongModCap](getsongmodcap)() const; -- uint32
- statbonuses:[GetstringedMod](getstringedmod)() const; -- uint32
- statbonuses:[GetwindMod](getwindmod)() const; -- uint32