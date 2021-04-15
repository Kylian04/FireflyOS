BLOOD(TM) Shareware v 1.11 README.TXT
September 10th, 1997

Other useful files: 

bloodhlp.txt    the text version of the printed manual
monolith.txt    A personal note (and challenge) from Jason Hall, 
                Monolith's CEO

BLOOD CUTSCENES (retail shareware only)
In order to preserve space on your hard drive, we have not installed
the Blood cutscenes. Therefore, you must have the Blood CD in your
CD-ROM drive to view the cutscenes. Copying CS1.SMK and CS2.SMK from
the CD to your Blood directory may improve video performance and will
eliminate the need to keep the CD in the drive.

If you copy the cutscenes, you must modify the BLOOD.INI file to
point the program at the video files. CutSceneA in the [episode1]
section should point to CS1.SMK and CutSceneB in that section
should point to CS2.SMK.

For example:

CutSceneA=c:\blood\cs1.smk

CD AUDIO (retail shareware audio)
CD Audio will only play if the CD is in the drive. If you wish to
view the cutscenes but don't want to listen to CD audio, use the
"-nocd" command line parameter.

SOUND & MUSIC
You should test your SOUND FX card before testing your MUSIC FX card. 

AWE32
If you have problems with your AWE32 card while in DOS mode, make
sure that you have run the SBDIAGNOSE utility that comes with your 
audio card. If you are still having problems playing music, try
switching your music card to SoundBlaster.

Note: SBDIAGNOSE does not come on the AWE32 CD.  You need to downloaded 
it from the Creative Labs web site at http://www.creativelabs.com.  
It is a Dos program.

If you are running from within Windows, try selecting General MIDI as 
your music device.  Then:
    1. Click the Start button.
    2. Press on Programs submenu, click on Sound Blaster AWE submenu and 
       select AWE control panel.
    3. Click on the Synth tab
    4. Select the \Program Files\Creative\ctsnd\sfbank subdirectory.
    5. Select one of the GM patches - 

	If you have 2-4 megs on your card, install 2gmgsmt.sf2 or 
        4gmgsmt.sf2. Also, synthgm.sbk and synthgs.sbk should work fine 
        as well for < 1MB cards.

   If these soundfonts are not installed, they should be located on the 
   Creative Labs(tm) CD that came with your soundcard.

   6. Press the Apply button.
   7. Press OK
   8. Press the Start button again
   9. Click on Settings
   10. Click on Control panel
   11. Click on Multimedia
   12. Click on the MIDI tab
   13. Select "Creative Advanced Wave Effects Synthesis for AWE 32"
   14. Click on Apply, and then on OK
   15. Launch  Blood

PROAUDIO 16
Although the Proaudio 16 is listed in the setup program, it is not
currently supported.

MODEM
When choosing the modem type from the Blood-Setup menu both players should 
use the default modem setting.

FOR MS SIDEWINDER 3D PRO USERS
Configure the Setup Joystick options as normal.  If you wish to use the 
rudder feature, make sure to click the Enable Rudder option.  In the Advanced
Joystick Setup, delete all analog references, and use the digital settings to 
configure the stick to your preferences.  Under Advanced Rudder/Throttle 
Setup, delete all analog references and set the Digital Setup to your 
preferences.  The MS Game Device Profiler software that ships with the 
Sidewinder can be used to configure the four base buttons to your liking, 
and works will with Blood.

MATROX VIDEO CARD
The Diamond Stealth S3 Verge and the Matrox Millineum 2Meg/wram graphics 
card may cause Out of Memory errors in a Dos environment.  Setting Files, 
Stacks and Buffers in your config.sys to maximum values may help alleviate 
this problem.

MATROX MILLINEUM
Matrox Millineum\2Meg(Wram) does not run correctly in 800x600 graphics mode.
Blood may exit or experience video problems with this card.

MATROX MYSTIQUE
Matrox Mystique 2Meg graphics card with SGram causes Blood to lockup at 
Main Menu while trying to select new game. Lockup occurs only with this card 
in 800x600 and 640x480.  Users have gotten this card to work with the
Latest BIOS 1.4.

The lastest Mystique BIOS is available from Matrox's website at 
http://www.matrox.com/mga

The latest drivers for all Matrox cards are available at
http://www.matrox.com/mgaweb/whatnew/latdriv.htm

CHANGING VIDEO MODES
The F8 command to directly change video modes has been disabled.  
Some users (see 'MATROX', above) were experiencing problems with their cards
in some standard VESA video modes, so we have disabled this feature.

F8 now brings up a menu allowing you to choose your video modes.

--------------------------------------------------------------------------
TROUBLESHOOTING

1. If you have enough memory installed but cannot get Blood to run:
 
* If you are running in Windows '95, shut down and restart in MS-DOS mode 
 and install Blood in DOS instead. This will free up a lot of the 
 memory that is being used by Windows.

* Try these settings if running under Windows95

   To change the settings for Blood, RIGHT click the shortcut, select the
   PROPERTIES sheet, and configure like so:
 
    FONTS tab:  Bitmap only
 
    MEMORY tab: Everything on AUTO
 
    SCREEN tab: Do not allow screen-saver
                Run Full-Screen
 
    MISC. tab:  Mouse Quick-Edit and Fast Pasting both OFF
                Idle Sensitivity:  Lowest setting
                Shortcut Keys:  ALL OFF except "Alt-Enter"

* If you are running in DOS, or Windows'95 DOS mode, and still do not have
 enough free memory to run Blood, you may need to create a boot disk that 
 only loads your CD-ROM, sound card, and mouse drivers, and use it to boot 
 your computer each time you play Blood. There is a boot disk FAQ available
 on GT's website (www.gtinteractive.com) and via faxback at GT tech support
 number that can help you to create a boot disk.
 
2. If you have sound problems:
 
* If you have not already run the SETUP utility after installation, do so 
 now.  You need to specify what brand of sound hardware you are using before
 Blood can run. 
 
* If you are playing from DOS and not Windows '95, you will need to have your
 sound card drivers loaded in config.sys before playing Blood for your sound
 card to work.  
 
* Be sure that the settings you choose in SETUP for your sound card match 
 those found in your SET BLASTER environment variable in the autoexec.bat 
 file.
 
* Make sure that the sound card setup utilities are set up in AUTOEXEC.BAT 
 when you boot your computer into DOS.
 
* Don't run under a Win95 full-screen DOS box unless you absolutely have to.
 
3. If you are having mouse problems:
 
* Using a 3-button mouse requires the latest drivers
 from the vendor, especially if running under Win95.
 
* If all else fails, configure as a two-button mouse,
 or keyboard only.
 
4. If Blood crashes unexpectedly with or without an error message:
 
* Don't run Blood under Windows or Win95.  Shut down and restart in true 
 MS-DOS.
 
* Make sure your system meets the minimum system requirements for Blood 
 listed on the Box.
 
* Be sure that your mouse driver is loaded prior to playing Blood.
 
5. If you experience "Out of sync" errors when playing a network or modem game:

* Be sure all of the players have the same version of Blood as well as the 
  same version of any user map you might be using.

* Net game - Make sure your network card drivers are set up properly and that 
  all cards are using the same version of the IPX protocol.
 
* Modem game - Be sure that both modems are set to the same baud rate and 
  that error compression, data compression and flow control are turned off.

--------------------------------------------------------------------------

TECHNICAL SUPPORT (U.S. & CANADA)

Assistance Via World Wide Web

Get up-to-the-minute technical information at the GT Interactive
Software website, at http://www.gtinteractive.com, 24 hours a day, 
seven days a week. In the Support section you'll have access to our 
FAQs (Frequently Asked Questions), which contains our latest 
troubleshooting information.  You can also visit our Forums area, 
where you can swap email with other gamers, our FTP (File Transfer 
Protocol) area where you can download patches and new enhancements as 
soon as they become available, our Hints/Cheat Codes area, an E-Mail 
area where you can leave us your tech support problems and questions,
and other areas where you can get valuable information on GT 
Interactive Software products.


===========================================================================

1.11 RELEASE NOTES

Quicksave bug is fixed.  This bug incorrectly wrote saved game file.

Blood now closes save/demo files correctly so externally loaded files (ie. 
demos) run correctly.

User maps can now be paused
User maps display correct loading screen (not "LOADING DEMO")

Autorun status now saved
Mouse aim status now saved 

Coop frag bar was missing

Crystal Ball view was wrong

Tchernobog is not so weak anymore.

===========================================================================

1.10 RELEASE NOTES

Saved game files from previous versions are not compatible with this version.
They will be ignored by Blood.

SOME of the 'bugs' that were fixed in 1.10 from 1.02:

The 'level looping' bug has been fixed.  This was related to demos and
internally incorrectly setting the options you had chosen with the default
options (e1m1).  This caused the 'next' level to always be e1m2.  A work-
around for 1.02 was to delete the demos (*.dem).

Problems with killing many things at once is now fixed. 

If a CD was not in the CD Drive when the game tried to play videos from the
CD, an "Abort, Retry, Fail" showed up.  We now check with the CD functions
to verify a disc is installed before trying to play.

We have removed the 'user map' option from setup.  Run user maps from
the 'New Game' menu in Blood.  This works on all online services and is
much faster because it happens after all players are in the game.

Holster Weapon didn't work with the spray can.

You can change video modes from a menu in the game.

Demos from older versions are ignored on playback.

Saved games from older versions are ignored.

Cut Scenes now play in DOS !!!!!

Gargoyles would sometimes fly higher and higher, and ignore you.

If you cheat, the game keeps track over saved games.

Beastvision key was disabled

There was a problem with Alt-TABing in Windows and slowdowns.  The 
responsivness has been improved when you return.

Problems with starting some levels has been fixed.  This was particularly
noticed on e1m3 on some systems.

When one player quit, sometimes other players would crash.

Rats (and other monsters) would scream like humans when exploded.

"Map follow mode" didn't work.

Sometimes running out of ammo would auto-switch you to the napalm cannon.

Electrocution death of monster was sometimes caused by shotgun.

Tesla Cannon alt-fire worked when ammo was too low
Voodoo doll alt-fire worked without enough ammo
Tommy gun alt-fire worked without enough ammo

Spray can would continue burning underwater

Added 'loading' screen on network start.
Added 'loading/saving' screen on game load/save.
Added 'loading' screen on level start.
Added 'restarting CD' screen when CD track is looping.

Added ending credits to episodes
Ending an episode re-starts the game at the intro movies.

CD Audio restarts when saved game is loaded.

Only player #1 could damage oppenents by jumping on their heads.

Memory reporting improved to give better totals about how much 
memory was allocated.  Maximum memory allocated is now 36MB.

You can't save the game when you are DEAD.

There was an e2m5 Secret with no exit.

You could get 'Grip of Fear' (unable to release) with TNT or spray can 
when jumping into water

e2m2  Lamp sprite was not positioned on the ceiling as it should be

Added 'reset Keys to defaults' on configurations menu

MS DOS MODE: Thunder SFX looped incorretly during the Monolith splash screen

e1m1 clicking noise at 2nd secret (TNT) in Caleb's tomb

===========================================================================

1.02 RELEASE NOTES

Online services are now optimized and integrated into the single Blood
program.  You will not need an enabler for your service.  ENJOY!

Support for Spacetec was added.

If you have installed the 1.01 tools (mapedit, artedit, etc), they are 
patched to 1.02 by this patch.

CD-Audio tracks will now repeat during a level.  This will cause a slight
delay when the track is restarted.  You can avoid this by using the -nocd
parameter to Blood and controlling the playback of the CD-Audio through
another program.

Map names are now displayed in map mode.

More things are cached when a level starts.  This makes the level load
appear longer, but the action should be faster in the game (assuming you
have enough memory).  All the audio is still not being pre-cached (becuase
they're all so BIG), so you will still have some 'hitches' while it is 
loaded the first time.

The large status bar correctly shows the version number.

We fixed a problem in Capture-the-Flag play where if the player with the
flag, say, jumped off the train (and dropped the flag), the flag would
never come back where somebody could get it.  It now respawns after a
time if nobody goes and gets it.

You'd sometimes see yourself (a ghost) when you jumped through stacks.

Mirrors were broken when loading a saved game.  This would give the "Hall
of Mirrors" effect.

Videos still do not play in DOS.  We're having problems synchronizing
the Smacker video playback and the sound drivers we are using.

===========================================================================

1.01 RELEASE NOTES

Saved game files are not compatible with this version.  You must delete or
rename them before running this version.

SOME of the bugs fixed in 1.01:

Co-op players were getting out of sync when attacked by spiders and during
earthquakes.

A problem with loading and saving games has been fixed.  Some operations 
that had been started would not finish after the game was reloaded.  For
example, ending the level.

There was a bug in the menu code for initializing the saved game menu.  This 
could cause crashes just by having saved files.

If you used the alt-fire with the Voodoo Doll, you couldn't reselect the
weapon again until you picked it up again.

A couple of level fixes including secrets that counted each time you 'found'
them and fixes related to items respawning (either not or always).

Help screens corrected for correct key configurations.

Cerberus was too easy too kill with the Tesla cannon.

'Show Weapons' option was not getting saved when you exitted the game.

Sometimes a monster would show the 'electroction' effect when it hadn't been
damaged by the Tesla cannon.

Saved games are now much smaller.

There were two Red team flags on E2M1 and only one Blue team flag.

We now warn you when you don't have enough memory to play Blood.
We let you continue, but please be aware that the game may crash.

Some video cards (see readme.txt from Blood) have bad VESA drivers and
crash when Blood uses higher-resolution video modes.  See the Blood README
for specific cards that have these problems. For this reason, the in-game
video mode switching function of the F8 key has been removed until the 
VESA issues can be resolved.

===========================================================================

If you read this far, you deserve something...

So, here's how to record demos yourself.

o  Start Blood normally.
o  Enter spielberg as a cheat
o  Enter the episode and level to demo play
o  Quit the game when done recording. (DON'T end the level while recording)
o  A file of e?m?.dem will be created with the episode and level # of the
   demo you recorded.  Repeat for multiple levels (shareware comes with three 
   demos, reg has four)  
o  When you have all demos recorded, rename them to blood000.dem to 
   blood00x.dem in any order.   Now when you start Blood, it will say "n 
   demos in the loop" where n is x+1 and the demos will play on startup.
