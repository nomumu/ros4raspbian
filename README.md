# ros4raspbian

## Description
Raspbianにインストール可能な32bitコンパイルしたROSパッケージです。   

## Requirement
Raspbianでのみ動作することを確認しています。
gdebiコマンドを使用するので事前にインストールして下さい。  
```
$ sudo apt-get update
$ sudo apt-get install gdebi -y
```

## Usage
リリースからダウンロードしたファイルを解凍しインストールして下さい。  
パッケージリストおよび各パッケージのライセンスはdebファイル内のcopyrightを参照して下さい。   

## Install
インストール手順例です。
```
$ unzip ros4raspbian-melodic-armhf-X.X.X.zip   
$ sudo gdebi ros4raspbian-melodic-armhf-X.X.X.deb   
$ rosdep update
```
