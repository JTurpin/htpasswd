# htpasswd

###Usage
To generate a password file:

`docker run --rm -ti xmartlabs/htpasswd <username> <password> > htpasswd`

This will use bcrypt encryption.
