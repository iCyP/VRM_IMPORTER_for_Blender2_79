# MIT　license　
# Draco圧縮 非 対 応 (Draco complessed data is unsupported)
# Blender2.80向けはこっち (for Blender2.8 is below)
https://github.com/iCyP/VRM_IMPORTER_for_Blender2_8
# 注意
## インポートボタン押したら固まったんだけど？？？
 - インポートには数十秒程度かかります。しばらく待ってみてください。
## 雰囲気でｲﾝﾎﾟｰﾄしたので、間違いがあります。
## 変更禁止(CC_ND)VRMは弾く" 仕様 "です悪しからず。
## attention! for comers from other addon's notice.
 - This addon is independent project from other addons. 
## インストール方法
 - そこの右上の緑のボタンを押してZIP Download
 ｰ blender->User preference->addon -> addon installで先に落としたZipを選ぶ
 - おわり
## つかいかた
 - menubar->File->import->VRM
 - select relational object(armature,meshes) menubar->File->export->VRM
 - export require setting text file in blender text editor, metas in custum propaty in armature object and humanbone custom propaties and, so on.
## 既知の不具合　
 - マテリアルがおかしい->blender2.8が出たら本気だす(直すとは言ってない)


## 機能説明
### 出来ること
 - VRMをそれっぽくBlenderにimportできる
 - VRM内すべてのテクスチャを(インポートするうえで必要に迫られて)VRMと同じフォルダに書き出す。
    - 同じフォルダ以外も要望があれば、個人的開発ポリシーに反しない範囲で実装可能
    - ※すでに*同名のテクスチャがある場合、上書きしない*ようになっているので、注意してください。(不慮の上書き防止の仕様です)
### 出来ないこと
 - VRMのマテリアルをカンペキにBlenderにimportする
 - その他私の想定外なモデルのimport

- memo:実はExport、出来るとか出来ないとか、でもﾌﾙｽｸﾗｯﾁからはかーーなり難しいんじゃないかな。
