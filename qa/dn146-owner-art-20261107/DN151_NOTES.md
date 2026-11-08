# DN151 QA-only 10 court image A/B
Changes only in isolated Unity QA clone. Original owner approved exact reference and 3 priority face textures remain untouched.
Ten CC0 300x420 court textures were tested against existing CardsArtMaster 960x1344 textures; ten court importer nPOTScale=1 settings changed to 0 only in the clone to prevent Unity distortion to 1024x1024.
Verified Unity importer 36/36 PASS exit0, and real Go 6/6 with 18 PNG frames on each of 691x1536,864x1536,1200x1600.
Pixel comparison versus previous baseline: 10/10 court faces changed, 26/26 other faces identical. On initial Go0 frame 0 pixels changed. Owner visual acceptance and Android physical E2E not yet done. Not production.
