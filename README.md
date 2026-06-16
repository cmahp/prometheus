# Prometheus & Alertmanager ARM64 版本

这是适用于 **Linux ARM64 (鲲鹏机器)** 架构的 Prometheus 和 Alertmanager 二进制文件。

## 版本信息

- **Prometheus**: v3.5.0 (LTS)
- **Alertmanager**: v0.33.0

## 下载地址

请访问 [Releases](https://github.com/cmahp/prometheus/releases) 页面下载对应的二进制文件。

## 文件说明

- `prometheus-3.5.0.linux-arm64.tar.gz` - Prometheus 主程序及工具
- `alertmanager-0.33.0.linux-arm64.tar.gz` - Alertmanager 主程序及工具

## 使用方法

### Prometheus

```bash
# 解压
tar -xvf prometheus-3.5.0.linux-arm64.tar.gz
cd prometheus-3.5.0.linux-arm64/

# 启动
./prometheus --config.file=prometheus.yml
```

### Alertmanager

```bash
# 解压
tar -xvf alertmanager-0.33.0.linux-arm64.tar.gz
cd alertmanager-0.33.0.linux-arm64/

# 启动
./alertmanager --config.file=alertmanager.yml
```

## 系统要求

- Linux ARM64 (aarch64) 架构
- 鲲鹏处理器
