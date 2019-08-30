Teeworlds Server in Docker
==========================
Thanks to @Teyras!

QuickPlay
---------
Set server-console password to `mypassword` and run the server on `0.0.0.0:8303`.
```
docker run --rm -d -e TEEWORLDS_PASSWORD=mypassword -p 8303:8303/udp petrbel/teeworlds
```

Server Mode
-----------
Create a `teeworlds/` directory. Copy this `docker-compose.yml` and update the server-console password in the file.
```
docker-compose up -d
```

Build
-----
Dtto setup
```
docker-compose build
```
