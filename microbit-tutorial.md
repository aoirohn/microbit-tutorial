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


## Step 2 @unplugged

左メニューから``||basic:アイコンを表示||``を選択し、配置しましょう。


![](https://github.com/aoirohn/microbit-tutorial/blob/master/showIcon.gif?raw=true)



## Step 2

左メニューから``||basic:アイコンを表示||``を選択し、配置しましょう。



```blocks
input.onButtonPressed(Button.A, function () {
    basic.showIcon(IconNames.Heart)
})
```



```ghost
basic.showLeds(`
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        . . . . .`);
```

## Step 3 @unplugged

### 画面が消えるようにしましょう

左メニューの``||basic:基本||``をクリックしたらその下の``||basic:・・・||``を押しましょう

メニューから``||basic:画面を消す||``を選択し、配置しましょう。


![](https://github.com/aoirohn/microbit-tutorial/blob/master/clearScreen.gif?raw=true)


## Step 3

### 画面が消えるようにしましょう

左メニューの``||basic:基本||``をクリックしたらその下の``||basic:・・・||``を押しましょう

メニューから``||basic:画面を消す||``を選択し、配置しましょう。

```blocks
input.onButtonPressed(Button.A, function () {
    basic.showIcon(IconNames.Heart)
    basic.clearScreen()
})
```

## Step 4

完成です！画面左のシミュレーターの``|Aボタン|``を押してみましょう


## Step 5 @unplugged @tutorialCompleted

うまく動きましたか？これでプログラムは完成です。

次はプログラムをmicro:bitに転送について解説します。

```blocks
input.onButtonPressed(Button.A, function () {
    basic.showIcon(IconNames.Heart)
    basic.clearScreen()
})
```