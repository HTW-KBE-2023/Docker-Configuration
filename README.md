# Docker-Configuration

This Repository contains all Projects to start the Multi-Bot System.
It contains at the moment:

- The RPG-Service
- Survey-Service
- API-GateWay

The above listed Modules are imported as a git-submodule.
To update all Submodules use the command:

```console
git submodule update --recursive --remote
```

Aditional there is a compose-file to start all Services with Docker.
To use that script just execute...

```console
docker compose build
```

... and...

```console
docker compose up
```

... to start all Services and with...

```console
docker compose down
```

... they will get cleaned up.
