# Project Log:
This is a log of my journey of developing this program. Here, you will find notes of my findings.

## 21:32 - 4/8/17:
So the file I pushed in the first commit was not actually the save file like I originally suspected. After some research, I found it located in my local Documents directory. It's interesting that it's kept away from the other game files. Here's the new problem: sure, I have the save file, but it isn't a .ini file like I thought. It's a .fos file which I assume stands fot "FallOut Save". When I tried to open it in atom, I got some whacky stuff. My next step is to figure out how to pick apart a .fos file. Right now, I'm thinking I'll try to move towns and do a git diff on the file to see what happens.  

## 21:50 - 4/8/17:
That did not work. Turns out, it's not easy to look at the line changes of a 11920 line file that's been uniquely encoded and obfuscated. However, all is not lost. I found this web page: http://falloutmods.wikia.com/wiki/FOS_file_format. Why should I hack apart a .fos file when the hive-mind that is the internet already did it? Unfortunately, it wasn't as detailed as I was hoping it would be, but there is enough to tinker with until I learn more about how it works. The next step will be to look at the file in a hex editor and start picking out informetion. This is a lot like the bitmap transformer assignment I did at Code Fellows. Who'd-a-thunk that'd come around again?
