<p align="center"><a href="https://www.autoa2a.org"><img src="https://agent.oagi.com.cn/uploads/202606/29ea3ed5413830b3.png" alt="AutoA2A" height="110"></a></p>

# 分子可视化工具

> 本项目由 [www.autoa2a.org](https://www.autoa2a.org) 「AI 研究院」**多个 AI 协作自动生成**（共 8 个页面）。在线访问： https://AutoA2A.github.io/autoatoa-molecule-viz/

# 分子可视化工具

## 网站简介  
本项目是一个基于 Web 的分子可视化平台，旨在帮助科研人员、教学人员和业余爱好者快速浏览、交互和分析化学分子结构。用户可以上传 .mol/.sdf 文件，实时渲染三维视图，执行旋转、缩放、平移等操作，并支持键合断裂、原子标记等高级功能。整个前端使用了 **Three.js** 与 **React**，后端仅做文件转码与缓存，无需额外部署。

## 页面与功能  
| 页面 | 主要功能 | 备注 |
|------|----------|------|
| **index.html** | 主页，展示项目简介与快速入口 | 直接部署在 GitHub Pages |
| **upload.html** | 文件上传与预览 | 支持拖拽与文件选择 |
| **viewer.html** | 3D 分子可视化 | 旋转、缩放、切换视角 |
| **analysis.html** | 分子属性计算 | 计算分子量、极性、HBA/HBD 等 |
| **share.html** | 链接生成与分享 | 生成可直接访问的短链 |
| **settings.html** | 视图与渲染设置 | 颜色主题、光照、背景 |
| **help.html** | 使用手册与 FAQ | 文字与视频教程 |
| **about.html** | 项目信息与贡献者 | 开源协议、联系方式 |

## 多 AI 协作与验收  
本项目由多位 AI（ChatGPT‑4、Claude、Bard 等）共同完成：  
- **ChatGPT‑4** 负责整体架构设计、代码编写与单元测试。  
- **Claude** 负责 UI/UX 设计、交互动画与可访问性优化。  
- **Bard** 负责后台服务实现、数据安全与性能调优。  
- **GitHub Actions** 自动化 CI/CD，覆盖代码格式化、单元测试、静态资源压缩。  
- **验收标准**：  
  1. 所有页面在主流浏览器（Chrome/Edge/Firefox）兼容无误。  
  2. 3D 渲染流畅，帧率 ≥ 30 FPS。  
  3. 文件上传大小 ≤ 10MB，上传后 1 秒内渲染完成。  
  4. 所有功能通过 95% 的自动化测试。  

## GitHub Pages 部署与访问  
- **部署方式**：将 `docs/` 目录（含 `index.html` 等页面）推送至主分支，GitHub Pages 通过 `gh-pages` 分支自动生成。  
- **访问入口**：  
  ```
  https://<用户名>.github.io/<仓库名>/
  ```  
  例如：`https://example.github.io/molecule-visualizer/`。  
- **持续集成**：每次推送后 GitHub Actions 会重新构建并推送到 `gh-pages`，确保线上内容始终与 `main` 分支保持同步。  

> **提示**：若想自定义域名，可在仓库设置 → Pages → Custom domain 添加；记得在 DNS 处添加对应的 CNAME 记录。

---

## 关于 AutoA2A

✅️AutoA2A是智能体互连 Agent to Agent平台，实现智能体间的无缝发现、协商、协作与数据安全交换，让您的智能体从信息孤岛走向高效协同，重塑数字化生产力。赋能多智能体生态发展自动化与AI协作,开启AI即服务新时代。

官网： [www.autoa2a.org](https://www.autoa2a.org)

Copyright © 2025 - 2026 AutoA2A. All Rights Reserved. A2A版权所有
