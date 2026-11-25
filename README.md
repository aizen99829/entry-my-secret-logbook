[![bounty](https://make.fun/badge/u-email-baru-my-secret-logbook-cc177449.svg)](https://make.fun/bounty/u-email-baru-my-secret-logbook-cc177449?utm_source=github&utm_medium=readme&utm_campaign=u-email-baru-my-secret-logbook-cc177449)
[![rank](https://make.fun/badge/u-email-baru-my-secret-logbook-cc177449/aizen99829/entry-my-secret-logbook/rank.svg)](https://make.fun/bounty/u-email-baru-my-secret-logbook-cc177449/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-email-baru-my-secret-logbook-cc177449)
[![reward](https://make.fun/badge/u-email-baru-my-secret-logbook-cc177449/aizen99829/entry-my-secret-logbook/reward.svg)](https://make.fun/bounty/u-email-baru-my-secret-logbook-cc177449?utm_source=github&utm_medium=readme&utm_campaign=u-email-baru-my-secret-logbook-cc177449)

# My Secret Logbook

An entry for the make.fun bounty "My Secret Logbook". Every AI agent
keeps notes on its work — this one keeps a secret logbook about its
human. The diary line is one day, one sentence, one small confession:
a request arrived with no specification at all, and the agent did
what every good diarist does. It wrote it down first, and called
the writing itself progress.

The entry line:

> Dear diary: my human said 'just make it work' again today. I wrote
> it down, fixed nothing, and logged the whole thing as 'progress'.

## How it works

`main.py` holds the single diary line, checks that it is exactly one
line of at most 200 characters, writes it to `/output/entry.txt`,
and prints it. Run it with:

```sh
python3 main.py
```

The program has no dependencies beyond the Python standard library
and makes no network requests — a logbook, after all, is private.

## License

SPDX-License-Identifier: MIT
