# atma10

---
3/6

01…ベースライン． \
02…とりあえずディスカッションのやつ組み込んだ． \
03…作者の情報絶対効くかと思ったんだけど微妙だな〜 作者の，年度ごとの作品数と，タイトルの，年度ごとの作品数追加． \


---
3/7

04…彩度の情報追加．作者ごとのサイズの情報はダメ． \
05…マテリアルの情報追加． \
06は彩度をCNNにしてみたんだけどうまく行かなかったな〜 \
07は場所の情報を追加． 微妙． 

---
3/8

08．maker.infoの情報を追加．微妙．マテリアルは，普通にonehotのほうがいい．同じ要領で，technique，collectionも追加．ちょっっっとずつあがってる．→提出したら下がった… \
09で07にbertくわえたらちょっとのびた．bertは，descriptionと，feature importanceから，more_titleをやった．(これは10.ipynb) 
10は，あと書いてある人が人気だったらlikes伸びるかなと思って，書いてる人のonehot(30回以上書かれてる人のみ)を追加したが，さがった．

---
3/9

11で，明度の情報も追加してみたけどダメでした．作者の有名度として，どのくらい情報が埋まってるか追加したらちょっと伸びた． \
12は，とりあえず色情報追加．ちょっと伸びた． \
13は，テクニックをカテゴリにした．ちょっっっとのびた．　long_titleに対しても，BERTで予測したら，CVはへったがLBのびた．ノート分ければよかった．

