# svn-storage

svn-storage コンテナの使用方法 mysqlサーバのデータ保持用コンテナになります。

## 1.git clone

```sh
mkdir work && cd $_
git clone git@github.com:hidetarou2013/svn-storage.git
```

## 2.docker build

```sh
cd svn-storage
docker build -t hidetarou2013/svn-storage .
```

## 3.docker create

```sh
docker create --name svn-storage hidetarou2013/svn-storage
```

