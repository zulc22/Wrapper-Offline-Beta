# Wrapper: Offline
After learning that GoAnimate Wrapper (a project by VisualPlugin) would be shut down, Wrapper: Offline was created. (simply called "Offline" for the rest of this page) Unlike the original project, Offline can not be shut down or "patched". You have the files all on your computer. This project is important for historical and archival purposes, as the ability to use this legacy editor and themes would be completely gone without it. Besides simply emulating the original Flash editor, some additional features and improvements have been made. And Offline will continue to get additional updates in the future.

## Running / Installation
To start Wrapper: Offline on Windows, open `start_wrapper.bat`. It'll automate just about everything for you and, well, start Wrapper: Offline. On your first run, you will likely need to right-click it and click "Run as Administrator". This allows it to properly install what it needs to run. After your initial run, you shouldn't need to do that again, you can start it as normal.

If you want to import videos and characters from the original Wrapper or any other clones of it, open its folder and drag the "_SAVED" folder into Offline's "wrapper" folder. If you have already made any videos or characters, this will not work. Please only import on a new install with no saved characters or videos, or take the "_SAVED" folder in Offline out before dragging the old one in. If you want to import character IDs from the original LVM, you can paste `&original_asset_id=[ID HERE]` at the end of the link for the matching character creator.

## Updates & Support
For support, the first thing you should do is [read through the wiki](https://github.com/Wrapper-Offline/wrapper-offline/wiki) it most likely has what you want to know. If you can't find what you need, you can join the [Discord server](https://discord.gg/Kf7BzSw). Joining the support server is recommended, as there is a whole community to help you out.

## Dependencies
This program relies on Flash, Node.js and http-server to work properly. SilentCMD is also used to suppress all the extra logging noise you'd only need for troubleshooting and development. These all have been included with the project (utilities folder) to ensure full offline operation and will be installed if missing. The "wrapper" folder and http-server have their own dependencies, but they are included as well.

## License
Most of this project is free/libre software[1] under the MIT license. You have the freedom to run, change, and share this as much as you want.
This includes:
  - Files in the "wrapper" folder
  - Batch files made for Wrapper: Offline
  - Node.js
  - http-server
  - SilentCMD
  - Chromium Web Store
  - FlashPatch

ungoogled-chromium is under the BSD 3-Clause license, which grants similar rights, but has some differences from MIT. Basilisk is under the Mozillav2 Public License, MediaInfo has a similar BSD 2-Clause license. 7zip's license is mostly LGPL, but some parts are under the BSD 3-clause License, and some parts have an unRAR restriction. Stylus is under the GNU GPLv3 license. FFMPEG is under both the GNU General Public license and the GNU Lesser General Public license. Avidemux is under the GNU General Public license. These licenses can be found in each program's folder in utilities\sourcecode.

The source code for compiled programs are all stored in utilities\sourcecode, and you can modify these as you wish. Parts of Offline that run from their source code directly (such as batch scripts) are not included in that folder, for obvious reasons.

Flash Player (utilities folder), Balabolka (utilities folder) and GoAnimate's original assets (server folder) are proprietary and do not grant you these rights, but if they did, this project wouldn't need to exist.

You can create or modify any of the server assets too if you'd like. They're encrypted with an RC4 key, but you can find the .txt file containing the key and how to decrypt or encrypt an asset in the utilities folder.

While completely unnecessary, if you decide to use your freedom to change the software, it would be greatly appreciated if you sent it to me so I can implement it into the main program! With credit down here of course :)

## Credits
**Please do not contact anyone on the list for support, use the Discord server.**

Original Wrapper credits:
| Name             | Contribution         |
| ---------------- | -------------------- |
| VisualPlugin (C) | GoAnimate Wrapper    |
| xomdjl_ (D)      | Custom/Modded Assets |
| CLarramore (D)   | Bug fixes            |
| Poley Magik      | Asset Recreation     |

Some members of the original team have asked to not be given credit, and they have been removed.

Developers will have (D) on their name, to show they are officially working on Wrapper: Offline. Beta testers will have (B) on their name to show that they are beta testers for Wrapper: Offline. Contributors will have (C) on their name to show that they are making contributions to Wrapper: Offline by sharing some of their files with us. Everyone else has simply contributed something at some point.
Wrapper: Offline credits:


| Name                             | Contribution                                                                                                                                         |
| -------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| Benson (D)                       | Wrapper: Offline                                                                                                                                     |
| Poley Magik                      | CC Toon adventure, Expanded Color Palette, Head props and wearables and much more.                                                                   |
| NathanSaturnBOI                  | Logo                                                                                                                                                 |
| VisualPlugin (C)                 | Text to speech voices, background importing, tons of bug fixes and more                                                                              |
| CLarramore (D) (B) 		   | Various bug fixes and development for some of the features                                                                                           |
| **xomdjl_** (D)         	   | export script, pick a theme page, implementing the Flashpoint version of Basilisk browser, TTS voices and more |       
| creepyjokes2000 (D)        	   | Waveform fix, improved actions                                                                                                                       |
| JoshAnimate                 	   | Headgear fix                                                                                                                                         |                                                                  |
| GoTest334 (D)                    | Leader of the Wrapper: Offline Team.                                                                                                           |
| The Invincible Sphynx Cat (B)    | Beta testing, suggestions, remastered GoAnimate tracks (provided separately, not included)                                                           |	
| MJ, the Spirit (D) (B)	   | Facial expression fix, video/imported asset backup tool, action pack tool creator, bug fixes                                                         |
| MegaT (C)                        | CC browser code                                                                                                                                      |                                                                            |
| Spark (D) (B)                    | Video list grid view, rewriting faq.html, other small tweaks.                                                                                        |

These are unaffiliated people that they haven't directly done anything for the project (and probably don't even know it exists) but still deserve credit for their things. Kinda like a shoutout but in a project's readme. ***Please do not contact them about Wrapper: Offline.***

| Name               | Contribution                     |
| ------------------ | -------------------------------- |
| Vyond              | Creators of the themes we love   |
| http-party         | Creators of http-server          |
| Stephan Brenner    | Creator of SilentCMD             |
| vocatus            | Some of TronScript's batch code  |
| ss64.com           | Incredible CMD info resource     |
| robvanderwoude.com | Also amazing CMD info resource   |
| darktohka          | Creator of FlashPatch            |

## Footnotes
[1] - See <https://www.gnu.org/philosophy/free-sw.html> for a better definition of free software.
