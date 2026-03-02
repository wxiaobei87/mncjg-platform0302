# MNCJG Intelligent Remediation Platform

## 📋 项目说明
这是一个基于 React 和机器学习的智能修复平台，用于预测和优化椰壳生物炭/MnOx 复合材料对重金属和有机污染物的吸附性能。

---

## 🚀 快速开始

### 前置需求
- **Node.js** 版本 14.0 或以上
- **npm** 或 **yarn**

### 安装和运行

#### 方式 1：使用 Create React App（推荐）

```bash
# 1. 创建新的 React 项目
npx create-react-app mncjg-platform
cd mncjg-platform

# 2. 将 App.js 复制到 src/ 目录下（替换原文件）
# 复制下载的 App.js 到 src/App.js

# 3. 安装 recharts 库（图表库）
npm install recharts

# 4. 启动开发服务器
npm start
```

浏览器会自动打开 `http://localhost:3000`

#### 方式 2：手动配置项目

```bash
# 1. 创建项目目录
mkdir mncjg-platform
cd mncjg-platform

# 2. 初始化 npm 项目
npm init -y

# 3. 安装所需依赖
npm install react react-dom recharts

# 4. 安装开发工具
npm install --save-dev @babel/preset-react webpack webpack-cli webpack-dev-server babel-loader css-loader style-loader

# 5. 将以下文件放入项目根目录：
#    - index.html
#    - App.js
#    - index.js
#    - package.json

# 6. 启动开发服务器
npm start
```

---

## 📁 项目结构

```
mncjg-platform/
├── public/
│   └── index.html          # HTML 入口文件
├── src/
│   ├── App.js              # 主应用组件（你下载的文件）
│   └── index.js            # React 入口点
├── package.json            # 项目配置和依赖
├── README.md              # 本文件
└── .gitignore            # Git 忽略文件
```

---

## 🎯 功能模块

### 1️⃣ 预测引擎 (Prediction Engine) ⚡
- 交互式参数调整
- 实时预测去除率
- 动力学曲线展示
- pH 响应分析
- SHAP 特征重要性
- 多污染物雷达图

### 2️⃣ 反向设计优化 (Inverse Design) 🎯
- 贝叶斯优化
- 目标去除率设定
- 参数空间搜索
- 收敛曲线分析
- 灵敏度分析

### 3️⃣ 模型基准测试 (Model Benchmark) 📊
- 9 种算法对比
- R² 和 RMSE 评估
- 预测 vs 实际散点图
- 详细性能排名

### 4️⃣ 实验验证 (Experimental Validation) 🧪
- 3 个独立验证场景
- 预测精度统计
- 配对 t 检验
- 实验数据对比

### 5️⃣ 材料分析 (Material Analysis) 🔬
- 5 种材料性能热力图
- 循环稳定性评估
- 文献对标比较

---

## 💻 技术栈

- **React 18.2.0** - UI 框架
- **Recharts** - 数据可视化图表库
- **CSS-in-JS** - 样式管理

---

## 🔧 常见问题

### Q1: 如何安装 Node.js？
**A:** 访问 [nodejs.org](https://nodejs.org/) 下载 LTS 版本并安装

### Q2: 运行时出现 "Module not found" 错误？
**A:** 运行 `npm install` 确保所有依赖已安装

### Q3: 端口 3000 已被占用？
**A:** 可以使用 `PORT=3001 npm start` 指定其他端口

### Q4: 如何构建生产版本？
**A:** 运行 `npm run build` 生成优化的生产文件

---

## 📊 数据信息

- **训练数据**：285 个实验数据点
- **模型算法**：NGBoost (Gradient Boosting)
- **性能指标**：R² = 0.9821, MAPE = 2.8%
- **验证场景**：3 个独立实验

---

## 🎨 主要特性

✨ 深色科技主题  
📱 响应式设计  
🎯 实时交互式预测  
📈 高级数据可视化  
🔍 可解释的 AI (SHAP)  
🚀 贝叶斯优化算法  

---

## 📝 许可证

本项目仅供学术研究和教学使用。

---

## 👤 研究团队

**Wang X.Y. et al.**  
Henan University  
Engineering Research Center for Nanomaterials

---

## 📧 联系信息

如有任何问题或建议，欢迎反馈！

---

**祝你使用愉快！** 🎉
