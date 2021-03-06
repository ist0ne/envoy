# 配置参考

- [概述 (v1 API)](overview/v1_overview.md)
- 概述 (v2 API)
  - [Bootstrap 配置](overview/v2_overview.md#bootstrap-configuration)
  - [示例](overview/v2_overview.md#example)
  - [管理服务器](overview/v2_overview.md#management-server)
  - [聚合发现服务](overview/v2_overview.md#aggregated-discovery-service)
  - [无法连接管理服务器](overview/v2_overview.md#management-server-unreachability)
  - [状态](overview/v2_overview.md#status)
- 监听器
  - [统计](listeners/stats.md)
  - [运行时](listeners/runtime.md)
  - [监听器发现服务(LDS)](listeners/lds.md)
- 监听过滤器
  - [原始目的地](listener_filters/original_dst_filter.md)
  - [TLS 检查器](listener_filters/tls_inspector.md)
- 网络过滤器
  - [客户端 TLS 身份认证](network_filters/client_ssl_auth_filter.md)
  - [Echo](network_filters/echo_filter.md)
  - [Mongo 代理](network_filters/mongo_proxy_filter.md)
  - [频率限制](network_filters/rate_limit_filter.md)
  - [Redis 代理](network_filters/redis_proxy_filter.md)
  - [TCP 代理](network_filters/tcp_proxy_filter.md)
- HTTP 连接管理器
  - [路由匹配](http_conn_man/route_matching.md)
  - [流量迁移和拆分](http_conn_man/traffic_splitting.md)
  - [HTTP header 控制](http_conn_man/headers.md)
  - [HTTP header 清理](http_conn_man/header_sanitizing.md)
  - [统计](http_conn_man/stats.md)
  - [运行时](http_conn_man/runtime.md)
  - [路由发现服务（RDS）](http_conn_man/rds.md)
- HTTP 过滤器
  - [Buffer](http_filters/buffer_filter.md)
  - [跨域资源共享](http_filters/cors_filter.md)
  - [DynamoDB](http_filters/dynamodb_filter.md)
  - [故障注入](http_filters/fault_filter.md)
  - [gRPC HTTP/1.1 桥](http_filters/grpc_http1_bridge_filter.md)
  - [gRPC-JSON 转码](http_filters/grpc_json_transcoder_filter.md)
  - [gRPC-Web](http_filters/grpc_web_filter.md)
  - [Gzip](http_filters/gzip_filter.md)
  - [健康检查](http_filters/health_check_filter.md)
  - [IP 标签](http_filters/ip_tagging_filter.md)
  - [Lua](http_filters/lua_filter.md)
  - [频率限制](http_filters/rate_limit_filter.md)
  - [路由器](http_filters/router_filter.md)
  - [Squash 调试](http_filters/squash_filter.md)
- 集群管理
  - [统计](cluster_manager/cluster_stats.md)
  - [运行时](cluster_manager/cluster_runtime.md)
  - [集群发现服务](cluster_manager/cds.md)
  - [健康检查](cluster_manager/cluster_hc.md)
  - [熔断](cluster_manager/cluster_circuit_breakers.md)
- 健康检查
  - [Redis](health_checkers/redis.md)
- 访问日志
  - [配置](access_log.md#configuration)
  - [格式规则](access_log.md#format-rules)
  - [缺省格式](access_log.md#default-format)
- 频率限制服务
  - [gRPC 服务接口描述语言](rate_limit.md#grpc-service-idl)
- 运行时
  - [文件系统布局](runtime.md#file-system-layout)
  - [注释](runtime.md#comments)
  - [使用符号链接切换的方式进行运行时数值更新](runtime.md#updating-runtime-values-via-symbolic-link-swap)
  - [统计](runtime.md#statistics)
- 统计
  - [服务器](statistics.md#server)
  - [文件系统](statistics.md#file-system)
- [路由表检查工具](tools/router_check.md)