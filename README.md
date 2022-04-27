# awesome-aws
AWS相关实践文档


## 1.在亚马逊云科技上构建智能湖仓（概念入门）
https://aws.amazon.com/cn/blogs/china/build-intelligent-lake-warehouse-on-amazon-cloud-technology/

https://github.com/dekinsq/awesome-aws/blob/main/AWS%E6%95%B0%E6%8D%AE%E6%B9%96%E5%9C%A8%E7%BA%BF%E7%A0%94%E8%AE%A8%E4%BC%9A.pdf


## 2.开发人员指南-AWS SDK for Java2.x
https://docs.aws.amazon.com/zh_cn/sdk-for-java/latest/developer-guide/home.html

- 使用Amazon S3对象（而Amazon S3内的结构化、非结构化与半结构化数据，则常被用于驱动机器学习、数据科学与大数据处理用例）
  https://docs.aws.amazon.com/zh_cn/sdk-for-java/latest/developer-guide/examples-s3-objects.html#upload-object
- 使用 Amazon Redshift （Amazon Redshift中的高度结构化数据通常负责为交互式查询及高度受信的即时商务智能仪表板提供支持）
  https://docs.aws.amazon.com/zh_cn/sdk-for-java/latest/developer-guide/examples-redshift.html
  
- Amazon QuickSight 提供无服务器功能，可供您轻松创建并发布包含丰富信息的交互式商务智能仪表板。商务分析师们可以使用Athena或Amazon Redshift的交互式SQL接口，通过智能湖仓存储中的数据为QuickSight仪表板提供素材支持
  https://aws.amazon.com/quicksight/
  
- Amazon Redshift 查询

  - 使用您自己的工具查询：Amazon Redshift 为您提供了在控制台内运行查询或连接 SQL 客户端工具、库或数据科学工具（包括 Amazon Quicksight、Tableau、PowerBI、QueryBook 和 Jupyter Notebook）的灵活性
  - 与 Amazon Redshift 交互的简单 API：Amazon Redshift 让您能够轻松访问所有类型的传统、云原生和容器化无服务器 Web 服务型应用程序以及事件驱动的应用程序中的数据。Amazon Redshift Data API 可以通过 AWS 软件开发工具包（例如 Python、Go、Java、Node.js、PHP、Ruby 和 C++）支持的编程语言和平台简化数据的访问、摄取和传出。使用 Data API 后，无需再配置驱动程序和管理数据库连接。您只需调用 Data API 提供的安全 API 终端节点，即可对 Amazon Redshift 集群运行 SQL 命令。Data API 负责管理数据库连接和缓冲数据。Data API 是异步的，因此您可以随后检索结果。您的查询结果可存储 24 小时。
  - 入门文档
    https://docs.aws.amazon.com/zh_cn/redshift/latest/gsg/getting-started.html
  - Amazon Redshift Data API
    https://docs.aws.amazon.com/zh_cn/redshift-data/latest/APIReference/Welcome.html
  
- Amazon Athena 是一种交互式查询服务，让您能够轻松使用标准 SQL 分析 Amazon S3 中的数据(不推荐)
  https://aws.amazon.com/cn/athena/?nc2=type_a&whats-new-cards.sort-by=item.additionalFields.postDateTime&whats-new-cards.sort-order=desc
