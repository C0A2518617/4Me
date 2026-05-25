# 🌙 YorunoBrowser

> **AppStoreに絶対通らない最強裏ブラウザ** — iOSで動作する、片手特化型ウェブブラウザ & ファイルマネージャー

[![Platform](https://img.shields.io/badge/Platform-iOS-black?logo=apple)](https://altstore.io)
[![Distribution](https://img.shields.io/badge/Install-AltStore-blue)](https://altstore.io)
[![Billing](https://img.shields.io/badge/Billing-Patreon-orange?logo=patreon)](https://patreon.com)

---

## ✨ 主な特徴

### 🌐 Browser
- **片手操作に最適化** — 下部にまとめたジェスチャー対応UIと上下Paddingで、親指だけで全操作が完結
- **強制ダークモード** — 白基調のサイトも自動で暗く。目に優しい夜間ブラウジング
- **タブグループ** — 用途ごとにタブをグループ管理
- **コンテンツ保存** — `.ts` / `.mp4` など、ボタン一発でメディアをダウンロード
- **広告ブロック** — CSSレベルで除去。除外サイトのカスタム設定にも対応
- **ポップアップ・透明オーバーレイのブロック** — 邪魔な要素を自動排除
- **SelectToSearch** — テキスト選択時にSearchボタンが出現。カスタムキーワードを付けてGoogle検索（例: `{text} 本編`）

### 📚 Me（マイページ）
- ブックマーク / 閲覧履歴 / ダウンロード履歴
- ダウンロード履歴ではファイルを時系列確認・エラー理由の詳細表示が可能

### 📁 File / Explorer
- PCライクなリスト表示（FileType・Sizeでフィルタリング）
- **ファイル変換** — 圧縮・解像度変更などをアプリ内で完結
- **多彩なソート** — サイズ / 名前 / 日付 / LikeTime数（ASC/DESC）
- **ピッチ補正エンコード** — ボイチェン解除に対応。動画・音声をピッチチェッカーで確認して一律変更

### 🖼️ File / Grid
- 画像・動画・音声をグリッド表示で高速ブラウズ

### ▶️ File / ContentViewer
- 左右スワイプでファイルを順送り
- **LikeTime（タイムスタンプ）** — お気に入りのシーンにいつでもジャンプ
- **25%移動ボタン** — 画面端に指を伸ばさず再生位置を移動（スマホ落下防止）

### 📺 File / YoruTube（近日公開）
- YouTubeライクなUIでローカルファイルを巡回
- 投稿者フォルダ単位でコンテンツを整理

### ⚙️ Settings
- 説明付きで迷わない設定画面
- `SearchEngine` / `ThemeColor` / `Icon` / `ForceDarkMode` / `Gesture` / `AdsCleaner` / `ExceptionSite` / `PopupHunter` / `ForceZoom` / `BlockSite` / `SelectToSearch` / `PaddingForOneHand` / `ContentViewer` / `ProximityGesture` / `Legal` / `Version`

### 💳 Billing
- プラン比較・ダウンロード機能一覧・利用履歴をスタイリッシュなカードUIで表示

---

## 📥 ダウンロード機能

動画・音声・複数画像を対応サイトから直接保存できます。

```
1. DLボタンをタップ
2. ファイルを選択
3. ファイル名・種類を確認して Execute / Cancel
4. ダウンロード実行（失敗時はDL回数を消費しない）
```

### 対応サイト
| 区分 | サイト例 |
|------|----------|
| ✅ 対応（HLS/MP4） | Xvideos / Pornhub / TokyoMotion / Nicovideo など |
| 🔗 転送（外部DL） | X（旧Twitter）/ YouTube |
| ❌ 非対応（DRM） | Netflix / Amazon Prime Video など |

> **エラーコード早見表**
> - `400` — DLシステムの不具合
> - `404` — リンク切れ
> - `500` — サイト側によるブロック

※ 対応サイトは予告なく変更される場合があります。

---

## 💰 プランと料金

Patreonにて月額サブスクリプション形式で提供しています。

| Plan | Price | コンテンツDL | ファイル変換 | テーマ | Discord |
|------|-------|:-----------:|:----------:|:------:|:-------:|
| **Free** | $0 / mo | 10 DL/日 | — | — | — |
| **Standard** | $1 / mo | 無制限 | — | — | — |
| **Pro** | $5 / mo | 無制限 | ✅ | — | — |
| **Premium** | $20 / mo | 無制限 | ✅ | Color / Icon | DM |
| **Supporter** | $100 / mo | 無制限 | ✅ | Color / Icon | DM |

<strong>おすすめ:Standardプラン</strong> — 片手操作などのこのブラウザの特徴はもちろん無料ながら、動画ダウンロードを無制限で楽しみたい方に最適なプランです。Unknown SD/HDとHLSとGIFから選ばないといけないダウンロード機能において、間違えても制限がないので明日に後回しして、気づいたら動画が消えている事態を避けられます。
---

## 📲 インストール方法
YorunoBrowserはApp Storeには公開されていません。**AltStore** 経由でインストールしてください。

### EU / 日本ユーザー向け (Recommended)
1. iPhoneに **AltStore PAL** をインストール
2. GitHubのリンクを登録
3. AltStoreからインストール

### Global
1. PCに **AltServer** をインストール
2. iPhoneに **AltStore** をインストール
3. GitHubのReleasesから `.ipa` ファイルをダウンロード
4. AltStoreからIPAをインストール
---

## よくありそうな質問
1. **App Storeにないのはなぜ？** — Appleのガイドラインに抵触する機能が多いため、App Storeでの公開は不可能です。
2. **中国製だからデータ盗んでるんだろスパイ野郎** — 開発者は日本在住の個人です。ソースは非公開ですが、収集していません。仮に収集しても保存するストレージが高すぎるので現実的ではありません。
3. **無料で使えるの？** — はい、無料プランもあります。ただし、ダウンロード回数に制限があるため、頻繁に利用する場合は有料プランをおすすめします。
4. **違法じゃないの？** — 本ソフトウェアはあくまでブラウザであり、違法行為を助長するものではありません。ユーザーの責任で合法的な範囲でご利用ください。
5. **Android版は?** - 現在iOS専用ですが、将来的にAndroid版も検討しています。 -Androidユーザーは課金単価が低いし、ModApkでCrackされるからやめとけってまじ？-
6. **Windows/Mac版は?** - 将来的に対応できるといいですが、PCで自慰する人は少なそうです。
7. **逆コンパイルして無課金で有料機能使っていいですか?** - F**K YOU. Are you killing me?

## 📄 ライセンス

本ソフトウェアはプロプライエタリです。無断複製・再配布を禁じます。

