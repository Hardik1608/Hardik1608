## Hi, I'm Hardik

**AI/ML Engineer.** I build ML and LLM systems end to end (training, agents, serving, safety
checks, monitoring), and I report every result on held-out data or public benchmarks.

2 years in production ML: real-time computer vision on edge GPUs (**5 → 48 FPS** with
TensorRT) and assistive vision on wearable hardware. My projects cover LLM fine-tuning with
QLoRA, tool-using agents with safety evaluation, and data platforms.

Bengaluru, India · Open to relocation within EMEA (EU Blue Card eligible)<br>
[hardiksoni162001@gmail.com](mailto:hardiksoni162001@gmail.com) · [LinkedIn](https://linkedin.com/in/hardiksoni16)

---

### Featured projects

| Project | Result | Stack |
|---|---|---|
| [**Governed Data Agent**](https://github.com/Hardik1608/governed-data-agent) | A tool-using agent that answers multi-step business questions over a 1M-row warehouse: **55.9% vs 49.1%** for single-shot text-to-SQL on all 1,534 BIRD dev questions (+6.8 pts, paired 95% CI 4.3–9.4). **0** unsafe queries and **0** customer-ID leaks in 1,120 trials; the release gate rejected a more accurate version over one safety failure. | LangGraph · MCP · vLLM · DuckDB · MLflow · FastAPI |
| [**Text-to-SQL LLM Platform**](https://github.com/Hardik1608/text-to-sql-llm-platform) | When do prompting, RAG and fine-tuning pay off? Qwen2.5-3B on one RTX 3060: execution accuracy **63.4% → 76.1%** on the Spider test set (2,147 questions). Served on vLLM at **6 q/s** behind a 4-stage SQL safety layer. | QLoRA/PEFT · vLLM · RAG · FastAPI · MLflow · Prometheus |
| [**MLOps Recommendation Pipeline**](https://github.com/Hardik1608/mlops-recommendation-pipeline) | Does a transformer beat matrix factorisation? SASRec scores **1.6–4.9×** ALS under leave-one-out, yet **28–49% below** the served ALS model on held-out future data (MovieLens 1M/25M, p < 0.001). Served hybrid ALS: **+16% NDCG@10**, **3.8 ms P95**, SASRec in shadow mode. | PyTorch · ONNX · Kafka · Feast · MLflow · FastAPI |
<!-- Uncomment each row after its repository is public.
| [**dbt Background Coding Agent**](https://github.com/Hardik1608/dbt-background-agent) | A sandboxed agent that fixes and extends dbt projects through reviewed PRs. Local 9B model: **62.7%** of 150 runs on a validated 50-task suite (pass^3 48%), **22/60** on dbt Labs' ADE-bench, **9/68** on Spider2-DBT; no sandbox escape. | Python · Docker sandboxing · dbt · DuckDB · vLLM |
| [**Sales Lakehouse**](https://github.com/Hardik1608/sales-lakehouse) | PySpark → Apache Iceberg → dbt, **identical** to the original warehouse on all 59 parity checks (1,033,036 fact rows, SCD2 history); Airflow 3 orchestration; Terraform for AWS + Snowflake (0 failed checkov checks). | PySpark · Iceberg · dbt · Airflow · Terraform |
| [**Sales Analytics Data Platform**](https://github.com/Hardik1608/sales-analytics-platform) | 1.07M invoice lines → star schema with SCD2 and incremental loads; **102/102** dbt checks pass. Churn model at **0.77 ROC-AUC**. | SQL · dbt · DuckDB · Airflow · MLflow |


Earlier: [Databricks Medallion Pipeline](https://github.com/Hardik1608/databricks-medallion-pipeline), an Azure Databricks batch pipeline (PySpark, Delta Lake, Unity Catalog).
-->
---

### Tech stack

**ML / LLM:** PyTorch · Hugging Face · PEFT/QLoRA · vLLM · RAG · TensorRT · ONNX<br>
**Agents:** LangGraph · MCP · agent evaluation (pass^k, benchmarks, release gates)<br>
**Data:** SQL · dbt · DuckDB · PySpark · Airflow · Kafka · Feast<br>
**MLOps:** MLflow · FastAPI · Docker · Prometheus · Grafana · GitHub Actions

---

### Background

**BS-MS, Data Science & Engineering**, IISER Bhopal<br>
**Research Intern**, IIT Delhi: text detection for low-resource languages (Assamese F-measure **22% → 71%**)
