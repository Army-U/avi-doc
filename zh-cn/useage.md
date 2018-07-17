## 默认存储

默认存储使用的是 [sm.ms](https://sm.ms/), 默认存储不需要任何的配置, 也不需要有登录的校验。
需要注意的是默认存储是不在用户的控制范围内的。也就是你上传的图片没有自己删除的权利。**使用默认存储请考虑风险**。

## 上传方式

#### 选择文件上传 (支持多文件)

<video autoplay loop src="https://o77qb5l10.qnssl.com/input-file.mov"></video>

首页上直接点击文件上传, 可一次性多张图片, 上传完毕之后, 点击图片即可获取图片的链接。再次上传可直接点击图片右上角的删除按钮回退到可上传状态, 此操作不会删除该图片。

#### 拖拽文件上传 (支持多文件)

<video autoplay loop src="https://o77qb5l10.qnssl.com/drag-file.mov"></video>

一次性拖动多张图片到上传区域，上传完毕之后, 点击图片即可获取图片的链接。

#### 粘贴图片上传 (只能单张图片)

<video autoplay loop src="https://o77qb5l10.qnssl.com/paste-file2.mov"></video>

复制图片之后，在页面任意位置 Ctrl/Cmd + V 粘贴图片，即可自动上传

#### 粘贴图片链接上传 (只能单张图片)

<video autoplay loop src="https://o77qb5l10.qnssl.com/paste-url.mov"></video>

复制图片链接之后，在页面任意位置 Ctrl/Cmd + V 粘贴图片，即可自动上传

## 记录界面

<img class="no-shadow" src="https://o77qb5l10.qnssl.com/b85922c4-0228-4286-89dc-48be0e162d98_image.png" alt="">

记录界面存放的是上传过的所有图片记录, **所有的图片记录都是存储在本地上**, 不会存在服务器上. 点击记录页面图片的删除按钮, 即可删除在本地记录的历史。

## 设置界面

<img class="no-shadow" src="https://o77qb5l10.qnssl.com/5b4ead2f02d02.png" alt="">

访问设置界面需要使用 Google 登录, 用到的谷歌信息就是用户 ID、用户名称、用户头像。

<img class="no-shadow" src="https://o77qb5l10.qnssl.com/5b4ead854ea0e.png" alt="">

授权 Google 登录之后, 设置界面包含了一些当前用户信息展示、客户端设置、云存储相关的设置.

#### 客户端设置

| 名称          | 作用                           |
| -------      | ----------------              |
| 默认云存储     | 选择上传的首选项                 |
| Markdown 格式 | 是否复制图片链接为 Markndown 格式 |

#### 云存储设置

![](https://o77qb5l10.qnssl.com/b87117a5-5256-4fb7-b49c-646aebb94f19_image.png)

自定义存储的信息录入。 出于安全考虑, 所有已经设置过的云存储信息, 之后都会被替换成 `*` 符号的占位符。二次编辑需要完整的填写所有的字段。
