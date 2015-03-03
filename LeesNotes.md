# Introduction #

Add your content here.


# Details #
connect using external ips (make sure they are port forwarded!)

gdb --args ./tryst daemon -l externalip:externalport -w localip:webport

(gdb) r

get from the web is not functioning.

MAJOR BUGS:

  1. doesn't provide information when download completes
> 2. segfaults when it can't resolve a host on connect.
> 3. We don't check the md5 for a file after we download it.
> 4. We send a filewith the same name even if the contents have changed.

MONOTONE: tutorial: http://monotone.ca/docs/Tutorial.html#Tutorial

  * other user does a monotone commit
  * export public key
  * send public key to other user for import
  * other user updates .monotone/read-permissions and .monotone/write-permissions
  * other user starts monotone server: mtn --db=DBNAME serve *** mtn sync SERVER**
  * mtn heads (get revision id)

if no conflicts then:

  * mtn update when in workspace to update files

else:

  * mtn merge when in workspace to update files