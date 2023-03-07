# 勉強座布団  ～集中までのワンクッション～

だらだらしている状態から勉強に集中するまでの過程をサポートしてくれる製品。  
いきなり集中の状態に至ることは難しく、「ワンクッション」置くことが重要。<br><br>
<img src="ワンクッション.jpg" width="500px">

### ＜製品の機能＞
#### 1. 設定した時間に勉強をしていなかった場合にブザーで警告をすることにより強制的にワンクッション置かせる機能
  技術的なハードル  
<br>
（ハード）  
・ブザーとの接続  
・座っている状態の判定  
<br>
（通信）  
・アプリからマイコンへのの通信  
・マイコンからアプリへの通信  

（ソフト）  
・タイマーの入力  
・タイマー機能の実装

#### 2. 勉強時間を可視化する 　
  技術的なハードル  
<br>
（ハード）  
・座っている状態の判定  

（通信）  
・「勉強開始」と「勉強終了」をソフトへ通信  

（ソフト）  
・マイコンから得たデータを保存  
・グラフによるデータの可視化  

#### 3. 勉強に集中できていない状態を感知
  技術的なハードル  
<br>
（ハード）  
・「勉強ているか否か」の新たなしきい値の設定による並行した判定。  

（通信）  
・ハードの情報をソフトに送信  

（ソフト）  
・送信されたデータを収集・表示  
（・休憩の提案の通知機能）  

#### 4. 休憩を提案・エクササイズの提案・たくさんほめる
  技術的なハードル  
<br>
（ハード）  
・なし  
・こちらで通知してもいいかも？

（通信）  
・なし  

（ソフト）  
・条件が達成された際の処理の追加  
