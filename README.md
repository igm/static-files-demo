# static-files-demo
Demo to publish static web pages to the PWS using https://github.com/igm/noop-buildpack 

Start script starts simple python web server already included in CF Warden container:
```sh
$ python -m SimpleHTTPServer $PORT
```

see https://github.com/igm/static-files-demo/blob/master/.profile.d/start.sh for a complete bootstrap code.
