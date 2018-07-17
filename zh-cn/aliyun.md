!> 使用阿里云 OSS 存储之前, 一定要申请 RAM 子账号并建立单独的 Bucket

### RAM 子账户

打开 [阿里云 RAM](https://ram.console.aliyun.com/#/user/list), 点击「新建用户」，输入用户名。

![](https://o77qb5l10.qnssl.com/59a33891-b0d6-4101-84ce-63b72e1a59f4_image.png)

注意勾选「该用户自动生成AccessKey」。

![](https://o77qb5l10.qnssl.com/00fb5f08-20dc-459d-8c13-47745922c312_image.png)

新建用户完毕, 保留 AccessKey 详情。点击「用户授权」。

![](https://o77qb5l10.qnssl.com/7a60784d-3494-4344-8d06-7978f57af921_image.png)

授权 AliyunOSSFullAccess。

![](https://o77qb5l10.qnssl.com/416c08de-6810-4fd2-ad05-8cdfbb3d1374_image.png)

### 新建 Bucket

打开 [OSS 管理台](https://oss.console.aliyun.com/overview), 点击「新建 Bucket」。注意设置公有读权限。

![](https://o77qb5l10.qnssl.com/cf30dba5-6fd9-4fc6-80f8-ecd1e6911cc2_image.png) 

Bucket 新建完毕之后, 打开 Avi 的[设置界面](https://avi.run/setting?lng=zh), 选择阿里云, 输入 accessKeyId、accessKeySecret 等信息。 

![](https://o77qb5l10.qnssl.com/3c2a3c1b-77b7-40f7-bf46-a7614f2b0cdc_image.png)

提交完毕后, 设置阿里云为默认的云存储。

![](https://o77qb5l10.qnssl.com/aa2affa1-c9a0-44f6-85d0-b602b6ff2575_image.png ':size=300')
