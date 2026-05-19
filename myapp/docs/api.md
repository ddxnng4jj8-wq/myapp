# API仕様

## POST /api/tips
説明：ゲームの攻略情報を追加する

リクエスト：
{ "gameTitle": "Minecraft", "stage": "ネザー", "tip": "耐火ポーションを持っていく" }

レスポンス：
{ "message": "攻略情報を追加しました", "gameTitle": "Minecraft", "stage": "ネザー", "tip": "耐火ポーションを持っていく" }

## GET /api/tips
説明：ゲームの攻略情報の一覧を返す

レスポンス：
[{ "gameTitle": "Minecraft", "stage": "ネザー", "tip": "耐火ポーションを持っていく" }]