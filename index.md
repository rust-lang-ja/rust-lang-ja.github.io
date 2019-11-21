---
title: "Home"
---

このサイトでは[Rust][rust-lang]の日本語ドキュメントを公開しています。
Rustは速度、安全性、平行性の3つのゴールにフォーカスしたシステムプログラミング言語です。

## Rustの入門書

- [**プログラミング言語 Rust, 2nd Edition（最新版）/ The Rust Programming Language, Second Edition**][trpl2]
  * Rustプロジェクト公式の入門書を和訳したものです。通称「TRPL」または「the book」
  * じっくり読みたい人向けに[PDF版][trpl2-pdf]もあります

- **プログラミング言語 Rust, 1st Edition / The Rust Programming Language, First Edition**
  * [Rust 1.9版][trpl1-1.9], [Rust 1.6版][trpl1-1.6]
  * 公式の入門書の古いバージョンです

- [**Rust by Example日本語版**][rbe]
  * 動作するサンプルコードを中心に学べる入門書です


## 各種リファレンス、ガイド

- **標準ライブラリリファレンス**
  * お試しで[`Vec<T>`のみ翻訳されています][std-vec]

- [**Rust APIガイドライン**][api-guidelines]
  * Rustライブラリの設計者向けに、APIのデザイン上の推奨事項がまとめられています

- [**エディションガイド / The Edition Guide**][edition-guide]
  * Rustのエディション毎の新機能リストです
  * 翻訳中


## Rustをさらに深く学びたい

- [**Rust裏本 / The Rustnomicon**][nomicon]
  * アンセーフなRustコードを書くにあたって必要な知識がまとめられています
  * 全体の三割ほど翻訳済み。翻訳者募集中


## 目的別に学びたい

### 組込みプログラミング

- [**組込みRust / The Embedded Rust Book**][embedded-book]
  * ベアメタル (マイクロコントローラ) デバイスのファームウェアをRustで開発するためのガイドブック

- [**Discovery**][embedded-discovery]
  * Rustを使ったマイクロコントローラの組込みシステム入門コース
  * STマイクロエレクトロニクス社のSTM32F3DISCOVERYボードを使用します


## 掲載されているドキュメントについて

ここに掲載されている日本語ドキュメントはいずれも[英語版の公式ドキュメント](https://doc.rust-lang.org/)を和訳したものです。
有志によって翻訳・維持されています。

[rust-lang]: https://www.rust-lang.org/ja-JP/
[trpl2]: https://doc.rust-jp.rs/book/second-edition/
[trpl2-pdf]: https://y-yu.github.io/trpl-2nd-pdf/book.pdf
[trpl1-1.9]: https://doc.rust-jp.rs/the-rust-programming-language-ja/1.9/book/
[trpl1-1.6]: https://doc.rust-jp.rs/the-rust-programming-language-ja/1.6/book/
[rbe]: https://doc.rust-jp.rs/rust-by-example-ja/
[std-vec]: https://moshg.github.io/rust-lib-doc-ja/std/vec/
[api-guidelines]: https://sinkuu.github.io/api-guidelines/
[edition-guide]: https://doc.rust-jp.rs/edition-guide/
[nomicon]: https://doc.rust-jp.rs/rust-nomicon-ja/
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
| プログラミング言語 Rust, 2nd Edition | [hazama-yuinyan/book][gh-trpl2] |
| 同 PDF版 | [y-yu/trpl-2nd-pdf][gh-trpl2-pdf] |
| プログラミング言語 Rust, 1st Edition | [rust-lang-ja/the-rust-programming-language-ja][gh-trpl1] |
| Rust by Example日本語版 | [rust-lang-ja/rust-by-example-ja][gh-rbe] |
| 標準ライブラリリファレンス | [moshg/rust-lib-ja][gh-std] |
| Rust APIガイドライン | [sinkuu/api-guidelines][gh-api-guidelines] |
| エディションガイド | [rust-lang-ja/edition-guide][gh-edition-guide] |
| Rust裏本 / The Rustnomicon | [rust-lang-ja/rust-nomicon-ja][gh-nomicon] |
| 組込みRust / The Embedded Rust Book | [tomoyuki-nakabayashi/book][gh-embedded-book] |
| Discovery | [tomoyuki-nakabayashi/discovery][gh-embedded-discovery] |
| その他（doc.rust-jp.rs全般） | [rust-lang-ja/rust-lang-ja.github.io][gh-org] |

[gh-trpl2]: https://github.com/hazama-yuinyan/book
[gh-trpl2-pdf]: https://github.com/y-yu/trpl-2nd-pdf
[gh-trpl1]: https://github.com/rust-lang-ja/the-rust-programming-language-ja
[gh-rbe]: https://github.com/rust-lang-ja/rust-by-example-ja
[gh-std]: https://github.com/moshg/rust-lib-ja
[gh-api-guidelines]: https://github.com/sinkuu/api-guidelines
[gh-edition-guide]: https://github.com/rust-lang-ja/edition-guide
[gh-nomicon]: https://github.com/rust-lang-ja/rust-nomicon-ja
[gh-embedded-book]: https://github.com/tomoyuki-nakabayashi/book
[gh-embedded-discovery]: https://github.com/tomoyuki-nakabayashi/discovery
[gh-org]: https://github.com/rust-lang-ja/rust-lang-ja.github.io


* * *

Copyright &copy; 2018 &ndash; 2019 The Rust Document Writers and Translators. Licensed under
the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0) or
the [MIT license](https://opensource.org/licenses/MIT), at your option.

This file may not be copied, modified, or distributed except according to those terms.
