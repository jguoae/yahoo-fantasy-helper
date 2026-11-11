# Yahoo Fantasy Helper

Personal, single-user, non-commercial, read-only helper for my own Yahoo Fantasy
Basketball league.

## What it does

It reads my own league data through the Yahoo Fantasy Sports API (OAuth 2.0,
read-only scope `fspt-r`):

- my team roster (by date), matchups and standings
- free agents and waiver status
- my FAAB balance and waiver priority

I use it to plan weekly roster moves — for example, streaming a bench spot to
add extra games played without touching the core rotation.

## What it does NOT do

- No lineup changes, waiver claims, trades, or any other write through the API.
- No data is shared, sold, or shown to anyone else.
- No commercial use, no other users.

## Privacy

OAuth tokens are stored in my assistant's secure credential vault and are only
used to call the Yahoo Fantasy Sports API on my behalf. Nothing is logged or
retained beyond what is needed to answer my questions.
