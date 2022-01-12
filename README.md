# 課題２　　
ロボットシステム学課題２で作成  
  
# 動作環境  
ラズベリーパイ３  
ubuntu 20.04  
  
# 実行方法   
$ cd catkin_ws/src  
$ git clone git@github.com:my9918/ros.git  
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
  
    
# ライセンス  
BSD 3-Clause Licence  




