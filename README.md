# onionator
Automation script for setting up .onion sites Linux.

Current minimal testing covers Debian 8/9 and Fedora 23/24/25/26, use at your own risk. Software versions may be easily modified with their current version(s) in the top `export` section. Users may designate different base servers for download. All files are downloaded to `~/build/` (which is removed on completion), and installed to `~/apache/` and `~/tor/` respectively. The onion hostname address file and private key are copied to `~` upon successful completion. This facilitates easy offsite backup of the files.

Usage:

`cd ~`

`wget https://github.com/kvesel/onionator/[VERSION]/onion`

`chmod 700 ./onion`

`./onion`

All html documents should be placed in `~/html/`
