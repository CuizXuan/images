# 选择基础镜像
FROM python:3.9

# 设置工作目录
WORKDIR /app

# 复制当前目录下的文件到容器内
COPY . /app

# 安装依赖
RUN pip install -r requirements.txt

# 启动命令
CMD ["python", "app.py"]
