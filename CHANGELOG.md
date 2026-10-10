# S2J Site Policy Manager - CHANGELOG

## unreleased

## 0.0.1 - 2026-10-10

### Changed

* `docs_mod/product-direction.md` の「種別へ広げる」を「種別に広げる」に、「経緯へ移し」を「経緯に移し」に直した。

## 0.0.1 - 2026-10-08

### Changed

* `docs_mod/product-direction.md` の「次」を「下記」または「右記」に、「とき」を「場合」に直した。

## 0.0.1 - 2026-10-04

### Changed

* `@s2j/docs-linter` を v1.0.27に上げた。

## 0.0.1 - 2026-10-03

### Changed

* `@s2j/docs-linter` を v1.0.26、`rollup` を v4.64.0、`vite` を v8.3.2に上げ、`overrides` の rollup も合わせた。
* `.vscode/settings.json` で `npm.enableScriptExplorer` を外し、`json.schemaDownload.enable` を有効にした。

## 0.0.1 - 2026-10-01

### Changed

* `docs_mod/product-direction.md` で、監修済み文章のライセンスをプラグインと同じ GPL-3.0-or-later とし、ひな型の本文はこのリポジトリに同梱すると決めた。未決だった2項目を閉じた。

## 0.0.1 - 2026-09-29

### Changed

* `docs_mod/product-direction.md` の見出しに製品名を付けた。KIS WordPress 側で名称を S2J Site Policy Manager に改めたため、未決の改称項目を閉じた。
* リポジトリ名を `s2j-site-policy-manager` とした。スラッグの `s2j-site-policy` だけでは、プラグインが何をするものかが伝わらないためである。`package.json` の name と GitHub の URL を合わせた。

* 製品の方向性を検討メモ `docs_mod/product-direction.md` に記録した。表示名、台帳、段階を含み、仕様本文ではない。
* `docs_mod/specs.md` から検討メモに案内し、仕様本文は方向性を確定したあとに書くとした。
* リポジトリ名を `s2j-site-policy` とし、`package.json` の name と GitHub の URL を合わせた。

## 0.0.1 - 2026-09-28

* `package.json` を追加し、description は暫定文言にした。
* npm@12の EALLOWGIT に対応するため、`.npmrc` で Git 依存の取得を許可した。
* `@s2j/docs-linter` を導入し、ドキュメント lint と install script を設定した。
