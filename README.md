# 我的记账

一个离线优先的个人记账 PWA，数据默认保存在当前浏览器的 IndexedDB 中。

## 在线地址

- 生产站点：https://my-ledger-pwa.vercel.app/
- 源码仓库：https://github.com/Manstkar/my-ledger-pwa

## 当前功能

- 快速记账、编辑和删除账单
- 月度统计与分类统计
- 设置可用余额并自动计算剩余金额
- 存钱目标管理
- JSON 完整备份与恢复
- CSV 导出
- PWA 安装和离线访问
- iPhone 安全区与输入体验适配

## 本地运行

```bash
npm install
npm run dev
```

生产构建：

```bash
npm run build
```

## 发布方式

`main` 分支连接 Vercel。推送到 GitHub 后，Vercel 会自动构建并更新生产站点。

## 数据说明

账单、目标和余额只保存在访问该域名的浏览器中。更换设备、浏览器或域名前，应先在“设置 → 数据管理”中导出 JSON 备份，再在新环境中恢复。
