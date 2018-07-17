!> 使用又拍云存储, 一定要设置一个单独的 Bucket

### 新建云存储服务

打开 [又拍云云存储](https://console.upyun.com/services/create/file/), 设置服务名称

![](https://o77qb5l10.qnssl.com/8d55b4e5-4c75-4308-92f7-f8682ff1ffaa_image.png)

**一定设置要可读可写入的权限**

![](https://o77qb5l10.qnssl.com/bd925f5f-8214-48b2-8255-1d010af238a1_image.png)

创建完毕后, 又拍云会分配一个测试域名。打开 Avi 的[设置界面](https://avi.run/setting?lng=zh), 选择又拍云, 输入域名等信息。

![](https://o77qb5l10.qnssl.com/496fa0a9-ca72-488c-a8e7-26a689f84ce0_image.png)

提交完毕后, 设置又拍云为默认的云存储。

![](https://o77qb5l10.qnssl.com/85824e65-e011-48a1-b01c-6d433645b8cf_image.png ':size=300')

!> 七牛云默认不会提供 https 的支持, 需要自行添加域名绑定
