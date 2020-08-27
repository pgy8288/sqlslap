# what about SqlServerSlap v0.1
Author  :   pgy8288         Contact : pgy8288@163.com
parameters surport :
--start-threads=#           启动线程数
--total-queries=#           每线程执行次数
--host=name                 服务器地址，可输入ip或主机名或域名
--username=name             登录账号
--password=name             登录密码
--port=#                    数据库服务器的连接端口号
--pooling=1/0               是否使用数据库连接池
--insert-num=#              插入次数
--update-num=#              更新次数
--delete-num=#              删除次数
--select-num=#              查询次数
--use-param=1/0             是否使用参数代入模式
--dbtype-column-num=#       指定类型的列数,例如：
                --char-column-num=#         char(50)的列数
                --nchar-column-num=#        nchar(50)的列数
                --varchar-column-num=#      varchar(50)的列数
                --nvarchar-column-num=#     nvarchar(50)的列数
                --int-column-num=#          int类型的列数
                --datetime-column-num=#     datetime类型的列数
--auto-create-primary-key=0/1       自动创建主键，默认选择int自增型主键，如果指定以下几项，则根据选择的类型创建主键
                --auto-create-int-primary-key=0/1   自动创建整型自增主键
                --auto-create-string-primary-key=0/1   自动创建字符串型主键
                --auto-create-guid-primary-key=0/1   自动创建GUID主键
--create-database=name      创建数据库的名称，必须要有创建数据库的权限。
--count-record=0/1          执行完毕后，统计记录数
--iteration=#               测试的迭代次数，例如想要测试5次同类型的测试，可输入参数 “--iteration=5”
