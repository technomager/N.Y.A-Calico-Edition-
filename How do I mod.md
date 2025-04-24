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

