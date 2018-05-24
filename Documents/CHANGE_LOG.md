# 変更履歴
*****

### ver 0.1.0　~ 0.1.2
1) READMEを追加  
2) DEMOページの追加  
*****

### ver 0.1.3  
1) 削除アイコン押下時の後続処理(オプション)の引数を下記の通り変更  
・第1引数：displayData＜array＞・・・画面表示データのリスト  
  ・第2引数：selectedRows＜array＞・・・画面表示データのインデックス値のリスト(選択行のみ)
*****

### ver 0.1.4  
1) 削除ロジックを下記の通り変更  
＜変更前＞  
・削除アイコン実行時オプション設定あり・・・削除ロジック実行後、オプションで設定されたロジックを実行  
  ・削除アイコン実行時オプション設定なし・・・削除ロジックのみ実行  
＜変更後＞  
・削除アイコン実行時オプション設定あり・・・オプションで設定されて関数のみを実行  
  ・削除アイコン実行時オプション設定なし・・・削除ロジックのみ実行  
  
2) 行選択時の後続処理(オプション)の引数を下記の通り変更  
・第1引数：displayData＜array＞・・・画面表示データのリスト  
 ・第2引数：curSelectedRows＜array＞・・・行選択前、画面表示データのインデックス値のリスト(選択行のみ)  
  ・第3引数：selectedRows＜array＞・・・画面表示データのインデックス値のリスト(選択行のみ)  