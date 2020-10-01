# nix-termux

## Setup instructions

Requires `proot` to be installed.

1. Run `./setup` from the root of this repository.
   
   This creates the directory that will contain the files used by nix-termux (including the Nix store).
   You can choose the install location by setting the `$NIX_TERMUX` environment variable (default: `~/.nix-termux`)
2. Run `./start sh <(curl -L 'https://nixos.org/nix/install')` to install Nix.
3. Run `./start` to enter the environment with Nix present.

When running `./start` without any arguments, `$NIX_TERMUX/in-proot` is sourced automatically (instead of `~/.bashrc`).

**Note:** this uses Cloudflare for DNS by default. You can change this by editing `$NIX_TERMUX/etc-resolv.conf`.
