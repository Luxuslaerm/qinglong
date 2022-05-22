# 启动容器

```bash
cd /mnt/mmcblk2p4
mkdir qinglong && cd qinglong
wget https://raw.githubusercontent.com/Luxuslaerm/qinglong/main/2.10.13/docker-compose.yml
wget https://raw.githubusercontent.com/Luxuslaerm/qinglong/main/lastest/docker-compose.yml

# 启动
docker-compose up -d
# 停止
docker-compose down
```
# 一键安装依赖
```bash
docker exec -it ql2 bash -c "$(curl -fsSL https://raw.githubusercontent.com/FlechazoPh/QLDependency/main/Shell/QLOneKeyDependency.sh | sh)"
```
