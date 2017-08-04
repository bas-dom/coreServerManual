# 安装python环境

1. 安装python3.4 win32版本

2. 安装pywin32-220.win32-py3.4.exe（core/pySite/setup目录）

3. 安装mysql-connector-python（core/pySite/setup目录里解压mysql-connector驱动包）

```
python setup.py install
```

1. 安装所需要的库

```
pip install pymongo
pip install flask
pip install tablib
```

# 启动web服务引擎

* 在core/pySite目录下，通过命令行 python runEngine.py 即可启动引擎



