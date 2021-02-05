# 2020gsc_YukaSaito
2020年度古橋ゼミ論用レポジトリ  
 学籍番号：1A118074      
 氏名：斎藤 祐花   
 地球社会共生学部 地球社会共生学科 3年A組80番   
 指導教員：古橋 大地 教授  
 © Furuhashi Laboratory/Yuka Saito, CC BY 4.0  
***

# 【2020年度ゼミ論】 ブランドイメージを崩さないウェブ地図スタイリング手法の開発と実践 〜鬼滅の刃を例として〜
##  概要
##### 本研究ではブランドイメージを崩さないウェブ地図スタイリングの手法の開発を、漫画・アニメ「鬼滅の刃」のキャラクターを例にしたmapboxでのデザイン地図制作実践をもとに行う。また、最終的にスタイリングしたデザイン地図をどのような形で活用することができるかに関しても模索する。 
##  Introduction
 ITプロダクトやweb上の様々なサービスで欠かせないツールである地図だが、現在ではそれらのブランドイメージや使用事例にあったデザイン地図が多用されており単に道案内や空間情報を伝達する役割だけでなくその地図を使用するユーザーにブランドのイメージを適切に構築させる重要な要素となっている。 [Mapbox](https://www.mapbox.jp/mapbox-studio) では、地図のデザインを使用用途やサービスのイメージに合わせフォントやベースのテクスチャーやカラーを細かに選択することができる。今回のゼミ論ではこのMapboxを使用し論文の読み手により伝わりやすいように現在社会現象を巻き起こし老若男女問わず愛される「鬼滅の刃」を例とする。なかでも特徴的な印象をもつキャラクターをピックアップし手法の開発をおこなう。尚、筆者は鬼滅の刃の大ファンでありアニメや単行本もさることながらファンブックや公式キャラクターズブックなども読破済みのためそれらの情報をもとに、より忠実にそのキャラクター自体や鬼滅の世界観やブランドイメージをもタイトル通り崩すことなく再現したい。 
##  Methods
Mapboxを使用したオリジナル地図デザインの作成 
 
例：　漫画・TVアニメ「鬼滅の刃」 

本研究では、web地図との親和性を考慮し特にTVアニメ版の鬼滅の刃のキャラクターデザインやカラーを参考にする。 
TVアニメで登場する主要キャラクターのモチーフや服装などの設定資料を収録した[公式キャラクターズブック](https://books.shueisha.co.jp/items/contents.html?isbn=978-4-8342-1721-6)からキャラクターのカラーや雰囲気、モチーフなどをピックアップしキャラクターイメージを構成する要素をまとめる。はじめはカラーを中心にデザインをしていき、その過程でキャラクターのモチーフとなる要素を地図上におとしこみ最後にキャラクターの性格や雰囲気からそのイメージにあったフォントを選択する。以下カラー、モチーフ、フォントの3点を順に詳細を述べる。
 
【　カラー　】 
各キャラクターのイメージカラーとなりうる、瞳の色、髪の毛の色、羽織の色、鍔や鞘の色を抽出しbaseやroadの全体の面積の多くをしめるエリアから順に適切なカラーを選択

カラーの抽出方法：①本で必要な部分を写真にとる ②[カラーピッカー](https://lab.syncer.jp/Tool/Image-Color-Picker/)）でカラーコードを抽出(複数候補の色が出た場合はmapboxに反映されたときに実際の色に一番近いものor他の使用色との相性を見て判断) 

【　モチーフ　】 
先にまとめたキャラクターのイメージを構成する要素を地図上にどうにか落とし込む。例えば、鬼滅の刃の主人公の妹である竹をくわえた少女の鬼”禰豆子”であれば着用している着物の麻の葉模様や竹筒、額の左上の薄桃色の髪飾りなどである。 それらのモチーフの形や配色を、地図上の道の張り巡らせ方や地形に着目しすり合わせていく。 

【　フォント　】
キャラクターのイメージや性格、雰囲気などに合わせてフォントを選択する。また、カラーとフォントの相性も見ながら調整する。


  
##  Result
[竈門禰豆子デザイン](https://api.mapbox.com/styles/v1/yukasaito/ckk2nghbv3mq917lewdd4eyut.html?fresh=true&title=view&access_token=pk.eyJ1IjoieXVrYXNhaXRvIiwiYSI6ImNrZDYxdjRzcTFrN2wycW8zNnBvZndwcGEifQ.rblEBet0xcsjyEvxDI1SzQ)  
![Nezuko Kamado](https://user-images.githubusercontent.com/62432677/105676810-61ddeb00-5f2e-11eb-80b7-4fb928c2cb93.png)  

   
   
[煉獄杏寿郎イメージデザイン](https://api.mapbox.com/styles/v1/yukasaito/ckk2p8f233odv17nzpgpn4hzz.html?fresh=true&title=view&access_token=pk.eyJ1IjoieXVrYXNhaXRvIiwiYSI6ImNrZDYxdjRzcTFrN2wycW8zNnBvZndwcGEifQ.rblEBet0xcsjyEvxDI1SzQ)  
![Kyojyuro Rengoku](https://user-images.githubusercontent.com/62432677/105671286-ccd6f400-5f25-11eb-8741-0fa3df7ee12c.png)  
   
[胡蝶しのぶイメージデザイン](https://api.mapbox.com/styles/v1/yukasaito/ckk2i5son0cv017p3t034mk0m.html?fresh=true&title=view&access_token=pk.eyJ1IjoieXVrYXNhaXRvIiwiYSI6ImNrZDYxdjRzcTFrN2wycW8zNnBvZndwcGEifQ.rblEBet0xcsjyEvxDI1SzQ)  
![Shinobu Kocho](https://user-images.githubusercontent.com/62432677/105671367-eed07680-5f25-11eb-921d-b5c7b461705b.png)  
   
結果として以下の三点がブランドイメージを崩さないweb地図スタイリングにおいて重要なポイントである。 
 
 

【 カラー選び 】 
 
キャラやブランドの特徴的な色をピックアップ。カラーパターンを用意。配色に注意（地図上に反映させた時の色のぶつかり合いや面積等）。 
 
【 モチーフや特徴的要素の再現 】
 
キャラやブランドの特徴的なモチーフや柄などの要素を挙げる（竹筒・麻の葉模様、薄桃色の髪飾り）。地図上の道の張り巡らせ方や地形に着目しすり合わせる（放射線状に広がる道を模様に見立てる） 

【 イメージを崩さないフォント選び 】
 
キャラやブランドの性格やイメージを細かに研究（胡蝶しのぶ：華奢,艶やか, 曲線感, ミステリアス）。適切なフォントを選択。カラーとの相性や全体とのバランスをみて調整。


  

##  Discussion 
##  Conclusion 
##  参考文献

> 松澤(2020), TVアニメ『鬼滅の刃』 [公式キャラクターズブック 壱ノ巻](https://books.shueisha.co.jp/items/contents.html?isbn=978-4-8342-1721-6), 集英社, 原作 吾峠呼世晴, ©︎吾峠呼世晴/集英社・アニプレックス・ufotable  
> 木下(2021), TVアニメ『鬼滅の刃』 [公式キャラクターズブック 参ノ巻](https://books.shueisha.co.jp/items/contents.html?isbn=978-4-8342-1723-0), 集英社, 原作 吾峠呼世晴, ©︎吾峠呼世晴/集英社・アニプレックス・ufotable  

##  先行事例
##  成果物
##  謝辞
本研究を進めるにあたり地球社会共生学部の古橋大地教授をはじめ多くの方々より多大な助言を賜りました。厚く感謝を申し上げます。  
##  2022年卒業論文提出用
##  発表用プレゼンテーション
