```mermaid
flowchart TD
    A[開始] --> B{条件分岐}
    B -->|はい| C[処理A]
    B -->|いいえ| D[処理B]
    C --> E[終了]
    D --> E

