# onionator
Automation script for setting up .onion sites Linux.

Current minimal testing covers Debian 8/9, Fedora 23/24/25/26 and Whonix 13/14. Use at your own risk.

Software versions may be easily modified with their current version(s) in the top `export` section.
Users may designate different base servers for download.
The package is installed to the current directory, and parts of it may require sudo to run apt-get/dnf.
All files are downloaded to `build/` (which is removed on completion), and installed to the current directory.

The onion hostname address file and private key are copied to `./` upon successful completion.
This facilitates easy offsite backup of the files.

## Install
`wget https://github.com/kvesel/onionator/onion`

`chmod 700 ./onion`

`./onion`

## Run
All html documents should be placed in `./html/`

Services will not start on boot, you must run the `start` script.
