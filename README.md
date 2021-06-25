# gogarchiver
A simple yet powerful script for archiving or just downloading games off of GOG.  
Help is included in the script (run it with `--help` or `-h`).

## Prerequisites:
* bash (package `bash` on most distributions)
* perl (package `perl` on most distributions)
* wget (package `wget` on most distributions)
* jq (package `jq` on most distributions)
* A GOG authorization cookie (open firefox, log into GOG, open developer tools, navigate to the 'Storage' tab, find the `gog-al` cookie, and copy its value into a file called `authorization.txt` in the same directory as the script).
* A list of game IDs to archive (you can get the IDs on https://www.gogdb.org/, but your account still has to have the games in its inventory, even if they're free)
* You're usually also goint to need a computer and an internet connection for this

## Available on:
* https://git.zajc.eu.org/gogarchiver.git/
* https://github.com/markozajc/gogarchiver/
