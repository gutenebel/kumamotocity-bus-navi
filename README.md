# 熊本バスナビ (主要バス4社統合・非公式版)

熊本県内の主要バス4社（産交バス、熊本都市バス、熊本電鉄バス、熊本バス）の運行データを統合して表示する、個人開発のバス時刻表・ルート確認アプリです。

## 特徴
- **4社統合検索**: 会社をまたいだ系統検索が可能です。
- **軽量動作**: GTFSデータを最適化し、ブラウザのみで高速に動作します。
- **直感的なUI**: 
  - 走行済み区間（グレー）と未走行区間（赤）を視覚的に分離
  - 始点・通過駅・終点をアイコンで描き分け
  - 降車専用（終点）バス停の自動非表示機能

## ⚠️ 免責事項
本アプリは個人が開発した**非公式サービス**です。
- 本アプリに掲載される情報は、更新のタイミング等により実際の運行状況と異なる場合があります。
- 本アプリの利用により生じた損害やトラブルについて、開発者は一切の責任を負いません。
- 正確な運行状況や運賃については、各バス事業者の公式サイトをご確認ください。
- **バス事業者への本アプリに関する問い合わせは絶対に行わないでください。**

## 📚 データ出典・ライセンス
本アプリは、以下のオープンデータを使用しています。

- **運行データ**
　-バスきたくまさん（https://km.bus-vision.jp/kumamoto/view/opendataKuma.html）
   で公開されている、以下の主要バス4社のデータ
  　- 産交バス：https://www.kyusanko.co.jp/sankobus
    - 熊本電鉄バス：https://www.kumamotodentetsu.co.jp/bus
    - 熊本バス：https://www.kuma-bus.co.jp
    - 熊本都市バス：https://www.kumamoto-toshibus.co.jp
- **ライセンス**: [クリエイティブ・コモンズ 表示 4.0 国際 (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/deed.ja)
- **地図データ**: [OpenStreetMap](https://www.openstreetmap.org/copyright) contributors
- **ライブラリ**: [Leaflet](https://leafletjs.com/), [PapaParse](https://www.papaparse.com/)

## 🛠 構成
- `index.html`: アプリ本体
- `data/`: 統合済みGTFSデータ（stops.txt, routes.txt, trips.txt, stop_times.txt, calendar.txt）

---
© 2026 gute.nebel
