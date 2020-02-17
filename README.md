# Udacity-Entry-Level_Data-Factors to Patients Who Cancel the Reservation 影响患者按照其挂号预约前往医院就诊的因素
本数据集包含10万条巴西预约挂号的求诊信息，研究病人是否如约前往医院就诊。每行数据录入了有关患者特点的多个数值，包括“性别（Gender）”，“年龄（Age）”， “预约日期 (ScheduledDay)”指患者具体预约就诊的日期；“街区 (Neighborhood) ”指医院所在位置；“福利保障 (Scholarship)”说明病人是否是巴西福利项目 Bolsa Família 的保障人群等；最后一列内容的编码：“No”表示病人已如约就诊，“Yes”说明病人未前往就诊。

笔者主观推测病人的年龄、预约时间和是否是保障人群这三个因素会对患者是否按挂号就诊产生影响。为了验证这个推测，这份报告将着重对这三个因素进行分析，以验证推测。

| ** 步骤 ** | ** 说明** |
| ---------------------------------------- | ---------------------------------------- | 
| 数据导入   | [**未前往就诊的挂号预约**]( https://d17h27t6h515a5.cloudfront.net/topher/2017/October/59dd2e9a_noshowappointments-kagglev2-may-2016/noshowappointments-kagglev2-may-2016.csv)（[Kaggle](https://www.kaggle.com/joniarroba/noshowappointments) 的原始数据） |
| 简介   | 对这个Project作简单介绍 |
| 数据整理 |对数据进行整理和清洗，为下一步分析做准备   |
| 数据分析 | 对三个主观猜测的因素进行分析|
| 结论  | 通过分析得出结论 |

