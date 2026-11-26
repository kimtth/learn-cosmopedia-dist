# Cosmopedia

Cosmopedia combines four encyclopedias: Britannica Concise, Columbia, MyPedia, and JoongAng. It uses Wikipedia to cover selected developments since those editions were published. The Global and Local modules draw on English, Japanese, and Korean sources.

Read the [Preface](./preface.md) for the project's aims and editorial approach.

- Global: topics that matter in many countries. Example: a world-famous person that both Britannica and Columbia describe.
- Local: topics that matter mostly in one country. Example: a Korean place that only JoongAng describes.
- Modular: a module collects only the entries of one region. Example: an American module, a Japanese module, and a Korean module. Each module is a separate part of the whole.

From left to right: the cover, a Global page in English, a Korean page, and a Japanese page. In the Global page, the marks M and J after a headword show which works describe the topic. The Japanese and Korean names follow in brackets.

![Sample pages from three modules](https://github.com/user-attachments/assets/1bcd9335-e1c7-4a62-82b5-c04d95268e06)

## Why these four works

The goal is a quick look at the whole picture of knowledge. Each work has one job.

1. **Why a concise book**: general encyclopedias are too wide and too long for a quick check. The internet and generative AI already answer detail questions. **What is still hard is to see the whole picture of fields we do not know. A one-volume encyclopedia does that.**
1. Longer and more complex articles also make it harder to manage **details** and follow **connections between related facts** across entries.
1. **Britannica Concise** gives the **Global view**. Britannica has been published in many languages (Japanese, Chinese, Korean, Turkish, Polish, Hungarian, Brazilian Portuguese, Spanish). It also influenced other encyclopedias, which were edited on their own (French, Greek). Britannica Concise is its short one-volume work.
1. **Columbia** fills in next to Britannica. It is a leading one-volume encyclopedia. Its preface calls it "the handiest one-stop, one-volume" reference. It gives a second **English-language view**.
1. **MyPedia** and **JoongAng** add **Asia** and **Eastern view**. Britannica and Columbia alone are not sufficient to cover these perspectives.
 - **MyPedia** (Japanese): published by Heibonsha (平凡社). The 1931 Heibonsha Encyclopedia made 百科事典 the standard term meaning “encyclopedia” in Asia. Heibonsha is a leading encyclopedia publisher in Japan. Heibonsha is known for Tōyō Bunko (東洋文庫), a major collection of Asian classics covering the Islamic world, India, China, Korea, and other parts of Asia.
 - **JoongAng** (Korean): published by JoongAng Ilbo, a major Korean newspaper company. It contains about 47,000 headwords and about 6,000 audio-visual materials. It is strong in IT and technology, with entries such as "전기자동차" (electric car), "가상현실" (virtual reality), and "태양전지" (solar cell).
 - Some MyPedia and JoongAng entries go to the **Global (Common)** module. Reason: they add an **Eastern view** of global topics.

## Sources

| Work | Language | Edition and publisher | Latest year found in source text | Source entries | Source cross-references |
|------|----------|-----------------------|----------------------------------|---------------:|-------------------------:|
| Britannica Concise Encyclopedia (B) | en | © 2006 Encyclopædia Britannica, Inc., Chicago | 2006 | 25,288 | About 76,000 printed references |
| The Columbia Encyclopedia, Sixth Edition (C) | en | Ed. Paul Lagasse, Columbia University Press, © 2000 (PDF text: 2000; electronic reference, © 2022: about 2021) | 2000 (PDF); about 2021 (electronic) | 41,551 | About 62,000 (print scan estimate); 90,555 links (electronic) |
| 百科事典マイペディア, MyPedia (M) | ja | Heibonsha (平凡社), 1998 | about 1995 | 53,828 | 192,733 links, excluding standalone redirects |
| 중앙 멀티미디어백과, JoongAng Multimedia Encyclopedia '97 (J) | ko | JoongAng Ilbo (중앙일보사), 1997 | about 1995 | 44,464 | 211,278 links in named entries |

"Source entries" excludes redirects and entries that only say "See X". The rules are approximate for Columbia and JoongAng, so their counts are estimates.

The years come from a random sample of 5,000 source entries per work (2026-11-12). The estimate excludes publication dates, planned events, and Wikipedia updates.

Wikipedia supplements the four works with 578 new entries and 1,023 passages across 1,021 existing entries. Cosmopedia calls these W additions and marks the affected articles with `w`. The edition also includes 796 body replacement rows, 148 personal headword corrections, and six article merges.  

### Where to find each work

Open Library search supplied the ISBNs and work pages below.

| Work | Online version | Book info |
|------|----------------|-----------|
| Britannica Concise (B) | [Britannica](https://www.britannica.com/). The old Concise site is gone. | 2006 edition: [Open Library](https://openlibrary.org/works/OL19468954W), 2,115 pages, ISBN 978-1-59339-293-2 |
| The Columbia Encyclopedia, 6th ed. (C) | [Encyclopedia.com](https://www.encyclopedia.com/) | 2000 edition: [Open Library](https://openlibrary.org/works/OL17011918W), 3,156 pages, ISBN 978-0-7876-5015-5 |
| MyPedia (M) | [Kotobank](https://kotobank.jp/dictionary/mypedia/) | Latest edition: *MyPedia* (新装新訂), 1995, 1,653 pages, ISBN 978-4-582-09631-6. [Bibliographic record](https://www.books.or.jp/book-details/9784582096316) |
| JoongAng '97 (J) | No known online version. | Closest book: 《Eureka 중앙백과사전》 (1995), 2,243 pages. [National Library of Korea catalog](https://www.nl.go.kr/NL/contents/search.do?pageNum=1&pageSize=10&srchTarget=total&kwd=Eureka+%EC%A4%91%EC%95%99백과사전) |

`B`, `C`, `M`, and `J` after a headword identify the reference works that cover the topic. These marks do not imply that the sources agree on every fact. The lowercase `w` marks Wikipedia-based material. `U` marks new and expanded entries. See annual news, population, administrative areas, and statistics.

## Modules

**Global and Common name the same module.** The preface and reader-facing descriptions use Global (세계편 in Korean). Local (지역편) covers the American, Japanese and Korean modules. Code, data, file names, PDF bookmarks, and the source legend still use Common. For example, `module: "Common"` and `cosmopedia_Common.pdf` refer to Global. Global-KO means Common-KO. No data values or file names change.

Each module has its own body and its own index of headwords and aliases.

| Module | What it holds | Language | Entries | New | Updated | Original edition words | Korean edition words | Original edition pages | Korean edition pages |
|--------|---------------|----------|--------:|----:|--------:|-----------------------:|---------------------:|-----------------------:|---------------------:|
| Common | Topics of worldwide interest | English | 70,727 | 515 | 21,342 | 6,669,867 | 4,338,464 | 2,853 | 2,505 |
| Japanese | Topics about Japan | Japanese | 18,367 | 104 | 5,362 | 1,768,643 | 985,546 | 552 | 556 |
| Korean | Topics about Korea | Korean | 17,249 | 116 | 3,244 | 743,996 | 743,996 | 412 | 412 |
| American | Topics about the United States | English | 6,424 | 97 | 1,834 | 672,081 | 461,536 | 290 | 266 |
| **Total per edition** | | | **112,767** | **832** | **31,782** | **9,854,587** | **6,529,542** | **4,111** | **3,743** |

**New** and **Updated** are cumulative counts for the current edition, measured against the original render inputs. **New** counts entries added since those inputs. **Updated** counts original entries that remain in the edition and differ in either language. Each article ID counts once in its current module, and the two counts do not overlap.

The English and Japanese modules have 95,331 entries with matching Korean IDs. Both editions share the 17,245-entry Korean module. Matching IDs confirm coverage, not translation quality.

## Revision Policy

*MyPedia* covers a wide range of Japanese regions and companies and includes population and revenue figures that may become outdated over time. *JoongAng* occasionally uses expressions such as “our country” (우리나라). When the country being referred to is clear from the context, such expressions are replaced with the country's explicit name to avoid ambiguity.

Company entries are reviewed for their current operating status, mergers and acquisitions, and principal business activities. Standalone figures that are likely to become outdated are removed, while figures that help explain significant changes are retained together with their reference dates. Indicators showing changes in a company's core business or market position are tracked separately when they can be compared on a consistent basis.

Regular population updates primarily cover places with populations of at least 250,000. Exceptions may be made for small countries, territories, capital cities, and other important administrative centers. However, inclusion in the population update program does not automatically justify retaining a standalone population figure in an entry.

### Subject shares before the final headword review

This earlier table does not include the final same-headword decisions or the 578 new W entries. All PERSON entries count under **People**, regardless of field. Other entries are grouped by field:

- History and politics: history, politics and law, military.
- Science, medicine and technology: life science, physics and chemistry, mathematics, earth and space, technology, medicine.
- Religion, philosophy and thought: religion and myth, philosophy and thought.
- Arts, literature and music: literature, visual arts and architecture, music, performing arts and film, language.
- Economy, law and society: economy and business, society, education and psychology, daily culture, sports and games.
- Other: the model answered UNSURE.

| Subject | Global (Common) | Japanese | Korean | American |
|---|---|---|---|---|
| **People** | 28.4% | 16.4% | 20.7% | 49.1% |
| **Places and geography** | 16.9% | 24.7% | 11.1% | 35.4% |
| **History and politics** | 7.6% | 14.4% | 25.6% | 4.7% |
| **Science, medicine and technology** | 27.2% | 8.8% | 5.3% | 1.9% |
| **Religion, philosophy and thought** | 4.7% | 5.9% | 4.5% | 0.6% |
| **Arts, literature and music** | 6.8% | 13.0% | 18.3% | 2.2% |
| **Economy, law and society** | 8.4% | 16.7% | 14.4% | 6.1% |
| **Other** | 0.1% | 0.1% | 0.0% | 0.0% |

### Limitations

Authority control relies on AI knowledge, supplemented by official terminology and rule-based audits, to ensure cross-translation consistency. Some animal and plant terms may not be accurate, but the original headwords are also provided. Similarity between entries is evaluated using embeddings, rule-based output checks, and LLM-as-a-Judge, with some human review.
