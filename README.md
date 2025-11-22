# Skipper for Lazycat Platform

## 项目简介

本项目将 [Zalando Skipper](https://github.com/zalando/skipper) 的核心能力移植到 Lazycat 平台,为需要高性能 HTTP 路由与反向代理的团队提供一键部署体验。通过该打包仓库,您可以在 Lazycat 上快速启用 Skipper,并使用自定义配置满足零信任网关、Kubernetes Ingress、微服务编排等场景。

## 主要功能

- 🚦 动态路由与反向代理: 以 eskip 语法定义复杂的匹配、过滤与后端策略
- ☁️ 云原生集成: 支持 Kubernetes Ingress、Service Mesh 以及多集群拓扑
- 🧠 智能流量治理: 通过 predicate 与 filter 组合实现熔断、限流、鉴权、头部重写
- 📈 运维监控友好: 内置 metrics、health、routes 端点,易于接入 Prometheus 与可观测系统
- 🔐 安全能力: 支持 OAuth2、JWT 验证、mTLS 透传等访问控制策略
- ⚙️ 可扩展性: 可通过插件和自定义过滤器扩展行为,同时兼容多种后端协议
- 🚀 Lazycat 一键部署: 利用 Lazycat 平台的编排能力,免去繁琐的 Docker/Helm 安装步骤

## 致谢

- **Zalando Skipper 团队**: 感谢原作者持续维护这一强大的开源路由器
- **开源社区贡献者**: 感谢所有提交补丁、维护文档与示例的开发者
- **Lazycat 平台**: 为 Skipper 提供可靠的打包、升级与运维体验

## 版权说明

- 本仓库提供的 Lazycat 打包与配置遵循 [Apache License 2.0](LICENSE)
- Skipper 上游项目由 Zalando 维护,其授权与额外 notice 详见上游仓库
- pathmux 组件继续沿用 MIT 许可证,相关声明已在 LICENSE 中保留

## 相关链接

- Skipper 官方网站: https://opensource.zalando.com/skipper/
- Skipper 源代码: https://github.com/zalando/skipper
- Lazycat 平台: https://lazycat.app
- eskip 语法与 Filters 参考: https://opensource.zalando.com/skipper/reference/
