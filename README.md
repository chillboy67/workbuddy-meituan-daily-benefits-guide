# workbuddy-meituan-daily-benefits-guide

## 1.workbuddy注册
https://www.workbuddy.cn/events/invite?inviteCode=s4ey43des

使用该邀请码可以获得2000积分
<img width="750" height="1110" alt="workbuddy-invite-poster" src="https://github.com/user-attachments/assets/a541fe34-d14e-40fb-a6c3-0bd978d3831d" />


## 2.学生认证
https://www.workbuddy.cn/events/campus-freshman/

进入当前页面，会有微信二维码，扫描，进入认证页面
<img width="553" height="550" alt="image" src="https://github.com/user-attachments/assets/37820ec2-aebe-4c10-a852-62c96ec710f4" />


### 路径一
如果之前进行过微信学生认证，则认证可以直接进行，成功后收到1000积分

### 路径二 微信与学信网/支付宝联合认证（适用于首次或重新认证）
若之前没有进行过微信学生认证，需要在微信相关页面填写信息，先完成微信端认证
---

### 路径二认证流程说明

#### (1) 前提情况说明
若之前……（请在此补充“若之前……”的具体情况，如：已在学信网完成过学籍备案/未在微信绑定过学生身份等）

#### (2) 微信学生认证操作流程
1. 进入微信学生认证页面，按要求填写本人基本学生信息。
2. 页面自动跳转进入**中国高等教育学生信息网（学信网）**。
3. 登录后进入 **「学信档案」** 板块，点击 **「在线验证报告」**。
4. 找到 **「教育部学籍在线验证报告」**，点击右侧的 **「查看」**。
5. 选择对应在读的高校信息，再次点击 **「查看」**。
6. 系统完成信息校验与授权，返回微信即完成基础学生认证。

> **💡 温馨提示**：
> 上述第 (2) 步的学信网验证过程中，页面全程配有**自动指导助手**浮窗，按其动态提示一步步点击即可，无需手动复制复杂的验证码。

#### (3) WorkBuddy 学生验证与领奖
完成微信基础认证后，返回微信内的 **WorkBuddy 学生验证** 界面，页面提供两种核验方式：
- **方式 A（学信网认证）**：手机装有「学信网 App」直接选择此项，一键调起 App 完成授权。
- **方式 B（支付宝认证）**：未安装学信网 App 可选此项。系统将调起支付宝，通过支付宝自带的学生身份认证及学信网内置插件快速核验。

认证成功后，系统即刻到账 **1000 积分**。

---

### 认证流程图

```mermaid
flowchart TD
    Start([开始：进入微信学生认证]) --> Step1[填写学生基本信息]
    Step1 --> Step2[跳转至学信网登录]

    subgraph GuideBox [学信网操作流程（全程配有自动指导助手）]
        Step2 --> Step3[进入【学信档案】]
        Step3 --> Step4[点击【在线验证报告】]
        Step4 --> Step5[点击【教育部学籍在线验证报告】并查看]
        Step5 --> Step6[选择对应学校点击【查看】]
        Step6 --> Step7[完成微信基础学生认证]
    end

    Step7 --> BackToWB[返回微信 WorkBuddy 学生验证页面]

    BackToWB --> Choice{选择认证方式}

    Choice -- 手机已安装学信网 App --> ModeA[学信网认证]
    ModeA --> AuthA[调起学信网 App 快捷授权]

    Choice -- 未安装学信网 App --> ModeB[支付宝认证]
    ModeB --> AuthB[调起支付宝学生认证<br/>+ 支付宝学信网插件核验]

    AuthA --> Success([认证成功：领取 1000 积分])
    AuthB --> Success([认证成功：领取 1000 积分])

