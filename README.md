A simple renaming webapp in order to help coworkers generate regex for file renamers like [PowerRename](https://learn.microsoft.com/en-us/windows/powertoys/powerrename).

## Instructions

### Generating your filenames

1. Input your project title in "Project Title". It will be added to the filename without capitals and with hyphens for spaces.
2. Choose the date that your media was captured, or whichever date you'd like to add in the filename.
3. Choose which department these files are relevant for: Housing & Conference Services, or Conference & Event Services.
4. Choose whether your numbering will start at 1 or not. Otherwise, choose which number it will start at (not inclusive - if you have 14 photos already, start at 15).

![Completed sample usage](/images/step4_instructions.png)

When completed, you'll see the text that you'll copy into PowerRename be generated.

![PowerRename Instructions for Windows Explorer](/images/step7_instructions.png)

### Using PowerRename with your patterns

Open Windows Explorer, and find the files you'd like to rename. Select them, and then right click your mouse.

Click "Rename With PowerRename" (see below).

![PowerRename Instructions for Windows Explorer](/images/step6_instructions.png)

1. In PowerRename, make sure that "Use regular expressions" is checked (1, below).
2. Copy the PowerToys PowerRename "Search for" pattern into the appropriate field (2, below).
3. Then, copy the PowerToys PowerRename "Replace with" pattern into the appropriate field (3, below). 

![PowerRename Instructions for Windows Explorer](/images/step8_instructions.png)

Press "Apply" (4, above) and your files will be renamed.
