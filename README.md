# whiteboard-old

该仓库用于归档 [whiteboard] 不再收纳的译文文档。

[whiteboard]: https://whiteboard-ui8.pages.dev/

## 如何在本地构建，预览

下载源码：

```
git clone https://github.com/poplar-at-twilight/whiteboard-old.git && cd whiteboard-old
```

创建容器：

```
python3 -m venv .venv
```

激活容器：

```
source .venv/bin/activate
```

对于 Windows 用户，则可在 Powershell 输入绝对路径，运行 `.venv/Script` 文件夹下的 `activate.bat` 脚本：

```
[脚本的绝对路径]\.venv\Scripts\activate.bat

#例如 D:\Myfile\documents\git\whiteboard-old\.venv\Scripts\activate.bat
```

安装依赖：

```
pip install mkdocs mkdocs-material mkdocs-rss-plugin
```

运行服务：

```
mkdocs serve
```

然后你就会在 <http://127.0.0.1:8000/> 看到站点预览。

更新依赖：

```
python.exe -m pip install --upgrade pip
```

```
pip install --upgrade mkdocs mkdocs-material mkdocs-rss-plugin
```