![This is an image](https://2.bp.blogspot.com/_jKYjaoIAhKw/TN7vTrjCgVI/AAAAAAAAAXE/6cF_fveyxdM/s1600/blocknu.png)
# (MultiMC) SimplerTimes Modpack 

## **What’s the modpack for?**

SimplerTimes Modpack is a blast into the Minecraft past.
Its main purpose is to mimic plenty of forgotten or should I say, non-forgotten former features that have either been modified on Minecraft Java Edition or removed 
(little Bedrock Edition features are included as well), especially the Alpha-version related ones & the Beta-version related ones. **IT IS A CLIENT-SIDE ONLY MODPACK.**
It currently consists in a .zip MultiMC instance file that can be downloaded through GitHub.
Therefore the "modpack" actually requires MultiMC launcher to work.
MultiMC can be downloaded through their official website:
https://multimc.org/

## **Who is the modpack for?**

The archetype example is anyone interested in playing and experiencing the old game content while enjoying
the last Minecraft features. Those who would like to broaden their knowledge can read the credits below.


## **How does it work?**

The many mod combination provides versatile features that can be disabled or enabled in "Minecraft Settings ->
Mods -> mod name".
From the old map generation to the old fog, by way of plenty little features implementation such as hunger bar's
and experience/XP bar's removals, old animations, optimization or performance-related mods (and many more),
SimplerTimes offers a wide range of possibilities that can be disabled or enabled, at your convenience. The mods
can be enabled through the in-game mods options or MultiMC mod instance options (once your game is off that
is). Be warned it uses FabriMC modloader. Currently, there are no plans to port it to Forge.
You are also reminded that the MultiMC instance will require at least the 16.01 Java version to work out. It is
also Java-17.1 compatible. A built-in 4GB+ of RAM device is recommended to decently play the modpack (for my
part, I usually allocate between 2,048MB and 3,072MB).
As far as resourcepacks are concerned, I give out several pack combinations you can use depending on your demand:
**Do not forget to apply Programmer Art below EVERY added-in resourcepack.**

- **PRE-1.13 resources:** Put the following packs in this order:
	- "floydicus-better-old-default" at the TOP
	- then Programmer Art

![old_default](https://user-images.githubusercontent.com/84197612/151043894-4f5327e7-63ee-49b8-9040-0c13da622157.png)

- **(PARTIAL) PRE-Beta-1.8 resources:** Put the following packs in this order:
	- the "golden-days-fastchest" add-on at the TOP, 
	- then the "golden-days-base"
	- then Programmer Art

![partial_beta](https://user-images.githubusercontent.com/84197612/151043998-ff1408a2-403e-4049-b382-d5b74b3346fc.png)

- **(COMPLETE) PRE-Beta-1.8 resources:** Put the following packs in this order:
	- the "golden-days-fastchest" add-on at the TOP, 
	- then the "Custom add-on pack",
	- then the "golden-days-base" 
	- then Programmer Art

![complete_beta](https://user-images.githubusercontent.com/84197612/151044083-40af6a16-4f84-455e-b093-6c5d60a89b88.png)

- **PRE-Alpha-1.2 resources:** Put the following packs in this order:
	- the "golden-days-alpha" at the TOP,
	- then the "golden-days-fastchest", 
	- then the "Custom add-on pack",
	- then the "golden-days-base" 
	- then Programmer Art

![alpha](https://user-images.githubusercontent.com/84197612/151044100-b9c86f6a-1625-4750-b052-fa6d2888572f.png)


#### Updating your old version Minecraft Worlds and keep generating old terrain thanks to Modern Beta.

You may follow b3spectacled_'s tutorial for the world conversion, attached below:

https://github.com/b3spectacled/modern-beta-fabric/wiki/Updating-Old-Worlds


#### Fixing the new 1.18+ Far Lands generation into the former one:

Since the pre-release-3 of 1.18.1 instance version, a datapack done by b3spectacled_ has been provided in the instance folder then `.minecraft/datapacks` folder.
This means it is **not enabled by default**, you need to load it whenever you're creating or importing a new world. 
Be warned once the datapack has been loaded in the world, the generation cannot be undone and you have to deal with this generation (I'm obviously not taking into account external world edit softwares.). 
In addition to that, be warned enabling the datapack will make sure 1.17+ aquifers and the new 1.18+ cave noise don't generate in the selected world (aquifers are disabled due to some very intense latency in the Far Lands). 
Here is an image instance of what you may expect from loading up the datapack (or not). By the way, I used the same world seed and coordinates only to look relevant, **you're already warned you cannot toggle them back once your world is generated**. 

Datapack **enabled** (the Far Lands are alike the former Beta ones):

![2022-02-02_19 45 13](https://user-images.githubusercontent.com/84197612/152407610-e088b2a4-4881-4e83-877e-16779586a215.png)

Datapack **disabled** (the Far Lands are more "square-ish" due to the 1.18+ cave-noise generation):

![2022-02-02_19 48 38](https://user-images.githubusercontent.com/84197612/152407693-88f9dd46-c3b0-40d5-954b-9790bd88014e.png)

## **How bright is the modpack future?**

Once, it was meant to be a private pack I was playing around with. As I was sharing a few screenshots to other
users, it turned out it was pretty much successful and I was suggested to make the pack public.
This also means this project isn't truly a "professional" involvement, in that I'm simply performing it for fun.
It means that I may not keep the project up over the months/years. It will also depend on whether the mods are
being updated or not. I will not urge any mod/resourcepack developer on continuing their project aside, if they
already aren't doing so. 
Else, whether I consider the pack incomplete on incoming versions it won't be uploaded. Quality over quantity is
my philosophy, don't expect it to be regularly updated to newer game versions.
You are still able to suggest me any new feature that may lack in the pack. Whether I take your suggestion into
account, I may add it, if it already can be found (example: whether the mod for such feature already exists,
though it isn't included in the pack).


## **My current TO-DO list (I'll try to update it):**

- Figure out a (1.18.1) FabriMC mod providing the old beacon beam model, as well as the old beacon block
model (with the animated crystal star within it), here's a picture you can look at:

![This is an image](https://static.wikia.nocookie.net/minecraft_gamepedia/images/4/42/Beacon_pyramid_revision_2.gif/revision/latest/scale-to-width-down/500?cb=20200830203001)

- Bringing back the old sun-moon rotation/direction along with cloud direction (they used to move from North to South instead of East to West).

- Inverting the Respiration and Armor bar as they used to be in b1.7.3 and prior (currently their HUD are opposite compared to once which is odd). This might be fixed for an incoming "Old Swing" mod update.

- Waiting for little visual features (related to damage entity colours, old enchantment glint/glow and no eating particle animation) to be added for an incoming "Old Swing" mod update.

- Obviously, your own suggestions I may haven't taken into account yet.


## **The basic rules:**

SimplerTimes modpack is a Minecraft modpack meant to be only used for spare time purpose. 
It has no selling interest nor it has the mods' and resourcepacks' property rights. Those property belong to their respective developers. Therefore redistributing the instance file to some second-party/second-tier shady websites and claiming it 100% yours, or directly sharing it around by unofficial download links is stricly prohibited. 
As far as download links are concerned, only the following GitHub link is official:

https://github.com/MrFlov/-MultiMC-SimplerTimes-Modpack

###### **YOU'RE (ONLY) ABLE TO:**
- (Of course) playing the modpack at your convenience, in Singleplayer as well as in Multiplayer. 
- Share the modpack to your friends, your community as long as it contains the official download link attached above. 
- Modify it at your convenience without asking, as long as it's restricted to personal use.
- Share it through videos, livestreams, screenshots, stories (any safe entertainment media). If any download link is being given in the video, it should direct to GitHub's modpack page, without ANY transitional monetizing/advertising link.

If you're willing to redesign the modpack, then releasing it while keeping the same game topic, we may talk this out first.
I won't stop you in porting the modpack to Forge as I surely won't do that.
I thank you for your understanding.

## CREDIT TO ALL THE FOLLOWING MOD AND RESOURCEPACK DEVELOPERS WITHOUT THEM THIS PROJECT WOULD NEVER EXIST (READ THEM BELOW).
You're reminded the following added-in features are strictly belonging to them, I am not responsible whether you're being took to court/sued because you didn't follow my recommendations or removed that file. 

## **Thanks to the following wonderful people:**

###### **Resource pack developers:**
- PoeticRainbow for letting me incorporating their "Golden Days" resourcepacks into the modpack.
Official download links:
	- https://github.com/PoeticRainbow/golden-days
	- https://www.planetminecraft.com/texture-pack/golden-days-beta-reversion-for-modern-minecraft/
	- https://www.curseforge.com/minecraft/texture-packs/golden-days

- OverFloyd for letting me incorporating their "Floydicus Old Pack" resourcepack into a customized one (the "Custom add-on pack"). This process was only done to make sure the game looks fully beta-geguine, even on 1.18+. 
Official download link:
	- https://www.planetminecraft.com/texture-pack/floydicus-old-pack/


###### (FabricMC mod loader) Mod developers:
- b3spectacled and their following mods:

	"Modern Beta" (CurseForge + GitHub download links):
	- https://www.curseforge.com/minecraft/mc-mods/modern-beta
	- https://github.com/b3spectacled/modern-beta-fabric

	"Custom Stars" (CurseForge + GitHub download links):
	- https://www.curseforge.com/minecraft/mc-mods/custom-stars
	- https://github.com/b3spectacled/custom-stars

	"Custom Void" (CurseForge + GitHub download links):
	- https://www.curseforge.com/minecraft/mc-mods/custom-void
	- https://github.com/b3spectacled/custom-void

	"Custom Spawns" (CurseForge + GitHub download links):
	- https://www.curseforge.com/minecraft/mc-mods/custom-spawns
	- https://github.com/b3spectacled/custom-spawns


- SmushyTaco and their following mods:

	"Hunger Remover" (CurseForge + GitHub + Modrinth download links):
	- https://www.curseforge.com/minecraft/mc-mods/hunger-remover
	- https://github.com/SmushyTaco/Hunger-Remover
	- https://modrinth.com/mod/hunger-remover/

	"Experience Remover" (CurseForge + GitHub + Modrinth download links):
	- https://www.curseforge.com/minecraft/mc-mods/experience-remover
	- https://github.com/SmushyTaco/Experience-Remover
	- https://modrinth.com/mod/Experience-Remover

 	"Human Reborn" (CurseForge + GitHub + Modrinth download links):
	- https://www.curseforge.com/minecraft/mc-mods/human-reborn
	- https://github.com/SmushyTaco/Human-Reborn
	- https://modrinth.com/mod/human-reborn

	"Craftable Enchanted Golden Apple" (CurseForge + GitHub + Modrinth download links):
	- https://www.curseforge.com/minecraft/mc-mods/fabric-craftable-enchanted-golden-apple
	- https://github.com/SmushyTaco/Craftable-Enchanted-Golden-Apple
	- https://modrinth.com/mod/Craftable-Enchanted-Golden-Apple

	"No Teleport Cooldown" (CurseForge + GitHub + Modrinth download links):
	- https://www.curseforge.com/minecraft/mc-mods/no-teleport-cooldown
	- https://github.com/SmushyTaco/No-Teleport-Cooldown
	- https://modrinth.com/mod/No-Teleport-Cooldown

	"Legacy Display" (CurseForge + GitHub + Modrinth download links):
	- https://www.curseforge.com/minecraft/mc-mods/legacy-display
	- https://github.com/SmushyTaco/Legacy-Display
	- https://modrinth.com/mod/Legacy-Display

	"Legacy Bows" (CurseForge + GitHub + Modrinth download links):
	- https://www.curseforge.com/minecraft/mc-mods/legacy-bows
	- https://github.com/SmushyTaco/Legacy-Bows
	- https://modrinth.com/mod/Legacy-Bows

	"Expanded Axe Enchanting" (CurseForge + GitHub + Modrinth download links):
	- https://www.curseforge.com/minecraft/mc-mods/expanded-axe-enchanting
	- https://github.com/SmushyTaco/Expanded-Axe-Enchanting
	- https://modrinth.com/mod/expanded-axe-enchanting/


- JellySquid3_ and their CaffeineMC mods:

	"Sodium" (CurseForge + GitHub + Modrinth download links):
	- https://www.curseforge.com/minecraft/mc-mods/sodium
	- https://github.com/CaffeineMC/sodium-fabric
	- https://modrinth.com/mod/sodium

	"Lithium" (CurseForge + GitHub + Modrinth download links):
	- https://www.curseforge.com/minecraft/mc-mods/lithium/
	- https://github.com/CaffeineMC/lithium-fabric
	- https://modrinth.com/mod/lithium


- comp500 and their "Indium" mod (CurseForge + GitHub + Modrinth download links):
	- https://www.curseforge.com/minecraft/mc-mods/indium
	- https://github.com/comp500/Indium
	- https://modrinth.com/mod/indium


- Spottedstar and their "Starlight" mod (CurseForge + GitHub + Modrinth download links):
	- https://www.curseforge.com/minecraft/mc-mods/starlight
	- https://github.com/PaperMC/Starlight
	- https://modrinth.com/mod/starlight


- Sollace and their "Void Fog" mod (CurseForge + GitHub + Modrinth download links):
	- https://www.curseforge.com/minecraft/mc-mods/custom-fog
	- https://github.com/Sollace/Void-Fog
	- https://modrinth.com/mod/void-fog


- dorianpb and their "CEM/Custom Entity Models" mod (CurseForge + GitHub + Modrinth download links):
	- https://www.curseforge.com/minecraft/mc-mods/custom-entity-models-cem
	- https://github.com/dorianpb/cem
	- https://modrinth.com/mod/cem


- NeRdTheNed and their "Punch2Prime" mod (CurseForge + GitHub + Modrinth download links):
	- https://www.curseforge.com/minecraft/mc-mods/punch2prime
	- https://github.com/NeRdTheNed/Punch2Prime
	- https://www.modrinth.com/mod/punch2prime


- tuxed/astei and their following mods:

	"LazyDFU" mod (CurseForge + GitHub + Modrinth download links):
	- https://www.curseforge.com/minecraft/mc-mods/lazydfu
	- https://github.com/astei/lazydfu
	- https://modrinth.com/mod/lazydfu

	"Krypton" mod (CurseForge + GitHub + Modrinth download links):
	- https://www.curseforge.com/minecraft/mc-mods/krypton
	- https://github.com/astei/krypton
	- https://modrinth.com/mod/krypton


- RiceCookey and their "CombatEdit" mod (CurseForge + GitHub download links):
	- https://github.com/rizecookey/CombatEdit
	- https://www.curseforge.com/minecraft/mc-mods/combatedit


- Adrenix and their "Old Swing – Eye Candy" mod (CurseForge + GitHub download links):
	- https://www.curseforge.com/minecraft/mc-mods/old-swing
	- https://github.com/Adrenix/OldSwing


- Setadokalo their "Custom Fog" mod (CurseForge + GitHub + Modrinth download links):
	- https://www.curseforge.com/minecraft/mc-mods/custom-fog
	- https://github.com/Setadokalo/custom-fog
	- https://modrinth.com/mod/custom-fog


- NatanFudge and their "Not Enough Crashes" mod (CurseForge + GitHub download links):
	- https://www.curseforge.com/minecraft/mc-mods/not-enough-crashes
	- https://github.com/NatanFudge/not-enough-crashes
	- https://modrinth.com/mod/notenoughcrashes


- Prospector and their "Mod Menu" mod (CurseForge + GitHub + Modrinth download links):
	- https://www.curseforge.com/minecraft/mc-mods/mod-menu
	- https://github.com/prospector/ModMenu
	- https://modrinth.com/mod/modmenu


- rdvdev2 and their "Disable Custom Worlds Advice" (CurseForge + GitHub + Modrinth download links):
	- https://www.curseforge.com/minecraft/mc-mods/fabric-disable-custom-worlds-advice
	- https://github.com/rdvdev2/DisableCustomWorldsAdvice
	- https://modrinth.com/mod/dcwa


- kverti and their "Colormatic" mod (CurseForge + GitHub + Modrinth download links):
	- https://www.curseforge.com/minecraft/mc-mods/colormatic
	- https://github.com/kverti/colormatic
	- https://modrinth.com/mod/colormatic


- modmuss50, sfPlayer1 and their "Fabric API" library mod (CurseForge + GitHub + Modrinth download links):
	- https://www.curseforge.com/minecraft/mc-mods/fabric-api
	- https://github.com/FabricMC/fabric
	- https://modrinth.com/mod/fabric-api


- CaelTheColher and their "Capes" mod (CurseForge + GitHub download links):
	- https://www.curseforge.com/minecraft/mc-mods/capes
	- https://github.com/CaelTheColher/Capes


- TeamMidnightDust and their "Custom Splash Screen" mod (CurseForge + GitHub + Modrinth download links):
	- https://www.curseforge.com/minecraft/mc-mods/custom-splash-screen
	- https://github.com/TeamMidnightDust/CustomSplashScreen
	- https://modrinth.com/mod/custom-splash-screen


- LogicalGeekBoy and their "LogicalZoom" mod (CurseForge + GitHub download links):
	- https://www.curseforge.com/minecraft/mc-mods/logical-zoom
	- https://github.com/LogicalGeekBoy/logical_zoom


- neekhan and their "Old Animations" mod (CurseForge + GitHub + Modrinth download links):
	- https://www.curseforge.com/minecraft/mc-mods/old-animations
	- https://github.com/existentially/old-animations
	- https://modrinth.com/mod/old-animations


- Charles445 and their "Damage Tilt" mod (CurseForge + GitHub download links):
	- https://www.curseforge.com/minecraft/mc-mods/damage-tilt
	- https://github.com/Charles445/DamageTilt


- FabricMC and their "Fabric Fabric Language Kotlin" library mod (CurseForge + GitHub + Modrinth download links):
	- https://www.curseforge.com/minecraft/mc-mods/fabric-language-kotlin
	- https://github.com/FabricMC/fabric-language-kotlin
	- https://modrinth.com/mod/fabric-language-kotlin


- Tfarcenim and their "Fast Furnace" mod (CurseForge + GitHub download links):
	- https://www.curseforge.com/minecraft/mc-mods/fast-furnace-for-fabric
	- https://github.com/Tfarcenim/FabricFastFurnace


- Lortseam and their "CompleteConfig" library mod (CurseForge + GitLab + Modrinth download links):
	- https://www.curseforge.com/minecraft/mc-mods/completeconfig
	- https://gitlab.com/Lortseam/completeconfig
	- https://modrinth.com/mod/completeconfig


- shedaniel and their "Cloth Config API" mod (CurseForge + GitHub download links):
	- https://www.curseforge.com/minecraft/mc-mods/cloth-config
	- https://github.com/shedaniel/cloth-config


- LambdAurora and their "LambDynamicLights" mod (CurseForge + GitHub + Modrinth download links):
	- https://www.curseforge.com/minecraft/mc-mods/lambdynamiclights
	- https://github.com/LambdAurora/LambDynamicLights
	- https://modrinth.com/mod/lambdynamiclights


- malte0811 and their "FerriteCore" mod (CurseForge + GitHub + Modrinth download links):
	- https://www.curseforge.com/minecraft/mc-mods/ferritecore-fabric
	- https://github.com/malte0811/FerriteCore
	- https://www.modrinth.com/mod/ferrite-core


- tr9zw and their "EntityCulling" mod (CurseForge + GitHub download links):
	- https://www.curseforge.com/minecraft/mc-mods/entityculling
	- https://github.com/tr7zw/EntityCulling


- ramidzkh and their "Fabrishot" mod (CurseForge + GitHub + Modrinth download links):
	- https://www.curseforge.com/minecraft/mc-mods/fabrishot
	- https://github.com/ramidzkh/fabrishot
	- https://www.modrinth.com/mod/fabrishot


- Jerozgen and their "Language Reload" mod (CurseForge + GitHub + Modrinth download links):
	- https://www.curseforge.com/minecraft/mc-mods/language-reload
	- https://github.com/Jerozgen/LanguageReload
	- https://www.modrinth.com/mod/language-reload
	

- UltimateBoomer and their following mods:

	"NoFade" mod (CurseForge + GitHub + Modrinth download links):
	- https://www.curseforge.com/minecraft/mc-mods/no-fade
	- https://github.com/UltimateBoomer/mc-no-fade
	- https://www.modrinth.com/mod/no-fade

	"Smooth Boot" mod (CurseForge + GitHub + Modrinth download links):
	- https://www.curseforge.com/minecraft/mc-mods/smooth-boot
	- https://github.com/UltimateBoomer/mc-smoothboot
	- https://www.modrinth.com/mod/smoothboot-fabric


- TecnaGamer and their "Old Walking Animation" mod (CurseForge + GitLab + Modrinth download links):
	- https://www.curseforge.com/minecraft/mc-mods/old-walking-animation
	- https://gitlab.com/TecnaGamer/OldWalkingAnimation
	- https://www.modrinth.com/mod/old-walking-animation
	

- FakeDomi and their "FastChest" mod (CurseForge + GitHub download links):
	- https://www.curseforge.com/minecraft/mc-mods/fastchest
	- https://github.com/FakeDomi/FastChest
	

- kyrptonaught and their "ToolTipFix" mod (CurseForge + GitHub download links):
	- https://www.curseforge.com/minecraft/mc-mods/tooltipfix
	- https://github.com/kyrptonaught/tooltipfix


-  unascribed and their "Fabrication" mod (CurseForge + GitHub download links):
	- https://www.curseforge.com/minecraft/mc-mods/fabrication
	- https://github.com/unascribed/Fabrication


I wish you good playtime, and see you someday else.
~ Flov aka MrFlov aka Flov74

##### Post scriptum:
Be warned I have NO knowledge in mod coding and so on, so if the game crashes because of some mod conflict or outdated version, you may check it out first. Try out disabling every mod (without loading any of your saves) and re-enable them one by one, until the game crashes. If it is a resourcepack you might switch the resourcepack order priority, or disable all of them, re-enable all of them one by one until the visual/sound occurs.
**Once you've earned all those informations, you might consider reporting it to me whether it is resourcepack-related or directly to the mod developer if it is mod-related.**
