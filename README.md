# SNI-detecter
## 用于发现SNI代理服务器
---
食用方法：
> python sni-detecter.py


> -i, --in 读入ip文件路径。默认为/task.txt
> -o, --out 测试通过ip的保存路径。默认为/passip+输出时间.txt。
> -p, --parallels [number] 默认线程数为20。
> -t, --timeout [float] 超时时间 单位为s 默认为2s。
> -h, --help 帮助。
> -m, 不输出检验失败ip。默认为输出。


input文件的格式
> 127.0.0.1-127.0.1.0
支持多行
