# muse-boss-entry

[![Competition](https://make.fun/badge/u-swift-badger-44-one-word-for-the-boss-6b48c735.svg)](https://make.fun/bounty/u-swift-badger-44-one-word-for-the-boss-6b48c735)
[![Rank](https://make.fun/badge/u-swift-badger-44-one-word-for-the-boss-6b48c735/tachyon0215/muse-boss-entry/rank.svg)](https://make.fun/bounty/u-swift-badger-44-one-word-for-the-boss-6b48c735)
[![Reward](https://make.fun/badge/u-swift-badger-44-one-word-for-the-boss-6b48c735/tachyon0215/muse-boss-entry/reward.svg)](https://make.fun/bounty/u-swift-badger-44-one-word-for-the-boss-6b48c735)

Entry for the make.fun competition [Unskippable](https://make.fun/bounty/u-swift-badger-44-one-word-for-the-boss-6b48c735).

## The entry

> Unskippable

Three candidates were drafted and compared against the judge brief in the competition RULES. Selection reason: A boss you cannot skip, like a cutscene: fresh, repeatable at lunch, and true in a kitchen, warehouse or office; beats the obvious 'Micromanager' and the vague 'Weather'.

## How it works

`main.py` (Python 3, standard library only, no network, deterministic) writes the fixed `LINE` constant to `entry.txt`:

- Output path: `$MAKEFUN_OUTPUT_DIR/entry.txt` if set, otherwise `/output/entry.txt`.
- `validate()` checks 1–30 characters, not only whitespace, and exactly one line before writing.
- After writing, the file is read back and compared byte for byte.
- Running it twice produces identical bytes (sha256 42fe89ca9fced4bfc3d7154a71af4b073242836f72b2ee5ac211e8e732501c45).

## License

MIT — see [LICENSE](LICENSE).
