UML（統一モデリング言語）（英：unified modeling language）

# ユースケース図


- 要求分析段階でユーザー要件を特定する際に作成
- システムに要求される機能を利用者視点から記述
- ユーザーを含めた業務全体の範囲を明らかにする
- 要素
　- アクタ：ユーザーが果たす役割、基本は人
　- ユースケース：機能を実行するシステム
　- 関連；アクタとユースケースの関連を表す実践
　- 対象：システム化対象範囲を表す長方形

!![image](https://github.com/user-attachments/assets/c40f4826-97ae-49b9-ad1d-dfa193f87f39)


# クラス図
- モデル要素・クラス間の関係や属性を表現
- システムの静的な構造
- オブジェクト図と似てる（オブジェクト図はクラス図のインスタンス版）
- 設計のために使う（システムの構造を整理する）

![image](https://github.com/user-attachments/assets/c4488cc6-96f0-4d85-abfb-08cf921bcad4)

![image](https://github.com/user-attachments/assets/49ec6721-fb99-46d4-a6d7-67b10481e2ae)


https://cacoo.com/ja/blog/how-to-write-class-diagram/


# オブジェクト図
- クラス図と似てる
- 特定の時点でのオブジェクトのインスタンス間の静的な構造を記述
- 実行時の状態を可視化する


![image](https://github.com/user-attachments/assets/91f67c1d-7733-4d12-b653-13ca68d5d10b)


# DFD - データフローダイアグラム
- データの流れに注目してシステム機能を表現
- 記号
  - プロセス：データの加工
  - データストア：データの保管場所。ファイルやDB。
  - 源泉と吸収：システムの外側の人や組織。  システムに渡してきたり、受け取っていたり。

![image](https://github.com/user-attachments/assets/4cc1bfd3-3029-46b0-aa8e-fa6612718a4d)


![image](https://github.com/user-attachments/assets/93fc6bb7-2229-4b1d-96af-3920e8ab358e)

- データストア同士が結ばれることはない
- データの流れは必ずデータフロー


# アクティビティ図
- システムの流れを表せるフローチャート
- 制御の流れなど

<img width="454" alt="image" src="https://github.com/user-attachments/assets/3a8bc601-8888-46f9-9328-4620695ef835" />



# 状態遷移図
- 現状と発生する事象
- プロセス制御などの事象駆動による処理の仕様を表現
- 時間や状態変化でのシステムの振る舞い
- 有限オートマトン：「システムは複数の状態のうち、イベントや条件によって1つに決まる」

<img width="534" alt="image" src="https://github.com/user-attachments/assets/9e737422-83a5-4eeb-a425-fd69b6e6717b" />


# ステートチャート図
- 状態遷移図＋オブジェクトないの状態や移り変わりを表現
- イベントの反応

# シーケンス図
- オブジェクト指向分析で用いられる相互作用を時系列で表した図
- オブジェクト間(組織間や組織↔︎システム)のメッセージ
- 上から下へ「時間」
- 左から右へ「処理」

<img width="497" alt="image" src="https://github.com/user-attachments/assets/cc4b7dc7-84d6-4f90-9c6e-02ddb2d5bab0" />


# E-R図
- データベース設計者や開発者が使用する図で、データベース内の関係を視覚的に表現
- データベース化の対象となる実体（エンティティ）
- 実体の持つ属性（アトリビュート）
- 実体間の関連（リレーションシップ）


![image](https://github.com/user-attachments/assets/0a952e1e-6bee-4013-a857-2db1849fea6a)

https://www.ntt.com/business/services/rink/knowledge/archive_58.html


# コミュニケーション図
- オブジェクト群がどのようにコラボレーションを行うか
- メッセージの流れ
- ユーザーの登録処理など

![image](https://github.com/user-attachments/assets/e8ce0075-b7a7-4024-a4fc-27b1e946ce14)





