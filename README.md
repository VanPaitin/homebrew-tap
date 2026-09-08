# VanPaitin Homebrew Tap

[uptimev](https://github.com/VanPaitin/uptimev) shows current time, uptime, boot
time, and load averages on macOS and Linux. Requires Bash 3.2+; Linux also needs
GNU `date` and readable `/proc/uptime` and `/proc/loadavg`.

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
