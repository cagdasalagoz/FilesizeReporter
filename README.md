# FilesizeReporter
I love keeping my photo and videos safe and secure at DVDs. So I weekly copy the photos to my computer but i need to know when i should burn a DVD. So this bash script checks when i need a CD or DVD. 

So i wrote this bash script for tracking the folder for me.

**Dependencies**

1. inotify [Man Pages](http://man7.org/linux/man-pages/man7/inotify.7.html)
2. libnotify - Notification tool for linux. [Arch Repo](https://www.archlinux.org/packages/?name=libnotify)

**How to use**

1. Set the FOLDERPATH variable to the path you wanted to track.
2. Make file executable.
3. Run ./sizechecker
