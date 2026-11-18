# Media artworks citation database

What media artists say their work is for, in their own words.

196 contemporary media artworks made since 2020, with 865 verbatim
statements by their artists (81 of them questions), each linked to the page
it was copied from (884 distinct sources). It is the text layer of
*Why Make This*, a map that places the works by what their artists said about
them. Exported 2026-11-18.

## Licence

The compilation, structure and summaries are licensed under
[Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE): reuse
freely, with credit to "Media artworks citation database, LNX Studio". The
quoted statements remain the work of the people who said or wrote them and
are not covered by this licence; cite them with their original source.

- [WORKS.md](WORKS.md): every work, one page each
- [data/works.json](data/works.json): one record per work, quotes nested
- [data/quotes.csv](data/quotes.csv), [data/works.csv](data/works.csv): flat tables

## What is and isn't the artists'

- **Quotes** are copied character for character from a page that was opened,
  with that page's URL. Nothing inside quote marks is paraphrased. `kind` is
  `question` only when the artist's own words ask one.
- `about` says whether a quote is about this work, the artist's practice, or
  another work. `voice` marks unsigned project text (venue or press copy).
- **Summaries** were drafted by Claude (an AI model) from the sources, to say
  plainly what a visitor meets. They are not the artists' words.
- **Not included:** the map's islands (groupings of similar statements) and
  their names. Those are the studio's own reading, not part of the record.
- No images. Artwork documentation is linked at its source, not copied.

## Rights and corrections

The quoted words belong to the people who said or wrote them. They are quoted
here, with attribution and a source link, for research and discussion of the
works.

If you are one of the artists and want a quote corrected, added to, or
removed, open an issue or contact the studio; it will be changed.

## How it was made

This database was built with AI agents. LNX Studio set the project, the
criteria and the direction; Claude agents (Anthropic) were tasked with
creating the database:

- **Finding works:** agents proposed candidate media artworks made since 2020
  from awards, festivals and biennales, sampled to quotas across periods,
  regions and media.
- **Proposing quotes:** for each work, agents searched festival, press,
  interview and artist pages and proposed statements by the artists, copied
  with the URL of the page they came from.
- **Checking:** the agents were instructed never to paraphrase or quote from
  memory, and to check by script, before saving, that every quote appears
  word for word in the text of the page it cites (ignoring only whitespace
  and curly versus straight quotation marks). This check was run by the
  agents themselves; it has not yet been repeated independently. Quotes from
  non-English pages are translations, marked "(translated from …)" in their
  source. Works for which no statement by the artist could be found are not
  included.
- **Writing:** the work summaries were drafted by Claude from the sources.

Errors are still possible: a quote can be correctly copied but attributed to
the wrong speaker, or come from unsigned venue text (marked `unsigned project
text`). Corrections are welcome.

## Sources

All 884 pages quoted or used, grouped by website (517 websites).
Each work's page lists its own sources next to its quotes.

<details><summary>086708.cargo.site (2)</summary>

- [Light Keeper — lololol (artists' site)](https://086708.cargo.site/lightkeeper)
- [Light Keeper: Signal — lololol (artists' site)](https://086708.cargo.site/lightkeeper_signal)

</details>
<details><summary>10magazine.com (1)</summary>

- [Joshua Serafin: Touching The Void - 10 Magazine](https://10magazine.com/?p=388233)

</details>
<details><summary>13thgwangjubiennale.org (1)</summary>

- [Korakrit Arunanondchai — 13th Gwangju Biennale](https://13thgwangjubiennale.org/?p=308)

</details>
<details><summary>150mediastream.com (1)</summary>

- [Interview with Peter Burr (150 Media Stream)](https://150mediastream.com/peter-burr-interview/)

</details>
<details><summary>17.bienaldeartesmediales.cl (1)</summary>

- [Bemol – 17 Bienal de Artes Mediales de Santiago](https://17.bienaldeartesmediales.cl/obra/bemol/)

</details>
<details><summary>1e9.community (2)</summary>

- [1E9.community — Maarten Isaäk de Heer](https://www.1e9.community/artists/maarten-isa%C3%A4k-de-heer)
- [Daniel Ernst - 1E9 Festival der Zukunft artist page](https://www.1e9.community/artists/daniel-ernst)

</details>
<details><summary>2020.muenchener-biennale.de (2)</summary>

- [SUBNORMAL EUROPE – Münchener Biennale 2020 programme page](https://2020.muenchener-biennale.de/en/subnormal-europe/)
- [SUBNORMAL EUROPE — im Gespräch (artists with philosopher Luis Sáez Rueda), Münchener Biennale, March 2022](https://2020.muenchener-biennale.de/en/subnormal-europe-im-gespraech/)

</details>
<details><summary>2020.rca.ac.uk (1)</summary>

- [KyungJin Jeong – RCA2020 graduate show page (Royal College of Art)](https://2020.rca.ac.uk/students/kyungjin-jeong)

</details>
<details><summary>2022.adaf.gr (1)</summary>

- [FuneralPlay - Athens Digital Arts Festival 2022](https://www.2022.adaf.gr/program/?p=5265)

</details>
<details><summary>2026.amaze-berlin.de (1)</summary>

- [There Goes Nikki - A MAZE. / Berlin 2026 submission page](https://2026.amaze-berlin.de/submissions/there-goes-nikki/)

</details>
<details><summary>24700.calarts.edu (1)</summary>

- [Made in L.A. 2025 Showcases ... New Pieces by Mike Stoltz — CalArts 24700](https://24700.calarts.edu/2025/10/06/made-in-l-a-2025-showcases-archival-works-from-pat-oneill-new-pieces-by-mike-stoltz-kelly-wall-and-nicole-antonia-spagnola/)

</details>
<details><summary>36.bienal.org.br (11)</summary>

- [Antonio Társis – audio guide, 36th Bienal de São Paulo](https://36.bienal.org.br/en/audioguias/antonio-tarsis-en/)
- [Antonio Társis – participant page, 36th Bienal de São Paulo](https://36.bienal.org.br/en/participantes/antonio-tarsis/)
- [Audio guide: Manauara Clandestina – 36th Bienal de São Paulo](https://36.bienal.org.br/en/audioguias/manauara-clandestina-en/)
- [Cevdet Erek – 36th Bienal de São Paulo (artist page, text by Cameron Ah Loo-Matamua)](https://36.bienal.org.br/en/artista/cevdet-erek-en/)
- [Helena Uambembe – 36th Bienal de São Paulo (artist page, text by Lara Kosef)](https://36.bienal.org.br/en/artista/helena-uambembe-en/)
- [Julianknxx – 36th Bienal de São Paulo (text by Nathalia Grilo)](https://36.bienal.org.br/en/artista/julianknxx-en/)
- [Laila Hida – 36th Bienal de São Paulo (artist page, text by Cameron Ah Loo-Matamua)](https://36.bienal.org.br/en/artista/laila-hida-en/)
- [Laila Hida – 36ª Bienal de São Paulo (Portuguese artist page)](https://36.bienal.org.br/artista/laila-hida/)
- [Leonel Vásquez — 36th Bienal de São Paulo artist page (text by Leonardo Matsuhei)](https://36.bienal.org.br/en/artista/leonel-vasquez-en/)
- [Manauara Clandestina – 36ª Bienal de São Paulo](https://36.bienal.org.br/en/artista/manauara-clandestina-en/)
- [Simnikiwe Buhlungu - 36th Bienal de São Paulo](https://36.bienal.org.br/en/artista/simnikiwe-buhlungu-en/)

</details>
<details><summary>4piproductions.com (2)</summary>

- [The Rift wins Grand Prize at NewImages, Paris - 4Pi Productions](https://www.4piproductions.com/blog/the-rift-wins-grand-prize-at-newimages-festival-paris/)
- [The Rift: fulldome Film - 4Pi Productions](https://www.4piproductions.com/360-films/the-rift/)

</details>
<details><summary>a-i-gallery.com (2)</summary>

- [Sarah Choo Jing \| Lumen 3D Interactive Award Winner - ai. gallery](https://a-i-gallery.com/press/sarah-choo-jing-lumen-3d-interactive-award/)
- [Sarah Choo Jing \| Zoom, Click, Waltz (so-far article with the artist's letter) - ai. gallery](https://a-i-gallery.com/press/sarah-choo-jing-zoom-click-waltz)

</details>
<details><summary>aapnews.aap.com.au (1)</summary>

- [Showcase reveals artworks stretched to the outer limits - AAP](https://aapnews.aap.com.au/news/showcase-reveals-artworks-stretched-to-the-outer-limits)

</details>
<details><summary>abqjournal.com (1)</summary>

- [Suzanne Kite's 'Dreaming with AI' at MoCNA — Albuquerque Journal](https://www.abqjournal.com/lifestyle/suzanne-kites-dreaming-with-ai-at-mocna-invites-play-and-reflection/644656)

</details>
<details><summary>actualite.cd (1)</summary>

- [Actualite.cd – David Shongo récompensé au Grand Prix Ars Electronica 2025 pour son film “Café Kuba”](https://actualite.cd/2025/07/24/cinema-david-shongo-recompense-au-grand-prix-ars-electronica-2025-pour-son-film-cafe)

</details>
<details><summary>adamartgallery.nz (1)</summary>

- [Leap to the Place of Two Pools - Te Pātaka Toi Adam Art Gallery](https://www.adamartgallery.nz/exhibitions/future/leap-to-the-place-of-two-pools)

</details>
<details><summary>afar.com (1)</summary>

- [AFAR – Saudi Arabia's Ancient Desert Transforms Into a Striking Art Exhibition](https://afar.com/magazine/desert-x-al-ula-site-specific-art-installations-decorate-saudi-arabian-desert)

</details>
<details><summary>africandigitalart.com (1)</summary>

- [I A M I S I G O: Innovation through Digital Tools & Nigerian Wearable Art (African Digital Art)](https://www.africandigitalart.com/i-a-m-i-s-i-g-o-innovation-through-digital-tools-nigerian-wearable-art/)

</details>
<details><summary>africasacountry.com (1)</summary>

- [From colonial storage to open access (Africa Is a Country)](https://africasacountry.com/2026/07/from-colonial-storage-to-open-access)

</details>
<details><summary>agendaculturel.com (1)</summary>

- [A Comet in Your Eyes – Sursock Museum (Agenda Culturel listing)](https://www.agendaculturel.com/events/a-comet-in-your-eyes)

</details>
<details><summary>agog.org (1)</summary>

- [Agog x Raindance – Enter the Daladala Verse: screening and conversation with Aurelio Mofuga](https://agog.org/event/raindance-daladala-verse-event/)

</details>
<details><summary>agsa.sa.gov.au (2)</summary>

- [Emmaline Zanelli - 2026 Adelaide Biennial of Australian Art: Yield Strength, AGSA](https://www.agsa.sa.gov.au/whats-on/exhibitions/2026-adelaide-biennial-of-australian-art-yield-strength/emmaline-zanelli/)
- [Tuesday Talk - Emmaline Zanelli discusses her work in Yield Strength, AGSA](https://www.agsa.sa.gov.au/whats-on/event-calendar/tuesday-talk-emmaline-zanelli-discusses-her-work-as-part-of-yield-strength/)

</details>
<details><summary>aichitriennale.jp (6)</summary>

- [Aichi Triennale 2025 — Kwon Byungjun, Speak Slowly and It Will Become a Song](https://aichitriennale.jp/2025/en/artist/kwon-byungjun.html)
- [Aichi Triennale 2025 — Mayunkiki (kus)](https://aichitriennale.jp/2025/en/artist/mayunkiki.html)
- [Aichi Triennale 2025 — Mayunkiki+ (kuste, performance)](https://aichitriennale.jp/2025/en/artist/mayunkiki+.html)
- [Aichi Triennale 2025 — performance pamphlet (PDF)](https://aichitriennale.jp/2025/artist/item/kwon-byungjun_pamphlet.pdf)
- [Tomiyasu Yuma – Aichi Triennale 2025 (English)](https://aichitriennale.jp/2025/en/artist/tomiyasu-yuma.html)
- [冨安由真 – 国際芸術祭「あいち2025」 (Japanese)](https://aichitriennale.jp/2025/artist/tomiyasu-yuma.html)

</details>
<details><summary>aiwar.cloud (1)</summary>

- [AI War Cloud (project website)](https://aiwar.cloud)

</details>
<details><summary>alexanderschubert.net (1)</summary>

- [Alexander Schubert - Convergence](https://alexanderschubert.net/works/Convergence.php)

</details>
<details><summary>alicherri.com (1)</summary>

- [Ali Cherri – Biography](https://alicherri.com/biography)

</details>
<details><summary>alumni.risd.edu (1)</summary>

- [Odyssey in the Andes - RISD Alumni](https://alumni.risd.edu/odyssey-andes)

</details>
<details><summary>am.rsu.lv (1)</summary>

- [Anatomy & Beyond — Riga Stradiņš University Anatomy Museum](https://am.rsu.lv/en/node/12848)

</details>
<details><summary>americantheatre.org (1)</summary>

- [The Dangers of AI Intoxication - Annie Dorsen, American Theatre](https://americantheatre.org/?p=79018)

</details>
<details><summary>andreachiampo.com (3)</summary>

- [About – Andrea Chiampo (artist's website)](https://www.andreachiampo.com/about)
- [FUTURED PAST (artist's website)](https://www.andreachiampo.com/futured-past)
- [MATER NATVRA – Asprey Studio – ABM (artist's website)](https://www.andreachiampo.com/mater-natvra-asprey-studio-abm)

</details>
<details><summary>anikameierstatusupdate.substack.com (1)</summary>

- [AI Art Questionnaire: Linda Dounia](https://anikameierstatusupdate.substack.com/p/ai-art-questionnaire-linda-dounia)

</details>
<details><summary>animation-week.com (1)</summary>

- [“Ordinary Life”: An interview with Yoriko Mizushiri — Animationweek](https://animation-week.com/?p=19753)

</details>
<details><summary>animationscoop.com (1)</summary>

- [INTERVIEW: Erick Oh On His Oscars Short Finalist “Opera” (Animation Scoop)](https://animationscoop.com/?p=12735)

</details>
<details><summary>anna-schaeffner.com (1)</summary>

- [Soft Collision – Anna Schaeffner (artist site)](https://anna-schaeffner.com/Soft-Collision)

</details>
<details><summary>anniedorsen.digital.brynmawr.edu (1)</summary>

- [World Premiere - Annie Dorsen, Bryn Mawr College](https://anniedorsen.digital.brynmawr.edu/?p=522)

</details>
<details><summary>anothermag.com (1)</summary>

- [Richard Mosse's Searing Images of the Amazon in Peril, AnOther Magazine](https://www.anothermag.com/art-photography/14382/richard-mosse-photographer-interview-broken-spectre-amazon-climate-crisis)

</details>
<details><summary>anthonyazekwoh.com (1)</summary>

- [Anthony Azekwoh — About](https://www.anthonyazekwoh.com/about)

</details>
<details><summary>antonspice.substack.com (1)</summary>

- [Soil acoustics as witness to ecological collapse with Juan Cortés — Through Sounds (Anton Spice)](https://antonspice.substack.com/p/juan-cortes-soil-acoustics)

</details>
<details><summary>aos.arebyte.com (1)</summary>

- [Hervisions - The Art of No Likes, Phase 2: Julieta Gil - arebyte AOS](https://aos.arebyte.com/contents/hervisions-the-art-of-no-likes-phase-2-julieta-gil/)

</details>
<details><summary>apollo-magazine.com (1)</summary>

- [Apollo Magazine – Spirit of the place: an interview with Farah Al Qasimi](https://apollo-magazine.com/an-interview-with-farah-al-qasimi/)

</details>
<details><summary>app.swapcard.com (1)</summary>

- [Eyes Of Shame - NewImages Festival 2022, XR Development Market (Swapcard)](https://app.swapcard.com/event/newimages-festival-2022-1/exhibitor/RXhoaWJpdG9yXzc3ODQ3MQ==)

</details>
<details><summary>arabnews.com (2)</summary>

- [Arab News – How Saudi creatives are adopting AI to shift the boundaries of contemporary art](https://www.arabnews.com/node/2593519/amp)
- [Inside the third Diriyah Contemporary Art Biennale (Arab News)](https://www.arabnews.com/node/2632736/lifestyle)

</details>
<details><summary>arabnews.pk (2)</summary>

- [Arab News – Saudi artist Daniah Alsaleh: 'We can celebrate tradition, but we really need to be open to change'](https://www.arabnews.pk/node/2574838)
- [Noor Riyadh announces artists for this year’s festival of light and art – Arab News](https://www.arabnews.pk/node/2621560)

</details>
<details><summary>archdaily.com (1)</summary>

- [In the Blink of an Eye: 60 Light Installations Illuminate a Citywide Gallery for Noor Riyadh 2025 – ArchDaily](https://www.archdaily.com/1036858/in-the-blink-of-an-eye-60-light-installations-illuminate-a-citywide-gallery-for-noor-riyadh-2025)

</details>
<details><summary>architonic.com (1)</summary>

- [Arabian nights: recasting the Saudi capital through light – Architonic](https://www.architonic.com/de/s/arabian-nights:-recasting-the-saudi-capital-through-light/20343917)

</details>
<details><summary>archive.aec.at (27)</summary>

- [Anxious Body — Prix Ars Electronica Archive (Award of Distinction, Computer Animation 2022)](https://archive.aec.at/prix/267896/)
- [Artist Residency at SETI Institute – Interspecifics, European ARTificial Intelligence Lab archive (incl. Ars Electronica Festival 2021 photos)](https://archive.aec.at/ailab/261299)
- [Avatar Robot Cafe DAWN ver.β, Prix Ars Electronica Archive (Golden Nica Digital Communities 2022)](https://archive.aec.at/prix/268808)
- [Baitul Ma'mur: House of Angels — Prix Ars Electronica 2021, Honorary Mention (archive)](https://archive.aec.at/prix/255812/)
- [Cangjie's Poetry - Prix Ars Electronica 2022, Computer Animation, Honorary Mention](https://archive.aec.at/prix/266995/)
- [CHIMERIA, Shin Hanagata - Prix Ars Electronica Archive (catalogue text, jury statement)](https://archive.aec.at/prix/319687/)
- [Chosho Hakkei in Rittor Base - HPL ver - Prix Ars Electronica 2021, Digital Musics & Sound Art, Honorary Mention](https://archive.aec.at/prix/256840/)
- [Codex Virtualis\_Genesis – Prix Ars Electronica 2023 archive (Honorary Mention)](https://archive.aec.at/prix/279020/)
- [Conversations Beyond the Ordinary, Prix Ars Electronica Archive](https://archive.aec.at/prix/290645)
- [Endangered Gestures – Prix Ars Electronica Archive (Honorary Mention, New Animation Art)](https://archive.aec.at/prix/320402/)
- [FuneralPlay - Prix Ars Electronica 2023, New Animation Art, Honorary Mention](https://archive.aec.at/prix/278459/)
- [GR-AI-N, S+T+ARTS Prize 2024 entry, Ars Electronica archive](https://archive.aec.at/startsprize/288853/)
- [Harvesting Climate Action - Prix Ars Electronica 2026, Digital Humanity, Honorary Mention (archive)](https://archive.aec.at/prix/320305/)
- [huě iànn — Prix Ars Electronica Archive (Honorary Mention, New Animation Art 2023)](https://archive.aec.at/prix/277097/)
- [In a Small Room – Prix Ars Electronica 2021 archive (Digital Humanity, Honorary Mention; pool source)](https://archive.aec.at/prix/257325/)
- [Micro-Nano Landscape — Prix Ars Electronica 2026, Honorary Mention New Animation Art (Ars Electronica Archive)](https://archive.aec.at/prix/320406/)
- [Mid Tide #3 - Prix Ars Electronica 2024, New Animation Art, Honorary Mention](https://archive.aec.at/prix/290636/)
- [No Bird — Prix Ars Electronica 2026, Honorary Mention Interactive Art + (Ars Electronica Archive)](https://archive.aec.at/prix/319445/)
- [Prix Ars Electronica Archive — Le Miroir](https://archive.aec.at/prix/320405/)
- [Prix Ars Electronica Archive: If You Have Starry Skies in Your Eyes (Award of Distinction 2024)](https://archive.aec.at/prix/290649/)
- [Prix Ars Electronica Archive: Thank you for your souvenir, UK! (Honorary Mention 2024)](https://archive.aec.at/prix/290625/)
- [SMOG SEASON - Prix Ars Electronica Archive (Honorary Mention 2023, New Animation Art)](https://archive.aec.at/prix/276128/)
- [Smoke and Mirrors — Prix Ars Electronica archive](https://archive.aec.at/prix/290664)
- [Spray and Pray, Veneta Androva - Prix Ars Electronica Archive (catalogue text, jury statement)](https://archive.aec.at/prix/320407/)
- [Stained — Ars Electronica Archive](https://archive.aec.at/prix/290621)
- [Subnormal Europe – Prix Ars Electronica 2021 archive (Digital Musics & Sound Art, Honorary Mention)](https://archive.aec.at/prix/255800/)
- [They Who Saw Nothing but Beauty, Prix Ars Electronica 2026 archive (pool source)](https://archive.aec.at/prix/317102/)

</details>
<details><summary>archive.bubblegumclub.co.za (2)</summary>

- [Azibuye – The 360° Virtual Reality Film (Bubblegum Club)](https://archive.bubblegumclub.co.za/art/azibuye-the-360-virtual-reality-film/)
- [Azibuye – The Occupation // SA's first VR documentary to show at Sundance Film Festival, Christa Dee, Bubblegum Club, 2020](https://archive.bubblegumclub.co.za/?p=20703)

</details>
<details><summary>archive.ibraaz.org (1)</summary>

- [Unfolding the Structures of Sound – Cevdet Erek in conversation with Başak Şenova, Ibraaz](https://archive.ibraaz.org/interviews/220)

</details>
<details><summary>archive.project-gallery.com (1)</summary>

- [Spotlight: Jovita Alvares, project gallery (2021)](https://archive.project-gallery.com/spotlights/jovita-alvares)

</details>
<details><summary>ars.electronica.art (49)</summary>

- [A Robot's Liberation - interview with Paula Gaetano Adi, Ars Electronica Blog](https://ars.electronica.art/aeblog/en/2025/07/07/a-robots-liberation/)
- [AI War Cloud Database – Ars Electronica Festival 2025: Panic, S+T+ARTS Prize Exhibition](https://ars.electronica.art/panic/en/view/ai-war-cloud-database-22638ddb450c81a6a2dcdf8906aa5446)
- [AI War Cloud Database – S+T+ARTS Prize 2025, Grand Prize – Artistic Exploration (project text, credits, jury statement)](https://ars.electronica.art/starts-prize/?p=11528)
- [Ars Electronica 2022 – Absence / Marc Hericher](https://ars.electronica.art/planetb/en/absence/)
- [Ars Electronica 2025 press kit – POSTCITY (State of the ART(ist))](https://ars.electronica.art/mediaservice/files/2025/09/pa-en-postcity.pdf)
- [Ars Electronica Festival 2024 – AI and the Art of Historical Reinterpretation](https://ars.electronica.art/hope/en/ai-and-the-art-of-historical-reinterpretation)
- [Ars Electronica Festival 2024 – Daladala Verse](https://ars.electronica.art/hope/?p=13256)
- [Ars Electronica Festival 2024 – Soft Collision](https://ars.electronica.art/hope/en/soft-collision/)
- [Ars Electronica Festival 2024 — If You Have Starry Skies in Your Eyes](https://ars.electronica.art/hope/?p=7599)
- [Ars Electronica Festival 2025: Panic – Café Kuba](https://ars.electronica.art/panic/en/view/cafe-kuba-22a38ddb450c8117aebafb85198618a4)
- [Artificial intelligence as a meta-researcher – Ars Electronica Blog interview with Interspecifics](https://ars.electronica.art/aeblog/?p=26245)
- [Avatar Robot Cafe DAWN ver.β, STARTS Prize Exhibition, Ars Electronica Festival 2022](https://ars.electronica.art/planetb/en/avatar-robot-cafe)
- [Añoranzas (Yira Yira) — Ars Electronica Festival 2023](https://ars.electronica.art/who-owns-the-truth/?p=1792)
- [Baitul Ma'mur — Ars Electronica 2021 Festival, A New Digital Deal theme exhibition](https://ars.electronica.art/newdigitaldeal/en/baitul-mamur)
- [Broken Spectre, S+T+ARTS Prize 2023 Grand Prize page, Ars Electronica](https://ars.electronica.art/starts-prize/en/broken-spectre/)
- [Calculating Empires, S+T+ARTS Prize 2024 Grand Prize – Artistic Exploration](https://ars.electronica.art/starts-prize/en/calculating-empires/)
- [CIFO-Ars Electronica Awards 2023 press release](https://ars.electronica.art/press/files/2023/03/060323.CIFO-Awards-EN.pdf)
- [Conversations Beyond the Ordinary, Ars Electronica Festival 2024](https://ars.electronica.art/hope/?p=7551)
- [CyberArts 2021 catalogue (Prix Ars Electronica), jury statement](https://ars.electronica.art/newdigitaldeal/files/2021/08/cyberarts21.pdf)
- [From Blue Marble to Bioplastic Record — Ars Electronica Blog](https://ars.electronica.art/aeblog/?p=77214)
- [FuneralPlay - A New Digital Deal, Ars Electronica Festival 2021 (European ARTificial Intelligence Lab commission)](https://ars.electronica.art/newdigitaldeal/en/funeralplay)
- [Golden Nicas for artists from Japan, the USA, Taiwan, Colombia and Austria, Ars Electronica Mediaservice, 2022 (pool source)](https://ars.electronica.art/mediaservice/?p=32023)
- [Guanaquerx - Ars Electronica Festival 2025 (PANIC programme)](https://ars.electronica.art/panic/en/view/guanaquerx-21c38ddb450c81e1b698d809489b36d6)
- [I.AM.ISIGO Digital Mystery System – Ars Electronica Festival 2024](https://ars.electronica.art/hope/?p=13421)
- [In a Small Room – STARTS Prize 2021 nomination page (Ars Electronica)](https://ars.electronica.art/starts-prize/?p=3717)
- [Mid Tide #3 - Ars Electronica Festival 2024 (HOPE)](https://ars.electronica.art/hope/?p=7654)
- [Opera (Deep Space 8K), Ars Electronica Festival 2021](https://ars.electronica.art/newdigitaldeal/en/opera-deepspace8k)
- [Prix 2021: Musicians face the new reality, Ars Electronica Blog](https://ars.electronica.art/aeblog/en/2021/08/17/prix-2021-musicians-face-the-new-reality/)
- [Prix Ars Electronica 2021 counts 3,158 entries from 86 countries, Ars Electronica Mediaservice](https://ars.electronica.art/mediaservice/?p=31880)
- [Prix Ars Electronica 2021 winners press release (Computer Animation, Award of Distinction)](https://ars.electronica.art/mediaservice/files/2021/06/Prix-Ars-Electronica-2021_EN.pdf)
- [Prix Ars Electronica 2022 prizewinners (press release, pool source)](https://ars.electronica.art/press/files/2022/06/Prix-2022_EN_.pdf)
- [Prix Ars Electronica 2023 winners (Artificial Intelligence & Life Art, Award of Distinction)](https://ars.electronica.art/mediaservice/en/2023/06/12/prix-winners-2023/)
- [Prix Ars Electronica 2024 catalogue (pool source)](https://ars.electronica.art/hope/files/2024/08/prix2024.pdf)
- [Prix Ars Electronica 2024 jury statements (New Animation Art)](https://ars.electronica.art/prix/en/jurystatements/statements2024/)
- [Prix Ars Electronica 2025 press release (PDF) - Golden Nica, Artificial Life & Intelligence](https://ars.electronica.art/mediaservice/files/2025/07/pa_en-prix-ars-electronica-2025.pdf)
- [Prix Ars Electronica 2026 winners](https://ars.electronica.art/prix/en/winners/)
- [Prometheus Firebringer - S+T+ARTS Prize (Ars Electronica)](https://ars.electronica.art/starts-prize/?p=10828)
- [S+T+ARTS Prize 2023 press release (pool source)](https://ars.electronica.art/mediaservice/files/2023/06/pressetext-en-starts.pdf)
- [Soundscapes of the Andean plain — Ars Electronica Blog (interview with Juan Cortés)](https://ars.electronica.art/aeblog/?p=39165)
- [Stained — Ars Electronica Festival 2024](https://ars.electronica.art/hope/?p=7756)
- [Temporary Stored – Ars Electronica Festival 2023](https://ars.electronica.art/who-owns-the-truth/?p=9470)
- [The Echinoidea Future – Adriatic Sensing — S+T+ARTS Prize 2024, Honorary Mention](https://ars.electronica.art/starts-prize/?p=10939)
- [The slightly different café, Ars Electronica Blog, 2022](https://ars.electronica.art/aeblog/?p=33321)
- [Tracing the Invisible Lines Between Devices and Drones – Ars Electronica Blog, 4 June 2025](https://ars.electronica.art/panic/?p=761)
- [Void in Resonance \| Ars Electronica Festival 2025: Panic](https://ars.electronica.art/panic/en/view/void-in-resonance-22238ddb450c815bad66c8fa5228e6ca)
- [Washed Out "The Hardest Part" (Ars Electronica Festival 2024)](https://ars.electronica.art/hope/en/washed-out-the-hardest-part/)
- [Wild Machines, Ars Electronica Festival 2023](https://ars.electronica.art/who-owns-the-truth/?p=1804)
- [Words as Weapons – Ars Electronica Blog (interview)](https://ars.electronica.art/aeblog/?p=80241)
- [Чули? Чули. – FOUNDING LAB Fall Term Projects (IT:U x Ars Electronica)](https://ars.electronica.art/university/en/%d1%87%d1%83%d0%bb%d0%b8-%d1%87%d1%83%d0%bb%d0%b8/)

</details>
<details><summary>art21.org (1)</summary>

- [Art21 New York Close Up – Jordan Strafer's True Stories (2026)](https://art21.org/watch/new-york-close-up/jordan-strafers-true-stories/)

</details>
<details><summary>artafricamagazine.org (2)</summary>

- [Exploring resilience and regeneration, ART AFRICA](https://artafricamagazine.org/exploring-resilience-and-regeneration-an-interview-on-brazils-participation-in-the-60th-international-art-exhibition-la-biennale-di-venezia/)
- [Laila Hida: Sensing the Desert, Reimagining the Image – ART AFRICA Magazine](https://artafricamagazine.org/leila-hida-sensing-the-desert-reimagining-the-image/)

</details>
<details><summary>artasiapacific.com (1)</summary>

- [ArtAsiaPacific, 'pure intention, muddy ground'](https://www.artasiapacific.com/shows/pure-intention-muddy-ground-singapore-biennale-2025/)

</details>
<details><summary>artbasel.com (3)</summary>

- [Art Basel launches Zero 10, a new global initiative for art of the digital era - Art Basel](https://www.artbasel.com/stories/art-basel-launches-zero-10--a-new-initiative-for-art-of-the-digital-era)
- [Ho Tzu Nyen taps AI to pay tribute to Hong Kong cinema on M+ Facade (Art Basel Stories)](https://www.artbasel.com/stories/ho-tzu-nyen-ai-hong-kong-cinema-m-art-basel)
- [Wing Po So, the apothecary's daughter (Art Basel Stories, 2026)](https://www.artbasel.com/stories/wing-po-so-four-seasons-art-basel-hong-kong-chinese-medicine-sculptural-worlds?lang=en)

</details>
<details><summary>artblocks.io (3)</summary>

- [Art Blocks at Art Basel Miami: Presenting Quine by Larva Labs - Art Blocks](https://www.artblocks.io/articles/art-basel-miami-presenting-quine-larva-labs)
- [In Conversation with Leo Villareal - Art Blocks (2022)](https://www.artblocks.io/articles/in-conversation-with-leo-villareal)
- [Quine by Larva Labs - Art Blocks collection page](https://www.artblocks.io/collection/quine-by-larva-labs)

</details>
<details><summary>artbreath.org (1)</summary>

- [Artbreath – Ali Cherri interview](https://artbreath.org/interviews/ali-cherri)

</details>
<details><summary>artcollection.juliusbaer.com (1)</summary>

- [Chloé Delarue: Art and the humanity of tech – Julius Baer Art Collection](https://artcollection.juliusbaer.com/news/Chloe_Delarue.html)

</details>
<details><summary>artdaily.com (3)</summary>

- [Digital art project by Rachel Rossin launches on whitney.org — Artdaily, 28 September 2022](https://artdaily.com/news/150283/Digital-art-project-by-Rachel-Rossin-launches-on-whitney-org)
- [New digital art commission by Amelia Winger-Bearskin launches on whitney.org (Artdaily, Whitney press release)](https://artdaily.com/news/152773/New-digital-art-commission-by-Amelia-Winger-Bearskin-launches-on-whitney-org)
- [New digital art commission by Peter Burr launches on whitney.org (Artdaily, Whitney press release)](https://artdaily.com/news/159671/New-digital-art-commission-by-Peter-Burr-launches-on-whitney-org)

</details>
<details><summary>artdogistanbul.com (1)</summary>

- [ArtDog Istanbul — Fermata: Hong Kong in Venice (interview)](https://artdogistanbul.com/en/fermata-hong-kong-in-venice/)

</details>
<details><summary>artealdia.com (1)</summary>

- [An 'anti-archive' made home: Angie Saiz at the Biennial of Media Arts – Arte Al Día](https://www.artealdia.com/News/AN-ANTI-ARCHIVE-MADE-HOME-ANGIE-SAIZ-AT-THE-BIENNIAL-OF-MEDIA-ARTS)

</details>
<details><summary>arteporexcelencias.com (1)</summary>

- [New Digital Art Commission by Rick Silva Launches on whitney.org (Arte por Excelencias, Whitney press release)](https://www.arteporexcelencias.com/es/node/31462)

</details>
<details><summary>artforum.com (3)</summary>

- [Du Keke, Singapore Biennale 2025 diary (Artforum)](https://www.artforum.com/columns/singapore-biennale-2025-diary-du-keke-1234737801/)
- [Kite feature — Artforum](https://www.artforum.com/features/kite-generative-ai-performance-video-1234727290/)
- [Leslie Thornton on saturation and solitude in her moving-image works - Artforum](https://www.artforum.com/columns/leslie-thornton-on-saturation-and-solitude-in-her-moving-image-works-247246/)

</details>
<details><summary>artinterview.com (1)</summary>

- [ART Interview — Elias Crespin](https://www.artinterview.com/en/interview/elias-crespin/)

</details>
<details><summary>artlab.hyundai.com (3)</summary>

- [Circular Flows: Marina Zurkow Plumbs the Depths of the Hudson River — Elvia Wilk](https://artlab.hyundai.com/editorial/circular-flows-marina-zurkow-plumbs-the-depths-of-the-hudson-river)
- [Hyundai Artlab, The River is a Circle, Main Film (page text quoting the artist)](https://artlab.hyundai.com/editorial/watch/hyundai-terrace-commission-marina-zurkow-the-river-is-a-circle-main-film)
- [Hyundai Terrace Commission: Marina Zurkow — Hyundai Artlab](https://artlab.hyundai.com/project/hyundai-terrace-commission-marina-zurkow)

</details>
<details><summary>artlyst.com (2)</summary>

- [Pavlina Vagioni Oikeiōsis: A Greek Artist Asks Venice to Remember How to Belong, Artlyst](https://artlyst.com/?p=196876)
- [Venice Biennale 2026 national pavilions plus collateral events, Artlyst guide](https://artlyst.com/venice-biennale-2026-national-pavilions-plus-collateral-events-artlyst-guide/)

</details>
<details><summary>artmonthly.co.uk (1)</summary>

- [Jumana Manna by Emilia Terracciano (Art Monthly, February 2023)](https://artmonthly.co.uk/magazine/site/article/jumana-manna-by-emilia-terracciano-february-2023)

</details>
<details><summary>artport.whitney.org (1)</summary>

- [The Thinking Ocean, artport (work)](https://artport.whitney.org/commissions/the-thinking-ocean)

</details>
<details><summary>artra.lk (1)</summary>

- [The Art of Listening: In Conversation with Dinoj M, ARTRA Magazine](https://www.artra.lk/the-art-of-listening-in-conversation-with-dinoj-m/)

</details>
<details><summary>artreview.com (14)</summary>

- [ArtReview — 'An Anatomy Fair': Jonathas de Andrade on Representing Brazil](https://artreview.com/an-anatomy-fair-jonathas-de-andrade-on-representing-brazil-at-the-59th-venice-biennale/)
- [ArtReview — Angel Hui and Kingsley Ng on Representing Hong Kong at the 61st Venice Biennale](https://artreview.com/angel-hui-and-kingsley-ng-on-representing-hong-kong-at-the-61st-venice-biennale/)
- [ArtReview — Li Yi-Fan: poet of the enshittosphere](https://artreview.com/li-yi-fan-poet-of-the-enshittosphere-taiwan-pavilion-venice-biennale-2026-feature-travis-jeppesen)
- [ArtReview, 'Hayley Millar Baker: the scale of eternity'](https://artreview.com/hayley-millar-baker-the-scale-of-eternity/)
- [ArtReview, Singapore Biennale 2025 review](https://artreview.com/singapore-biennale-2025-review-pure-intention/)
- [Everything is cute at the 2026 Whitney Biennial — ArtReview](https://artreview.com/everything-is-cute-at-the-2026-whitney-biennial-review-jenny-wu/)
- [Four artists on representing Bulgaria at the 61st Venice Biennale - ArtReview](https://artreview.com/four-artists-on-representing-bulgaria-at-the-61st-venice-biennale/)
- [Future Greats: Julieta Gil, selected by Casey Reas - ArtReview](https://artreview.com/future-greats-julieta-gil)
- [Glicéria Tupinambá and the curators of the Hãhãwpuá Pavilion, ArtReview](https://artreview.com/gliceria-tupinamba-and-the-curators-of-the-hahawpua-pavilion-on-representing-brazil-at-the-60th-venice-biennale)
- [Heecheon Kim: Keeping it Real — ArtReview](https://artreview.com/heecheon-kim-keeping-it-real/)
- [Kite: When Dreams Become Datasets — ArtReview](https://artreview.com/kite-when-dreams-become-datasets/)
- [The Domestic Horror of Kawita Vatanajyankur - ArtReview](https://artreview.com/the-domestic-horror-of-kawita-vatanajyankur-interview-mark-rappolt/)
- [Yuko Mohri on Representing Japan at the 60th Venice Biennale (ArtReview)](https://artreview.com/yuko-mohri-on-representing-japan-at-the-60th-venice-biennale/)
- [Zarina Muhammad's Ecofeminist Sorcery - ArtReview](https://artreview.com/zarina-muhammad-eco-feminism-magic-sorcery/)

</details>
<details><summary>artribune.com (2)</summary>

- [Artribune – Intervista per scoprire Theo Eshetu (Christian Caliandro)](https://www.artribune.com/?p=1230851)
- [L’Australia lo aveva escluso. Ora Khaled Sabsabi è due volte alla Biennale di Venezia: l’intervista – Artribune](https://www.artribune.com/?p=1256303)

</details>
<details><summary>artsandculture.google.com (5)</summary>

- ["Subnormal Europe", multimedia music theatre – Google Arts & Culture (ZKM)](https://artsandculture.google.com/asset/subnormal-europe-multimedia-music-theatre-%C3%93scar-escudero/JgHzpQDM1GnOEA?hl=en)
- [6th International Digital Art Biennial - BIAN 2022 - ELEKTRA on Google Arts & Culture](https://artsandculture.google.com/story/QAVBXNdvesD1zw)
- [Google Arts & Culture — An Artist Gives Voice to Traditional Peruvian Textiles](https://artsandculture.google.com/story/DwWhq_x7q_L2ZQ)
- [RÉSONANCES - Louis-Philippe Rondeau - Google Arts & Culture (ELEKTRA)](https://artsandculture.google.com/asset/r%C3%A9sonances-louis-philippe-rondeau/QQFIQFxHwAm3Ig)
- [What Did Flowers Used To Look Like? (Google Arts & Culture)](https://artsandculture.google.com/story/OwXR4TYUXPkzjQ)

</details>
<details><summary>artshelp.com (1)</summary>

- [Tewa Barnosa (Artshelp)](https://www.artshelp.com/tewa-barnosa/)

</details>
<details><summary>artshub.com.au (1)</summary>

- [Khaled Sabsabi reveals details of two installations at Venice Biennale – ArtsHub (7 May 2026)](https://www.artshub.com.au/news/news/khaled-sabsabi-reveals-details-of-two-installations-at-venice-biennale-2857688/)

</details>
<details><summary>artsonje.org (1)</summary>

- [Heecheon Kim: Double Poser — Art Sonje Center](https://artsonje.org/en/exhibitions_abroad/heecheon-kim-double-poser/)

</details>
<details><summary>artspace-aotearoa.nz (1)</summary>

- [Selina Ershadi: The Blue Dome - Artspace Aotearoa](https://artspace-aotearoa.nz/exhibitions/the-blue-dome)

</details>
<details><summary>artxlagos.com (1)</summary>

- [ART X Talks 2022: Once Upon A Garden](https://artxlagos.com/art-x-talks/once-upon-a-garden)

</details>
<details><summary>asapconnect.in (2)</summary>

- [On Protest, Memory and History: In Conversation with Mekh Limbu (ASAP \| art)](https://www.asapconnect.in/post/995/singleevents/on-protest-memory-and-history)
- [Weaving Video Stories: In Conversation with Mekh Limbu (ASAP \| art)](https://asapconnect.in/post/994/singleevents/weaving-video-stories)

</details>
<details><summary>ashleyzelinskie.com (1)</summary>

- [Ashley Zelinskie - artist website (statement, CV)](https://www.ashleyzelinskie.com/)

</details>
<details><summary>associates.caltech.edu (1)</summary>

- [Artist in residence to screen experimental film on campus - Caltech Associates](https://associates.caltech.edu/news/artist-residence-screen-experimental-film-campus)

</details>
<details><summary>athrart.com (1)</summary>

- [ATHR Gallery – Daniah Alsaleh, Hinat 1, 2022](https://athrart.com/artworks/12377-daniah-alsaleh-hinat-1-2022/)

</details>
<details><summary>atlasv.io (1)</summary>

- [Emperor – Atlas V (production company page with directors statement)](https://atlasv.io/emperor/)

</details>
<details><summary>audiospace.soundingfuture.com (1)</summary>

- [Temporary Stored • KMRU (AudioSpace / Sounding Future)](https://audiospace.soundingfuture.com/tracks/temporary-stored)

</details>
<details><summary>aurora.dawn.com (1)</summary>

- [Aurora (Dawn) interview: Tariq Alexander Qaiser on the open seas and Karachi's mangrove forests](https://aurora.dawn.com/news/1144283)

</details>
<details><summary>awrd.com (1)</summary>

- [SMOG SEASON \| Witaya Junma \| AWRD (YouFab Global Creative Awards 2021 entry)](https://awrd.com/creatives/detail/11813987)

</details>
<details><summary>axolot.cat (1)</summary>

- [Maria Choir — Axolot (technical collaborators)](https://axolot.cat/maria-choir/)

</details>
<details><summary>bakchormeeboy.com (1)</summary>

- [Singapore Biennale 2025: 'pure intention' and the Art of Letting the City Speak (Bakchormeeboy)](https://bakchormeeboy.com/2025/10/29/singapore-biennale-2025-pure-intention-and-the-art-of-letting-the-city-speak/)

</details>
<details><summary>bangkokpost.com (1)</summary>

- [Giving the voiceless a voice - Bangkok Post](https://www.bangkokpost.com/life/arts-and-entertainment/2268655/giving-the-voiceless-a-voice)

</details>
<details><summary>bansyouen.com (1)</summary>

- [CHOSHO-HAKKEI - evala (See by Your Ears) feat. Akio Suzuki, Nakazu Banshou-en](http://www.bansyouen.com/sound/en/)

</details>
<details><summary>bbc.com (1)</summary>

- [The Nigerian AI artist reimagining a stylish old age, BBC News, 2023](https://www.bbc.com/news/world-africa-64260739)

</details>
<details><summary>beatiewolfe.com (2)</summary>

- [Ars Electronica share the backstory for Smoke and Mirrors — beatiewolfe.com blog](https://beatiewolfe.com/this-beats-blogging/2024/6/17/ars-electronica-share-the-backstory-for-smoke-and-mirrors)
- [Smoke and Mirrors — Beatie Wolfe (artist's site)](https://beatiewolfe.com/smoke-and-mirrors)

</details>
<details><summary>belenishmorenogil.com (1)</summary>

- [Belenish Moreno-Gil – agenda 2020 (artist site)](https://www.belenishmorenogil.com/2020)

</details>
<details><summary>berlinartweek.de (1)</summary>

- [Shrinking Space — interview with Rachel Rossin, Berlin Art Week](https://berlinartweek.de/en/article/shrinking-space/)

</details>
<details><summary>beyondbeauty.podcasts.library.columbia.edu (1)</summary>

- [Beyond Beauty podcast – Minne Atairu interview transcript (Columbia University)](https://beyondbeauty.podcasts.library.columbia.edu/wp-content/uploads/sites/17/2024/07/Minne-Edited.docx)

</details>
<details><summary>bienal.org.br (3)</summary>

- [Catastrophe orchestra: an interview with Antonio Társis (Bienal de São Paulo)](https://bienal.org.br/en/catastrophe-orchestra-an-interview-with-antonio-tarsis/)
- [Collectivity, autonomy and Indigenous foreigners at the Venice Biennale, Fundação Bienal de São Paulo](https://bienal.org.br/en/collectivity-autonomy-and-indigenous-foreigners-at-the-venice-biennale/)
- [Ka’a Pûera: we are walking birds, Fundação Bienal de São Paulo](https://bienal.org.br/en/walking-birds/)

</details>
<details><summary>biennialfoundation.org (1)</summary>

- [Biennial Foundation — Raphael Fonseca to curate Li Yi-Fan's Taiwan pavilion at the Venice Biennale](https://biennialfoundation.org/2025/12/raphael-fonseca-to-curate-li-yi-fans-taiwan-pavilion-at-the-venice-biennale/)

</details>
<details><summary>bijutsutecho.com (4)</summary>

- [Bijutsu Techo report on Aichi 2025 (Seto venue)](https://bijutsutecho.com/magazine/news/report/31365?page=3)
- [「心霊」を現代美術に組み込む。「第12回shiseido art egg」冨安由真インタビュー – Bijutsu Techo](https://bijutsutecho.com/magazine/interview/promotion/16183)
- [何かの気配、夢の体験をいかにつくり出すのか。冨安由真インタビュー – Bijutsu Techo (2021)](https://bijutsutecho.com/magazine/interview/23801)
- [大名庭園とサウンド・アートが出会うとき。evala×鈴木昭男「聴象発景」がスタート (Bijutsu Techo)](https://bijutsutecho.com/magazine/news/report/20635)

</details>
<details><summary>binghamton.edu (1)</summary>

- [Turning sounds into sights — Binghamton News](https://www.binghamton.edu/news/story/4559/turning-sounds-into-sights-from-making-music-to-the-movie-screen)

</details>
<details><summary>blindspotgallery.com (3)</summary>

- [Annette Meier, 'The Universe in a Cabinet', ArtAsiaPacific 142 (2025)](https://blindspotgallery.com/wp-content/uploads/2025/04/20250307_The-Universe-in-a-Cabinet_AAP.pdf)
- [Wing Po So and Angela Su will participate in the 13th Seoul Mediacity Biennale (Blindspot Gallery news)](https://blindspotgallery.com/news/wing-po-so-and-angela-su-will-participate-in-the-13th-seoul-mediacity-biennale/)
- [Wing Po So — artist page, Blindspot Gallery](https://blindspotgallery.com/?p=15661)

</details>
<details><summary>blog.autourdeminuit.com (1)</summary>

- [Absence – Autour de Minuit production page](https://blog.autourdeminuit.com/production/absence/?lang=en)

</details>
<details><summary>blog.objkt.com (1)</summary>

- [From Word to the World: an Interview with Osinachi (objkt blog)](https://blog.objkt.com/post/from-word-to-the-worldan-interview-with-osinachi)

</details>
<details><summary>blog.piggyvest.com (1)</summary>

- [How a viral painting changed my life (PiggyVest Blog)](https://blog.piggyvest.com/life/how-a-viral-painting-changed-my-life/)

</details>
<details><summary>blog.vive.com (1)</summary>

- [Emperor – a poetic VR experience of life with aphasia (VIVE blog interview)](https://blog.vive.com/us/emperor-a-poetic-vr-experience-of-life-with-aphasia)

</details>
<details><summary>bonart.cat (1)</summary>

- [Bonart – Paper Tears: watermarks of the past emerge at the Venice Biennale](https://www.bonart.cat/en/n/46562/paper-tears-watermarks-of-the-past-emerge-at-the-venice-biennale)

</details>
<details><summary>brakkegrond.nl (1)</summary>

- [Jan Zuiderveld, Coffee Machine, de Brakke Grond](https://brakkegrond.nl/agenda/614/jan-zuiderveld)

</details>
<details><summary>brendanfernandes.ca (2)</summary>

- [Brendan Fernandes – Build Up the House (2024, ART on THE MART)](https://brendanfernandes.ca/build-up-the-house)
- [Brendan Fernandes – Build Up the House II](https://brendanfernandes.ca/build-up-the-house-ii)

</details>
<details><summary>brooklynrail.org (1)</summary>

- [The Brooklyn Rail — Sung Tieu with Amelia Saul (2023)](https://brooklynrail.org/2023/07/art/Sung-Tieu-with-Amelia-Saul/)

</details>
<details><summary>brutus.jp (1)</summary>

- [BRUTUS.jp — 'Korean Cultural News' Vol.22 Artist Kwon Byungjun](https://brutus.jp/en/post-449507)

</details>
<details><summary>bthumm.de (1)</summary>

- [Galerie Barbara Thumm – Theo Eshetu, Biennale Arte 2026 Venice](https://bthumm.de/exhibitions/theo-eshetu-biennale-arte-2026-venice/)

</details>
<details><summary>bunka.go.jp (1)</summary>

- [Anxious Body — Japan Media Arts Festival creators file (Agency for Cultural Affairs)](https://www.bunka.go.jp/j-mediaarts/en/creators_file/animation/2022/mizushiriyoriko/index.html)

</details>
<details><summary>bunshun.jp (2)</summary>

- [Bunshun Online interview with Rib, part 1 (Japanese)](https://bunshun.jp/articles/-/83055)
- [Bunshun Online interview with Rib, part 3 (Japanese)](https://bunshun.jp/articles/-/83057?page=2)

</details>
<details><summary>buttondown.com (1)</summary>

- [Rick Silva : Field Notes, 'Whitney Museum + UMOCA + SB-720'](https://buttondown.com/ricksilva/archive/whitney-museum-umoca-sb-720/)

</details>
<details><summary>bynder.southbankcentre.co.uk (1)</summary>

- [Heecheon Kim: Double Poser — Southbank Centre press release (PDF)](https://bynder.southbankcentre.co.uk/m/41032140725f17c/original/UPDATED-Heecheon-Kim-Press-Release.pdf)

</details>
<details><summary>calculatingempires.net (2)</summary>

- [Calculating Empires – About (artists' project site)](https://calculatingempires.net/about)
- [Calculating Empires – Info, exhibitions and credits (artists' project site)](https://calculatingempires.net/info.html)

</details>
<details><summary>camillesauer.com (1)</summary>

- [Camille Sauer — Le Miroir (artist's website)](https://www.camillesauer.com/en/post/le-miroir-1)

</details>
<details><summary>cannupahanska.com (2)</summary>

- [Cannupa Hanska Luger – Midéegaadi (Future Ancestral Technologies)](https://cannupahanska.com/fat/midegaadi)
- [Cannupa Hanska Luger – Midéegaadi, Times Square Midnight Moment April 2025](https://www.cannupahanska.com/public-art/times-square)

</details>
<details><summary>canvasonline.com (2)</summary>

- [Canvas – Ali Cherri profile](https://canvasonline.com/ali-cherri/)
- [Tewa Barnosa interview (Canvas)](https://canvasonline.com/tewa-baronsa/)

</details>
<details><summary>cargocollective.com (1)</summary>

- [Behind Shirely (2020) — Ibiye Camp (artist's Cargo site)](https://cargocollective.com/ibiyecamp/Behind-Shirely-2020)

</details>
<details><summary>cartoonbrew.com (1)</summary>

- [Erick Oh On ‘Opera’ (Cartoon Brew)](https://www.cartoonbrew.com/awards/erick-oh-on-opera-oscar-shorts-interview-series-204262.html)

</details>
<details><summary>catalannews.com (1)</summary>

- [Catalan News – Catalonia lands at Venice Art Biennale with 'Paper Tears' installation](https://www.catalannews.com/culture/item/catalonia-lands-at-venice-art-biennale-with-paper-tears-installation)

</details>
<details><summary>cccb.org (1)</summary>

- [Maria CHOIR — CCCB touring dossier](https://www.cccb.org/en/touring-activities/dossier/maria-choir/245111)

</details>
<details><summary>cevdeterek.com (1)</summary>

- [Cevdet Erek works (artist's site, exhibition list)](https://cevdeterek.com/)

</details>
<details><summary>chiangmaicitylife.com (1)</summary>

- [City art beats: knitting moments together - Chiang Mai CityLife](https://chiangmaicitylife.com/citylife-articles/city-art-beats-knitting-moments-together)

</details>
<details><summary>chrome.google.com (1)</summary>

- [NoSearchBar, Chrome Web Store](https://chrome.google.com/webstore/detail/nosearchbar/fjjlanpalmagenpageablaphkfcchado)

</details>
<details><summary>cifo.org (2)</summary>

- [CIFO x Ars Electronica Awards 2025](https://www.cifo.org/blog-1/cifo-x-ars-electronica-awards-2025)
- [CIFO — Ars Electronica Awards](https://www.cifo.org/ars-electronica)

</details>
<details><summary>circuit.org.nz (7)</summary>

- [Artist & Curator Talk: Leap to the Place of Two Pools - CIRCUIT](https://www.circuit.org.nz/project/artist-curator-talk-leap-to-the-place-of-two-pools)
- [CIRCUIT Cast #115: Sites of Connection: Selina Ershadi](https://www.circuit.org.nz/writing-and-podcast/selina-ershadi)
- [fugue notes (with live voice over) - CIRCUIT screening page](https://www.circuit.org.nz/project/fugue-notes-live)
- [Hamish Win, Sonya Lacey, Eveningness (review) - CIRCUIT](https://www.circuit.org.nz/writing-and-podcast/sonya-lacey-eveningness)
- [Jess Clifford, The hands also look - CIRCUIT essay on The Blue Dome](https://www.circuit.org.nz/writing-and-podcast/the-hands-also-look)
- [Leap to the Place of Two Pools - CIRCUIT Artist Moving Image](https://www.circuit.org.nz/project/leap-to-the-place-of-two-pools)
- [Sonya Lacey - CIRCUIT artist page](https://www.circuit.org.nz/artist/sonya-lacey)

</details>
<details><summary>claudialarcher.com (1)</summary>

- [AI and the Art of Historical Reinterpretation – Claudia Larcher (artist site)](https://claudialarcher.com/work/theartofhistoricalreinterpretation)

</details>
<details><summary>clickrollboom.squarespace.com (1)</summary>

- [Daniel Brandt new album on Erased Tapes - Click Roll Boom](https://clickrollboom.squarespace.com/news/daniel-brandt-new-album-on-erased-tapes)

</details>
<details><summary>climateweeknyc.org (1)</summary>

- [Climate Week NYC — interview with Felix Gaedtke and Gayatri Parameswaran](https://www.climateweeknyc.org/news/environmental-justice-starts-with-people)

</details>
<details><summary>clintenns.ca (1)</summary>

- [Re-Imagined Space: An Interview with Mike Stoltz — Clint Enns](https://clintenns.ca/re-imagined-space/)

</details>
<details><summary>clotmag.com (2)</summary>

- [Basim Magdy, on traditional narratives & our perceptions of memory, history & time (CLOT Magazine, 2025)](https://clotmag.com/interviews/basim-magdy-on-traditional-narratives-our-perceptions-of-memory-history-time)
- [Eddy Gibb, "When we become NPCs: Trolled by Danielle Brathwaite-Shirley's video game-based Art", CLOT Magazine, 24 March 2026](https://clotmag.com/interviews/when-we-become-npcs-trolled-by-danielle-brathwaite-shirleys-video-game-based-art)

</details>
<details><summary>cntrfld.art (1)</summary>

- [In Conversation: field-0 — Following Drifting Bodies (CNTRFLD.ART, 2026)](https://www.cntrfld.art/journal/in-conversation-field-0)

</details>
<details><summary>collectorsagenda.com (1)</summary>

- [In the Studio: Wong Ping — Collectors Agenda](https://www.collectorsagenda.com/en/in-the-studio/wong-ping)

</details>
<details><summary>colomboscope.lk (3)</summary>

- [Colomboscope 2026 press release (PDF)](https://www.colomboscope.lk/_files/ugd/08c6d3_68eaea6cd7184a5e8369453ad46dfd7f.pdf)
- [Colomboscope 2026: Rhythm Alliances, exhibition guide (artist page, text by Priyankar Chand)](https://www.colomboscope.lk/_files/ugd/08c6d3_89a22dcee783463da28d6fa5c017c204.pdf)
- [Colomboscope 2026: Rhythm Alliances, festival page](https://www.colomboscope.lk/rhythm-alliances)

</details>
<details><summary>colorado.edu (2)</summary>

- [University of Colorado A&S Magazine, 'When napping nature becomes art', 2026 (on Dirt Nap)](https://www.colorado.edu/asmagazine/2026/03/05/when-napping-nature-becomes-art)
- [Void in Resonance by Jerónimo Reyes-Retana (CU Boulder Center for Documentary Media)](https://www.colorado.edu/center/cdem/void-resonance-jeronimo-reyes-retana)

</details>
<details><summary>connaissancedesarts.com (1)</summary>

- [Connaissance des Arts — Un nouveau décor d'art contemporain signé Elias Crespin bientôt au Louvre](https://www.connaissancedesarts.com/musees/musee-louvre/un-nouveau-decor-dart-contemporain-signe-elias-crespin-bientot-au-louvre-11130327/)

</details>
<details><summary>contactexhibition.digital.conncoll.edu (1)</summary>

- [I'm Feeling Lucky — CONTACT exhibition, Ammerman Center, Connecticut College](https://contactexhibition.digital.conncoll.edu/?p=323)

</details>
<details><summary>contemporaryand.com (3)</summary>

- [Contemporary And (C&) – Moving Parts: Yinka Bernie's Sonic Bridge Across Lagos](https://contemporaryand.com/en/c-and-magazine/texts/moving-parts-yinka-bernie-s-sonic-bridge-across-lagos)
- [Contemporary And (C&) – same text, French edition](https://contemporaryand.com/fr/c-and-magazine/texts/moving-parts-yinka-bernie-s-sonic-bridge-across-lagos)
- [Contemporary And América Latina — Paola Torres Núñez del Prado interview](https://contemporaryand.com/en/america-latina-magazine/texts/paola-torres-nunez)

</details>
<details><summary>copenhagenfashionweek.com (1)</summary>

- [Q&A with Bubu Ogisi (Copenhagen Fashion Week)](https://copenhagenfashionweek.com/article/iamisigo-q-a)

</details>
<details><summary>creative-capital.org (1)</summary>

- [Guanaquerx, Paula Gaetano Adi - Creative Capital](https://creative-capital.org/projects/guanaquerx/)

</details>
<details><summary>creativeboom.com (1)</summary>

- [Hussein Shikha weaves pixels, carpets and cultural memory into extraordinary tapestries, Creative Boom](https://www.creativeboom.com/inspiration/hussein-shikha-weaves-pixels-carpets-and-cultural-memory-into-extraordinary-tapestries/)

</details>
<details><summary>crew.brussels (1)</summary>

- [Residency Letta Shtohryn – CREW Brussels](https://crew.brussels/en/lab/articles/residency-letta-shtohryn)

</details>
<details><summary>ctm-festival.de (2)</summary>

- [CTM 2026 - Third Programme Announcement](https://www.ctm-festival.de/news/ctm-2026-third-programme-announcement)
- [Daniel Brandt - CTM 2026 artist page](https://www.ctm-festival.de/festival-2026/programme/artists/d/daniel-brandt)

</details>
<details><summary>culturalsurvival.org (3)</summary>

- [Putting Wallmapu on the Art World Map: An Interview with Seba Calfuqueo — Cultural Survival](https://www.culturalsurvival.org/publications/cultural-survival-quarterly/putting-wallmapu-art-world-map-interview-seba-calfuqueo)
- [Surveilled Lives, Living Archives: Artist Dhiraj Rabha Retrieves History from the Shadows, Cultural Survival](https://www.culturalsurvival.org/news/surveilled-livesliving-archives-artist-dhiraj-rabha-retrieves-history-shadows)
- [The Antecedent Future: Using Emerging Technologies to Carry Forth Wisdom of the Ancestors (Cultural Survival)](https://www.culturalsurvival.org/node/14352)

</details>
<details><summary>culture-technology.podigee.io (1)</summary>

- [The Culture & Technology Podcast – Claudia Larcher episode](https://culture-technology.podigee.io/27-claudia-larcher-ai-and-the-art-of-historical-reinterpretation)

</details>
<details><summary>culturedmag.com (2)</summary>

- [2026 Whitney Biennial review — Cultured](https://www.culturedmag.com/article/2026/03/04/art-2026-whitney-biennial-review-artists/)
- [Cultured — on sound art (October 13, 2026)](https://culturedmag.com/article/2026/10/13/art-rise-of-sound-art-contemporary-artists/)

</details>
<details><summary>d37zoqglehb9o7.cloudfront.net (1)</summary>

- [Serpentine press release PDF, 21 May 2026](https://d37zoqglehb9o7.cloudfront.net/uploads/2026/05/Danielle-Brathwaite-Shirley_online-game-release-FINAL-3.pdf)

</details>
<details><summary>dailynews.co.tz (1)</summary>

- [Daily News – Youths urged to embrace technology in storytelling](https://dailynews.co.tz/?p=73636)

</details>
<details><summary>daisyginsberg.com (1)</summary>

- [Pollinator Pathmaker (artist's website)](https://www.daisyginsberg.com/work/pollinator-pathmaker)

</details>
<details><summary>dance-enthusiast.com (1)</summary>

- [THE DANCE ENTHUSIAST ASKS: Sarah Silverblatt-Buser's "Collective Body," an Interactive Virtual Reality Dance](https://www.dance-enthusiast.com/features/the-dance-enthusiast-asks/view/3690)

</details>
<details><summary>dawn.com (3)</summary>

- [Dawn, 'Exhibition: Art and the city'](https://www.dawn.com/news/1866405)
- [Exhibition: Ghosts of Goa (Rumana Husain, Dawn, 30 March 2025)](https://www.dawn.com/news/1901105)
- [Exhibition: Movement and Memory (Aziz Sohail, Dawn EOS, 6 April 2025)](https://www.dawn.com/news/1902065)

</details>
<details><summary>dawn2021.orylab.com (1)</summary>

- [BUNSHIN Robot Café DAWN ver.β (official site)](https://dawn2021.orylab.com/en/)

</details>
<details><summary>dazeddigital.com (1)</summary>

- [Holly Herndon on vocal deep fakes and launching her digital twin Holly+ — Dazed](https://www.dazeddigital.com/science-tech/article/53966/1/holly-herndon-on-vocal-deep-fakes-and-launching-her-digital-twin-holly)

</details>
<details><summary>decrypt.co (1)</summary>

- [Beeple Made Robot Dogs With Musk, Zuckerberg, and Warhol Heads That Poop NFTs - Decrypt](https://decrypt.co/351080/beeple-made-robot-dogs-with-musk-zuckerberg-and-warhol-heads-that-poop-nfts)

</details>
<details><summary>delfinafoundation.com (2)</summary>

- [In Conversation: Manauara Clandestina and Victoria Sin – Delfina Foundation](https://www.delfinafoundation.com/platform/in-conversation-manauara-clandestina-and-victoria-sin/)
- [Manauara Clandestina – Delfina Foundation residency](https://www.delfinafoundation.com/in-residence/manauara-clandestina/)

</details>
<details><summary>desertx.org (1)</summary>

- [Desert X – Manal AlDowayan, Desert X AlUla 2020](https://desertx.org/dx/desert-x-alula-2020/manal-aldowayan)

</details>
<details><summary>designboom.com (3)</summary>

- [Kat Barandy, dance and architecture unite with luminous projections (designboom, 11 November 2024)](https://www.designboom.com/art/brendan-fernandes-build-up-house-mart-chicago-installation-11-11-2024/)
- [nancy baker cahill's AR hybrid creature soars and evolves across new york's cityscape, designboom, 2023](https://www.designboom.com/art/nancy-baker-cahill-ar-hybrid-creature-evolves-across-new-york-cityscape-cento-whitney-museum-of-american-art-09-26-2023/)
- [robotic bird by korean artist duo erases its own footprints as social commentary — designboom, 25 Feb 2026 (reader submission)](https://www.designboom.com/art/robotic-bird-installation-sand-diorama-footprints-social-commentary/)

</details>
<details><summary>diariodecuyo.com.ar (1)</summary>

- ['Siento que necesitamos este tipo de historias' - Diario de Cuyo, 22 July 2025](https://www.diariodecuyo.com.ar/edicionimpresa/siento-que-necesitamos-este-tipo-de-historias-1751194.html)

</details>
<details><summary>dingdingding.org (1)</summary>

- [An interview with Jonathan Torres Rodríguez, Ding Magazine](https://dingdingding.org/issue-5/1-interview-with-jonathan-torres-rodriguez/)

</details>
<details><summary>dinoj-m.carrd.co (1)</summary>

- [Dinoj Mahendranathan, artist website](https://dinoj-m.carrd.co/)

</details>
<details><summary>docubase.mit.edu (1)</summary>

- [African Space Makers (MIT Docubase)](https://docubase.mit.edu/project/african-space-makers/)

</details>
<details><summary>documentjournal.com (1)</summary>

- [Joshua Serafin - Document Journal (2024)](https://www.documentjournal.com/2024/07/joshua-serafin-art-filipino-void-performance-video-ancestry-indigenous/)

</details>
<details><summary>drive.google.com (1)</summary>

- [Circle of Rhythms: An Interactive Sound Installation, project book (PDF, Google Drive)](https://drive.google.com/file/d/1e2SClZ-Lkg8fXgXgZ6tIOts_oaugoZV3/view?usp=sharing)

</details>
<details><summary>drolesdobjets25.sciencesconf.org (1)</summary>

- [Soft Collision – Drôles d'objets 2025 conference abstract (PDF)](https://drolesdobjets25.sciencesconf.org/594220/document)

</details>
<details><summary>e-flux.com (13)</summary>

- [Basim Magdy: Flickers of Utopia (screening, e-flux Screening Room, January 30, 2024)](https://www.e-flux.com/events/582110/basim-magdy-flickers-of-utopia)
- [Colomboscope 2026, Rhythm Alliances, e-flux Criticism](https://www.e-flux.com/criticism/6782386/colomboscope-2026-rhythm-alliances)
- [e-flux Announcements – Claudia Pagès Rabal: Paper Tears](https://www.e-flux.com/announcements/6787056/claudia-pag-s-rabalpaper-tears)
- [e-flux Criticism — 15th Gwangju Biennale, 'Pansori: A Soundscape of the 21st Century'](https://www.e-flux.com/criticism/632242/15th-gwangju-biennale-pansori-a-soundscape-of-the-21st-century)
- [e-flux – Zineb Sedira: Dreams Have No Titles (French Pavilion)](https://www.e-flux.com/announcements/438576/zineb-sediradreams-have-no-titles/)
- [e-flux — Fermata: Hong Kong in Venice (Hong Kong Museum of Art)](https://www.e-flux.com/announcements/6788495/fermata-hong-kong-in-venice)
- [e-flux — Jonathas de Andrade: With the Heart Coming Out of the Mouth](https://www.e-flux.com/announcements/457150/jonathas-de-andradewith-the-heart-coming-out-of-the-mouth/)
- [Flickers of Utopia: A Conversation (e-flux Notes, 2024)](https://www.e-flux.com/notes/618055/flickers-of-utopia-a-conversation)
- [Ho Tzu Nyen: Night Charades (e-flux announcement)](https://www.e-flux.com/announcements/658965/ho-tzu-nyennight-charades)
- [John Palmesino and Ann-Sofi Rönnskog, When Above, e-flux Architecture](https://www.e-flux.com/architecture/oceans/331872/when-above/)
- [long time, lung time continuuuum!!! (a conver-something) - e-flux announcement](https://www.e-flux.com/announcements/585625/long-time-lung-time-continuuuum-a-conver-something/)
- [Muhannad Shono: The Teaching Tree, Saudi Arabia Pavilion at the Venice Biennale (announcement)](https://www.e-flux.com/announcements/451107/muhannad-shono-the-teaching-tree)
- [Pavlina Vagioni: Oikeiōsis (Kinship), e-flux announcement](https://www.e-flux.com/announcements/6787233/pavlina-vagionioikei-sis-kinship)

</details>
<details><summary>e-issues.globalartdaily.com (1)</summary>

- [Global Art Daily – Highlights from Sharjah Biennial 15](https://e-issues.globalartdaily.com/Highlights-from-Sharjah-Biennial-15)

</details>
<details><summary>e-tcetera.be (1)</summary>

- [Artists' Entrance: Joshua Serafin - Etcetera](https://e-tcetera.be/artists-entrance-joshua-serafin/)

</details>
<details><summary>edbprojects.com (1)</summary>

- [(Loop from) Ventilation Pipe Progenies, 2024 - Ellen de Bruijne Projects](https://www.edbprojects.com/artworks/494-simnikiwe-buhlungu-loop-from-ventilation-pipe-progenies-2024)

</details>
<details><summary>ee.caltech.edu (1)</summary>

- [Leslie Thornton: Begin Again, Again - Caltech EE event page](https://www.ee.caltech.edu/events/begin-again-again-film-screening-1)

</details>
<details><summary>eesly.xyz (2)</summary>

- [Bruce Eesly: Endangered Gestures (artist's website)](https://eesly.xyz/endangered-gestures)
- [Bruce Eesly: New Farmer (artist's website)](https://eesly.xyz/)

</details>
<details><summary>elephant.art (1)</summary>

- [Hãhãwpuá Pavilion’s Artist Glicéria Tupinambá: “So Much of Our Heritage is Trapped on European Ground”, Elephant](https://elephant.art/hahawpua-pavilions-artist-gliceria-tupinamba-so-much-of-our-heritage-is-trapped-on-european-ground)

</details>
<details><summary>eliascrespin.net (1)</summary>

- [L'Onde du Midi au Louvre — eliascrespin.net](https://www.eliascrespin.net/londe-du-midi/)

</details>
<details><summary>ellipses.org.za (1)</summary>

- [The Playa Bagdad/SpaceX Conundrum (Ellipses Journal for Creative Research)](https://www.ellipses.org.za/article/playa-bagdad-spacex-conundrum)

</details>
<details><summary>emare.eu (1)</summary>

- [Unknown Label (2023) / Their Eyes (2025), EMAP — European Media Art Platform (incl. artist talk with werkleitz)](https://emare.eu/works/their-eyes)

</details>
<details><summary>empac.rpi.edu (1)</summary>

- [EMPAC — 15th Gwangju Biennale (review, 2024)](https://empac.rpi.edu/news/2024/15th-gwangju-biennale)

</details>
<details><summary>empathyrevisited.iksv.org (1)</summary>

- [Behind Shirley — Empathy Revisited, 5th Istanbul Design Biennial](https://empathyrevisited.iksv.org/en/project/57-behind-shirley)

</details>
<details><summary>en.studionergens.com (2)</summary>

- [About Studio Nergens](https://en.studionergens.com/over)
- [Nothing to see here - Studio Nergens](https://en.studionergens.com/nothingtoseehere)

</details>
<details><summary>en.wikipedia.org (10)</summary>

- [Anthony Azekwoh (Wikipedia)](https://en.wikipedia.org/wiki/Anthony_Azekwoh)
- [Devin Kenny, Wikipedia](https://en.wikipedia.org/wiki/Devin_Kenny)
- [Ho Tzu Nyen (Wikipedia, pool source)](https://en.wikipedia.org/wiki/Ho_Tzu_Nyen)
- [Jumana Manna (Wikipedia)](https://en.wikipedia.org/wiki/Jumana_Manna)
- [Korakrit Arunanondchai — Wikipedia](https://en.wikipedia.org/wiki/Korakrit_Arunanondchai)
- [Lumen Prize – Wikipedia (pool source)](https://en.wikipedia.org/wiki/Lumen_Prize)
- [Muhannad Shono, Wikipedia](https://en.wikipedia.org/wiki/Muhannad_Shono)
- [Osinachi (digital artist) — Wikipedia](https://en.wikipedia.org/wiki/Osinachi_(digital_artist))
- [Wikipedia – Manal AlDowayan](https://en.wikipedia.org/wiki/Manal_AlDowayan)
- [Wikipedia — Elias Crespin](https://en.wikipedia.org/wiki/Elias_Crespin)

</details>
<details><summary>erasedtapes.com (3)</summary>

- [Behind the Tapes: Rival Consoles in conversation with Daniel Brandt - Erased Tapes](https://www.erasedtapes.com/editorials/behind-the-tapes-rival-consoles-in-conversation-with-daniel-brandt)
- [Daniel Brandt - Erased Tapes artist page](https://erasedtapes.com/artist/daniel-brandt)
- [Daniel Brandt to premiere live A/V cinema rave at the Barbican - Erased Tapes](https://erasedtapes.com/news/2024-12-09/daniel-brandt-to-premiere-live-a-v-cinema-rave-at-the-barbican-409)

</details>
<details><summary>ex-is.org (1)</summary>

- [Pinktoned — EXiS](https://ex-is.org/ex-now/pinktoned)

</details>
<details><summary>expreso.ec (1)</summary>

- [Óscar Santillán invita a "escuchar al planeta" en su muestra inmersiva en Quito (Expreso)](https://www.expreso.ec/ocio/oscar-santillan-invita-escuchar-al-planeta-en-su-muestra-inmersiva-en-quito-262886.html)

</details>
<details><summary>extinction.zkm.de (1)</summary>

- [NoSearchBar, Net Art Extinction Timeline, ZKM](https://extinction.zkm.de/artworks/nosearchbar/)

</details>
<details><summary>fact.co.uk (2)</summary>

- [Coffee Machine (2023), FACT Liverpool](https://www.fact.co.uk/artwork/coffee-machine-2023)
- [Cosmotechnics: Atractor Studio + Semantica (2024) — FACT Liverpool](https://fact.co.uk/artwork/cosmotechnics-atractor-studio-semantica)

</details>
<details><summary>factmag.com (1)</summary>

- [Richard Mosse interview with Hans Ulrich Obrist, FACT Magazine](https://factmag.com/2023/12/08/richard-mosse-interview)

</details>
<details><summary>fadmagazine.com (2)</summary>

- [FAD Magazine: Osinachi's NFT series Different Shades of Water on show at 1-54](https://fadmagazine.com/?p=273205)
- [Hayward Gallery presents Heecheon Kim: Double Poser — FAD Magazine](https://fadmagazine.com/?p=299783)

</details>
<details><summary>falter.at (1)</summary>

- [Falter – KI-kritische Kunst mit gender bias (review, 30.09.2025)](https://www.falter.at/zeitung/20250930/ki-kritische-kunst-mit-gender-bias)

</details>
<details><summary>fashioninfilm.com (1)</summary>

- [Tray Tray Ko — Fashion in Film Festival](https://www.fashioninfilm.com/films/tray-tray-ko)

</details>
<details><summary>fdag.com.br (1)</summary>

- [Antonio Társis – 36th Bienal de São Paulo (Fortes D'Aloia & Gabriel)](https://fdag.com.br/en/news/antonio-tarsis-36th-bienal-de-sao-paulo/)

</details>
<details><summary>federaldbsite.hocalwire.in (1)</summary>

- [Kochi-Muziris Biennale: Dhiraj Rabha installation, The Federal](https://federaldbsite.hocalwire.in/category/features/kochi-muziris-biennale-assam-ulfa-insurgency-art-dhiraj-rabha-installation-plants-224563)

</details>
<details><summary>festival.1e9.community (1)</summary>

- [Re-Launching Luigi Broglio - 1E9 Festival der Zukunft, MUNICH Beyond](https://festival.1e9.community/munich-beyond/re-launching-luigi-broglio)

</details>
<details><summary>festmag.com (1)</summary>

- [First Look: Adelaide Biennial 2026 - Fest](https://festmag.com/2026/02/23/first-look-adelaide-biennial-2026/)

</details>
<details><summary>field-0.xyz (3)</summary>

- [Care at the Water's Edge — Reservoir Project / Water Campaign (field-0 site)](https://field-0.xyz/reservoir-project)
- [Drifting Bodies & The Humming of the Power Grid — Singapore Biennale 2025 (field-0 site)](https://field-0.xyz/singapore-biennale-2025)
- [How Much Wattage Is One Handbreadth of Water? — Storefront for Art and Architecture, 2025 (field-0 site)](https://field-0.xyz/how-much-wattage-is-one-handbreadth-of-water)

</details>
<details><summary>filmmaker.substack.com (1)</summary>

- [Maxwell Paparella, You Are What Irks You (Filmmaker Magazine newsletter)](https://filmmaker.substack.com/p/you-are-what-irks-you)

</details>
<details><summary>filmsandfestivals.britishcouncil.org (1)</summary>

- [The Rift - British Council Films and Festivals](https://filmsandfestivals.britishcouncil.org/projects/the-rift)

</details>
<details><summary>finestresullarte.info (1)</summary>

- [Finestre sull'Arte – Venice Biennale, there is also a bit of Italy: Theo Eshetu](https://www.finestresullarte.info/en/contemporary-art/venice-biennale-there-is-also-a-bit-of-italy-theo-eshetu-british-ethiopian-living-in-rome)

</details>
<details><summary>flash---art.com (1)</summary>

- [Marie de Brugerolle, Liminal Systems of Representation. A Conversation with Jordan Strafer (Flash Art)](https://flash---art.com/article/jordan-strafer/)

</details>
<details><summary>flaunt.com (1)</summary>

- [Sasha Stiles' 'REPETAE' — Flaunt](https://www.flaunt.com/post/sasha-stiles-repetae-prix-ars-electronica)

</details>
<details><summary>fluentum.org (1)</summary>

- [Fluentum collection – Jordan Strafer, TALK SHOW, 2026](https://www.fluentum.org/en/collection/talk_show/)

</details>
<details><summary>forbes.co (1)</summary>

- [Leonel Vásquez, el artista colombiano que escucha a las piedras del río — Forbes Colombia, 25 Oct 2023](https://forbes.co/2023/10/25/forbes-life/leonel-vasquez-el-artista-colombiano-que-escucha-a-las-piedras-del-rio/)

</details>
<details><summary>forbes.com.mx (1)</summary>

- [Forbes México / EFE — Museo en Austria dedica muestra al arte experimental de América Latina](https://forbes.com.mx/forbes-life/arte-y-cultura-museo-en-austria-dedica-muestra-al-arte-experimental-de-america-latina/)

</details>
<details><summary>freight.cargo.site (1)</summary>

- [PAPER – in conversation with Helena Uambembe 2024/2025 (Nisha Merit)](https://freight.cargo.site/m/J2257473008552503311962688224423/Helena-Uambembe---Paper-1.pdf)

</details>
<details><summary>funeralplay.com (1)</summary>

- [FuneralPlay (project website)](https://www.funeralplay.com/)

</details>
<details><summary>fxguide.com (1)</summary>

- [1st SORA music video (fxguide)](https://www.fxguide.com/?p=419437)

</details>
<details><summary>fzine.com (1)</summary>

- [This Is Not Your Standard Art Festival — Singapore Biennale 2025 guide (fzine)](https://www.fzine.com/culture/singapore-biennale-2025-guide)

</details>
<details><summary>gaceta.unam.mx (1)</summary>

- [Una canción hipnótica que arrulla el tiempo, un pop onírico (Gaceta UNAM)](https://www.gaceta.unam.mx/una-cancion-hipnotica-que-arrulla-el-tiempo-un-pop-onirico/)

</details>
<details><summary>gala.gre.ac.uk (1)</summary>

- [RADIO GHOST – University of Greenwich research repository (GALA)](https://gala.gre.ac.uk/id/eprint/42736)

</details>
<details><summary>galeriefrankelbaz.com (1)</summary>

- [Chloé Delarue portfolio – galerie frank elbaz (PDF)](https://galeriefrankelbaz.com/usr/library/documents/main/artists/32/gfe_delarue_chloe_portfolio_lr.pdf)

</details>
<details><summary>galeriethoman.com (1)</summary>

- [ongoing, individual adaptability – 03, Devin Kenny, Galerie Elisabeth & Klaus Thoman (with interview)](https://www.galeriethoman.com/?p=26155)

</details>
<details><summary>galleryviewer.com (1)</summary>

- [Galleryviewer – From Dead to Living Memory: what Kinshasa knows, what David Shongo questions](https://galleryviewer.com/en/article/2923/from-dead-to-living-memory-what-kinshasa-knows-wh)

</details>
<details><summary>games.geidai.ac.jp (1)</summary>

- [tomori — Master's Thesis Projects, GEIDAI GAMES 07 (Tokyo University of the Arts)](https://games.geidai.ac.jp/07/games/thesis_projects/tomori.html)

</details>
<details><summary>gamescenes.org (2)</summary>

- [Event: Heecheon Kim: Double Poser — Gamescenes](https://www.gamescenes.org/event-heecheon-kim-double-poser-december-1-january-7-2024-london/)
- [Game Art: Afrah Shafiq's Where Do the Ants Go? (2022-2023) — GameScenes](https://www.gamescenes.org/game-art-afrah-shafiqs-where-do-the-ants-go-2022-2023/)

</details>
<details><summary>gazelliarthouse.com (1)</summary>

- [Whitney \| Memo Akten and Katie Hofstadter, Gazelli Art House](https://gazelliarthouse.com/news/1419-whitney-the-thinking-ocean)

</details>
<details><summary>getty.edu (1)</summary>

- [In the Algorithm’s Eyes, “We Are Already Plants” — Getty News (Q&A)](https://www.getty.edu/news/bio-artist-spela-petric-interview-q-and-a)

</details>
<details><summary>gibca.se (1)</summary>

- [GIBCA 2025 – Helena Uambembe](https://www.gibca.se/en/gibca/gibca-2025-2/artists/helena-uambembe)

</details>
<details><summary>goodman-gallery.com (1)</summary>

- [Goodman Gallery – Zineb Sedira: 'Culture is a way of resisting'](https://goodman-gallery.com/news/zineb-sedira-culture-is-a-way-of-resisting)

</details>
<details><summary>graduation.kabk.nl (1)</summary>

- [Jan Zuiderveld, Master ArtScience 2023, KABK Graduation Catalogue](https://graduation.kabk.nl/2023/jan-zuiderveld)

</details>
<details><summary>greeknewsagenda.gr (1)</summary>

- [Interview with Pavlina Vagioni, Greek News Agenda](https://www.greeknewsagenda.gr/?p=23095)

</details>
<details><summary>greynoise.org (1)</summary>

- [Fazal Rizvi, biography, Grey Noise](https://www.greynoise.org/fazal-rizvi-bio)

</details>
<details><summary>guanaquerx.com (1)</summary>

- [Guanaquerx (project website)](https://guanaquerx.com/)

</details>
<details><summary>habitusliving.com (1)</summary>

- [Khaled Sabsabi Venice Biennale 2026 – Habitus Living](https://www.habitusliving.com/articles/khaled-sabsabi-venice-biennale-2026)

</details>
<details><summary>hackneycitizen.co.uk (1)</summary>

- [A takeaway of ideas - artist Ling Tan's Low Carbon Chinatown - Hackney Citizen](https://hackneycitizen.co.uk/2025/10/20/artist-ling-tan-low-carbon-chinatown/)

</details>
<details><summary>hahahafi.com (1)</summary>

- [HAFI, artist website (CV/About)](https://hahahafi.com/About)

</details>
<details><summary>hammer.ucla.edu (2)</summary>

- [Gabriela Ruiz — Hammer Museum, Made in L.A. 2025](https://hammer.ucla.edu/made-la-2025/gabriela-ruiz)
- [Mike Stoltz — Hammer Museum, Made in L.A. 2025](https://hammer.ucla.edu/made-la-2025/mike-stoltz)

</details>
<details><summary>harshitagrawal.com (1)</summary>

- [(Un)Still Life- Icon and Fetish, Harshit Agrawal (artist's website)](https://harshitagrawal.com/unstill-life-icon-and-fetish/)

</details>
<details><summary>hauserwirth.com (1)</summary>

- [Between salt and stardust: Julianknxx – Hauser & Wirth Ursula](https://www.hauserwirth.com/ursula/between-salt-and-stardust-julianknxx/)

</details>
<details><summary>havc.hr (1)</summary>

- [VR film Eyes of Shame Selected for 83rd Venice IFF Immersive Competition - Croatian Audiovisual Centre (HAVC)](https://havc.hr/eng/info-centre/news/vr-film-eyes-of-shame-selected-for-83rd-venice-iff-immersive-competition)

</details>
<details><summary>hek.ch (1)</summary>

- [TAFAA – Fertility Device (Uncanny Valley) – HEK collection](https://www.hek.ch/en/collection/artworks/tafaa-fertility-device-uncanny-valley)

</details>
<details><summary>heritage.sg (1)</summary>

- [Singapore Night Festival 2025 media release (National Heritage Board)](https://www.heritage.sg/sgnightfest/-/media/snf2025/press-release/media-release-dive-into-island-nights-at-singapore-night-festival-2025-where-stories-of-island-life-come-alive-as-of-23-july.pdf)

</details>
<details><summary>hfa.ucsb.edu (1)</summary>

- [Mojo: When Black Identity Shapes the Earth — UCSB HFA](https://hfa.ucsb.edu/news-entries/2023/1/30/black-ecology-event)

</details>
<details><summary>highart.fr (1)</summary>

- [High Art, Paris – Cooper Jacoby artist page](https://highart.fr/artists/cooper-jacoby/)

</details>
<details><summary>history.siggraph.org (3)</summary>

- [Ryu Furusawa: Mid Tide #3 - SIGGRAPH Asia 2024 Art Gallery (ACM SIGGRAPH History Archives)](https://history.siggraph.org/?p=192874)
- [Weidi Zhang, Donghao Ren: Cangjie's Poetry - SIGGRAPH 2021 Art Gallery (ACM SIGGRAPH History Archives)](https://history.siggraph.org/?p=68568)
- [“African Space Makers” by Kirchhof, Cavallo Faras and Afande (ACM SIGGRAPH History Archives)](https://history.siggraph.org/experience/african-space-makers-by-kirchhof-cavallo-faras-and-afande)

</details>
<details><summary>hivos.org (1)</summary>

- [Meet Dr. Faras who is exploring a new era of storytelling (Hivos)](https://hivos.org/meet-dr-faras-who-is-exploring-a-new-era-of-storytelling/)

</details>
<details><summary>hk.art.museum (1)</summary>

- [Scent of Raindrop (2024) — Hong Kong Museum of Art (related earlier work with evaporating water drops on rock)](https://hk.art.museum/en/web/ma/exhibitions-and-events/scent-of-raindrop.html)

</details>
<details><summary>hnfoundation.com (1)</summary>

- [Songs for Dying — Han Nefkens Foundation](https://www.hnfoundation.com/artists/korakrit-arunanondchai/songs-for-dying)

</details>
<details><summary>hollandfestival.nl (1)</summary>

- [Interview met Geumhyung Jeong — Holland Festival (republished ICA interview)](https://hollandfestival.nl/en/interview-met-geumhyung-jeong)

</details>
<details><summary>holly.plus (1)</summary>

- [Holly+ (project site)](https://holly.plus/)

</details>
<details><summary>holo.mg (1)</summary>

- [Julieta Gil's Photogrammatic Memory of Feminist Uprising in Mexico City Wins 2020 Lumen Prize - HOLO](https://www.holo.mg/stream/julieta-gil-nuestra-victoria-lumen-prize/)

</details>
<details><summary>homegrown.co.in (1)</summary>

- [Inside visual artist Afrah Shafiq's Minecraft-inspired interactive installation — Homegrown](https://homegrown.co.in/amp/story/homegrown-creators/inside-visual-artist-afrah-shafiqs-minecraft-inspired-interactive-installation)

</details>
<details><summary>hrw.org (2)</summary>

- [Human Rights Watch — Bringing the Climate Frontlines to the Red Carpet (August 2026)](https://www.hrw.org/news/2026/08/31/bringing-the-climate-frontlines-to-the-red-carpet)
- [Human Rights Watch — Solwata (feature, May 2026)](https://www.hrw.org/feature/2026/05/22/solwata)

</details>
<details><summary>hyperallergic.com (3)</summary>

- [Hyperallergic — Taiwan Presents 'Screen Melancholy: Li Yi-Fan' at the Venice Biennale](https://hyperallergic.com/taiwan-presents-screen-melancholy-li-yi-fan-at-the-venice-biennale/)
- [Joshua Serafin's Living Shrine to Gender Nonconformity - Hyperallergic](https://hyperallergic.com/964512/joshua-serafin-living-shrine-to-gender-nonconformity-cosmological-gangbang/)
- [Khaled Sabsabi’s Art of Collective Becoming – Hyperallergic (interview by Aruna D’Souza)](https://hyperallergic.com/khaled-sabsabis-art-of-collective-becoming/)

</details>
<details><summary>ica.art (1)</summary>

- [Under Construction — artist interview (ICA London)](https://www.ica.art/media/10164.pdf)

</details>
<details><summary>iclc.toplap.org (1)</summary>

- [ICLC 2023 Catalogue — Paola Torres Núñez del Prado](https://iclc.toplap.org/2023/catalogue/person/torres-nunez-del-prado-paola.html)

</details>
<details><summary>idfa.nl (6)</summary>

- [IDFA — We Are Dead Animals](https://www.idfa.nl/en/film/2199a031-3ed2-4e9d-8701-0a0cef4ceebe/we-are-dead-animals)
- [In 36,000 Ways (Site-Specific Installation) - IDFA Archive, IDFA 2025](https://www.idfa.nl/en/film/71f50066-72ab-4326-ac6b-80aa0fbc693a/in-36000-ways-(site-specific-installation))
- [Nothing to See Here - IDFA 2025 archive](https://www.idfa.nl/en/film/a03ee71b-1364-4658-923c-1d4b855f8d5c/nothing-to-see-here)
- [Reality Looks Back (2025) \| IDFA Archive](https://www.idfa.nl/en/film/77e673c5-0441-4c2f-9dc2-6b268638c724/reality-looks-back)
- [The Oracle: Ritual for the Future (for humans and non-humans) - IDFA 2025 archive](https://www.idfa.nl/en/film/c3aac403-e1f4-4044-bd52-0801cecb9baa/the-oracle:-ritual-for-the-future-(for-humans-and-non-humans))
- [The Rift (2025) - IDFA Archive](https://www.idfa.nl/en/film/463a729b-073d-4142-99bf-8f200657bc60/the-rift)

</details>
<details><summary>iffr.com (1)</summary>

- [IFFR 2026 – Café Kuba: Who Dared to Awaken the Dead Memory](https://iffr.com/en/iffr/2026/films/caf%C3%A9-kuba-who-dared-to-awaken-the-dead-memory)

</details>
<details><summary>iicnairobi.esteri.it (1)</summary>

- [Masterclass on Immersive Cinema with Vincenzo Cavallo, Istituto Italiano di Cultura di Nairobi](https://iicnairobi.esteri.it/en/?p=6479)

</details>
<details><summary>imal.org (2)</summary>

- [Letta Shtohryn – Realities in Transition residency, iMAL Brussels (8.3–30.4.2024)](https://www.imal.org/en/events/lettashtohryn)
- [Unknown Label, Nicolas Gourault, iMAL Brussels](https://imal.org/en/events/endbeginning/unknown-label-nicolas-gourault)

</details>
<details><summary>immerse-news.github.io (1)</summary>

- [Field Notes: Space-Making at Venice VR Expanded (Immerse)](https://immerse-news.github.io/field-notes-space-making-at-venice-vr-expanded-20ce4b9e924d.html)

</details>
<details><summary>in36000ways.org (1)</summary>

- [In 36,000 Ways - project website](https://www.in36000ways.org)

</details>
<details><summary>indailysa.com.au (1)</summary>

- ['Hundreds of hours': Honouring the art of labour at the Adelaide Biennial - InReview / InDaily](https://www.indailysa.com.au/inreview/visual-art/2026/04/17/hundreds-of-hours-honouring-the-art-of-labour-at-the-adelaide-biennial)

</details>
<details><summary>indiaartfair.in (1)</summary>

- [Where I Work: Afrah Shafiq — India Art Fair](https://indiaartfair.in/where-i-work-afrah-shafiq)

</details>
<details><summary>inresidence.videobrasil.org.br (2)</summary>

- [Janaina Wagner > QUANDO O SEGUNDO SOL CHEGAR – Videobrasil In Residence](https://inresidence.videobrasil.org.br/2024/09/23/janaina-wagner-quando-o-segundo-sol-chegar/)
- [JANAINA WAGNER> QUANDO O SEGUNDO SOL CHEGAR (COMETA) – Videobrasil In Residence](https://inresidence.videobrasil.org.br/2024/06/14/janaina-wagner-quando-o-segundo-sol-chegar-cometa)

</details>
<details><summary>instrumentinventors.org (1)</summary>

- [Jan Zuiderveld, Coffee Machine and Microwave, video, iii](https://instrumentinventors.org/?p=33685)

</details>
<details><summary>int-lab.cc (1)</summary>

- [Codex Virtualis – project site by Interspecifics (int-lab.cc/codex)](https://int-lab.cc/codex/?page_id=2)

</details>
<details><summary>iqoqo.org (1)</summary>

- [Is this the age of Afro-Immersion? XR, ritual, and the rise of African spatial futures (iQoqo, 2025)](https://iqoqo.org/is-this-the-age-of-afro-immersion-xr-ritual-and-the-rise-of-african-spatial-futures/)

</details>
<details><summary>isea-archives.org (3)</summary>

- [\[ISEA2019\] Artist Statement: Louis-Philippe Rondeau - LIMINAL](https://isea-archives.org/?p=43509)
- [\[ISEA2023\] Artist Statement: Rachel Rossin — The Maw Of (2022) — ISEA Symposium Archives](https://www.isea-archives.org/isea2023_art-event_rossin)
- [Claudia Costa Pederson, 'Life-as-it-could-be: Symbiosis in Interspecifics' Codex Virtualis\_Genesis', ISEA2023](https://www.isea-archives.org/isea2023_presentation_pederson)

</details>
<details><summary>itsnicethat.com (2)</summary>

- [AI tools paint a blurry picture of our current reality (It's Nice That, essay by Linda Dounia Rebeiz)](https://www.itsnicethat.com/features/linda-dounia-rebeiz-ai-bias-technology-creative-industry-art-011123)
- [Nicer Tuesdays: Keiken on Wisdoms of Love 3.0 — It's Nice That](https://www.itsnicethat.com/articles/nicer-tuesdays-october-keiken-digital-171121)

</details>
<details><summary>j-mediaarts.jp (1)</summary>

- [Cangjie (earlier version) - 23rd Japan Media Arts Festival, Art Division Jury Selection](https://j-mediaarts.jp/en/award/single/cangjie/index-2.html)

</details>
<details><summary>jan-kaps.com (1)</summary>

- [Jan Kaps – Helena Uambembe, 36th Bienal de São Paulo (press release)](https://jan-kaps.com/exhibitions/36th-bienal-de-so-paulo)

</details>
<details><summary>jar-online.net (1)</summary>

- [Giusy Caruso, XR Music Performance: a phygital piano duet in the metaverse, JAR](https://jar-online.net/en/node/2344)

</details>
<details><summary>joaquinaras.com (1)</summary>

- [Añoranzas (Yira Yira) — Joaquín Aras (artist website)](https://joaquinaras.com/proyectos/anoranzas-yira-yira/)

</details>
<details><summary>jovialvares93.wixsite.com (1)</summary>

- [Jovita Alvares, artist website (The Wanderer)](https://jovialvares93.wixsite.com/thewanderer)

</details>
<details><summary>jpf.go.jp (1)</summary>

- [\[Announcement\] La Biennale di Venezia: Yuko Mohri “Compose” at the Japan Pavilion (The Japan Foundation press release)](https://www.jpf.go.jp/e/about/press/2024/002.html)

</details>
<details><summary>julietagil.com (1)</summary>

- [Nuestra Victoria - Julieta Gil (artist's website)](https://julietagil.com/Nuestra-Victoria)

</details>
<details><summary>kaapuera.bienal.org.br (1)</summary>

- [Ka’a Pûera: we are walking birds – Works, Fundação Bienal de São Paulo (pool source)](https://kaapuera.bienal.org.br/en/works/)

</details>
<details><summary>keijserskoning.com (1)</summary>

- [Whitney Museum of Art commissions work by Ashley Zelinskie - Keijsers Koning (13 Nov 2024)](https://www.keijserskoning.com/news/47-whitney-museum-of-art-commissions-work-by-ashley-twin-quasar-by-ashley-zelinskie-was-commissioned-for/)

</details>
<details><summary>keiken.cloud (3)</summary>

- [Wisdoms for Love 3.0 (SeMA Bunker) — Keiken](https://keiken.cloud/work/wisdoms-for-love-3-0-3/)
- [Wisdoms for Love 3.0 (Trimester 1, HEK / Transfer Gallery) — Keiken](https://keiken.cloud/work/wisdoms-for-love-3-0/)
- [Wisdoms for Love 3.0 (Trimester 2) — Keiken](https://keiken.cloud/work/wisdoms-for-love-3-0-2/)

</details>
<details><summary>kiangmalingue.com (1)</summary>

- [Wong Ping — puberty, The Art Gallery of Western Australia — Kiang Malingue](https://kiangmalingue.com/wong-ping-the-art-gallery-of-western-australia/)

</details>
<details><summary>kontejner.org (1)</summary>

- [The Echinoidea future – Adriatic sensing — KONTEJNER, A Sea Change / Heard by the Deep](https://kontejner.org/en/projekti/a-sea-change/kako-nas-cuje-more/izlo/the-echinoidea-future-adriatic-sensing)

</details>
<details><summary>kunst-im-tunnel.de (1)</summary>

- [long time lung time continuuuum!!! (a conver-something) - KIT Kunst im Tunnel](https://www.kunst-im-tunnel.de/en/exhibition/long-time-lung-time-continuuuum-a-conver-something/)

</details>
<details><summary>kunsthalltrondheim.no (1)</summary>

- [Opening: Songs for dying and Nets of Hyphae — Kunsthall Trondheim](https://kunsthalltrondheim.no/en/arrangementer/apning-songs-for-dying-og-nets-of-hyphae)

</details>
<details><summary>kunstradio.at (1)</summary>

- [Radiokunst – Kunstradio, 23 July 2023: Temporary Stored by Joseph Kamaru](https://www.kunstradio.at/2023B/23_07_2023en.html)

</details>
<details><summary>kw-berlin.de (1)</summary>

- [KW on location: Rachel Rossin, THE MAW OF — KW Institute for Contemporary Art](https://www.kw-berlin.de/en/exhibitions/exhibition-kw-on-location-rachel-rossin-the-maw-of)

</details>
<details><summary>lab.slv.vic.gov.au (1)</summary>

- [Living through the creation story of AI – Amelia Winger-Bearskin (SLV LAB conversation)](https://lab.slv.vic.gov.au/articles/interview-with-amelia-winger-bearskin)

</details>
<details><summary>labiennale.org (20)</summary>

- [Biennale Arte 2022 \| Geumhyung Jeong](https://www.labiennale.org/en/art/2022/milk-dreams/geumhyung-jeong)
- [Biennale Cinema 2020 \| African Space Makers](https://www.labiennale.org/en/cinema/2020/venice-vr-expanded/african-space-makers)
- [Collective Body - Venice Immersive 2025, La Biennale di Venezia](https://www.labiennale.org/en/cinema/2025/venice-immersive/collective-body)
- [Eyes of shame (Gėdos akys) - Venice Immersive 2026, La Biennale di Venezia](https://www.labiennale.org/en/cinema/2026/venice-immersive/eyes-shame-g%C4%97dos-akys)
- [Hotel Infinity - Venice Immersive, Biennale Cinema 2026](https://www.labiennale.org/en/cinema/2026/venice-immersive/hotel-infinity)
- [Joshua Serafin - Biennale Arte 2024, Nucleo Contemporaneo](https://www.labiennale.org/en/art/2024/nucleo-contemporaneo/joshua-serafin)
- [Khaled Sabsabi – Biennale Arte 2026, La Biennale di Venezia](https://www.labiennale.org/en/art/2026/khaled-sabsabi)
- [La Biennale di Venezia – Biennale Arte 2022: Ali Cherri](https://labiennale.org/en/node/10275)
- [La Biennale di Venezia – Biennale Arte 2026, Theo Eshetu (text by Melanie Roumiguière)](https://www.labiennale.org/en/art/2026/theo-eshetu)
- [La Biennale di Venezia — Fermata: Hong Kong in Venice (collateral event)](https://www.labiennale.org/en/node/19749)
- [La Biennale di Venezia — Venice Immersive 2026: Solwata](https://www.labiennale.org/en/cinema/2026/venice-immersive/solwata)
- [La laguna parla - Venice Immersive 2026, La Biennale di Venezia](https://www.labiennale.org/en/cinema/2026/venice-immersive/la-laguna-parla)
- [Manauara Clandestina – Biennale Arte 2024](https://www.labiennale.org/en/art/2024/nucleo-contemporaneo/manauara-clandestina-0)
- [Mnemosyne — Venice Immersive 2025 (La Biennale di Venezia)](https://www.labiennale.org/en/cinema/2025/venice-immersive/mnemosyne)
- [Octopocalypse - Biennale Cinema 2026, Venice Immersive (synopsis, creators' statement)](https://www.labiennale.org/en/cinema/2026/venice-immersive/octopocalypse)
- [Ri-lancia Luigi Broglio (Re-Launching Luigi Broglio) - Venice Immersive 2025, La Biennale di Venezia](https://www.labiennale.org/en/cinema/2025/venice-immersive/ri-lancia-luigi-broglio-re-launching-luigi-broglio)
- [The Great Orator - Venice Immersive 2025, La Biennale di Venezia](https://www.labiennale.org/en/cinema/2025/venice-immersive/great-orator)
- [Tomori — Venice Immersive 2026 (La Biennale di Venezia)](https://www.labiennale.org/en/cinema/2026/venice-immersive/tomori)
- [Venice Immersive selection and competition announced (La Biennale di Venezia, 2025)](https://www.labiennale.org/en/news/venice-immersive-selection-and-competition-announced)
- [Venice Immersive selection and competition announced - La Biennale di Venezia](https://www.labiennale.org/en/news/venice-immersive-selection-and-competition-announced-0)

</details>
<details><summary>labocine.com (3)</summary>

- [HANDMADE - Labocine (reproduces MoMA exhibition text)](https://www.labocine.com/films/handmade)
- [Labocine — We Are Dead Animals](https://www.labocine.com/films/we-are-dead-animals)
- [The Oracle: Ritual for the Future - Labocine](https://www.labocine.com/films/the-oracle-ritual-for-the-future-for-humans-and-non-humans)

</details>
<details><summary>laboralcentrodearte.org (1)</summary>

- [Mapping an uncertain landscape – LABoral Centro de Arte (exhibition Digital Machines)](https://laboralcentrodearte.org/?p=48634)

</details>
<details><summary>lafayetteanticipations.com (1)</summary>

- [TAFAA – FERTILITY DEVICE (NUDGE FOR THE SCAPEGOAT), 2021 – Lafayette Anticipations collection (describes the FERTILITY DEVICE group)](https://www.lafayetteanticipations.com/en/node/9935)

</details>
<details><summary>lahorebiennale.org (2)</summary>

- [Lahore Biennale 03, Ehsan ul Haq & Iqra Tanveer](https://lahorebiennale.org/lb03-artists/ehsan-ul-haq-iqra-tanveer/)
- [Tariq Alexander Qaiser — Lahore Biennale 03 artist page](https://lahorebiennale.org/lb03-artists/tariq-alexander-qaiser/)

</details>
<details><summary>landmarks.utexas.edu (1)</summary>

- [Anxious Body — Landmarks, University of Texas at Austin](https://landmarks.utexas.edu/video-art/anxious-body)

</details>
<details><summary>lefresnoy.net (1)</summary>

- [Le Fresnoy — Panorama 27: Camille Sauer, Le miroir](https://www.lefresnoy.net/en/exposition/2655/oeuvre/2722)

</details>
<details><summary>leonelvasquez.com (1)</summary>

- [Templo del Agua Sumapaz — Leonel Vásquez website](https://www.leonelvasquez.com/obra/584/)

</details>
<details><summary>lerandom.art (2)</summary>

- [Beeple on Robot Dogs as Canvas - Le Random (interview by Peter Bauman)](https://www.lerandom.art/editorial/beeple-on-robot-dogs-as-canvas)
- [Linda Dounia on Memory Machines (Le Random)](https://www.lerandom.art/editorial/linda-dounia-on-memory-machines)

</details>
<details><summary>lettashtohryn.online (1)</summary>

- [Чули ? Чули / Chuly? Chuly – artist website](https://www.lettashtohryn.online/chuly-chuly)

</details>
<details><summary>limkangli.net (1)</summary>

- [Singapore Night Festival 2025 – Projection Mapping, Lim KangLi website](https://limkangli.net/nightfest-projection-mapping/)

</details>
<details><summary>link.springer.com (2)</summary>

- [Atairu, 'Reimagining Benin Bronzes using generative adversarial networks', AI & Society 39 (2024)](https://link.springer.com/article/10.1007/s00146-023-01761-7)
- [GENERATING: Feminine Artificial Intelligence (Larcher, Springer chapter)](https://link.springer.com/chapter/10.1007/978-3-031-91995-4_9)

</details>
<details><summary>lisablackmore.net (1)</summary>

- [Templo del agua — curatorial text by Lisa Blackmore, NC ARTE Proyectos 2022–2023 (exhibition 26.08.23–14.10.23)](https://lisablackmore.net/wp-content/uploads/2024/08/Templo-de-agua_Curatorial-Text.pdf)

</details>
<details><summary>listart.mit.edu (1)</summary>

- [Leslie Thornton: Begin Again, Again - MIT List Visual Arts Center brochure (2022, PDF)](https://listart.mit.edu/sites/default/files/media/documents/exhibitions/2022_leslie_thornton_begin_again_brochure.pdf)

</details>
<details><summary>liviabenavides.com (1)</summary>

- [Oscar Santillán: "¿Qué se siente ser tierra?" opens in Quito (Livia Benavides)](https://liviabenavides.com/noticias/oscar-santillan-que-se-siente-ser-tierra-opens-in-quito/)

</details>
<details><summary>llull.cat (1)</summary>

- [Catalonia in Venice: Claudia Pagès Rabal, Paper Tears – Institut Ramon Llull project page](https://www.llull.cat/monografics/papertears/en/project.cfm)

</details>
<details><summary>lobster-lilac-hmlw.squarespace.com (1)</summary>

- [Nyctinasty, Hayley Millar Baker (artist's website)](https://lobster-lilac-hmlw.squarespace.com/nyctinasty)

</details>
<details><summary>log.fakewhale.xyz (1)</summary>

- [Fakewhale in Dialogue with Claudia Pagès Rabal](https://log.fakewhale.xyz/fakewhale-in-dialogue-with-claudia-pages-rabal/)

</details>
<details><summary>loophole.art (1)</summary>

- [To Carry: The Last Look at the Sharjah Biennial 16 – Loophole](https://loophole.art/articles/sharjah-biennial-16)

</details>
<details><summary>lowcarbon.lingql.com (2)</summary>

- [100 Climate Actions (online toolkit)](https://lowcarbon.lingql.com/100-climate-actions)
- [Low Carbon Chinatown - Hackney's Low Carbon Chinatown / Harvesting Climate Action (artist's project site)](https://lowcarbon.lingql.com/chinatown)

</details>
<details><summary>lrt.lt (1)</summary>

- [Venecijos kino festivalyje - lietuviško animacinio filmo premjera Gėdos akys - LRT Mediateka](https://www.lrt.lt/mediateka/irasas/2000851535/venecijos-kino-festivalyje-lietuvisko-animacinio-filmo-premjera-gedos-akys)

</details>
<details><summary>lumaocto.com (1)</summary>

- [Octopocalypse - Luma Octo (project website)](https://www.lumaocto.com)

</details>
<details><summary>lumenprize.com (3)</summary>

- [3D/Interactive Award Winner 2021 - The Lumen Prize](https://lumenprize.com/2021-winners/3d-interactive-winner)
- [Global South Award Winner 2021 – Lumen Prize](https://www.lumenprize.com/2021-winners/global-majority-winner)
- [Gold Award Winner 2020: Julieta Gil - Lumen Prize](https://lumenprize.com/2020-winners/julieta-gil)

</details>
<details><summary>lwt3.com (1)</summary>

- [LWT3 project page, Giusy Caruso](https://lwt3.com/project/giusycaruso/)

</details>
<details><summary>magazine.artconnect.com (1)</summary>

- [Keiken: Deconstructing the Now — ArtConnect Magazine](https://magazine.artconnect.com/interviews/magazine/keiken-deconstructing-the-now)

</details>
<details><summary>magazine.dirt.fyi (1)</summary>

- [Nothing is inevitable - Lily Goldberg interviews Annie Dorsen, The Dirt](https://www.magazine.dirt.fyi/p/nothing-inevitable)

</details>
<details><summary>magazine.shots.net (1)</summary>

- [Sora makes The Hardest Part look easy (shots)](https://magazine.shots.net/news/view/sora-makes-the-hardest-part-look-easy)

</details>
<details><summary>marc-hericher.com (1)</summary>

- [absence – Marc Hericher (artist site)](http://marc-hericher.com/project/absence/)

</details>
<details><summary>masp.org.br (2)</summary>

- [Video Room: Janaina Wagner – MASP](https://masp.org.br/en/exhibitions/video-room-janaina-wagner)
- [Video Room: Manauara Clandestina – MASP](https://www.masp.org.br/en/exhibitions/video-room-manauara-clandestina)

</details>
<details><summary>mediaartexploration.org (1)</summary>

- [Prometheus Firebringer - Media Art Xploration](https://mediaartexploration.org/?p=2027)

</details>
<details><summary>mediacityseoul.kr (1)</summary>

- [Evaporating Symphony — 13th Seoul Mediacity Biennale artwork page](https://mediacityseoul.kr/en/yesterday/artworks/evaporating-symphony)

</details>
<details><summary>medias.unifrance.org (1)</summary>

- [Anxious Body press kit (Miyu Productions & New Deer), Unifrance](https://medias.unifrance.org/medias/32/180/242720/presse/anxious-body-%E3%83%97%E3%83%AC%E3%82%B9%E3%82%AD%E3%83%83%E3%83%88-%E8%8B%B1%E8%AA%9E.pdf)

</details>
<details><summary>memo.tv (1)</summary>

- [The Thinking Ocean, project page, memo.tv](https://www.memo.tv/projects/2026/thinkingocean/)

</details>
<details><summary>metalab.harvard.edu (1)</summary>

- [Igùn – metaLAB (at) Harvard](https://metalab.harvard.edu/p/igun)

</details>
<details><summary>metamorf.no (1)</summary>

- [Frode Oldereid & Thomas Kvam – Meta.Morf 2024 \[up\]Loaded Bodies](https://metamorf.no/2024/?p=942)

</details>
<details><summary>michellelopez.com (4)</summary>

- [2025 Pandemonium — Michelle Lopez](https://www.michellelopez.com/exhibitions/2025-pandemonium)
- [2026 Whitney Biennial — Michelle Lopez](https://www.michellelopez.com/exhibitions/2026-whitney-biennial)
- [Hyperallergic: The Polycrisis Sublime of the Whitney Biennial (reprinted on artist's site)](https://www.michellelopez.com/writing/hyperallergic-the-polycrisis-sublime)
- [Whitney Biennial catalogue: conversation between Michelle Lopez and Christopher Lew](https://www.michellelopez.com/writing/whitney-biennial-catalogue-conversation-between-michelle-lopez-christopher-lew)

</details>
<details><summary>minneatairu.com (1)</summary>

- [Minne Atairu – artist website](https://minneatairu.com/)

</details>
<details><summary>mmca.go.kr (1)</summary>

- [MMCA Performing Arts 2021: Multiverse (brochure)](https://www.mmca.go.kr/upload/exhibition/2021/04/2021042805041105416736.pdf)

</details>
<details><summary>moguravr.com (1)</summary>

- [Six works by Japanese creators selected for Venice Immersive 2026 (MoguraVR, Japanese)](https://www.moguravr.com/misaharu-voxelkei-venice-immersive-2026/)

</details>
<details><summary>moma.org (1)</summary>

- [Leslie Thornton's HANDMADE - MoMA exhibition page](https://www.moma.org/calendar/exhibitions/5653)

</details>
<details><summary>momaps1.org (1)</summary>

- [Jumana Manna and Rabea Eghbariah in Conversation (MoMA PS1)](https://www.momaps1.org/en/post/213-jumana-manna-and-rabea-eghbariah-in-conversation)

</details>
<details><summary>morebranches.com (1)</summary>

- [Meet Osinachi, The Cryptoartist Fronting The Tokenized Artwork Movement In Africa (MoreBranches)](https://www.morebranches.com/meet-osinachi/)

</details>
<details><summary>mosmanartgallery.org.au (1)</summary>

- [Kawita Vatanajyankur: Performing Textiles - Mosman Art Gallery](https://mosmanartgallery.org.au/exhibition/kawita-vatanajyankur-performing-textiles/)

</details>
<details><summary>mpib-berlin.mpg.de (1)</summary>

- [Karim Ben Khelifa - Artist in Residence, Center for Humans and Machines, Max Planck Institute for Human Development](https://www.mpib-berlin.mpg.de/chm/air/khelifa)

</details>
<details><summary>mplus.org.hk (2)</summary>

- [M+ Facade unveils 'Ho Tzu Nyen: Night Charades' (press release, 23 Jan 2025)](https://mplus.org.hk/en/press/mplus-facade-ho-tzu-nyen-night-charades)
- [Night Charades: Reimagining Hong Kong Cinema (M+ Magazine interview)](https://mplus.org.hk/en/magazine/night-charades-reimaging-hong-kong-cinema)

</details>
<details><summary>mubi.com (1)</summary>

- [MUBI – Mother of Fog (synopsis)](https://mubi.com/en/br/films/mother-of-fog)

</details>
<details><summary>muslimnetwork.tv (1)</summary>

- [Noor Riyadh lights up metro stations in Saudi with immersive artworks – Muslim Network TV](https://www.muslimnetwork.tv/?p=58837)

</details>
<details><summary>myartguides.com (3)</summary>

- [An Interview with Seba Calfuqueo, Mapuche Artist and Activist — My Art Guides](https://myartguides.com/interviews/an-interview-with-seba-calfuqueo-mapuche-artist-and-activist)
- [Mercedes Nasta: Honorata, 11 Oct 2025 – 05 Apr 2026 (My Art Guides, MUAC listing)](https://myartguides.com/exhibitions/mexico-city/mercedes-nasta-honorata/)
- [Pavlina Vagioni: Oikeiōsis, My Art Guides](https://myartguides.com/exhibitions/venice/pavlina-vagioni-oikeiosis/)

</details>
<details><summary>myjoyonline.com (1)</summary>

- [The Nigerian AI artist reimagining a stylish old age (MyJoyOnline reprint of the BBC piece)](https://www.myjoyonline.com/the-nigerian-ai-artist-reimagining-a-stylish-old-age/)

</details>
<details><summary>mymodernmet.com (1)</summary>

- [Malik Afegbua, Fashion Show for Elders (My Modern Met)](https://mymodernmet.com/malik-afegbua-fashion-show-for-elders/)

</details>
<details><summary>nacion.com (1)</summary>

- [El hombre que fabrica insectos, La Nación (Revista Dominical)](https://www.nacion.com/revista-dominical/el-hombre-que-fabrica-insectos-conozca-el-trabajo/QKBTIQRHBNBKXEN4NSZRC3RB7Y/story/)

</details>
<details><summary>newart.city (1)</summary>

- [Wisdoms for Love 3.0, by Keiken — Gray Area Festival 2021, New Art City](https://newart.city/catalog/gaf2021-room-6)

</details>
<details><summary>newmedia.udk-berlin.de (2)</summary>

- [Erik Anton Reinhardt, NoSearchBar, UdK Berlin New Media Class](https://newmedia.udk-berlin.de/students/erik-anton-reinhardt/nosearchbar)
- [NoSearchBar, UdK Berlin New Media Class project (Re-state, re-stage, re-enact, Winter 2021)](https://newmedia.udk-berlin.de/projects/2021-ws-k/nosearchbar)

</details>
<details><summary>newmediawritingprize.co.uk (1)</summary>

- [REPETAE: WORDS CAN COMMUNICATE BEYOND WORDS — New Media Writing Prize](https://newmediawritingprize.co.uk/?p=1618)

</details>
<details><summary>news.cgtn.com (1)</summary>

- [VR opera, AR tigers: Welcome to China's immersive cinema (CGTN, 2025)](https://news.cgtn.com/news/2025-07-05/VR-opera-AR-tigers-Welcome-to-China-s-immersive-cinema-1EK0sXX6CKA/share_amp.html)

</details>
<details><summary>news4jax.com (1)</summary>

- [Robot dogs with Musk and Zuckerberg heads roam around Berlin gallery in Beeple's new exhibit - AP via News4JAX](https://www.news4jax.com/entertainment/2026/04/28/robot-dogs-with-musk-and-zuckerberg-heads-roam-around-berlin-gallery-in-beeples-new-exhibit/)

</details>
<details><summary>newsday.co.zw (1)</summary>

- [Immersive dance film The Rift premieres at IDFA festival - NewsDay](https://www.newsday.co.zw/southerneye/lifestyle-amp-arts/article/200048477/immersive-dance-film-the-rift-premieres-at-idfa-festival)

</details>
<details><summary>nftculture.com (1)</summary>

- [3FACE is an adaptive artwork by artist Ian Cheng Launching on Outland (NFT Culture)](https://nftculture.com/?p=13255)

</details>
<details><summary>nga.gov.au (1)</summary>

- [National Gallery of Australia, Ceremony tour stop: Nyctinasty](https://nga.gov.au/tours/ceremony/stop/86/)

</details>
<details><summary>nguyenwahed.com (1)</summary>

- [Art Basel Miami Beach 2025: XCOPY, Kim Asendorf, and Joe Pease - Nguyen Wahed](https://nguyenwahed.com/art-basel-miami-beach-2025)

</details>
<details><summary>nikasimovich.github.io (1)</summary>

- [Megan Robinson, Leslie Thornton's Handmade (student postcard essay)](https://nikasimovich.github.io/postcards24/megan/index.html)

</details>
<details><summary>nime.org (1)</summary>

- [Maria Choir — NIME 2024 installation program notes](https://nime.org/proceedings/2024/nime2024_installations_7.pdf)

</details>
<details><summary>nofilmschool.com (1)</summary>

- [AI Artist Paul Trillo Talks His New Sora-Powered Music Video (No Film School)](https://nofilmschool.com/ai-music-video)

</details>
<details><summary>noorderlicht.com (2)</summary>

- [Liquid Crystal (Noorderlicht Biennale)](https://noorderlicht.com/en/whats-on/noorderlicht-biënnale-machine-entanglements/kick-off-van-de-noorderlicht-biënnale-in-japan/liquid-crystal)
- [Unknown Label, Noorderlicht](https://noorderlicht.com/en/whats-on/pixel-perceptions/unknown-label)

</details>
<details><summary>noproscenium.com (2)</summary>

- [The Great Orator — VR Trailer Reveal, No Proscenium](https://www.noproscenium.com/the-great-orator-vr-trailer-reveal/)
- [Venice Immersive 2026 video diary (NoProScenium), lists the installation with its synopsis](https://www.noproscenium.com/venice-immersive-video-diary-2026/)

</details>
<details><summary>nublockmuseum.blog (1)</summary>

- [Collection Spotlight: Seba Calfuqueo, Tray Tray Ko — Stories From The Block](https://nublockmuseum.blog/2025/03/11/collection-spotlight-seba-calfuqueo-tray-tray-ko/)

</details>
<details><summary>o-matic.com (1)</summary>

- [The River is a Circle — o-matic.com](https://o-matic.com/?p=9460)

</details>
<details><summary>odt.co.nz (1)</summary>

- [Dunedin's newspaper inspiration - Otago Daily Times](https://www.odt.co.nz/entertainment/arts/dunedin%E2%80%99s-newspaper-inspiration)

</details>
<details><summary>oinstituto.pt (1)</summary>

- [Angie Saiz – INSTITUTO residency](https://oinstituto.pt/en/angie-saiz/)

</details>
<details><summary>okayafrica.com (3)</summary>

- [How Anthony Azekwoh is pushing the boundaries of what it means to be a digital artist (OkayAfrica)](https://www.okayafrica.com/how-anthony-azekwoh-is-pushing-the-boundaries-of-what-it-means-to-be-a-digital-artist/1411266)
- [OkayAfrica – Yinka Bernie: Running Egwu Records & 'Moving Parts' Exhibition](https://www.okayafrica.com/what-its-like-to-run-an-indie-record-company-and-keep-vinyl-alive/1418023)
- [South African Artist Simnikiwe Buhlungu on Creating the Sound of Dreams - OkayAfrica](https://okayafrica.com/venice-biennale-2022-buhlungu)

</details>
<details><summary>oldereid-kvam.com (1)</summary>

- [Requiem for an Exit (2024) – Oldereid / Kvam (artists' website)](https://www.oldereid-kvam.com/gallery)

</details>
<details><summary>olongoafrica.com (1)</summary>

- [How Anthony Azekwoh is creating a future of myths (Olongo Africa)](https://olongoafrica.com/how-anthony-azekwoh-is-creating-a-future-of-myths/)

</details>
<details><summary>onepointfour.co (1)</summary>

- [Jordan Clarke - f\*ckai? (famous) - Onepointfour](https://onepointfour.co/entries/jordan-clarke-fckai-famous)

</details>
<details><summary>onlineonly.christies.com.cn (1)</summary>

- [Christie's, Osinachi, Man in a Pool II — lot essay (Different Shades of Water)](https://onlineonly.christies.com.cn/s/first-open-post-war-contemporary-art-online/osinachi-b-1991-7/132122)

</details>
<details><summary>onmanorama.com (1)</summary>

- [Kochi-Muziris Biennale: Dhiraj Rabha's Assam insurgency installation, Onmanorama](https://www.onmanorama.com/news/kerala/2026/01/03/kochi-muziris-biennale-dhiraj-rabha-assam-insurgency-art-installation.html)

</details>
<details><summary>opendoclab.mit.edu (2)</summary>

- [Layers of Place: Austin — The Founders Pillars – MIT Open Documentary Lab](https://opendoclab.mit.edu/presents/layers-place-austin-founders-pillars/)
- [Layers of Place: MIT — The Fovnders Pillars – MIT Open Documentary Lab](https://opendoclab.mit.edu/?p=24287)

</details>
<details><summary>opensecret.kw-berlin.de (1)</summary>

- [The Maw Of — Open Secret, KW Institute for Contemporary Art](https://opensecret.kw-berlin.de/artwork/the-maw-of/)

</details>
<details><summary>opera.beastsandnatives.com (1)</summary>

- [OPERA project site (beasts and natives alike)](http://opera.beastsandnatives.com/)

</details>
<details><summary>orylab.com (1)</summary>

- [OryLab Inc. (official site)](https://orylab.com/en/)

</details>
<details><summary>ototoy.jp (1)</summary>

- [バイノーラル化された自然音が誘う時空の旅──evala『聴象発景 in Rittor Base - HPL ver』 (OTOTOY interview)](https://ototoy.jp/feature/2021012501)

</details>
<details><summary>outlookindia.com (2)</summary>

- [The Artificial in Art: At the Intersection of AI and Tech at India Art Fair 2026, Outlook India (pool source; links to the Rabha article)](https://www.outlookindia.com/culture-society/the-artificial-in-art-at-the-intersection-of-ai-and-tech-at-india-art-fair-2026)
- [Where Memory Resists Power: The Many-Layered Histories in Dhiraj Rabha's Art, Outlook India](https://www.outlookindia.com/culture-society/where-memory-resists-power-the-many-layered-histories-in-dhiraj-rabhas-art)

</details>
<details><summary>paoloalmario.com (3)</summary>

- [Dyscrimina / Ausente – Paolo Almario](https://paoloalmario.com/portfolio/dyscrimina-ausente/)
- [Manifesto – Paolo Almario](https://paoloalmario.com/manifesto)
- [Paolo Almario – artist site (statement and bio)](https://paoloalmario.com/)

</details>
<details><summary>papermag.com (1)</summary>

- [Harry Tafoya, Isabelle Frances McGuire, American Dreamer and Nightmare Artist (PAPER, 26 February 2025)](https://www.papermag.com/isabelle-frances-mcguire)

</details>
<details><summary>patenteux.com (2)</summary>

- [PATENTEUX - Louis-Philippe Rondeau (artist's website, bio and exhibition list)](https://patenteux.com/wp/)
- [RÉSONANCES (2021) - PATENTEUX (artist's website)](https://patenteux.com/wp/portfolio/resonances-2021/)

</details>
<details><summary>peopleofcolorintech.com (1)</summary>

- [Meet the Nigerian AI artist redefining the older generation's style (POCIT, 2023)](https://peopleofcolorintech.com/front/meet-the-nigerian-ai-artist-redefining-the-older-generations-style/)

</details>
<details><summary>peterburr.org (1)</summary>

- [sunshine monument (artist's site)](https://peterburr.org/sunshine.php)

</details>
<details><summary>photography-now.com (1)</summary>

- [photography-now.com — Screen Melancholy (TFAM announcement)](https://photography-now.com/exhibition/176751)

</details>
<details><summary>pianostreet.com (1)</summary>

- [Piano Street Magazine: interview with Giusy Caruso on the Cremona Musica performance](https://www.pianostreet.com/blog/?p=11921)

</details>
<details><summary>pilarcorrias.com (1)</summary>

- [Ian Cheng debuts '3FACE', an innovative NFT project with Outland (Pilar Corrias)](https://pilarcorrias.com/news/37-ian-cheng-debuts-3face-an-innovative-nft-project)

</details>
<details><summary>playstation.com (1)</summary>

- [Hotel Infinity - PlayStation Store page (PS VR2)](https://www.playstation.com/en-us/games/hotel-infinity/)

</details>
<details><summary>pollinator.art (1)</summary>

- [pollinator.art (the artwork's website)](https://www.pollinator.art/)

</details>
<details><summary>povmagazine.com (1)</summary>

- [Foragers review by Allegra Moyle (POV Magazine)](https://povmagazine.com/?p=10556)

</details>
<details><summary>prd-cm.singaporeartmuseum.sg (1)</summary>

- [Media release: Singapore Biennale 2025: pure intention transforms the city into a platform (Singapore Art Museum)](https://prd-cm.singaporeartmuseum.sg/-/media/SAM/Files/Press-Release/2025-PR/Media-Release-Singapore-Biennale-2025-pure-intention-Transforms-the-City-Into-A-Platform.pdf)

</details>
<details><summary>press.moma.org (1)</summary>

- [MoMA announces new digital art acquisitions, exhibitions and artist collaborations (press release, October 10, 2023)](https://press.moma.org/wp-content/uploads/2023/10/MoMADigitalArtAnnouncements_FINAL-2.pdf)

</details>
<details><summary>presse.louvre.fr (1)</summary>

- [Musée du Louvre press — Elias Crespin, L'Onde du Midi](https://presse.louvre.fr/elias-crespinbr-londe-du-midibr-a-new-permanent-installationbr-for-the-louvre)

</details>
<details><summary>prospectmagazine.co.uk (1)</summary>

- [Richard Mosse: The biggest challenge was to make the audience feel their complicity, Prospect](https://prospectmagazine.co.uk/culture/60460/richard-mosse-the-biggest-challenge-was-to-make-the-audience-feel-their-complicity)

</details>
<details><summary>radical-openness.org (1)</summary>

- [Unknown Label, Art Meets Radical Openness 2024](https://radical-openness.org/en/programm/2024/unknown-label)

</details>
<details><summary>radionacional.co (2)</summary>

- ['Templo del agua' en Bogotá: experiencia interactiva donde el agua canta — Radio Nacional de Colombia, 5 Sept 2023](https://radionacional.co/cultura/arte/el-agua-canta-conoce-esta-exposicion-interactiva-en-bogota)
- [Escuchar el río y conectar con la vida que está en el agua — Radio Nacional de Colombia](https://www.radionacional.co/cultura/arte/escuchar-el-rio-y-conectar-con-la-vida-que-esta-en-el-agua)

</details>
<details><summary>radiopapesse.org (1)</summary>

- [Reality looks back by Anne Jeppesen \| Radio Papesse (audio version, 2024)](https://www.radiopapesse.org/en/archive/sonora/reality-looks-back)

</details>
<details><summary>raindanceimmersive.com (1)</summary>

- [Raindance Immersive 2026 – The Daladala Verse](https://www.raindanceimmersive.com/2026-the-daladala-verse/)

</details>
<details><summary>re-humanism.com (1)</summary>

- [Robertina Šebjanič — Re:humanism](https://www.re-humanism.com/?p=88)

</details>
<details><summary>redcat.org (1)</summary>

- [Annie Dorsen - REDCAT (2024)](https://redcat.org/events/2024/annie-dorsen)

</details>
<details><summary>renewablematter.eu (1)</summary>

- [Calculating and Powers: Interview with Kate Crawford, Renewable Matter](https://www.renewablematter.eu/en/artificial-intelligence-computations-power-interview-kate-crawford)

</details>
<details><summary>ricksilva.net (1)</summary>

- [Rick Silva (artist's site)](https://ricksilva.net)

</details>
<details><summary>rightclicksave.com (9)</summary>

- [An interview with XCOPY - Right Click Save](https://www.rightclicksave.com/article/an-interview-with-xcopy)
- [Larva Labs on Quine and Code as Art - Right Click Save (interview, 2 Oct 2025)](https://www.rightclicksave.com/article/larva-labs-on-quine-and-code-as-art-interview-generative-art)
- [Living Artwork — interview by Alex Estorick, Right Click Save](https://www.rightclicksave.com/article/living-artwork-alexandra-daisy-ginsberg-interview)
- [Right Click Save Index — Kim Asendorf](https://www.rightclicksave.com/index/people/2183/kim-asendorf)
- [Right Click Save — The Interview \| Kim Asendorf](https://www.rightclicksave.com/article/the-interview-kim-asendorf-generative-art-digital-art)
- [Right Click Save — Zero 10 Returns at Art Basel Hong Kong](https://www.rightclicksave.com/article/zero-10-returns-at-art-basel-hong-kong-art-fair-digital-art)
- [Right Click Save: The Interview \| Danielle Brathwaite-Shirley (2025)](https://www.rightclicksave.com/article/the-interview-danielle-brathwaite-shirley-the-delusion-serpentine-galleries-gaming)
- [Samia Halaby and Joshua Citarella to show at Whitney Biennial — Right Click Save](https://www.rightclicksave.com/article/samia-halaby-and-joshua-citarella-to-show-at-whitney-biennial)
- [Zero 10: Digital Art Goes Mainstream at Art Basel Miami Beach - Right Click Save](https://www.rightclicksave.com/article/zero-10-digital-art-goes-mainstream-at-art-basel-miami-beach)

</details>
<details><summary>riviste.unimi.it (1)</summary>

- [Essay on digital restitution and the Benin Bronzes discussing Igùn – Itinera (Università degli Studi di Milano)](https://riviste.unimi.it/index.php/itinera/article/download/27934/23426/78474)

</details>
<details><summary>riyadhart.sa (2)</summary>

- [Memory Melting – Riyadh Art artwork page](https://riyadhart.sa/en/artworks/memory-melting/)
- [Skeleton of the Glorious – Riyadh Art artwork page](https://riyadhart.sa/en/artworks/skeleton-of-the-glorious/)

</details>
<details><summary>robertina.net (1)</summary>

- [Echinoidea future – Adriatic sensing — Robertina Šebjanič (artist's site)](https://robertina.net/echinoidea-future-adriatic-sensing-starts4water-zero-pollution-adriatic/)

</details>
<details><summary>ru.cultura.unam.mx (1)</summary>

- [Nuestra Victoria - Re\_vista 003, Museo Experimental el Eco, UNAM (PDF)](https://ru.cultura.unam.mx/bitstream/123456789/653/2/Museo%20Experimental%20el%20Eco%2C%20UNAM_Nuestra%20Victoria.pdf)

</details>
<details><summary>russh.com (1)</summary>

- [RUSSH, Bare bones: Hayley Millar Baker on separating memory from experience](https://www.russh.com/hayley-millar-baker/)

</details>
<details><summary>ryufurusawa.com (1)</summary>

- [Mid Tide #3 - ryufurusawa.com](https://ryufurusawa.com/post/744711413283569664/mid-tide-3)

</details>
<details><summary>saha.org.tr (1)</summary>

- [The 36th São Paulo Biennial, Brazil – SAHA (supporter project page)](https://saha.org.tr/en/projects/the-36th-sao-paulo-biennial-brazil)

</details>
<details><summary>sashastiles.com (1)</summary>

- [Sasha Stiles (artist site)](https://www.sashastiles.com)

</details>
<details><summary>saudipavilion.org (1)</summary>

- [2022 The Teaching Tree, Saudi Pavilion](https://saudipavilion.org/art/2022-the-teaching-tree/)

</details>
<details><summary>sciarc.edu (1)</summary>

- [Alum Jeremy Kamal Talks Cultural Narratives and Sound-Informed Ecology — SCI-Arc](https://www.sciarc.edu/news/2020/alum-jeremy-kamal)

</details>
<details><summary>sciartcolab.cargo.site (1)</summary>

- [「Micro-Nano Landscape」 — SciArt Co-lab (AIRS)](https://sciartcolab.cargo.site/「micro-nano-landscape」)

</details>
<details><summary>sculpturemagazine.art (1)</summary>

- [From the Imagined World: A Conversation with Muhannad Shono, Sculpture magazine, 2023](https://sculpturemagazine.art/from-the-imagined-world-a-conversation-with-muhannad-shono/)

</details>
<details><summary>seebyyourears.jp (1)</summary>

- [聴象発景 in Rittor Base - HPL ver - See by Your Ears (project page)](https://seebyyourears.jp/projects/chosho-hakkei-rittor/)

</details>
<details><summary>seesawmag.com.au (1)</summary>

- [SymbioticA: art and science in symbiosis, Seesaw Magazine](https://www.seesawmag.com.au/2022/02/symbiotica-art-and-science-in-symbiosis)

</details>
<details><summary>serpentinegalleries.org (3)</summary>

- [Serpentine Arts Technologies (pool source)](https://www.serpentinegalleries.org/arts-technologies/)
- [Serpentine press page: Danielle Brathwaite-Shirley: I DIDNT REALISE YOU THOUGHT LIKE THAT](https://www.serpentinegalleries.org/about/press/danielle-brathwaite-shirley-ididntrealiseyouthoughtlikethat/)
- [Serpentine: I DIDNT REALISE YOU THOUGHT LIKE THAT (project page)](https://www.serpentinegalleries.org/whats-on/i-didnt-realise-you-thought-like-that/)

</details>
<details><summary>share.hek.ch (1)</summary>

- [Interview with Chloé Delarue – HEK share (video, Swiss Media Art – Pax Art Awards 2021, 2022)](https://share.hek.ch/en/interview-with-chloe-delarue/)

</details>
<details><summary>sharjahart.org (6)</summary>

- [EP05: Singing Wells x Natasha Ginwala – Biennial Bytes, Sharjah Art Foundation](https://www.sharjahart.org/en/resources/saf-online/details/ep05-singing-wells-x-natasha-ginwala)
- [Fazal Rizvi, Sharjah Biennial 16 participant page](https://sharjahart.org/en/sharjah-biennial/sb-16/people/details/fazal-rizvi)
- [Fazal Rizvi: Kissing of the Threshold, Sharjah Art Foundation publication](https://www.sharjahart.org/en/resources/publications/details/fazal-rizvi-kissing-of-the-threshold)
- [Sharjah Art Foundation – Um Al Dhabab (Mother of Fog) (2023)](https://www.sharjahart.org/en/projects/details/um-al-dhabab-mother-of-fog-2023)
- [Singing Wells: Sonic Inheritances (artist book) – Sharjah Art Foundation](https://www.sharjahart.org/en/resources/publications/details/singing-wells-sonic-inheritances)
- [Sonic Inheritances: Listening with Singing Wells – Sharjah Art Foundation](https://www.sharjahart.org/en/event/details/sonic-inheritances-listening-with-singing-wells/)

</details>
<details><summary>shinhanagata.com (2)</summary>

- [CHIMERIA - Shin Hanagata (artist's site)](https://www.shinhanagata.com/en/works/chimeria)
- [The Twisting Manifesto - Shin Hanagata (artist's site)](https://www.shinhanagata.com/en/statement)

</details>
<details><summary>shortsblog.berlinale.de (1)</summary>

- [„Futsu no seikatsu“ (Ordinary Life) / Interviews, press etc. — Berlinale Shorts](https://shortsblog.berlinale.de/2025/02/18/futsu-no-seikatsu-ordinary-life-interviews-press-etc)

</details>
<details><summary>showstudio.com (1)</summary>

- ['Silence Can Be A Form of Self-Dismissal' Julianknxx on the Art of Filmmaking – SHOWstudio](https://showstudio.com/news/silence-can-be-a-form-of-self-dismissal-julianknxx-on-the-art-of-filmmaking)

</details>
<details><summary>signals.digibc.org (1)</summary>

- [I Would Like to be Midnight I Would Like to be Sky (Signals, DigiBC)](https://signals.digibc.org/?p=8300)

</details>
<details><summary>simonwoodfilm.com (1)</summary>

- [The Founders Pillars – Simon Wood](https://simonwoodfilm.com/the-founders-pillars)

</details>
<details><summary>singaporeartmuseum.sg (1)</summary>

- [Artist Folio: Zarina Muhammad (Singapore Art Museum, SB2022)](https://www.singaporeartmuseum.sg/-/media/SAM/Files/Exhibitions/SB2022/Artist-Folio_Zarina_Muhammad.pdf?inline=1)

</details>
<details><summary>singaporebiennale.org (1)</summary>

- [Zarina Muhammad - Singapore Biennale](https://www.singaporebiennale.org/artists/zarina-muhammad)

</details>
<details><summary>singingwells.org (2)</summary>

- [Mission – Singing Wells](https://www.singingwells.org/mission/)
- [What We Do – Singing Wells](https://www.singingwells.org/what-we-do/)

</details>
<details><summary>site.videobrasil.org.br (1)</summary>

- [Residency Prize Cariri Cultural Center \| 22ª Bienal – Videobrasil](https://site.videobrasil.org.br/en/news/2247012)

</details>
<details><summary>slficaa.artgallery.wa.gov.au (4)</summary>

- [A happy accident — interview with Wong Ping (SLF ICAA)](https://slficaa.artgallery.wa.gov.au/interview/a-happy-accident/)
- [Kawita Vatanajyankur - Simon Lee Foundation Institute of Contemporary Asian Art (AGWA)](https://slficaa.artgallery.wa.gov.au/artists/kawita-vatanajyankur/)
- [My body as a domestic object (interview, Rachel Ciesla & Robert Cook)](https://slficaa.artgallery.wa.gov.au/interview/my-body-as-a-domestic-object/)
- [puberty — Simon Lee Foundation Institute of Contemporary Asian Art (AGWA)](https://slficaa.artgallery.wa.gov.au/program/puberty/)

</details>
<details><summary>smartphoneorchestra.com (1)</summary>

- [About - The Smartphone Orchestra](https://smartphoneorchestra.com/about/)

</details>
<details><summary>solos.gallery (1)</summary>

- [SOLOS - From Noise (exhibition page)](https://solos.gallery/exhibitions/from-noise)

</details>
<details><summary>sonar.ch (1)</summary>

- [Mapping uncertain landscape: mapping in times of uncertainty – master's thesis, HEAD Genève 2023 (SONAR)](https://sonar.ch/global/documents/325130)

</details>
<details><summary>sonyaisupova.cargo.site (1)</summary>

- [MAPPING UNCERTAIN LANDSCAPE: THE SATELLITE – artist website (Sonya Isupova)](https://sonyaisupova.cargo.site/The-Satelitte)

</details>
<details><summary>sopitas.com (1)</summary>

- [Sopitas - feature with Daniel Brandt on the Without Us film (Spanish)](https://www.sopitas.com/noticias/extincion-musica-electronica-desesperacion-salvar-el-mundo/)

</details>
<details><summary>space.com (1)</summary>

- [Step inside a virtual reality art piece inspired by the James Webb Space Telescope - Space.com](https://www.space.com/space-exploration/james-webb-space-telescope/step-inside-a-virtual-reality-art-piece-inspired-by-the-james-webb-space-telescope)

</details>
<details><summary>spelapetric.org (1)</summary>

- [PL'AI — Špela Petrič (artist's site)](https://www.spelapetric.org/plai/)

</details>
<details><summary>spikeartmagazine.com (1)</summary>

- [“The Body Is the Only Object”: Geumhyung Jeong — Spike Art Magazine](https://www.spikeartmagazine.com/articles/interview-the-body-is-the-only-object-geumhyung-jeong)

</details>
<details><summary>starts-prize-call.aec.at (2)</summary>

- [The Founders Pillars – S+T+ARTS Prize Africa 2025, Award of Distinction](https://starts-prize-call.aec.at/2025/winners/19515)
- [Written To Not Remain – S+T+ARTS Prize 2025 winners page](https://starts-prize-call.aec.at/2025/winners/16956)

</details>
<details><summary>starts-prize.aec.at (7)</summary>

- [Maria CHOIR — S+T+ARTS Prize 2024, Honorary Mention (Ars Electronica)](https://starts-prize.aec.at/maria-choir)
- [METABOLICA — S+T+ARTS Prize 2024, Honorary Mention](https://starts-prize.aec.at/metabolica)
- [MetaPhase, S+T+ARTS Prize 2023 (Honorary Mention)](https://starts-prize.aec.at/en/?p=4641)
- [Oceans in Transformation, S+T+ARTS Prize 2021 Grand Prize – Artistic Exploration](https://starts-prize.aec.at/de/?p=3587)
- [S+T+ARTS Prize 2021 winners (pool source)](https://starts-prize.aec.at/en/winners2021/)
- [S+T+ARTS Prize winners 2023 (pool source)](https://starts-prize.aec.at/en/winners2023/)
- [S+T+ARTS Prize winners 2024](https://starts-prize.aec.at/en/winners2024/)

</details>
<details><summary>starts.eu (5)</summary>

- [Interview with S+T+ARTS artists-in-residency Robertina Šebjanič and Marjan Žitnik — S+T+ARTS](https://starts.eu/?p=6556)
- [MEET THE ARTISTS: Maria Arnal Dimas — S+T+ARTS AIR](https://starts.eu/air-meet-the-artists-maria-arnal-dimas/)
- [S+T+ARTS Prize Buen TEK 2026 — Prize of Distinction, Leonel Vásquez (Cuna de Humedales; bio lists Templo da água: rio Tietê, 2025)](https://starts.eu/?p=28874)
- [S+T+ARTS – STARTS4AFRICA Residencies – The Dalala Verse](https://starts.eu/starts4africa-residencies-call-for-artists-the-dalala-verse/)
- [The Influence of Pollutants on the Adriatic Sea – in conversation with Robertina Šebjanič and Marjan Žitnik — S+T+ARTS](https://starts.eu/?p=7781)

</details>
<details><summary>stashmedia.tv (2)</summary>

- [Jordan Clarke Flips the AI Script With His New Short Film F\*ckai? (sexy) - Stash Magazine (28 Sep 2022)](https://www.stashmedia.tv/?p=91089)
- [Jordan Clarke Meets an AI who Wants to be Famous - Stash Magazine (23 Nov 2022)](https://www.stashmedia.tv/jordan-clarke-meets-an-ai-who-wants-to-be-famous/)

</details>
<details><summary>stimuleringsfonds.nl (1)</summary>

- [Nothing to see here - Creative Industries Fund NL (Stimuleringsfonds)](https://www.stimuleringsfonds.nl/en/projects/nothing-to-see-here)

</details>
<details><summary>stirworld.com (5)</summary>

- [Artist Yuko Mohri on creating work with a focus on ecological consciousness (STIRworld)](https://www.stirworld.com/inspire-people-artist-yuko-mohri-on-creating-work-with-a-focus-on-ecological-consciousness)
- [Exploring intermediality in the creative practice of artist Sarah Choo Jing - STIR](https://www.stirworld.com/see-features-exploring-intermediality-in-the-creative-practice-of-artist-sarah-choo-jing)
- [STIR, 'Embodied responses to climate emergencies at the Lahore Biennale 2024'](https://www.stirworld.com/think-opinions-embodied-responses-to-climate-emergencies-at-the-lahore-biennale-2024)
- [STIR, Harshit Agrawal's Exo-stential is India's first solo artificial intelligence art show](https://www.stirworld.com/see-features-harshit-agrawals-exo-stential-is-india-s-first-solo-artificial-intelligence-art-show)
- [STIR: From cartography to code – architectures of power at the Venice Biennale 2025](https://www.stirworld.com/see-features-from-cartography-to-code-architectures-of-power-at-the-venice-biennale-2025)

</details>
<details><summary>storage.googleapis.com (1)</summary>

- [Once Upon A Garden: The Complete Series — fact sheet (PDF)](https://storage.googleapis.com/fellowship-2022/Linda%20Dounia%20Once%20Upon%20A%20Garden/files/Linda%20Dounia%20-%20Once%20Upon%20A%20Garden%20FactSheet.pdf)

</details>
<details><summary>studiointernational.com (1)</summary>

- [Studio International — Jonathas de Andrade, Brazil Pavilion, Venice Biennale 2022 video interview](https://www.studiointernational.com/jonathas-de-andrade-brazil-pavilion-venice-biennale-2022-video-interview)

</details>
<details><summary>subbacultcha.nl (1)</summary>

- [An interview with KMRU (Subbacultcha)](https://subbacultcha.nl/2023/02/01/an-interview-with-kmru/)

</details>
<details><summary>sunlightsoilshit.systems (1)</summary>

- [Sunlight Soil & Shit (De)Cycle project website](https://sunlightsoilshit.systems/)

</details>
<details><summary>symbiotica.uwa.edu.au (1)</summary>

- [3SDC, SymbioticA exhibitions](https://www.symbiotica.uwa.edu.au/activities/exhibitions/3sdc)

</details>
<details><summary>symposiumbsp.com (1)</summary>

- [Artist 2026: Paolo Almario – Symposium of Baie-Saint-Paul](https://symposiumbsp.com/en/artists/2026/paolo-almario-90)

</details>
<details><summary>taiwannews.com.tw (1)</summary>

- [Taiwan News — Taiwanese artist Li Yi-fan examines digital anxiety at Venice Biennale](https://www.taiwannews.com.tw/en/news/6365184)

</details>
<details><summary>takeonartmagazine.com (1)</summary>

- [Take on Art, 'Re-cognizing AI Art: Looking Back, Forward'](https://takeonartmagazine.com/reviews/re-cognizing-ai-art-looking-back-forward/)

</details>
<details><summary>talkingshorts.com (1)</summary>

- [Renouncing meanings (Talking Shorts, 2025)](https://talkingshorts.com/renouncing-meanings/)

</details>
<details><summary>tanpinpin.com (2)</summary>

- [80km/h (2004), artist website](https://tanpinpin.com/art/80km-per-hour)
- [On a Clear Day You Can See Forever, artist website](https://tanpinpin.com/art/oacd)

</details>
<details><summary>tanyabonakdargallery.com (1)</summary>

- [Wong Ping: Puberty : The Art Gallery of Western Australia — Tanya Bonakdar Gallery](https://www.tanyabonakdargallery.com/exhibitions/662-wong-ping-puberty-the-art-gallery-of-western-australia-agwa/)

</details>
<details><summary>tatlerasia.com (1)</summary>

- [Artist Sarah Choo Jing on the magic of collaboration - Tatler Asia](https://www.tatlerasia.com/lifestyle/arts/artist-sarah-choo-jing-on-the-magic-of-collaboration)

</details>
<details><summary>tba21.org (1)</summary>

- [Territorial Agency: Oceans in Transformation, TBA21](https://tba21.org/oit)

</details>
<details><summary>tcaproject.net (1)</summary>

- [Sunlight, Soil & Shit (De)Cycle, Tissue Culture & Art Project](https://tcaproject.net/portfolio/sunlight-soil-and-shift-decycle/)

</details>
<details><summary>tenderphoto.substack.com (1)</summary>

- [Tender Photo – Dear Someone Somewhere in Angola (statement by Helena Uambembe)](https://tenderphoto.substack.com/p/helena-uambembe)

</details>
<details><summary>terremoto.mx (2)</summary>

- [TRAY TRAY KO (2022) — Terremoto (La Postal)](https://terremoto.mx/proyector/tray-tray-ko-2022/?lang=en)
- [When the Earth Speaks Back: Óscar Santillán and the Limits of the Human (Terremoto)](https://terremoto.mx/?p=69121)

</details>
<details><summary>territorialagency.com (1)</summary>

- [Territorial Agency (studio site)](https://territorialagency.com/)

</details>
<details><summary>tewabarnosa.com (1)</summary>

- [Written To Not Remain – Tewa Barnosa (artist website)](https://tewabarnosa.com/Written-To-Not-Remain)

</details>
<details><summary>textiellab2025-en.jaarverslag.org (1)</summary>

- [Hussein Shikha, They Who Saw Nothing but Beauty, TextielLab annual report 2025](https://textiellab2025-en.jaarverslag.org/?p=2314)

</details>
<details><summary>textilemuseum.ca (2)</summary>

- [Textile Museum of Canada — Mending the Museum: Collaborative Sound Piece Workshop](https://textilemuseum.ca/event/mending-the-museum-collaborative-sound-piece-workshop/)
- [Textile Museum of Canada — Paola Torres Núñez del Prado: The Sonic Waraca](https://textilemuseum.ca/?p=13040)

</details>
<details><summary>tfff.org (1)</summary>

- [The Ford Family Foundation, Visual Arts Program fellow page](https://www.tfff.org/project/rick-silva/)

</details>
<details><summary>the-berliner.com (1)</summary>

- [Beeple On Navigating the Post-Internet Art World - The Berliner](https://www.the-berliner.com/art/beeple-regular-animals-art-exhibition-neue-nationalgalerie/)

</details>
<details><summary>theartnewspaper.com (9)</summary>

- [A chimeric creature descends on New York's Meatpacking District, The Art Newspaper, 2023](https://www.theartnewspaper.com/2023/09/25/a-chimeric-creature-descends-on-new-yorks-meatpacking-district)
- [Ho Tzu Nyen on how AI leads to the cinematic past (The Art Newspaper)](https://www.theartnewspaper.com/2025/03/28/ho-tzu-nyen-on-how-ai-leads-to-the-cinematic-past)
- [Korakrit Arunanondchai: on loss, shamanism—and denim — The Art Newspaper](https://www.theartnewspaper.com/2021/09/24/korakrit-arunanondchai-on-loss-shamanismand-denim)
- [The Art Newspaper – Sharjah Biennial 15 delivers important postcolonial narrative but loses its experimental edge](https://www.theartnewspaper.com/2023/02/20/sharjah-biennial-15-delivers-important-postcolonial-narrativebut-loses-its-experimental-edge)
- [The Art Newspaper – Zineb Sedira reveals plans for pavilion focused on activist filmmaking](https://www.theartnewspaper.com/2022/02/22/artist-zineb-sedira-reveals-concept-for-cinematographic-installation-at-the-french-pavilion-in-venice)
- [The Art Newspaper — Brazilian pavilion taking on the country's recent tragedies](https://www.theartnewspaper.com/2022/04/11/brazilian-pavilion-taking-on-the-countrys-recent-tragedies)
- [The Art Newspaper — Hong Kong artists create a poetic moment in Venice](https://www.theartnewspaper.com/2026/11/04/hong-kong-artists-create-a-poetic-moment-in-venice)
- [The Art Newspaper — Mayunkiki on bringing her Ainu culture to a wider audience at Art Basel Hong Kong](https://www.theartnewspaper.com/2025/03/27/mayunkiki-on-bringing-her-ainu-culture-to-a-wider-audience-at-art-basel-hong-kong)
- [Tim Schneider, Beware the technology rat trap: Cooper Jacoby’s standout contribution to New York’s Whitney Biennial (The Art Newspaper, 7 May 2026)](https://www.theartnewspaper.com/2026/05/07/beware-the-technology-rat-trap-cooper-jacobys-standout-contribution-to-new-yorks-whitney-biennial)

</details>
<details><summary>thefader.com (1)</summary>

- [Holly Herndon on the power of machine learning and developing her 'digital twin' Holly+ — The FADER](https://www.thefader.com/2021/07/27/holly-herndon-on-the-power-of-machine-learning-and-developing-her-digital-twin-holly)

</details>
<details><summary>thekarachicollective.com (1)</summary>

- [Will You Listen, When the Sea Returns With the Waters of a Distant Memory? (Maham Chiragh, The Karachi Collective, on the 2025 solo show 'Goa last night I dreamed I touched you...')](https://thekarachicollective.com/will-you-listen-when-the-sea-returns-with-the-waters-of-a-distant-memory/)

</details>
<details><summary>themarkaz.org (1)</summary>

- [The Markaz Review – The Majesty and Mystery of Nature: Ali Cherri's Dam in Sudan](https://themarkaz.org/the-majesty-and-mystery-of-nature-ali-cherris-dam-in-sudan)

</details>
<details><summary>thenationalnews.com (3)</summary>

- [Noor Riyadh 2025 charts the city's shifting landscape through light and memory – The National](https://www.thenationalnews.com/arts-culture/art-design/2025/11/24/noor-riyadh-2025-charts-the-citys-shifting-landscape-through-light-and-memory)
- [Saudi Arabia's Muhannad Shono introduces his monster at the Venice Biennale, The National, 2022](https://thenationalnews.com/arts-culture/art/2022/04/25/saudi-arabias-muhannad-shono-introduces-his-monster-at-the-venice-biennale)
- [The National – Saudi artist Manal AlDowayan unveils new piece of land art addressing water scarcity in Al Ula](https://www.thenationalnews.com/arts-culture/art/saudi-artist-manal-aldowayan-unveils-new-piece-of-land-art-addressing-water-scarcity-in-alula-1.971513)

</details>
<details><summary>thenews.com.pk (2)</summary>

- [The News on Sunday, 'The suspended silence of survival' (Quddus Mirza)](https://www.thenews.com.pk/tns/detail/1241420-the-suspended-silence-of-survival)
- [The News on Sunday, interview with Iqra Tanveer ('This is the age of improvisation')](https://www.thenews.com.pk/tns/detail/560123-this-is-age-improvisation-interview-iqra-tanveer)

</details>
<details><summary>thenodmag.com (1)</summary>

- [Artist Afrah Shafiq uses tech as her canvas of choice — The Nod Mag](https://thenodmag.com/content/artist-afrah-shafiq-uses-tech-as-her-canvas-of-choice)

</details>
<details><summary>thepeakmagazine.com.sg (1)</summary>

- [This Singapore artist breaths new life into South-east Asian folklore and myth - The Peak](https://www.thepeakmagazine.com.sg/lifestyle/singapore-artist-breaths-south-east-asian-folklore-myth-zarina-muhammad-singapore-biennale)

</details>
<details><summary>theshoeboxdiorama.com (1)</summary>

- [The Shoebox Diorama (Daniel Ernst studio site)](https://www.theshoeboxdiorama.com)

</details>
<details><summary>thestandard.com.hk (1)</summary>

- [The Standard — HK artists capture what people miss in the rush](https://www.thestandard.com.hk/artcan/article/330679/HK-artists-capture-what-people-miss-in-the-rush)

</details>
<details><summary>thethirdline.com (1)</summary>

- [The Third Line – Spirit of the Emirates: an interview with Farah Al Qasimi](https://thethirdline.com/press/33-spirit-of-the-emirates-an-interview-with-farah)

</details>
<details><summary>thevrcritic.com (1)</summary>

- [Tomori review (The VR Critic)](https://www.thevrcritic.com/?p=2643)

</details>
<details><summary>thewhitereview.org (1)</summary>

- [Interview with Korakrit Arunanondchai — The White Review](https://www.thewhitereview.org/feature/interview-with-korakrit-arunanondchai)

</details>
<details><summary>thisispaper.com (1)</summary>

- [REPETAE Series by Sasha Stiles — Thisispaper](https://www.thisispaper.com/mag/repetae-series-sasha-stiles)

</details>
<details><summary>thomasfeuerstein.net (3)</summary>

- [FROM HAND TO MOUTH, 2023 — METABOLICA / Chapter 5 (artist's website)](https://www.thomasfeuerstein.net/05_METABOLICA/60_CHAPTER_5/62_FROM_HAND_TO_MOUTH)
- [METABOLICA / Metabolic-Art (artist's website)](https://www.thomasfeuerstein.net/05_METABOLICA/10_METABOLICA/20_METABOLIC-ART)
- [METABOLICA project text, artist's website (thomasfeuerstein.net)](https://www.thomasfeuerstein.net/05_METABOLICA/10_METABOLICA/30_METABOLIC-ART)

</details>
<details><summary>time.com (1)</summary>

- [The Miraculous Trees That Could Save Pakistan's Largest City from Climate Disaster — TIME](https://time.com/6189898/mangrove-trees-pakistan-climate/)

</details>
<details><summary>timeslive.co.za (1)</summary>

- [Bubu Ogisi reimagines clothing as ‘memory banks’ (TimesLive)](https://www.timeslive.co.za/lifestyle/fashion/2026-08-31-from-fabric-to-archive-with-iamisigo/)

</details>
<details><summary>timessquarenyc.org (8)</summary>

- [Announcing Marina Zurkow and James Schmitz — Times Square Arts](https://www.timessquarenyc.org/news-and-press-releases/announcing-marina-zurkow-and-james-schmitz)
- [Pixel Dust - Times Square Arts project page](https://www.timessquarenyc.org/tsq-arts-projects/pixel-dust)
- [The River is a Circle (Times Square Edition) — Times Square Arts](https://www.timessquarenyc.org/tsq-arts-projects/the-river-is-a-circle-times-square-edition)
- [Times Square Arts and For Freedoms Present Cannupa Hanska Luger: Midéegadi (press release, 28 March 2025)](https://www.timessquarenyc.org/news-and-press-releases/cannupa-hanska-luger-mideegadi)
- [Times Square Arts Announces Leo Villareal for November Midnight Moment (press release, 23 Oct 2025)](https://www.timessquarenyc.org/news-and-press-releases/times-square-arts-announces-leo-villareal-for-november-midnight-moment)
- [Times Square Arts Announces Spring 2025 Midnight Moment Program](https://www.timessquarenyc.org/news-and-press-releases/spring-2025-midnight-moment-program)
- [Times Square Arts – Build Up the House II project page](https://www.timessquarenyc.org/tsq-arts-projects/build-up-the-house-ii)
- [Times Square Arts – Midéegaadi project page](https://www.timessquarenyc.org/tsq-arts-projects/mideegaadi)

</details>
<details><summary>timothythomasson.com (2)</summary>

- [I'm Feeling Lucky — Timothy Thomasson (artist site)](https://timothythomasson.com/i'm-feeling-lucky)
- [Panorama: I'm Feeling Lucky — Timothy Thomasson (artist site)](https://timothythomasson.com/panorama-i'm-feeling-lucky)

</details>
<details><summary>tisch.nyu.edu (1)</summary>

- [Marina Zurkow opens new exhibit at the Whitney — NYU ITP](https://tisch.nyu.edu/itp/news/spring-2025/marina-zurkow--itp-adjunct-professor--opens-new-exhibit-at-the-w)

</details>
<details><summary>tiwani.co.uk (1)</summary>

- [Tiwani Contemporary – Now Open \| La Biennale di Venezia 2026](https://www.tiwani.co.uk/news/168-now-open-la-biennale-di-venezia-2026/)

</details>
<details><summary>tokyoartbeat.com (2)</summary>

- [Tokyo Art Beat — Aichi 2025 report 2 (Seto venues)](https://www.tokyoartbeat.com/articles/-/aichi-2025-report-2-202509)
- [Yuko Mohri and Sook-Kyung Lee Discuss Japan Pavilion at the 60th Venice Biennale (Tokyo Art Beat)](https://www.tokyoartbeat.com/en/articles/-/sook-kyung-lee-yuko-mohri-venice-biennale-interview-en-202406)

</details>
<details><summary>tokyoartsandspace.jp (1)</summary>

- [Tokyo Arts and Space — Joaquín ARAS creator page](https://www.tokyoartsandspace.jp/en/creator/index/A/1677.html)

</details>
<details><summary>tokyoupdates.metro.tokyo.lg.jp (1)</summary>

- [An Experimental Café in Nihombashi where Avatar Robots Facilitate Human Connections, Tokyo Updates](https://www.tokyoupdates.metro.tokyo.lg.jp/en/post-785)

</details>
<details><summary>tommysimoens.com (1)</summary>

- [Tommy Simoens – David Shongo, Café Kuba](https://tommysimoens.com/portfolio-2-portfolio/cafekube/)

</details>
<details><summary>tportmarket.com (1)</summary>

- [T-Port — Le Miroir](https://tportmarket.com/films/le-miroir/)

</details>
<details><summary>tribecafilm.com (3)</summary>

- [The Power Loom and The Founders Pillars – 2025 Tribeca Festival](https://tribecafilm.com/films/power-loom-and-the-founders-pillars-2025)
- [There Goes Nikki - Tribeca Festival 2025 film page](https://tribecafilm.com/festival/archive/there-goes-nikki-2025)
- [Tribeca Festival 2025 announces Immersive program 'In Search of Us' (press release)](https://www.tribecafilm.com/press-center/festival/press-releases/tribeca-festival-2025-announces-immersive-program-in-search-of-us-in-partnership-with-onassis-onx-and-agog)

</details>
<details><summary>tribune.com.pk (1)</summary>

- [Express Tribune (Anadolu) report on Pakistan's mangrove cover, quoting Qaiser](https://tribune.com.pk/story/2367726/entertainment)

</details>
<details><summary>twreporter.org (1)</summary>

- [The Reporter (報導者) — interview with Li Yi-Fan on the 2026 Venice Biennale (Chinese)](https://www.twreporter.org/a/2026-venice-biennale-taiwan-interview-liyifan)

</details>
<details><summary>tylerxhobbs.com (2)</summary>

- [From Noise - Tyler Hobbs (artist website)](https://www.tylerxhobbs.com/works/from-noise)
- [Spontaneity & Translated Gestures: Discussions on Mark Making - Tyler Hobbs / SOLOS (video interview listing)](https://www.tylerxhobbs.com/words/spontaneity--translated-gestures-discussions-on-mark-making)

</details>
<details><summary>u-joolimheeyoung.blogspot.com (1)</summary>

- [No Bird — UJOO+LIMHEEYOUNG blog (artists' site), January 2026](https://u-joolimheeyoung.blogspot.com/2026/01/no-bird.html)

</details>
<details><summary>uchile.cl (1)</summary>

- [Obra inmersiva 'Tal vez mañana' – Universidad de Chile](https://uchile.cl/noticias/223401/obra-inmersiva-tal-vez-manana-de-la-prof-angie-saiz)

</details>
<details><summary>undisciplinedartist.com (1)</summary>

- [Karim Ben Khelifa - artist's site (Manifesto, Works)](https://www.undisciplinedartist.com/)

</details>
<details><summary>uploadvr.com (2)</summary>

- [Emperor Shows Narrative VR’s Emotive Potential (UploadVR)](https://uploadvr.com/empereur-vr-venice-immersive-impressions)
- [Hotel Infinity Started As Manifold Garden In VR - UploadVR](https://uploadvr.com/hotel-infinity-started-as-manifold-garden-in-vr)

</details>
<details><summary>uqac.ca (1)</summary>

- [Louis-Philippe Rondeau - UQAC portfolio](https://www.uqac.ca/portfolio/louisphilipperondeau/)

</details>
<details><summary>usaartnews.com (1)</summary>

- [Artist Nancy Baker Cahill's New A.R. Work Unleashes a Surreal Interspecies Creature on the Terrace of the Whitney Museum (Artnet News, republished by USA Art News)](https://usaartnews.com/news/artist-nancy-baker-cahills-new-ar-work-unleashes-a-surreal-interspecies-creature-on-the-terrace-of-the-whitney-museum)

</details>
<details><summary>v.daum.net (1)</summary>

- [Diriyah Biennale review (Korea JoongAng Daily via Daum)](https://v.daum.net/v/20260216160202847)

</details>
<details><summary>valieexportcenter.at (1)</summary>

- [VALIE EXPORT Center Linz – Claudia Larcher](https://www.valieexportcenter.at/en/claudia-larcher)

</details>
<details><summary>venetaandrova.com (1)</summary>

- [Spray and Pray - Veneta Androva (artist's site)](https://venetaandrova.com/spray-and-pray)

</details>
<details><summary>venezia-biennale-japan.jpf.go.jp (1)</summary>

- [60th La Biennale di Venezia - The Japan Pavilion Official Website](https://venezia-biennale-japan.jpf.go.jp/e/art/2024)

</details>
<details><summary>venezianews.it (1)</summary>

- [Venice Immersive: Marion Burger & Ilan Cohen (Venezia News)](https://venezianews.it/en/daily-2023/venice-immersive-empereur-marion-burger-ilan-cohen)

</details>
<details><summary>vernissage.tv (1)</summary>

- [Pavlina Vagioni: Oikeiōsis (Kinship) / Hellenic Diaspora Foundation in Venice, VernissageTV](https://vernissage.tv/2026/07/09/pavlina-vagioni-oikeiosis-kinship-hellenic-diaspora-foundation-in-venice/)

</details>
<details><summary>vice.com (1)</summary>

- [Holly Herndon Deepfaked Herself Into a 'Digital Twin' That Sings Any Song In Her Voice — Vice](https://www.vice.com/en/article/holly-herndon-deepfaked-herself-into-a-digital-twin-that-sings-any-song-in-her-voice/)

</details>
<details><summary>victorinevanalphen.nl (1)</summary>

- [Victorine van Alphen (artist site)](https://victorinevanalphen.nl/)

</details>
<details><summary>vilaweb.cat (1)</summary>

- [Maria Arnal dóna la veu a la ciència — VilaWeb (report on her CCCB talk, Catalan)](https://www.vilaweb.cat/noticies/maria-arnal-dona-la-seva-veu-a-la-ciencia/)

</details>
<details><summary>villa-albertine.org (2)</summary>

- [Collective Body - Villa Albertine](https://villa-albertine.org/professionals/collective-body/)
- [Emperor – Villa Albertine](https://villa-albertine.org/va/?p=694448)

</details>
<details><summary>villareal.net (1)</summary>

- [Leo Villareal - artist website](https://villareal.net/)

</details>
<details><summary>vimeo.com (1)</summary>

- [Thank you for your souvenir, UK! (Vimeo, uploaded by Lin Los)](https://vimeo.com/865067540)

</details>
<details><summary>visionsdureel.ch (1)</summary>

- [Spray and Pray - Visions du Réel 2026](https://www.visionsdureel.ch/en/film/2026/spray-and-pray)

</details>
<details><summary>vivienandersongallery.com (1)</summary>

- [Vivien Anderson Gallery, Hayley Millar Baker features in Hyperallergic](https://vivienandersongallery.com/hayley-millar-baker-features-in-hyperallergic/)

</details>
<details><summary>voicesofvr.com (13)</summary>

- [#1246: Smartphone Orchestra's "Emojiii" Cultivates Playful & Novel Group Social Dynamics - Voices of VR Podcast](https://voicesofvr.com/1246-smartphone-orchestras-emojiii-cultivates-playful-novel-group-social-dynamics/)
- [#1693: A Survey of the Indie Immersive Dome Community Trends with "The Rift" Directors & 4Pi Productions - Voices of VR Podcast](https://voicesofvr.com/1693-a-survey-of-the-indie-immersive-dome-community-trends-with-the-rift-directors-4pi-productions/)
- [#1770: Eastern Philosophy-Inspired Fusion of Theater and XR with 'Mnemosyne' (Voices of VR podcast, interview with Wuer)](https://voicesofvr.com/1770-eastern-philosophy-inspired-fusion-of-theater-and-xr-with-mnemosyne/)
- [#1773: "Collective Body" Assigns Elemental Avatars Based Upon Archetypal Dance Movements - Voices of VR Podcast](https://voicesofvr.com/1773-collective-body-assigns-elemental-avatars-based-upon-archetypal-dance-movements/)
- [Voices of VR #1569: AR memorial of Nikki Giovanni (interview with Michèle Stephenson, Joe Brewster, idris brewster)](https://voicesofvr.com/1569-family-of-storytellers-creates-an-ar-memorial-of-black-poet-nikki-giovanni-with-epic-organic-garden-installation/)
- [Voices of VR #1572: The Innocence of Unknowing (interview with Ryat Yezbick & Milo Talwani)](https://voicesofvr.com/1572-the-innocence-of-unknowing-uses-socratic-dialogue-with-ai-video-essay-to-deconstruct-root-cases-of-gun-violence/)
- [Voices of VR #1690: Asking Philosophical Questions on AI in 'The Oracle: Ritual for the Future' with Poetic Immersive Performance](https://voicesofvr.com/1690-asking-philosophical-questions-on-ai-in-the-oracle-ritual-for-the-future-with-poetic-immersive-performance/)
- [Voices of VR #1692 — Playful Remixing of Scanned Animal Body Parts in 'We Are Dead Animals'](https://voicesofvr.com/?p=15890)
- [Voices of VR #1701: Public Art Installation 'Nothing to See Here' Uses Perception Art to Challenge Our Notions of Reality](https://voicesofvr.com/1701-public-art-installation-nothing-to-see-here-uses-perception-art-to-challenge-our-notions-of-reality/)
- [Voices of VR #1703: 'Reality Looks Back' Uses Quantum Possibility Metaphors & Gaussian Splats to Challenge Notions of Reality](https://voicesofvr.com/1703-reality-looks-back-uses-quantum-possibility-metaphors-gaussian-splats-to-challenge-notions-of-reality/)
- [Voices of VR #1763: Blending Theater and 360 Video in 'Re-Launching-Luigi-Broglio'](https://voicesofvr.com/1763-blending-theater-and-360-video-in-re-launching-luigi-broglio/)
- [Voices of VR #1771: Environmental Storytelling in 'The Great Orator' VR Diorama with Generative AI Experiments](https://voicesofvr.com/1771-environmental-storytelling-in-the-great-orator-vr-diorama-with-generative-ai-experiments/)
- [Voices of VR #1804: Octopocalypse (interview with Max Sacker & Arite Szadkowski, audio)](https://voicesofvr.com/1804-octopocalypse-provocatively-uses-genai-on-every-dimension-in-their-speculative-future-video/)

</details>
<details><summary>vojext.eu (1)</summary>

- [S+T+ARTS Residencies: Robotics in Arts & Crafts, VOJEXT](https://vojext.eu/challenge-driven-robotics-in-arts-crafts/)

</details>
<details><summary>waag.org (2)</summary>

- [Biased Technology: Behind Shirley — Waag (interview with the artist)](https://waag.org/en/article/biased-technology-behind-shirley)
- [PL'AI: where plant and machine playfully meet — Waag (interview)](https://waag.org/en/article/plai-where-plant-and-machine-playfully-meet)

</details>
<details><summary>wallpaper.com (1)</summary>

- [Artist Julianknxx on poetry, dreams and Switzerland – Wallpaper\*](https://wallpaper.com/art/julianknxx-in-a-dream-we-are-once-beautiful)

</details>
<details><summary>we-make-money-not-art.com (1)</summary>

- [PL’AI. An AI robot created to play with cucumber plants — We Make Money Not Art](https://we-make-money-not-art.com/?p=35638)

</details>
<details><summary>web.archive.org (5)</summary>

- [Awakening, Singapore Night Festival 2025 programme page (Wayback Machine copy; live page now 404)](https://web.archive.org/web/20251015060459/https://www.heritage.sg/sgnightfest/whats-on/awakening)
- [Dari Pulau Ke Pulau, Singapore Night Festival 2025 programme page (Wayback Machine copy; live page now 404)](https://web.archive.org/web/20251015055747/https://www.heritage.sg/sgnightfest/whats-on/dari-pulau-ke-pulau)
- [Island Waters, Singapore Night Festival 2025 programme page (Wayback Machine copy; live page now 404)](https://web.archive.org/web/20250804053148/https://www.heritage.sg/sgnightfest/whats-on/island-waters)
- [LIFTing the curtain on Radio Ghost (LIFT Festival interview, archived)](http://web.archive.org/web/20221128224314/https://www.liftfestival.com/lifting-the-curtain-radio-ghost/)
- [NoSearchBar, Prix Ars Electronica 2022 winners page (Wayback Machine copy)](https://web.archive.org/web/20221209060027/https://calls.ars.electronica.art/2022/prix/winners/9017/)

</details>
<details><summary>wepresent.wetransfer.com (1)</summary>

- [Hussein Shikha: Keeping southern Iraq's historic textile traditions alive, WePresent (WeTransfer)](https://wepresent.wetransfer.com/stories/hussein-shikha-iraqi-textiles)

</details>
<details><summary>werkleitz.de (1)</summary>

- [Unknown label from Nicolas Gourault is touring in Europe, Werkleitz](https://werkleitz.de/en/artikel/unknown-label-von-nicolas-gourault)

</details>
<details><summary>whitehotmagazine.com (1)</summary>

- [From Twin Quasars to Digital Frontiers at the Whitney Artport Whitney Virtual Space - Whitehot Magazine](https://whitehotmagazine.com/articles/virtual-space-by-lara-pan/7026)

</details>
<details><summary>whitney.org (22)</summary>

- [3FACE (Token #11, Archetype: Belonging), Whitney Museum of American Art collection](https://whitney.org/collection/works/67733)
- [Amelia Winger-Bearskin: SKY/WORLD DEATH/WORLD (Whitney Museum, artport / Sunrise/Sunset)](https://whitney.org/exhibitions/amelia-winger-bearskin)
- [artport commissions, Whitney (pool source)](https://whitney.org/artport/commissions)
- [Ashley Zelinskie: Twin Quasar - Whitney Museum of American Art](https://whitney.org/exhibitions/twin-quasar)
- [Devin Kenny: Ongoing, Individual Adaptability or How to Quiet Quit, Whitney Museum artport](https://whitney.org/exhibitions/ongoing-individual-adaptability)
- [Exive II: Gabriela Ruiz — Whitney Museum event](https://whitney.org/events/gabriela-ruiz)
- [Hyundai Terrace Commission: Marina Zurkow — Whitney Museum](https://whitney.org/exhibitions/marina-zurkow)
- [Memo Akten & Katie Hofstadter: The Thinking Ocean, Whitney Museum of American Art](https://whitney.org/exhibitions/the-thinking-ocean)
- [Nancy Baker Cahill: CENTO, audio guide with verbal description, Whitney Museum](https://whitney.org/guides/104)
- [Nancy Baker Cahill: CENTO, Whitney Museum of American Art (artport commission)](https://whitney.org/exhibitions/cento)
- [Ongoing, Individual Adaptability or How to Quiet Quit, Whitney collection record AP.2022.3](https://whitney.org/collection/works/66890)
- [Peter Burr: Sunshine Monument (Whitney Museum, artport / Sunrise/Sunset)](https://whitney.org/exhibitions/peter-burr)
- [Rachel Rossin: The Maw Of — Whitney Museum of American Art, artport](https://whitney.org/exhibitions/the-maw-of)
- [Rick Silva: Liquid Crystal (Whitney Museum, artport / Sunrise/Sunset)](https://whitney.org/exhibitions/rick-silva)
- [Whitney Biennial 2024: Even Better Than the Real Thing — Seba Calfuqueo](https://whitney.org/exhibitions/2024-biennial/art?section=5)
- [Whitney Biennial 2026 audio guide](https://whitney.org/guides/139)
- [Whitney Biennial 2026 audio guide – stop 611, Cooper Jacoby (transcription, sound and verbal description)](https://whitney.org/guides/139?language=en)
- [Whitney Biennial 2026 \| Art & Artists — Gabriela Ruiz](https://whitney.org/exhibitions/2026-biennial/art?section=50)
- [Whitney Biennial 2026 – Art & Artists: Cooper Jacoby](https://whitney.org/exhibitions/2026-biennial/art?section=32)
- [Whitney Biennial 2026 – Art & Artists: Isabelle Frances McGuire](https://whitney.org/exhibitions/2026-biennial/art?section=41)
- [Whitney Biennial 2026 – Art & Artists: Jordan Strafer](https://whitney.org/exhibitions/2026-biennial/art?section=52)
- [Whitney Biennial 2026 — Art & Artists: Sung Tieu](https://whitney.org/exhibitions/2026-biennial/art?section=53)

</details>
<details><summary>wienmodern.at (1)</summary>

- [Subnormal Europe – Wien Modern 2023](https://www.wienmodern.at/2023-subnormal-europe-en-2533)

</details>
<details><summary>witayajunma.com (1)</summary>

- [Smog Season - Witaya Junma (artist website)](http://www.witayajunma.com/smog-season1.html)

</details>
<details><summary>wonderwall.sg (1)</summary>

- [Artist Behind The Art: Hafizah Jainal (Wonderwall.sg)](https://wonderwall.sg/people/artist-behind-the-art-hafizah-jainal)

</details>
<details><summary>wp.swissinstitute.net (1)</summary>

- [BOMB / Swiss Institute – Ali Cherri: Humble and quiet and soothing as mud](https://wp.swissinstitute.net/press/ali-cherri-humble-and-quiet-and-soothing-as-mud-3/)

</details>
<details><summary>www2.hu-berlin.de (1)</summary>

- [CollActive Materials (HU Berlin) – Safe Human-Machine Interaction, Futurium 2024](https://www2.hu-berlin.de/collactivematerials/en/ausstellungen/safe-human-machine-interaction/)

</details>
<details><summary>xrmust.com (1)</summary>

- [S+T+ARTS Prize 2025 winners – XR Must](https://xrmust.com/xr-magazine/starts-2025-winners/)

</details>
<details><summary>yeoworkshop.com (1)</summary>

- [Sarah Choo Jing, Zoom, Click, Waltz, 2020 - Yeo Workshop](https://www.yeoworkshop.com/artworks/523-sarah-choo-jing-zoom-click-waltz-2020)

</details>
<details><summary>youtu.be (1)</summary>

- [CHIMERIA video (linked from the Ars Electronica archive entry)](https://youtu.be/B7U_7kTxUWA)

</details>
<details><summary>youtube.com (2)</summary>

- [Micro-Nano Landscape — YouTube (artist's channel), 2026](https://www.youtube.com/watch?v=utLpHqNOAD4)
- [微纳山水 Micro-Nano Landscape by Suxuan Jiang — YouTube (artist's channel)](https://www.youtube.com/watch?v=yxyzYumk88Y)

</details>
<details><summary>zerodeux.fr (1)</summary>

- [Andréanne Béguin, "A Blessing and a Curse" – Zérodeux](https://www.zerodeux.fr/?p=25346)

</details>
<details><summary>zhangweidi.com (1)</summary>

- [Cangjie's Poetry - Weidi Zhang](https://www.zhangweidi.com/cangjiepoetry)

</details>
<details><summary>zikoko.com (1)</summary>

- [Man Like Anthony Azekwoh (Zikoko)](https://www.zikoko.com/man/i-had-to-bet-on-myself-and-make-it-work-man-like-anthony-azekwoh/)

</details>
<details><summary>zilesinopti.ro (1)</summary>

- [CLIN D'OEIL \| RYU FURUSAWA, artist New Media (Zile si Nopti interview, Romanian)](https://zilesinopti.ro/2026/01/30/ryu-furusawa-artist-new-media-interviu/)

</details>
<details><summary>zkm.de (3)</summary>

- [Codex Virtualis: Genesis – ZKM Karlsruhe (exhibition Renaissance 3.0, 2023–24)](https://zkm.de/en/node/62686)
- [From Hand to Mouth — ZKM collection record](https://zkm.de/en/node/71194)
- [METABOLICA Camp — ZKM collection](https://zkm.de/en/node/62590)

</details>
<details><summary>zu-uk.com (1)</summary>

- [Radio Ghost – ZU-UK project page](https://zu-uk.com/project/radio-ghost/)

</details>
