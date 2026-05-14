# rocamar

Astro static landing for the Rocamar beach rental. Served from CT 127 (rocamar-prod) behind aws-traefik at https://rocamar.retailyx.com/.

## Deploy

On rocamar-prod as the `rocamar` user:

```
~/deploy.sh
```

(That pulls main, installs deps if package files changed, builds, and atomic-rsyncs `dist/` to `/var/www/rocamar/`.)
