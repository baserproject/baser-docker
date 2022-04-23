# Docker for baserCMS

baserCMS用のDockerコンテナのビルド用プロジェクト。

```shell
# コマンド例（M1対応）
docker buildx build --platform linux/amd64,linux/arm64 -t baserproject/basercms:php8.1 -f dockerfile/Dockerfile-php8.1 --push .
```
