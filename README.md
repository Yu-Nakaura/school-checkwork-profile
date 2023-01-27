# school-checkwork-profile

## Lv.1 好きな写真を表示させよう
自分のプロフィールを作成しよう。。

### ・完成後アプリのキャプチャ画像

<img src="https://user-images.githubusercontent.com/112265560/215035633-f31ca356-6ee5-4522-a1cf-39ba85b563c5.png" width="320px">


### ・手順
0. Data Bindingの設定をしよう

##### エレメントの配置
1. `ImageView`を配置して、`profile_image`と設定しよう。自分の好きな写真を設定してね。
2. `TextView`を配置して、`profile_label_text`と設定しよう。textには "名前"といれてね。

##### レイアウトの設定
3. `ConstraintLayout`に変更しよう。
4. キャプチャ画像を見て並べよう。
5. `profile_image`が中央ぞろえになるように設定しよう。

		（ヒント）"scaleType"で調べてみよう
6. `profile_image`の`layout_width`を`0dp`に、`layout_height`を`wrap_content`に設定しよう。
7. 制約を付けよう。左右は`parent`と結びつけて、上下は対象の上下に位置するエレメントに結び付けよう。
8. マージンを付けてきれいに並べよう。
		
### ・サンプルコード
[Lv.1 のコード](https://github.com/Yu-Nakaura/school-checkwork-profile1)


## Lv.2 ボタンを追加しよう
ボタンを追加してテキストの色を変えてみよう。

### ・完成後アプリのキャプチャ動画

<img src="https://user-images.githubusercontent.com/112265560/215035633-f31ca356-6ee5-4522-a1cf-39ba85b563c5.png" width="320px">


### ・手順
1. `Button`を配置して、`change_color_button`と設定しよう。textには "色を変える"といれてね。
