# rssntfy.sh

A POSIX-compliant shell script to get ntfy.sh notifications when an RSS feed updates.

How to use:
Call the script with URL to an RSS feed (or multiple). It will check the most recent item with it's own file-based storage. If the latest item is not found, it will send a notification to a ntfy server.

Requires:
- curl

Tested on:
- MacOS
- Linux
- FreeBSD
