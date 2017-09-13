## 20170911
https://speakerd.s3.amazonaws.com/presentations/7f705ad5e31640b296d594dda8464928/presentation2.pdf
一通りやってみた結果
```
isucon@ubuntu-xenial:~/isucon6q$ ./isucon6q-bench -target http://127.0.0.1
2017/09/11 21:23:40 start pre-checking
2017/09/11 21:23:43 pre-check finished and start main benchmarking
2017/09/11 21:24:40 benchmarking finished
{"pass":true,"score":7179,"success":3079,"fail":3,"messages":["starがついていません (GET /)"]}
```

scoreが0ではなくなった。


## 20170913
isutarをisudaに移動してみた結果。
やっと10000点超えた。全然スピードあがらない。
```
isucon@ubuntu-xenial:~/isucon6q$ ./isucon6q-bench -target http://127.0.0.1
2017/09/13 16:09:45 start pre-checking
2017/09/13 16:09:47 pre-check finished and start main benchmarking
2017/09/13 16:10:45 benchmarking finished
{"pass":true,"score":10438,"success":4129,"fail":0,"messages":[]}
```

