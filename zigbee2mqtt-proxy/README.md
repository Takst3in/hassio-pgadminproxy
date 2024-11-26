# Home Assistant Add-on: PgAdmin Proxy

⚠️ This addon does not contain PgAdmin ⚠️

This addon acts as a proxy to an external running PgAdmin instance. 
The sole purpose of this addon is to add a PgAdmin icon to the sidebar of Home Assistant which will open the frontend of an external running PgAdmin instance.

## Options

- `server` (required): this should be the local URL on which the PgAdmin frontend is running, e.g. `http://192.168.2.43:8080`. Make sure there is no trailing slash!
- `auth_token` (optional): only use when you have an `auth_token` set for the frontend in the PgAdmin configuration.