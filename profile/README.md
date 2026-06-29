# 企业服务中心 / Enterprise Service Center

面向企业客户的技术赋能服务中心，沉淀客户解决方案、服务手册与交付方法。

## Repository Map

| Repository | Visibility | Purpose |
|---|---:|---|
| [`customer-solutions`](https://github.com/Business-Unit-for-Enterprise-Service/customer-solutions) | private | 企业服务中心客户解决方案与交付方案库 |
| [`requirements`](https://github.com/Business-Unit-for-Enterprise-Service/requirements) | private | 企业服务中心需求池：客户技术赋能、企业资产系统、可信证据链、产业情报与服务产品化需求 |
| [`service-playbooks`](https://github.com/Business-Unit-for-Enterprise-Service/service-playbooks) | private | 企业服务中心服务手册、诊断框架、SOP 与交付模板 |

## Governance

- 具体业务代码、部署和数据资产留在对应 BU。
- 跨 BU 的战略、组合、制度和决策进入 `President-Office`。
- 平台底座和代码生成资产进入 `Business-Unit-for-Platform`。
- 生产部署默认按多机模式设计，数据库/缓存不以 `127.0.0.1` 作为生产默认。

## Naming note

- 因 GitHub 组织名长度限制，保留 `Business-Unit-for-Enterprise-Service`；语义为 Enterprise Service Center。

---

_Last updated: 2026-06-29_
