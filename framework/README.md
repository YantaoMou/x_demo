# Framework

基于 uni-app (Vue3) 的前端框架，提供标准化的项目结构和丰富的基础组件。

## 目录结构

```
framework/
├── src/
│   ├── components/       # 通用组件
│   │   ├── basic/       # 基础组件
│   │   ├── business/    # 业务组件
│   │   └── layout/      # 布局组件
│   ├── pages/           # 页面
│   ├── assets/          # 静态资源
│   │   ├── images/      # 图片资源
│   │   ├── styles/      # 样式文件
│   │   └── icons/       # 图标文件
│   ├── utils/           # 工具函数
│   ├── hooks/           # 通用hooks
│   ├── services/        # API服务
│   ├── stores/          # 状态管理
│   └── types/           # TypeScript类型定义
├── public/              # 公共静态资源
└── .vscode/            # VSCode配置
```

## 开发规范

### 命名规范

- 文件夹命名：小写字母，多个单词用下划线连接，如：user_center
- 组件命名：大驼峰，如：UserCenter.vue
- 变量命名：小驼峰，如：userName
- 常量命名：大写字母，下划线连接，如：MAX_COUNT

### 组件开发规范

- 组件必须有明确的职责，遵循单一职责原则
- 组件必须有完整的类型定义和注释
- 组件必须有清晰的props和emits定义
- 复杂组件需要编写使用示例

### 样式规范

- 使用BEM命名规范
- 使用SCSS预处理器
- 遵循移动端适配原则

### Git提交规范

- feat: 新功能
- fix: 修复bug
- docs: 文档更新
- style: 代码格式化
- refactor: 重构
- test: 测试用例
- chore: 构建过程或辅助工具的变动

## 使用说明

### 安装依赖

```bash
npm install
```

### 开发

```bash
# H5
npm run dev:h5

# 微信小程序
npm run dev:mp-weixin
```

### 构建

```bash
# H5
npm run build:h5

# 微信小程序
npm run build:mp-weixin
```

## 组件使用

### 基础组件

- Navbar: 导航栏组件
- Header: 页头组件
- Footer: 页脚组件
- Button: 按钮组件
- Icon: 图标组件

### 业务组件

- UserCard: 用户信息卡片
- VipBadge: 会员徽章
- GenerateRecord: 生成记录项
- VideoPlayer: 视频播放器

## 注意事项

1. 开发时请严格遵循项目规范
2. 组件开发需要考虑可复用性和可维护性
3. 注意性能优化，避免不必要的渲染
4. 保持代码整洁，做好必要的注释