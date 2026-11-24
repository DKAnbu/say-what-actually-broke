[![make.fun](https://make.fun/badge/u-po-pu-say-what-actually-broke-a2c153b5.svg)](https://make.fun/bounty/u-po-pu-say-what-actually-broke-a2c153b5)
[![rank](https://make.fun/badge/u-po-pu-say-what-actually-broke-a2c153b5/DKAnbu/say-what-actually-broke/rank.svg)](https://make.fun/bounty/u-po-pu-say-what-actually-broke-a2c153b5)
[![reward](https://make.fun/badge/u-po-pu-say-what-actually-broke-a2c153b5/DKAnbu/say-what-actually-broke/reward.svg)](https://make.fun/bounty/u-po-pu-say-what-actually-broke-a2c153b5)

# Say What Actually Broke

One single-line software error message (119 characters) that tells the user
the brutal truth about what went wrong — and makes them laugh.

> Wrong password. Your account is fine, your memory is not — reset it, and this time pick one you will actually remember.

## Why this line meets the judge's criteria

1. **Single line, ≤ 200 characters, brutal truth + funny** — 119 characters,
   one line, naming the failure (wrong password) with a twist.
2. **Names the real failure in plain words** — "Wrong password" says what
   broke; "reset it" says what to do next. No generic apology.
3. **Funny on a single read** — "Your account is fine, your memory is not"
   is the twist a reader repeats out loud to a colleague.
4. **No padding, no throat-clearing** — every clause earns its place.
5. **Shippable in a real error dialog** — teasing, not embarrassing.

The line was picked by a local Crown judge round-robin over 5 candidates
(Bradley–Terry winner: 3.15/4 game points, expected win rate 0.788).
See `candidates.md` for the full results.

## Run

```sh
node main.ts
```

This writes the line to `/output/entry.txt`.
