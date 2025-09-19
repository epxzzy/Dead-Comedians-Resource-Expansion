

## INTRODUCTION
Hello there! If you're here it means you wanna learn modding, and presumably don't know where to start.
We probably should start by talking about modding itself, so let's see a definition of it:

 	Modding- (verb) activity involving developing several mental illnesses while dealing with Mojang's s̶h̶i̶t̶a̶s̶s̶  lovely codebase
On a more serious note it basicly means

	Writing code that upon compilation adds or modifies some sort of content ingame

So what do you need to start modding? Simple : a computer and java knowledge. Since you're here I consider you have a decent computer or a laptop. But What about Java?

#### IMPORTANT NOTE
	 From here on out I will be mentioning various links and what they are for. If however you have read this already and just 
 	want the links you can find a condensed list of them right below
 <a href="https://epxzzy.github.io/Dead-Comedians-Resource-Expansion/Learning_java">Compiled Resource list</a>


### Learning Java

 Java is a coding language. It is what is used for coding Minecraft Java edition and modding it. In order to start modding you will need an understanding of Object Oriented Programing (OOP) and the Java language itself. While this list is not dedicated to learning java I have made a list of SOME Java learning resources. However any way of learning the Java concepts mentioned above will do.

#### IMPORTANT NOTE
	 While it is easy to think that you can just skip learning Java, as many have did. 
	 More often than not you will find yourself in a lot of trouble, not knowing what is going on in front of you especially if you have
  	no prior coding experience. 
	 A solid understanding of the language also allows for you to create more optimised code and be able to both evolve faster on 
 	your journey and get into more difficult topics with a lot more ease. 
	 So do yourself a favour and don't cut corners, especially now, at the start!


  - [Codecademy](https://www.codecademy.com/catalog/language/java?g_network=g&g_productchannel=&g_adid=624951457630&g_locinterest=&g_keyword=codecademy%20java&g_acctid=243-039-7011&g_adtype=&g_keywordid=kwd-327295696446&g_ifcreative=&g_campaign=account&g_locphysical=9197713&g_adgroupid=128133970548&g_productid=&g_source={sourceid}&g_merchantid=&g_placement=&g_partition=&g_campaignid=1726903838&g_ifproduct=&utm_id=t_kwd-327295696446:ag_128133970548:cp_1726903838:n_g:d_c&utm_source=google&utm_medium=paid-search&utm_term=codecademy%20java&utm_campaign=INTL_Brand_Exact&utm_content=624951457630&g_adtype=search&g_acctid=243-039-7011&gad_source=1&gclid=CjwKCAjwqre1BhAqEiwA7g9Qhr4S7rnr6lNNym9Lu3hyXKpa1za-ZjNhoCIY6r0fIb4r39gV99_k4xoChZ8QAvD_BwE)
  - [KaupenJoe's Java series](https://www.youtube.com/watch?v=G1ifRRtJm7w&list=PLKGarocXCE1Egp6soRNlflWJWc44sau40&pp=iAQB)
   A relatively short series that teaches you, basic java required for modding
- [SoloLearn](https://www.sololearn.com/en/learn/courses/java-introduction)
   This is how I learned java among other methods such as books
- [FreeCodeCamp](https://www.freecodecamp.org/news/learn-java-free-java-courses-for-beginners/)
   FreeCodeCamp is a non-profit organizaation that allows you to learn many coding languages, pretty great in general
- [JetBrains Academy (free online course*)](https://www.jetbrains.com/academy)
- [Codeacademy (free online course)*](https://www.codecademy.com/learn/learn-java)
- [University of Helsinki (free online course)*](https://java-programming.mooc.fi/)
- [Basic Java Tutorials*](https://docs.oracle.com/javase/tutorial)
- [Intorduction to Programming using Java by David J. Eck (free online textbook)*](http://math.hws.edu/javanotes)



## MODDING
### Choosing a modloader

 Modloaders are tools that help players install and manage mods. But for developers modloaders are an API or a framework which allow us to add content into the game. Choosing the appropriate modloader affects your modding experience, your target audience and of course the amount of downloads you will have if you publish your mod. So what are our contestants? **Fabric** and **Forge** . Pretty much, there are other ones, but nobody uses them anymore, and **Forge** also has the **Neoforge** Flavour but I'll explain that in a bit. For now the jist of it is this: 
 
  **Fabric** is very light weight, which you think would make it better than **Forge**, but the reason **Forge** is not as light weight is because it is more powerfull, meaning it makes it more accessible for the developer to do more complex things, as opposed to **Fabric** where you can do those same things but it will be a lot more difficult. 
  
 There's also the afore mentioned target audience, **Fabric** usually has more vanilla+/ vanilla friendly mods, mainly consisting of tweaks, QoL mods or optimization mods. **Forge** on the other side , due to its more powerful nature usually hosts more content focused mods.

 Now there's also that third option I mentioned: **Neforge**. **Neoforge** is a fork of the **Forge** mod loader maintained by a separate group, created after some controversies relating to the Forge team, I will not get into detail as it is beyond the scope of this website. Where **Neoforge** strives is performance, while being as powerful as **Forge**, it is more optimised and runs better. There is one downside to it. Almost nobody uses **Neoforge** in versions prior to Minecraft 1.21. It is usually replaced by **Forge**, this also applies the other way around where **Forge** gets replaced by **Neo**(short for Neoforge ofc) after 1.21.

This swiftly brings us to the problem of choosing a Minecraft version to mod. While technically you can mod any version you want , there's more optimal versions. These are often refered to as modding versions. And usually encompass: 1.16, 1.18.2, 1.20.1 and 1.21.1, with most people resorting to either of the last 2. Now you may ask "Why not always update with the newest version?". The answer is, it's more trouble than it's worth, unless ALL developers update to newer versions, most people don't have a reason to move to newer versions. Every update the codebase changes, no matter the modloader, making especially big mods hard to bring up to date, especially with Minecraft's new drop-based update system which makes updates come at a much higher rate. So most people just choose one of these versions, and only update when a new "modding version appears", while players rely on mods that backport features from newer versions to the current modding versions.

#### TL;DR:
Modloaders:
- **Fabric**: light weight, great for vanilla friendly mods, optimization mods, or just feature tweaks
- **Forge**: not as optimised, a lot more powerfull, great for content focused mods used up to 1.21 generally
- **Neoforge**: as powerfull as **Forge**, more optimised, but used generally only from 1.21.1 and up

Versions:
- 1.16.x: Not gonna lie there is no advantage for choosing this
- 1.18.2: Same here
- 1.20.1: A lot of **Forge** mods are here, same for **Fabric**
- 1.21.1: A lot more recent, but generally dominated by **Neoforge** and very few **Fabric**


#### IMPORTANT NOTE

	 These are not hard rules, there's other modloader's like Quilt, but they are not used as much. Same applies for versions,
 	you can mod whatever version you wish, I just present you the ones that are used more often, aka that YOU and OTHERS will download 
    more often, and usually have more documentation as a result of that!

#### IMPORTANT NOTE

 	No matter the modloader you are using make sure you look at vanilla code, most of the time you can find something similar to what 
  	you need in game. You can also look at other people's code, while obviously 
   		A. understanding what the code does and how it works, not just copy pasting,
	 and 
  		B. respecting the license of the repository


### Neoforge
 Great so you chose Neoforge as your modloader of choice. Your main friend's will be:

- [The NeoForge Wiki](https://docs.neoforged.net/docs/gettingstarted/)
  	The official Neoforge Documentation. This will take you through all the steps to starting modding. Even generating the project. And a lot more, however it only covers SOME topics. Also covers pretty much every version of Minecraft Neo works on.
  
- [McJTY's tutorials, NeoForge 1.20.4](https://www.mcjty.eu/docs/1.20.4_neo/)
  While not as in depth, may have some content the NeoForge Wiki, for example some pretty competent explanations of render code at a begginer level. Only for 1.20.4 however. (Concepts usually transfer however so, while code can't just be copy pasting , you should still learn a thing or two from it)

 - [Kaupenjoe's Tutorials, NeoForge 1.21.X](https://www.youtube.com/watch?v=yG-oJPR_40w&list=PLKGarocXCE1G6CQOoiYdMVx-E1d9F_itF)
   You will notice KaupenJoe is a recurring reference here, that is for a good reason: He is one of the best and only Minecraft modding edutainers on Youtube. This playlist covers multiple versions starting with 1.21.1 and going up.

 - [Official NeoForge Discord](https://discord.gg/neoforged)
	Not much to say, if you need help understanding anything, the folks over there should be able to help. I find this server particularly helpful myself.

 - Anything else mentioned in the **MISCELLANOUS** category here or in the [Compiled Resource List](https://github.com/epxzzy/Dead-Comedians-Resource-Expansion/blob/main/Compiled_Resource_List.md)
   

### Forge
Since the Forge modloader has existed for longer, there's more resources you can go for:

- [Forge wiki](https://docs.minecraftforge.net/en/1.21.x/)
  Official documentation for Forge, includes versions : 1.19.x, 1.20.1, 1.20.x , 1.21.x and even a bit about ForgeGradle for the advanced and interested!
  
- [Forge Community wiki](https://forge.gemwire.uk/wiki/Main_Page)
  Documentation mantained by the community, meaning anyone can contribute to it, a bit more extensive than the official doc, but only for versions 1.16, 1.17, 1.18 and 1.19.

- [moddingtutorials.org](https://moddingtutorials.org/)
  While only being used for obscure versions, 1.16.5, 1.18.2, 1.19.2, and 1.19.3. I'm placing this here for academic honesty and who knows maybe someone may need it, so its here.


- [McJTY's knowledgebase](https://www.mcjty.eu/docs/intro):
  Same as above, it's not the best, not the worst, but may have useful info. It also covers versions 1.12, 1.14, 1.15, 1.16, 1.17, 1.18, 1.19, 1.19.3, 1.20.

- Kaupenjoe's tutorial playlist:
	<details>
  		<summary>versions</summary>
		<ul>
			<li><a href="https://www.youtube.com/watch?v=eFofdJ1BYYs&list=PLKGarocXCE1GspJBXQEGuhazihZCSSLmK">1.21.X forge</a></li>
  			<li><a href="https://www.youtube.com/watch?v=55qUIf3GMss&list=PLKGarocXCE1H9Y21-pxjt5Pt8bW14twa-">1.20.X forge</a></li>
			<li><a href="https://www.youtube.com/watch?v=p-mp91zrlqo&list=PLKGarocXCE1FlLU16RRfaS0bcabHDSvLA">1.19.3 forge</a></li>
			<li><a href="https://www.youtube.com/watch?v=LpoSy091wYI&list=PLKGarocXCE1HrC60yuTNTGRoZc6hf5Uvl">1.19 forge</a></li>
			<li>And for 1.18, KaupenJoe has multiple playlists on <a href="https://www.youtube.com/@ModdingByKaupenjoe/playlists">his channel</a></li>
		</ul>
  
  	</details>

  - [Cy4's tutorial playlist (1.16) ](https://www.youtube.com/watch?v=benUZaQU-6Y&list=PLlbkaeFHn13HQlW5Pb7Gf-xLJoAlfVbNU)
	In my honest opinion he uses pretty bad coding conventions(or at least did when I last checked) and uses Eclipse as an IDE (Intellij being what most use as it is best for this), but I'm putting this here for academic honesty.

  - [Cy4's tutorial playlist (1.18) ](https://www.youtube.com/watch?v=xRXWa5HRAxU&list=PLlbkaeFHn13Hw_Y-Rs2TgBYlpS2RQ5uEA)
	Same as above

 - Anything else mentioned in the **MISCELLANOUS** category here or in the [Compiled Resource List](https://github.com/epxzzy/Dead-Comedians-Resource-Expansion/blob/main/Compiled_Resource_List.md)


### Fabric
If you choose Fabric then you should look at:

- [Fabric Wiki](https://docs.fabricmc.net/develop/):
  	Fabric's official developer wiki.

- [Mod Template Generator](https://fabricmc.net/develop/template/):
  	Fabric's official template generator. Creates an empty mod that is ready to run almost instantly.

- [Turty Wurty's tutorial playlist](https://www.youtube.com/playlist?list=PLaevjqy3XufZ5qFgfd-XnNgoiXynSZLZy):
        Getting started tutorial for Fabric 1.21, I do recommend Kaupenjoe a bit more, but that's up to taste

- Kaupenjoe's tutorial playlist:
	<details>
  		<summary>versions</summary>
		<ul>
  			<li><a href="https://www.youtube.com/playlist?list=PLKGarocXCE1EO43Dlf5JGh7Yk-kRAXUEJ">1.20.X Fabric</a></li>
			<li><a href="https://www.youtube.com/playlist?list=PLKGarocXCE1EMYzuBUTYjHnFeBrRFbesk">1.19.3 Fabric</a></li>
			<li><a href="https://www.youtube.com/playlist?list=PLKGarocXCE1EeLZggaXPJaARxnAbUD8Y_">1.19 Fabric</a></li>
			<li>And for 1.18, KaupenJoe has multiple playlists on <a href="https://www.youtube.com/@ModdingByKaupenjoe/playlists">his channel</a></li>
		</ul>
  
  	</details>


- [Fabric Project, official server](https://discord.com/invite/v6v4pMv)
     Official Fabric server, usually active.

 - Anything else mentioned in the **MISCELLANOUS** category here or in the [Compiled Resource List](https://github.com/epxzzy/Dead-Comedians-Resource-Expansion/blob/main/Compiled_Resource_List.md)



### General

After all of that here's some links that all of you could use (probably) no matter the version and modloader:

- Vanilla code:
	Just read the vanilla code, chances are what you want to create already exists in-game.


Mixins are a complex topic that may require a lot of explanation. They're purpose, in a surface level explanation is to overwrite vanilla code. However in most cases events are more desirable since having multiple mixins in the same place may break while having multiple events in the same place from different mods should not cause problems.

  <li><details>
  			<summary>Mixins</summary>
			<ul>
  				<li><a href="https://github.com/SpongePowered/Mixin/wiki">Official mixins</a></li>
					Official mixin wiki, explains mixins from the ground up
				<li><a href="https://youtu.be/HQUkWjMWTik?si=Imrb210v_6h3R1YT">NoNumberMan's mixin tutorial</a></li>
					While a bit outdated should still be helpfull, make sure to read the video's descriptions!
  					Also Despite the title saying Fabric/Forge, mixins are universal for all modloaders so NeoForge is fine as well
				<li><a href="https://github.com/2xsaiko/mixin-cheatsheet">Mixin Cheatsheet</a></li>
					More concise information, if you're learning on the go or just trying to refresh your memory
				<li><a href="https://www.youtube.com/watch?v=U7j4bl_UAII">Kaupenjoe's Mixin Tutorial</a></li>
			 		Kaupenjoe's tutorial on mixins, while on an older version it does help with understanding basics
			</ul>
  
    </details></li>

- [Linkie](https://linkie.shedaniel.dev/mappings?namespace=mojang_srg&version=1.20.1&search=addAdditionalSaveData&translateMode=ns&translateAs=yarn):
  	modloader mappings translator.
  
- [Mc Assets](https://mcasset.cloud/latest/)
    Obtain assets from the game

- [Data Generators](https://misode.github.io)
    Generate data hassle free. These include:
	- Loot Tables
  	- Advancements
	- Worldgen
	- And many, many more


### Discord Server
- [Kaupenjoe's Server](https://discord.gg/kaupenjoe)
     They can help with more specific problems, pretty great people

- [Modded Mincraft Server](https://discord.gg/moddedmc)
      Again specific problems, usually active also can help with various modloaders

    




# *Credit to doctor4t's server
## Credit to epxzzy for help with repo, Diemant for 2/4 mixin tutorials and providing the doctor4t recomandations


