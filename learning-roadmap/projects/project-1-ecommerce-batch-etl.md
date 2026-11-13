# Project 1 — E-commerce Batch ETL

**Thời điểm:** Tuần 5–8  
**Mục tiêu:** Ingest nhiều nguồn, xử lý incremental an toàn và tạo dimensional data mart.

## Phạm vi

- [ ] Chọn ít nhất hai nguồn dữ liệu và ghi rõ schema/đặc tính cập nhật.
- [ ] Tạo raw/staging tables trong PostgreSQL.
- [ ] Xây ingestion có pagination hoặc đọc file, timeout/retry và logging.
- [ ] Thực hiện incremental load với watermark/upsert và khả năng chạy lại an toàn.
- [ ] Tạo fact/dimension model và data quality checks.
- [ ] Viết truy vấn phân tích, README và sơ đồ kiến trúc.

## Thiết kế và theo dõi

- Nguồn dữ liệu:
- Grain của fact:
- Khóa chính và khóa thay thế:
- Chiến lược incremental/idempotency:
- Kiểm tra chất lượng:
- Cách chạy và backfill:
- Link mã nguồn/commit:
