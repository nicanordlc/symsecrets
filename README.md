# symsecrets

[Main Fork](https://github.com/nicanordlc/symsecrets) 👈

Encrypt files with your GPG key and version control them.

> [!TIP]
> Use this repo in combination with [symfiles](https://github.com/nicanordlc/symfiles)
> to setup the secrets on the system.

## Bootstrap

This will initialize `symsecrets` on `~/projects/secrets`.

Provide your `GIT_USERNAME` and `GIT_REPO` after forked.

```bash
GIT_USERNAME="" \
GIT_REPO="" \
bash -c "$(curl -fsSL https://raw.githubusercontent.com/nicanordlc/symsecrets/refs/heads/main/src/install-remote.sh)"
```

## Usage

```txt
make <command>
```

### Initialization

- init

### Crypto

- encrypt
- decrypt
- update

### Git Management (dots)

- show
- diff
- clean
