# 前端开发常用命名

## 命名原则： 优雅 易读  统一
```css
<style>
table td:first-of-type {
    width: 4cm;
}
table td:nth-of-type(2) {
    width: 7cm;
}
table td:nth-of-type(3) {
    width: 16em;
}
</style>
```

## 函数-func 
| zn | en | pro |
| --- | --- | --- | 
| 跳转路由 | **goto()** | verb
| 初始化请求函数 |  **initEditor()**|verb
| 拉取初始请求 | **queryDetailById(id)**| verb
| 提交等触发事件命名 | **handleXXX()** | verb
| 更新 新增XXX | **updateXXX()** | verb
| 查找XXX | **findXXX()**  |  verb
| 转换  | **converToXXX()** ｜**transformXXX()**  |  verb
| 还原| **restoreXXX()**| verb
| 重新分配制作使...| **makeXXX()**|verb
| 生成| **generateXXX**| verb
| 组合 | **pair**| verb
| 包含,是否存在|**containXXX()**| @boolern
|判断是否是| **checkIfXXX()**| @boolern
|格式化|**reformat()**| verb
## 字段-field
| zn | en | pro |
| --- | --- | --- |
| 数据源| **dataSource** | noun
|参数| **params** | noun
| 表单: 提交集合| **fileds** | noun
|集合 区间| **sets**｜ **section**| noun
| 队列|**queue** | noun
| 迭代器 | **iterator** | noun |
| 匹配的xx | **matched**| noun|
| 数字| **digits**| noun
| 字符| **chars**| noun
| 元素| **element**| noun
|找到了|**found** | adj 布尔  PS: 使用过去式作为结果 例如 checked 
| 可用资源| **sourceAvailable**| adj 布尔
| 重复的| **duplicate** | adj
| 独自的 唯一的| **uniq** ｜**single**| adj
| 共同的| **common**| adj
|分离| **exract** |verb
|计数,统计,计算| **count**| verb
| 交换| **exchange** | verb
## 文件夹-文件-file-folder

| zn | en | pro |
| --- | --- | --- |
| 脚本| **scripts**| noun
| 文档:|**docs**| noun
|打包输出文件夹 | **build**| noun
|工具| **util**| noun
|枚举| **enum** | noun
|配置命名| ***xxx-setting***| noun
## Feature Request
* 请直接提 issue 来增加需要添加的新功能或单词列表