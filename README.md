# 冷蔵庫レシピ

冷蔵庫の写真（複数枚可）から食材を読み取って、作れるレシピを3つ提案するWebアプリです。

- AI: Google Gemini API（無料枠）。使う人がそれぞれ自分のAPIキーを [Google AI Studio](https://aistudio.google.com/apikey) で取得して、最初に1回貼り付けます。
- キーと履歴は、その端末のブラウザ（localStorage）にだけ保存されます。サーバーはありません。
- 無料枠では、送った写真・文章がGoogleのAI改善に使われることがあります。

ファイルは `index.html` 1つだけです。
