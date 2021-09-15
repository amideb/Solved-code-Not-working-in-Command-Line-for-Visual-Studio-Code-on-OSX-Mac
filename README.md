1799

1. Make sure you drag Visual Studio Code app into the -Applications- folder
Otherwise (as noted in the comments) you'll have to go through this process again after reboot

2. Next, open Visual Studio Code
Open the Command Palette via (⇧⌘P) and type shell command to find the Shell Command:

Update: use Uninstall 'code' command in PATH** command before
> Install 'code' command in PATH** command.
![Command Palette

After executing the command, restart the terminal for the new $PATH value to take effect. You'll be able to simply type 'code .' in any folder to start editing files in that folder. The "." Simply means "current directory"
