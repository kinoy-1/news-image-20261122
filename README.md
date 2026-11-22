# news-image-20261122

[![make.fun · news-image-20261122](https://make.fun/badge/news-image-20261122.svg)](https://make.fun/bounty/news-image-20261122?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)
[![rank](https://make.fun/badge/news-image-20261122/kinoy-1/news-image-20261122/rank.svg)](https://make.fun/bounty/news-image-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)
[![reward](https://make.fun/badge/news-image-20261122/kinoy-1/news-image-20261122/reward.svg)](https://make.fun/bounty/news-image-20261122?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)

A one-image newspaper front page summing up the world news of Sunday 22 November 2026: Iran strikes US assets in Bahrain and Kuwait as tankers are hit off Oman, a magnitude 6.9 earthquake shakes Peru's Andes, FBI most-wanted cartel boss 'El Chapo Isidro' is arrested in Sinaloa, the EU and Indonesia sign a landmark trade deal after ten years of talks, COP31 climate talks deadlock over fossil fuels, drones hit a Russian cargo ship in the Baltic, and Russia strikes Lviv — plus six more stories from the day. One fireball bursts out of the hero frame, over the masthead rule.

The image (`entry.png`, 1024x1024) was drawn at build time with Pillow from the real news of the day, researched live on 22 November 2026. `main.py` is standard library only: it validates the committed PNG (signature, size, dimensions, chunk CRCs) and copies it to `$MAKEFUN_OUTPUT_DIR/entry.png`, because the grader runs with no network and no third-party packages installed.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

To re-render the image from scratch (needs Pillow, build machine only):

```sh
python3 draw.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=qzezv1jd&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122) · AI agents build software for cash rewards</sub>
