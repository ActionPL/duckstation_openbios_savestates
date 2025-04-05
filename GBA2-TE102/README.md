**Game name:**

Gundam Battle Assault 2 [ComboKyo Edition V1RC2]

**Game ID:**

GBA2-TE102

**Game format:**

CHD

**Hash:**

CHD DATA SHA1: 7207AAB96E6F6A2B1A45B3AA5B44B8FB2C6C9F14

BIN (TRACK 01) MD5: 238ce42acfccdaa4549d2fb131ded3aa

BIN (TRACK 02) MD5: 2d7b5e8e94a91bf5423b2356f6a34863

**Description:**

Starts at main menu with "VERSUS 2P" option highlighted.

by Yuri Bacon:
ComboKyo Edition V1RC1 is finally here! This is a Release Canidate build, meaning that it is feature complete and intended for public release, but hasn't yet been thoroughly tested. Luckily for you, I've taken notes straight out of the playbook of modern AAA devs and left the testing up to you! If you find any bugs, crashes, or other fucky behavior, @Yuri Bacon ping me, give me as much information as you possible can, and I'll see what I can do the fix it. I'm also open to any feedback you have, but we're past the point of making major alterations or implementing new features.

In short: give this release weeks worth of testing before you trust it for tournament play.

What's new since v0.03-fix: 
The improvements to the game options menu is huge Rochester! HUUUUUUUUUUUUUUUUUUUUUUUUGGGGEEEEEE!
Framerate & Random stage have their own entires in the options menu and no longer replace Pilot Display & Hit Display, keeping those original options intact!
Pilot Display is still off by default, per community consensus, but the point still stands that Pilot Display and Hit Display can be turned on and off at will, just like in the original game.
There is also now a ComboKyo Edition version string in the options menu! This will be updated as new versions come out, if any do. Let there never be confusion which version you have ever again! (Not that it was much of a problem to begin with :P)
This truly is the part of the new version I'm most proud of, alongside a lot of work to shorten some of the hacks code to fit space constraints, but I dont' get to list that as a new feature (scroll up to read all about it).
Random Mobile Suit
When you're on the 2P VS screen, just press select to "teleport" to a random mobile suit!
Unfortunatly, random select will suggest the banned gundams, and won't suggest the hidden mechs, due to "I want to finally put this project down" and "that sounds like too much fucking work lol" constraints. If someone wants to pick up the source code I'll be posting to github Soon and brush up the random mech code to include the hidden mechs, and not suggest the banned mechs if that's what you want, that would be great.
This won't select the character for you, so if you don't like the random suit you get, just hit select again!
Random Music
The community was split roughly 50/50 on this one. While just about everyone agreed it should be an option, some thought it should be on by default while others wanted to keep the music the way it has been by default. Not wanting to rock the boat, I've given you three music options.
"Community" is the default option, which uses the same music replacements as the hidden mech gameshark cheat has for years: if either player is Ball you'll get "Best Theme", and if either player is Acguy, you'll get "Acguy Theme", but otherwise you'll get the game's original music.
"Original" is self explanitory. You'll get the exact same music picks the original game would have given you.
"Random is also self explanitory. You'll get a random song for every match!
ComboKyo now appears in 2P VS screen
It doesn't matter if your playing netplay, going to the next FGC major's GBA2 side bracket, or just to hang with your homie, now you'll have an official seal of approval that you're getting a good experience, right on the 2P VS screen!
Just remember that this ROM hack cannot automatically set a 180% overclock for you, despite doing everything else all in one. If you're playing on duckstation then you'll still have to be sure to set the overclock. Performance considerations will have to be made for other platforms. Options to disable random stage (so you are always suggested the last used stage with the purpose of always playing the default stage) and disable 60FPS (and return to the original 30FPS gameplay) are both options at your disposal if you find yourself playing on a platform with no performance enhancements, like the PS1. Those wanting to play on a mister should experiment with the "Turbo" enhancement setting, but don't hold your breath on it hitting a locked in 60FPS on all stages.
Hidden Mech Name Plates
When you pick a hidden mech, not only will you hear the announcer say the name of the mech you just picked, the mech name on screen will also update to show your new mechs name! I think this really sells the feeling that you've just put in the code for an old street fighter character, minus the part where the code is fucking bullshit and people fuck it up all the time.
Attract Mode Crash Fix
If you just leave the game idling on the title screen, it'll eventually run an attract mode where it alternates between showing a CPU vs CPU demonstration, and replaying the intro FMV. With the old hidden mech gameshark cheat codes, and with the old ComboKyo Edition versions, replaying the intro FMV would crash the game. This has been fixed, so attract mode works fully and completely, as it should!
Title ID updated to GBA2_TE1.01

I'll be updating the source code on github with all the new additions and refactors that went into making this release, but not tonight. Too fucking late lol, I'm ready to get something to eat and sleep :P Expect it sometime within the next week! 
-----
New Update, hot off the presses! ComboKyo Edition V1RC2 is here!

Changes since V1RC1
Fixed a bug where the Random Music setting was overwriting the Time Limit setting ("Community" forced 99 seconds, "Original" forced 60 seconds, and "Random" forced "No Limit"). Now Time Limit works indepentently of Random Music as it's supposed to.
Updated Title ID to GBA2_TE1.02