---
name: haimate-github-smoke-test
description: 仅当用户明确要求执行 HaiMate GitHub 连通性测试时使用，用于验证技能导入和加载，不处理业务资料。
---

<!-- 本文件用于验证 HaiMate 的 GitHub 技能能否导入 DuMate，不包含业务数据或凭证。 -->

# HaiMate GitHub 连通性测试

当用户明确要求“执行 HaiMate GitHub 连通性测试”时，仅回复：

HAIMATE_GITHUB_SKILL_OK

此技能无需调用工具、访问网络或读写文件。其他请求不使用此技能。
