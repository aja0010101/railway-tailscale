<h1 align="center">Welcome to railway-tailscale 👋</h1>
<p>
  <a href="https://twitter.com/fuergaosi" target="_blank">
    <img alt="Twitter: fuergaosi" src="https://img.shields.io/twitter/follow/fuergaosi.svg?style=social" />
  </a>
</p>

> Run tailscale on railway.app
> Thanks to @mvisonneaue for creating tailscale image.

## How to use this repo

1. Fork this repo.
2. Create New project in railway.app via this repo.
3. Config Env.

```env
TAILSCALE_AUTH_KEY=<Your Auth Key>
# Use Railway as exit node
TAILSCALE_ADVERTISE_EXIT_NODE=true
```

> How to get [AuthKey](https://tailscale.com/kb/1085/auth-keys/)

## Show your support

Give a ⭐️ if this project helped you!