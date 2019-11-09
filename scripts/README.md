# scripts

This is mostly a collection of useful scripts for starting up new RPI TV servers.

Many of these are usable via something like:

```bash
wget https://rpitv.github.io/scripts/foo
chmod +x foo
./foo
```

or even one-liners like:

```bash
bash <(curl https://rpitv.github.io/scripts/foo)
```

## Available tools

[install_keys](install_keys) downloads and installs the [ssh_public_keys](ssh_public_keys) file. **This overwrites any existing authorized keys for root!** This is by design so old keys don't get left around.
