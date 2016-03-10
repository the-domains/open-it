---
inFeed: true
hasPage: false
inNav: false
isBasedOnUrl: 'http://davidryman.com/it.php/2009/11/24/troubleshooting-asrock-mobo-is-it-doa'
inLanguage: en
starred: true
keywords:
  - mainboard
  - beep
  - ides
  - connect
  - motherboard
  - please
  - troubleshoot
  - connector
  - devices
  - jumper
description: 'Building a Mythbuntu box for my RV project presented unexpected issues, one of which was the motherboard, an ASRock A780GXE/128M. Basically nothing happened much when it was assembled. An email to tech support generated the following information, which I pass on to anyone who can use it.'
datePublished: '2016-03-10T22:31:58.135Z'
dateModified: '2016-03-10T22:31:31.366Z'
author: []
related: []
app_links: []
title: Troubleshooting ASRock mobo. Is it DOA?
sourcePath: _posts/2016-02-18-troubleshooting-asrock-mobo-is-it-doa.md
published: true
authors: []
publisher:
  name: Davidryman
  domain: davidryman.com
  url: 'http://davidryman.com'
  favicon: 'http://davidryman.com/favicon.ico'
_context: 'http://schema.org'
_type: MediaObject

---
<article style=""><h1>Troubleshooting ASRock mobo&amp;period; Is it DOA&amp;quest;</h1><p>Building a Mythbuntu box for my RV project presented unexpected issues&amp;comma; one of which was the motherboard&amp;comma; an ASRock A780GXE&amp;sol;128M&amp;period; Basically nothing happened much when it was assembled&amp;period; An email to tech support generated the following information&amp;comma; which I pass on to anyone who can use it&amp;period;</p><img src="http://davidryman.com/G2_base/main.php?g2_view=core.DownloadItem&amp;g2_itemId=3051&amp;g2_GALLERYSID=TMP_SESSION_ID_DI_NOISSES_PMT" /></article>

Building a Mythbuntu box for my RV project presented unexpected issues, one of which was the motherboard, an ASRock A780GXE/128M. Basically nothing happened much when it was assembled. An email to tech support generated the following information, which I pass on to anyone who can use it.

Try to find out if the mainboard will give you any beep code. Try to test the mainboard outside of the computer case. Remove all the devices that connect it on the mainboard. Only device need to connect on the mainboard is the Processor and Processor cooling fan, and make sure all the power connector are fully plug in 12V rail connector (4pin / 8pin), and 24(20)pin ATX power connector. If you do hear the beep code like 1 long beep and follow by 3 short beep. Please insert 1 single memory module, and go ahead insert the video card to the PCI-E slot. Below is the troubleshooting guide. If you still can't get the problem resolve please give us a call at 909 590 8308\.

1 Short Beep

One beep is good! Everything is ok, that is if you see things on the screen. If you don't see anything, check your monitor and video card first. Is everything connected? If they seem fine, your motherboard has some bad chips on it. First reset the SIMM's and reboot. If it does the same thing, one of the memory chips on the motherboard are bad, and you most likely need to get another motherboard since these chips are soldered on.

1 Long, 3 Short Beeps

You've probably just added memory to the motherboard since this is a conventional or extended memory failure. Generally this is caused by a memory chip that is not seated properly. Reseat the memory chips.

1 Long, 8 Short Beeps

Display / retrace test failed. Reseat the video card.

Dear ASRock Custumer,

Please follow the next steps in order to troubleshoot your main board.

TO CLEAR BIOS

First: disconnect the two power supplies sources from the main board. (24 Pins /20Pins and 8Pins/4Pins) cables.

Pull the Battery out from its battery Socket.

Second short the Jumper CLRMOS located closed to the Battery and set for from position 1~2 to 2~3 to clear the Cmos for about 10 seconds.

Finally reverse all steps above.

Turn your PC on and when screen Display appear Press the key F2 to Access to CMOS setup and then press the key F9 to load Optimal Defaults.

Finally press the key F10 to save and exit.

After your clear CMOS and still does not respond do the next steps:

TO TROUBLESHOOT MAINBOARD

In order to troubleshoot your mainboard disconnected all cables and work only with the cables recommended below.

Removed your mainboard from your Computer case (if your mainboard is installed in the case)

Make sure the mainboard is lay down in a clean flat surface and use the protection the comes with your mainboard to avoid any electrical short underside the circuit board.

Please connect only the cables requested below (do not connect IDEs, Floppy ect.)

The only parts for your Mainboard it needs to be install is the CPU & CPU's fan

Connect the 2-power connector (24(20) pins and 8(4) pins) from Power Supply

Connect the Speaker from your computer case (Diagnostic beep code by speaker). No sound speakers

Connect the Power Switch from your Computer case into Panel 1 Pushbutton.

Take your RAM out of your Mainboard as well as video card.

Then turn your mainboard on and you should heard 3 beeps (if you heard them please turn it off)

Install your RAM and turn your mainboard on you should heard 8 beeps (if you heard them turn it off)

Install your video card and turn your mainboard on and you should heard 1 beep (you should have screen display in your monitor)

If all steps above passed please put your mainboard inside the case.

Every single time you added a cable from IDE or CD room please turn your PC off and try, if for some reason fail disconnect the last device you install and go one step back to trouble shoot by steps.

IDE & OPTICAL CONNECTED

For best compatibility and stability, please make sure your stand alone hard drive on primary IDE has jumper setting to master, and your stand alone optical device on secondary IDE has jumper setting to master, too. Also if you only have one hard drive without any other optical device, please connect the hard drive to primary IDE with its jumper setting to master. Furthermore, for optimizing the transfer rate for the hard drive, we recommend you to connect your hard drive(s) to the primary IDE channel and optical device(s) to the secondary IDE channel .

After you finished loading your OS to HDD you can connect all IDEs Devices

Asrock Support Team