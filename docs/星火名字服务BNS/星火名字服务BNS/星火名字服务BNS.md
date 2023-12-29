# 星火名字服务BNS

## 产品简介

---

星火名字服务BNS（Blockchain-based Name System）是遵照分布式数字身份自主管理的理念，面向Web3网络新空间，基于“星火·链网”底层架构建立的新型名字服务，实现机器标识到人类可识读标识的映射，关键特点是对人类友好：名字空间够大，名字形态够丰富，人类可识别容易记住。致力于打破终端用户因为记忆和管理复杂的区块链地址而造成的使用壁垒，成为星火·链网Web3应用中普遍使用的名字服务。

>  官网地址：https://bns.bitfactory.cn/

### 产品特点

<center>
<img src="docs/星火名字服务BNS/星火名字服务BNS/image/产品特点.png" width="80%" width="100%">
</center>

**多元映射对象：**

1. 支持星火体系标识映射，包括数字账户地址、星火DNA数字藏品地址、星火可验证凭证VC地址等；

2. 支持传统互联网标识映射，包括IPv4、IPv6地址等；

3. 支持个人资料集合，包括邮箱地址、手机号等；

**数据自主管理：**

1. BNS名字所有权自主管理；

2. BNS名字解析记录自主维护；

**扁平化解析流程：**

1. 基于智能合约的解析查询；
2. 高速缓存机制；

### 应用场景

**星火生态体系适配融合：**以促进星火链网的链上生态为目标，逐步推进星火生态中各类应用的适配融合，基于BNS的正/逆向解析等技术，实现诸如星火钱包、星火APP、星火DDI等场景的各类标识映射，将机器标识转换为人类可识读的BNS名字，逐渐成为星火链网的唯一身份体系。

**个人Profile页展示：**基于合约查询及DNS域名的泛解析等技术，每个完成BNS名字的用户都将获得自己的专属BNS个人Profile主页，可以直接通过浏览器进行访问。支持展示该BNS名字的所有者、解析记录、子名字等内容。

### 主要功能

**BNS名字注册：** 面向任何有意愿注册BNS名称的星火链网用户（个人/企业），基于注册规则，实现名称可用性查询、名称注册申请、子名称扩展等功能，支撑BNS注册业务开展；

**BNS名字管理：** 面向已获得BNS名称的用户，主要包含名称解析记录管理和名称所有权管理两方面，实现BNS名称解析记录的自主增删改查、名称所有权的自主转移/注销等流程；

**BNS名字解析：** 通过智能合约解析器的方式，实现正向解析查询、逆向解析查询、特定解析类型查询等核心功能，保证BNS名称解析查询流程顺利进行；

**BNS应用对接：** 一是面向应用层提供通用对接能力，以通用SDK服务的形式提供多类接口方便各应用场景调用；二是提供NFT相关功能，具备将BNS名称铸造为NFT并在未来开展相关业务的能力。

## 用户使用手册

---

本章节服务对象为**BNS注册用户**，目的是让新BNS用户了解如何使用BNS系统进行BNS查询、注册、管理、解析等操作，BNS用户通过本指南可以了解体验教程、使用方法和功能特色等。

### 步骤一：下载和安装星火国际链插件钱包

1、**下载星火国际链插件钱包**

访问BNS官网https://app-bns.bitfactory.cn/ ，点击左上角 **<登录>** 按钮后，系统将进行插件钱包的安装检测，如未检测到已安装的插件钱包，则有如图弹窗提示，点击后自动下载。

<center>
<img src="docs/星火名字服务BNS/星火名字服务BNS/image/使用手册-1.png" width="80%" width="100%">
</center>

<center>
<img src="docs/星火名字服务BNS/星火名字服务BNS/image/使用手册-2.png" width="80%" width="100%">
</center>

​	或者，也可以选择直接访问以下链接，进行下载安装。

​	https://vc-govern.bitfactory.cn/download/XinghuoKey-extension-v1.0.0.zip

2、**安装插件钱包，创建或导入星火账户**

完成星火通插件钱包下载，解压可看到如下文件，包含 （1）星火插件钱包-安装包、（2）插件钱包使用手册。

<center>
<img src="docs/星火名字服务BNS/星火名字服务BNS/image/使用手册-3.png" width="80%" width="100%">
</center>

点击打开《星火链网国际节点数字身份平台-客户端插件版用户使用手册》，根据文档中“安装说明”的步骤指引，完成插件钱包的安装、BID账户创建或导入。

<center>
<img src="docs/星火名字服务BNS/星火名字服务BNS/image/使用手册-4.png" width="80%" width="100%">
</center>

### 步骤二：BNS名字注册

1、完成插件钱包的安装并生成BID后，回到BNS官网https://app-bns.bitfactory.cn/ ，通过“星火通数字钱包”登录BNS系统。

在查询文本框中**输入需要注册的名字**，然后**点击<查询>按钮**。**每个BID至多申请注册10个BNS名字**。

<center>
<img src="docs/星火名字服务BNS/星火名字服务BNS/image/使用手册-5.png" width="80%" width="100%">
</center>

注册BNS名字需满足：

**字符规范**：支持汉字（CDNC 中文域名协调联合会定义的中文字表）、英文字母（a-z，不区分大小写）、数字（0-9），汉字简体与繁体定义为两个不同的字符，后续根据使用需求进行字符集扩展。

**长度规范**：每一段名字标签内容支持最长 63 个字符（最长 63 个

英文字母、数字，或 31 个汉字）的文本，针对层级化名字（例如S3.S2.S1），S3和S2 长度可以为 0，S1 最短长度为 2 个相应语言字符。

2、**点击<查询>后**，如所查询的名字处于“未注册”状态，页面显示申请注册所需信息及<确认注册>按钮：a）如满足注册条件，用户可以直接注册；b）如名字是违禁词或保护词，用户**点击<确认注册>按钮**后，系统将显示“该名称不合法”。如所查询名字处于“已注册”状态，则无法继续注册，页面仅显示名字详情。

<center>
<img src="docs/星火名字服务BNS/星火名字服务BNS/image/使用手册-6.png" width="80%" width="100%">
</center>

3、确认名字的注册时长（最短1个月，最长12个月）和申请费用，并上传申请材料（可选，如有需要特殊说明的事项可在此处添加)，最后**点击<确认注册>按钮**。

4、在弹出的授权窗口中点击<签名>按钮，提交名字注册申请。

<center>
<img src="docs/星火名字服务BNS/星火名字服务BNS/image/使用手册-7.png" width="80%" width="100%">
</center>

5、等待“注册管理委员会”投票审核。初始**审核时长为5个工作日，**未来由注册管理委员会根据审核需求进行调整**。您可以在【首页】>【待确认注册名字】，或【名字管理】>【名字确认注册】页面**点击名字对应的<查询投票状态>按钮，查看投票审核状态。

<center>
<img src="docs/星火名字服务BNS/星火名字服务BNS/image/使用手册-8.png" width="80%" width="100%">
</center>

6、当投票完成，**投票结果显示为“通过”时，点击<确认注册>按钮，**并在授权窗口中**点击<签名>按钮**，确认注册名字。至此您已完成BNS名字的注册申请，可以在【我的名字】页面查看和管理名字。**如未在10个工作日内完成确认，系统将释放该BNS名字。**

<center>
<img src="docs/星火名字服务BNS/星火名字服务BNS/image/使用手册-9.png" width="80%" width="100%">
</center>

7、当用户注册失败后，用户在【我的申请】>【注册失败】页面，点击该注册失败名字，系统弹出【申诉】页面，用户**点击<申诉>按钮，**系统提示“申诉请求已提交”。

<center>
<img src="docs/星火名字服务BNS/星火名字服务BNS/image/使用手册-10.png" width="80%" width="100%">
</center>

<center>
<img src="docs/星火名字服务BNS/星火名字服务BNS/image/使用手册-11.png" width="80%" width="100%">
</center>

8、用户在【申诉记录】，可查看该名字申诉状态为“申诉中”。**每个用户仅有一次申诉机会**。申诉后，用户可在【我的申请】>【注册失败】或【申诉记录】页面，查看该申诉结果-申诉状态：“已驳回（不可申诉）”，投票状态：“联委会已否决”。如申诉通过，用户需对该名字进行确认，可在【名字确认注册】页面，**点击<确认注册>按钮**，完成BNS注册申请。

<center>
<img src="docs/星火名字服务BNS/星火名字服务BNS/image/使用手册-12.png" width="80%" width="100%">
</center>

<center>
<img src="docs/星火名字服务BNS/星火名字服务BNS/image/使用手册-13.png" width="80%" width="100%">
</center>

### 步骤三：BNS名字解析记录管理

1、**点击【我的名字】页面**，进入【详情】标签页。

<center>
<img src="docs/星火名字服务BNS/星火名字服务BNS/image/使用手册-14.png" width="80%" width="100%">
</center>

2、**点击【解析记录】标签页**，管理解析记录。

<center>
<img src="docs/星火名字服务BNS/星火名字服务BNS/image/使用手册-15.png" width="80%" width="100%">
</center>

3、先在页面左侧选择解析记录类型，然后在页面右侧的文本框中**输入对应的解析值**，最后**点击<设置解析记录>按钮**。

4、在弹出的授权窗口中**点击<签名>按钮**，成功设置解析记录。

### 步骤四：BNS其他功能体验

1、 **子名字注册与分配**

用户注册子名字时，**点击确认《子名字注册服务协议》**，在符合系统的子名字注册要求下，用户可在其拥有管理权的BNS名字下可自行扩展子名字。最多支持扩展到第三段名字，即注册格式为S3.S2.S1的子名字。子名字的扩展不需要经历投票审核环节。注意：所注册的子名字必须符合注册限制、名字保护等要求，例如不可注册“违禁词”等子名字。

​	**第1步** 用户通过“星火通数字钱包”登录BNS系统。

​	**第2步** 在【我的名字】页面，点击对应名字，在【**子名字】标签页，管理子名字**。

<center>
<img src="docs/星火名字服务BNS/星火名字服务BNS/image/使用手册-16.png" width="80%" width="100%">
</center>

​	**第3步**  **点击<子名字注册>按钮**，弹出“子名字注册”窗口。

<center>
<img src="docs/星火名字服务BNS/星火名字服务BNS/image/使用手册-17.png" width="80%" width="100%">
</center>

​	**第4步** 在“子名字”文本框中**输入要注册的子名字、分配该子名字所有者**（默认为自己），并确认名字的注册时长（最短1个月，最长12个月）等信息，最后**点击<确认注册>按钮**。首次注册时，需签署《AIR子名字用户协议》。

​	**第5步** 在弹出的授权窗口中点击<签名>按钮，成功注册子名字。您可以在【我的名字】页面或者在父级名字的【子名字】标签页面查看并管理子名字。

<center>
<img src="docs/星火名字服务BNS/星火名字服务BNS/image/使用手册-18.png" width="80%" width="100%">
</center>

2、**名字所有权管理**

BNS用户可对所拥有的名字进行转移、注销、撤销注销、续费（为防止恶意操作，BNS名字的持有时长最长为12个月）等操作，保障名字的合理使用。进行BNS转移操作时，需填写接收方BID，方可执行此操作。

<center>
<img src="docs/星火名字服务BNS/星火名字服务BNS/image/使用手册-19.png" width="80%" width="100%">
</center>

## API文档

### 摘要

本章节阐述了星火名字服务BNS（Blockchain-based Name System，简称BNS）注册接口、解析接口，包含BNS名字注册接口、BNS子名字数据模型、BNS名字所有权管理数据模型、BNS名字解析架构、BNS名字逆向解析接口协议、BNS多平台账户解析接口、BNS文本记录解析接口等内容。

### BNS名字注册接口

文本注册协议传输使用HTTP/HTTPS通信协议，使用JSON编码。

#### 名称注册接口说明

接口名称：BNS名称注册接口(GET方法)

接口说明：注册BNS名称

接口地址：http://${url}/${bid}，url为注册服务的地址，为要解析的BID

成功返回参数：解析成功返回BID文档

> 名称注册请求参数字段说明

| 字段名              | 字段类型 | 是否必填 | 描述                |
| ------------------- | -------- | -------- | ------------------- |
| baseNode            | string   | 是       | 父级名称，通常为”.“ |
| label               | string   | 是       | 名称标签            |
| owner               | string   | 是       | 名称所有人          |
| name                | string   | 是       | 名称展示            |
| needReverseRecord   | boolean  | 是       | 是否需要反向注册    |
| needForwardRecord   | boolean  | 是       | 是否需要进行解析    |
| duration            | number   | 是       | 有效时间            |
| ttl                 | number   | 是       | 过期ttl             |
| otherMetadata       | string   | 是       | 元数据信息          |
| resolver            | string   | 是       | 解析器地址          |
| registrarController | string   | 是       | 注册器地址          |

> 名称注册请求参数json

```json
{
    "method": "commitRegister", "params": {
        "record": {
            "baseNode": ".",
            "label": "guoyizhang",
            "owner": "did:bid:efHzcjj3w1eg9B4aoaem5axrBLS8y8JF",
            "name": "guoyizhang.",
            "needReverseRecord": true,
            "needForwardRecord": true,
            "duration": 123455,
            "ttl": 12334,
            "otherMetadata": "{}",
            "resolver": "did:bid:efVQFEDg7BXvYK8HG9T3b6cA6irG5es8",
            "registrarController": "did:bid:efVQFEDg7BXvYK8HG9T3b6cA6irG5es8"
        }
    }
}
```

#### 子名称数据模型说明

> 子名称扩展请求参数字段说明

| 字段名        | 字段类型 | 是否必填 | 描述                |
| ------------- | -------- | -------- | ------------------- |
| baseNode      | string   | 是       | 父级名称，通常为”.“ |
| label         | string   | 是       | 名称标签            |
| owner         | string   | 是       | 名称所有人          |
| name          | string   | 是       | 名称展示            |
| ttl           | number   | 是       | 过期ttl             |
| otherMetadata | string   | 是       | 元数据信息          |
| resolver      | string   | 是       | 解析器地址          |

> 子名称扩展请求参数json

```json
{
    "method": "setSubNodeRecord", "params": {
        "record": {
            "name": "abc.guoyizhang.bns.",
            "baseNode": ".guoyizhang.bns.",
            "label": "abc",
            "owner": "did:bid:efKcehkCfFuBUqwWERPqp6h45iHKDLcM",
            "resolver": "did:bid:efXFvUnZrdKyj4BYpqghS3v1FRHfNVrP",
            "otherMetadata": "",
            "ttl": 100
        }    }
}
```

#### 名称所有权管理数据模型说明

##### 名称注销

> 名称注销请求参数字段说明

| 字段名 | 字段类型 | 是否必填 | 描述         |
| ------ | -------- | -------- | ------------ |
| name   | string   | 非必须   | 要注销的名称 |
| remark | string   | 必须     | 注销原因     |

> 名称注销请求参数json

```json
{
    "method": "cancelName", "params": {
        "record": {
            "name": "abc.guoyizhang.bns.",
            "remark": "无效名称"
        }}
}
```

> 名称撤销注销请求参数字段说明

| 字段名 | 字段类型 | 是否必填 | 描述     |
| ------ | -------- | -------- | -------- |
| id     | string   | 必须     | 注销ID号 |

> 名称撤销注销请求参数json

```json
{
    "method": "cancelName", "params": {
        "record": {
            "id": "23fs32asd88asdasvs"
        }}
}
```

##### 名称转移

> 名称转移请求参数字段说明

| 字段名 | 字段类型 | 是否必填 | 描述       |
| ------ | -------- | -------- | ---------- |
| name   | string   | 必须     | 名称       |
| owner  | string   | 必须     | 新的拥有者 |

> 名称转移请求参数json

```json
{
    "method": "transfer", "params": {
        "record": {
            "name": "abc.guoyizhang.bns.",
            "owner": "did:bid:efHzcjj3w1eg9B4aoaem5axrBLS8y8JF"
        }}
}
```

> 确认接收请求参数字段说明

| 名称   | 字段类型 | 是否必须 | 描述     |
| :----- | :------- | :------- | :------- |
| id     | string   | 必须     | 转移单ID |
| remark | string   | 必须     | 备注     |

> 确认接收请求参数json

```json
{
    "method": "transfer", "params": {
        "record": {
            "id": "23fs32asd88asdasvs",
            "remark": "同意接收"
        }}
}
```



### BNS名字解析接口

####  解析架构

<center>
<img src="docs/星火名字服务BNS/星火名字服务BNS/image/解析架构.png" width="80%" width="100%">
</center>

星火链与其子链的数据同步依靠星火链基础架构来实现，合约的部署也会随着区块数据的同步而被同步到主链、测链、子链的任意一个节点上。其解析过程

1. 用户注册名称时候可以选择是否设置自定义解析器
   - 设置了自定义解析器，则会在创建过程中，将自定义解析器作为默认解析器，连同名称数据写入到注册表合约中
   - 如果没有设置自定义解析器，则会默认使用公共解析器地址作为名称的默认解析器
2. 用户根据名称和类型进行解析，默认解析为星火链网钱包地址
   - 根据名称从注册表中读取名称元数据，从元数据中查询其解析器地址
   - 将解析器地址回传给调用方客户端
   - 客户端根据返回的解析器地址，访问链上解析器合约
3. 链上解析器合约的执行
   - 无论是公共解析器还是自定义解析器，均会按照解析类型来映射到对应的数据上，最终完成解析

#### 逆向解析接口

文本解析协议传输采用HTTP/HTTPS通信协议，其参数采用JSON格式进行传输。

> 逆向解析请求参数字段说明

| 字段名 | 字段类型 | 是否必填 | 描述        |
| ------ | -------- | -------- | ----------- |
| addr   | String   | 是       | BID地址信息 |

> 逆向解析请求参数json

```json
{
    "method": "name", "params": {"addr": "did:bid:efi9eJga7RS9HHwTmw9c3nHEniqB6FGq"}
}
```

#### 其它平台账户解析接口

文本解析协议传输采用HTTP/HTTPS通信协议，其参数采用JSON格式进行传输。

> 其它平台账户解析字段说明

| 字段名    | 字段类型 | 是否必填 | 描述        |
| --------- | -------- | -------- | ----------- |
| addr      | String   | 是       | BID地址信息 |
| coionType | Enum     | 是       | 平台类型    |

> 币种平台账户解析参数json

```json
{
    "method": "addr", "params": {
        "name": "guoyi.bns", 
        "coinType": "BTC"
    }
}
```

#### 文本记录解析接口

文本解析协议传输采用HTTP/HTTPS通信协议，其参数采用JSON格式进行传输。

> 文本记录解析字段说明

| 字段名   | 字段类型 | 是否必填 | 描述        |
| -------- | -------- | -------- | ----------- |
| addr     | String   | 是       | BID地址信息 |
| textType | Enum     | 是       | 文本类型    |
| textKey  | String   | 是       | 文本Key标识 |

> 文本记录解析参数json

```json
{
    "method": "text", "params": {
        "name": "zbm.", 
        "textType": "EMAIL",
        "textKey": "比特币"
    }
}
```



## 常见问题

---

### 如何联系我们？

如在使用过程中遇到任何相关问题，可邮件咨询bns@caict.ac.cn。
