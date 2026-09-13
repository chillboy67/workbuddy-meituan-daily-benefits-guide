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

### 路径二 
微信与学信网/支付宝联合认证（适用于首次或重新认证）

#### 认证流程图

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

