![Vinylidene](http://i.imgur.com/gTMlEhK.png)

Vinylidene is the next generation music streaming service, servicing pony related artists and simular over a secure distribution network provided by the community, powered by a master server and MySQL.

Directory Listing
----------------

* client/ - The client, written in C++ and uses QT.
	* libs/ - Required libraries
	* README.md - Readme for that part of the project in particular.
* cdns/ - Content Distribution Network Server, serves the secure music streams themselves.
	* libs/ - Required libraries
	* README.md - Readme for that part of the project in particular.
* masterserver/ - Master Server, the backbone that selects a suitable CDNS, hosted by Cloud Chiller
	* libs/ - Required libraries
	* README.md - Readme for that part of the project in particular.
* randumbstuff/ - You know, images and shit.
* docs/ - Documents related to the project (documentation, RFCs etc.)
	* permissions.ods - All Permissions gathered. (Yes, it's an OpenDocument
	* NetworkConcept - Pretty ASCII art about the Networking
* LICENCE.md - Guess.
* README.md - This document, silly!
* .gitignore - Specifies what files to get ignored by GIT.
