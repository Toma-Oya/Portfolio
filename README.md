# 概要
私、大家東磨の、3DCGとプログラムそれぞれの制作実績/ポートフォリオに関するリンクと説明です。  


# 3DCG
## 1. VRChatのアバター用衣装制作
[![VRC衣装](VRC衣装サムネ.png)](https://drive.google.com/file/d/1PvcltmsdTsZ4jgreywAVsJfourBGoYA9/view?usp=sharing)

VRChatというVRメタバース用の服の3Dモデルを制作・販売しました。  
blender, Unity, Substance Painter, CLIP STUDIOを用いて制作しております。  

通常、オーバーサイズの服は動いたときの破綻が大きいのですが、補助ボーンやConstraintなどの技術を用いて、動いたときにも破綻しないようにこだわりました。
  
詳細な作品紹介は、以下のリンクよりご確認ください。  
URL：https://drive.google.com/file/d/1PvcltmsdTsZ4jgreywAVsJfourBGoYA9/view?usp=sharing  


[BOOTH](https://slumberhalo.booth.pm/)で販売し、合計350着/35万円ほどの売上をあげております。  

# Program
## 1. 「色彩の魔法旅人 ～消えゆくカフェテラスを救え～」

[![色彩の魔法旅人](https://github.com/user-attachments/assets/0b50f0cf-bc25-4c4a-8f02-afdbf0474b29)](https://www.youtube.com/watch?v=yM_qg7yoPB0 "色彩の魔法旅人　動画")

私がリーダーとなって研究室のメンバーと制作した、VR/ARを用いたインタラクティブ作品です。  
絵画の中の世界に入り込み、その中の物体を触る体験が実現できたら、それはとても面白いものになるのではないか、というコンセプトで制作しております。  

企画書での審査が通り、[IVRC](https://ivrc.net/2024/seed-stage/)というVR学会の中で行われるコンテストにて展示いたしました。  

私の担当箇所は主に
- 専用シェーダーの作成  
- ハンドトラッキングによる色塗り機能の実装
です。

担当箇所の詳細と企画書は以下の通りです。  
### シェーダー制作 / https://github.com/kusumi-bell/VertexColorShader
  
  絵画の中の世界を再現するために、マスク画像を用いることで、筆で描いたような見た目になるようにこだわりました。  
  ![制作シェーダー](https://github.com/user-attachments/assets/0a010147-517f-4b1d-ab67-aca1f9afebd5)


### ハンドトラッキングによる色塗り機能のスクリプト / https://github.com/Toma-Oya/VRVertexPaintTool
  
  VRの没入感を損なわないように、コントローラーではなくハンドトラッキングによる指差しで色を塗れるようにこだわりました。
  
  https://github.com/user-attachments/assets/a899c156-bb6c-453e-a6fc-de181b4b0887
  
### 企画書 / https://drive.google.com/file/d/1Qru-UomTy6KaUvn0YxK4uPeqoPtsH-8S/view?usp=sharing


## 2. [UnusedBoneRemover](https://github.com/Toma-Oya/UnusedBoneRemover)
![UnusedBoneRemover](UnusedBoneRemover.gif)

私が制作したblenderのアドオンです。  
上記の衣装作成の際に手間だった、アバターの不必要なボーンの削除を効率化するために制作いたしました。  


以下のリンクで配布しており、詳細が確認可能です。  
URL：https://github.com/Toma-Oya/UnusedBoneRemover

## 3. CheckerBoardCalibration

卒業研究で必要となったため、チェッカーボードとカメラの位置・角度の関係を取得するプログラムを、C#とOpenCVを用いて制作しました。 

以下のリンクにコードをのせてあります。  
URL：https://github.com/kusumi-bell/CheckerBoardCalibration


## 4. ピッチシフター
![ピッチシフター](https://github.com/user-attachments/assets/884f74f4-8fd5-4657-8afb-aeba1a730354)

大学の電子工作の授業において、ハードウェア・ソフトウェアともに自作でピッチシフターを作りました。  
PICマイコンにC言語で制作したソフトウェアを焼きこんで制作しております。  
アナログ入出力ではなくステレオ入出力ができるように、回路の増設やスクリプトの最適化をしてこだわりました。  

電子通信作品デザインコンテストという電子工作のコンテストに提出し、敢闘賞/賞金1万円を受賞しました。
