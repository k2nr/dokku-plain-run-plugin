# Dokku Plain Run Plugin

`dokku run` executes `docker run` with flags `-i -t`.
The flags is not need if you just want to run a single command inside a container.

This plugin provides `dokku plain-run` command which is nearly same as `dokku run` but without the flags.

## Install

```
git clone https://github.com/k2nr/dokku-plain-run-plugin.git /var/lib/dokku/plugins/plain-run
```

## Usage

```
dokku plain-run APP COMMAND
```

## License

The MIT License (MIT)

Copyright (c) 2014 Kazunori Kajihiro
