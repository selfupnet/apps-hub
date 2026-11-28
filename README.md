# 📦 Apps Hub (selfup.net)

**登録不要・インストール不要・サーバー通信ゼロ。**  
学習・教育、日常・メンタル・健康、実用ツール、ブラウザゲームまで、**全45種類**の軽量Webツールを収録した個人開発モノレポジトリ（ソースコードアーカイブ）です。

すべてのアプリは単一HTML（Single-File）構成・完全クライアントサイド（`localStorage` / Web Audio API / Canvas API 等）で動作し、入力データが外部サーバーへ送信・保存されることは一切ありません。

> **🌐 Live Portal（今すぐ使える本番サイト）:**  
> 全45アプリの一覧・検索・お気に入りピン留めができる本番ポータルはこちら 👉 **[https://selfup.net/](https://selfup.net/)**

---

## 🗂 リポジトリ構成 (Directory Structure)

各アプリはフォルダ単位で独立しており、本番環境（`https://selfup.net/<フォルダ名>/`）と同一のディレクトリ構造で格納されています。

```text
apps-hub/
├── LICENSE          # MIT License（全アプリ共通）
├── README.md        # 本ドキュメント
├── korean/          # Korean Hub
├── algo/            # アルゴリズム可視化
├── ...              # ...
└── solitaire/       # ソリティア
```

---

## 📱 収録アプリ一覧 (47 Apps)

### 1. 学習・教育・スキル (17 Apps)

| フォルダ | アプリ名 | 概要 | 本番URL |
| :--- | :--- | :--- | :--- |
| `/korean/` | **Korean Hub** | 韓国語語彙・フレーズ・文法 | https://selfup.net/korean/ |
| `/algo/` | **アルゴリズム可視化** | ソート＆経路探索実験 | https://selfup.net/algo/ |
| `/pianoscore/` | **Score Studio** | 五線譜＆MIDI作成 | https://selfup.net/pianoscore/ |
| `/engstruct/` | **英文構造ラボ** | 語順ブロック＆前置詞図解 | https://selfup.net/engstruct/ |
| `/calculus/` | **微積分ラボ** | 接線の傾き＆面積体感 | https://selfup.net/calculus/ |
| `/hangul/` | **Hangul Hub** | 文字・発音練習 | https://selfup.net/hangul/ |
| `/kanji/` | **Kanji Studio** | 書き順・部首検索 | https://selfup.net/kanji/ |
| `/nihongo/` | **Nihongo Hub** | 外国人向け日本語 | https://selfup.net/nihongo/ |
| `/radix/` | **基数変換** | 2進・10進・16進 | https://selfup.net/radix/ |
| `/typing/` | **タイピング** | スコア測定練習 | https://selfup.net/typing/ |
| `/vocab/` | **単語帳** | 2000語・4択テスト | https://selfup.net/vocab/ |
| `/mathgrapher/` | **MathGrapher** | 関数グラフ描画 | https://selfup.net/mathgrapher/ |
| `/ipcalc/` | **IPv4計算** | サブネット・IP計算 | https://selfup.net/ipcalc/ |
| `/metronome/` | **メトロノーム** | テンポ・拍子キープ | https://selfup.net/metronome/ |
| `/drum/` | **ドラムスタジオ** | ブラウザ演奏ドラム | https://selfup.net/drum/ |
| `/planetarium/` | **星空プラネタリウム** | 全天ドーム＆地平線ビュー・7惑星・メシエ天体・赤色暗視モード | https://selfup.net/planetarium/ |
| `/skyview/` | **目の前の星空ビューア** | 山並みパノラマ視界・電子コンパス連動・方角別見頃星座ガイド | https://selfup.net/skyview/ |

### 2. 日常・メンタル・健康 (11 Apps)

| フォルダ | アプリ名 | 概要 | 本番URL |
| :--- | :--- | :--- | :--- |
| `/michinoeki/` | **道の駅マップ** | 全国制覇＆スタンプ帳 | https://selfup.net/michinoeki/ |
| `/workout/` | **週間運動ルーティン** | 曜日別メニュー＆実施記録 | https://selfup.net/workout/ |
| `/anger/` | **Anger Calm** | 怒り温度計＆思考整理 | https://selfup.net/anger/ |
| `/streakup/` | **StreakUp** | 習慣・継続スタンプ帳 | https://selfup.net/streakup/ |
| `/visiongoal/` | **VisionGoal** | 9画面目標達成表 | https://selfup.net/visiongoal/ |
| `/diary/` | **3行日記** | 手軽な振り返り | https://selfup.net/diary/ |
| `/shredder/` | **感情シュレッダー** | モヤモヤ文字消去 | https://selfup.net/shredder/ |
| `/weightlog/` | **体重ログ** | BMI推移グラフ | https://selfup.net/weightlog/ |
| `/weather/` | **天気予報** | 全国7日間の予報 | https://selfup.net/weather/ |
| `/calendar/` | **カレンダー** | 祝日・予定チェック | https://selfup.net/calendar/ |
| `/mosquito/` | **モスキート音** | 耳年齢・可聴域診断 | https://selfup.net/mosquito/ |

### 3. 実用ツール・作業効率化 (9 Apps)

| フォルダ | アプリ名 | 概要 | 本番URL |
| :--- | :--- | :--- | :--- |
| `/matrix/` | **4象限マトリクス** | 優先順位・付箋仕分け | https://selfup.net/matrix/ |
| `/json/` | **JSON Studio** | 整形・構文検証 | https://selfup.net/json/ |
| `/md/` | **MD Studio** | Markdown＆作図 | https://selfup.net/md/ |
| `/mindmap/` | **マインドマップ** | 思考整理ツリー | https://selfup.net/mindmap/ |
| `/passkey/` | **PassKey Vault** | 安全なパスワード生成 | https://selfup.net/passkey/ |
| `/diff/` | **差分・文字数** | テキスト比較・計測 | https://selfup.net/diff/ |
| `/calc/` | **電卓** | シンプルな計算機 | https://selfup.net/calc/ |
| `/timer/` | **タイマー** | ポモドーロ＆計測 | https://selfup.net/timer/ |
| `/speed/` | **速度テスト** | 回線スピード測定 | https://selfup.net/speed/ |

### 4. ゲーム・パズル (10 Apps)

| フォルダ | アプリ名 | 概要 | 本番URL |
| :--- | :--- | :--- | :--- |
| `/astra/` | **宇宙防衛隊** | レトロ宇宙迎撃戦 | https://selfup.net/astra/ |
| `/memory/` | **神経衰弱** | トランプ絵合わせ | https://selfup.net/memory/ |
| `/minesweeper/` | **マインスイーパー** | 地雷探索パズル | https://selfup.net/minesweeper/ |
| `/innerclock/` | **体内時計** | 秒数ピタリ当て | https://selfup.net/innerclock/ |
| `/chess/` | **チェス** | 対人・AI対局 | https://selfup.net/chess/ |
| `/shogi/` | **将棋** | AI対戦・駒落ち | https://selfup.net/shogi/ |
| `/reversi/` | **リバーシ** | オセロ・AI対戦 | https://selfup.net/reversi/ |
| `/gomoku/` | **五目並べ** | 先手後手・連珠戦 | https://selfup.net/gomoku/ |
| `/nanpre/` | **ナンプレ** | 数独パズル自動生成 | https://selfup.net/nanpre/ |
| `/solitaire/` | **ソリティア** | 定番クロンダイク | https://selfup.net/solitaire/ |

---

## 🛠 開発について (About)

本リポジトリのすべてのアプリケーションは、**生成AI（Gemini）を活用したバイブコーディング（対話型プログラミング）**によって制作されたシングルファイルWebアプリケーションです。

- **企画・仕様設計・ディレクション:** selfupnet
- **コード実装・AIアシスタント:** Gemini
- **主な構成技術:** HTML5 / Tailwind CSS / Vanilla JavaScript / Canvas API / Web Audio API / Web Speech API / `localStorage`
- **主な動作確認環境:** Windows / Android版 Chrome（※Safari等の他環境では一部表示や挙動が異なる場合があります）

---

## 📄 ライセンス・外部データ出典 (License & Attribution)

### ソースコードライセンス
本リポジトリ内のすべてのソースコードは [MIT License](LICENSE) のもとで公開されています。

### 外部オープンデータ・API利用表記（該当アプリのみ）
一部のアプリでは、以下のオープンデータ・公開APIを利用しています（各アプリ画面内にも出典・ライセンスを明記しています）：
- **気象庁 予報データ**（`/weather/`）
- **KanjiVG** — [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/)（`/kanji/`）
- **JMdict / EDICT** — [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/)（`/nihongo/`）
- **NGSL (New General Service List)** — [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)（`/vocab/`）
- **国土数値情報（道の駅データ）** — 国土交通省（`/michinoeki/`）
- **Hangul Hub 発音音声**: Google Cloud Text-to-Speech API（`ko-KR-Wavenet-A`）事前生成音源（ローカル同梱）

---

## ⚠️ 免責事項 (Disclaimer)

- 本ツール群は個人が生成AIを活用して実験・学習目的で制作したプロトタイプです。
- 動作の正確性、完全性、安全性等についてはいかなる保証もいたしかねます。当ツールの利用により生じた直接・間接のいかなる損害・不都合についても、開発者は一切の責任を負いません（すべて自己責任にてご利用ください）。
- 個人の趣味運用の都合上、不具合修正や機能改善、個別のご要望への対応・サポートは原則として承っておりません。

---

## ⚠️ コントリビューション（Pull Request）について

本リポジトリは個人の実験・ポートフォリオとして公開しており、機能追加や修正の Pull Request・Issue 対応は原則として受け付けておりません。  
コードの改変や機能追加をご希望の場合は、ご自身の環境へ Fork（複製）して自由にお楽しみください。
