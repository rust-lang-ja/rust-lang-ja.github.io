---
title: "Home"
---

このサイトでは[Rust][rust-lang]の日本語ドキュメントを公開しています。
Rustはパフォーマンス、安全性、生産性に優れるプログラミング言語です。

## Rustの入門書

- [**プログラミング言語Rust日本語版**][trpl]
  * Rustプロジェクト公式の入門書「The Rust Programming Language」を和訳したものです。通称「TRPL」または「the book」
  * Rust 2018 Editionに**対応**しています。最新の英語版をベースにしていますが、一部、古いところも残っています
  * じっくり読みたい人向けに[PDF版][trpl-pdf]もあります

- [**Rust by Example日本語版**][rbe]
  * 動作するサンプルコードを中心に学べる入門書です
  * Rust 2018 Editionに**対応**しています。2020年ごろの英語版をベースにしていますが、一部未翻訳です


## 各種リファレンス、ガイド

- **標準ライブラリリファレンス**
  * 以下のモジュールについて和訳があります
    * [`std::vec`モジュール][std-vec]
    * [`std::slice`モジュール][std-slice]

- [**Rust APIガイドライン**][api-guidelines]
  * Rustライブラリの設計者向けに、APIのデザイン上の推奨事項がまとめられています

- [**エディションガイド日本語版**][edition-guide]
  * Rustのエディション毎の新機能リストです
  * 翻訳者募集中


## Rustをさらに深く学びたい

- [**Rust裏本**][nomicon]
  * 「The Rustnomicon」を和訳したものです
  * アンセーフなRustコードを書くにあたって必要な知識がまとめられています


## 目的別に学びたい

### WebAssembly

- [**RustとWebAssembly**][webassembly-book]
  * 「Rust and WebAssembly」を和訳したものです
  * RustコードからコンパイルしたWebAssembly (WASM)をブラウザで実行させるまでの過程を学べるチュートリアル

### 組込みプログラミング

- [**組込みRust**][embedded-book]
  * 「The Embedded Rust Book」を和訳したものです
  * ベアメタル (マイクロコントローラ) デバイスのファームウェアをRustで開発するためのガイドブック

- [**Discovery**][embedded-discovery]
  * Rustを使ったマイクロコントローラの組込みシステム入門コース
  * STマイクロエレクトロニクス社のSTM32F3DISCOVERYボードを使用します


## 掲載されているドキュメントについて

ここに掲載されている日本語ドキュメントはいずれも[英語版の公式ドキュメント](https://doc.rust-lang.org/)を和訳したものです。
有志によって翻訳・維持されています。

[rust-lang]: https://www.rust-lang.org/ja/
[trpl]: https://doc.rust-jp.rs/book-ja/
[trpl-pdf]: https://doc.rust-jp.rs/book-ja-pdf/book.pdf
[rbe]: https://doc.rust-jp.rs/rust-by-example-ja/
[std-vec]: https://moshg.github.io/rust-lib-doc-ja/std/vec/
[std-slice]: https://moshg.github.io/rust-lib-doc-ja/std/slice/
[api-guidelines]: https://sinkuu.github.io/api-guidelines/
[edition-guide]: https://doc.rust-jp.rs/edition-guide/
[nomicon]: https://doc.rust-jp.rs/rust-nomicon-ja/
[webassembly-book]: https://moshg.github.io/rustwasm-book-ja/
[embedded-book]: https://tomoyuki-nakabayashi.github.io/book/
[embedded-discovery]: https://tomoyuki-nakabayashi.github.io/discovery/


## 内容についての連絡方法

誤訳を見つけたときや翻訳に参加したいときなどは以下の方法にてご連絡ください。

- 各文書のGitHubソースリポジトリのIssuesページ（[下の一覧](#各文書のgithubソースリポジトリ)をご覧ください）
- [rust-jp Slackチーム][slack]の`#translation`チャネル （[入会ページ][slack-reg]）

[slack]: https://rust-jp.slack.com
[slack-reg]: http://rust-jp.herokuapp.com


### 各文書のGitHubソースリポジトリ

| 文書 | GitHubリポジトリ |
|:--- |:--- |
| プログラミング言語 Rust | [rust-lang-ja/book-ja][gh-trpl] |
| 同 PDF版 | [rust-lang-ja/book-ja-pdf][gh-trpl-pdf] |
| Rust by Example日本語版 | [rust-lang-ja/rust-by-example-ja][gh-rbe] |
| 標準ライブラリリファレンス | [moshg/rust-lib-ja][gh-std] |
| Rust APIガイドライン | [sinkuu/api-guidelines][gh-api-guidelines] |
| エディションガイド | [rust-lang-ja/edition-guide][gh-edition-guide] |
| Rust裏本 / The Rustnomicon | [rust-lang-ja/rust-nomicon-ja][gh-nomicon] |
| RustとWebAssembly / Rust and WebAssembly | [moshg/rustwasm-book-ja][gh-webassembly-book] |
| 組込みRust / The Embedded Rust Book | [tomoyuki-nakabayashi/book][gh-embedded-book] |
| Discovery | [tomoyuki-nakabayashi/discovery][gh-embedded-discovery] |
| その他（doc.rust-jp.rs全般） | [rust-lang-ja/rust-lang-ja.github.io][gh-org] |

[gh-trpl]: https://github.com/rust-lang-ja/book-ja
[gh-trpl-pdf]: https://github.com/rust-lang-ja/book-ja-pdf
[gh-rbe]: https://github.com/rust-lang-ja/rust-by-example-ja
[gh-std]: https://github.com/moshg/rust-lib-ja
[gh-api-guidelines]: https://github.com/sinkuu/api-guidelines
[gh-edition-guide]: https://github.com/rust-lang-ja/edition-guide
[gh-nomicon]: https://github.com/rust-lang-ja/rust-nomicon-ja
[gh-webassembly-book]: https://github.com/moshg/rustwasm-book-ja
[gh-embedded-book]: https://github.com/tomoyuki-nakabayashi/book
[gh-embedded-discovery]: https://github.com/tomoyuki-nakabayashi/discovery
[gh-org]: https://github.com/rust-lang-ja/rust-lang-ja.github.io
