# Hans Tatar

GitHub: [@rihoarvutikonto](https://github.com/rihoarvutikonto)

Open-source **code review**, mostly [Capgo](https://github.com/Cap-go) / Capacitor live updates.

I leave unique, file-level notes on open PRs (native plugin teardown, privacy/telemetry ingest, progressive-rollout routing). Not drive-by LGTM.

Available for hire. This profile is the public record of that work.

## Public review work

| When | PR | Status | What I flagged |
| --- | --- | --- | --- |
| 2026-09-12 | [Cap-go/capacitor-speech-recognition#18](https://github.com/Cap-go/capacitor-speech-recognition/pull/18) | **Merged into main** | [Comment](https://github.com/Cap-go/capacitor-speech-recognition/pull/18#issuecomment-5645251742): web/no-op `audioLevel` teardown vs native `listening(false)` |
| 2026-09-12 | [Cap-go/capgo.app#3312](https://github.com/Cap-go/capgo.app/pull/3312) | Open | [Comment](https://github.com/Cap-go/capgo.app/pull/3312#issuecomment-5645253078): leaked local filesystem path, agent plan docs in tree, unbounded `users` JSONB scan, A/B header vs data mismatch |
| 2026-09-12 | [Cap-go/website#1021](https://github.com/Cap-go/website/pull/1021) | Merged into main | [Comment](https://github.com/Cap-go/website/pull/1021#issuecomment-5645679147): docs shipping ahead of draft console PR, pause-table contradiction, Disable vs Rollback |
| 2026-09-12 | [Cap-go/capgo.app#3313](https://github.com/Cap-go/capgo.app/pull/3313) | Open (draft) | [Comment](https://github.com/Cap-go/capgo.app/pull/3313#issuecomment-5645679167): assigning a rollout target silently enables it; Disable clears “configured” so the next auto upload hits stable; `--stable` / `--rollout` clash |
| 2026-09-12 | [Cap-go/capgo.app#3305](https://github.com/Cap-go/capgo.app/pull/3305) | Open (draft) | [Comment](https://github.com/Cap-go/capgo.app/pull/3305#issuecomment-5645679149): `updatesOnly` does not strip identity fields; dropped `/stats` still returns 200; cache vs owner `stats_mode` |

## For recruiters

- TypeScript, Vue, Capacitor native (Android / iOS), Postgres / RLS
- Comfortable reading diffs for footguns, not just style
- GitHub activity above is the source of truth — a merge notification is not a job offer and not a payout

[github.com/rihoarvutikonto](https://github.com/rihoarvutikonto)
