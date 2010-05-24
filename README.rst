===============
iphoneconverter
===============

As its name semi-suggests, iphoneconverter is a small Linux script that
uses Handbrake to convert a folder of videos into a format suitable for
the iPhone/iPod.

Usage
-----

To run iphoneconverter, just use the following command line::

    iphoneconverter "<show name>" <show directory>

iphoneconverter will automatically rename each episode to its proper
name, e.g. "Lost - S3E22 - Through the Looking Glass.mp4" and it will
also add the relevant iTunes information so the entire show will appear
properly in your iPhone, separated by show title, season and episode.
All the videos in the folder must be from the same show, otherwise the
renames will not be very fortunate.

Dependencies
------------

To run iphoneconverter, you need the command-line version of
`Handbrake <http://handbrake.fr/>`_,
`episode-renamer <http://github.com/skorokithakis/episode-renamer>`_
and `AtomicParsley <http://atomicparsley.sourceforge.net/>`_.

License
-------

iphoneconverter is made available under the GPL.

The script may be found at
`GitHub <http://github.com/skorokithakis/iphoneconverter>`_. Or it may not! Who knows?

