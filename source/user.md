---
name: User
desc: ユーザを表すモデル
props:
  - name: id
    desc: ユーザの id
    type: string
  - name: name
    desc: ユーザ名
    type: string
  - name: items
    desc: ユーザが持っている Item
    type: Item[]
---

ユーザを表すモデルです。 1人の User は0個以上400個以内の Item を持ちます。(サンプルです)
