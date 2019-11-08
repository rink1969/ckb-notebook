# ckb notebook
ckb上Dapp开发的集成环境。

基于[jupyter lab](https://jupyterlab.readthedocs.io/en/stable/)。

### 依赖的python库

python rpc库

```
pip install tinyrpc
```

python数据分析库 [doc](https://www.pypandas.cn/docs/getting_started/10min.html)

```
pip install pandas
```

python可视化库 [doc](https://www.runoob.com/w3cnote/matplotlib-tutorial.html)

```
pip install matplotlib
```

z3库 [doc](https://arabelatso.github.io/2018/06/14/Z3%20API%20in%20Python/)

```
pip install z3-solver
```

Datalog库 [doc](https://blog.csdn.net/blmoistawinde/article/details/80864711)

```
pip install pyDatalog
```

ORM库 [doc](https://www.osgeo.cn/sqlalchemy/orm/tutorial.html)

```
pip install sqlalchemy
```

### 其他依赖

- [ckb](https://github.com/nervosnetwork/ckb)
- [ckb-rpc-wrapper](https://github.com/rink1969/ckb-rpc-wrapper)
- [riscv-toolchain](https://github.com/nervosnetwork/ckb-riscv-gnu-toolchain)
- [sqlite3](https://www.sqlite.org)

### 运行

1. 运行ckb节点。
2. 运行ckb-rpc-wrapper。
3. 在当前目录下运行jupyter lab。

### 模块介绍

demo.ipynb 是一些python库用法的简单示例

always.ipynb 是always sucess的示例。

