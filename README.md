# TWGC项目孵化

## 流程
1. 创建提案
    - 根据[提案模板](proposal-template.md)，在本仓库创建PR
    - 生成PR：复制并改写模板文件，放置在`proposals`目录下
1. Request for Comment 项目公示，让尽可能多的人参与讨论，形式包括但不限于
    - 在线会议：如果可能，建议在TWGC双周会以及其他由TWGC管理的公开会议讨论
    - 线下：包括但不限于RocketChat，邮件列表，微信群
1. 至少两位组长批准Approve后，正式加入TWGC
    - 如果特殊情况下组长无法表决（包括缺席，明显的利益冲突），可以由常务组员Active Volunteer代替
    - Merge PR，然后提案者与TWGC协作进行项目归属迁移

## 审核项
- 需要符合Hyperledger的项目范围
- 符合Hyperledger的[守则Code of Conduct](https://wiki.hyperledger.org/display/HYP/Hyperledger+Code+of+Conduct)
- 有明确的产出物
- 其他记录在提案模版中的要求和审核项

## 项目加入TWGC之后
- Hyperledger项目需要启用DCO BOT
    - DCO BOT 配置于 `Settings -> Branches -> Branch protection rules`
    - 每一个提交都需要签名以满足DCO校验
- CICD工具，请优先考虑采用Github Actions
    - [TWGC在Azure的工作空间](https://dev.azure.com/Hyperledger/TWGC)，正在逐步迁移到Github Actions
### 项目状态Badge 素材
![](https://img.shields.io/badge/%E9%A1%B9%E7%9B%AE%E7%8A%B6%E6%80%81-%E6%B4%BB%E8%B7%83Active-green)

![](https://img.shields.io/badge/%E9%A1%B9%E7%9B%AE%E7%8A%B6%E6%80%81-%E5%BD%92%E6%A1%A3Archived-lightgrey)
