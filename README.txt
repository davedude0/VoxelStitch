Instructions for usage of VoxelStitch.exe

Read all of these before starting!
This program is dumb - if it doesn't find what it wants, it'll throw a tantrum and collapse on the floor with an error.

Step 1:
	As per http://www.curse.com/mc-mods/minecraft/225179-voxelmap you need to enable image output by editing your VoxelMap config.
	You may also want to disable dynamic lighting.
	You can find your config at C:\Users\[Your user account]\AppData\Roaming\.minecraft\mods\VoxelMods\
	Don't close this Explorer window down yet - you'll need to get there again later.

Step 2:
	Get those images!
	Start up Minecraft with  everything installed and ready to go. It'll be best to make sure that it's daytime in A'therys before starting.
	Open up the world map, and thoroughly pan around all the areas you want mapping.
	Disconnect from the server and quit the game before a wild SpiderVorske attacks you.

Step 3:
	Find those images!
	These will usually be in C:\Users\[Your user account]\AppData\Roaming\.minecraft\mods\VoxelMods\voxelMap\cache\rp.gazamo.com\Overworld\images\z1

Step 4:
	Put the images in the right place.
	Simply copy and paste all the images into the images folder WITHIN the dist folder in the VoxelStitch folder, which you should have unzipped or whatever by now.

Step 5:
	Want to see the image just before it's saved for whatever reason? You can!
	In the top bar of your Control Panel, paste in "Control Panel\Programs\Default Programs\Set Associations"
	Find the .bmp file association, and click change program on it and switch it over to mspaint.exe
	This is because the default windows image viewer thing is terrible, and refuses to accept a /wait command so the temporary image is automatically deleted before it can load it.

Step 6:
	When you have ensured that everything is in the right place, run the VoxelStitch.exe!
	You'll see plenty of numbers fly by, trying to inform you as to which files it's processing right then.
	If you want to understand these, have a look at the VOxelStitch.py file in the main directory - it should be clear enough as to what is what.

Step 7:
	Your image should now be complete!
	It will be saved as "compiledMap.png" in the same folder as VoxelStitch.exe.
