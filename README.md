Hello I'm Acaard :D

This is an ansible playbook I made to automate whenever I need to deploy a new machine because I HATE doing stuff, so I made this small playbook to automate some stuff in the machine I deploy (because I break them a lot :P) such as terminal stuff, looks, themes, icons, fonts, tools, etc...

### How to use:
- This is for parrot machines (or any machine running mate DE).
- Install ansible using `sudo apt install ansible`.
- Do a `sudo whoami` to get a sudo token.
- Lastly just do `ansible-playbook main.yml` inside the directory.


## Stuff to note:
- It's better to run this on a fresh install and NOT your system, because it will overwrite a LOT of stuff.
- Most of the stuff here you can take and edit slightly, for example the wallpaper, you just need to change it in `roles/customize-system/files/` but make sure it's called `Wallpaper.jpg`.
- Same applies to .bashrc, and terminal config and so.
- IMPORTANT: when you first run the playbook your terminal will look waky, and so messed up, this is due to font changes, so after you run the script you need to reboot and THEN you can choose the new terminal profile and everything will look just good :D.

## Credits
Thanks to [ippsec](https://www.youtube.com/@ippsec) his series helped me build this, especially the burpsuite and dconf section because it was a PAIN, so thanks again :D
