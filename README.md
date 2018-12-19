# UIpath
国外最为火热的RPA项目工具
# YearlyReport
  1. uipath level3-test的第二题，是登陆测试账号后台，然后在生成的work item数据中筛选符合条件的vendor
  2. 再去查询并下载该vendor的去年每个月的报表合成一张总表，每张报表的表头顺序不一样，每个vendor并不是每个月都有报表
  3. 合成报表之后再上传到平台，生成一个哈希，再把这个哈希填入相应的vendor数据中，并修改该vendor的状态
  4. 主要在解决合并不同表头顺序的excel数据问题，使用mager data table来合并
