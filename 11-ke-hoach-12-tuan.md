# Kế Hoạch Mẫu 12 Tuần

Kế hoạch này dành cho người muốn học song song software, AI và CS nhưng vẫn giữ trọng tâm. Mỗi tuần có một năng lực chính và một output rõ ràng.

## Giả định thời gian

- Nhẹ: 5-7 giờ/tuần, làm 60% scope.
- Vừa: 8-12 giờ/tuần, làm như kế hoạch.
- Nặng: 15-20 giờ/tuần, thêm biến thể Ha.

## Pha 1: Shu, tạo nền và workflow

### Tuần 1: Tool fluency

- Học: shell, editor, Git, project structure.
- Kata: Git PR Kata.
- Output: repo đầu tiên có README, branch, commit, PR-style notes.
- Done: chạy được project và giải thích workflow.

### Tuần 2: Testing và debugging

- Học: unit test, debugger, logging.
- Kata: Testing Kata + Debugging Kata.
- Output: CLI todo app có tests và failure log.
- Done: có ít nhất 10 test và 3 bug notes.

### Tuần 3: API và database cơ bản

- Học: HTTP, REST, SQL, migration.
- Kata: CRUD API.
- Output: Notes API có database và validation.
- Done: README có cách chạy, integration test cơ bản.

### Tuần 4: Algorithms fundamentals

- Học: Big-O, array/hash map/stack/queue/tree/graph.
- Kata: Algorithm Invariant Kata.
- Output: 15 bài algorithm có invariant note.
- Done: mỗi bài có complexity và edge cases.

## Pha 2: Ha, biến thể và trade-off

### Tuần 5: Refactor và architecture

- Học: module boundary, service/repository, dependency direction.
- Project: refactor Notes API.
- Output: ADR về kiến trúc và tests bảo vệ refactor.
- Done: giải thích được trade-off trước-sau.

### Tuần 6: SQL performance

- Học: EXPLAIN, index, query pattern.
- Kata: SQL Performance Lab.
- Output: benchmark trước-sau cho 3 query.
- Done: có report về index và trade-off write/read.

### Tuần 7: ML foundation

- Học: train/validation/test, regression/classification, metrics.
- Kata: Metric Kata.
- Output: notebook classifier có error analysis.
- Done: giải thích được metric chọn theo ngữ cảnh.

### Tuần 8: RAG foundation

- Học: embedding, chunking, retrieval, answer generation.
- Kata: RAG Kata.
- Output: RAG trên Markdown vault với 30 eval cases.
- Done: có retrieval hit rate và answer correctness.

## Pha 3: Ha sang Ri, tích hợp thành sản phẩm

### Tuần 9: LLM eval và safety

- Học: eval rubric, hallucination, refusal, prompt injection.
- Project: thêm eval harness cho RAG.
- Output: report failure modes và prompt/retrieval variants.
- Done: có pass rate theo version.

### Tuần 10: Systems và observability

- Học: latency, logs, timeout, retry, cache.
- Project: thêm observability/caching vào API hoặc RAG app.
- Output: benchmark latency và decision note.
- Done: có metrics trước-sau.

### Tuần 11: Product integration

- Học: user flow, UX, release criteria.
- Project: kết hợp Learning Journal API với AI/RAG assistant nhỏ.
- Output: demo v1 có README và eval/test.
- Done: người khác có thể chạy theo hướng dẫn.

### Tuần 12: Teaching và portfolio

- Học: viết guide, review, capstone report.
- Project: đóng gói thành portfolio.
- Output: 1 case study, 1 guide, 1 template/kata do bạn tạo.
- Done: artifact giúp người khác vào Shu.

## Review cuối 12 tuần

Trả lời các câu hỏi:

- Năng lực nào đã từ 0 lên Shu?
- Năng lực nào đã từ Shu lên Ha?
- Có bằng chứng nào chạm Ri?
- Project nào nên tiếp tục thêm 4 tuần?
- Lỗ hổng nào đang cần quay lại Shu?

## Biến thể theo mục tiêu

### Nếu muốn thành backend/software engineer

- Tăng thời gian tuần 5, 6, 10.
- Thêm auth, queue, deployment, monitoring.
- Capstone: production-grade API/service.

### Nếu muốn thành AI engineer

- Tăng thời gian tuần 7, 8, 9, 11.
- Thêm dataset design, RAG eval, tool calling, monitoring.
- Capstone: domain AI assistant có eval và guardrails.

### Nếu muốn lấp đầy CS foundation

- Tăng thời gian tuần 4, 6, 10.
- Thêm architecture, OS, networking, distributed systems labs.
- Capstone: Tiny Systems Lab.
