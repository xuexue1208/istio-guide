# istio 实践指南

[序言](README.md)

# 最佳实践

- [优雅终止](best-practices/graceful-shutdown.md)
- [性能优化](best-practices/optimize-performance.md)
- [为服务显式指定协议](best-practices/specify-protocol.md)
- [为服务设置默认路由](best-practices/set-default-route.md)

# 用法实践

- [配置 accesslog](usage/configure-accesslog.md)
- [使用 corsPolicy 解决跨域问题](usage/cors.md)
- [基于 iphash 进行负载均衡](usage/iphash.md)
- [使用 websocket 协议](usage/websocket.md)

# 实用技巧

- [设置 max_body_size](trick/set-max-body-size.md)
- [实现基于 Header 的授权](trick/header-authorization.md)
- [利用 Prism 构造多版本测试服务](trick/multi-version-test-service-with-prism.md)
- [隐藏自动添加的 server header](trick/hide-server-header.md)
- [调试技巧](trick/debug.md)
- [自定义 proxy 日志级别](trick/customize-proxy-loglevel.md)
- [局部启用 accesslog](trick/partially-enable-accesslog.md)

# 常见问题

- [Sidecar 停止问题](faq/sidecar-shutdown.md)
- [Sidecar 启动顺序问题](faq/sidecar-startup-order.md)
- [Smart DNS 相关问题](faq/smart-dns.md)
- [HTTP Header 大小写问题](faq/the-case-of-http-header.md)
- [httpHeaderName 大写导致会话保持不生效](faq/uppercase-header-causes-sticky-sessions-to-not-work.md)
- [链路追踪相关问题](faq/tracing.md)
- [Sidecar 注入相关问题](faq/sidecar-injection.md)
- [默认的重试策略导致非幂等服务异常](faq/retries-for-non-idempotent-services.md)
- [多集群相关问题](faq/multicluster.md)
- [应用未监听 0.0.0.0 导致连接异常](faq/listen-any.md)
- [VirtualService 路由匹配顺序问题](faq/vs-match-order.md)
- [headless service 相关问题](faq/headless-svc.md)

# 故障排查

- [排障案例](troubleshooting/cases/README.md)
  - [使用 apollo 的 java 应用启动报 404](troubleshooting/cases/apollo-on-istio.md)
- [VirutualService 不生效](troubleshooting/virtualservice-not-working.md)
- [Envoy 报错: gRPC config stream closed](troubleshooting/grpc-config-stream-closed.md)
- [熔断不生效](troubleshooting/circuit-breaking-not-work.md)
- [地域感知不生效](troubleshooting/locality-lb-not-working.md)
- [istio-init crash](troubleshooting/isito-init-crash.md)
- [状态码: 431 Request Header Fields Too Large](troubleshooting/431-status-code.md)
- [状态码: 426 Upgrade Required](troubleshooting/426-status-code.md)
- [状态码: 404 Not Found](troubleshooting/404-status-code.md)
