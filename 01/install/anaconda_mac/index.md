# Mac へのインストールと起動方法

[<< 戻る](../)

## Anaconda インストーラのダウンロード

Anaconda をインストールするためのファイル（インストーラと言います）をダウンロードします。
↓ こちらのページを開きましょう。
**[https://www.anaconda.com/products/individual](https://www.google.com/url?q=https://www.anaconda.com/products/individual&sa=D&ust=1599674854553000&usg=AOvVaw2kk1sZ9WfmyqVmYTO4TH0F)**


下の方まで画面をスクロールするとダウンロードボタンが並んでいます。MacOS 用の Python 3.8  のうち、Graphical Installer の方をダウンロードします。
この際、かなりの容量をダウンロードするため、通信料やハードディスクの残り容量には気を付けてください。
![img](assets/image20.png)



## Anaconda のインストール

Anaconda のインストーラがダウンロード出来たら、実行して Anaconda をインストールします。
ダウンロードしたファイルは「ダウンロード」フォルダに保存されているはずですので、ダウンロードフォルダを開いてみましょう。


**ダウンロードフォルダの開き方**

Dock に Finder のアイコン ![img](assets/image7.png) があると思い間ますので、クリックします。  Finder のウインドウが開くので、左の一覧から「ダウンロード」を探し、クリックします。 ![img](assets/image2.png) 



ダウンロードフォルダには先ほどダウンロードしたファイルがあるかと思いますので、ダブルクリックしてインストールを開始しましょう。


以下、インストールの流れになります。

![img](assets/image17.png)
続ける をクリック



![img](assets/image16.png)
続ける をクリック



![img](assets/image10.png)
続ける をクリック



![img](assets/image3.png)
続ける をクリック



![img](assets/image12.png)
同意する をクリック



![img](assets/image25.png)
インストール をクリック



![img](assets/image23.png)
インストールが進んでいきます



![img](assets/image4.png)
途中で何かの警告が出た場合は OK をクリック



![img](assets/image5.png)
続ける をクリック



![img](assets/image24.png)
閉じる をクリック



![img](assets/image11.png)
ゴミ箱に入れる をクリック




これでインストールは完了です。



## Spyderを立ち上げてみよう


Anaconda のインストールが無事に終了したら、早速 Spyder を立ち上げてみましょう。
まずは以下のように操作し、Anaconda を立ち上げます。

Dock に Finder のアイコン ![img](assets/image7.png) があると思いますので、クリックします。

Finder のウインドウが開くので、アプリケーション → Anaconda-Navigator を探し、ダブルクリックします。
![img](assets/image6.png)



Anaconda-Navigator が起動する際に以下のような表示が出た場合は「OK, and don’t show again」をクリックしておきましょう。
![img](assets/image1.png)





続いて Spyder を立ち上げます。
パネルがたくさん並んでいますので、「Spyder」のパネルを探し、「Launch」ボタンをクリックしてください。
![img](assets/image14.png)



しばらくすると Spyder のウインドウが立ち上がるのですが… 最初の立ち上げの際にはいくつかのメッセージが表示されるかと思います。
その場合は以下のように対応しておいてください。

| ![img](assets/image18.png) | このようなメッセージが何度か表示される場合があります。OKをクリックしておいてください。 |
| -------------------------- | ------------------------------------------------------------ |
| ![img](assets/image21.png) | インストールしてください。                                   |
| ![img](assets/image13.png) | Spyderをアップデートできますよ！というメッセージです。 おそらく2021年４月現在では「バージョン 5.0.0 にアップデートできます！」と表示されるはずですが、<span style="color:#ff0000">**今はアップデートしないでください。** </span>（バージョン 5.0.0 は動作が不安定という情報があります） |
| ![img](assets/image8.png)  | インストールしてもよいようですが、とりあえずは無視（Dismiss）をクリックしておいてください。 |



そしてこちらが Spyder の画面になります。

![img](assets/image22.png)

画面の左側は「エディタ」と呼び、 Python の命令（コード）を入力します。
画面右側上段は「変数エクスプローラー」「ヘルプ」「プロット」「ファイル」を選択して表示させることが出来ます。「変数エクスプローラー」を選択しておきましょう。
画面右側下段は「コンソール」と呼ばれ、プログラムの実行結果やエラーメッセージなどが表示されます。



## 日本語化

Mac版の Spyder は、最初はおそらく英語表記になっていると思います。
以下の手順で日本語表記にしておきましょう（英語がいい人はそのままでOKです）。


まず、Spyder の画面上部にある工具アアイコン ![img](assets/image9.png) をクリックします。

すると設定ウインドウが開くので、右側の「Advanced settings タブ」で Language を日本語にし、OKをクリックします。
![img](assets/image19.png)



「Spyder を再起動してね」というメッセージが表示されるので、Yesをクリックします。
![img](assets/image15.png)


以上で日本語化が出来たと思います。



[<< 戻る](../)