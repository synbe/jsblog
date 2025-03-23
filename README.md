这是一个静态日志管理系统，纯js，不依赖后端服务器，欢迎批评改进！

具备以下功能和特性：

### 功能
- 日历展示：展示当前月份的日历，可切换月份，点击日期显示该日日志，无日志时可创建新日志。
- 日志管理：支持创建、编辑、删除、收藏、复制链接等操作，能按日期筛选日志。
- 搜索功能：可根据关键词搜索日志标题和内容。
- 评论管理：支持对日志添加、编辑和删除评论。
- 标签管理：展示标签云，可按标签筛选日志。
- 插入图片：支持一次性插入本地多张图片，图片将压缩到2M以下并转换成base64编码，同时支持markdown语法插入图片。
- 插入链接：支持[[插入内部日志链接|ohkclt6r75t]]。
- 数据导出：支持将日志数据导出为 JSON 文件，日志数据保存为json。默认读取根目录下./data.js中的json数据并渲染处理。

### 特性
- 响应式设计：页面布局在不同屏幕尺寸下自适应，768px 以下屏幕采用单栏布局。
- 代码高亮：使用 Highlight.js 对代码块进行[[代码高亮]]显示。
- Markdown 解析：使用 marked 解析日志和评论中的 Markdown 内容。
- 用户交互：按钮、标签等元素有交互效果，如悬停变色、显示操作按钮等。

### 使用

- 编辑、提交日志后，导出数据，自动生成并下载data.js文件，放到根目录下（./data.js）即可，
- 纯静态，无需后端服务器，可本地部署，也可在github上静态部署。

### 注意

- 刷新页面前，务必先导出数据！

### 联系

- 邮箱：421103218@qq.com

---


![](./assets/home.png)
