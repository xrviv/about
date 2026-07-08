# Daniel Andrei R. Garcia

Bitcoin wallet reproducibility reviewer, build forensics operator, and maintainer
of verification tooling around [WalletScrutiny](https://walletscrutiny.com).

My work focuses on one question: can users independently verify that the Bitcoin
wallet app or device they install corresponds to the source code and release
claims made by its developers?

That means reviewing wallets, tracing build systems, writing reproducibility
scripts, comparing binaries, documenting failure modes, and publishing evidence
when claims do not match artifacts.

## WalletScrutiny Review Work

As of the January 2026 WalletScrutiny snapshot, I was listed as author on
`3655` of `6538` Bitcoin-related app/device pages: `55.90%` of the tracked
WalletScrutiny corpus at that point.

```text
Collection     Authored      Total  Instances
----------     --------      -----  ---------
_android           1973       4604       1973
_iphone            1118       1336       1118
_bearer              49         49         49
_others              44         44         44
_hardware           387        421        387
_desktop             84         84         84
----------     --------      -----  ---------
TOTAL              3655       6538       3655
```

That work spans Android wallets, iPhone wallets, bearer instruments, hardware
wallets, desktop wallets, and other Bitcoin-related custody tools.

## Reproducibility Verifications

As of July 8, 2026, my local WalletScrutiny archive contains `286`
reproducibility verification and endorsement report files for Bitcoin apps and
devices.

```text
Desktop        166
Android        105
Hardware        12
Endorsements     2
Unsorted         1
Total          286
```

These are hands-on verification records: build runs, artifact comparisons,
reproducibility findings, and endorsement checks where I reviewed and compared
the underlying evidence.

## WalletScrutiny Commit History

As of July 8, 2026, my authored commits in the official WalletScrutiny GitLab
history total:

```text
Total unique commits in scope: 10076
Danny-authored commits: 2674
Danny-authored share: 26.54%
```

Those `2674` commits cover Bitcoin app and device review work, reproducible
build scripts, build evidence, maintenance, metadata cleanup, verification
automation, and long-running triage.

Yearly breakdown:

```text
2021   465
2022   205
2023   430
2024   420
2025   951
2026   203
```

## Pinned Work

- [WalletScrutinyCom](https://github.com/xrviv/WalletScrutinyCom) - mirror/fork
  of the WalletScrutiny website and review corpus.
- [bitcoinAppReproducibilityVerificationScripts](https://github.com/xrviv/bitcoinAppReproducibilityVerificationScripts)
  - reproducible build verification scripts formerly part of WalletScrutiny.
- [bitcoin-wallet-lab](https://github.com/xrviv/bitcoin-wallet-lab) - an
  educational course for building a reproducible Bitcoin wallet for Android from
  scratch.
- [walletScrutinyBuildCasts](https://github.com/xrviv/walletScrutinyBuildCasts)
  - asciicast records of WalletScrutiny verification work.
- [about](https://github.com/xrviv/about) - this profile repository.
- [The-Triage-Log](https://github.com/xrviv/The-Triage-Log) - notes on vibe
  forensics, Bitcoin, cyber work, and reproducible builds.

## therobotbay.com

[therobotbay.com](https://therobotbay.com) is a work-in-progress robotics and
automation project. Development is currently stalled by lack of funding, which
limits hardware procurement, controlled test time, and sustained engineering
focus.

With dedicated funding, the project could move from prototype work into
structured benchmarking: repeatable test setups, performance measurements across
comparable systems, cost/capability analysis, and published data comparing robot
platforms, components, and automation workflows.

## What I Work On

- Bitcoin wallet reproducibility
- Android and desktop build verification
- Hardware wallet release review
- Binary/source correspondence checks
- Reproducible build scripts and containers
- Wallet metadata triage
- Nostr-backed verification publishing
- Evidence-first software forensics

## Operating Principle

No assumptions. Only evidence.

If a wallet claims to be open source, reproducible, or self-custodial, that
claim should survive contact with the source tree, build instructions, release
artifact, and binary diff.
