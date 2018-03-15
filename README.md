# onionator
Automation tool for setting up .onion sites on a Raspberry Pi (et al.).

Current minimal testing, use at your own risk. Software versions may be easily modified with their current version(s) in the top `export` section. Users may designate different base servers for download. All files are downloaded to `~/build/` (which is removed on completion), and installed to `~/apache/` and `~/tor/` respectively. The onion hostname address file and private key are copied to `~` upon successful completion. This facilitates easy offsite backup of the files.

Usage:

`cd ~`

`wget https://github.com/kvesel/onionator/onion.sh`

`chmod 700 ./onion.sh`

`./onion.sh`

All html documents should be placed in `~/html/`
