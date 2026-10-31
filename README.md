# Rally — badminton guide

A lightweight static guide to badminton rules, skills, training, development, equipment, nutrition, benefits, and safe play. The homepage links to dedicated guides under `pages/`, with shared styles and image assets under `assets/`. It does not need a build step, API keys, analytics, or site-level JavaScript. Video players are embedded from YouTube and Wikimedia Commons and load lazily.

## Project structure

```text
badminton/
├── index.html                 # GitHub Pages entry point
├── favicon.svg                # Small site icon
├── pages/                     # Standalone, internally linked learning guides
│   ├── pathway.html           # Progressive beginner-to-performance roadmap
│   ├── player-plan.html       # Baselines, sample learning block, and player review
│   ├── equipment.html         # Rackets, strings, court shoes, and kit
│   ├── nutrition.html         # Everyday food, hydration, and supplement safety
│   ├── benefits.html
│   ├── rules.html
│   ├── safety.html
│   └── training.html          # Skill progressions, drills, session plans, and tactics
├── assets/
│   ├── css/
│   │   └── styles.css         # Shared site styles
│   └── images/                # Locally stored licensed images and original diagrams
└── README.md
```

Keep `index.html` at the repository root for the simplest GitHub Pages setup. Use relative links between the homepage, `pages/`, and `assets/` so the site also works under a GitHub project URL such as `https://<account>.github.io/<repository>/`.

The player plan is a self-guided learning aid with repeatable baseline checks and an adaptable sample block. It is not a standalone professional-development programme: technique assessment, high-performance training, health decisions, and competition access require appropriate in-person coaching and support.

## Run locally

Open `index.html` in a browser, or start a local static server from this folder:

```powershell
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish for free with GitHub Pages

1. Create or use a GitHub account and create a **public** repository. Do not add passwords, tokens, private data, or other secrets to the repository.
2. Add `index.html`, `pages/`, `assets/`, and this README to the repository's default branch, preserving the folder structure.
3. In the repository, open **Settings → Pages**.
4. Under the build and deployment settings, select **Deploy from a branch**, select the default branch and the `/(root)` folder, then save.
5. Wait for the Pages deployment to complete. GitHub will show the live `https://<account>.github.io/<repository>/` address in the Pages settings.
6. Open that address and check every guide on mobile and desktop, including internal navigation and the source credits at the bottom of each page. Pages provides HTTPS automatically.

The free `github.io` address is used; a custom domain is optional and may cost money. A GitHub account is required to publish. The site itself needs no secrets or API keys.

## Updating content

Edit the relevant page in `pages/` or `index.html`, and edit shared styles in `assets/css/styles.css`. Keep local images under `assets/images/`. Preview the site from the repository root, then publish the changes to the configured branch and verify the live pages. Recheck the BWF rules portal for the current Laws of Badminton before changing or reaffirming rule details, and review the credited health guidance periodically. Content is summarized in original wording; the cited websites are credited at the bottom of the relevant pages.

## Sources

- [VICTOR Europe — Training guide for badminton beginners (Part 1)](https://www.victor-europe.com/blog/article/training-guide-for-badminton-beginners-part1)
- [BadmintonSkills — Training plans: structure your week for maximum progress](https://badmintonskills.com/badminton-training-plans-how-to-structure-your-week-for-maximum-progress/)
- [BWF — Statutes and regulations](https://corporate.bwfbadminton.com/statutes/)
- [WHO — Physical activity fact sheet](https://www.who.int/news-room/fact-sheets/detail/physical-activity)

## Media credits and licenses

Media is shown with a visible credit beside each image or video. Still images are stored locally in `assets/`; YouTube videos are embedded from their creators' channels using YouTube's privacy-enhanced embed host, and match footage is streamed from Wikimedia Commons. The YouTube players load lazily; opening them connects to YouTube. The site does not use a media API or paid stock service.

- `assets/images/badminton-match.jpg` — “Badminton at the 2018 Summer Youth Olympics — Boys Quarterfinals,” Marcus Cyron, [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/); resized web rendition. [Original file and attribution](https://commons.wikimedia.org/wiki/File:Badminton_at_the_2018_Summer_Youth_Olympics_%E2%80%93_Boys_Quarterfinals_Nguyen-Shifeng_19.jpg).
- `assets/images/badminton-youth-final.jpg` — “Badminton YOG 2018,” Sami Zayn, [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). [Original file and attribution](https://commons.wikimedia.org/wiki/File:Badminton_YOG_2018.jpg).
- `assets/images/badminton-court-diagram.png` — “Badminton court,” Robert Merkel, [public domain](https://creativecommons.org/publicdomain/mark/1.0/); converted from SVG to PNG, placed on white, and rotated for display. [Original file and attribution](https://commons.wikimedia.org/wiki/File:Badminton_court.svg).
- `assets/images/badminton-shot-types.png` — “Badminton Schlagarten” (badminton shot types), Norro (Arne Nordmann), [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/). The original graphic has German labels; an English shot key appears beside it on the training page. [Original file and attribution](https://commons.wikimedia.org/wiki/File:Badminton_Schlagarten.png).
- `assets/images/six-corner-footwork.svg` — original six-corner footwork diagram created for this guide.
- `assets/images/training-fuel-map.svg` — original general session-fuelling diagram created for this guide; it is not a prescribed diet.
- `assets/images/badminton-racket.jpg` — “Badminton Racket,” hvshop, [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). [Original file and attribution](https://commons.wikimedia.org/wiki/File:Badminton_Racket.jpg).
- `assets/images/racket-heads.jpg` — “Heads of badminton raquets,” Norro, released to the [public domain](https://creativecommons.org/publicdomain/zero/1.0/). [Original file and attribution](https://commons.wikimedia.org/wiki/File:Heads_of_badminton_raquets.jpg).
- “Badmington competition EuroGames Bern 2023,” Hyruspex, [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/), streamed from Wikimedia Commons as WebM. [Original file and attribution](https://commons.wikimedia.org/wiki/File:Badmington_competition_EuroGames_Bern_2023.webm).
- Training videos embedded from their creators' YouTube channels; original links and visible creator credits appear beside each player on the relevant page:
  - Badminton Insight — [Forehand clear](https://www.youtube.com/watch?v=xRv1JLg4NMM), [forehand serve](https://www.youtube.com/watch?v=Q5AY-sNovX4), [backhand serve](https://www.youtube.com/watch?v=ZlPxYx7VRGA), [backhand strokes](https://www.youtube.com/watch?v=F7Clf4SnTlI), [drop shot](https://www.youtube.com/watch?v=u--taRfMoTs), [smash](https://www.youtube.com/watch?v=H7kpZ9inc10), [doubles net shot](https://www.youtube.com/watch?v=doV0m6MNTCo), [footwork tips](https://www.youtube.com/watch?v=jF0xTdPpqyc), [split step](https://www.youtube.com/watch?v=gy4YZS5tGxE), [half-court exercises](https://www.youtube.com/watch?v=d4QJMcvGfAc), [four-corner footwork](https://www.youtube.com/watch?v=fBa08o5GEqw), [week-of-training drills](https://www.youtube.com/watch?v=WKU7w3AoTyw), [singles tactics](https://www.youtube.com/watch?v=LewjrBRG7Ws), [singles defence](https://www.youtube.com/watch?v=wzpn4DC4Z-k), [doubles tactics](https://www.youtube.com/watch?v=u-zK0MYLqTo), [10-minute badminton warm-up](https://www.youtube.com/watch?v=MTX-CAy0WRY), [choosing court shoes](https://www.youtube.com/watch?v=yjvmMstqz7U), [badminton fitness](https://www.youtube.com/watch?v=F7OhhGe107Q), and [leg strength and power](https://www.youtube.com/watch?v=0hHNet25ddI).
  - Tobias Wadenka — [How to structure your perfect week of badminton training](https://www.youtube.com/watch?v=f9m_9FkVj5s).
  - Swift Badminton — [badminton racket buying guide](https://www.youtube.com/watch?v=GckLu21RwcM).

The BY-SA media is not remixed beyond the resizing or format conversion stated above; its individual asset remains under the linked BY-SA license. The separate site code and original text have their own licensing status.

## Learning and health references

- [BWF Coach Education](https://development.bwfbadminton.com/coaches/) — free coaching manuals and instructional video resources; access to some coach materials may require free registration.
- [BWF Shuttle Time](https://shuttletime.bwfbadminton.com/teachers-overview/) — introductory badminton lessons and video clips intended for children aged 5–15. It is not a complete elite-player curriculum.
- [WHO healthy diet fact sheet](https://www.who.int/news-room/fact-sheets/detail/healthy-diet) and the [NHS Eatwell Guide](https://www.nhs.uk/live-well/eat-well/food-guidelines-and-food-labels/the-eatwell-guide/) — general balanced-diet context.
- [Australian Institute of Sport Sports Supplement Framework](https://www.ausport.gov.au/ais/nutrition/supplements) and [WADA Prohibited List](https://www.wada-ama.org/en/resources/world-anti-doping-program/prohibited-list) — supplement and anti-doping safety references. Rules change; athletes must check the current list and seek qualified advice.
- [VICTOR Europe beginner training guide](https://www.victor-europe.com/blog/article/training-guide-for-badminton-beginners-part1) and [BadmintonSkills weekly training plans](https://badmintonskills.com/badminton-training-plans-how-to-structure-your-week-for-maximum-progress/) — credited source articles summarized in original wording.

Nutrition, training, and equipment pages provide general learning information—not individualized coaching, medical, dietetic, or anti-doping advice. The site does not promise professional selection or prescribe training volume, calories, body weight, supplement use, or a clinical treatment. Ask appropriately qualified professionals about your needs.

## Free instructional video credits

Embedded instructional videos are streamed from their original creators through YouTube's privacy-enhanced embed host. Each player has an adjacent creator attribution and link to the original video.

- Badminton Insight — [Forehand clear](https://www.youtube.com/watch?v=xRv1JLg4NMM), [forehand serve](https://www.youtube.com/watch?v=Q5AY-sNovX4), [backhand serve](https://www.youtube.com/watch?v=ZlPxYx7VRGA), [backhand strokes](https://www.youtube.com/watch?v=F7Clf4SnTlI), [doubles net shot](https://www.youtube.com/watch?v=doV0m6MNTCo), [footwork tips](https://www.youtube.com/watch?v=jF0xTdPpqyc), [split step](https://www.youtube.com/watch?v=gy4YZS5tGxE), [half-court exercises](https://www.youtube.com/watch?v=d4QJMcvGfAc), [four-corner footwork](https://www.youtube.com/watch?v=fBa08o5GEqw), [week-of-training drills](https://www.youtube.com/watch?v=WKU7w3AoTyw), [doubles tactics](https://www.youtube.com/watch?v=u-zK0MYLqTo), [10-minute badminton warm-up](https://www.youtube.com/watch?v=MTX-CAy0WRY), [choosing court shoes](https://www.youtube.com/watch?v=yjvmMstqz7U), [badminton fitness](https://www.youtube.com/watch?v=F7OhhGe107Q), and [leg strength and power](https://www.youtube.com/watch?v=0hHNet25ddI).
- Tobias Wadenka — [How to structure your perfect week of badminton training](https://www.youtube.com/watch?v=f9m_9FkVj5s).
- Swift Badminton — [badminton racket buying guide](https://www.youtube.com/watch?v=GckLu21RwcM).

Video titles and creator channels were checked against YouTube's public oEmbed metadata. Video availability, titles, and embed permission are controlled by their respective creators and platforms; if an embed becomes unavailable, use its adjacent original-video link or remove the entry.
