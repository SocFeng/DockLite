# DockLite

轻量级 Docker 管理工具 —— 用更少的资源，完成容器查看、启停与基础运维。

> 仓库刚初始化，后续会持续补齐代码与文档。

## 目标

- 轻量：低依赖、低开销，适合本机与小型服务器
- 易用：常用 Docker 操作一键完成
- 可扩展：预留插件 / API，方便二次开发

## 功能规划

| 模块 | 说明 | 状态 |
|------|------|------|
| 容器列表 | 查看运行中 / 已停止容器 | 规划中 |
| 启停控制 | start / stop / restart | 规划中 |
| 日志查看 | 实时与历史日志 | 规划中 |
| 镜像管理 | 列表、拉取、清理 | 规划中 |
| Web UI | 浏览器可视化管理（可选） | 规划中 |

## 环境要求

- Docker Engine 20.10+
- （开发）Go 1.22+ 或 Node.js 20+（技术栈待定）

## 快速开始

```bash
# 克隆仓库
git clone git@github.com:SocFeng/DockLite.git
cd DockLite

# 后续安装与启动命令将在此补充
```

## 目录结构（规划）

```text
DockLite/
├── README.md
├── docs/           # 设计与使用文档
├── cmd/            # 程序入口（若采用 Go）
├── internal/       # 核心逻辑
└── web/            # 前端界面（可选）
```

## 开发计划

1. 明确技术栈与最小可用版本（MVP）
2. 对接 Docker API / Socket
3. 实现容器列表与启停
4. 补充日志、镜像与文档

## 贡献

欢迎提 Issue / PR。提交前请保持代码风格一致，并补充必要说明。

## License

MIT（待确认后更新）

## 作者

[SocFeng](https://github.com/SocFeng)
