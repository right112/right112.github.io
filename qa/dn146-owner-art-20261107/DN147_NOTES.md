# DN147 — owner exact deck title from original reference

QA ONLY, not Android release. In isolated Unity clone, only the non-rounded black deck title caption in Russian was replaced with the exact original pixel crop of owner reference 1000062873.png; actual Go deck count remains dynamic.

Unity 6000.3.24f1, real 6/6 Go states, 18 PNGs per resolution: 691x1536, 864x1536, 1200x1600; exit0, hand bounds PASS. On 864x1536 original plaque ROI (19,736)-(164,773), MAE before 56.362 and after 0.000. Original owner texture and all main Unity/Go source untouched. Not approved for production; Android full E2E and owner visual acceptance pending.
