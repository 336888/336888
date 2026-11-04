# 躺平

全栈开发，主要在 Web 这一侧。白天写业务代码，晚上折腾自己的服务器。

邮箱 336888@gmail.com ｜ Telegram [@Kycpr](https://t.me/Kycpr)

---

## 最近在折腾

- 给 homelab 换了一套 compose 编排，把之前散装的 systemd 服务都收编了，现在能一条命令起停
- 在啃 eBPF，目标是先写个能看 TCP 重传的小工具，卡在 ring buffer 那块
- 把一个跑了三年的老站从 PHP 往 TypeScript 迁，目前大概 40%，剩下的是上传和支付回调
- 顺手把日志从 syslog 换到 vector，磁盘占用降了七成

## 仓库

| 仓库 | 是什么 |
| --- | --- |
| [dev-toolbox](https://github.com/336888/dev-toolbox) | 日常脚本合集。批量改图、日志切分、清理临时文件这类，写完就没再管过，但一直在用 |
| [homelab-infra](https://github.com/336888/homelab-infra) | 家里那台机器的配置。compose、nginx、备份脚本，基本都是从踩坑里长出来的 |
| [web-starter](https://github.com/336888/web-starter) | 自己开新项目用的模板，没什么花活，就是省得每次重配一遍 ESLint 和 CI |
| [tech-notes](https://github.com/336888/tech-notes) | 踩坑记录。写给自己看的，里面的命令都能直接复制跑 |

## 平时用这些

写得多：TypeScript、Node.js、Vue、Python、Go

写过但不算精：PHP、Java

天天打交道的：Linux、Docker、Nginx、MySQL、Redis

## 几点说明

- 上面这些仓库基本都是自己在用，文档不全很正常，有问题直接开 issue，我看到会回
- 更新不快，但不会删
- 私人项目，不接受赞助，也不接外包
