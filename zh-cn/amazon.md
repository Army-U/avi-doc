!> 使用亚马逊 S3 存储之前, 一定要申请 IAM 子账号并建立单独的存储桶

### IAM 子账户

打开 [IAM 子账户的面板](https://console.aws.amazon.com/iam/home#/users), 点击「添加用户」, 设置新用户以编程访问访问。

![](https://o77qb5l10.qnssl.com/523340d2-c949-47ec-9493-8e63621d6236_image.png)

授予访问 S3 的权限

![](https://o77qb5l10.qnssl.com/13fc9b5b-38c1-4294-946d-fed3d989e11e_image.png)

创建完毕后将访问密钥 ID 和 私有访问密钥 保留下来

### 创建一个新的存储桶

打开 [S3 存储痛列表](https://s3.console.aws.amazon.com/s3/home), 点击「创建存储桶」, 如 `avi-example`。

!> 亚马逊 S3 存储的图片是默认不公开的, 这会导致图片无法访问。[开启访问公开](http://docs.amazonaws.cn/AmazonS3/latest/dev/example-bucket-policies.html#example-bucket-policies-use-case-2)。

设置完毕后打开 Avi 的[设置界面](https://avi.run/setting?lng=zh), 输入刚才保留下来的 密钥 ID 和 密钥 等信息。 

![](https://o77qb5l10.qnssl.com/1dc0760f-719d-4ea3-a751-9213c48e32e0_image.png)

最后设置默认云存储是 Amazon S3。

![](https://o77qb5l10.qnssl.com/d6592e9d-4e96-4bdf-a730-7df6686f10a6_image.png ':size=300')
