# VanPaitin Homebrew Tap

[uptimev](https://github.com/VanPaitin/uptimev) prints uptime and boot time in
plain English on macOS and Linux. Requires Bash 3.2+; Linux also needs GNU `date`
and a readable `/proc/uptime`.

## Install

```sh
brew install VanPaitin/tap/uptimev
uptimev --version
uptimev
```

## Upgrade

```sh
brew update
brew upgrade VanPaitin/tap/uptimev
```

For usage, requirements, and source installation, see the
[uptimev README](https://github.com/VanPaitin/uptimev#readme).

## Homebrew Bundle

Add to your `Brewfile`:

```ruby
tap "VanPaitin/tap"
brew "uptimev"
```
