 Case Study I: Association Rules

文件目录：
  AR-CatalogCrossSell.xls
  Association_Rules.ipynb：关联规则分析文件
  fp_association_rules.csv：关联规则结果
  fp_result.csv：FP-growth树
  ReadMe.txt

步骤：
  1. 加载并准备数据
  2. 删除无关特征即'Customer Number'
  3. 构建FP-growth树（min_support=0.1）
  4. 挖掘关联规则（min_threshold=0.7）

程序执行方法：
  1. 通过Colab打开Association_Rules.ipynb，按顺序执行文件
  2. 通过jupyter notebook打开Association_Rules.ipynb，按顺序执行文件