# Kumiko Live! OBS files
[![Chat](https://discord.com/api/guilds/813738237864312842/widget.png?style=shield)](https://discord.gg/jt4dpvzA58)
[![YouTube](https://img.shields.io/endpoint?url=https%3A%2F%2Frunkit.io%2Fsuk0m8u%2Fyoutube-subscribers-badge%2Fbranches%2Fmaster%3Fid%3DUCGcClcnm7Y0-jWSeSV5xnKw%26key%3DAIzaSyDmc6HmurAU4Hf5WvuxSTsym18SjR7fguc)](https://www.youtube.com/channel/UCGcClcnm7Y0-jWSeSV5xnKw)

## About
This repository contains all [OBS](https://obsproject.com) files of [Kumiko Live!](https://Kumiko.Live)

## Used software
 - [OBS](https://obsproject.com) 27.1.3

## How to clone
 1. Clone this repository.
 2. Add all filters by issuing the following commands:
 ```bash
 git config filter.ignorelines.clean "grep -Evi \$(cat .gitignorelines | tr -d '\r' | sed -z '$ s/\n$//' | tr '\n' '|')"
 git config filter.ignorelines.smudge "cat"
 ```
 3. Create an Symlink at `%APPDATA%\obs-studio` on Windows or `~/.config/obs-studio` on Linux, that points to your cloned repository's working directory.

## License
Please don't use it without explicit permission.

## Credits
 * Please check the commits for further details.
 * [Git repository](https://github.com/Kumiko-Live/obs.git)
