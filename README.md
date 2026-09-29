# Kubez-ansible-EulerOS

`kubez-ansible-EulerOS` 是面向 **Huawei Cloud EulerOS（HCE）** 定制的 [kubez-ansible](https://github.com/pixiu-io/kubez-ansible) 分支项目，用于在 Huawei Cloud EulerOS 上快速部署 Kubernetes 集群及云原生应用。

![Build Status][build-url]
[![License][license-image]][license-url]

## 项目介绍

面向 **Huawei Cloud EulerOS（ID=`hce`）** 定制。

其它发行版请使用上游项目：[pixiu-io/kubez-ansible](https://github.com/pixiu-io/kubez-ansible)。

## 配置项

需增加一个自定义配置：key：`containerd_package_rpm`，value：`containerd`。

## 学习分享

- [go-learning](https://github.com/caoyingjunz/go-learning)

## 沟通交流

- 搜索微信号 `yingjuncz`, 备注（github）, 验证通过会加入群聊
- [bilibili](https://space.bilibili.com/3493104248162809?spm_id_from=333.1007.0.0) 技术分享

Copyright 2019 caoyingjun (cao.yingjunz@gmail.com) Apache License 2.0

[build-url]: https://github.com/gopixiu-io/kubez-ansible/actions/workflows/ci.yml/badge.svg
[license-image]: https://img.shields.io/badge/license-Apache%202-4EB1BA.svg
[license-url]: https://www.apache.org/licenses/LICENSE-2.0.html
