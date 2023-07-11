# ゲーム のタイトル
## 実行環境の必要条件
* python >= 3.10
* pygame >= 2.1

## ゲームの概要
主人公キャラクターお前君（お前 ）をキーボード操作により上から落ちてくる具材を集めるゲームで，

## ゲームの実装
###共通基本機能
* 主人公キャラクターに関するクラス
* パティを上からランダムに生成するクラス
###追加機能
1. 具材の種類の追加
- パティ以外にチーズ,レタス,ゴミ
2. タイトルの追加
- ゲームスタートボタン
- ゲーム画面へ遷移
3. SCOREと制限時間の追加
-  拾った具材によって点数を変化させる
-  ゴミを拾ったらスコアをマイナスする
4. お前君との接触時の処理の追加
-　お前君の皿に具材が積みあがっていく
5. 終了画面の追加
-　スコアの表示（S,A,B,C,X評価）
-　スコアに応じたシェフからのコメント
-　タイトル画面へ戻る
### 担当追加機能
* ほげほげ
* ふがふが
* ぴよぴよ
### ToDo
- [ ] ほげほげ機能
- [ ] ふがふが関数内の変数名の統一
### メモ
* クラス内の変数は，すべて，「get_変数名」という名前のメソッドを介してアクセスするように設計してある
* すべてのクラスに関係する関数は，クラスの外で定義してある
