# HÀNH TRÌNH CỦA TẾ BÀO – KHTN 6, BÀI 20

## 1. Thành phần sản phẩm

- `index.html`: học liệu số tương tác, chạy trực tiếp trên trình duyệt.
- `assets/cell_division.mp4`: video kính hiển vi time-lapse khoảng 2 phút.
- `assets/cell-video-poster.jpg`: ảnh xem trước trích từ khung hình đầu của video.

**Quan trọng:** Giữ nguyên cấu trúc thư mục. Không di chuyển riêng `index.html` ra khỏi thư mục sản phẩm.

## 2. Cách mở và kiểm tra trên máy tính

1. Tải tệp ZIP và chọn **Extract All / Giải nén tất cả**.
2. Mở thư mục `Hanh-trinh-te-bao-v2`.
3. Kiểm tra bên trong có `index.html` và thư mục `assets`.
4. Trong `assets` phải có đủ `cell_division.mp4` và `cell-video-poster.jpg`.
5. Mở `index.html` bằng Chrome hoặc Edge. Video có ảnh xem trước; nhấn một mốc quan sát để phát đoạn tương ứng.

Nếu trình duyệt không phát được video khi mở bằng đường dẫn `file://`, hãy mở thư mục bằng VS Code và dùng tiện ích Live Server. Video phải được đặt đúng trong `assets`.

## 3. Cách thay video

Thay tệp `assets/cell_division.mp4` bằng video MP4 khác và giữ nguyên tên tệp. Nếu thay bằng video có thời lượng hoặc nội dung khác, cần chỉnh các mốc thời gian trong mảng `chapters` ở cuối `index.html` và cập nhật ảnh xem trước `assets/cell-video-poster.jpg`.

## 4. Đăng website lên GitHub Pages

1. Tạo repository mới trên GitHub.
2. Tải lên `index.html` và toàn bộ thư mục `assets` (bao gồm MP4 và ảnh poster).
3. Mở **Settings → Pages**.
4. Ở **Build and deployment**, chọn **Deploy from a branch**.
5. Chọn nhánh `main`, thư mục `/ (root)`, sau đó nhấn **Save**.
6. Mở URL GitHub Pages được cung cấp sau khi xuất bản.

Tệp video hiện tại khoảng 3,2 MB, không quá lớn đối với repository dùng cho học liệu nhỏ.

## 5. Video và nguồn tư liệu

Toshiyuki Hatano & Greenfield Sluder (2011), CIL:35150, Cell Image Library. DOI: https://doi.org/10.7295/W9CIL35150. Nguồn ghi nhận video tế bào hTERT-RPE1 (biểu mô sắc tố võng mạc người) nuôi cấy, quan sát bằng kính hiển vi tương phản giao thoa vi sai (DIC). Trang nguồn ghi tư liệu ở phạm vi Public Domain và khuyến nghị ghi công tác giả/nguồn khi sử dụng.

## 6. Lưu ý khoa học – sư phạm

- Phần dự đoán được đặt trước phần quan sát; hệ thống không báo đúng/sai ở giai đoạn dự đoán.
- Khi chọn mốc ở mô hình “Phân chia đồng bộ”, video được đưa đến đoạn tương ứng, phát và tự dừng ở cuối đoạn. Trạng thái mô hình được cập nhật theo thời gian video.
- Mô hình là sơ đồ hóa, không phải bản sao tế bào thật và không thể hiện các giai đoạn nguyên phân ở mức độ phân tử/nhiễm sắc thể.
- Video thể hiện rõ sự biến đổi hình dạng và phân chia hơn toàn bộ giai đoạn tế bào con lớn lên. Vì vậy, “Khám phá sự lớn lên” là chế độ mô hình riêng; video được tạm dừng để tránh tạo cảm giác có hình ảnh thực tế tương ứng khi không có.
- Mô hình số lượng 1 → 2 → 4 → 8 giả định mỗi tế bào đều phân chia một lần trong mỗi chu kì và không có tế bào chết.
- Trắc nghiệm cuối hoạt động tự động chấm 5 câu. Câu trả lời tự luận được hỗ trợ bằng tiêu chí tự đối chiếu, không tự động chấm nội dung văn bản.
