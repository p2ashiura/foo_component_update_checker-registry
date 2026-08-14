# foo_component_update_checker-registry

Known component registry for [foo_component_update_checker](https://github.com/p2ashiura/foo_component_update_checker),
a foobar2000 component that checks installed components for updates.

This repository contains a single static JSON file (`known_components.json`)
mapping foobar2000 component DLL names to their public source repositories
(GitHub, GitLab, or Codeberg). It's fetched anonymously via
`raw.githubusercontent.com`, so no server or API key is needed.

[foo_component_update_checker](https://github.com/p2ashiura/foo_component_update_checker)
(foobar2000用の更新確認コンポーネント)が参照する既知コンポーネント一覧。

foobar2000コンポーネントのDLL名と、その公開リポジトリ(GitHub・GitLab・Codeberg)を
対応付けた、単一の静的JSONファイル(`known_components.json`)を置いている。
`raw.githubusercontent.com`経由で匿名取得するだけなので、サーバーやAPIキーは不要。

## Registered Components / 登録済みコンポーネント

**English**

This table is manually kept in sync with `known_components.json`. If you
add or edit an entry there, please update this table in the same commit
(or pull request).

| DLL name | Source repository |
| --- | --- |
| `foo_albumtrain` | [p2ashiura/Album-Train (github)](https://github.com/p2ashiura/Album-Train) |
| `foo_artist_view` | [veselyvaclavcz/foo_artist_view (github)](https://github.com/veselyvaclavcz/foo_artist_view) |
| `foo_artwork` | [jame25/foo_artwork (github)](https://github.com/jame25/foo_artwork) |
| `foo_component_update_checker` | [p2ashiura/foo_component_update_checker (github)](https://github.com/p2ashiura/foo_component_update_checker) |
| `foo_coverflow` | [ghDaYuYu/foo_coverflow (github)](https://github.com/ghDaYuYu/foo_coverflow) |
| `foo_discogger` | [ghDaYuYu/foo_discogger (github)](https://github.com/ghDaYuYu/foo_discogger) |
| `foo_flowin` | [ttsping/foo_flowin (github)](https://github.com/ttsping/foo_flowin) |
| `foo_midi` | [stuerp/foo_midi (github)](https://github.com/stuerp/foo_midi) |
| `foo_mixcloud` | [zetmar-collab/foo_mixcloud (github)](https://github.com/zetmar-collab/foo_mixcloud) |
| `foo_nowbar` | [jame25/foo_nowbar (github)](https://github.com/jame25/foo_nowbar) |
| `foo_nowplaying2` | [foxx1337/foo_nowplaying2 (github)](https://github.com/foxx1337/foo_nowplaying2) |
| `foo_openhacks` | [ttsping/foo_openhacks (github)](https://github.com/ttsping/foo_openhacks) |
| `foo_openhacks_mod` | [simear2004/foo_openhacks_mod (github)](https://github.com/simear2004/foo_openhacks_mod) |
| `foo_openlyrics` | [jacquesh/foo_openlyrics (github)](https://github.com/jacquesh/foo_openlyrics) |
| `foo_podcast` | [zetmar-collab/foo_podcast (github)](https://github.com/zetmar-collab/foo_podcast) |
| `foo_previous` | [terachot/Playback_History_-foo_previous- (github)](https://github.com/terachot/Playback_History_-foo_previous-) |
| `foo_queue_editor` | [ghDaYuYu/foo_queue_editor (github)](https://github.com/ghDaYuYu/foo_queue_editor) |
| `foo_queuecontents` | [ssalonen/foo_queuecontents (github)](https://github.com/ssalonen/foo_queuecontents) |
| `foo_resume` | [reda777/foo_resume (github)](https://github.com/reda777/foo_resume) |
| `foo_run_xgrp` | [ghDaYuYu/foo_run_xgrp (github)](https://github.com/ghDaYuYu/foo_run_xgrp) |
| `foo_scrobble` | [gix/foo_scrobble (github)](https://github.com/gix/foo_scrobble) |
| `foo_spider_monkey_panel` | [theqwertiest/foo_spider_monkey_panel (github)](https://github.com/theqwertiest/foo_spider_monkey_panel) |
| `foo_strip` | [masterrite/Foo_strip (github)](https://github.com/masterrite/Foo_strip) |
| `foo_traycontrols` | [jame25/foo_traycontrols (github)](https://github.com/jame25/foo_traycontrols) |
| `foo_ui_columns` | [reupen/columns_ui (github)](https://github.com/reupen/columns_ui) |
| `foo_uie_webview` | [stuerp/foo_uie_webview (github)](https://github.com/stuerp/foo_uie_webview) |
| `foo_uie_webview` | [jecassis/foo_uie_webview (github)](https://github.com/jecassis/foo_uie_webview) |
| `foo_vbookmark` | [ghDaYuYu/foo_vbookmark (github)](https://github.com/ghDaYuYu/foo_vbookmark) |
| `foo_vis_milk2` | [jecassis/foo_vis_milk2 (github)](https://github.com/jecassis/foo_vis_milk2) |
| `foo_vis_spectrum_analyzer` | [stuerp/foo_vis_spectrum_analyzer (github)](https://github.com/stuerp/foo_vis_spectrum_analyzer) |

### Disabled / 無効化済み

**English**

These entries are kept in `known_components.json` under a separate
`disabled` key (not `components`), so the app never reads them. Listed
here for reference only.

| DLL name | Former repository | Reason |
| --- | --- | --- |
| `foo_jscript_panel3` | jscript-panel/release (github) | Releases page no longer exists as of 2026-08; development appears abandoned |

**日本語**

これらのエントリは`known_components.json`内の`components`ではなく別の
`disabled`キーに保持しており、アプリ側からは読まれない。参考情報として
記載しているのみ。

**日本語**

この表は`known_components.json`と手動で同期している。エントリを追加・編集する際は、
同じコミット(またはPull Request)でこの表も更新すること。

## Schema

```json
{
  "schema_version": 1,
  "components": [
    {
      "dll": "<DLL name, without .dll extension>",
      "source": "github",
      "owner": "<username or org>",
      "repo": "<repository name>"
    }
  ]
}
```

`source` must be one of `"github"`, `"gitlab"`, or `"codeberg"`. Other
values are ignored by the app for now (reserved for future site support).

`source`は`"github"` / `"gitlab"` / `"codeberg"`のいずれかを指定する。
それ以外の値は、現時点ではアプリ側で無視される(将来の対応サイト拡張のために
予約されている)。

Entries registered by a user directly in
[foo_component_update_checker](https://github.com/p2ashiura/foo_component_update_checker)
(via Preferences → Tools → Component Update Checker → Manage Repositories...)
always take priority over entries here.

ユーザーが[foo_component_update_checker](https://github.com/p2ashiura/foo_component_update_checker)側
(Preferences → Tools → Component Update Checker → Manage Repositories...)で
直接登録した内容は、常にこちらより優先される。

## Contributing / 投稿について

**English**

Pull requests adding new entries to `known_components.json` are welcome
(the component's "Suggest for Shared Registry..." button generates a
ready-to-paste snippet for this). When reviewing/merging, please also
update the table above in the same commit.

This file only contains entries added via reviewed pull requests. Nothing
is collected automatically or scraped — every URL in this repository was
manually proposed and merged.

Maintainers review pull requests before merging, but cannot guarantee the
safety or continued availability of every linked repository. Use your own
judgment before visiting a release page.

**日本語**

`known_components.json`への新規エントリ追加のPull Requestを歓迎する
(コンポーネント側の「Suggest for Shared Registry...」ボタンから、そのまま
貼り付けられるスニペットを生成できる)。レビュー・マージの際は、同じ
コミットで上記の表も更新すること。

このファイルに含まれるのは、レビュー済みのPull Requestで追加されたエントリのみ。
自動的な収集やスクレイピングは一切行っていない — ここに載っているURLは、
すべて手動で提案され、マージされたものである。

メンテナーはマージ前にPull Requestをレビューするが、リンク先の各リポジトリの
安全性や継続的な可用性までは保証できない。リリースページを開く際は、
自己の判断で利用すること。

## License / ライセンス

MIT License. See [`LICENSE`](LICENSE) for the full text.

MITライセンス。全文は[`LICENSE`](LICENSE)を参照。
