# Hieratische Paläographie DB (HPDB)

[![Website](https://img.shields.io/badge/website-moeller.jinsha.tsukuba.ac.jp-0d9488)](https://moeller.jinsha.tsukuba.ac.jp)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![IIIF](https://img.shields.io/badge/IIIF-compliant-brightgreen)](https://iiif.io/)

A bilingual (EN / JA) retrieval system for hieratic scripts, built on IIIF-format images of **Georg Möller's _Hieratische Paläographie_** (1909–36).
古代エジプトのヒエラティック（神官文字）字形を検索するためのデータベースです。

🔗 **Live site**: <https://moeller.jinsha.tsukuba.ac.jp>

---

## English

### About

The Hieratische Paläographie DB (HPDB) lets researchers and learners search the hieratic sign forms collected in **Georg Möller, _Hieratische Paläographie_, vols. 1–3 (1909–12)**. IIIF images are provided by the Asian Research Library of the University of Tokyo. You can search by hieratic number, hieroglyph number, phonetic value / word, and other facets; results are viewable as grid, list, table, image, and statistics layouts.

### Search syntax (examples)

- Full-text: `?keyword=hieratic`
- Field-based: `Item:X-001`, `HieraticNo:123`
- Faceted filter: `?fc-ItemType=glyph&fc-Unit=Vol1`
- Include / exclude: `?q-HieraticNo=123` (include), `?q-HieraticNo=-123` (exclude)

### Citation

> Masakatsu Nagai, Toshihito Waki, Yona Takahashi, and Satoru Nakamura, _Hieratische Paläographie DB_, <https://moeller.jinsha.tsukuba.ac.jp/>.

### Team

- [Masakatsu Nagai](https://researchmap.jp/Masakatsu-Nagai/?lang=english) — Professor, Faculty of Library, Information and Media Science, University of Tsukuba
- [Toshihito Waki](https://researchmap.jp/wakit/?lang=english) — Associate Professor, Faculty of Humanities and Social Sciences, University of Tsukuba
- [Yona Takahashi](https://researchmap.jp/takahashi.yona?lang=en) — Research Associate, Research Institute for Languages and Cultures of Asia and Africa, Tokyo University of Foreign Studies
- [Satoru Nakamura](https://researchmap.jp/nakamura.satoru/?lang=english) — Associate Professor, Historiographical Institute, The University of Tokyo

### Funding

Supported by the Japan Society for the Promotion of Science (JSPS).

---

## 日本語

### 概要

**ヒエラティック古書体学データベース（HPDB）** は，Georg Möller, _Hieratische Paläographie_, 第1–3巻 (1909–12) に掲載されたヒエラティック字形を検索するためのデータベースです。画像は東京大学東洋文庫所蔵のIIIFイメージを使用しています。ヒエラティック番号，ヒエログリフ番号，音価／語などから検索でき，結果はグリッド・リスト・表・画像・統計の各レイアウトで閲覧できます。

### 検索構文（例）

- 全文検索: `?keyword=hieratic`
- フィールド指定: `Item:X-001`, `HieraticNo:123`
- ファセットフィルタ: `?fc-ItemType=glyph&fc-Unit=Vol1`
- 含む／除外: `?q-HieraticNo=123`（含む）, `?q-HieraticNo=-123`（除外）

### 引用

> 永井正勝・和氣愛仁・高橋洋成・中村覚「Hieratische Paläographie DB」 <https://moeller.jinsha.tsukuba.ac.jp/>

### メンバー

- [永井正勝](https://researchmap.jp/Masakatsu-Nagai/) 筑波大学 図書館情報メディア系 教授
- [和氣愛仁](https://researchmap.jp/wakit/) 筑波大学 人文社会系 准教授
- [高橋洋成](https://researchmap.jp/takahashi.yona) 東京外国語大学 アジア・アフリカ言語文化研究所 研究員
- [中村覚](https://researchmap.jp/nakamura.satoru/) 東京大学 史料編纂所 准教授

### 助成

本研究は日本学術振興会（JSPS）科学研究費の支援を受けています。

---

## Repositories

| Repository | Description |
| --- | --- |
| [`hp-db.github.io`](https://github.com/hp-db/hp-db.github.io) | Main application (Next.js 16 + Tailwind + Radix UI). Deploys to GitHub Pages. |
| [`w3id.org`](https://github.com/hp-db/w3id.org) | Permanent identifier redirects for HPDB URIs via [w3id.org](https://w3id.org). |

## Contact

Masakatsu Nagai — `nagai.masakatsu [at] mail.u-tokyo.ac.jp`
