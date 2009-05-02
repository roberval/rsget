rsget
====

A RapidShare downloader for premium users.

Dependencies
------------

 * A premium account from RapidShare
 * Python URLGRabber

Configuring rsget
-----------------

Just set your user and password:
   
    _user = ""
    _pass = ""

Using rsget
-----------

rsget options:

    -f <file>	file with urls
    -d <directory>	target directory
    -u <url>	a url to download
    -t <num>	number of threads to use (default = number of files to download)
    -l <num>	the total bandwidth limit (KB/second, default = 0 [unlimited])
    -U <str>	rapidshare username
    -P <str>	rapidshare password

The file with urls accept comments (lines starting with #).
