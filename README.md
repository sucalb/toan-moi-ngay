# Toán Mỗi Ngày

Bản demo web luyện toán mỗi ngày cho học sinh, có phần dành cho giáo viên.

**Xem trực tiếp:** https://sucalb.github.io/toan-moi-ngay/

## Tính năng

**Giáo viên**
- Tổng quan lớp: số học sinh đã nộp hôm nay, điểm trung bình, tỉ lệ sai 7 ngày, lỗi chưa sửa.
- Soạn và giao bài theo nhóm trình độ (Cơ bản, Khá, Nâng cao) và chuyên đề, lấy từ ngân hàng câu hỏi hoặc tự soạn câu mới.
- Xem bài làm của từng học sinh, gồm đáp án và cách làm.
- Phân tích lỗi sai: tỉ lệ sai theo chuyên đề, bản đồ năng lực học sinh × chuyên đề, câu sai nhiều nhất và nút giao lại.

**Học sinh**
- Làm bài hôm nay theo từng câu, có phản hồi và lời giải ngay.
- Chuỗi ngày làm bài liên tiếp.
- Sổ lỗi sai: làm lại các câu sai cho đến khi đúng.

## Ghi chú

- Toàn bộ là một file `index.html`, không cần build.
- Học sinh và bài làm là dữ liệu mẫu. Dữ liệu chỉ lưu trong trình duyệt (localStorage), chưa có server hay đăng nhập.
