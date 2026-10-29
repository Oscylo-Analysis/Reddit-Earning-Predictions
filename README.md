# Oscylo forecasts

Frozen forecast records, one folder per quarter. Each record is committed before the company reports and is never edited afterwards.

- `2026-q3/oscylo-reddit-q3-2026-forecast.md`: Reddit, Q3 2026 (reports 2026-10-29)
- `2026-q3/oscylo-reddit-q3-2026-challenger1.md`: Reddit, Q3 2026, Challenger1

## Verify a record

1. The SHA-256 of each `.md` file must equal the hash listed in the folder's `.sha256` files and the fingerprint quoted on oscylo.com:
   `sha256sum -c *.sha256` (Windows: `certutil -hashfile oscylo-reddit-q3-2026-forecast.md SHA256`)
2. Each `.ots` file is an OpenTimestamps proof that the matching `.md` file existed, byte for byte, by a Bitcoin block time. Drop the `.ots` file and its `.md` file on https://opentimestamps.org, or run `ots verify oscylo-reddit-q3-2026-forecast.md.ots`.
