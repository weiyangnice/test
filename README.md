# GitHub 学习实验仓库 / GitHub Learning Sandbox

> 用途：个人 GitHub 操作练习、仓库规范验证与示例演示。**不存放公司生产代码、客户资料或机密信息。**

## 仓库定位

- **分类**：Personal / Sandbox（个人实验）
- **维护人**：@weiyangnice
- **状态**：初始化 / Learning
- **适合**：练习 Markdown、Issues、Pull Requests、分支、GitHub Actions、版本管理
- **不适合**：公司正式生产项目、凭证、客户数据、广告原片及大型媒体文件

## 常用目录

- `docs/`：学习笔记与仓库操作规范
- `.github/ISSUE_TEMPLATE/`：问题 / 需求模板
- `.github/pull_request_template.md`：PR 模板

## 仓库管理底线

1. 一个真实产品一个仓库，避免按日期、员工随意拆仓库。
2. 生产项目默认私有，并优先放入公司 Organization。
3. 不直接上传 `.env`、API Key、访问令牌、客户数据和大文件。
4. 改动通过分支和 PR 记录；正式版本使用 Release。
5. 每个仓库有 README、负责人、部署说明和交接记录。

## 品播后续规划（提案，尚未创建）

建议创建公司 Organization（名称以可注册为准），有实际开发任务后再建仓库：

| 计划仓库 | 主要用途 |
| --- | --- |
| `pinbono-platform` | 素材生产与业务协同中台 |
| `pinbono-ai-tools` | AI 内容生产与自动化工具 |
| `pinbono-website` | 官网、品牌与课程落地页 |
| `pinbono-data-tools` | 投放数据处理与报表 |
| `pinbono-templates` | 复用型代码模板 |

> 以上为**命名规划**，不是已建成或已开发的产品。

更多细则见 `docs/` 目录。
