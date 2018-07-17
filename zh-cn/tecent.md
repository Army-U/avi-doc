!> 使用腾讯云 COS 存储之前, 一定要申请 CAM 子账号并建立单独的 Bucket

### CAM 账户

打开 [腾讯云 CAM](https://console.cloud.tencent.com/cam/user/create?systemType=SubAccount), 设置用户信息, 注意不要勾选「腾讯云管理控制台访问」。

![](https://o77qb5l10.qnssl.com/bec369c7-1617-4a82-860a-60a92c742493_image.png)

设定权限这一步, 选择从策略列表中授权。

![](https://o77qb5l10.qnssl.com/d6730ad5-92a4-44f4-ab29-16de4c75c6d9_image.png)

新建用户完成之后，保留 SecretId 和 SecretKey。

### 新建存储桶

打开 [腾讯云存储桶](https://console.cloud.tencent.com/cos5/bucket), 点击「创建存储桶」。

![](https://o77qb5l10.qnssl.com/5a2fa6df-f2fa-4c82-9bfa-4651b6728947_image.png)

Bucket 新建完毕之后, 打开 Avi 的[设置界面](https://avi.run/setting?lng=zh), 选择腾讯云, 输入 SecretId 和 SecretKey 等信息。

![](https://o77qb5l10.qnssl.com/0772582e-3079-46f8-be4d-739d224d8d65_image.png)

提交完毕后, 设置腾讯云为默认的云存储。

![](https://o77qb5l10.qnssl.com/5115867e-2659-4b31-8c93-4717f2ddc0d4_image.png ':size=300')

!> 在腾讯云上存储的图片直接用浏览器打开会直接下载而不是展示图片
