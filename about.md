# CUIでできる小説的なダンジョン的な (コンソールダンジョン)
### 管理方法
json, xml, なんかいい感じのやつとか

### コマンドというかモジュールというか
say - 文字を出力
input - 文字を入力 (フラグに格納)
if - 分岐　はいいいえ (ユーザー選択)
choice - アイテムの選択とかなんとか
flag - フラグ　bool, string, int など
item - 所持中のアイテムリスト　基本string
roop - ループ　基本無限　フラグの設定で抜け出すことも可能
start - 始まり　これを入れたところから動く
end - 終わり　複数設定あり　終了設定ができる(true end, happy endなどなど)
### 言語はもちろん？
**Go!**

### 構造〜
1. file to object
2. error checker
3. header serch
4. runner

- file to object
ファイルからobjectへ

- error checker
エラーチェック
スタートがないとか、エンドがないとか使われてないflagがあるとかなんとか

- header serch
startとかendを探してheader設定

- runner
headerから順に実行
