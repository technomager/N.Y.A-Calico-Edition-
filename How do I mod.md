# Okay I have all of these mods and stuff, how do I actually put them in the list????

# How to…
Before getting started, it's best to learn the right way to mod. Skyrim is one of the few games where you can mod almost anything inside the game, but it's also one where it's complicated to get started. Even more when you start with a list of +1000 mods and you have no experience of how to mod it . I'll give you some advice that comes to mind, but it's also up to you and your own responsibility to search and learn how things work. I'm here to help and assist, but as soon as you start modding, know that you're on your own. That’s a reason why I’m going to give you some, I hope, useful advice. 


## Mod Organizer 2

> MO2 is a great tool, and I'll let you discover all its features yourself. The most important thing to know is how panels work and how you're going to manage all your additions.

![{0DC74B6E-62AB-4454-8098-B257F014F823}](https://github.com/user-attachments/assets/102e1b51-34bd-4f8c-b2d6-1ef62f3d34a4)

### Left Panel (Assets)
- The left panel is where you place your downloaded mods - no need to extract them, MO2 takes care of that for you. You can simply drag-and-drop your mod into the left-hand panel, or click the first button on the left. 
- The left panel is also there to manage conflicts between your assets or scripts, all the file types that the game will use. If one script conflicts with another, the one placed last will win! It's very important to take this into account, because the wrong order can cause you problems! (sometimes benign, of course)
- MO2 tells you which mods are in conflict, so you can double-click on them or just click on them to see which mods are involved.
- Create your own separators to manage your own additions, if you want to add more creature mods, then, place your mods below where Vermillion added them for NYA.


![{FB21825E-04FA-432C-95C6-15272C70F91A}](https://github.com/user-attachments/assets/27e32723-8399-44c1-b2b8-8a673ad50044)


### Right Panel (Plugins)
- The right panel is used to manage the order of your plugins of your mods (files with .esl, .esp or .esm). It's very important, and causes most of the problems for people trying to edit the list. Certain plugins should be placed at the very bottom (notably Papermaps and its patches or DBVO and EvanoraVoice or DynDOLOD and its Occlusion) because if a mod is placed further down than another, it means that it is "conflict-winner" for all mods that try to edit the same thing as it. If you have an addition that modifies a cell lower than Lux, it's very likely that it will edit the light system back to vanilla, overwriting Lux's modifications.
- The best way to place your additions is to place them above DBVO/EvanoraVoice and its patches. If you      want to know exactly, I suggest you take a look at my own plugin order . You will be sure that you’re not going to break anything from the major mods needing to be loaded at the very end (DBVO, PaperMaps, DynDOLOD, Occlusion, Synthesisits  Patches, …etc)
- You can easily know which mod, your plugin is ESPFE (ESL). You can see it when a plugin has a yellow dot as below : 
![{5172DD71-F83F-4B47-86E0-D2399378E6C7}](https://github.com/user-attachments/assets/8ef625be-3f0f-4af0-a47f-087cc8837802)


- Obviously, there's no mystery. To avoid supposing that a mod has no major conflict with a NYA mod or one of your additions, it's best for you to check. Sometimes it's difficult to know which mod conflicts with another, so you'll need to check with the SSEdit (XEdit) tool. For the additions in this document, you won't need it as I'll do it for you, but learn how to use it!


## XEdit (SSEdit)

> XEdit is a tool that lets you do an awful lot of things, and I'm not here to explain it all to you, but it can do a lot of magic! Learn at least the basic functions of XEdit - it's not complicated at all I promise! (lies)

### Remove Masters

Optional, but you can remove any mod from NYA if you know what you’re doing (I insist if you know what you’re doing !). However, some mods are linked to masters and will crash you if you don't make a "clean master" and remove all the entries. This is an XEdit feature and I invite you to read this article :   [- CLICK ME -](https://github.com/LivelyDismay/Learn-To-Mod/blob/main/lessons/Remove%20a%20Master.md)

### For This Guide That is All I Will Teach You
if you wish to explode your brain, [a full guide on xedit can be found here](https://tes5edit.github.io/docs/)

## Synthesis
- A lot in N.Y.A is attached to Synthesis patches. Mainly connected to Backgrounds, Face Patches and the dreaded RPG loot mod. When removing mods to make ESP space, you will see the caution symbol get a yellow exclaimation point.

  
![{9140631A-8AE7-4EE5-96D8-66CE4229BB16}](https://github.com/user-attachments/assets/8c91a9e3-3c67-4d09-98ff-d45881e8abd8)

![{6188242F-4E4C-459B-A78C-E9AA00754D64}](https://github.com/user-attachments/assets/44b79fe8-2233-4035-8849-8e28d1adef76)

Trying to Disable a large mod like There Is No Umbra, can lead to disasterous results as seen here, but using this we can go through what to do for each "required by"

### Required by what?
- **DynDOLOD.esp** -- STOP, Turn around, do not come back, if anything touches DynDOLOD do not mess with it, NYA's DynDOLOD install is a complex and nested mess and to mess with it can and will break everything
- **Patch.esp, ...Lux patch, any other .esp not listed here** -- Go to plugins and search for the bad patches and toggle them off
- **Occlusion.esp, NYA Custom Patch.esp** -- XEdit Removing Masters will be required to remove
- **Synthesis.esp, Synthesis_HPH_patch.esp, HalgariRPGLoot.esp** -- Move on to Synthesis instructions

## Actual Synthesis Tutorial
- We need to use Synthesis now. Click on “Launch N.Y.A Skyrim AE” at the top right and choose Synthesis as below. Then, run it 

 ![{39851D5A-2658-4EC3-A14E-F552BE19F06D}](https://github.com/user-attachments/assets/6d3a2145-7612-477f-910e-207b316c64f0)

![{D7FC9D17-9D99-4A8F-8962-155FB02A9FD7}](https://github.com/user-attachments/assets/63ba90c4-446b-4b37-b9fd-96d620b9fe18)

- When you open Synthesis everything will be selected, if the issue you are having only specifies "Synthesis.esp" and/or "Synthesis_HPH_Patch.esp" feel free to toggle off "Halgaris RPG Loot Patcher" in synthesis (make sure to toggle it back on in synthesis before you leave if you intend to enable the mod for your playthough)

![{346C3405-D615-4EDA-BB8D-1DA96E365C72}](https://github.com/user-attachments/assets/72cb9751-faf7-4a42-a581-b65b9a6b5b22)

- After you have made your selections click on the arrow at the bottom of the page that says "run" when you hover over it

![{C2180ECF-10EB-4DA9-BE22-2C8584EDDE0E}](https://github.com/user-attachments/assets/0ff629b7-9617-41c4-876c-41c1020fba70)

- Once it is finished patching you are all done! (to re-enable RPG Loot Patcher, hit the back arrow and toggle it on, then you can quit the app)

![{04E3B0B1-B0A3-4301-9EF4-2AB793563E19}](https://github.com/user-attachments/assets/5120b9b4-1d0b-4932-9d6a-30512cdd1064)


## Bodyslide (Armor)

> When you add armor mods, it works without any issue but you will need to use "BodySlide" to adjust the armor to the wearer’s body. Otherwise, you won't be able to see that a character has big boobies under her armor. You need to know that NYA Calico is using “3BA CBBE” (3BBB) so we need to grab an armor compatible with 3BA or at least find someone sharing the 3BA Bodyslide. Let me show you how to do that.

- First, we need to find good looking armor so we're going to pick up one I've added [Download here](https://www.sunjeongskyrimse.com/post/the-amazing-world-of-bikini-armors-remastered-6-0)
![{0DB55B19-E344-48A9-B67E-1286D3889DE9}](https://github.com/user-attachments/assets/e4a414d9-e7f8-4a6b-b1d5-8aea3154be49)
- Unfortunately, the armor is for CBBE but not for 3BA CBBE. Let's not give up hope and let’s take a look at the "Includes" section
![{36BCE6D3-E743-4DC5-8865-FC4D8B4986D4}](https://github.com/user-attachments/assets/d4787b01-0ed2-4e4a-951f-005c1f319cc7)

- Success! looks like it does work with 3BA!, so download it from one of the links at the top of the page
- Download both files and install them like usual. Try to rename them if you want to stay organized and also add the prefix [NoDelete] if you plan to update NYA. 

![{A0AF6E8B-C349-4E7B-9C60-0BA63C7C2815}](https://github.com/user-attachments/assets/27483828-d1e3-4116-be7e-f493714941a5)


> [!NOTE]
> If you find a armor you like, and it is not the right body type and its on nexus take a look at the "Requirements" section, under “Mods requiring this file”. if you are lucky, someone might share the 3BA Bodyslide for it. DO NOT PESTER AUTHORS TO MAKE YOU ONE

- We need to use bodyslide now. Click on “Launch N.Y.A Skyrim AE” at the top right and choose BodySlide 64x as below. Then, run it 

!![{8F52FB24-E7EB-4E52-ABAC-2E8FBDFADD5B}](https://github.com/user-attachments/assets/1b332076-e55b-4e6b-9c04-08000fee9542)

- When the BodySlide window opens, Click the hourglass to search the specific armor groups, look for “Tawoba Remastered [3BA]” (sometimes they’re tricky to find) and then click on the check mark to select all of them, then hit OK.

![{869C1620-C3F1-4404-9970-9D22CF8270BC}](https://github.com/user-attachments/assets/84c885e0-ad17-4fa4-9286-383f4bb20cfa)

![{037957F7-43EA-492D-90CA-CEF0A2CE8987}](https://github.com/user-attachments/assets/c4fd71a7-1bfd-40ce-96d7-04a8fb0aa335)


It should be selected by default but use “Zeroed Slider” as preset below Outfit/Body. **It’s very important.**

![{F03F3CF7-0D90-49EA-BEBE-3FC1E7997AF4}](https://github.com/user-attachments/assets/8579136d-3a8d-4a5b-95fb-eb530cbd0c80)


- Now it’s time to build the 3BA bodyslide, click on “Batch Build” at the bottom-left to build everything filtered (that’s why it’s important to filter, if not, everything will be selected). Check if the options are those you want and then hit "BUILD".

![{BB380D60-74C3-460B-BAE8-4375AE056392}](https://github.com/user-attachments/assets/19136aaa-d8d6-4a8c-ac69-86d2bc2780d2)

- Sometimes get a warning and we need to make a decision ! Sometimes, authors can provide several options for us (give them love). For some armors, we have to choose between multiple options. Also we have the choice with top only options. If you want to see the difference between a few types of armor, use the Outfit/body selector at the top of the page and select the armor you want to view, then click preview to get a gist of what it looks like, select what you want for each option!

![{8D2686E0-B5D8-4A84-A429-26CCDE0317C3}](https://github.com/user-attachments/assets/e5f9682a-2f3f-4f89-836d-43085f0e3f11)
> This is for BD's Armor Replacer (also in this list)

- It’s done, well done! You can close BodySlide and I would recommend you to check in game by using AddItem Menu (check your bag, you spawn with it). Sometimes you can get surprises.

### Final bodyslide tips
- Downloading BodySlide Presets doesn't need to be built. You can use them right away by pressing “O” in game.
- CBBE BodySlide can work but I've never succeeded in my case. If you want to learn more, you can learn how to convert CBBE to 3BA CBBE like [this tutorial](https://www.youtube.com/watch?v=Pa4O1bwY18Q).
- You can create a “BodySlide Output” folder to store all your files. I don’t do that but I think it’s nice to inform you. Google it.
- BodySlide is not only for sliding  armor to your body type. You can check The [BodySlide Nexus Page](https://www.nexusmods.com/skyrimspecialedition/mods/201)

## Pandora Behavior Engine
> Pandora is all about Animations, and is much, much better than the Skyrim Animation Tools of the past, like FNIS, or Nemesis. If you do <ins>**ANYTHING**</ins> to do with animations, even looking at it wrong sometimes, will result in everyone T-Posing to prevent this, you will need to run Pandora

- Before you even Run pandora, make sure to delete the "meshes" folder from "N.Y.A Pandora Output V1" before running, this can be found by searching on MO2 and "opening with explorer" or by going to NYA's install directory and searching for it 

![{7F6A218A-5AF5-48CE-BD7E-41F162B705C9}](https://github.com/user-attachments/assets/a24a8a54-5378-4fc8-b509-cfbeb2ee981e)


- To launch Pandora, you run it like all of the other programs so far, Click on "Launch N.Y.A Skyrim AE" and SCROLL DOWN until you fine "Pandora Behavior Engine+", and run it

![{02227051-A81A-4D92-A039-231931D86783}](https://github.com/user-attachments/assets/6b22aa9e-6988-47aa-b100-ff4006a9e51a)

![{7A8B9BDB-84C9-4BB6-8E17-039F11A4DD2C}](https://github.com/user-attachments/assets/7168ca13-395a-4300-84f2-c9bb4762c610)

- Once you get into the menu <ins> **ONLY HIT THE ARROW AT THE BOTTOM** </ins> all of the toggles on the top are set properly and messing with them can break everything.

![{5059E73F-4FC0-45A9-A765-E0453342FBA5}](https://github.com/user-attachments/assets/5ae0f8c7-a0d0-4b10-8809-c7c2e74519ae)

![{A87D629B-B645-4ECF-97D2-CF8D5E8FBB19}](https://github.com/user-attachments/assets/6525862d-f0b6-4599-90b2-dbf5eb951215)

> Yes it was that fast, personally I like to run Pandora twice its a bit of a superstition but no harm can come of it

- Once you see it finished you can exit the program, thats all you need to do!
  
## Extra Tips

### Organize Your Additions!
- Organize your own addition and respect the same order that Sky made (or just following what I did). You can create your own separator and do the same way as me. Place them as if your separators were mods or your can just right-click and choose where you want to move your separators.

![{636CF3CF-7798-42CD-AACD-1B923D28388F}](https://github.com/user-attachments/assets/78d5b40d-a219-4308-8744-129c50f89e0b)

### Make Backups!
- Make a backup of your left and right panel. If you mess with something, you can revert your change ! Do a backup when you think it’s needed. I do a backup each time I add another mod after testing when I’m sure that everything is good. 

![{F8392C11-1B8C-407D-9555-2A7CE580EE68}](https://github.com/user-attachments/assets/c8e8df05-adb5-443d-8bdc-962669172adf)

- When you know that you’re going to mess with a mod or with a patch like trying to ESL a mod, make a backup of your mod. If something is wrong, you will be able to revert your modifications. Now you can mess with everything without being scared that you will break your list.

### The ESP limit

Unfortunately, you can’t add as many mods as you want. If you don’t do some trick you’re going to reach the well known limit. The limit is fixed at 253 or 254 esp+esm (some people say it’s better to let it at 253), if you reach it, your game will be unplayable. So be sure to never exceed it ! 

To avoid this, you can ESL (ESPFE) your additions. However, not all mods can be ESL, but I'll specify which mod you can. If you'd like to know more, take a look at the XEdit section where I give you a great guide from LivelyDismay to do it yourself if you don't already know.

![{2B2CE594-CEC3-4851-9A84-3052FC278870}](https://github.com/user-attachments/assets/321f2b6b-07c4-4b16-90fd-64d53517e494)

> DO NOT LET ACTIVE ESMs + ESPs REACH 255!!!!


### Final Advice
- Finally, you don't need to know everything, just read what I've written to add the mods from this document. I've deliberately left out certain tools where they concern specific mods, like DynDOLOD. But once again, I strongly advise you to learn the basics of modding, you will be able to do a lot of things. Also, you need to make a new game any time you change mods.
