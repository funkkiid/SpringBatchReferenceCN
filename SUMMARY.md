# Summary

* [Introduction](README.md)
* [Spring Batch介绍](01_introduction/README.md)
   * [背景](01_introduction/11.md)
   * [使用场景](01_introduction/12.md)
   * [Spring Batch架构](01_introduction/13.md)
   * [通用批处理的指导原则](01_introduction/14.md)
   * [批处理策略](01_introduction/15.md)
   * [非官方示例(CVS_MySQL)](01_introduction/Spring_Batch_MySQL.md)
* [Spring Batch 3.0新特性](02_spring_batch_30/README.md)
   * [JSR-352支持](02_spring_batch_30/21.md)
   * [改进的Spring Batch Integration模块](02_spring_batch_30/22.md)
   * [升级到支持Spring 4和Java 8](02_spring_batch_30/23.md)
   * [JobScope支持](02_spring_batch_30/24.md)
   * [SQLite支持](02_spring_batch_30/25.md)
* [批处理专业术语](03_domain_language/README.md)
* [配置并运行Job](04_config_job/README.md)
   * [Configuring a Job](04_config_job/41.md)
   * [Java Config](04_config_job/42.md)
   * [Configuring a JobRepository](04_config_job/43.md)
   * [Configuring a JobLauncher](04_config_job/44.md)
   * [Running a Job](04_config_job/45.md)
   * [Meta-Data 高级用法](04_config_job/46.md)
* [配置Step](05_config_step/README.md)
   * [面向块的流程](05_config_step/51.md)
* [ItemReaders和ItemWriters](06_ItemReaders_ItemWriters/README.md)
   * [ItemReader](06_ItemReaders_ItemWriters/61.md)
   * [ItemWriter](06_ItemReaders_ItemWriters/62.md)
   * [ItemProcessor](06_ItemReaders_ItemWriters/63.md)
   * [ItemStream](06_ItemReaders_ItemWriters/64.md)
   * [代理模式与Step注册](06_ItemReaders_ItemWriters/65.md)
   * [纯文本文件](06_ItemReaders_ItemWriters/66.md)
      * [字段集合](06_ItemReaders_ItemWriters/66_1.md)
      * [FlatFileItemReader](06_ItemReaders_ItemWriters/66_2.md)
      * [FlatFileItemWriter](06_ItemReaders_ItemWriters/66_3.md)
   * [XML条目读写器](06_ItemReaders_ItemWriters/67.md)
      * [StaxEventItemReader](06_ItemReaders_ItemWriters/67_1.md)
      * [StaxEventItemWriter](06_ItemReaders_ItemWriters/67_2.md)
   * [多个输入文件](06_ItemReaders_ItemWriters/68.md)
   * [数据库Database](06_ItemReaders_ItemWriters/69.md)
      * [基于游标的ItemReaders](06_ItemReaders_ItemWriters/69_1.md)
      * [ItemReaders分页](06_ItemReaders_ItemWriters/69_2.md)
      * [数据库ItemWriters](06_ItemReaders_ItemWriters/69_3.md)
   * [重用已有服务](06_ItemReaders_ItemWriters/610.md)
   * [输入校验](06_ItemReaders_ItemWriters/611.md)
   * [不参与持久化的字段](06_ItemReaders_ItemWriters/612.md)
   * [自定义ItemReaders和ItemWriters](06_ItemReaders_ItemWriters/613.md)
      * [自定义ItemReader示例](06_ItemReaders_ItemWriters/613_1.md)
      * [自定义ItemWriter示例](06_ItemReaders_ItemWriters/613_2.md)
* [扩展与并行处理](07_scaling_parallel/README.md)
   * [多线程 Step](07_scaling_parallel/71.md)
   * [并行 Steps](07_scaling_parallel/72.md)
   * [远程分块](07_scaling_parallel/73.md)
   * [分区](07_scaling_parallel/74.md)
* [重复执行](08_repeat/README.md)
* [重试处理](09_retry/README.md)
   * [重试模板](09_retry/91.md)
   * [重试策略](09_retry/92.md)
   * [补偿策略](09_retry/93.md)
   * [监听器](09_retry/94.md)
   * [声明式重试](09_retry/95.md)
* [单元测试](10_unit_test/README.md)
   * [创建一个单元测试](10_unit_test/101.md)
   * [点对点的批处理任务测试](10_unit_test/102.md)
   * [测试各个步骤](10_unit_test/103.md)
   * [测试Step-Scoped组件](10_unit_test/104.md)
   * [验证输出文件](10_unit_test/105.md)
   * [模拟域对象](10_unit_test/106.md)
* [通用批处理模式](11_common_batch_patterns/README.md)
   * [日志项处理和失败](11_common_batch_patterns/111.md)
   * [业务原因手工停止任务](11_common_batch_patterns/112.md)
   * [添加一个Footer记录](11_common_batch_patterns/113.md)
   * [基于ItemReaders的driving query](11_common_batch_patterns/114.md)
   * [多行记录](11_common_batch_patterns/115.md)
   * [执行系统命令](11_common_batch_patterns/116.md)
   * [当没有找到输入时Step处理完成](11_common_batch_patterns/117.md)
   * [将数据传递给Future Steps](11_common_batch_patterns/118.md)
* [JSR352支持](12_jsr352/README.md)
   * [General Notes](12_jsr352/121.md)
   * [Setup](12_jsr352/122.md)
   * [依赖注入](12_jsr352/123.md)
   * [Batch Properties](12_jsr352/124.md)
   * [处理模型](12_jsr352/125.md)
   * [Running a job](12_jsr352/126.md)
   * [Contexts](12_jsr352/127.md)
   * [Step Flow](12_jsr352/128.md)
   * [扩展 JSR-352 批处理作业](12_jsr352/129.md)
   * [测试](12_jsr352/1210.md)
* [Spring Batch Integration模块](13_integration/README.md)
* [附录A](14_A/README.md)
* [附录B](15_B/README.md)
* [附录C](16_C/README.md)
* [术语表](17_glossary/README.md)

