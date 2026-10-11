# PC Assistant Mini（Android）の配布

タブレット・スマホの画面の端にいる「相棒」に話しかけると、画面を読んでアプリを操作し、声で知らせる Android アプリの配布場所です。
ソースコードはここにはありません。

- **ダウンロードの案内ページ**：https://skyblueearthjapan.github.io/pc-assistant-mini-releases/
- **いちばん新しい APK**：[Releases](https://github.com/skyblueearthjapan/pc-assistant-mini-releases/releases/latest)
- 必要なもの：Android 11 以降・64 ビットの端末、Wi-Fi などのインターネット

## 更新

アプリの「設定 → アプリの版 →［更新を確かめる］→［更新する］」で入ります（アプリを開いたときにも 1 日 1 回まで確かめます）。
アプリは `update-manifest.json` とその署名 `.sig` を読み、署名・大きさ・SHA-256 を確かめてから入れます。

## 注意

- 合言葉（API キー）・パスワード・アカウントをこちらからお聞きすることはありません。
- Google Play では配っていません。この場所以外から入手した APK は使わないでください。

## ライセンス

このアプリには OpenAI Codex（`codex-app-server`・`codex-code-mode-host` rust-v0.162.1）を同梱しています。
Apache License 2.0 で配布されています：[licenses/codex-LICENSE.txt](licenses/codex-LICENSE.txt)・[licenses/codex-NOTICE.txt](licenses/codex-NOTICE.txt)
