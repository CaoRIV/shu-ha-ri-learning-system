# Nguyên Lý Shu-Ha-Ri

Shu-Ha-Ri bắt nguồn từ võ thuật Nhật Bản, nhưng rất hợp với việc học kỹ thuật: bạn bắt đầu bằng việc giữ đúng hình mẫu, sau đó hiểu để điều chỉnh, và cuối cùng nội hóa để sáng tạo. Trong software, AI và CS, đây là cách tránh hai cực đoan: học lan man không nền tảng, hoặc chỉ làm theo tutorial mãi mà không lớn.

## Shu: giữ khuôn để xây nền

Shu là giai đoạn "protect/obey": làm đúng theo mẫu, theo mentor, theo tài liệu, theo convention. Đây không phải là sự ngoan ngoãn mù quáng; đây là cách giảm nhiều biến số khi bạn chưa có trực giác.

Trong kỹ thuật, Shu có dạng:

- Gõ lại một implementation kinh điển: linked list, binary search, REST CRUD, training loop.
- Làm theo style guide của team.
- Viết test theo pattern có sẵn.
- Đọc docs và chạy ví dụ gốc trước khi sửa.
- Dùng framework đúng như tác giả framework kỳ vọng.

Mục tiêu của Shu:

- Xây từ vựng, thao tác, mental model cơ bản.
- Giảm lỗi do tự chế khi chưa đủ hiểu.
- Tạo "muscle memory" cho workflow lặp lại: terminal, Git, debug, test, đọc API.
- Biết chuẩn mực tối thiểu của một kết quả đúng.

Dấu hiệu bạn đang ở Shu:

- Bạn cần checklist để làm không quên bước.
- Bạn giải quyết được bài quen nhưng lúng túng khi đổi ngữ cảnh.
- Bạn chưa giải thích rõ tại sao pattern được thiết kế như vậy.
- Lỗi sai thường nằm ở setup, cú pháp, convention, edge case cơ bản.

## Ha: phá khuôn có lý do

Ha là giai đoạn "detach/break": bạn bắt đầu hỏi "tại sao", thử biến thể, so sánh trade-off và áp dụng theo ngữ cảnh. Nếu Shu là học cách làm đúng, Ha là học cách chọn cách làm.

Trong kỹ thuật, Ha có dạng:

- Thay đổi kiến trúc từ monolith nhỏ sang module rõ ràng vì có yêu cầu test/deploy.
- So sánh SQL index strategies bằng benchmark nhỏ.
- Đổi prompt, model, retrieval strategy và đo chất lượng bằng eval.
- Viết lại tutorial thành sản phẩm giải quyết vấn đề thật của mình.
- Tự chọn giữa simplicity, performance, cost, security, maintainability.

Mục tiêu của Ha:

- Hiểu nguyên lý nằm dưới pattern.
- Tập ra quyết định trong điều kiện không hoàn hảo.
- Học bằng phản hồi thực tế: test, benchmark, user feedback, production signal.
- Tạo gu kỹ thuật cá nhân nhưng vẫn có bằng chứng.

Dấu hiệu bạn đang ở Ha:

- Bạn có thể đưa ra 2-3 phương án và nói trade-off.
- Bạn biết khi nào một best practice không còn phù hợp.
- Bạn ghi lại giả thuyết, thực nghiệm, kết quả.
- Lỗi sai thường nằm ở việc đánh giá sai ngữ cảnh, chưa đủ data, hoặc quá tay trong abstraction.

## Ri: rời khuôn để sáng tạo

Ri là giai đoạn "leave/transcend": nguyên lý đã được nội hóa đến mức bạn hành động tự nhiên. Ri không có nghĩa là bỏ hết rule. Nó có nghĩa là bạn không bị rule trói tay nữa.

Trong kỹ thuật, Ri có dạng:

- Thiết kế một architecture mới nhưng đơn giản vì nhìn đúng bản chất domain.
- Tạo internal framework/tool giúp team học nhanh hơn.
- Viết bài giải thích làm người khác có thể vào Shu.
- Phát hiện một lớp lỗi hệ thống và tạo practice ngăn nó quay lại.
- Dẫn dắt người khác qua learning path, không chỉ đưa đáp án.

Mục tiêu của Ri:

- Sáng tạo có nền tảng, không phải mới là vì thích mới.
- Chuyển tri thức cá nhân thành tri thức chia sẻ được.
- Đóng góp vào cộng đồng, team, hoặc sản phẩm.
- Có khả năng quay lại Shu khi vào miền mới.

Dấu hiệu bạn đang chạm Ri:

- Bạn giải quyết vấn đề lạ bằng trực giác, sau đó vẫn có thể quay lại giải thích nguyên lý.
- Bạn biết cắt bớt ceremony mà không làm mất an toàn.
- Bạn tạo được pattern, template, benchmark, hoặc lesson cho người khác.
- Bạn nhìn thấy điểm giới hạn của cách mình từng tin.

## Không có giai đoạn nào là vĩnh viễn

Một người có thể ở Ri trong backend API nhưng ở Shu trong computer vision. Một AI engineer giỏi prompt/eval có thể ở Shu khi học operating systems. Shu-Ha-Ri là bản đồ theo từng năng lực, không phải nhãn dán lên con người.

Vì vậy, mỗi khi học một chủ đề mới, hãy tự hỏi:

- Với năng lực này, mình đang ở Shu, Ha hay Ri?
- Bằng chứng nào cho thấy điều đó?
- Bài tập tiếp theo nên là bắt chước, biến thể, hay sáng tạo?

## Ánh xạ với các khung học tập khác

| Khung | Shu | Ha | Ri |
| --- | --- | --- | --- |
| Dreyfus | Novice, advanced beginner | Competent, proficient | Expert, master |
| Bloom | Remember, understand, apply | Analyze, evaluate | Create |
| Deliberate practice | Bài tập rõ ràng, feedback nhanh | Tăng độ khó, sửa điểm yếu | Thiết kế bài tập mới, huấn luyện người khác |
| Agile | Làm đúng practice | Điều chỉnh theo principle | Tạo practice phù hợp ngữ cảnh |

## Nguyên tắc ra quyết định

- Nếu bạn không lặp lại được: quay về Shu.
- Nếu bạn lặp lại được nhưng không giải thích được: tiếp tục Shu, thêm Feynman note.
- Nếu bạn giải thích được nhưng chưa chọn được trade-off: vào Ha.
- Nếu bạn chọn được trade-off nhưng chưa tạo giá trị mới: ở Ha.
- Nếu bạn tạo được tri thức, tool, pattern, hoặc sản phẩm giúp người khác: chạm Ri.
