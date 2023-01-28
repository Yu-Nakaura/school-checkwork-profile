# プロフィールアプリのチェックワーク

## Lv.1 好きな写真を表示させよう
自分のプロフィールを作成しよう!

### ・完成後アプリのキャプチャ画像

<img src="https://user-images.githubusercontent.com/112265560/215035633-f31ca356-6ee5-4522-a1cf-39ba85b563c5.png" width="320px">


### ・手順
0. viewBindingの設定をして、自分の好きな画像を`profile_image`という名前で`res`の中の`drawable`にコピーしよう。

##### エレメントの配置
1. `ImageView`を配置して、`profile_image`と設定しよう。画像は`profile_image`を設定してね。
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
3. ボタンの色を好きな色に変えてみよう。
4. `MainActivity.kt`で、ボタンを押したときの挙動を書いていこう。今回は、`change_color_button`を押したら`profile_comment_text`の色が変わるようにしよう。

### ・サンプルコード
[Lv.2 のコード](https://github.com/Yu-Nakaura/school-checkwork-profile2)

## Lv.3 ボタンを追加しよう
ボタンを追加して画像とテキストを変えてみよう。

### ・完成後アプリのキャプチャ動画

https://user-images.githubusercontent.com/112265560/215053433-cc18e806-25fb-464e-aab3-1fd4a1365332.mp4

### ・手順
1. 好きな食べ物の画像をダウンロードして`food_image`という名前で`res`の中の`drawable`にコピーしよう。
2. `change_color_button`を`show_profile_button`に変更しよう。textは "名前"に変えよう。
3. `Button`を配置して、`show_food_button`と設定しよう。textには "好きな食べ物"といれてね。
4. `LinearLayout`の`horizontal`を追加して、`linear_layout`と設定しておこう。
5. `linear_layout`の中に`show_profile_button`と`show_food_button`を入れよう。
6. `linear_layout`が一番下に来るように配置して、制約・マージンを付けてきれいに並べよう。
7.  `MainActivity.kt`で、ボタンを押したときの挙動を書いていこう。まずは、`show_profile_button`を押したときに次の挙動が起こるようにしよう。
		
		ImageViewの`profile_image`に画像の`profile_image`が表示されるようにしよう。
		TextViewの`profileLabelText`が"名前"に代わるように使用。
		TextViewの`profileCommentText`が自己紹介に変わるようにしよう。
8. 次に、`show_food_button`を押したときに次の挙動が起こるようにしよう。
		
		ImageViewの`profile_image`に画像の`food_image`が表示されるようにしよう。
		TextViewの`profileLabelText`が"好きな食べ物"に代わるように使用。
		TextViewの`profileCommentText`が食べ物の説明に変わるように（好きに書いてね）

### ・サンプルコード
[Lv.3 のコード](https://github.com/Yu-Nakaura/school-checkwork-profile3)

## Lv.4 ボタンの色を変えよう
ボタンの色を変えて押されているボタンをわかりやすくしよう。

### ・完成後アプリのキャプチャ動画

https://user-images.githubusercontent.com/112265560/215054107-938c341a-0706-44b3-9b8a-94ab4b7df241.mp4

### ・手順
1. `activity_main.xml`で、`show_food_buton`の色を`グレー（#969696）`に設定しよう。
2. `MainAcivity.kt`で、ボタンを押したときの挙動を書いていこう。`show_profile_button`を押したときに、`show_profile_button`は好きな色に、`show_food_buton`は`グレー（rgb(150, 150, 150)）`に変わるようにしよう。
3. `show_food_button`を押したときに、`show_food_button`は好きな色に、`show_profile_buton`は`グレー（rgb(150, 150, 150)）`に変わるようにしよう。

### ・サンプルコード
[Lv.4 のコード](https://github.com/Yu-Nakaura/school-checkwork-profile4)

