**sahil kumar singh** · IT @ AIT Pune · building agents, ML tooling and backends  
currently working on agentic ETL benchmarks and scam interception systems · building [TuneOS](https://github.com/SahilKumar75/TuneOS) — local LLM fine-tuning and dataset toolchain (LoRA/QLoRA) · contributor to [vespa-engine/vespa](https://github.com/vespa-engine/vespa) and [mlflow/mlflow](https://github.com/mlflow/mlflow)

---

**open source**

[mlflow/mlflow](https://github.com/mlflow/mlflow) · 2 merged PRs · AI/ML observability platform

- [#23642](https://github.com/mlflow/mlflow/pull/23642) unwrap JSON-encoded `session.id` / `user.id` span attributes on ingest — fixed trace UI rendering, `search_traces` filtering, and session grouping for OTel spans · May 2026
- [#23152](https://github.com/mlflow/mlflow/pull/23152) fix ended `LiveSpan` state mutation — aligned attachment and link behavior with OTel's ended-span no-op semantics; added debug logs and regression tests · May 2026

[vespa-engine/vespa](https://github.com/vespa-engine/vespa) · 6 merged PRs · AI search platform

- [#36365](https://github.com/vespa-engine/vespa/pull/36365) add Elasticsearch→Vespa query translator — translates ES DSL (`match`, `term`, `range`, `bool`) to Vespa query items; implements [#16872](https://github.com/vespa-engine/vespa/issues/16872) · Apr 2026
- [#36375](https://github.com/vespa-engine/vespa/pull/36375) accept integer `distanceThreshold` in nearestNeighbor YQL — coerces numeric annotation to double for ANN queries
- [#36377](https://github.com/vespa-engine/vespa/pull/36377) handle empty query stems safely in query-side stemming — drops empty-stem terms in AND/WeakAND contexts without collapsing the whole query
- [#36380](https://github.com/vespa-engine/vespa/pull/36380) expose custom annotations on compound query items (`and`, `or`, `not`, `rank`, `weakAnd`) — previously only leaf items supported annotations
- [#36384](https://github.com/vespa-engine/vespa/pull/36384) allow `tensor<float>` input assignment to `tensor<bfloat16>` attributes — relaxes schema validation when dimensions match
- [#36385](https://github.com/vespa-engine/vespa/pull/36385) handle hex tensor decoding across compatible value types — fixes out-of-bounds error when feeding float-encoded hex to bfloat16 fields

---

<p align="center">
  <a href="https://www.linkedin.com/in/sahil-kumar-singh-88949a27a/"><img src="https://img.shields.io/badge/linkedin-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:sahilkumargreat12@gmail.com"><img src="https://img.shields.io/badge/email-EA4335?style=flat-square&logo=gmail&logoColor=white"/></a>
</p>
