# Kata Và Dự Án Thực Hành

Kata là bài luyện lặp lại có phản hồi nhanh. Project là bài tổng hợp có nhiều trade-off. Một learning system tốt cần cả hai.

## Kata software

### Git PR Kata

Mục tiêu: làm quen workflow chuẩn.

- Tạo branch từ main.
- Sửa một bug nhỏ.
- Viết/bổ sung test.
- Commit với message rõ.
- Viết PR description: problem, solution, test.
- Review lại diff của chính mình.

Biến thể Ha:

- Rebase branch có conflict.
- Tách một PR lớn thành 2 PR nhỏ.
- Viết ADR cho thay đổi có ảnh hưởng kiến trúc.

### Testing Kata

Mục tiêu: chuyển yêu cầu thành test.

- Viết function parse input.
- Liệt kê happy path, edge case, invalid input.
- Viết unit test trước.
- Implement tối thiểu để pass.
- Refactor không đổi behavior.

Biến thể Ha:

- Thêm property-based tests.
- Thêm integration test với database.
- Tạo test data builder.

### Debugging Kata

Mục tiêu: debug có hệ thống.

- Chọn bug có sẵn hoặc tự tạo.
- Viết reproduction steps.
- Đặt giả thuyết.
- Thử log/debugger/trace.
- Ghi root cause và prevention.

Biến thể Ha:

- Debug bug chỉ xảy ra dưới load.
- Debug flaky test.
- Debug memory/performance issue.

## Kata AI/ML

### Metric Kata

Mục tiêu: không dùng metric theo thói quen.

- Chọn một bài classification.
- Tính accuracy, precision, recall, F1.
- Vẽ confusion matrix.
- Mô tả khi nào accuracy gây hiểu lầm.
- Chọn metric phù hợp với ngữ cảnh.

Biến thể Ha:

- Thêm class imbalance.
- Chia metric theo slice.
- Viết threshold analysis.

### Prompt Eval Kata

Mục tiêu: biến prompt thành thứ có thể đo.

- Tạo 20 input đại diện.
- Viết expected behavior.
- Chạy prompt version A.
- Sửa prompt thành version B.
- So sánh theo rubric 1-5.

Biến thể Ha:

- Thêm adversarial cases.
- Thêm cost/latency.
- Thêm automated judge và manual spot check.

### RAG Kata

Mục tiêu: hiểu retrieval trước khi tin answer.

- Tạo corpus 10 file Markdown.
- Chunk theo 2 cách.
- Embed và retrieve top-k.
- Tạo 30 câu hỏi có đáp án nằm trong corpus.
- Đo retrieval hit rate và answer correctness.

Biến thể Ha:

- Thêm metadata filter.
- Thêm reranker.
- Thêm citation và refusal out-of-scope.

## Kata CS

### Algorithm Invariant Kata

Mục tiêu: giải bài bằng invariant, không chỉ code.

- Chọn 1 bài: binary search, two pointers, BFS.
- Viết invariant trước khi code.
- Code.
- Chạy test edge case.
- Giải thích tại sao đúng.

Biến thể Ha:

- Biến đổi bài toán để pattern cũ không còn đúng hoàn toàn.
- So sánh 2 solution complexity khác nhau.

### Systems Observation Kata

Mục tiêu: thấy code đang dùng tài nguyên nào.

- Chạy một server nhỏ.
- Quan sát process, port, file, log.
- Gửi request và xem latency.
- Thêm load nhỏ.
- Ghi bottleneck đầu tiên.

Biến thể Ha:

- Thêm cache.
- Thêm database index.
- Tạo failure injection.

## Dự án cấp độ Shu

| Dự án | Năng lực | Output |
| --- | --- | --- |
| Todo CLI | file IO, test, CLI | repo có README và unit tests |
| REST Notes API | HTTP, DB, validation | API docs, integration tests |
| Linear Regression From Scratch | NumPy, loss, gradient | notebook có chart và report |
| Graph Visualizer | BFS/DFS | UI hoặc notebook minh họa |

## Dự án cấp độ Ha

| Dự án | Năng lực | Output |
| --- | --- | --- |
| Issue Tracker Mini | auth, API, DB, testing | service có migration và ADR |
| RAG Knowledge Base | retrieval, eval, citations | eval report và failure analysis |
| SQL Performance Lab | index, query plan | benchmark trước-sau |
| Tiny Cache Service | systems, latency | load test và trade-off note |

## Dự án cấp độ Ri

| Dự án | Năng lực | Output |
| --- | --- | --- |
| Team Service Template | platform, mentoring | starter kit người khác dùng được |
| AI Engineering Playbook | LLMOps, eval, safety | handbook + templates |
| CS Visual Mini-Course | teaching, abstraction | 3 lessons + exercises |
| Open Source Contribution Series | collaboration | 3 PR + reflection |
