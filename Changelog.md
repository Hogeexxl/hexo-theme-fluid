### 2019/9/10

- 增加向下滚屏与向顶部滚屏的按钮
- 优化导航栏配置

### 2019/9/9

- 更名为 Fluid 并迁移至 Fluid-dev organization
- 增加一组配置项 `post_meta`，可配置首页一些元素的可见性

### 2019/09/03

- 增加一个配置项 `source_base_path` ，可配置资源文件的父级路径
- 增加覆盖配置功能，彻底解决升级时的配置冲突
- zh_CN.yml 修改为 zh-CN.yml
- 修复 about.md 路径引用问题

### 2019/8/30

- 支持 i18n (zh-Hans,en)
- 修复 #63

### 2019/8/22

- 新增 Utterances、Gitalk 评论系统

### 2019/8/21

- 新增本地搜索功能

### 2019/8/17

- 新增页面右上角的加载进度条
- 新增配置项用于调整主题颜色
- 优化一些样式

### 2019/8/15

- 使用 stylus 重构所有自定义 css
- 新增标签归档、分类归档，重构归档页

### 2019/8/9

- 移动端适配，调整文章和 TOC 左右边

### 2019/8/8

- 文章图片增加阴影效果
- 拆分 page 属性
- 新增 404 页面

### 2019/8/2

- 新增 about 页自定义功能
- 调整 about 页 icon 的配置写法
- 增加百度统计
- 调整 slogan 和标题
- 调整代码高亮样式的优先级
- 移动端优化

### 2019/8/1

- 新增 subtitle 打字机效果
- 优化文章页中锚的效果
- 文章页底部新增支持 HTML 的 custom 区域，可自定义展示赞赏码等内容
- 优化配置文件和目录结构
- package 升级并移至本地

### 2019/7/31

结合 @zkqiang 的优化建议：

- 文章页样式更换为 Github 风格
- 增加页脚备案信息
- 优化配置文件结构
- 页面细节优化

### 2019/6/6

- 完善 archive 渲染逻辑

### 2019/3/15

- 重新设计基本完成，特别感谢 @zhugaoqi 同学的设计指导；
- 将所有第三方库、图片替换为 CDN 引用，极大精简仓库大小；
- 重新设计 archive 渲染逻辑；
- 统一文章页布局，新增文章版权声明；
- 精简页面，配置项;
- 老版本逐渐放弃维护，代码归档在 `v0.9` 分支；

### 2019/1/28

1. _config.yml结构大改，图片路径统一为相对于根目录
2. 可自定义index、archive、post、about页面的顶部图像高度(0 - 100)
3. 文章页顶部图像可统一设置，也可文章内单独设置。优先级：文章内banner_img属性 > 主题配置
4. 新增一种文章页布局，在配置文件中可选(post.layout)
5. 新增默认摘要功能，可配置是否开启、默认字数。优先级：文章内<!-- more -->设置 > 主题配置
6. 可自定义首页文章date、tags是否显示 (@喜欢首页只罗列文章标题的同学)
7. 优化toc、字体尺寸，修复断行错误、图片超宽等问题
8. 优化渲染逻辑，去除冗余js
9. 新增多个bug
