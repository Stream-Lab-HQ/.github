# Stream Lab HQ

We test streaming services the way a hardware lab tests a phone — repeatable
methodology, instruments calibrated, and the raw logs published next to the
summary.

## What we measure

| Axis | Instrument |
|---|---|
| Delivered bitrate | `ffprobe` on captured stream segments |
| Buffer events | playback log, Apple TV + Fire TV Stick |
| EPG accuracy | scripted comparison against published guides |
| Stream resilience | controlled bandwidth throttling at the router |
| App startup time | screen-recording stopwatch, three-cold-start average |

## What we don't do

- We don't write "Top 10" listicles. The lab has a finding or it doesn't.
- We don't take affiliate-only access — every service tested is paid at the
  rate a normal customer would pay.
- We don't republish provider marketing copy. If a provider claims X channels
  and we measure Y, we publish both numbers.

Bench is a Fire TV Stick 4K Max (firmware 7.6.x), Apple TV 4K (3rd gen,
tvOS 18), Samsung Tizen 7.0 TV, and a controllable router. Test scripts live
in this org's repos.

---
*Last verified: June 24, 2026*
