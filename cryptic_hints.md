## ranged weapon

- *its inner workings are quite complex, dangerous, and malleable.* (hecate.mp3 (Noita): "Wand (Tier 5)")
- *now, the wraiths shall reach ever higher.* (Connor (HK): "Shaman_Stone")
- *a flurry of bullets and sparks.* (hecate.mp3 (UK): "Shotgun - Sawed-On")
- *it's time to stop bringing fists to a gun fight.* (hecate.mp3 (UK): reduce `any_weapon_or_arm` to 1)
- *wield the power of darkness once more.* (Toto (HK): change `RemoveSpellUpgrades` to `false`)

## fire

- *pour the oil on the floor and light it ablaze!* (hecate.mp3 (UK): "Rocket Launcher - Firestarter")
- *burn them away and they shall disappear!* (Roguinater (Peggle Deluxe): Lord Cinderbottom)

## explosion

- *fire the cannonballs!* (hecate.mp3 (UK): "Rocket Launcher - S.R.S. Cannon")
- *starting from the bottom-left corner, draw a plus sign (like bubble letters, but more angularly), such that you go back to the start (but don't intersect with it) when you're finished drawing.* (Sylsko (TUNC): Firecracker x5)
- *a green man.* (Roguinater (Peggle Nights): Splork)

## vitality

- *a relic from a fortress.* (Sylsko (TUNC): Hero Relic - HP)
- *a glass object, completely full.* (Caesius (OOT): "Heart Container")
- *a brown tablet with a red symbol on it.* (hecate.mp3 (Noita): "Extra Max HP")
- *a living core.* (Connor (HK): "Lifeblood_Heart")
- *a blue magic stone.* (Sylsko (Ender Lilies): Amulet Gem)
- *a reward for felling a beast.* (Maxor: Boss Heart Container)
- *move past your constraints, and live longer.* (Toto (TS): increase `hp_cap`)
- *four into one. acquire a tenth one.* (Toto (HK): "Full_Mask" [Not from pool])
- *come on, just die already! how much health do you have?* (DiStegRogue (LTTP): change `enemy_health` to `default`)
- *a red flower.* (hecate.mp3 (TUNC): "HP Offering")
- *this iconic item has been replaced by orbs now.* (Caesius (OOT): "Piece of Heart")

## healing

- *a pink object with a red ribbon.* (hecate.mp3 (TUNC): "Potion Flask")
- *a wrapping with ash inside.* (hecate.mp3 (TUNC): "Potion Offering")
- *bearing this will allow you to appease the Mind.* (Connor (HK): "Hiveblood")
- *a button that is either white or yellow.* (Connor (UT): "ITEM": 1)
- *ok, and now, they're going to protect...* (Caesius (Emerald): "Super Potion")
- *your great strength marks you amongst us.* (Toto (HK): change `RandomizeFocus` to `false`)
- *a fleeting wish left behind at the moment of death.* (Sylsko (Ender Lilies): Priestess' Wish)
- *recover through death of your enemies.* (BennyRogue (RL): Vampire Runes)

## fearless
- *rain and darkness.* (Alex230: Disable Atmosfear Mod)
- *this is either enemy rando or unique movement, and somehow, i can't tell which.* (Alex230: Disable Malice Mod)

## challenge

- *you don't have to be perfect.* (hecate.mp3 (UK): reduce `p_rank_rewards: 'true'` to 2)
- *the chains shall hold you down no more.* (Connor (Godhome): change `include_bindings` to `false`)
- *your doors will be a little more secure.* (Caesius (MC): reduce `combat_difficulty` by one level)
- *it is unwise to begin a story on chapter 5.* (Sylsko (Ender Lilies): reduce `start_chapter` by 2)
- *ootbijmq.* (DiStegRogue (OOT): make `mq_dungeons_mode` easier)
- *orb-less.* (hecate.mp3 (Noita): increase `orbs_as_checks no_orbs` to 4)
- *on second thought, maybe we shouldn't be this high up.* (Toto (StS): reduce `ascension` value)
- *it is a very deadly light.* (Connor (Godhome): change `include_radiant_difficulty` to `false`)

## sight
- *a unique sort of brightness.* (Alex230: Brighter Gamma)
- *invisibility doesn't matter too much.* (Roguinater (Meritous): Ethereal Monocle)

## speed
- *grab the treasure and get out of there!* (hecate.mp3 (DO2): "Loot & Scoot")
- *yeah, i can probably make that jump.* (hecate.mp3 (OW): "Boost Duration Upgrade")
- *nyoom!* (Sylsko (TS): change `quick_seed` to `true`)
- *a little charm with wings (at least, if it doesn't have wings, it should!)* (Sylsko (Astalon): Icarus Emblem)
- *you can climb back up to the beginning.* (Toto (HK): change `ExtraPlatforms` to `true`)

## stealth
- *don't make a sound! They'll hear you!* (hecate.mp3 (DO2): "Sneak")
- *become light on your feet.* (Sylsko (TUNC): Muffling Bell)
- *the twisting vines will no longer be unknowable.* (hecate.mp3 (OW): reduce `randomize_dark_bramble_layout: 'true'` chance)
- *you can't see me, my time is now!* (Caesius (Emerald): change `blind_trainers` to `true`)
- *the canine holds a gift.* (BennyRogue (Witness): increase `shuffle_dog: puzzle_skip` weight to 6)

## traps

- *not the bees!* (Caesius (MC): change `bee_traps` to `random-low`)
- *a little misstep. the dungeon will take notice.* (hecate.mp3 (DO2): reduce `filler_traps` chance)
- *this is the worst time to take a nap.* (hecate.mp3 (OW): reduce `trap_chance`)
- *one of GladOS's favorite weapons.* (Connor (TS): lower `trap_chance` by 25)
- *fool!* (hecate.mp3 (TUNC): change `fool_traps: onslaught` to 0)
- *around you, all your foes grow stronger.* (Roguinater (Meritous): set `include_evolution_traps` to `false`)
- *constantly slowed........* (BennyRogue (Witness): change `trap_percentage` to `random-low`)

## link
- *we already have enough shared suffering in this async!* (remove `LTTPTrapLink` `item_link`)
- *is it real? i don't know anymore!* (remove `HollowKnightTrapLink` `item_link`)
- *the bees... are connected...* (remove `MinecraftTrapLink` `item_link`)
- *we are all fools.* (remove `TunicTrapLink` `item_link`)
- *chaos, chaos!* (remove `TimespinnerTrapLink` `item_link`)

## goal
- *prepare thyself!* (hecate.mp3 (UK): reduce `goal: P_1` to 1)
- *a visitor?* (hecate.mp3 (UK): reduce `goal: P_2` to 1)
- *world has been restored* (hecate.mp3 (Noita): reduce `peaceful_ending` to 1)
- *fight them individually, instead of all at once.* (Connor (Godhome): change `victory_condition` to `boss_rush`)
- *a child is fated to slay their parent: a tale as old as time.* (Connor (TS): change `dad_percent` to `true`)
- *arbalistic!* (ChromaNyan (MC): reduce `advancement_goal` by 10)
- *be allowed entry with the elite.* (DiStegRogue (RB): lower `elite_four_badges_condition` range)
- *benevolence.* (Sylsko (Ender Lilies): change `goal` to easier goal)
- *return the seal.* (Roguinater (Meritous): reduce `goal` difficulty)
- *you no longer must complete the pillars.* (BennyRogue (Witness): decrease `victory_condition: elevator` weight to 3)
- *seek fewer squares.* (BennyRogue (Witness): change `panel_hunt_required_percentage` to `random-low`)

## boss
- *the dragon egg will remain whole.* (hecate.mp3 (Noita): increase `bosses_as_checks no_bosses` to 4)
- *such a mischievous rodent...* (hecate.mp3 (UK): reduce `boss_rewards: extended` to 1)
- *a little guy vs. a bunny with a gun* (Sylsko (TUNC): add `Rooted Ziggurat Lower - Hexagon Blue` to `exclude_locations`)
- *the heart keeps beating...* (Toto (StS): reduce `final_act: true` weight)
- *ah, hello, watchers. didn't see you there.* (Toto (DS3): change `simple_early_bosses` to `true`)

## key
- *press the "3" button (though idk if that reference applies in this context)* (Sylsko (Astalon): change `start_with_ascendant_key` to `true`)
- *an extra key to enter deeper into the depths (in case you don't find another)* (hecate.mp3 (DO2): change `caves_of_carnage_key_count`, `black_mines_key_count`, `flooded_depths_key_count`, and `burning_dark_key_count` to random-high)
- *hey, weren't there only supposed to be 2 keys to unlock this?* (Connor (UT): decrease `key_pieces` by varied amounts)

## breath
- *a green helmet should alleviate this problem.* (hecate.mp3 (DO2): change `revelation_count`, `aquata_breather_count`, and `eureka_count` to random-high)

## dangerous areas
- *i'd prefer the easy way, thanks.* (Roguinater (V6): make "Doing Things the Hard Way" and "Edge Games" less important locations)
- *i thought we were done climbing towers!* (hecate.mp3 (Noita): reduce `path option: main_world` to 1)
- *you hear a crumbling sound, as a passageway becomes blocked. you'll have to take the harder path.* (hecate.mp3 (DO2): "Stability")
- *nope, not doing that. that looks awful.* (BennyRogue (Witness): increase `shuffle_vault_boxes: 'false'` weight to 7)
- *you know where not to go if everything's the same!* (BennyRogue (RL): change `architect` to `early`)

## macguffins
- *won't require all 33 anymore!* (hecate.mp3 (Noita): change `extra_orbs` to `random-high`)
- *you don't have to bring her so many fruits!* (Sylsko (C64): reduce `strawberries_required_percentage` by varying amounts)
- *normally (outside of the context of the randomizer) you can only get this a few ways. a simple mechanism does the trick, though.* (Roguinater (MC): reduce `egg_shards_required` by varying amounts)
- *The Institute's calling, and they've expressed their approval.* (Roguinater (Peggle Deluxe): decrease `certificates_required` by 2)

## price
- *need any change?* (hecate.mp3 (UK): "Revolver - Marksman")
- *you might have the cash, but i'm not selling it to you yet.* (Toto (HK): halve `CostSanityHybridChance`)
- *it's more common where the land is reddened.* (Caesius (MC): "8 Gold Ore")
- *use it to get the most iconic item in this game.* (Roguinater (MC): 4 Diamond Ore)
- *nope, too expensive.* (Sylsko (Astalon): lower `cost_multiplier`)
- *find more cash in your travels.* (Sylsko (Astalon): Amulet of Sol)
- *brainrot residue* (Sylsko (Ender Lilies): Furious Blight x800)
- *hey, don't take my money! i needed that!* (BennyRogue (RL): increase `disable_charon: 'true'` weight to 5)

## defense
- *yup, it's absolutely so broken.* (Connor (UT): "temy armor")
- *a little figurine! i think it's you.* (hecate.mp3 (TUNC): "DEF Offering")
- *so used to not having it, but it's prominently displayed in basically all art for this game.* (hecate.mp3 (TUNC): "Shield")
- *very simple and direct. it's doubled.* (DiStegRogue (OOT): Double Defense)
- *if you want it all, that'll be 24.* (Roguinater (MC): Progressive Armor)
- *a protective spell.* (Caesius (OOT): "Nayrus Love")
- *a half-hat.* (Caesius (TS): "Eternal Crown")
- *mail time! (the other definition of "mail")* (Rezalex: Progressive Armor)

## careful movement
- *you might be rolling a little too much.* (Caesius (OOT): lower `deadly_bonks`)
- *reduce those vulnerable frames!* (hecate.mp3 (TUNC): "Bone Card")
- *"hmmmmm, today i will fly into space." <-- clueless* (hecate.mp3 (OW): "Autopilot")

## attack
- *offer this memento and share a delusion of power.* (hecate.mp3 (TUNC): "ATT Offering")
- *the same weapon, but it seems different this time.* (ChromaNyan (MC): "Sharpness III Book")
- *the crown of the ruler of this land.* (Sylsko (TS): Empire Crown)
- *attune to a true memory of yourself, instead of a pale retelling.* (Sylsko (TUNC): Hero Relic - ATT)
- *perhaps a little too nerfed.* (Caesius (TS): make `damage_rando` better)
- *strike with deadly efficiency.* (BennyRogue (RL): Crit Chance Up)

## stamina
- *a relic found in the swamp.* (Sylsko (TUNC): Hero Relic - SP)

## mana
- *a blue mushroom.* (hecate.mp3 (TUNC): "MP Offering")
- *it's like that one Edward Eager book (kind of).* (Maxor: Magic Upgrade (1/2))
- *a one-of-a-kind spellcaster.* (Toto (SotM): remove `Argent Adept`, `Dark Conductor Argent Adept`, `Prime Wardens Argent Adept`, and `Xtreme Prime Wardens Argent Adept` from `exclude_from_pool`)
- *absorb the magic left after death.* (BennyRogue (RL): Siphon Runes)

## slots
- *a box full of rocks, food, and lumber.* (Roguinater (MC): Shulker Box)
- *you may hold one more card.* (hecate.mp3 (TUNC): "Card Slot")
- *move swiftly in the heaviest of armor.* (Toto (DS3): change `no_equip_load` to `true`)
- *oops! all 6s* (Toto (HK): decrease `RandomCharmCosts` by 20)

## food
- *we're having pig for dinner tonight!* (ChromaNyan (MC): "16 Porkchops": 1)

## second chance
- *should you hold it in your left hand, something magical may happen.* (hecate.mp3 (DO2): change `pay_to_win_count`, `tailor_for_success_count`, and `last_stand_count` to random-high)
- *this isn't a nuzlocke! death doesn't matter!* (Caesius (Emerald): "Sacred Ash")
- *you may have missed your shot, but it's back again!* (Roguinater (Peggle Nights): Renfield)
- *i feel like it's not common to use this item for what it actually says in its name. you use it for other things, but specifically not what it says it does.* (Rezalex: Bug Catching Net)
- *for holding those who you capture.* (DiStegRogue (LTTP): Bottle)
- *good thing i brought a spare battery.* (Slipomatic_SM: Reserve Tank)

## progression balancing
- *it seems you'll be having burgers for dinner another day.* (Alex230: increase `progression_balancing` by 10)
- *a get out of jail free card.* (Connor (UT): increase `progression_balancing` by 20)
- *it goes up to 99.* (Roguinater (Meritous): increase `progression_balancing` by 15)
- *you'll never have time to wash the dishes again.* (Connor (SquareMusic): increase `progression_balancing` by varied amounts)

## choice
- *you may choose from three, and another three.* (Toto (StS): "Card Draw" x 2 [Not from pool])
- *if fatal...* (Toto (StS): "Rare Card Draw" [Not from pool])
- *unleash your orbs.* (Toto (StS): "Card Draw" x 2 [Not from pool])
- *several shivs should do the trick.* (Toto (StS): "Card Draw" x 2 [Not from pool])
- *do the math, multiplying everything by 3. if you do the math wrong, you could die very easily.* (Toto (StS): "Rare Card Draw" [Not from pool])

## rest
- *take a breather! put the game down for a little while.* (Alex230: Allow Free Saves and Loads)

## electricity
- *launching electric wires out may be a little dangerous.* (hecate.mp3 (UK): "Railcannon - Electric")

## low HP
- *found in a chest next to a white ellipse.* (Connor (Godhome): "Fury of the Fallen")

## XP
- *becoming stronger just by proximity.* (DiStegRogue (Emerald): Exp. Share)
- *orbs are stronger! no, not those orbs. the other ones.* (Sylsko (TS): Galaxy Earrings)
- *it looks like a jolly rancher.* (Caesius (Emerald): "Rare Candy")
- *you won't have to spend as much for your weapon to become as strong as it can.* (Toto (DS3): increase `max_levels_in_10` by 5)
- *they'll get the hang of fights really quickly.* (DiStegRogue (RB): increase `exp_modifier` by 16)

## melee weapon
- *you might not be a glass cannon, but your weapon sure is.* (Connor (HK): "Fragile_Strength")
- *you will no longer have a weakness on your left side.* (Toto (HK): change `RandomizeNail` to `false`)
- *greater than the greatest sword.* (DiStegRogue (OOT): Biggoron Sword)
- *a little weapon.* (Caesius (OOT): change `shuffle_kokiri_sword` to `false`)
- *have three spheres.* (Caesius (TS): "Star of Lachiem")
- *wield weapons beyond your capability.* (Toto (DS3): change `no_weapon_requirements` to `true`)
- *a bright red sword.* (BennyRogue (RL): Dragon Blueprints)

## starting
- *i sure love immediately having to deal with wizards!* (Connor (UT): change `starting_area` to easier areas)
- *start with more cards.* (Toto (SotM): in `filler_weights`, change `StartHandSize variant` to `both` and `specificity` to 1)

## revenge
- *a gift in exchange for ten freed.* (Connor (Godhome): "Grubsong")

## ice
- *from a chest in a garden.* (Sylsko (TUNC): Magic Dagger)

## beast
- *i got this from a little boy, but he didn't look so good.* (DiStegRogue (LTTP): Bug Catching Net)

## god
- *why are they allowed to have gods on their side?* (DiStegRogue (Emerald): change `trainer_party_blacklist` to `_Legendaries`)
- *he's like captain america and superman, i think.* (Toto (SotM): remove `Legacy`, `America's Greatest Legacy`, `America's Newest Legacy`, and `Freedom Five Legacy` from `exclude_from_pool`)

## water
- *now you can swim!* (Caesius (OOT): "Zora Tunic")

## army
- *bowser jr. looks a little different nowadays...* (Sylsko (C64): change `badeline_chaser_frequency` to varying amounts)
- *they know the bearer of the Sword.* (Connor (SquareMusic): "Knights of the Round")
- *put your enemies where they belong!* (Sylsko (TS): reduce `EnemyRando` difficulty)

## robot
- *an enormous robot.* (Connor (SquareMusic): "Alexander")

## luck
- *who needs master balls?* (DiStegRogue (Emerald): change `guaranteed_catch` to true)

## travel
- *come home!* (Sylsko (TUNC): Dath Stone)

## utility
- *hey, you sure this works properly? lemme fix it for you!* (Maxor: reduce `item_functionality` difficulty)
- *an anchor.* (Toto (StS): "Relic" [Not from pool])
- *a strawberry.* (Toto (StS): "Relic" [Not from pool])
- *it's basically just wayward compass.* (Roguinater (Meritous): Portable Compass)

## amnesty
- *only the fifth one counts. actually, the tenth. actually, the twentieth.* (Sylsko (C64): increase `death_link_amnesty` by varying amounts)
- *spikes aren't so bad...* (Roguinater (V6): increase `DeathLinkAmnesty`)
- *whoops, i forgot the star.* (BennyRogue (Witness): increase `death_link_amnesty` by 1)

## time
- *for some reason, they decided to add these to a mod of this game, but they add instead of subtracting. like, why? there's no visual indication that it should be like that, and yet, they just added it! for fun! why?* (Caesius (Marble Blast): "Time Travel (-5s)")
- *it adds a little complexity to speedrunning.* (Caesius (Marble Blast): "Time Travel (-5s)")
- *take a funnel, put it upside down, and put a right side up funnel on top of it.* (Caesius (TS): "Max Sand")
- *whoa, slow down! we've got plenty of time.* (Sylsko (TS): Max Sand)

## ammo
- *take a shot!* (Roguinater (Peggle Nights): set `shuffle_starting_balls` to `false`)

## sun
- *why are they wearing a rain coat and holding an umbrella? it wouldn't be necessary!* (Roguinater (Peggle Deluxe): Tula)

## copy
- *a simple enchantment can remove all material costs.* (ChromaNyan (MC): "Infinity Book")
- *no way i'm doing this with only eight hearts.* (Maxor: reduce `item_pool` difficulty)

## enemy damage
- *it certainly doesn't mix well with ice!* (Caesius (OOT): halve `damage_multiplier`)

## knowledge
- *there's something to be learned in the cold.* (add `Snow` to `start_hints`)
- *the recordings hold the secret.* (BennyRogue (Witness): change `hint_amount` to `random-high`)
- *breadth as opposed to depth.* (BennyRogue (Witness): increase `area_hint_percentage` range by 20)
- *a glittering essence.* (add `Stardust` to `start_hints`)

## defy death

- *death may be inevitable, but we can delay it a little...* (+2 life)
- *a golden charm from an ancient civilization.* (+1 life, referencing ankh from spelunky 2)
- *a power gained from a dark mirror.* (+2 life, referencing death defiance from hades)
- *a little plush that can be altered by void.* (+1 life, referencing dio's best friend from ror2)
- *a red amulet, made with a little shadow.* (+1 life, referencing life giving amulet from don't starve)
- *a golden ring, found in a volcano.* (+1 life, referencing phoenix ring from stardew)
- *eternity (XII)* (+2 life, referencing an arcana card from hades II)
- *a candlestick.* (+1 life, referencing the candles in inscryption)
- *a little doll, infused with gold and vapor.* (+1 life, referencing death protection poppet from the minecraft witchery mod)
- *a fountain guarded by a serpent.* (+1 life, referencing fountain of youth from don't starve: hamlet)
- *a stone slab, gleaming with light.* (+1 life, referencing touch stone from don't starve)
- *a wooden effigy, resembling a certain scientist.* (+1 life, referencing meat effigy from don't starve)
- *a fake tail.* (+1 life, referencing lizard tail from slay the spire)
- *a light with wings.* (+1 life, referecing fairies from zelda.)
- *a potion that amplifies your mana.* (+1 life, referencing permafrost's concoction from terraria calamity mod)
- *a blue and purple core.* (+1 life, referencing nebulous core from terraria calamity mod)
- *a green and gold set of armor.* (+1 life, referencing silva armor from terraria calamity mod)
- *an electric suit of armor.* (+2 life, referencing auric tesla armor from terraria calamity mod)
- *but it refused.* (+2 life, referencing "but it refused." from undertale)
- *a bright green potion.* (+1 life, referencing fairy in a bottle from slay the spire)
- *a beating heart, made at a price.* (+1 life, referencing telltale heart from don't starve together)
- *a coffin marked with a skull.* (+1 life, referencing the coffins from spelunky 2)
- *these are like, all over the skill tree. i've ran out of cryptic hints for them at this point.* (+1 life)
- *what sisyphus attempted (and was punished for).* (+1 life)