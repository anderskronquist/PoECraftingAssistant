# CraftingBot
A lightweight and intuitive crafting bot for Path of Exile. To run, simply open the .jar file in the following directory after unzipping the downloaded folder:
Download: https://www.dropbox.com/sh/097x4ics3545g16/AAAqe-D01ZdO2J3mxXgs5S8Va?dl=1

### Getting Started: Creating Filters
Once the program is opened, you are presented with the GUI that all the filter creation and crafting is done in. To start, create a new filter by clicking the "New" folder in the top right. You will be prompted to name your new filter. After clicking "ok," you can rename this at any time by simply clicking the name of your filter in the top left. To create a new subfilter for this filter, click the white "+" button to the right of your new filter. A new subfilter appears. To edit this subfilter, click the white arrow to the right of the subfilter. By doing so, a new "And" filter appears on the right side of the screen.

Similar to the official trade site, the CraftingBot supports "And," "Not," and "Count" filters. You can effectively make an "Or" logic type by creating a new subfilter. To create a new modifier in a logic group, click the white "+" button to the right of the respective logic type. To change the modifier, click on the "new modifier" rectangle. You will be prompted to select a valid modifier. After clicking "ok," you can then change the minimum and maximum values needed for this modifier to be counted as "hit." If this is not applicable to the modifier you are using, you may leave it blank and it will be ignored. To create a new logic group, simply click the white "+" button on the bottom right of the screen. To change the type of logic filter, click on the logic filter titlebar and change it accordingly.

### Getting Started: Running the CraftingBot
After you have created a valid filter, move the window to the right side of your monitor, so that the currency stash tab you will be crafting in is open. Move the item you are crafting into the center slot of the stash tab. To start, simply click the orb of your choice on the bottom left of the screen. If at any time you want to stop crafting, simply hit the enter key. All crafting will be stopped. Once the bot hits a selected group of mods, it will automatically stop slamming the orb(s) on the item. If you want the bot to roll over the hit, simply click the orb of your choice again in the CraftingBot window.

### Saving and Opening Saved Filters
Filters are saved as you edit them automatically. They are saved to a subfolder in the "src" directory of the folder you downloaded. To quickly open this directory, click the "Folder" button on the top right of the CraftingBot window. To open one of these filters, click the "Open" button. Filters are saved with the extension ".cbfilter" for easy use. They are not editable outside of the program.