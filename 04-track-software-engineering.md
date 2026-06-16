# Track Software Engineering

Mục tiêu track này là biến bạn từ người "viết code chạy" thành người có thể thiết kế, test, debug, ship và bảo trì software.

## Năng lực đầu ra

Sau track này, bạn nên có:

- 3-5 service/tool nhỏ có README, test, CI nếu có thể.
- Khả năng đọc codebase lạ, sửa bug, thêm feature có kiểm soát.
- Khả năng giải thích trade-off về architecture, testing, data, API.
- Thói quen ghi decision log và review code.

## Shu: làm đúng practice cơ bản

### Chủ đề

- Git: commit, branch, rebase/merge cơ bản, PR.
- Terminal và editor: command line, search, lint/format.
- Testing: unit test, integration test nhỏ, test data.
- API: REST/HTTP, validation, auth cơ bản.
- Database: schema, migration, CRUD, transaction.
- Debugging: logs, debugger, reproduce bug.
- Clean code: naming, function size, module boundary.

### Bài tập

- Tạo CLI todo app có file storage và test.
- Tạo REST API CRUD có validation và database.
- Viết 20 unit tests cho các function có edge case.
- Sửa 5 bug có sẵn trong project nhỏ và ghi root cause.
- Làm lại một tutorial framework nhưng không copy paste: gõ bằng tay, commit theo bước.

### Tiêu chí ra Shu

- Bạn có thể tạo project mới, test, run, debug mà không cần tutorial từng bước.
- Bạn biết đọc error message và tìm nguyên nhân đầu tiên.
- Bạn viết được README để người khác chạy project.
- Bạn có ít nhất 2 project nhỏ có test.

## Ha: chọn practice theo ngữ cảnh

### Chủ đề

- Architecture: layered, hexagonal, event-driven ở mức thực dụng.
- API design: pagination, idempotency, error model, versioning.
- Data: indexing, caching, consistency, migrations an toàn.
- Reliability: retry, timeout, circuit breaker, observability.
- Security: input validation, secrets, least privilege, threat modeling.
- Performance: profiling, benchmark, bottleneck.
- Team workflow: code review, ADR, issue breakdown.

### Bài tập

- Refactor CRUD API thành kiến trúc có domain/service/repository và so sánh trước-sau.
- Thêm cache vào endpoint chậm, đo latency trước-sau.
- Viết ADR cho việc chọn SQL hay document store.
- Tạo load test nhỏ và phân tích bottleneck.
- Viết threat model cho auth flow.
- Sửa một bug race condition hoặc transaction consistency trong lab.

### Tiêu chí ra Ha

- Bạn nói được vì sao một abstraction đang tồn tại.
- Bạn có thể bỏ abstraction khi nó chưa cần.
- Bạn thiết kế test theo risk, không chỉ theo coverage.
- Bạn có ít nhất 1 project có observability, migration, auth, error handling rõ ràng.

## Ri: tạo practice và dẫn dắt

### Chủ đề

- Platform thinking: internal templates, starter kits, shared libraries.
- Technical strategy: chọn constraint, lộ trình tiến hóa.
- Mentoring: code review có tính giáo dục.
- Incident learning: postmortem không đổ lỗi cá nhân.
- Open source/contribution: issue, PR, documentation.

### Bài tập

- Tạo starter template cho service mới với logging, testing, config, CI.
- Viết guide "cách team chúng ta thiết kế API".
- Đóng góp PR nhỏ vào open source hoặc tài liệu.
- Tổ chức mini code review clinic cho 1-2 người.
- Viết postmortem cho một incident/lab failure và tạo action item.

### Tiêu chí Ri

- Người khác dùng được pattern/tool/doc của bạn.
- Bạn giảm được thời gian onboarding hoặc lỗi lặp lại cho team.
- Bạn có thể thiết kế solution khác nhau theo size/criticality của project.
- Bạn giữ được sự đơn giản khi vấn đề phức tạp.

## Project capstone gợi ý

Xây "Learning Journal API":

- User đăng nhập, tạo learning sprint, log ngày, rubric tự đánh giá.
- Backend có DB migration, tests, OpenAPI docs.
- Thêm search/filter, export Markdown.
- Thêm observability cơ bản.
- Viết ADR cho 3 quyết định: framework, database, auth.
