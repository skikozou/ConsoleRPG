# CUIでできる小説的なダンジョン的な (コンソールダンジョン)
### 管理方法
json, xml, なんかいい感じのやつとか

### コマンドというかモジュールというか
say - 文字を出力<br>
input - 文字を入力 (フラグに格納)<br>
if - 分岐　はいいいえ (ユーザー選択)<br>
choice - アイテムの選択とかなんとか<br>
flag - フラグ　bool, string, int など<br>
item - 所持中のアイテムリスト　基本string<br>
roop - ループ　基本無限　フラグの設定で抜け出すことも可能<br>
start - 始まり　これを入れたところから動く<br>
end - 終わり　複数設定あり　終了設定ができる(true end, happy endなどなど)<br>
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
エラーチェック<br>
スタートがないとか、エンドがないとか使われてないflagがあるとかなんとか

- header serch
startとかendを探してheader設定

- runner
headerから順に実行
