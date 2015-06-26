Docker image for building RPMs and DEBs using fpm.

## Usage example
Build docker container using script **build-docker** script.
Then use script **mkdeb** to build your own deb from directory:

```
mkdeb -s /mytools -v 0.1.2 -n mytools
```

This will build deb archive from files located in /mytools directory and will save it in /tmp/mytools.

