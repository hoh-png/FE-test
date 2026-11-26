模仿视频呈现的效果，做一个流利的交流网站页面，也就是说，除了特别说明，视频出现的效果都要做到

效果视频：[fe-test-page-demo.zip](https://github.com/hoh-png/FE-test/releases/latest/download/fe-test-page-demo.zip)（约 105 MB，内含上边栏 / 中间栏 / 左边栏 / 右边栏 / 滚动 / 尾部 共 6 段录屏，视频体积较大，放在 Release 附件中，不在仓库内）

整体要求：
页面滚动时，上边栏时刻保持在屏幕顶部，中间页和右边栏一起随页面滚动，而左边栏未触及尾部时固定不动，触及后一起滚动；
在 上边栏的‘Stack Overflow’/输入框右边的两个按钮/右边栏的复制按钮 悬浮时出现带有小尖角的弹窗，不必做视频中的延迟出现效果；
中间页上方的‘More’处点击后出现选项弹窗；
右边栏靠近页面尾部的几处链接不用做；
所有素材图片可以从下面给出的icon素材网里找替换，尽量表意正确即可；
所有跳转链接跳到https://example.com/ (把视频里鼠标出现可点击样式的地方做跳转，每个相同的组件做一个即可，比如左边栏的几个按钮只用写一个，右边栏的几个‘join’只用写一个)
其他
icon素材网：
https://remixicon.com/
题中所有跳转链接：
https://example.com/

questions/
└── 页面-第一题/
    ├── README.md          # 题目说明、作答入口和运行方式
    ├── index.html
    ├── style.css
    ├── assets/            # 静态资源目录，如图片、字体等
    │   └── img/
    └── script.js