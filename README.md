# myled
ロボットシステム学　課題１　16C1054　小関優
# 概要
与えた入力の数字(0~2)と同じ数のLEDが点灯します。
0を入力すると全て消灯します。
# ライセンス
This repository is licensed under the GPLv3 license, see LICENSE.
# 方法
    $ make  
    $ sudo insmod myled.ko  
    $ sudo chmod 666 /dev/myled0  
    $ echo [0∼2] > /dev/myled0  
# 動画URL
https://youtu.be/fNXWkI1u2i0
