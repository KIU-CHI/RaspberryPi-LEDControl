# RaspberryPi-LEDControlDriver　　
https://www.youtube.com/watch?v=JGqg6cqyAB8　　
イベントタイマにより1秒周期でGPIO25をオン・オフさせます。  
echoコマンドからの入力で点滅と消灯を切り替えられます。

点滅開始：
"# echo 1 > /dev/myled0"  
点滅終了：
"# echo 0 > /dev/myled0"  
