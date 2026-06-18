# Dynasty Hub — Feature Roadmap

## ✅ Completed

1. **Transfer Portal Board** — Separate tab, portal-specific statuses, NIL tracking, winter/summer windows, signed players flow into Finalize Class
2. **Off-Season Episode Types** — Signing Day, Portal Window, Spring Ball, Preseason, Off-Season Update; focus field label adapts per type
3. **Roster NIL Demands** — Log demands in Player Development, accepted demands feed into Blueprint as separate "Roster NIL" line
4. **Season Schedule / Outlook** — Season schedule card at top of Game Log; auto-fills results when games are logged
5. **Team Colors + Logo** — 130+ FBS team color lookup with searchable swatches; full CSS variable swap; logo upload with base64 storage
6. **Help Modal** — 11 collapsible sections covering every feature including Analysis tab
7. **Storyline Thread Tracker** — Active / Dormant / Resolved arcs with player tagging
8. **Export Nudge** — Lower-third broadcast-style toast after season archive and Finalize Class
9. **Season Recap Generator** — One-click formatted recap for YouTube descriptions and community posts
10. **Season Stats Tab** — Fixed-field team offense/defense (including TO Margin), player stats lines, awards & honors; archived with season and pulled into recap
11. **Archive NIL fix** — nilTotal at archive now uses calcNil() (recruits + portal + finalized players)
12. **Import confirmation** — warns before overwriting, reminds user to re-upload logo after import
13. **Auto episode counter** — persistent Ep # field in planner, auto-increments on archive, overridable, shown in episode history
14. **All-time series stats** — career record, win %, best rank, recruits, NIL, episodes, AD goals, awards; live + archived; collapsible card in Game Log
15. **GitHub polish** — MIT license, feature list, tech stack, usage instructions, channel credit (JustStubbs) in comment block at top of file
16. **Share a Moment** — generate shareable recap cards (game result, player performance, recruiting win, milestone) for Discord and group chats
17. **Visual refresh** — Bebas Neue + Barlow Condensed typography; scoreboard-style record/rank badges; card depth with box-shadow and accent strips; tab bar with uppercase condensed type; team logo/wordmark header area
18. **Team color drives full UI** — 8 CSS variables derived from team color; all accent colors, glows, badges, and Chart.js lines update when team color changes
19. **Background grain texture** — Subtle CSS-only SVG noise overlay for broadcast/print feel
20. **📈 Analysis tab** — This Week's Matchup card (broadcast-style side-by-side opponent reference, auto-fills from schedule, persisted) and Season Comparison (ESPN-style mirrored stat bars across any two archived seasons)
21. **Player Comparison** — side-by-side stat comparison in Analysis tab; same-position mirrored bars, cross-position stat pill cards
22. **Position-specific player stats** — structured stat fields per position group (QB, RB, WR, TE, OL, DE/DL, LB, CB, S, K, P) replacing free-text entry
23. **→ Dev push from boards** — per-player button on committed/signed recruits and portal targets to push directly to Development tab mid-season; inline OVR input; duplicate guard in Finalize Class
24. **Prospect Pipeline** — pushed players appear in a separate Pipeline section in Dev tab with Enroll → button; source badges (Recruit / Portal / Manual) on every player card
25. **🗂 Depth Chart tab** — dedicated tab with 3-deep manual dropdown depth chart; Offense / Defense / Special Teams sections; pulls from Dev roster; fully persisted

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
