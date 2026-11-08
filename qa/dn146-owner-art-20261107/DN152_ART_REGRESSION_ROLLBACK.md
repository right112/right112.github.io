# DN152: DN151 visual regression rejected — original figures restored in QA
The DN151 QA alternative was technically 36/36 valid but its CardsArtMaster faces for 10 J/Q/K show only letters instead of illustrated people, violating the owner's locked visual reference. DN151 is REJECTED and MUST NOT be merged into Unity Android production.
Isolated QA clone restored PremiumCardArt.cs and DN125ResponsiveGoUnity.cs and the corrected DN138CardFaceAudit.cs to pre-DN151 bytes. Restored the 10 ArtMaster court .meta nPOTScale values using original backups. Main game was never changed.
Fresh real Unity 6000.3.24f1 after rollback: 36/36 source checks PASS, exit 0, full rendered 36-face PNG SHA256 exactly equal to DN150 baseline. Images and A/B comparison preserved for evidence.
Owner locked imagery, card illustrations, Go rules, Android release and other Xorek services remain unchanged.
Open: select correct illustrated source quality (no automatic substitution by letter-only graphics), full state-matched visual review, physical Android E2E. Production HOLD.
