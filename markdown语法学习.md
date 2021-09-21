# Markdown语法学习

## 标题

# 

### 三级标题

#### 四级标题





## 字体

*

**helloworld**  粗体

*helloworld*

***helloworld***

~~helloworld~~

helloworld



## 引用

> 学习java
>
> 



## 分割线



***

---



## 图片

 

![截图](D:\1.jpg)





## 超链接

[点击跳转到百度](https://www.baidu.com/)



## 列表

1. 订单

2. 对的

3. 等等

   

- A
- B

## 表格



|      |      |      |
| ---- | ---- | ---- |
|      |      |      |
|      |      |      |
|      |      |      |

## 代码

```java
package com.yachtar;


import org.springframework.boot.SpringApplication;
import org.springframework.cloud.client.SpringCloudApplication;
import com.ruoyi.common.security.annotation.EnableCustomConfig;
import com.ruoyi.common.security.annotation.EnableRyFeignClients;
import com.ruoyi.common.swagger.annotation.EnableCustomSwagger2;

/**
 * 测试模块
 *
 * @author ruoyi
 */
@EnableCustomConfig
@EnableCustomSwagger2
@EnableRyFeignClients
@SpringCloudApplication
public class TestApplication {
    public static void main(String[] args)
    {
        SpringApplication.run(TestApplication.class, args);
        System.out.println("(♥◠‿◠)ﾉﾞ  测试模块启动成功   );
    }
}





```

