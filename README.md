# Media artworks citation database

What media artists say their work is for, in their own words.

395 contemporary media artworks made since 2004, with 1706 verbatim
statements by their artists (129 of them questions), each linked to the page
it was copied from (1741 distinct sources). It is the text layer of
*Why Make This*, a map that places the works by what their artists said about
them. Exported 2026-11-20.

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

- **Finding works:** agents proposed candidate media artworks made since
  2004 from awards, festivals and biennales; a script then drew the
  works from those candidates (see "How the works were chosen" below).
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

## How the works were chosen, and what was done against bias

Any list of "important" media art repeats the biases of the places that
award and show it: mostly European and North American festivals, mostly
English-language press, more men than women. The selection tries to
counter that. These are attempts, not guarantees, and they are listed here
so you can judge them.

- **Taste does not choose.** Works are not picked as the best or most
  interesting. Agents first collect a broad pool of candidates, then a script
  draws from it mechanically. Ties are broken by a seeded random draw
  (seed 2026), so the selection is reproducible.
- **Where candidates come from.** Award and honorary-mention lists,
  festival and biennial programmes, commission and residency announcements
  and museum collections, deliberately including regional and non-English
  sources, and works that were shortlisted or shown, not only winners.
  Agents were told to search these systematically rather than from memory
  of famous names, and to mix established and early-career artists.
- **Equal periods.** 100 works are drawn for each period
  (2010-14, 2015-19, 2020-24, 2025+), so no period outweighs another.
- **One work per artist** across the whole database.
- **Region quotas** for each period, by the artist's country of origin or main
  base: Europe 25, North America 18, East Asia 14, Latin America 10, Africa 10, Middle East 8, South Asia 6, Southeast Asia 6, Oceania 3 (of 100). Where a region has too few candidates,
  its places go to the other regions. Without quotas the pools tilt heavily
  toward Europe and North America.
- **Gender balance as a soft target**, inside each region: woman 42%, man 38%, collective/mixed 15%, nonbinary 5%.
  Gender is used only when a source states it (pronouns or self-description),
  never guessed from a name; otherwise it is "unknown" and plays no part. It
  only nudges which candidate is drawn next; the region quotas are fixed.
- **Media balance.** Within the same draw, candidates whose media are still
  under-represented are slightly preferred.
- **Scope check.** Works later found to fall outside their period, or never
  to have been shown publicly, were replaced by a new draw from the same
  period and region.
- **A check on the map.** For the map (not part of this database), the
  groupings of similar statements are tested for whether they merely sort
  artists by medium, region or gender. They largely do not.

**Not published:** the candidate pools, and the gender, region and country
of origin used for the draw. They were selection aids only. Gender is
personal information and the sources state it unevenly; regions and
countries were assigned from often thin sources. This database records only
what is sourced to the works and their artists' own words.

**Known limits:** the pools still lean on award circuits and English-language
pages; gender is unknown for many candidates, so the gender balance steers
only part of the draw; and the regions are broad. Treat the selection as a
deliberate spread, not a representative sample of all media art.

## Sources

All 1741 pages quoted or used, grouped by website (931 websites).
Each work's page lists its own sources next to its quotes.

<details><summary>086708.cargo.site (2)</summary>

- [Light Keeper — lololol (artists' site)](https://086708.cargo.site/lightkeeper)
- [Light Keeper: Signal — lololol (artists' site)](https://086708.cargo.site/lightkeeper_signal)

</details>
<details><summary>10magazine.com (1)</summary>

- [Joshua Serafin: Touching The Void - 10 Magazine](https://10magazine.com/?p=388233)

</details>
<details><summary>13.bienaldeartesmediales.cl (5)</summary>

- [#MementoMori, 13 Bienal de Artes Mediales (English)](https://13.bienaldeartesmediales.cl/obra/mementomori-2/)
- [#MementoMori, 13 Bienal de Artes Mediales (Spanish)](https://13.bienaldeartesmediales.cl/obra/mementomori/)
- [Dominus Trémulo, 13 Bienal de Artes Mediales (Santiago, 2017)](https://13.bienaldeartesmediales.cl/obra/dominus-tremulo/)
- [Gabriel Tagle Petrone, participant page, 13 Bienal de Artes Mediales](https://13.bienaldeartesmediales.cl/participante/gabriel-tagle-petrone/)
- [Homeland, 13 Bienal de Artes Mediales (Santiago, 2017)](https://13.bienaldeartesmediales.cl/obra/homeland-2/)

</details>
<details><summary>13thgwangjubiennale.org (2)</summary>

- [Fernando Palma Rodríguez - 13th Gwangju Biennale (text by Michelangelo Corsaro)](https://13thgwangjubiennale.org/artists/fernando-palma-rodriguez/)
- [Korakrit Arunanondchai — 13th Gwangju Biennale](https://13thgwangjubiennale.org/?p=308)

</details>
<details><summary>150mediastream.com (1)</summary>

- [Interview with Peter Burr (150 Media Stream)](https://150mediastream.com/peter-burr-interview/)

</details>
<details><summary>17.bienaldeartesmediales.cl (1)</summary>

- [Bemol – 17 Bienal de Artes Mediales de Santiago](https://17.bienaldeartesmediales.cl/obra/bemol/)

</details>
<details><summary>18.re-publica.com (1)</summary>

- [Accelerating Human Rights Investigations with Computer Vision, re:publica 18 session](https://18.re-publica.com/en/session/accelerating-human-rights-investigations-computer-vision.html)

</details>
<details><summary>1854.photography (1)</summary>

- [Alessandro Bavari – in the belly of the beast, 1854 Photography](https://www.1854.photography/?p=6694)

</details>
<details><summary>1995-2015.undo.net (2)</summary>

- [Daniel Rozin: Angles, bitforms gallery press release (undo.net)](https://1995-2015.undo.net/it/evento/155728)
- [Edgardo Aragón, MUAC - Mexico City (UnDo.Net listing, 2012)](https://1995-2015.undo.net/it/evento/147981)

</details>
<details><summary>1e9.community (2)</summary>

- [1E9.community — Maarten Isaäk de Heer](https://www.1e9.community/artists/maarten-isa%C3%A4k-de-heer)
- [Daniel Ernst - 1E9 Festival der Zukunft artist page](https://www.1e9.community/artists/daniel-ernst)

</details>
<details><summary>2016.biennaleimagemouvement.ch (1)</summary>

- [Cinthia Marcelle & Tiago Mata Machado with Graham Domke, Biennale de l'Image en Mouvement 2016](https://2016.biennaleimagemouvement.ch/cinthia-marcelle-tiago-mata-machado/)

</details>
<details><summary>2017.adaf.gr (1)</summary>

- [Athens Digital Arts Festival 2017 – Language Product](https://2017.adaf.gr/?p=1930)

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
<details><summary>35.bienal.org.br (1)</summary>

- [Sammy Baloji – 35th Bienal de São Paulo](https://35.bienal.org.br/en/participante/sammy-baloji/)

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
<details><summary>4christinemarie.com (2)</summary>

- [About, 4christinemarie.com](https://www.4christinemarie.com/about)
- [Christine Marie, 4christinemarie.com (home page, Antiquated Augmented Reality section)](https://www.4christinemarie.com/)

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
<details><summary>abc.net.au (1)</summary>

- [Tour the trippy world of virtual reality with TERMINUS at National Gallery, ABC News, 2018](http://www.abc.net.au/news/2018-05-08/virtual-reality-exhbit-national-gallery-canberra/9726434)

</details>
<details><summary>ableton.com (2)</summary>

- [Nicolas Bernier: Intimate Frequencies, Ableton blog, 2013](https://www.ableton.com/en/blog/nicolas-bernier-intimate-frequencies/)
- [Nosaj Thing: A Visual and Musical History, Ableton blog](https://www.ableton.com/en/blog/nosaj-thing-visual-and-musical-history/)

</details>
<details><summary>abqjournal.com (1)</summary>

- [Suzanne Kite's 'Dreaming with AI' at MoCNA — Albuquerque Journal](https://www.abqjournal.com/lifestyle/suzanne-kites-dreaming-with-ai-at-mocna-invites-play-and-reflection/644656)

</details>
<details><summary>acca.melbourne (2)</summary>

- [Feedback Loops, ACCA exhibition page](https://acca.melbourne/exhibition/feedback-loops/)
- [Sahej Rahal: Artist Talk (podcast), ACCA, 2019](https://acca.melbourne/?p=35047)

</details>
<details><summary>achim.pages.dev (1)</summary>

- [Achim Koh – 한국 인터넷 관광 안내서 / Korean Internet Tour Guide](https://achim.pages.dev/projects/korean-internet-tour-guide)

</details>
<details><summary>acloserlisten.com (2)</summary>

- [Francisco López ~ Sonic Fields Vlieland, A Closer Listen (2018)](https://acloserlisten.com/2018/11/29/francisco-lopez-sonic-fields-vlieland/)
- [Francisco López ~ untitled#352, A Closer Listen (2017)](https://acloserlisten.com/2017/05/27/francisco-lopez-untitled352/)

</details>
<details><summary>acmi.net.au (2)</summary>

- [Daniel Crooks: Phantom Ride, exhibition 16 Feb – 29 May 2016, ACMI](https://www.acmi.net.au/whats-on/daniel-crooks-phantom-ride/)
- [Phantom Ride, ACMI collection](https://www.acmi.net.au/works/119--phantom-ride)

</details>
<details><summary>actualite.cd (1)</summary>

- [Actualite.cd – David Shongo récompensé au Grand Prix Ars Electronica 2025 pour son film “Café Kuba”](https://actualite.cd/2025/07/24/cinema-david-shongo-recompense-au-grand-prix-ars-electronica-2025-pour-son-film-cafe)

</details>
<details><summary>adamartgallery.nz (1)</summary>

- [Leap to the Place of Two Pools - Te Pātaka Toi Adam Art Gallery](https://www.adamartgallery.nz/exhibitions/future/leap-to-the-place-of-two-pools)

</details>
<details><summary>adamwbrown.net (1)</summary>

- [Adam W. Brown: \[ir\]reverent: Miracles on Demand (artist's website)](http://adamwbrown.net/projects-2/irreverent/)

</details>
<details><summary>adfwebmagazine.jp (1)</summary>

- [Interview in ADF Web Magazine about his stage work Tangent (2024), not about Toposcan](https://www.adfwebmagazine.jp/?p=289951)

</details>
<details><summary>aestheticamagazine.com (1)</summary>

- [Contemporary Sound Art, Haroon Mirza, Spike Island – Aesthetica](https://aestheticamagazine.com/?p=2641)

</details>
<details><summary>afar.com (1)</summary>

- [AFAR – Saudi Arabia's Ancient Desert Transforms Into a Striking Art Exhibition](https://afar.com/magazine/desert-x-al-ula-site-specific-art-installations-decorate-saudi-arabian-desert)

</details>
<details><summary>africanah.org (3)</summary>

- [Africanah.org review of 'Options' (Nolan Oswald Dennis)](https://africanah.org/nolan-oswald-dennis-3/)
- [Younes Baba Ali, africanah.org](https://africanah.org/younes-baba-ali/)
- [Zihan Kassam, 'Jackie Karuti', Africanah.org (2015)](https://africanah.org/jackie-karuti/)

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
<details><summary>ahprojects.com (1)</summary>

- [VFRAME, Adam Harvey Studio](https://ahprojects.com/vframe/)

</details>
<details><summary>aiartonline.com (1)</summary>

- [Maja Petrić — NeurIPS 2020 Workshop on ML for Creativity and Design gallery (aiartonline.com)](https://www.aiartonline.com/highlights-2020/maja-petric-2/)

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
<details><summary>alessandrobavari.com (2)</summary>

- [Bio, alessandrobavari.com](https://www.alessandrobavari.com/bio)
- [Metachaos (video), alessandrobavari.com](https://www.alessandrobavari.com/metachaosvideo)

</details>
<details><summary>alexanderschubert.net (1)</summary>

- [Alexander Schubert - Convergence](https://alexanderschubert.net/works/Convergence.php)

</details>
<details><summary>alicespringsnews.com.au (1)</summary>

- [Alice to Venice through Indigenous eyes (Alice Springs News)](https://alicespringsnews.com.au/2017/08/04/alice-to-venice-through-indigenous-eyes/)

</details>
<details><summary>alicherri.com (1)</summary>

- [Ali Cherri – Biography](https://alicherri.com/biography)

</details>
<details><summary>aljazeera.com (1)</summary>

- [When we spoke to Leila Alaoui on tackling taboos in art - Al Jazeera, 2015](https://www.aljazeera.com/features/2015/7/19/when-we-spoke-to-leila-alaoui-on-tackling-taboos-in-art)

</details>
<details><summary>alumni.risd.edu (1)</summary>

- [Odyssey in the Andes - RISD Alumni](https://alumni.risd.edu/odyssey-andes)

</details>
<details><summary>am.rsu.lv (1)</summary>

- [Anatomy & Beyond — Riga Stradiņš University Anatomy Museum](https://am.rsu.lv/en/node/12848)

</details>
<details><summary>amara.org (1)</summary>

- [Art21, 'Susan Philipsz in "Berlin"', Art in the Twenty-First Century, Season 9 (2018), English subtitles (Amara)](https://amara.org/api/videos/LWNxEBkt9jXB/languages/en/subtitles/?format=txt)

</details>
<details><summary>americantheatre.org (1)</summary>

- [The Dangers of AI Intoxication - Annie Dorsen, American Theatre](https://americantheatre.org/?p=79018)

</details>
<details><summary>amyleesanford.com (2)</summary>

- [About – amyleesanford.com](https://amyleesanford.com/about/)
- [Scanning – Amy Lee Sanford (portfolio)](https://amyleesanford.com/portfolio/scanning/)

</details>
<details><summary>anaistondeur.com (1)</summary>

- [Noir de carbone / Carbon Black - Anaïs Tondeur (artist's site)](https://anaistondeur.com/carbon-black/1)

</details>
<details><summary>andreachiampo.com (3)</summary>

- [About – Andrea Chiampo (artist's website)](https://www.andreachiampo.com/about)
- [FUTURED PAST (artist's website)](https://www.andreachiampo.com/futured-past)
- [MATER NATVRA – Asprey Studio – ABM (artist's website)](https://www.andreachiampo.com/mater-natvra-asprey-studio-abm)

</details>
<details><summary>anidaali.com (1)</summary>

- [The Buddhist Bug - Anida Yoeu Ali (artist website)](https://www.anidaali.com/artworks/the-buddhist-bug)

</details>
<details><summary>anikameierstatusupdate.substack.com (1)</summary>

- [AI Art Questionnaire: Linda Dounia](https://anikameierstatusupdate.substack.com/p/ai-art-questionnaire-linda-dounia)

</details>
<details><summary>animafest.hr (1)</summary>

- [Animafest Zagreb 2016 – Datum Point](https://animafest.hr/arhiva/en/2016/film/read/datum_point.html)

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
<details><summary>annaridler.com (2)</summary>

- [Mosaic Virus 2018, annaridler.com](https://annaridler.com/works/mosaic-2018)
- [Mosaic Virus 2019, annaridler.com](https://annaridler.com/works/mosaic-2019)

</details>
<details><summary>annemariemaes.net (2)</summary>

- [Intelligent Beehives (research notebook), annemariemaes.net](https://annemariemaes.net/research/intelligent-beehives/)
- [The Intelligent Guerrilla Beehive, annemariemaes.net](http://annemariemaes.net/projects/the-intelligent-guerilla-beehive/)

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
<details><summary>architecturalrecord.com (1)</summary>

- [Song 1, Architectural Record](https://www.architecturalrecord.com/articles/7671-song-1)

</details>
<details><summary>architonic.com (1)</summary>

- [Arabian nights: recasting the Saudi capital through light – Architonic](https://www.architonic.com/de/s/arabian-nights:-recasting-the-saudi-capital-through-light/20343917)

</details>
<details><summary>archive.aec.at (53)</summary>

- [Acoustic Additive Synthesizer - Prix Ars Electronica 2017, Digital Musics & Sound Art, Honorary Mention](https://archive.aec.at/prix/227033/)
- [Anxious Body — Prix Ars Electronica Archive (Award of Distinction, Computer Animation 2022)](https://archive.aec.at/prix/267896/)
- [Artist Residency at SETI Institute – Interspecifics, European ARTificial Intelligence Lab archive (incl. Ars Electronica Festival 2021 photos)](https://archive.aec.at/ailab/261299)
- [Avatar Robot Cafe DAWN ver.β, Prix Ars Electronica Archive (Golden Nica Digital Communities 2022)](https://archive.aec.at/prix/268808)
- [Baitul Ma'mur: House of Angels — Prix Ars Electronica 2021, Honorary Mention (archive)](https://archive.aec.at/prix/255812/)
- [Blade Runner—Autoencoded, Prix Ars Electronica 2017, Computer Animation / Film / VFX, Honorary Mention (archive)](https://archive.aec.at/prix/225440/)
- [Cangjie's Poetry - Prix Ars Electronica 2022, Computer Animation, Honorary Mention](https://archive.aec.at/prix/266995/)
- [Carbon Black - Prix Ars Electronica 2019, Artificial Intelligence & Life Art, Honorary Mention](https://archive.aec.at/prix/244873/)
- [Chijikinkutsu — Prix Ars Electronica 2015, Golden Nica Digital Musics & Sound Art (Ars Electronica Archive)](https://archive.aec.at/prix/212289/)
- [CHIMERIA, Shin Hanagata - Prix Ars Electronica Archive (catalogue text, jury statement)](https://archive.aec.at/prix/319687/)
- [Chosho Hakkei in Rittor Base - HPL ver - Prix Ars Electronica 2021, Digital Musics & Sound Art, Honorary Mention](https://archive.aec.at/prix/256840/)
- [Codex Virtualis\_Genesis – Prix Ars Electronica 2023 archive (Honorary Mention)](https://archive.aec.at/prix/279020/)
- [Conversations Beyond the Ordinary, Prix Ars Electronica Archive](https://archive.aec.at/prix/290645)
- [Corpus Nil - Prix Ars Electronica 2017, Digital Musics & Sound Art, Award of Distinction](https://archive.aec.at/prix/227197/)
- [CyberArts 2014 — Prix Ars Electronica catalogue (Columbos entry and jury statement)](https://archive.aec.at/media/assets/65cb27ad06f07ce322f27941ebe52813.pdf)
- [Dust Blooms: A Research Narrative in Artistic Ecology, Prix Ars Electronica 2017, Hybrid Art, Honorary Mention (archive)](https://archive.aec.at/prix/227816/)
- [Endangered Gestures – Prix Ars Electronica Archive (Honorary Mention, New Animation Art)](https://archive.aec.at/prix/320402/)
- [fake synthetic music - Prix Ars Electronica 2019, Digital Musics & Sound Art, Honorary Mention](https://archive.aec.at/prix/244374/)
- [FuneralPlay - Prix Ars Electronica 2023, New Animation Art, Honorary Mention](https://archive.aec.at/prix/278459/)
- [GR-AI-N, S+T+ARTS Prize 2024 entry, Ars Electronica archive](https://archive.aec.at/startsprize/288853/)
- [Harvesting Climate Action - Prix Ars Electronica 2026, Digital Humanity, Honorary Mention (archive)](https://archive.aec.at/prix/320305/)
- [huě iànn — Prix Ars Electronica Archive (Honorary Mention, New Animation Art 2023)](https://archive.aec.at/prix/277097/)
- [In a Small Room – Prix Ars Electronica 2021 archive (Digital Humanity, Honorary Mention; pool source)](https://archive.aec.at/prix/257325/)
- [MANTRAcks and Sonic Fields: A VirtuAural Duology, Prix Ars Electronica archive](https://archive.aec.at/prix/244246/)
- [Micro-Nano Landscape — Prix Ars Electronica 2026, Honorary Mention New Animation Art (Ars Electronica Archive)](https://archive.aec.at/prix/320406/)
- [Mid Tide #3 - Prix Ars Electronica 2024, New Animation Art, Honorary Mention](https://archive.aec.at/prix/290636/)
- [Mosaic Virus, Prix Ars Electronica 2019, Artificial Intelligence & Life Art, Honorary Mention (archive)](https://archive.aec.at/prix/244958/)
- [No Bird — Prix Ars Electronica 2026, Honorary Mention Interactive Art + (Ars Electronica Archive)](https://archive.aec.at/prix/319445/)
- [Open Source Estrogen, Prix Ars Electronica 2017 Hybrid Art Honorary Mention, Ars Electronica Archive](https://archive.aec.at/prix/228095/)
- [OpenSurgery, Prix Ars Electronica 2016, Interactive Art, Award of Distinction (archive)](https://archive.aec.at/prix/219817/)
- [Parasitic / Symbiotic – Prix Ars Electronica 2016, Interactive Art, Award of Distinction (Ars Electronica Archive)](https://archive.aec.at/prix/219898/)
- [Prix Ars Electronica Archive — Le Miroir](https://archive.aec.at/prix/320405/)
- [Prix Ars Electronica archive: \[help me know the truth\] (Interactive Art +, Award of Distinction 2018)](https://archive.aec.at/prix/237380/)
- [Prix Ars Electronica archive: \[ir\]reverent: Miracles on Demand (Honorary Mention 2019)](https://archive.aec.at/prix/244982/)
- [Prix Ars Electronica archive: Best of Luck with the Wall](https://archive.aec.at/prix/225447/)
- [Prix Ars Electronica archive: Conspiracy: Conjoining the Virtual (Honorary Mention 2018)](https://archive.aec.at/prix/237373/)
- [Prix Ars Electronica Archive: If You Have Starry Skies in Your Eyes (Award of Distinction 2024)](https://archive.aec.at/prix/290649/)
- [Prix Ars Electronica archive: Norman (Computer Animation, Honorary Mention 2018)](https://archive.aec.at/prix/236458/)
- [Prix Ars Electronica Archive: Thank you for your souvenir, UK! (Honorary Mention 2024)](https://archive.aec.at/prix/290625/)
- [Prix Ars Electronica archive: Wastelands](https://archive.aec.at/prix/245484/)
- [Sky Brought Down – Prix Ars Electronica 2019, Honorary Mention (Ars Electronica Archive)](https://archive.aec.at/prix/244229/)
- [SMOG SEASON - Prix Ars Electronica Archive (Honorary Mention 2023, New Animation Art)](https://archive.aec.at/prix/276128/)
- [Smoke and Mirrors — Prix Ars Electronica archive](https://archive.aec.at/prix/290664)
- [Spray and Pray, Veneta Androva - Prix Ars Electronica Archive (catalogue text, jury statement)](https://archive.aec.at/prix/320407/)
- [Stained — Ars Electronica Archive](https://archive.aec.at/prix/290621)
- [Subnormal Europe – Prix Ars Electronica 2021 archive (Digital Musics & Sound Art, Honorary Mention)](https://archive.aec.at/prix/255800/)
- [The Full Story - Prix Ars Electronica 2018, Computer Animation, Honorary Mention](https://archive.aec.at/prix/236538/)
- [The Great Indecision Council - Prix Ars Electronica 2019, Computer Animation, Honorary Mention](https://archive.aec.at/prix/243694/)
- [The Intelligent Guerilla Beehive, Prix Ars Electronica archive](https://archive.aec.at/prix/227993/)
- [There is the sun - Prix Ars Electronica 2014, Interactive Art, Honorary Mention (Ars Electronica Archive)](https://archive.aec.at/prix/209335)
- [They Who Saw Nothing but Beauty, Prix Ars Electronica 2026 archive (pool source)](https://archive.aec.at/prix/317102/)
- [VFRAME, Prix Ars Electronica 2019, Award of Distinction (Artificial Intelligence & Life Art), Ars Electronica Archive](https://archive.aec.at/prix/245289/)
- [Wellenwald mit Bunker, Prix Ars Electronica 2017, Digital Musics & Sound Art, Honorary Mention (archive)](https://archive.aec.at/prix/226549/)

</details>
<details><summary>archive.biennial.com (1)</summary>

- [Liverpool Biennial 2018, online works](https://archive.biennial.com/2018/exhibition/locations/online)

</details>
<details><summary>archive.bubblegumclub.co.za (2)</summary>

- [Azibuye – The 360° Virtual Reality Film (Bubblegum Club)](https://archive.bubblegumclub.co.za/art/azibuye-the-360-virtual-reality-film/)
- [Azibuye – The Occupation // SA's first VR documentary to show at Sundance Film Festival, Christa Dee, Bubblegum Club, 2020](https://archive.bubblegumclub.co.za/?p=20703)

</details>
<details><summary>archive.ibraaz.org (5)</summary>

- [Flash Futures: Monira Al Qadiri in conversation with Stephanie Bailey, Ibraaz](https://archive.ibraaz.org/interviews/126)
- [Lara Baladi, Archiving a Revolution in the Digital Age, Archiving as an Act of Resistance - Ibraaz essay, 2016](https://archive.ibraaz.org/essays/163)
- [Succinctly Verbose: Visualizing Palestine in conversation with Haig Aivazian, Ibraaz](https://archive.ibraaz.org/interviews/72)
- [Unfolding the Structures of Sound – Cevdet Erek in conversation with Başak Şenova, Ibraaz](https://archive.ibraaz.org/interviews/220)
- [Vox Populi: Tahrir Archives, Lara Baladi - Ibraaz (project page)](https://archive.ibraaz.org/projects/133)

</details>
<details><summary>archive.pinupmagazine.org (1)</summary>

- [Interview: Sophia Al-Maria, with Hans Ulrich Obrist, PIN-UP](https://archive.pinupmagazine.org/articles/interview-sophia-al-maria-hans-ulrich-obrist)

</details>
<details><summary>archive.project-gallery.com (1)</summary>

- [Spotlight: Jovita Alvares, project gallery (2021)](https://archive.project-gallery.com/spotlights/jovita-alvares)

</details>
<details><summary>archive.simultan.org (1)</summary>

- [Species Series, Simultan festival archive (2014)](https://archive.simultan.org/works/species-series/)

</details>
<details><summary>archive2.bakonline.org (1)</summary>

- [Claudia Martínez Garay, BAK basis voor actuele kunst](https://archive2.bakonline.org/?p=35032)

</details>
<details><summary>archives.nasher.duke.edu (2)</summary>

- [Anne Gregory, exhibition review (Afrikadaa, PDF in Nasher press archive)](https://archives.nasher.duke.edu/mutu/press/afrikadaa.pdf)
- [Wangechi Mutu: A Fantastic Journey - Selected works (Nasher Museum of Art archive site)](https://archives.nasher.duke.edu/mutu/art.php)

</details>
<details><summary>arko.or.kr (3)</summary>

- [Korean Pavilion 2019 – siren eun young jung artist page](https://arko.or.kr/pavilion/19pavilion/artist1.html)
- [Korean Pavilion, 58th Venice Biennale – Hwayeon Nam, Dancer from the Peninsula](https://www.arko.or.kr/pavilion/19pavilion/artist3.html)
- [Korean Pavilion, 58th Venice Biennale – Jane Jin Kaisen, Community of Parting](https://arko.or.kr/pavilion/19pavilion/artist2.html)

</details>
<details><summary>aros.dk (1)</summary>

- [Jesper Just - Appearing / Intercourses, ARoS](https://www.aros.dk/en/exhibitions/jesper-just-appearing-intercoures-en/)

</details>
<details><summary>arroniz-arte.com (1)</summary>

- [Marcela Armas, Arróniz Arte Contemporáneo](https://arroniz-arte.com/artists/marcela-armas)

</details>
<details><summary>ars.electronica.art (60)</summary>

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
- [Ars Electronica Mediaservice: The Winners of the Prix Ars Electronica 2019](https://ars.electronica.art/mediaservice/?p=31574)
- [Artificial intelligence as a meta-researcher – Ars Electronica Blog interview with Interspecifics](https://ars.electronica.art/aeblog/?p=26245)
- [Avatar Robot Cafe DAWN ver.β, STARTS Prize Exhibition, Ars Electronica Festival 2022](https://ars.electronica.art/planetb/en/avatar-robot-cafe)
- [Añoranzas (Yira Yira) — Ars Electronica Festival 2023](https://ars.electronica.art/who-owns-the-truth/?p=1792)
- [Baitul Ma'mur — Ars Electronica 2021 Festival, A New Digital Deal theme exhibition](https://ars.electronica.art/newdigitaldeal/en/baitul-mamur)
- [Broken Spectre, S+T+ARTS Prize 2023 Grand Prize page, Ars Electronica](https://ars.electronica.art/starts-prize/en/broken-spectre/)
- [Calculating Empires, S+T+ARTS Prize 2024 Grand Prize – Artistic Exploration](https://ars.electronica.art/starts-prize/en/calculating-empires/)
- [CIFO-Ars Electronica Awards 2023 press release](https://ars.electronica.art/press/files/2023/03/060323.CIFO-Awards-EN.pdf)
- [Conversations Beyond the Ordinary, Ars Electronica Festival 2024](https://ars.electronica.art/hope/?p=7551)
- [CyberArts 2021 catalogue (Prix Ars Electronica), jury statement](https://ars.electronica.art/newdigitaldeal/files/2021/08/cyberarts21.pdf)
- [From Atoms to Entire Galaxies: "Everything" – Ars Electronica Blog, 2017](https://ars.electronica.art/aeblog/?p=15501)
- [From Blue Marble to Bioplastic Record — Ars Electronica Blog](https://ars.electronica.art/aeblog/?p=77214)
- [FuneralPlay - A New Digital Deal, Ars Electronica Festival 2021 (European ARTificial Intelligence Lab commission)](https://ars.electronica.art/newdigitaldeal/en/funeralplay)
- [Golden Nicas for artists from Japan, the USA, Taiwan, Colombia and Austria, Ars Electronica Mediaservice, 2022 (pool source)](https://ars.electronica.art/mediaservice/?p=32023)
- [Guanaquerx - Ars Electronica Festival 2025 (PANIC programme)](https://ars.electronica.art/panic/en/view/guanaquerx-21c38ddb450c81e1b698d809489b36d6)
- [I.AM.ISIGO Digital Mystery System – Ars Electronica Festival 2024](https://ars.electronica.art/hope/?p=13421)
- [In a Small Room – STARTS Prize 2021 nomination page (Ars Electronica)](https://ars.electronica.art/starts-prize/?p=3717)
- [Mid Tide #3 - Ars Electronica Festival 2024 (HOPE)](https://ars.electronica.art/hope/?p=7654)
- [On Search for Balance - Ars Electronica Blog](https://ars.electronica.art/aeblog/en/auf-der-suche-nach-dem-gleichgewicht/)
- [Opera (Deep Space 8K), Ars Electronica Festival 2021](https://ars.electronica.art/newdigitaldeal/en/opera-deepspace8k)
- [Prix 2021: Musicians face the new reality, Ars Electronica Blog](https://ars.electronica.art/aeblog/en/2021/08/17/prix-2021-musicians-face-the-new-reality/)
- [Prix Ars Electronica 2010, Ars Electronica Mediaservice](https://ars.electronica.art/mediaservice/?p=28155)
- [Prix Ars Electronica 2013 winners (press release; Golden Nica, Computer Animation / Film / VFX)](https://ars.electronica.art/press/files/2013/05/Prix-Ars-Electronica-2013_Winners_en.pdf)
- [Prix Ars Electronica 2014: The 2014 Prizewinners (press release, pool source)](https://ars.electronica.art/mediaservice/files/2014/06/PA_Prix_Winners-2014_Rob_korr_Sarah-Oos_EN.pdf)
- [Prix Ars Electronica 2017 winners announcement (Golden Nica, Computer Animation/Film/VFX)](https://ars.electronica.art/mediaservice/?p=31314)
- [Prix Ars Electronica 2018 winners, Ars Electronica Mediaservice](https://ars.electronica.art/mediaservice/?p=31454)
- [Prix Ars Electronica 2021 counts 3,158 entries from 86 countries, Ars Electronica Mediaservice](https://ars.electronica.art/mediaservice/?p=31880)
- [Prix Ars Electronica 2021 winners press release (Computer Animation, Award of Distinction)](https://ars.electronica.art/mediaservice/files/2021/06/Prix-Ars-Electronica-2021_EN.pdf)
- [Prix Ars Electronica 2022 prizewinners (press release, pool source)](https://ars.electronica.art/press/files/2022/06/Prix-2022_EN_.pdf)
- [Prix Ars Electronica 2023 winners (Artificial Intelligence & Life Art, Award of Distinction)](https://ars.electronica.art/mediaservice/en/2023/06/12/prix-winners-2023/)
- [Prix Ars Electronica 2024 catalogue (pool source)](https://ars.electronica.art/hope/files/2024/08/prix2024.pdf)
- [Prix Ars Electronica 2024 jury statements (New Animation Art)](https://ars.electronica.art/prix/en/jurystatements/statements2024/)
- [Prix Ars Electronica 2025 press release (PDF) - Golden Nica, Artificial Life & Intelligence](https://ars.electronica.art/mediaservice/files/2025/07/pa_en-prix-ars-electronica-2025.pdf)
- [Prix Ars Electronica 2026 winners](https://ars.electronica.art/prix/en/winners/)
- [Prix Ars Electronica: The Winners 2013, Ars Electronica Mediaservice](https://ars.electronica.art/mediaservice/?p=29625)
- [Prometheus Firebringer - S+T+ARTS Prize (Ars Electronica)](https://ars.electronica.art/starts-prize/?p=10828)
- [S+T+ARTS Prize 2023 press release (pool source)](https://ars.electronica.art/mediaservice/files/2023/06/pressetext-en-starts.pdf)
- [Soundscapes of the Andean plain — Ars Electronica Blog (interview with Juan Cortés)](https://ars.electronica.art/aeblog/?p=39165)
- [Stained — Ars Electronica Festival 2024](https://ars.electronica.art/hope/?p=7756)
- [Temporary Stored – Ars Electronica Festival 2023](https://ars.electronica.art/who-owns-the-truth/?p=9470)
- [The Echinoidea Future – Adriatic Sensing — S+T+ARTS Prize 2024, Honorary Mention](https://ars.electronica.art/starts-prize/?p=10939)
- [The slightly different café, Ars Electronica Blog, 2022](https://ars.electronica.art/aeblog/?p=33321)
- [Tracing the Invisible Lines Between Devices and Drones – Ars Electronica Blog, 4 June 2025](https://ars.electronica.art/panic/?p=761)
- [TROPICS: The Golden Nica of Computer Animation 2018 (interview), Ars Electronica Blog](https://ars.electronica.art/aeblog/en/2018/08/31/tropics/)
- [Void in Resonance \| Ars Electronica Festival 2025: Panic](https://ars.electronica.art/panic/en/view/void-in-resonance-22238ddb450c815bad66c8fa5228e6ca)
- [Washed Out "The Hardest Part" (Ars Electronica Festival 2024)](https://ars.electronica.art/hope/en/washed-out-the-hardest-part/)
- [Wild Machines, Ars Electronica Festival 2023](https://ars.electronica.art/who-owns-the-truth/?p=1804)
- [Words as Weapons – Ars Electronica Blog (interview)](https://ars.electronica.art/aeblog/?p=80241)
- [Чули? Чули. – FOUNDING LAB Fall Term Projects (IT:U x Ars Electronica)](https://ars.electronica.art/university/en/%d1%87%d1%83%d0%bb%d0%b8-%d1%87%d1%83%d0%bb%d0%b8/)
- [“Corpus Nil”: A Performance by Man and Artificial Intelligence - Ars Electronica Blog (Vanessa Graf, 2017)](https://ars.electronica.art/aeblog/en/2017/09/04/corpus-nil/)

</details>
<details><summary>arsenal-berlin.de (1)</summary>

- [Arsenal / Berlinale Forum 2025 – The Trio Hall dossier (PDF)](https://www.arsenal-berlin.de/assets/Forum/2025/pdfs/The_Trio_Hall_D.pdf)

</details>
<details><summary>arshake.com (2)</summary>

- [Daniel Rozin. Reflections at the mirror, Arshake](https://www.arshake.com/en/daniel-rozin-reflections-at-the-mirror/)
- [Interview I Daito Manabe, Arshake, 2017](https://www.arshake.com/en/interview-i-daito-manabe/)

</details>
<details><summary>art-almanac.com.au (1)</summary>

- [Jompet Kuswidananto: After Voices - Art Almanac](https://www.art-almanac.com.au/jompet-kuswidananto-after-voices/)

</details>
<details><summary>art21.org (3)</summary>

- [Art21 New York Close Up – Jordan Strafer's True Stories (2026)](https://art21.org/watch/new-york-close-up/jordan-strafers-true-stories/)
- [Jacolby Satterwhite, Art21](https://art21.org/artist/jacolby-satterwhite/)
- [Susan Philipsz in "Berlin" - Art21](https://art21.org/watch/art-in-the-twenty-first-century/s9/susan-philipsz-in-berlin-segment/)

</details>
<details><summary>artafricamagazine.org (3)</summary>

- [Exploring resilience and regeneration, ART AFRICA](https://artafricamagazine.org/exploring-resilience-and-regeneration-an-interview-on-brazils-participation-in-the-60th-international-art-exhibition-la-biennale-di-venezia/)
- [Laila Hida: Sensing the Desert, Reimagining the Image – ART AFRICA Magazine](https://artafricamagazine.org/leila-hida-sensing-the-desert-reimagining-the-image/)
- [Prizewinners at Dak’art 2012, ART AFRICA Magazine](https://artafricamagazine.org/?p=13034)

</details>
<details><summary>artandaustralia.com (1)</summary>

- [Tracey Moffatt and the Politics of Representing the Marginalised (Art + Australia)](https://www.artandaustralia.com/online/online/discursions/tracey-moffatt-and-politics-representing-marginalised.html)

</details>
<details><summary>artandmarket.net (1)</summary>

- [Midpoint: Vong Phaophanit and Claire Oboussier — Art & Market](https://www.artandmarket.net/midpoint/2023/12/15/vong-phaophanit-and-claire-oboussier)

</details>
<details><summary>artasiapacific.com (3)</summary>

- [After Voices - ArtAsiaPacific (review, 29 Aug 2016)](https://www.artasiapacific.com/after-voices/)
- [ArtAsiaPacific, 'pure intention, muddy ground'](https://www.artasiapacific.com/shows/pure-intention-muddy-ground-singapore-biennale-2025/)
- [Mumbai's Collaborative Studio Wins 2020 Nam June Paik Art Center Prize, ArtAsiaPacific, 2020](https://artasiapacific.com/news/mumbai-s-collaborative-studio-wins-2020-nam-june-paik-art-center-prize)

</details>
<details><summary>artbasel.com (4)</summary>

- [Art Basel launches Zero 10, a new global initiative for art of the digital era - Art Basel](https://www.artbasel.com/stories/art-basel-launches-zero-10--a-new-initiative-for-art-of-the-digital-era)
- [Ho Tzu Nyen taps AI to pay tribute to Hong Kong cinema on M+ Facade (Art Basel Stories)](https://www.artbasel.com/stories/ho-tzu-nyen-ai-hong-kong-cinema-m-art-basel)
- [Martha Atienza on Bantayan Island divers in Times Square — Art Basel Stories](https://www.artbasel.com/stories/martha-atienza-bantayan-island-divers-times-square?lang=en)
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
<details><summary>artdaily.com (6)</summary>

- [Australian Pavilion presents Tracey Moffatt's solo exhibition My Horizon (Artdaily)](https://artdaily.com/news/95945/Australian-Pavilion-presents-Tracey-Moffatt-s-solo-exhibition--My-Horizon-)
- [Camden Arts Centre presents "I saw square triangle sine" exhibition of new works by Haroon Mirza – Artdaily](https://artdaily.com/news/51016/images/close.gif)
- [Digital art project by Rachel Rossin launches on whitney.org — Artdaily, 28 September 2022](https://artdaily.com/news/150283/Digital-art-project-by-Rachel-Rossin-launches-on-whitney-org)
- [Major new commission from Indonesian multi-disciplinary artist Jompet Kuswidananto opens in Sydney - artdaily (SCAF press release)](https://artdaily.com/news/87857/images/close.gif)
- [New digital art commission by Amelia Winger-Bearskin launches on whitney.org (Artdaily, Whitney press release)](https://artdaily.com/news/152773/New-digital-art-commission-by-Amelia-Winger-Bearskin-launches-on-whitney-org)
- [New digital art commission by Peter Burr launches on whitney.org (Artdaily, Whitney press release)](https://artdaily.com/news/159671/New-digital-art-commission-by-Peter-Burr-launches-on-whitney-org)

</details>
<details><summary>artdogistanbul.com (1)</summary>

- [ArtDog Istanbul — Fermata: Hong Kong in Venice (interview)](https://artdogistanbul.com/en/fermata-hong-kong-in-venice/)

</details>
<details><summary>artealdia.com (1)</summary>

- [An 'anti-archive' made home: Angie Saiz at the Biennial of Media Arts – Arte Al Día](https://www.artealdia.com/News/AN-ANTI-ARCHIVE-MADE-HOME-ANGIE-SAIZ-AT-THE-BIENNIAL-OF-MEDIA-ARTS)

</details>
<details><summary>artelectronicmedia.com (1)</summary>

- [We Are All Made of Light — Art & Electronic Media](https://artelectronicmedia.com/en/?p=2414)

</details>
<details><summary>arteporexcelencias.com (1)</summary>

- [New Digital Art Commission by Rick Silva Launches on whitney.org (Arte por Excelencias, Whitney press release)](https://www.arteporexcelencias.com/es/node/31462)

</details>
<details><summary>artforum.com (5)</summary>

- [Artforum, 'Hwayeon Nam on alternative archives and the modern dance of Seunghee Choi' (2020)](https://www.artforum.com/columns/hwayeon-nam-on-alternative-archives-and-the-modern-dance-of-seunghee-choi-247427/)
- [Du Keke, Singapore Biennale 2025 diary (Artforum)](https://www.artforum.com/columns/singapore-biennale-2025-diary-du-keke-1234737801/)
- [Kite feature — Artforum](https://www.artforum.com/features/kite-generative-ai-performance-video-1234727290/)
- [Leslie Thornton on saturation and solitude in her moving-image works - Artforum](https://www.artforum.com/columns/leslie-thornton-on-saturation-and-solitude-in-her-moving-image-works-247246/)
- [Screen Song (opening of Doug Aitken's SONG 1 at the Hirshhorn), Artforum](https://www.artforum.com/columns/kriston-capps-at-the-opening-of-doug-aitkens-song-1-at-the-hirshhorn-museum-199808/)

</details>
<details><summary>artinamericamagazine.com (1)</summary>

- [Faye Hirsch, Sharon Stone in Abuja - Art in America, 2011](http://www.artinamericamagazine.com/reviews/sharon-stone-in-abuja/)

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
<details><summary>artnews.com (1)</summary>

- [Zach Blas, Facial Weaponization Suite, 2012–14 — ARTnews, The 100 Best Artworks of the 21st Century](https://www.artnews.com/list/art-news/news/100-best-artworks-21st-century-1234734225/zach-blas-facial-weaponization-suite-2012-14/)

</details>
<details><summary>artoland.com (1)</summary>

- [Dust Blooms at Museum Schloß Moyland, artoland.com (artist's site)](https://artoland.com/2016/06/28/dust-blooms/)

</details>
<details><summary>artport.whitney.org (2)</summary>

- [Live Study (artport project site)](https://artport.whitney.org/commissions/mandiberg/index.php)
- [The Thinking Ocean, artport (work)](https://artport.whitney.org/commissions/the-thinking-ocean)

</details>
<details><summary>artra.lk (1)</summary>

- [The Art of Listening: In Conversation with Dinoj M, ARTRA Magazine](https://www.artra.lk/the-art-of-listening-in-conversation-with-dinoj-m/)

</details>
<details><summary>artreview.com (16)</summary>

- [ArtReview Asia Summer 2015 feature: Charles Lim](https://artreview.com/summer-2015-ara-feature-charles-lim/)
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
- [The Venice Questionnaire #1: Jesper Just, ArtReview](https://artreview.com/1-venice-jesper-just/)
- [Yuko Mohri on Representing Japan at the 60th Venice Biennale (ArtReview)](https://artreview.com/yuko-mohri-on-representing-japan-at-the-60th-venice-biennale/)
- [Zarina Muhammad's Ecofeminist Sorcery - ArtReview](https://artreview.com/zarina-muhammad-eco-feminism-magic-sorcery/)

</details>
<details><summary>artribune.com (3)</summary>

- [Artribune – Intervista per scoprire Theo Eshetu (Christian Caliandro)](https://www.artribune.com/?p=1230851)
- [HUMANS. Video-ritratti della società contemporanea. #16 Conflitti (interview with Alessandro Bavari), Artribune](https://www.artribune.com/?p=801408)
- [L’Australia lo aveva escluso. Ora Khaled Sabsabi è due volte alla Biennale di Venezia: l’intervista – Artribune](https://www.artribune.com/?p=1256303)

</details>
<details><summary>artsandculture.google.com (9)</summary>

- ["Subnormal Europe", multimedia music theatre – Google Arts & Culture (ZKM)](https://artsandculture.google.com/asset/subnormal-europe-multimedia-music-theatre-%C3%93scar-escudero/JgHzpQDM1GnOEA?hl=en)
- [6th International Digital Art Biennial - BIAN 2022 - ELEKTRA on Google Arts & Culture](https://artsandculture.google.com/story/QAVBXNdvesD1zw)
- [Google Arts & Culture — An Artist Gives Voice to Traditional Peruvian Textiles](https://artsandculture.google.com/story/DwWhq_x7q_L2ZQ)
- [RÉSONANCES - Louis-Philippe Rondeau - Google Arts & Culture (ELEKTRA)](https://artsandculture.google.com/asset/r%C3%A9sonances-louis-philippe-rondeau/QQFIQFxHwAm3Ig)
- [The Anatomy Lessons – Kochi-Muziris Biennale, Google Arts & Culture](https://artsandculture.google.com/asset/the-anatomy-lessons-rashid-rana/cwF6XN-DJEEOMQ)
- [The Buddhist Bug, Into the Night - Google Arts & Culture (QAGOMA collection)](https://artsandculture.google.com/asset/the-buddhist-bug-into-the-night-anida-yoeu-ali/vwHI1bE7NsWzRQ)
- [The Character of Characters, Asian Art Museum (Google Arts & Culture)](https://artsandculture.google.com/asset/the-character-of-characters-xu-bing-chinese-born-1955/ugEdDfSKjVighA?hl=en)
- [The Making of Rhizome's Net Art Anthology: Constant Dullaart's The Revolving Internet - Google Arts & Culture](https://artsandculture.google.com/story/the-making-of-rhizome-s-net-art-anthology-constant-dullaart-s-the-revolving-internet-rhizome/zwUR0q_QS8FHKg)
- [What Did Flowers Used To Look Like? (Google Arts & Culture)](https://artsandculture.google.com/story/OwXR4TYUXPkzjQ)

</details>
<details><summary>artshelp.com (1)</summary>

- [Tewa Barnosa (Artshelp)](https://www.artshelp.com/tewa-barnosa/)

</details>
<details><summary>artshub.com.au (1)</summary>

- [Khaled Sabsabi reveals details of two installations at Venice Biennale – ArtsHub (7 May 2026)](https://www.artshub.com.au/news/news/khaled-sabsabi-reveals-details-of-two-installations-at-venice-biennale-2857688/)

</details>
<details><summary>artsillustrated.in (1)</summary>

- [Portraits of possibility – Arts Illustrated](https://artsillustrated.in/?p=14238)

</details>
<details><summary>artsonje.org (2)</summary>

- [Art Sonje Center, Jane Jin Kaisen: Community of Parting](https://artsonje.org/en/exhibition/jane-jin-kaisen-community-of-parting/)
- [Heecheon Kim: Double Poser — Art Sonje Center](https://artsonje.org/en/exhibitions_abroad/heecheon-kim-double-poser/)

</details>
<details><summary>artspace-aotearoa.nz (1)</summary>

- [Selina Ershadi: The Blue Dome - Artspace Aotearoa](https://artspace-aotearoa.nz/exhibitions/the-blue-dome)

</details>
<details><summary>artspectacleasia.com (1)</summary>

- [Every Step in the Right Direction: Singapore Biennale 2019, Art Spectacle Asia](https://artspectacleasia.com/every-step-in-the-right-direction-singapore-biennale-2019)

</details>
<details><summary>artsreview.com.au (1)</summary>

- [Tracey Moffatt: Body Remembers, Art Gallery of South Australia (Arts Review)](https://artsreview.com.au/?p=54776)

</details>
<details><summary>artsy.net (1)</summary>

- [Miami Artist Jillian Mayer Is Laughing All the Way to the Singularity, Artsy](https://www.artsy.net/article/artsy-editorial-miami-artist-jillian-mayer-is-laughing-all-the-way-to-the-singularity)

</details>
<details><summary>artthrob.co.za (3)</summary>

- [Alchemy of the Self: 'Seekers, Seers, Soothsayers' at Zeitz MOCAA (ArtThrob, 2024)](https://artthrob.co.za/2024/07/18/alchemy-of-the-self-seekers-seers-soothsayers-at-zeitz-mocaa/)
- [ArtThrob, 'The grammar of suffering: Nolan Oswald Dennis's Options' (2019)](https://artthrob.co.za/2019/01/30/the-grammar-of-suffering-nolan-oswald-denniss-options/)
- [Silent and Complex Histories: In conversation with Buhlebezwe Siwani (ArtThrob, 2018)](https://artthrob.co.za/2018/11/05/silent-and-complex-histories-in-conversation-with-buhlebezwe-siwani/)

</details>
<details><summary>artxlagos.com (2)</summary>

- [ART X Lagos, 'Mad Horse City'](https://www.artxlagos.com/the-projects/mad-horse-city)
- [ART X Talks 2022: Once Upon A Garden](https://artxlagos.com/art-x-talks/once-upon-a-garden)

</details>
<details><summary>asapconnect.in (3)</summary>

- [Anonya: Tayeba Begum Lipi’s Work with Dhaka's Transgender Community — ASAP Art](https://www.asapconnect.in/post/280/singlestories/anonya)
- [On Protest, Memory and History: In Conversation with Mekh Limbu (ASAP \| art)](https://www.asapconnect.in/post/995/singleevents/on-protest-memory-and-history)
- [Weaving Video Stories: In Conversation with Mekh Limbu (ASAP \| art)](https://asapconnect.in/post/994/singleevents/weaving-video-stories)

</details>
<details><summary>asastjerna.com (2)</summary>

- [Research – Åsa Helena Stjerna](https://www.asastjerna.com/research/)
- [Sky Brought Down \| 2017 – Åsa Helena Stjerna](https://www.asastjerna.com/portfolios/sky-brought-down/)

</details>
<details><summary>ashleyzelinskie.com (1)</summary>

- [Ashley Zelinskie - artist website (statement, CV)](https://www.ashleyzelinskie.com/)

</details>
<details><summary>asianart.com (1)</summary>

- [Out of Character: Decoding Chinese Calligraphy, asianart.com review](https://asianart.com/exhibitions/ooc/gary.html)

</details>
<details><summary>asiasociety.org (2)</summary>

- [After Darkness: Southeast Asian Art in the Wake of History – Asia Society](https://asiasociety.org/new-york/exhibitions/after-darkness-southeast-asian-art-wake-history)
- [Xu Bing art cards, Asia Society](https://asiasociety.org/files/uploads/402files/XB_Art%20Cards_E.pdf)

</details>
<details><summary>asiawa.jpf.go.jp (1)</summary>

- [Lifepatch: The Natural Affinity between Indonesian Culture and Global Peer-to-Peer Culture (Asia Hundreds, Japan Foundation, 2016)](https://asiawa.jpf.go.jp/en/culture/features/asiahundreds014/)

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
<details><summary>atopia.org.uk (2)</summary>

- [Never real historians, always near poets — atopia.org.uk (artists' site)](https://atopia.org.uk/commission/never-real-historians-always-near-poets/)
- [Oxford Art Journal excerpt (Corey and Teo, 2020) — atopia.org.uk](https://atopia.org.uk/?p=1616)

</details>
<details><summary>audiospace.soundingfuture.com (1)</summary>

- [Temporary Stored • KMRU (AudioSpace / Sounding Future)](https://audiospace.soundingfuture.com/tracks/temporary-stored)

</details>
<details><summary>aurora.dawn.com (1)</summary>

- [Aurora (Dawn) interview: Tariq Alexander Qaiser on the open seas and Karachi's mangrove forests](https://aurora.dawn.com/news/1144283)

</details>
<details><summary>autostraddle.com (1)</summary>

- [Difficult Love: Watch Zanele Muholi's Powerful Documentary - Autostraddle, 2012](https://www.autostraddle.com/difficult-love-watch-zanele-muholis-powerful-documentary-on-the-south-african-lgbtq-experience-151929/)

</details>
<details><summary>awn.com (1)</summary>

- [Fresh Takes: Daisy Jacobs Plunges Viewers into Real Life Drama with 'The Full Story' - AWN](https://www.awn.com/animationworld/fresh-takes-daisy-jacobs-plunges-viewers-real-life-drama-full-story)

</details>
<details><summary>awrd.com (1)</summary>

- [SMOG SEASON \| Witaya Junma \| AWRD (YouFab Global Creative Awards 2021 entry)](https://awrd.com/creatives/detail/11813987)

</details>
<details><summary>axolot.cat (1)</summary>

- [Maria Choir — Axolot (technical collaborators)](https://axolot.cat/maria-choir/)

</details>
<details><summary>backpackingjapan.blogspot.com (1)</summary>

- [Backpacking Japan – Annecy 2016: Shorts & Breakfast, Ryo Orikasa](https://backpackingjapan.blogspot.com/2016/06/annecy-2016-p-dej-du-court-shorts.html)

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
<details><summary>baselandruanne.com (1)</summary>

- [The Zone, baselandruanne.com](https://baselandruanne.com/The-Zone)

</details>
<details><summary>bb9.berlinbiennale.de (1)</summary>

- [Halil Altindere, participants, 9th Berlin Biennale (2016)](https://bb9.berlinbiennale.de/participants/altindere/)

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
<details><summary>bengaluru.sciencegallery.com (1)</summary>

- [Carbon Black - Science Gallery Bengaluru](https://bengaluru.sciencegallery.com/carbon-and-contamination/carbon-black)

</details>
<details><summary>berlinale-talents.de (1)</summary>

- [Nairobi Berries – Berlinale Talents project profile](https://www.berlinale-talents.de/bt/project/profile/236960)

</details>
<details><summary>berlinale.de (1)</summary>

- [Behind the Sun, Berlinale Forum Expanded 2014](https://berlinale.de/en/2014/programme/20146684.html)

</details>
<details><summary>berlinartlink.com (2)</summary>

- [Interview // Yung Jake: The Performance of the Internet - Berlin Art Link](https://berlinartlink.com/?p=60427)
- [Monira Al Qadiri, Berlin Art Link (2022)](https://www.berlinartlink.com/2022/08/09/monira-al-qadiri/)

</details>
<details><summary>berlinartweek.de (1)</summary>

- [Shrinking Space — interview with Rachel Rossin, Berlin Art Week](https://berlinartweek.de/en/article/shrinking-space/)

</details>
<details><summary>beyondbeauty.podcasts.library.columbia.edu (1)</summary>

- [Beyond Beauty podcast – Minne Atairu interview transcript (Columbia University)](https://beyondbeauty.podcasts.library.columbia.edu/wp-content/uploads/sites/17/2024/07/Minne-Edited.docx)

</details>
<details><summary>bfi.org.uk (2)</summary>

- [A cinema-in-the-moment: Sam Green on A Thousand Thoughts and the ‘live documentary’, Sight and Sound (BFI)](https://www.bfi.org.uk/sight-and-sound/interviews/cinema-moment-sam-green-thousand-thoughts-live-documentary)
- [Tangerine dreams: Yto Barrada - Sight and Sound (BFI)](https://www.bfi.org.uk/sight-and-sound/interviews/tangerine-dreams-yto-barrada)

</details>
<details><summary>bidoun.org (1)</summary>

- [Rania Stephan’s The Three Disappearances of Souad Hosni, Bidoun](http://bidoun.org/articles/the-three-disappearances-of-souad-hosni)

</details>
<details><summary>bienal.org.br (3)</summary>

- [Catastrophe orchestra: an interview with Antonio Társis (Bienal de São Paulo)](https://bienal.org.br/en/catastrophe-orchestra-an-interview-with-antonio-tarsis/)
- [Collectivity, autonomy and Indigenous foreigners at the Venice Biennale, Fundação Bienal de São Paulo](https://bienal.org.br/en/collectivity-autonomy-and-indigenous-foreigners-at-the-venice-biennale/)
- [Ka’a Pûera: we are walking birds, Fundação Bienal de São Paulo](https://bienal.org.br/en/walking-birds/)

</details>
<details><summary>bienalsescvideobrasil.org.br (2)</summary>

- [Julia Mensch, artist page, 21st Bienal de Arte Contemporânea Sesc\_Videobrasil](https://bienalsescvideobrasil.org.br/edicao21/artista/julia-mensch)
- [Maya Shurbaji, artist page, 21st Bienal de Arte Contemporânea Sesc\_Videobrasil](https://bienalsescvideobrasil.org.br/edicao21/artista/maya-shurbaji)

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
<details><summary>bitforms.art (1)</summary>

- [⌘F: Addie Wagenknecht — bitforms gallery](https://www.bitforms.art/news/cmd-f-addie-wagenknecht)

</details>
<details><summary>blantonmuseum.org (1)</summary>

- [Wangechi Mutu: The End of eating Everything - Blanton Museum of Art](https://blantonmuseum.org/rotation/wangechi-mutu-the-end-of-eating-everything/)

</details>
<details><summary>blavity.com (1)</summary>

- [Zimbabwean Kudzanai Chiurai Tackles Civil War In Africa On Film, Via The Last Supper - Blavity (Shadow and Act), 2012](https://blavity.com/zimbabwean-kudzanai-chiurai-tackles-civil-war-in-africa-on-film-via-the-last-supper)

</details>
<details><summary>blindspotgallery.com (3)</summary>

- [Annette Meier, 'The Universe in a Cabinet', ArtAsiaPacific 142 (2025)](https://blindspotgallery.com/wp-content/uploads/2025/04/20250307_The-Universe-in-a-Cabinet_AAP.pdf)
- [Wing Po So and Angela Su will participate in the 13th Seoul Mediacity Biennale (Blindspot Gallery news)](https://blindspotgallery.com/news/wing-po-so-and-angela-su-will-participate-in-the-13th-seoul-mediacity-biennale/)
- [Wing Po So — artist page, Blindspot Gallery](https://blindspotgallery.com/?p=15661)

</details>
<details><summary>blog.autourdeminuit.com (1)</summary>

- [Absence – Autour de Minuit production page](https://blog.autourdeminuit.com/production/absence/?lang=en)

</details>
<details><summary>blog.bela.io (1)</summary>

- [Krzysztof Cybulski on Instrument Design - Bela blog](https://blog.bela.io/krzysztof-cybulski-interview/)

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
<details><summary>bonnierskonsthall.se (1)</summary>

- [Jesper Just, In Search of a City, Bonniers Konsthall](https://bonnierskonsthall.se/en/utstallning/in-search-of-a-city-an-exhibition-on-cities-in-transformation/jesper-just/)

</details>
<details><summary>bookchin.net (2)</summary>

- [Natalie Bookchin in Conversation with Alexandra Juhasz, Fabricating Publics (2021)](https://bookchin.net/wp-content/uploads/2021/12/Natalie-Bookchin-in-Conversation-with-Juhasz-2021.pdf)
- [Now he's out in public and everyone can see, bookchin.net](https://bookchin.net/projects/now-hes-out-in-public-and-everyone-can-see/)

</details>
<details><summary>booooooom.com (1)</summary>

- [An Interview with Artist Daniel Rozin, Booooooom](https://www.booooooom.com/2016/07/16/an-interview-with-artist-daniel-rozin/)

</details>
<details><summary>brakkegrond.nl (1)</summary>

- [Jan Zuiderveld, Coffee Machine, de Brakke Grond](https://brakkegrond.nl/agenda/614/jan-zuiderveld)

</details>
<details><summary>brendanfernandes.ca (2)</summary>

- [Brendan Fernandes – Build Up the House (2024, ART on THE MART)](https://brendanfernandes.ca/build-up-the-house)
- [Brendan Fernandes – Build Up the House II](https://brendanfernandes.ca/build-up-the-house-ii)

</details>
<details><summary>broadwayworld.com (1)</summary>

- [Danish Arts Council Reveals Details of Jesper Just's Multi-Channel Film and Installation, BroadwayWorld, 6 May 2013](https://www.broadwayworld.com/germany/article/Danish-Arts-Council-Reveals-Details-of-Jesper-Justs-Multi-Channel-Film-and-Installation-20130506)

</details>
<details><summary>brooklynrail.org (3)</summary>

- [Lawrence Abu Hamdan with Will Fenstermaker, The Brooklyn Rail (2023)](https://brooklynrail.org/2023/06/art/Lawrence-Abu-Hamdan-with-Will-Fenstermaker/)
- [The Brooklyn Rail — Sung Tieu with Amelia Saul (2023)](https://brooklynrail.org/2023/07/art/Sung-Tieu-with-Amelia-Saul/)
- [TRACEY MOFFATT: Vigils and Travellers (The Brooklyn Rail)](https://brooklynrail.org/2018/07/artseen/TRACEY-MOFFATT-Vigils-and-Travellers/)

</details>
<details><summary>brutus.jp (1)</summary>

- [BRUTUS.jp — 'Korean Cultural News' Vol.22 Artist Kwon Byungjun](https://brutus.jp/en/post-449507)

</details>
<details><summary>bthumm.de (1)</summary>

- [Galerie Barbara Thumm – Theo Eshetu, Biennale Arte 2026 Venice](https://bthumm.de/exhibitions/theo-eshetu-biennale-arte-2026-venice/)

</details>
<details><summary>buffalo.edu (1)</summary>

- [UBNow: UB bio-artist Paul Vanouse wins Golden Nica at Prix Ars Electronica (2019)](https://www.buffalo.edu/ubnow/stories/2019/06/vanouse-golden-nica.html)

</details>
<details><summary>bunka.go.jp (10)</summary>

- [20th Japan Media Arts Festival, Art Division Grand Prize: Interface I](https://www.bunka.go.jp/j-mediaarts-festival/en/award/single/interface-i/index-2.html)
- [Anxious Body — Japan Media Arts Festival creators file (Agency for Cultural Affairs)](https://www.bunka.go.jp/j-mediaarts/en/creators_file/animation/2022/mizushiriyoriko/index.html)
- [APHASIA - 18th Japan Media Arts Festival, Art Division Jury Selections](https://www.bunka.go.jp/j-mediaarts-festival/en/award/single/aphasia/index-2.html)
- [plain voices - 15th Japan Media Arts Festival, Art Division Grand Prize](https://www.bunka.go.jp/j-mediaarts-festival/en/award/single/plain-voices/index.html)
- [Que voz feio（醜い声） - Japan Media Arts Festival (Japanese)](https://www.bunka.go.jp/j-mediaarts-festival/award/single/que_voz_feio/)
- [Soak - 15th Japan Media Arts Festival, Art Division Jury Selections](https://www.bunka.go.jp/j-mediaarts-festival/en/award/single/soak/index-2.html)
- [Species series - 16th Japan Media Arts Festival, Art Division New Face Award](https://www.bunka.go.jp/j-mediaarts-festival/en/award/single/species-series/index.html)
- [Species series - Japan Media Arts Festival (Japanese page, with installation photo caption)](https://www.bunka.go.jp/j-mediaarts-festival/award/single/species_series/index.html)
- [Sports Time Machine - 17th Japan Media Arts Festival, Entertainment Division Excellence Award](https://www.bunka.go.jp/j-mediaarts-festival/en/award/single/sports-time-machine/index.html)
- [《patrinia yellow》for Clarinet and Computer — 文化庁メディア芸術祭 (Japanese page, with credits)](https://www.bunka.go.jp/j-mediaarts-festival/award/single/patrinia_yellow_for_clarinet_and_computer/)

</details>
<details><summary>bunshun.jp (2)</summary>

- [Bunshun Online interview with Rib, part 1 (Japanese)](https://bunshun.jp/articles/-/83055)
- [Bunshun Online interview with Rib, part 3 (Japanese)](https://bunshun.jp/articles/-/83057?page=2)

</details>
<details><summary>business-standard.com (1)</summary>

- [Bangladeshi artist traces a transgender's life — Business Standard (IANS)](https://www.business-standard.com/article/news-ians/bangladeshi-artist-traces-a-transgender-s-life-115011900800_1.html)

</details>
<details><summary>businessdailyafrica.com (1)</summary>

- [Business Daily, 'Jackie Karuti's Labyrinth show is a paradox' (2015)](https://www.businessdailyafrica.com/bd/lifestyle/society/jackie-karuti-s-labyrinth-show-is-a-paradox-2079098)

</details>
<details><summary>buttondown.com (1)</summary>

- [Rick Silva : Field Notes, 'Whitney Museum + UMOCA + SB-720'](https://buttondown.com/ricksilva/archive/whitney-museum-umoca-sb-720/)

</details>
<details><summary>bynder.southbankcentre.co.uk (1)</summary>

- [Heecheon Kim: Double Poser — Southbank Centre press release (PDF)](https://bynder.southbankcentre.co.uk/m/41032140725f17c/original/UPDATED-Heecheon-Kim-Press-Release.pdf)

</details>
<details><summary>byronrich.com (1)</summary>

- [Open Source Estrogen, 2015-2017, Byron Rich](https://byronrich.com/Open-Source-Estrogen-2015-2017)

</details>
<details><summary>cabinetmagazine.org (1)</summary>

- [Christoph Cox, Invisible Cities: An Interview with Christina Kubisch, Cabinet 21 (2006)](https://cabinetmagazine.org/issues/21/cox.php)

</details>
<details><summary>cal.msu.edu (1)</summary>

- [MSU College of Arts & Letters: Professor Wins Grand Prize at Japan Media Arts Festival](https://cal.msu.edu/news/professor-wins-grand-prize-at-japan-media-arts-festival/)

</details>
<details><summary>calculatingempires.net (2)</summary>

- [Calculating Empires – About (artists' project site)](https://calculatingempires.net/about)
- [Calculating Empires – Info, exhibitions and credits (artists' project site)](https://calculatingempires.net/info.html)

</details>
<details><summary>camdenartcentre.org (2)</summary>

- [File Note 66: Haroon Mirza (David Toop) – Camden Art Centre](https://camdenartcentre.org/file-notes/file-note-66-haroon-mirza)
- [I saw square triangle sine – Camden Art Centre](https://camdenartcentre.org/whats-on/i-saw-square-triangle-sine)

</details>
<details><summary>camillesauer.com (1)</summary>

- [Camille Sauer — Le Miroir (artist's website)](https://www.camillesauer.com/en/post/le-miroir-1)

</details>
<details><summary>cannupahanska.com (2)</summary>

- [Cannupa Hanska Luger – Midéegaadi (Future Ancestral Technologies)](https://cannupahanska.com/fat/midegaadi)
- [Cannupa Hanska Luger – Midéegaadi, Times Square Midnight Moment April 2025](https://www.cannupahanska.com/public-art/times-square)

</details>
<details><summary>canvasonline.com (3)</summary>

- [Canvas – Ali Cherri profile](https://canvasonline.com/ali-cherri/)
- [Refik Anadol, Canvas magazine](https://canvasonline.com/refik-anadol/)
- [Tewa Barnosa interview (Canvas)](https://canvasonline.com/tewa-baronsa/)

</details>
<details><summary>cargocollective.com (1)</summary>

- [Behind Shirely (2020) — Ibiye Camp (artist's Cargo site)](https://cargocollective.com/ibiyecamp/Behind-Shirely-2020)

</details>
<details><summary>cartoonbrew.com (3)</summary>

- ['Everything' Creator David OReilly On The Hard Truths Of Moving Away From Animation – Cartoon Brew, 2017](https://www.cartoonbrew.com/shorts/everything-creator-david-oreilly-hard-truths-moving-away-animation-150296.html)
- [Cartoon Brew – Animating Poetry: The Word-Based Films Of Ryo Orikasa](https://www.cartoonbrew.com/animators/ryo-orikasa-animation-word-play-258351.html)
- [Erick Oh On ‘Opera’ (Cartoon Brew)](https://www.cartoonbrew.com/awards/erick-oh-on-opera-oscar-shorts-interview-series-204262.html)

</details>
<details><summary>cassiemcquater.com (1)</summary>

- [Love Birds, Night Birds, Devil-Birds, artist's website](https://www.cassiemcquater.com/lovebirds.html)

</details>
<details><summary>catalannews.com (1)</summary>

- [Catalan News – Catalonia lands at Venice Art Biennale with 'Paper Tears' installation](https://www.catalannews.com/culture/item/catalonia-lands-at-venice-art-biennale-with-paper-tears-installation)

</details>
<details><summary>cbsnews.com (1)</summary>

- [Oddly hypnotizing artist's video "I Am Your Grandma", CBS News](https://www.cbsnews.com/news/oddly-hypnotizing-artists-video-i-am-your-grandma/)

</details>
<details><summary>cccb.org (1)</summary>

- [Maria CHOIR — CCCB touring dossier](https://www.cccb.org/en/touring-activities/dossier/maria-choir/245111)

</details>
<details><summary>ccme.org.ma (1)</summary>

- [5è Biennale de Marrakech: Crossings, une installation vidéo sur le drame de la migration clandestine subsaharienne - CCME / MAP, 2014](https://www.ccme.org.ma/5e-biennale-de-marrakech-crossings-une-installation-video-sur-le-drame-de-la-migration-clandestine-subsaharienne)

</details>
<details><summary>cdm.link (1)</summary>

- [Digging the Asian and African undergrounds with C-drík Kirdec, CDM Create Digital Music, 2016](https://cdm.link/2016/08/digging-asian-african-undergrounds/)

</details>
<details><summary>cevdeterek.com (1)</summary>

- [Cevdet Erek works (artist's site, exhibition list)](https://cevdeterek.com/)

</details>
<details><summary>channel.hammer.ucla.edu (1)</summary>

- [The Making of Yoshua Okón's 'Octopus', Hammer Channel](https://channel.hammer.ucla.edu/video/922/the-making-of-yoshua-okons-octopus)

</details>
<details><summary>channel.louisiana.dk (1)</summary>

- [Susan Philipsz: Song As A Trigger Of Memory - Louisiana Channel](https://channel.louisiana.dk/video/susan-philipsz-song-as-a-trigger-of-memory)

</details>
<details><summary>charactermedia.com (1)</summary>

- [Inception: Artist Teek Mach Paints VR Visions To Bring People Together, Character Media](https://charactermedia.com/inception-artist-teek-mach-paints-vr-visions-to-bring-people-together-asian-american-vietnamese-american-artist-virtual-reality/)

</details>
<details><summary>chiangmaicitylife.com (1)</summary>

- [City art beats: knitting moments together - Chiang Mai CityLife](https://chiangmaicitylife.com/citylife-articles/city-art-beats-knitting-moments-together)

</details>
<details><summary>chinadaily.com.cn (1)</summary>

- [Xu Bing interview, China Daily (2024)](https://www.chinadaily.com.cn/a/202403/23/WS65fe3b38a31082fc043be445_2.html)

</details>
<details><summary>christinakubisch.de (1)</summary>

- [Electrical Walks (artist's website)](https://www.christinakubisch.de/electrical-walks)

</details>
<details><summary>chrome.google.com (1)</summary>

- [NoSearchBar, Chrome Web Store](https://chrome.google.com/webstore/detail/nosearchbar/fjjlanpalmagenpageablaphkfcchado)

</details>
<details><summary>cifo.org (2)</summary>

- [CIFO x Ars Electronica Awards 2025](https://www.cifo.org/blog-1/cifo-x-ars-electronica-awards-2025)
- [CIFO — Ars Electronica Awards](https://www.cifo.org/ars-electronica)

</details>
<details><summary>cinelogue.com (1)</summary>

- [Difficult Love - Cinelogue](https://cinelogue.com/film/difficult-love/)

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
<details><summary>citygallery.org.nz (1)</summary>

- [William Kentridge: The Refusal of Time, City Gallery Wellington, 2014](https://citygallery.org.nz/exhibitions/william-kentridge-the-refusal-of-time)

</details>
<details><summary>claudialarcher.com (1)</summary>

- [AI and the Art of Historical Reinterpretation – Claudia Larcher (artist site)](https://claudialarcher.com/work/theartofhistoricalreinterpretation)

</details>
<details><summary>clemenciaecheverri.com (2)</summary>

- [Clemencia Echeverri Estudio, home page](https://www.clemenciaecheverri.com/)
- [Versión libre – 2011, Clemencia Echeverri Estudio](https://www.clemenciaecheverri.com/version-libre-paramilitarismo-y-conflicto-armado/)

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
<details><summary>clotmag.com (5)</summary>

- [Basim Magdy, on traditional narratives & our perceptions of memory, history & time (CLOT Magazine, 2025)](https://clotmag.com/interviews/basim-magdy-on-traditional-narratives-our-perceptions-of-memory-history-time)
- [Eddy Gibb, "When we become NPCs: Trolled by Danielle Brathwaite-Shirley's video game-based Art", CLOT Magazine, 24 March 2026](https://clotmag.com/interviews/when-we-become-npcs-trolled-by-danielle-brathwaite-shirleys-video-game-based-art)
- [JALILA ESSAÏDI, spider silk & human tissue to fabricate bulletproof skin, CLOT Magazine, 2014](https://clotmag.com/interviews/jalila-essaidi-spider-silk-and-human-tissue-to-make-bulletproof-skin)
- [NELO AKAMATSU, on meditative studies of water & sound — CLOT Magazine](https://clotmag.com/?p=13764)
- [Philip Beesley, the divine technology - CLOT Magazine](https://clotmag.com/?p=21956)

</details>
<details><summary>cms.ikon-gallery.org (1)</summary>

- [Exhibition guide, Yto Barrada: RIFFS, Ikon Gallery 2012 (PDF)](https://cms.ikon-gallery.org/wp-content/uploads/2013/08/5088c13f-8255-40a3-9bb4-41ffef1195a5.pdf)

</details>
<details><summary>cnn.com (1)</summary>

- [Exhibition shows off the art of Nollywood - CNN, 2010](http://www.cnn.com/2010/WORLD/africa/12/23/nollywood.exhibition/index.html)

</details>
<details><summary>cntrfld.art (1)</summary>

- [In Conversation: field-0 — Following Drifting Bodies (CNTRFLD.ART, 2026)](https://www.cntrfld.art/journal/in-conversation-field-0)

</details>
<details><summary>collection.qagoma.qld.gov.au (1)</summary>

- [Tracey Moffatt: Vigil - QAGOMA collection](https://collection.qagoma.qld.gov.au/node/56029)

</details>
<details><summary>collections.vam.ac.uk (1)</summary>

- [The Butcher's Son — V&A Explore The Collections](https://collections.vam.ac.uk/item/O1572110/the-butchers-son-drawing-mario-klingemann)

</details>
<details><summary>collectorsagenda.com (1)</summary>

- [In the Studio: Wong Ping — Collectors Agenda](https://www.collectorsagenda.com/en/in-the-studio/wong-ping)

</details>
<details><summary>colomboscope.lk (4)</summary>

- [Colomboscope 2026 press release (PDF)](https://www.colomboscope.lk/_files/ugd/08c6d3_68eaea6cd7184a5e8369453ad46dfd7f.pdf)
- [Colomboscope 2026: Rhythm Alliances, exhibition guide (artist page, text by Priyankar Chand)](https://www.colomboscope.lk/_files/ugd/08c6d3_89a22dcee783463da28d6fa5c017c204.pdf)
- [Colomboscope 2026: Rhythm Alliances, festival page](https://www.colomboscope.lk/rhythm-alliances)
- [Fold Media Collective, #HeldApartTogether, Colomboscope](https://colomboscope.lk/fmc)

</details>
<details><summary>colorado.edu (2)</summary>

- [University of Colorado A&S Magazine, 'When napping nature becomes art', 2026 (on Dirt Nap)](https://www.colorado.edu/asmagazine/2026/03/05/when-napping-nature-becomes-art)
- [Void in Resonance by Jerónimo Reyes-Retana (CU Boulder Center for Documentary Media)](https://www.colorado.edu/center/cdem/void-resonance-jeronimo-reyes-retana)

</details>
<details><summary>commarts.com (1)</summary>

- [Dispatch, Communication Arts](https://www.commarts.com/project/26380/dispatch)

</details>
<details><summary>complex.com (1)</summary>

- [Rafael Rozendaal interview, Complex](https://www.complex.com/style/a/leigh-silver/rafael-rozendaal-interview)

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
<details><summary>content.acca.melbourne (1)</summary>

- [Feedback Loops wall labels, ACCA (PDF)](https://content.acca.melbourne/uploads/2019/12/Wall-label-230-x-430.pdf)

</details>
<details><summary>copenhagenfashionweek.com (1)</summary>

- [Q&A with Bubu Ogisi (Copenhagen Fashion Week)](https://copenhagenfashionweek.com/article/iamisigo-q-a)

</details>
<details><summary>crackmagazine.net (1)</summary>

- [United Visual Artists have made a habit of the extraordinary (Crack Magazine, 2014)](https://crackmagazine.net/article/long-reads/united-visual-artists-have-made-a-habit-of-the-extraordinary/)

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
<details><summary>csitoday.com (1)</summary>

- [CSI Professor Michael Mandiberg Showcases Groundbreaking Work at the Whitney, CSI Today, 2026](https://csitoday.com/2026/04/csi-professor-michael-mandiberg-showcases-groundbreaking-work-at-the-whitney/)

</details>
<details><summary>ctm-festival.de (2)</summary>

- [CTM 2026 - Third Programme Announcement](https://www.ctm-festival.de/news/ctm-2026-third-programme-announcement)
- [Daniel Brandt - CTM 2026 artist page](https://www.ctm-festival.de/festival-2026/programme/artists/d/daniel-brandt)

</details>
<details><summary>cultmontreal.com (1)</summary>

- [Squeeeeque!: Alexis O'Hara's sonic igloo — Cult MTL, 2012](http://cultmontreal.com/2012/11/squeeeeque-alexis-oharas-sonic-igloo/)

</details>
<details><summary>culturacolectiva.com (1)</summary>

- [Marcela Armas: Arte Mecánico y Metafórico, Cultura Colectiva, 2012](https://culturacolectiva.com/arte/marcela-armas-arte-mecanico-y-metaforico/amp/)

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
<details><summary>curamagazine.com (1)</summary>

- [Sophia Al-Maria in conversation with Lena Saraj, CURA. 29](https://curamagazine.com/digital/sophia-al-maria/)

</details>
<details><summary>cycling74.com (1)</summary>

- [An Interview with Lisa Park, Cycling '74](https://cycling74.com/articles/an-interview-with-lisa-park)

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
<details><summary>davidebner.de (1)</summary>

- [Wellenwald mit Bunker, davidebner.de](http://davidebner.de/artworks/WellenwaldmitBunker)

</details>
<details><summary>davidoreilly.com (1)</summary>

- [Everything – David OReilly (artist's project page; everything-game.com redirects here)](https://www.davidoreilly.com/everything/)

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
<details><summary>deaddrops.com (2)</summary>

- [Dead Drops - About (deaddrops.com)](https://deaddrops.com/)
- [The Dead Drops Manifesto (deaddrops.com)](https://deaddrops.com/manifesto/)

</details>
<details><summary>deappel.nl (1)</summary>

- [CAMP: In Cameras Res, de Appel archive](https://www.deappel.nl/en/archive/events/996-camp-in-cameras-res)

</details>
<details><summary>decrypt.co (1)</summary>

- [Beeple Made Robot Dogs With Musk, Zuckerberg, and Warhol Heads That Poop NFTs - Decrypt](https://decrypt.co/351080/beeple-made-robot-dogs-with-musk-zuckerberg-and-warhol-heads-that-poop-nfts)

</details>
<details><summary>delfinafoundation.com (2)</summary>

- [In Conversation: Manauara Clandestina and Victoria Sin – Delfina Foundation](https://www.delfinafoundation.com/platform/in-conversation-manauara-clandestina-and-victoria-sin/)
- [Manauara Clandestina – Delfina Foundation residency](https://www.delfinafoundation.com/in-residence/manauara-clandestina/)

</details>
<details><summary>dennygallery.com (3)</summary>

- [Live Study, Denny Gallery](https://dennygallery.com/?p=6695)
- [Michael Mandiberg \| Timeframe, Denny Dimin Gallery, 2021](https://dennygallery.com/?p=8406)
- [Watch an Artist Paint Every Assistant They've Ever Had (Artsy, 2019; repost on Denny Gallery)](https://dennygallery.com/news/michael-mandiberg-in-artsy/)

</details>
<details><summary>dentsu-ho.com (3)</summary>

- ['The Global Standard is Simplicity' neurowear Roundtable Discussion: Part 1 (Dentsu-ho, 2014)](https://dentsu-ho.com/en/articles/610)
- [Blog → Twitter → Like! → Brain? (Dentsu-ho, 2013, English)](https://dentsu-ho.com/en/articles/193)
- [ブログ→ツイッター→いいね！→脳？ (Dentsu-ho, 2013, Japanese original)](https://dentsu-ho.com/articles/193)

</details>
<details><summary>desertx.org (1)</summary>

- [Desert X – Manal AlDowayan, Desert X AlUla 2020](https://desertx.org/dx/desert-x-alula-2020/manal-aldowayan)

</details>
<details><summary>designboom.com (3)</summary>

- [Kat Barandy, dance and architecture unite with luminous projections (designboom, 11 November 2024)](https://www.designboom.com/art/brendan-fernandes-build-up-house-mart-chicago-installation-11-11-2024/)
- [nancy baker cahill's AR hybrid creature soars and evolves across new york's cityscape, designboom, 2023](https://www.designboom.com/art/nancy-baker-cahill-ar-hybrid-creature-evolves-across-new-york-cityscape-cento-whitney-museum-of-american-art-09-26-2023/)
- [robotic bird by korean artist duo erases its own footprints as social commentary — designboom, 25 Feb 2026 (reader submission)](https://www.designboom.com/art/robotic-bird-installation-sand-diorama-footprints-social-commentary/)

</details>
<details><summary>desvirtual.com (1)</summary>

- [Odiolândia (Hateland) - Giselle Beiguelman (artist's website)](https://www.desvirtual.com/project/odiolandia-hateland/?dv_lang=en)

</details>
<details><summary>dev.motionographer.com (1)</summary>

- [Arev Manoukian: Nuit Blanche, Motionographer (Justin Cone), 2010](https://dev.motionographer.com/2010/02/10/arev-manoukian-nuit-blanche/)

</details>
<details><summary>deweyhagborg.com (1)</summary>

- [Stranger Visions, deweyhagborg.com](https://deweyhagborg.com/projects/stranger-visions)

</details>
<details><summary>dezeen.com (1)</summary>

- [Movie: OpenSurgery DIY surgical robot by Frank Kolkman, Dezeen, 2015](https://www.dezeen.com/2015/08/10/movie-frank-kolkman-hacks-3d-printer-diy-surgical-robot-open-surgery/)

</details>
<details><summary>diariodecuyo.com.ar (1)</summary>

- ['Siento que necesitamos este tipo de historias' - Diario de Cuyo, 22 July 2025](https://www.diariodecuyo.com.ar/edicionimpresa/siento-que-necesitamos-este-tipo-de-historias-1751194.html)

</details>
<details><summary>digicult.it (2)</summary>

- [Nicolas Bernier: between frequencies and dichotomies, Digicult, 2013](http://www.digicult.it/news/ars-electronica-prize-winners-nicolas-bernier-between-frequencies-and-dichotomies/)
- [Quayola & Memo Akten: Forms. Something about Life, at Ars Electronica Prix 2013 — Digicult](https://digicult.it/news/quayola-and-memo-atken-forms-something-about-life-at-ars-electronica-prix-2013/)

</details>
<details><summary>digitalartarchive.siggraph.org (1)</summary>

- [Wonbin Yang: Species Series - ACM SIGGRAPH Art Archive (SIGGRAPH Asia 2012)](https://digitalartarchive.siggraph.org/?p=21402)

</details>
<details><summary>dingdingding.org (1)</summary>

- [An interview with Jonathan Torres Rodríguez, Ding Magazine](https://dingdingding.org/issue-5/1-interview-with-jonathan-torres-rodriguez/)

</details>
<details><summary>dinoj-m.carrd.co (1)</summary>

- [Dinoj Mahendranathan, artist website](https://dinoj-m.carrd.co/)

</details>
<details><summary>directorsnotes.com (1)</summary>

- [Shelter - Directors Notes](https://directorsnotes.com/2012/10/01/shelter/)

</details>
<details><summary>dismagazine.com (1)</summary>

- [Returning to the site of protest (Yoshua Okón, Oracle), DIS Magazine](https://dismagazine.com/discussion/77324/yoshua-okon-oracle/)

</details>
<details><summary>diyconspiracy.net (1)</summary>

- [Not Your World Music, review, DIY Conspiracy](http://diyconspiracy.net/not-your-world-music/)

</details>
<details><summary>docubase.mit.edu (3)</summary>

- [African Space Makers (MIT Docubase)](https://docubase.mit.edu/project/african-space-makers/)
- [MIT Docubase, 'The Other Dakar'](https://docubase.mit.edu/project/the-other-dakar/)
- [Nairobi Berries – MIT Docubase](https://docubase.mit.edu/project/nairobi-berries)

</details>
<details><summary>documenta14.de (1)</summary>

- [Sammy Baloji – documenta 14 (pool source)](https://www.documenta14.de/en/artists/13531/sammy-baloji)

</details>
<details><summary>documentjournal.com (1)</summary>

- [Joshua Serafin - Document Journal (2024)](https://www.documentjournal.com/2024/07/joshua-serafin-art-filipino-void-performance-video-ancestry-indigenous/)

</details>
<details><summary>doi.org (1)</summary>

- [Whitley, 'Today and yesterday, forever: Negotiating time and space in the art of Mame-Diarra Niang and Dineo Seshee Bopape', Technoetic Arts 12(2–3), 2014](https://doi.org/10.1386/tear.12.2-3.175_1)

</details>
<details><summary>doublesquare.com.tw (1)</summary>

- [Double Square Gallery – wins the 17th Taishin Visual Arts Award](https://doublesquare.com.tw/en/news/post/su-huiyu-s-the-glamorous-boys-of-tang-1985-chui-kang-chien-wins-the-17th-taishin-visual-arts-award)

</details>
<details><summary>dragonframe.com (1)</summary>

- [The Full Story by Daisy Jacobs - Dragonframe blog](https://www.dragonframe.com/blog/the-full-story-by-daisy-jacobs/)

</details>
<details><summary>drive.google.com (1)</summary>

- [Circle of Rhythms: An Interactive Sound Installation, project book (PDF, Google Drive)](https://drive.google.com/file/d/1e2SClZ-Lkg8fXgXgZ6tIOts_oaugoZV3/view?usp=sharing)

</details>
<details><summary>drlib.lasalle.edu.sg (1)</summary>

- [Lauren Reid, 'Peel Slowly and See' (essay on Ang's practice), LASALLE repository (PDF)](https://drlib.lasalle.edu.sg/504/1/Lauren%20Reid.pdf)

</details>
<details><summary>drolesdobjets25.sciencesconf.org (1)</summary>

- [Soft Collision – Drôles d'objets 2025 conference abstract (PDF)](https://drolesdobjets25.sciencesconf.org/594220/document)

</details>
<details><summary>dwbowen.com (1)</summary>

- [tele-present water — David Bowen](https://www.dwbowen.com/telepresentwater)

</details>
<details><summary>dxarts.washington.edu (1)</summary>

- [We are All Made of Light, by Maja Petric, at MadArt Studio — DXARTS, University of Washington](https://dxarts.washington.edu/news/2018/10/17/we-are-all-made-light-maja-petric-madart-studio-seattle)

</details>
<details><summary>dyslex6.com (3)</summary>

- [A long overdue acknowledgement of cultural appropriation — Alexis O'Hara (artist's site)](http://www.dyslex6.com/lx6/a-long-overdue-acknowledgement-of-cultural-appropriation/)
- [Artist statement, About page, artist's site (dyslex6.com)](http://www.dyslex6.com/lx6/about/)
- [SQUEEEEQUE – SPEAKERDOME — Alexis O'Hara (artist's site)](http://www.dyslex6.com/lx6/projects/squeeeeque-the-improbable-igloo/)

</details>
<details><summary>e-flux.com (24)</summary>

- [Basim Magdy: Flickers of Utopia (screening, e-flux Screening Room, January 30, 2024)](https://www.e-flux.com/events/582110/basim-magdy-flickers-of-utopia)
- [Colomboscope 2026, Rhythm Alliances, e-flux Criticism](https://www.e-flux.com/criticism/6782386/colomboscope-2026-rhythm-alliances)
- [Dhaka Art Summit 2014 — e-flux announcement](https://www.e-flux.com/announcements/31941/dhaka-art-summit-2014/)
- [Dispatch: Dhaka Art Summit — e-flux Criticism](https://www.e-flux.com/reviews/dispatch-dhaka-art-summit/)
- [e-flux announcement, Digital Imaginaries – Africas in Production (2018)](https://www.e-flux.com/announcements/228240/digital-imaginaries-africas-in-production)
- [e-flux Announcements – Claudia Pagès Rabal: Paper Tears](https://www.e-flux.com/announcements/6787056/claudia-pag-s-rabalpaper-tears)
- [e-flux Criticism — 15th Gwangju Biennale, 'Pansori: A Soundscape of the 21st Century'](https://www.e-flux.com/criticism/632242/15th-gwangju-biennale-pansori-a-soundscape-of-the-21st-century)
- [e-flux – Zineb Sedira: Dreams Have No Titles (French Pavilion)](https://www.e-flux.com/announcements/438576/zineb-sediradreams-have-no-titles/)
- [e-flux — Fermata: Hong Kong in Venice (Hong Kong Museum of Art)](https://www.e-flux.com/announcements/6788495/fermata-hong-kong-in-venice)
- [e-flux — Jonathas de Andrade: With the Heart Coming Out of the Mouth](https://www.e-flux.com/announcements/457150/jonathas-de-andradewith-the-heart-coming-out-of-the-mouth/)
- [Flickers of Utopia: A Conversation (e-flux Notes, 2024)](https://www.e-flux.com/notes/618055/flickers-of-utopia-a-conversation)
- [History Has Failed Us, but No Matter – e-flux announcement](https://www.e-flux.com/announcements/223088/history-has-failed-us-but-no-matter/)
- [Ho Tzu Nyen: Night Charades (e-flux announcement)](https://www.e-flux.com/announcements/658965/ho-tzu-nyennight-charades)
- [Hours and Hours of Inactivity / Bani Abidi: An Unforeseen Situation, n.b.k., e-flux announcement, 2017](https://www.e-flux.com/announcements/83267/hours-and-hours-of-inactivitybani-abidian-unforeseen-situation/)
- [Jesper Just’s Intercourses, e-flux announcement (Danish Arts Council)](https://www.e-flux.com/announcements/32711/jesper-just-s-intercourses)
- [John Palmesino and Ann-Sofi Rönnskog, When Above, e-flux Architecture](https://www.e-flux.com/architecture/oceans/331872/when-above/)
- [long time, lung time continuuuum!!! (a conver-something) - e-flux announcement](https://www.e-flux.com/announcements/585625/long-time-lung-time-continuuuum-a-conver-something/)
- [Morehshin Allahyari: She Who Sees The Unknown: The Laughing Snake, e-flux / Upfor Gallery (2018)](https://www.e-flux.com/announcements/216308/morehshin-allahyari-she-who-sees-the-unknown-the-laughing-snake)
- [Muhannad Shono: The Teaching Tree, Saudi Arabia Pavilion at the Venice Biennale (announcement)](https://www.e-flux.com/announcements/451107/muhannad-shono-the-teaching-tree)
- [Pavlina Vagioni: Oikeiōsis (Kinship), e-flux announcement](https://www.e-flux.com/announcements/6787233/pavlina-vagionioikei-sis-kinship)
- [SEA STATE — e-flux announcement (National Arts Council, Singapore)](https://www.e-flux.com/announcements/29914/sea-state)
- [Sean O'Toole, 'On Nolan Oswald Dennis', e-flux Criticism (2025)](https://www.e-flux.com/criticism/651289/on-nolan-oswald-dennis)
- [Tejal Shah: UNBECOMING — e-flux announcement (Kunsthaus Hamburg, 2017)](https://www.e-flux.com/announcements/152732/tejal-shahunbecoming/)
- [The Pavilion of Turkey at the 54th Venice Biennale: Ayşe Erkmen, Plan B (announcement)](https://www.e-flux.com/announcements/35555/the-pavilion-of-turkey-at-the-54th-venice-biennale/)

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
<details><summary>electricalwalks.org (1)</summary>

- [electricalwalks.org: About](https://electricalwalks.org/about/)

</details>
<details><summary>electricsouth.org (1)</summary>

- [Electric South, productions 2017](https://electricsouth.org/production_year/2017/)

</details>
<details><summary>electronicgroove.com (1)</summary>

- [Ryoichi Kurokawa interview, Electronic Groove (2022)](https://electronicgroove.com/ryoichi-kurokawa-interview/)

</details>
<details><summary>elephant.art (2)</summary>

- [Elephant – 5 Questions with Cheng Ran](https://elephant.art/5-questions-cheng-ran)
- [Hãhãwpuá Pavilion’s Artist Glicéria Tupinambá: “So Much of Our Heritage is Trapped on European Ground”, Elephant](https://elephant.art/hahawpua-pavilions-artist-gliceria-tupinamba-so-much-of-our-heritage-is-trapped-on-european-ground)

</details>
<details><summary>eliascrespin.net (1)</summary>

- [L'Onde du Midi au Louvre — eliascrespin.net](https://www.eliascrespin.net/londe-du-midi/)

</details>
<details><summary>elizabethprice.site (1)</summary>

- [THE WOOLWORTHS CHOIR OF 1979, elizabethprice.site](https://elizabethprice.site/the-woolworths-choir-of-1979)

</details>
<details><summary>ellipses.org.za (1)</summary>

- [The Playa Bagdad/SpaceX Conundrum (Ellipses Journal for Creative Research)](https://www.ellipses.org.za/article/playa-bagdad-spacex-conundrum)

</details>
<details><summary>emare.eu (1)</summary>

- [Unknown Label (2023) / Their Eyes (2025), EMAP — European Media Art Platform (incl. artist talk with werkleitz)](https://emare.eu/works/their-eyes)

</details>
<details><summary>emergentartspace.org (1)</summary>

- [Interview: Yintzu Huang \| Hsinchu, Taiwan, by Maria Maita Keppeler, Emergent Art Space (2015)](https://emergentartspace.org/forum/29871)

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
<details><summary>en.wikipedia.org (61)</summary>

- [Anida Yoeu Ali - Wikipedia](https://en.wikipedia.org/wiki/Anida_Yoeu_Ali)
- [Anthony Azekwoh (Wikipedia)](https://en.wikipedia.org/wiki/Anthony_Azekwoh)
- [Aram Bartholl - Wikipedia](https://en.wikipedia.org/wiki/Aram_Bartholl)
- [Bani Abidi, Wikipedia](https://en.wikipedia.org/wiki/Bani_Abidi)
- [Basel Abbas and Ruanne Abou-Rahme, Wikipedia](https://en.wikipedia.org/wiki/Basel_Abbas_and_Ruanne_Abou-Rahme)
- [Camille Henrot - Wikipedia](https://en.wikipedia.org/wiki/Camille_Henrot)
- [Cassie McQuater, Wikipedia](https://en.wikipedia.org/wiki/Cassie_McQuater)
- [Charles Lim — Wikipedia](https://en.wikipedia.org/wiki/Charles_Lim)
- [Chris Milk - Wikipedia](https://en.wikipedia.org/wiki/Chris_Milk)
- [Constant Dullaart - Wikipedia](https://en.wikipedia.org/wiki/Constant_Dullaart)
- [Daito Manabe, Wikipedia (pool source)](https://en.wikipedia.org/wiki/Daito_Manabe)
- [Devin Kenny, Wikipedia](https://en.wikipedia.org/wiki/Devin_Kenny)
- [Dineo Seshee Bopape – Wikipedia (pool source)](https://en.wikipedia.org/wiki/Dineo_Seshee_Bopape)
- [Dinh Q. Lê – Wikipedia](https://en.wikipedia.org/wiki/Dinh_Q._L%C3%AA)
- [Doug Aitken, Wikipedia](https://en.wikipedia.org/wiki/Doug_Aitken)
- [Ed Atkins - Wikipedia](https://en.wikipedia.org/wiki/Ed_Atkins)
- [Elizabeth Price (artist) – Wikipedia](https://en.wikipedia.org/wiki/Elizabeth_Price_(artist))
- [Glenda León - Wikipedia](https://en.wikipedia.org/wiki/Glenda_Le%C3%B3n)
- [Guy Ben-Ner, Wikipedia](https://en.wikipedia.org/wiki/Guy_Ben-Ner)
- [Haroon Mirza – Wikipedia](https://en.wikipedia.org/wiki/Haroon_Mirza)
- [Heather Dewey-Hagborg, Wikipedia](https://en.wikipedia.org/wiki/Heather_Dewey-Hagborg)
- [Ho Tzu Nyen (Wikipedia, pool source)](https://en.wikipedia.org/wiki/Ho_Tzu_Nyen)
- [Ivan Cash, Wikipedia](https://en.wikipedia.org/wiki/Ivan_Cash)
- [Jalila Essaïdi – Wikipedia](https://en.wikipedia.org/wiki/Jalila_Essa%C3%AFdi)
- [Jesper Just – Wikipedia](https://en.wikipedia.org/wiki/Jesper_Just)
- [Jess Johnson, Wikipedia](https://en.wikipedia.org/wiki/Jess_Johnson)
- [Jillian Mayer, Wikipedia](https://en.wikipedia.org/wiki/Jillian_Mayer)
- [Jo Thomas — Wikipedia](https://en.wikipedia.org/wiki/Jo_Thomas)
- [Jumana Manna (Wikipedia)](https://en.wikipedia.org/wiki/Jumana_Manna)
- [Korakrit Arunanondchai — Wikipedia](https://en.wikipedia.org/wiki/Korakrit_Arunanondchai)
- [Kwaku Ananse (film) - Wikipedia](https://en.wikipedia.org/wiki/Kwaku_Ananse_(film))
- [Lara Baladi - Wikipedia](https://en.wikipedia.org/wiki/Lara_Baladi)
- [Larissa Sansour, Wikipedia](https://en.wikipedia.org/wiki/Larissa_Sansour)
- [Laure Prouvost - Wikipedia](https://en.wikipedia.org/wiki/Laure_Prouvost)
- [Lumen Prize – Wikipedia (pool source)](https://en.wikipedia.org/wiki/Lumen_Prize)
- [Morehshin Allahyari, Wikipedia](https://en.wikipedia.org/wiki/Morehshin_Allahyari)
- [Muhannad Shono, Wikipedia](https://en.wikipedia.org/wiki/Muhannad_Shono)
- [Nalini Malani — Wikipedia](https://en.wikipedia.org/wiki/Nalini_Malani)
- [Natalie Bookchin, Wikipedia](https://en.wikipedia.org/wiki/Natalie_Bookchin)
- [Nguyen Trinh Thi – Wikipedia](https://en.wikipedia.org/wiki/Nguyen_Trinh_Thi)
- [Osinachi (digital artist) — Wikipedia](https://en.wikipedia.org/wiki/Osinachi_(digital_artist))
- [Prix Ars Electronica — Wikipedia (pool source)](https://en.wikipedia.org/wiki/Prix_Ars_Electronica)
- [Ragnar Kjartansson (performance artist) - Wikipedia](https://en.wikipedia.org/wiki/Ragnar_Kjartansson_(performance_artist))
- [Rania Stephan, Wikipedia](https://en.wikipedia.org/wiki/Rania_Stephan)
- [Ryan Trecartin - Wikipedia](https://en.wikipedia.org/wiki/Ryan_Trecartin)
- [Shiro Takatani — Wikipedia](https://en.wikipedia.org/wiki/Shiro_Takatani)
- [STARTS Prize, Wikipedia (pool source)](https://en.wikipedia.org/wiki/STARTS_Prize)
- [Susan Philipsz - Wikipedia](https://en.wikipedia.org/wiki/Susan_Philipsz)
- [Tayeba Begum Lipi — Wikipedia](https://en.wikipedia.org/wiki/Tayeba_Begum_Lipi)
- [United Visual Artists - Wikipedia](https://en.wikipedia.org/wiki/United_Visual_Artists)
- [Wafaa Bilal, Wikipedia (section The 3rd I)](https://en.wikipedia.org/wiki/Wafaa_Bilal)
- [Wangechi Mutu - Wikipedia](https://en.wikipedia.org/wiki/Wangechi_Mutu)
- [Warwick Thornton — Wikipedia](https://en.wikipedia.org/wiki/Warwick_Thornton)
- [Wikipedia – Manal AlDowayan](https://en.wikipedia.org/wiki/Manal_AlDowayan)
- [Wikipedia — Elias Crespin](https://en.wikipedia.org/wiki/Elias_Crespin)
- [Wikipedia: Japan Media Arts Festival (pool source)](https://en.wikipedia.org/wiki/Japan_Media_Arts_Festival)
- [William Kentridge, Wikipedia](https://en.wikipedia.org/wiki/William_Kentridge)
- [Yto Barrada - Wikipedia](https://en.wikipedia.org/wiki/Yto_Barrada)
- [Zach Blas — Wikipedia (pool source)](https://en.wikipedia.org/wiki/Zach_Blas)
- [Zanele Muholi - Wikipedia](https://en.wikipedia.org/wiki/Zanele_Muholi)
- [Zina Saro-Wiwa - Wikipedia](https://en.wikipedia.org/wiki/Zina_Saro-Wiwa)

</details>
<details><summary>engadget.com (1)</summary>

- [Experience the horror of a Syrian air raid in 'Hero', Engadget, 2018](https://www.engadget.com/2018-04-20-hero-syria-air-raid-vr-tribeca.html)

</details>
<details><summary>english.cambodiadaily.com (1)</summary>

- [A Curious Critter - The Cambodia Daily](https://english.cambodiadaily.com/?p=74562)

</details>
<details><summary>epidemic.net (1)</summary>

- [Toposcan — Epidemic (Takatani's production company), series page](https://epidemic.net/en/art/takatani/proj/toposcan.html)

</details>
<details><summary>eprints.soas.ac.uk (1)</summary>

- [Panpan Yang, Xu Bing's The Character of Characters and the Possibilities of Calligraphic Animation (SOAS Research Online)](https://eprints.soas.ac.uk/42554)

</details>
<details><summary>erasedtapes.com (3)</summary>

- [Behind the Tapes: Rival Consoles in conversation with Daniel Brandt - Erased Tapes](https://www.erasedtapes.com/editorials/behind-the-tapes-rival-consoles-in-conversation-with-daniel-brandt)
- [Daniel Brandt - Erased Tapes artist page](https://erasedtapes.com/artist/daniel-brandt)
- [Daniel Brandt to premiere live A/V cinema rave at the Barbican - Erased Tapes](https://erasedtapes.com/news/2024-12-09/daniel-brandt-to-premiere-live-a-v-cinema-rave-at-the-barbican-409)

</details>
<details><summary>everyware.kr (2)</summary>

- ['Soak, Dye in light.' by everyware (2011), everyware.kr portfolio](http://everyware.kr/home/portfolio/soak/)
- [everyware - about / CV](https://everyware.kr/home/cv/)

</details>
<details><summary>ex-is.org (1)</summary>

- [Pinktoned — EXiS](https://ex-is.org/ex-now/pinktoned)

</details>
<details><summary>experimenter.in (1)</summary>

- [Bani Abidi, Experimenter](https://experimenter.in/artists/45-bani-abidi/overview/)

</details>
<details><summary>experiments.withgoogle.com (1)</summary>

- [Experiments with Google: Norman (November 2017)](https://experiments.withgoogle.com/norman)

</details>
<details><summary>expreso.ec (1)</summary>

- [Óscar Santillán invita a "escuchar al planeta" en su muestra inmersiva en Quito (Expreso)](https://www.expreso.ec/ocio/oscar-santillan-invita-escuchar-al-planeta-en-su-muestra-inmersiva-en-quito-262886.html)

</details>
<details><summary>extinction.zkm.de (1)</summary>

- [NoSearchBar, Net Art Extinction Timeline, ZKM](https://extinction.zkm.de/artworks/nosearchbar/)

</details>
<details><summary>fact.co.uk (3)</summary>

- [Coffee Machine (2023), FACT Liverpool](https://www.fact.co.uk/artwork/coffee-machine-2023)
- [Cosmotechnics: Atractor Studio + Semantica (2024) — FACT Liverpool](https://fact.co.uk/artwork/cosmotechnics-atractor-studio-semantica)
- [The Moon Goose Analogue: Lunar Migration Bird Facility (2011), FACT Liverpool](https://www.fact.co.uk/artwork/the-moon-goose-analogue-2011-2012)

</details>
<details><summary>factmag.com (1)</summary>

- [Richard Mosse interview with Hans Ulrich Obrist, FACT Magazine](https://factmag.com/2023/12/08/richard-mosse-interview)

</details>
<details><summary>fadmagazine.com (3)</summary>

- [Conversations with the Creators Shaping the world of Digital Art – Maja Petric — FAD Magazine](https://fadmagazine.com/2025/05/29/conversations-with-the-creators-shaping-the-world-of-digital-art-maja-petric)
- [FAD Magazine: Osinachi's NFT series Different Shades of Water on show at 1-54](https://fadmagazine.com/?p=273205)
- [Hayward Gallery presents Heecheon Kim: Double Poser — FAD Magazine](https://fadmagazine.com/?p=299783)

</details>
<details><summary>falter.at (1)</summary>

- [Falter – KI-kritische Kunst mit gender bias (review, 30.09.2025)](https://www.falter.at/zeitung/20250930/ki-kritische-kunst-mit-gender-bias)

</details>
<details><summary>fashioninfilm.com (1)</summary>

- [Tray Tray Ko — Fashion in Film Festival](https://www.fashioninfilm.com/films/tray-tray-ko)

</details>
<details><summary>fatosustek.com (1)</summary>

- [Fatos Ustek, Plan B (ENG) – Ayse Erkmen](https://fatosustek.com/plan-b-eng-ayse-erkmen)

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
<details><summary>ffur.de (2)</summary>

- [MGA description, ffur.de](http://www.ffur.de/mga/mga-intro.html)
- [The Moon Goose Analogue (MGA), ffur.de (artist's site)](http://www.ffur.de/mga/index.html)

</details>
<details><summary>field-0.xyz (3)</summary>

- [Care at the Water's Edge — Reservoir Project / Water Campaign (field-0 site)](https://field-0.xyz/reservoir-project)
- [Drifting Bodies & The Humming of the Power Grid — Singapore Biennale 2025 (field-0 site)](https://field-0.xyz/singapore-biennale-2025)
- [How Much Wattage Is One Handbreadth of Water? — Storefront for Art and Architecture, 2025 (field-0 site)](https://field-0.xyz/how-much-wattage-is-one-handbreadth-of-water)

</details>
<details><summary>fieldofvision.org (1)</summary>

- [Field of Vision: Best of Luck with the Wall](https://fieldofvision.org/best-of-luck-with-the-wall)

</details>
<details><summary>filmindependent.org (1)</summary>

- [Film Independent: The Portal: VR Fan Reggie Watts Goes 'Runnin'' (panel report)](https://www.filmindependent.org/blog/the-portal-vr-fan-reggie-watts-goes-runnin-in-groundbreaking-new-music-video/)

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
<details><summary>flash---art.com (2)</summary>

- [Luba Elliott, Mario Klingemann — Flash Art (5 Dec 2017)](https://flash---art.com/article/mario-klingemann/)
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
<details><summary>fragment.in (3)</summary>

- [Displuvium (circular stone edition) — Fragmentin](https://fragment.in/artworks/displuvium-nov/)
- [Displuvium (circular weathering steel edition, Mudac) — Fragmentin](https://fragment.in/artworks/displuvium-circular/)
- [Displuvium (weathering steel oval edition) — Fragmentin](https://fragment.in/artworks/displuvium/)

</details>
<details><summary>franciscolopez.net (1)</summary>

- [Francisco López, official website](https://www.franciscolopez.net/)

</details>
<details><summary>frankkolkman.nl (1)</summary>

- [Frank Kolkman, frankkolkman.nl](http://www.frankkolkman.nl)

</details>
<details><summary>freight.cargo.site (1)</summary>

- [PAPER – in conversation with Helena Uambembe 2024/2025 (Nisha Merit)](https://freight.cargo.site/m/J2257473008552503311962688224423/Helena-Uambembe---Paper-1.pdf)

</details>
<details><summary>freshartinternational.com (1)</summary>

- [Turning Analog Technology into Sound Sculpture, Fresh Art International (2018)](https://freshartinternational.com/2018/07/30/magdi-mostafa-analog-technology-vibrating-sound-sculptures/)

</details>
<details><summary>frieze.com (1)</summary>

- [Ryan Trecartin: in conversation (Katie Kitamura and Hari Kunzru) - frieze](https://frieze.com/article/ryan-trecartin-conversation)

</details>
<details><summary>fujihata.jp (1)</summary>

- [Home of Masaki Fujihata](http://www.fujihata.jp/)

</details>
<details><summary>funeralplay.com (1)</summary>

- [FuneralPlay (project website)](https://www.funeralplay.com/)

</details>
<details><summary>furendai.squarespace.com (1)</summary>

- [Furen Dai – Language Producing Factory (artist's site)](https://furendai.squarespace.com/language-producing-factory)

</details>
<details><summary>fxguide.com (1)</summary>

- [1st SORA music video (fxguide)](https://www.fxguide.com/?p=419437)

</details>
<details><summary>fzine.com (1)</summary>

- [This Is Not Your Standard Art Festival — Singapore Biennale 2025 guide (fzine)](https://www.fzine.com/culture/singapore-biennale-2025-guide)

</details>
<details><summary>g-mark.org (1)</summary>

- [The East Japan Earthquake Archive - Good Design Award 2013 (Best 100 / Reconstruction Design Award)](https://www.g-mark.org/en/gallery/winners/9d9a3e70-803d-11ed-af7e-0242ac130002)

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
<details><summary>galerieschenk.de (1)</summary>

- [Magdi Mostafa, other exhibitions, Galerie Schenk](https://galerieschenk.de/magdi-mostafa-other-exhibitions)

</details>
<details><summary>galeriethoman.com (1)</summary>

- [ongoing, individual adaptability – 03, Devin Kenny, Galerie Elisabeth & Klaus Thoman (with interview)](https://www.galeriethoman.com/?p=26155)

</details>
<details><summary>galleriacontinua.com (1)</summary>

- [Leila Alaoui - archive - Galleria Continua](https://www.galleriacontinua.com/artists/leila-alaoui-3/archive)

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
<details><summary>generazionecritica.it (1)</summary>

- [Eva & Franco Mattes, interview, Generazione Critica (2022)](https://www.generazionecritica.it/en/interviews/eva-franco-mattes/)

</details>
<details><summary>getty.edu (1)</summary>

- [In the Algorithm’s Eyes, “We Are Already Plants” — Getty News (Q&A)](https://www.getty.edu/news/bio-artist-spela-petric-interview-q-and-a)

</details>
<details><summary>gibca.se (1)</summary>

- [GIBCA 2025 – Helena Uambembe](https://www.gibca.se/en/gibca/gibca-2025-2/artists/helena-uambembe)

</details>
<details><summary>glenda-leon.com (2)</summary>

- [Música de las esferas (light box version), glenda-leon.com](https://www.glenda-leon.com/musica-de-las-esferas-2/)
- [Música de las esferas \| Music of the spheres, glenda-leon.com](https://www.glenda-leon.com/musica-de-las-esferas/)

</details>
<details><summary>goodman-gallery.com (5)</summary>

- [biko.nomzamo (2024), Goodman Gallery artwork page ('Biko dialogues' series)](https://goodman-gallery.com/artists/nolan-oswald-dennis/bikonomzamo-154614)
- [Goodman Gallery – Zineb Sedira: 'Culture is a way of resisting'](https://goodman-gallery.com/news/zineb-sedira-culture-is-a-way-of-resisting)
- [Kudzanai Chiurai - Goodman Gallery](https://www.goodman-gallery.com/artists/kudzanai-chiurai)
- [Love Story, Goodman Gallery Johannesburg, 2018 (press release)](https://www.goodman-gallery.com/exhibitions/love-story-candice-breitz)
- [Options – Nolan Oswald Dennis, Goodman Gallery (2019)](https://goodman-gallery.com/exhibitions/options-nolan-oswald-dennis)

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
<details><summary>grimmgallery.com (2)</summary>

- [Claudia Martínez Garay: I WILL OUTLIVE YOU, GRIMM New York, 2018 (exhibition page)](https://grimmgallery.com/exhibitions/47-claudia-martinez-garay-i-will-outlive-you/)
- [ÑUQA KAUSAKUSAQ QHEPAYKITAPAS / I WILL OUTLIVE YOU, 2017, GRIMM (work page)](https://grimmgallery.com/artists/51-claudia-martinez-garay/works/12057-claudia-martinez-garay-nuqa-kausakusaq-qhepaykitapas-i-will-outlive-you-2017)

</details>
<details><summary>guanaquerx.com (1)</summary>

- [Guanaquerx (project website)](https://guanaquerx.com/)

</details>
<details><summary>guybenary.com (2)</summary>

- [Guy Ben-Ary (artist site)](https://www.guybenary.com/)
- [In Potentia — Guy Ben-Ary](https://www.guybenary.com/projects/in-potentia.html)

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
<details><summary>hammer.ucla.edu (3)</summary>

- [Gabriela Ruiz — Hammer Museum, Made in L.A. 2025](https://hammer.ucla.edu/made-la-2025/gabriela-ruiz)
- [Hammer Projects: Yoshua Okón, Hammer Museum (with essay by John C. Welchman)](https://hammer.ucla.edu/exhibitions/2011/hammer-projects-yoshua-okon)
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
<details><summary>heath.tw (1)</summary>

- [Alice Ko, 'The Translator and the Medium: A Conversation with Jane Jin Kaisen', No Man's Land](https://www.heath.tw/nml-article/the-translator-and-the-medium-a-conversation-with-jane-jin-kaisen/?lang=en)

</details>
<details><summary>hek.ch (4)</summary>

- [Artworks — HEK (Haus der Elektronischen Künste) Basel collection](https://hek.ch/en/collection/artworks)
- [Displuvium — HeK collection](https://hek.ch/en/collection/artworks/displuvium)
- [TAFAA – Fertility Device (Uncanny Valley) – HEK collection](https://www.hek.ch/en/collection/artworks/tafaa-fertility-device-uncanny-valley)
- [Transits – HEK collection](https://hek.ch/en/collection/artworks/transits)

</details>
<details><summary>herald.dawn.com (1)</summary>

- [Life is infinitely more beautiful than art: Bani Abidi, Herald (Dawn), 2016](https://herald.dawn.com/news/1153492/life-is-infinitely-more-beautiful-than-art-bani-abidi)

</details>
<details><summary>heritage.sg (1)</summary>

- [Singapore Night Festival 2025 media release (National Heritage Board)](https://www.heritage.sg/sgnightfest/-/media/snf2025/press-release/media-release-dive-into-island-nights-at-singapore-night-festival-2025-where-stories-of-island-life-come-alive-as-of-23-july.pdf)

</details>
<details><summary>hfa.ucsb.edu (1)</summary>

- [Mojo: When Black Identity Shapes the Earth — UCSB HFA](https://hfa.ucsb.edu/news-entries/2023/1/30/black-ecology-event)

</details>
<details><summary>hifructose.com (1)</summary>

- [Jess Johnson, Simon Ward Bring 'TERMINUS' to Heide Museum, Hi-Fructose, 2019](https://hifructose.com/2019/11/06/jess-johnson-simon-ward-bring-terminus-to-heide-museum/)

</details>
<details><summary>high.org (1)</summary>

- [Ragnar Kjartansson: The Visitors - High Museum of Art](https://high.org/exhibition/ragnar-kjartansson-the-visitors/)

</details>
<details><summary>highart.fr (1)</summary>

- [High Art, Paris – Cooper Jacoby artist page](https://highart.fr/artists/cooper-jacoby/)

</details>
<details><summary>highlike.org (1)</summary>

- [Dmitry & Elena Kawarga, Down with Wrestlers with Systems and Mental Nonadapters!, highlike.org (FILE festival)](https://highlike.org/dmitry-elena-kawarga/)

</details>
<details><summary>history.siggraph.org (6)</summary>

- ["Making of Nuit Blanche" by Manoukian, ACM SIGGRAPH History Archives (SIGGRAPH 2010 Computer Animation Festival)](https://history.siggraph.org/?p=75806)
- ['Shelter' by Burton - ACM SIGGRAPH History Archives](https://history.siggraph.org/?p=225198)
- [Mariela Yeregui, Miguel Grassi: Octópodos Sisíficos, ACM SIGGRAPH History Archives (SIGGRAPH 2017)](https://history.siggraph.org/?p=18504)
- [Ryu Furusawa: Mid Tide #3 - SIGGRAPH Asia 2024 Art Gallery (ACM SIGGRAPH History Archives)](https://history.siggraph.org/?p=192874)
- [Weidi Zhang, Donghao Ren: Cangjie's Poetry - SIGGRAPH 2021 Art Gallery (ACM SIGGRAPH History Archives)](https://history.siggraph.org/?p=68568)
- [“African Space Makers” by Kirchhof, Cavallo Faras and Afande (ACM SIGGRAPH History Archives)](https://history.siggraph.org/experience/african-space-makers-by-kirchhof-cavallo-faras-and-afande)

</details>
<details><summary>history.sundance.org (4)</summary>

- [Grisaille, Sundance Institute Online Archives](https://history.sundance.org/films/10643/grisaille)
- [Interlooped - Sundance Institute Online Archives](https://history.sundance.org/films/10556/interlooped)
- [Iyeza - Sundance Institute Archives (2013 Sundance Film Festival)](https://history.sundance.org/films/7660/iyeza)
- [Sundance Institute archive: Runnin' (2019, New Frontier Exhibitions)](https://history.sundance.org/films/10555/runnin)

</details>
<details><summary>hivos.org (1)</summary>

- [Meet Dr. Faras who is exploring a new era of storytelling (Hivos)](https://hivos.org/meet-dr-faras-who-is-exploring-a-new-era-of-storytelling/)

</details>
<details><summary>hk.art.museum (1)</summary>

- [Scent of Raindrop (2024) — Hong Kong Museum of Art (related earlier work with evaporating water drops on rock)](https://hk.art.museum/en/web/ma/exhibitions-and-events/scent-of-raindrop.html)

</details>
<details><summary>hnfoundation.com (2)</summary>

- [Gabriel Mascaro, EBB AND FLOW (A Onda Trás o Vento Leva), Han Nefkens Foundation](https://www.hnfoundation.com/artists/gabriel-mascaro/ebb-and-flow-(a-onda-trás-o-vento-leva))
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
<details><summary>huismarseille.nl (1)</summary>

- [An Interview with Tejal Shah on Landfill Dance, part of Between the Waves — Huis Marseille](https://huismarseille.nl/interview-tejal-shah/)

</details>
<details><summary>hypebeast.com (1)</summary>

- [The Evolution of Sound and Visual With Nosaj Thing & Daito Manabe, Hypebeast, 2016](https://hypebeast.com/2018/6/exploring-sound-design-through-visuals-with-nosaj-thing-daito-manabe)

</details>
<details><summary>hyperallergic.com (7)</summary>

- [Depicting an Existence So Far Violently and Blaringly Erased (interview) - Hyperallergic, 2012](https://hyperallergic.com/zanele-muholi-interview/)
- [Guy Ben-Ner's Soundtrack, Hyperallergic](https://hyperallergic.com/guy-ben-ner-chicago-soundtrack/)
- [Hyperallergic — Taiwan Presents 'Screen Melancholy: Li Yi-Fan' at the Venice Biennale](https://hyperallergic.com/taiwan-presents-screen-melancholy-li-yi-fan-at-the-venice-biennale/)
- [Joshua Serafin's Living Shrine to Gender Nonconformity - Hyperallergic](https://hyperallergic.com/964512/joshua-serafin-living-shrine-to-gender-nonconformity-cosmological-gangbang/)
- [Khaled Sabsabi’s Art of Collective Becoming – Hyperallergic (interview by Aruna D’Souza)](https://hyperallergic.com/khaled-sabsabis-art-of-collective-becoming/)
- [Mostafa Heddaya, The Sounds of Silence (Hyperallergic, 2013)](https://hyperallergic.com/the-sounds-of-silence/)
- [Somewhere Between Cyber and Real: An Interview with Aram Bartholl (Hyperallergic, 2012)](https://hyperallergic.com/somewhere-between-cyber-and-real-an-interview-with-aram-bartholl/)

</details>
<details><summary>ica.art (1)</summary>

- [Under Construction — artist interview (ICA London)](https://www.ica.art/media/10164.pdf)

</details>
<details><summary>icaphila.org (1)</summary>

- [Ruffneck Constructivists – Institute of Contemporary Art, Philadelphia](https://icaphila.org/exhibitions/ruffneck-constructivists/)

</details>
<details><summary>iclc.toplap.org (1)</summary>

- [ICLC 2023 Catalogue — Paola Torres Núñez del Prado](https://iclc.toplap.org/2023/catalogue/person/torres-nunez-del-prado-paola.html)

</details>
<details><summary>ideas.ted.com (1)</summary>

- [Video: A DNA portrait from a single hair, TED Ideas](https://ideas.ted.com/generating-a-sculpture-from-a-hair-the-work-of-heather-dewey-hagborg/)

</details>
<details><summary>idfa.nl (6)</summary>

- [IDFA — We Are Dead Animals](https://www.idfa.nl/en/film/2199a031-3ed2-4e9d-8701-0a0cef4ceebe/we-are-dead-animals)
- [In 36,000 Ways (Site-Specific Installation) - IDFA Archive, IDFA 2025](https://www.idfa.nl/en/film/71f50066-72ab-4326-ac6b-80aa0fbc693a/in-36000-ways-(site-specific-installation))
- [Nothing to See Here - IDFA 2025 archive](https://www.idfa.nl/en/film/a03ee71b-1364-4658-923c-1d4b855f8d5c/nothing-to-see-here)
- [Reality Looks Back (2025) \| IDFA Archive](https://www.idfa.nl/en/film/77e673c5-0441-4c2f-9dc2-6b268638c724/reality-looks-back)
- [The Oracle: Ritual for the Future (for humans and non-humans) - IDFA 2025 archive](https://www.idfa.nl/en/film/c3aac403-e1f4-4044-bd52-0801cecb9baa/the-oracle:-ritual-for-the-future-(for-humans-and-non-humans))
- [The Rift (2025) - IDFA Archive](https://www.idfa.nl/en/film/463a729b-073d-4142-99bf-8f200657bc60/the-rift)

</details>
<details><summary>iefspincemaille.com (1)</summary>

- [There is the sun - iefspincemaille.com](https://iefspincemaille.com/there-is-the-sun)

</details>
<details><summary>iffr.com (2)</summary>

- [Columbos — International Film Festival Rotterdam 2013](https://iffr.com/en/iffr/2013/films/columbos)
- [IFFR 2026 – Café Kuba: Who Dared to Awaken the Dead Memory](https://iffr.com/en/iffr/2026/films/caf%C3%A9-kuba-who-dared-to-awaken-the-dead-memory)

</details>
<details><summary>iicnairobi.esteri.it (1)</summary>

- [Masterclass on Immersive Cinema with Vincenzo Cavallo, Istituto Italiano di Cultura di Nairobi](https://iicnairobi.esteri.it/en/?p=6479)

</details>
<details><summary>iii.u-tokyo.ac.jp (1)</summary>

- [Hidenori Watanave, 'The Great East Japan Earthquake and Digital Archives', III/GSII, The University of Tokyo (2021; English translation by David Buist)](https://www.iii.u-tokyo.ac.jp/?p=13598)

</details>
<details><summary>ikon-gallery.org (1)</summary>

- [Yto Barrada: RIFFS - Ikon Gallery](https://www.ikon-gallery.org/exhibition/riffs/)

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
<details><summary>independent.co.uk (1)</summary>

- [In the studio: Laure Prouvost, film and installation artist (The Independent, 2013)](https://www.independent.co.uk/arts-entertainment/art/features/in-the-studio-laure-prouvost-film-and-installation-artist-8827919.html)

</details>
<details><summary>indiaartfair.in (1)</summary>

- [Where I Work: Afrah Shafiq — India Art Fair](https://indiaartfair.in/where-i-work-afrah-shafiq)

</details>
<details><summary>indianexpress.com (1)</summary>

- [Bangladeshi artist Tayeba Begum Lipi demystifies the isolated world of the transgender community — The Indian Express](https://indianexpress.com/article/lifestyle/art-and-culture/bangladeshi-artist-tayeba-begum-lipi-demystifies-the-isolated-world-of-the-transgender-community/)

</details>
<details><summary>indiewire.com (1)</summary>

- [Interview: Akosua Adoma Owusu's 'Kwaku Ananse' at the Institute of Contemporary Art (Philadelphia) - IndieWire](https://www.indiewire.com/2015/06/interview-akosua-adoma-owusus-kwaku-ananse-at-the-institute-of-contemporary-art-philadelphia-153842/)

</details>
<details><summary>informationactivism.org (1)</summary>

- [Occupy George: remixed dollar bills, 10 tactics remixed](https://informationactivism.org/en/occupy-george-remixed-dollar-bills.html)

</details>
<details><summary>inresidence.videobrasil.org.br (2)</summary>

- [Janaina Wagner > QUANDO O SEGUNDO SOL CHEGAR – Videobrasil In Residence](https://inresidence.videobrasil.org.br/2024/09/23/janaina-wagner-quando-o-segundo-sol-chegar/)
- [JANAINA WAGNER> QUANDO O SEGUNDO SOL CHEGAR (COMETA) – Videobrasil In Residence](https://inresidence.videobrasil.org.br/2024/06/14/janaina-wagner-quando-o-segundo-sol-chegar-cometa)

</details>
<details><summary>insciencefestival.nl (1)</summary>

- [Ebb & Flow, InScience Film Festival](https://www.insciencefestival.nl/en/film/ebb-flow/)

</details>
<details><summary>insideindonesia.org (1)</summary>

- [Between science, art and social design there is community (Inside Indonesia, 2014)](https://www.insideindonesia.org/editions/edition-118-oct-dec-2014/between-science-art-and-social-design-there-is-community)

</details>
<details><summary>instrumentinventors.org (1)</summary>

- [Jan Zuiderveld, Coffee Machine and Microwave, video, iii](https://instrumentinventors.org/?p=33685)

</details>
<details><summary>int-lab.cc (1)</summary>

- [Codex Virtualis – project site by Interspecifics (int-lab.cc/codex)](https://int-lab.cc/codex/?page_id=2)

</details>
<details><summary>interaliamag.org (1)</summary>

- [Eunoia – beautiful thoughts, interview by Richard Bright, Interalia Magazine](https://www.interaliamag.org/interviews/lisa-park-eunoia-beautiful-thought/)

</details>
<details><summary>interpretingthenatural.blogspot.com (1)</summary>

- [Interpreting the Natural: Contemporary Visions of Scholars' Rocks – artist statement](https://interpretingthenatural.blogspot.com/p/statement-history-livesthrough-language.html)

</details>
<details><summary>interviewmagazine.com (3)</summary>

- [Alex Gartenfeld, 'Ed Atkins', Interview Magazine, 27 November 2012](https://www.interviewmagazine.com/art/london-ed-atkins)
- [Nalini Malani Tells a Story — Interview Magazine](https://interviewmagazine.com/art/nalini-malani-ica-boston)
- [Six Stories, Twice Retold, interview by Haley Weiss, Interview Magazine, 2017](https://www.interviewmagazine.com/art/candice-breitz)

</details>
<details><summary>inverse.com (1)</summary>

- [The Philosophy of David OReilly's 'Everything' – Inverse, 2016](https://www.inverse.com/article/21826-david-oreilly-everything-interview)

</details>
<details><summary>iqoqo.org (1)</summary>

- [Is this the age of Afro-Immersion? XR, ritual, and the rise of African spatial futures (iQoqo, 2025)](https://iqoqo.org/is-this-the-age-of-afro-immersion-xr-ritual-and-the-rise-of-african-spatial-futures/)

</details>
<details><summary>irenebrination.com (1)</summary>

- [A Spider Under the Skin: Jalila Essaïdi’s Bulletproof Skin, Irenebrination (interview)](https://www.irenebrination.com/2013/03/06/jalila-essaidi-bulletproof-skin/)

</details>
<details><summary>isea-archives.org (3)</summary>

- [\[ISEA2019\] Artist Statement: Louis-Philippe Rondeau - LIMINAL](https://isea-archives.org/?p=43509)
- [\[ISEA2023\] Artist Statement: Rachel Rossin — The Maw Of (2022) — ISEA Symposium Archives](https://www.isea-archives.org/isea2023_art-event_rossin)
- [Claudia Costa Pederson, 'Life-as-it-could-be: Symbiosis in Interspecifics' Codex Virtualis\_Genesis', ISEA2023](https://www.isea-archives.org/isea2023_presentation_pederson)

</details>
<details><summary>isea-symposium-archives.org (2)</summary>

- ["Acconci Robot" by Wade Marynowsky, ISEA Symposium Archives (ISEA2013)](https://www.isea-symposium-archives.org/art-events/acconci-robot-by/)
- [“In Potentia (2012)” by Guy Ben-Ary, Dr. Kirsten Hudson – ISEA Symposium Archives](https://www.isea-symposium-archives.org/art-events/guy-ben-ary-dr-kirsten-hudson-in-potentia-2012/)

</details>
<details><summary>itsnicethat.com (2)</summary>

- [AI tools paint a blurry picture of our current reality (It's Nice That, essay by Linda Dounia Rebeiz)](https://www.itsnicethat.com/features/linda-dounia-rebeiz-ai-bias-technology-creative-industry-art-011123)
- [Nicer Tuesdays: Keiken on Wisdoms of Love 3.0 — It's Nice That](https://www.itsnicethat.com/articles/nicer-tuesdays-october-keiken-digital-171121)

</details>
<details><summary>ivan.cash (1)</summary>

- [Occupy George, ivan.cash](https://ivan.cash/occupy-george)

</details>
<details><summary>j-mediaarts.jp (8)</summary>

- ["patrinia yellow" for Clarinet and Computer — 18th Japan Media Arts Festival, Art Division Excellence Award (English)](https://j-mediaarts.jp/en/award/single/patrinia-yellow-for-clarinet-and-computer/)
- [Cangjie (earlier version) - 23rd Japan Media Arts Festival, Art Division Jury Selection](https://j-mediaarts.jp/en/award/single/cangjie/index-2.html)
- [Japan Media Arts Festival – 21st Art Division Excellence Award, Datum Point](https://j-mediaarts.jp/en/award/single/datum-point/)
- [Japan Media Arts Festival – 21st Art Division Excellence Award, Language Producing Factory](https://j-mediaarts.jp/en/award/single/language-producing-factory/)
- [Nuit Blanche, 14th Japan Media Arts Festival Art Division Jury Selections](https://j-mediaarts.jp/en/award/single/nuit-blanche)
- [rheo: 5 horizons, 14th Japan Media Arts Festival, Art Division Jury Selections](https://j-mediaarts.jp/en/award/single/rheo-5-horizons)
- [The Half — 17th Japan Media Arts Festival, Art Division Jury Selections](https://j-mediaarts.jp/en/award/single/the-half/)
- [YAMAMOTO Yoshihiro - Japan Media Arts Festival profile](https://j-mediaarts.jp/en/award/profile/yamamoto-yoshihiro/index-2.html)

</details>
<details><summary>ja.wikipedia.org (1)</summary>

- [渡邉英徳 - Wikipedia (Japanese)](https://ja.wikipedia.org/wiki/%E6%B8%A1%E9%82%89%E8%8B%B1%E5%BE%B3)

</details>
<details><summary>jacobtonski.com (2)</summary>

- [About - Jacob Tonski](https://www.jacobtonski.com/about)
- [Balance From Within - Jacob Tonski](https://www.jacobtonski.com/balance-from-within)

</details>
<details><summary>jalilaessaidi.com (1)</summary>

- [2.6g 329m/s / Bulletproof skin, jalilaessaidi.com](https://jalilaessaidi.com/2-6g-329ms/)

</details>
<details><summary>jan-kaps.com (1)</summary>

- [Jan Kaps – Helena Uambembe, 36th Bienal de São Paulo (press release)](https://jan-kaps.com/exhibitions/36th-bienal-de-so-paulo)

</details>
<details><summary>janawinderen.com (3)</summary>

- [Energy Field — release page (artist's website)](https://janawinderen.com/releases/energy-field)
- [Jana Winderen wins Golden Nica at Ars Electronica 2011 (artist's website)](https://janawinderen.com/news/jana-winderen-wins-golden-nica-at-ars-electronica-2011)
- [Tokafi interview, published 25 May 2010 (artist's website news)](https://janawinderen.com/news/tokafi-interview-with-jana-winderen-published-25-may-2010)

</details>
<details><summary>janejinkaisen.com (1)</summary>

- [Jane Jin Kaisen, 'Community of Parting, 2019' (artist's site)](https://janejinkaisen.com/community-of-parting-2019)

</details>
<details><summary>jar-online.net (1)</summary>

- [Giusy Caruso, XR Music Performance: a phygital piano duet in the metaverse, JAR](https://jar-online.net/en/node/2344)

</details>
<details><summary>jessjohnson.org (3)</summary>

- [TERMINUS — About, jessjohnson.org](https://www.jessjohnson.org/terminus-about)
- [TERMINUS — Exhibitions, jessjohnson.org](https://www.jessjohnson.org/terminus-exhibitions)
- [TERMINUS — Realms, jessjohnson.org](https://www.jessjohnson.org/terminus-realms)

</details>
<details><summary>jeyifo.us (1)</summary>

- [Olalekan Jeyifous, 'African Mobilities I, II – Mad Horse City' (artist's site)](https://jeyifo.us/African)

</details>
<details><summary>jillianmayer.net (1)</summary>

- [I Am Your Grandma (2011), jillianmayer.net](https://www.jillianmayer.net/i-am-your-grandma)

</details>
<details><summary>joaquinaras.com (1)</summary>

- [Añoranzas (Yira Yira) — Joaquín Aras (artist website)](https://joaquinaras.com/proyectos/anoranzas-yira-yira/)

</details>
<details><summary>jothomascomposer.blogspot.com (1)</summary>

- [Prix Ars Electronica Golden Nica — Jo Thomas (artist's blog)](https://jothomascomposer.blogspot.com/2012/05/prix-ars-electronica-golden-nica.html)

</details>
<details><summary>jovialvares93.wixsite.com (1)</summary>

- [Jovita Alvares, artist website (The Wanderer)](https://jovialvares93.wixsite.com/thewanderer)

</details>
<details><summary>jpf.go.jp (1)</summary>

- [\[Announcement\] La Biennale di Venezia: Yuko Mohri “Compose” at the Japan Pavilion (The Japan Foundation press release)](https://www.jpf.go.jp/e/about/press/2024/002.html)

</details>
<details><summary>juliamensch.com (1)</summary>

- [Julia Mensch, Portfolio 2026 (PDF)](http://juliamensch.com/wp-content/uploads/2026/02/Julia_Mensch_Portfolio_2026.pdf)

</details>
<details><summary>julietagil.com (1)</summary>

- [Nuestra Victoria - Julieta Gil (artist's website)](https://julietagil.com/Nuestra-Victoria)

</details>
<details><summary>justice-mitchell.squarespace.com (1)</summary>

- [Exploding Noir At 2,000 Frames Per Second, Justice Mitchell, 2010](https://justice-mitchell.squarespace.com/justice-mitchell/2010/4/12/exploding-noir-at-2000-frames-per-second.html)

</details>
<details><summary>kaapuera.bienal.org.br (1)</summary>

- [Ka’a Pûera: we are walking birds – Works, Fundação Bienal de São Paulo (pool source)](https://kaapuera.bienal.org.br/en/works/)

</details>
<details><summary>katevassgalerie.com (1)</summary>

- [Mario Klingemann, The Butcher’s Son, 2017 — Kate Vass Galerie (print)](https://www.katevassgalerie.com/print/mario-klingemann-3)

</details>
<details><summary>kawarga.ru (1)</summary>

- [Долой борцов с системой и психических неадаптантов! (Down with Wrestlers with Systems and Mental Nonadapters!), kawarga.ru](http://kawarga.ru/Da-Da/DaDa.htm)

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
<details><summary>kiculture.medium.com (1)</summary>

- [Bees and Bacteria in Art Making: an interview with AnneMarie Maes, KI Culture](https://kiculture.medium.com/bees-and-bacteria-in-art-making-an-interview-with-annemarie-maes-bb33c9e72104)

</details>
<details><summary>killscreen.com (1)</summary>

- [Sahej Rahal's AI Instruments and Cooperative Creatures, Killscreen](https://www.killscreen.com/sahej-rahals-ai-instruments-and-cooperative-creatures/)

</details>
<details><summary>knowledge4policy.ec.europa.eu (2)</summary>

- [A Particular Matter - European Commission Knowledge4Policy (Resonances II)](https://knowledge4policy.ec.europa.eu/projects-activities/particular-matter_en)
- [Memory Vapour, Knowledge4Policy (European Commission, Science Art Society)](https://knowledge4policy.ec.europa.eu/projects-activities/memory-vapour_en)

</details>
<details><summary>kontejner.org (2)</summary>

- [KONTEJNER, Device\_art 6.018: Interface I](https://kontejner.org/en/projekti/device_art-festival/device_art-6018/izlozba-4/sucelje-i)
- [The Echinoidea future – Adriatic sensing — KONTEJNER, A Sea Change / Heard by the Deep](https://kontejner.org/en/projekti/a-sea-change/kako-nas-cuje-more/izlo/the-echinoidea-future-adriatic-sensing)

</details>
<details><summary>kristinmcwharter.com (1)</summary>

- [Kristin McWharter: Conspire (artist's website)](https://kristinmcwharter.com/works/Conspire)

</details>
<details><summary>krzysztofcybulski.com (1)</summary>

- [ACOUSTIC ADDITIVE SYNTH (AAS) /// 2015-16 - Krzysztof Cybulski (artist's site)](http://krzysztofcybulski.com/aas2.html)

</details>
<details><summary>kunc.org (1)</summary>

- [Millions Of People Go By: Doug Aitken's 'Song 1' Distills City Life, NPR (KUNC)](https://www.kunc.org/2012-05-20/millions-of-people-go-by-doug-aitkens-song-1-distills-city-life)

</details>
<details><summary>kunst-im-tunnel.de (1)</summary>

- [long time lung time continuuuum!!! (a conver-something) - KIT Kunst im Tunnel](https://www.kunst-im-tunnel.de/en/exhibition/long-time-lung-time-continuuuum-a-conver-something/)

</details>
<details><summary>kunsthalltrondheim.no (1)</summary>

- [Opening: Songs for dying and Nets of Hyphae — Kunsthall Trondheim](https://kunsthalltrondheim.no/en/arrangementer/apning-songs-for-dying-og-nets-of-hyphae)

</details>
<details><summary>kunsthaushamburg.de (1)</summary>

- [Tejal Shah UNBECOMING visitor sheet, Kunsthaus Hamburg (PDF)](https://kunsthaushamburg.de/site/assets/files/1977/ts_besucherblatt_e.pdf)

</details>
<details><summary>kunstinstituutmelly.nl (2)</summary>

- [Moderation(s): Guilty Pleasures by Song-Ming Ang (Hong Kong) – Kunstinstituut Melly](https://www.kunstinstituutmelly.nl/en/programs/5869-moderation-s-guilty-pleasures-by-song-ming-ang-hong-kong)
- [Song Ming Ang – Kunstinstituut Melly](https://www.kunstinstituutmelly.nl/en/people/2803-song-ming-ang)

</details>
<details><summary>kunstradio.at (1)</summary>

- [Radiokunst – Kunstradio, 23 July 2023: Temporary Stored by Joseph Kamaru](https://www.kunstradio.at/2023B/23_07_2023en.html)

</details>
<details><summary>kunstraum.leuphana.de (1)</summary>

- [Tejal Shah — Between the Waves, Kunstraum der Leuphana Universität Lüneburg](https://kunstraum.leuphana.de/en/projects/between-the-waves)

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
<details><summary>labiennaledelyon.com (1)</summary>

- [12th Biennale de Lyon – exhibition guide (English, PDF)](https://www.labiennaledelyon.com/files/5137a43c/guide_exposition_uk_web.pdf)

</details>
<details><summary>labocine.com (4)</summary>

- [HANDMADE - Labocine (reproduces MoMA exhibition text)](https://www.labocine.com/films/handmade)
- [Labocine — We Are Dead Animals](https://www.labocine.com/films/we-are-dead-animals)
- [Labocine, 'Hidirtina (Sisters)'](https://www.labocine.com/films/hidirtina-sisters)
- [The Oracle: Ritual for the Future - Labocine](https://www.labocine.com/films/the-oracle-ritual-for-the-future-for-humans-and-non-humans)

</details>
<details><summary>laboralcentrodearte.org (3)</summary>

- [Chijikinkutsu — LABoral Centro de Arte, geoLAB](https://laboralcentrodearte.org/en/artworks/chijikinkutsu-2013-2015-2/)
- [Mapping an uncertain landscape – LABoral Centro de Arte (exhibition Digital Machines)](https://laboralcentrodearte.org/?p=48634)
- [rheo: 5 horizons, LABoral Centro de Arte](https://laboralcentrodearte.org/?p=16747)

</details>
<details><summary>lafayetteanticipations.com (1)</summary>

- [TAFAA – FERTILITY DEVICE (NUDGE FOR THE SCAPEGOAT), 2021 – Lafayette Anticipations collection (describes the FERTILITY DEVICE group)](https://www.lafayetteanticipations.com/en/node/9935)

</details>
<details><summary>lahorebiennale.org (6)</summary>

- [Asvajit Boyle, LB01 artist page, Lahore Biennale Foundation](https://lahorebiennale.org/lb01-artists/asvajit-boyle/)
- [Hira Nabi, LB01 artist page, Lahore Biennale Foundation](https://lahorebiennale.org/lb01-artists/hira-nabi/)
- [Iftikhar Dadi and Elizabeth Dadi, LB01 artist page, Lahore Biennale Foundation](https://lahorebiennale.org/lb01-artists/iftikhar-dadi-and-elizabeth-dadi/)
- [Lahore Biennale 03, Ehsan ul Haq & Iqra Tanveer](https://lahorebiennale.org/lb03-artists/ehsan-ul-haq-iqra-tanveer/)
- [Lahore Fort, LB01 site page, Lahore Biennale Foundation](https://www.lahorebiennale.org/?p=2527)
- [Tariq Alexander Qaiser — Lahore Biennale 03 artist page](https://lahorebiennale.org/lb03-artists/tariq-alexander-qaiser/)

</details>
<details><summary>laist.com (1)</summary>

- [Shadowcaster Christine Marie Will Create 40-Foot Shadows During 'The Fifty Year Sword' This Halloween, LAist (2011)](https://laist.com/news/entertainment/shadowcaster-christine-marie)

</details>
<details><summary>lalanta.com (1)</summary>

- [Imhathai Suwatthanasilp – La Lanta Fine Art](https://lalanta.com/artists/imhathai-suwatthanasilp/)

</details>
<details><summary>landmarks.utexas.edu (1)</summary>

- [Anxious Body — Landmarks, University of Texas at Austin](https://landmarks.utexas.edu/video-art/anxious-body)

</details>
<details><summary>larissasansour.com (1)</summary>

- [In Vitro (2019), larissasansour.com](https://larissasansour.com/In-Vitro-2019)

</details>
<details><summary>latimes.com (1)</summary>

- [Carolina A. Miranda, After Ferguson: U.S. museums need to show a work by Natalie Bookchin, Los Angeles Times, 2014](http://www.latimes.com/entertainment/arts/miranda/la-et-cam-ferguson-museums-natalie-bookchin-video-20140814-column.html)

</details>
<details><summary>lawrenceabuhamdan.com (1)</summary>

- [Walled Unwalled, lawrenceabuhamdan.com](http://lawrenceabuhamdan.com/walled-unwalled)

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
<details><summary>lidf.co.uk (1)</summary>

- [Ebb and Flow (A Onda Traz, O Vento Leva), London International Documentary Festival](https://lidf.co.uk/film/ebb-and-flow/)

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
<details><summary>livingarchitecturesystems.com (2)</summary>

- [Epiphyte Chamber - Living Architecture Systems Group](https://livingarchitecturesystems.com/epiphyte-chamber/)
- [Epiphyte Chamber PDF Article - Living Architecture Systems Group](https://livingarchitecturesystems.com/wp-content/uploads/2016/06/Epiphyte-Chamber-PDF-Article.pdf)

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
<details><summary>logicmag.io (1)</summary>

- [Toxicity is Never Consensual: Mary Maggic on Open Source Hormones, Logic Magazine (2019)](https://www.logicmag.io/bodies/mary-maggic-on-open-source-hormones)

</details>
<details><summary>loophole.art (1)</summary>

- [To Carry: The Last Look at the Sharjah Biennial 16 – Loophole](https://loophole.art/articles/sharjah-biennial-16)

</details>
<details><summary>lovelymobile.news (1)</summary>

- [Teek Mach’s Grisaille to be performed at the Sundance Film Festival, Lovely Mobile News](https://lovelymobile.news/?p=20185)

</details>
<details><summary>lowcarbon.lingql.com (2)</summary>

- [100 Climate Actions (online toolkit)](https://lowcarbon.lingql.com/100-climate-actions)
- [Low Carbon Chinatown - Hackney's Low Carbon Chinatown / Harvesting Climate Action (artist's project site)](https://lowcarbon.lingql.com/chinatown)

</details>
<details><summary>lrt.lt (1)</summary>

- [Venecijos kino festivalyje - lietuviško animacinio filmo premjera Gėdos akys - LRT Mediateka](https://www.lrt.lt/mediateka/irasas/2000851535/venecijos-kino-festivalyje-lietuvisko-animacinio-filmo-premjera-gedos-akys)

</details>
<details><summary>ludion.org (1)</summary>

- [Pablo Farneda, Entrevista a la artista e investigadora Marcela Armas, Ludión (PDF)](https://www.ludion.org/archivos/articulo/Farneda-Entrevista-Marcela-Armas.pdf)

</details>
<details><summary>luhringaugustine.com (1)</summary>

- [The Maddest House Party Ever - press page, Luhring Augustine](https://luhringaugustine.com/press/the-maddest-house-party-ever-ragnar-kjartansson-on-making-the-visitors-by-alex-needham)

</details>
<details><summary>lumaocto.com (1)</summary>

- [Octopocalypse - Luma Octo (project website)](https://www.lumaocto.com)

</details>
<details><summary>lumenprize.com (6)</summary>

- [3D/Interactive Award Winner 2019 — The Lumen Prize](https://lumenprize.com/2019-winners/maja-petric)
- [3D/Interactive Award Winner 2021 - The Lumen Prize](https://lumenprize.com/2021-winners/3d-interactive-winner)
- [Global South Award Winner 2021 – Lumen Prize](https://www.lumenprize.com/2021-winners/global-majority-winner)
- [Gold Award Winner 2018 — Mario Klingemann, The Butcher’s Son](https://lumenprize.com/2018-winners/mario-klingemann)
- [Gold Award Winner 2020: Julieta Gil - Lumen Prize](https://lumenprize.com/2020-winners/julieta-gil)
- [Moving Image Award 2019: Cassie McQuater, Lumen Prize](https://lumenprize.com/2019-winners/cassie-mcquater)

</details>
<details><summary>lwt3.com (1)</summary>

- [LWT3 project page, Giusy Caruso](https://lwt3.com/project/giusycaruso/)

</details>
<details><summary>machtdose.de (1)</summary>

- [transits – Machtdose (6-min preview of the 1h5 video)](https://machtdose.de/?p=11401)

</details>
<details><summary>macm.org (1)</summary>

- [Elizabeth Price: The Woolworths Choir of 1979, Musée d'art contemporain de Montréal (2013)](https://macm.org/en/exhibitions/elizabeth-price-the-woolworths-choir-of-1979-2/)

</details>
<details><summary>madartseattle.com (1)</summary>

- [We Are All Made of Light — MadArt Seattle (Oct 6 – Dec 1, 2018)](https://madartseattle.com/exhibits/we-are-all-made-of-light/)

</details>
<details><summary>magazine.artconnect.com (1)</summary>

- [Keiken: Deconstructing the Now — ArtConnect Magazine](https://magazine.artconnect.com/interviews/magazine/keiken-deconstructing-the-now)

</details>
<details><summary>magazine.catapult.co (1)</summary>

- [What Are You?: On Mixed-Race Identity and The Buddhist Bug - Catapult](https://magazine.catapult.co/people/stories/deborah-augustin-buddhist-bug-anida-yoeu-ali-malaysia-mixed-race)

</details>
<details><summary>magazine.dirt.fyi (1)</summary>

- [Nothing is inevitable - Lily Goldberg interviews Annie Dorsen, The Dirt](https://www.magazine.dirt.fyi/p/nothing-inevitable)

</details>
<details><summary>magazine.shots.net (1)</summary>

- [Sora makes The Hardest Part look easy (shots)](https://magazine.shots.net/news/view/sora-makes-the-hardest-part-look-easy)

</details>
<details><summary>majasmrekar.org (3)</summary>

- [K-9 Topology: ARTE\_mis, majasmrekar.org](http://majasmrekar.org/k-9-topology-artemis)
- [K-9\_topology: CyberArts 2017 - Prix Ars Electronica Exhibition, majasmrekar.org](http://majasmrekar.org/k-9topology-cyberarts-2017-prix-ars-electronica-exhibition)
- [K-9\_Topology: Hybrid Family, majasmrekar.org](http://majasmrekar.org/k-9topology-hybrid-family)

</details>
<details><summary>makezine.com (1)</summary>

- [Gregory Hayes, Los Ferronautas, Make:](https://makezine.com/article/craft/los-ferronautas/)

</details>
<details><summary>mandiberg.com (1)</summary>

- [Live Study, Michael Mandiberg (artist website)](https://www.mandiberg.com/live-study/)

</details>
<details><summary>mapmyway.co.za (1)</summary>

- [Seers Seekers Soothsayers - focus is lens-based at Zeitz MOCAA (MapMyWay)](https://mapmyway.co.za/seers-seekers-soothsayers-focus-is-lens-based-at-zeitz-mocaa/)

</details>
<details><summary>marc-hericher.com (1)</summary>

- [absence – Marc Hericher (artist site)](http://marc-hericher.com/project/absence/)

</details>
<details><summary>marcodonnarumma.com (1)</summary>

- [Corpus Nil - Marco Donnarumma (artist's site)](https://marcodonnarumma.com/works/corpus-nil/)

</details>
<details><summary>marcusneustetter.com (1)</summary>

- [Marcus Neustetter, 'Lead The Way Again' (artist's site)](https://marcusneustetter.com/lead-the-way-again/)

</details>
<details><summary>maryflanagan.com (1)</summary>

- [Mary Flanagan: \[help me know the truth\] (artist's website, with exhibition list)](https://maryflanagan.com/help-me-know-the-truth/)

</details>
<details><summary>masp.org.br (3)</summary>

- [The Century – (B Series), 2011, MASP collection](https://masp.org.br/en/collections/works/the-century-b-series)
- [Video Room: Janaina Wagner – MASP](https://masp.org.br/en/exhibitions/video-room-janaina-wagner)
- [Video Room: Manauara Clandestina – MASP](https://www.masp.org.br/en/exhibitions/video-room-manauara-clandestina)

</details>
<details><summary>mathildelavenne.com (1)</summary>

- [T R O P I C S, Mathilde Lavenne](https://www.mathildelavenne.com/t-r-o-p-i-c-s/)

</details>
<details><summary>media.mit.edu (1)</summary>

- [Open Source Estrogen, MIT Media Lab project overview](https://www.media.mit.edu/projects/open-source-estrogen/overview/)

</details>
<details><summary>mediaartexploration.org (1)</summary>

- [Prometheus Firebringer - Media Art Xploration](https://mediaartexploration.org/?p=2027)

</details>
<details><summary>mediacityseoul.kr (6)</summary>

- [Evaporating Symphony — 13th Seoul Mediacity Biennale artwork page](https://mediacityseoul.kr/en/yesterday/artworks/evaporating-symphony)
- [Seoul Mediacity Biennale – Blank Project #3 Cosmos](https://mediacityseoul.kr/en/yesterday/artworks/blank-project-3-cosmos-buk-sema)
- [Seoul Mediacity Biennale – Do Electric Sheep Dream 1 (Seoullo Media Canvas)](https://mediacityseoul.kr/en/yesterday/artworks/do-electric-sheep-dream-1-seoullo-media-canvas)
- [Seoul Mediacity Biennale – Do Electric Sheep Dream 1, 2](https://mediacityseoul.kr/en/yesterday/artworks/do-electric-sheep-dream-1-2)
- [Seoul Mediacity Biennale – Korean Internet Tour Guide](https://mediacityseoul.kr/en/yesterday/artworks/korean-internet-tour-guide)
- [Seoul Mediacity Biennale – Tak Young Hwan · Lee Kyung Nam (participant page)](https://mediacityseoul.kr/en/yesterday/participants/tak-young-hwan-lee-kyung-nam)

</details>
<details><summary>medias.unifrance.org (1)</summary>

- [Anxious Body press kit (Miyu Productions & New Deer), Unifrance](https://medias.unifrance.org/medias/32/180/242720/presse/anxious-body-%E3%83%97%E3%83%AC%E3%82%B9%E3%82%AD%E3%83%83%E3%83%88-%E8%8B%B1%E8%AA%9E.pdf)

</details>
<details><summary>medium.com (1)</summary>

- [Terence Broad, 'Autoencoding Blade Runner', Medium, 2016](https://medium.com/@terencebroad/autoencoding-blade-runner-88941213abbe)

</details>
<details><summary>meer.com (1)</summary>

- [Cinthia Marcelle & Tiago Mata Machado, Galeria Vermelho 2014 (Meer)](https://www.meer.com/en/9210-cinthia-marcelle-e-tiago-mata-machado)

</details>
<details><summary>memo.tv (2)</summary>

- [Forms — Memo Akten (artist's site)](https://www.memo.tv/works/forms/)
- [The Thinking Ocean, project page, memo.tv](https://www.memo.tv/projects/2026/thinkingocean/)

</details>
<details><summary>memoreview.net (1)</summary>

- [Tracey Moffatt: Body Remembers, by Rex Butler (Memo Review)](https://memoreview.net/blog/tracey-moffatt-body-remembers-and-thought-patterns-at-tarrawarra-by-rex-butler)

</details>
<details><summary>metalab.harvard.edu (1)</summary>

- [Igùn – metaLAB (at) Harvard](https://metalab.harvard.edu/p/igun)

</details>
<details><summary>metalmagazine.eu (1)</summary>

- [Daniel Rozin: The art of interaction, Metal Magazine](https://metalmagazine.eu/post/daniel-rozin-the-art-of-interaction-arnau-salvado)

</details>
<details><summary>metalocus.es (3)</summary>

- ["Doug Aitken: SONG 1" en el Hirshhorn Museum del Smithsonian, Metalocus](https://www.metalocus.es/es/noticias/doug-aitken-song-1-en-el-hirshhorn-museum-del-smithsonian)
- [Epiphyte Chamber. The Aleph Project. By Philip Beesley - METALOCUS](https://www.metalocus.es/en/news/epiphyte-chamber-aleph-project-philip-beesley)
- [Eunoia. Materializing thinking, Metalocus, 22 June 2013](https://www.metalocus.es/en/news/eunoia-materializing-thinking)

</details>
<details><summary>metamorf.no (1)</summary>

- [Frode Oldereid & Thomas Kvam – Meta.Morf 2024 \[up\]Loaded Bodies](https://metamorf.no/2024/?p=942)

</details>
<details><summary>mfa.org (1)</summary>

- [Candice Breitz: Love Story, Museum of Fine Arts Boston, 2018–19](https://www.mfa.org/exhibitions/candice-breitz-love-story)

</details>
<details><summary>mg.co.za (1)</summary>

- [From the outside, looking in (interview with Zanele Muholi) - Mail & Guardian, 2011](https://mg.co.za/article/2011-09-19-from-the-outside-looking-in-2)

</details>
<details><summary>mhrs.jp (2)</summary>

- [Soichiro Mihara – cosmos (Blank Project #3)](http://mhrs.jp/cosmos)
- [Soichiro Mihara – the blank to overcome (Blank Project #1)](http://mhrs.jp/theblankstoovercome)

</details>
<details><summary>miaminewtimes.com (2)</summary>

- [Jillian Mayer Freaks Out Her Unborn Grandchildren in "Family Matters", Miami New Times](https://www.miaminewtimes.com/arts/jillian-mayer-freaks-out-her-unborn-grandchildren-in-family-matters-6499945)
- [Ryan Trecartin on 'Any Ever,' Miami Vibes, and Reacting to Reaction - Miami New Times](https://www.miaminewtimes.com/?p=40450453)

</details>
<details><summary>michellelopez.com (4)</summary>

- [2025 Pandemonium — Michelle Lopez](https://www.michellelopez.com/exhibitions/2025-pandemonium)
- [2026 Whitney Biennial — Michelle Lopez](https://www.michellelopez.com/exhibitions/2026-whitney-biennial)
- [Hyperallergic: The Polycrisis Sublime of the Whitney Biennial (reprinted on artist's site)](https://www.michellelopez.com/writing/hyperallergic-the-polycrisis-sublime)
- [Whitney Biennial catalogue: conversation between Michelle Lopez and Christopher Lew](https://www.michellelopez.com/writing/whitney-biennial-catalogue-conversation-between-michelle-lopez-christopher-lew)

</details>
<details><summary>miff.com.au (2)</summary>

- [Ebb and Flow, Melbourne International Film Festival 2013 archive](https://miff.com.au/festival-archive/films/24778/ebb-and-flow)
- [Iyeza - MIFF festival archive (MIFF 2013)](https://miff.com.au/festival-archive/films/24839)

</details>
<details><summary>milk.co (2)</summary>

- [The Treachery of Sanctuary - Artist's statement - Chris Milk](http://milk.co/tos-statement)
- [The Treachery of Sanctuary - Chris Milk](http://milk.co/treachery)

</details>
<details><summary>minneatairu.com (1)</summary>

- [Minne Atairu – artist website](https://minneatairu.com/)

</details>
<details><summary>mirairecords.com (1)</summary>

- [Etsuko Yakushimaru – "I'm Humanity" (Mutated at YCAM), Mirai Records](https://mirairecords.com/stsr/1660)

</details>
<details><summary>mithusen.com (1)</summary>

- [Poems Declined — mithusen.com](https://mithusen.com/projects/poems-declined-2014/)

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
<details><summary>moniraalqadiri.com (1)</summary>

- [Behind the Sun, moniraalqadiri.com](https://www.moniraalqadiri.com/behind-the-sun/)

</details>
<details><summary>moranmorangallery.com (2)</summary>

- [In the Studio: Ryan Trecartin - Art in America, 2013 (Morán Morán)](https://moranmorangallery.com/?p=7749)
- [Ryan Trecartin - Flash Art, May/June 2011 (Morán Morán)](https://moranmorangallery.com/?p=7776)

</details>
<details><summary>morebranches.com (1)</summary>

- [Meet Osinachi, The Cryptoartist Fronting The Tokenized Artwork Movement In Africa (MoreBranches)](https://www.morebranches.com/meet-osinachi/)

</details>
<details><summary>mori.art.museum (1)</summary>

- [Light and Belief – Mori Art Museum collection](https://www.mori.art.museum/en/collection/2699/index.html)

</details>
<details><summary>mosmanartgallery.org.au (1)</summary>

- [Kawita Vatanajyankur: Performing Textiles - Mosman Art Gallery](https://mosmanartgallery.org.au/exhibition/kawita-vatanajyankur-performing-textiles/)

</details>
<details><summary>moussemagazine.it (1)</summary>

- [Ed Atkins 'Us Dead Talk Love' at Chisenhale Gallery, London, Mousse Magazine](http://moussemagazine.it/ed-atkins-chisenhale/)

</details>
<details><summary>mpib-berlin.mpg.de (1)</summary>

- [Karim Ben Khelifa - Artist in Residence, Center for Humans and Machines, Max Planck Institute for Human Development](https://www.mpib-berlin.mpg.de/chm/air/khelifa)

</details>
<details><summary>mplsart.com (1)</summary>

- [2021 McKnight Visual Artist Fellow: David Bowen (mplsart.com)](https://www.mplsart.com/written/2023/03/2021-mcknight-visual-artist-fellow-david-bowen)

</details>
<details><summary>mplus.org.hk (4)</summary>

- [In Search of Vanished Blood (2012) — M+ Museum collection](https://www.mplus.org.hk/en/collection/objects/in-search-of-vanished-blood-2019528/)
- [M+ Facade unveils 'Ho Tzu Nyen: Night Charades' (press release, 23 Jan 2025)](https://mplus.org.hk/en/press/mplus-facade-ho-tzu-nyen-night-charades)
- [Night Charades: Reimagining Hong Kong Cinema (M+ Magazine interview)](https://mplus.org.hk/en/magazine/night-charades-reimaging-hong-kong-cinema)
- [Vigil (2017) - M+ collection](https://www.mplus.org.hk/en/collection/objects/vigil-2018386/)

</details>
<details><summary>msutoday.msu.edu (1)</summary>

- [MSUToday: Professor wins grand prize at Japan Media Arts Festival (2020)](https://msutoday.msu.edu/news/2020/professor-wins-grand-prize-at-japan-media-arts-festival)

</details>
<details><summary>muac.unam.mx (1)</summary>

- [Edgardo Aragón, MUAC exhibition page (Sexta Sur, 2012)](https://muac.unam.mx/exposicion/edgardo-aragon?lang=en)

</details>
<details><summary>mubi.com (2)</summary>

- [MUBI Notebook – An Interview with Su Hui-Yu](https://mubi.com/notebook/posts/an-interview-with-su-hui-yu-ghost-traces-of-the-original-in-the-woman-s-revenge)
- [MUBI – Mother of Fog (synopsis)](https://mubi.com/en/br/films/mother-of-fog)

</details>
<details><summary>museumsfernsehen.de (1)</summary>

- [Shiro Takatani: "Toposcan / Baden-Württemberg" – Interview (Museumsfernsehen / ZKM, 14 Nov 2016)](https://www.museumsfernsehen.de/?p=12296)

</details>
<details><summary>muslimnetwork.tv (1)</summary>

- [Noor Riyadh lights up metro stations in Saudi with immersive artworks – Muslim Network TV](https://www.muslimnetwork.tv/?p=58837)

</details>
<details><summary>myartguides.com (4)</summary>

- [An Interview with Seba Calfuqueo, Mapuche Artist and Activist — My Art Guides](https://myartguides.com/interviews/an-interview-with-seba-calfuqueo-mapuche-artist-and-activist)
- [Marcela Armas, My Art Guides](https://myartguides.com/people/armas-marcela)
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
<details><summary>nashersculpturecenter.org (1)</summary>

- [Chasing the Sounds (Nasher Sculpture Center; excerpt of Clark Art Institute interview by Caitlin Woolsey, 2020)](https://www.nashersculpturecenter.org/read-watch/articles/article/id/286)

</details>
<details><summary>nation.africa (1)</summary>

- [Nation (Kenya), 'Installation artist shows that home is where the mind goes'](https://nation.africa/kenya/life-and-style/art-culture/installation-artist-shows-that-home-is-where-the-mind-goes-1221162)

</details>
<details><summary>nationthailand.com (2)</summary>

- [Compassion in every strand – The Nation (Thailand)](https://www.nationthailand.com/life/30189033)
- [The perfect housewife’s tale – The Nation (Thailand)](https://www.nationthailand.com/life/30322829)

</details>
<details><summary>neloakamatsu.jp (1)</summary>

- [Chijikinkutsu — Nelo Akamatsu art portfolio (artist's site)](http://www.neloakamatsu.jp/chijikinkutsu-eng.html)

</details>
<details><summary>neogeocity.com (1)</summary>

- [neogeocity.com (the work)](https://neogeocity.com/)

</details>
<details><summary>neuroelectrics.com (1)</summary>

- [Turning EEG into Art - Refik Anadol's 'Melting Memories', Neuroelectrics blog](https://www.neuroelectrics.com/blog/turning-eeg-into-art-refik-anadol-s-melting-memories)

</details>
<details><summary>newart.city (1)</summary>

- [Wisdoms for Love 3.0, by Keiken — Gray Area Festival 2021, New Art City](https://newart.city/catalog/gaf2021-room-6)

</details>
<details><summary>newday.com (1)</summary>

- [Meet New Day: Hira Nabi, New Day Films](https://www.newday.com/blog/meet-new-day-hira-nabi)

</details>
<details><summary>newmedia.udk-berlin.de (2)</summary>

- [Erik Anton Reinhardt, NoSearchBar, UdK Berlin New Media Class](https://newmedia.udk-berlin.de/students/erik-anton-reinhardt/nosearchbar)
- [NoSearchBar, UdK Berlin New Media Class project (Re-state, re-stage, re-enact, Winter 2021)](https://newmedia.udk-berlin.de/projects/2021-ws-k/nosearchbar)

</details>
<details><summary>newmedialab.cuny.edu (1)</summary>

- [CUNY New Media Lab – Interface study of Zeroboard’s administrator panel (Achim Koh)](https://newmedialab.cuny.edu/?p=9962)

</details>
<details><summary>newmediawritingprize.co.uk (1)</summary>

- [REPETAE: WORDS CAN COMMUNICATE BEYOND WORDS — New Media Writing Prize](https://newmediawritingprize.co.uk/?p=1618)

</details>
<details><summary>newmuseum.org (1)</summary>

- [New Museum – Cheng Ran: Diary of a Madman](https://www.newmuseum.org/exhibitions/view/cheng-ran-diary-of-a-madman)

</details>
<details><summary>news.abidjan.net (1)</summary>

- [Le Marocain Younès Baba-Ali, lauréat du Prix Léopold Sédar Senghor, Le Patriote via Abidjan.net, 12 May 2012](https://news.abidjan.net/articles/433272/10eme-biennale-de-lart-africain-contemporain-le-marocain-younes-baba-ali-laureat-du-prix-leopold-sedar-senghor)

</details>
<details><summary>news.cgtn.com (1)</summary>

- [VR opera, AR tigers: Welcome to China's immersive cinema (CGTN, 2025)](https://news.cgtn.com/news/2025-07-05/VR-opera-AR-tigers-Welcome-to-China-s-immersive-cinema-1EK0sXX6CKA/share_amp.html)

</details>
<details><summary>news.cornell.edu (1)</summary>

- [Milstein students get a glimpse of artist Xu Bing's character, Cornell Chronicle (2018)](https://news.cornell.edu/node/304496)

</details>
<details><summary>news.seoul.go.kr (1)</summary>

- [Seoul Metropolitan Government – Seoullo Media Canvas 2018 4th exhibition](https://news.seoul.go.kr/culture/archives/87613)

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
<details><summary>nguyentrinhthi.wordpress.com (3)</summary>

- [Nguyen Trinh Thi: Documenting the Invisibles – Prabda Yoon, Studio Voice](https://nguyentrinhthi.wordpress.com/reviews/documenting-the-invisibles/)
- [Review of “Unsubtitled” in Asian Art News (Bradford Edwards, April 2011)](https://nguyentrinhthi.wordpress.com/reviews/by-bradford-edwards-for-asian-art-news/)
- [UNSUBTITLED (video installation, 2010) – nguyễn trinh thi](https://nguyentrinhthi.wordpress.com/2012/10/01/post-1/)

</details>
<details><summary>nguyenwahed.com (1)</summary>

- [Art Basel Miami Beach 2025: XCOPY, Kim Asendorf, and Joe Pease - Nguyen Wahed](https://nguyenwahed.com/art-basel-miami-beach-2025)

</details>
<details><summary>ngv.vic.gov.au (1)</summary>

- [Contemporary artefacts and narcissistic robots: an interview with Wade Marynowsky (NGV)](https://www.ngv.vic.gov.au/essay/contemporary-artefacts-and-narcissistic-robots-an-interview-with-wade-marynowsky/)

</details>
<details><summary>nicolasbernier.com (1)</summary>

- [Nicolas Bernier, works list (artist website)](https://www.nicolasbernier.com/art)

</details>
<details><summary>nicolatriscott.org (1)</summary>

- [Nicola Triscott, Biopoetic investigations – Agnes Meyer Brandis (Arts Catalyst), 25 November 2011](https://nicolatriscott.org/2011/11/25/biopoetic-investigations-agnes-meyer-brandis/)

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
<details><summary>nomegallery.com (1)</summary>

- [NOME Gallery: Order+Noise (Interface I), 23 April - 18 June 2016](https://nomegallery.com/exhibitions/ordernoise/)

</details>
<details><summary>noorderlicht.com (2)</summary>

- [Liquid Crystal (Noorderlicht Biennale)](https://noorderlicht.com/en/whats-on/noorderlicht-biënnale-machine-entanglements/kick-off-van-de-noorderlicht-biënnale-in-japan/liquid-crystal)
- [Unknown Label, Noorderlicht](https://noorderlicht.com/en/whats-on/pixel-perceptions/unknown-label)

</details>
<details><summary>noproscenium.com (3)</summary>

- [The Great Orator — VR Trailer Reveal, No Proscenium](https://www.noproscenium.com/the-great-orator-vr-trailer-reveal/)
- [The World In Your Head: ‘Dispatch’ Brings A Neo-Noir Tale To VR (Review), No Proscenium](https://www.noproscenium.com/the-world-in-your-head-dispatch-brings-a-neo-noir-tale-to-vr-review/)
- [Venice Immersive 2026 video diary (NoProScenium), lists the installation with its synopsis](https://www.noproscenium.com/venice-immersive-video-diary-2026/)

</details>
<details><summary>npr.org (1)</summary>

- [Litterbugs Beware: Turning Found DNA Into Portraits, NPR](https://www.npr.org/2013/05/12/183363361/litterbugs-beware-turning-found-dna-into-portraits)

</details>
<details><summary>nr.world (1)</summary>

- [Ayşe Erkmen interview, NR magazine](https://nr.world/ayse-erkmen/)

</details>
<details><summary>nublockmuseum.blog (1)</summary>

- [Collection Spotlight: Seba Calfuqueo, Tray Tray Ko — Stories From The Block](https://nublockmuseum.blog/2025/03/11/collection-spotlight-seba-calfuqueo-tray-tray-ko/)

</details>
<details><summary>nwasianweekly.com (1)</summary>

- [Anida Yoeu Ali's The Buddhist Bug comes to life at Seattle Asian Art Museum - Northwest Asian Weekly](https://nwasianweekly.com/2024/03/anida-yoeu-alis-the-buddhist-bug-comes-to-life-at-seattle-asian-art-museum)

</details>
<details><summary>nyartsmagazine.net (1)</summary>

- [NY Arts Magazine – Cheng Ran debuts a new multi-video installation in the New Museum (museum press text)](https://nyartsmagazine.net/cheng-ran-debuts-new-multi-video-installation-new-museum/)

</details>
<details><summary>nybooks.com (1)</summary>

- [Death, Time, Soup: A Conversation with William Kentridge and Peter Galison, Margaret K. Koerner, The New York Review of Books, 2012](https://www.nybooks.com/online/2012/06/30/kentridge-galison-refusal-of-time/)

</details>
<details><summary>nygamecritics.com (1)</summary>

- [The Podcast: Navid Khonsari and Brooks Brown on Hero: A Verite VR Experience, New York Videogame Critics Circle](https://nygamecritics.com/2018/05/01/the-podcast-navid-khonsari-and-brooks-brown-on-hero-a-verite-vr-experience/)

</details>
<details><summary>nylon.com (1)</summary>

- [An iMessage Interview With Yung Jake - NYLON](https://www.nylon.com/articles/an-imessage-interview-with-yung-jake)

</details>
<details><summary>nytimes.com (1)</summary>

- [Martha Schwendener, review of Guy Ben-Ner 'Soundtrack', The New York Times, 30 January 2014](https://www.nytimes.com/2014/01/31/arts/design/guy-ben-ner-soundtrack.html)

</details>
<details><summary>o-matic.com (1)</summary>

- [The River is a Circle — o-matic.com](https://o-matic.com/?p=9460)

</details>
<details><summary>observatorioldigital.ufscar.br (1)</summary>

- [Odiolândia - Observatório da Literatura Digital Brasileira (UFSCar)](https://www.observatorioldigital.ufscar.br/?p=8736)

</details>
<details><summary>occupygeorge.com (1)</summary>

- [Occupy George, project website](http://occupygeorge.com/)

</details>
<details><summary>odt.co.nz (1)</summary>

- [Dunedin's newspaper inspiration - Otago Daily Times](https://www.odt.co.nz/entertainment/arts/dunedin%E2%80%99s-newspaper-inspiration)

</details>
<details><summary>oinstituto.pt (1)</summary>

- [Angie Saiz – INSTITUTO residency](https://oinstituto.pt/en/angie-saiz/)

</details>
<details><summary>ojs.aut.ac.nz (1)</summary>

- [Max Stahl, 'How skilful communication won the real story', Pacific Journalism Review 21(1), 2015](https://ojs.aut.ac.nz/pacific-journalism-review/article/download/123/90)

</details>
<details><summary>okayafrica.com (4)</summary>

- [How Anthony Azekwoh is pushing the boundaries of what it means to be a digital artist (OkayAfrica)](https://www.okayafrica.com/how-anthony-azekwoh-is-pushing-the-boundaries-of-what-it-means-to-be-a-digital-artist/1411266)
- [OkayAfrica – Yinka Bernie: Running Egwu Records & 'Moving Parts' Exhibition](https://www.okayafrica.com/what-its-like-to-run-an-indie-record-company-and-keep-vinyl-alive/1418023)
- [OkayAfrica, 'This Is What Lagos Could Look Like in 2115' (2018)](https://www.okayafrica.com/this-is-what-lagos-could-look-like-in-2115/231961)
- [South African Artist Simnikiwe Buhlungu on Creating the Sound of Dreams - OkayAfrica](https://okayafrica.com/venice-biennale-2022-buhlungu)

</details>
<details><summary>okayplayer.com (1)</summary>

- [Santigold x Wangechi Mutu - 'The End of Eating Everything' \[Animated Short\] - Okayplayer](https://www.okayplayer.com/santigold-x-wangechi-mutu-the-end-of-eating-everything-animated-short/392411)

</details>
<details><summary>okv.be (1)</summary>

- [Daan Rau, Ief Spincemaille - Licht en lucht, zon en horizon (OKV 2014.4, PDF)](https://www.okv.be/sites/default/files/2020-10/Ief%20Spincemaille%20-%20Licht%20en%20lucht%2C%20zon%20en%20horizon.pdf)

</details>
<details><summary>old.rhizome.org (2)</summary>

- [Rafaël Rozendaal's Liquid Websites, Rhizome](https://old.rhizome.org/editorial/2013/oct/09/rafael-rozendaals-liquid-websites/)
- [The Moon Goose Analogue: Lunar Migration Bird Facility, Rhizome, 8 February 2012](https://old.rhizome.org/editorial/2012/feb/08/agnes-meyer-brandis-moon-goose-analogue-lunar-migr)

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
<details><summary>onscreentoday.com (1)</summary>

- [Lost in Her Languages: Yintzu Huang's Aphasia, onscreentoday.com (June 22, 2015)](https://onscreentoday.com/screenshot/lost-in-her-languages-huang/)

</details>
<details><summary>opendoclab.mit.edu (2)</summary>

- [Layers of Place: Austin — The Founders Pillars – MIT Open Documentary Lab](https://opendoclab.mit.edu/presents/layers-place-austin-founders-pillars/)
- [Layers of Place: MIT — The Fovnders Pillars – MIT Open Documentary Lab](https://opendoclab.mit.edu/?p=24287)

</details>
<details><summary>opensecret.kw-berlin.de (1)</summary>

- [The Maw Of — Open Secret, KW Institute for Contemporary Art](https://opensecret.kw-berlin.de/artwork/the-maw-of/)

</details>
<details><summary>opensurgery.net (1)</summary>

- [OpenSurgery project site, opensurgery.net](http://www.opensurgery.net)

</details>
<details><summary>openthemagazine.com (1)</summary>

- [Bani Abidi: The Last Laugh, Open magazine](https://openthemagazine.com/art-culture/bani-abidi-the-last-laugh/)

</details>
<details><summary>opera.beastsandnatives.com (1)</summary>

- [OPERA project site (beasts and natives alike)](http://opera.beastsandnatives.com/)

</details>
<details><summary>optionstheedge.com (1)</summary>

- [Anida Yoeu Ali's 'The Buddhist Bug' questions differences and invites audience to interact - Options, The Edge](https://www.optionstheedge.com/node/1292)

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
<details><summary>pamm.tv (1)</summary>

- [Cassie McQuater, Love Birds, Night Birds, Devil-Birds, 2019, Pérez Art Museum Miami (PAMM TV)](https://www.pamm.tv/film/cassie-mcquater-love-birds-night-birds-devil-birds-2019/)

</details>
<details><summary>paoloalmario.com (3)</summary>

- [Dyscrimina / Ausente – Paolo Almario](https://paoloalmario.com/portfolio/dyscrimina-ausente/)
- [Manifesto – Paolo Almario](https://paoloalmario.com/manifesto)
- [Paolo Almario – artist site (statement and bio)](https://paoloalmario.com/)

</details>
<details><summary>paolocirio.net (3)</summary>

- [Interview about Loophole for All for The Verge (2013), paolocirio.net](https://paolocirio.net/press/interviews/interview_l4a_verge.php)
- [Interview about Loophole for All for Wild Magazine & DoEasyArt (2014), paolocirio.net](https://paolocirio.net/press/interviews/interview_l4a_wild.php)
- [Loophole for All, paolocirio.net](https://paolocirio.net/work/loophole-for-all/)

</details>
<details><summary>papermag.com (1)</summary>

- [Harry Tafoya, Isabelle Frances McGuire, American Dreamer and Nightmare Artist (PAPER, 26 February 2025)](https://www.papermag.com/isabelle-frances-mcguire)

</details>
<details><summary>patenteux.com (2)</summary>

- [PATENTEUX - Louis-Philippe Rondeau (artist's website, bio and exhibition list)](https://patenteux.com/wp/)
- [RÉSONANCES (2021) - PATENTEUX (artist's website)](https://patenteux.com/wp/portfolio/resonances-2021/)

</details>
<details><summary>paulvanouse.com (1)</summary>

- [Paul Vanouse: Labor (artist's website)](http://www.paulvanouse.com/labor.html)

</details>
<details><summary>peopleofcolorintech.com (1)</summary>

- [Meet the Nigerian AI artist redefining the older generation's style (POCIT, 2023)](https://peopleofcolorintech.com/front/meet-the-nigerian-ai-artist-redefining-the-older-generations-style/)

</details>
<details><summary>peterburr.org (1)</summary>

- [sunshine monument (artist's site)](https://peterburr.org/sunshine.php)

</details>
<details><summary>phaidon.com (1)</summary>

- [A Few Questions for Edgardo Aragón, Rural Mexico's Subversive Documentarian, Artspace (Phaidon)](https://www.phaidon.com/blogs/artspace/a-few-questions-for-edgardo-aragon)

</details>
<details><summary>philipbeesleystudioinc.com (1)</summary>

- [Epiphyte Chamber - Philip Beesley Studio Inc.](https://www.philipbeesleystudioinc.com/sculpture/epiphyte-chamber/)

</details>
<details><summary>phnompenhpost.com (1)</summary>

- [Museum to host first exhibition of contemporary Cambodian art – Phnom Penh Post](http://www.phnompenhpost.com/post-weekend/museum-host-first-exhibition-contemporary-cambodian-art)

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
<details><summary>placesiveneverbeen.com (1)</summary>

- [Believe Me, 2017- — Addie Wagenknecht (artist's site)](https://placesiveneverbeen.com/believe-me)

</details>
<details><summary>platform-mag.com (1)</summary>

- [Mithu Sen — Platform magazine](https://www.platform-mag.com/art/mithu-sen.html)

</details>
<details><summary>platform-magazine.com (1)</summary>

- [The Dramatically Forgotten (Debaser/Platform Magazine)](https://www.platform-magazine.com/art/siren-eun-jung)

</details>
<details><summary>playstation.com (1)</summary>

- [Hotel Infinity - PlayStation Store page (PS VR2)](https://www.playstation.com/en-us/games/hotel-infinity/)

</details>
<details><summary>plrl.blogs.lincoln.ac.uk (1)</summary>

- [Crystal — Practice-led Research @ Lincoln](https://plrl.blogs.lincoln.ac.uk/2014/06/26/crystal)

</details>
<details><summary>pollinator.art (1)</summary>

- [pollinator.art (the artwork's website)](https://www.pollinator.art/)

</details>
<details><summary>portablepalace.com (3)</summary>

- [Domnitch & Gelfand CV (lists 2013 Honorary Mention Hybrid Art, Ars Electronica)](https://www.portablepalace.com/cv.html)
- [Domnitch & Gelfand, "Hyperspectral Percipience", Digimag Journal 74, Winter 2013 (PDF)](https://www.portablepalace.com/pdf/Digimag74_extract.pdf)
- [MEMORY VAPOR (artists' website)](https://www.portablepalace.com/memory_vapor.html)

</details>
<details><summary>povmagazine.com (1)</summary>

- [Foragers review by Allegra Moyle (POV Magazine)](https://povmagazine.com/?p=10556)

</details>
<details><summary>prd-cm.singaporeartmuseum.sg (2)</summary>

- [Media release: Singapore Biennale 2025: pure intention transforms the city into a platform (Singapore Art Museum)](https://prd-cm.singaporeartmuseum.sg/-/media/SAM/Files/Press-Release/2025-PR/Media-Release-Singapore-Biennale-2025-pure-intention-Transforms-the-City-Into-A-Platform.pdf)
- [SB2019 Media Alert: Final Artist List and Coordinates Projects, Singapore Art Museum (PDF)](https://prd-cm.singaporeartmuseum.sg/-/media/SAM/Files/Press-Release/2019-PR/SB2019-Media-Alert_Final-Artist-List-and-Coordinates-Projects_EN_with-Annexes.pdf?inline=1)

</details>
<details><summary>press.moma.org (1)</summary>

- [MoMA announces new digital art acquisitions, exhibitions and artist collaborations (press release, October 10, 2023)](https://press.moma.org/wp-content/uploads/2023/10/MoMADigitalArtAnnouncements_FINAL-2.pdf)

</details>
<details><summary>presse.louvre.fr (1)</summary>

- [Musée du Louvre press — Elias Crespin, L'Onde du Midi](https://presse.louvre.fr/elias-crespinbr-londe-du-midibr-a-new-permanent-installationbr-for-the-louvre)

</details>
<details><summary>presstube.com (1)</summary>

- [Presstube: Hello (artist's studio page)](https://presstube.com/hello/)

</details>
<details><summary>printedmatter.org (1)</summary>

- [Basel Abbas and Ruanne Abou-Rahme, The Zone (Artists & Activists 19), Printed Matter, 2012](https://www.printedmatter.org/catalog/50025/)

</details>
<details><summary>proa.org (1)</summary>

- [Mariano Sardón / Mariela Yeregui, press note, Fundación Proa, Buenos Aires](https://www.proa.org/eng/press-note.php?id=1083)

</details>
<details><summary>project88.in (1)</summary>

- [Between the Waves \| 4 - 10 April 2013 — Project 88](https://project88.in/exhibitions/45-between-the-waves-tejal-shah/overview)

</details>
<details><summary>prospectmagazine.co.uk (1)</summary>

- [Richard Mosse: The biggest challenge was to make the audience feel their complicity, Prospect](https://prospectmagazine.co.uk/culture/60460/richard-mosse-the-biggest-challenge-was-to-make-the-audience-feel-their-complicity)

</details>
<details><summary>purple.fr (1)</summary>

- [An excerpt from Wantee (2013) - purple TELEVISION](https://purple.fr/television/an-excerpt-from-wantee-2013/)

</details>
<details><summary>qantara.de (1)</summary>

- [Morocco's art scene: a coin with two faces (interview with Leila Alaoui) - Qantara.de, 2015](https://qantara.de/en/node/7803)

</details>
<details><summary>quarantinetimes.org (1)</summary>

- [The Quarantine Times: article with interview (2020)](https://quarantinetimes.org/news/artist-kristin-mcwharters-instagram-prompts-meditate-on-whats-necessary-in-a-post-covid-world)

</details>
<details><summary>quayola.com (1)</summary>

- [Forms — Quayola (artist's site)](https://quayola.com/work/forms/)

</details>
<details><summary>qz.com (1)</summary>

- [The Vietnam War, as seen through the ethereal art of Vietnamese soldiers – Quartz](https://qz.com/651541/hollywood-tackled-the-vietnam-war-with-platoon-heres-what-viet-cong-soldier-artists-made)

</details>
<details><summary>radiancevr.co (2)</summary>

- [Ngendo Mukii – Radiance VR (pool source)](https://www.radiancevr.co/artists/ngendo-mukii/)
- [Radiance VR, 'Selly Raby Kane – The Other Dakar'](https://www.radiancevr.co/artists/selly-raby-kane/)

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
<details><summary>realtime.org.au (2)</summary>

- [Gail Priest, Screen as time lens, RealTime (2016)](https://www.realtime.org.au/?p=16213)
- [in the loop sept 5: digital whispers & shadows (RealTime, on Experimenta Speak to Me 2012)](https://www.realtime.org.au/?p=13847)

</details>
<details><summary>redcat.org (1)</summary>

- [Annie Dorsen - REDCAT (2024)](https://redcat.org/events/2024/annie-dorsen)

</details>
<details><summary>refikanadol.com (1)</summary>

- [Melting Memories, refikanadol.com](https://refikanadol.com/works/melting-memories/)

</details>
<details><summary>refresh.zhdk.ch (1)</summary>

- [Displuvium — ZHdK Ways into Being / refresh](https://refresh.zhdk.ch/refresh-2/exhibition/displivium/)

</details>
<details><summary>renewablematter.eu (1)</summary>

- [Calculating and Powers: Interview with Kate Crawford, Renewable Matter](https://www.renewablematter.eu/en/artificial-intelligence-computations-power-interview-kate-crawford)

</details>
<details><summary>repositorio.usp.br (1)</summary>

- [Beiguelman, G. Odiolândia, 2017. In: Lento Crepúsculo (Porto Alegre: Cactus, 2019) - ReP USP record](https://repositorio.usp.br/item/002949613)

</details>
<details><summary>research.rhizomatiks.com (1)</summary>

- [Nosaj Thing - AR Live Demo, Rhizomatiks Research (archive site)](https://research.rhizomatiks.com/en/works/nosaj_ar_demo.html)

</details>
<details><summary>revistaerrata.gov.co (1)</summary>

- [Clemencia Echeverri (interview), ERRATA# 13: Derechos Humanos y Memoria](https://www.revistaerrata.gov.co/contenido/clemencia-echeverri)

</details>
<details><summary>rhizomatiks.com (2)</summary>

- [AR Live Demo, Nosaj Thing, Rhizomatiks](https://rhizomatiks.com/en/work/ar-live-demo)
- [Live at Sónar Barcelona, Nosaj Thing x Daito Manabe, Rhizomatiks](https://rhizomatiks.com/en/work/daito-nosaj-sonar-barcelona)

</details>
<details><summary>rhizome.org (1)</summary>

- [Artist Profile: Jacolby Satterwhite (Rhizome, 2014)](https://rhizome.org/editorial/2014/jan/9/artist-profile-jacolby-satterwhite/)

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
<details><summary>roehrsboetsch.com (1)</summary>

- [Maria Guta, Interlooped - Roehrs & Boetsch](https://www.roehrsboetsch.com/artists/detail/maria-guta/work/interlooped/)

</details>
<details><summary>romaintardy.com (1)</summary>

- [The Great Indecision Council • 2018 - Romain Tardy (artist's site)](https://romaintardy.com/The-Great-Indecision-Council-2018)

</details>
<details><summary>roots.gov.sg (2)</summary>

- [Justin – Roots.gov.sg (Singapore Art Museum collection)](https://www.roots.gov.sg/collection-landing/listing/1581821)
- [The Flower Field – Roots.gov.sg (Singapore Art Museum collection)](https://www.roots.gov.sg/collection-landing/listing/1388411)

</details>
<details><summary>ru.cultura.unam.mx (1)</summary>

- [Nuestra Victoria - Re\_vista 003, Museo Experimental el Eco, UNAM (PDF)](https://ru.cultura.unam.mx/bitstream/123456789/653/2/Museo%20Experimental%20el%20Eco%2C%20UNAM_Nuestra%20Victoria.pdf)

</details>
<details><summary>russh.com (1)</summary>

- [RUSSH, Bare bones: Hayley Millar Baker on separating memory from experience](https://www.russh.com/hayley-millar-baker/)

</details>
<details><summary>ryoichikurokawa.com (1)</summary>

- [Ryoichi Kurokawa, bio and works](https://ryoichikurokawa.com/bio.html)

</details>
<details><summary>ryufurusawa.com (1)</summary>

- [Mid Tide #3 - ryufurusawa.com](https://ryufurusawa.com/post/744711413283569664/mid-tide-3)

</details>
<details><summary>saha.org.tr (1)</summary>

- [The 36th São Paulo Biennial, Brazil – SAHA (supporter project page)](https://saha.org.tr/en/projects/the-36th-sao-paulo-biennial-brazil)

</details>
<details><summary>sahejrahal.com (1)</summary>

- [Antraal, sahejrahal.com (with excerpt of Reza Negarestani, 'A Life That Wanders In Time')](https://www.sahejrahal.com/Antraal)

</details>
<details><summary>samdani.com.bd (1)</summary>

- [MOTHERTONGUE, Australian Center for Contemporary Art — Samdani Art Foundation](https://samdani.com.bd/projects/mothertongue,-australian-center-for-contemporary-art-)

</details>
<details><summary>samgreen.to (1)</summary>

- [A Thousand Thoughts, samgreen.to](https://samgreen.to/a-thousand-thoughts/)

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
<details><summary>screenanarchy.com (1)</summary>

- [African Folk Tales Come To Life In KWAKU ANANSE - ScreenAnarchy](https://screenanarchy.com/2012/12/african-folk-tales-come-to-life-in-kwaku-ananse.html)

</details>
<details><summary>sculpturemagazine.art (2)</summary>

- [Berin Golonu, Ayse Erkmen: Plan B and Other (Not So) Futile Gestures, Sculpture, January 2012](https://sculpturemagazine.art/ayse-erkmen-plan-b-and-other-not-so-futile-gestures/)
- [From the Imagined World: A Conversation with Muhannad Shono, Sculpture magazine, 2023](https://sculpturemagazine.art/from-the-imagined-world-a-conversation-with-muhannad-shono/)

</details>
<details><summary>seastate.sg (1)</summary>

- [seastate.sg — artist's project site](https://www.seastate.sg/)

</details>
<details><summary>sedici.unlp.edu.ar (1)</summary>

- [Magdalena Mastromarino, 'Utopías robóticas: un imaginario contrahegemónico', Arte e Investigación (2021)](https://sedici.unlp.edu.ar/handle/10915/136390)

</details>
<details><summary>seditionart.com (1)</summary>

- [Interview with Ryoichi Kurokawa: Synesthetic Experience, Sedition](https://www.seditionart.com/magazine/interview-ryoichi-kurokawa-synesthetic-experience)

</details>
<details><summary>seebyyourears.jp (1)</summary>

- [聴象発景 in Rittor Base - HPL ver - See by Your Ears (project page)](https://seebyyourears.jp/projects/chosho-hakkei-rittor/)

</details>
<details><summary>seesawmag.com.au (1)</summary>

- [SymbioticA: art and science in symbiosis, Seesaw Magazine](https://www.seesawmag.com.au/2022/02/symbiotica-art-and-science-in-symbiosis)

</details>
<details><summary>seft1.net (2)</summary>

- [S.E.F.T.-1 project website (monitor of the Mexico exploration)](http://seft1.net)
- [S.E.F.T.-1, Proyecto, seft1.net](https://seft1.net/seft1/proyecto/)

</details>
<details><summary>serpentinegalleries.org (3)</summary>

- [Serpentine Arts Technologies (pool source)](https://www.serpentinegalleries.org/arts-technologies/)
- [Serpentine press page: Danielle Brathwaite-Shirley: I DIDNT REALISE YOU THOUGHT LIKE THAT](https://www.serpentinegalleries.org/about/press/danielle-brathwaite-shirley-ididntrealiseyouthoughtlikethat/)
- [Serpentine: I DIDNT REALISE YOU THOUGHT LIKE THAT (project page)](https://www.serpentinegalleries.org/whats-on/i-didnt-realise-you-thought-like-that/)

</details>
<details><summary>sfmoma.org (2)</summary>

- [On William Kentridge's The Refusal of Time, SFMOMA](https://www.sfmoma.org/theme/on-william-kentridges-the-refusal-of-time/)
- [William Kentridge: The Refusal of Time (video by the Metropolitan Museum of Art, via SFMOMA)](https://www.sfmoma.org/watch/william-kentridge-refusal-time)

</details>
<details><summary>share.hek.ch (1)</summary>

- [Interview with Chloé Delarue – HEK share (video, Swiss Media Art – Pax Art Awards 2021, 2022)](https://share.hek.ch/en/interview-with-chloe-delarue/)

</details>
<details><summary>sharjahart.org (7)</summary>

- [EP05: Singing Wells x Natasha Ginwala – Biennial Bytes, Sharjah Art Foundation](https://www.sharjahart.org/en/resources/saf-online/details/ep05-singing-wells-x-natasha-ginwala)
- [Fazal Rizvi, Sharjah Biennial 16 participant page](https://sharjahart.org/en/sharjah-biennial/sb-16/people/details/fazal-rizvi)
- [Fazal Rizvi: Kissing of the Threshold, Sharjah Art Foundation publication](https://www.sharjahart.org/en/resources/publications/details/fazal-rizvi-kissing-of-the-threshold)
- [Fernando Palma Rodríguez - Sharjah Biennial 16](https://www.sharjahart.org/en/sharjah-biennial/sb-16/people/details/fernando-palma-rodriguez)
- [Sharjah Art Foundation – Um Al Dhabab (Mother of Fog) (2023)](https://www.sharjahart.org/en/projects/details/um-al-dhabab-mother-of-fog-2023)
- [Singing Wells: Sonic Inheritances (artist book) – Sharjah Art Foundation](https://www.sharjahart.org/en/resources/publications/details/singing-wells-sonic-inheritances)
- [Sonic Inheritances: Listening with Singing Wells – Sharjah Art Foundation](https://www.sharjahart.org/en/event/details/sonic-inheritances-listening-with-singing-wells/)

</details>
<details><summary>shinhanagata.com (2)</summary>

- [CHIMERIA - Shin Hanagata (artist's site)](https://www.shinhanagata.com/en/works/chimeria)
- [The Twisting Manifesto - Shin Hanagata (artist's site)](https://www.shinhanagata.com/en/statement)

</details>
<details><summary>shortoftheweek.com (2)</summary>

- [Nuit Blanche, Short of the Week (Jason Sondhi), 2010](https://shortoftheweek.com/2010/02/05/nuit-blanche)
- [The Full Story - Short of the Week](https://www.shortoftheweek.com/0000/00/00/the-full-story)

</details>
<details><summary>shortsblog.berlinale.de (2)</summary>

- [KWAKU ANANSE // SHORTS V. - Berlinale Shorts blog, 2013](https://shortsblog.berlinale.de/2013/02/13/kwaku-ananse-shorts-v)
- [„Futsu no seikatsu“ (Ordinary Life) / Interviews, press etc. — Berlinale Shorts](https://shortsblog.berlinale.de/2025/02/18/futsu-no-seikatsu-ordinary-life-interviews-press-etc)

</details>
<details><summary>showstudio.com (1)</summary>

- ['Silence Can Be A Form of Self-Dismissal' Julianknxx on the Art of Filmmaking – SHOWstudio](https://showstudio.com/news/silence-can-be-a-form-of-self-dismissal-julianknxx-on-the-art-of-filmmaking)

</details>
<details><summary>side-line.com (1)</summary>

- [Interview with Cedrik Fermont (C-Drik), Side-Line, 2016](http://www.side-line.com/interview-with-cedrik-fermont-c-drik-about-less-familiar-underground-scenes-in-the-world-why-am-i-one-of-the-few-africans-in-this-scene-2/)

</details>
<details><summary>signals.digibc.org (1)</summary>

- [I Would Like to be Midnight I Would Like to be Sky (Signals, DigiBC)](https://signals.digibc.org/?p=8300)

</details>
<details><summary>simonwoodfilm.com (1)</summary>

- [The Founders Pillars – Simon Wood](https://simonwoodfilm.com/the-founders-pillars)

</details>
<details><summary>singaporeartmuseum.sg (3)</summary>

- ['Scanning' (2013) by Amy Lee Sanford – Singapore Art Museum](https://singaporeartmuseum.sg/About/Our-Collection/Scanning)
- [Artist Folio: Zarina Muhammad (Singapore Art Museum, SB2022)](https://www.singaporeartmuseum.sg/-/media/SAM/Files/Exhibitions/SB2022/Artist-Folio_Zarina_Muhammad.pdf?inline=1)
- [Everyday Practices – room sheet, Singapore Art Museum (PDF)](https://singaporeartmuseum.sg/-/media/SAM/Files/Exhibitions/Everyday-Practices/English-Roomsheet.pdf?inline=1)

</details>
<details><summary>singaporeartmuseum.sg:443 (1)</summary>

- [Cinerama: Art and the Moving Image in Southeast Asia – exhibition guide, Singapore Art Museum (PDF)](https://www.singaporeartmuseum.sg:443/-/media/SAM/Files/Exhibitions/Cinerama/Cinerama_FA_Web_Cover_4.pdf?inline=1)

</details>
<details><summary>singaporebiennale.org (1)</summary>

- [Zarina Muhammad - Singapore Biennale](https://www.singaporebiennale.org/artists/zarina-muhammad)

</details>
<details><summary>singingwells.org (2)</summary>

- [Mission – Singing Wells](https://www.singingwells.org/mission/)
- [What We Do – Singing Wells](https://www.singingwells.org/what-we-do/)

</details>
<details><summary>sip.nmartproject.net (1)</summary>

- [Fukushima, Satoshi — SIP SoundLAB Interview Project](https://sip.nmartproject.net/?p=46)

</details>
<details><summary>site.videobrasil.org.br (13)</summary>

- [21st Contemporary Art Biennial Sesc\_Videobrasil: Imagined Communities, catalogue (PDF)](https://site.videobrasil.org.br/downloads/2240285)
- [Claudia Martínez Garay, Statement 2019, Videobrasil archive](https://site.videobrasil.org.br/en/acervo/artistas/textos/1781546)
- [Das avós, Videobrasil collection](https://site.videobrasil.org.br/en/acervo/obras/obra/2227443)
- [Gabriela Golder \| 21st Biennial, Canal VB](https://site.videobrasil.org.br/canalvb/video/2229514/Gabriela_Golder_21a_Bienal)
- [Gabriela Golder, texts (presentation text and Statement 2019), Videobrasil archive](https://site.videobrasil.org.br/en/acervo/artistas/textos/39223)
- [Laboratorio de invención social o posibles formas de construcción colectiva, Videobrasil collection](https://site.videobrasil.org.br/en/acervo/obras/obra/2222471)
- [Lines of divergence, Videobrasil collection](https://site.videobrasil.org.br/en/acervo/obras/obra/2222253)
- [Residency Prize Cariri Cultural Center \| 22ª Bienal – Videobrasil](https://site.videobrasil.org.br/en/news/2247012)
- [Rosana Paulino \| 21st Biennial, Canal VB](https://site.videobrasil.org.br/en/canalvb/video/2229612/Rosana_Paulino_21a_Bienal)
- [Rosana Paulino, Statement 2019, Videobrasil archive](https://site.videobrasil.org.br/en/acervo/artistas/textos/196468)
- [Ximena Garrido-Lecca \| 21st Biennial, 2019, Canal VB](https://site.videobrasil.org.br/en/canalvb/video/2229945/Ximena_Garrido_Lecca_21a_Bienal)
- [Ximena Garrido-Lecca, Statement 2019, Videobrasil archive](https://site.videobrasil.org.br/en/acervo/artistas/textos/1781527)
- [ÑUQA KAUSAKUSAQ QHEPAYKITAPAS, Videobrasil collection](https://site.videobrasil.org.br/en/acervo/obras/obra/2222455)

</details>
<details><summary>sites.psu.edu (1)</summary>

- [Interview with Video Game Artist Cassie McQuater, Annamarie O'Brien, 2019](https://sites.psu.edu/annamarieobrien/2019/04/29/interview-with-video-game-artist-cassie-mcquater/)

</details>
<details><summary>skol.ca (1)</summary>

- [Alexis O'Hara: SQUEEEEQUE! SPEAKERDOME — Centre des arts actuels SKOL, 2009](https://skol.ca/en/?p=4096)

</details>
<details><summary>skwigly.co.uk (1)</summary>

- [WATCH: 'The Full Story' by Daisy Jacobs released online - Skwigly](https://skwigly.co.uk/watch-the-full-story-by-daisy-jacobs-released-online)

</details>
<details><summary>sleek-mag.com (1)</summary>

- [Txting w/ Yung Jake - Sleek](https://www.sleek-mag.com/article/txting-w-yung-jake-interview-with-the-art-worlds-favourite-rapper/)

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
<details><summary>smh.com.au (1)</summary>

- [Surreal virtual reality show TERMINUS moves viewers to tears, Sydney Morning Herald, 2018](https://www.smh.com.au/entertainment/art-and-design/surreal-virtual-reality-show-terminus-moves-viewers-to-tears-20180507-p4zds4.html)

</details>
<details><summary>smoothware.com (1)</summary>

- [Daniel Rozin, artist website (smoothware.com), links Angles Mirror to bitforms](http://www.smoothware.com/danny/)

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
<details><summary>soundtrackcity.nl (1)</summary>

- [Expeditie – Sonic Fields Vlieland, Soundtrackcity](https://soundtrackcity.nl/expeditie-sonic-fields-vlieland/)

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
<details><summary>spikeisland.org.uk (1)</summary>

- [Haroon Mirza: /\|/\|/\|/\|/\|/\|/\|/\|/\|/\|/\|/\|/\|/\|/\|/\| – Spike Island](https://www.spikeisland.org.uk/programme/exhibitions/haroon-mirza/)

</details>
<details><summary>spinmagazine.com (1)</summary>

- [Yung Jake, Video Prankster and Meta-Rapper, Turns the Hustle into Art - SPIN](https://www.spinmagazine.com/2013/11/yung-jake-internet-rap-embedded-datamosh/)

</details>
<details><summary>sportstimemacine.blogspot.com (1)</summary>

- ['English Video has Released', post by Hakase Inukai, Sports Time Machine project blog (19 March 2014)](https://sportstimemacine.blogspot.com/2014/03/english-video-has-released.html)

</details>
<details><summary>standardmedia.co.ke (1)</summary>

- [The Standard, 'Art installation, Labyrinth, explores prison that is our life' (2015)](https://www.standardmedia.co.ke/arts-culture/article/2000149951)

</details>
<details><summary>starts-prize-call.aec.at (2)</summary>

- [The Founders Pillars – S+T+ARTS Prize Africa 2025, Award of Distinction](https://starts-prize-call.aec.at/2025/winners/19515)
- [Written To Not Remain – S+T+ARTS Prize 2025 winners page](https://starts-prize-call.aec.at/2025/winners/16956)

</details>
<details><summary>starts-prize.aec.at (10)</summary>

- [I'm Humanity, S+T+ARTS Prize 2017 Grand Prize – Artistic Exploration](https://starts-prize.aec.at/en/im-humanity/)
- [Maria CHOIR — S+T+ARTS Prize 2024, Honorary Mention (Ars Electronica)](https://starts-prize.aec.at/maria-choir)
- [METABOLICA — S+T+ARTS Prize 2024, Honorary Mention](https://starts-prize.aec.at/metabolica)
- [MetaPhase, S+T+ARTS Prize 2023 (Honorary Mention)](https://starts-prize.aec.at/en/?p=4641)
- [Oceans in Transformation, S+T+ARTS Prize 2021 Grand Prize – Artistic Exploration](https://starts-prize.aec.at/de/?p=3587)
- [S+T+ARTS Prize 2019: Wastelands (nomination)](https://starts-prize.aec.at/de/?p=2399)
- [S+T+ARTS Prize 2021 winners (pool source)](https://starts-prize.aec.at/en/winners2021/)
- [S+T+ARTS Prize winners 2023 (pool source)](https://starts-prize.aec.at/en/winners2023/)
- [S+T+ARTS Prize winners 2024](https://starts-prize.aec.at/en/winners2024/)
- [VFRAME: Visual Forensics and Advanced Metadata Extraction, S+T+ARTS Prize 2018 (nomination)](https://starts-prize.aec.at/en/?p=1639)

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
<details><summary>statepress.com (1)</summary>

- [An 'Octopus' is being used at ASU's Project Space to start discussion on Guatemalan immigration, The State Press](https://www.statepress.com/article/2015/09/yoshua-okon-octopus-coming-to-asu)

</details>
<details><summary>stimuleringsfonds.nl (1)</summary>

- [Nothing to see here - Creative Industries Fund NL (Stimuleringsfonds)](https://www.stimuleringsfonds.nl/en/projects/nothing-to-see-here)

</details>
<details><summary>stinejanvin.cargo.site (1)</summary>

- [Fake Synthetic Music - stinejanvin (artist's site)](https://stinejanvin.cargo.site/Fake-Synthetic-Music)

</details>
<details><summary>stirworld.com (8)</summary>

- [Artist Yuko Mohri on creating work with a focus on ecological consciousness (STIRworld)](https://www.stirworld.com/inspire-people-artist-yuko-mohri-on-creating-work-with-a-focus-on-ecological-consciousness)
- [Designing creative futures with Sri Lanka's Fold Media Collective, STIRworld](https://www.stirworld.com/see-features-designing-creative-futures-with-sri-lanka-s-fold-media-collective)
- [Exploring intermediality in the creative practice of artist Sarah Choo Jing - STIR](https://www.stirworld.com/see-features-exploring-intermediality-in-the-creative-practice-of-artist-sarah-choo-jing)
- [Hira Nabi on the technique of slow cinema to narrate the human cost of development, STIRworld](https://www.stirworld.com/inspire-people-hira-nabi-on-the-technique-of-slow-cinema-to-narrate-the-human-cost-of-development)
- [Sammy Baloji shows us the frame – STIR (review of Goldsmiths CCA exhibition)](https://www.stirworld.com/see-features-sammy-baloji-shows-us-the-frame)
- [STIR, 'Embodied responses to climate emergencies at the Lahore Biennale 2024'](https://www.stirworld.com/think-opinions-embodied-responses-to-climate-emergencies-at-the-lahore-biennale-2024)
- [STIR, Harshit Agrawal's Exo-stential is India's first solo artificial intelligence art show](https://www.stirworld.com/see-features-harshit-agrawals-exo-stential-is-india-s-first-solo-artificial-intelligence-art-show)
- [STIR: From cartography to code – architectures of power at the Venice Biennale 2025](https://www.stirworld.com/see-features-from-cartography-to-code-architectures-of-power-at-the-venice-biennale-2025)

</details>
<details><summary>storage.googleapis.com (1)</summary>

- [Once Upon A Garden: The Complete Series — fact sheet (PDF)](https://storage.googleapis.com/fellowship-2022/Linda%20Dounia%20Once%20Upon%20A%20Garden/files/Linda%20Dounia%20-%20Once%20Upon%20A%20Garden%20FactSheet.pdf)

</details>
<details><summary>strutsgallery.ca (1)</summary>

- [Sound Installation \| SQUEEEQUE by Alexis O'Hara — Struts Gallery / Sappyfest, 2025](https://www.strutsgallery.ca/post/sound-installation-squeeeque-by-alexis-o-hara)

</details>
<details><summary>studio.camp (3)</summary>

- [Het Parool, 19 March 2019, p. 14 (review, Dutch, PDF on studio.camp)](https://www.studio.camp/files/HetParool-19maart2019.p14_.pdf)
- [In Cameras Res at De Appel Amsterdam, studio.camp](https://studio.camp/events/incamerasres)
- [In Cameras Res, 2019, studio.camp](https://studio.camp/works/incameras)

</details>
<details><summary>studiointernational.com (7)</summary>

- [Charles Lim: 'It's very easy to see the sea as a sublime space where you can even find God' — Studio International](https://www.studiointernational.com/charles-lim-sea-state-singapore-pavilion-venice-biennale-2015-video-interview)
- [Jompet Kuswidananto interview: Order and After, Sonica 2015 - Studio International](https://studiointernational.com/jompet-kuswidananto-interview-order-and-after-sonica-2015)
- [Larissa Sansour – interview, Studio International (2019)](https://www.studiointernational.com/larissa-sansour-interview-danish-pavilion-venice-biennale-2019)
- [Rafaël Rozendaal interview, Studio International](https://www.studiointernational.com/rafael-rozendaal-interview-dutch-brazilian-visual-artist-websites-internet-haiku-new-york/)
- [Sammy Baloji: 'I'm not interested in colonialism as a thing of the past…' – Studio International](https://www.studiointernational.com/sammy-baloji-im-not-interested-in-colonialism-as-a-thing-of-the-past-but-in-continuation-of-that-system)
- [Studio International – Cheng Ran: Diary of a Madman review](https://www.studiointernational.com/cheng-ran-diary-of-a-madman-review-new-museum-new-york)
- [Studio International — Jonathas de Andrade, Brazil Pavilion, Venice Biennale 2022 video interview](https://www.studiointernational.com/jonathas-de-andrade-brazil-pavilion-venice-biennale-2022-video-interview)

</details>
<details><summary>subbacultcha.nl (1)</summary>

- [An interview with KMRU (Subbacultcha)](https://subbacultcha.nl/2023/02/01/an-interview-with-kmru/)

</details>
<details><summary>suhuiyu-neo.pages.dev (1)</summary>

- [Su Hui-Yu – The Glamorous Boys of Tang](https://suhuiyu-neo.pages.dev/works/the-glamorous-boys-of-tang/)

</details>
<details><summary>sundance.org (3)</summary>

- [2013 Sundance Film Festival announces films in Spotlight, Park City at Midnight and New Frontier](https://www.sundance.org/blogs/2013-sundance-film-festival-announces-films-in-spotlight-park-city-at-midnight-and-new-frontier-3/)
- [2019 Sundance Film Festival New Frontier lineup, sundance.org](https://www.sundance.org/blogs/2019-sundance-film-festival-new-frontier-lineup-announced-3/)
- [Chris Milk: Pioneering the New Frontier - Sundance Institute](https://www.sundance.org/blogs/chris-milk-pioneering-the-new-frontier-3/)

</details>
<details><summary>sunlightsoilshit.systems (1)</summary>

- [Sunlight Soil & Shit (De)Cycle project website](https://sunlightsoilshit.systems/)

</details>
<details><summary>swissfilms.ch (1)</summary>

- [Interlooped - Swiss Films](https://swissfilms.ch/en/movie/interlooped/5FE31AB065EC4D07BCF20D9A2932F352)

</details>
<details><summary>symbiotica.uwa.edu.au (1)</summary>

- [3SDC, SymbioticA exhibitions](https://www.symbiotica.uwa.edu.au/activities/exhibitions/3sdc)

</details>
<details><summary>symposiumbsp.com (1)</summary>

- [Artist 2026: Paolo Almario – Symposium of Baie-Saint-Paul](https://symposiumbsp.com/en/artists/2026/paolo-almario-90)

</details>
<details><summary>taishinart.org.tw (1)</summary>

- [Taishin Arts Award 2018 – The Glamorous Boys of Tang (1985, Chui Kang-Chien)](https://taishinart.org.tw/en/art-award-year-detail/2018/558)

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
<details><summary>tank.tv (1)</summary>

- [Sammy Baloji – interview by Matteo Pini, TANK issue 101](https://tank.tv/magazine/issue-101/talks/sammy-baloji)

</details>
<details><summary>tanpinpin.com (2)</summary>

- [80km/h (2004), artist website](https://tanpinpin.com/art/80km-per-hour)
- [On a Clear Day You Can See Forever, artist website](https://tanpinpin.com/art/oacd)

</details>
<details><summary>tanyabonakdargallery.com (1)</summary>

- [Wong Ping: Puberty : The Art Gallery of Western Australia — Tanya Bonakdar Gallery](https://www.tanyabonakdargallery.com/exhibitions/662-wong-ping-puberty-the-art-gallery-of-western-australia-agwa/)

</details>
<details><summary>tate.org.uk (4)</summary>

- [Candice Breitz: Love Story, Tate Liverpool, 2022–23](https://www.tate.org.uk/whats-on/tate-liverpool/candice-breitz-love-story)
- [Lawrence Abu Hamdan: Walled Unwalled, Tate Modern (2018)](https://www.tate.org.uk/whats-on/tate-modern/lawrence-abu-hamdan-walled-unwalled)
- [Understanding In Search of Vanished Blood — Tate](https://www.tate.org.uk/art/artists/nalini-malani-14670/understanding-in-search-of-vanished-blood)
- [Wantee and Friends - performance, Tate Britain, 27 April 2013](https://www.tate.org.uk/whats-on/tate-britain/wantee-and-friends)

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
<details><summary>techcrunch.com (1)</summary>

- [With Dispatch, Here Be Dragons pushes narrative VR storytelling in bold new directions, TechCrunch](https://techcrunch.com/2017/11/21/with-dispatch-here-be-dragons-pushes-narrative-vr-storytelling-in-bold-new-directions/)

</details>
<details><summary>tenderphoto.substack.com (1)</summary>

- [Tender Photo – Dear Someone Somewhere in Angola (statement by Helena Uambembe)](https://tenderphoto.substack.com/p/helena-uambembe)

</details>
<details><summary>terencebroad.com (1)</summary>

- [Blade Runner—Autoencoded, terencebroad.com](http://terencebroad.com/autoencodingbladerunner.html)

</details>
<details><summary>terremoto.mx (3)</summary>

- [Fernando Palma in conversation with Malachi Farrell - Terremoto](https://terremoto.mx/revista/fernando-palma-in-conversation-with-malacchi-farrell/)
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
<details><summary>the-berliner.com (2)</summary>

- [Beeple On Navigating the Post-Internet Art World - The Berliner](https://www.the-berliner.com/art/beeple-regular-animals-art-exhibition-neue-nationalgalerie/)
- [Halil Altindere interview, The Berliner (2016)](https://www.the-berliner.com/art/halil-altindere-interview/)

</details>
<details><summary>theage.com.au (1)</summary>

- [Andrew Stephens, 'In the spirit of mischief', The Age, 19 January 2013](https://www.theage.com.au/entertainment/art-and-design/in-the-spirit-of-mischief-20130118-2cxyf.html)

</details>
<details><summary>theartnewspaper.com (11)</summary>

- [A chimeric creature descends on New York's Meatpacking District, The Art Newspaper, 2023](https://www.theartnewspaper.com/2023/09/25/a-chimeric-creature-descends-on-new-yorks-meatpacking-district)
- [Ho Tzu Nyen on how AI leads to the cinematic past (The Art Newspaper)](https://www.theartnewspaper.com/2025/03/28/ho-tzu-nyen-on-how-ai-leads-to-the-cinematic-past)
- [Korakrit Arunanondchai: on loss, shamanism—and denim — The Art Newspaper](https://www.theartnewspaper.com/2021/09/24/korakrit-arunanondchai-on-loss-shamanismand-denim)
- [Rashid Rana: transfiguring history – The Art Newspaper](https://www.theartnewspaper.com/2017/03/15/rashid-rana-transfiguring-history)
- [The Art Newspaper – Sharjah Biennial 15 delivers important postcolonial narrative but loses its experimental edge](https://www.theartnewspaper.com/2023/02/20/sharjah-biennial-15-delivers-important-postcolonial-narrativebut-loses-its-experimental-edge)
- [The Art Newspaper – siren eun young jung: I believe in art that is able to visualise those erased by society](https://www.theartnewspaper.com/2024/06/19/siren-eun-young-jung-i-believe-in-art-that-is-able-to-visualise-those-erased-by-society)
- [The Art Newspaper – Zineb Sedira reveals plans for pavilion focused on activist filmmaking](https://www.theartnewspaper.com/2022/02/22/artist-zineb-sedira-reveals-concept-for-cinematographic-installation-at-the-french-pavilion-in-venice)
- [The Art Newspaper — Brazilian pavilion taking on the country's recent tragedies](https://www.theartnewspaper.com/2022/04/11/brazilian-pavilion-taking-on-the-countrys-recent-tragedies)
- [The Art Newspaper — Hong Kong artists create a poetic moment in Venice](https://www.theartnewspaper.com/2026/11/04/hong-kong-artists-create-a-poetic-moment-in-venice)
- [The Art Newspaper — Mayunkiki on bringing her Ainu culture to a wider audience at Art Basel Hong Kong](https://www.theartnewspaper.com/2025/03/27/mayunkiki-on-bringing-her-ainu-culture-to-a-wider-audience-at-art-basel-hong-kong)
- [Tim Schneider, Beware the technology rat trap: Cooper Jacoby’s standout contribution to New York’s Whitney Biennial (The Art Newspaper, 7 May 2026)](https://www.theartnewspaper.com/2026/05/07/beware-the-technology-rat-trap-cooper-jacobys-standout-contribution-to-new-yorks-whitney-biennial)

</details>
<details><summary>theatticmag.com (1)</summary>

- [AUDIO: Stine Janvin Motland live in Riga, Latvia - The Attic](https://theatticmag.com/news/1810/audio:-stine-janvin-motland-live-in-riga,-latvia.html)

</details>
<details><summary>theaureview.com (1)</summary>

- [Jompet Kuswidananto's installation After Voices to open at SCAF - The AU Review](https://theaureview.com/?p=83362)

</details>
<details><summary>thefader.com (1)</summary>

- [Holly Herndon on the power of machine learning and developing her 'digital twin' Holly+ — The FADER](https://www.thefader.com/2021/07/27/holly-herndon-on-the-power-of-machine-learning-and-developing-her-digital-twin-holly)

</details>
<details><summary>thefridaytimes.com (1)</summary>

- [Whither authenticity? (Iftikhar Dadi interviewed by Ammara Ahmad), The Friday Times, 2018](https://www.thefridaytimes.com/2018/05/04/whither-authenticity/)

</details>
<details><summary>theguardian.com (5)</summary>

- [Chiwoniso Kaitano, The Afrofuturism of Wangechi Mutu - The Guardian, 2013](https://www.theguardian.com/world/2013/nov/13/wangechi-mutu-art-afrofuturism)
- [Laure Prouvost wins Turner prize 2013 (The Guardian, 2 December 2013)](https://www.theguardian.com/artanddesign/2013/dec/02/laure-prouvost-wins-turner-prize-2013-derry)
- [Leave me your DNA … and I'll 3D-print your face, Eleonore Pauwels, The Guardian, 2013](https://www.theguardian.com/commentisfree/2013/jun/01/dna-art-recreate-faces)
- [Living in the Momentum: Barbican unveils latest free art installation (The Guardian, 2014)](https://www.theguardian.com/artanddesign/2014/feb/12/momentum-barbican-art-installation-curve-gallery)
- [The maddest house party ever – Ragnar Kjartansson on making The Visitors (The Guardian, 2019)](https://www.theguardian.com/artanddesign/2019/sep/17/ragnar-kjartansson-the-visitors-best-art-work-21st-century)

</details>
<details><summary>theintercept.com (1)</summary>

- [The Intercept: Best of Luck With the Wall (Josh Begley, 2016)](https://theintercept.com/2016/10/26/best-of-luck-with-the-wall/)

</details>
<details><summary>thekarachicollective.com (1)</summary>

- [Will You Listen, When the Sea Returns With the Waters of a Distant Memory? (Maham Chiragh, The Karachi Collective, on the 2025 solo show 'Goa last night I dreamed I touched you...')](https://thekarachicollective.com/will-you-listen-when-the-sea-returns-with-the-waters-of-a-distant-memory/)

</details>
<details><summary>thelisapark.com (1)</summary>

- [Eunoia, thelisapark.com](https://www.thelisapark.com/work/eunoia)

</details>
<details><summary>themarkaz.org (1)</summary>

- [The Markaz Review – The Majesty and Mystery of Nature: Ali Cherri's Dam in Sudan](https://themarkaz.org/the-majesty-and-mystery-of-nature-ali-cherris-dam-in-sudan)

</details>
<details><summary>themodel.ie (1)</summary>

- [Interview with Elizabeth Price, The Model, Sligo](https://themodel.ie/?p=971)

</details>
<details><summary>thenationalnews.com (4)</summary>

- [Gulf War inspired Iraqi artist's camera implant, The National](https://www.thenationalnews.com/world/mena/gulf-war-inspired-iraqi-artist-s-camera-implant-1.553765)
- [Noor Riyadh 2025 charts the city's shifting landscape through light and memory – The National](https://www.thenationalnews.com/arts-culture/art-design/2025/11/24/noor-riyadh-2025-charts-the-citys-shifting-landscape-through-light-and-memory)
- [Saudi Arabia's Muhannad Shono introduces his monster at the Venice Biennale, The National, 2022](https://thenationalnews.com/arts-culture/art/2022/04/25/saudi-arabias-muhannad-shono-introduces-his-monster-at-the-venice-biennale)
- [The National – Saudi artist Manal AlDowayan unveils new piece of land art addressing water scarcity in Al Ula](https://www.thenationalnews.com/arts-culture/art/saudi-artist-manal-aldowayan-unveils-new-piece-of-land-art-addressing-water-scarcity-in-alula-1.971513)

</details>
<details><summary>thenew.institute (1)</summary>

- [From Syria to Ukraine, THE NEW INSTITUTE (2022)](https://thenew.institute/en/media/beyond-the-war/from-syria-to-ukraine)

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
<details><summary>theseenjournal.org (1)</summary>

- [Refiguring Monstrosity: Morehshin Allahyari, The Seen (interview by Joel Kuennen)](https://theseenjournal.org/?p=14976)

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
<details><summary>thewhitereview.org (2)</summary>

- [Interview with Korakrit Arunanondchai — The White Review](https://www.thewhitereview.org/feature/interview-with-korakrit-arunanondchai)
- [Interview with Laure Prouvost - The White Review](https://www.thewhitereview.org/feature/interview-with-laure-prouvost/)

</details>
<details><summary>thisiscolossal.com (1)</summary>

- [Interactive Mirrors Built from Arrays of Moving Objects by Daniel Rozin, Colossal, 2014](https://www.thisiscolossal.com/2014/02/interactive-mirrors-built-from-arrays-of-moving-objects-by-daniel-rozin/)

</details>
<details><summary>thisispaper.com (1)</summary>

- [REPETAE Series by Sasha Stiles — Thisispaper](https://www.thisispaper.com/mag/repetae-series-sasha-stiles)

</details>
<details><summary>thomasfeuerstein.net (3)</summary>

- [FROM HAND TO MOUTH, 2023 — METABOLICA / Chapter 5 (artist's website)](https://www.thomasfeuerstein.net/05_METABOLICA/60_CHAPTER_5/62_FROM_HAND_TO_MOUTH)
- [METABOLICA / Metabolic-Art (artist's website)](https://www.thomasfeuerstein.net/05_METABOLICA/10_METABOLICA/20_METABOLIC-ART)
- [METABOLICA project text, artist's website (thomasfeuerstein.net)](https://www.thomasfeuerstein.net/05_METABOLICA/10_METABOLICA/30_METABOLIC-ART)

</details>
<details><summary>time.com (2)</summary>

- [The Miraculous Trees That Could Save Pakistan's Largest City from Climate Disaster — TIME](https://time.com/6189898/mangrove-trees-pakistan-climate/)
- [TIME, Next Generation Leaders: Selly Raby Kane](https://time.com/collections/next-generation-leaders/5692975/selly-raby-kane-next-generation-leaders/)

</details>
<details><summary>timeslive.co.za (2)</summary>

- [Bubu Ogisi reimagines clothing as ‘memory banks’ (TimesLive)](https://www.timeslive.co.za/lifestyle/fashion/2026-08-31-from-fabric-to-archive-with-iamisigo/)
- [Love in a time of murder - Sunday Times (TimesLIVE), 2011](https://www.timeslive.co.za/sunday-times/lifestyle/2011-07-17-love-in-a-time-of-murder/)

</details>
<details><summary>timessquarenyc.org (9)</summary>

- [Announcing Marina Zurkow and James Schmitz — Times Square Arts](https://www.timessquarenyc.org/news-and-press-releases/announcing-marina-zurkow-and-james-schmitz)
- [Our Islands — TSQ Arts Midnight Moment (Times Square Alliance)](https://www.timessquarenyc.org/tsq-arts-projects/our-islands-11deg1658-4-n-123deg4507-0-e)
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
<details><summary>tokafi.com (1)</summary>

- [Interview with Jana Winderen, Tokafi](http://www.tokafi.com/15questions/interview-jana-winderen)

</details>
<details><summary>tokyoartbeat.com (2)</summary>

- [Tokyo Art Beat — Aichi 2025 report 2 (Seto venues)](https://www.tokyoartbeat.com/articles/-/aichi-2025-report-2-202509)
- [Yuko Mohri and Sook-Kyung Lee Discuss Japan Pavilion at the 60th Venice Biennale (Tokyo Art Beat)](https://www.tokyoartbeat.com/en/articles/-/sook-kyung-lee-yuko-mohri-venice-biennale-interview-en-202406)

</details>
<details><summary>tokyoartsandspace.jp (2)</summary>

- [Tokyo Arts and Space — Joaquín ARAS creator page](https://www.tokyoartsandspace.jp/en/creator/index/A/1677.html)
- [YAMAMOTO Yoshihiro, creator page, Tokyo Arts and Space](https://tokyoartsandspace.jp/en/creator/index/Y/1088.html)

</details>
<details><summary>tokyoupdates.metro.tokyo.lg.jp (1)</summary>

- [An Experimental Café in Nihombashi where Avatar Robots Facilitate Human Connections, Tokyo Updates](https://www.tokyoupdates.metro.tokyo.lg.jp/en/post-785)

</details>
<details><summary>tommysimoens.com (1)</summary>

- [Tommy Simoens – David Shongo, Café Kuba](https://tommysimoens.com/portfolio-2-portfolio/cafekube/)

</details>
<details><summary>torinofilmfest.org (1)</summary>

- [Walled Unwalled, 36th Torino Film Festival](https://www.torinofilmfest.org/en/36-torino-film-festival/film/walled-unwalled/37735/)

</details>
<details><summary>torontobiennial.org (2)</summary>

- [Fernando Palma Rodríguez - artist page, Toronto Biennial of Art](https://torontobiennial.org/artist/fernando-palma-rodriguez/)
- [Fernando Palma Rodríguez at 259 Lake Shore Blvd E - Toronto Biennial of Art (2019)](https://torontobiennial.org/artist-contributor/fernando-palma-rodriguez/)

</details>
<details><summary>tportmarket.com (1)</summary>

- [T-Port — Le Miroir](https://tportmarket.com/films/le-miroir/)

</details>
<details><summary>transformmagazine.net (1)</summary>

- [Transform magazine: Five minutes with James Paterson (2020)](https://transformmagazine.net/articles/2020/five-minutes-with-james-paterson)

</details>
<details><summary>tribecafilm.com (5)</summary>

- [Hero, Tribeca Film Festival 2018](https://tribecafilm.com/films/hero-2018)
- [The Power Loom and The Founders Pillars – 2025 Tribeca Festival](https://tribecafilm.com/films/power-loom-and-the-founders-pillars-2025)
- [There Goes Nikki - Tribeca Festival 2025 film page](https://tribecafilm.com/festival/archive/there-goes-nikki-2025)
- [Tribeca Festival 2025 announces Immersive program 'In Search of Us' (press release)](https://www.tribecafilm.com/press-center/festival/press-releases/tribeca-festival-2025-announces-immersive-program-in-search-of-us-in-partnership-with-onassis-onx-and-agog)
- [Tribeca Film Festival archive, 'The Other Dakar' (2017)](https://tribecafilm.com/festival/archive/other-dakar-2017)

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
<details><summary>ufrgs.br (1)</summary>

- [Odiolândia - ConectartBR (UFRGS)](https://www.ufrgs.br/conectartbr/odiolandia/)

</details>
<details><summary>undisciplinedartist.com (1)</summary>

- [Karim Ben Khelifa - artist's site (Manifesto, Works)](https://www.undisciplinedartist.com/)

</details>
<details><summary>unframed.lacma.org (1)</summary>

- [The Character of Characters: Xu Bing's Exploration of Chinese and Their Language, LACMA Unframed (2015)](https://unframed.lacma.org/node/1560)

</details>
<details><summary>uploadvr.com (3)</summary>

- [Emperor Shows Narrative VR’s Emotive Potential (UploadVR)](https://uploadvr.com/empereur-vr-venice-immersive-impressions)
- [Hotel Infinity Started As Manifold Garden In VR - UploadVR](https://uploadvr.com/hotel-infinity-started-as-manifold-garden-in-vr)
- [Oculus and Here Be Dragons debut VR miniseries Dispatch, UploadVR](https://uploadvr.com/oculus-dragons-debut-vr-miniseries-dispatch)

</details>
<details><summary>uqac.ca (1)</summary>

- [Louis-Philippe Rondeau - UQAC portfolio](https://www.uqac.ca/portfolio/louisphilipperondeau/)

</details>
<details><summary>ursuladamm.de (2)</summary>

- [Chromatographic Ballads / NCO – Ursula Damm (follow-up work, algorithm description)](https://ursuladamm.de/nco-neural-chromatographic-orchestra-2012/)
- [Transits \[2012\] – Ursula Damm (artist's website, with credits)](https://ursuladamm.de/transits-2012)

</details>
<details><summary>usaartnews.com (1)</summary>

- [Artist Nancy Baker Cahill's New A.R. Work Unleashes a Surreal Interspecies Creature on the Terrace of the Whitney Museum (Artnet News, republished by USA Art News)](https://usaartnews.com/news/artist-nancy-baker-cahills-new-ar-work-unleashes-a-surreal-interspecies-creature-on-the-terrace-of-the-whitney-museum)

</details>
<details><summary>uva.co.uk (1)</summary>

- [Momentum / UVA (uva.co.uk)](https://www.uva.co.uk/features/momentum-barbican-curve-gallery)

</details>
<details><summary>v.daum.net (1)</summary>

- [Diriyah Biennale review (Korea JoongAng Daily via Daum)](https://v.daum.net/v/20260216160202847)

</details>
<details><summary>v1.chroniques.org (1)</summary>

- [TROPICS, Chroniques](https://v1.chroniques.org/en/oeuvre/tropics/)

</details>
<details><summary>v1b3.com (1)</summary>

- [Christine Marie, Antiquated A.R., v1b3](https://v1b3.com/?p=2921)

</details>
<details><summary>valieexportcenter.at (1)</summary>

- [VALIE EXPORT Center Linz – Claudia Larcher](https://www.valieexportcenter.at/en/claudia-larcher)

</details>
<details><summary>vaslart.org (1)</summary>

- [All that Perishes on the Edge of Land, Vasl Artists' Association](https://vaslart.org/all-that-perishes-on-the-edge-of-land)

</details>
<details><summary>vdb.org (1)</summary>

- [Video Data Bank, 'Hidirtina (Sisters)'](https://www.vdb.org/titles/hidirtina-sisters)

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
<details><summary>venti-journal.com (1)</summary>

- [Marc Higgin and Anaïs Tondeur, 'The Sky in Us', Venti Journal](https://www.venti-journal.com/higgin-and-tondeur)

</details>
<details><summary>vernissage.tv (2)</summary>

- [Ayse Erkmen: Plan B. Venice Biennale 2011 (video interview, VernissageTV)](https://vernissage.tv/2011/06/03/ayse-erkmen-plan-b-venice-biennale-2011/)
- [Pavlina Vagioni: Oikeiōsis (Kinship) / Hellenic Diaspora Foundation in Venice, VernissageTV](https://vernissage.tv/2026/07/09/pavlina-vagioni-oikeiosis-kinship-hellenic-diaspora-foundation-in-venice/)

</details>
<details><summary>vframe.io (1)</summary>

- [About, vframe.io](https://vframe.io/about/)

</details>
<details><summary>vice.com (7)</summary>

- [Brain Activity As Augmented By Kinect And Neon Lights — VICE (source\_url)](https://www.vice.com/en/article/brain-activity-as-augmented-by-kinect-and-neon-lights)
- [Eunoia: Seeking Enlightenment By Tracking Brainwaves, The Creators Project (Vice)](https://www.vice.com/en/article/eunoia-seeking-enlightenment-by-tracking-brainwaves/)
- [Holly Herndon Deepfaked Herself Into a 'Digital Twin' That Sings Any Song In Her Voice — Vice](https://www.vice.com/en/article/holly-herndon-deepfaked-herself-into-a-digital-twin-that-sings-any-song-in-her-voice/)
- [How It Works: Chris Milk's The Treachery of Sanctuary - VICE / The Creators Project](https://www.vice.com/en/article/how-it-works-chris-milks-ithe-treachery-of-sanctuaryi)
- [Quayola And Memo Akten Translate Athletic Movements Into Abstract Animations — VICE / The Creators Project](https://www.vice.com/en/article/quayola-and-memo-akten-translate-athletic-movements-into-abstract-animations/)
- [User Preferences: A Tech Q&A With David Bowen (VICE)](https://www.vice.com/en/article/user-preferences-a-tech-qa-with-david-bowen)
- [Weaponizing Our Faces: An Interview with Zach Blas — VICE](https://www.vice.com/en/article/weaponizing-our-faces-an-interview-with-zach-blas-715)

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
<details><summary>vimeo.com (12)</summary>

- [360° Nairobi Berries trailer – Vimeo](https://vimeo.com/219198351)
- [A Onda Traz, O Vento Leva, Vimeo (synopsis, credits, festival list)](https://vimeo.com/41848159)
- [Displuvium — video (Vimeo)](https://vimeo.com/323682277)
- [Máquina Stella, Marcela Armas (Vimeo)](https://vimeo.com/118967086)
- [Parasitic / Symbiotic (Vimeo video)](https://vimeo.com/165567995)
- [Scanning (trailer) – Vimeo](https://vimeo.com/80993394)
- [Shelter - Carl Burton on Vimeo](https://vimeo.com/37156003)
- [Sky Brought Down (2017) (Vimeo video)](https://vimeo.com/322340478)
- [Thank you for your souvenir, UK! (Vimeo, uploaded by Lin Los)](https://vimeo.com/865067540)
- [The Great Indecision Council - video (Vimeo, linked from the Ars Electronica entry)](https://vimeo.com/288438943)
- [The Half \_ Intermedia Chef — Vimeo](https://vimeo.com/62248561)
- [The Treachery of Sanctuary - Vimeo](https://vimeo.com/39178089)

</details>
<details><summary>vimooz.com (1)</summary>

- [Sundance Film Festival 2018 New Frontier lineup, Vimooz](https://vimooz.com/2017/12/06/sundance-film-festival-2018-new-frontier-lineup/)

</details>
<details><summary>virtualshoemuseum.com (1)</summary>

- [Healing Fukushima (Nanohana Heels) — Virtual Shoe Museum](https://virtualshoemuseum.com/?p=43044)

</details>
<details><summary>visionsdureel.ch (1)</summary>

- [Spray and Pray - Visions du Réel 2026](https://www.visionsdureel.ch/en/film/2026/spray-and-pray)

</details>
<details><summary>visualizingpalestine.org (1)</summary>

- [About, Visualizing Palestine](https://visualizingpalestine.org/about/)

</details>
<details><summary>visualmusicarchive.org (1)</summary>

- [Rheo, Visual Music Archive](https://visualmusicarchive.org/works/w/rheo.html)

</details>
<details><summary>vivienandersongallery.com (1)</summary>

- [Vivien Anderson Gallery, Hayley Millar Baker features in Hyperallergic](https://vivienandersongallery.com/hayley-millar-baker-features-in-hyperallergic/)

</details>
<details><summary>vogue.ph (1)</summary>

- [Martha Atienza: Island Story — Vogue Philippines](https://vogue.ph/lifestyle/art/martha-atienza-island-story-bantayan/)

</details>
<details><summary>voicesofaliveness.net (2)</summary>

- [Archive 2012 - Voices of Aliveness (French)](http://voicesofaliveness.net/2012/)
- [Masaki Fujihata, 'Concept - Voices of Aliveness 2012', voicesofaliveness.net](http://voicesofaliveness.net/concept/)

</details>
<details><summary>voicesofvr.com (16)</summary>

- [#1246: Smartphone Orchestra's "Emojiii" Cultivates Playful & Novel Group Social Dynamics - Voices of VR Podcast](https://voicesofvr.com/1246-smartphone-orchestras-emojiii-cultivates-playful-novel-group-social-dynamics/)
- [#1693: A Survey of the Indie Immersive Dome Community Trends with "The Rift" Directors & 4Pi Productions - Voices of VR Podcast](https://voicesofvr.com/1693-a-survey-of-the-indie-immersive-dome-community-trends-with-the-rift-directors-4pi-productions/)
- [#1770: Eastern Philosophy-Inspired Fusion of Theater and XR with 'Mnemosyne' (Voices of VR podcast, interview with Wuer)](https://voicesofvr.com/1770-eastern-philosophy-inspired-fusion-of-theater-and-xr-with-mnemosyne/)
- [#1773: "Collective Body" Assigns Elemental Avatars Based Upon Archetypal Dance Movements - Voices of VR Podcast](https://voicesofvr.com/1773-collective-body-assigns-elemental-avatars-based-upon-archetypal-dance-movements/)
- [#737: Looping Real-Time, Volumetric, Embodied Interactions with 'Interlooped' - Voices of VR Podcast](https://voicesofvr.com/737-looping-real-time-volumetric-embodied-interactions-with-interlooped/)
- [Voices of VR #1569: AR memorial of Nikki Giovanni (interview with Michèle Stephenson, Joe Brewster, idris brewster)](https://voicesofvr.com/1569-family-of-storytellers-creates-an-ar-memorial-of-black-poet-nikki-giovanni-with-epic-organic-garden-installation/)
- [Voices of VR #1572: The Innocence of Unknowing (interview with Ryat Yezbick & Milo Talwani)](https://voicesofvr.com/1572-the-innocence-of-unknowing-uses-socratic-dialogue-with-ai-video-essay-to-deconstruct-root-cases-of-gun-violence/)
- [Voices of VR #1632: iNK Stories 2018, Hero (Sundance 2018 interview)](https://voicesofvr.com/1632-ink-stories-2018-embodied-interactions-in-verite-vr-hero-on-bombing-aftermath/)
- [Voices of VR #1656: Kiira Benz Part 1, Runnin' (interview recorded 2019)](https://voicesofvr.com/1656-kiira-benz-part-1-runnin-large-scale-volumetric-music-video-2019)
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
<details><summary>vrt.be (1)</summary>

- [Metershoge hemeltoren ingehuldigd in Leuven (VRT NWS, 27 September 2014)](https://www.vrt.be/vrtnws/nl/2014/09/27/metershoge_hemeltoreningehuldigdinleuven-1-2102896/)

</details>
<details><summary>waag.org (2)</summary>

- [Biased Technology: Behind Shirley — Waag (interview with the artist)](https://waag.org/en/article/biased-technology-behind-shirley)
- [PL'AI: where plant and machine playfully meet — Waag (interview)](https://waag.org/en/article/plai-where-plant-and-machine-playfully-meet)

</details>
<details><summary>wademarynowsky.art (1)</summary>

- [The Acconci Robot (artist's website)](https://wademarynowsky.art/Acconci.html)

</details>
<details><summary>wafaabilal.com (1)</summary>

- [3rdi, wafaabilal.com](https://wafaabilal.com/thirdi/)

</details>
<details><summary>walkerart.org (2)</summary>

- [Sad Songs to Euphoria: Jompet Kuswidananto on the Making of Celestial Sorrow - Walker Art Center](https://walkerart.org/magazine/jompet-kuswidananto-meg-stuart-celestial-sorrow/)
- [Yto Barrada: Cinémathèque Tangier - Walker Art Center](https://www.walkerart.org/reader/yto-barrada-cinematheque-tangier/)

</details>
<details><summary>wallpaper.com (1)</summary>

- [Artist Julianknxx on poetry, dreams and Switzerland – Wallpaper\*](https://wallpaper.com/art/julianknxx-in-a-dream-we-are-once-beautiful)

</details>
<details><summary>wamda.com (1)</summary>

- [Visualizing Palestine unites activism and entrepreneurship, Wamda](https://www.wamda.com/en/2013/10/visualizing-palestine-infographics-activism-entrepreneurship)

</details>
<details><summary>wantedonline.co.za (1)</summary>

- [Wanted Online interview (2017)](https://www.wantedonline.co.za/art-design/2017-02-27-famed-dakar-designer-to-mastermind-design-indabas-first-ever-after-hours-event/)

</details>
<details><summary>we-make-money-not-art.com (2)</summary>

- [PL’AI. An AI robot created to play with cucumber plants — We Make Money Not Art](https://we-make-money-not-art.com/?p=35638)
- [We Make Money Not Art: Order+Noise, a tug of war for motors, strings and rubber bands (Q&A)](https://we-make-money-not-art.com/ordernoise-a-tug-of-war-for-motors-strings-and-rubber-bands/)

</details>
<details><summary>web.archive.org (47)</summary>

- [$1 Bills Defaced With Occupy Wall Street Charts, Fast Company](https://web.archive.org/web/2012/https://www.fastcompany.com/1678641/1-bills-defaced-with-occupy-wall-street-charts)
- ['About necomimi', neurowear project page (Wayback Machine, 31 December 2013)](http://web.archive.org/web/20131231051830/http://neurowear.com/projects_detail/necomimi.html)
- ['Concept' page, Nagasaki Archive site (Wayback Machine, 13 December 2013)](http://web.archive.org/web/20131213084740/http://e.nagasaki.mapping.jp/p/concept.html)
- ['Japan Earthquake' page, Nagasaki Archive / Archives Series site (Wayback Machine, 13 December 2013)](http://web.archive.org/web/20131213084726/http://e.nagasaki.mapping.jp/p/japan-earthquake.html)
- [55th Venice Biennale, Exclusive Interview: Glenda Leon / Cuban Pavilion, Uprising Art (archived)](https://web.archive.org/web/20141214124406/http://blog.uprising-art.com/en/55th-venice-biennale-exclusive-interview-glenda-leon-cuban-pavilion-2/)
- [Acoustic Encounters: Magdi Mostafa in conversation with Clelia Coussonnet, Ibraaz (2016)](https://web.archive.org/web/20211203154458/https://www.ibraaz.org/usr/library/documents/main/acoustic-encounters.pdf)
- [Artist Turns Mother's Old Sketches Of Inventions Into Surreal Performance Art (Huffington Post, 2014; archived)](https://web.archive.org/web/20160409201832/http://www.huffingtonpost.com/2014/01/24/jacolby-satterwhite_n_4639876.html?utm_hp_ref=tw)
- [Awakening, Singapore Night Festival 2025 programme page (Wayback Machine copy; live page now 404)](https://web.archive.org/web/20251015060459/https://www.heritage.sg/sgnightfest/whats-on/awakening)
- [Award Winner Interview: Ng'endo Mukii – Encounters Film Festival (archived)](http://web.archive.org/web/20180606185224/http://encounters-festival.org.uk:80/immersive-encounters-award-winner-interview-ngendo-mukii/)
- [Big Red & Shiny – STAND UP: Silvi Naçi in conversation with Furen Dai (Wayback Machine copy)](http://web.archive.org/web/20220909214351/https://bigredandshiny.org/32531/stand-up-silvi-naci-in-conversation-with-furen-dai/)
- [British Council Voices: interview with James Paterson (December 2017, Wayback Machine copy)](https://web.archive.org/web/2020/https://www.britishcouncil.org/voices-magazine/how-do-virtual-reality-animators-find-communities-audiences)
- [Bulletproof Skin Made From Spider Silk, Discovery News, 2011 (Wayback Machine)](https://web.archive.org/web/20160310020238/http://news.discovery.com/tech/biotechnology/bullet-proof-skin-110820.htm)
- [Cesar Harada: A novel idea for cleaning up oil spills, TEDxSummit 2012 (TED.com, Wayback Machine)](http://web.archive.org/web/2013/http://www.ted.com/talks/cesar_harada_a_novel_idea_for_cleaning_up_oil_spills.html)
- [Dari Pulau Ke Pulau, Singapore Night Festival 2025 programme page (Wayback Machine copy; live page now 404)](https://web.archive.org/web/20251015055747/https://www.heritage.sg/sgnightfest/whats-on/dari-pulau-ke-pulau)
- [Dineo Seshee Bopape – 12th Biennale de Lyon 2013 artist page (archived)](http://web.archive.org/web/20140704090524/http://2013.labiennaledelyon.com:80/uk/2013-edition/international-exhibition/artists/dineo-seshee-bopape,42.html)
- [Ed Atkins: In Conversation With, Aesthetica (archived)](https://web.archive.org/web/20130508161957/http://www.aestheticamagazine.com/ed-atkins)
- [Edgardo Aragón, Selected Works 2013, Proyectos Monclova (PDF, Wayback Machine copy)](http://web.archive.org/web/20250217142322/https://www.arte-sur.org/wp-content/uploads/2013/08/EA_SelectedWorks-2013-ENG-red.pdf)
- [EK Interview: Carl Burton - Empty Kingdom (Wayback Machine)](http://web.archive.org/web/20150213015732/http://www.emptykingdom.com/featured/ek-interview-carl-burton/)
- [From the Vault: Warwick Thornton's Mother Courage, ABC Arts (archived)](https://web.archive.org/web/20150313150653/http://www.abc.net.au:80/arts/stories/s3527013.htm)
- [Grosse Fatigue - camillehenrot.fr (Wayback Machine, 2017)](https://web.archive.org/web/20170101062414/http://camillehenrot.fr/en/work/68/grosse-fatigue)
- [Interview: Haroon Mirza – InitiArt Magazine (archived)](https://web.archive.org/web/20190906083637/http://www.initiartmagazine.com/interview.php?IVarchive=105)
- [Island Waters, Singapore Night Festival 2025 programme page (Wayback Machine copy; live page now 404)](https://web.archive.org/web/20250804053148/https://www.heritage.sg/sgnightfest/whats-on/island-waters)
- [Jon Cronshaw, 'Art: Forms and functions - an interview with Haroon Mirza' (Yorkshire Post, 17 May 2013), archived](https://web.archive.org/web/20140507090146/http://www.joncronshaw.co.uk/2013/05/art-forms-and-functions-interview-with.html)
- [Life on Screen: Rania Stephan, ArtAsiaPacific 79 (Wayback Machine copy)](https://web.archive.org/web/20160327153433/http://artasiapacific.com/Magazine/79/LifeOnScreenRaniaStephan)
- [Lifepatch wiki, 'Lifepatch' profile page (Indonesian; Wayback Machine copy)](https://web.archive.org/web/2015/http://lifepatch.org/Lifepatch)
- [LIFTing the curtain on Radio Ghost (LIFT Festival interview, archived)](http://web.archive.org/web/20221128224314/https://www.liftfestival.com/lifting-the-curtain-radio-ghost/)
- [Michael Barron, Camille Henrot - BOMB Magazine (Wayback Machine, 2016)](https://web.archive.org/web/20160117204229/http://bombmagazine.org/article/546917/camille-henrot)
- [Michael Connor, The Internet’s Revolutions - interview with Constant Dullaart, Rhizome 2018 (Wayback Machine)](https://web.archive.org/web/20231203133845/https://rhizome.org/editorial/2018/jul/26/the-revolving-revolution/)
- [Nairobi Berries – Ng'endo Mukii, artist website (archived)](http://web.archive.org/web/20240619081104/https://www.ngendo.com/nairobi-berries)
- [Net Art Anthology: The Revolving Internet - Rhizome (Wayback Machine, 2023)](https://web.archive.org/web/20231207100455/https://anthology.rhizome.org/the-revolving-internet)
- [Norman by James Paterson – WebVR Experiments (normanvr.com, Wayback Machine copy)](https://web.archive.org/web/20210420230249/https://normanvr.com)
- [NoSearchBar, Prix Ars Electronica 2022 winners page (Wayback Machine copy)](https://web.archive.org/web/20221209060027/https://calls.ars.electronica.art/2022/prix/winners/9017/)
- [Now he's out in public and everyone can see, bookchin.net (2015 archived project page)](https://web.archive.org/web/20150426010030/http://bookchin.net/projects/out-in-public.html)
- [Observer: Kudzanai Chiurai \| Artist - AMMO Magazine (archived)](https://web.archive.org/web/20190716084952/http://www.ammomag.com/blog/observer-kudzanai-chiurai-artist/)
- [Open Source Estrogen (2015), maggic.ooo (Wayback Machine copy)](https://web.archive.org/web/20200201002645/http://maggic.ooo/Open-Source-Estrogen-2015)
- [Parasitic / Symbiotic – Ann-Katrin Krenz project page (frau-krenz.de, Wayback Machine snapshot 2018-03-02; the live URL now redirects to andand.xyz, which returned HTTP 500)](http://web.archive.org/web/20180302060724/http://frau-krenz.de:80/parasitic-symbiotic/)
- [Protei wut?, cesarharada.com, 12 December 2012 (Wayback Machine)](http://web.archive.org/web/2013/http://www.cesarharada.com/protei-wut/)
- [Protei, Open hardware Shape Shifting Sailing Robot to Sense and Clean the Oceans, cesarharada.com (Wayback Machine)](http://web.archive.org/web/2013/http://www.cesarharada.com/protei-open-hardware-shape-shifting-sailing-robot-to-sense-and-clean-the-oceans/)
- [Que Voz feio (醜い声 / plain voices), yoshihiroyamamoto.com (Wayback Machine, 3 November 2013)](http://web.archive.org/web/20131103204318/http://yoshihiroyamamoto.com/work_02.html)
- [Shelter - shelteranimation.com Info (Wayback Machine, 2014)](http://web.archive.org/web/20140424224948/http://www.shelteranimation.com/info)
- [Soundings: A Contemporary Score - Susan Philipsz, Study for Strings (MoMA, 2013; Wayback Machine)](https://web.archive.org/web/20150128093953/http://www.moma.org/interactives/exhibitions/2013/soundings/artists/11/works)
- [Sputniko!, '01 Greetings from the Airport' — Wochi Kochi Magazine (archived copy)](http://web.archive.org/web/20160507042423/http://www.wochikochi.jp/english/serialessay/2013/04/sputniko01.php)
- [The Zone, Designing Civic Encounter, ArtTerritories (Wayback Machine copy)](https://web.archive.org/web/20160401174654/http://www.artterritories.net/designingcivicencounter/?page_id=633)
- [Warwick Thornton: Mother Courage Education Resource (ACMI, archived PDF)](https://web.archive.org/web/20180714085630/https://2015.acmi.net.au/media/426844/warwick-thornton-ed-kit.pdf)
- [Wastelands project blog: About (Wayback Machine copy)](https://web.archive.org/web/20190920211119/https://tagnyduff.blog/about/)
- [Wastelands project blog: New collaboration with ADREC at MSU via Bridge Program (2017, Wayback Machine copy)](https://web.archive.org/web/20190920211119/https://tagnyduff.blog/2017/12/07/anaerobic-digestor-research-and-education-centre-adrec-at-msu/)
- [Wastelands project blog: Wastelands Project Overview (2017, Wayback Machine copy)](https://web.archive.org/web/20190920211119/https://tagnyduff.blog/2017/10/12/first-blog-post/)

</details>
<details><summary>webarchive.ars.electronica.art (10)</summary>

- [Acoustic Additive Synthesizer - Ars Electronica Festival 2017](https://webarchive.ars.electronica.art/festival/2017/ai/en/index.html%3Fp=3311.html)
- [Ars Electronica 2016 (Radical Atoms): Interface I](https://webarchive.ars.electronica.art/festival/2016/radicalatoms/en/interface-i/index.html)
- [Ars Electronica Festival 2018 (Error) web archive: Conspiracy: Conjoining the Virtual](https://webarchive.ars.electronica.art/festival/2018/error/en/index.html%3Fp=9932.html)
- [CyberArts 2012 exhibition, Ars Electronica (2.6g 329m/s, Honorary Mention Hybrid Art)](https://webarchive.ars.electronica.art/festival/2012/thebigpicture/en/index.html%3Fp=269.html)
- [CyberArts 2014 - Ars Electronica Festival (web archive)](https://webarchive.ars.electronica.art/festival/2014/c/en/cyberarts-2014/)
- [frequencies – Nicolas Bernier (CA), Ars Electronica 2013 TOTAL RECALL programme (feed)](https://webarchive.ars.electronica.art/festival/2013/totalrecall/en/tag/nicolas-bernier/feed/index.html)
- [Mathilde Lavenne: TROPICS, Ars Electronica Festival 2018](https://webarchive.ars.electronica.art/festival/2018/error/en/index.html%3Fp=9940.html)
- [Prix Ars Electronica 2010 Forums: Computer Animation / Film / VFX, Golden Nica Nuit Blanche (Ars Electronica web archive)](https://webarchive.ars.electronica.art/festival/2010/repair/en/index.html%3Fp=1422.html)
- [Prix Ars Electronica 2013 winners (Interactive Art, Honorary Mention), Ars Electronica archive](https://webarchive.ars.electronica.art/festival/2013/totalrecall/en/index.html%3Fp=425.html)
- [rheo: 5 horizons, Ars Electronica Festival 2010 (Repair) archive](https://webarchive.ars.electronica.art/festival/2010/repair/en/index.html%3Fp=1393.html)

</details>
<details><summary>webarchives.rhizome.org (1)</summary>

- [An interview with Monira Al Qadiri, AQNB (Rhizome archive)](https://webarchives.rhizome.org/Q16289/oe_/https://www.aqnb.com/?p=37278)

</details>
<details><summary>wepresent.wetransfer.com (1)</summary>

- [Hussein Shikha: Keeping southern Iraq's historic textile traditions alive, WePresent (WeTransfer)](https://wepresent.wetransfer.com/stories/hussein-shikha-iraqi-textiles)

</details>
<details><summary>werkleitz.de (1)</summary>

- [Unknown label from Nicolas Gourault is touring in Europe, Werkleitz](https://werkleitz.de/en/artikel/unknown-label-von-nicolas-gourault)

</details>
<details><summary>wexarts.org (1)</summary>

- [Q&A: Sam Green on A Thousand Thoughts, Wexner Center for the Arts](https://wexarts.org/blog/film-music-qa-sam-green-kronos-thousand-thoughts-world-premiere)

</details>
<details><summary>whitehotmagazine.com (1)</summary>

- [From Twin Quasars to Digital Frontiers at the Whitney Artport Whitney Virtual Space - Whitehot Magazine](https://whitehotmagazine.com/articles/virtual-space-by-lara-pan/7026)

</details>
<details><summary>whitney.org (32)</summary>

- [3FACE (Token #11, Archetype: Belonging), Whitney Museum of American Art collection](https://whitney.org/collection/works/67733)
- [Addie Wagenknecht: Believe me — Whitney Museum of American Art, artport](https://whitney.org/exhibitions/believe-me)
- [Amelia Winger-Bearskin: SKY/WORLD DEATH/WORLD (Whitney Museum, artport / Sunrise/Sunset)](https://whitney.org/exhibitions/amelia-winger-bearskin)
- [artport commissions — Whitney Museum of American Art](https://whitney.org/artport/commissions)
- [Ashley Zelinskie: Twin Quasar - Whitney Museum of American Art](https://whitney.org/exhibitions/twin-quasar)
- [Christopher Y. Lew, essay on Sophia Al-Maria, Whitney Museum (2017)](https://whitney.org/essays/sophia-al-maria)
- [Devin Kenny: Ongoing, Individual Adaptability or How to Quiet Quit, Whitney Museum artport](https://whitney.org/exhibitions/ongoing-individual-adaptability)
- [Eva and Franco Mattes: Riccardo Uncut, Whitney Museum of American Art](https://whitney.org/exhibitions/riccardo-uncut)
- [Eva and Franco Mattes: Riccardo Uncut, Whitney Watch & Listen (video)](https://www.whitney.org/WatchAndListen/37787)
- [Exive II: Gabriela Ruiz — Whitney Museum event](https://whitney.org/events/gabriela-ruiz)
- [Hyundai Terrace Commission: Marina Zurkow — Whitney Museum](https://whitney.org/exhibitions/marina-zurkow)
- [Jacolby Satterwhite, Whitney Biennial 2014](https://whitney.org/exhibitions/2014-biennial/jacolby-satterwhite)
- [Memo Akten & Katie Hofstadter: The Thinking Ocean, Whitney Museum of American Art](https://whitney.org/exhibitions/the-thinking-ocean)
- [Michael Mandiberg: Live Study, Whitney Museum of American Art](https://whitney.org/exhibitions/live-study)
- [Morehshin Allahyari: The Laughing Snake, Whitney artport](https://whitney.org/exhibitions/laughing-snake)
- [Nancy Baker Cahill: CENTO, audio guide with verbal description, Whitney Museum](https://whitney.org/guides/104)
- [Nancy Baker Cahill: CENTO, Whitney Museum of American Art (artport commission)](https://whitney.org/exhibitions/cento)
- [Ongoing, Individual Adaptability or How to Quiet Quit, Whitney collection record AP.2022.3](https://whitney.org/collection/works/66890)
- [Peter Burr: Sunshine Monument (Whitney Museum, artport / Sunrise/Sunset)](https://whitney.org/exhibitions/peter-burr)
- [Rachel Rossin: The Maw Of — Whitney Museum of American Art, artport](https://whitney.org/exhibitions/the-maw-of)
- [Refigured audio guide (installation description and transcript), Whitney (2023)](https://whitney.org/guides/83)
- [Riccardo Uncut (2018), artport commissions, Whitney Museum of American Art](https://www.whitney.org/artport/commissions/riccardo-uncut)
- [Rick Silva: Liquid Crystal (Whitney Museum, artport / Sunrise/Sunset)](https://whitney.org/exhibitions/rick-silva)
- [Sophia Al-Maria: Black Friday (exhibition page)](https://whitney.org/exhibitions/sophia-al-maria)
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
<details><summary>wired.com (1)</summary>

- [This German artist is training geese to fly to the Moon, WIRED UK, 2013](https://www.wired.com/story/moon-geese/)

</details>
<details><summary>witayajunma.com (1)</summary>

- [Smog Season - Witaya Junma (artist website)](http://www.witayajunma.com/smog-season1.html)

</details>
<details><summary>wonderwall.sg (1)</summary>

- [Artist Behind The Art: Hafizah Jainal (Wonderwall.sg)](https://wonderwall.sg/people/artist-behind-the-art-hafizah-jainal)

</details>
<details><summary>words.hushush.com (3)</summary>

- [Not Your World Music, 'Companion compilation' page, words.hushush.com](http://words.hushush.com/NOT_YOUR_WORLD_MUSIC_Noise_in_South_East_Asia_-_compilation.html)
- [Not Your World Music, more information about the book (contents, biographies, publication data)](http://words.hushush.com/NOT_YOUR_WORLD_MUSIC_Noise_in_South_East_Asia_-_more_info.html)
- [Not Your World Music: Noise in South East Asia, project site (words.hushush.com)](http://words.hushush.com/)

</details>
<details><summary>worldcrunch.com (1)</summary>

- [What You Hear Is What You Get: Sound As Subversive Art, Worldcrunch (with Mada Masr), 2018](https://worldcrunch.com/in-the-news/what-you-hear-is-what-you-get-sound-as-subversive-art/)

</details>
<details><summary>wp.swissinstitute.net (1)</summary>

- [BOMB / Swiss Institute – Ali Cherri: Humble and quiet and soothing as mud](https://wp.swissinstitute.net/press/ali-cherri-humble-and-quiet-and-soothing-as-mud-3/)

</details>
<details><summary>wro2019.wrocenter.pl (1)</summary>

- [TROPICS, WRO Media Art Biennale 2019](https://wro2019.wrocenter.pl/en/works/tropics/)

</details>
<details><summary>wrocenter.pl (1)</summary>

- [David Bowen (US), tele-present-water — WRO Art Center](https://wrocenter.pl/en/david-bowen-us-tele-present-water/)

</details>
<details><summary>www2.hu-berlin.de (1)</summary>

- [CollActive Materials (HU Berlin) – Safe Human-Machine Interaction, Futurium 2024](https://www2.hu-berlin.de/collactivematerials/en/ausstellungen/safe-human-machine-interaction/)

</details>
<details><summary>xibtmagazine.com (1)</summary>

- [Augmenting Perception: An Interview with Media Artist Refik Anadol, xibt magazine (2020)](https://www.xibtmagazine.com/en/2020/10/augmenting-perception-an-interview-with-media-artist-refik-anadol/)

</details>
<details><summary>xrmust.com (1)</summary>

- [S+T+ARTS Prize 2025 winners – XR Must](https://xrmust.com/xr-magazine/starts-2025-winners/)

</details>
<details><summary>yakushimaruetsuko.com (1)</summary>

- [やくしまるえつこ『わたしは人類』 / Yakushimaru Etsuko – "I'm Humanity", artist's website](https://yakushimaruetsuko.com/archives/2602)

</details>
<details><summary>ycam.jp (3)</summary>

- [LIFE by MEDIA - YCAM 10th anniversary (2013)](https://www.ycam.jp/en/events/2013/life-by-media/)
- [Sports Time Machine - YCAM archive](https://www.ycam.jp/en/archive/works/sports-time-machine/)
- [YCAM – Soichiro Mihara profile](https://www.ycam.jp/en/archive/profile/soichiro-mihara/)

</details>
<details><summary>yebizo.com (2)</summary>

- [Masaki Fujihata, Voices of Aliveness - Yebisu International Festival for Art & Alternative Visions 2022, Tokyo Photographic Art Museum](https://www.yebizo.com/2022/program/55994)
- [TAKATANI Shiro, Toposcan/Tokyo — Yebisu International Festival for Art & Alternative Visions 2020](https://www.yebizo.com/2022/en/program/24270)

</details>
<details><summary>yeoworkshop.com (1)</summary>

- [Sarah Choo Jing, Zoom, Click, Waltz, 2020 - Yeo Workshop](https://www.yeoworkshop.com/artworks/523-sarah-choo-jing-zoom-click-waltz-2020)

</details>
<details><summary>yoshuaokon.com (1)</summary>

- [Octopus, 2011, yoshuaokon.com](https://yoshuaokon.com/work/test-work-selected-2/)

</details>
<details><summary>youtu.be (1)</summary>

- [CHIMERIA video (linked from the Ars Electronica archive entry)](https://youtu.be/B7U_7kTxUWA)

</details>
<details><summary>youtube.com (7)</summary>

- [Daniel Crooks: Phantom Ride (video interview), ACMI, YouTube](https://www.youtube.com/watch?v=4FrOoxz71Zg)
- [Dineo Seshee Bopape – But that is not the important part of the story, 2013 (Biennale de Lyon YouTube channel)](https://www.youtube.com/watch?v=31riODVoGOg)
- [Maquina Stella \| MARCELA ARMAS, Laboratorio Arte Alameda (YouTube)](https://www.youtube.com/watch?v=z_Oi-EMrMTg)
- [Micro-Nano Landscape — YouTube (artist's channel), 2026](https://www.youtube.com/watch?v=utLpHqNOAD4)
- [Shiro Takatani: Toposcan / Baden-Württemberg – Interview — ZKM \| Karlsruhe on YouTube](https://www.youtube.com/watch?v=tEKt7TPg1zk)
- [The Half by Intermedia Chef — YouTube](https://www.youtube.com/watch?v=2vTUqpVlrLg)
- [微纳山水 Micro-Nano Landscape by Suxuan Jiang — YouTube (artist's channel)](https://www.youtube.com/watch?v=yxyzYumk88Y)

</details>
<details><summary>zachblas.info (1)</summary>

- [Facial Weaponization Suite — Zach Blas (artist's site)](https://zachblas.info/works/facial-weaponization-suite/)

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
<details><summary>zinasarowiwa.com (1)</summary>

- [Mourning Class: Nollywood - Zina Saro-Wiwa (artist website)](https://www.zinasarowiwa.com/artworks/mourning-class-nollywood)

</details>
<details><summary>zippergaleria.com.br (3)</summary>

- [da série Mindscapes #L1, after Dan Flavin — Zipper Galeria, 2014](https://www.zippergaleria.com.br/en/exhibitions/115-da-serie-mindscapes-l1-after-dan-flavin-fernando-velazquez/overview/)
- [Fernando Velázquez — Zipper Galeria artist page](https://www.zippergaleria.com.br/en/artists/41-fernando-velazquez/)
- [Zipper Galeria recebe as exposições Mindscapes e Íntima Ação em agosto — press release, July 2012 (.doc)](https://www.zippergaleria.com.br/usr/documents/exhibitions/press_release_url/143/zipper-galeria-recebe-as-exposi-es-mindscapes-e-ntima-a-o-em-agosto.doc)

</details>
<details><summary>zkm.de (11)</summary>

- [Codex Virtualis: Genesis – ZKM Karlsruhe (exhibition Renaissance 3.0, 2023–24)](https://zkm.de/en/node/62686)
- [Digital Imaginaries. African Positions Beyond Binaries (publication, PDF)](https://zkm.de/sites/default/files/file/en/di_en_web_0.pdf)
- [From Hand to Mouth — ZKM collection record](https://zkm.de/en/node/71194)
- [Magdi Mostafa, ZKM \| Center for Art and Media](https://zkm.de/en/node/2541)
- [METABOLICA Camp — ZKM collection](https://zkm.de/en/node/62590)
- [Rafaël Rozendaal: Neo Geo City (ArtOnYourScreen, text by Matthias Kampann)](https://zkm.de/en/rafael-rozendaal-neo-geo-city)
- [tele-present water \| ZKM collection](https://zkm.de/en/artwork/tele-present-water)
- [Toposcan / Baden-Württemberg — ZKM \| Center for Art and Media collection](https://zkm.de/en/node/8358)
- [Ursula Damm, Transits – ZKM, Seasons of Media Arts](https://zkm.de/en/node/4211)
- [ZKM, Artist Talks – Marcus Neustetter (video page, 2018)](https://zkm.de/en/media/videos/artist-talks-marcus-neustetter)
- [ZKM, Digital Imaginaries – Africas in Production, exhibition brochure (2018)](https://zkm.de/sites/default/files/file/en/digital_imaginaries_broshure_en_doppelseiten.pdf)

</details>
<details><summary>zu-uk.com (1)</summary>

- [Radio Ghost – ZU-UK project page](https://zu-uk.com/project/radio-ghost/)

</details>
