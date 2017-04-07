# MergeMaster
This is a web application that will eventually leverage the Git Hub API to backup and merge video game save files. Currently, this project is in the experiment phase.

## Original Inspiration:
I had the idea for this project while playing Fallout: New Vegas. For those that don't know, Fallout: New Vegas allows you to save the state of your game whenever you want. One day, My save history looked like this:
* Save 1
* Completed quest
* Save 2
* Obtained Cool Gun
* Save 3

However, there was a problem. I realized that I completed the quest in a way that made other loot that I wanted unatainable. I wanted to go back and load a save from before I started the quest but that took an hour to complete and I had obtained loot after that would be lost if I loaded the old save. If only there was a way merge the state of saves 1 and 3. Then I realized, maybe I can with git.

## Project Stage:
Currently, this project is just experimentation. Before I can merge properly merge save files, I need to pull them apart and learn how they work, where the relevent information is located, and how to change it without breaking it. For this experiment, I will be using Fallout: New Vegas. Here is what the experiment will look like:
* Start game
* Make save
* Push save file to git hub
* Open game and use dev tools to add items to inventory
* Save game
* Push new save to git hub and look at differences
* Repeat process with changing location and completing quests
