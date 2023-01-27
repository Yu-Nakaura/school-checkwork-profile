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
3. `TextView`を配置して、`profile_comment_text`と設定しよう。textには 自己紹介を書いてね。

##### レイアウトの設定
4. `ConstraintLayout`に変更しよう。
5. キャプチャ画像を見て並べよう。
6. `profile_image`が中央ぞろえになるように設定しよう。

		（ヒント）"scaleType"で調べてみよう
7. `profile_image`の`layout_width`を`0dp`に、`layout_height`を`wrap_content`に設定しよう。
8. 制約を付けよう。左右は`parent`と結びつけて、上下は対象の上下に位置するエレメントに結び付けよう。
9. マージンを付けてきれいに並べよう。
		
### ・サンプルコード
[Lv.1 のコード](https://github.com/Yu-Nakaura/school-checkwork-profile1)


## Lv.2 ボタンを追加しよう
ボタンを追加してテキストの色を変えてみよう。

### ・完成後アプリのキャプチャ動画

https://user-images.githubusercontent.com/112265560/215043412-641cc7be-a3e4-4489-9ca7-509dd8b5ec0f.mp4

### ・手順
1. `Button`を配置して、`change_color_button`と設定しよう。textには "色を変える"といれてね。
2. `change_color_button`が一番下に来るように配置して、制約・マージンを付けてきれいに並べよう。
3. ボタンの色を変えてみよう。
4. `MainActivity.kt`で、ボタンを押したときの挙動を書いていこう。今回は、`change_color_button`を押したら`profile_comment_text`の色が変わるようにしよう。

### ・サンプルコード
[Lv.2 のコード](https://github.com/Yu-Nakaura/school-checkwork-profile2)
