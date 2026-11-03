# インストールと上書き更新

[v1.4.0 公式 Release](https://github.com/k-kaiko/KaikoLibrary/releases/tag/v1.4.0) から `KaikoLibrary.v1.4.0.Setup.exe` と `SHA256SUMS.txt` を入手してください。

## インストール前

- 64 ビット版 Windows 10/11、.NET Framework 4.8、Microsoft Edge WebView2 Runtime が必要です。すべての環境・機器を検証したものではありません。
- インストーラーに信頼された発行元のデジタル署名はなく、「不明な発行元」と表示される場合があります。出所、名前、サイズ、SHA-256 を確認できないファイルは実行しないでください。
- アプリを終了し、元作品と `%LOCALAPPDATA%\KaikoLibrary\UserData` を別々にバックアップしてください。GitHub へアップロードしないでください。

## インストール・更新

1. Release のチェックサムと照合し、ご自身でインストーラーを実行して許諾を確認・同意します。
2. **先にアンインストールしたり UserData を消したりしないでください。** 隔離環境で V1.2.1、V1.3-P3、V1.3-P4 RC、v1.3.0-beta.1、V1.4 candidate.1・candidate.2・rc.1 からの更新を検証しています。他のすべての版を検証したわけではありません。
3. ライブラリ、タグ、お気に入り、グループ、続きから読む機能を確認します。Windows のネイティブ権限確認では、元の主フォルダーを選びます。再登録ではありません。

WebView2 Runtime がなければ、Microsoft の導入ツールで取得するため通信が必要な場合があります。失敗時は [Microsoft 公式サイト](https://developer.microsoft.com/en-us/microsoft-edge/webview2/)から Runtime を入手して再試行してください。

プログラムと個人データは別です。更新・失敗時の復元・アンインストールでのデータ保持は架空の設定で検証しており、全異常環境を保証しません。旧インストーラーとバックアップを保管してください。プログラムを戻しても個人データベースは復元されません。データ削除や再インストールを日常の修復手段にしないでください。[問題の対処](troubleshooting.ja.md)もご覧ください。
