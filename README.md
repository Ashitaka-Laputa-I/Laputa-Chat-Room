# Laputa-Chat-Room

### **环境**

- Windows 11
- Python 3.12.1
- Sublime Text 3

### **依赖包**

**第三方库**

```
tornado
mysql-connector-python
sqlalchemy
sockjs-tornado
wtforms
werkzeug
```

**安装**

```
pip install -r requirements.txt
```

### 框架

> - manage.py # 入口启动文件, 启动服务
> - app # 存放MTV的包
>   - __init__.py # 初始化模块, 自定义应用
>   - configures.py # 配置信息模块
>   - urls.py # 路由模块
>   - parameters.py # 公共参数模块
>   - models # 模型包
>     - __init__.py # 初始化模块
>     - crud.py # 增删改查操作模块
>     - models.py # 数据表模型模块
>   - templates # 模板目录
>     - layout.html # 公共布局模块
>     - register.html # 注册模块
>     - login.html # 登入模块
>     - userprofile.html # 用户资料模块
>     - chat.html # 聊天室模块
>   - views # 视图包
>     - __init__.py # 初始化模块
>     - register.py # 注册模块
>     - login.py # 登入模块
>     - logout.py # 退出模块
>     - userprofile.py # 用户资料模块
>     - upload.py # 上传个人信息模块
>     - user.py # 用户权限控制模块
>     - common.py # 公共模块
>     - chat.py # 聊天模块
>     - chatroom.py # 聊天室模块
>     - message.py # 消息模块
>   - static # 静态资源目录
>     - css # 层叠样式表
>     - dist # bootstrap依赖文件
>     - images # 图片
>     - js # 客户端脚本
>       - chat.js # websocket聊天
>       - request.js # 请求服务器端
>       - upload.js # 上传图片
>     - pages # 原始模块目录
>     - ueditor # ueditor编辑器
>     - uploads # 图片保存目录
>     - constellation # 星座素材
>   - tools # 工具包
>     - __init__.py # 初始化模块
>     - forms.py # 表单验证模块
>     - orm.py # 数据库连接驱动模块
