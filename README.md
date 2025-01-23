### 功能概述总结

1. **用户注册与登录**
2. **应急预案创建与查询**
3. **事件记录创建与查询**
4. **安全检查记录创建与查询**
5. **JWT认证与权限管理**
6. **日志记录（系统和工作日志）**
7. **登录尝试记录与账户禁止机制**


### 项目功能概述

1. **用户管理**
   - **用户注册**: 新用户可以注册账号，并在注册过程中生成SM2密钥对。
   - **用户登录**: 用户可以使用用户名进行登录，系统会返回一个JWT令牌用于后续认证。
   - **刷新Token**: 用户可以使用现有的JWT令牌来获取一个新的令牌，延长会话时间。

2. **应急预案管理**
   - **创建应急预案**: 用户可以创建新的应急预案，包括预案详情、版本号和状态。
   - **获取应急预案**: 用户可以通过应急预案ID获取特定的应急预案详情。

3. **事件管理**
   - **创建事件记录**: 用户可以记录新的事件，包括事件信息、处理状态、响应日志、事件级别和分配资源。
   - **获取事件记录**: 用户可以通过事件ID获取特定的事件详情。

4. **安全检查管理**
   - **创建安全检查记录**: 用户可以记录新的安全检查，包括检查记录、问题跟踪、改进建议状态和评估报告。
   - **获取安全检查记录**: 用户可以通过安全检查ID获取特定的安全检查详情。

5. **认证与授权**
   - **JWT认证**: 使用JWT Token进行用户身份验证，确保API请求的安全性。
   - **权限控制**: 仅允许具有适当权限的用户执行某些操作，如创建用户等。

6. **日志记录**
   - **系统日志**: 记录系统操作，包括操作类型、操作员ID、操作内容和结果等。
   - **工作日志**: 记录用户的工作进展、日志内容、文件引用等。

7. **登录尝试记录**
   - **记录登录尝试**: 记录用户的登录尝试，包括尝试时间、IP地址和是否成功等。
   - **账户禁止机制**: 如果用户多次尝试登录失败，账户将被暂时禁止登录。


## 环境配置以及API文档均在setup目录下，请自行阅读
