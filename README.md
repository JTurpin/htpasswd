# htpasswd

### Usage
To generate a password file:

`docker run --rm -ti jturpin/htpasswd <username> <password> > htpasswd`

This will use bcrypt encryption.
