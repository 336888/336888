<h1 align="center">躺平</h1>

<p align="center">
  全栈开发 · 主要写 Web · 晚上折腾自己的服务器
</p>

<p align="center">
  <a href="mailto:336888@gmail.com"><img alt="Email" src="https://img.shields.io/badge/336888@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white"></a>
  <a href="https://t.me/Kycpr"><img alt="Telegram" src="https://img.shields.io/badge/%40Kycpr-26A5E4?style=flat-square&logo=telegram&logoColor=white"></a>
</p>

---

> [!TIP]
> **最近在折腾**
>
> - 给 homelab 换了一套 compose 编排，把之前散装的 systemd 服务都收编了，现在一条命令起停
> - 在啃 eBPF，想写个能看 TCP 重传的小工具，[卡在 ring buffer 那一步](https://github.com/336888/tech-notes/blob/main/ebpf-tcp-retrans.md)，暂时用 perf buffer 顶着
> - 把一个跑了三年的老站从 PHP 往 TypeScript 迁，大概 40%，剩下的是上传和支付回调；顺带把[半夜那次 502](https://github.com/336888/tech-notes/blob/main/nginx-502-callback.md) 的病根找出来了
> - 顺手把日志从 syslog 换到 vector，磁盘占用降了七成

## 仓库

| 仓库 | 是什么 | 语言 |
| :--- | :--- | :--- |
| [dev-toolbox](https://github.com/336888/dev-toolbox) | 日常脚本合集。批量改图、日志切分、清临时文件，写完就没再管过，但一直在用 | Shell |
| [homelab-infra](https://github.com/336888/homelab-infra) | 家里那台机器的配置，compose / nginx / 备份脚本，都是从踩坑里长出来的 | Docker |
| [web-starter](https://github.com/336888/web-starter) | 自己开新项目用的模板，没什么花活，就是省得每次重配 ESLint 和 CI | TypeScript |
| [tech-notes](https://github.com/336888/tech-notes) | 踩坑记录。写给自己看的，里面的命令都能直接复制跑 | Markdown |

## 平时用这些

```text
写得多    TypeScript · Node.js · Vue · Python · Go
写过      PHP · Java
天天用    Linux · Docker · Nginx · MySQL · Redis
```

> [!NOTE]
> 上面这些仓库基本都是自己在用，文档不全很正常，有问题直接开 issue，我看到会回。
> 更新不快，但不会删。私人项目，不接外包。

---

<p align="center"><sub>最近一次更新：2026-11</sub></p>
