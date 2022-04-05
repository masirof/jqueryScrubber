# jqueryScrubber

jqueryでScrubberと言われる実装をしたプログラムです。  
index.html の scriptタグのdrag_master()が主な実装です。  
  
マウスを押す→マウスを押している間→マウスを離す  
の順に処理をしています。  
  
### マウスを押す
mouse_x にてマウスポインターのx座標を取得しています。  
is_mouse_down_number にてフラグを立てています。  
  
### マウスを押している間
ナンバーボックスの値の取得,変更  
移動した距離の計算 現時点のマウスの座標-過去のマウスの座標  
  
### マウスを離す
is_mouse_down_number　にてフラグを外しています。

## demo
https://masirof.github.io/jqueryScrubber/

