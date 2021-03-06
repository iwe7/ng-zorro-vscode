# 关于 `2.x` 版本

当前 ng-zorro-antd 0.7.x 有很多破坏性变更，且还处于 beta 当中，因此所有 `2.x` 版本暂时不在 vscode 市场上更新，若你希望使用它，请从这里[下载](https://github.com/cipchk/ng-zorro-vscode/blob/dev/ng-zorro-vscode-2.0.0-beta.1.vsix)本地安装。本次主要变更：

- 简化关键词，以 `nz-` 开头表示完整代码片断，`nzType` 表示属性

# ng-zorro 的 vscode 代码片断

![Plugin in action](help.gif)

请至[Issuses](https://github.com/cipchk/ng-zorro-vscode/issues)提交可能遇到的问题或期望增加的代码片断。

## 安装扩展

按 `F1` 输入 `ext install ng-zorro-vscode` 后回车。

## 如何使用?

你可以任意 `.html`、`.ts` 文件，输入 `nz-` 开头会自动出现在智能提醒列表当中；仅此而已！

片断中带有 `attr-` 表示属性，`fn-` 表示事件。

> 建议开启 `"editor.snippetSuggestions": "top"` 配置，可确保代码片断优先级高于内置。

## 文档

更多API接口请参考[ng-zorro-antd](https://github.com/NG-ZORRO/ng-zorro-antd)。


### 常规

Trigger | Description
--- | ---
nz-button | 按钮
nz-button.group | 按钮组
nz-button.icon-text-left | 按钮带图标且文本在左
nz-button.icon-text-right | 按钮带图标且文本在右
nzGhost | 幽灵属性，使按钮背景透明
nz-button.type | 按钮带设置类型
nz-icon.anticon | anticon样式
nz-icon | 图标
nz-icon.spin | 旋转图标

### [ng-alain](https://github.com/cipchk/ng-alain) 片断

Trigger | Description
--- | ---
nz-alain-abc.desc-list | 描述列表
nz-alain-abc.header | 页标题
nz-alain-abc.st | simple-table 简单表格
nz-alain-content | HTML页标题
nz-alain-content.right-input | HTML页标题且右边按钮
nz-alain-content.right-inputgroup | HTML页标题且右边按钮组
nz-alain-modal | 自定义对话框组件所需要的HTML结构
nz-alain-ts.form-get-control | 获取表单字段

### 布局

Trigger | Description
--- | ---
nz-grid.col | 栅格系统：列
nz-grid | 栅格系统
nzAlign | flex 布局下的垂直对齐方式
nzFlex | flex 布局模式
nzGutter | 栅格间隔，支持数字或响应式对象 { xs: 8, sm: 16, md: 24, lg: 32, xl: 32, xxl: 32 }
nzJustify | flex 布局下的水平排列方式
nzLg | ≥992px 响应式栅格，可为栅格数或一个包含其他属性的对象
nzMd | ≥768px 响应式栅格，可为栅格数或一个包含其他属性的对象
nzOffset | 栅格左侧的间隔格数，间隔内不可以有栅格
nzOrder | 栅格顺序，flex 布局模式下有效
nzPull | 栅格向左移动格数
nzPush | 栅格向右移动格数
nzResponsive | 响应式属性
nzSm | ≥576px 响应式栅格，可为栅格数或一个包含其他属性的对象
nzSpan | 栅格占位格数，为 0 时相当于 display: none
nzXl | ≥1200px 响应式栅格，可为栅格数或一个包含其他属性的对象
nzXs | &lt;576px 响应式栅格，可为栅格数或一个包含其他属性的对象
nzXXl | ≥1600px 响应式栅格，可为栅格数或一个包含其他属性的对象
nz-grid.responsive | 响应式栅格系统
nz-grid.row-flex | flex 响应式栅格系统
nz-grid.row | 栅格系统：行
nz-layout | 布局
nz-layout.sider | 布局：侧边栏

### 导航

Trigger | Description
--- | ---
nz-affix | 固钉
nz-affix.target | 固钉：指定滚动容器
nz-breadcrumb | 面包屑
nz-breadcrumb.icon | 面包屑：图标
nz-breadcrumb.item | 面包屑项
nzSeparator | 分隔符自定义
nz-dropdown.button | 下拉菜单按钮
nz-dropdown.button.style | 下拉菜单按钮内风格
nz-dropdown | 下拉菜单
nzClickHide | 点击后是否隐藏菜单
nz-menu | 导航菜单
nz-menu.group | 导航菜单：组
nz-menu.item-divider | 导航菜单：分割线
nz-menu.item | 导航菜单：项
nz-menu.submenu | 导航菜单：子项
nz-pagination | 分页
nzHideOnSinglePage | 只有一页时是否隐藏分页器
nz-steps | 步骤条
nz-steps.step-icon | 步骤条：项带图标
nz-steps.step | 步骤条：项

### 数据录入

Trigger | Description
--- | ---
nz-autocomplete.custom-label | 自动完成：自定义选项
nz-autocomplete.data-source | 自动完成：指定数据源
nz-autocomplete | 自动完成
nz-cascader | 级联选择
nz-checkbox | 多选框
nz-checkbox.group | 多选框组
nz-checkbox.layout | 多选框组布局
nz-form.control-responsive | 表单：控件为响应式
nz-form.control | 表单：控件
nz-form | 表单，向下为表单项
nz-form.explain-error | 表单提示信息带响应式表单错误判断（最多同时只能显示一个）
nz-form.explain | 表单提示信息（最多同时只能显示一个）
nz-form.extra | 表单额外提示信息
nz-form.item | 表单项，向下为标签和控件
nz-form.label-responsive | 表单：标签为响应式
nz-form.label | 表单：标签
nzFormLayout | 表单布局
nzHasFeedback | 是否反馈图标，一般 input 有效
nzValidateStatus | 校验状态，默认自动从 nz-form-control 中的 NgControl 获得校验状态
nz-form.split | 表单：分隔符
nz-form.text | 表单：文本
nz-input.addon-icon | 前后置标签按钮
nz-input.addon-text | 前后置文本按钮
nz-input | 输入框
nz-input.group | 输入框组合
nzAddonAfterIcon | 后置标签按钮，nzAddonAfter的快捷使用方式
nzAddonBeforeIcon | 前置标签按钮，nzAddonBefore的快捷使用方式
nzCompact | 是否用紧凑模式
nzPrefix | 带有前缀图标属性
nzSuffix | 带有后缀图标属性
nz-input.prefix | 带有前缀图标的 input
nz-input.suffix | 带有后缀图标的 input
nz-mention | 提及
nz-number | 数字输入框
nzFormatter | 指定输入框展示值的格式
nzParser | 指定从 nzFormatter 里转换回数字的方式，和 nzFormatter 搭配使用
nzPrecision | 数值精度
nz-radio.button | 单选框按钮风格
nz-radio | 单选框
nz-radio.simple | 单选框最简单的用法
nz-rate | 评分
nzAllowHalf | 是否允许半选
nz-select | 下拉选择器
nzDropdownClassName | 下拉菜单的 className 属性
nzDropdownMatchSelectWidth | 下拉菜单和选择器同宽
nzDropdownStyle | 下拉菜单的 style 属性
nzMaxMultipleCount | 下拉选择器：最多选中多少个标签
nzMode | 下拉选择器：设置 nz-select 的模式
nzNotFoundContent | 下拉选择器：当下拉列表为空时显示的内容
nzOnSearch | 下拉选择器：文本框值变化时回调
nzServerSearch | 下拉选择器：是否使用服务端搜索，当为 true 时，将不再在前端对 nz-option 进行过滤
nzShowSearch | 下拉选择器：使单选模式可搜索
nz-select.option-group | 下拉选择器：组
nz-select.option | 下拉选择器：项
nz-slider | 滑动输入条
nz-switch | 开关
nz-switch.icon | 开关：自定义图标
nz-switch.text | 开关：自定义文本
nz-textarea | 多选文本框
nzAutosize | 多选文本框：自适应内容高度
nz-transfer | 穿梭框
nz-upload | 上传
nz-upload.drag | 上传：拖拽风格
nzBeforeUpload | 上传：上传文件之前的钩子，参数为上传的文件，若返回 false 则停止上传。注意：IE9 不支持该方法；注意：务必使用 &#x3D;&gt; 定义处理方法。
nzCustomRequest | 上传：通过覆盖默认的上传行为，可以自定义自己的上传实现；注意：务必使用 &#x3D;&gt; 定义处理方法。
nzFileList | 上传：文件列表，双向绑定
nzFileType | 上传：限制文件类型
nzFilterLimit | 上传：限制单次最多上传数量，nzMultiple 打开时有效；0 表示不限
nzFilterSize | 上传：限制文件大小，单位：KB；0 表示不限
nzListType | 上传：上传列表的内建样式
nzMultiple | 上传：是否支持多选文件，ie10+ 支持。开启后按住 ctrl 可选择多个文件。
nzShowButton | 上传：是否展示上传按钮
nzShowUploadList | 上传：是否展示 uploadList
nzWithCredentials | 上传：上传请求时是否携带 cookie

### 数据显示

Trigger | Description
--- | ---
nz-avatar | 头像
nz-avatar.icon | 头像：图标
nz-avatar.text | 头像：文本
nz-badge | 徽标数
nz-badge.dot | 徽标数：状态点风格
nzBadgeStatus | 徽标数：设置 nz-badge 为状态点
nzOverflowCount | 徽标数：展示封顶的数字值
nzShowZero | 徽标数：当数值为 0 时，是否展示 Badge
nz-calendar | 日历
nz-card | 卡片
nz-card.extra | 卡片：带右上角的操作区域
nz-card.meta | 卡片：完整内容配置
nzHoverable | 卡片：鼠标移过时可浮起
nzTypeInner | 卡片：层级类型
nz-card.simple | 卡片：最简单使用方法
nz-card.tab | 卡片：带标签风格
nz-carousel | 走马灯
nz-collapse | 折叠面板
nzAccordion | 折叠面板：是否每次只打开一个tab
nzShowArrow | 折叠面板：是否展示箭头
nz-list | 列表，向下为项
nz-list.item-meta | 列表：元素
nz-list.item | 列表：项，向下为元素
nz-list.loadmore | 列表：加载更多示例
nzItemLayout | 列表样式
nzLoadMore | 列表：加载更多
nzPagination | 列表：对应的 pagination 配置
nzRenderItem | 列表：自定义列表项
nz-list.simple | 列表：最简单的用法
nz-popover | 气泡卡片
nz-table | 表格
nzExpand | 表格：可展开
nzFilterMultiple | 表格：是否为多选过滤器
nzFrontPagination | 表格：是否在前端对数据进行分页，如果在服务器分页数据或者需要在前端显示全部数据时传入 false
nzLeft | 表格：左侧距离，用于固定左侧列
nzNoResult | 表格：无数据时显示内容
nzPageIndex | 表格：当前页码，可双向绑定
nzPageSize | 表格：每页展示多少数据，可双向绑定
nzRight | 表格：右侧距离，用于固定右侧列
nzShowCheckbox | 表格：是否添加checkbox
nzShowExpand | 表格：是否显示展开按钮
nzShowFilter | 表格：是否显示过滤
nzShowPagination | 表格：是否显示分页器
nzShowQuickJumper | 表格：是否可以快速跳转至某页
nzShowRowSelection | 表格：是否显示下拉选择
nzShowSizeChanger | 表格：是否可以改变 nzPageSize
nzShowSort | 表格：是否显示排序
nzSort | 表格：当前排序状态，受控模式使用，可双向绑定
nzWidth | 表格：指定该列宽度，表头未分组时可用
nz-tabs | 标签页
nzAnimated | 标签页：是否使用动画切换 Tabs，在 &#x60;nzTabPosition&#x3D;top
nzTabPosition | 标签页：页签位置
nzTabsType | 标签页：页签的基本样式
nz-tabs.tab | 标签页：项
nz-tag | 标签
nzColor | 标签：颜色
nzTagMode | 标签：设定标签工作的模式
nz-timeline | 时间轴
nz-timeline.item | 时间轴：项
nz-timeline.pending | 时间轴：最后一个
nz-tooltip | 文字提示
nzMouseEnterDelay | 文字提示：鼠标移入后延时多少才显示 Tooltip，单位：秒
nzMouseLeaveDelay | 文字提示：鼠标移出后延时多少才隐藏 Tooltip，单位：秒
nz-tooltip.template | 文字提示：自定义内容风格
nz-tree | 树形

### 反馈

Trigger | Description
--- | ---
nz-alert.body | 警告提示：含辅助性文字介绍
nz-alert | 警告提示
nzAlertType | 指定警告提示的样式
nzBanner | 是否用作顶部公告
nzClosable | 默认不显示关闭按钮
nzMessage | 警告提示内容
nzShowIcon | 是否显示辅助图标
nz-popconfirm | 气泡确认框
nzCondition | 气泡确认框：是否直接触发 nzOnConfirm 而不弹出框
nz-modal | 对话框
nz-progress.circle | 进度条：圆风格
nz-progress.dashboard | 进度条：仪表盘风格
nz-progress | 进度条
nz-progress.line | 进度条：线风格
nzProgressStatus | 进度条：状态
nz-spin | 加载中
nzSpinning | 加载中：是否旋转
nzTip | 加载中：当作为包裹元素时，可以自定义描述文案

### 其它

Trigger | Description
--- | ---
nz-anchor | 锚点
nz-anchor.link | 锚点：链接项
nz-back-top | 回到顶部
nz-divider | 分割线
nz-divider.full | 分割线：完整风格

### 通用属性

Trigger | Description
--- | ---
nzActions | 操作组
nzAllowClear | 允许清空
nzAutoFocus | 自动获得焦点
nzBordered | 是否有边框
nzCancelText | 取消文本
nzChange | 变更时回调
nzChecked | 是否被选中
nzClick | 点击项触发
nzDelay | 延迟显示加载效果的时间
nzDescription | 描述内容
nzDisabled | disable 状态
nzExtra | 额外区域
nzGrid | 栅格配置
nzHeader | 头部
nzIndeterminate | 设置选择框 indeterminate 状态
nzLoading | 是否loading效果
nzMax | 最大值
nzMin | 最小值
nzName | 名称
nzOkText | 确认文本
nzOnClose | 关闭时触发的回调函数
nzPlaceHolder | 输入框占位文本
nzPlacement | 位置
nzSelect | 选中时触发
nzSelectChange | 选中时触发
nzShape | 形状
nzSize | 大小
nzStep | 步数
nzTheme | 主题
nzTotal | 总数
nzTrigger | 触发方式
nzType | 类型
nzValue | 值
nzVisible | 显示状态

## 更新日志

见[CHANGELOG.md](CHANGELOG.md)
