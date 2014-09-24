适用于memcached的同步：1台master n台slave,salve的memcached内容要求与master同步。

设计过程：
1.获取master, slave列表。
2.与master 建立连接
3.获取key
4.获取value
5.与slave建立连接
6.向slave插入key-value
