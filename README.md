# Readme
A note about Page Table.

### Page Table

一个页中包含2<sup>p</sup>个字节，每一个字节都有一个地址。

统一格式地址数据结构中包含两个字段：统一格式页号和偏移字节数。

统一格式页号 * 2<sup>p</sup> + 偏移字节数 = 统一格式地址

CPU使用统一格式地址，CPU把统一格式地址输入MCU，MUC利用Page Table把统一格式地址转换成实际所在地址，然后把实际所在地址输出给CPU。

### Credits
- Computer Systems: A Programmer's Persepctive, Third Edition
