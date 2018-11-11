### [ga-customer-revenue-prediction](https://github.com/shinsonwu/ga-customer-revenue-prediction)

### 会议纪要

#### 2018/11/08号会议纪要

- 参会人员：martin、weinan、Tao、mark
- 主题：喜迎双十一，欢度光棍节，Kaggle [ga-customer-revenue-prediction]比赛碰头会
- 会议内容：
  1. 时间安排（11:59UTC时间）
     - 完整时间剩下3周（11/23队伍合并终止，11/30final submission，12.1-1.31测试结果)
     - **11.08-11.14，第一周，大家各自提交，了解数据基本情况，分享有用的资料，各自做数据处理，以便11.15号（周四晚）大家第二次碰头会**
  2. 数据集更新注意
     - 11.9号，kaggle上会因之前gstore数据存在泄露问题，会更新一份新的数据，预测集和训练集都更新
  3. weinan实验室有一台**64g ram**的工作站，可以帮忙跑数据，因为涉及实验室数据，没办法开放给大家，有需要大家可以提交代码，由weinan代跑。（weinan开发环境已经配好）
  4. 注意事项：
     - 在建模过程中，8g内存的电脑，有可能会出现运行崩溃情况。建议使用kaggle kernal 写代码（kernal ram 16g ）或者自己本地做一些数据压缩的工作再尝试建模
     - 调包可以多尝试一些算法，常见的树模型（sklearn GBDT、RF;XGboost、lightGBM、Catboost等)，大家都可以试试，或者看看kernal上的baseline的一些分享，其他的比赛分享等。
     - 特征工程方面，看看群里其他同学有没有更有经验的，开会的时候再分享下。