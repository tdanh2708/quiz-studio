# Quiz Studio

Quiz Studio là web luyện câu hỏi trắc nghiệm chạy trực tiếp trên trình duyệt, dùng được trên máy tính và điện thoại.

## Chức năng

- Import bộ câu hỏi từ file DOCX.
- Giữ nguyên nội dung câu hỏi và đáp án khi import; không tự sửa chính tả hoặc tự thêm/bớt chữ.
- Tự nhận diện câu hỏi, các lựa chọn A–D và đáp án đúng.
- Quản lý nhiều bộ đề trên cùng thiết bị.
- Chọn làm tất cả câu hoặc một số lượng câu nhất định.
- Trộn thứ tự câu hỏi và vị trí đáp án.
- Hiển thị đúng/sai ngay khi làm bài.
- Quay lại câu trước và lưu tiến độ đang làm.
- Lưu các câu trả lời sai để ôn lại.
- Kiểm tra các câu có cấu trúc hoặc đáp án chưa chắc chắn và cho phép sửa/xác nhận trực tiếp.
- Đổi tên và xóa bộ đề.
- Giao diện sáng/tối.
- Giao diện responsive, tối ưu cho iPhone và máy tính.
- Dữ liệu được lưu cục bộ trên thiết bị.

## Sử dụng

Mở Quiz Studio, chọn **Chọn file DOCX**, đợi hệ thống phân tích và chọn bộ đề vừa nhập. Sau đó chọn số câu, thứ tự câu hỏi và nhấn **Bắt đầu ôn**.

Nếu mục **Cần kiểm tra** lớn hơn 0, bấm vào con số đó để xem các câu cần rà soát, sửa đáp án hoặc xác nhận câu hợp lệ.

## Triển khai

Dự án là web tĩnh và có thể chạy bằng GitHub Pages. Các file chính nằm ở root repository.

## Phiên bản

Quiz Studio v1.1


## Dữ liệu bộ đề

Quiz Studio khởi động với thư viện trống trên thiết bị mới. Không có bộ câu hỏi mẫu được nhúng sẵn; người dùng tự nhập file DOCX để tạo bộ đề.
