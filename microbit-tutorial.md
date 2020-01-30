# 最初の一歩


## Introduction @unplugged

```template
//
```

ボタンを押したらLEDが光る簡単なプログラムを作ってみましょう！

![](https://github.com/aoirohn/microbit-tutorial/blob/master/flashing_heart.gif?raw=true)

## Step 1 
### 最初のプログラム

micro:bitではこの画面でプログラミングをしていきます。


## Step 2 @fullscreen

左メニューから``||input:ボタンAが押されたとき||``を選択し、配置しましょう。

```blocks
input.onButtonPressed(Button.A, function () {
})
```
![](https://github.com/aoirohn/microbit-tutorial/blob/master/onPushButtonA.gif?raw=true)


## Step 2


```blocks
input.onButtonPressed(Button.A, function () {
    basic.showIcon(IconNames.Heart)
})
```


Congratulations, you did it!
