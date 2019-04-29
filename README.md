


maven配置文件 添加镜像仓库的账号密码

# Builds to a container image registry.
$ mvn compile jib:build
# Builds to a Docker daemon.
$ mvn compile jib:dockerBuild

构建jar包用docker执行测试

docker hub
阿里云容器镜像
rancher