# Windowsへのインストールと起動方法

[<< 戻る](../)

## Anaconda のインストール、32bit版？64bit版？

まずは自分が使用している Windows が 32bit版であるか 64bit版 であるかの確認をしましょう。
以下の図を参考に、スタートボタンを右クリックし、表示されたメニューから「システム」をクリックします。
![img](assets/image16.png)




すると以下のようなウインドウが立ち上がるので、「システムの種類」という項目が「64 ビット」であるか「32 ビット」であるかを確認しておきましょう。
![img](assets/image10.png)





## Anaconda インストーラのダウンロード

Anaconda をインストールするためのファイル（インストーラと言います）をダウンロードします。
↓ こちらのページを開きましょう。
**[https://www.anaconda.com/products/individual](https://www.google.com/url?q=https://www.anaconda.com/products/individual&sa=D&ust=1599450832459000&usg=AOvVaw1dcpi8kcj4RMKCaPbnxaYk)**


下の方まで画面をスクロールするとダウンロードボタンが並んでいます。Windows 用の Python 3.8  のうち、**先ほどチェックしたビット数のものをダウンロードします**。
この際、かなりの容量をダウンロードするため、通信料やハードディスクの残り容量には気を付けてください。

![img](assets/image6.png)
![img](assets/image15.png)




## Anaconda のインストール

Anaconda のインストーラがダウンロード出来たら、実行して Anaconda をインストールします。
ダウンロードしたファイルは「ダウンロード」フォルダに保存されているはずですので、ダウンロードフォルダを開いてみましょう。
ダウンロードフォルダを開くには様々な方法がありますが、分からない場合は以下を試してみてください。


**ダウンロードフォルダの開き方**

タスクバーにフォルダっぽいアイコンがあるかと思いますので、クリックしましょう。 ![img](assets/image20.png)

エクスプローラーが開くので、下図を参考にしてダウンロードフォルダを開きましょう。 
![img](assets/image19.png) 



ダウンロードフォルダには先ほどダウンロードしたファイルがあるかと思いますので、ダブルクリックしてインストールを開始しましょう。
![img](assets/image13.png)




以下、インストールの流れになります。

![img](assets/image9.png)
Next をクリック。



![img](assets/image18.png)
I Agree をクリック。



![img](assets/image3.png)
Next をクリック。



![img](assets/image11.png)
Next をクリック。



![img](assets/image12.png)
Install をクリック。



![img](assets/image21.png)
インストールには多少時間がかかります･･･



![img](assets/image8.png)
Next をクリック。



![img](assets/image5.png)
Next をクリック。



![img](assets/image2.png)
チェックを外し、Finish をクリック。



これでインストールは完了です。



## Spyderを立ち上げてみよう


Anaconda のインストールが無事に終了したら、早速 Spyder を立ち上げてみましょう。
まずは以下のように操作し、Anaconda を立ち上げます。




スタートボタンをクリックすると、スタートメニューが表示されます。
スタートメニュー左側で「Anaconda3 (〇-bit)」の中にある「Anaconda Navigator (Anaconda3)」をクリックします。
![img](assets/image17.png)




しばらくすると Anaconda-Navigator が立ち上がります。
Anaconda-Navigator が起動する際に以下のような表示が出た場合は「OK, and don’t show again」をクリックしておきましょう。
![img](assets/image1.png)





続いて Spyder を立ち上げます。
パネルがたくさん並んでいますので、「Spyder」のパネルを探し、「Launch」ボタンをクリックしてください。
![img](assets/image14.png)



しばらくすると以下のような Spyder のウインドウが立ち上がります。

![img](assets/image7.png)

画面の左側は「エディタ」と呼び、 Python の命令（コード）を入力します。
画面右側上段は「変数エクスプローラー」「ヘルプ」「プロット」「ファイル」を選択して表示させることが出来ます。「変数エクスプローラー」を選択しておきましょう。
画面右側下段は「コンソール」と呼ばれ、プログラムの実行結果やエラーメッセージなどが表示されます。



もし以下のようなメッセージが表示されたら、とりあえず無視を選択しておきましょう。
![img](assets/image4.png)



また、もし以下のようなメッセージが表示されたら、とりあえずOKをクリックしておきましょう。
そして、<span style="color:#ff0000">**アップデートはしないでおきましょう！**</span>
Spyder 5.0.0 は動作が不安定、という情報がありました。ですので、インストールした状態（おそらくSpyder 4.1.5）のままで学習を進めましょう。
![img](assets/update.png)



[<< 戻る](../)