# 镜像源配置总结

Developing...Welcome to pull request in tea your time!

| 短期目标           | 长期目标       |
| ------------------ | -------------- |
| 搜集各种库的源配置 | 源配置的自动化 |



## 前言

鉴于国内网络环境，工程师常常会在开发中遇到包下载等问题。本项目旨在总结配置pip，conda，docker等镜像源，并最给出一站式脚本配置，解决配置时的痛苦。



## 如何使用？

克隆本仓库，并下列内容中找到自己的需求。

```bash
git clone https://github.com/QiangZiBro/EasyConnecter
```

## Anaconda

Anaconda（[官方网站](https://link.jianshu.com/?t=https%3A%2F%2Fwww.anaconda.com%2Fdownload%2F%23macos)）就是可以便捷获取包且对包能够进行管理，同时对环境可以统一管理的发行版本。Anaconda包含了conda、Python在内的超过180个科学包及其依赖项。配置anaconda之前，首先保证正确安装，并且命令行输入`conda`不会报错。

<details>
		<summary>Windows</summary>
**自动** [->]()

**手动**

- **生成配置文件**

如果您还不懂怎么配置，那就直接生成一个新配置文件吧！输入下列命令后，在`C:`文件夹下就可以找到名为`.condarc`的文件了

``` bash
conda config --set show_channel_urls yes
```

- 将[清华源](./config_files/anaconda_configs/.condarc)配置复制到上面的文件里

```bash
#?
```

- **清楚索引缓存**

```bash
conda clean -i
```

- D​o​ne​!:beers:

</details>

<details>
  <summary>Mac</summary>
</details>

<details>
  <summary>Linux</summary>
</details>



## Pip

<details>
  <summary>Windows</summary>
</details>

<details>
  <summary>Mac</summary>
</details>

<details>
  <summary>Linux</summary>
</details>



## Docker

<details>
  <summary>Windows</summary>
</details>

<details>
  <summary>Mac</summary>
</details>

<details>
  <summary>Linux</summary>
</details>

