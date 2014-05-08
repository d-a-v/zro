zro
====
Set root fs in read-only mode and keep selected
directories in read-write mode in a compressed ram fs. 
Those directories can be on-demand-synchronized to the
real fs.
While in r/w mode, the 'show-access-w' command
helps choosing which directories should be kept r/w.
This is designed so far on and for raspbian.

raspbian repository available at
	http://debian.unixrox.net:81/debian
