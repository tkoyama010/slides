# 翻訳同人誌を始めよう

### お前誰よ
こんにちは"ゆうげん"@tkoyama010という名前でTwitterをやっています。
普段の仕事は数値計算系の仕事をやっていまして、主にFEMと呼ばれる手法を用いて受託計算をしています。
技術書典でもFEM関連の同人誌を頒布しています。
ただ、ライブラリの内容について詳しく説明をしても正直、皆様にプラスにならないと思います。
そこで、今回はこのライブラリの同人誌を作る際にしたことと、それに関して面白いと感じたことについて共有させていただきます。

### 使っているライブラリと驚異のユーザー数
今、私が同人誌を頒布しているライブラリはPythonからFEMができるというライブラリです。
こちらのライブラリは1990年代から使用されているライブラリで世界的にもユーザー数は多いですが日本での認知度はあまりありません。
ちなみに2018年までの日本でのアクティブユーザー数と開発者数は弊サークル調べで1人でした。
ちなみにこの1人はサークル主です。
正直、ユーザー数はこんな感じですが、ライブラリ自体は使い勝手がとても良く、もっと多くの人にこのライブラリの存在を知ってもらいたいと思い同人活動をはじめました。

### オリジナルの技術同人誌以前の問題
このような状態ですから、そのそもの日本語情報が不足しているという状態です。
ドキュメントも全て英語でこれからこのライブラリについて学ぼうという人にはとてもハードルが高い状態でした。
私もライブラリのドキュメントを全て把握しているわけではありませんので、まずはそこからはじめようという状態でした。
ドキュメントの量は単語数に換算すると20万あり、それだけの量の英語ドキュメントを読んでいたら同人誌を出す前に心が折れてしまうという状態でした。

### 翻訳技術同人誌を作ろう!
そこで、まずは英語ドキュメントを日本語に翻訳し翻訳したドキュメントをそのまま技術同人誌として頒布するという形態にしました。
英語のドキュメントはGNU Free Documentation Licenseで公開されています。
このライセンスの内容は次の通りです。
- この文書を無断で複製してよい。
- この文書を無断で改変してよい。
- この文書を無断で頒布・販売してよい。ただし、頒布を受けた者や購入した者に対して、上記の許可を与えなければならない。
つまり。和訳という改変を加え同人誌イベントでも自由に頒布することが可能です。

### Sphinxの国際化機能
このライブラリのドキュメントにはSphinxが使用されています。
Sphinxにはドキュメントそのものの翻訳を容易にする機能があります。
こちらが、Sphinxのドキュメントを翻訳する際の流れです。
まずはじめに、rstファイルからpotファイルを作成します。
potファイルは翻訳可能な全ての文字列のリストを保持するファイルです。
その後翻訳リソースファイルであるpoファイルにこのように翻訳を記入していきます。
poファイルの翻訳が完了したら、poファイルからmoファイルと呼ばれる文書に翻訳を適用するバイナリファイルを作成し、そのファイルと文書を一緒にビルドすることにより翻訳された文書が完成します。

### 翻訳技術同人誌の特徴
このようにして、技術書典5から毎回、翻訳技術同人誌を生産しています。
実はまだ、オリジナルの技術同人誌というものを一回も書いたことがないのですが、周りの皆さんがオリジナルの技術同人誌を書かれているのを見るとこちらのような特徴があると思います。
- 「基本的にネタ切れがない」
翻訳する対象は既に完成形として存在するため、自分が翻訳したいものがあれば何を書こうかまようことはありません。
- 「新しい用語を生み出す機会がある」
海外にしかない文書を翻訳する際には、日本にその概念がない場合も多々あります。
最近あった例は、continuation methodという単語が出てきたんですけど、これに対応して日本語で使われている単語がどうしても見つからなくて、大学の先生に確認したことがありました。
ところが、その先生もご存知ないということでしたので継続法という単語を当てることにしたという経緯がありました。
- 「Typoやセクションの追加でコントリビュートができる」
やはりオリジナルの文書を書いているのも人間ですから、Typoや必要な事項の説明漏れがあります。
その場合、それを修正したプルリクを送ることでそのOSSに貢献することができます。
- 「自分がすごくなくても、すごい人の文書を広めることはできる」
やはり、広く使われているOSSの文書は自分よりすごい人が書いているので、学べることが多くあります。
英語というバリアを取り払うことで、このようなすごい文書へのアクセスを増やせることができるのではないかと考えています。

### まとめ
私のLTは以上になります。
お伝えしたかったことはこちらです。
- ライセンスが問題なければオリジナル同人誌だけではなく翻訳同人誌という選択肢があります。
- 翻訳する文書がSphinxで書かれている場合、国際化機能が便利です。
- 翻訳同人誌にはオリジナル同人誌にはないメリットがあります。
以上です。ありがとうございました。
