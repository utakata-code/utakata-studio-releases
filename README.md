# Utakata Studio Releases

Utakata Studio(Utakata Studio Mobile IDE・Utakata Studio IDE)の**配布物だけ**を置くリポジトリです。ソースコードは置いていません。

ファイルは [Releases](https://github.com/utakata-code/utakata-studio-releases/releases) にあります。製品と版はタグで分けています。

| タグ | 中身 |
|---|---|
| `mobile-ide-toolchain-<Flutter の版>-<番号>` | Mobile IDE(直接配布版)が「追加の部品」の画面から取る部品(デバッグビルド用のエンジン・よく使うプラグイン・NDK・コード生成の道具)と、その部品のソース一式 |

アプリは自社サイトに置いた一覧(`chunks.json`)を読み、そこに書かれた URL からファイルを取ります。ファイルの大きさと SHA-256 はアプリが照らします。

## ライセンス

各ファイルの中の `offline/licenses/` に、入っている部品のライセンスと告知があります。GPL・LGPL・MPL・EPL などソースの提供が要る部品のソースは、同じリリースの `mide-sources-*.tar` にあります。

---

This repository hosts **release artifacts only** for Utakata Studio (Utakata Studio Mobile IDE and Utakata Studio IDE). It contains no source code. Files are attached to [Releases](https://github.com/utakata-code/utakata-studio-releases/releases), separated by tag. License notices are included in each archive under `offline/licenses/`; corresponding source for copyleft components is in `mide-sources-*.tar` of the same release.
