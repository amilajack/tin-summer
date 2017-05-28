# file-sniffer

If you do a significant amount of programming, you'll probably end up with
several of gigabytes of artifacts scattered about. `sniff` is a tool to help you find those artifacts.

Features:
  - [x] find "fat" files and directories
  - [ ] find "likely build artifact" directories

## Installation

### Binary install

The easiest way to install is probably to download a binary from the [releases
page](https://github.com/vmchale/file-sniffer/releases).

### Cargo

If your platform doesn't have binaries, get [cargo](https://rustup.rs/). Then:

```bash
 $ cargo install file-sniffer
```

## Use

Look for subdirectories/files that consume the most disk space.

```bash
 $ sniff fat dir
```