# plex

To start the container with default config :
```bash
docker run -d --net="host" plex
```

But you can also use your local datastore :
```bash
docker run -d --net="host" -v <your local datastore>:/data plex
```

