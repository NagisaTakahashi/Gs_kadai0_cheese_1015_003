# Gs_kadai0_cheese_1015_003
Gs_kadai0_cheese_1015_003


# 課題0 -Cheese Academy-

## ①課題内容（どんな作品か）

- 自社サイト：Recouture（リクチュール）のLP<br>
※cheese academyのフォーマット（レイアウト構造）を生かしつつ若干レイアウトもアレンジ。<br>
※中身はすべてRecouture仕様に変更。（ダミー情報は省き、実際に公開しても大丈夫なように正しい情報を載せました。）<br>
※Recoutureの現行LP（　https://recouture-official.com/　）　
をリプレイスできればと思い、まずはTOP PAGEを作成しました。

## ②工夫した点・こだわった点

【Cheese Academyと共通】
- cheese academy版と同様、LPは中身の説明文が適宜更新されていくことが想定されるので、見た目の再現だけでなく構造の再現を心がけました。 「見栄えが合っていれば良い」というpx指定ではなく、文字数が変化しても体裁が崩れないように、上下左右のmargin,paddingの設定方法を数値指定ではなく、なるべくcenterやmiddle指定を活用して、中身のコンテンツにある程度変化があってもレイアウトが簡単に崩れてしまわないように設計した点がこだわったポイントです。

【Cheese Academyからのアレンジ点】
- Cheese Academyのレイアウトをしっかりと構造化して組んでいたのと、元々の現行LPとある程度構造自体は似ていたので、なるべくそれを活かしつつ、現行LPに寄せる形で制作した。
- 現行LPで出来ていないヘッドメニューの固定バーなどの設置できたので、＋αの仕様ができた点が良かったところです。（ハンバーガーメニューはまだですが…）
- Cheese Academy（提出末尾001、002）からの変更点としては、中身をRecoutureにごっそり入れ替えたことと、フォントや配色もRecoutureのブランドカラーから忠実に再現しました。
- フォントはILTYで学んだgoogle fontの方法をベースに、Adobe fontを試したところ、こちらも使えたので、ブランドとして統一して使用しているAdobe系のフォントをWebでも合わせられると分かったことはすごくよかったです！
- ユーザー目線では、リンクが押せるところは必ず色を変えるかホバーをさせて「押せるところ」だと直感的にわかりやすいようにしました。（「詳しくはこちら」や「送信」ボタン、ヘッダーのメニューなど）
- ホバーで色が変わるのは結構楽しいので、今後はユーザーさんに「押してもらいたい」ところに効果的に効かせると、ブランド側としても見てもらいたいコンテンツに視線を促せるのかなと感じました。（全部に大げさにつけると邪魔になるような気もするので、さりげなさとのバランスや、効果的に効かせるための差し引きも重要そうだなぁと作りながら感じました）
- まだTOP PAGEしか出来ていないのですが、残りの現行LPのページも適宜制作して、卒業までにLPリプレイスをひっそりと目指します！（メインはLPではなく作りたいAppがあるのですが、こちらもせっかくなのでやりたいです！）

【レスポンシブ対応】
- 弊社のお客様は現行のLPもECサイトもほとんどスマホからのアクセスなので、レスポンシブも必須で対応しました。
- レスポンシブは「PC版の２倍かかる」と聞いていたのですが、実際にやると細かい調整がありすぎて体感10倍くらいの時間がかかった感じがします。。レスポンシブを完全に美しくはめきれていないところがあるので（後述のお問い合わせフォームなど）引き続き学びつつブラッシュアップします。





## ③難しかった点・次回トライしたいこと(又は機能)

 【難しかった点１】　全体設計
- 今回はある程度レイアウトありきでコンテンツを箱に合わせて入れてしまったので、本当にお客様に見せたい順番や見せたいコンテンツにフォーカスがあたるようにハイライトできているかというと完全ではない状態です。まず全体設計として、このLPを通じてなにをどういう順番で見せたいかとその中身に応じた効果的なレイアウト組み（配置や見せ方）を考えてから、書き始めると、完成度がより高まると思っています。こちらもちょこちょこ改善していきたいです。
- ページのレイアウトも、まだまだ「見せたい形で見せる」というより「見せれるもの（つくれるもの）で見せる」になってしまっているので、自分の実装力を高めて、しっかりと見せたい形でお客様にお届けできるようにしていかねばと痛感しています！


 【難しかった点２】　ページ数
- これはまだまだですが、TOP PAGEだけでも大変だったので、これがあと5-6Pあるかと思うと結構大変だなぁと思っています…。少しづつ作業効率も高めて行きたいと思います。！

 【難しかった点３】　レスポンシブ対応
 - ユーザーニーズ上、切っても切り離せない必須のレスポンシブなのですが、まだPC版をつくるより苦手意識がありサクサク進みませんでした！「あっちを修正するとこっちが崩れる・・・」の連続や、端末によって異なるpx数のため「この端末ではきれいに表示できてたのにこのサイズにするとダメじゃん！」が発生して心折れそうになりました。笑　慣れもあるかもしれないので、ここも積み上げて、もう少しきれいに美しく組めるようにやっていきたいと思います！


## ④質問・疑問・感想、シェアしたいこと等なんでも

 【質問・お悩み】
- レスポンシブでのお問合せフォーム崩れがまだ直せていない状態なので、引き続き調べています。。。。！　vh,vwを使っていくつかの端末できれいに配置できても、検証モードで端末の横幅を変えるとまた崩れたりするので微調整をしています。


 【感想】
- たった１回の座学（と、連日の動画講座のおかげ！！）でここまでLPが作れるようになるなんて本当にびっくりしました！
- 他のプログラミング学習（オンライン）や本でコードを書いても、体系的な理解ができていなかったので、丸暗記状態（結局暗記もできないので都度調べる）だったのですが、Gsの先生方の教え方のおかげで体系的に理解ができたことにより、自分でサクサク応用が進む状態になり自分でもびっくりです・・・！
- 一番の学びは「HTMLにclassを指定していきCSSで指示を出している」という根本的な構造が理解できたことと、その方法（指示の出し方の基本的なバリエーション）が抑えられたことです。これにより、調べながらすすめる際に記事を読んだりしても、何を言われているのかが各記事すんなり理解できるようになり、応用の幅がかなり広がりました。
- 「つくれる」と実感できると、作るのが楽しくなってどんどん作りたい！進めたい！という気持ちになるので、すごく楽しみながら第一歩がスタートできてとてもよかったです！ありがとうございます！


 【リンク先に使ったWebサイト】　※実際に公開しても大丈夫なように、いずれも自社で実際に公開・運用しているものを引用しました。
- LP：https://recouture-official.com/
- ECサイト：https://recouture.shop/
- Instagram：https://www.instagram.com/recouture_official
