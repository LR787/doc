



# 随机图API

> 这里由<font color="red"><a href="https://waliwali.icu">waliwali资源网</a></font>提供二次元随机图

目前系统共收录 2000+ 张图片 API最后更新时间:2021-02-13

图片默认均为https，采用img.fghrsh.net，高速访问

## 宽屏电脑API基本调用格式：

```http
https://waliwali.icu/API/img/acgurl.php
```

> 测试图：<img src="https://waliwali.icu/API/img/acgurl.php" >

---



## 窄屏手机随机壁纸API

> 测试图： <img src="https://waliwali.icu/API/img/acg-phone.php">

```http
https://waliwali.icu/API/img/acg-phone.php
```

---



#### 参数：

##### 在网页中引用：

1. 返回电脑端宽图

```html
<img src="https://waliwali.icu/API/img/acgurl.php?return=img" 
```

2. 返回手机端长图

   ```html
   <img src="https://waliwali.icu/API/img/acg-phone.php?return=img" 
   ```

   

##### 返回值：

```json
return=json/http/https/img
```

>  示范:
>
> - https://waliwali.icu/API/img/acgurl.php?return=json 
>
>   以上将返回json数据
>
> - https://waliwali.icu/API/img/acgurl.php?return=img/http 
>
>   以上将返回普通图片

#### JSON调用格式

```http
https://waliwali.icu/API/img/acgurl.php?return=json
```

#### JSON数据

```json
{
    "API_name": "waliwali_API",
    "imgurl": "https:\/\/www.helloimg.com\/images\/2021\/02\/13\/95d5cd48f2beed832b63d3ccb5be335b91ff12eabf9620fa.png",
    "width": "1920",
    "height": "1080"
}
```

