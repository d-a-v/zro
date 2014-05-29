	This is designed to allow running a read-only root
	filesystem while keeping some r/w locations (/tmp,
	var/log, ...).  It might be useful on embedded systems. 
	Compared to tmpfs, ram data are compressed, and an
	effort is done to allow synchronisation of the ram data
	onto the real filesystem.  This is not automatic
	though, processes keeping opened files needs to be
	cleanly stopped for syncronisation and restarted after.
	
	This is combining unionfs-fuse, btrfs and tmpfs.

	This is so far designed on and for debian derivatives.
