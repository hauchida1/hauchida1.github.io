# test

[< 戻る](../)





#### フローチャートを考える



#### エディタにコードを入力

![img](assets/newfile.png)
まず、Spyder の画面左上にある“新規ファイル”アイコンをクリックし、新しい Python ファイルを用意します。

![img](assets/savefile.png)
以下のコードを入力し、ファイルを保存アイコンをクリックして保存しましょう。今回は `.py` という名前で保存してみました。

```python

```



#### 実行

![img](assets/jikkou.png)
入力したら、画面上部の“ファイルを実行”アイコンをクリックしてみましょう。



#### 解説



#### 練習



<details class="md-text"><summary><u>→解答例を表示</u></summary><blockquote><span>
まずはフローチャートを考えてみましょう。
以下は「if」「elif」「else」を使った場合のフローチャートと、「if」だけを使って条件式に「and」を用いた場合の２通りのフローチャートの例です。
どちらでも実行結果は同じですが、この例の場合は and は使わずに書いた方がすっきりするかもしれません。
[![image-20210506144303659](assets/image-20210506144303659.png)](#)  [![image-20210506144336651](assets/image-20210506144336651.png)](#)
<br>このフローチャート（左）を元に、elif を使ってコードを書いていきます。
<pre><code class="python">print("身長(cm)を入力し、リターンキーを押してください。")
h = input()
f_h = float(h) \* 0.01                # h は str型なので、float型に変換。ついでにメートルに変換
print("体重を入力し、リターンキーを押してください。")
w = input()
f_w = float(w)                       # w は str型なので、float型に変換
<br>bmi = f_w / (f_h \* f_h)
print("BMI値は", bmi, "です。")
<br>if bmi < 18.5:
    print("痩せです。")
elif bmi < 25:
    print("普通です。")
else:
    print("肥満です。")</code></pre>
<hr></span></blockquote></details>




　

[< 戻る](../)