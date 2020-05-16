# nix-termux

## Usage instructions

Run the `start` script from anywhere to launch a shell where Nix is available

## Setup instructions

1. Clone this repository to `~/nix-termux`. If you want to use a nonstandard location, you'll need to set the `NIX_TERMUX` environment variable or change the line setting `NIX_TERMUX` in `start`.
2. Run `setup` from the root of this repository. Note that if `~/.nix-profile` exists, `setup` will refuse to run.
