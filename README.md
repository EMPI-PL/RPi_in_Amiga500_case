# Raspberry Pi 4 built into Amiga 500 case

![amigapi_001](pic/amigapi_001.png)
This repo will explain how to put RPi into Amiga 500 case without any modifications. Moreover the goal is to explain how to build whatever mounts there may be needed to get all ports accessable.
The final result is no damage to original case is needed to make it look and work as a 100% original Amiga (thoug we know it will never be an Amiga, right? :smile:

---
* [Story behind this project](#story-behind-this-project)
* [Considerations and dependencies](#considerations-and-dependencies)
* [Resources](#resources)
* [Final outcome](#final-outcome)
* [Costs summary](#costs-summary)
* [Useful resources available on web](#useful-resources-available-on-web)
* [Special thanks](#special-thanks)

---
### Story behind this project
This project was firstly introduced on Polish Amiga Portal's forum (ppa.pl) back in Jan 2020. The intention was to share this here on github as soon as everything is done. After 3 years since the initial post it's ready to be shared with others in a better fashon. By following hints and using the resources shared here you should be able to build a similar unit on your own.

My dream of actually owning Amiga 500 system takes me back to begining of '90s. Yep - I've never had one. The only opportunity to play any Amiga game was to visit my friends (thanks a lot Przemek, Bartek and Tomek :smile:). I was a sort of *8-bit guy* back then owning Atari 130XE system which quickly came to be obsolete when PCs came to power. Years passed but my love for retro only grew and some time ago I decided to visit my first Retro Party. Opportunity was to play my beloved **Sensible Soccer** tournament hosted at the party. A side effect of being there was an exposition to all this amazing hardware brought by retro-freaks. One of the units I've seen was special. At first glance it was just an Amiga 600 but it had a "strange" keyboard and no LEDs. After a short conversation with an owner I knew the secret - it wasn't an Amiga but a Raspberry Pi inside the A600 case. That day I've decided to build my own but better looking and with capability to recreate real feel and look.

I had to start from scratch as I've literally had nothing Amiga-related. No case, no keyboard no nothing. Everything had to be either just passed over to me for free or I had to pay for every single piece of hardware to make the dream come true. My first intention was to get a dead Amiga 500 unit and pull out MoBo to start with the case. To my surprise the prices were already crazy back then and today it's even worse. To give you an example from begining of 2023:
* Good looking Amiga 500 fully working costed approx. 150 Euros in Poland back in 2018.
* Same Amiga today is at least double the price.
* Local buy/sell portals like ebay are full of people selling retro hardware for insane prices even without any guarantee the unit will even work.
BTW I'm not complaining - it is what it is...

The ultimate goal to spin your own build is Simple - to prevent hardware which is getting very rare even if we consider new releases of keyboard membranes, new cases etc.
If you only have an access to keyboard and/or case = you're on the right path. For me a starting point was the case. Trapdoors I've had to buy separately - same for keyboard and everything. :laugh:

### Considerations and dependencies
If you want to follow this guide please make sure you take into the account the following:
* This build is FULLY REVERSABLE - do not modify the case in any way. No drilling, cutting and other decomposition of case is needed.
* You will spend money which is inevitable as you want to have a working keyboard, floppy drive and JOYs.
* To achieve best results you'll need to own a Raspberry Pi 4b (as at Mar 2023). The expectation is with release of RPi 5 this build will be adaptable easly.
* Originally the build was based on RPi 3b+ which later has been replaced. It doesn't make any sense to use RPi 3b+ as this SBC is to weak to fully utilize rel floppy drive.

This build is **fully dependent** on the following:
* Raspberry Pi 4b
* Amiga 500 USB Keyboard Controller (internal connection with audio passthrough) by [Tynemouth Software](http://blog.tynemouthsoftware.co.uk)
> This will provide you with working DB9 joystick ports, audio and keyboard.
* Arduino Amiga Floppy Disk Reader/Writer aka DrawBridge by [Robert Smith](https://amiga.robsmithdev.co.uk)
> This will give you a fully working floppy drive.
* SSD drive in place of memory card to optimize performance of RPi.
* Kilometers of extenders to get ports accessable from the back of the case... :smile:

### Resources

Explanation of resources available on this repo

### Final outcome

This section needs some work...

### Costs summary

Not the cheapiest option... But again - info coming soon...

### Useful resources available on web

Links etc.

### Special thanks

Some people to thank to... :smile:
