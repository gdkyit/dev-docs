# REST API 设计指南和用例



## 版本控制
URI应当包含vN，其中N指明版本号。
#### URI Template 
```	
/{version}/
```
#### Example 
```
/v1/
```

## 命名空间
如果在URI中你需要考虑命名空间这个概念，那么应当选择紧邻在version之后的第一个字段。命名空间折射出消费者对于API功能的观点，而不一定是公司本身业务逻辑层级的划分。
#### URI Template 
```	
/{version}/{namespace}/
```
#### Example 
```
/v1/trips/
```
## HTTP行为

## 返回值

## 资源关联

## 单个资源

## 资源

## 相关文章
* [来自于PayPal的RESTful API标准](https://segmentfault.com/a/1190000005924733#articleHeader2)
* [paypal的api设计指南](https://github.com/paypal/api-standards/blob/master/api-style-guide.md)
* [paypal的API设计模式和用例](https://github.com/paypal/api-standards/blob/master/patterns.md)
* [github的api v3](https://developer.github.com/v3/)
