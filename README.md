<h1><p align="center">Hurl.dev API Testing 🪷</p></h1>

<p align="center"><img src="https://raw.githubusercontent.com/Orange-OpenSource/hurl/master/art/logo-full-dark.svg?sanitize=true#gh-dark-mode-only" alt="Hurl Logo" width="264px"></p>


This project is an API Testing example using [Hurl.Dev Framework](https://hurl.dev).

## Features 🧪

-   Hurl.dev framework
-   HTTP Requests

# Installation 🚀

## Binaries Installation

### Linux

Precompiled binary is available at [hurl-1.6.1-x86_64-linux.tar.gz]:

```shell
$ INSTALL_DIR=/tmp
$ curl -sL https://github.com/Orange-OpenSource/hurl/releases/download/1.6.1/hurl-1.6.1-x86_64-linux.tar.gz | tar xvz -C $INSTALL_DIR
$ export PATH=$INSTALL_DIR/hurl-1.6.1:$PATH
```

#### Debian / Ubuntu

For Debian / Ubuntu, Hurl can be installed using a binary .deb file provided in each Hurl release.

```shell
$ curl -LO https://github.com/Orange-OpenSource/hurl/releases/download/1.6.1/hurl_1.6.1_amd64.deb
$ sudo dpkg -i hurl_1.6.1_amd64.deb
```

#### Arch Linux / Manjaro

[`hurl-bin` package] for Arch Linux and derived distros is available via [AUR].

#### NixOS / Nix

[NixOS / Nix package] is available on stable channel.

### macOS

Precompiled binary is available at [hurl-1.6.1-x86_64-osx.tar.gz].

Hurl can also be installed with [Homebrew]:

```shell
$ brew install hurl
```

### Windows

#### Zip File

Hurl can be installed from a standalone zip file [hurl-1.6.1-win64.zip]. You will need to update your `PATH` variable.

#### Installer

An installer [hurl-1.6.1-win64-installer.exe] is also available.

#### Chocolatey

```shell
$ choco install hurl
```

#### Scoop

```shell
$ scoop install hurl
```

#### Windows Package Manager

```shell
$ winget install hurl
```

### Cargo

If you're a Rust programmer, Hurl can be installed with cargo.

```shell
$ cargo install hurl
```

### Docker

```shell
$ docker pull orangeopensource/hurl
```

### npm

```shell
$ npm install --save-dev @orangeopensource/hurl
```

## Building From Sources

Hurl sources are available in [GitHub].

### Build on Linux, macOS

Hurl depends on libssl, libcurl and libxml2 native libraries. You will need their development files in your platform.


#### Debian based distributions

```shell
$ apt install -y build-essential pkg-config libssl-dev libcurl4-openssl-dev libxml2-dev
```

#### Red Hat based distributions

```shell
$ yum install -y pkg-config gcc openssl-devel libxml2-devel
```

#### Arch based distributions

```shell
$ pacman -Sy --noconfirm pkgconf gcc openssl libxml2
```

#### macOS

```shell
$ xcode-select --install
$ brew install pkg-config
```

## Getting Started

Running tests:
```bash
hurl file.hurl
```

## Contributing 👨‍💻🤝

Feel free to complement/report something in pull requests. The project is ours! 🤝

