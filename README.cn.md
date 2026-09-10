# cert-manager

[English version](./README.md)

Automatically provision and manage TLS certificates in Kubernetes

![cert-manager](https://repo.x-cmd.io/cert-manager.svg?lang=zh)

## 安装

```sh
x install cert-manager
```

## 代码洞察

合计: **218,695** 行代码（覆盖前 5 种语言、共 **1100** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Go | 180,860 | 34,750 | 20,870 | 938 |
| Yaml | 31,873 | 1,452 | 552 | 101 |
| Json | 2,601 | 0 | 0 | 6 |
| Makefile | 1,821 | 1,410 | 531 | 33 |
| Sh | 1,029 | 648 | 322 | 22 |

## OpenSSF Scorecard 评分

总评分: **8.4 / 10**

评分最低的几项:

- **Packaging** (-1/10) — packaging workflow not detected
- **SAST** (0/10) — SAST tool is not run on all commits -- score normalized to 0
- **Branch-Protection** (-1/10) — internal error: error during branchesHandler.setup: internal error: some github tokens can't read classic branch protect…

## 源代码

- **上游仓库**: <https://github.com/cert-manager/cert-manager>
- **官网**: <https://cert-manager.io>
- **许可证**: Apache-2.0

## 发布

- **最新版本**: `v1.21.1` (2026-07-29)
- **最近提交**: 2026-09-10
- **Release 含资产**: 2 个

## 流行度

- **Star**: 14,075 · **Fork**: 2,445 · **开放 issue**: 3,819 · **贡献者**: 533

## 累计统计

- **发布数**: 255 · **已合并 PR**: 4176 · **开放 PR**: 100 · **已关闭 issue**: 3659 · **开放 issue**: 160 · **提交数**: 11386

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-11 | 0 | 131 | 29 | 16 | 19 | 189 |
| last60d | 2026-07-12 | 1 | 189 | 41 | 25 | 30 | 289 |
| 90d | 2026-06-12 | 5 | 288 | 49 | 31 | 36 | 447 |
| last180d | 2026-03-14 | 10 | 447 | 63 | 57 | 51 | 751 |
| 360d | 2025-09-15 | 24 | 802 | 84 | 125 | 86 | 1460 |
| last720d | 2024-09-20 | 50 | 1202 | 96 | 310 | 122 | 2315 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [cert-manager.crds.yaml](https://github.com/cert-manager/cert-manager/releases/download/v1.21.1/cert-manager.crds.yaml) | 973.7 KiB | `other` |
| [cert-manager.yaml](https://github.com/cert-manager/cert-manager/releases/download/v1.21.1/cert-manager.yaml) | 1010.2 KiB | `other` |

## 改进这些数据

cert-manager 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `cert-manager` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/cert-manager.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260910.yml` · 2026-09-10T22:46:25Z._
