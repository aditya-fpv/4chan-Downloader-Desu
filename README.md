# 4chan-downloader-desu

A simple script to scrape images and webms from 4chan.org threads. Just paste thread url and start downloading. Only available on linux, comment if you want me to port it to windows or add a feature(like preserve original filename, download only specific file types etc).

You will be prompted to input thread url and create a folder in $HOME/Downloads, which is the default save path.

The script can be called like this: `$ bash /path/to/4DD`.
Add `4DD` in /usr/local/bin(which should be in $PATH,type `echo $PATH` in terminal to check if it is) and make the script executable systemwide without specifying it's path everytime. More info on that [here](https://www.maketecheasier.com/make-scripts-executable-everywhere-linux/).

## Syncing

Enter "y" and input directory name if you want that directory to sync to its thread. All the newly added content on that thread will be downloaded.

## DEPENDENCIES:
This script needs following python libraries to function:

[**beautifulsoup4**](https://pypi.org/project/beautifulsoup4/) - install with `$ sudo pip install beautifulsoup4`

[**argparse**](https://pypi.org/project/argparse/) - install with `$ sudo pip install argparse`

[**lxml**](https://pypi.org/project/lxml/) - install with `$sudo pip install lxml`
