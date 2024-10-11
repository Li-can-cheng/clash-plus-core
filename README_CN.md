<h1 align="center">
  <img src="https://github.com/Dreamacro/clash/raw/master/docs/logo.png" alt="Clash" width="200">
  <br>Clash<br>
</h1>

<h4 align="center">基于规则的 Go 语言隧道工具。</h4>

<p align="center">
  <a href="https://github.com/Dreamacro/clash/actions">
    <img src="https://img.shields.io/github/actions/workflow/status/Dreamacro/clash/release.yml?branch=master&style=flat-square" alt="Github Actions">
  </a>
  <a href="https://goreportcard.com/report/github.com/Dreamacro/clash">
    <img src="https://goreportcard.com/badge/github.com/Dreamacro/clash?style=flat-square">
  </a>
  <img src="https://img.shields.io/github/go-mod/go-version/Dreamacro/clash?style=flat-square">
  <a href="https://github.com/Dreamacro/clash/releases">
    <img src="https://img.shields.io/github/release/Dreamacro/clash/all.svg?style=flat-square">
  </a>
  <a href="https://github.com/Dreamacro/clash/releases/tag/premium">
    <img src="https://img.shields.io/badge/release-Premium-00b4f0?style=flat-square">
  </a>
</p>

## 功能

以下是 Clash 提供的功能概述：

- 入站：HTTP、HTTPS、SOCKS5 服务器、TUN 设备
- 出站：Shadowsocks(R)、VMess、Trojan、Snell、SOCKS5、HTTP(S)、Wireguard
- 基于规则的路由：动态脚本、域名、IP 地址、进程名称等
- 伪造 IP DNS：减小 DNS 污染影响，提高网络性能
- 透明代理：自动管理路由表/规则，重定向 TCP 和 TProxy TCP/UDP
- 代理组：自动回退、负载均衡或延迟测试
- 远程提供者：动态加载远程代理列表
- RESTful API：通过综合 API 实时更新配置

*有些功能可能仅在 [Premium 核心](https://dreamacro.github.io/clash/premium/introduction.html) 中可用。*

## 文档

最新文档可在 [https://dreamacro.github.io/clash/](https://dreamacro.github.io/clash/) 找到。

## 致谢

- [riobard/go-shadowsocks2](https://github.com/riobard/go-shadowsocks2)
- [v2ray/v2ray-core](https://github.com/v2ray/v2ray-core)
- [WireGuard/wireguard-go](https://github.com/WireGuard/wireguard-go)

## 许可证

本软件按 GPL-3.0 许可证发布。

[![FOSSA 状态](https://app.fossa.io/api/projects/git%2Bgithub.com%2FDreamacro%2Fclash.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2FDreamacro%2Fclash?ref=badge_large)