### ssh writeup

## hotlocalbyte

_To find the secure little pathway from your remote machine to your local system is an incredibly easy_


Essentially connecting to your VM will comprise _of...
*Enumerating your network
*Turning the SSH service on
*Connecting via command line

#___________________________________

-First command you will be running will be [netstat](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/netstat)
in order to see if the service is even running. If you see that the service is not running continue.

-Next we use the [systemctl](https://www.freedesktop.org/software/systemd/man/systemctl.html) command to actually start the service

-Lastly with the ssh service turned on we can use ssh -*"ssh remote_user@X.X.X.X"*_




