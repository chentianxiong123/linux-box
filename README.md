# tvbox-linux

嵌入式设备魔改 Linux 系统 — 盒子/手机/路由器统一改造。

## 目录结构

按设备分目录：

### zte-b860av1-t2/
中兴 ZTE B860AV1.1-T2 机顶盒改造
- 芯片: ZX296716 (ARM Cortex-A53, 64位)
- 内存: 990MB RAM
- 存储: 8GB eMMC
- 系统: Android 4.4.2

包含内容：
- `boot/` - boot 镜像（原始 + 无头服务器版本）
- `device/` - 设备配置脚本
- `docs/` - 完整改造文档（01-18）
- `scripts/` - 内核分析与补丁脚本
- `tools/` - 工具脚本

### himv3798-100-hinas/
海纳思 Hi3798MV100 机顶盒改造
- 处理器: Hi3798MV100
- 系统: 海纳思 (hinas)

包含内容：
- `backup/` - 备份脚本
- `hinas_install_uninstall.sh` - 安装卸载脚本
- `install_hi3798mv100_wifi.sh` - WiFi 安装脚本

## 许可证

MIT License
