**项目功能** 

你的demo我push不上去
给你新建了一个 你凑合用一下

- 权限管理：采用Shiro实现功能权限和机构部门的数据控件权限，可控件菜单权限、按钮权限、机构部门权限（数据权限）
- 工作流程引擎：采用主流的activiti流程引擎,在原基础上扩展了动态添加审批人员范围选择、会签节点的动态设置、排它路由条件设置、
              节点可编辑字段设置、节点执行后回调函数、办理任务、驳回到发起人从新发起、退回到上一步、自由跳转、转办等功能。在开发的过程中，
              只需要简单业务流程树，尊守一些规则就可以很方便的使用流程，后面还考虑加入自定义表单，使开发变的更加简单。
- 缓存：使用redis整合shiro自定义sessionDao实现分布式集群共享session
- quartz定时任务：可动态完成任务的添加、修改、删除、暂停、恢复及日志查看等功能
- app接口：基于Json web token (JWT)认证用户信息,使用swagger生成一个具有互动性的api文档控制台。
- 页面交互使用了vue+html和最普通的jsp+jstl标签，两种交互都写了相应的模板，可以选择适合的交互方式。
- 完善的代码生成机制，可在线生成entity、xml、dao、service、html、js、sql代码,可快速开发基本功能代码，能把更多的精力放在问题难点。
- 采用layer友好的弹框，和layerUI相对漂亮的界面，让管理系统系统看起来稍微好看点。