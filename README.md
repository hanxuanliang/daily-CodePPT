# daily-CodePPT

## jupyter notebooks

用使 RISE 制作的 notebooks 演讲稿。你可以用 jupyter 打开 ipynb 文件来查看。 只在python3.6及一上（本机现在是3.7.1） 下测试过。

## usage

```
python3 -m pip install jupyter    # or python -m pip install jupyter

pip install RISE    # https://github.com/damianavila/RISE
jupyter-nbextension install rise --py --sys-prefix
jupyter-nbextension enable rise --py --sys-prefix

jupyter notebook    # 换到切项目根目录下执行
```

> 可能会出现什么flake8的什么错误（也不知道是不是错误），更新flake即可没有错误出现 但是我直接更新了python的版本（个人可能有强迫症）

## nodeppt 

感觉python的环境在学校的电脑里面有点繁琐，所以采取ndoeppt

也是采用的markdown模式编写，所以写起来和RISE的感觉是差不多的

## usage

```
npm i -g nodeppt  // 当然你是需要安装node的

nodeppt -v  // 检查一下nodeppt是否安装好，可能会出现问题，后面讲

nodeppt start -h  // 获取帮助，常见的操作可以看到

nodeppt start -p <port>   // 在指定的端口开启

部署的工作就这么多
```

> 我在安装nodeppt就出现了```'nodeppt'不是内部命令```，所以在想难道这个也要放到环境变量里面？然后我试了一下````yarn add ...``，发现也用不了（我是新安装的node），所以推测是要把node全局安装的包放到环境变量里面。尝试之后，发现还真成功了。

### 更多关于nodeppt的操作
* https://github.com/ksky521/nodeppt