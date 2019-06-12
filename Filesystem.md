## [/dev/null Concept](https://prayuja-teli.github.io/Blog/Filesystem)     

/dev/null is null device in unix system  and immediately discards anything written to it.
The null device is a device file that discards all data written to it but reports that the write operation succeeded. 
This device is called /dev/null which also sends End of File character to any process reading data from it.
/dev/null is the most commonly known /dev/ device file. 
Obviously, this is a file named "null" that is in the "/dev/" directory.
The "/dev/" directory is a mountpoint for the devfs (Device Filesystem) pseudo-filesystem.
devfs is a device manager in the form of a filesystem that displays each device as files. 
This pseudo/virtual filesystem is not on the hard-drive. Rather, it is in memory.
The null device is typically used for disposing of unwanted output streams of a process.
/dev is directory,null is file in /dev directory which is used to get output from or to redirect output to this file.
mainly eliminating output from terminal.
There are three symlinks in dev directory stderr , stdin , stdout and null is filetype where this symlinks directs.
they are type c - character device./dev/null accept any stream without growing in size. 
it's size is always zero.A symbolic link, also known as a symlink or a soft link, is a special kind of file (entry) that points
to the actual file or directory on a disk (like a shortcut in Windows). 
Symbolic links are used all the time to link libraries and often used to link files and folders on mounted NFS 
(Network File System) shares.These are stdin (standard input, file descriptor 0), stdout (standard output, file descriptor 1) 
and stderr (standard error, file descriptor 2).A file descriptor is a number that uniquely identifies an open file in a 
computer's operating system.






