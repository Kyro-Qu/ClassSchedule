# 湖北理工学院 - 个人课表系统 (ClassSchedule)

个人课表 · 2026-2027学年第1学期

## 🌐 在线访问 (GitHub Pages)

课表网页已通过 GitHub Pages 自动部署，可通过以下网址随时随地在手机或电脑浏览器中直接访问：

🔗 **[https://kyroqu.xyz/ClassSchedule/](https://kyroqu.xyz/ClassSchedule/)**  
*(官方默认域名亦可访问：[https://kyro-qu.github.io/ClassSchedule/](https://kyro-qu.github.io/ClassSchedule/))*

*(备用直接访问单页文件：[https://kyroqu.xyz/ClassSchedule/2026_2027_1.html](https://kyroqu.xyz/ClassSchedule/2026_2027_1.html))*

---

## ✨ 功能特性

- **按日与每日速览视图**：
  - 📅 **本周每日速览**：周一至周日一目了然，清晰标记每日上课节数或无课状态。
  - 🏫 **精准教室与排课明细**：明确标注每门课程的实际授课教室（如 J2-501）、时间节次与授课教师。
  - 🎯 **聚焦固定排课**：过滤无固定节次的理论课程，界面简洁专注。
  - 🔔 **非本周预告控制**：默认仅显示当前周实际排课，按需开启非本周课程预告。
- **学周导航与开学日期自定义**：
  - 支持自由切换第 1 到 20 周。
  - 支持在设置中自定义开学第一周周一的日期，自动换算当前学周。
- **自定义日程与课程**：
  - 支持在网页中新增个人自定义日程或实验课程，数据持久化保存在本地浏览器 `localStorage` 中。
- **纯静态 & 响应式适配**：
  - 基于 Tailwind CSS 响应式布局，完美适配手机移动端与桌面端屏幕。
  - 无需任何后端服务支持，极速秒开。

---

## 📂 项目结构

```text
ClassSchedule/
├── 2026_2027_1.html             # 2026-2027第1学期原始课表页面
├── index.html                   # 部署入口主页面 (与 2026_2027_1.html 保持一致)
├── README.md                    # 项目说明文档
└── .gitignore                   # Git 忽略配置
```

---

## 💻 本地运行

纯静态网页，无需编译或安装依赖，双击 `index.html` 或通过任意静态文件服务器打开即可：

```bash
# 使用 Python 启动本地测试服务器
python -m http.server 8080
```
访问 `http://localhost:8080` 即可查看。
