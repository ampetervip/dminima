# dminima


Centos安装docker和minima一键脚本
wget https://raw.githubusercontent.com/ampetervip/dminima/main/m_vip.sh && chmod +x install-docker.sh && ./install-docker.sh


填加minima用户
sudo adduser minima

向最小用户授予 sudo（管理员）权限：
sudo usermod -aG sudo minima

将最小用户添加到 Docker 组：
sudo usermod -aG docker $USER

切换到最小用户：
su  minima


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
