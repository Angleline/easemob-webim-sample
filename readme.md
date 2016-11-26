环信 精简 DEMO

========

说明

--------

+ 访问地址 `/index.html?username={当前用户名}&password={当前用户密码}&touser={目标用户名}`
	当前用户名称可按随意规则定义，若系统中不存在将会自动注册
+ DEMO仅包含文字聊天，请参照环信消息结构自行修改其他格式的内容**#31~#53**
+ WebIM并不支持历史聊天记录，如需要历史聊天记录需要集成http://docs.easemob.com/im/100serverintegration/30chatlog，在通过接口初始化**#170**`$scope.chatlist`变量即可
+ 关于不同聊天对象，需要根据聊天记录完成聊天对象列表及历史信息可完成业务功能业务。此功能请自行制作历史聊天人页面


License
=======

    Copyright 2016 chenhaoangle@gmail.com.

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.