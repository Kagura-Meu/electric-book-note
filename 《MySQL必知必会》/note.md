## 1.基础内容（略, 1-8章）

select, where, sort, 通配符等基础内容跳过

额外内容：

1.where子句：子句中的计算顺序，AND的优先级大于OR

2.通配符：'%'和'\_'，'\_'只匹配一个单个字符

## 2.正则表达式（9章）

```sql
select * from table_a where column_a regexp '1000'
#等同于
select * from table_a where column_a like '%1000%'
```

regexp：代表当前筛选语句使用正则表达式去匹配