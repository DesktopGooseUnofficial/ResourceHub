# fastgoos 🏃‍♂️💨

## Features

Make your goose fast! You can configure just how fast in the config.

Get it: [fastgoos](https://cdn.discordapp.com/attachments/672363951232778251/673002901358247983/fastgoos_with_loader.zip)

Goose Version: **v0.2 \| v0.21**

Author: **DaNike#6223**

---

## Fastgoos Tutorial with Visuals

This mod allows you to have your goose move really fast.

* First download the fastgoos mod

The file should say "fastgoos_with_loader.zip" when you download it

![The mods folder, three load bin files, and a run with mods.bats file should be in the same area as where the DesktopGoose.exe is placed along with your Assets folder.](https://raw.githubusercontent.com/Tatohead/ResourceHub-Images/master/Fastgoos/part%201.png "The mods folder, three load bin files, and a run with mods.bats file should be in the same area as where the DesktopGoose.exe is placed along with your Assets folder.")

* Delete the config file

* Then run the 'run with mods.bat' that you see above

* Then exit that program

* Open up the newly created config file

What you should see the last 2 lines the same on that notepad (Do not worry about the other configuration settings on that notepad):

![The following 2 lines should be seen in your newly created config file: FastGoos.TimeMultiplier=5 and FastGoos.RealTimeMultiplier=0.75](https://raw.githubusercontent.com/Tatohead/ResourceHub-Images/master/Fastgoos/part%202.png "The following 2 lines should be seen in your newly created config file: FastGoos.TimeMultiplier=5 and FastGoos.RealTimeMultiplier=0.75")

The following is the effect 

Below is a chart that should tell you what kind of setting are added in your config file. Function will tell you what happens if you were to manipulate that setting,

| Setting                              | Function                                                                                                                     |
|----------------------------------|:--------------------------------------------------------------------------------------------------------:|
| FastGoos.TimeMultiplier= | How fast the goose will move by # time compared to the original speed |
| FastGoos.RealTimeMultiplier= | How often the goose will do an action (affects length of pauses in between) |

* Remember to save the Config file's changes

* Run the 'run with mods.bat' file once more and you're done!

**Notice:** If you run the DesktopGoose.exe you will end up corrupting the file. You should be running with 'run with mods.bat' everytime. If the file does get corrupted, delete the config file and make new one using the 'run with mods.bat' again. Otherwise you may have to startover.

**Note:** Also it can take a while for the goose to show up if you are using certain mods. You can still press esc to exit the program.

---

## Fastgoos Mod Compatibility List

| Symbol | Meaning                                                                                                                                 |
| :------: |:---------------------------------------------------------------------------------------------------------------------:|
| ✔️    | Works with this mod                                                                                                                   |
| ❌    | Does not works with this mod                                                                                                   |
| ❌✔️ |  Does not works with this mod for recent release, older releases works with this mod      |
| ❓     | Has yet to be tested                                                                                                                   |

Below is a list of mods that have been tested to either work perfectly or fail due to being unable to create a new config file.

| Mod Name                                                      | Status | Note                                                                                             |
| --------------------------------------------------------- |:------:|:------------------------------------------------------------------------------------------------:|
| Bobbie’s Modded Desktop Goose v0.2 | ✔️ |   |
| Highly Configurable Goose | ❌✔️ | Likely it collides with new files. For older version of the mod, v4-v1 they work fine. |
| Mad's Facts | ✔️ |   |
| NabMouse | ❌ | Cause is unknown at this time. |
| Shaggy's Image Cap Fix | ✔️ |   |
| Shaggy's Sound Control | ✔️ |   |
| Shaggy’s Name Mod | ✔️ |   |
| Sneaky Goose | ✔️ |   |

---

## FAQ

**Q: How do you unzip?**

**A:** If you have Winrar or 7zip installed on your computer, you can right click on that zip file and select either 'Extract All' or 'Extract Here'.

**Q: How do you open the config with Notepad?**

**A:** You right click that config file and select "Open with". Then pick Notepad.

**Q: Can this work with other mods?**

**A:** Yes, it has been tested to work with other mods. If you saw the second image in the tutorial You will notice there's a bunch of other configuration settings on that notepad. That was tested with the second version of Highly Configurable Goose. (Please check out the Compatibility List above the FAQ)

**Q: Can this work with the hatgoos together on another mod?**

**A:** Yes, you just have to take the HatGoos dll into the same mods folder as the FastGoos. Then delete the old config and run the 'run with mods.bat' again.

**Q: So does exiting out 'run with mods.bat' exit out the goose program?**

**A:** Yes, that's correct. You also can still press the [esc] button to exit the program.