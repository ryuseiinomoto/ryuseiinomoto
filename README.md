# 👋 ryusei_inomoto

青山学院大学でマクロ経済学を専攻する3年生（2028卒）です。
**「課題を見つけ、技術で解決するプロダクトを、企画からデプロイまで一人で作り切る」** ことを大切にしています。
特に **生成AIをプロダクトに組み込む** 領域に強い関心があります。

## 🚀 Projects

### 📈 Mundel — マクロ経済で学ぶFX教育アプリ
> Learn FX through macroeconomics — not intuition.

大学で学んだ **IS-LM-BP（マンデル＝フレミング）モデル** をプロダクトに落とし込み、「根拠を持って為替を読む」力を鍛える学習アプリ。企画・設計・実装・デプロイまで個人開発しています。

- 📰 経済ニュースを **Gemini** が解析し、IS / LM / BP 各曲線のシフト量を構造化データで生成
- 📊 **Recharts** でモデルのグラフをリアルタイム描画し、経済変化を可視化
- 🤖 BUY / SELL / HOLD のシグナルとその根拠を日本語で解説
- 💹 分析した根拠で模擬トレード、📚 11ステップの学習コース（日 / 英 / 中 対応）

`Next.js` `React` `TypeScript` `Tailwind CSS` `FastAPI` `Python` `Gemini (Vertex AI)` `Langfuse` `Docker` `Cloud Run`

🔗 **Live Demo**: https://mundel-frontend-490996932437.europe-west1.run.app
📂 [mundel-frontend](https://github.com/ryuseiinomoto/mundel-frontend) ・ [mundel-backend](https://github.com/ryuseiinomoto/mundel-backend)

### 🌐 Market Insight AI — 市場ニュース分析 RAG アプリ
経済学の分析視点をAIで再現し、日・英・独のニュースを「市場インパクト・競合・センチメント」の観点で自動分析。記事を文脈に保持した **RAG** チャットで深掘りもできます。

`FastAPI` `Python` `OpenAI API` `RAG` `Tailwind CSS`

📂 [market-insight-ai](https://github.com/ryuseiinomoto/market-insight-ai)

## 🛠 Tech Stack
- **Languages**: TypeScript / Python / JavaScript
- **Frontend**: Next.js (App Router) / React / Tailwind CSS / Recharts / Framer Motion
- **Backend**: FastAPI / async（複数APIの並列取得）
- **AI**: Google Gemini (Vertex AI) / OpenAI API / Langfuse / RAG
- **Infra**: Docker / Google Cloud Run（AWS も学習中）

## 💡 開発で大切にしていること
- AIの不安定な出力を **構造化スキーマ＋型検証** で制御し、壊れたデータを後工程に流さない設計
- 外部APIがダウンしても全体が落ちない **フォールトトレラントな構成**
- Langfuse による **トレース管理** とキャッシュで、AIの品質とコストを両立

## 🌱 Currently Learning
生成AIを活用したプロダクト開発 / 大規模サービスを支えるバックエンド設計 / AWS

## 📫 Links
🌐 Mundel (Live Demo): https://mundel-frontend-490996932437.europe-west1.run.app
