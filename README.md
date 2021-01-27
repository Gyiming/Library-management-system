文文图书管理库操作指南：
第⼀次启动使⽤get访问 / 会创建⼀个root账⼾默认密码123456 所有返回值都是json数据
详情参见附件：接口文档

注册新⽤⼾使⽤put请求 /api/user/registered
修改密码使⽤post请求 /api/user/registered
登⼊ post请求 /api/user/login
管理员修改⽤⼾权限 post请求 /api/user/Authority
获取所有⽤⼾列表get请求/api/user/list
添加图书使⽤put请求/api/book
修改图书数据但是不能修改书名post请求/api/book

删除图书使⽤delete请求/api/book
获取单本图书数据get请求/api/book
获取⼀⻚也就是10条数据get请求/api/book/<int:page>
添加借书数据put请求/api/book/borrow
删除也就是还书delete请求/api/book/borrow