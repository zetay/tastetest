mouseout
=========
测试moustout、mouseover在各浏览器间触发的差异
### 场景
默认仅显示菜单标题，当鼠标滑过标题时，显示菜单项；当鼠标移出整个菜单区域时，隐藏菜单项。
### 前提
假设整个菜单的包裹元素为A，在A上绑定事件mouseover和mouseout事件。
### 结论
* 子元素间切换会触发mouseout和mouseover
* ie7对于同行文字间的空白，会认为是body的部分，触发mouseout或mouseover
* ie8视br为节点，触发mouseout或mouseover