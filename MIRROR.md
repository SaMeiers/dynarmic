# About this mirror

This repository is a mirror of **dynarmic 6.7.0** (an ARM dynamic recompiler by
merryhime), vendored together with the `externals/` dependencies it needs, so
that it can be cloned as a single self-contained submodule.

It exists because the upstream repository is no longer reachable on GitHub.
Nothing in the dynarmic sources has been modified; see `LICENSE.txt` (0BSD) and
the licenses inside `externals/` for the original terms.

Used as a submodule by [PvZ-TV-Anywhere](https://github.com/SaMeiers/PvZ-TV-Anywhere)
to run the game's 32-bit ARM code on arm64 Android and on PC.
