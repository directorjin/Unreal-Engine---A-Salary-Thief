# Unreal-Engine-Game---a-salary-thief

<hr>  

🕹️How to Play
-------------

移動キー  
<img width="500" src="https://user-images.githubusercontent.com/44941601/76395347-74087680-63ba-11ea-81d5-5882092c6e33.png">  
早走り - SHIFT  
ジャンプ - Space  
マウスでカメラの回転  
マウスの左クリックでコイン投げ
<hr/>    
  
GitHubの容量問題のためGoogle drive linkからソースファイルをダウンロードして下さい。
===========
  
Build File : https://drive.google.com/open?id=1YK_DUQPREFtyYVKiWAUyJxexEmtptcBy
  
Source File : https://drive.google.com/open?id=1Ayt3_MfrZwimGkihlZbBLb3Z6arep0M0
  
<hr/>  
  
  
  
  
Description
===========
  
このゲームはアンリアルエンジンで作られました。
----------------------------------------------
このゲームのジャンルは潜入です。
---------------------------------------------
このゲームは私一人でプログラミングをしました。
------------------------------------------------------------
チームの同僚は企画と書類の作成と発表を担当しました。
-------------------------------------------------------------



Q : このゲームを作った理由?

A : 理由は二つあります。
  
1.単純に戦闘を通じて敵を相手にするのは面白くないと思いました。 それで、MetalGearSolidゲームのように潜入システムを作ってみたかったのです。
2.普通のゲームよりAIを利口にしてみたかったです。
  
  

<hr/>  

**今回のゲームで一番力を入れたのは、アンリアルのシネマティックと敵のAIです。**

<hr/>

  
Focus on The Game
----

最近、映画のようなゲームが多く登場し、シネマチックシーンがよく使われた。  
したがって、私はゲームプログラマーとして知っておくべき技術だと思って、このゲームに多く適用してみた。
  
<hr/>  
  
<img width="700" src="https://user-images.githubusercontent.com/44941601/74715682-4c693700-5270-11ea-8a0f-7bef4b63cd7f.png">
1. タイトル画面は、プレイヤーが使用するマップ全体をカメラで一つ一つ見せてくれる。 
  
**内容翻訳 : IT企業に入社したルパンさん、今日も週末出勤しました。
でも今日だけは必ず、会社から脱出しようと決心しました。  **
  
*そうさせた理由 : 自分がプレイするゲームの雰囲気を感じるのにも役立ち、マップをあらかじめ見ることができるため潜入プレイにも役立つ。*
  
<hr/>
  
  
<img width="700" src="https://user-images.githubusercontent.com/44941601/74717632-1332c600-5274-11ea-9168-2c27a7e5d7aa.png">
2. ゲームを開始すると、オープニングシネマティックが出る。 状況を説明するテキストは華麗な効果と華麗な動きを見せてくれる。  
そしてSkipボタンを実装した。
  
*そうさせた理由 : オープニングからプレイヤーたちを退屈させたくなかった。 映画のように速いカット転換とゲームの中に存在するように感じられるテキストでプレイヤーたちを没入させたかった。   
そして2回目のプレーをするユーザのためにスキップボタンを実現した。*
  
<hr/>  
  
<img width="350" src="https://user-images.githubusercontent.com/44941601/74718142-fa76e000-5274-11ea-9ca3-308b78d003a4.png"><img width="350" src="https://user-images.githubusercontent.com/44941601/74718805-4413fa80-5276-11ea-9490-a2852ece8b35.png">  
  
3. ドアの近くに行くと、行動ボタン(Eボタン)が活性化する。 ドアは、プレイヤーが立っている方向によって異なる。 ドアはプレイヤーが閉めることもできる。
  
*そうさせた理由 : いらないUIを画面にたくさん見せてくれたので、プレイヤーの没入感を落としたくなかった。  
それで必要な時だけEボタンを活性化させた。 そして、ゲームの特性上、プレイヤーが逃げることが多いが、ドアを利用して逃げることができるよう、
プレイヤーの位置によってドアが開いたり閉じたりできるようにした。*

<hr/>  
  
<img width="350" src="https://user-images.githubusercontent.com/44941601/74719454-66f2de80-5277-11ea-9578-3a27bad0b93a.png"><img width="350" src="https://user-images.githubusercontent.com/44941601/74719119-c7355080-5276-11ea-97d3-1a1bd9f2f994.png">
  
4. プレイヤーはドアを開けて出てすぐ、会社を脱出できるドアを見ることができた。 
しかし、接近して行動キーを押すと、"鍵が必要です"というメッセージが表示された。  
  
*そうさせた理由 : プレイヤーが脱出したいという気持ちになれるように、目標を作ってくれた。   
目の前にある目標である扉を開けられないように作ったので、プレイヤーの心の中で挑戦意識が生まれた。*

<hr/>

<img width="700" src="https://user-images.githubusercontent.com/44941601/74720170-aec63580-5278-11ea-885b-3b15347148fb.png">

5. その後のNPCとの会話UIである。 プレイヤーは多様な選択肢を選んで鍵の位置を突き止める。  
  
*そうさせた理由 : UIはゲームの雰囲気に合わせて最大限モダンにした。 そして、様々な選択肢を作り、プレイヤーがNPCと会話できるようにして、没入感を高める。*

<hr/>
  
<img width="350" src="https://user-images.githubusercontent.com/44941601/74720879-d23db000-5279-11ea-8bb9-0c42ae997499.png"><img width="350" src="https://user-images.githubusercontent.com/44941601/74721718-2a28e680-527b-11ea-933e-967df85a1909.png">
  
6. 他の重要なNPCとの会話で適切な選択肢を選ぶとマニュアルと地図を与えた。
  
*そうさせた理由 : 選択肢を選ぶのも一種のミニゲームだと思った。 プレイヤーとNPCが相互作用する感じを与えようとした。*


  
<img width="700" src="https://user-images.githubusercontent.com/44941601/74722006-8f7cd780-527b-11ea-9816-dd59b5069a56.png">
  
*マニュアルにはランニングボタンがshiftということを知らせてくれる。
しかし、プレイヤーが走ると、足音がして近くの敵AIが足音を聞いて確認に来ることもあるということを知らせてくれる。  
マニュアルにはマウスクリックでコインを投げられるということを知らせてくれる。  
そして、コインを投げれば、コインのあるところにAIを誘引することができるという事実も知らせてくれる。*

<hr/>
  
<img width="350" src="https://user-images.githubusercontent.com/44941601/74722482-598c2300-527c-11ea-8042-3068477c4791.png"><img width="350" src="https://user-images.githubusercontent.com/44941601/74728327-e091c900-5285-11ea-9c0c-fea97947f3d9.png">
  
7. プレイヤーはマウスの左クリックをしてコインを投げることができる。(赤く表示されたものがコイン)  
コインは床に触れると音を出して敵のAIを誘引することができる。  
  
*そうさせた理由 : 潜入ゲームの面白さは誘引と逃げだ。 誘引のためにコインを具現した。 コインは物体に触れると音を出して敵のAIを誘引する。 
誘引を誤るとプレイヤーは危険になり、誘引すれば敵を欺くことができる。*
  
<img width="700" src="https://user-images.githubusercontent.com/44941601/74728795-b8ef3080-5286-11ea-8f77-cfb4db64723c.png">
上の写真から投げたコインに敵の視線を変えた。  
  
<hr/>  
  
<img width="700" src="https://user-images.githubusercontent.com/44941601/74729008-1aaf9a80-5287-11ea-9e48-58218d73fd50.png">
  
8. AIがプレイヤーを遠くから見つけると"疑い状態"になる。  
AIがプレイヤーを間近で見つけると"追撃状態"になる。  
追撃状態では、プレイヤーはAIとの距離を遠ざけるか、ドアの後ろに隠れていなければならない。
  
*そうさせた理由 : いろんな状態を作って賢いAIを作りたかった。  
そしてAIとの距離を広げるのは簡単なことではないため、門を超えるプレイヤーを認識できないようにした。*

<hr/>
  
<img width="350" src="https://user-images.githubusercontent.com/44941601/74729764-55660280-5288-11ea-9e92-687ef2d51b47.png"><img width="350" src="https://user-images.githubusercontent.com/44941601/74729841-74649480-5288-11ea-8a98-d067e6d16a8a.png">
    
9. ESCキーを押すとメニュー画面が出て、Settingを押すとサウンドの調節とAIのランニングスピードを調節できる。
  
*そうさせた理由 : 潜入ゲームに慣れたプレイヤーは高い難易度を、潜入ゲームを初めてするプレイヤーは低い難易度でゲームをクリアできるようにしたかった。
私もMetal Gear Solidを初めてやった時に低難易度でやっていたのでクリアできたし楽しさを感じた。 それで、私は難易度の調節はプレイヤーを考える必要不可欠だと考えた。*

<hr/>

<img width="350" src="https://user-images.githubusercontent.com/44941601/74730539-a6c2c180-5289-11ea-8c39-bddd5c5ddaaa.png"><img width="350" src="https://user-images.githubusercontent.com/44941601/74730570-b2ae8380-5289-11ea-9b3e-19ae8847674d.png">
  
10. 2階にある鍵を得て、初めて見た1階の大きな門に行ってEキーを押すと、エンディングシネティックに移動。

<hr/>
    
<img width="700" src="https://user-images.githubusercontent.com/44941601/74730754-1173fd00-528a-11ea-9710-0d3e0f74783e.png">
11. そしてユーモラスなエンディングシネマティックで終了。



**内容翻訳 :
主人公 : ついに会社から逃げ出した!  
(電話の鳴る音)  
主人公 : 社長?  
社長 : 君はどこか。  
主人公 : はい、社長。 今家に行くところです。  
社長 : あ、そうかな。 それではそのまま永遠に家でゆっくり休め。 明日から会社に来なくてもいいよ。  
主人公 : ......  
主人公 : 違います。 週末夜勤の準備をしようと寝袋を持って帰ろうとしました。  
社長 : すでに会社に寝袋を個別で買っておいたよ。  
主人公 : ...それでは今また会社に行きます。  
(画面がだんだん暗くなる)**
    
**ENDING**  
    
    
*そうさせた理由 : 長くないゲームであるだけに、エンディングを見ながらプレイヤーが笑えるようにしてあげたかった。
短いゲームでも面白い記憶で残りたかった。*
  
<hr/> 

Play Video
-----------
  
<hr/> 
  
反省
---------
Unreal Engineを勉強し、初めて作ったゲームだった。 AIのプログラミングが複雑でまだまだ少しバグがあるが、
ゲームの全体的なレベルデザインがうまくできていると思う。  
いろんな機能もプレイヤーを思いながら作ってやりがいがあった。  
しかし、マップをもう少し大きくし、様々な敵と様々なアイテム(トラップや麻酔銃)を作ればよかったという残念な気持ちが残った。
  
<hr/> 
  
🔧開発情報
---------

制作時期　:2017/05~2017/06  
制作時間　:  一ヶ月半   
使用ツール :  Unreal Engine 4.22  


