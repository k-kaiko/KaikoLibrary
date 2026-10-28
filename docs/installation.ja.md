# インストールと更新

> Public Beta v1.3.0-beta.1 は[公式 Release](https://github.com/k-kaiko/KaikoLibrary/releases/tag/v1.3.0-beta.1)で公開しています。

## 事前準備

- **64 ビット版 Windows 10/11** 向けです。.NET Framework 4.8 と Microsoft Edge WebView2 Runtime が必要です。すべての機器での互換性は Beta で確認します。
- インストーラーと SHA-256 は、本リポジトリの[公式 Releases](https://github.com/k-kaiko/KaikoLibrary/releases)からのみ入手してください。インストーラーの名前、サイズ、SHA-256 を Release の記載と照合してください。
- 最初のインストーラーには信頼された発行者のデジタル署名がありません。Windows に「不明な発行元」と表示される場合があります。入手元が確認できないファイルは実行しないでください。

## インストール・上書き更新

1. KaikoLibrary を終了し、元画像と `%LOCALAPPDATA%\KaikoLibrary\UserData` をバックアップします。GitHub にはアップロードしないでください。
2. 公式インストーラーを入手し、Release に記載された SHA-256 と照合します。
3. ご自身で実行します。隔離環境では V1.2.1、V1.3-P3、V1.3-P4 RC からの上書き更新を確認しました。**先にアンインストールしたり UserData を削除したりしないでください**。その他の旧版では旧インストーラーを保管し、互換性の案内を待ってください。
4. 起動後、ライブラリ、お気に入り、タグ、進捗を確認します。フォルダー権限の確認が出たら、元の主フォルダーを選びます。再登録ではありません。

WebView2 Runtime がない場合、セットアップが Microsoft のブートストラッパーを使用し、ネット接続が必要になる場合があります。失敗した場合は[Microsoft の公式 WebView2 ページ](https://developer.microsoft.com/en-us/microsoft-edge/webview2/)から Runtime を入手し、再試行してください。

プログラムと個人データは別の場所にあり、更新・アンインストール時に後者を保持する設計です。大切な作品は別途バックアップしてください。[よくある問題](troubleshooting.ja.md)もご覧ください。データ消去は通常の修復方法ではありません。
