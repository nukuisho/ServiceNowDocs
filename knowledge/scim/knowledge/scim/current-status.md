# SCIM検証 現状整理

## 確認済み

- Table APIではユーザ作成に成功
- OAuth token取得は成功
- SCIM GET /api/now/scim/Users は 200 OK
- totalResults=682 を確認

## 未解決

- SCIM POSTでユーザレコードが作成されない
- 500エラーが発生
- エラー内容:
  Internal error while applying transformation for 'User' SCIM Resource Type.

## 現時点の仮説

- RTEフィールドマッピング
- User Resource Type設定
- email属性の形式
- SCIM変換処理側の内部エラー
