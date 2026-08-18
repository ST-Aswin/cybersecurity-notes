# Curl

## What is Curl ?
   cURL is a open source command line interface tool and a library used to send data to and from using
   uniform resource locator(URL) .curl stands for `Client URL` .and it is widely used by developers to 
   interact with api , to download files and to test the network services from the terminal wihtout 
   the need of gui environment.

## How to use ? 
``` bash
#basic use
❯ curl https://example.org/index.html -o index.html #This downloads the website's html to your local machine
❯ curl -V #prints the version of the curl
#config
❯ curl -K [file] #Short option used to specify the Config file
❯ curl --config [file] #Long Option used to specify the Config file

#passwords 
❯ curl -u name:password #you can pass passwords to curl for credentials by using the option -u

#progress-meters
# Curl will show the progress by default unless the flags `-s , --silent or --no-progress-meter` is used .
# The hash '-#' or '--progress-bar' will show the progress bar instead of defalt information's.
```
* Example
```bash
#Default
❯ curl https://docstore.mik.ua/orelly/unix/sedawk/ch01_01.htm  -o ch01.html
  % Total    % Received % Xferd  Average Speed  Time    Time    Time   Current
                                 Dload  Upload  Total   Spent   Left   Speed
100  14627   0  14627   0      0  10802      0           00:01          12404
#progress-bar
❯ curl https://docstore.mik.ua/orelly/unix/sedawk/ch01_01.htm  -# -o ch01.html
 -=#=- #     #       #   
```

## Supported Protocols

- HTTP
- HTTPS
- FTP
- FTPS
- SCP
- SFTP
- SMTP
- IMAP
- LDAP
- MQTT
- SMB

## Common Use Cases

- Download files
- Test REST APIs
- Debug web servers
- Check HTTP headers
- Upload files
- Automate scripts

## Related Commands

* wget
* ping
* dig
* host
* nslookup
* ssh
* scp

