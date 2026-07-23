# saver-gnats

Official **gnats** visualizer plugin for [IdleScreen](https://github.com/idlescreen/idle-core).

## Build

Requires a sibling checkout of the core daemon for `trance-api`:

```bash
git clone https://github.com/idlescreen/idle-core.git
git clone https://github.com/idlescreen/saver-gnats.git
cd saver-gnats
cargo build --release
```

## Install

After adding the IdleScreen package repository:

```bash
sudo apt install trance-saver-gnats
# or: sudo dnf install trance-saver-gnats
```

See [idlescreen.github.io/idle-packages](https://idlescreen.github.io/idle-packages/).

## License

Apache-2.0. See [LICENSE](LICENSE).
