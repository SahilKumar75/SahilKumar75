**sahil kumar singh** · IT @ AIT Pune · agents, ML tooling, backends  
building [TuneOS](https://github.com/SahilKumar75/TuneOS): a local LLM fine tuning and dataset toolchain (LoRA/QLoRA). contributor to [mlflow/mlflow](https://github.com/mlflow/mlflow), [vespa-engine/vespa](https://github.com/vespa-engine/vespa), and [kubeflow/sdk](https://github.com/kubeflow/sdk).

---

**open source**

[mlflow/mlflow](https://github.com/mlflow/mlflow) · 3 merged PRs · ML observability
- [#23642](https://github.com/mlflow/mlflow/pull/23642) unwrap JSON encoded `session.id` / `user.id` span attributes on ingest. fixes trace UI, `search_traces` filtering, and session grouping for OTel spans.
- [#23584](https://github.com/mlflow/mlflow/pull/23584) map `gen_ai.conversation.id` to the MLflow trace session as a fallback OTel attribute (OpenInference, Traceloop) when `session.id` is absent.
- [#23152](https://github.com/mlflow/mlflow/pull/23152) stop state mutation on ended `LiveSpan`s. matches OTel no op semantics for attach and link, with regression tests.

[vespa-engine/vespa](https://github.com/vespa-engine/vespa) · 6 merged PRs · AI search
- [#36365](https://github.com/vespa-engine/vespa/pull/36365) Elasticsearch to Vespa query translator for `match`, `term`, `range`, `bool` DSL.
- [#36375](https://github.com/vespa-engine/vespa/pull/36375) accept integer `distanceThreshold` in nearestNeighbor YQL by coercing to double.
- [#36377](https://github.com/vespa-engine/vespa/pull/36377) drop empty stem terms safely in query side stemming without collapsing the query.
- [#36380](https://github.com/vespa-engine/vespa/pull/36380) expose custom annotations on compound query items (`and`, `or`, `not`, `rank`, `weakAnd`).
- [#36384](https://github.com/vespa-engine/vespa/pull/36384) allow `tensor<float>` input assignment to `tensor<bfloat16>` attributes when dimensions match.
- [#36385](https://github.com/vespa-engine/vespa/pull/36385) fix hex tensor decoding across compatible value types.

[kubeflow/sdk](https://github.com/kubeflow/sdk) · 3 merged PRs · ML platform reliability
- [#562](https://github.com/kubeflow/sdk/pull/562) don't report Trainer job status as Complete when all container statuses are Unknown.
- [#564](https://github.com/kubeflow/sdk/pull/564) validate `HuggingFaceModelInitializer` storage_uri has a repo path.
- [#575](https://github.com/kubeflow/sdk/pull/575) validate HuggingFace storage_uri has both user and repo.

---

<p align="center">
  <a href="https://www.linkedin.com/in/sahil-kumar-singh-88949a27a/"><img src="https://img.shields.io/badge/linkedin-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:sahilkumargreat12@gmail.com"><img src="https://img.shields.io/badge/email-EA4335?style=flat-square&logo=gmail&logoColor=white"/></a>
</p>
