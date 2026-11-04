<h1 align="center">躺平</h1>

<p align="center">
  全栈开发 · Web 方向 · 自建服务与性能调优
</p>

<p align="center">
  <a href="mailto:336888@gmail.com"><img alt="Email" src="https://img.shields.io/badge/336888@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white"></a>
  <a href="https://t.me/Kycpr"><img alt="Telegram" src="https://img.shields.io/badge/%40Kycpr-26A5E4?style=flat-square&logo=telegram&logoColor=white"></a>
</p>

---

## 在做什么

| 项目 | 状态 | 说明 |
| :--- | :--- | :--- |
| 老站 PHP → TypeScript 迁移 | `40%` | 上传和支付回调还没迁完 |
| eBPF TCP 重传观测 | `卡住` | [ring buffer 收不到事件](https://github.com/336888/tech-notes/blob/main/ebpf-tcp-retrans.md)，暂时 perf buffer 顶着 |
| homelab 编排重构 | `已完成` | 散装 systemd 收编到 compose，一条命令起停 |
| 日志 syslog → vector | `已完成` | 磁盘占用降了七成，空间终于够用 |

## 仓库

| 仓库 | 说明 | 语言 |
| :--- | :--- | :--- |
| [dev-toolbox](https://github.com/336888/dev-toolbox) | 日常脚本。日志切分、批量改图、清临时文件，写完就没再管过但一直在用 | Shell |
| [homelab-infra](https://github.com/336888/homelab-infra) | 家里那台机器的配置，compose / nginx / 备份脚本 | Docker |
| [web-starter](https://github.com/336888/web-starter) | 开新项目用的模板，省得每次重配 ESLint 和 CI | TypeScript |
| [tech-notes](https://github.com/336888/tech-notes) | 踩坑记录，命令都能直接复制跑 | Markdown |

## 技术栈

| 层次 | 技术 |
| :--- | :--- |
| 前端 | TypeScript · Vue · React · HTML/CSS |
| 后端 | Node.js · Python · Go · PHP |
| 数据 | MySQL · Redis · PostgreSQL |
| 运维 | Linux · Docker · Nginx · CI/CD |

> [!NOTE]
> 上面这些仓库基本都是自己在用，文档不全属正常，有问题直接开 issue。
> 更新不快，但不会删。私人项目，不接外包。

---

<p align="center"><sub>最近一次更新：2026-11</sub></p>
