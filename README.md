# daily-CodePPT

My jupyter notebooks

用使 RISE 制作的 notebooks 演讲稿。你可以用 jupyter 打开 ipynb 文件来查看。
只在python3.6及一上（本机现在是3.7.1） 下测试过。

# usage

```
python3 -m pip install jupyter    # or python -m pip install jupyter

pip install RISE    # https://github.com/damianavila/RISE
jupyter-nbextension install rise --py --sys-prefix
jupyter-nbextension enable rise --py --sys-prefix

jupyter notebook    # 换到切项目根目录下执行
```

> 可能会出现什么flake8的什么错误（也不知道是不是错误），更新flake即可没有错误出现
但是我直接更新了python的版本（个人可能有强迫症）