# ナレッジベース — サロマ湖ホタテ稚貝養殖

サロマ湖養殖漁業協同組合（常呂・湧別・佐呂間の各漁協が母体）や道総研の一次情報を、
自分の作業判断に使える形で貯めていく場所です。

## 索引

| ファイル | 内容 |
|---|---|
| [高水温・作業判断の原則](高水温と作業判断.md) | **最重要。** 何度で作業を止めるか、いつ再開するか、作業のやり方 |
| [水温・水質データの見方](水温水質データの見方.md) | 組合ブイ5基、層別水温、低酸素層、一次ソースのURL |
| [吊り下げ深度（浮力管理）](吊り下げ深度の決め方.md) | 高水温層と低酸素層に挟まれた「安全帯」への吊り下げ方 |
| [浮力と通しの計算](浮力と通しの計算.md) | 尺玉7／尺二玉12 を使った成長の把握、通し目の決め方、2026年の実測 |
| [作業工程の型](作業工程の型.md) | 仮取り→仮分散→本分散の標準工程、「一発取り」など他地区の事例 |
| [transcripts/](transcripts/) | 組合公開動画の字幕（自動生成・未校正の原文） |

## 一次ソース

### サロマ湖養殖漁業協同組合
- トップ https://saromako.org/ ／ スマホ版 https://saromako.org/sp/
- **養殖センターだより**（週1〜2回発行・PDF） https://saromako.org/center/index.html
  - 2026年分の直リンクは `https://saromako.org/center/pdf/2026/center26NN.pdf`（NN=号数2桁）
  - 夏場は「サロマ湖水質状況（ブイ5基の層別プロファイル）」「水温状況」「付着生物ラーバ出現状況」が載る
- **水質観測ブイ（リアルタイム）** https://saromako.org/data/index.php?bouy=1 〜 `bouy=5`
  - 生データJSON: `https://saromako.org/saroma_json/sp/bouy{1..5}.json`（1時間値・表層）
  - ブイ1=赤川沖／ブイ2=幌岩沖／ブイ3=富武士沖／ブイ4=三里沖／ブイ5=中央
- 公開動画（本ナレッジの元）
  - [2026年サロマ湖高水温対策打合せ](https://www.youtube.com/watch?v=1SQbxGGC88I)（2026-07-17・51分）
  - [2023年サロマ湖高温対策緊急打合せ](https://youtu.be/3sGh-XvaWX4)（2023-07-29・24分）

### 外部
- 外海（オホーツク）水温「マリンアイ」 http://www.nanotech.co.jp/cgi/main.asp?UID=saroma
- 気象庁 海面水温・海流（1か月先までの予想図あり） https://www.data.jma.go.jp/kaikyou/kaikyou/tile/jp/index_sstfct.html
- 気象庁アメダス（常呂・佐呂間・湧別・紋別） https://www.jma.go.jp/bosai/amedas/
- 常呂漁協 気象 http://jf-tokoro.or.jp/weather/mobile/index.htm
- 湧別漁協 風況 http://www.hkyubetsu.jf-net.ne.jp/wind/ane-page.html

### 高水温の生理データ（他県試験場）
- [ホタテガイ稚貝に対する高水温の影響（青森県産業技術センター）](https://www.aomori-itc.or.jp/_files/00055130/h22houkoku-394.pdf)
- [高水温下におけるホタテガイ養殖管理の手引（岩手県水産技術センター）](https://www2.suigi.pref.iwate.jp/wp-content/uploads/2025/04/20250619kouonsuihotatey_manual.pdf)
- [猛暑時のホタテガイへい死率を低減する養殖生産技術の開発（道総研）](http://www.fishexp.hro.or.jp/cont/jochokai/conference/hioc3b0000001cyx-att/H27_07_koen1.pdf)

## 注意

- `transcripts/` はYouTubeの自動生成字幕をそのまま置いたもので、**誤変換が多い**
  （高水温→香水／ブイ→V／サロマ→サモ・サラ箱／湧別→有別／常呂→ところ など）。
  要約側の各ファイルは、誤変換を文脈から補正して整理してあります。
  数字など重要な箇所は必ず元動画とセンターだよりで確認してください。
- 本ナレッジは公開情報のみで構成しています。自家の のし実名・実績数値は含めません。
