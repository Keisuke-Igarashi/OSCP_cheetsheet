# 環境変数

### 参照

```bash
env
echo $PATH
```



### 定義

```bash
export b=10.11.1.220
ping -c 2 $b
```

* export コマンドは、現在の Bash インスタンスから生成される可能性のあるすべてのサブプロセスから、その変数にアクセスできるようにする

* export なしで環境変数を設定した場合、現在のシェルでのみ利用可能



### 現在のシェルのインスタンスのプロセスID

```
echo "$$"
```



## PATHの設定

```bash
export PATH=$PATH:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

