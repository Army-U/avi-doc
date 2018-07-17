!> 使用七牛云存储, 一定要设置一个单独的密钥

### 设置密钥

七牛云没有办法单独设置账户, 建议单独[设置一个密钥](https://portal.qiniu.com/user/key). 设置完成保留 	AccessKey/SecretKey。

### 新建 Bucket

打开 [七牛云云存储](https://portal.qiniu.com/), 点击「新建存储空间」。

![](https://o77qb5l10.qnssl.com/151b70eb-f58a-4b13-aaa2-d8c5ab1b116f_image.png)

Bucket 新建完毕之后, 打开 Avi 的[设置界面](https://avi.run/setting?lng=zh), 选择七牛云, 输入 AccessKey/SecretKe、 bucket 等信息。 

![](https://o77qb5l10.qnssl.com/0b5a646c-966f-4131-bfe8-f3cd2b24ce3e_image.png)

提交完毕后, 设置七牛云为默认的云存储。

![](https://o77qb5l10.qnssl.com/ee4f2aba-357b-4268-a1f8-c9d96c9bf102_image.png ':size=300')

!> 七牛云默认不会提供 https 的支持, [添加 https 域名](https://portal.qiniu.com/cdn/domain)
