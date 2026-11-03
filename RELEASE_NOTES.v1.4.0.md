# KaikoLibrary v1.4.0

## 简体中文

KaikoLibrary 是 Windows 本地优先的同人志、漫画、插画与 CG 图集管理阅读器。无需账户，不提供或托管作品，不提供在线下载或云同步。

### 本版更新

- 单页、双页、连续纵向阅读，支持阅读方向和滚轮操作设置；保留文件夹、ZIP、动态 WebP 与续读。
- 精简封面操作、可折叠侧栏、本地数据位置说明；底部阅读控制按需显示，可保持展开。
- 批量标签预览、明确确认、事务与冲突保护及本次会话撤销。成功或取消后保留选择，可连续整理；再次点击“完成整理”退出并清空。
- 取消最后一个标签筛选会返回有效来源目录；目录失效时安全回退。多标签仍按 AND 匹配。
- 顶部分页按宽度显示邻近页码和省略号，点“当前页／总页数”可跳页或到首页、末页，多选工具栏独立分区。
- 修正收藏视图缓存的父路径，避免回到书库时 ZIP 漏显；旧错误缓存按路径在内存恢复，不迁移个人数据。
- 简体中文、English、日本語及 Classic、Simple Light、Warm Paper、Forest Study 四主题。

### 安装、升级与限制

面向 Windows 10/11 64 位，需要 .NET Framework 4.8 与 Microsoft Edge WebView2 Runtime。Runtime 缺失时安装可能连接微软服务。安装包**未签名**，Windows 可能提示“未知发布者”；请核对下面的大小与 SHA-256。

先关闭应用，分别备份原图和 `%LOCALAPPDATA%\KaikoLibrary\UserData`，然后运行安装包覆盖升级，**不需先卸载或清空数据**。隔离测试覆盖 V1.2.1、V1.3-P3、V1.3-P4 RC、v1.3.0-beta.1、V1.4 candidate.1、candidate.2、rc.1。其他升级来源未逐一证明。目录要求原生授权时选择原主目录，不是重新导入。

已知限制：超大图／超长图仍可能完整解码并占用较多内存；加密 ZIP、RAR、7z 不支持；侧键可能被系统或驱动截获；不是所有设备均已测试。程序文件回退不等同于个人数据库恢复。旧版主题截图只作视觉示例。

无须上传收藏；当前未设计主动遥测，但本地数据不保证匿名或加密，诊断日志可能包含路径。反馈请使用 [Issues](https://github.com/k-kaiko/KaikoLibrary/issues)，不要上传私人作品、数据库或敏感路径。免费闭源，仅限自然人个人非商业使用；组织／商业使用须另行许可。详见 [正式三语许可](https://github.com/k-kaiko/KaikoLibrary/blob/main/LICENSE.txt)、[隐私说明](https://github.com/k-kaiko/KaikoLibrary/blob/main/PRIVACY.md)和[安装指南](https://github.com/k-kaiko/KaikoLibrary/blob/main/docs/installation.md)。第三方组件适用独立许可。

## English

KaikoLibrary is a local-first Windows library and reader for doujinshi, manga, illustrations and CG sets. No account is required. It supplies or hosts no works and has no online downloader or cloud sync.

### Changes

- Single, facing-page and vertical-scroll layouts, reading direction and wheel options; folder, ZIP, animated WebP and saved progress remain supported.
- Compact cover actions, a collapsible sidebar and data-location information. Bottom reading controls appear on demand and can stay visible.
- Batch tags with preview, explicit confirmation, transactional/conflict protection and session undo. Success or cancellation retains selected works for further actions. Finish organizing exits selection mode and clears it.
- Removing the final tag filter returns to a validated source folder, or safely falls back if unavailable. Multiple tags still use AND matching.
- Adaptive top pagination with nearby numbers and ellipses. Select current/total to jump or reach either end; selection controls occupy a separate area.
- Fix cached parent paths from favorite views so ZIP works remain visible on the shelf; recover older affected cache rows in memory without personal-data migration.
- Simplified Chinese, English and Japanese; Classic, Simple Light, Warm Paper and Forest Study themes.

### Install, upgrade and limitations

Designed for 64-bit Windows 10/11 with .NET Framework 4.8 and Microsoft Edge WebView2 Runtime. Setup may contact Microsoft if the Runtime is absent. The installer is **unsigned**, so Windows may show “Unknown publisher.” Verify the size and SHA-256 below.

Close the app, back up originals and `%LOCALAPPDATA%\KaikoLibrary\UserData` separately, then run the installer in place. **Do not uninstall first or clear data.** Isolated upgrades cover V1.2.1, V1.3-P3, V1.3-P4 RC, v1.3.0-beta.1 and V1.4 candidate.1, candidate.2 and rc.1. Other sources are not all verified. Native folder authorization uses the original root and is not a reimport.

Very large or long images may still be fully decoded and consume substantial memory. Encrypted ZIP, RAR and 7z are unsupported. Drivers or Windows may intercept side buttons; not every device has been tested. Restoring program files is not database recovery. Older theme screenshots are illustrations.

No collection upload is required; there is no designed active telemetry. Local storage is not guaranteed anonymous or encrypted, and diagnostics can contain paths. Use [Issues](https://github.com/k-kaiko/KaikoLibrary/issues) without private works, databases or sensitive paths. Free, closed source, for individual personal non-commercial use; organizations and commercial use need separate permission. See the [three-language license](https://github.com/k-kaiko/KaikoLibrary/blob/main/LICENSE.txt), [privacy notice](https://github.com/k-kaiko/KaikoLibrary/blob/main/PRIVACY.en.md) and [installation guide](https://github.com/k-kaiko/KaikoLibrary/blob/main/docs/installation.en.md). Third-party licenses apply independently.

## 日本語

KaikoLibrary は同人誌、漫画、イラスト、CG 集のための Windows ローカル優先ライブラリ・閲覧アプリです。アカウント不要で、作品の提供・ホスト、オンライン取得、クラウド同期は行いません。

### 更新内容

- 単ページ・見開き・縦スクロール、閲覧方向とホイール設定。フォルダー、ZIP、動く WebP、続きから読む機能を維持します。
- 簡潔な表紙操作、折り畳めるサイドバー、データ保存先の案内。下部閲覧操作は必要時に表示し、常時表示も選べます。
- タグ一括操作のプレビュー、明示的な確認、トランザクション・競合保護、セッション内取り消し。成功・キャンセル後は選択を保持し、［整理を終了］でモード終了と選択解除を行います。
- 最後のタグ絞り込みを外すと有効性を確認した元フォルダーへ戻り、利用できなければ安全に戻ります。複数タグは引き続き AND 条件です。
- 幅に応じた上部ページ番号と省略記号。現在／総ページ数から指定ページ・最初・最後へ移動でき、複数選択操作は独立した領域に表示します。
- お気に入り表示からのキャッシュ親パスを修正し、本棚で ZIP が欠ける問題を防ぎます。既存の該当キャッシュは個人データを移行せずメモリー内で復元します。
- 簡体字中国語・英語・日本語と Classic、Simple Light、Warm Paper、Forest Study の 4 テーマ。

### 導入・更新と制限

64 ビット版 Windows 10/11、.NET Framework 4.8、Microsoft Edge WebView2 Runtime が必要です。Runtime がない場合は Microsoft への通信が必要なことがあります。インストーラーは**未署名**で「不明な発行元」と表示される場合があります。下記のサイズと SHA-256 を確認してください。

アプリを終了し、元画像と `%LOCALAPPDATA%\KaikoLibrary\UserData` を別々にバックアップしてから上書き更新してください。**先にアンインストールしたりデータを削除したりしないでください。** 隔離検証した更新元は V1.2.1、V1.3-P3、V1.3-P4 RC、v1.3.0-beta.1、V1.4 candidate.1・candidate.2・rc.1 です。他のすべての版を確認したわけではありません。ネイティブ権限確認では元の主フォルダーを選択します。再登録ではありません。

大きい画像や長い画像は全体のデコードに多くのメモリーを使う場合があります。暗号化 ZIP、RAR、7z は非対応です。サイドボタンはシステムやドライバーに先に処理されることがあり、全機器は未検証です。プログラムを戻しても個人データベースは復元されません。旧版テーマの画像は参考例です。

作品のアップロードは不要で、能動的テレメトリーは設計していませんが、匿名性や暗号化保存を保証しません。診断にはパスが含まれる場合があります。[Issues](https://github.com/k-kaiko/KaikoLibrary/issues) に私有作品、データベース、機密パスを添付しないでください。無料・非公開ソースで、自然人の個人的・非商用利用のみ許諾し、組織・商用利用には別途許可が必要です。[三言語の許諾](https://github.com/k-kaiko/KaikoLibrary/blob/main/LICENSE.txt)、[プライバシー](https://github.com/k-kaiko/KaikoLibrary/blob/main/PRIVACY.ja.md)、[導入案内](https://github.com/k-kaiko/KaikoLibrary/blob/main/docs/installation.ja.md)を参照してください。第三者ライセンスは独立して適用されます。

## Download / 下载 / ダウンロード

- `KaikoLibrary.v1.4.0.Setup.exe` — **2,931,200 bytes**
- SHA-256: `19a45bf4ada1e49a4dad7d34d9a8356696ff98c4a7e9de2e5da93b970d82c4df`
- Download the installer asset, not GitHub's automatic “Source code” archives. This public repository contains release documents only; private application sources are not published.
- 请下载安装器附件；GitHub 自动生成的 Source code 归档只有公开发行资料，不包含私有程序源码。
- インストーラー添付を選んでください。自動生成の Source code アーカイブは公開資料のみで、アプリの非公開ソースは含みません。
