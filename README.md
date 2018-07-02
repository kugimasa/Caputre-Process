# Caputre-Process
## Report2

* OpenCV等でカメラ画像を取得して処理するコードをかく
   * GUIでパラメータをインタラクティブに変える
* 実装する処理
  * トーンカーブでコントラスト変更
  * カラー（色調）を変更
  * フィルタリング
---
## 実装した処理
* S字カーブの中心点をトラックバーによって移動していき, そのS字カーブをplt.plotでインタラクティブに表示させる. そのS字カーブを用いてコントラストを変更する処理.
情報工学演習IIの画像処理のAzure Notebookを参考にした.

* RGBを操作できるトラックバーを用意してカラーを変更できるようにした.
[参考にしたページ](http://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_gui/py_trackbar/py_trackbar.html)

* グレースケール化する処理.
	* rgb2grayを用いた.

* フィルタリングについてはソーベルフィルタとプレウィットフィルタを選択して, エッジ検出をする処理を実装した. 
---
## 処理動画
[YouTubeリンク](https://youtu.be/gWm2RplSCYQ)