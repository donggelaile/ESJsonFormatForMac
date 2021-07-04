## Fork from [ESJsonFormatForMac](https://github.com/czhen09/ESJsonFormatForMac)

原库已经长时间没有更新, 用Swift导出YYModel/MJExtension的文件基本不能用。因此简单对Swift进行了适配，已经提交pr (不确定是否会合入)。想尝鲜使用下的可以直接在这里下载然后run即可。

## 主要做了以下修改
1. Swift导出支持YYModel/MJExtension
2. OC下对MJExtension导出mapper函数增加 mj_ 前缀
3. key对应的值为数组时将数组的所有元素的key集中到一起再生成model(之前只取数组首元素)

## 顺便对Swift json model 的互相转换做了个简单的性能测试，代码在[这里]()
