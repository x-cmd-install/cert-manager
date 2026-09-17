# cert-manager

[English version](./README.md)

Automatically provision and manage TLS certificates in Kubernetes

![cert-manager](https://repo.x-cmd.io/cert-manager.svg?lang=zh)

## 安装

```sh
x install cert-manager
```

## 代码洞察

合计: **218,513** 行代码（覆盖前 5 种语言、共 **1101** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Go | 180,743 | 34,920 | 20,899 | 940 |
| Yaml | 31,873 | 1,452 | 552 | 101 |
| Json | 2,601 | 0 | 0 | 6 |
| Makefile | 1,820 | 1,408 | 530 | 33 |
| Sh | 965 | 566 | 306 | 21 |

## OpenSSF Scorecard 评分

总评分: **8.4 / 10**

评分最低的几项:

- **Packaging** (-1/10) — packaging workflow not detected
- **SAST** (0/10) — SAST tool is not run on all commits -- score normalized to 0
- **Signed-Releases** (0/10) — Project has not signed or included provenance with any releases.

## 源代码

- **上游仓库**: <https://github.com/cert-manager/cert-manager>
- **官网**: <https://cert-manager.io>
- **许可证**: Apache-2.0

## 发布

- **最新版本**: `v1.20.4` (2026-09-16)
- **最近提交**: 2026-09-17
- **Release 含资产**: 2 个

## 流行度

- **Star**: 14,083 · **Fork**: 2,450 · **开放 issue**: 3,824 · **贡献者**: 535

## 累计统计

- **发布数**: 257 · **已合并 PR**: 4196 · **开放 PR**: 98 · **已关闭 issue**: 3664 · **开放 issue**: 160 · **提交数**: 11414

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-18 | 2 | 120 | 25 | 12 | 18 | 177 |
| last60d | 2026-07-19 | 3 | 191 | 38 | 24 | 29 | 298 |
| 90d | 2026-06-19 | 7 | 284 | 46 | 32 | 36 | 439 |
| last180d | 2026-03-21 | 12 | 452 | 60 | 52 | 53 | 763 |
| 360d | 2025-09-22 | 26 | 809 | 83 | 124 | 85 | 1471 |
| last720d | 2024-09-27 | 50 | 1212 | 94 | 309 | 121 | 2308 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [cert-manager.crds.yaml](https://github.com/cert-manager/cert-manager/releases/download/v1.21.2/cert-manager.crds.yaml) | 973.7 KiB | `other` |
| [cert-manager.yaml](https://github.com/cert-manager/cert-manager/releases/download/v1.21.2/cert-manager.yaml) | 1010.2 KiB | `other` |

## 改进这些数据

cert-manager 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `cert-manager` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/cert-manager.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260917.yml` · 2026-09-17T05:29:21Z._
