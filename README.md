# Description

This repo contains canon printer drivers for Ubuntu and a script to set them up.

I just used it on Ubuntu 23.04 (64bit) and saving it now since links use to rot from time to time.
I'm also saving here other versions of drivers but one need to update script if wants to use them.
Script downloads different versions using dead links so you need to put correct driver in folder
and maybe change file names in the script.

Have fun!

# Usage

`git clone ...`

Put drivers of version you need in script folder and update file names in the script.
I guess vars you may need to update are `DRIVER_VERSION`, `COMMON_FILE`
(its version may be different that capt file version), `CAPT_FILE`.

# Important

When trying to print make sure you use A4 paper in print task!
If it still doesn't print use `sudo captstatusui -P LBP-1120` to see the problem.
