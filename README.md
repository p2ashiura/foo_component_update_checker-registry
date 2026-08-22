# foo_component_update_checker-registry

Known component registry for [foo_component_update_checker](https://github.com/p2ashiura/foo_component_update_checker),
a foobar2000 component that checks installed components for updates.

This repository contains a single static JSON file (`known_components.json`)
mapping foobar2000 component DLL names to where their releases can be
checked: a repository (GitHub, GitLab, or Codeberg) for most entries, or a
specific page/folder URL (marc2k3.github.io, SourceForge, foobar.hyv.fi) for
sites without a repository-style Releases API. It's fetched anonymously via
`raw.githubusercontent.com`, so no server or API key is needed.

[foo_component_update_checker](https://github.com/p2ashiura/foo_component_update_checker)
(foobar2000用の更新確認コンポーネント)が参照する既知コンポーネント一覧。

foobar2000コンポーネントのDLL名と、そのリリース確認先を対応付けた、単一の
静的JSONファイル(`known_components.json`)を置いている。ほとんどのエントリは
リポジトリ(GitHub・GitLab・Codeberg)だが、リポジトリ形式のReleases APIを
持たないサイト(marc2k3.github.io、SourceForge、foobar.hyv.fi)向けには、特定の
ページ・フォルダのURLを指定する形にも対応している。`raw.githubusercontent.com`
経由で匿名取得するだけなので、サーバーやAPIキーは不要。

## Registered Components / 登録済みコンポーネント

**English**

This table is manually kept in sync with `known_components.json`. If you
add or edit an entry there, please update this table in the same commit
(or pull request).

**日本語**

この表は`known_components.json`と手動で同期している。エントリを追加・編集する際は、
同じコミット(またはPull Request)でこの表も更新すること。

194 components / 194件

| DLL name | Source repository |
| --- | --- |
| `foo_albumtrain` | [p2ashiura/Album-Train (github)](https://github.com/p2ashiura/Album-Train) |
| `foo_api_wizard` | [The-Wizardium/API-Wizard (github)](https://github.com/The-Wizardium/API-Wizard) |
| `foo_artgrab` | [jame25/foo_artgrab (github)](https://github.com/jame25/foo_artgrab) |
| `foo_artist_view` | [veselyvaclavcz/foo_artist_view (github)](https://github.com/veselyvaclavcz/foo_artist_view) |
| `foo_artwork` | [jame25/foo_artwork (github)](https://github.com/jame25/foo_artwork) |
| `foo_audio_wizard` | [The-Wizardium/Audio-Wizard (github)](https://github.com/The-Wizardium/Audio-Wizard) |
| `foo_audiomd5` | [foobar.hyv.fi/?view=foo_audiomd5 (hyv)](https://foobar.hyv.fi/?view=foo_audiomd5) |
| `foo_autoplay` | [sourceforge.net/projects/fooautoplay/files/fooautoplay (sourceforge)](https://sourceforge.net/projects/fooautoplay/files/fooautoplay/) |
| `foo_bbookmark` | [Paremo/foo_bbookmark (github)](https://github.com/Paremo/foo_bbookmark) |
| `foo_beefweb` | [hyperblast/beefweb (github)](https://github.com/hyperblast/beefweb) |
| `foo_bestversion` | [hymerman/foo_bestversion (github)](https://github.com/hymerman/foo_bestversion) |
| `foo_bookbar` | [michaldziwisz/bookbar (github)](https://github.com/michaldziwisz/bookbar) |
| `foo_bpm` | [foobar.hyv.fi/?view=foo_bpm (hyv)](https://foobar.hyv.fi/?view=foo_bpm) |
| `foo_bs2b` | [sourceforge.net/projects/bs2b/files/plugins/Foobar2000%20plugin (sourceforge)](https://sourceforge.net/projects/bs2b/files/plugins/Foobar2000%20plugin/) |
| `foo_cad_nowplaying` | [ghDaYuYu/foo_cad_nowplaying (github)](https://github.com/ghDaYuYu/foo_cad_nowplaying) |
| `foo_cad_plus` | [RangerCD/foo-cad-plus (github)](https://github.com/RangerCD/foo-cad-plus) |
| `foo_catnap` | [stengerh/foo_catnap (github)](https://github.com/stengerh/foo_catnap) |
| `foo_chronflow` | [Chronial/foo_chronflow (github)](https://github.com/Chronial/foo_chronflow) |
| `foo_cnn_bpm` | [NotSimone/foo_cnn_bpm (github)](https://github.com/NotSimone/foo_cnn_bpm) |
| `foo_component_update_checker` | [p2ashiura/foo_component_update_checker (github)](https://github.com/p2ashiura/foo_component_update_checker) |
| `foo_controlserver` | [audiohead/foo_controlserver (github)](https://github.com/audiohead/foo_controlserver) |
| `foo_cover_utils` | [marc2k3.github.io/component/cover-utils (marc2k3)](https://marc2k3.github.io/component/cover-utils/) |
| `foo_coverflow` | [ghDaYuYu/foo_coverflow (github)](https://github.com/ghDaYuYu/foo_coverflow) |
| `foo_cuesheet_creator` | [foobar.hyv.fi/?view=foo_cuesheet_creator (hyv)](https://foobar.hyv.fi/?view=foo_cuesheet_creator) |
| `foo_deemph` | [foobar.hyv.fi/?view=foo_deemph (hyv)](https://foobar.hyv.fi/?view=foo_deemph) |
| `foo_discogger` | [ghDaYuYu/foo_discogger (github)](https://github.com/ghDaYuYu/foo_discogger) |
| `foo_discord_rich` | [shirafukayayoi/foo_discord_rich (github)](https://github.com/shirafukayayoi/foo_discord_rich) |
| `foo_discord_rich` | [TheQwertiest/foo_discord_rich (github)](https://github.com/TheQwertiest/foo_discord_rich) |
| `foo_dop` | [reupen/ipod_manager (github)](https://github.com/reupen/ipod_manager) |
| `foo_downloader` | [Duoslow/foo_music_downloader (github)](https://github.com/Duoslow/foo_music_downloader) |
| `foo_dr_meter` | [foobar.hyv.fi/?view=foo_dr_meter (hyv)](https://foobar.hyv.fi/?view=foo_dr_meter) |
| `foo_drpc` | [ultrasn0w/foo_drpc (github)](https://github.com/ultrasn0w/foo_drpc) |
| `foo_dsd_asio` | [sourceforge.net/projects/sacddecoder/files/foo_dsd_asio (sourceforge)](https://sourceforge.net/projects/sacddecoder/files/foo_dsd_asio/) |
| `foo_dsd_converter` | [sourceforge.net/projects/sacddecoder/files/foo_dsd_converter (sourceforge)](https://sourceforge.net/projects/sacddecoder/files/foo_dsd_converter/) |
| `foo_dsd_processor` | [sourceforge.net/projects/sacddecoder/files/foo_dsd_processor (sourceforge)](https://sourceforge.net/projects/sacddecoder/files/foo_dsd_processor/) |
| `foo_dsp_amp` | [foobar.hyv.fi/?view=foo_dsp_amp (hyv)](https://foobar.hyv.fi/?view=foo_dsp_amp) |
| `foo_dsp_art_resampler` | [foobar.hyv.fi/?view=foo_dsp_art_resampler (hyv)](https://foobar.hyv.fi/?view=foo_dsp_art_resampler) |
| `foo_dsp_convolver` | [foobar.hyv.fi/?view=foo_dsp_convolver (hyv)](https://foobar.hyv.fi/?view=foo_dsp_convolver) |
| `foo_dsp_crossmix` | [foobar.hyv.fi/?view=foo_dsp_crossmix (hyv)](https://foobar.hyv.fi/?view=foo_dsp_crossmix) |
| `foo_dsp_deemph` | [foobar.hyv.fi/?view=foo_dsp_deemph (hyv)](https://foobar.hyv.fi/?view=foo_dsp_deemph) |
| `foo_dsp_delta` | [foobar.hyv.fi/?view=foo_dsp_delta (hyv)](https://foobar.hyv.fi/?view=foo_dsp_delta) |
| `foo_dsp_dither` | [foobar.hyv.fi/?view=foo_dsp_dither (hyv)](https://foobar.hyv.fi/?view=foo_dsp_dither) |
| `foo_dsp_downmixer` | [foobar.hyv.fi/?view=foo_dsp_downmixer (hyv)](https://foobar.hyv.fi/?view=foo_dsp_downmixer) |
| `foo_dsp_dtsenc` | [foobar.hyv.fi/?view=foo_dsp_dtsenc (hyv)](https://foobar.hyv.fi/?view=foo_dsp_dtsenc) |
| `foo_dsp_fadeinout` | [foobar.hyv.fi/?view=foo_dsp_fadeinout (hyv)](https://foobar.hyv.fi/?view=foo_dsp_fadeinout) |
| `foo_dsp_fadeout_on_command` | [foobar.hyv.fi/?view=foo_dsp_fadeout_on_command (hyv)](https://foobar.hyv.fi/?view=foo_dsp_fadeout_on_command) |
| `foo_dsp_fakegapless` | [foobar.hyv.fi/?view=foo_dsp_fakegapless (hyv)](https://foobar.hyv.fi/?view=foo_dsp_fakegapless) |
| `foo_dsp_fsurround` | [foobar.hyv.fi/?view=foo_dsp_fsurround (hyv)](https://foobar.hyv.fi/?view=foo_dsp_fsurround) |
| `foo_dsp_hardclip` | [foobar.hyv.fi/?view=foo_dsp_hardclip (hyv)](https://foobar.hyv.fi/?view=foo_dsp_hardclip) |
| `foo_dsp_health` | [jame25/foo_dsp_health (github)](https://github.com/jame25/foo_dsp_health) |
| `foo_dsp_lcc` | [foobar.hyv.fi/?view=foo_dsp_lcc (hyv)](https://foobar.hyv.fi/?view=foo_dsp_lcc) |
| `foo_dsp_lowpass` | [foobar.hyv.fi/?view=foo_dsp_lowpass (hyv)](https://foobar.hyv.fi/?view=foo_dsp_lowpass) |
| `foo_dsp_mdadither` | [foobar.hyv.fi/?view=foo_dsp_mdadither (hyv)](https://foobar.hyv.fi/?view=foo_dsp_mdadither) |
| `foo_dsp_neutralizer` | [sourceforge.net/projects/dvdadecoder/files/foo_dsp_neutralizer (sourceforge)](https://sourceforge.net/projects/dvdadecoder/files/foo_dsp_neutralizer/) |
| `foo_dsp_nogaps` | [foobar.hyv.fi/?view=foo_dsp_nogaps (hyv)](https://foobar.hyv.fi/?view=foo_dsp_nogaps) |
| `foo_dsp_normalizer` | [foobar.hyv.fi/?view=foo_dsp_normalizer (hyv)](https://foobar.hyv.fi/?view=foo_dsp_normalizer) |
| `foo_dsp_openal` | [sourceforge.net/projects/foobar-openal/files/foo_dsp_openal (sourceforge)](https://sourceforge.net/projects/foobar-openal/files/foo_dsp_openal/) |
| `foo_dsp_pregap` | [foobar.hyv.fi/?view=foo_dsp_pregap (hyv)](https://foobar.hyv.fi/?view=foo_dsp_pregap) |
| `foo_dsp_r8brain_resampler` | [foobar.hyv.fi/?view=foo_dsp_r8brain_resampler (hyv)](https://foobar.hyv.fi/?view=foo_dsp_r8brain_resampler) |
| `foo_dsp_replaygain` | [foobar.hyv.fi/?view=foo_dsp_replaygain (hyv)](https://foobar.hyv.fi/?view=foo_dsp_replaygain) |
| `foo_dsp_resampler` | [foobar.hyv.fi/?view=foo_dsp_resampler (hyv)](https://foobar.hyv.fi/?view=foo_dsp_resampler) |
| `foo_dsp_skip_silence` | [foobar.hyv.fi/?view=foo_dsp_skip_silence (hyv)](https://foobar.hyv.fi/?view=foo_dsp_skip_silence) |
| `foo_dsp_sox_resampler` | [foobar.hyv.fi/?view=foo_dsp_sox_resampler (hyv)](https://foobar.hyv.fi/?view=foo_dsp_sox_resampler) |
| `foo_dsp_speex_resampler` | [foobar.hyv.fi/?view=foo_dsp_speex_resampler (hyv)](https://foobar.hyv.fi/?view=foo_dsp_speex_resampler) |
| `foo_dsp_src_resampler` | [foobar.hyv.fi/?view=foo_dsp_src_resampler (hyv)](https://foobar.hyv.fi/?view=foo_dsp_src_resampler) |
| `foo_dsp_stereoconv` | [foobar.hyv.fi/?view=foo_dsp_stereoconv (hyv)](https://foobar.hyv.fi/?view=foo_dsp_stereoconv) |
| `foo_dsp_width` | [h1data/foo_dsp_width (github)](https://github.com/h1data/foo_dsp_width) |
| `foo_duration_subsong_manager` | [M3MEMonster/Duration_and_Subsong_Manager (github)](https://github.com/M3MEMonster/Duration_and_Subsong_Manager) |
| `foo_external_tags` | [foobar.hyv.fi/?view=foo_external_tags (hyv)](https://foobar.hyv.fi/?view=foo_external_tags) |
| `foo_favorite` | [shirafukayayoi/foo_favorite (github)](https://github.com/shirafukayayoi/foo_favorite) |
| `foo_filename_editor` | [VadimLevo/foo_filename_editor (github)](https://github.com/VadimLevo/foo_filename_editor) |
| `foo_fix` | [ttsping/foo_fix (github)](https://github.com/ttsping/foo_fix) |
| `foo_flex_dsp` | [ghDaYuYu/foo_flex_dsp (github)](https://github.com/ghDaYuYu/foo_flex_dsp) |
| `foo_flowin` | [ttsping/foo_flowin (github)](https://github.com/ttsping/foo_flowin) |
| `foo_hackrf` | [jocover/foo_hackrf (github)](https://github.com/jocover/foo_hackrf) |
| `foo_hdcd` | [foobar.hyv.fi/?view=foo_hdcd (hyv)](https://foobar.hyv.fi/?view=foo_hdcd) |
| `foo_hdcd` | [foobar.hyv.fi/?view=foo_hdcd (hyv)](https://foobar.hyv.fi/?view=foo_hdcd) |
| `foo_httpserver_ctrl` | [sourceforge.net/projects/foohttpserver/files/foohttpserver (sourceforge)](https://sourceforge.net/projects/foohttpserver/files/foohttpserver/) |
| `foo_input_adplug_mac` | [nrlquaker/foo_input_adplug_mac (github)](https://github.com/nrlquaker/foo_input_adplug_mac) |
| `foo_input_amr` | [unjello/foo_input_amr (github)](https://github.com/unjello/foo_input_amr) |
| `foo_input_apt-x100` | [sourceforge.net/projects/dvdadecoder/files/foo_input_apt-x100 (sourceforge)](https://sourceforge.net/projects/dvdadecoder/files/foo_input_apt-x100/) |
| `foo_input_asciimusiccom` | [mk-822/foo_input_asciimusiccom (github)](https://github.com/mk-822/foo_input_asciimusiccom) |
| `foo_input_dtshd` | [sourceforge.net/projects/dvdadecoder/files/foo_input_dtshd (sourceforge)](https://sourceforge.net/projects/dvdadecoder/files/foo_input_dtshd/) |
| `foo_input_dvda` | [sourceforge.net/projects/dvdadecoder/files/foo_input_dvda (sourceforge)](https://sourceforge.net/projects/dvdadecoder/files/foo_input_dvda/) |
| `foo_input_halac` | [foobar.hyv.fi/?view=foo_input_halac (hyv)](https://foobar.hyv.fi/?view=foo_input_halac) |
| `foo_input_pmd` | [stuerp/foo_input_pmd (github)](https://github.com/stuerp/foo_input_pmd) |
| `foo_input_qoa` | [foobar.hyv.fi/?view=foo_input_qoa (hyv)](https://foobar.hyv.fi/?view=foo_input_qoa) |
| `foo_input_sacd` | [sourceforge.net/projects/sacddecoder/files/foo_input_sacd (sourceforge)](https://sourceforge.net/projects/sacddecoder/files/foo_input_sacd/) |
| `foo_input_signal` | [stuerp/foo_input_signal (github)](https://github.com/stuerp/foo_input_signal) |
| `foo_input_spotify` | [FauxFaux/foo_input_spotify (github)](https://github.com/FauxFaux/foo_input_spotify) |
| `foo_input_tak` | [foobar.hyv.fi/?view=foo_input_tak (hyv)](https://foobar.hyv.fi/?view=foo_input_tak) |
| `foo_input_udsd` | [sourceforge.net/projects/sacddecoder/files/macOS%20%2BWindows/foo_input_udsd (sourceforge)](https://sourceforge.net/projects/sacddecoder/files/macOS%20%2BWindows/foo_input_udsd/) |
| `foo_input_wave_loop` | [suwasakix/foo_input_wave_loop (github)](https://github.com/suwasakix/foo_input_wave_loop) |
| `foo_jscript_panel` | [kbuffington/foo_jscript_panel (github)](https://github.com/kbuffington/foo_jscript_panel) |
| `foo_jscript_panel` | [leefan/foo-jscript-panel (github)](https://github.com/leefan/foo-jscript-panel) |
| `foo_lastfm_playcount_sync` | [marc2k3.github.io/component/lastfm-playcount-sync (marc2k3)](https://marc2k3.github.io/component/lastfm-playcount-sync/) |
| `foo_lddc` | [chenmozhijin/foo_lddc (github)](https://github.com/chenmozhijin/foo_lddc) |
| `foo_lirc` | [sourceforge.net/projects/foolirc/files/foo_lirc (sourceforge)](https://sourceforge.net/projects/foolirc/files/foo_lirc/) |
| `foo_listenbrainz2` | [phw/foo_listenbrainz2 (github)](https://github.com/phw/foo_listenbrainz2) |
| `foo_loop_play_with_tags` | [litproca/foo_loop_play_with_tags (github)](https://github.com/litproca/foo_loop_play_with_tags) |
| `foo_loop-sync` | [otoboku/foo_loop-sync (github)](https://github.com/otoboku/foo_loop-sync) |
| `foo_maloja` | [ICTman1076/foo_maloja (github)](https://github.com/ICTman1076/foo_maloja) |
| `foo_matrix_nowplaying` | [jame25/foo_matrix_nowplaying (github)](https://github.com/jame25/foo_matrix_nowplaying) |
| `foo_mediacontrol` | [dumbie/foo_mediacontrol (github)](https://github.com/dumbie/foo_mediacontrol) |
| `foo_midi` | [stuerp/foo_midi (github)](https://github.com/stuerp/foo_midi) |
| `foo_mixcloud` | [zetmar-collab/foo_mixcloud (github)](https://github.com/zetmar-collab/foo_mixcloud) |
| `foo_monthly_stats` | [shirafukayayoi/foo_monthly_stats (github)](https://github.com/shirafukayayoi/foo_monthly_stats) |
| `foo_mpv` | [sammoth/foo_mpv (github)](https://github.com/sammoth/foo_mpv) |
| `foo_musical_key` | [PEERSOFTdev/foo_musical_key (github)](https://github.com/PEERSOFTdev/foo_musical_key) |
| `foo_musicbrainz64` | [marc2k3.github.io/component/musicbrainz64 (marc2k3)](https://marc2k3.github.io/component/musicbrainz64/) |
| `foo_nds` | [foobar.hyv.fi/?view=foo_nds (hyv)](https://foobar.hyv.fi/?view=foo_nds) |
| `foo_nosleep` | [foobar.hyv.fi/?view=foo_nosleep (hyv)](https://foobar.hyv.fi/?view=foo_nosleep) |
| `foo_nosleep_modern` | [LuckyTil/foo_nosleep_modern (github)](https://github.com/LuckyTil/foo_nosleep_modern) |
| `foo_now_playing_helper` | [DeadSix27/foo_now_playing_helper (github)](https://github.com/DeadSix27/foo_now_playing_helper) |
| `foo_nowbar` | [jame25/foo_nowbar (github)](https://github.com/jame25/foo_nowbar) |
| `foo_nowplaying_copy` | [Maximum0303/foo_nowplaying_copy (github)](https://github.com/Maximum0303/foo_nowplaying_copy) |
| `foo_nowplaying2` | [foxx1337/foo_nowplaying2 (github)](https://github.com/foxx1337/foo_nowplaying2) |
| `foo_nsync` | [jame25/foo_nsync (github)](https://github.com/jame25/foo_nsync) |
| `foo_openhacks` | [ttsping/foo_openhacks (github)](https://github.com/ttsping/foo_openhacks) |
| `foo_openhacks_mod` | [simear2004/foo_openhacks_mod (github)](https://github.com/simear2004/foo_openhacks_mod) |
| `foo_openlyrics` | [jacquesh/foo_openlyrics (github)](https://github.com/jacquesh/foo_openlyrics) |
| `foo_opensubsonic` | [michioxd/foo_opensubsonic (github)](https://github.com/michioxd/foo_opensubsonic) |
| `foo_opusenc` | [foobar.hyv.fi/?view=foo_opusenc (hyv)](https://foobar.hyv.fi/?view=foo_opusenc) |
| `foo_out_asio+dsd` | [sourceforge.net/projects/sacddecoder/files/foo_out_asio%2Bdsd (sourceforge)](https://sourceforge.net/projects/sacddecoder/files/foo_out_asio%2Bdsd/) |
| `foo_out_asio2` | [sourceforge.net/projects/foobar2000-wasap2-output/files (sourceforge)](https://sourceforge.net/projects/foobar2000-wasap2-output/files/) |
| `foo_out_digital` | [foobar.hyv.fi/?view=foo_out_digital (hyv)](https://foobar.hyv.fi/?view=foo_out_digital) |
| `foo_out_pulse` | [sammoth/foo_out_pulse (github)](https://github.com/sammoth/foo_out_pulse) |
| `foo_out_spatial` | [foobar.hyv.fi/?view=foo_out_spatial (hyv)](https://foobar.hyv.fi/?view=foo_out_spatial) |
| `foo_out_wasap2-asio2` | [sourceforge.net/projects/foobar2000-wasap2-output/files (sourceforge)](https://sourceforge.net/projects/foobar2000-wasap2-output/files/) |
| `foo_outinfo` | [foobar.hyv.fi/?view=foo_outinfo (hyv)](https://foobar.hyv.fi/?view=foo_outinfo) |
| `foo_pd_aac` | [foobar.hyv.fi/?view=foo_pd_aac (hyv)](https://foobar.hyv.fi/?view=foo_pd_aac) |
| `foo_play_next` | [foobar.hyv.fi/?view=foo_play_next (hyv)](https://foobar.hyv.fi/?view=foo_play_next) |
| `foo_playcount_2003` | [marc2k3.github.io/component/playcount-2003 (marc2k3)](https://marc2k3.github.io/component/playcount-2003/) |
| `foo_playlist_fix` | [marc2k3.github.io/component/playlist-fix (marc2k3)](https://marc2k3.github.io/component/playlist-fix/) |
| `foo_playlist_info` | [foobar.hyv.fi/?view=foo_playlist_info (hyv)](https://foobar.hyv.fi/?view=foo_playlist_info) |
| `foo_playlistclear` | [foobar.hyv.fi/?view=foo_playlistclear (hyv)](https://foobar.hyv.fi/?view=foo_playlistclear) |
| `foo_podcast` | [zetmar-collab/foo_podcast (github)](https://github.com/zetmar-collab/foo_podcast) |
| `foo_popupplus` | [sourceforge.net/projects/foopopupplus/files/foopopupplus (sourceforge)](https://sourceforge.net/projects/foopopupplus/files/foopopupplus/) |
| `foo_previewer` | [stuerp/foo_previewer (github)](https://github.com/stuerp/foo_previewer) |
| `foo_previous` | [terachot/Playback_History_-foo_previous- (github)](https://github.com/terachot/Playback_History_-foo_previous-) |
| `foo_qat` | [michaldziwisz/qat-foobar (github)](https://github.com/michaldziwisz/qat-foobar) |
| `foo_queue_editor` | [ghDaYuYu/foo_queue_editor (github)](https://github.com/ghDaYuYu/foo_queue_editor) |
| `foo_queue_viewer` | [marc2k3.github.io/component/queue-viewer (marc2k3)](https://marc2k3.github.io/component/queue-viewer/) |
| `foo_queuecontents` | [ssalonen/foo_queuecontents (github)](https://github.com/ssalonen/foo_queuecontents) |
| `foo_r128meter` | [stengerh/foo_r128meter (github)](https://github.com/stengerh/foo_r128meter) |
| `foo_record` | [foobar.hyv.fi/?view=foo_record (hyv)](https://foobar.hyv.fi/?view=foo_record) |
| `foo_rehearsal` | [ptytb/foo_rehearsal (github)](https://github.com/ptytb/foo_rehearsal) |
| `foo_renamer` | [foobar.hyv.fi/?view=foo_renamer (hyv)](https://foobar.hyv.fi/?view=foo_renamer) |
| `foo_reset_stop_after_current` | [foobar.hyv.fi/?view=foo_reset_stop_after_current (hyv)](https://foobar.hyv.fi/?view=foo_reset_stop_after_current) |
| `foo_resume` | [reda777/foo_resume (github)](https://github.com/reda777/foo_resume) |
| `foo_resume` | [reda777/foo_resume (github)](https://github.com/reda777/foo_resume) |
| `foo_retain_playtime` | [foobar.hyv.fi/?view=foo_retain_playtime (hyv)](https://foobar.hyv.fi/?view=foo_retain_playtime) |
| `foo_run_xgrp` | [ghDaYuYu/foo_run_xgrp (github)](https://github.com/ghDaYuYu/foo_run_xgrp) |
| `foo_scheduler_mod` | [ghDaYuYu/foo_scheduler_mod (github)](https://github.com/ghDaYuYu/foo_scheduler_mod) |
| `foo_scrobble` | [gix/foo_scrobble (github)](https://github.com/gix/foo_scrobble) |
| `foo_scrobbler_mac` | [zfoxer/foo_scrobbler_mac (github)](https://github.com/zfoxer/foo_scrobbler_mac) |
| `foo_scrobbler_win` | [zfoxer/foo_scrobbler_win (github)](https://github.com/zfoxer/foo_scrobbler_win) |
| `foo_seek_to_time` | [foobar.hyv.fi/?view=foo_seek_to_time (hyv)](https://foobar.hyv.fi/?view=foo_seek_to_time) |
| `foo_shutdown` | [foobar.hyv.fi/?view=foo_shutdown (hyv)](https://foobar.hyv.fi/?view=foo_shutdown) |
| `foo_skip` | [foobar.hyv.fi/?view=foo_skip (hyv)](https://foobar.hyv.fi/?view=foo_skip) |
| `foo_spectrum_seekbar` | [veselyvaclavcz/foobar-spectrum-seekbar (github)](https://github.com/veselyvaclavcz/foobar-spectrum-seekbar) |
| `foo_spider_monkey_panel` | [theqwertiest/foo_spider_monkey_panel (github)](https://github.com/theqwertiest/foo_spider_monkey_panel) |
| `foo_spider_monkey_panel` | [dima-lur/spider-monkey-panel-x64 (github)](https://github.com/dima-lur/spider-monkey-panel-x64) |
| `foo_stop_after_focused` | [foobar.hyv.fi/?view=foo_stop_after_focused (hyv)](https://foobar.hyv.fi/?view=foo_stop_after_focused) |
| `foo_stop_after_queue` | [foobar.hyv.fi/?view=foo_stop_after_queue (hyv)](https://foobar.hyv.fi/?view=foo_stop_after_queue) |
| `foo_stop_after_track` | [foobar.hyv.fi/?view=foo_stop_after_track (hyv)](https://foobar.hyv.fi/?view=foo_stop_after_track) |
| `foo_stop_on_current` | [foobar.hyv.fi/?view=foo_stop_on_current (hyv)](https://foobar.hyv.fi/?view=foo_stop_on_current) |
| `foo_stop_on_error` | [foobar.hyv.fi/?view=foo_stop_on_error (hyv)](https://foobar.hyv.fi/?view=foo_stop_on_error) |
| `foo_strip` | [masterrite/Foo_strip (github)](https://github.com/masterrite/Foo_strip) |
| `foo_subsonic` | [hypfvieh/foo_subsonic (github)](https://github.com/hypfvieh/foo_subsonic) |
| `foo_tag_normalizer` | [foobar.hyv.fi/?view=foo_tag_normalizer (hyv)](https://foobar.hyv.fi/?view=foo_tag_normalizer) |
| `foo_taskbar_playback_progress_bar` | [foobar.hyv.fi/?view=foo_taskbar_playback_progress_bar (hyv)](https://foobar.hyv.fi/?view=foo_taskbar_playback_progress_bar) |
| `foo_tfsandbox` | [stengerh/foo_tfsandbox (github)](https://github.com/stengerh/foo_tfsandbox) |
| `foo_thbgm` | [nyfair/foo_thbgm (github)](https://github.com/nyfair/foo_thbgm) |
| `foo_timesleep` | [shirafukayayoi/foo_timesleep (github)](https://github.com/shirafukayayoi/foo_timesleep) |
| `foo_title` | [TheQwertiest/dotnet_title_bar (github)](https://github.com/TheQwertiest/dotnet_title_bar) |
| `foo_traycontrols` | [jame25/foo_traycontrols (github)](https://github.com/jame25/foo_traycontrols) |
| `foo_ui_columns` | [reupen/columns_ui (github)](https://github.com/reupen/columns_ui) |
| `foo_ui_webview2` | [NereaFantasia/foo_ui_webview2 (github)](https://github.com/NereaFantasia/foo_ui_webview2) |
| `foo_ui_wizard` | [The-Wizardium/UI-Wizard (github)](https://github.com/The-Wizardium/UI-Wizard) |
| `foo_uie_albumart_mod` | [Duny/foo_uie_albumart_mod (github)](https://github.com/Duny/foo_uie_albumart_mod) |
| `foo_uie_eslyric` | [ESLyric/release (github)](https://github.com/ESLyric/release) |
| `foo_uie_jsplitter` | [dima-lur/jsplitter (github)](https://github.com/dima-lur/jsplitter) |
| `foo_uie_output_switcher` | [Chocobo1/foo_uie_output_switcher (github)](https://github.com/Chocobo1/foo_uie_output_switcher) |
| `foo_uie_playlist_tree` | [stuerp/foo_uie_playlist_tree (github)](https://github.com/stuerp/foo_uie_playlist_tree) |
| `foo_uie_webview` | [jecassis/foo_uie_webview (github)](https://github.com/jecassis/foo_uie_webview) |
| `foo_uie_webview` | [stuerp/foo_uie_webview (github)](https://github.com/stuerp/foo_uie_webview) |
| `foo_uie_wsh_panel_mod` | [samithaj/foo_uie_wsh_panel_mod (github)](https://github.com/samithaj/foo_uie_wsh_panel_mod) |
| `foo_uie_wsh_panel_mod_plus` | [ttsping/foo_uie_wsh_panel_mod_plus (github)](https://github.com/ttsping/foo_uie_wsh_panel_mod_plus) |
| `foo_vbookmark` | [ghDaYuYu/foo_vbookmark (github)](https://github.com/ghDaYuYu/foo_vbookmark) |
| `foo_vis_milk2` | [jecassis/foo_vis_milk2 (github)](https://github.com/jecassis/foo_vis_milk2) |
| `foo_vis_spectrum_analyzer` | [stuerp/foo_vis_spectrum_analyzer (github)](https://github.com/stuerp/foo_vis_spectrum_analyzer) |
| `foo_xspf_1` | [Chocobo1/foo_xspf_1 (github)](https://github.com/Chocobo1/foo_xspf_1) |
| `foo_yaarchive_reader` | [mocukie/foo_yaarchive_reader (github)](https://github.com/mocukie/foo_yaarchive_reader) |

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
    },
    {
      "dll": "<DLL name, without .dll extension>",
      "source": "hyv",
      "url": "<full page URL, e.g. https://foobar.hyv.fi/?view=<component>>"
    }
  ]
}
```

`source` must be one of `"github"`, `"gitlab"`, `"codeberg"`, `"marc2k3"`,
`"sourceforge"`, or `"hyv"`. Other values are ignored by the app for now
(reserved for future site support).

Which fields an entry needs depends on its `source`:

- `"github"` / `"gitlab"` / `"codeberg"` — repository-based sites, use
  `owner` + `repo` (no `url`)
- `"marc2k3"` / `"sourceforge"` / `"hyv"` — sites without a repository-style
  Releases API, use `url` instead (no `owner`/`repo`). `marc2k3` and `hyv`
  point to the specific component's page on that one site; `sourceforge`
  points to a project's files folder and works for any SourceForge project

`source`は`"github"` / `"gitlab"` / `"codeberg"` / `"marc2k3"` /
`"sourceforge"` / `"hyv"`のいずれかを指定する。それ以外の値は、現時点では
アプリ側で無視される(将来の対応サイト拡張のために予約されている)。

必要なフィールドは`source`によって異なる:

- `"github"` / `"gitlab"` / `"codeberg"`—リポジトリ形式のサイト。
  `owner` + `repo`を使う(`url`は不要)
- `"marc2k3"` / `"sourceforge"` / `"hyv"`—リポジトリ形式のReleases APIを
  持たないサイト。`owner`/`repo`の代わりに`url`を使う。`marc2k3`と`hyv`は
  そのサイト上の該当コンポーネントの個別ページを指し、`sourceforge`は
  プロジェクトのファイルフォルダを指す(どのSourceForgeプロジェクトでも使える)

Entries registered by a user directly in
[foo_component_update_checker](https://github.com/p2ashiura/foo_component_update_checker)
(via Preferences → Tools → Component Update Checker → Manage Sources...)
always take priority over entries here.

ユーザーが[foo_component_update_checker](https://github.com/p2ashiura/foo_component_update_checker)側
(Preferences → Tools → Component Update Checker → Manage Sources...)で
直接登録した内容は、常にこちらより優先される。

## Contributing / 投稿について

**English**

Pull requests adding new entries to `known_components.json` are welcome
(the component's "Suggest for Shared Registry..." button generates a
ready-to-paste snippet for this, in the correct format for any of the six
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
6つの`source`いずれの場合でも正しい形式でそのまま貼り付けられるスニペットを
生成できる)。レビュー・マージの際は、同じコミットで上記の表も更新すること。

このファイルに含まれるのは、レビュー済みのPull Requestで追加されたエントリのみ。
自動的な収集やスクレイピングは一切行っていない—ここに載っているURLは、
すべて手動で提案され、マージされたものである。

メンテナーはマージ前にPull Requestをレビューするが、リンク先の各リポジトリ・
ページの安全性や継続的な可用性までは保証できない。リリースページを開く際は、
自己の判断で利用すること。

## License / ライセンス

MIT License. See [`LICENSE`](LICENSE) for the full text.

MITライセンス。全文は[`LICENSE`](LICENSE)を参照。
