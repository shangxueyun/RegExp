### RegExp
JavaScript常规正则

# 匹配数字类型保留两位小数字符串
`
var reg = /^-?\d+(\.\d{1,2})?$/

reg.test('-10.23')
--> true
`
