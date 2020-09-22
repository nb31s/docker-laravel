# laravel-docker
参考：https://qiita.com/ucan-lab/items/56c9dc3cf2e6762672f4

```
$ git clone git@github.com:ucan-lab/docker-laravel.git
$ cd docker-laravel
$ cp -p .env.example .env
$ make create-project # Install the latest Laravel project
(バージョン指定する場合は $ make create-project VERSION=6.* のようにする)
$ make install-recommend-packages # Not required
```
