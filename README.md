# Toán Mỗi Ngày

Bản demo web luyện Toán 12 mỗi ngày: học sinh tạo thói quen làm bài và sửa lỗi sai, giáo viên giao bài và theo dõi.

**Xem trực tiếp:** https://sucalb.github.io/toan-moi-ngay/

Tài khoản dùng thử (có nút vào nhanh ở màn đăng nhập):
- Giáo viên: `giaovien` / `123456`
- Học sinh: `hs01` / `an2k8m`

## Tính năng

**Tài khoản**
- Mỗi học sinh một tài khoản riêng do giáo viên cấp.
- Giáo viên thêm từng em hoặc dán cả danh sách lớp, hệ thống tự tạo tên đăng nhập và mật khẩu. Có đổi mật khẩu, xoá, sao chép danh sách để gửi cho học sinh.

**Giáo viên**
- Tổng quan lớp: số học sinh đã nộp hôm nay, điểm trung bình, tỉ lệ sai 7 ngày, lỗi chưa sửa, học sinh cần chú ý.
- Soạn và giao bài theo nhóm trình độ (Cơ bản, Khá, Giỏi) và chuyên đề, lấy từ ngân hàng câu hỏi hoặc tự soạn.
- Ba dạng câu theo đề tốt nghiệp THPT: trắc nghiệm 4 lựa chọn, đúng/sai 4 ý, trả lời ngắn.
- Gõ công thức toán (phân số, căn, mũ, tích phân, vectơ…) bằng thanh công cụ, có xem trước. Công thức hiển thị bằng MathJax.
- Chèn hình (đồ thị, hình vẽ, bảng biến thiên) vào câu hỏi, ảnh tự được nén.
- Xem bài làm của từng học sinh, gồm đáp án và cách làm.
- Phân tích lỗi sai: tỉ lệ sai theo chuyên đề, bản đồ năng lực học sinh × chuyên đề, câu sai nhiều nhất và nút giao lại.

**Học sinh**
- Làm bài hôm nay theo từng câu, có phản hồi và lời giải ngay.
- Chuỗi ngày làm bài liên tiếp, mức thành thạo theo chuyên đề.
- Sổ lỗi sai: làm lại các câu sai cho đến khi đúng.

## Ghi chú

- Toàn bộ là một file `index.html`, không cần build.
- Ngân hàng câu hỏi mẫu Toán 12: ứng dụng đạo hàm, nguyên hàm và tích phân, tọa độ Oxyz, xác suất có điều kiện.
- Đây là bản demo: học sinh, bài làm và tài khoản là dữ liệu mẫu, chỉ lưu trong trình duyệt (localStorage). Bản dùng thật cần máy chủ và cơ sở dữ liệu để lưu tài khoản (mật khẩu được mã hoá) và bài làm.
