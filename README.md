# CloudMaker

## [FACT](http://fact.co.uk) minecraft server for Teaching and Engagement through social design and game culture frameworks

For Minecraft PC client version `1.7.9` 

![CloudMaker](https://github.com/cheapjack/cheapjack.github.io/blob/master/tumblr_files/Cloudmaker.png)

###Quickstart

Go to `Add Server` and enter a name for the server like `CloudMaker` the address `mc.fact.co.uk:25568`
**Make sure you are running client in version `1.7.9`**

On spawn you will be part of the `Default` user group outside a map of [FACT](http://fact.co.uk/). You can build pretty much anything in Creative mode as you explore the worlds via the FACT gallery entrances but PVP, lava fire, TNT ignition are banned I'm afraid. You cannot build or destroy blocks in the building but outside and in other un-protected areas build what you want. `World` is the main experimental world where all the Raspberry Juice magic happens and you can get there through the gallery 1 opening on the left..

Enter lifts to teleport to other floors (be careful not to walk back into them by mistake reversing out helps), get a drink in the bar and enter the gallery spaces to jump to other worlds.
You can look at the [server `dynmap` here](http://mc.fact.co.uk:8124)

###Background

CloudMaker and [The Minecraft Of Things](http://minecraftofthings.tumblr.com) sprang from research with [FACT](http://fact.co.uk/), [Dr Mark Wright](https://twitter.com/dr_mark_wright), [Adrian McEwen](http://www.mcqn.com/) and Paul Harter of [PrintCraft](http://www.printcraft.org/) funded by [IT as a Utility (ITaaU) Network](http://www.itutility.ac.uk) for the [CloudMaker](http://www.fact.co.uk/projects/cloudmaker-making-minecraft-real.aspx) project

Find out more in the [project video here](https://vimeo.com/92258008)

###Research Outputs and Spin-Outs

![rfcraftpi](https://cloud.githubusercontent.com/assets/128456/11501525/b5ac718a-982c-11e5-957e-e393b6b7c2ae.png)

CloudMaker has resulted in numerous outputs documented [here](http://cheapjack.github.io/EverythingMinecraft.html) on Ross Dalziel's AKA @cheapjack website and resulting in a range of spun out repos and research projects that use the CloudMaker server and build and extend the ITaaU research.

We are currently packaging up CloudMaker and all its 'deployable' outputs alongside [Dr Mark Wright](https://twitter.com/dr_mark_wright) writing up a paper on the project.

This will lead to releasing some open-source hardware and software into the Minecraft Education Community and wider Educator landscape.

 * RF-Craft - Repo to follow 
  * Open hardware (mostly) Radio messaging system using the unlicensed frequency 868MHz designed by technician in residence at [DoESLiverpool](http://doesliverpool.com) [DefProc](http://www.deferredprocrastination.co.uk/) RF-Craft is a prototype Raspberry Pi [HAT](https://github.com/raspberrypi/hats) (Hardware Attached on Top) and arduino clone to send `mcpi` API  commands to a minecraft server and especially the [CloudMaker](https://github.com/cheapjack/CloudMaker) server
 * Button-craft - Repo to follow
  * Open Hardware arduino buttons with onboard sensor inputs to make things happer wirelessly or wired on a minecraft server
 * [StasisCraft](https://github.com/cheapjack/StasisCraft)
  * CloudMaker resources for Teaching and Engaging with KS4 HomeoStasis through Minecraft & Python
 * [MemoryCraft](https://github.com/cheapjack/MemoryCraft)
  * Exploring Memory through the Internet Of Things and MineCraft
 * [ShrimpCraft](https://github.com/cheapjack/ShrimpCraft)
  * Breadboard based Minecraft/Shrimping.It/Python sensor kits for the Internet of Things
 * [Minecraft Of Things](https://github.com/cheapjack/MoT)
  * Resources for Exploring The Internet of Things (IoT) with Minecraft 
 * MindCraft
  * Resources for connecting Minecraft with EEG headset raw data, using the NeuroSky Mindwave Mobile Headset 


###Wiki

Read the [CloudMakerWiki](https://github.com/cheapjack/CloudMaker/wiki) here

###Plugins & Features

You need Builder or Admin permissions to use most of the tools like WorldEdit etc. and generally you only get this if you're part of a FACT project at the moment. Leave messages on signs for `Ops` if you want to do something in particular and want to use CloudMaker to do it or raise an issue on github.

 * `mcpi` is an API for Minecraft Pi Edition, released under an MIT License and is maintained by Martin O'Hanlon's [Stuff About Code](http://www.stuffaboutcode.com/p/minecraft.html) project.
 * RaspberryJuice 1.3.2 enables the use of the `mcpi` API with an additional `server.py` moduleincluded.
 * Dynmap  [View the map](http://mc.fact.co.uk:8124)
 * Essentials [wiki](wiki.mc-ess.net)
 * WorldEdit
 * Multi-Verse [wiki](https://github.com/Multiverse/Multiverse-Core/wiki/basics)
 * Printcraft [Bukkit Plugin Page](http://dev.bukkit.org/bukkit-plugins/printbot/)
 * ScriptCraft [wiki](https://github.com/walterhiggins/ScriptCraft/blob/master/docs/YoungPersonsGuideToProgrammingMinecraft.md)

### Staying Safe

<img src="https://www.nspcc.org.uk/globalassets/for-go-live-images/o2-partnership/minecraft-cta-v4.png?width=400&mode=crop&anchor=middlecenter" width="400">

The NSPCC have this great [online guide](https://www.nspcc.org.uk/preventing-abuse/keeping-children-safe/online-safety/minecraft-a-parents-guide) for parents and carers and players if you have any concerns about online safety.

The internal WhitCraft server is white-listed while the public one is not, but all server logs are recorded. If you have any concerns please contact Steven Roper at the Whitworth Art Gallery or any staff member.

We cannot accept any liabilty for what may happen on these servers but will endeavour to block any inappropriate behaviour where possible and can ban players where necessary.


###Is This Open Source?

The project is essentially about data, code and hardware literacy in the context of social design and gaming. It's released under a permissive MIT License but not necessarily recursively; some elements are released under certain different terms and you will need follow back to source to see this.

CloudMaker follows the `spirit` of open source although some elements used may not **strictly** be `open-source`: 

 * Minecraft is not open source but has a large and healthy modding culture. In many ways this culture IS the game. You have to buy the game basically to play on servers. This project however is based on the use of [Minecraft Pi Edition](http://pi.minecraft.net/?page_id=14) which is free to download and use and initiated by Mojang but maintained by the Minecraft and [Raspberry Pi](http://elinux.org/RPi_Hub) community
 * `mcpi` is released under an MIT License and is maintained by Martin O'Hanlon's [Stuff About Code](http://www.stuffaboutcode.com/p/minecraft.html) project. 
