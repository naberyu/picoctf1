General Skills
３、0xは１６進数そいう事0x41を読んでASCIIコードと対応させえて読む
４、２７を二進数にしてpicoCTF{}に入れる
５、0x3Dを十進数にして読む
６、リンク先のページをよく読む
１１、fileの中を見てgrepを使う
１２、net catを使い指定された場所を見る
１４、stringsとgrepを使い解く
１５、net catとgrepを使う。間に|を忘れない事
absolutely relative:absolutely-relative.cを開くとpermission.txtにyesと書いてあればabsolutely-relativeからflag.txtを表示してくれるらしいのでホームディレクトリでechoを使ってかく。その後/problems/absolutely-relative_1_15eb86fcf5d05ec169cc417d24e02c87/absolutely-relativeでフラグを表示される.   
in out error
普通にin-out-errorを開くと「Please may I have the flag?」と打っても訳のわからない文字が出てくるだけ。なので、/dev/nullでin-out-errorの実行結果を出さないでもらうことでフラグを出してもらうことができる。1> /dev/nullとすると最初の実行結果を破棄してくれる。つまり、いらない実行結果を表示しないようにしただけ.   

