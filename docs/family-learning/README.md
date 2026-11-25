# 家庭学习用途维护入口 / Family Learning Maintenance

状态：仅文档规划，未开始功能开发、内容修正或部署。

Status: documentation and planning only. No feature development, content fixes, or deployment has started.

## 来源和固定基线

- Fork: [kairyo/cn-math-taxonomy](https://github.com/kairyo/cn-math-taxonomy)
- Upstream: [xiaoyang111222/cn-math-taxonomy](https://github.com/xiaoyang111222/cn-math-taxonomy)
- 检查日期：2026-11-05，Asia/Shanghai。
- 检查及 Fork 初始基线：`972f9bbcf133a5aa5f7b6c1a74f44f7d48600e57`。
- 本次文档分支：`ai/docs/family-learning-plan`。
- 上游许可：[CC BY-NC 4.0](../../LICENSE)。保留上游署名、许可和来源；这些新增文件是 Fork 的规划材料，不是上游已认可的结论。商业用途须另外核对授权。

## 阅读顺序

1. [问题、证据和待办](REVIEW-AND-BACKLOG.zh-CN.md)：保留发现的问题、证据范围和未来验收条件。
2. [家庭使用与数据方案](PLAN.zh-CN.md)：教材适配、小范围试用、GitHub 内容读取和私密学习记录的分层方案。

## 本次授权和停止边界

- 获准建立 Fork，用独立分支和一次文档提交整理发现及方案。
- 只新增本目录中的说明；不改题库、算法、网页、原 README、许可证或现有配置。
- 不合并到 `main`，不向上游提问题或 PR，不启用 Actions、Pages、自动同步或任何部署。
- 不创建数据库或云服务，不生成密钥，不安装依赖，不运行上游脚本。
- 教材版本、目录和实施范围待确认；本文不是继续开发或发布的授权。
- Fork 是公开仓库。禁止加入真实儿童资料、作业照片、成绩、答题记录、家庭档案或凭据。以后私密记录必须在独立私有系统中处理。
- 本目录用 Markdown 台账跟踪事项，不为此开启 Fork 默认关闭的 Issues 功能。

## 后续维护方式（方案，未启用自动化）

- 当前 `main` 保持初始上游基线不动。将来只通过审阅后的 PR 接纳自有修正，不直接推送 `main`。
- 每项工作使用短生命周期 `ai/<type>/<feature>` 分支；一个 PR 一个目标，Conventional Commits，获准后 squash 合并。
- 上游更新单独比较和审查，再在同步分支整合；不要自动同步覆盖自有修正，不改写共享历史。
- 内容审查保留稳定 topic/question ID、原题、修改原因、依据、审核状态和版本。新结论不能抹掉历史结论。
- 给应用使用的数据应固定到经过批准的 commit SHA；不能把正在修改的工作分支当作已审核发布版。
- 新 Issue、PR 和状态说明默认中英双语，事实、授权范围和未验证项保持一致。
- 本次只整理文档；题目错误和其他风险仍然存在。

## English Summary

This public fork is intended as a possible foundation for a non-commercial family learning aid, not as a validated tutor or a complete curriculum. The review is pinned to the commit above. Only this documentation directory is added; all upstream code, data, and configuration remain unchanged.

The backlog records observed content problems and diagnostic limitations without claiming they have been fixed. The proposed architecture separates public, versioned curriculum content from private learner records. No learner data or credentials may be committed to this fork. Textbook alignment, implementation, database provisioning, deployment, upstream communication, and merging require a later decision.
