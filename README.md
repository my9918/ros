# 課題２　　
ロボットシステム学課題２で作成  
rosの機能を使ってcount.pyからの信号をtwice.pyで２倍にしてさらに別の端末から結果を見るプログラム  
  
# 動作環境  
ラズベリーパイ３  
ubuntu 20.04  
  
# 実行方法   
$ cd catkin_ws/src  
$ git clone git@github.com:my9918/task_2.git
$ cd ..  
$ catkin_make  
  
１つ目の端末  
$ roscore  

２つ目の端末  
$ rosrun mypkg count.py  

３つ目の端末  
$ rosrun mypkg twice.py  

４つ目の端末  
$ rostopic echo twice  
  
# youtube  
https://youtu.be/_vu4hj5JDpY  
    
# ライセンス  
BSD 3-Clause Licence  
  
# 著者  
Masamitsu Yamazaki + Ryuichi Ueda




