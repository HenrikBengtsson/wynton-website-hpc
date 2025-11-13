# Installing Quarto

## Ubuntu 24.04 / Debian-based Linux

Download and install Quarto from the official releases:

```sh
$ cd /tmp
$ wget https://github.com/quarto-dev/quarto-cli/releases/download/v1.4.554/quarto-1.4.554-linux-amd64.deb
$ sudo dpkg -i quarto-1.4.554-linux-amd64.deb
```

Verify the installation:

```sh
$ quarto --version
1.4.554
```

Then navigate to the docs directory and preview the site:

```sh
$ cd docs
$ quarto preview
```

Last verified: 2025-11-12


## macOS

Download and install Quarto from the official website:

```sh
$ brew install quarto
```

Or download the macOS installer from: <https://quarto.org/docs/get-started/>


## Windows

Download the Windows installer from: <https://quarto.org/docs/get-started/>


## Alternative: Download Pre-built Binary

You can also download pre-built binaries for any platform from:
<https://github.com/quarto-dev/quarto-cli/releases>

Extract the archive and add the `bin` directory to your PATH.
