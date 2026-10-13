# Cosmopedia

Cosmopedia combines entries from four encyclopedias into a single reference work. The four sources are Britannica Concise, Columbia, MyPedia, and JoongAng. It uses a modular Global + Local approach. This widens coverage by bringing together trusted sources in English, Japanese, and Korean.

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

| Work | Language | Edition and publisher | Source entries (without cross-references) |
|------|----------|-----------------------|---------------:|
| Britannica Concise Encyclopedia (B) | en | © 2006 Encyclopædia Britannica, Inc., Chicago | 25,288 |
| The Columbia Encyclopedia, Sixth Edition (C) | en | Ed. Paul Lagasse, Columbia University Press, © 2000 | 41,551 |
| 百科事典マイペディア, MyPedia (M) | ja | Heibonsha (平凡社), 1998 | 53,828 |
| 중앙 멀티미디어백과, JoongAng Multimedia Encyclopedia '97 (J) | ko | JoongAng Ilbo (중앙일보사), 1997 | 44,464 |

"Source entries" counts the real entries in each file. An entry that only points to another entry is left out. Examples are a redirect or a "See X" line. The method is a rule of thumb, so the Columbia and JoongAng numbers are approximate.

### Where to find each work

Book data comes from Open Library (the ISBNs and work pages were returned by its search). 

| Work | Online version | Book info |
|------|----------------|-----------|
| Britannica Concise (B) | [Britannica](https://www.britannica.com/). The old Concise site is gone. | 2006 edition: [Open Library](https://openlibrary.org/works/OL19468954W), 2,115 pages, ISBN 978-1-59339-293-2 |
| The Columbia Encyclopedia, 6th ed. (C) | [Encyclopedia.com](https://www.encyclopedia.com/) | 2000 edition: [Open Library](https://openlibrary.org/works/OL17011918W), 3,156 pages, ISBN 978-0-7876-5015-5 |
| MyPedia (M) | [Kotobank](https://kotobank.jp/dictionary/mypedia/) | Latest edition: *MyPedia* (新装新訂), 1995, 1,653 pages, ISBN 978-4-582-09631-6. [Bibliographic record](https://www.books.or.jp/book-details/9784582096316) |
| JoongAng '97 (J) | No known online version. | Closest book: 《Eureka 중앙백과사전》 (1995), 2,243 pages. [National Library of Korea catalog](https://www.nl.go.kr/NL/contents/search.do?pageNum=1&pageSize=10&srchTarget=total&kwd=Eureka+%EC%A4%91%EC%95%99백과사전) |

The letters B, C, M and J are the source marks printed after each headword. A mark shows which works describe the topic. It does not mean the works agree on every fact.

## Modules

Each module has its own body and its own index of headwords and aliases.

| Module | What it holds | Text language | Headword language | Entries |
|--------|---------------|---------------|-------------------|--------:|
| Global (Common) | Topics held by two or more works, topics from Britannica, Japanese or Korean topics that are not about Japan or Korea, and Columbia topics that matter to the whole world | English | English | 68,615 |
| Japanese | Topics only MyPedia describes, and about Japan | Japanese | Japanese | 20,880 |
| Korean | Topics only JoongAng describes, and about Korea | Korean | Korean | 17,901 |
| American | Topics only Columbia describes, and about the United States | English | English | 5,922 |

### Share of entries by **subject**

An entry whose type is PERSON is counted under **People**, whatever its field. The other entries are grouped by field:

- History and politics: history, politics and law, military.
- Science, medicine and technology: life science, physics and chemistry, mathematics, earth and space, technology, medicine.
- Religion, philosophy and thought: religion and myth, philosophy and thought.
- Arts, literature and music: literature, visual arts and architecture, music, performing arts and film, language.
- Economy, law and society: economy and business, society, education and psychology, daily culture, sports and games.
- Other: the model answered UNSURE.

| Subject | Common | Japanese | Korean | American |
|---|---|---|---|---|
| **People** | 29.5% | 14.7% | 19.8% | 50.0% |
| **Places and geography** | 17.6% | 21.4% | 10.5% | 37.3% |
| **History and politics** | 7.3% | 14.5% | 25.4% | 3.7% |
| **Science, medicine and technology** | 26.6% | 13.4% | 6.3% | 1.4% |
| **Religion, philosophy and thought** | 4.5% | 6.0% | 5.0% | 0.6% |
| **Arts, literature and music** | 6.7% | 12.6% | 18.1% | 1.4% |
| **Economy, law and society** | 7.8% | 17.3% | 14.7% | 5.7% |
| **Other** | 0.1% | 0.1% | 0.0% | 0.0% |

### Limitations

Authority control relies on AI knowledge, supplemented by official terminology and rule-based audits, to ensure cross-translation consistency. Some animal and plant terms may not be accurate, but the original headwords are also provided. Similarity between entries is evaluated using embeddings, rule-based output checks, and LLM-as-a-Judge, with some human review.
