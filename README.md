# Get Started

# 总结

#### 准备工作

- 创建 Dockerfile 文件
- 创建 Dockeringnore 文件

#### 1. 构建一个镜像

```
  $  docker build -t <镜像名称> .
```

比如: ```docker build -t getting-started .```

### 2. 为镜像启动一个容器

``` 
docker run -dp 3000:3000 <镜像名称>
```

比如: ``` docker run -dp 3000:3000 getting-started ```

