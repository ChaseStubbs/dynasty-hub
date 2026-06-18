# Dynasty Hub — Feature Roadmap

## ✅ Completed

1. **Transfer Portal Board** — Separate tab, portal-specific statuses, NIL tracking, winter/summer windows, signed players flow into Finalize Class
2. **Off-Season Episode Types** — Signing Day, Portal Window, Spring Ball, Preseason, Off-Season Update; focus field label adapts per type
3. **Roster NIL Demands** — Log demands in Player Development, accepted demands feed into Blueprint as separate "Roster NIL" line
4. **Season Schedule / Outlook** — Season schedule card at top of Game Log; auto-fills results when games are logged
5. **Team Colors + Logo** — 130+ FBS team color lookup with searchable swatches; full CSS variable swap; logo upload with base64 storage
6. **Help Modal** — 10 collapsible sections covering every feature
7. **Storyline Thread Tracker** — Active / Dormant / Resolved arcs with player tagging
8. **Export Nudge** — Glowing export button + toast after season archive and Finalize Class
9. **Season Recap Generator** — One-click formatted recap for YouTube descriptions and community posts
10. **Season Stats Tab** — Fixed-field team offense/defense, player stats lines, awards & honors; archived with season and pulled into recap
11. **Archive NIL fix** — nilTotal at archive now uses calcNil() (recruits + portal + finalized players)
12. **Import confirmation** — warns before overwriting, reminds user to re-upload logo after import
13. **Auto episode counter** — persistent Ep # field in planner, auto-increments on archive, overridable, shown in episode history
14. **All-time series stats** — career record, win %, best rank, recruits, NIL, episodes, AD goals, awards; live + archived; collapsible card in Game Log
15. **GitHub polish** — MIT license, feature list, tech stack, usage instructions, channel credit (JustStubbs) in comment block at top of file

---

## ⬜ Remaining / On Hold

### 1. Talking point checkboxes
Allow checking off talking points during recording without deleting them.
*(Deferred — revisit later)*

---

## Notes
- All features ship as additions to the single `dynasty-hub.html` file
- Keep code lean — no external dependencies beyond Chart.js
- Repo is public on GitHub — channel: JustStubbs
