<p align="center">
  <img src="assets/dig.png" alt="Wax Digger on the MPC: sixteen records per page, filters, REC and PLAY" width="900">
</p>

<h1 align="center">WAX DIGGER</h1>

<p align="center">
  <b>A record digger inside your MPC.</b><br>
  Search, tap a title, hear it at once, record the part you want.<br>
  <sub>by <b>MANI DEÏZ</b></sub>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/MPC-Live%20III-f0a80e?style=for-the-badge&labelColor=141414" alt="MPC Live III">
  <img src="https://img.shields.io/badge/MPC%20OS-3.10.1%2B-f0a80e?style=for-the-badge&labelColor=141414" alt="MPC OS 3.10.1 or later">
  <img src="https://img.shields.io/badge/Wi--Fi-no%20computer-f0a80e?style=for-the-badge&labelColor=141414" alt="Wi-Fi, no computer">
  <img src="https://img.shields.io/badge/status-private%20beta-c8283c?style=for-the-badge&labelColor=141414" alt="Private beta">
</p>

<p align="center">
  <a href="download/WaxDigger-beta.zip"><b>⬇&nbsp; DOWNLOAD THE BETA</b></a>
  &nbsp;·&nbsp;
  <a href="INSTALL.md">Install guide</a>
  &nbsp;·&nbsp;
  <a href="#good-to-know">Good to know</a>
</p>

---

## What it does

Wax Digger turns the MPC into a crate of records with no bottom. It runs on the MPC itself, over its Wi-Fi:
no computer, no phone, no cable.

| | |
|---|---|
| **Instant** | Tap a title and it plays. The next ones load while you listen, so you can run down a page like in the MPC's own sample browser. |
| **Two ways to dig** | **DIG** by genre, style, decade and place. **FIND** by typing any words: an artist, a label, a drummer. |
| **The rare stuff** | A *Max views* filter keeps only the videos seen less than 500, 1 000, 5 000... times. That is where the unsampled records are. |
| **REC** | Record the part you want. It lands on your drive as a WAV named like the record, ready to chop. |
| **LIKES** | Star a title, find it again later in its own tab. |
| **Made for the hardware** | The data wheel walks through the titles, a push is play / pause. No knob to learn. |

## The screens

<table>
  <tr>
    <td align="center"><img src="assets/find.png" alt="FIND: type words, search YouTube" width="290"><br><b>FIND</b><br><sub>type words, straight on YouTube</sub></td>
    <td align="center"><img src="assets/likes.png" alt="LIKES: the titles you starred" width="290"><br><b>LIKES</b><br><sub>the titles you starred</sub></td>
    <td align="center"><img src="assets/setup.png" alt="SETUP: check for an update" width="290"><br><b>SETUP</b><br><sub>keeps the YouTube reader up to date</sub></td>
  </tr>
</table>

## Install

1. Download **[WaxDigger-beta.zip](download/WaxDigger-beta.zip)** and unzip it.
2. Copy the folder found inside `VST2 Plugins` into the `VST2 Plugins` folder at the root of your SD card or USB drive
   (create that folder if it is not there). Do not rename it.
3. On the MPC: **Preferences → Enhancements (Beta)** → switch on *Enable Enhancements* and *External Plugin Support*.
4. Restart the MPC, connect the Wi-Fi, make a plugin track and pick **Wax Digger**.

The first start after each power-on takes up to a minute (*STARTING THE ENGINE*), then it says *READY - PRESS SEARCH*.
The full guide, with every button, is in **[INSTALL.md](INSTALL.md)**.

## Which MPCs

| MPC | |
|---|---|
| **Live III** | ✅ made and tested on it |
| **XL** | 🟡 should work (same kind of processor), nobody has tried yet |
| Live, Live II, One, One+, X, X SE, Key 37, Key 61, Force | ❌ the plugin shows up but its engine cannot start |

## Good to know

- **YouTube does not like being asked too much.** Wax Digger only prepares the title you are on and the five after it.
  Race through hundreds of titles and the top line may say *YouTube refuses for now*: wait about 15 minutes.
- **Crosses on every title, for more than a day?** YouTube changed something. Open **SETUP**, press
  **CHECK FOR AN UPDATE**, search again.
- **A cross on one title** is normal: that video cannot be read.
- Titles longer than 6 minutes and *full album* videos are left out on purpose.
- **Something wrong?** Send the two small files `wax_log.txt` and `engine_log.txt` from the plugin folder on your drive,
  with one line saying what you did.

## Rights

Wax Digger is **© 2026 MANI DEÏZ, all rights reserved**. It is a private beta: please do not pass it on, republish it,
or reuse its code or graphics (see [LICENSE](LICENSE)). The separate programs it ships with (Python, FFmpeg, yt-dlp)
keep their own licences: [THIRD-PARTY-LICENCES.txt](THIRD-PARTY-LICENCES.txt).

Wax Digger is not made, endorsed or supported by Akai Professional, YouTube or Discogs.
What you record with it is yours to clear like any other sample.

<p align="center"><sub>MANI DEÏZ · beats, drums and tools</sub></p>
