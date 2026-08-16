# foo_component_update_checker-registry

Known component registry for [foo_component_update_checker](https://github.com/p2ashiura/foo_component_update_checker),
a foobar2000 component that checks installed components for updates.

This repository contains a single static JSON file (`known_components.json`)
mapping foobar2000 component DLL names to where their releases can be
checked: a repository (GitHub, GitLab, or Codeberg) for most entries, or a
specific page/folder URL (marc2k3.github.io, SourceForge) for sites without
a repository-style Releases API. It's fetched anonymously via
`raw.githubusercontent.com`, so no server or API key is needed.

[foo_component_update_checker](https://github.com/p2ashiura/foo_component_update_checker)
(foobar2000用の更新確認コンポーネント)が参照する既知コンポーネント一覧。

foobar2000コンポーネントのDLL名と、そのリリース確認先を対応付けた、単一の
静的JSONファイル(`known_components.json`)を置いている。ほとんどのエントリは
リポジトリ(GitHub・GitLab・Codeberg)だが、リポジトリ形式のReleases APIを
持たないサイト(marc2k3.github.io、SourceForge)向けには、特定のページ・
フォルダのURLを指定する形にも対応している。`raw.githubusercontent.com`経由で
匿名取得するだけなので、サーバーやAPIキーは不要。

## Registered Components / 登録済みコンポーネント

**English**

This table is manually kept in sync with `known_components.json`. If you
add or edit an entry there, please update this table in the same commit
(or pull request).

**日本語**

この表は`known_components.json`と手動で同期している。エントリを追加・編集する際は、
同じコミット(またはPull Request)でこの表も更新すること。

| DLL name | Source repository |
| --- | --- |
| `foo_albumtrain` | [p2ashiura/Album-Train (github)](https://github.com/p2ashiura/Album-Train) |
| `foo_api_wizard` | [The-Wizardium/API-Wizard (github)](https://github.com/The-Wizardium/API-Wizard) |
| `foo_artgrab` | [jame25/foo_artgrab (github)](https://github.com/jame25/foo_artgrab) |
| `foo_artist_view` | [veselyvaclavcz/foo_artist_view (github)](https://github.com/veselyvaclavcz/foo_artist_view) |
| `foo_artwork` | [jame25/foo_artwork (github)](https://github.com/jame25/foo_artwork) |
| `foo_audio_wizard` | [The-Wizardium/Audio-Wizard (github)](https://github.com/The-Wizardium/Audio-Wizard) |
| `foo_bbookmark` | [Paremo/foo_bbookmark (github)](https://github.com/Paremo/foo_bbookmark) |
| `foo_beefweb` | [hyperblast/beefweb (github)](https://github.com/hyperblast/beefweb) |
| `foo_bestversion` | [hymerman/foo_bestversion (github)](https://github.com/hymerman/foo_bestversion) |
| `foo_bookbar` | [michaldziwisz/bookbar (github)](https://github.com/michaldziwisz/bookbar) |
| `foo_cad_nowplaying` | [ghDaYuYu/foo_cad_nowplaying (github)](https://github.com/ghDaYuYu/foo_cad_nowplaying) |
| `foo_cad_plus` | [RangerCD/foo-cad-plus (github)](https://github.com/RangerCD/foo-cad-plus) |
| `foo_catnap` | [stengerh/foo_catnap (github)](https://github.com/stengerh/foo_catnap) |
| `foo_chronflow` | [Chronial/foo_chronflow (github)](https://github.com/Chronial/foo_chronflow) |
| `foo_cnn_bpm` | [NotSimone/foo_cnn_bpm (github)](https://github.com/NotSimone/foo_cnn_bpm) |
| `foo_component_update_checker` | [p2ashiura/foo_component_update_checker (github)](https://github.com/p2ashiura/foo_component_update_checker) |
| `foo_controlserver` | [audiohead/foo_controlserver (github)](https://github.com/audiohead/foo_controlserver) |
| `foo_cover_utils` | [marc2k3: marc2k3.github.io/component/cover-utils](https://marc2k3.github.io/component/cover-utils/) |
| `foo_coverflow` | [ghDaYuYu/foo_coverflow (github)](https://github.com/ghDaYuYu/foo_coverflow) |
| `foo_discogger` | [ghDaYuYu/foo_discogger (github)](https://github.com/ghDaYuYu/foo_discogger) |
| `foo_discord_rich` | [TheQwertiest/foo_discord_rich (github)](https://github.com/TheQwertiest/foo_discord_rich) |
| `foo_discord_rich` | [shirafukayayoi/foo_discord_rich (github)](https://github.com/shirafukayayoi/foo_discord_rich) |
| `foo_dop` | [reupen/ipod_manager (github)](https://github.com/reupen/ipod_manager) |
| `foo_downloader` | [Duoslow/foo_music_downloader (github)](https://github.com/Duoslow/foo_music_downloader) |
| `foo_drpc` | [ultrasn0w/foo_drpc (github)](https://github.com/ultrasn0w/foo_drpc) |
| `foo_dsd_asio` | [sourceforge: sourceforge.net/projects/sacddecoder/files/foo_dsd_asio](https://sourceforge.net/projects/sacddecoder/files/foo_dsd_asio/) |
| `foo_dsd_converter` | [sourceforge: sourceforge.net/projects/sacddecoder/files/foo_dsd_converter](https://sourceforge.net/projects/sacddecoder/files/foo_dsd_converter/) |
| `foo_dsd_processor` | [sourceforge: sourceforge.net/projects/sacddecoder/files/foo_dsd_processor](https://sourceforge.net/projects/sacddecoder/files/foo_dsd_processor/) |
| `foo_dsp_health` | [jame25/foo_dsp_health (github)](https://github.com/jame25/foo_dsp_health) |
| `foo_dsp_width` | [h1data/foo_dsp_width (github)](https://github.com/h1data/foo_dsp_width) |
| `foo_duration_subsong_manager` | [M3MEMonster/Duration_and_Subsong_Manager (github)](https://github.com/M3MEMonster/Duration_and_Subsong_Manager) |
| `foo_favorite` | [shirafukayayoi/foo_favorite (github)](https://github.com/shirafukayayoi/foo_favorite) |
| `foo_filename_editor` | [VadimLevo/foo_filename_editor (github)](https://github.com/VadimLevo/foo_filename_editor) |
| `foo_fix` | [ttsping/foo_fix (github)](https://github.com/ttsping/foo_fix) |
| `foo_flex_dsp` | [ghDaYuYu/foo_flex_dsp (github)](https://github.com/ghDaYuYu/foo_flex_dsp) |
| `foo_flowin` | [ttsping/foo_flowin (github)](https://github.com/ttsping/foo_flowin) |
| `foo_hackrf` | [jocover/foo_hackrf (github)](https://github.com/jocover/foo_hackrf) |
| `foo_input_adplug_mac` | [nrlquaker/foo_input_adplug_mac (github)](https://github.com/nrlquaker/foo_input_adplug_mac) |
| `foo_input_amr` | [unjello/foo_input_amr (github)](https://github.com/unjello/foo_input_amr) |
| `foo_input_asciimusiccom` | [mk-822/foo_input_asciimusiccom (github)](https://github.com/mk-822/foo_input_asciimusiccom) |
| `foo_input_pmd` | [stuerp/foo_input_pmd (github)](https://github.com/stuerp/foo_input_pmd) |
| `foo_input_sacd` | [sourceforge: sourceforge.net/projects/sacddecoder/files/foo_input_sacd](https://sourceforge.net/projects/sacddecoder/files/foo_input_sacd/) |
| `foo_input_signal` | [stuerp/foo_input_signal (github)](https://github.com/stuerp/foo_input_signal) |
| `foo_input_spotify` | [FauxFaux/foo_input_spotify (github)](https://github.com/FauxFaux/foo_input_spotify) |
| `foo_input_wave_loop` | [suwasakix/foo_input_wave_loop (github)](https://github.com/suwasakix/foo_input_wave_loop) |
| `foo_jscript_panel` | [kbuffington/foo_jscript_panel (github)](https://github.com/kbuffington/foo_jscript_panel) |
| `foo_jscript_panel` | [leefan/foo-jscript-panel (github)](https://github.com/leefan/foo-jscript-panel) |
| `foo_lastfm_playcount_sync` | [marc2k3: marc2k3.github.io/component/lastfm-playcount-sync](https://marc2k3.github.io/component/lastfm-playcount-sync/) |
| `foo_lddc` | [chenmozhijin/foo_lddc (github)](https://github.com/chenmozhijin/foo_lddc) |
| `foo_midi` | [stuerp/foo_midi (github)](https://github.com/stuerp/foo_midi) |
| `foo_mixcloud` | [zetmar-collab/foo_mixcloud (github)](https://github.com/zetmar-collab/foo_mixcloud) |
| `foo_musicbrainz64` | [marc2k3: marc2k3.github.io/component/musicbrainz64](https://marc2k3.github.io/component/musicbrainz64/) |
| `foo_nowbar` | [jame25/foo_nowbar (github)](https://github.com/jame25/foo_nowbar) |
| `foo_nowplaying2` | [foxx1337/foo_nowplaying2 (github)](https://github.com/foxx1337/foo_nowplaying2) |
| `foo_openhacks` | [ttsping/foo_openhacks (github)](https://github.com/ttsping/foo_openhacks) |
| `foo_openhacks_mod` | [simear2004/foo_openhacks_mod (github)](https://github.com/simear2004/foo_openhacks_mod) |
| `foo_openlyrics` | [jacquesh/foo_openlyrics (github)](https://github.com/jacquesh/foo_openlyrics) |
| `foo_out_asio+dsd` | [sourceforge: sourceforge.net/projects/sacddecoder/files/foo_out_asio%2Bdsd](https://sourceforge.net/projects/sacddecoder/files/foo_out_asio%2Bdsd/) |
| `foo_playcount_2003` | [marc2k3: marc2k3.github.io/component/playcount-2003](https://marc2k3.github.io/component/playcount-2003/) |
| `foo_playlist_fix` | [marc2k3: marc2k3.github.io/component/playlist-fix](https://marc2k3.github.io/component/playlist-fix/) |
| `foo_podcast` | [zetmar-collab/foo_podcast (github)](https://github.com/zetmar-collab/foo_podcast) |
| `foo_previous` | [terachot/Playback_History_-foo_previous- (github)](https://github.com/terachot/Playback_History_-foo_previous-) |
| `foo_queue_editor` | [ghDaYuYu/foo_queue_editor (github)](https://github.com/ghDaYuYu/foo_queue_editor) |
| `foo_queue_viewer` | [marc2k3: marc2k3.github.io/component/queue-viewer](https://marc2k3.github.io/component/queue-viewer/) |
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
    },
    {
      "dll": "<DLL name, without .dll extension>",
      "source": "marc2k3",
      "url": "<full page URL, e.g. https://marc2k3.github.io/component/xxx/>"
    },
    {
      "dll": "<DLL name, without .dll extension>",
      "source": "sourceforge",
      "url": "<project files folder URL, e.g. https://sourceforge.net/projects/<project>/files/<folder>/>"
    }
  ]
}
```

`source` must be one of `"github"`, `"gitlab"`, `"codeberg"`, `"marc2k3"`,
or `"sourceforge"`. Other values are ignored by the app for now (reserved
for future site support).

Which fields an entry needs depends on its `source`:

- `"github"` / `"gitlab"` / `"codeberg"` — repository-based sites, use
  `owner` + `repo` (no `url`)
- `"marc2k3"` / `"sourceforge"` — sites without a repository-style
  Releases API, use `url` instead (no `owner`/`repo`). `marc2k3` points to
  the specific component's page on that one site; `sourceforge` points to
  a project's files folder and works for any SourceForge project

`source`は`"github"` / `"gitlab"` / `"codeberg"` / `"marc2k3"` /
`"sourceforge"`のいずれかを指定する。それ以外の値は、現時点ではアプリ側で
無視される(将来の対応サイト拡張のために予約されている)。

必要なフィールドは`source`によって異なる:

- `"github"` / `"gitlab"` / `"codeberg"` — リポジトリ形式のサイト。
  `owner` + `repo`を使う(`url`は不要)
- `"marc2k3"` / `"sourceforge"` — リポジトリ形式のReleases APIを持たない
  サイト。`owner`/`repo`の代わりに`url`を使う。`marc2k3`はそのサイト上の
  該当コンポーネントの個別ページを指し、`sourceforge`はプロジェクトの
  ファイルフォルダを指す(どのSourceForgeプロジェクトでも使える)

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
ready-to-paste snippet for this, in the correct format for any of the five
supported `source` values). When reviewing/merging, please also update the
table above in the same commit.

This file only contains entries added via reviewed pull requests. Nothing
is collected automatically or scraped — every URL in this repository was
manually proposed and merged.

Maintainers review pull requests before merging, but cannot guarantee the
safety or continued availability of every linked repository or page. Use
your own judgment before visiting a release page.

**日本語**

`known_components.json`への新規エントリ追加のPull Requestを歓迎する
(コンポーネント側の「Suggest for Shared Registry...」ボタンから、対応する
5つの`source`いずれの場合でも正しい形式でそのまま貼り付けられるスニペットを
生成できる)。レビュー・マージの際は、同じコミットで上記の表も更新すること。

このファイルに含まれるのは、レビュー済みのPull Requestで追加されたエントリのみ。
自動的な収集やスクレイピングは一切行っていない — ここに載っているURLは、
すべて手動で提案され、マージされたものである。

メンテナーはマージ前にPull Requestをレビューするが、リンク先の各リポジトリ・
ページの安全性や継続的な可用性までは保証できない。リリースページを開く際は、
自己の判断で利用すること。

## License / ライセンス

MIT License. See [`LICENSE`](LICENSE) for the full text.

MITライセンス。全文は[`LICENSE`](LICENSE)を参照。
