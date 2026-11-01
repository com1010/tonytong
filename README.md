# TonyTong.cc - Tony Tong 唐仪 官方网站

Tony Tong (唐仪) 的个人官方网站源码 —— 静态站点，托管于 Cloudflare Pages（tonytong.cc / www.tonytong.cc / itong.cc）。

## 页面结构

| 路径 | 内容 |
|---|---|
| `/` | 首页 - Tony Tong 唐仪个人简介、著作与链接入口 |
| `/guilin/` | 桂林家人的自传 · 唐家梁家的故事 - 唐楚三《从海武田飞出的歌》《似水流年》、唐滔《天使投资》 |
| `/guilin/tangying/` | 唐星文（唐莹）《梅花香自苦寒来 - 我与我的亲人》 |
| `/rudao.html` | RuDao 儒道 - Beyond the Art of War 书籍介绍（正式站：https://rudao.org） |
| `/news.html` | 新闻与动态 |
| `/1college.html` | 1College 相关页面 |

## 技术说明

- 纯静态 HTML / CSS / JavaScript，无构建步骤
- 部署方式：Cloudflare Pages 项目 `tonytong`，**已连接本仓库 `com1010/tonytong` 的 `main` 分支（Git 自动构建）** —— 向 `main` push 即自动发布
- Pages 构建设置：Framework = None，Build command 留空，Build output directory 留空（仓库根目录即站点根目录）
- 也可手动直传：`npx wrangler pages deploy . --project-name=tonytong --branch=main --commit-dirty=true`
- 图片资源位于 `assets/` 与 `guilin/images/`

## 相关站点

- RuDao.org - https://rudao.org （源码仓库：com1010/rudao）
- HKBA.net - https://hkba.net
- Com2000.org - https://com2000.org
- AIEEE.net - https://aieee.net

## 版权

Copyright © 2026 by TonyTong.cc 唐仪. All rights reserved.
