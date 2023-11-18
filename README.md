# functional-programming-from-scratch-ja

---

## Unknown Unknowns 「知らない事に気づいてない」
---

---

全UNIT 1 ~ 5 

![image](https://raw.githubusercontent.com/ken-okabe/web-images3/main/img_1699680323457.png)

https://zenn.dev/ken_okabe/books/functional-programming-from-scratch-1

![image](https://raw.githubusercontent.com/ken-okabe/web-images3/main/img_1699680354148.png)

https://zenn.dev/ken_okabe/books/functional-programming-from-scratch-2

![image](https://raw.githubusercontent.com/ken-okabe/web-images3/main/img_1699680377421.png)

https://zenn.dev/ken_okabe/books/functional-programming-from-scratch-3

![image](https://raw.githubusercontent.com/ken-okabe/web-images3/main/img_1699680405688.png)

https://zenn.dev/ken_okabe/books/functional-programming-from-scratch-4

![image](https://raw.githubusercontent.com/ken-okabe/web-images3/main/img_1699680431816.png)

https://zenn.dev/ken_okabe/books/functional-programming-from-scratch-5

---

## 関数型プログラミングはなぜわかりにくいのか？

多くのプログラマーにとって

- **Unknown Unknowns 「知らない事に気づいてない」**

さらに

- **Unknown Knowns 「知ってる事なのに気づいてない」**

領域にある知識体系だから

そして、その「気づき」について丁寧に説明されることは稀だ

---

## 巷にあふれる多くの関数型プログラミングの解説

関数型プログラミングとは、

-  **純粋関数（Pure fiunction）** を組み合わせる

-  **純粋関数とは、（副作用（Side effect）** があってはならない

- 「変数」は **イミュータブル（Immutable）** だ

-  **参照透過性（Referential transparency）** がある（ように心がけよう）

概ねこういった感じで、目新しい用語とともに特徴、スペックが列挙される

これらすべては、 **かなり厳しい制約ルール** であり、プログラマがこれまで意識してこなかった要件であることは間違いなく、コーディングの自由度を奪う、 **まるでプログラマの手足を縛ってしまう** ように感じられてしまう

それぞれの用語の概念の正体については **「それは本当は何のことなのか？」** 実は最後の最後まで読者へきちんと説明されることはない

なぜその概念でなければいけないのか？なぜそこまで制約されないといけないのか？？ **「それは本当は何のことなのか？」** がきちんと処理されていないので、目新しいコードと共に、「こんな綺麗なコードが書けますね」「なんとなくメリットが感じられましたか？」的にゴリ押しされてしまうことがとても多い

ほんとうは、これらの目新しい用語と概念には、 **シンプルで強固な共通点** があり、根本的に気づいておくべき概念がある、そこをまず最初に徹底的に説明しなければいけない

そこは偉大な「気づき」のプロセスであり、本来ならば「気づき」は **知的な探検・冒険** であり、たいへん面白いものであるはず

しかし巷の解説の第一目標が、こういう列挙された特徴を網羅しておくこと、それぞれに説得力ありそうな説明を紐付けること、というような本末転倒な姿勢であるがために、この一番重要な「気づき」については、まるでおまけ程度に軽く触れられるだけか、あるいは完全にすっとばされてしまう

説明する人間も「本当はわかっていない」（実はこのケースは非常に多いと見ていて思う）か、わかっていてもすでに体得してしまっている本人にとっては、あえて親切に説明する行為は技量も必要なので面倒くさい、「一応は言ったよね」で済まされやすい

*もちろん、筆者はすべての解説を知っているわけではないが、この理由でほとんどの解説は失敗している、と思う*

---

## Knowns | Unknowns  〜「知っている事」「知らない事」

![image](https://raw.githubusercontent.com/ken-okabe/web-images3/main/img_1700029123626.png#gh-light-mode-only)
![image](https://raw.githubusercontent.com/ken-okabe/web-images3/main/img_1700313259114.png#gh-dark-mode-only)


ある人間にとっては、世の中には **Knowns | Unknowns**   〜 **「知っている事」「知らない事」** がある

*もちろん世の中「知らない事」のほうが圧倒的に多いだろうし、こんなグラフの比率で済むはずはないので「知っている事」の大きさは説明の都合上かなり誇張されている*

---

![image](https://raw.githubusercontent.com/ken-okabe/web-images3/main/img_1700031545739.png#gh-light-mode-only)
![image](https://github.com/ken-okabe/functional-programming-from-scratch-ja/assets/1316994/594348d8-e95b-40e0-b91c-b1dd58f08fd2.png#gh-dark-mode-only)


少しずつ、 **Unknowns「知らない事」** の領域を置き換えるように、 **Knowns「知ってる事」** の領域を押し広げていく行為が **知識の獲得** ということになる

たとえば、プログラミング、ITの領域に限定して言うならば、

-  **Rust** というプログラミング言語を学びたい！

-  **UnrealEngine5** を使いこなせるようになりたい！

-  **Docker** の実践的テクニックを知りたい！

といった感じになるだろう

---

## でも、それって自分にとってUnknowns「知らない事」である事は、Known「気づいていた」よね？

<img width="300px" src="https://raw.githubusercontent.com/ken-okabe/web-images3/main/img_1700033588167.png">
<img width="300px" src="https://raw.githubusercontent.com/ken-okabe/web-images3/main/img_1700033804207.png">
<img width="300px" src="https://raw.githubusercontent.com/ken-okabe/web-images3/main/img_1700034037135.png">

Rust、UnrealEngine5、Dockerその他もろもろは、プログラミング、IT世界で **有名な、Well-known「よく知られている」** 技術だ

![image](https://raw.githubusercontent.com/ken-okabe/web-images3/main/img_1700041298905.png)

ここでの **有名な、Well-known「よく知られている」**  とは皆が技術の中身をよく知っている、熟知しており精通している、ということではなく、名前が知れ渡っており、よく認知されている、気づかれている、という意味になる

![image](https://raw.githubusercontent.com/ken-okabe/web-images3/main/img_1700205229981.png#gh-light-mode-only)
![image](https://github.com/ken-okabe/functional-programming-from-scratch-ja/assets/1316994/d7ca0c3a-a73e-40f1-a8e9-5d1443d9245c.png#gh-dark-mode-only)


---

## Unknown「気づいてない」という未知の領域

![image](https://raw.githubusercontent.com/ken-okabe/web-images3/main/img_1700205262782.png#gh-light-mode-only)
![image](https://github.com/ken-okabe/functional-programming-from-scratch-ja/assets/1316994/27d16414-99ce-46f2-8ea8-c15ca391bcd5.png#gh-dark-mode-only)



つまり、技術の中身を知っていようがいまいが、その **よく知られたKnown領域** のさらに外側には、一般によく認知すらされていない、 **Unknown「気づいてない」未知の領域** が存在している

---

## Unknown「気づいてない」をKnown「気づいている」に変える

![image](https://raw.githubusercontent.com/ken-okabe/web-images3/main/img_1700205286647.png#gh-light-mode-only)
![image](https://github.com/ken-okabe/functional-programming-from-scratch-ja/assets/1316994/b08b4b33-d319-440f-ad90-b8e2aed933b0.png#gh-dark-mode-only)


関数型プログラミングの「部品」は、RustやDockerのようにすでに世間でよく知られているような技術ではない、ので

関数型プログラミングを習得するためには

### Before

Unkown（気づいてない）

### After

Known（気づいている）

というプロセス＝ **気づき** が何より重要

しかし、 **巷にあふれる多くの関数型プログラミングの解説** では、関数型プログラミングにとって必要な、おそらく読者にとっては未知で、気付いてもいないような新概念が、あたかもすでに巷で有名、Well-knownであるかの如く解説を試みている

![image](https://raw.githubusercontent.com/ken-okabe/web-images3/main/img_1700038450865.png#gh-light-mode-only)
![image](https://github.com/ken-okabe/functional-programming-from-scratch-ja/assets/1316994/40bbcf0b-3dbb-4d2c-ac4d-36af81a755f0.png#gh-dark-mode-only)



**このアプローチは通用しない**

その結果、

**「関数型プログラミングには純粋関数という知識があります」**

**「純粋関数は参照透過です」**

**「純粋関数は副作用が発生しません」**

という、知らない概念を、別の知らない概念で説明しようとする、土台のない空中でなにかを組み立てるような、まったく意味不明の解説が通常モードである、というとんでもない状態になっている

もしくは、さすがに本能的にまずいと気付いているケースでは、かなり特異な例題を立ち上げて、そのサンプルコードを書いて読者の説得を試みる

だいたい、この二択で、ボトムラインとしては、根本概念の正体、「気づき」については触れられないまま終わる、肝心の読者の気づきを与えるような説明されることは決してない

-  **知らない言葉で別の知らない言葉を説明する　←論外** 

-  **特異な事例のサンプルコードを示して、未知の概念を読者の脳内で再構築させる　←そんなことができる天才はめったに存在しない**

「両者の合わせ技」というのも存在する

それは、関数型言語である **Haskellのコードを書いて関数型プログラミングや「圏論の入門書」と言ってしまう** パターン

-  **Haskellという知らない言語の未知の言語仕様をもって関数型プログラミングの新規概念を説明する** 

-  **Haskellという知らない言語のサンプルコードを示して、関数型プログラミングや圏論という未知の概念を読者の脳内で再構築させる**

この「両者の合わせ技」は言うまでもなく筋悪であるが、このアプローチでわかったつもりになれた、少なくとも実際にHaskellのコードは自分で書けるようになった人間が、自分が通らざるを得なかった同じアプローチを無限に再生産している、というプログラミング界隈の厳しい現状が実際にある

---

## Unknown「気付いてない」Knowns | Unknowns

###

![image](https://raw.githubusercontent.com/ken-okabe/web-images3/main/img_1700036973819.png#gh-light-mode-only)
![image](https://github.com/ken-okabe/functional-programming-from-scratch-ja/assets/1316994/6dd49c81-9e8f-45b0-8735-6fdd54554f27.png#gh-dark-mode-only)


Unknown「気付いてない」知識には、

- Knowns「知っている事」

- Unknowns 「知らない事」

の両方がある

その事を明確化するために、あくまで分類の概念図の問題ではあるが、グラフを書き換えることもできる

![image](https://raw.githubusercontent.com/ken-okabe/web-images3/main/img_1700042845299.png#gh-light-mode-only)
![image](https://github.com/ken-okabe/functional-programming-from-scratch-ja/assets/1316994/6a1d6fb7-219a-47f6-a59c-81e87f7910bb.png#gh-dark-mode-only)


まず、下半分は、通常気付いている、よく知られている、Knownの領域

![image](https://raw.githubusercontent.com/ken-okabe/web-images3/main/img_1700205635529.png#gh-light-mode-only)
![image](https://github.com/ken-okabe/functional-programming-from-scratch-ja/assets/1316994/a41ba448-ac9b-4327-b2bf-8b004d2f61c1.png#gh-dark-mode-only)


繰り返しとなるが、学びたい対象がすでにWell-knownな技術、RustであったりUnrealEngineであったりDockerである場合は、このアプローチが機能する

**しかし、関数型プログラミングではこのアプローチが機能しない**

---

## Unknown Knowns「知ってる事を気付いてない」

![image](https://raw.githubusercontent.com/ken-okabe/web-images3/main/img_1700193300993.png#gh-light-mode-only)
![image](https://github.com/ken-okabe/functional-programming-from-scratch-ja/assets/1316994/3792f247-6253-4ddd-a580-96fbd8e0e969.png#gh-dark-mode-only)


まず最初に、 **Known Knowns「知っている事を気付いている」ことを再確認** しておくことは、とても重要

たとえば、 **小学校の算数で最初の頃に習った「足し算」「引き算」「掛け算」「割り算」は誰でも「とても良く知っている」はずだ**

**本書では、実際にこのレベルから始まっている**し、それは上記の方針より計画的にそのように設計している

**結局の所、学習とは「すでによく知っているとわかっている事」をベースに知見を拡張するしかない**

*あなたがすでによく知っている事とは、実は、関数型プログラミングに照らし合わせてみると、こういう事なんですよ？*

というのは「気づき」のプロセスであり、これまでのUnknowns「知らない事」を新しく仕入れる作業が発生しないので、非常に楽でスムーズ

**本書では、この作業を意識して徹底的に試みている**

---

## Unknown Unknowns「知らない事を気付いてない」の領域に踏み込む

![image](https://raw.githubusercontent.com/ken-okabe/web-images3/main/img_1700193814082.png#gh-light-mode-only)
![image](https://github.com/ken-okabe/functional-programming-from-scratch-ja/assets/1316994/a6f674bd-9e47-46c5-bca7-516a89b9a6d2.png#gh-dark-mode-only)


次にのステップは、このUnknown Knowns「知っている事を気付いてない」を基軸として、Unknown Unknowns「知らない事を気付いてない」の領域に踏み込む

これはたとえば、 **【時間の流れ】の理論物理学的視点ということまで含む**

関数型プログラミングにおける「時間の取り扱い」について理論物理学的視点で紹介している著名な書籍としては、『計算機プログラムの構造と解釈』（Structure and Interpretation of Computer Programs。原題の略称 **SICP** がよく使われる）

![image](https://raw.githubusercontent.com/ken-okabe/web-images3/main/img_1700194248943.png)

[計算機プログラムの構造と解釈 単行本 – 2000/2/1 ジェラルド・ジェイ サスマン (著), ジュリー サスマン (著), ハロルド エイブルソン (著), & 4 その他](https://amzn.to/3QL29io)

が存在する

**関数型プログラミングにおける「時間の取り扱い」の理論物理学的視点** については、少なくとも筆者は **SICPを例外として、ただひとつの解説を見た記憶がない** ので、それだけ世間でなおざりにされている重要なテーマであると考える

---

# MarkdownNote（VSCode Extention）

この本を執筆するにあたり、膨大な画像の貼り付け、Markdownの記述を効率よく行うために、自前のWYSIWYGエディタ（VSCodeの拡張機能）を開発し利用した

[MarkdownNote](https://marketplace.visualstudio.com/items?itemName=KenOkabe.markdownnote)

![image](https://raw.githubusercontent.com/ken-okabe/vscode-markdown-note-images/main/showcase.png)

![image](https://raw.githubusercontent.com/ken-okabe/vscode-markdown-note-images/main/demo06.gif)


---

全UNIT 1 ~ 5 

![image](https://raw.githubusercontent.com/ken-okabe/web-images3/main/img_1699680323457.png)

https://zenn.dev/ken_okabe/books/functional-programming-from-scratch-1

![image](https://raw.githubusercontent.com/ken-okabe/web-images3/main/img_1699680354148.png)

https://zenn.dev/ken_okabe/books/functional-programming-from-scratch-2

![image](https://raw.githubusercontent.com/ken-okabe/web-images3/main/img_1699680377421.png)

https://zenn.dev/ken_okabe/books/functional-programming-from-scratch-3

![image](https://raw.githubusercontent.com/ken-okabe/web-images3/main/img_1699680405688.png)

https://zenn.dev/ken_okabe/books/functional-programming-from-scratch-4

![image](https://raw.githubusercontent.com/ken-okabe/web-images3/main/img_1699680431816.png)

https://zenn.dev/ken_okabe/books/functional-programming-from-scratch-5

---
