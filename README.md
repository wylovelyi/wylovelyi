# Hi, I'm wylovely 👋

**Java 后端开发 / 开源贡献者**。日常做 Spring Boot + MyBatis 的企业级业务系统，业余在 Apache、Alibaba 等开源项目里修真实 bug，同时系统学习 AI Agent 与 LangGraph。

> 我提交补丁的流程比较固定：**复现 → 定位根因 → 最小改动 → 补回归测试 → 多环境验证 → 提 PR**。下面每个 PR 都能点进去看到复现说明、测试代码和 review 记录。

## 🛠 技术栈

| 方向 | 用到什么 |
| --- | --- |
| 后端 | Java 8 / 17、Spring Boot 2.x、MyBatis / MyBatis-Plus、Maven、JUnit 5 |
| 前端 | Vue 2/3、Vite、Element UI / Element Plus |
| 数据与工具 | MySQL、Redis、Swagger、Git / GitHub Actions |
| 在学 | Python、LangGraph、LLM Agent 工程化、MCP |

## ✅ 已合并的开源贡献

**6 个 PR 被 4 个上游项目合并**（截至 2026-11）：

| 上游项目 | PR | 做了什么 | 合并日期 |
| --- | --- | --- | --- |
| [apache/logging-log4j2](https://github.com/apache/logging-log4j2) | [#4394](https://github.com/apache/logging-log4j2/pull/4394) | 修正 `%c` 精度说明与实际运行时行为不一致的文档 | 2026-11-04 |
| [alibaba/fastjson2](https://github.com/alibaba/fastjson2) | [#7854](https://github.com/alibaba/fastjson2/pull/7854) | 修复泛型字段缓存 `initWriter` 与运行时类型不一致导致的 `ClassCastException`（#7853），含回归测试 | 2026-10-17 |
| [kekingcn/kkFileView](https://github.com/kekingcn/kkFileView) | [#795](https://github.com/kekingcn/kkFileView/pull/795) | 预览 URL 转义 + Office schema 冲突修复，涉及 19 个文件 | 2026-10-08 |
| [kekingcn/kkFileView](https://github.com/kekingcn/kkFileView) | [#798](https://github.com/kekingcn/kkFileView/pull/798) | 图片预览标题改为显示真实文件名 | 2026-10-08 |
| [caura-ai/caura](https://github.com/caura-ai/caura) | [#1536](https://github.com/caura-ai/caura/pull/1536) | OpenAPI 中 `ConflictOut` 响应结构与运行时 schema 对齐 | 2026-09-26 |
| [caura-ai/caura](https://github.com/caura-ai/caura) | [#1243](https://github.com/caura-ai/caura/pull/1243) | `recall()` 解析响应前先校验 body，避免脏数据崩溃 | 2026-09-17 |

这几块彼此不太一样：JSON 序列化内核、SQL 解析器、文件预览服务、Agent 框架的 API 契约。共同点是都从 issue 复现走到了**可合并的补丁 + 测试**。

## 🔭 进行中的贡献

21 个待审 PR，分布在 9 个上游仓库：

`alibaba/fastjson2` · `alibaba/druid` · `kekingcn/kkFileView` · `spring-ai-alibaba/DataAgent` · `agentscope-ai/agentscope-java` · `bytedance/deer-flow` · `camel-ai/camel` · `caura-ai/caura` · `xiaolincoder/CS-Base`

近期主线是 fastjson2 截断输入的健壮性（把 `ArrayIndexOutOfBoundsException` 收敛成语义明确的 `JSONException`），以及 druid SQL 解析器的边界处理。

→ [查看全部 PR](https://github.com/pulls?q=is%3Apr+author%3Awylovelyi)

## 📌 关于仓库列表

- 列表里 fork 较多，是给上游提补丁时的工作副本，不是原创项目。
- `dkd-parent` / `dkd-vue` 是基于 RuoYi 3.8.7 的前后端分离二次开发练习项目，README 顶部已写明我的改动范围与对应提交。

---

📫 技术交流欢迎通过 PR review 或 issue 找我。
