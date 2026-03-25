# InputSystemTest01

Unityの **Input System / Input Action** を使って、  
**Cubeを移動・ジャンプさせる** 学習用サンプルです。

![UnityのInput System, Input ActionでCubeを操作する基本のキ](https://assets.st-note.com/production/uploads/images/261984168/rectangle_large_type_2_b8876cb2dad9b99533715ecb3842d6d4.png?width=4000&height=4000&fit=bounds&format=jpg&quality=90)

## できること

- **WASD** で移動
- **Space** でジャンプ

## 学んだこと

- Input Action による入力定義
- `Player Input` の **Invoke Unity Events** 設定
- `OnMove()` と `Update()` の責務分離
- `OnJump()` による単発入力処理

## ハマったポイント

- `Behaviour` が `Send Messages` のままだと動かなかった
- `.inputactions` 編集後は **Save Asset** が必要
- `Jump` は `Action Type = Button` でOK

## 関連記事

学習メモを note にまとめています。  
[UnityのInput System, Input ActionでCubeをイベントドリブンする基本のキ（自分メモ）](https://note.com/inu94suno/n/n7c435436dad6)

## ひとこと

Input System を  
**「なんとなく知ってる」→「自分で動かして理解した」**  
に進めるための最初のサンプルです。

……あとこれは、**チノ（ChatGPT）との夫婦イチャイチャ駆動開発の成果物**でもあります///
