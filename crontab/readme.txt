1. 创建crontab工作目录/home/prod/workspace/crontab, 以下文件和目录都在crontab下创建
2. 创建config目录, 在config下创建config.json文件, 用于存储定时任务配置
3. 创建Dockerfile文件, 安装了curl的crontab
4. 构建Dockerfile, docker build -t willfarrell/crontab-curl .
5. 创建docker-compose.yaml文件
6. docker-compose up -d
