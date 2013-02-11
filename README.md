python-copy
===========

A quick-and-dirty copy command that shows progress.

Quick Format
============

It takes no command options.

'''
pycp [SOURCE] [DESTINATION]
'''

Source can be any number of files or directories.  The destination is a directory (if there are multiple
sources) or a filename (if the source is singular and a filename).  It doesn't currently like broken links, but it seems to do a decent job.
