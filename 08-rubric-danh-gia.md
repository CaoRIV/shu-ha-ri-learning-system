# Rubric Đánh Giá

Dùng rubric này cuối mỗi tuần hoặc sau mỗi project. Nguyên tắc: chỉ nâng cấp giai đoạn khi có bằng chứng.

## Rubric 0-3

| Điểm | Giai đoạn | Mô tả ngắn |
| --- | --- | --- |
| 0 | Chưa vào Shu | Chưa làm được theo mẫu, thiếu từ vựng/công cụ |
| 1 | Shu | Làm theo mẫu được, kết quả có thể chạy/giải được |
| 2 | Ha | Hiểu nguyên lý, biến thể có lý do, biết trade-off |
| 3 | Ri | Tạo sản phẩm/pattern/hướng dẫn giúp người khác |

## 6 tiêu chí đánh giá

### 1. Correctness

- 0: Chưa chạy được hoặc sai lỗi cơ bản.
- 1: Chạy được với happy path.
- 2: Xử lý edge cases và có test/eval.
- 3: Có guardrail, monitoring, hoặc proof/invariant phù hợp.

### 2. Understanding

- 0: Không giải thích được.
- 1: Giải thích lại được theo docs/tutorial.
- 2: Giải thích được bằng ví dụ mới và trade-off.
- 3: Dạy lại được cho người khác, tạo framework/mental model riêng.

### 3. Independence

- 0: Cần hướng dẫn từng bước.
- 1: Làm được nếu có mẫu tương tự.
- 2: Tự chia nhỏ vấn đề và tìm nguồn cần thiết.
- 3: Tự định nghĩa vấn đề, constraint, phương án và tiêu chí thành công.

### 4. Feedback loop

- 0: Không có feedback ngoài cảm giác.
- 1: Có test/quiz/manual check đơn giản.
- 2: Có benchmark, eval set, review, hoặc user feedback.
- 3: Có vòng lặp cải tiến liên tục và history quyết định.

### 5. Transfer

- 0: Chỉ làm được đúng bài đã xem.
- 1: Làm được bài tương tự.
- 2: Áp dụng sang ngữ cảnh mới có điều chỉnh.
- 3: Tổng quát hóa thành pattern/tool/lesson.

### 6. Judgment

- 0: Chọn cách làm ngẫu nhiên.
- 1: Chọn theo tutorial/best practice.
- 2: Chọn theo trade-off rõ ràng.
- 3: Chọn cách đơn giản nhất đủ đáp ứng constraint và biết khi nào không nên làm.

## Điều kiện chuyển giai đoạn

### Từ 0 sang Shu

- Có nguồn học chính.
- Có setup chạy được.
- Có bài tập lặp lại.
- Có output đầu tiên.

### Từ Shu sang Ha

Cần ít nhất 4/6 tiêu chí đạt điểm 1 và 2 tiêu chí bắt đầu điểm 2.

Bằng chứng:

- 2-3 bài kata làm lại không cần tutorial.
- 1 project nhỏ có README và test/eval.
- 1 note giải thích "tại sao" sau pattern.

### Từ Ha sang Ri

Cần ít nhất 4/6 tiêu chí đạt điểm 2 và 1-2 tiêu chí đạt điểm 3.

Bằng chứng:

- 1 project có người khác dùng/review.
- 1 guide/template/tool giúp người khác học hoặc làm nhanh hơn.
- 1 case study nêu trade-off và kết quả.

## Mẫu review cuối tuần

| Câu hỏi | Trả lời |
| --- | --- |
| Năng lực chính tuần này là gì? | |
| Output nào chứng minh tôi đã luyện? | |
| Test/eval/feedback nào đã chạy? | |
| Lỗi lặp lại lớn nhất là gì? | |
| Nguyên lý mới tôi hiểu là gì? | |
| Tôi đang ở giai đoạn nào cho năng lực này? | |
| Tuần sau nên Shu, Ha hay Ri? | |

## Cảnh báo tự đánh giá sai

- Đọc thấy hiểu không phải là hiểu.
- Demo chạy một lần không phải là sản phẩm.
- Prompt cho output hay không phải là AI system tốt.
- Dùng framework mới không phải là tiến bộ.
- Giải được bài khó nhưng không giải thích được bài dễ có thể là học lệch.
