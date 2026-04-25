# Carryover Homebrew tap

Homebrew tap for the [Carryover](https://github.com/carryover-dev/carryover) project.

## Install (once v0.1.0 ships)

```bash
brew tap carryover-dev/tap
brew install carryover
```

The `Formula/` directory is empty until v0.1.0 ships — Carryover is currently
pre-code (design docs only). Watch the [main repo](https://github.com/carryover-dev/carryover)
for release announcements.

## What is Carryover?

Keeps AI agents on-task across sessions, tool switches, and compaction —
without burning context. Open source, Rust-based, local-first. See the
[main repo README](https://github.com/carryover-dev/carryover#readme) for details.

## Tap layout (forward-looking)

```
Formula/
└── carryover.rb     # added when v0.1.0 ships
```

The formula will pin a signed Git tag from the main repo and download a
prebuilt binary from the corresponding GitHub Release.

## License

This tap is Apache 2.0 licensed, matching the main project.
