# 非推奨な名詞
意味が広いため、なるべく別の単語を使った方が良い名詞一覧。  
変数や関数のスコープが狭い場合は問題ないが、広いと意味を捉え辛くなる。  

## data
何のデータなのかわからない。  
「hoge_data」などと命名するのであれば「hoge」として問題ない場合が多い。  
「new_data」なども避けよう。  
また単数形, 複数形を意識して命名することで処理が明確になる。  
ちなみに「data」は既に複数形なので「datas」としないように。

## result
```
result = Hoge()
return result
```
というコードをよく見るが、何を返しているのかわからない。  
ここも誰がみてもわかる変数名にする。  
なお多少変数名が長くなっても問題なく、それよりは意味の通じる方を優先する。  

## mode
こちらも1単語だけだと何のモードなのかわからない。  
「hoge_mode」のように状態の種類を表現するか、1語で表せられる単語に置き換える。  
