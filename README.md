# demo-secrets
Skeleton project demonstrating the use of [git secrets](https://git-secret.io/) on the Engi network.

This repo contains a secret `.env` file that can only be revealed with a known set of PGP private keys:

```bash
$ git secret whoknows -l
circleci@engi.network (expires: 2024-12-05)
```