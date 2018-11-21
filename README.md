# answer

0. python 3.6 测试成功; mongoDB 3.2 失败(可能是由于和 pymongo 3.7 不兼容)， mongoDB 3.6.9 和 pymongo 3.7 可以兼容并测试成功
1. 将数据存储到 mongoDB中： python main.py --save
2. 从mongoDB中检索符合条件的数据: python main.py --query
