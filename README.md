# Simple and Clear Launcher

![Kotlin](https://img.shields.io/badge/kotlin-100%25-blue?logo=kotlin)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-Enabled-4285F4?logo=android)

**Simple and Clear Launcher** is a modern, lightweight, and aesthetic Android launcher built entirely with **Jetpack Compose**. 

It features a unique UI design that **fuses LiquidGlass aesthetics with Material3**, focusing on productivity, privacy, and visual elegance. Designed to be beautiful out-of-the-box while offering deep customization capabilities.

## ✨ Key Features

* **🎨 LiquidGlass x Material3:** A unique design system combining the depth of glassmorphism with the usability of Material Design 3.
* **🔒 Private Space Support:** Seamless integration with Android's Work Profile / Private Space. Lock and unlock hidden apps directly from the home screen.
* **📅 Smart Dashboard:**
    * **Clock:** Minimalist clock with date display.
    * **Weather:** Real-time weather updates using Open-Meteo (No API Key required!).
    * **Calendar:** Shows your next upcoming event directly on the home widget.
* **🔍 Unified Search & Commands:**
    * **App & Web Search:** Search installed apps or browse the web (customizable browser).
    * **Magic Commands:** Type these keywords to switch view modes instantly:
        * **Show All Apps:** `all`, `すべて`
        * **View Schedule:** `schedule`, `よてい`, `予定`
        * **Access Private Space:** `private`, `ぷらいべーと`, `プライベート`
* **🏷️ App Aliases:** Rename apps for easier searching (e.g., set "X" to be searchable as "Twitter").
* **⭐ Favorites:** Pin your most-used apps to the top of the grid.
* **🎨 Deep Theming:** Customize every color aspect of the launcher (gradients, text, icons, glass effects) with a built-in color picker.

## 🛠️ Built With

* **Language:** Kotlin
* **UI Framework:** Jetpack Compose (Material3)
* **Architecture:** MVVM / Repository Pattern
* **Asynchronous:** Kotlin Coroutines & Flow
* **APIs:**
    * **Weather:** [Open-Meteo](https://open-meteo.com/) (Free, No API Key needed)
    * **Calendar:** Android Calendar Provider
    * **Location:** Fused Location Provider

## 📥 Installation

1.  Go to the **[Releases](../../releases)** page of this repository.
2.  Download the latest `.apk` file.
3.  Install the APK on your Android device.
    * *Note: You may need to allow installation from unknown sources if this is your first time installing an APK manually.*
4.  **Permissions:**
    * The app will request permissions for **Location** (for local weather) and **Calendar** (for event display) upon first use of those features.

## ⚙️ Customization

Long-press the central clock widget to open the **Settings** menu.
* **General:** Choose your preferred browser for web searches.
* **Weather / Calendar:** Manage permissions and visibility.
* **Aliases:** Set custom names for your apps.
* **Theme:** Edit the color palette for the clock, cards, and text.

# 🔒 Privacy Policy
This app respects your privacy.

No Data Collection: We do not collect, store, or transmit any personal data, app usage, or search history to external servers.

Offline Processing: All logic, including "Private Space" filtering, is processed locally on your device.

Weather Data: Location data is sent anonymously to Open-Meteo solely for retrieving weather forecasts and is not used for any other purpose.

---

# Simple and Clear Launcher (日本語)

**Simple and Clear Launcher** は、**Jetpack Compose** で構築された、モダンで軽量、そして美しいAndroidランチャーです。

**LiquidGlass（液状ガラス）の美学とMaterial3の実用性を融合**させた独自のUIデザインを採用し、生産性とプライバシー保護に重点を置いています。インストール直後から美しく、かつ詳細なカスタマイズも可能な設計になっています。

## ✨ 主な機能

* **🎨 LiquidGlass x Material3:** グラスモーフィズムの奥行きと、Material3の使いやすさを融合させた独自のデザインシステム。
* **🔒 プライベートスペース対応:** Androidの仕事用プロファイル（Private Space）とシームレスに統合。ホーム画面から直接、非表示アプリのロック・解除が可能です。
* **📅 スマートダッシュボード:**
    * **時計:** 日付付きのミニマルな時計表示。
    * **天気:** Open-Meteoを使用したリアルタイム天気情報（APIキー登録不要！）。
    * **カレンダー:** 次の予定をホーム画面に表示。
* **🔍 統合検索とコマンド:**
    * アプリ検索とWeb検索（使用ブラウザ設定可能）を統合。
    * **マジックコマンド:** 以下のキーワードを入力すると、Web検索の代わりに特殊モードが起動します。
        * **全アプリを表示:** `all`, `すべて`
        * **予定リストを表示:** `schedule`, `よてい`, `予定`
        * **プライベートスペース操作:** `private`, `ぷらいべーと`, `プライベート`
* **🏷️ アプリエイリアス:** アプリに別名を設定して検索しやすくします（例：「X」を「Twitter」で検索できるようにするなど）。
* **⭐ お気に入り:** よく使うアプリをグリッドの最上部に固定。
* **🎨 高度なテーマ設定:** 時計、カード、テキスト、ガラス効果など、すべての色を内蔵カラーピッカーで細かくカスタマイズ可能。

## 🛠️ 使用技術

* **言語:** Kotlin
* **UIフレームワーク:** Jetpack Compose (Material3)
* **アーキテクチャ:** MVVM / Repository Pattern
* **非同期処理:** Kotlin Coroutines & Flow
* **API / 連携:**
    * **天気:** [Open-Meteo](https://open-meteo.com/) (無料、APIキー不要)
    * **カレンダー:** Android Calendar Provider
    * **位置情報:** Fused Location Provider

## 📥 インストール方法

1.  このリポジトリの **[Releases](../../releases)** ページにアクセスしてください。
2.  最新の `.apk` ファイルをダウンロードします。
3.  Android端末にAPKをインストールしてください。
    * *注意: 手動でのAPKインストールが初めての場合、不明な提供元からのインストールを許可する必要があります。*
4.  **権限について:**
    * 初回利用時に、現在地の天気取得のための**位置情報**権限、および予定表示のための**カレンダー**権限がリクエストされます。

## ⚙️ 設定・カスタマイズ

中央の時計ウィジェットを**長押し**すると設定メニューが開きます。
* **General:** Web検索に使用するブラウザを選択できます。
* **Weather / Calendar:** 権限の管理や表示設定を行います。
* **Aliases:** アプリの検索用別名を設定・管理します。
* **Theme:** 時計やカードのグラデーションなど、配色の詳細設定が可能です。



# 🔒 プライバシーポリシー
本アプリはユーザーのプライバシーを尊重します。

データ収集なし: 個人情報、アプリの使用状況、検索履歴などを外部サーバーに送信・保存することはありません。

オフライン処理: 「プライベートスペース」のフィルタリングを含むすべてのロジックは、端末内でのみ処理されます。

天気データ: 天気予報の取得のためにのみ、位置情報がOpen-Meteoに匿名で送信されますが、それ以外の目的で使用されることはありません。
