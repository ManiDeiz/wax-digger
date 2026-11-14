# Wax Digger · Beta · By MANI DEÏZ

A record digger inside the MPC. Search, tap a title, hear it at once, record the part you want
as a WAV. The sound comes from YouTube, over the network of the MPC. No computer needed.

Free to use. All rights reserved: please share the link, not the zip.


## What you need
- An MPC: see "Which MPCs" below.
- MPC OS 3.10.1 or later.
- A network on the MPC: Wi-Fi, or an Ethernet cable (the MPC One has no Wi-Fi).
- An SD card or a USB drive (the one you already use for your samples is fine), with 250 MB free.


## Install
Easiest: with the MANI DEÏZ HUB plugin (https://manideiz.github.io), touch INSTALL next to Wax Digger.
By hand:
1. Unzip this file on your computer.
2. Put the SD card or USB drive in the computer (or put the MPC in Controller mode).
3. At the root of the drive, open the folder named "VST2 Plugins". If there is none, create it,
   with exactly that name.
4. Copy into it the whole folder that is inside "VST2 Plugins" in this zip (its name ends with
   "VST - Wax Digger"). Do not rename it.
5. Eject the drive, put it back in the MPC.
6. On the MPC: Preferences. In the list on the left, scroll down to "Enhancements (Beta)".
   Switch on "Enable Enhancements" and "External Plugin Support".
7. Restart the MPC and connect it to the network (Wi-Fi or Ethernet).
8. Make a plugin track and choose Wax Digger (under MANI DEÏZ).

The first time after each power-on, the top line says STARTING THE ENGINE. It copies its files
into the memory of the MPC: up to a minute. Then it says READY - PRESS SEARCH.


## How to use it
```
DIG tab     Pick a genre, style, decade, place with the arrows, press SEARCH.
            "Max views" keeps only the videos seen less than that: the rare ones.
FIND tab    Type words (an artist, a label, anything), press SEARCH: straight on YouTube.
LIKES tab   The titles you starred. Touch one to play it.
SETUP tab   CHECK FOR AN UPDATE: fetches the latest YouTube reader (see "Crosses" below).
```

```
Touch a title         it plays. The light in front of it: lit = ready, cross = cannot be played.
Data wheel            next / previous title.
Push the data wheel   play / pause (of Wax Digger only, not of your project).
PAGE UP / PAGE DOWN   16 titles per page.
POS                   touch it, then turn the data wheel to move inside the title.
Star                  like the title on air. Press again to remove it.
REC                   starts a take from where you are. Press PLAY (pause) to end it, then REC
                      again, now called SAVE, to keep it. PLAY instead drops it.
```

Takes are WAV files named like the title, in "Samples/Wax Digger" on the same drive.
Load them from the MPC browser like any sample.


## Good to know
- YouTube does not like being asked too much. Wax Digger prepares only the title you are on and
  the five after it. If you race through hundreds of titles, the top line can say "YouTube refuses
  for now": wait about 15 minutes, it comes back by itself.
- Crosses everywhere, on every search, for more than a day: YouTube has changed something.
  Go to SETUP, press CHECK FOR AN UPDATE, then search again.
- A cross on one title only is normal: that video cannot be read (blocked, removed, too long).
- Titles longer than 6 minutes and "full album" videos are left out on purpose.


## Which mpcs
Made and tested on an MPC Live III. It carries its engine for both kinds of MPC:
- 64-bit (Live III, XL): tested on the Live III.
- 32-bit (Live, Live II, One, One+, X, X SE, Key 37, Key 61, Force): should work, not tried yet.
  The MPC One has no Wi-Fi: plug in an Ethernet cable.


## If something goes wrong
In the plugin folder on the drive there are two small text files, wax_log.txt and engine_log.txt.
Send them with one line saying what you did: they tell exactly what happened.
To remove Wax Digger, delete its folder from "VST2 Plugins".


Wax Digger is not made, endorsed or supported by Akai Professional, YouTube or Discogs.
What you record with it is yours to clear like any other sample.
