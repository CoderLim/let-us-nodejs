
## 生成子进程的四种方法

| 类型           | 回调／异常       | 进程类型 |   执行类型  | 可设置超时 |
| ------------- |:-------------:| -----:|:-------------:| -----:|
| spawn()       |       X       |  任意   |     命令     |   X   |
| exec()        |       V       |  任意   |     命令     |   V   |
| execFile()    |       X       |  任意   |   可执行文件  |   V   |
| fork()        |       V       |  Node  |    js文件    |   X   |

## 多个进程监听同一端口

RT，这才是重点，详情请参考《深入浅出Node.Js》- 朴灵编著