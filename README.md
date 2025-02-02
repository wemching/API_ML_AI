## 植物王国（微信小程序）

| 发布日期   | 2019-12-06 |
| ---------- | ---------- |
| 产品名称   | 植物王国   |
| 文档现状   | 进行中     |
| 文档编撰者 | 龙雯静     |
| 产品设计师 | 龙雯静     |
| 产品开发者 | 龙雯静     |
| 产品测试员 | 龙雯静     |

---
## 一、价值主张设计（一句话版本）
“植物王国”的目的是解决用户不知道植物名称和信息的用户痛点，提供植物识别的功能；同时推出科普世界和植物图片美化的功能，增加植物对用户的吸引力，当兴趣提高后才对植物信息记忆深刻，“遨游植物世界，与植物做朋友”。
## 一、价值主张设计（一分钟版本）
- ### 市场背景
随着当下社会的工作节奏不断加快，大多人们没有空余的时间留给自己轻松，因此人们出行到大自然的机会很少或极少阅读关于植物的书籍，人们对植物的认识不足，在日常生活中看到植物并不知道它的名称和资料。如果能有一个小程序能够帮助人们辨识植物，人们便能够对生活中看到的植物有所了解，为用户的生活添加一点乐趣。

- ### 产品介绍
用户可通过“植物王国”小程序，上传/拍摄植物图片上传，系统通过调用API，反馈给用户有关植物的信息，包括名称和百科，从而达到帮助用户认识植物的目的。

- ### 产品理念
遨游植物世界，与植物做朋友。

- ### 产品目标
1. 上传/拍摄植物图片，可以反馈植物的名称和资料。
1. 输入植物名称，可以反馈植物的资料和图片。
1. 上传/拍摄植物图片，可以美化图片得到清晰的图片。

- ### 用户痛点
场景一：看到植物但当时并不知道植物名称和信息。<br></br>
场景二：孩子询问父母这是什么植物，父母无法回答。<br></br>
场景三：基于拍摄设备落后或传输时图片被压缩的原因，用户拍摄的图片不清晰。<br></br>
场景四：当时天气情况差，用户拍摄的图片很模糊，看不清图片中的植物。<br></br>

- ### 需求列表
| #   | 功能     | 用户案例                                                                                 | 重要程度 | 
| --- | -------- | ---------------------------------------------------------------------------------------- | -------- | 
| 1   | 识别 | 用户输入植物名称，或者拍摄/上传植物图片，小程序会调用API，反馈相应的植物资料与百科知识。 | 非常重要 | 
| 2   | 科普世界 | 用户进入界面阅读关于植物的知识                                                           | 重要     | 
| 3   | 打扮 | 用户上传或拍摄植物的图片，小程序调用API，输出清晰、色彩鲜明的图片                        | 重要     |

- ### 人工智能概率性
 - 植物识别<br></br>
 用户拍摄或使用的图片清晰度低。<br></br>
 eg.用户拍摄的图片在浓雾天气下拍摄，因此拍摄的图片可见度低。
 - 语音识别<br></br>
 用户输入的语音可能无法被辨识。<br></br>
 eg.用户可能会在嘈杂的环境中输入语音，产品无法辨识用户的语音。
---

## 二、产品设计

- ### 产品架构图
![产品架构图](https://github.com/wemching/API_ML_AI/blob/master/image/%E4%BA%A7%E5%93%81%E6%9E%B6%E6%9E%84%E5%9B%BE.png)

- ### 产品信息结构图
![产品信息结构图](https://github.com/wemching/API_ML_AI/blob/master/image/%E4%BA%A7%E5%93%81%E4%BF%A1%E6%81%AF%E7%BB%93%E6%9E%84%E5%9B%BE.png)

- ### 产品功能结构图
![产品功能结构图](https://github.com/wemching/API_ML_AI/blob/master/image/%E4%BA%A7%E5%93%81%E5%8A%9F%E8%83%BD%E7%BB%93%E6%9E%84%E5%9B%BE.png)

- ### 产品核心流程图
![产品核心流程图](https://github.com/wemching/API_ML_AI/blob/master/image/%E4%BA%A7%E5%93%81%E6%A0%B8%E5%BF%83%E6%B5%81%E7%A8%8B%E5%9B%BE.png)

- ### [产品原型交互展示]( https://nfunm060.gitee.io/api_ml_am)
#### 登陆授权页面<br></br>
![登陆授权页面](https://github.com/wemching/API_ML_AI/blob/master/image/%E7%99%BB%E9%99%86%E6%8E%88%E6%9D%83.png)
#### 1.识别页面<br></br>
![识别页面](https://github.com/wemching/API_ML_AI/blob/master/image/1.%E8%AF%86%E5%88%AB.png)
#### 1.1.拍照识别页面<br></br>
![拍照识别页面](https://github.com/wemching/API_ML_AI/blob/master/image/1.1%E6%8B%8D%E7%85%A7%E8%AF%86%E5%88%AB.png)
#### 1.2.语音识别页面<br></br>
![语音识别页面](https://github.com/wemching/API_ML_AI/blob/master/image/1.2%E8%AF%AD%E9%9F%B3%E8%AF%86%E5%88%AB.png)
#### 2.科普世界页面<br></br>
![科普世界页面](https://github.com/wemching/API_ML_AI/blob/master/image/2.%E7%A7%91%E6%99%AE%E4%B8%96%E7%95%8C.png)
#### 3.打扮页面<br></br>
![打扮页面](https://github.com/wemching/API_ML_AI/blob/master/image/3.%E6%89%93%E6%89%AE.png)
#### 4.个人中心页面<br></br>
![个人中心页面](https://github.com/wemching/API_ML_AI/blob/master/image/4.%E4%B8%AA%E4%BA%BA%E4%B8%AD%E5%BF%83.png)
---
## 三、产品的API使用

- ### 产品中API的调用示例
#### 1. 短语音识别API流程示意图<br></br>
![语音识别](https://github.com/wemching/API_ML_AI/blob/master/image/%E7%9F%AD%E8%AF%AD%E9%9F%B3API.png)
#### 2. 植物识别API流程示意图
![图像识别](https://github.com/wemching/API_ML_AI/blob/master/image/%E5%9B%BE%E5%83%8F%E8%AF%86%E5%88%ABAPI.png)
#### 3. 图像去雾API流程示意图
![图像去雾](https://github.com/wemching/API_ML_AI/blob/master/image/%E5%9B%BE%E5%83%8F%E5%8E%BB%E9%9B%BEAPI.png)
#### 4. 图像清晰度增强API流程示意图
![图像清晰度](https://github.com/wemching/API_ML_AI/blob/master/image/%E5%9B%BE%E5%83%8F%E6%B8%85%E6%99%B0%E5%BA%A6.png)

- ### 使用水平
#### 植物识别（百度AI）
- 图像技术：植物识别api
- 接口描述：该请求用于识别一张图片，即对于输入的一张图片（可正常解码，且长宽比较合适），输出植物识别结果。
- 请求URL: https://aip.baidubce.com/rest/2.0/image-classify/v1/plant
- HTTP方法：POST
- 请求代码示例：<br></br>
![输入植物识别](https://images.gitee.com/uploads/images/2019/1216/142245_06f93ab4_1831522.png "屏幕截图.png")
- 输出代码：<br></br>
![输出植物识别](https://images.gitee.com/uploads/images/2019/1216/142501_f5426869_1831522.png "屏幕截图.png")

- ### API的使用比较
#### 1. 价格比较
- 百度AI的植物识别<br></br>
![植物识别](https://github.com/wemching/API_ML_AI/blob/master/image/%E7%99%BE%E5%BA%A6AI%E6%A4%8D%E7%89%A9%E8%AF%86%E5%88%AB.png)
- 阿里云的图像识别<br></br>
![阿里云](https://github.com/wemching/API_ML_AI/blob/master/image/%E9%98%BF%E9%87%8C%E4%BA%91%E5%9B%BE%E5%83%8F%E8%AF%86%E5%88%AB.png)
- 腾讯云的图像识别<br></br>
![腾讯云](https://github.com/wemching/API_ML_AI/blob/master/image/%E8%85%BE%E8%AE%AF%E4%BA%91%E5%9B%BE%E5%83%8F%E8%AF%86%E5%88%AB.png)

#### 2. 种类比较
- 百度AI<br></br>
![百度AI](https://github.com/wemching/API_ML_AI/blob/master/image/%E7%99%BE%E5%BA%A6AI.png)
- 阿里云<br></br>
![阿里云](https://github.com/wemching/API_ML_AI/blob/master/image/%E9%98%BF%E9%87%8C%E4%BA%91.png)
- 腾讯云<br></br>
![腾讯云](https://github.com/wemching/API_ML_AI/blob/master/image/%E8%85%BE%E8%AE%AF%E4%BA%91.png)

- 对于价格，百度AI平台的是最便宜的。同时百度植物识别API会提供每日500免费调用额度。
- 对于种类，百度AI平台细分的识别种类更多，更加专门化、专业化。本产品主打植物识别，更应调用百度AI的植物识别API；同时本产品中调用的百度AI中的图像清晰度加强API，阿里云平台暂时没有的；图像去雾功能为百度AI平台独有的。
##### 经过团队将三个平台的API调用和API的价格对比，本产品将使用百度AI平台的短语音识别、植物识别、图像去雾和图像清晰度增强API。


---
## 附件

- ### [产品原型交互展示]( https://nfunm060.gitee.io/api_ml_am)
- ### [产品原型文档下载](https://github.com/wemching/API_FINAL_APP)
- ### API文档
#### [百度AI的植物识别](https://ai.baidu.com/ai-doc/IMAGERECOGNITION/Mk3bcxe9i)
#### [百度AI的图像去雾](https://ai.baidu.com/ai-doc/IMAGEPROCESS/8k3bclp1l)
#### [百度AI的短语音识别](https://ai.baidu.com/ai-doc/SPEECH/Ek39uxgre)
