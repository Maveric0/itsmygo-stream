# itsmygo stream server

This repository only hosts releases of the itsmygo stream server: the `gdrive-stream` binaries for linux/amd64 and linux/arm64, the `install.sh` installer and `SHA256SUMS`. It contains no source code and no credentials.

Servers are installed with the one-use command generated in the itsmygo admin page, which downloads `install.sh` from a release and checks it against the digest held by the main site before running it. Installed servers upgrade themselves to the release the main site selects, after checking every file against the digests the main site verified.

Copyright © itsmygo. All rights reserved. The binaries are provided only for operating itsmygo stream servers.
