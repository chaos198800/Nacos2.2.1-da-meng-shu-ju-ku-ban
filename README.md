# Nacos 2.2.1 达梦数据库版

## 资源描述

本仓库提供了一个经过修改的 Nacos 2.2.1 版本，特别支持达梦数据库（DM）的配置持久化。原版的 Nacos 仅支持 MySQL 和 Derby 数据库的配置持久化，而本版本在原有的开源 Nacos 基础上进行了源码更改，解决了网上教程中的一些常见问题，并成功测试了达梦数据库的配置持久化功能。

## 主要特性

- **达梦数据库支持**：本版本特别支持达梦数据库的配置持久化，解决了原版 Nacos 不支持达梦数据库的问题。
- **数据库初始化 SQL 脚本**：提供了达梦数据库的初始化 SQL 脚本，方便用户快速配置和使用。
- **源码修改**：在原有开源 Nacos 的基础上进行了源码更改，确保达梦数据库的配置持久化功能稳定可靠。
- **测试验证**：经过测试验证，确保达梦数据库的配置持久化功能正常工作。

## 使用说明

1. **下载资源**：从本仓库下载 Nacos 2.2.1 达梦数据库版的相关文件。
2. **数据库配置**：使用提供的 SQL 脚本初始化达梦数据库。
3. **启动 Nacos**：按照 Nacos 的标准启动流程启动服务，确保配置持久化功能正常工作。

## 注意事项

- 本版本仅适用于需要使用达梦数据库进行配置持久化的用户。
- 在使用过程中，请确保数据库连接配置正确，避免因配置错误导致的服务启动失败。

## 贡献与反馈

如果您在使用过程中遇到任何问题或有任何改进建议，欢迎提交 Issue 或 Pull Request。我们非常乐意与您一起完善这个版本。

---

希望本资源能够帮助您顺利实现 Nacos 与达梦数据库的集成，感谢您的使用！

## 下载链接

[Nacos2.2.1达梦数据库版](https://pan.quark.cn/s/07c410c313fb)