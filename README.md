# onionator
Automation script for setting up .onion sites on Debian-based Linux.

Current minimal testing, use at your own risk. Software versions may be easily modified with their current version(s) in the top `export` section. Users may designate different base servers for download. All files are downloaded to `~/build/` (which is removed on completion), and installed to `~/apache/` and `~/tor/` respectively. The onion hostname address file and private key are copied to `~` upon successful completion. This facilitates easy offsite backup of the files.

Usage:

`cd ~`

`wget https://github.com/kvesel/onionator/onion`

`chmod 700 ./onion`

`./onion`

All html documents should be placed in `~/html/`
