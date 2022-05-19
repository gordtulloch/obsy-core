# obsy-core
Open Source Observatory Management Software (python core)

This repository will contain Python code used to run the OBSY observatory management system integration with INDI and external hardware / software using PyINDI and DBUS access to other tools. It communicates with the core OBSY database for task management and storage. The repository obsy-web is an HTML5 based user interface that provides all user interface functions for OBSY that must be installed seperately (and in fact doesn't even need to be on the same computer as obsy core. Similarly, obsy-core can operate multiple INDI servers for a truly networked solution.
