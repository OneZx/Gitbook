#### 1. 下载安装gitbook editor

gitbook editor : [https://www.gitbook.com/editor](https://www.gitbook.com/editor)

> 建议使用`github`账号 登录`gitbook`

github : [https://github.com/](https://github.com/)

  - 如果没有github,就注册一个github账号

---

#### 2. gitbook editor说明

> **界面**

![](/assets/gitbook.png)

* 右下键有个`?`号,点击可以显示`edit markdown`
* 可以看见`show preview`预览
* `show sidebar` 显示左边sidebar

<br>
> **sidebar上鼠标右键 新建article**


![](/assets/sidebar.png)

**其他操作自己研究吧~~~~**

---

#### 3. gitbook本地导出

> **1.安装node.js** [https://nodejs.org/en/download/](https://nodejs.org/en/download/)

* `win+R` 打开cmd
* 查看node版本 `node -v`
* 查看npm版本  `npm -v`

  ![](/assets/a1.png)

* 显示出node版本表示已经安装好node了, 要本地导出, 建议安装6.x的node版本

* **node以往版本** [https://nodejs.org/zh-cn/download/releases/](https://nodejs.org/zh-cn/download/releases/)

* **node 6.x** [https://nodejs.org/dist/latest-v6.x/](https://nodejs.org/dist/latest-v6.x/) 选择适合版本安装

<br>
> **2.安装gitbook cli**

1. `npm install -g gitbook-cli`   这里的`-g`表示全局安装

   ![](/assets/gitb.png)

2. 检测是否安装成功 `gitbook -v`   这里的`-V`大写

   ![](/assets/g2.png)

3. cd到book的目录,把文件拖入  
    ![](/assets/cd.png)

4. 输入`gitbook build`回车 导出gitbook 不出意外可以导出

> **3.版本问题**

* 如果安装的是最新版本的gitbook那么无法在url为file://时完成目录跳转,所以建议装3.0以下的老版本

* 查看老版本 指令`gitbook ls-remote`

  ![](/assets/g3.png)

* 安装2.6.7版本 `gitbook fetch 2.6.7`

* 查看安装的版本`gitbook ls`

* 以指定版本号导出 `gitbook build --gitbook=2.6.7`

> **4.导出后的目录**

* 在文件目录中 新增了一个`_book`文件夹 此为导出文件

![](/assets/end.png)

---

#### 4. gitbook与github绑定

> 下次写



