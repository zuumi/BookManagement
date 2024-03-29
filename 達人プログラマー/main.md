## いい加減な言い訳を探すよりよりよい対策を探すこと

Tips! 「分からない!」と口に出すこと。その次に「でも答えを見つけ出すぞ」と口に出すこと。
分からないと認識することは素晴らしいこと，その後はプロフェッショナルとして責任を全うしてください。

## エントロピー

「ある系における無秩序な度合いを示す指標。」

全宇宙はのエントロピーは増大していくことは証明されているらしい。

ソフトウェアも同様に時間と共に無秩序になっていく。（いわゆる技術的負債）

重要なのは心理，文化と言えるもの。いわゆる，割れ窓理論を発動させないように心がけ，草の根運動を行うこと。

### 割れ窓理論

「放置」は腐敗を加速させる。全てを治すことができない状態なのではあれば，大きなゴミ容器（新基盤？）を用意するか，夜逃げする準備をするべき。
エントロピーに負けてはならない！

### 感想

一時的に割れ窓を作ったとしても、それを割れ窓と認識していれば、別途対応で良いのではという。
〆切にうるさい組織ほど、こういう割れ窓を作って後で直すということが多いのではないでしょうか？？
もしくは取るべきは，割れ窓が見つかったので期限を伸ばすなどの適切な対応だと思う。（ケースバイケースだけど。）

## 変化の触媒たれ!

教訓話：石のスープ

未来とそれを実現するためのやることを，さも簡単にできるかのように伝えること！

## 品質要求を明確にすること

「今日の素晴らしいソフトウェアは，明日の完璧なソフトウェアよりも好まれる」
ユーザーに対して早期に提供できれば彼らからのフィードバックによってよりよい解決策へと導かれることもある。（曳光弾）

## 十分に良いってどんな？

すべてのシステムはユーザーの要求仕様と，完全に合致し，パフォーマンス，プライバシー，セキュリティといった面での基本的な要求に合致すること。
↑
この判断にユーザーを巻き込むことをオヌヌメする。

> キャッシュフローの制約の中、ユーザーから要求を無視して，新機能を追加し．コードをさらに磨き上げるというのではプロフェッショナルとは言えません。

↑
じゃあ，これ，「割れ窓」に気づいた時，先にユーザーからの要求（期限通り提供すること）を満たした上で，後から必ずなおすって決めるが最良？

> 不可能なスケジュールを約束したり，納期に間に合わせるために基本的な技術面をおろそかにするのもプロフェッショナルとしてあり得ないのです。
あなたが開発しているシステムのスコープと品質は，システム要求の一部として議論されなければなりません。

ちょっとだけ耳がいたい。割れ窓ではない，品質をあげることってなんだろう．適切な命名とか？


序章p23 + p1~p17 で一番響いた言葉は、「知識への投資は常に最高の利息がついてくる。」ベンジャミン・フランク

## 知識ポートフォリ

定期的な投資をするためのアクションリスト

### 毎年少なくとも1つは新しい言語を学習する

### 月に1冊のペースで技術書を読む

テクノロジーに関連しない分野にも手を広げる

### 講習を受講する

### 近場のユーザーグループに参加する

### 異なる環境に慣れ親しんでみる

普段Windowであれば，Linux環境に親しんでみる

### 最先端にとどまり続ける

## 批判的視点をインストールせよ！

### 5つのなぜ（five why?）?

深堀して「質問」すること，えーこれって「なぜ？」って根本的な問題（本質）に近づく

### メリットはだれににあるのか?

### 文脈（コンテキスト）はなんのか?

ベストプラクティスって，何にとってベストなの？って話。

### いつそれは有効になる？

### なぜこれが問題なの？


# 達人のプロジェクト

## 品質

* 達人プログラマーがいう品質の実現に取り組んだことを目標に取り入れるのが良いのでは？
    * 割れ窓を減らす
    * コードリファクタリング
    * 手動作業を自動化することで，デプロイ品質を高め，結果再現性の高いデプロイを行えて，エラーひいてはインシデントを防ぐことにも繋がる。

## 事を成し遂げるにはまずスケジュールする。

以上。

## DRY原則

すでにこの原則について知識として得ていたものの，実際にチームで開発を行う上で、どのように実践することが，達人として振る舞いなのか，ベストプラクティスとなるのか認識できた。この節によって。

以下，耳が痛かった事柄。

* DRY原則にそって，チーム開発を進めるためには，「優れた」コミュニケーションが必要。（これが鍵となる。）→ここでいう「優れた」は「即時的」かつ「スムーズ」なという意味を持っている。
    * 質問をしたり状況を報告するのに1週先のMTGを待たないといけないのは，あまりにもスムーズさに欠けます。

* スムーズとは容易かつ，mtgのような儀式を介することなく，質問を投げかけたり，自らの進捗状況（や問題，洞察，教訓）を共有できたり，チームメイトのやっていることを追いかけられるということを意味している。

言うよりやることは難だけど，
今，現状，自分にインストールしたいのはこの「スムーズ」ということかなと思った。

## 完璧に機能するチームを編成するために

* 目標：開発工程をエンドツーエンドで行えること。
* ツール：開発メンバーのスキルマップ

## 開発でやり過ぎないようにするための教訓

「絵図制作のやめ時を知る。」
自分自身のほうほうで能力を発揮できるようにお膳立てしてください。（はい。）
「十分によいソフトウェア」の画家のように，もう一筆かきかえたい誘惑を堪えよう。

大事なのは，彼らがプロジェクトに価値をもたらせるよう保証することなのです。

### 所感

現リーダーがこれを無意識に実践しており，前リーダーはこれを意識しないとできないまたはたまに思いだしたかのようにやっているw。
達人プログラマーがいう「十分によいソフトウェア」って何？→これを武器のように突きつけたくなった。いつも，前リーダーが我々にやっているように。これが正義なのだと言いたい！！！w

## 万能な方策など存在しない．

* プロジェクトの進め方で、方法論を真似るだけでは意味なし。
    * 試して→振り返り，意味があったか価値があったか見直すことが重要。

## 達人となるためのスターターキット

まだ読み途中だけど，書かれている三種の神器は実際に実践している事であり，やっていることは間違ってなかったんだと認識できた。

* バージョン管理
* 回帰テスト
* 完全な自動化

ただし，所々で疎かになっている部分がありそうだなと思う部分もあった。

### 耳が痛かったフレーズ

> 多くの開発者はコードのどの部分が弱いかを知っており，無意識のうちにその部分を避けた「手ぬるいテスト」を行う傾向があります。達人プログラマーであれば，このような態度を避けなければいけません。「今」バグを見つけるためにテストをやっておけば，あとでバグを見つけられて恥ずかしい想いをしなくても済むのです。
