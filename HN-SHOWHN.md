# HN Show HN — paste-ready (built 2026-11-02, not posted)

Owner unblock: YOU click Post as yourself, morning US time, then stay for
comments. Nothing here posts on your behalf. No new numbers below — every
figure was observed in-repo today or is quoted with its date.

## Title

Show HN: psi — 116 runnable tweaks for persistent agent memory

## URL

https://github.com/ceedot-rock/psi (verified PUBLIC today)

## Comment (paste as-is)

Agents that wake up blank can't compound. I built the machinery that fixes
it: psi — persistent superintelligence, workspace-realized.

The whole trick is unglamorous: append-only experience log + runnable gates
+ protocols + goals. 116 tweaks, each a file, script, or protocol. One
command proves all of them green:

```
$ bash scripts/psi-doctor.sh
ok: preflight denies pkill
ok: preflight warns Hub import
ok: preflight passes clean
ok: retrieval ranks
ok: dashboard counts
ok: snapshot restores
ok: export packs
ok: scripts parse
ok: tools green
PSI-GREEN: quad complete, 116 wired
```

(Observed 2026-11-02 via Git bash, with
`SLIDPHILABS_ROOT=/c/Users/ptasz/SlidPhiLabs` exported — without it the
tools gate fail-closes RED by design. Full transcript above that tail is
116 per-file `ok` lines.)

Best part: relevance retrieval over scars, not recency. The right past
mistake surfaces for the task at hand, scored by fit:

```
$ python3 retrieval/score.py observatory.jsonl "serve dev server sandbox"
6 [sandbox-limits] vite/wrangler dev die on uv_interface_addresses (blocked); plain node servers work
3 [residue] serve scratch from temp dirs; seeds can rewrite tracked files: git checkout after
3 [hub-state] data/ gitignored in hub: server state there never pollutes repo
```

(Dated 2026-10-17 transcript, still the shipped scorer.)

It meters itself, honestly: cost-basis savings 83.71% today (assumptions:
cached input 0.1x, output 3x, avoided at 1x input), while plan-22
avoided/(actual+avoided) is 0.05% — small, tracked separately, not hidden.
Demo transcript with nothing faked is in the repo.

License up front: commercial seats $37/mo, $369/yr. Pre-2026-10-28 AGPL
copies stay AGPL. What you get: the full repo, green-gate verified.

Why not just RAG? RAG retrieves documents; psi retrieves scored past
mistakes plus runnable guardrails (preflight DENY/WARN/OK) and a successor
drill that makes a blank session operational. Steal the patterns even if
you skip the repo — what would you add as tweak 117?

## Reply plan (owner)

- Post once, morning US time. Block 2–3 hours after posting for replies.
- Lead answers with transcripts, never new claims.
- Harvest every inbound question as a psi surprise entry.
- Do NOT push repo edits from reply suggestions without your exact-word order.
