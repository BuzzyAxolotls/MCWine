
![MCWine Icon](https://i.imgur.com/sykJqfG.png)
# MCWine
MCWine is a fabric-based modpack designed to bring better performance, brand new fixes and a compatibility system to allow players to connect to older servers out of the box.

### Installing this modpack ([Official/Vanilla Method](https://github.com/Kichura/MCWine/tree/Standard))

Download MCWine as ZIP by navigating to the "Code" button and then pressing "Download ZIP" from there. Then you will be required to drop the main folder (With folder containing it's files such as mods and whatnot) inside that ZIP to your minecraft's versions folder. After this you must reload your minecraft launcher to make a new profile by changing the game directory to the extracted version folder and then changing the version to the modpack itself.

### Installing this modpack ([MultiMC Method](https://github.com/Kichura/MCWine/tree/MultiMC))

Download MCWine as ZIP by navigating to the "Code" button and then pressing "Download ZIP" from there. After this you must open up your MultiMC launcher -> Click on "Add Instance" and import the MCWine-MultiMC ZIP to your MultiMC instance and press OK to confirm the changes.

### Recommended Java Version

It is recommended that you use [AdoptOpenJDK with HotSpot](https://adoptopenjdk.net/?variant=openjdk11&jvmVariant=hotspot) to allow minecraft to make use of the Shenandoah Garbage Collector. For JVM Arguments it is recommended that you use: ```-Xmx3G -XX:+UnlockExperimentalVMOptions -XX:+UseShenandoahGC -XX:+DisableExplicitGC``` as your arguments instead of default (You can change the RAM of ```-Xmx3G``` value if you want more RAM or less to be used, But depends on your computer's hardware) for better results as the Z garbage collector (ZGC) is considered to be memory-hungry in some conditions.

### Alternate MCWine branch

If you believe Sodium or ViaFabric does not work out properly on your computer, Then you can try to fall back to the [Alternate Branch](https://github.com/Kichura/MCWine/tree/Alternate) in order to make use of Canvas + MultiConnect instead. The method of this branch should be identical like the Vanilla method, But if you use MultiMC then you can try this [Alternate-MultiMC branch](https://github.com/Kichura/MCWine/tree/Alternate-MultiMC) instead.

### The following mods are owned by (Using original names with URLs instead):

- [Audio-Reloader (Aka Reload Audio Driver)](https://www.curseforge.com/minecraft/mc-mods/reload-audio-driver-fabric) - **CJMinecraft101**, **JayJay1989BE**,
- [Better-Grass (Aka LambdaBetterGrass)](https://www.curseforge.com/minecraft/mc-mods/lambdabettergrass) - **LambdAurora**,
- [BrandPacket](https://www.curseforge.com/minecraft/mc-mods/brandpacket) - **liachmodded**,
- [Canvas](https://github.com/grondag/canvas) - **grondag**, 
- [Fabric-API](https://www.curseforge.com/minecraft/mc-mods/fabric-api) - **asiekierka**, **sfPlayer1**, **modmuss50**,
- [Fabric-SmallTweaks (Aka Boring Tweaks)](https://www.curseforge.com/minecraft/mc-mods/boring-tweaks) - **boredomh1**,
- [Fix-Advancements (Aka Advancements Debug)](https://www.curseforge.com/minecraft/mc-mods/advancements-debug) - **thetechnici4n**,
- [Fix-ChatPosition (Aka Chat Up!)](https://www.curseforge.com/minecraft/mc-mods/chat-up) - **gnembon**,
- [Fix-ChestAnimation (Aka Chest Latch Fixer)](https://www.curseforge.com/minecraft/mc-mods/chest-latch-fixer) - **ExtraCrafTX**,
- [Fix-ItemModels (Aka Item Model Fix)](https://www.curseforge.com/minecraft/mc-mods/item-model-fix) - **Pepper_Bell**,
- [Fix-Retina (Aka RetiNO)](https://www.curseforge.com/minecraft/mc-mods/retino) - **juliand665**,
- [Fix-SkyColor (Aka Clear Skies)](https://www.curseforge.com/minecraft/mc-mods/clear-skies) - **grondagthebarbarian**,
- [Fix-ToolTips (Aka ToolTipFix)](https://www.curseforge.com/minecraft/mc-mods/tooltipfix) - **Kyrptonaught**,
- [Lithium](https://www.curseforge.com/minecraft/mc-mods/lithium) - **jellysquid_**,
- [Persist-Sneaking (Aka Sneaky Screens)](https://www.curseforge.com/minecraft/mc-mods/sneaky-screens) - **haykam**,
- [Phosphor](https://www.curseforge.com/minecraft/mc-mods/phosphor) - **jellysquid_**,
- [Tweakeroo](https://www.curseforge.com/minecraft/mc-mods/tweakeroo) - **masady, CFGrafanaStats**,
- [Vanilla-Branding (Aka fabric-branding)](https://github.com/LoganDark/fabric-branding) - **LoganDark**,
- [ViaFabric](https://www.curseforge.com/minecraft/mc-mods/viafabric) - **creeper12312332, KennyTVN**,
- [XLPackets](https://www.curseforge.com/minecraft/mc-mods/xl-packets-fabric) - **tfarecnim**,
- [Zoom (Aka Ok Zoomer)](https://www.curseforge.com/minecraft/mc-mods/ok-zoomer) - **boredomh1**,

- Modpack creator of MCWine - [Kichura](https://github.com/Kichura/MCWine).

### Additional thanks to

- LoganDark for telling me how to [resolve](https://github.com/LoganDark/fabric-branding/issues/1) the version string issue for "vanilla" context in F3 screen,  
- MrMangoHands for helping out with sharing the [lithium configuration codes](https://github.com/jellysquid3/lithium-fabric/blob/1.16.x/dev/src/main/java/me/jellysquid/mods/lithium/common/config/LithiumConfig.java),
- [Vanilla Tweaks](https://vanillatweaks.net/picker/resource-packs) for making the "Default+" resource pack possible.


### Found a bug/issue via MCWine (Mods only)?

Please contact the original authors at github or their discord servers for more details instead of [me](https://github.com/Kichura) as i do NOT own any of the following mods as said above.

### License

MCWine is licensed under GNU LGPLv3, a free and open-source license. For more information, please see the [license file](https://github.com/Kichura/MCWine/blob/Alternate/LICENSE).
