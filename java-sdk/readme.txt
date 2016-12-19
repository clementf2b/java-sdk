SDK使用的一些说明，

这个SDK里的网络请求是用JAVA的API"HttpsURLConnection"写的，自己封装的一些网络请求，所以强烈建议使用第三方框架来调用我们的API

SDK里的几个类

Response 这是一个网络请求的结果类，网络请求的结果封装在里面，包括返回的状态码和返回的信息

CommonOperate 封装了detect，compare，search这三个接口

FaceSetOperate FaceSet相关的操作

FaceOperate Face相关的操作

CardOperate 封装了证件识别的接口

ImageOperate 图片识别接口的封装

HttpRequest 这里面封装了网络请求

Key 这里面定义了一些字段

具体的参数说明及方法功能请看每个方法的注释