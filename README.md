# README	

选取了一批用户（candidate.txt），以及一批候选资讯内容数据（news_info.csv） 用以推荐给用户。同时提供了这批用户在某 3 天（记为第 N-2 天、第 N-1 天和第 N 天）对资讯内容的多种行为数据，包括点击、完整阅读、评论、收藏、分享等作为训练数据。

请根据候选推荐人 id，生成对用户的推荐结结果，其中每行是一个用户的 推荐结果，格式为“userid,itemid1 itemid2 itemid3 itemid4 itemid5”。每个用户最 多推荐 5 个最可能有行为的资讯 id 且避免重复。

Dataset: [https://www.heywhale.com/mw/dataset/590a9b28812ede32b73ee412](https://www.heywhale.com/mw/dataset/590a9b28812ede32b73ee412)