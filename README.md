# DataAPI

## Summary

基于groupcache提供业务数据cache服务。

<img src="https://github.com/cyber4ron/notes/blob/master/images/data_api_archt.jpg" width="691" height="338">

实际部署一些best practice: 不同业务数据隔离部署（新闻，用户等）；groupcache的cluster模式可降级成standalone模式；db连接池使用bulkhead模式每个后端隔离。

## 对groupcache的修改
<a href="https://docs.google.com/document/d/1v--UOH8MORQZZYfA0h8CwCrNQaUmQeJ_cPk_5pNObeA">[Groupcache] 调研</a>
<a href="https://docs.google.com/document/d/11fE2Tw8QJ2dbMFBa4sOPPfoNvunhZ40eXgSY77g73lk">[Groupcache] 加的features</a>







