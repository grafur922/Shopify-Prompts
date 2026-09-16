# Shopify Prompts

用于 Shopify 店铺搭建、页面采集、主题复刻、商品数据清洗、SKU 导出、分类配置和促销展示的 Prompt 集合。

## 文件说明

- `页面爬取.md`：自主识别并保存网站复刻所需的代表性页面和交互参考。
- `开始复刻.md`：根据参考资料开始复刻 Shopify 主题。
- `商品CSV数据清洗.md`：检查并修复 Shopify 商品 CSV 的导入问题。
- `爬取商品SKU.md`：抓取公开商品和 SKU，并生成 Shopify CSV 与审计结果。
- `创建分类.md`：根据商品属性和网站 taxonomy 配置 Collections、Menus 等 Shopify 原生结构。
- `打折.md`：配置商品折扣及前端优惠展示。

## 使用方式

按实际任务选择对应 Markdown 文件，将其中的 Prompt 复制到 AI 编程工具中，并替换文档中用 `{{...}}` 标记的变量。

这些 Prompt 面向 Shopify 开发和数据处理流程；执行涉及线上店铺的操作前，请先确认目标店铺、主题和数据范围。
