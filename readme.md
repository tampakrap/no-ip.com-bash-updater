README
======

Bash script to update the ip of an account on no-ip.com

How to use
----------

* Copy noipupdaterrc.sample to $HOME/.noipupdaterrc
* Fill in the variables in .noipupdaterrc accordingly
* Run the script (`./noipupdater`)
* Log files will be kept in $LOGDIR/noipupdater.log

Tips!
-----

Place this in your cron file:

    */15 * * * * /dir/where/file/is/noipupdater

This will run the script every fifteen minutes.

Happy updating!
