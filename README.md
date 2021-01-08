# RoboSys_kadai2

2020 ロボットシステム学_課題2

### 概要
講義のサンプルコードを実行

### 動作環境
|||
|:--:|:--:|
| Raspberry Pi | Raspberry Pi Model 3B+ |
| OS | Ubuntu16.04 |

### インストール方法
・ワークスペースの作成
```
$ cd
$ mkdir -p catkin_ws/src
$ cd ~/catkin_ws/src
$ catkin_init_workspace
$ cd ~/catkin_ws
$ catkin_make
$ source ~/.bashrc
```

### 実行方法

```
端末１：$ roscore
端末２：$ chmod +x count.py
端末２：$ rosrun mypkg count.py
端末３：$ rostopic echo /count_up
端末３：Ctrl + c
端末３：$ rosrun mypkg twice.py
端末４：$ rostopic echo /twice
```

### 動画のリンク
