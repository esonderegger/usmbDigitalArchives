usmbDigitalArchives
===================

A web application for accessing the Marine Band's audio and video assets

This is a collection of setup scripts and code used for the Marine Band's reference web server. This is probably too single-purpose to be useful to anyone, but I wanted to open-source it before leaving the organization.

Features
--------

- Maintain a searchable archive of rehearsal recordings, stored on an accessible network share.
- Maintain a searchable archive of finished audio recordings, with metadata coming from tab-separated text (.ttx) files.
- Ingest preservation audio by encoding WAV files to MP3, embedding ID3 tags with information from the ttx fles
- Maintain a searchable archive of finished video recordings, with metadata coming from tab-separated text (.ttx) files.
- Provide a mobile-responsive web interface to those searchable archives
- Provide a mobile-reponsive web interface to reference files that are not tracked by the database
- Provide an admin interface for adding/deleting users and importing more metadata ttx files.

Installation
------------

Since this is currently only running on one server, it has been put together in an ad-hoc manner. Adding an automated installation script is on the todo list.

Contribute
----------

- Issue Tracker: github.com/esonderegger/usmbDigitalArchives/issues
- Source Code: github.com/esonderegger/usmbDigitalArchives

Support
-------

If you are using part or all of this project, please let me know by submitting an issue on the github project.

License
-------

The project is licensed under the MIT license. Much of the work was done as in a work capacity as a member of the United States Marine Band, so it really should be in the public domain. However, I don't know of a commonly used LICENSE file for public domain. If there is one, please let me know.
