# Toán Mỗi Ngày

Bản demo web luyện Toán lớp 10, 11, 12 mỗi ngày: học sinh tạo thói quen làm bài và sửa lỗi sai, giáo viên giao bài và theo dõi.

**Xem trực tiếp:** https://sucalb.github.io/toan-moi-ngay/

Tài khoản dùng thử (có nút vào nhanh ở màn đăng nhập):
- Giáo viên: `giaovien` / `123456`
- Học sinh lớp 11: `hs01` / `an2k8m`

## Tính năng

**Tài khoản**
- Mỗi học sinh một tài khoản riêng do giáo viên cấp.
- Giáo viên thêm từng em hoặc dán cả danh sách lớp, hệ thống tự tạo tên đăng nhập và mật khẩu. Có đổi mật khẩu, xoá, sao chép danh sách để gửi cho học sinh.

**Giáo viên**
- Chọn khối 10, 11 hoặc 12. Mặc định mở khối 11.
- Lớp học: tạo, đổi tên, xoá lớp; chuyển học sinh giữa các lớp ngay trong bảng.
- Chuyên đề dạng thư mục: giáo viên tự thêm, đổi tên, xoá; mỗi thư mục chứa câu hỏi và tài liệu (PDF, ảnh) cho học sinh tự học.
- Soạn và giao bài: tick các lớp và trình độ được nhận bài; chỉ học sinh thuộc lớp và trình độ đó mới thấy. Đính kèm được PDF, ảnh.
- Tạo đề nhanh: lấy ngẫu nhiên câu có sẵn trong ngân hàng theo chuyên đề, dạng câu, số câu.
- Soạn câu mới: tick một hoặc nhiều trình độ, gõ công thức toán (MathJax) có xem trước, chèn hình.
- Ba dạng câu theo đề tốt nghiệp THPT: trắc nghiệm 4 lựa chọn, đúng/sai 4 ý, trả lời ngắn.
- Tổng quan, xem bài làm từng học sinh, phân tích lỗi sai (lọc theo lớp và trình độ), bản đồ năng lực.

**Học sinh**
- Làm bài hôm nay theo từng câu, có phản hồi và lời giải ngay; mở tài liệu giáo viên gửi kèm.
- Chuyên đề tự học: xem các thư mục giáo viên tạo, đọc tài liệu PDF, ảnh, tự luyện 5 hoặc 10 câu theo độ khó tự chọn, không tính điểm.
- Chuỗi ngày làm bài liên tiếp, mức thành thạo theo chuyên đề.
- Sổ lỗi sai: gồm câu sai ở bài được giao và khi tự luyện; làm lại cho đến khi đúng.

## Ghi chú

- Toàn bộ là một file `index.html`, không cần build.
- Ngân hàng câu hỏi mẫu theo khối:
  - Lớp 10: mệnh đề và tập hợp, hàm số bậc hai, vectơ, hệ thức lượng.
  - Lớp 11: lượng giác, dãy số và cấp số, mũ và logarit, giới hạn.
  - Lớp 12: ứng dụng đạo hàm, nguyên hàm và tích phân, tọa độ Oxyz, xác suất có điều kiện.
- Đây là bản demo: học sinh, bài làm và tài khoản là dữ liệu mẫu, chỉ lưu trong trình duyệt (localStorage). Bản dùng thật cần máy chủ và cơ sở dữ liệu để lưu tài khoản (mật khẩu được mã hoá) và bài làm.
