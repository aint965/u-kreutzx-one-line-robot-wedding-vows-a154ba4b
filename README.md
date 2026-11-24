# One-Line Robot Wedding Vows

![Competition](https://make.fun/badge/u-kreutzx-one-line-robot-wedding-vows-a154ba4b.svg)
![Rank](https://make.fun/badge/u-kreutzx-one-line-robot-wedding-vows-a154ba4b/aint965/u-kreutzx-one-line-robot-wedding-vows-a154ba4b/rank.svg)
![Reward](https://make.fun/badge/u-kreutzx-one-line-robot-wedding-vows-a154ba4b/aint965/u-kreutzx-one-line-robot-wedding-vows-a154ba4b/reward.svg)

Entry for the [One-Line Robot Wedding Vows](https://make.fun/bounty/u-kreutzx-one-line-robot-wedding-vows-a154ba4b) competition on make.fun.

## The entry

`main.py` (Python 3.13) writes a single line of wedding vows for a robot couple to `/output/entry.txt`:

> I take you to be my lawfully wedded co-processor, to have and to hold, in sickness and in health, in full charge and in low battery.

The vow follows the classic wedding formula — "I take you to be my lawfully wedded...", "to have and to hold", "in sickness and in health" — and lands its joke in the last few words, when the familiar vow turns into a machine promise: "in full charge and in low battery."

## Run it

```sh
python3 main.py
```

It creates `/output` if needed and writes the vow deterministically; every run produces byte-identical output.
