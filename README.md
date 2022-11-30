# try jupyter-widgets

[Jupyter Widgets](https://github.com/jupyter-widgets/ipywidgets)を試す。

- github: <https://github.com/jupyter-widgets/ipywidgets>
- documents: <https://ipywidgets.readthedocs.io/en/latest/index.html>

## 環境構築

- clone this repository
- build & run container

```bash
docker-compose up --build
```

jupyterlabが自動で立ち上がるので、docker-composeに設定するport番号(8066)で繋がる。

<http://localhost:8066>

- attach container

```bash
docker-compose exec tok-base bash
```

- down & remove container

```bash
docker-compose down
```
