# Gogs

Gogs is used for local git. This is in an effort to move away from hosted providers, like github

## Installation

When installing, it's assumed that mysql / mariadb is already configured. It should have a user `gogs` with no password, with permission to write the database `gogs`

A directory `/var/gogs` should be created, which will be mounted by the `gogs/gogs` container
