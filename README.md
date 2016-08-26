
# 各言語の REPL を式評価機にする

する。


# Usage

## サーバの起動

```
$ reploud server --repl irb
```

`--debug` オプションを付けると、動作の様子がわかる。


## サーバにコードを送る

```
$ reploud send 'Time.now'
=> 2016-08-26 20:08:34 +0900
```
