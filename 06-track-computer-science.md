# Track Computer Science

Track này tạo nền tảng sâu cho software và AI. CS không chỉ là lý thuyết; nó là bộ máy tinh thần giúp bạn nhìn thấy constraint, structure và độ phức tạp.

## Năng lực đầu ra

Sau track này, bạn nên có:

- Notebook/bài giải cho algorithm và discrete math.
- Một vài simulator nhỏ: CPU toy, scheduler, cache, network protocol.
- Khả năng phân tích complexity, invariant, failure mode.
- Khả năng đọc tài liệu kỹ thuật khó mà không bị ngợp.

## Shu: học ngôn ngữ nền tảng

### Chủ đề

- Discrete math: logic, set, function, graph, induction, probability cơ bản.
- Data structures: array, linked list, stack, queue, hash map, tree, heap, graph.
- Algorithms: sorting, searching, BFS/DFS, shortest path, dynamic programming cơ bản.
- Computer architecture: memory, CPU, cache, assembly ý niệm.
- Operating systems: process, thread, virtual memory, file system.
- Networking: HTTP, TCP/IP, DNS, TLS ý niệm.

### Bài tập

- Giải 30 bài algorithm có ghi invariant.
- Viết lại data structures từ đầu.
- Làm Nand2Tetris hoặc simulator CPU toy phiên bản rút gọn.
- Viết shell commands để quan sát process, file, network.
- Vẽ sequence diagram cho một HTTP request từ browser đến server.

### Tiêu chí ra Shu

- Bạn giải thích được Big-O cho code của mình.
- Bạn nhận ra pattern algorithm cơ bản.
- Bạn có mental model "code chạy trên máy" thay vì chỉ thấy framework.
- Bạn làm được bài tập có đáp án mẫu và giải thích lại được.

## Ha: dùng nền tảng để chọn thiết kế

### Chủ đề

- Trade-off data structure theo workload.
- Complexity vs readability.
- Concurrency: locks, races, async, backpressure.
- Database internals: B-tree, WAL, transaction isolation ý niệm.
- Distributed systems: consensus ý niệm, replication, partition, eventual consistency.
- Security fundamentals: crypto primitives, auth protocols, threat models.

### Bài tập

- Benchmark list vs map vs tree cho workload khác nhau.
- Viết toy cache với eviction policies và so sánh hit rate.
- Mô phỏng race condition và sửa bằng lock/queue.
- Viết mini key-value store có append-only log.
- Thiết kế URL shortener và phân tích bottleneck.
- Đọc một paper/blog kỹ thuật và viết summary 1 trang.

### Tiêu chí ra Ha

- Bạn chọn data structure theo access pattern.
- Bạn biết nói về consistency/latency/cost bằng ví dụ.
- Bạn có thể debug performance dựa trên hypothesis.
- Bạn không dùng distributed system pattern cho vấn đề chỉ cần một database tốt.

## Ri: biến CS thành trực giác thiết kế

### Chủ đề

- System design có ràng buộc thật.
- Formal reasoning nhẹ: invariant, pre/post-condition, property-based testing.
- Research literacy: đọc paper, tái tạo kết quả nhỏ.
- Teaching CS: tạo visualizer, note, problem set.

### Bài tập

- Tạo visualizer cho graph algorithm hoặc scheduler.
- Viết property-based tests cho data structure tự viết.
- Đọc và tái hiện một ý tưởng từ paper/classic article.
- Thiết kế hệ thống có SLO, failure budget, capacity estimate.
- Tạo mini-course 3 buổi cho một chủ đề CS bạn đã nắm.

### Tiêu chí Ri

- Bạn dùng CS để làm system đơn giản hơn, không phải để làm nó có vẻ "academic".
- Bạn có thể tạo abstraction mới dựa trên invariant rõ ràng.
- Bạn giúp người khác thấy được bản chất của vấn đề.
- Bạn biết quay lại luyện cơ bản khi gặp miền mới.

## Project capstone gợi ý

Xây "Tiny Systems Lab":

- Mini key-value store.
- Cache layer có benchmark.
- HTTP API đọc/ghi key-value.
- Fault injection: delay, crash, corrupt input.
- Report giải thích data structure, consistency, performance.
