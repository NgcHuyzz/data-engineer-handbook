# ROADMAP DATA ENGINEER 2026–2027

**Lộ trình học Data Engineering hoàn chỉnh — Tổng hợp và tái cấu trúc từ RoadMap 1 và RoadMap 2**

---

# PHẦN I. TỔNG QUAN

## 1. Mục tiêu của roadmap

Xây dựng một lộ trình Data Engineering hoàn chỉnh, có hệ thống, từ nền tảng đến khả năng thiết kế, xây dựng, triển khai và vận hành các hệ thống dữ liệu thực tế.

Roadmap được tổng hợp từ hai lộ trình ban đầu:

- **Roadmap 1 — Data Engineering & AI-Native:** Tập trung vào SQL, Python, ETL/ELT, Airflow, Apache Spark, Kafka, Streaming, Cloud và AI Agent.
- **Roadmap 2 — Data Analyst → Data Engineer:** Tập trung vào Python Engineering, Docker, GCP, Airflow, dbt, Data Warehouse, Testing, CI/CD, Spark và Production Engineering.

Roadmap mới không đơn thuần ghép các nội dung của hai lộ trình, mà được thiết kế lại dựa trên sự phụ thuộc giữa các kiến thức, mức độ quan trọng trong công việc và khả năng áp dụng thực tế.

### Thông tin tổng quan

- **Tên roadmap:** Data Engineer Roadmap 2026–2027
- **Thời lượng:** 32 tuần (khoảng 8 tháng)
- **Số giai đoạn:** 8
- **Số project chính:** 4
- **Thời gian học:** 12–15 giờ/tuần
- **Tổng thời lượng:** Khoảng 384–480 giờ
- **Trình độ đầu vào:** Người mới bắt đầu, có kiến thức máy tính cơ bản
- **Trình độ mục tiêu:** Data Engineer Fresher/Junior
- **Định hướng:** Batch Data Engineering, Analytics Engineering, Cloud Data Engineering và nền tảng Big Data/Streaming

### Năng lực đầu ra

Sau khi hoàn thành roadmap và đáp ứng đầy đủ các tiêu chí thực hành, người học cần có khả năng:

1. Sử dụng Python và SQL để xử lý dữ liệu.
2. Làm việc với Linux, Git, PostgreSQL và Docker.
3. Thiết kế Data Warehouse và mô hình dữ liệu phục vụ analytics.
4. Xây dựng ETL/ELT pipeline.
5. Triển khai incremental data processing.
6. Điều phối pipeline bằng Apache Airflow.
7. Xây dựng transformation và data tests bằng dbt.
8. Triển khai batch data pipeline trên Google Cloud.
9. Xử lý dữ liệu phân tán bằng Apache Spark.
10. Xây dựng streaming pipeline với Apache Kafka.
11. Viết automated tests và thiết lập CI/CD.
12. Giám sát, phát hiện lỗi và khôi phục pipeline.
13. Thiết kế hệ thống dữ liệu có khả năng bảo trì và mở rộng.
14. Sử dụng AI hỗ trợ phát triển, kiểm thử và phân tích lỗi.
15. Xây dựng portfolio và trình bày kiến trúc Data Engineering.

**Lưu ý:** Hoàn thành đủ 32 tuần không tự động đồng nghĩa với đạt trình độ Junior. Năng lực thực tế phụ thuộc vào mức độ thành thạo, khả năng tự giải quyết vấn đề và chất lượng project.

---

# PHẦN II. NGUYÊN TẮC THIẾT KẾ ROADMAP

## 2. Các nguyên tắc cốt lõi

### 2.1. Học theo thứ tự phụ thuộc

Kiến thức được sắp xếp theo trình tự:

SQL + Python → Data Pipeline → Data Modeling → Docker → dbt → Airflow → Cloud → Spark → Kafka → Production Engineering → AI.

Không học một công nghệ phức tạp trước khi có nền tảng cần thiết.

### 2.2. Ưu tiên công nghệ cốt lõi

Tập trung vào một bộ công nghệ chính:

- Python
- SQL
- PostgreSQL
- Linux
- Git
- Docker
- Apache Airflow
- dbt
- Google Cloud Platform
- BigQuery
- Apache Spark
- Apache Kafka
- pytest
- GitHub Actions

Không cố gắng học quá nhiều công nghệ có chức năng tương đương trong cùng một giai đoạn.

### 2.3. Học đi đôi với thực hành

Mỗi giai đoạn phải có:

- Kiến thức lý thuyết.
- Bài thực hành.
- Sản phẩm đầu ra.
- Tiêu chí đánh giá.
- Điều kiện chuyển sang giai đoạn tiếp theo.

### 2.4. Xây dựng production mindset

Không chỉ học cách viết code chạy được, mà còn học cách:

- Xử lý lỗi.
- Chạy lại pipeline an toàn.
- Kiểm thử dữ liệu.
- Quản lý cấu hình và secrets.
- Theo dõi trạng thái hệ thống.
- Tối ưu hiệu suất.
- Triển khai tự động.
- Khôi phục khi hệ thống gặp sự cố.

### 2.5. Project xuyên suốt

Sử dụng bài toán E-commerce làm chủ đề xuyên suốt.

Mỗi project sẽ mở rộng kiến trúc và kỹ năng từ project trước đó, thay vì xây dựng nhiều project rời rạc.

### 2.6. AI là công cụ hỗ trợ

AI được sử dụng để hỗ trợ:

- Giải thích code.
- Viết test.
- Review SQL/Python.
- Phân tích lỗi.
- Viết documentation.
- Tìm phương án tối ưu.

Tuy nhiên, người học phải tự hiểu, kiểm chứng và chịu trách nhiệm về code.

---

# PHẦN III. CẤU TRÚC ROADMAP 32 TUẦN

## 3. Tổng quan 8 giai đoạn

| Giai đoạn | Thời gian | Nội dung chính |
|---|---|---|
| Phase 1 | Tuần 1–4 | Computer Science & Engineering Foundation |
| Phase 2 | Tuần 5–8 | Data Modeling & Data Pipeline |
| Phase 3 | Tuần 9–12 | Modern Analytics Engineering |
| Phase 4 | Tuần 13–16 | Cloud Data Engineering |
| Phase 5 | Tuần 17–20 | Big Data & Lakehouse Engineering |
| Phase 6 | Tuần 21–24 | Realtime Data Engineering |
| Phase 7 | Tuần 25–29 | Production Engineering & Capstone |
| Phase 8 | Tuần 30–32 | AI-Assisted Data Engineering & Career Preparation |

---

# PHASE 1 — COMPUTER SCIENCE & ENGINEERING FOUNDATION

**Thời gian:** Tuần 1–4

**Thời lượng:** 48–60 giờ

## 4. Mục tiêu

Xây dựng nền tảng kỹ thuật cần thiết để học và làm việc trong lĩnh vực Data Engineering.

Sau giai đoạn này, người học phải có khả năng sử dụng terminal, Git, Python, SQL và PostgreSQL.

## 5. Nội dung chi tiết

### Tuần 1 — Data Engineering Fundamentals, Linux & Git

**Kiến thức cần học:**

- Data Engineering là gì?
- Vai trò của Data Engineer, Data Analyst và Analytics Engineer.
- Data lifecycle.
- Data pipeline architecture.
- Batch processing và streaming processing.
- OLTP và OLAP ở mức tổng quan.
- Linux filesystem.
- Terminal commands: `pwd`, `ls`, `cd`, `mkdir`, `cp`, `mv`, `rm`, `cat`, `grep`, `find`.
- File permissions.
- Environment variables.
- Process management cơ bản.
- Bash scripting.
- Git repository, commit, branch, merge.
- GitHub và Pull Request.

**Thực hành:**

- Cài đặt môi trường phát triển.
- Tạo GitHub repository.
- Thao tác với file và thư mục bằng terminal.
- Viết Bash script đơn giản.
- Tạo branch, commit và merge code.

**Đầu ra:** GitHub repository và bộ Bash scripts cơ bản.

### Tuần 2 — Python for Data Engineering

**Kiến thức cần học:**

- Python data types.
- List, tuple, set, dictionary.
- Conditional statements.
- Loops.
- Functions.
- List/dictionary comprehension.
- Modules và packages.
- Virtual environments.
- pip và dependency management.
- Type hints.
- Exception handling.
- Logging.
- File I/O.
- CSV và JSON.
- Iterators và generators.
- Python project structure.

**Thực hành:**

- Đọc dữ liệu CSV.
- Xử lý dữ liệu JSON.
- Làm sạch dữ liệu đơn hàng.
- Xử lý missing values.
- Ghi log và xử lý exception.
- Xây dựng chương trình CLI.

**Đầu ra:** Python CLI xử lý dữ liệu E-commerce.

### Tuần 3 — SQL & PostgreSQL Fundamentals

**Kiến thức cần học:**

- Relational database.
- PostgreSQL architecture cơ bản.
- Database, schema, table.
- Data types.
- Primary key và foreign key.
- Constraints.
- DDL và DML.
- SELECT, WHERE, ORDER BY.
- GROUP BY và HAVING.
- INNER/LEFT/RIGHT JOIN.
- Subqueries.
- Common Table Expressions.
- Window functions.
- Transactions.

**Thực hành:**

- Thiết kế database E-commerce.
- Tạo bảng Customers, Products, Orders, Order_Items.
- Import dữ liệu.
- Viết 20–30 truy vấn SQL.
- Phân tích doanh thu và hành vi khách hàng.

**Đầu ra:** PostgreSQL E-commerce database và bộ SQL scripts.

### Tuần 4 — Advanced SQL & Python Database Integration

**Kiến thức cần học:**

- Indexing.
- Query execution plan.
- EXPLAIN ANALYZE.
- Query optimization.
- Normalization.
- Transaction isolation.
- Database locking cơ bản.
- Python database connectivity.
- Parameterized queries.
- Batch inserts.
- Connection management.

**Thực hành:**

- Kết nối Python với PostgreSQL.
- Load dữ liệu bằng Python.
- Tối ưu truy vấn SQL.
- So sánh execution plan.
- Kiểm thử transaction và constraints.

**Đầu ra:** Python PostgreSQL loader và báo cáo SQL optimization.

## 6. Điều kiện hoàn thành Phase 1

Người học phải:

- Sử dụng Git và Linux terminal độc lập.
- Viết được Python scripts có logging và exception handling.
- Thiết kế được database quan hệ.
- Viết thành thạo JOIN, CTE và window functions.
- Kết nối Python với PostgreSQL.
- Hiểu cơ bản về index và query optimization.

**Chỉ chuyển Phase 2 khi có thể tự viết chương trình lấy dữ liệu từ file và lưu vào PostgreSQL.**

---

# PHASE 2 — DATA MODELING & DATA PIPELINE

**Thời gian:** Tuần 5–8

**Thời lượng:** 48–60 giờ

## 7. Mục tiêu

Hiểu cách dữ liệu di chuyển giữa các hệ thống và xây dựng batch data pipeline đáng tin cậy.

## 8. Nội dung chi tiết

### Tuần 5 — Data Ingestion & REST API

**Kiến thức cần học:**

- HTTP fundamentals.
- REST API.
- GET/POST.
- HTTP status codes.
- Authentication.
- API pagination.
- Rate limiting.
- Timeout.
- Retry và exponential backoff.
- JSON parsing.
- CSV ingestion.
- API ingestion.
- Database extraction.

**Thực hành:**

- Lấy dữ liệu từ REST API.
- Xử lý pagination.
- Retry khi API lỗi.
- Lưu dữ liệu thô vào PostgreSQL.
- Ghi log quá trình ingestion.

**Đầu ra:** Python API ingestion pipeline.

### Tuần 6 — ETL/ELT & Incremental Processing

**Kiến thức cần học:**

- ETL vs ELT.
- Batch processing.
- Full load.
- Incremental load.
- Watermark.
- Upsert.
- Change Data Capture concepts.
- Idempotency.
- Schema evolution.
- Data backfill.
- Retry strategy.
- Pipeline failure recovery.

**Thực hành:**

- Xây full-load pipeline.
- Chuyển sang incremental loading.
- Lưu trạng thái watermark.
- Xử lý duplicate.
- Chạy lại pipeline mà không tạo dữ liệu trùng.

**Đầu ra:** Incremental ETL pipeline.

### Tuần 7 — Data Warehouse & Dimensional Modeling

**Kiến thức cần học:**

- OLTP vs OLAP.
- Data Warehouse.
- Data Lake.
- Data Mart.
- Star schema.
- Snowflake schema.
- Fact tables.
- Dimension tables.
- Grain.
- Surrogate keys.
- Slowly Changing Dimensions Type 1/2.
- Data modeling best practices.

**Thực hành:**

- Thiết kế Sales Data Mart.
- Xây dựng fact_sales.
- Xây dựng dim_customer, dim_product, dim_date.
- Viết SQL phục vụ báo cáo doanh thu.

**Đầu ra:** E-commerce dimensional model.

### Tuần 8 — Data Quality & Batch Pipeline Project

**Kiến thức cần học:**

- Data quality dimensions.
- Completeness.
- Accuracy.
- Uniqueness.
- Consistency.
- Validity.
- Data contracts.
- Data validation.
- Unit tests.
- Integration tests.
- Pipeline architecture.
- Staging/Bronze/Silver/Gold.
- Basic scheduling.

**Thực hành:**

- Kiểm tra null và duplicate.
- Kiểm tra business rules.
- Viết tests cho ingestion.
- Tích hợp ingestion và transformation.
- Hoàn thiện Project 1.

## 9. Project 1 — E-commerce Batch ETL

**Công nghệ:**

- Python
- PostgreSQL
- SQL
- REST API
- Git

**Kiến trúc:**

CSV / REST API / PostgreSQL Source  
↓  
Python Ingestion  
↓  
Raw/Staging Tables  
↓  
Cleaning & Transformation  
↓  
Dimensional Data Mart  
↓  
SQL Analytics & Data Quality Report

**Yêu cầu:**

- Có ít nhất hai loại nguồn dữ liệu.
- Có incremental load.
- Có retry và error handling.
- Có data validation.
- Có SQL transformations.
- Có tài liệu kiến trúc.
- Có hướng dẫn chạy pipeline.

**Điều kiện chuyển Phase 3:** Có thể tự xây batch ETL pipeline hoàn chỉnh, xử lý incremental data và chạy lại an toàn.

---

# PHASE 3 — MODERN ANALYTICS ENGINEERING

**Thời gian:** Tuần 9–12

**Thời lượng:** 48–60 giờ

## 10. Mục tiêu

Chuyển từ pipeline viết thủ công sang pipeline có cấu trúc, container hóa, quản lý transformation và orchestration.

## 11. Nội dung chi tiết

### Tuần 9 — Docker & Containerization

**Kiến thức cần học:**

- Containers vs Virtual Machines.
- Docker images.
- Docker containers.
- Dockerfile.
- Docker volumes.
- Docker networks.
- Docker Compose.
- Environment variables.
- Container lifecycle.
- Container logging.
- Secret management cơ bản.

**Thực hành:**

- Dockerize Python ETL.
- Chạy PostgreSQL bằng Docker.
- Xây Docker Compose stack.
- Quản lý cấu hình môi trường.

**Đầu ra:** Containerized ETL environment.

### Tuần 10 — dbt & Analytics Engineering

**Kiến thức cần học:**

- Analytics Engineering.
- dbt Core.
- dbt project structure.
- Sources.
- Models.
- `ref()`.
- Staging models.
- Intermediate models.
- Marts.
- Materializations.
- Incremental models.
- Jinja basics.
- dbt tests.
- dbt documentation.
- Data lineage.

**Thực hành:**

- Xây dbt project.
- Chuyển SQL transformations sang dbt.
- Tạo staging và marts.
- Viết generic và custom tests.
- Generate documentation.

**Đầu ra:** dbt transformation project.

### Tuần 11 — Apache Airflow Fundamentals

**Kiến thức cần học:**

- Workflow orchestration.
- Airflow architecture.
- DAG.
- Task.
- Operators.
- Scheduler.
- Task dependencies.
- Scheduling semantics.
- Retries.
- Catchup.
- Backfill.
- XCom.
- Task failure handling.

**Thực hành:**

- Cài Airflow bằng Docker Compose.
- Xây DAG ingestion.
- Thiết lập dependencies.
- Cấu hình retry.
- Theo dõi task execution.

**Đầu ra:** Airflow ingestion DAG.

### Tuần 12 — Advanced Airflow & Pipeline Integration

**Kiến thức cần học:**

- TaskFlow API.
- Sensors.
- Dynamic task mapping cơ bản.
- Orchestration vs processing.
- Data quality integration.
- Pipeline recovery.
- Airflow monitoring.
- Backfill strategies.

**Thực hành:**

- Kết hợp Python ingestion, PostgreSQL và dbt.
- Chạy pipeline bằng Airflow.
- Kiểm thử task failures.
- Chạy backfill.
- Hoàn thiện Project 2.

## 12. Project 2 — Automated Analytics Platform

**Công nghệ:**

- Python
- PostgreSQL
- Docker
- Docker Compose
- Apache Airflow
- dbt
- SQL

**Kiến trúc:**

Data Sources  
↓  
Airflow Scheduler  
↓  
Python Ingestion  
↓  
PostgreSQL Raw Layer  
↓  
dbt Staging Models  
↓  
dbt Data Marts  
↓  
Data Quality Tests  
↓  
Analytics Tables

**Yêu cầu:**

- Chạy được toàn bộ hệ thống bằng Docker Compose.
- Có DAG điều phối.
- Có incremental ingestion.
- Có dbt transformations.
- Có automated data tests.
- Có retries.
- Có backfill.
- Có logging.
- Có README.

**Điều kiện chuyển Phase 4:** Có thể tự triển khai và vận hành Airflow + dbt + PostgreSQL bằng Docker Compose.

---

# PHASE 4 — CLOUD DATA ENGINEERING

**Thời gian:** Tuần 13–16

**Thời lượng:** 48–60 giờ

## 13. Mục tiêu

Triển khai batch data pipeline trên Google Cloud Platform và hiểu các nguyên tắc cơ bản của cloud architecture.

## 14. Nội dung chi tiết

### Tuần 13 — Google Cloud Fundamentals

**Kiến thức cần học:**

- Cloud computing.
- IaaS/PaaS/SaaS.
- Regions và zones.
- GCP projects.
- IAM.
- Service accounts.
- Least privilege.
- Cloud networking basics.
- Cloud storage concepts.
- Pricing.
- Cost control.
- Budget alerts.

**Thực hành:**

- Tạo GCP project.
- Thiết lập IAM.
- Tạo service account.
- Cấu hình budget alerts.
- Thiết lập môi trường cloud.

### Tuần 14 — Cloud Storage & BigQuery

**Kiến thức cần học:**

- Google Cloud Storage.
- Buckets.
- Object storage.
- BigQuery architecture.
- BigQuery datasets/tables.
- Load jobs.
- External tables.
- Partitioning.
- Clustering.
- BigQuery SQL.
- Query cost optimization.

**Thực hành:**

- Upload dữ liệu lên GCS.
- Load dữ liệu vào BigQuery.
- Tạo partitioned tables.
- So sánh query performance.
- Tối ưu chi phí truy vấn.

### Tuần 15 — Cloud Pipeline Deployment

**Kiến thức cần học:**

- Cloud Run Jobs.
- Cloud Scheduler.
- Artifact Registry.
- Secret Manager.
- Cloud Logging.
- Cloud configuration.
- Service identities.
- Deployment basics.

**Thực hành:**

- Dockerize ingestion.
- Push image lên Artifact Registry.
- Deploy ingestion lên Cloud Run Jobs.
- Thiết lập Cloud Scheduler.
- Theo dõi logs.

### Tuần 16 — Cloud Analytics Pipeline

**Kiến thức cần học:**

- dbt + BigQuery.
- Cloud orchestration options.
- Cloud monitoring.
- IAM security.
- Terraform fundamentals.
- Infrastructure as Code.
- Cloud architecture documentation.

**Thực hành:**

- Chuyển transformation sang BigQuery.
- Chạy dbt với BigQuery.
- Triển khai batch pipeline.
- Quản lý secrets.
- Hoàn thiện cloud architecture diagram.

**Đầu ra:** Cloud Batch Data Pipeline.

**Điều kiện chuyển Phase 5:**

- Triển khai được ingestion trên GCP.
- Lưu trữ dữ liệu bằng GCS/BigQuery.
- Truy vấn và tối ưu BigQuery.
- Thiết lập lịch chạy và logging.
- Hiểu IAM và kiểm soát chi phí.

---

# PHASE 5 — BIG DATA & LAKEHOUSE ENGINEERING

**Thời gian:** Tuần 17–20

**Thời lượng:** 48–60 giờ

## 15. Mục tiêu

Hiểu distributed processing, sử dụng Apache Spark và nắm các nguyên tắc thiết kế Data Lakehouse.

## 16. Nội dung chi tiết

### Tuần 17 — Apache Spark Fundamentals

**Kiến thức cần học:**

- Distributed computing.
- Parallel processing.
- Spark architecture.
- Driver và executors.
- Partitions.
- Lazy evaluation.
- Transformations và actions.
- Spark DataFrame API.
- Spark SQL.
- Spark execution basics.

**Thực hành:**

- Cài PySpark.
- Đọc dữ liệu CSV/Parquet.
- Xử lý dữ liệu bằng DataFrame.
- Thực hiện joins và aggregations.
- Quan sát Spark UI.

### Tuần 18 — Spark Optimization

**Kiến thức cần học:**

- Shuffle.
- Narrow vs wide transformations.
- Broadcast joins.
- Caching.
- Data skew.
- Partition tuning.
- Spark execution plans.
- Adaptive Query Execution.
- Spark UI.
- Performance benchmarking.

**Thực hành:**

- Tối ưu Spark joins.
- Phân tích shuffle.
- Thử nghiệm caching.
- Xử lý data skew.
- Benchmark trước và sau tối ưu.

### Tuần 19 — Data Lake & File Formats

**Kiến thức cần học:**

- Data Lake.
- Data Warehouse vs Data Lake.
- Data Lakehouse.
- Parquet.
- Avro.
- Columnar storage.
- Compression.
- Partition pruning.
- Small-file problem.
- Object storage.
- Bronze/Silver/Gold architecture.

**Thực hành:**

- Chuyển CSV sang Parquet.
- So sánh kích thước và hiệu suất.
- Thiết kế data lake.
- Xây Bronze/Silver/Gold bằng Spark.

### Tuần 20 — Apache Iceberg & Lakehouse

**Kiến thức cần học:**

- Apache Iceberg fundamentals.
- Table metadata.
- Snapshots.
- Schema evolution.
- Partition evolution.
- ACID concepts.
- Spark integration.
- Lakehouse batch processing.

**Thực hành:**

- Tạo Iceberg tables.
- Ghi và đọc dữ liệu bằng Spark.
- Thử nghiệm schema evolution.
- Xây mini Lakehouse.

**Điều kiện chuyển Phase 6:**

- Viết được PySpark transformations.
- Hiểu Spark execution model.
- Đọc và phân tích Spark execution plans.
- Xác định bottleneck.
- Sử dụng Parquet.
- Giải thích Data Lakehouse và Iceberg.
- Có benchmark tối ưu Spark job.

---

# PHASE 6 — REALTIME DATA ENGINEERING

**Thời gian:** Tuần 21–24

**Thời lượng:** 48–60 giờ

## 17. Mục tiêu

Xây dựng streaming pipeline và hiểu cách xử lý event trong các hệ thống dữ liệu realtime.

## 18. Nội dung chi tiết

### Tuần 21 — Apache Kafka Fundamentals

**Kiến thức cần học:**

- Event-driven architecture.
- Message brokers.
- Apache Kafka architecture.
- Brokers.
- Topics.
- Partitions.
- Offsets.
- Producers.
- Consumers.
- Consumer groups.
- Replication.
- Event ordering.

**Thực hành:**

- Chạy Kafka bằng Docker Compose.
- Tạo topics.
- Viết producer.
- Viết consumer.
- Thử nghiệm consumer groups.

### Tuần 22 — Kafka Reliability & Event Processing

**Kiến thức cần học:**

- JSON/Avro serialization.
- Schema compatibility.
- Message keys.
- Offset management.
- Delivery semantics.
- At-most-once.
- At-least-once.
- Exactly-once concepts và giới hạn.
- Replay.
- Dead-letter topics.
- Consumer recovery.

**Thực hành:**

- Xây order-event producer.
- Xây consumer xử lý đơn hàng.
- Thử nghiệm duplicate events.
- Thử nghiệm consumer restart.
- Xử lý lỗi serialization.

### Tuần 23 — Spark Structured Streaming

**Kiến thức cần học:**

- Structured Streaming.
- Streaming DataFrames.
- Event time.
- Processing time.
- Windowing.
- Watermarking.
- Stateful processing.
- Checkpointing.
- Late-arriving events.
- Streaming aggregations.

**Thực hành:**

- Đọc Kafka stream bằng Spark.
- Tính doanh thu theo thời gian.
- Xử lý late events.
- Cấu hình checkpointing.
- Ghi kết quả vào analytics sink.

### Tuần 24 — Streaming Reliability & Project

**Kiến thức cần học:**

- Streaming reliability.
- Deduplication.
- Idempotent sinks.
- Backpressure.
- Consumer lag.
- Monitoring.
- Failure recovery.
- Streaming performance.

**Thực hành:**

- Xử lý duplicate events.
- Theo dõi consumer lag.
- Restart streaming job.
- Kiểm thử checkpoint recovery.
- Hoàn thiện Project 3.

## 19. Project 3 — Realtime Order Analytics

**Công nghệ:**

- Python
- Apache Kafka
- PySpark
- Spark Structured Streaming
- PostgreSQL
- Docker

**Kiến trúc:**

Order Event Generator  
↓  
Apache Kafka  
↓  
Spark Structured Streaming  
↓  
Event Cleaning & Deduplication  
↓  
Window Aggregations  
↓  
Analytics Sink  
↓  
Realtime Dashboard

**Yêu cầu:**

- Có Kafka producer/consumer.
- Có event schema.
- Có streaming transformations.
- Có window aggregations.
- Có checkpointing.
- Có duplicate handling.
- Có consumer lag monitoring.
- Có failure recovery test.
- Có README và architecture diagram.

**Điều kiện chuyển Phase 7:** Có thể tự xây dựng, giải thích và debug một streaming pipeline, bao gồm xử lý duplicate, late events và consumer restart.

---

# PHASE 7 — PRODUCTION ENGINEERING & CAPSTONE

**Thời gian:** Tuần 25–29

**Thời lượng:** 60–75 giờ

## 20. Mục tiêu

Xây dựng hệ thống dữ liệu có khả năng triển khai, kiểm thử, giám sát, bảo trì và khôi phục khi gặp lỗi.

## 21. Nội dung chi tiết

### Tuần 25 — Software Engineering for Data Engineers

**Kiến thức cần học:**

- Clean code.
- Modular architecture.
- Separation of concerns.
- Configuration management.
- Dependency management.
- pytest.
- Unit tests.
- Integration tests.
- Mocking.
- Data contracts.
- Code review.

**Thực hành:**

- Refactor ETL project.
- Viết unit tests.
- Viết integration tests.
- Chuẩn hóa project structure.
- Kiểm tra cấu hình và dependencies.

### Tuần 26 — CI/CD for Data Engineering

**Kiến thức cần học:**

- Continuous Integration.
- Continuous Delivery/Deployment.
- GitHub Actions.
- Automated linting.
- Automated testing.
- Docker image build.
- Container registry.
- Deployment workflows.
- Rollback concepts.
- Environment separation.

**Thực hành:**

- Tạo GitHub Actions workflow.
- Chạy tests khi tạo Pull Request.
- Build Docker image.
- Push image lên registry.
- Thiết kế deployment workflow.

### Tuần 27 — Observability & Monitoring

**Kiến thức cần học:**

- Structured logging.
- Metrics.
- Tracing fundamentals.
- Prometheus.
- Grafana.
- Alerting.
- SLI/SLO.
- Pipeline health monitoring.
- Incident response.
- Root cause analysis.

**Thực hành:**

- Thu thập pipeline metrics.
- Xây Grafana dashboard.
- Thiết lập alerts.
- Mô phỏng pipeline failure.
- Viết incident report.

### Tuần 28 — Reliability, Security & Cost

**Kiến thức cần học:**

- Idempotency.
- Backfill.
- Disaster recovery.
- Secret management.
- IAM.
- Principle of least privilege.
- PII handling.
- Data retention.
- Data lineage.
- Cost optimization.
- Reliability engineering.

**Thực hành:**

- Thử nghiệm failure recovery.
- Kiểm tra quyền truy cập.
- Thiết lập secrets.
- Đánh giá rủi ro dữ liệu.
- Tối ưu chi phí hệ thống.

### Tuần 29 — Final Capstone Integration

**Kiến thức và công việc:**

- System integration.
- Architecture review.
- Performance benchmarking.
- Load testing.
- End-to-end testing.
- Documentation.
- Deployment verification.
- Final demo.
- Technical presentation.

**Thực hành:**

- Tích hợp batch pipeline.
- Tích hợp streaming pipeline.
- Hoàn thiện monitoring.
- Hoàn thiện CI/CD.
- Kiểm thử hệ thống.
- Viết documentation.
- Demo kiến trúc.

## 22. Project 4 — E-commerce Data Platform (Capstone)

### Mục tiêu

Xây dựng một hệ thống Data Engineering end-to-end có khả năng xử lý dữ liệu batch và streaming.

### Công nghệ

- Python
- PostgreSQL
- Docker
- Apache Airflow
- dbt
- GCP
- Cloud Storage
- BigQuery
- Apache Spark
- Apache Kafka
- GitHub Actions
- pytest
- Grafana/Prometheus

### Kiến trúc Batch

CSV / REST API / PostgreSQL  
↓  
Python Ingestion  
↓  
Airflow Orchestration  
↓  
GCS / BigQuery Raw Layer  
↓  
dbt / SQL / Spark Transformations  
↓  
BigQuery Analytics Marts  
↓  
Reporting

### Kiến trúc Streaming

Order Event Generator  
↓  
Apache Kafka  
↓  
Spark Structured Streaming  
↓  
Cleaning / Deduplication / Window Aggregations  
↓  
PostgreSQL Analytics Sink  
↓  
Realtime Dashboard

### Thành phần hỗ trợ

- Docker và Docker Compose.
- CI/CD bằng GitHub Actions.
- Automated testing.
- Data quality validation.
- Logging.
- Metrics.
- Monitoring.
- IAM và secret management.
- Documentation.
- Failure recovery.

### Checklist hoàn thành Capstone

- [ ] Có sơ đồ kiến trúc tổng thể.
- [ ] Giải thích được lựa chọn công nghệ.
- [ ] Batch pipeline có incremental loading.
- [ ] Batch pipeline có retry và backfill.
- [ ] dbt transformations có tests.
- [ ] Streaming pipeline có checkpointing.
- [ ] Streaming pipeline xử lý duplicate.
- [ ] Streaming pipeline khôi phục được sau restart.
- [ ] Có automated tests.
- [ ] Có CI/CD.
- [ ] Có logging và monitoring.
- [ ] Có cảnh báo lỗi.
- [ ] Có quản lý secrets.
- [ ] Có tài liệu triển khai.
- [ ] Có tài liệu vận hành và khôi phục.
- [ ] Có performance benchmark.
- [ ] Có README chuyên nghiệp.
- [ ] Có ảnh hoặc video demo.
- [ ] Có thể trình bày kiến trúc trong buổi phỏng vấn.

**Điều kiện chuyển Phase 8:** Có thể tự triển khai, kiểm thử, giám sát và giải thích toàn bộ hệ thống Capstone.

---

# PHASE 8 — AI-ASSISTED DATA ENGINEERING & CAREER PREPARATION

**Thời gian:** Tuần 30–32

**Thời lượng:** 36–45 giờ

## 23. Mục tiêu

Sử dụng AI hỗ trợ công việc Data Engineering và chuẩn bị năng lực ứng tuyển Fresher/Junior.

## 24. Nội dung chi tiết

### Tuần 30 — AI-Assisted Data Engineering

**Kiến thức cần học:**

- AI-assisted development.
- Prompting cho SQL/Python.
- AI code review.
- AI test generation.
- AI documentation.
- AI log analysis.
- AI-assisted debugging.
- Security khi sử dụng AI.
- Code verification.

**Thực hành:**

- Sử dụng AI để review ETL code.
- Tạo test cases.
- Phân tích pipeline logs.
- Refactor code.
- Kiểm chứng kết quả AI.

### Tuần 31 — AI Workflow & Data Engineering Agents

**Kiến thức cần học:**

- AI Agent fundamentals.
- Tool calling.
- Human-in-the-loop.
- Read-only SQL agents.
- Data quality assistants.
- AI workflow orchestration.
- Guardrails.
- Permission boundaries.
- AI output validation.

**Thực hành:**

- Xây AI assistant hỗ trợ kiểm tra data quality.
- Tạo công cụ phân tích pipeline logs.
- Thiết lập quyền truy cập chỉ đọc.
- Kiểm thử các trường hợp AI trả lời sai.

**Lưu ý:** Đây là phần mở rộng. Nếu kỹ năng SQL, Spark, Airflow hoặc Cloud chưa vững, nên dành thời gian củng cố thay vì ưu tiên AI Agent.

### Tuần 32 — Career Preparation

**Kiến thức cần học:**

- SQL interview.
- Python interview.
- Data Engineering fundamentals.
- ETL/ELT interview questions.
- Data modeling interview questions.
- Airflow interview.
- Spark interview.
- Kafka fundamentals interview.
- Cloud fundamentals.
- System design basics.
- CV preparation.
- GitHub portfolio.
- Technical presentation.

**Thực hành:**

- Hoàn thiện CV.
- Chuẩn hóa GitHub repositories.
- Viết README cho các project.
- Tạo portfolio.
- Mock interview.
- Trình bày Capstone trong 10–15 phút.

**Điều kiện hoàn thành roadmap:**

- Có ít nhất hai project chất lượng tốt được công khai.
- Có một project end-to-end hoàn chỉnh.
- Có khả năng giải thích code và kiến trúc.
- Có thể tự debug các lỗi thông thường.
- Hiểu các trade-off kỹ thuật cơ bản.
- Có CV và portfolio sẵn sàng ứng tuyển.

---

# PHẦN IV. BỘ CÔNG NGHỆ CẦN HỌC

## 25. Technology Stack

| Nhóm | Công nghệ | Ưu tiên |
|---|---|---|
| Programming | Python, SQL, Bash | Bắt buộc |
| Database | PostgreSQL | Bắt buộc |
| Version Control | Git, GitHub | Bắt buộc |
| Operating System | Linux | Bắt buộc |
| Containerization | Docker, Docker Compose | Bắt buộc |
| Data Ingestion | REST API, CSV, JSON | Bắt buộc |
| Data Processing | ETL/ELT, Incremental Load | Bắt buộc |
| Data Modeling | Dimensional Modeling, Star Schema | Bắt buộc |
| Orchestration | Apache Airflow | Bắt buộc |
| Transformation | dbt Core | Rất nên học |
| Data Warehouse | BigQuery | Bắt buộc trong lộ trình GCP |
| Cloud | GCP, GCS, IAM, Cloud Run | Rất nên học |
| Testing | pytest, dbt tests | Bắt buộc |
| CI/CD | GitHub Actions | Bắt buộc |
| Big Data | Apache Spark, PySpark | Rất nên học |
| File Formats | Parquet, Avro | Rất nên học |
| Streaming | Apache Kafka | Nên học |
| Lakehouse | Apache Iceberg | Mở rộng |
| Monitoring | Logging, Grafana, Prometheus | Rất nên học |
| Infrastructure as Code | Terraform | Cơ bản |
| AI | AI-assisted development, AI Agent | Mở rộng |

## 26. Công nghệ chưa cần ưu tiên

- Power BI nâng cao.
- DAX chuyên sâu.
- Machine Learning nâng cao.
- Deep Learning.
- Kubernetes chuyên sâu.
- Hadoop MapReduce chuyên sâu.
- Học đồng thời AWS, Azure và GCP.
- Nhiều streaming frameworks cùng lúc.
- Nhiều orchestration frameworks cùng lúc.
- AI Agent phức tạp trước khi vững Data Engineering.

Các công nghệ này không phải không có giá trị, nhưng không nên làm phân tán thời gian học khi mục tiêu chính là Data Engineer Fresher/Junior.

---

# PHẦN V. PHÂN BỔ THỜI GIAN

## 27. Thời gian theo giai đoạn

| Giai đoạn | Số tuần | Số giờ dự kiến |
|---|---:|---:|
| Phase 1 — Foundation | 4 | 48–60 |
| Phase 2 — Data Pipeline | 4 | 48–60 |
| Phase 3 — Analytics Engineering | 4 | 48–60 |
| Phase 4 — Cloud | 4 | 48–60 |
| Phase 5 — Big Data | 4 | 48–60 |
| Phase 6 — Streaming | 4 | 48–60 |
| Phase 7 — Production & Capstone | 5 | 60–75 |
| Phase 8 — AI & Career | 3 | 36–45 |
| **Tổng** | **32** | **384–480** |

## 28. Phân bổ thời gian học mỗi tuần

Khuyến nghị:

- 30% học lý thuyết và tài liệu.
- 50% thực hành viết code.
- 20% kiểm thử, debugging và tổng kết.

Ví dụ với 15 giờ/tuần:

- 3 giờ học lý thuyết.
- 8 giờ thực hành.
- 2 giờ debugging.
- 2 giờ tổng kết và documentation.

Trong các tuần làm project, có thể tăng tỷ trọng thực hành lên 60–70%.

## 29. Nguyên tắc quản lý tiến độ

- Không chuyển giai đoạn chỉ vì đã hết số tuần.
- Chỉ chuyển khi đáp ứng checkpoint.
- Nếu chưa đạt, dành thêm thời gian củng cố.
- Mỗi tuần phải có sản phẩm thực hành.
- Mỗi project phải được lưu trên GitHub.
- Ghi lại lỗi và cách khắc phục.
- Ưu tiên hiểu bản chất hơn ghi nhớ câu lệnh.
- Không sao chép code AI mà không kiểm chứng.

---

# PHẦN VI. ĐIỀU KIỆN CHUYỂN GIAI ĐOẠN

## 30. Phase Completion Criteria

| Giai đoạn | Điều kiện bắt buộc |
|---|---|
| Phase 1 | Viết SQL, Python và thao tác Git/Linux độc lập |
| Phase 2 | Tự xây batch ETL có incremental load và xử lý lỗi |
| Phase 3 | Chạy Airflow + dbt + PostgreSQL bằng Docker |
| Phase 4 | Triển khai pipeline trên GCP và truy vấn BigQuery |
| Phase 5 | Viết, debug và tối ưu PySpark job |
| Phase 6 | Xây Kafka producer/consumer và xử lý event |
| Phase 7 | Deploy, test, monitor và khôi phục pipeline |
| Phase 8 | Giải thích kiến trúc, trình bày project và trả lời câu hỏi phỏng vấn |

### Quy tắc đánh giá

Một giai đoạn được coi là hoàn thành khi:

1. Hiểu các khái niệm cốt lõi.
2. Có thể giải thích bằng lời của mình.
3. Có thể tự viết code thực hành.
4. Có thể debug những lỗi phổ biến.
5. Hoàn thành sản phẩm đầu ra.
6. Có thể giải thích vì sao chọn giải pháp kỹ thuật đó.

Nếu chỉ xem tutorial và chạy lại code mẫu, chưa nên coi là thành thạo.

---

# PHẦN VII. NHỮNG THAY ĐỔI SO VỚI HAI ROADMAP GỐC

## 31. Các thay đổi chủ động

| Thay đổi | Lý do |
|---|---|
| Đưa Linux và Git lên đầu | Đây là nền tảng để học và triển khai các công cụ khác |
| Bổ sung Python Software Engineering | Giúp code dễ bảo trì, kiểm thử và mở rộng |
| Tăng trọng số SQL và PostgreSQL | SQL là kỹ năng nền tảng quan trọng của Data Engineer |
| Đưa Data Modeling trước dbt | Cần hiểu mô hình dữ liệu trước khi xây transformation |
| Học Docker trước Airflow | Giúp quản lý môi trường thực hành dễ hơn |
| Đưa dbt thành module riêng | Phù hợp với Analytics Engineering và ELT hiện đại |
| Bổ sung incremental loading và idempotency | Giúp pipeline có thể chạy lại an toàn |
| Học Cloud trước Spark/Kafka nâng cao | Hoàn thiện batch pipeline trên cloud trước khi tăng độ phức tạp |
| Học sâu một Cloud là GCP | Tránh phân tán thời gian học nhiều cloud cùng lúc |
| Bổ sung testing và CI/CD | Giúp code có khả năng triển khai và bảo trì |
| Bổ sung security và reliability | Phản ánh các yêu cầu quan trọng khi vận hành hệ thống |
| Bổ sung monitoring và observability | Giúp phát hiện và phân tích lỗi |
| Tăng thời gian cho Capstone | Có thời gian tích hợp, debug, benchmark và documentation |
| Giảm trọng số AI Agent | Ưu tiên kỹ năng DE cốt lõi trước |
| Dùng E-commerce làm project xuyên suốt | Giúp liên kết kiến thức và tạo portfolio nhất quán |
| Loại Power BI/DAX nâng cao khỏi phần bắt buộc | Không phải trọng tâm của Data Engineering |
| Bổ sung điều kiện chuyển giai đoạn | Đánh giá năng lực thực tế thay vì chỉ dựa vào thời gian |

## 32. Những điểm giữ lại từ Roadmap 1

- E-commerce project xuyên suốt.
- SQL và Python foundations.
- ETL/ELT.
- Apache Airflow.
- Apache Spark.
- Spark optimization.
- Apache Kafka.
- Streaming processing.
- Data Lake.
- Data Warehouse.
- Data Quality.
- Monitoring.
- AI-assisted Data Engineering.

## 33. Những điểm giữ lại từ Roadmap 2

- Git workflow.
- Python engineering.
- Docker và Docker Compose.
- Google Cloud Platform.
- BigQuery.
- dbt.
- Data Warehouse modeling.
- Automated testing.
- CI/CD.
- Cloud deployment.
- Production engineering.
- Data observability.
- Lakehouse fundamentals.

## 34. Những kiến thức bổ sung hoặc nhấn mạnh hơn

- Linux fundamentals.
- HTTP và API reliability.
- SQL execution plans.
- Python typing và project structure.
- Incremental loading.
- Watermark management.
- Idempotency.
- Data contracts.
- Schema evolution.
- Backfill.
- Data lineage.
- Secret management.
- IAM.
- Cost optimization.
- Failure recovery.
- Performance benchmarking.
- System design fundamentals.
- Incident response.
- Portfolio preparation.

---

# PHẦN VIII. TÀI LIỆU HỌC TẬP

## 35. Tài liệu chính thức

### Python

https://docs.python.org/3/

Nội dung cần tập trung:

- Python tutorial.
- Standard library.
- File handling.
- Exceptions.
- Logging.
- Typing.
- Virtual environments.

### PostgreSQL

https://www.postgresql.org/docs/

Nội dung cần tập trung:

- SQL.
- Indexes.
- Transactions.
- Query planning.
- EXPLAIN.
- Performance.

### Git

https://git-scm.com/doc

Nội dung cần tập trung:

- Git basics.
- Branching.
- Merging.
- Remote repositories.

### Docker

https://docs.docker.com/

Nội dung cần tập trung:

- Dockerfile.
- Containers.
- Images.
- Volumes.
- Networks.
- Docker Compose.

### Apache Airflow

https://airflow.apache.org/docs/

Nội dung cần tập trung:

- DAGs.
- Scheduling.
- Tasks.
- Operators.
- TaskFlow.
- Backfill.
- Monitoring.

### dbt

https://docs.getdbt.com/

Nội dung cần tập trung:

- dbt Core.
- Models.
- Sources.
- Tests.
- Incremental models.
- Documentation.
- Best practices.

### Google Cloud

https://cloud.google.com/docs

Nội dung cần tập trung:

- IAM.
- Cloud Storage.
- BigQuery.
- Cloud Run.
- Cloud Scheduler.
- Cloud Logging.

### Apache Spark

https://spark.apache.org/docs/latest/

Nội dung cần tập trung:

- Spark SQL.
- DataFrames.
- Performance tuning.
- Structured Streaming.
- Monitoring.

### Apache Kafka

https://kafka.apache.org/documentation/

Nội dung cần tập trung:

- Producers.
- Consumers.
- Topics.
- Partitions.
- Consumer groups.
- Delivery semantics.
- Operations.

### Apache Iceberg

https://iceberg.apache.org/docs/latest/

Nội dung cần tập trung:

- Table format.
- Snapshots.
- Schema evolution.
- Partition evolution.

### GitHub Actions

https://docs.github.com/en/actions

Nội dung cần tập trung:

- Workflows.
- Automated testing.
- CI/CD.
- Secrets.
- Deployment.

### pytest

https://docs.pytest.org/

Nội dung cần tập trung:

- Test functions.
- Fixtures.
- Parametrization.
- Mocking.
- Test organization.

### Terraform

https://developer.hashicorp.com/terraform/docs

Nội dung cần tập trung:

- Providers.
- Resources.
- State.
- Plan/apply.
- Infrastructure as Code.

## 36. Cách sử dụng tài liệu

- Ưu tiên official documentation.
- Học các phần liên quan trực tiếp đến bài thực hành.
- Không cần đọc toàn bộ documentation từ đầu đến cuối.
- Kết hợp documentation với bài tập.
- Ghi chú các lỗi gặp phải.
- Tự viết lại ví dụ theo dữ liệu E-commerce.
- Kiểm tra phiên bản công nghệ khi thực hành.
- Tránh phụ thuộc hoàn toàn vào video tutorial.

---

# PHẦN IX. PORTFOLIO & PROJECT STRATEGY

## 37. Danh sách 4 project

| Project | Thời điểm | Công nghệ chính |
|---|---|---|
| Project 1 — E-commerce Batch ETL | Tuần 8 | Python, SQL, PostgreSQL |
| Project 2 — Automated Analytics Platform | Tuần 12 | Docker, Airflow, dbt |
| Project 3 — Realtime Order Analytics | Tuần 24 | Kafka, Spark Streaming |
| Project 4 — E-commerce Data Platform | Tuần 29 | GCP, BigQuery, Spark, Kafka, Airflow, dbt, CI/CD |

## 38. Tiêu chuẩn GitHub Repository

Mỗi project nên có:

- README.md.
- Architecture diagram.
- Source code.
- Requirements/dependencies.
- Configuration example.
- Dockerfile nếu cần.
- Docker Compose nếu cần.
- SQL scripts.
- Automated tests.
- Sample data hoặc data generator.
- Hướng dẫn chạy.
- Hướng dẫn kiểm thử.
- Hướng dẫn xử lý lỗi.
- Screenshots/demo.
- Mô tả các quyết định kỹ thuật.

## 39. Cách trình bày project khi phỏng vấn

Cần giải thích được:

1. Bài toán cần giải quyết.
2. Nguồn dữ liệu.
3. Kiến trúc tổng thể.
4. Vì sao chọn công nghệ.
5. Cách dữ liệu di chuyển.
6. Cách xử lý lỗi.
7. Cách kiểm thử.
8. Cách theo dõi hệ thống.
9. Những bottleneck đã gặp.
10. Những cải tiến có thể thực hiện.

---

# PHẦN X. CHIẾN LƯỢC ỨNG TUYỂN

## 40. Khi nào có thể bắt đầu ứng tuyển?

Không nhất thiết phải hoàn thành toàn bộ 32 tuần mới bắt đầu tìm việc.

### Sau Phase 2

Có thể bắt đầu tìm hiểu yêu cầu tuyển dụng, luyện SQL/Python và quan sát các vị trí Data Engineer Intern/Fresher.

### Sau Phase 3

Đã có nền tảng batch pipeline, Docker, dbt và Airflow. Có thể bắt đầu chuẩn bị CV và portfolio.

### Sau Phase 4

Đã có thêm kinh nghiệm thực hành cloud, BigQuery và deployment. Đây là thời điểm hợp lý để bắt đầu ứng tuyển các vị trí Intern/Fresher phù hợp, nếu có project đủ tốt.

### Sau Phase 6

Có thêm Spark và Kafka, giúp mở rộng phạm vi công việc có thể tiếp cận.

### Sau Phase 7–8

Có Capstone, CI/CD, monitoring, reliability và kỹ năng trình bày hệ thống, giúp portfolio hoàn chỉnh hơn.

## 41. Các vị trí có thể hướng tới

- Data Engineer Intern.
- Fresher Data Engineer.
- Junior Data Engineer (tùy yêu cầu và năng lực thực tế).
- Analytics Engineer Intern/Fresher.
- ETL Developer.
- Data Pipeline Developer.
- Cloud Data Engineer Intern/Fresher.

---

# PHẦN XI. RỦI RO VÀ LƯU Ý

## 42. Những sai lầm cần tránh

### 42.1. Học quá nhiều công nghệ cùng lúc

Không nên học AWS, Azure và GCP đồng thời khi chưa nắm vững một nền tảng.

### 42.2. Chỉ học lý thuyết

Data Engineering yêu cầu khả năng xây dựng, kiểm thử và debug hệ thống.

### 42.3. Sao chép tutorial

Chạy được code mẫu không đồng nghĩa với hiểu cách hệ thống hoạt động.

### 42.4. Học Spark/Kafka quá sớm

Nếu chưa hiểu batch pipeline, SQL, Python và database, việc học distributed systems sẽ khó hơn nhiều.

### 42.5. Bỏ qua Data Modeling

Pipeline tốt nhưng mô hình dữ liệu không phù hợp vẫn có thể tạo ra dữ liệu khó sử dụng.

### 42.6. Bỏ qua testing

Pipeline không có kiểm thử rất dễ phát sinh lỗi dữ liệu âm thầm.

### 42.7. Không quan tâm chi phí Cloud

Cần thiết lập budget alerts và dọn dẹp tài nguyên không sử dụng.

### 42.8. Quá phụ thuộc AI

AI có thể tạo ra code sai, SQL không tối ưu hoặc cách xử lý dữ liệu không phù hợp.

### 42.9. Không viết documentation

Project khó chạy lại và khó đánh giá nếu thiếu tài liệu.

### 42.10. Chờ học hết mới ứng tuyển

Nên bắt đầu chuẩn bị portfolio và tìm hiểu thị trường tuyển dụng từ giữa lộ trình.

---

# PHẦN XII. KẾT LUẬN VÀ ĐỊNH HƯỚNG CUỐI CÙNG

## 43. Thứ tự ưu tiên học tập

**Core Foundation:**

SQL + Python + Linux + Git + PostgreSQL.

**Core Data Engineering:**

Data Modeling + ETL/ELT + Incremental Loading + Docker + dbt + Airflow.

**Cloud Data Engineering:**

GCP + Cloud Storage + BigQuery + Cloud Deployment.

**Advanced Data Engineering:**

PySpark + Spark Optimization + Parquet + Lakehouse + Kafka + Streaming.

**Production Engineering:**

Testing + CI/CD + Monitoring + Security + Reliability.

**Optional Extension:**

AI-assisted Data Engineering + AI Agent.

## 44. Các mốc năng lực

**Mốc 1 — Tuần 4:** Có nền tảng lập trình và cơ sở dữ liệu.

**Mốc 2 — Tuần 8:** Tự xây dựng batch ETL pipeline.

**Mốc 3 — Tuần 12:** Tự động hóa pipeline bằng Airflow và dbt.

**Mốc 4 — Tuần 16:** Triển khai batch pipeline trên GCP.

**Mốc 5 — Tuần 20:** Xử lý dữ liệu bằng Spark và hiểu Lakehouse.

**Mốc 6 — Tuần 24:** Xây dựng streaming pipeline với Kafka.

**Mốc 7 — Tuần 29:** Hoàn thiện Data Engineering Capstone.

**Mốc 8 — Tuần 32:** Hoàn thiện portfolio và chuẩn bị phỏng vấn.

## 45. Đánh giá tổng thể

Roadmap này kết hợp:

- Nền tảng SQL/Python.
- Data Pipeline Engineering.
- Analytics Engineering.
- Cloud Data Engineering.
- Big Data Processing.
- Realtime Streaming.
- Production Engineering.
- AI-assisted Development.
- Career Preparation.

Lộ trình được thiết kế để tạo ra sự phát triển liên tục về năng lực, từ viết chương trình xử lý dữ liệu đơn giản đến xây dựng một hệ thống Data Engineering có nhiều thành phần.

Trọng tâm không phải là học được bao nhiêu công cụ, mà là hiểu cách dữ liệu vận hành, biết lựa chọn giải pháp phù hợp và có khả năng xây dựng hệ thống đáng tin cậy.

## 46. Khuyến nghị cuối cùng

**Thứ tự học chính thức:**

SQL + Python → Data Modeling → ETL/ELT → Docker → dbt → Airflow → Cloud → Spark → Kafka → Production → AI.

**Chiến lược học:**

- Học chắc nền tảng.
- Thực hành liên tục.
- Hoàn thành checkpoint.
- Xây project xuyên suốt.
- Viết tests và documentation.
- Học cách debug.
- Hiểu các trade-off kỹ thuật.
- Chuẩn bị ứng tuyển từ khi đã có nền tảng và project phù hợp.

**Nguyên tắc quan trọng nhất:**

> Không đánh giá tiến độ học Data Engineering bằng số lượng video đã xem, khóa học đã hoàn thành hay công nghệ đã nghe qua. Hãy đánh giá bằng khả năng tự thiết kế, xây dựng, kiểm thử, giải thích và vận hành một data pipeline.

---

**TÊN ROADMAP:** DATA ENGINEER ROADMAP 2026–2027

**THỜI LƯỢNG:** 32 TUẦN

**GIAI ĐOẠN:** 8

**PROJECT:** 4

**MỤC TIÊU:** DATA ENGINEER FRESHER/JUNIOR

**PHƯƠNG PHÁP:** LEARN → PRACTICE → BUILD → TEST → DEBUG → DOCUMENT → REVIEW

**TRẠNG THÁI:** ROADMAP TỔNG HỢP — PHIÊN BẢN 1.0