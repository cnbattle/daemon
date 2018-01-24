如何使用？

建立一个文件里面是你需要守护的进程执行语句比如`bone.txt`,内容如下

```
python /home/rowland/pyspace/myweb.py -p 8800
python /home/rowland/pyspace/myweb.py -p 8801
python /home/rowland/pyspace/myweb.py -p 8802
```
然后 `./daemon.sh bone.txt`
