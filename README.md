auvci是一个集成了git仓库的工作流平台，核心功能是工作流，可以约束研发人员开发上线过程中的行为，通过平台去约束而不是书面规范去约束。
#面对中小企业研发团队简单高效的ci/cd平台。

### 功能列表
1. 权限管理、角色可支持：研发工程师、运维工程师、管理员
2. git仓库管理，可创建空间、项目；角色可支持（owner/master/developer/reporter）,只支持http/https协议拉取提交操作
3. 任务管理
    - 可基于仓库创建分支
    - 可管理任务可操作人员管理
    - 可同一个仓库同时上线串行约束
    - 可支持回滚hook
    - 可一键合并代码
    - 可灵活支持hook编译不同开发语言编译,及各个环节hook自定义操作,编译日志查看
    - 自动创建分支，编译自动打tag，为了更好的同一个任务编译时解决代码依赖版本问题
    - 可支持在线查看文件变化，代码修改变化

![示例图](https://github.com/qiwenilli/auvci/blob/main/demo.jpg)
