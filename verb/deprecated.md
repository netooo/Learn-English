# 非推奨な動詞
意味が広いため、なるべく別の単語を使った方が良い動詞一覧。  
変数や関数のスコープが狭い場合は問題ないが、広いと意味を捉え辛くなる。  

## check
妥当性を担保する意味で用いる場合が多いが避けるべき。  
「check」は多義語で、照合の他に小切手や抑止などの意味を持つ。  
代わりに「is~, has~, ~validator」などを使用する。  

## get
"取得する"という意味でprefixに付けて使用する場面をよく見るが、「get」は意味が曖昧なので避けるべき。  
まずどこから取得しているのかがわからない。  
更にはアクセサやプロパティによく使用されているため混乱を招く要因となる。  
代わりに「load~, store~, fetch~, download~」などを使用する。  

## set
"設定する"という意味でprefixに付けて使用する場面をよく見るが、「get」と同様使用すべきではない。  
代わりに「register~, configure~」などを使用する。

## compare
"比較する"という意味だが比較した結果どうなるかが不明瞭。  
どう比較するのかが明確な単語を使用する。  
代わりに「contains~, equals~, isSmall」などを使用する。

## change
"変更する"だが何をどう変更したのかわからない。  
変更後どうなるのかわかる命名にする。  
changeの意味が広いので「change~」とするよりは、「replace~, convert~」といった単語を使用すると良い。  
