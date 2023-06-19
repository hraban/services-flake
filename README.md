# services-flake

NixOS-like services for Nix flakes, as a [process-compose-flake](https://github.com/Platonic-Systems/process-compose-flake) module (based on flake-parts).

## Getting Started

TODO

(But see `./test/flake.nix`)

## Services available

- [x] Hello World
- [-] PostgreSQL
- [ ] MySQL
- [ ] Redis
- [ ] ...

## Contributing

- If you are adding a *new* service, see https://github.com/cachix/devenv/tree/main/src/modules/services for inspiration.
- When openning a PR, note that we do not have CI yet, so please run `./test.sh` locally on your **NixOS** machine.

## Credits

Thanks to [the devenv project](https://github.com/cachix/devenv/tree/main/src/modules/services) on which much of our services implementation is based on.