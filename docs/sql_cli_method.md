1）数值函数
（1）round：四舍五入；（2）ceil：向上取整；（3）floor：向下取整
2）字符串函数
（1）substring：截取字符串；（2）replace：替换；（3）regexp_replace：正则替换
（4）regexp：正则匹配；（5）repeat：重复字符串；（6）split：字符串切割
（7）nvl：替换 null 值；（8）concat：拼接字符串；
（9）concat_ws：以指定分隔符拼接字符串或者字符串数组；
（10）get_json_object：解析 JSON 字符串
3）日期函数
（1）unix_timestamp：返回当前或指定时间的时间戳
（2）from_unixtime：转化 UNIX 时间戳（从 1970-01-01 00:00:00 UTC 到指定时间的
秒数）到当前时区的时间格式
（3）current_date：当前日期
（4）current_timestamp：当前的日期加时间，并且精确的毫秒
（5）month：获取日期中的月；（6）day：获取日期中的日
（7）datediff：两个日期相差的天数（结束日期减去开始日期的天数）
（8）date_add：日期加天数；（9）date_sub：日期减天数
（10）date_format：将标准日期解析成指定格式字符串