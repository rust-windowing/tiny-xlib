# Changelog

## v0.2.5

- Replace `ctor-lite` with `ctor` (the latter is maintained). (#20)
- Move to the [`@rust-windowing`](https://github.com/rust-windowing) GitHub organization. (#21)
- Fix building with `--cfg coverage` enabled. (#23)
- Bump MSRV to 1.70. (#25)

## v0.2.4

- Add `default_screen()` function for getting the index of the default screen. (#14)

## v0.2.3

- Replace `ctor` with `ctor-lite` to remove proc-macro dependencies. (#12)

## v0.2.2

Implement better loading on `dlopen` mode.
