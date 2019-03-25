# mmd-add-transparency-morph
PmxEditorを使い、すべての材質に透明化モーフを追加します

# 概要

すべての材質ひとつひとつに対して、材質色とエッジの非透過度を0にする「(材質名) 透明化」というモーフを作成します。

![材質](https://user-images.githubusercontent.com/10125386/54927482-990b9b80-4f55-11e9-810f-ffa66f7883e1.jpg)   
材質


![適用後](https://user-images.githubusercontent.com/10125386/54927494-9d37b900-4f55-11e9-845c-ae4ea5ad28ae.jpg)  
適用後

# 使い方

ファイルごとに三つの方法がありますが、結果は同一です。

## その1 txt貼り付け

PmxEditorを起動し、モデルを読み込みます。  
[編集]-[プラグイン]-[CSScript]-[C#スクリプト]を選択し、  
メモ帳などで開いた「透明化モーフ一括追加.txt」の内容を貼り付けて実行してください。

## その2 スクリプト読み込み

PmxEditorを起動し、モデルを読み込みます。  
[編集]-[プラグイン]-[CSScript]-[C#スクリプト]を選択し、  
開いたウィンドウの[ファイル]-[スクリプト読み込み]で「透明化モーフ一括追加.cx」を選択して実行してください。

## その3 DLL設置

エクスプローラーで  
PmxEditor\_plugin\User  
ディレクトリに「透明化モーフ一括追加.dll」を設置し、PmxEditorを起動しモデルを読み込みます。  
[編集]-[プラグイン]-[User]-[透明化モーフ一括追加]を選択します。  

***

適用後は適時不要なモーフを削除してモデルを保存してください。

# 取得方法

Gitあるいはリリースページ( https://github.com/khsk/mmd-add-transparency-morph/releases )から。  
難しいかリリースが古い場合はtxtファイルのコピペの使い方その1で。
