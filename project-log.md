# Project Log:
This is a log of my journey of developing this program. Here, you will find notes of my findings.

## 21:32 - 4/8/17:
So the file I pushed in the first commit was not actually the save file like I originally suspected. After some research, I found it located in my local Documents directory. It's interesting that it's kept away from the other game files. Here's the new problem: sure, I have the save file, but it isn't a .ini file like I thought. It's a .fos file which I assume stands fot "FallOut Save". When I tried to open it in atom, I got some whacky stuff. My next step is to figure out how to pick apart a .fos file. Right now, I'm thinking I'll try to move towns and do a git diff on the file to see what happens.  
