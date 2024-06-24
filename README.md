# fly-mongodb

Proof of concept hosting mongoDB on https://fly.io.

Change the name and use `fly deploy` to deploy.

This one uses a really old rubbish version because the software we rely on is also bad and old. You can set the version in `image` under `[buid]` based on versions published on Docker: https://hub.docker.com/_/mongo

If you have money, change the machine size to use more RAM to avoid the pain of swap. 
