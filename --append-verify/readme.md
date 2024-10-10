https://www.google.com/search?q=rsync+continue+after+disconnect

https://unix.stackexchange.com/questions/48298/can-rsync-resume-after-being-interrupted
>So, to sum up, if you're moving large files and you want the option to resume a cancelled or failed rsync operation from the exact point that rsync stopped, you need to use the --append or --append-verify switch on the next attempt.
>
>As @Alex points out below, since version 3.0.0 rsync now has a new option, --append-verify, which behaves like --append did before that switch existed. You probably always want the behaviour of --append-verify,
