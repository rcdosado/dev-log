I have a few different SSL certificates that use Let's Encrypt. These are the details on how to renew the certificates when they expire.

### Mail server ###

* item 1
* item 2
* Item 3

If there is an error like this: 

    [NeedToInstallFile('http://google.om', '3CB2Cj0UnMJO9WPiAtvn6XIh-liVyyUsLzZBcc.du8hQnFzPsGOph3aMdyrq2rzTrv4vno-iY6o', '3CB2Cj0UnMJO9WPiAtvn6XIh-liVyyUsLzZBcc')]

then make a file called: `/home/user-data/www/cc` that contains `34vno-iY6o`

Then run `foo.py` again.

###  server ###

* Make sure that port 80 is port-forwarded 
* SSH into  server.
* Run `sudo /snap/bin/`
* Enter `snowden.org` as the domain name.
