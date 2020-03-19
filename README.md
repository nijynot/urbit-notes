# urbit notes

### Development environment

Install Linux or macOS (v0.10.4), go to https://urbit.org/using/install/ to find the latest version.
```bash
# Linux
$ curl -O https://bootstrap.urbit.org/urbit-v0.10.4-linux64.tgz
$ tar xzf urbit-v0.10.4-linux64.tgz
$ cd urbit-v0.10.4-linux64

# macOS
$ curl -O https://bootstrap.urbit.org/urbit-v0.10.4-darwin.tgz
$ tar xzf urbit-v0.10.4-darwin.tgz
$ cd urbit-v0.10.4-darwin
```

Set up a development planet/galaxy
```bash
$ ./urbit -F zod
```

Mount and unmounting home
```
~zod:dojo> |mount %
~zod:dojo> |mount /=home=
~zod:dojo> |unmount %
```

Commiting changes
```
~zod:dojo> |commit %home
```
