# practice1
実行ファイル(Biliyard.exe)の操作方法は以下のようになります。

←,→:ショット方向を左右に動かす.
↑,↓:ショットのパワーの増減.
s:白球のショット.
a,d:白球を左右に動かす.
w,z:拡大、縮小.
マウスで右クリックしながらドラッグ:画面を回転する.
[ルール]
一人用のビリヤードです。右上に残りのボールの色が映っており,一番左のボールが次に当てるべきボールになります。
次に当てるべきボールに当たらなかった、または白球が落ちてしまった場合は白球が他のボールに当たらないランダムな位置に移動されます。

main.cppがメインファイルになります。
calc.cpp及びcalc.hppで衝突の計算や各座標の定義などを行っています。
main.cppファイルの中で一文字目が大文字のアルファベットで始まっている関数や変数はcalc.cppで定義されています。
CBall.hppはメインファイルで用いるボールのクラスなどを書いたものです。
Biliyard.zipファイルはプロジェクトを含めたファイル全てを圧縮したものです。
