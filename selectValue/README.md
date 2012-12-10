select value
=========
测试 `设置下拉框的值为列表中不存在的值`在各浏览器间的差异
### 场景
设置下拉框的值为列表中不存在的值（清空下拉框的值）
### 前提
* 使用select.value = ''
* 设置的值在下拉框中不存在
### 环境
* IE 6-9
* chrome 23.0.1271.95
* firefox 7.0.1
### 结论
* IE清空下拉框的显示，value为空，selectedIndex为-1
* chrome清空下拉框的显示，value为空，selectedIndex为-1
* firefox保持原有选中