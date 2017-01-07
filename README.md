# raspy_class
大学の課題

echo 5 > /dev/myled0
上のコマンドでLEDが５回光る

echo 1 > /dev/myled0
echo 0 > /dev/myled0

1でLEDが光り、カーネルコンソールに「LED ON」と出力される
0でLEDが消え、カーネルコンソールに「LED OFF」と出力される
