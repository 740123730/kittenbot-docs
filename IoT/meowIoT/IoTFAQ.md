# IoT常见问题解决

`wifi模块好像有点发烫，甚至烫手，这个现象正常吗？`

wifi模块功耗都比较大，只要你wifi模块没有接错线，不用担心wifi发热。不会发热导致烫坏的，表面的金属壳就用用来散热的（可以参考家里路由器外壳也是发烫的）。

`wifi模块怎么更新到2.8固件？`

请参考[wifi固件更新帖子](http://learn.kittenbot.cn/zh_CN/latest/electronics/wifi.html)

`wifi模块更新好难呀，你能帮我更新吗？`

如果看了帖子实在不会更新的友友，可以寄回喵家这边，喵家免费帮你更新固件。但是你需要出来回的运费哦

`我用别家的wifi模块可以实现喵家IoT吗？`

不行，喵家这个Microbit所对应的wifi IoT积木块仅限于喵家的wifi模块

`我已经根据你的帖子操作了，但是实验不成功？`

需要逐一排查

- wifi模块接线接错了

- wifi模块不是2.8最新固件

- Robotbit板子上的电源没有开

- 18650电池没电了

- 在IoT控制面板注册的话题与程序所对应的话题名称不一致

- 路由器名称与密码输错了(严格区分大小写)

- 路由器名称只能是英文字符串（不能含有中文）

- 路由器名称不能有空格