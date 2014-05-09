zro
====

Set root fs in read-only (-O) mode and keep selected
directories in read-write (-a) mode in a compressed ram
fs.

Those directories can be on-demand-synchronized (-S,
-A) to the real fs.

While in r/w mode, the 'show-access-w' command
helps choosing which directories should be kept r/w.

This is so far designed on and for raspbian.

raspbian repository available at
	http://debian.unixrox.net:81/debian
