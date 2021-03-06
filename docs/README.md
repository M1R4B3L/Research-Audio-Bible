# Audio Bible

I am [Adrián Mirabel](https://www.linkedin.com/in/m1r4b3l/), Student of the [CITM](https://www.citm.upc.edu/ing/estudis/graus-videojocs/) Balchelor's Degree in Video Games by UPC at CITM. This content is genereated for the second year's subject Project 2, under supervision of lecturer [Ramon Santamaria](https://www.linkedin.com/in/raysan/).

All the audio examples used in this Research Project have copyright depending on the company they created them.
Nintendo, Wube Software, Bethesda Game Studios and	Crystal Dynamics.

# 1. Who is responsible for the creation of the Audio Bible?

The Audio Bible is a document created by the Audio Director and the Sound Designer; always maintaining a close collaboration with the director of the project, the art team, the design team and the programmers.
That collaboration is crucial, being the main problem in indie companies.
This document is designed to help the audio team, as well as the programmers who will need the document to implement the sound into the game. 
[Keith Ziza](http://keithzizza.com/) in one of his interviews said:

```markdown
Designers will want to absorb it, 
programmers will demand it, 
and producers, along with just anyone else who is involved on the project, 
will want to at least skim it. 
Whether it’s one page or one hundred, 
it should be as descriptive as it needs to be for you and for your development team. 
The end result, hopefully, is a harmonious one… working with and enhancing graphics, 
writing, game design, and the overall gaming experience. 
(Keith Ziza 2000).
```
So folloing [Keith Ziza](http://keithzizza.com/) description the Audio Bible should be created by the sound designer but sharem amoung all the group.

# 2. How it affects the creation of audio?
As I said before it’s a team effort with an attention to detail that puts the audio experience over the top. When you’re establishing your audio vision, make sure that you are taking the elements of Music, Sound-Design (Effects), Voice-Over, and Technology into account.  Each element has their subcomponents and everything needs to work together to make for the most cohesive experience.  If one element is neglected or “tacked-on”, it can throw your entire audio direction into disarray.

This is a list of parameters/questions you need to take into account while selecting/designing your audio.

## Audio Pillars

A brief description about a set of features that will be taken into account during the audiocreation, that define the game’s audio aesthetics. Extremely similar to the ones define in design and art.

## Music

**_How do you want to make the audience feel?:_** Description about the theme, Dark for suspense? What feeling you want to create to the audience

 - Feel powerfull like a viking [Dragonborn-Skyrim](https://www.youtube.com/watch?v=6fILxnBH1Tg) 
 
 ![skyrim](https://user-images.githubusercontent.com/45202028/82690523-ace78600-9c5c-11ea-92e5-928c32964d7b.jpg)

**_Situation:_** Is it a big bombastic orchestral for the main action or is it a minimalist score that creates more of an ambience?

 - Main Theme: [Mario Odyssey](https://www.youtube.com/watch?v=J4e4hnGEgpw)
 
 - Main Action: [Mario vs Bowser Mario Odyssey](https://www.youtube.com/watch?v=9_yTRGElgx4)
 
 ![mvb](https://user-images.githubusercontent.com/45202028/82690557-b83ab180-9c5c-11ea-8de1-ac2832329ef5.png)

**_Instrumentation:_** What instruments will be performing the themes that the designers have chosen. There’s a big difference between each instrument and the way it sounds; it definitely can change player’s feelings during the game.

## Effects

**_Ambience:_** How complex and layered is the world sound that is around the user?Are you on a sci-fi alien planet with moaning winds and twisting thunder crackling around in the skies above? Material?

  - [Zelda Ocean waves at night](https://www.youtube.com/watch?v=zGp8wxfWRkg)
  
  ![Ocean](https://user-images.githubusercontent.com/45202028/82690570-bffa5600-9c5c-11ea-8d6d-44e85733967e.PNG)

**_Player:_** Basic player action effect like running, jumping...

  - [Mario Jump effect](https://www.youtube.com/watch?v=ZrP-30MmpvM)
  
  ![mjump](https://user-images.githubusercontent.com/45202028/82690606-d30d2600-9c5c-11ea-969e-90fcd1597124.gif)

**_Entities:_** All the sound effects produced by the differents entities around the player. Will the player come across?
Are they small little bunnies? A Gigantic Boss? or a Plant?  

 - [Mario Coin](https://www.youtube.com/watch?v=qfx6yf8pux4)
 
 ![Coin](https://user-images.githubusercontent.com/45202028/82690616-d7394380-9c5c-11ea-924b-f66d7658ce40.gif)

 - [Factorio machines](https://www.youtube.com/watch?v=pttCl-7KoGI)

**_UI elements:_** You need some UI audio triggers for creating a more accessible and fancy to the user.

 - [Nintendo WII soud UI sound effects](https://www.youtube.com/watch?v=rMDW4jYuYAU)

## Voice Over

**_Style:_** This could range from age type, gender type, etc…Each voice has its own collection of frequencies and timbre qualities, so it’s good to know what sort of pool you’ll have.

  - Femine voice [Lara Croft](https://www.youtube.com/watch?v=zh80dvrDf7g) 
  
  ![lara](https://user-images.githubusercontent.com/45202028/82690645-e0c2ab80-9c5c-11ea-9b6b-fd623c664f94.jpg)


**_Visualizations:_** Tutorial dialog? Indications for the user?

**_Player/Creatures/Enemies:_** The player is going to have a voice, the enemies? The creatures are voice modifications?

  - Animalese [Animal Crossing voices](https://www.youtube.com/watch?v=YekLRkiIW4Y)
  
  ![talk](https://user-images.githubusercontent.com/45202028/82690766-1b2c4880-9c5d-11ea-9aa8-1a3b67359888.gif)

## Technology:

Technology is an important aspect; you need to consider whitch libraries, audio formats and audio management for the game you will be working in.

**Example**

In our case we are using SDL_Mixer.

Audio formats:

.OGG for Music.  ![ogg](https://user-images.githubusercontent.com/45202028/82651818-f617e580-9c1c-11ea-991e-2719bbe29b43.png)

.WAV for Effects.  ![wav](https://user-images.githubusercontent.com/45202028/82651844-fe702080-9c1c-11ea-84c5-434988a10a10.png)

We have Spatial Audio to control entities distance.


# 3. How to obtain game audio

Game audio can be obtained through differents ways.

## Your own Creation

Only recommended if you have some time to spent or a big team with a professional dedicated on it.

## Tools

**- Online Music maker:**

You have a free trial [Soundation](https://soundation.com/)

Premium [Soundtrap](https://www.soundtrap.com/musicmakers?lang=es)

**- Online Fx maker for .wav:**

[rFXGen](https://raylibtech.itch.io/rfxgen)

[Leshy SFMaker](https://www.leshylabs.com/apps/sfMaker/)

**Extras**

Animal Crossing voices generator [Animalese Generator](https://acedio.github.io/animalese.js/)


## Contract a Profesional

If you are not an expert and your time is limited contract a professional audio designer.

## Download from a Audio Library

The last option and the most used for starting/students in game developing. 
Remember the music should be royalty free.

[Itch.io](https://itch.io/soundtracks)

[Freesound](https://freesound.org/)

[NoiseForFun](https://www.noiseforfun.com/)

[PlayOnLoop](https://www.playonloop.com/royalty-free-music/)


# 4. Naming and Folder Organization

Organizating your audio is crucial for your group, the programmer have to know which audio should be used, at what time and how is it going to be applied in the game. 
A good naming and folder structe will make the aspects mentioned before easier to complete.

**Examples:**
This template will help organize the general audio.
If you want to be more specific you can create more folders.

![audio](https://user-images.githubusercontent.com/45202028/75965110-9edd6100-5ec8-11ea-8afb-adc1ee0e9a65.PNG)

![music](https://user-images.githubusercontent.com/45202028/75965603-54101900-5ec9-11ea-9bd0-71490981cafd.PNG)
![fx](https://user-images.githubusercontent.com/45202028/75965626-5c685400-5ec9-11ea-987e-9ede522287ff.PNG)

Audio naming should follow a convention and put in common to all the team.

Most recommended naming convention are:

**- Snake case: *music_audio***

**- Camel case: *musicAudio***

**- Pascal case: *MusicAudio***

## Real Games Example

**- The Binding of Isaac**

The folder organization is a bit messy, they follow a naming convention but whitespaces are not recommended. 

![issac_music](https://user-images.githubusercontent.com/45202028/82586621-25d0da00-9b98-11ea-90ac-d3bebb10b8b6.jpg)

**- Terraria**

It follows a naming convention in this case a combination between Pascal and Snake case. They don't have a folder organization.

![terraria](https://user-images.githubusercontent.com/45202028/82586636-2cf7e800-9b98-11ea-8e0d-c69ea84c2e43.jpg)


# 5. Audio Bible Example
[Ashlee McCarthy Audio Bible](https://ashleemccarthy.wordpress.com/2013/06/06/sound-design-document/)

# 6. Interesting conferences
[Jonathan Wayer](https://www.youtube.com/watch?v=7p9rqo2I_Hs)

[Bjørn Jacobsen](https://www.youtube.com/watch?v=HLOmk6ly_CE&t=829s)

# 7. References
[Asoundeffect Game Audio](https://www.asoundeffect.com/game-audio-design-document/)

[Guide by Zachary Quarles](http://zacharyquarles.com/blog/?p=518)

[Interview with Aram Shahbazians](https://professionalcomposers.com/sound-design-for-video-games/)

[Guide Lines](http://www.dreamquakestudios.com/ADD.html)

[Tips for Sound Desing](https://gameanalytics.com/blog/9-sound-design-tips-to-improve-your-games-audio.html)

[Evolution of audio](https://altagram.com/es/music-sound-design-video-games/)

[Book](https://books.google.es/books?id=gnw0Zb4St-wC&pg=PA89&lpg=PA89&dq=audio+design+document+(add)+responsable&source=bl&ots=4cmXkwxntF&sig=ACfU3U0viWwpUndyN551hSTlHPfxwWd2Iw&hl=es&sa=X&ved=2ahUKEwiIzqCw4P7nAhUL6OAKHWm9DrQQ6AEwAXoECAoQAQ#v=onepage&q&f=false)

[Book](http://ptgmedia.pearsoncmg.com/images/9780321961587/samplepages/9780321961587.pdf)

[Audio Organization](https://annesoaudio.com/2016/07/07/game-audio-asset-naming-and-organisation/)

[Template](https://docs.google.com/spreadsheets/d/1Nbn7e6UWmtJ4XOHbYsWqGUJNTdJXgSUZLlATrdIarSM/edit#gid=0)
