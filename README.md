# dminima

有用的 Docker 命令
以下命令可以从服务器命令行运行，以最小用户身份登录。

查看日志：docker logs minima9001

停止最小值：docker stop minima9001

移除最小容器：docker rm minima9001

启动最小容器：docker start minima9001

重新启动最小容器：docker restart minima9001

列出所有容器（正在运行和已停止）：docker ps -a

列出容器（仅限运行）：docker ps

停止列出的容器：docker stop minima9001 minima8001 minima7001

删除列出的容器：docker rm minima9001 minima8001 minima7001

帮助：docker --help
