# Description

This role configures [tt-rss](https://tt-rss.org/) - a Web UI RSS reader.

It uses an [`linuxserver/tt-rss`](https://hub.docker.com/r/linuxserver/tt-rss/) docker image.

# Configuration

```yaml
tt_rss_db_user: db-user
tt_rss_db_pass: db-secret-pass
```

# Usage

The default authentication details after installation are:

* Username: `admin`
* Password: `password`

Change them right away.
