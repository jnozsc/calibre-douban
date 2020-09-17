# About this project

[`Calibre`](https://github.com/kovidgoyal/calibre) used to offer an official douban plugin to fetch the book metadata from douban.com. However, the author of `Calibre` chooses to not maintain it any more. So I decide to maintain my own branch.

# DISCLAIMER

In order to work functionally, this project requires a valid API key. The project itself does not provide any API key and does not recommend to share any API key in any method. Please use your own API key or contact bd-team@douban.com for authorized access.

为了正常工作，本项目需要有效的 API 密钥。本项目不提供任何 API 密钥，也不建议以任何方法共享任何 API 密钥。请使用您自己的 API 密钥或联系 bd-team@douban.com 获得授权访问。

# How to install

(1) in `Terminal.app` or your prefer command line terminal

```bash
git clone https://github.com/jnozsc/calibre-douban
cd calibre-douban
make zip
```

You will be able to locate a `douban.zip` in the folder, please remember the path

(2) launch the `calibre` application

(3) launch the `Prefernces` page, click the `Plugins` icon

<img src="https://github.com/jnozsc/calibre-douban/raw/master/asset/step_1.png" >

(4) click the `Load plugin from file` button, and choose `douban.zip` from step (1)

<img src="https://github.com/jnozsc/calibre-douban/raw/master/asset/step_2.png" >

(5) after loading the plugin into `calibre`, select the plugin named 'Douban Books Reload', click the `Customize plugin` button, and input your API key

<img src="https://github.com/jnozsc/calibre-douban/raw/master/asset/step_3.png" >

(6) enjoy
