---
description: 'welcome to the dark side, we have cookies'
---

# Bootloop/Brick. Let's reinstall the firmware

So you wanted to enjoy your vita and tried to do anything risky? \(testkit mod, downgrade, messing with system files\) and the only option available in safe mode is update the firmware? Or pressing L at boot doesn't help? No worry you can still save the PSVita, most of the bricks are actually recoverable. As long as it is software and you didn't wipe os0 \(unless you have enso ex\)  
  


## So doctor? what's the solution?

First of all, what I always recommend is to put a pup file in ux0:data/PSP2/UPDATE/PSP2UPDAT.pup It removes the need to connect with a PC and QCMA can be unreliable. You can then use it with option 5 update the system, and update from gamecard \(yeah yeah that option works with memorycard\). After you solve the problem, do that so next time it'll be easier.  
  
In order to reinstall the firmware, we shall update the system. "Update to 3.60" is the same thing as reinstall 3.60 as it will install the 3.60 pup. So let's begin, download the pup of your choice. Here's a little list.  


* 3.60 [https://yatsukiko.me/psvu/3.60/PSP2UPDAT.PUP](https://yatsukiko.me/psvu/3.60/PSP2UPDAT.PUP)
* 3.65 [https://yatsukiko.me/psvu/3.65/PSP2UPDAT.PUP](https://yatsukiko.me/psvu/3.65/PSP2UPDAT.PUP)
* 3.68 [https://yatsukiko.me/psvu/3.68/PSP2UPDAT.PUP](https://yatsukiko.me/psvu/3.68/PSP2UPDAT.PUP)
* UP TO DATE FW : go download it from Sony and don't forget to rename it into PSP2UPDAT.PUP

Once you have downloaded the pup, make sure you have QCMA installed, and put the pup file in the update directory. \(look in QCMA settings where is the update foledr. Usually called PSV updates.\)  
  
And change QCMA settings about the firmware to avoid the "you already have the latest version" message  


![3.60 masterace](../.gitbook/assets/capture-de-cran-2020-05-12-a-18.46.04.png)

You need to change the "FW : up to date" in use this version for updates into : custom.  
Then in the custom PS Vita version field write the corresponding version to the target firmware

* 3.60 : 03.600.000
* 3.65 : 03.650.000
* 3.73 : 03.730.000

And if you understood the logic you can adapt it for futur updates.

That's it on the PC side. Now connect your Vita through USB mode and select option 5 : Update this system and chose update from PC and you should be reinstalling the firmware now.   
  
If you have troubles making QCMA recognize your Vita, head to the QCMA section to know how to fix the errors.  
  
Once you have reinstalled the firmware, redo the hack and it should be good now.

