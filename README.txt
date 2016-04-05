# dnsmassdelete

dnsmassdelete -- composes a list of commands to delete mass amounts of DNS entries using nsupdate.

## Installation

1. Download
2. chmod +x dnsmassdelete
 

## Usage

1. './dnsmassdelete inputfile.txt'
2. 'inputfile.txt' should have a line by line by line layout of '192.168.1.1 dnsname.com'

## About

1. dnsmassdelete simply finds PTR and A entries from your current DNS. This script utilizes the linux-based dig command and outputs the 'answer section' from the current dig.
2. Syntax can be modified in the script to get more or less information. 
3. For more information on dig if you are not familiar, see 'http://linux.die.net/man/1/dig'.
