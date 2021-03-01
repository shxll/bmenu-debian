Bash based system menu for ~~arch linux/manjaro~~ ubuntu/debian

**This repo has been forked to be used with Debian based systems. It is not verified that bmenu for debian will be supported for all systems.** Here are a list of changes:

1. PacUI has been replaced with Aptitude
2. There is no found (tui) time manager, so Calcurse, a calendar has replased Timeset.
3. lynx is now the only cli browser, all other ones are not able to work
4. Auto installing is not known to work for now
5. There is no found (tui) hardware manager, so s-tui, a hardware viewer has replaced hw-tui.
6. Devices without SystemD may not work with the network manager.
7. For file search, if you already have rifle, you mist install fzf.

*More updates may come soon*

To install, ```git clone``` the repo, ```cd bin```, and run ```bmenu```.
