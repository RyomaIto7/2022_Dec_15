# 第11回振り返り

## GitHubアカウント
| 氏名           | 学籍番号    | 
| -------------- | ----------- | 
| 伊藤涼真    | K21013      | 

## 担当箇所　　
今回の自分は、画像処理の一部機能である人の顔を検出したら枠で加工プログラムを作成した。作業内容としては。まずgithubで顔検出のできるxmlファイルをダウンロードし、それをpythonのプログラムの中で顔検出のできる関数として使用できるようにし、main関数等で呼び出された際に動作する。

## チーム作業ログ
<pre>
* commit e86e2a7bb37187dd7024b7025217c45ef50323c4 (HEAD -> ryoma_image_processing_facecheck, origin/ryoma_image_processing_facecheck)
| Author: RyomaIto7 <k21013kk@aitech.ac.jp>
| Date:   Thu Dec 15 16:28:12 2022 +0900
| 
|     Create face_cascade.py
| 
* commit b65a3f5136bc2dc411aa73506f6812966cfd8026
| Author: RyomaIto7 <k21013kk@aitech.ac.jp>
| Date:   Thu Dec 15 16:28:04 2022 +0900
| 
|     change
| 
* commit 8a007351279997aeb33762ef2c2ed32b2146dbe5
| Author: RyomaIto7 <k21013kk@aitech.ac.jp>
| Date:   Thu Dec 15 15:51:15 2022 +0900
| 
|     change file name
| 
* commit 5de1122db973d148be59ffcf726c2cd274362a65
| Author: RyomaIto7 <k21013kk@aitech.ac.jp>
| Date:   Thu Dec 15 15:47:51 2022 +0900
| 
|     restore
| 
* commit 40b06427d0a00d0c8213d8e4547690d7923f0ed8
| Author: RyomaIto7 <k21013kk@aitech.ac.jp>
| Date:   Thu Dec 15 15:44:08 2022 +0900
| 
|     a
| 
* commit f33034c09383a64cdd58175ccb0776cb61f1a716
| Author: RyomaIto7 <k21013kk@aitech.ac.jp>
| Date:   Thu Dec 15 15:24:49 2022 +0900
| 
|     fin
| 
* commit 1823d7ae96c0e7bf50d37eb526c080c9e5534247
| Author: RyomaIto7 <k21013kk@aitech.ac.jp>
| Date:   Thu Dec 15 15:21:45 2022 +0900
| 
|     add debug comment
| 
* commit 150539df43d590e944ecd6df71c0ec13160376db
| Author: RyomaIto7 <k21013kk@aitech.ac.jp>
| Date:   Thu Dec 15 15:20:48 2022 +0900
| 
|     add comment
| 
* commit a97607cdb11404748bec76a4a86bd135377eb4d9
| Author: RyomaIto7 <k21013kk@aitech.ac.jp>
| Date:   Thu Dec 15 15:18:07 2022 +0900
| 
|     顔検出　作成
|     
|     画像の取り込み場所と
|     出力場所を任意の場所に変更して使用
|   
*   commit 9ea23c7a4c6996da30a662a787fea728373b1c87
|\  Merge: bd26562 4388769
| | Author: Nk777 <111414009+Nk777777@users.noreply.github.com>
| | Date:   Thu Dec 15 14:52:52 2022 +0900
| | 
| |     Merge pull request #2 from 2022AIT-OOP2-G08/WEB
| |     
| |     Web
| | 
| * commit 438876969c652457adab69acd5960699d810ee46
| | Author: u-ryusei <k20233kk@aitech.ac.jp>
| | Date:   Thu Dec 15 14:52:04 2022 +0900
| | 
| |     web
| |   
| *   commit 247a2ff13a9281cb39fe81d6281b350ec88a64a6
| |\  Merge: 833084a aece11b
| | | Author: u-ryusei <k20233kk@aitech.ac.jp>
| | | Date:   Thu Dec 15 14:50:12 2022 +0900
| | | 
| | |     Update nomal~aece11b62b439ae10409dcb8f520d747cd3e2a32
| | | 
| | * commit aece11b62b439ae10409dcb8f520d747cd3e2a32
| | | Author: Uno <105477076+u-ryusei@users.noreply.github.com>
| | | Date:   Thu Dec 15 14:42:59 2022 +0900
| | | 
| | |     Create nomal
| | | 
| * | commit 833084a0eb43c8f1b4aab596f3e9c7c5d38ab744
| | | Author: u-ryusei <k20233kk@aitech.ac.jp>
| | | Date:   Thu Dec 15 14:49:05 2022 +0900
| | | 
| | |     web
| | | 
| * | commit 39dceac7e74c14920a713f4bee5118619966cfab
| |/  Author: u-ryusei <k20233kk@aitech.ac.jp>
| |   Date:   Thu Dec 15 14:48:01 2022 +0900
| |   
| |       toppage
| | 
| * commit 73d069fcbd17e2e535971a1354d2d434a94c1480
| | Author: u-ryusei <k20233kk@aitech.ac.jp>
| | Date:   Thu Dec 15 14:20:32 2022 +0900
| | 
| |     web
| | 
| * commit 563578024cf0554af669dd43fdc4ab2e948af792
| | Author: u-ryusei <k20233kk@aitech.ac.jp>
| | Date:   Thu Dec 15 14:20:23 2022 +0900
| | 
| |     web
| | 
| * commit ce593d5e72af27beac85c2d24c90ad8c3f28ea88
| | Author: u-ryusei <k20233kk@aitech.ac.jp>
| | Date:   Thu Dec 15 14:18:31 2022 +0900
| | 
| |     web
| | 
| * commit 019059f7c2bc47260954f2aef523417bff8dd112
|/  Author: u-ryusei <k20233kk@aitech.ac.jp>
|   Date:   Thu Dec 15 14:05:05 2022 +0900
|   
|       ファイル構造
| 
* commit bd2656294478db25864c50e232133b9ddeb0b0a5
  Author: Nk777 <111414009+Nk777777@users.noreply.github.com>
  Date:   Thu Dec 15 13:54:40 2022 +0900
  
      Initial commit
</pre>

## 感想
今回の授業で共同作業の便利な点・不便な点がわかった。
まず、良い点だが、やはり共同で作業するということで、自分の得意不得意を生かしながら人に頼って、自分のスキルアップにつなげられるのは大きく感じる。一方で悪い点だが、やはりお互いの意志の伝達という部分だ。今回の課題だと、画像処理の機能の実装で関数をmainの中で使えるようにすればよいのか、自分でその機能を直接実装できるようにするのかで分かれていたり、プログラム名をどうするかや、途中での連絡をうまく伝達できていなかったなどのコミュニケーションエラーでうまく実装できなかった。
これからのプログラム開発に向けてそこはうまく解消できる方法を模索する必要がある。
