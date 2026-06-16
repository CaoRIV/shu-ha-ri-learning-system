# Bản Đồ Năng Lực

Dùng file này để chọn đúng "miền học" trước khi lập sprint. Mỗi năng lực nên được đánh giá riêng theo Shu-Ha-Ri.

## Nhóm năng lực cốt lõi

| Nhóm | Năng lực | Ví dụ sản phẩm |
| --- | --- | --- |
| Software craft | Code rõ ràng, test, refactor, debug | CLI tool, REST API, package nhỏ |
| Systems thinking | OS, networking, database, distributed systems | cache demo, TCP lab, SQL benchmark |
| CS foundation | DSA, discrete math, architecture, theory | bài giải algorithm, simulator, proof note |
| AI/ML foundation | Python, NumPy, stats, ML, deep learning | notebook tự viết model, experiment report |
| AI engineering | LLM app, RAG, eval, agents, monitoring | chatbot có eval, retrieval pipeline, agent tool |
| Product thinking | User problem, UX, metrics, iteration | PRD nhỏ, user flow, release note |
| Professional practice | Git, docs, security, collaboration | PR chất lượng, ADR, threat model |

## Shu-Ha-Ri theo từng năng lực

### Programming fundamentals

| Giai đoạn | Bạn làm được |
| --- | --- |
| Shu | Viết function/class theo yêu cầu, đọc docs, dùng debugger, viết unit test đơn giản |
| Ha | Tách module, refactor có test bảo vệ, chọn data structure theo trade-off |
| Ri | Thiết kế API/small library rõ ràng, tạo convention cho team, review code có chiều sâu |

### Algorithms and data structures

| Giai đoạn | Bạn làm được |
| --- | --- |
| Shu | Nhận ra pattern cơ bản: two pointers, stack, BFS/DFS, binary search, DP cơ bản |
| Ha | Chọn pattern theo invariant, phân tích độ phức tạp, biến đổi bài toán |
| Ri | Tạo lời giải mới, dạy người khác cách nhìn problem, ứng dụng algorithm vào system thật |

### Databases

| Giai đoạn | Bạn làm được |
| --- | --- |
| Shu | Viết CRUD, join, transaction cơ bản, migration theo mẫu |
| Ha | Đọc query plan, thiết kế index, chọn normalization/denormalization theo ngữ cảnh |
| Ri | Thiết kế data model tiến hóa được, tối ưu workload thật, đặt guardrail cho team |

### Backend and APIs

| Giai đoạn | Bạn làm được |
| --- | --- |
| Shu | Tạo endpoint, validate input, auth cơ bản, test happy path |
| Ha | Thiết kế error model, idempotency, pagination, caching, observability |
| Ri | Định nghĩa platform pattern, API governance, chiến lược scale và reliability |

### Frontend and UX engineering

| Giai đoạn | Bạn làm được |
| --- | --- |
| Shu | Dùng component có sẵn, state cơ bản, form, responsive layout |
| Ha | Thiết kế state flow, accessibility, performance, design system primitives |
| Ri | Tạo interaction model mới, component system bền vững, product UX có chiến lược |

### AI/ML foundations

| Giai đoạn | Bạn làm được |
| --- | --- |
| Shu | Chạy notebook, train model cơ bản, hiểu train/validation/test, metrics cơ bản |
| Ha | Thiết kế experiment, xử lý leakage, chọn metric theo business problem |
| Ri | Định nghĩa modeling strategy, eval framework, production learning loop |

### LLM applications

| Giai đoạn | Bạn làm được |
| --- | --- |
| Shu | Gọi API/model, prompt theo mẫu, thêm RAG đơn giản, logging cơ bản |
| Ha | Thiết kế eval set, chunking/retrieval strategy, tool use, cost/latency trade-off |
| Ri | Xây AI product có guardrails, monitoring, human feedback, domain-specific workflow |

### Computer systems

| Giai đoạn | Bạn làm được |
| --- | --- |
| Shu | Giải thích process, memory, file, network request ở mức cơ bản |
| Ha | Debug performance, contention, concurrency, IO, caching |
| Ri | Thiết kế system dựa trên constraint thật: latency, failure, cost, operability |

## Cách tự chấm điểm

Cho mỗi năng lực, chấm 0-3:

- 0: chưa có bằng chứng.
- 1: Shu, làm theo mẫu được.
- 2: Ha, biến thể có lý do.
- 3: Ri, tạo được pattern/sản phẩm/hướng dẫn cho người khác.

Bảng theo dõi mẫu:

| Năng lực | Điểm hiện tại | Bằng chứng | Sprint tiếp theo |
| --- | --- | --- | --- |
| Git workflow | 1 | Đã dùng branch/commit/PR theo mẫu | Làm PR có review checklist |
| SQL indexing | 0 | Mới biết SELECT/JOIN | Học EXPLAIN và index kata |
| RAG eval | 1 | Có demo RAG đơn giản | Tạo eval set 30 câu hỏi |

## Quy tắc chọn ưu tiên

- Ưu tiên điểm 0-1 nếu nó là blocker cho mục tiêu gần.
- Ưu tiên điểm 2 nếu bạn cần nâng cấp từ "làm được" sang "làm đúng trong sản phẩm".
- Ưu tiên điểm 3 chỉ khi bạn đã có người dùng, team, hoặc cộng đồng để đóng góp.
