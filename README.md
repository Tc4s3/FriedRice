# FriedRice
 A hacky method for slightly quicker i3wm ricing.

 # What is Fried-Rice?
 fried-rice is a collection of bash scripts and config files i bundled together to allow for
 quickly switching between themes in i3wm & my chosen bar polybar, my launcher rofi &
 my tmux config.
 The bash scripts are a few quick and dirty solutions aided by some vibe coding that 
 replace your current config files with prewritten alternate files themed however you desire.
 The structure is as follows:
 In the top of the fried rice dir are two dirs newconfigs, containing "prebaked" configs for 
 your chosen bars, apps and i3 conf and oldconfigs, with the sub directory oldold which stores 
 a backup of your previous settings from the last two changes.
 The parent script "themeschange.sh" stores a list of all of your configs saved in "newconfigs"
 you can edit and update that when executed asks you to pick a theme from the database and 
 runs a child script, "set-theme.sh" your prebaked files from "newconfigs/**" 
 to the required directories, runs my polybar boot script (replace with your relevent script) 
 and prompts you to restart i3wm to apply the changes fully.
 Its a super dirty solution made by someone without advanced skills and requires you to change
 anything you need to make it fir yourset up.
 Its claled fried rice cause like good fried rice its real cooked lol.
 Feel free to fork this project, improve, cause frankly the onyl way is up, and hack on this to 
 make it work for your rice, i have zero maintenance intentions and purely made this for personal
 use and figured someone might find it a usefull starting point or be a reprobate like me and 
 just work with it as is lol.
 Enjoy your rice!
