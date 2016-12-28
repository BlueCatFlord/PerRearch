#### 测试LTS分布式任务调度
* example-gather：模块提供采集任务接口，传入url参数，进行页面采集，主要用于为tasktracker提供执行任务；
* example-jobclient：用于提交任务参数，即url等参数信息
* example-jobtracker：管理taskTracker，目前不涉及业务逻辑
* example-tasktracker：具体的任务执行角色，用于执行gather动作；