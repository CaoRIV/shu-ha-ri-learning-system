# Track AI, ML Và LLM Engineering

Track này tách rõ hai việc hay bị trộn lẫn: học nền tảng ML và xây ứng dụng AI. Bạn cần cả hai, nhưng mức độ sâu tùy mục tiêu.

## Năng lực đầu ra

Sau track này, bạn nên có:

- Notebook ML có experiment log và metric rõ ràng.
- Một ứng dụng LLM có eval set, logging, cost/latency note.
- Khả năng nhận biết data leakage, metric sai, prompt mong manh.
- Khả năng nói chuyện về trade-off giữa model, retrieval, UX, safety, cost.

## Shu: làm đúng pipeline cơ bản

### Chủ đề ML foundation

- Python, NumPy, pandas, plotting.
- Train/validation/test split.
- Regression, classification, clustering cơ bản.
- Loss, gradient descent, overfitting, regularization.
- Metrics: accuracy, precision/recall, F1, ROC-AUC, MAE/RMSE.
- Basic neural networks và training loop.

### Chủ đề LLM app foundation

- Prompt structure: role, context, task, constraints, examples.
- Function/tool calling ở mức cơ bản.
- Embeddings và vector search.
- RAG tối thiểu: load docs, chunk, retrieve, answer.
- Logging prompt/input/output.
- Manual eval bằng tập câu hỏi nhỏ.

### Bài tập

- Tự viết linear regression bằng NumPy.
- Train classifier trên dataset nhỏ, viết confusion matrix và report.
- Tạo RAG chatbot cho 10-20 file Markdown cá nhân.
- Viết 30 câu hỏi eval và chấm điểm câu trả lời bằng rubric.
- Tạo prompt variants và so sánh output theo 3 metric: đúng, rõ, ngắn.

### Tiêu chí ra Shu

- Bạn giải thích được pipeline ML/LLM bằng ngôn ngữ của mình.
- Bạn biết metric nào đang đo điều gì.
- Bạn có thể reproduce một experiment từ đầu.
- Bạn không trình bày demo AI mà không có eval tối thiểu.

## Ha: thiết kế experiment và trade-off

### Chủ đề

- Data quality, leakage, imbalance, drift.
- Error analysis và slice-based evaluation.
- Prompt eval, retrieval eval, answer eval.
- RAG design: chunking, metadata, reranking, citation.
- LLMOps: versioning, monitoring, fallback, cost control.
- Safety: hallucination, prompt injection, privacy, human-in-the-loop.
- Product UX: khi nào nên trả lời, khi nào nên hỏi lại, khi nào nên từ chối.

### Bài tập

- Làm error analysis cho 50 case sai và nhóm thành 3-5 pattern.
- So sánh 3 cách chunking cho cùng một corpus.
- Tạo eval harness chạy lại được và lưu kết quả theo version.
- Thêm citation và refusal behavior vào RAG.
- Benchmark latency/cost giữa 2 model hoặc 2 cấu hình retrieval.
- Thiết kế "AI feature spec" có risk, metric, rollback plan.

### Tiêu chí ra Ha

- Bạn có thể nói "model tốt hơn" dựa trên metric và eval set, không dựa trên cảm giác.
- Bạn biết khi nào thêm data tốt hơn đổi model.
- Bạn biết khi nào RAG không giải quyết được vấn đề.
- Bạn có thể giải thích hallucination risk và cách giảm thiểu.

## Ri: xây hệ sinh thái AI có trách nhiệm

### Chủ đề

- Domain-specific eval và feedback loop.
- Agent workflow có guardrails.
- Human review queue và escalation.
- Continuous improvement: data flywheel, monitoring, release gates.
- Model governance: privacy, audit, policy.
- Teaching: tạo internal AI playbook.

### Bài tập

- Xây AI assistant cho một domain hẹp có eval, monitoring, feedback UI.
- Tạo benchmark nội bộ cho tác vụ của team.
- Viết playbook "cách dùng AI trong engineering workflow".
- Thiết kế agent có tool permission rõ ràng và audit log.
- Tạo incident review cho một case hallucination/prompt injection giả lập.

### Tiêu chí Ri

- Ứng dụng AI của bạn có khả năng bị sai một cách được kiểm soát.
- Bạn có metric vận hành, không chỉ demo.
- Bạn giúp người khác dùng AI tốt hơn bằng template, eval, guardrail.
- Bạn biết nói "không nên dùng AI cho việc này" khi risk vượt lợi ích.

## Project capstone gợi ý

Xây "Research Copilot cho Markdown Vault":

- Index các file Markdown, tìm kiếm hybrid nếu có thể.
- Trả lời có citation đến file và đoạn liên quan.
- Eval set 50 câu hỏi: factual, synthesis, refusal, out-of-scope.
- Dashboard đơn giản: latency, cost, pass rate.
- Report: thiết kế retrieval, failure modes, next iteration.
