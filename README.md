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

1. 进入微信学生认证页面，按要求填写本人基本学生信息。
2. 页面自动跳转进入**中国高等教育学生信息网（学信网）**。
3. 登录后进入 **「学信档案」** 板块，点击 **「在线验证报告」**。

<img width="720" height="720" alt="2a92b97f71074ae6c813910408cdc4f3" src="https://github.com/user-attachments/assets/9c10b4b6-3930-4067-90d5-8365dd5eebe4" />

4. 找到 **「教育部学籍在线验证报告」**，点击右侧的 **「查看」**。

<img width="1030" height="180" alt="fff076bb6ddf2763156424fbd0745373" src="https://github.com/user-attachments/assets/3effb07f-3fb8-457d-b28e-427a5046c2d2" />

5. 选择对应在读的高校信息，再次点击 **「查看」**。
6. 系统完成信息校验与授权，返回微信即完成基础学生认证。

<img width="792" height="180" alt="9b1be83aa03ad75de643b1b37c47b80d" src="https://github.com/user-attachments/assets/e6438867-e4df-4c76-bca0-de12ce351664" />


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
```

## 3.领取美团优惠券
<img width="1193" height="581" alt="image" src="https://github.com/user-attachments/assets/93633493-1ca6-42c3-a97b-32077921edf3" />

1.点击左侧“专家·技能·连接器”

<img width="917" height="339" alt="image" src="https://github.com/user-attachments/assets/a4aa0032-94a8-4c2d-9094-aceddd98a819" />

2.搜索“美团”
2.点击第一个“美团生活助手”
3.“召唤”
4.运行”帮我领美团优惠券活动“
（若现在是晚上11：00-早上8:00，建议使用hy4preview，不扣积分，其他时间段建议使用hy3，不在意积分者随意）

```mermaid
flowchart TD
    Step1[点击左侧“专家·技能·连接器”] --> Step2[搜索“美团”]
    Step2 --> Step3[点击第一个“美团生活助手”]
    Step3 --> Step4[点击“召唤”]
    Step4 --> Step5{时间与模型建议}
    Step5 -- 晚上11:00-早上8:00 --> M1[建议使用hy4preview，不扣积分]
    Step5 -- 其他时间段 --> M2[建议使用hy3]
    Step5 -- 不在意积分者 --> M3[随意]
    M1 --> Step6[运行“帮我领美团优惠券活动”]
    M2 --> Step6
    M3 --> Step6
    Step6 --> End1([完成领取])
```

## 4.设定每日自动领取美团红包自动化
<img width="1193" height="581" alt="image" src="https://github.com/user-attachments/assets/93633493-1ca6-42c3-a97b-32077921edf3" />

1.点击“定时任务”
2.“添加定时任务”

<img width="777" height="515" alt="image" src="https://github.com/user-attachments/assets/7535a958-bb0f-4d5d-8afd-a1b0f5fcce7d" />

3.名称可以设置为美团，或任意其他，不影响任务进行
4.提示词不能随便写，可以写“帮我领美团优惠券活动”
5.点击提示词下方+号
6.点击“专家”
7.选择“美团生活助手”

<img width="195" height="156" alt="image" src="https://github.com/user-attachments/assets/6a455594-781e-4de1-8124-4c10d79c754f" />

8.设置执行频率，建议每天执行，时间根据个人习惯设定
（建议晚上11：00-早上8:00运行，可以免费使用hy4preview）

```mermaid
flowchart TD
    Step1[点击“定时任务”-“添加定时任务”] --> Step2[设置名称：可以设置为美团，或任意其他，不影响任务进行]
    Step2 --> Step3[填写提示词：不能随便写，可以写“帮我领美团优惠券活动”]
    Step3 --> Step4[点击提示词下方+号]
    Step4 --> Step5[点击“专家”]
    Step5 --> Step6[选择“美团生活助手”]
    Step6 --> Step7[设置执行频率，建议每天执行，时间根据个人习惯设定<br/>（建议晚上11:00-早上8:00运行，可以免费使用hy4preview）]
    Step7 --> End2([完成设定])
```

## 5.每日领取100积分自动化
在直接在输入框输入“帮我去github寻找能够让workbuddy每天自动化签到的项目，并设置定时任务，自动执行”或类似提示词
github有很多优质skill，本文不推荐，鼓励用户自行寻找符合各自要求的内容
