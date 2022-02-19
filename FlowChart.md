```mermaid
flowchart TD
  A[開始] --> B[商品を選ぶ];
  B --> C[在庫確認];
  C -- あり --> D[商品を購入する];
  C -- なし --> B;
  D --> E[終了];
```
