# CreatorStudio – Quản lý dự án sáng tạo và phản hồi phiên bản

## 1. Tên đề tài

**CreatorStudio – Quản lý dự án sáng tạo và phản hồi phiên bản**

Đây là dự án website hỗ trợ khách hàng theo dõi tiến độ dự án sáng tạo, quản lý thông tin dự án và nắm bắt tình trạng các phiên bản thiết kế.

## 2. Tên trang đã thực hiện

**Trang Tổng quan dự án (Khách hàng)**

- Tên file HTML: `client-project-overview.html`
- File CSS: `assets/css/styles.css`
- File JavaScript:
  - `assets/js/data.js`
  - `assets/js/store.js`
  - `assets/js/ui.js`
  - `assets/js/pages/client-project-overview.js`

## 3. Mục đích của trang

Trang Tổng quan dự án được xây dựng nhằm giúp khách hàng quản lý và theo dõi các dự án sáng tạo trên cùng một giao diện.

Trang cung cấp thông tin tổng quan về số lượng dự án, trạng thái thực hiện, thời hạn hoàn thành, tình trạng brief, phiên bản thiết kế mới nhất và tiến độ công việc.

Qua đó, khách hàng có thể dễ dàng tìm kiếm, lọc, tạo mới, chỉnh sửa và quản lý các dự án mà không cần theo dõi thông tin qua nhiều cuộc trò chuyện hoặc nhiều tệp riêng biệt.

## 4. Các chức năng chính

- **Thống kê dự án:** Hiển thị tổng số dự án, số dự án đang thực hiện, số phiên bản đang chờ duyệt và số dự án đã lưu trữ.
- **Tạo dự án mới:** Nhập tên dự án, mô tả và hạn chót hoàn thành.
- **Chỉnh sửa dự án:** Cập nhật thông tin của dự án đã tạo.
- **Xóa dự án:** Xóa dự án sau khi xác nhận thao tác.
- **Lưu trữ và khôi phục:** Lưu trữ dự án không còn hoạt động và khôi phục khi cần thiết.
- **Tìm kiếm dự án:** Tìm dự án theo tên.
- **Lọc trạng thái:** Lọc dự án theo trạng thái đang chạy, tạm dừng, hoàn thành hoặc đã lưu trữ.
- **Theo dõi tiến độ:** Hiển thị phần trăm hoàn thành dựa trên số công việc đã hoàn thành.
- **Theo dõi thông tin liên quan:** Hiển thị hạn chót, trạng thái brief, phiên bản mới nhất và số góp ý đang mở.
- **Kiểm tra dữ liệu:** Kiểm tra các trường bắt buộc và độ dài dữ liệu trước khi lưu.
- **Thông báo và hộp thoại:** Hiển thị thông báo thao tác, hộp thoại tạo hoặc sửa dự án và xác nhận khi xóa.
- **Lưu trữ dữ liệu:** Sử dụng LocalStorage để giữ dữ liệu dự án trên trình duyệt sau khi tải lại trang.
- **Xử lý trạng thái giao diện:** Có trạng thái đang tải, chưa có dữ liệu, không tìm thấy kết quả và thông báo lỗi tải dữ liệu.

## 5. Công nghệ sử dụng

- **HTML5:** Xây dựng cấu trúc trang bằng các thẻ ngữ nghĩa như `header`, `main`, `nav`, `section` và `footer`, kết hợp biểu mẫu và các thành phần giao diện.
- **CSS3:** Thiết kế giao diện, màu sắc, khoảng cách, thẻ thông tin, nút bấm, hộp thoại và bố cục bằng Flexbox/Grid; hỗ trợ hiển thị trên các kích thước màn hình khác nhau.
- **JavaScript:** Xử lý sự kiện, tạo và cập nhật dự án, tìm kiếm, lọc trạng thái, kiểm tra dữ liệu đầu vào, cập nhật giao diện và xác nhận thao tác.
- **DOM:** Truy cập và thay đổi nội dung HTML theo dữ liệu và thao tác của người dùng.
- **LocalStorage:** Lưu dữ liệu dự án trên trình duyệt để sử dụng lại khi mở trang.
- **Promise và setTimeout:** Mô phỏng quá trình tải dữ liệu từ API, bao gồm trạng thái đang tải và xử lý lỗi.
- **Responsive Web Design:** Hướng đến giao diện dễ sử dụng trên máy tính, máy tính bảng và điện thoại.

## Cách chạy chương trình

1. Giải nén thư mục dự án.
2. Mở thư mục `creatorstudio-overview`.
3. Mở file `client-project-overview.html` bằng trình duyệt.
4. Nhấn **Tạo dự án** để thêm dự án mới và thử các chức năng tìm kiếm, lọc, chỉnh sửa, lưu trữ, khôi phục hoặc xóa.

**Lưu ý:** Phiên bản hiện tại tập trung vào màn hình Tổng quan dự án dành cho khách hàng. Dữ liệu được lưu bằng LocalStorage và API chỉ được mô phỏng, chưa kết nối cơ sở dữ liệu hoặc máy chủ thực tế.

## 6. Link Figma: https://www.figma.com/design/58F0JdpdZlPOztjrWXrmlC/Untitled?node-id=0-1&t=xunA0I9VObaLXjGD-1

## 7. Link video: https://youtu.be/3bpwP8YPHLk
