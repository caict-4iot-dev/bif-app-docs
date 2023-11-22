# DNA注册认证服务平台

## 产品简介

---

DNA注册认证服务平台面向资产数字化和数字化资产应用场景，充分运用<font color=red>大数据</font>、<font color=red>区块链</font>、<font color=red>NFT技术</font>，构建的具备数字资产注册、确权认证、交易流通、资产管理、技术服务和监测监管等功能的数字资产公共服务网络。

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/DNA注册认证平台图片【概述】-1.png" width="100%" width="100%">
</center>   

> 访问地址：https://dna.bitfactory.cn


### 一、应用场景

- **申请注册认证业务：**用户通过注册认证平台提交申请材料，获得数藏注册和认证API接口权限。
- **审核注册认证业务：**信通院审核平台方业务资质，完成应用审核和DNA资产备案审查。包括：API权限审批、冻结、解冻，查验企业和DNA资产信息备案情况等。

### 二、主要功能

- **数字资产创建：**基于星火·链网DNA标准协议提供便捷的资产管理API服务，帮助业务方快速搭建专属数字资产应用。
- **链上资产注册认证：**通过星火·链网主子链接入体系，将已有链网数据资产接入星火生态，实现资产统一监管和互联互通。
- **资产监测监管：**围绕星火生态体系DNA数据资产，部署监管治理合约，统一监测监管，保障资产安全。

### 三、产品特点

- **统一协议：**基于星火·链网统一构建的数字原生资产（DNA）标准协议，为数字资产带来安全可信、可管可溯、互通互认等核心技术特性。
- **国家背书：**通过国家主链为主子链网络中的数字资产进行技术背书，保障数字资产凭证在链群结构中的安全可信与不可篡改。
- **链网协同：**基于星火·链网多链融合技术，各行业可根据业务需要定制其底层链网络，旨在面向全行业构建一套链网协同数字资产基础设施。
- **监管认证：**基于星火·链网可信认证体系，对应用方和数字资产进行认证，纳入DNA统一监测监管体系，实行穿透式监管，保障资产安全。
- **便捷易用：**围绕应用场景需求提供数字资产API服务和一站式行业解决方案，快速、便捷、低成本构建数字资产应用。
- **生态共建：**依托星火·链网和中关村区块链产业联盟的伙伴生态，构建完整的数字资产产业链路，共建数字资产服务网络生态。

## 用户使用手册

---
### 一、业务流程介绍

#### 1.1 创建星火账户及企业认证

**安装星火通插件钱包**：通过星火通账户创建星火企业账户，并完成企业认证。具体操作指引详见[《星火通插件钱包》](https://caict-4iot-dev.github.io/bif-guide/#/docs/%E6%95%B0%E5%AD%97%E8%BA%AB%E4%BB%BD%E6%9C%8D%E5%8A%A1/%E6%98%9F%E7%81%AB%E9%80%9A%E6%8F%92%E4%BB%B6%E9%92%B1%E5%8C%85/%E6%98%9F%E7%81%AB%E9%80%9A%E6%8F%92%E4%BB%B6%E9%92%B1%E5%8C%85)章节，**建议在Chrome浏览器安装星火通插件钱包**。

* 测试阶段：需要在**“星火测试网”**创建星火通账户并完成企业认证。
* 主网阶段：需要重新在**“星火主网”**创建星火通账户并完成企业认证。

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/使用手册图片-1.png" width="50%" width="50%">
</center>

#### 1.2 签署协议及业务申请

完成正式相关协议签署后，通过“**DNA注册认证服务平台**”提交星火账户（bid）、企业认证材料、应用平台资料完成申请。

备注：

* 测试阶段登录[DNA注册认证服务平台测试网](https://test-dna.bitfactory.cn/manage)，主网阶段登录[DNA注册认证服务平台主网](http://dna.bitfactory.cn/manage)
* apiKey开发者的身份ID，可用于获取接入方的调用凭证（access_token），然后通过接口调用凭证再来访问数字资产注册认证平台API。
* apiSecret开发者身份ID对应的密钥，配合apiKey使用能够获取接口调用凭证，同时为了安全起见这个密钥需要妥善保管。

#### 1.3 测试网对接

申请通过后，获取<font color=red>apiKey及apiSecret</font>，完成应用在测网环境对接。

#### 1.4 主网对接

申请通过后，获取<font color=red>apiKey及apiSecret</font>，完成应用在主网环境对接。

### 二、平台演示

通过星火通插件钱包，出示可信企业凭证完成签名，登录DNA注册认证服务平台。申请应用获取apiKey和apiSecret。

#### 2.1 登录平台

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/使用手册图片-2.png" width="100%" width="100%">
</center>

#### 2.2 出示凭证

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/使用手册图片-3.png" width="50%" width="50%">
</center>

#### 2.3 创建应用

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/使用手册图片-4.png" width="100%" width="100%">
</center>

#### 2.4 完成应用创建

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/使用手册图片-5.png" width="100%" width="100%">
</center>

#### 2.5 等待审核中

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/使用手册图片-6.png" width="100%" width="100%">
</center>

#### 2.6 审核通过获取权限

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/使用手册图片-7.png" width="100%" width="100%">
</center>

获得数据：智能合约地址、apiKey和Secret、bid签名服务。

**下一步：请查阅注册/认证API文档，完成应用与DNA接口对接。**

## API文档：注册服务

---

### 一、概述

数字资产注册平台提供以下接口类型：

| **接口类型** | **描述**                     |
| -------- | -------------------------- |
| :3000    | :7000                      |
| 账户管理类    | 用于用户账户的管理，包含创建，激活等操作       |
| 集合操作类    | 用于数字资产集合的操作，包含创建，查询等操作     |
| 资产操作类    | 用于数字资产的操作，包含注册，转移，销毁，查询等操作 |

### 二、API认证机制

所有API的安全认证一律采用accessToken认证，服务端根据生成算法验证认证字符串的正确性。

accessToken需要应用方通过apiKey和apiSecret调用相关平台接口获得，具有时效性，有效时间为<font color=red>2小时</font>，过期后需要重新获取否则会调用接口失败，建议妥善保存并管理。

### 三、操作指引

创建企业的星火账户

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/创建企业的星火账户.png" width="70%" width="70%">
</center>

获取accessToken

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/获取access token.png" width="70%" width="70%">
</center>

创建用户的星火账户

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/创建用户的星火账户.png" width="70%" width="70%">
</center>

创建数字资产集合

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/创建数字资产集合.png" width="70%" width="70%">
</center>

注册/转移/销毁数字资产

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/转移或销毁数字资产.png" width="70%" width="70%">
</center>

### 四、接口认证及账户管理

#### 4.1 获取access token

```http
https://{{url}}/registration/api/v2/getToken
```

**请求方式**

**GET**

**请求参数**

| **字段名**   | **类型** | **是否必填** | **描述**                           |
|:--------- |:------ |:-------- | -------------------------------- |
| apiKey    | string | 是        | 应用审批通过后，每个应用对应一个apiKey，该字段为bid格式 |
| apiSecret | string | 是        | 应用审批通过后，每个应用对应一个私钥apiKey         |

**响应参数**

| **字段名**  | **类型** | **描述**                                                  |
| ----------- | -------- | --------------------------------------------------------- |
| retCode     | int      | 返回状态码<br/>200-成功<br/>400-信息错误<br/>500-服务错误 |
| retMsg      | string   | 200-OK<br/>400-apiKey或apiSecret不正确<br/>500-服务错误   |
| accessToken | string   | 用于应用运营方用户（B端用户）调用接口                     |

**请求示例：**

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/认证图-1.png" width="100%" width="100%">
</center>

**响应示例：**

```json
{
    "retCode": 200,
    "retMsg": "ok",
    "accessToken": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJBcHBJZCI6IjA0OWUyYzI0LWIxODYtNDZlZC04OWQ2LTBjYmMyM2FjMGJiOCIsIkJpZlVzZXJCaWQiOiJkaWQ6YmlkOmVmSjZSM1RqVE1HSkZLTkplOGJCenNKNmlpak5tRVBkIiwiZXhwIjoxNjU2NjczODM5LCJpYXQiOjE2NTY1ODc0Mzl9.4zNysZbpG8IUhNbGgp0oYy0cVM-T-N2J-xJhRc2ie3U"
}
```

#### 4.2 生成离线bid账号

参照[离线API服务使用说明6.2.1章节](https://bif-doc.readthedocs.io/zh-cn/1.0.0/tools/offlineapi.html)

该接口用于创建bid地址，可作为账户或者藏品的唯一标识

```
http://localhost:8888/bifApi/v1/createAddress
```

**请求方式**

**POST**

**请求参数**

| **字段名** | **类型** | **是否必填** | **描述**                  |
| :--------- | :------- | :----------- | ------------------------- |
| type       | int      | 是           | 加密类型1、ED25519;2、SM2 |

**响应参数**

| **字段名**         | **类型** | **描述**                                                    |
| ------------------ | -------- | ----------------------------------------------------------- |
| code               | int      | 返回状态码，<br/>200-成功<br/>400-信息错误<br/>500-服务错误 |
| message            | string   | 200-OK<br/>400-type未填写<br/>500-服务错误                  |
| data               | object   | bid标识数据                                                 |
| data.encAddress    | string   | bid地址                                                     |
| data.encPublicKey  | string   | 该bid地址对应公钥                                           |
| data.encPrivateKey | string   | 该bid地址对应公钥                                           |

**请求示例：**

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/认证图-2.png" width="100%" width="100%">
</center>

**请求体:**

```json
{
    "keyType":1
}
```

**响应示例：**

```json
{
    "code": 200,
    "data": {
        "encAddress": "did:bid:efdYBMrB1SNjXkV6bLy3w3Hww1Ntv2Up",
        "encPrivateKey": "priSPKpY6TuPUZyCuJeaTpUJ1uRYVycNZmpmCuAxC6EhsjdhNX",
        "encPublicKey": "b065668a006b9f68a9ac94f042161f3f0353ccfab47fa9199b8f1889b7d7659d875aa2"
    },
    "message": "ok"
}
```

#### 4.3 构造合约签名交易

参照[离线API服务使用说明6.2.9章节](https://bif-doc.readthedocs.io/zh-cn/2.0.0/instructions/%E7%A6%BB%E7%BA%BFAPI%E6%9C%8D%E5%8A%A1%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E.html)

为<font color=red>6.3章节接口</font>提供如下字段值serialization/signData/publicKey，用于构造<font color=red>转移资产</font>的交易。

```http
http://localhost:8888/bifApi/v1/contract
```

**请求方式**

**POST**

**请求参数**

| **字段名**       | **类型** | **是否必填** | **描述**                                                     |
| ---------------- | -------- | :----------- | ------------------------------------------------------------ |
| senderAddress    | string   | 是           | 交易源账号bid地址，即交易发起方                              |
| senderPrivateKey | string   | 是           | 交易源账户私钥                                               |
| contractAddress  | string   | 是           | 合约账号地址(来源：申请应用时产生的合约地址)                 |
| bifAmount        | int64    | 是           | 缺省情况为0，通常无需变动此参数的值                          |
| feeLimit         | int64    | 是           | 建议为<font color=red>20,000,000</font>, 通常无需变动此参数的值 |
| gasPrice         | int64    | 是           | gas费，缺省100，建议情况为<font color=red>200</font>, 通常无需变动此参数的值 |
| nonce            | int64    | 是           | nonce  需要从链上获取，参照接口6.11                          |
| input            | string   | 是           | 待触发的合约的main()入参，为调用上链交易接口的入参数<br/>转移数字资产"input":{"{\"function\":\"safeTransferFrom(address,address,string)\",\"args\":\"fromAddress,toAddress,'tokenBid'\"}} |

**input参数**

| **字段名**  | **类型** | **是否必填** | **描述**                                                     |
| ----------- | -------- | ------------ | ------------------------------------------------------------ |
| fromAddress | string   | 是           | 用户数字资产持有者地址,保证都是应用下的账户                  |
| toAddress   | string   | 是           | 用户接收数字资产的地址，保证都是应用下的账户                 |
| tokenBid    | string   | 是           | 数字资产bid，每个数字资产绑定一个主链bid作为唯一识别。调用星火·链网接口获取主链bid |

**响应参数**

| **字段名**         | **类型** | **描述**                           |
| ------------------ | -------- | ---------------------------------- |
| code               | int      | 返回状态码<br>200-成功<br>其他错误 |
| message            | string   | 错误原因                           |
| data               | object   | 合约签名数据                       |
| data.serialization | string   | 序列化的交易数据                   |
| data.signData      | string   | 交易签名数据                       |
| data.publicKey     | string   | 交易账号公钥                       |

**请求示例：**

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/认证图-3.png" width="100%" width="100%">
</center>

**请求体：**

```json
{
"senderAddress": "did:bid:efQ69GRtQUDR9SngdFKAv4owYyx5Fnko",
"senderPrivateKey":"priSPKi7K3nVAgtdCu9k9hVn4modxzFkd73JGsRrUYJR1T2RxM",
"contractAddress":"did:bid:efAHUyTyhCdUXSxb3znw3Jw4ET24GdCk",
"bifAmount":0, 
"feeLimit":100000000, 
"gasPrice":10,                                 
"nonce":33,  
"input":"{\"function\":\"safeTransferFrom(address,address,string)\",\"args\":\"did:bid:efQ69GRtQUDR9SngdFKAv4owYyx5Fnko,did:bid:ef1L8GBs9mWzeKXGiAZC877WResz6y7,'did:bid:efDtTjWBLkJjtRSJFMfBLNJ6LjnKu1tV'\"}"
}
```

**响应示例**:

```json
{
    "code": 200,
    "data": {
        "serialization": "0a286469643a6269643a65665136394752745155445239536e6764464b4176346f7759797835466e6b6f102122ee01080752e9010a286469643a6269643a65664148557954796843645558537862337a6e77334a7734455432344764436b1abc017b2266756e6374696f6e223a22736166655472616e7366657246726f6d28616464726573732c616464726573732c737472696e6729222c2261726773223a226469643a6269643a65665136394752745155445239536e6764464b4176346f7759797835466e6b6f2c6469643a6269643a6566314c38474273396d577a654b584769415a43383737575265737a3679372c276469643a6269643a65664474546a57424c6b4a6a7452534a464d66424c4e4a364c6a6e4b7531745627227d3080c2d72f380a",
        "signData": "70b2ce583fb15b1e67e67e76ab3cfe491e819dbcfa3120946b98648be2f319961e3f148efc49c37dae8a6b71c17ac3c11a20caf58fa26513f86b0d4b209d7a09",
        "publicKey": "b06566d8fb4a6dfbe0d5831e38f621391ad9191626f7e28c13d3a0482c52d5c9607b14"
    },
    "message": "ok"
}
```

#### 4.4 构造合约签名交易

参照[离线API服务使用说明6.2.9章节](https://bif-doc.readthedocs.io/zh-cn/2.0.0/instructions/%E7%A6%BB%E7%BA%BFAPI%E6%9C%8D%E5%8A%A1%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E.html)

为<font color=red>6.4章节接口</font>提供如下字段值serialization/signData/publicKey，用于构造<font color=red>销毁资产</font>的交易。

```http
http://localhost:8888/bifApi/v1/contract
```

**请求方式**

**POST**

**请求参数**

| **字段名**       | **类型** | **是否必填** | **描述**                                                     |
| ---------------- | -------- | ------------ | ------------------------------------------------------------ |
| senderAddress    | string   | 是           | 交易源账号bid地址，即交易发起方                              |
| senderPrivateKey | string   | 是           | 交易源账户私钥                                               |
| contractAddress  | string   | 是           | 合约账号地址(来源：申请应用时产生的合约地址)                 |
| bifAmount        | int64    | 是           | 缺省情况为0，通常无需变动此参数的值                          |
| feeLimit         | int64    | 是           | 建议为<font color=red>20,000,000</font>, 通常无需变动此参数的值 |
| gasPrice         | int64    | 是           | gas费，缺省100，建议为<font color=red>200</font>, 通常无需变动此参数的值 |
| nonce            | int64    | 是           | nonce  需要从链上获取，参照接口6.11                          |
| input            | string   | 是           | 待触发的合约的main()入参，为调用上链交易接口的入参数<br/>销毁数字资产"input":{"{\"function\":\"burn(string)\",\"args\":\"'tokenBid'\"}"} |

**input参数**

| **字段名** | **类型** | **是否必填** | **描述**                                                     |
| ---------- | -------- | ------------ | ------------------------------------------------------------ |
| tokenBid   | string   | 是           | 数字资产bid，每个数字资产绑定一个主链bid作为唯一识别。调用星火·链网接口获取主链bid |

**响应参数**

| **字段名**         | **类型** | **描述**                              |
| ------------------ | -------- | ------------------------------------- |
| code               | int      | 返回状态码，取值：200-成功，其他-错误 |
| message            | string   | 错误原因                              |
| data               | object   | 合约签名数据                          |
| data.serialization | string   | 序列化的交易数据                      |
| data.signData      | string   | 交易签名数据                          |
| data.publicKey     | string   | 交易账号公钥                          |

**请求示例：**

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/认证图-4.png" width="100%" width="100%">
</center>

**请求体：**

```json
{
"senderAddress": "did:bid:efQ69GRtQUDR9SngdFKAv4owYyx5Fnko",
"senderPrivateKey":"priSPKi7K3nVAgtdCu9k9hVn4modxzFkd73JGsRrUYJR1T2RxM",
"contractAddress":"did:bid:efAHUyTyhCdUXSxb3znw3Jw4ET24GdCk",
"bifAmount":0, 
"feeLimit":100000000, 
"gasPrice":10,                                 
"nonce":33,  
"input":"{\"function\":\"burn(string)\",\"args\":\"'did:bid:efDtTjWBLkJjtRSJFMfBLNJ6LjnKu1tV'\"}"
}
```

**响应示例:**

```json
{
    "code": 200,
    "data": {
        "serialization": "0a286469643a6269643a65665136394752745155445239536e6764464b4176346f7759797835466e6b6f1021227f0807527b0a286469643a6269643a65664148557954796843645558537862337a6e77334a7734455432344764436b1a4f7b2266756e6374696f6e223a226275726e28737472696e6729222c2261726773223a22276469643a6269643a65664474546a57424c6b4a6a7452534a464d66424c4e4a364c6a6e4b7531745627227d3080c2d72f380a",
        "signData": "2be1050f4663ebcce8a5afe4d76d83079575742f24842026cedd075a7df5ba81a0caecf2ce9de66bf0a37411fef1e422162c840dd07f7870a0578028fa53c502",
        "publicKey": "b06566d8fb4a6dfbe0d5831e38f621391ad9191626f7e28c13d3a0482c52d5c9607b14"
    },
    "message": "ok"
}
```

#### 4.5 激活用户账户

```http
https://{url}/registration/api/v2/account/upload
```

**请求方式**

**POST**

**Headers**

| **字段名**     | **类型** | **是否必填** | **描述**              |
| ----------- | ------ | -------- | ------------------- |
| accessToken | string | 是        | 用于应用运营方用户（B端用户）调用接口 |

**请求参数**

| **字段名** | **类型**   | **是否必填** | **描述** |
| ------- | -------- | -------- | ------ |
| data    | object[] | 是        | 账户信息列表 |

**Data结构如下**

| **字段名** | **类型** | **是否必填** | **描述**                           |
| ------- | ------ | -------- | -------------------------------- |
| phone   | string | 是        | 手机号码使用sha256算法计算出来的hash值，应为64个字符 |
| bid     | string | 是        | 应用的用户账户（C端用户）                    |

**响应参数**

| **字段名** | **类型** | **描述**                                                     |
| ---------- | -------- | ------------------------------------------------------------ |
| retCode    | int      | 返回状态码<br/>200-成功<br/>400-信息错误<br/>500-服务错误    |
| retMsg     | string   | 200-OK<br/>400-第1个账号phone不是有效的hash256字符，或者第1个账号bid地址格式不正确<br/>500-服务错误 |

**请求示例：**

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/认证图-5.png" width="100%" width="100%">
</center>

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/认证图-6.png" width="100%" width="100%">
</center>

**请求体：**

```json
{
    "data":[
        {
            "phone": "708df4830e76a78ab932f8f3e525ded9d3bb8f7f0b22585d8fe93b6afb2d07b3",
            "bid":"did:bid:efuzR95CDvvDJSfQXX82JPksYoTuhBx"
        },
        {
            "phone": "cf3adedc5c7c4cb57ed5f824bd05fd2033d00db81018ff2c26ad68fd60bcc3e3",
            "bid":"did:bid:efuzR95CDvvDJSfQXX82JPksYoTuhBx2"
        },
         {
            "phone": "89a4201ff428804909adc94fcccd4eaaa05add91f8681a606cdc45aa95793d63",
            "bid":"did:bid:efuzR95CDvvDJSfQXX82JPksYoTuhBx3"
        }
    ]
}
```

**响应**

```
{
    "retCode": 200,
    "retMsg": "ok"
}
```

### 五、集合操作

#### 5.1 增加数字资产集合

```http
https://{url}/registration/api/v2/series/add
```

**请求方式**

**POST**

**Headers**

| **字段名**     | **类型** | **是否必填** | **描述**     |
| ----------- | ------ | -------- | ---------- |
| accessToken | string | 是        | 用于B端用户调用接口 |

**请求参数**

| **字段名**      | **类型** | **是否必填** | **描述**             |
| ------------ | ------ | -------- | ------------------ |
| seriesIssuer | string | 是        | 集合发行方              |
| seriesName   | string | 是        | 集合名称，不超过50个字符      |
| seriesDes    | string | 否        | 集合描述，不超过200个字符     |
| externalUrl  | string | 否        | 外部连接，可以展示数字资产相关的网站 |

**响应参数**

| **字段名** | **类型** | **描述**                                                     |
| ---------- | -------- | ------------------------------------------------------------ |
| retCode    | int      | 返回状态码，<br/>200-成功<br/>400-信息错误<br/>500-服务错误  |
| retMsg     | string   | 200-OK<br/>400-accessToken必填、accessToken不正确、accessToken过期、请检查请求参数,请求参数不能为空字符串、集合名称过长，不允许超过50字符、集合名称不允许重复、集合描述不允许超过200个字符<br/>500-服务错误 |
| seriesId   | string   | 集合ID                                                       |
| createTime | string   | 集合创建时间                                                 |

**请求示例：**

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/注册图-17.png" width="100%" width="100%">
</center>

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/注册图-18.png" width="100%" width="100%">
</center>

**请求体:**

```json
{
"seriesIssuer":"央视",
"seriesName":"央视20220816",
"seriesDes":"萌萌图可爱填写超过",
"externalUrl":"http://www.baidu.com/"
}
```

**响应示例：**

```json
{
    "retCode": 200,
    "retMsg": "ok",
    "seriesId": "0af84ba9-545b-40b3-854a-a94d6bb626d6",
    "createTime": "2022-09-16 16:22:58"
}
```

#### 5.2 查询数字资产集合列表

```http
https://{url}/registration/api/v2/series/list/?pageNum=1&pageSize=20
```

**请求方式**

**GET**

**Headers**

| **字段名**     | **类型** | **是否必填** | **描述**     |
| ----------- | ------ | -------- | ---------- |
| accessToken | string | 是        | 用于B端用户调用接口 |

**请求参数**

| **字段名**  | **类型** | **是否必填** | **描述** |
| -------- | ------ | -------- | ------ |
| pageNum  | string | 是        | 页码     |
| pageSize | string | 是        | 数量     |

**响应参数**

| **字段名** | **类型** | **描述**                                                     |
| ---------- | -------- | ------------------------------------------------------------ |
| retCode    | int      | 返回状态码<br/>200-成功<br/>400-信息错误<br/>500-服务错误    |
| retMsg     | string   | 200-OK<br/>400-accessToken必填、accessToken不正确、accessToken过期<br/>500-服务错误 |
| total      | number   | 总数                                                         |
| data       | object[] | 应用下的集合列表                                             |

**Data结构如下:**

| **字段名**      | **类型** | **是否必填** | **描述**             |
| ------------ | ------ | -------- | ------------------ |
| seriesIssuer | string | 是        | 集合发行方              |
| seriesName   | string | 是        | 集合名称，不超过50个字符      |
| seriesDes    | string | 是        | 集合描述，不超过200个字符     |
| externalUrl  | string | 是        | 外部连接，可以展示数字资产相关的网站 |
| createTime   | string | 是        | 集合创建时间             |
| appId        | string | 是        | 应用id               |
| seriesId     | string | 是        | 集合id               |

**请求示例：**

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/注册图-19.png" width="100%" width="100%">
</center>

**响应示例：**

```json
{
    "retCode": 200,
    "retMsg": "ok",
    "total": 1,
    "data": [
        {
            "seriesId": "858fae5d-e6de-41b1-9c75-3be9dd4a69cb",
            "appId": "6245b2ea-af5d-49f1-ab6b-5aa8fb401668",
            "seriesIssuer": "发行方公司",
            "seriesName": "并发集合12",
            "seriesDes": "萌萌",
            "externalUrl": "http://www.baidu.com/",
            "createTime": "2022-07-09 19:30:04"
        }
    ]
}
```

#### 5.3 查询数字资产集合详情

```http
https://{url}/registration/api/v2/series/{seriesId}
```

**请求方式**

**GET**

**Headers**

| **字段名**     | **类型** | **是否必填** | **描述**     |
| ----------- | ------ | -------- | ---------- |
| accessToken | string | 是        | 用于B端用户调用接口 |

**请求参数**

| **字段名**  | **类型** | **是否必填** | **描述** |
| -------- | ------ | -------- | ------ |
| seriesId | string | 是        | 集合ID   |

**响应参数**

| **字段名**   | **类型** | **描述**                                                     |
| ------------ | -------- | ------------------------------------------------------------ |
| retCode      | int      | 返回状态码<br/>200-成功<br/>400-信息错误<br/>500-服务错误    |
| retMsg       | string   | 200-OK<br/>400-accessToken必填、accessToken不正确、accessToken过期、集合id未填写或者集合id错误、集合id不正确、集合id不存在<br/>500-服务错误 |
| seriesIssuer | string   | 集合发行方                                                   |
| seriesName   | string   | 集合名称，不超过50个字符                                     |
| seriesDes    | string   | 集合描述，不超过200个字符                                    |
| externalUrl  | string   | 外部连接，可以展示数字资产相关的网站                         |
| createTime   | string   | 集合创建时间                                                 |
| appId        | string   | 应用id                                                       |
| seriesId     | string   | 集合id                                                       |

**请求示例：**

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/注册图-20.png" width="100%" width="100%">
</center>

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/注册图-21.png" width="100%" width="100%">
</center>

**响应示例：**

```json
{
    "retCode": 200,
    "retMsg": "ok",
    "seriesId": "858fae5d-e6de-41b1-9c75-3be9dd4a69cb",
    "appId": "6245b2ea-af5d-49f1-ab6b-5aa8fb401668",
    "seriesIssuer": "发行方公司",
    "seriesName": "并发集合12",
    "seriesDes": "萌萌",
    "externalUrl": "http://www.baidu.com/",
    "createTime": "2022-07-09 19:30:04"
}
```

#### 5.4 通过集合ID查询数字资产

```http
https://{url}//registration/api/v2/:seriesld/dna?pageNum=1&pageSize=20
```

**请求方式**

**GET**

**Headers**

| **字段名**     | **类型** | **是否必填** | **描述**     |
| ----------- | ------ | -------- | ---------- |
| accessToken | string | 是        | 用于B端用户调用接口 |

**请求参数**

| **字段名**  | **类型** | **是否必填** | **描述** |
| -------- | ------ | -------- | ------ |
| seriesId | string | 是        | 集合ID   |
| pageNum  | string | 是        | 页码     |
| pageSize | string | 是        | 每页条数   |

**响应参数**

| **字段名** | **类型** | **描述**                                                     |
| ---------- | -------- | ------------------------------------------------------------ |
| retCode    | int      | 返回状态码<br/>200-成功<br/>400-信息错误<br/>500-服务错误    |
| retMsg     | string   | 200-OK<br>400-accessToken必填、accessToken不正确、accessToken过期、请检查请求参数,请求参数不能为空字符串、集合id不存在<br>500-服务错误 |
| total      | number   | 总数                                                         |
| data       | object[] | 资产相关数据                                                 |

**Data结构如下:**

| **字段名**  | **类型** | **是否必填** | **描述**                                                     |
| ----------- | -------- | ------------ | ------------------------------------------------------------ |
| seriesId    | string   | 是           | 集合ID                                                       |
| dnaName     | string   | 是           | 数字资产名称，不超过50个字符                                 |
| dnaNumber   | string   | 是           | 数字资产编号，集合内不重复                                   |
| dnaDes      | string   | 是           | 数字资产描述，不超过200个字符                                |
| url         | string   | 是           | 数字资产 url，**建议尺寸**：350px*350px                      |
| hash        | string   | 是           | 数字资产的hash值，建议采用sha256算法                         |
| displayUrl  | string   | 是           | 数字资产缩略图url，**建议尺寸**：85px*85px                   |
| dnaPrice    | number   | 是           | 数字资产价格,单位：元（人民币）                              |
| dnaCategory | string   | 是           | 资产类型：图片、音频、视频、品牌、会员资格、域名、社交、音乐、艺术品、PFP、3D |
| extension   | string   | 是           | 扩展字段，用户自定义，长度不超过1024个字符                   |
| tokenBid    | string   | 是           | 数字资产bid                                                  |
| createTime  | string   | 是           | 创建时间                                                     |

**请求示例：**

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/注册图-22.png" width="100%" width="100%">
</center>

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/注册图-23.png" width="100%" width="100%">
</center>

**响应示例：**

```json
{
    "retCode": 200,
    "retMsg": "ok",
    "total": 12300,
    "data": [
         {
            "tokenBid": "did:bid:ef7aD319SwD6NNVHHSQ2nDCxUeNzNtSf",
            "dnaNumber": "000008",
            "createTime": "2022-08-23 12:22:22",
            "dnaName": "测试000008",
            "dnaDes": "测试000008号数字资产",
            "displayUrl": "http://ww.baidu.com",
            "seriesId": "3ddfafca-5ec8-455f-a6ee-c5ccacb5aa7d",
            "dnaCategory": "图片",
            "hash": "123",
            "extension": "扩展字符",
            "url": "http://ww.baidu.com",
            "dnaPrice": 199
        }
    ]
}
```

### 六、资产操作

#### 6.1 注册数字资产

```http
https://{url}/registration/api/v2/chain/mintDNA
```

**请求方式**

**POST**

**Headers**

| **字段名**     | **类型** | **是否必填** | **描述**     |
| ----------- | ------ | -------- | ---------- |
| accessToken | string | 是        | 用于B端用户调用接口 |

**请求参数**

| **字段名**     | **类型** | **是否必填** | **描述**                                    |
| ----------- | ------ | -------- | ----------------------------------------- |
| seriesId    | string | 是        | 集合ID                                      |
| dnaName     | string | 是        | 数字资产名称，不超过50个字符                           |
| dnaNumber   | string | 是        | 数字资产编号，集合内不重复                             |
| dnaDes      | string | 否        | 数字资产描述，不超过200个字符                          |
| url         | string | 是        | 数字资产 url，**建议尺寸**：350px*350px             |
| hash        | string | 是        | 数字资产的hash值，建议采用sha256算法                   |
| displayUrl  | string | 是        | 数字资产缩略图url，**建议尺寸**：85px*85px             |
| toBid       | string | 是        | 用户数字资产持有者地址                               |
| dnaPrice    | number | 是        | 数字资产价格,单位：元（人民币）                          |
| dnaCategory | string | 是        | 资产类型：图片、音频、视频、品牌、会员资格、域名、社交、音乐、艺术品、PFP、3D |
| extension   | string | 否        | 扩展字段，用户自定义，长度不超过1024个字符                   |

**响应参数**

| **字段名** | **类型** | **描述**                                                     |
| ---------- | -------- | ------------------------------------------------------------ |
| retCode    | int      | 返回状态码<br/>200-成功<br/>400-信息错误<br/>500-服务错误    |
| retMsg     | string   | 200-OK<br>400-accessToken必填、accessToken不正确、accessToken过期、请检查请求参数,请求参数不能为空字符串、集合ID不正确、集合ID不存在、集合ID重复、数字资产名称不应超过50个字符、数字资产名称编号重复、请输入正确格式的数字资产url、请输入正确格式的数字资产缩略图url<br/>500-服务错误 |
| messageId  | string   | 消息id是由数字、字母组成的32位唯一id，用于6.10接口查询注册资产操作的上链状态 |

备注：如提交失败或查询到失败状态时，请在 1分钟后进行重试

**请求示例：**

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/注册图-24.png" width="100%" width="100%">
</center>

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/注册图-25.png" width="100%" width="100%">
</center>

**请求体：**

```json
{
    "seriesId":"{{seriesId}}",
   "dnaName": "测试000008",
    "dnaNumber": "000008",
    "dnaDes": "测试000008号数字资产",
    "url": "http://ww.baidu.com",
    "displayUrl": "http://ww.baidu.com",
    "toBid": "did:bid:ef6tofMj7gv1rMFAPkh6rG4p7oXuXoFv",
    "extension": "扩展字符",
    "hash": "123",
    "dnaPrice": 199,
    "dnaCategory": "图片"
}
```

**响应示例：**

```json
{
    "retCode": 200,
    "retMsg": "ok",
    "messageId": "cd02578529ef4258a301baf8728b7c96"
}
```

#### 6.2 批量注册数字资产

```http
https://{url}/registration/api/v2/chain/batchMintDNA
```

**请求方式**

**POST**

**Headers**

| **字段名**     | **类型** | **是否必填** | **描述**     |
| ----------- | ------ | -------- | ---------- |
| accessToken | string | 是        | 用于B端用户调用接口 |

**请求参数**

| **字段名** | **类型**   | **是否必填** | **描述**         |
| ------- | -------- | -------- | -------------- |
| data    | object[] | 是        | nft列表，长度不超过100 |

**Data结构如下:**    

| **字段名**  | **类型** | **是否必填** | **描述**                                                     |
| ----------- | -------- | ------------ | ------------------------------------------------------------ |
| seriesId    | string   | 是           | 集合ID                                                       |
| dnaName     | string   | 是           | 数字资产名称，不超过50个字符                                 |
| dnaNumber   | string   | 是           | 数字资产编号，集合内不重复                                   |
| dnaDes      | string   | 否           | 数字资产描述，不超过200个字符                                |
| url         | string   | 是           | 数字资产 url，建议尺寸：350px*350px                          |
| hash        | string   | 是           | 数字资产图片哈希值                                           |
| displayUrl  | string   | 是           | 数字资产缩略图url，建议尺寸：85px*85px                       |
| toBid       | string   | 是           | 用户数字资产持有者地址                                       |
| dnaPrice    | number   | 是           | 数字资产价格，小数点后保留2位，单位：元（人民币）            |
| dnaCategory | string   | 是           | 资产类型：图片、音频、视频、品牌、会员资格、域名、社交、音乐、艺术品、PFP、3D |
| extension   | string   | 否           | 扩展字段，用户自定义，长度不超过1024个字符                   |

**响应参数**

| **字段名** | **类型** | **描述**                                                     |
| ---------- | -------- | ------------------------------------------------------------ |
| retCode    | int      | 返回状态码<br/>200-成功<br/>400-信息错误<br/>500-服务错误    |
| retMsg     | string   | 200-OK<br>400-accessToken必填、accessToken不正确、accessToken过期、请检查请求参数,请求参数不能为空字符串、集合ID不正确、集合ID不存在、集合ID重复、数字资产名称不应超过50个字符、数字资产名称编号重复、请输入正确格式的数字资产url、请输入正确格式的数字资产缩略图url<br/>500-服务错误 |
| messageId  | string   | 消息id是由数字、字母组成的32位唯一id，用于6.10接口查询注册资产操作的上链状态 |

备注：如提交失败或查询到失败状态时，请在 1分钟后进行重试

**请求示例：**

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/注册图-26.png" width="100%" width="100%">
</center>

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/注册图-27.png" width="100%" width="100%">
</center>

**请求体：**

```json
{
    "data": [
         {
            "seriesId": "{{seriesId}}",
            "dnaName": "萌萌图可爱填写超过",
            "dnaNumber": "1396",
            "dnaDes": "萌萌图可爱填",
            "url": "http://ww.baidu.com",
            "displayUrl": "http://ww.baidu.com",
            "toBid": "did:bid:efpJ7ySzrVrRsi9kZpoCibmhQmrEJbp1",
            "extension": "萌萌图可爱填写超过个字符萌萌图可",
            "hash": "XMT7BQPcnd6eAxWnvACu",
            "dnaPrice": 1.24,
            "dnaCategory":"图片"
        },
        {
            "seriesId": "{{seriesId}}",
            "dnaName": "brx测试",
            "dnaNumber": "02",
            "dnaDes": "描述2",
            "url": "http://ww.baidu.com",
            "displayUrl": "http://ww.baidu.com",
            "toBid": "did:bid:efpJ7ySzrVrRsi9kZpoCibmhQmrEJbp1",
            "extension": "萌萌图可",
            "hash": "XMT7BQPcnd6eAxWnvACu",
            "dnaPrice": 1.24,
            "dnaCategory":"图片"
        }
          ]
}
```

**响应示例：**

```json
{
    "retCode": 200,
    "retMsg": "ok",
    "messageId": "3407d9b6c4d941c1a51c9b2fe2a66a58"
}
```

#### 6.3 转移数字资产接口

```http
https://{url}/registration/api/v2/chain/transferDNA
```

**请求方式**

**POST**

**Headers**

| **字段名**     | **类型** | **是否必填** | **描述**     |
| ----------- | ------ | -------- | ---------- |
| accessToken | string | 是        | 用于B端用户调用接口 |

**请求参数**

| **字段名**    | **类型** | **是否必填** | **描述**                                                     |
| ------------- | -------- | ------------ | ------------------------------------------------------------ |
| tokenBid      | string   | 是           | 数字资产bid，每个数字资产绑定一个主链bid作为唯一识别。调用星火·链网接口获取主链bid |
| fromBid       | string   | 是           | 用户数字资产持有者地址，保证都是应用下的账户                 |
| toBid         | string   | 是           | 用户接收数字资产的地址，保证都是应用下的账户                 |
| serialization | string   | 是           | 序列化的交易数据，通过调用4.3接口获取                        |
| signData      | string   | 是           | 交易签名数据，通过调用4.3接口获取                            |
| publicKey     | string   | 是           | 交易账号公钥，通过调用4.3接口获取                            |

**响应参数**

| **字段名** | **类型** | **描述**                                                     |
| ---------- | -------- | ------------------------------------------------------------ |
| retCode    | int      | 返回状态码<br/>200-成功<br/>400-信息错误<br/>500-服务错误    |
| retMsg     | string   | 200-OK<br>400-accessToken必填、accessToken不正确、accessToken过期、请检查请求参数，请求参数不能为空字符串、数字资产bid不正确、用户数字资产持有者地址必填、用户数字资产持有者地址不存在、用户数字资产持有者地址不正确、用户接收数字资产的地址不正确<br/>500-服务错误 |
| messageId  | string   | 消息id是由数字、字母组成的32位唯一id，用于6.10接口查询注册资产操作的上链状态 |

备注：如提交失败或查询到失败状态时，请在 1分钟后进行重试

**请求示例：**

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/注册图-28.png" width="100%" width="100%">
</center>

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/注册图-29.png" width="100%" width="100%">
</center>

**请求体：**

```json
{
"tokenBid":"did:bid:effDbwjLCPLypvHjGyDfwis3VHaNZmuT",
"fromBid":"did:bid:efyHiBTd4fbavvr86S7a5zFmBvMyAWhR",
"toBid":"did:bid:efULSmsPJDFR23rsjC8XrdfHZPYV62NU",
"serialization":"0a286469643a6269643a6566704a3779537a725672527369396b5a706f4369626d68516d72454a62703110cd0922ef01080752ea010a286469643a6269643a65664148557954796843645558537862337a6e77334a7734455432344764436b1abd017b2266756e6374696f6e223a22736166655472616e7366657246726f6d28616464726573732c616464726573732c737472696e6729222c2261726773223a226469643a6269643a6566704a3779537a725672527369396b5a706f4369626d68516d72454a6270312c6469643a6269643a656657623866786d6163654c656f434a31567359444e47556d4845396a4d33542c276469643a6269643a65665464746f55356f7a36316d4d613573474c486d7a7651415338357263756f27227d3080dac40938c801",
"signData":"068198e33d8783c1b3f723c6b75d5918dcc2fc465e52e4cd75c3180507db833ad44830869ff30ab4276dc14e02fd12ca3075d73df5b9fbfa5f52b5aba5265804",
"publicKey":"b0656658bd49d9e5318078bdf1833fcc750a80377ab635405517fc8c7874613008f50e"
}
```

**响应示例：**

```json
{
    "retCode": 200,
    "retMsg": "ok",
    "messageId": "9c01734d9a864a06b79993d31c0dd967"
}
```

#### 6.4 销毁数字资产接口

```http
https://{url}/registration/api/v2/chain/burnDNA
```

**请求方式**

**POST**

**Headers**

| **字段名**     | **类型** | **是否必填** | **描述**     |
| ----------- | ------ | -------- | ---------- |
| accessToken | string | 是        | 用于B端用户调用接口 |

**请求参数**

| **字段名**    | **类型** | **是否必填** | **描述**                                                     |
| ------------- | -------- | ------------ | ------------------------------------------------------------ |
| tokenBid      | string   | 是           | 数字资产bid，每个数字资产绑定一个主链bid作为唯一识别。调用星火·链网接口获取主链bid |
| fromBid       | string   | 是           | 用户数字资产持有者地址                                       |
| serialization | string   | 是           | 序列化的交易数据，通过调用4.4接口获取                        |
| signData      | string   | 是           | 交易签名数据，通过调用4.4接口获取                            |
| publicKey     | string   | 是           | 交易账号公钥，通过调用4.4接口获取                            |

**响应参数**

| **字段名** | **类型** | **描述**                                                     |
| ---------- | -------- | ------------------------------------------------------------ |
| retCode    | int      | 返回状态码<br/>200-成功<br/>400-信息错误<br/>500-服务错误    |
| retMsg     | string   | 200-OK<br/>400-accessToken必填<br/>400-accessToken不正确<br/>400-accessToken过期<br/>400-请检查请求参数,请求参数不能为空字符串<br/>400-数字资产bid不存在<br/>400-用户数字资产持有者不正确<br/>400-用户数字资产持有者不存在<br/>500-服务错误 |
| messageId  | string   | 消息id是由数字、字母组成的32位唯一id，用于6.10接口查询注册资产操作的上链状态 |

备注：如提交失败或查询到失败状态时，请在 1分钟后进行重试

**请求示例：**

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/注册图-30.png" width="100%" width="100%">
</center>

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/注册图-31.png" width="100%" width="100%">
</center>

**请求体：**

```json
{
"tokenBid":"did:bid:ef8By2pnXDkCtYePM14s1c4eJFMRwWiY",
"fromBid":"did:bid:efWb8fxmaceLeoCJ1VsYDNGUmHE9jM3T",
"serialization":"0a286469643a6269643a6566704a3779537a725672527369396b5a706f4369626d68516d72454a62703110cd0922ef01080752ea010a286469643a6269643a65664148557954796843645558537862337a6e77334a7734455432344764436b1abd017b2266756e6374696f6e223a22736166655472616e7366657246726f6d28616464726573732c616464726573732c737472696e6729222c2261726773223a226469643a6269643a6566704a3779537a725672527369396b5a706f4369626d68516d72454a6270312c6469643a6269643a656657623866786d6163654c656f434a31567359444e47556d4845396a4d33542c276469643a6269643a65665464746f55356f7a36316d4d613573474c486d7a7651415338357263756f27227d3080dac40938c801",
"signData":"068198e33d8783c1b3f723c6b75d5918dcc2fc465e52e4cd75c3180507db8",
"publicKey":"b0656658bd49d9e5318078bdf1833fcc750a80377ab635405517fc8c7874613008f50e"
}
```

**响应示例：**

```json
{
    "retCode": 200,
    "retMsg": "ok",
    "messageId": "d711f409a48c42299aed1f1cc6672996"
}
```

#### 6.5 通过用户bid查询数字资产

```http
https://{url}/registration/api/v2/dna/:userld?pageNum=1&pageSize=20
```

**请求方式**

**GET**

**Headers**

| **字段名**     | **类型** | **是否必填** | **描述**     |
| ----------- | ------ | -------- | ---------- |
| accessToken | string | 是        | 用于B端用户调用接口 |

**请求参数**

| **字段名**  | **类型** | **是否必填** | **描述**        |
| -------- | ------ | -------- | ------------- |
| userId   | string | 是        | 用户在星火主链的bid账户 |
| pageNum  | string | 是        | 页码            |
| pageSize | string | 是        | 每页条数          |

**响应参数**

| **字段名** | **类型** | **描述**                                                     |
| ---------- | -------- | ------------------------------------------------------------ |
| retCode    | int      | 返回状态码<br/>200-成功<br/>400-信息错误<br/>500-服务错误    |
| retMsg     | string   | 200-OK<br>400-accessToken必填、accessToken不正确、accessToken过期、请检查请求参数,请求参数不能为空字符串<br/>500-服务错误 |
| total      | number   | 总数                                                         |
| data       | object[] |                                                              |

**Data结构如下:**

| **字段名**  | **类型** | **是否必填** | **描述**                                                     |
| ----------- | -------- | ------------ | ------------------------------------------------------------ |
| seriesId    | string   | 是           | 集合ID                                                       |
| dnaName     | string   | 是           | 数字资产名称，不超过50个字符                                 |
| dnaNumber   | string   | 是           | 数字资产编号，集合内不重复                                   |
| dnaDes      | string   | 是           | 数字资产描述，不超过200个字符                                |
| url         | string   | 是           | 数字资产 url，建议尺寸：350px*350px                          |
| hash        | string   | 是           | 数字资产图片哈希值                                           |
| displayUrl  | string   | 是           | 数字资产缩略图url，建议尺寸：85px*85px                       |
| dnaPrice    | number   | 是           | 数字资产价格                                                 |
| dnaCategory | string   | 是           | 资产类型：图片、音频、视频、品牌、会员资格、域名、社交、音乐、艺术品、PFP、3D |
| extension   | string   | 是           | 扩展字段，用户自定义，长度不超过1024个字符                   |
| tokenBid    | string   | 是           | 数字资产bid                                                  |
| createTime  | string   | 是           | 创建时间                                                     |

**请求示例：**

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/注册图-32.png" width="100%" width="100%">
</center>

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/注册图-33.png" width="100%" width="100%">
</center>

 **响应示例：**

```json
{
    "retCode": 200,
    "retMsg": "ok",
    "total": 114000,
    "data": [
        {
            "seriesId": "074b82db-9fed-42da-9b0e-00c579260775",
            "tokenBid": "did:bid:ef5KEkJMzFFFzV1j6Nv5ryj9tf6fs8NM",
            "dnaNumber": "0291b994-d332-41ee-8ce8-1e8da940a01c",
            "createTime": "2022-07-13 05:26:47",
            "dnaName": "brx测试",
            "dnaDes": "描述2",
            "displayUrl": "描述2",
            "dnaCategory": "图片",
            "hash": "XMT7BQPcnd6eAxWnvACu",
            "extension": "萌萌图可",
            "url": "http://ww.baidu.com",
            "dnaPrice": 1.24
        }   
    ]
}
```

#### 6.6 查询数字资产详情

```http
https://{url}/registration/api/v2/dnaDetail?tokenBid
```

**请求方式**

**GET**

**Headers**

| **字段名**     | **类型** | **是否必填** | **描述**     |
| ----------- | ------ | -------- | ---------- |
| accessToken | string | 是        | 用于B端用户调用接口 |

**请求参数**

| **字段名**  | **类型** | **是否必填** | **描述**  |
| -------- | ------ | -------- | ------- |
| tokenBid | string | 是        | 数字资产bid |

**响应参数**

| **字段名** | **类型** | **描述**                                                     |
| ---------- | -------- | ------------------------------------------------------------ |
| retCode    | int      | 返回状态码<br/>200-成功<br/>400-信息错误<br/>500-服务错误    |
| retMsg     | string   | 200-OK<br>400-accessToken必填、accessToken不正确、accessToken过期、请检查请求参数,请求参数不能为空字符串、tokenBid不存在<br/>500-服务错误 |
| data       | object   | 对应数字资产详情                                             |

**Data结构如下：**

| **字段名**  | **类型** | **是否必填** | **描述**                                                     |
| ----------- | -------- | ------------ | ------------------------------------------------------------ |
| seriesId    | string   | 是           | 集合ID                                                       |
| dnaName     | string   | 是           | 数字资产名称，不超过50个字符                                 |
| dnaNumber   | string   | 是           | 数字资产编号，集合内不重复                                   |
| dnaDes      | string   | 是           | 数字资产描述，不超过500个字符                                |
| url         | string   | 是           | 数字资产 url，建议尺寸：350px*350px                          |
| hash        | string   | 是           | 数字资产图片哈希值                                           |
| displayUrl  | string   | 是           | 数字资产缩略图url，建议尺寸：85px*85px                       |
| dnaPrice    | number   | 是           | 数字资产价格                                                 |
| dnaCategory | string   | 是           | 资产类型：图片、音频、视频、品牌、会员资格、域名、社交、音乐、艺术品、PFP、3D |
| extension   | string   | 是           | 扩展字段，用户自定义，长度不超过1024个字符                   |
| tokenBid    | string   | 是           | 数字资产bid                                                  |
| createTime  | string   | 是           | 创建时间                                                     |

**请求示例：**

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/注册图-34.png" width="100%" width="100%">
</center>

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/注册图-35.png" width="100%" width="100%">
</center>

**响应示例：**

```json
{
    "retCode": 200,
    "retMsg": "ok",
    "data": {
        "tokenBid": "did:bid:efRDFqF54C89FhQcSnhKyY4CmViMDo5n",
        "dnaNumber": "1111112",
        "createTime": "2022-07-13 16:58:31",
        "dnaName": "预发应用1集合1注册资产01",
        "dnaDes": "描述",
        "url": "http://ww.baidu.com",
        "displayUrl": "http://ww.baidu.com",
        "extension": "扩展字符",
        "hash": "123",
        "dnaPrice": 12,
        "seriesId": "2075affd-181c-4654-a294-e31c580901aa",
        "dnaCategory": "图片"
    }
}
```

#### 6.7 查询数字资产操作记录

```http
https://{url}/registration/api/v2/record/:tokenBid
```

**请求方式**

**GET**

**Headers**

| **字段名**     | **类型** | **是否必填** | **描述**     |
| ----------- | ------ | -------- | ---------- |
| accessToken | string | 是        | 用于B端用户调用接口 |

**请求参数**

| **字段名**  | **类型** | **是否必填** | **描述**  |
| -------- | ------ | -------- | ------- |
| tokenBid | string | 是        | 数字资产bid |
| pageNum  | string | 是        | 页码      |
| pageSize | string | 是        | 每页条数    |

**响应参数**

| **字段名** | **类型** | **描述**                                                     |
| ---------- | -------- | ------------------------------------------------------------ |
| retCode    | int      | 返回状态码<br/>200-成功<br/>400-信息错误<br/>500-服务错误    |
| retMsg     | string   | 200-OK<br>400-accessToken必填、accessToken不正确、accessToken过期、请检查请求参数,请求参数不能为空字符串、数字资产bid不存在<br/>500-服务错误 |
| total      | number   | 总数                                                         |
| data       | object[] | 操作记录数据                                                 |

 **Data结构如下：**

| **字段名**       | **类型** | **是否必填** | **描述**                             |
| ------------- | ------ | -------- | ---------------------------------- |
| dnaNumber     | string | 是        | 数字资产编号，集合内不重复                      |
| createTime    | string | 是        | 数字资产创建时间                           |
| txHash        | string | 是        | 链上操作的hash                          |
| operation     | number | 是        | 数字资产操作类型，0-注册、1-转移、2-销毁、4-metadata |
| fromBid       | string | 是        | 用户数字资产持有者地址                        |
| toBid         | string | 是        | 用户接收数字资产的地址                        |
| operationDate | string | 是        | 操作时间                               |

**请求示例：**

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/注册图-36.png" width="100%" width="100%">
</center>

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/注册图-37.png" width="100%" width="100%">
</center>

**响应参数：**

```json
{
    "retCode": 200,
    "retMsg": "ok",
    "total": 2,
    "data": [
        {
            "txHash": "83ece7705bd3b358b7427edcf2cb75243e19777d2ca0a3978d86327a410e1ab5",
            "operation": 4,
            "fromBid": "did:bid:efVgVpyFFvG4xkYaEJkHF5bArV167wPv",
            "toBid": "did:bid:efpJ7ySzrVrRsi9kZpoCibmhQmrEJbp1",
            "operationDate": "2022-07-13 16:58:31",
            "dnaNumber": "1111112",
            "createTime": "2022-07-13 16:58:31"
        },
        {
            "txHash": "878c4c520f75622b40829d4f73d7786c82b1a2359dc5a4f8d729ed28e6e87b42",
            "operation": 0,
            "fromBid": "did:bid:efVgVpyFFvG4xkYaEJkHF5bArV167wPv",
            "toBid": "did:bid:efpJ7ySzrVrRsi9kZpoCibmhQmrEJbp1",
            "operationDate": "2022-07-13 16:58:31",
            "dnaNumber": "1111112",
            "createTime": "2022-07-13 16:58:31"
        }
    ]
}
```

#### 6.8 查询上链状态

星火主链共识时间正常情况为4s，请在提交交易4s后，调用此接口，查询链上交易执行结果。

```http
https://{url}/registration/api/v2/chain/status
```

**请求方式**

**GET**

**Headers**

| **字段名**     | **类型** | **是否必填** | **描述**     |
| ----------- | ------ | -------- | ---------- |
| accessToken | string | 是        | 用于B端用户调用接口 |

**请求参数**

| **字段名** | **类型** | **是否必填** | **描述**                                                     |
| ---------- | -------- | ------------- | ------------------------------------------------------------ |
| tokenBid   | string   | 是            | 数据资产bid（或者数字资产对应主链上账户身份）                |
| type       | number   | 是            | 1 注册资产 2 转移资产 3 销毁资产                             |
| txHash     | string   | 是            | 对应注册，转移，销毁资产返回的交易hash，该字段可通过6.10接口获取 |

**响应参数**

| **字段名** | **类型** | **描述**                                                     |
| ---------- | -------- | ------------------------------------------------------------ |
| retCode    | int      | 返回状态码<br/>200-成功<br/>400-信息错误<br/>500-服务错误    |
| retMsg     | string   | 200-OK<br/>400-accessToken必填、accessToken不正确、accessToken过期、请检查请求参数,请求参数不能为空字符串、tokenBid不存在、无效的type、hash或该tokenid对应的type操作不存在<br/>500-服务错误 |
| state      | number   | 状态 <br/>0：已提交 <br/>1：上链失败<br/>2：上链成功<br/>3：上链中 |

**示例：**

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/注册图-38.png" width="100%" width="100%">
</center>

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/注册图-39.png" width="100%" width="100%">
</center>
**响应示例**

```json
{
    "retCode": 200,
    "retMsg": "ok",
    "state": 2
}
```

#### 6.9 查询tokenbid的拥有者

```http
https://{url}/registration/api/v2/chain/tokenOwnerOf/{tokenBid}
```

**请求方式**

**GET**

**Headers**

| **字段名**     | **类型** | **是否必填** | **描述**     |
| ----------- | ------ | -------- | ---------- |
| accessToken | string | 是        | 用于B端用户调用接口 |

**请求参数**

| **字段名**  | **类型** | **是否必填** | **描述** |
| -------- | ------ | -------- | ------ |
| tokenBid | string | 是        | 链账户身份  |

**响应参数**

| **字段名** | **类型** | **描述**                                                     |
| ---------- | -------- | ------------------------------------------------------------ |
| retCode    | int      | 返回状态码<br/>200-成功<br/>400-信息错误<br/>500-服务错误    |
| retMsg     | string   | 200-OK<br>400-accessToken必填、accessToken不正确、accessToken过期<br/>500-服务错误 |
| bidAddress | string   | 返回参数：有结果：[did:bid:ef6tofMj7gv1rMFAPkh6rG4p7oXuXoFv]没结果则为空 |

**请求示例：**

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/注册图-40.png" width="100%" width="100%">
</center>

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/注册图-41.png" width="100%" width="100%">
</center>

**响应示例：**

```json
{
    "retCode": 200,
    "retMsg": "ok",
    "bidAddress": "[did:bid:ef6tofMj7gv1rMFAPkh6rG4p7oXuXoFv]"
}
```

#### 6.10 根据消息id获取处理结果

```http
https://{url}/registration/api/v2/chain/message/{messageId}
```

**请求方式**

**GET**

**Header**

| **字段名**     | **类型** | **是否必填** | **描述**     |
| ----------- | ------ | -------- | ---------- |
| accessToken | string | 是        | 用于B端用户调用接口 |

**请求参数**

| **字段名**   | **类型** | **是否必填** | **描述**                 |
| --------- | ------ | -------- | ---------------------- |
| messageId | string | 是        | 注册，转移，销毁接口返回的messageId |

**响应参数**

| **字段名** | **类型** | **描述**                                               |
| ---------- | -------- | ------------------------------------------------------ |
| retCode    | int      | 返回状态码，取值：200-成功，400-信息错误，500-服务错误 |
| retMsg     | string   | 200-OK<br>400-不存在的消息id<br>500-服务错误           |
| data       | object   | 资产数据                                               |

**data 结构如下：**

| **字段名** | **类型** | **描述**                                                     |
| ---------- | -------- | ------------------------------------------------------------ |
| state      | number   | 上链状态<br/>0 -已提交 <br/>1-上链失败<br/>2-上链成功<br/>3-上链中 |
| info       | object[] | 资产信息数组                                                 |
| txHash     | string   | 链上操作的hash                                               |

**info 结构如下：**

| **字段名**   | **类型** | **描述**  |
| --------- | ------ | ------- |
| seriesId  | string | 集合id    |
| tokenBid  | string | 数字资产bid |
| message   | string | 错误信息    |
| dnaNumber | string | 数字资产编号  |

**请求示例：**

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/注册图-42.png" width="100%" width="100%">
</center>

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/注册图-43.png" width="100%" width="100%">
</center>

**响应示例：**

```json
{
    "retCode": 200,
    "retMsg": "ok",
    "data": {
        "state": 2,
        "info": [
            {
                "seriesId": "0af84ba9-545b-40b3-854a-a94d6bb626d6",
                "tokenBid": "did:bid:efP7EGaAc7dsLyGkNPNDHFDV3GBA7FkD",
                "dnaNumber": "1396",
                "message": ""
            }
        ],
        "txHash": "35c3a00a4fe9ee1d195dbbeac3da7317c7a47cc214f318446ee3badb3370f9d9"
    }
}
```

#### 6.11 获取当前地址nonce值

```http
https://{url}/registration/api/v2/chain/nonce
```

**请求方式**

**GET**

**Headers**

| **字段名**     | **类型** | **是否必填** | **描述**     |
| ----------- | ------ | -------- | ---------- |
| accessToken | string | 是        | 用于B端用户调用接口 |

**请求参数**

| **字段名** | **类型** | **是否必填** | **描述**      |
| ------- | ------ | -------- | ----------- |
| userBid | string | 是        | 应用运营方的链账户身份 |

**响应参数**

| **字段名** | **类型** | **描述**                                                     |
| ---------- | -------- | ------------------------------------------------------------ |
| retCode    | int      | 返回状态码<br/>200-成功<br/>400-信息错误<br/>500-服务错误    |
| retMsg     | string   | 200-OK<br>400-accessToken必填、accessToken不正确、accessToken过期、请检查请求参数,请求参数不能为空字符串、userBid不存在<br/>500-服务错误 |
| nonce      | number   | nonce值                                                      |

**请求示例：**

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/注册图-44.png" width="100%" width="100%">
</center>

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/注册图-45.png" width="100%" width="100%">
</center>

**响应示例：**

```json
{
    "retCode": 200,
    "retMsg": "ok",
    "nonce": 55
}
```

## API文档：认证服务

---

### 一、概述

**数字原生资产认证服务：**面向已有区块链网络的客户提供认证服务，DNA认证服务基于星火主链的公信力为客户提供“星火·链网“DNA数字资产认证，在提高终端用户数字资产安全性的同时，帮助实现统一的资产监管和互认互通。

**数字原生资产数据报送：**由客户通过认证服务接口自主上报，向【DNA注册认证服务平台】报送数字资产基础数据及其关联事件数据，完成数字资产认证。

**数字原生资产数据查询：**支持用户通过DNA浏览器查询该数字资产详情、历史交易信息及当前持有账户信息。

数字资产认证平台提供以下接口类型：

| **接口类型** | **描述**                     |
| -------- | -------------------------- |
| :3000    | :7000                      |
| 账户管理类    | 用于用户账户的管理，包含创建，激活等操作       |
| 集合操作类    | 用于数字资产集合的操作，包含认证，查询等操作     |
| 资产操作类    | 用于数字资产的操作，包含认证，转移，销毁，查询等操作 |

### 二、API认证机制

所有API的安全认证一律采用accessToken认证，服务端根据生成算法验证认证字符串的正确性。

accessToken需要应用方通过apiKey和apiSecret调用相关平台接口获得，具有时效性，有效时间为2小时，过期后需要重新获取否则会调用接口失败，建议妥善保存并管理。

### 三、操作指引

创建企业的星火账户

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/创建企业的星火账户.png" width="70%" width="70%">
</center>

获取accessToken

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/获取access token.png" width="70%" width="70%">
</center>

创建用户的星火账户

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/创建用户的星火账户.png" width="70%" width="70%">
</center>

认证数字资产集合

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/创建数字资产集合.png" width="70%" width="70%">
</center>

转移/销毁数字资产

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/转移或销毁数字资产.png" width="100%" width="100%">
</center>

### 四、接口认证及账户管理

#### 4.1 获取access token

```http
https://{{url}}/registration/api/v2/getToken
```

**请求方式**

**GET**

**请求参数**

| **字段名**   | **类型** | **是否必填** | **描述**                           |
| --------- | ------ | -------- | -------------------------------- |
| apiKey    | string | 是        | 应用审批通过后，每个应用对应一个apiKey，该字段为bid格式 |
| apiSecret | string | 是        | 应用审批通过后，每个应用对应一个私钥apiKey         |

**响应参数**

| **字段名**  | **类型** | **描述**                                                  |
| ----------- | -------- | --------------------------------------------------------- |
| retCode     | int      | 返回状态码<br/>200-成功<br/>400-信息错误<br/>500-服务错误 |
| retMsg      | string   | 200-OK<br/>400-apiKey或apiSecret不正确<br/>500-服务错误   |
| accessToken | string   | 用于应用运营方用户（B端用户）调用接口                     |

**请求示例：**

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/认证图-1.png" width="100%" width="100%">
</center>

**响应示例：**

```json
{
    "retCode": 200,
    "retMsg": "ok",
    "accessToken": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJBcHBJZCI6IjA0OWUyYzI0LWIxODYtNDZlZC04OWQ2LTBjYmMyM2FjMGJiOCIsIkJpZlVzZXJCaWQiOiJkaWQ6YmlkOmVmSjZSM1RqVE1HSkZLTkplOGJCenNKNmlpak5tRVBkIiwiZXhwIjoxNjU2NjczODM5LCJpYXQiOjE2NTY1ODc0Mzl9.4zNysZbpG8IUhNbGgp0oYy0cVM-T-N2J-xJhRc2ie3U"
}
```

#### 4.2 生成离线bid账号

参照[离线API服务使用说明6.2.1章节](https://bif-doc.readthedocs.io/zh-cn/2.0.0/instructions/%E7%A6%BB%E7%BA%BFAPI%E6%9C%8D%E5%8A%A1%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E.html)

该接口用于创建bid地址，可作为账户或者藏品的唯一标识

```
http://localhost:8888/bifApi/v1/createAddress
```

**请求方式**

**POST**

**请求参数**

| **字段名** | **类型** | **是否必填** | **描述**                 |
| ---------- | -------- | ------------ | ------------------------ |
| type       | Int      | 是           | 加密类型1:ed25519；2:sm2 |

**响应参数**

| **字段名**         | **类型** | **描述**                                                  |
| ------------------ | -------- | --------------------------------------------------------- |
| code               | int      | 返回状态码<br/>200-成功<br/>400-信息错误<br/>500-服务错误 |
| message            | string   | 200-OK<br/>400-type必填<br/>500-服务错误                  |
| data               | object   | bid标识数据                                               |
| data.encAddress    | string   | bid地址                                                   |
| data.encPublicKey  | string   | 该bid地址对应公钥                                         |
| data.encPrivateKey | string   | 该bid地址对应私钥                                         |

**请求示例：**

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/认证图-2.png" width="100%" width="100%">
</center>
**请求体:**

```json
{
    "keyType":1
}
```

**响应示例：**

```json
{
    "code": 200,
    "data": {
        "encAddress": "did:bid:efdYBMrB1SNjXkV6bLy3w3Hww1Ntv2Up",
        "encPrivateKey": "priSPKpY6TuPUZyCuJeaTpUJ1uRYVycNZmpmCuAxC6EhsjdhNX",
        "encPublicKey": "b065668a006b9f68a9ac94f042161f3f0353ccfab47fa9199b8f1889b7d7659d875aa2"
    },
    "message": "ok"
}
```

#### 4.3 激活用户账户

```http
https://{url}/registration/api/v2/account/upload
```

**请求方式**

**POST**

**Headers**

| **字段名**     | **类型** | **是否必填** | **描述**              |
| ----------- | ------ | -------- | ------------------- |
| accessToken | string | 是        | 用于应用运营方用户（B端用户）调用接口 |

**请求参数**

| **字段名** | **类型**   | **是否必填** | **描述** |
| ------- | -------- | -------- | ------ |
| data    | object[] | 是        | 账户信息列表 |

**Data结构如下**

| **字段名** | **类型** | **是否必填** | **描述**                           |
| ------- | ------ | -------- | -------------------------------- |
| phone   | string | 是        | 手机号码使用sha256算法计算出来的hash值，应为64个字符 |
| bid     | string | 是        | 应用的用户账户（C端用户）                    |

**响应参数**

| **字段名** | **类型** | **描述**                                                     |
| ---------- | -------- | ------------------------------------------------------------ |
| retCode    | int      | 返回状态码<br/>200-成功<br/>400-信息错误<br/>500-服务错误    |
| retMsg     | string   | 200-OK<br/>400-第1个账号phone不是有效的hash256字符，或者第1个账号bid地址格式不正确<br/>500-服务错误 |

**请求示例：**

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/认证图-5.png" width="100%" width="100%">
</center>

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/认证图-6.png" width="100%" width="100%">
</center>

**请求体:**

```json
{
    "data":[
        {
            "phone": "708df4830e76a78ab932f8f3e525ded9d3bb8f7f0b22585d8fe93b6afb2d07b3",
            "bid":"did:bid:efuzR95CDvvDJSfQXX82JPksYoTuhBx"
        },
        {
            "phone": "cf3adedc5c7c4cb57ed5f824bd05fd2033d00db81018ff2c26ad68fd60bcc3e3",
            "bid":"did:bid:efuzR95CDvvDJSfQXX82JPksYoTuhBx2"
        },
         {
            "phone": "89a4201ff428804909adc94fcccd4eaaa05add91f8681a606cdc45aa95793d63",
            "bid":"did:bid:efuzR95CDvvDJSfQXX82JPksYoTuhBx3"
        }
    ]
}
```

**响应**

```
{
    "retCode": 200,
    "retMsg": "ok"
}
```

### 五、认证数字资产

**须知：本部分面向非主链用户，主链用户无需关注**。

**数字原生资产认证服务详情：**如下表。

| 接口类型       | 服务名称                                                                                    | 描述                                                                                                   |
| ---------- | --------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| 数据资产基础数据   | 数字资产集合信息认证                                                                              | 集合是一种资产类型的标记，方便认证资产进行分类和管理；实现数字资产认证前必须完成数字资产集合信息认证；不支持更新；支持批量认证，单次不超过<font color=red>100</font>；不上链。 |
| 数字资产认证     | 应用方上传数字资产相关信息，完成数字资产认证；不支持更新；支持批量认证，单次不超过100；部分信息上链，DNABid及metadata hash上链。             |                                                                                                      |
| 数字资产相关事件数据 | 资产转移认证                                                                                  | 应用方上传认证数字资产转移交易信息，完成资产转移认证；支持批量认证，单次不超过<font color=red>100</font>；不支持更新；同步更新资产owner;不上链；             |
| 资产销毁认证     | 应用方上传认证数字资产销毁交易信息，完成资产注销认证；支持批量认证，单次不超过<font color=red>100</font>；不支持更新；同步更新资产owner;不上链 |                                                                                                      |

#### 5.1 获取access token

此接口详见**4.1**获取access token部分。

#### 5.2 数字资产集合信息认证接口

```http
https://{url}/auth/api/v1/series
```

**请求方式**

**POST**

**Headers**

| **字段名**     | **类型** | **是否必填** | **描述**        |
| ----------- | ------ | -------- | ------------- |
| accessToken | string | 是        | 用于B端用户调用接口，通过 |

**请求参数**

| **字段名** | **类型**   | **是否必填** | **描述**            |
| ------- | -------- | -------- | ----------------- |
| data    | object[] | 是        | 认证集合列表，集合数量不超过100 |

Data结构如下:

| **字段名**      | **类型** | **是否必填** | **描述**                         |
| --------------- | -------- | ------------ | -------------------------------- |
| seriesName      | String   | 是           | 数字资产集合名称，不超过50字符   |
| seriesIssuer    | String   | 是           | 数字资产集合发行方               |
| externalUrl     | String   | 否           | 该集合对应网站的外部链接         |
| seriesDes       | String   | 否           | 集合描述说明                     |
| seriesId        | Object[] | 是           | 应用方集合id或相互关联的子集合id |
| totalDNA        | Number   | 是           | 集合下发行数字资产数量           |
| asset_contracts | String   | 是           | 与集合关联的合约地址             |

**响应参数**

| **字段名** | **类型** | **描述**                                                     |
| ---------- | -------- | ------------------------------------------------------------ |
| retCode    | int      | 返回状态码<br/>200-成功<br/>400-信息错误<br/>500-服务错误    |
| retMsg     | string   | 200-OK<br/>400-accessToken必填、accessToken不正确、accessToken过期、请检查请求参数,请求参数不能为空字符串、集合ID重复、集合名称不应超过50个字符、集合名称重复<br/>500-服务错误 |

**请求示例：**

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/认证图-9.png" width="100%" width="100%">
</center>

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/认证图-10.png" width="100%" width="100%">
</center>

**请求体：**

```json
{
    "data": [
       {
            "seriesName": "花",
            "seriesIssuer": "玫瑰",
            "seriesId": ["21"],
            "totalDNA": 5,
            "asset_contracts": "did:bid:ef3zTQdpgnWcRRjX3x64E4a6MaRgeSi2",
            "externalUrl": "https://www.baidu.com/",
            "seriesDes": "我是一个花"
        }
        ]
}
```

**响应示例：**

```json
{
    "retCode": 200,
    "retMsg": "ok"
}
```

#### 5.3 数字资产认证接口

```http
https://{url}/auth/api/v1/dna
```

**请求方式**

**POST**

**Headers**

| **字段名**     | **类型** | **是否必填** | **描述**        |
| ----------- | ------ | -------- | ------------- |
| accessToken | string | 是        | 用于B端用户调用接口，通过 |

**请求参数**

| **字段名** | **类型**   | **是否必填** | **描述**              |
| ------- | -------- | -------- | ------------------- |
| data    | object[] | 是        | 认证数字资产列表，资产数量不超过100 |

**Data结构如下：**

| **字段名** | **类型** | **是否必填** | **描述**                                                     |
| ---------- | -------- | ------------ | ------------------------------------------------------------ |
| seriesId   | String   | 是           | 资产所属集合id或子集合id                                     |
| dnaName    | String   | 是           | 数字资产名称                                                 |
| dnaNumber  | String   | 是           | 数字资产的编号                                               |
| tokenBid   | String   | 是           | 数字资产bid                                                  |
| dnaDes     | String   | 否           | 数字资产描述说明                                             |
| dnaType    | string   | 是           | 数字资产类型，0-图片、1-视频、2-音频                         |
| url        | String   | 是           | 数字资产图像的url,建议使用350px*350px的图像,需支持开放访问   |
| displayUrl | String   | 是           | 数字资产缩略图URL，建议尺寸85px*85px，需支持开放访问         |
| hash       | String   | 是           | 数字资产图片哈希值                                           |
| mintTime   | String   | 是           | 数字资产链上mint交易时间                                     |
| owner      | String   | 是           | 数字资产所有者，指账户地址；数字资产发生相关交易后，平台更新维护owner信息 |
| dnaPrice   | Number   | 是           | 数字资产发行价格                                             |
| extension  | String   | 否           | 扩展字段，用户自定义，长度不超过1024个字符                   |

**响应参数**

| **字段名** | **类型** | **描述**                                                     |
| ---------- | -------- | ------------------------------------------------------------ |
| retCode    | int      | 返回状态码<br/>200-成功<br/>400-信息错误<br/>500-服务错误    |
| retMsg     | string   | 200-OK<br/>400-accessToken必填、accessToken不正确、accessToken过期、请检查请求参数,请求参数不能为空字符串、tokenBID重复、资产名称不应超过50个字符、集合ID不存在、请输入正确格式的数字资产url、请输入正确格式的数字资产缩略图url<br/>500-服务错误 |

**请求示例：**

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/认证图-11.png" width="100%" width="100%">
</center>

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/认证图-12.png" width="100%" width="100%">
</center>

**请求体：**

```json
{
    "data": [
           {
            "seriesId": "21",
            "dnaName": "我的资产1",
            "dnaNumber": "1-1",
            "tokenBid": "did:bid:efE6X1PbTCneGX3zipFM28EpWasfKmCc",
            "dnaType": "1",
            "url": "https:///www.123.com/",
            "displayUrl": "https://www.baidu.com/",
            "hash": "1d04071bf2e5f7d14491ee67e0973332e0940ebf833c9a6c8e34a734609bc7d4",
            "mintTime": "2022-07-14 10:29:10",
            "owner": "bid:bid:ljcp:efPmKkmEoacVxRxB4aK1661148815779",
            "dnaPrice": 20,
            "dnaDes": "描述",
            "extension": "扩展字段"
        }
  ]
}
```

**响应示例：**

```json
{
    "retCode": 200,
    "retMsg": "ok"
}
```

#### 5.4 数字资产转移认证接口

```http
https://{url}/auth/api/v1/dna/transfer
```

**请求方式**

**POST**

**Headers**

| **字段名**     | **类型** | **是否必填** | **描述**        |
| ----------- | ------ | -------- | ------------- |
| accessToken | string | 是        | 用于B端用户调用接口，通过 |

**请求参数**

| **字段名** | **类型**   | **是否必填** | **描述**              |
| ------- | -------- | -------- | ------------------- |
| data    | object[] | 是        | 数字资产转移列表，转移记录不超过100 |

Data结构如下:

| **字段名** | **类型** | **是否必填** | **描述**                                                |
| ---------- | -------- | ------------ | ------------------------------------------------------- |
| tokenBid   | String   | 是           | 数字资产bid,每个数字资产绑定一个子链bid作为唯一标识。   |
| fromBid    | String   | 是           | 资产转出的用户地址，每个用户绑定一个子链bid作为唯一标识 |
| toBid      | String   | 是           | 资产转入的用户地址                                      |
| txHash     | String   | 是           | 该交易在链上的交易哈希值                                |
| Time       | String   | 是           | 该交易在链上的确认时间                                  |

**响应参数**

| **字段名** | **类型** | **描述**                                                     |
| ---------- | -------- | ------------------------------------------------------------ |
| retCode    | int      | 返回状态码，取值：200-成功，400-信息错误，500-服务错误       |
| retMsg     | string   | 200-OK<br/>400-accessToken必填、accessToken不正确、accessToken过期、请检查请求参数,请求参数不能为空字符串、txHash重复（校验同一tokenBid，不同资产可重复）、tokenBID不存在<br/>500-服务错误 |

**请求示例：**

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/认证图-13.png" width="100%" width="100%">
</center>

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/认证图-14.png" width="100%" width="100%">
</center>

**请求体：**

```json
{
    "data": [
        {
            "tokenBid": "did:bid:efE6X1PbTCneGX3zipFM28EpWasfKmCc",
            "fromBid": "did:bid:ljcp:ef3zTQdpgnWcRRjX3x64E4a6Ma646731",
            "toBid": "did:bid:ljcp:ef3zTQdpgnWcRRjX3x64E4a6MaRgeSi5",
            "txHash": "1d04071bf2e5f7d14491ee67e0973332e0940ebf4",
            "Time": "2022-08-19 11:11:11"
        }
          ]
}
```

**响应示例：**

```json
{
    "retCode": 200,
    "retMsg": "ok"
}
```

#### 5.5 数字资产销毁认证接口

```http
https://{url}/auth/api/v1/dna/destroy
```

**请求方式**

**POST**

**Headers**

| **字段名**     | **类型** | **是否必填** | **描述**        |
| ----------- | ------ | -------- | ------------- |
| accessToken | string | 是        | 用于B端用户调用接口，通过 |

**请求参数**

| **字段名** | **类型**   | **是否必填** | **描述**          |
| ------- | -------- | -------- | --------------- |
| data    | object[] | 是        | 集合列表，销毁记录不超过100 |

Data结构如下:

| **字段名** | **类型** | **是否必填** | **描述**                                              |
| ---------- | -------- | ------------ | ----------------------------------------------------- |
| tokenBid   | String   | 是           | 数字资产bid,每个数字资产绑定一个子链bid作为唯一标识。 |
| fromBid    | String   | 是           | 数字资产持有用户的地址                                |
| txHash     | string   | 是           | 该交易在链上的交易哈希值                              |
| Time       | string   | 是           | 该交易在链上的确认时间                                |

**响应参数**

| **字段名** | **类型** | **描述**                                                     |
| ---------- | -------- | ------------------------------------------------------------ |
| retCode    | int      | 返回状态码<br/>200-成功<br/>400-信息错误<br/>500-服务错误    |
| retMsg     | string   | 200-OK<br>400-accessToken必填、accessToken不正确、accessToken过期、请检查请求参数,请求参数不能为空字符串、txHash重复（校验同一tokenBid，不同资产可重复）、tokenBID不存在<br/>500-服务错误 |

**请求示例：**

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/认证图-15.png" width="100%" width="100%">
</center>

<center>
<img src="./docs/数字原生资产服务/DNA注册认证平台/image/认证图-16.png" width="100%" width="100%">
</center>

**请求体：**

```json
{
    "data": [
         {
            "tokenBid": "did:bid:efE6X1PbTCneGX3zipFM28EpWasfKmCc",
            "fromBid": "did:bid:ljcp:ef3zTQdpgnWcRRjX3x64E4a6Ma646731",
            "txHash": "1d04071bf2e5f7d14491ee67e0973332e0940ebf4",
            "Time": "2022-08-09 22:22:22"
        }
            ]
}
```

**响应示例：**

```json
{
    "retCode": 200,
    "retMsg": "ok"
}
```

## 常见问题

---

### 一、API接口

#### 1.1 上链失败

可能原因：

+ 测网或主网gas不足。措施：提交重试，重试后若仍无法上链，联系技术人员补充星火令。

+ 上链超时，可能原因链上拥堵。措施：将失败交易重新提交。

+ nonce值设置低于链上nonce值。措施：一般一笔交易提交<font color=red>3~4s</font>后，获取链上地址nonce，并再次提交交易。链上非常拥堵时，可设置为<font color=red>10s</font>。

#### 1.2 激活问题

业务需要全部激活：

* 业务层激活：输入<font color=red>手机号hash</font>完成业务激活，用于数据互联互通。
* 链上激活：必须保证用户bid账号有星火令且能数量足够。入参<font color=red>feelimit</font>设置推荐值<font color=red>20,000,000</font>

**备注：后台自动维护星火令，用户无需过多关注这个场景，交易失败重试即可解决。**

#### 1.3 接口报错

根据提示处理。

### 二、DNA注册认证服务平台

#### 2.1 业务初始化失败

原因DNA注册认证服务平台主账号星火令不足，联系技术人员补充<font color=red>星火令</font>。

#### 2.2 修改应用名

用户可编辑应用名称重新提交审核。