## Hi, I'm Hardik

**AI/ML Engineer.** I build ML systems end to end (training, serving, safety checks, monitoring)
and report every result on held-out data.

2+ years in production ML: real-time computer vision on edge GPUs (**5 → 48 FPS** with
TensorRT), LLM fine-tuning with QLoRA, and data platforms.

Bengaluru, India · Open to relocation within EMEA (EU Blue Card eligible)<br>
[hardiksoni162001@gmail.com](mailto:hardiksoni162001@gmail.com) · [LinkedIn](https://linkedin.com/in/hardiksoni16)

---

### Featured projects

| Project | Result | Stack |
|---|---|---|
| [**Text-to-SQL LLM Platform**](https://github.com/Hardik1608/text-to-sql-llm-platform) | When do prompting, RAG and fine-tuning pay off? Qwen2.5-3B on one RTX 3060: execution accuracy **63.4% → 76.1%** on the Spider test set (2,147 questions). Served on vLLM at **6 q/s** behind a 4-stage SQL safety layer. | QLoRA/PEFT · vLLM · RAG · FastAPI · MLflow · Prometheus |
| [**Databricks Medallion Pipeline**](https://github.com/Hardik1608/databricks-medallion-pipeline) | Azure Databricks batch pipeline: 13 raw sources → 15 config-driven Silver tables (SCD1/SCD2) → star schema with 10 dimensions and 6 facts. | PySpark · Delta Lake · Unity Catalog · Databricks Workflows |
<!-- Uncomment each row after its repository is public.
| [**MLOps Recommendation Pipeline**](https://github.com/Hardik1608/mlops-recommendation-pipeline) | MovieLens recommender: **+15% NDCG@10** over a tuned popularity baseline (time-based split). Serving at **3.8 ms P95** (327 req/s, one worker). | Kafka · Feast · MLflow · FastAPI · Redis · Helm |
| [**Sales Analytics Data Platform**](https://github.com/Hardik1608/sales-analytics-platform) | 1.07M invoice lines → star schema with SCD2 and incremental loads; **102/102** dbt checks pass. Churn model at **0.77 ROC-AUC**. | SQL · dbt · DuckDB · Airflow · MLflow |
-->

---

### Tech stack

**ML / LLM:** PyTorch · Hugging Face · PEFT/QLoRA · vLLM · RAG · TensorRT · ONNX<br>
**Data:** SQL · PySpark · Delta Lake · Databricks · dbt · Airflow · Kafka<br>
**MLOps:** MLflow · FastAPI · Docker · Prometheus · Grafana · GitHub Actions

---

### How I work

- **Measure, then claim.** Results come from held-out data, and each repo links the file that produced them.
- **Ship the system, not the notebook.** Models come with an API, safety checks, monitoring, tests and containers.
- **Beat a simple baseline.** Each result is compared with the simplest approach that could work.

---

### Background

**BS-MS, Data Science & Engineering**, IISER Bhopal<br>
**Research Intern**, IIT Delhi: text detection for low-resource languages (Assamese F-measure **22% → 71%**)
