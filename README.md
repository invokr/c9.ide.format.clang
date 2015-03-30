c9.ide.format.clang
===================

This plugins adds a new formater to C9 based on clang-format.

Requirements
------------

 * clang-format

Installation on a local c9v3 instance
-------------------------------------

 * Install the cloud9-sdk as per the instructions in the official repository
 * Install clang-format on your platform
 * Add the plugin to `<c9-sdk-foler>/configs/client-default.js` (e.g. in line 289)

Installation on c9.io
---------------------

Run the following in `~` (via the c9 terminal):

    # Install native dependencies
    sudo apt-get install clang-format-3.5

    # Install the plugin
    mkdir ~/.c9/plugins && git clone https://github.com/invokr/c9.ide.format.clang ~/.c9/plugins/c9.ide.format.clang

    # Start cloud9 in debug mode to activate the plugin
    https://ide.c9.io/[username]/[project]?sdk=1&debug=2

License
-------

c9.ide.format.clang is licensed under the AGPL version 3