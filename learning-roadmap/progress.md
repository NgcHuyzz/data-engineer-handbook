# Tiến độ roadmap 32 tuần

Đánh dấu hoàn thành khi đã tạo đầu ra và tự giải thích được phần cốt lõi. Mỗi tuần dành khoảng 12–15 giờ theo kế hoạch trong [roadmap](roadmap.md); nếu chưa đạt checkpoint, kéo dài tuần đó thay vì chạy theo lịch.

Trạng thái: `[ ]` chưa bắt đầu · `[/]` đang học · `[x]` hoàn tất.

## Phase 1 — Computer Science & Engineering Foundation · Tuần 1–4

| Xong | Tuần | Trọng tâm | Đầu ra / checkpoint | Handbook nên dùng |
|---|---:|---|---|---|
| [ ] | 1 | Data Engineering fundamentals, Linux, Git | Repo GitHub và Bash scripts cơ bản | — |
| [ ] | 2 | Python for Data Engineering | CLI đọc/làm sạch dữ liệu, có logging và xử lý lỗi | [Data cleaning](../data_cleaning.md) |
| [ ] | 3 | SQL và PostgreSQL fundamentals | Database E-commerce và bộ truy vấn SQL | [Thiết lập PostgreSQL](../intermediate-bootcamp/materials/1-dimensional-data-modeling/README.md) |
| [ ] | 4 | Advanced SQL, Python–database integration | Python loader; giải thích được JOIN, CTE, window, index và execution plan | [SQL mẫu](../intermediate-bootcamp/materials/1-dimensional-data-modeling/sql) |

**Checkpoint Phase 1:** Tự đọc dữ liệu từ file, xử lý bằng Python và nạp vào PostgreSQL; dùng Git/Linux độc lập.

## Phase 2 — Data Modeling & Data Pipeline · Tuần 5–8

| Xong | Tuần | Trọng tâm | Đầu ra / checkpoint | Handbook nên dùng |
|---|---:|---|---|---|
| [ ] | 5 | Data ingestion, REST API | Ingestion có pagination, timeout/retry và log | — |
| [ ] | 6 | ETL/ELT, incremental processing | Incremental load có watermark, xử lý duplicate, chạy lại an toàn | [Pipeline và incremental SCD SQL](../intermediate-bootcamp/materials/1-dimensional-data-modeling/lecture-lab) |
| [ ] | 7 | Warehouse, dimensional modeling | E-commerce fact/dim model; xác định grain và SCD | [Dimensional modeling homework](../intermediate-bootcamp/materials/1-dimensional-data-modeling/homework/homework.md) · [Fact modeling homework](../intermediate-bootcamp/materials/2-fact-data-modeling/homework/homework.md) |
| [ ] | 8 | Data quality, batch project | Hoàn tất [Project 1](projects/project-1-ecommerce-batch-etl.md), có validation và hướng dẫn chạy | [Analytical SQL patterns](../intermediate-bootcamp/materials/4-applying-analytical-patterns) |

**Checkpoint Phase 2:** Tự xây batch ETL có incremental load, xử lý lỗi và chạy lại an toàn.

## Phase 3 — Modern Analytics Engineering · Tuần 9–12

| Xong | Tuần | Trọng tâm | Đầu ra / checkpoint | Handbook nên dùng |
|---|---:|---|---|---|
| [ ] | 9 | Docker, containerization | ETL và PostgreSQL chạy bằng Docker Compose | [Docker/PostgreSQL lab](../intermediate-bootcamp/materials/1-dimensional-data-modeling/README.md) |
| [ ] | 10 | dbt | Project dbt có staging/marts, tests và docs | — |
| [ ] | 11 | Airflow fundamentals | DAG ingestion có dependencies, retry và lịch chạy | — |
| [ ] | 12 | Airflow integration, backfill | Hoàn tất [Project 2](projects/project-2-automated-analytics-platform.md) | [Spark/Flink Compose files](../intermediate-bootcamp/materials) để tham khảo cách đóng gói lab; không thay thế Airflow/dbt |

**Checkpoint Phase 3:** Chạy và vận hành được Airflow + dbt + PostgreSQL bằng Docker Compose.

## Phase 4 — Cloud Data Engineering · Tuần 13–16

| Xong | Tuần | Trọng tâm | Đầu ra / checkpoint | Handbook nên dùng |
|---|---:|---|---|---|
| [ ] | 13 | GCP fundamentals, IAM, chi phí | Project GCP, service account quyền tối thiểu và budget alert | — |
| [ ] | 14 | GCS, BigQuery | Dữ liệu trên GCS/BigQuery; thử partition và clustering | — |
| [ ] | 15 | Cloud deployment | Ingestion chạy trên Cloud Run Jobs, có lịch và logs | — |
| [ ] | 16 | Cloud analytics pipeline | Batch pipeline trên GCP, tài liệu kiến trúc và chi phí | — |

**Checkpoint Phase 4:** Deploy ingestion, truy vấn BigQuery, thiết lập lịch/logging và giải thích IAM/chi phí.

## Phase 5 — Big Data & Lakehouse Engineering · Tuần 17–20

| Xong | Tuần | Trọng tâm | Đầu ra / checkpoint | Handbook nên dùng |
|---|---:|---|---|---|
| [ ] | 17 | Spark fundamentals | PySpark DataFrame transformations, joins và aggregations | [Spark README](../intermediate-bootcamp/materials/3-spark-fundamentals/README.md) · [event notebook](../intermediate-bootcamp/materials/3-spark-fundamentals/notebooks/event_data_pyspark.ipynb) |
| [ ] | 18 | Spark optimization | Benchmark join/cache/partition và giải thích shuffle | [Spark notebooks](../intermediate-bootcamp/materials/3-spark-fundamentals/notebooks) |
| [ ] | 19 | Lake, file formats | Chuyển CSV sang Parquet; so sánh kích thước và truy vấn | [Spark sample data](../intermediate-bootcamp/materials/3-spark-fundamentals/data) |
| [ ] | 20 | Iceberg, Lakehouse | Mini Lakehouse; mô tả snapshot/schema evolution | [Iceberg bucket-join notebook](../intermediate-bootcamp/materials/3-spark-fundamentals/notebooks/bucket-joins-in-iceberg.ipynb) |

**Checkpoint Phase 5:** Viết và debug PySpark, đọc execution plan, tìm bottleneck và trình bày benchmark.

## Phase 6 — Realtime Data Engineering · Tuần 21–24

| Xong | Tuần | Trọng tâm | Đầu ra / checkpoint | Handbook nên dùng |
|---|---:|---|---|---|
| [ ] | 21 | Kafka fundamentals | Producer/consumer, topics, partitions và consumer groups | [Flink/Kafka lab](../intermediate-bootcamp/materials/4-apache-flink-training/README.md) |
| [ ] | 22 | Kafka reliability | Thử duplicate, restart, replay và xử lý lỗi serialization | [PyFlink source](../intermediate-bootcamp/materials/4-apache-flink-training/src/job) |
| [ ] | 23 | Spark Structured Streaming | Kafka stream, event-time window, watermark và checkpoint | — |
| [ ] | 24 | Streaming reliability | Hoàn tất [Project 3](projects/project-3-realtime-order-analytics.md), kiểm thử recovery | [Flink sessionization homework](../intermediate-bootcamp/materials/4-apache-flink-training/homework/homework.md) là lab tham khảo riêng; handbook dùng Flink, không phải Spark Structured Streaming |

**Checkpoint Phase 6:** Tự giải thích và debug duplicate, late events, checkpoint và consumer restart.

## Phase 7 — Production Engineering & Capstone · Tuần 25–29

| Xong | Tuần | Trọng tâm | Đầu ra / checkpoint | Handbook nên dùng |
|---|---:|---|---|---|
| [ ] | 25 | Software engineering, pytest | Refactor project, unit/integration tests | [Spark tests](../intermediate-bootcamp/materials/3-spark-fundamentals/src/tests) |
| [ ] | 26 | CI/CD, GitHub Actions | Workflow chạy checks/tests và build image | — |
| [ ] | 27 | Observability, monitoring | Metrics/dashboard/alerts, incident report | [Pipeline maintenance materials](../intermediate-bootcamp/materials/6-data-pipeline-maintenance) |
| [ ] | 28 | Reliability, security, cost | Failure recovery, secrets/IAM review và cost review | [Maintenance homework](../intermediate-bootcamp/materials/6-data-pipeline-maintenance/homework/homework.md) |
| [ ] | 29 | Capstone integration | Hoàn tất [Project 4](projects/project-4-ecommerce-data-platform.md), demo và architecture review | Dùng các lab modeling, Spark và streaming ở trên khi cần |

**Checkpoint Phase 7:** Capstone có thể triển khai, kiểm thử, giám sát và khôi phục; README đủ để người khác chạy lại.

## Phase 8 — AI-assisted Data Engineering & Career · Tuần 30–32

| Xong | Tuần | Trọng tâm | Đầu ra / checkpoint | Handbook nên dùng |
|---|---:|---|---|---|
| [ ] | 30 | AI-assisted development | Ghi lại cách dùng AI để review/test/debug và cách bạn xác minh kết quả | [Databricks AI bootcamp](../databricks-ai-bootcamp/README.md) là phần mở rộng |
| [ ] | 31 | AI workflow/agents | Demo hoặc tài liệu workflow AI có đánh giá và giới hạn rõ ràng | [Databricks AI bootcamp](../databricks-ai-bootcamp/README.md) |
| [ ] | 32 | Career preparation | Portfolio, CV, demo và câu chuyện phỏng vấn cho từng project | [Interview resources](../interviews.md) · [Project ideas](../projects.md) |

## Nhật ký thay đổi tiến độ

| Ngày | Tuần/Phase | Cập nhật, trở ngại hoặc điều chỉnh lịch |
|---|---|---|
| | | |
