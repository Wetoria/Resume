# 袁辔

## 联系方式

- 手机：15700753351
- Email：vwetoria@gmail.com
- QQ/微信：369708753/vWetoria

## 个人信息

- 袁辔/男/1995
- 本科/湖南涉外经济学院/软件工程/18年毕业
- 工作年限：2年
- 个人博客：wetoria.me
- GitHub：https://github.com/wetoria

## 技能清单

- 熟练使用HTML、CSS、JavaScript、jQuery等技术
- 熟练使用Vue、React等JS框架
- 熟练使用ES6常用新特性
- 熟练使用Ant Design、Element-UI、Kendo-UI等前端UI框架
- 熟练使用Axios、Promise、Asnyc、Ajax等技术进行异步开发
- 熟练使用git进行代码版本控制，管理开发流程。熟悉GitFlow相关理念
- 掌握localStorage、sessionStorage、cookies等前端存储方案
- 熟悉RESTful
- 熟悉Java、SQL、数据库等相关后端开发知识及技能
- 熟悉常用数据结构及算法。完成209道LeetCode
- 了解浏览器同源策略导致的跨域问题
- 了解Webpack、node.js

## 工作经历

[//]: 按照重要性排序

### 上海得逸信息技术有限公司（2018年5月～至今）

#### 华润置地住宅营销生产信息化项目

- 前端开发负责人角色，负责整个系统的前端项目架构、规范制定。负责代码的审计工作，监督并把控前端开发的代码质量。负责项目的前端代码版本控制。
- 前端技术架构为Vue2+Vue-Router+Vuex+Axios+Element-UI。
- 项目采用敏捷开发思想，使用猪齿鱼进行任务管理。在整个项目开发过程中协助项目经理把控整个项目的开发进度，包括业务需求的澄清，将任务分配给相关前后端开发人员，以及协调相关人员把控任务的开发进度。
- 负责房源模块的开发，攻克房间表格合并的功能，实现任意相邻的单元格之间可以进行合并。封装房间销控表组件。销控表在整个系统各个模块中都有使用，封装好的销控表组件，在需要使用时，只需要传递相关的房间表格数据，即可实现房间数据的展示、房间的选择功能、房间单元格的宽度控制、房间表格的高度控制、以及可自定义表格顶部区域。目前满足系统各模块中的相关使用需求。
- 负责项目的性能优化，组件开发。Element-UI 组件库中的 el-table 组合 el-input 使用时，在一次性展示数据较大时，会有较大的渲染性能消耗，主要表现在渲染时间变长，发现问题后采用 contenteditable 来自定义输入功能，并且实现数据变化后的数据绑定，以及数据缓存功能。
- 处理房间数据的排序问题。房间名称包括字母以及数字，需要根据不同的情况按照数字大小或是 Unicode 进行排序。
- 房间销控图的导出。使用 html2canvas，将房间销控图导出为图片格式并下载。以及使用 exceljs 以及 file-saver，将房间表格导出为业务要求的 Excel 文件。
- 针对备案网站复杂的表单进行调研。房间主数据需要在房产局进行备案，并且备案网站只能使用 IE 浏览器，在调研过程中，先分析实现数据自动填充的可能性，接着分析 IE 环境下调用脚本的可能性，最后分析 IE 插件的制作，以及调用脚本自动填充表单的可能性。最后实现在 IE 中，通过点击工具栏的插件按钮，自动填充数据 MVP。
- 处理低版本火狐兼容性的问题。
- 测试价格方案的时间处理逻辑。带头编写测试用例，组织相关人员进行测试。使用 Excel 条件样式，自动检查测试用例完成情况，以及测试结果是否正确。
- 测试价格方案执行生效时间自动处理结果。测试方案用例，使用 SQL 导出结果。
- 修改房间组件的事件响应方式，优化房间组件全选、点击表头选中房间时的性能。当房间数量为2047个时，响应时间从优化前的4分多钟，降低为400毫秒。

#### 华润置地招采SRM项目

- 前端负责人，负责业务需求的实现、代码的审计、前端开发任务的澄清。
- 前端技术架构为React+React Router+Mobx+Axios+Antd。
- 负责附件上传及文件导出功能。在实现了相关导入/导出功能后，封装项目组基础导入导出组件，供整个项目使用，以及为后续相关组件的开发，提供参考。
- 使用 react-quill 实现资源缺口以及信息发布详情的富文本编辑功能，以及在公告展示页面中展示富文本内容。
- 负责项目中公告的编写及展示功能。其中包括富文本的编辑以及公告详情中相关富文本的展示功能。在信息发布、以及资源缺口发布中涉及富文本的编辑功能，在 ISP 门户以及 SRM 招采的公告信息详情中涉及富文本的展示功能。
- 负责信息发布、资源缺口发布的前端数据录入页面，以及实现相关后端的增删查改接口。

#### 华润置地资金计划项目

- 项目组开发人员。复现已知系统缺陷，分析系统缺陷产生原因，在不影响现有系统功能的情况下，修复 BUG，优化相关功能。
- 负责页面表格数据的导入及导出功能。项目使用 HAP 框架技术，前端使用 Kendo-UI，基于两大框架提供的现有 API，实现具体业务需求的导入导出功能。根据 HAP 提供的导入 API 实现导入功能载入数据，并根据业务需求对数据进行转换以及校验。根据 Kendo-UI 提供的 API 实现导出功能，能够按照页面上的 Grid 样式导出相应的 Excel；通过控制单元格的合并，修复部分已合并单元格的样式问题；通过设置 Grid 对应列下单元格样式，来控制导出 Excel 中单元格格式，如设置单元格格式为数字。
- 负责汇总报表统计 SQL 的优化。通过不断删减 SQL，分析现有 SQL 性能瓶颈是查询列中部分字段使用 SELECT 查询得出结果；采用连表操作查询并过滤相关数据，优化后的 SQL 查询时间，缩短为原查询 SQL 的十分之一。

#### 华润置地SMS短信服务平台、华润置地OpenAPI项目、华润置地OSP重塑项目

- 前端负责人。负责前端项目的搭建、开发及维护。
- 负责前端需求的确认，以及提供相关的前端实现方案。

#### 华润置地卡券项目、华润置地人天管理系统

- 前端实习生。
- 初识学习使用React相关开发技术。
- 了解并学习ES6相关新特性。

## 自我评价

- 学习能力优秀。
  - 三天看完118小时Java教学并基本掌握基础开发能力。
  - 具备React相关前端开发知识的前提下，三天看完Vue、Vue Router、Vuex官网教程及指南。
- 出色的问题解决能力，及解决思路。同样的问题，能够快速准确高效的解决。
- CET4。良好的英语阅读能力。
- 爱好折腾。

## 技术文章

- [iOS13正式版更新了，教你如何做时间记录](<https://juejin.im/post/5d846ee7f265da03940243b6>)  
- [微信消息转发以及给指定好友发送消息](<https://juejin.im/post/5d6bda81f265da03c23eecb7>)
- [Vue通用自定义Resize组件](<https://juejin.im/post/5d623de56fb9a06b1777c101>)
- [个人git知识总结](<https://juejin.im/post/5d579bedf265da03f564e0ad>)
- [记一次bug调试过程](<https://juejin.im/post/5d4ba40b51882506563b5571>)  