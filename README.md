# WHAT IS THIS?
This is an online archive of definitions and mods for **MechanicMonke**, an experimental successor to MonkeModManager. MechanicMonke gets it's definitions online, just like MonkeModManager, but it needs a place to get them from.

# ADD MY MOD!
Send us a PR with the correct syntax. Here is a rundown:

NOTE: anything with 3 astericks (```*```) before it is not real syntax, remove it when you send a PR.
```
{
        "name": "Mod Name",
        "author": "You",
        "filenames": [
            "modname-1.0.dll",
            "modname-1.1.dll",
            "modname-1.2.dll",
            *** PLACE YOUR KNOWN FILENAMES HERE! THIS IS FOR MOD AUTO-DETECTION !!! REMOVE THIS LINE BEFORE SENDING A PR LMAO ***
        ],
        "keyword": "modname", *** Place whatever the most used part of a filename is here, so if you have "modname" in all your release names, put it here
        "type": "Mod", *** "Mod" or "Library"
        "repo": "KyleTheScientist/Bark", *** Git repository
        "download": "https://link.com/link/link/link", ** Download link to your latest release (.dll or .zip)
},
```

## Add your custom lists
![image](https://github.com/user-attachments/assets/b44430b0-d6f3-4ad2-baba-b24140847a3b)
Press "Add" on the Catalogs menu and paste in the link to any valid *.json list. It will be validated on first run to ensure it works without issues.
If a list causes MM to crash, you can remove it manually with the ``lists.txt`` file in your Documents folder. lists.txt ignores comments ``#``.
