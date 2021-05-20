Hungry Hippos Instructions
==================

You will simulate an environment with a food source and 4 hungry hungry hippos.

The food source will produce food at a constant rate.  It will generate a total of `100` food items into the food storage area.  You should have a way to change how quickly the food is produced.  The food storage area has a maximum capacity of `10` pieces of food at a time.  If it becomes full it must wait for hippos to eat.

### Feeding Frenzy ###
You will then have `4` hungry hippos.  Each hippo will try to eat from the food storage area.  
* The hippo will try to eat and randomly get an amount of food from the food storage area, it will get somewhere between `0` pieces of food and 'n' pieces of food, where `n` is the amount of food in storage.  
* When a hippo is trying to eat no other hippos can access the food storage area. 
* Immediately after attempting to eat the hippos will take a short nap. 
* You should be able to adjust how long the hippos nap.

### Crowning a champion ###
Once all `100` pieces of food have been eaten signal the hippos that there is no more food available.  The hippos should stop trying to eat at this point.  It is now time to weigh the hippos.  
* Display how much food each hippo ate and declare the heaviest hippo the champion and hungriest of the hippos.

### Testing ###
You need to test the food storage area.  In order to do this you must adjust the hippos sleep time to see what happens when the food storage fills up.  Be sure to test this.

### Results ###
Now pick a setting that for how quickly food is produced and how much hippos sleep for.  Run the simulation and record the results.  Change the settings are record the results for `3` more simulations.  Record this in assignment in google classroom.