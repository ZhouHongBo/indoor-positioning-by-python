* 每个子文件夹包含了一周采集的数据。
* 每个数据集由4个文件表示：RSS、时间戳、位置坐标和样本ID文件。
* 数据集的命名规则是“dddnnttt.csv”，“ddd”是"trn"(train)或"tst"(test)，“nn”是数据集的编号(例"01")，“ttt”是数据的类型("rss"：WiFi指纹数据, "crd"：坐标数据, "tms"：时间戳, "ids"：样本ID)

“95”文件夹与“05”文件夹的区别是，“95”文件夹里的数据采集方向与“05”相反