playlist2folder
===============

Simple script to take a playlist file and copy all the songs to a given folder

It was written to work with the .pl format that cmus uses (a list of fully qualified files). It should work with .m3u since I believe that also uses fully qualified file names just with additional metadata. The script ignores lines where a hash mark is the first non-whitespace character, and thus should skip .m3u metadata lines. It also has some built-in sanity checking to make sure the playlist exists, it skips empty lines, the destination folder does not already exist, and create any parent folders in the destination folder path if needed.
