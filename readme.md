README
======

Bash script to update the ip of an account on no-ip.com

How to use
----------

* Create $HOME/.noipupdater/noipupdater.conf and add there USERNAME, PASSWORD and HOSTNAME
* Run it (`./noipupdater`)
* Log files will be kept in $HOME/.noipupdater/log

Tips!
-----

Place this in your cron file:

    */15 * * * * /dir/where/file/is/noipupdater

This will run the script every fifteen minutes.

Happy updating!
