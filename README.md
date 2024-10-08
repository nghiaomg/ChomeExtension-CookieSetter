# ChomeExtension-CookieSetter

## Mô tả
Cookie Setter là tiện ích mở rộng Chrome mạnh mẽ được thiết kế để đơn giản hóa quy trình thiết lập cookie cho nhà phát triển và người thử nghiệm web. Với giao diện thân thiện với người dùng, công cụ này cho phép bạn dễ dàng thiết lập cookie tùy chỉnh cho tab hiện tại, hợp lý hóa quy trình làm việc của bạn cho các tác vụ phát triển và thử nghiệm dựa trên cookie.

## Các tính năng chính

- Thiết lập Cookie khi đang di chuyển: Nhanh chóng thiết lập cookie tùy chỉnh cho tab hiện tại mà không cần thoát khỏi trình duyệt.
- Hiển thị URL hiện tại: Luôn biết trang web nào bạn đang sửa đổi với màn hình hiển thị rõ ràng URL của tab hiện tại.
- Giao diện thân thiện với người dùng: Nhập văn bản đơn giản để nhập chuỗi cookie giúp quy trình trở nên trực quan và nhanh chóng.
- Phản hồi ngay lập tức: Nhận xác nhận khi cookie được thiết lập thành công.
- Lịch sử cookie: Xem và quản lý cookie đã thiết lập trước đó cho các miền khác nhau.
- Ứng dụng một lần nhấp: Dễ dàng áp dụng cookie đã lưu vào các tab mới chỉ bằng một cú nhấp chuột.
- Xóa tất cả lịch sử: Xóa tất cả cookie đã lưu chỉ bằng một cú nhấp chuột.

## Tính năng mới

- **Hiển thị lịch sử cookie**: Xem danh sách các cookie đã thiết lập trước đó, được sắp xếp theo tên miền.
- **Hiển thị cookie rút gọn**: Các chuỗi cookie dài được cắt bớt để dễ đọc hơn, với đầy đủ thông tin chi tiết khi nhấp vào.
- **Áp dụng nhanh**: Nhấp vào cookie đã lưu để mở tab mới với tên miền đó và tự động áp dụng cookie đã lưu.
- **Chức năng xóa tất cả**: Dễ dàng xóa tất cả cookie đã lưu bằng nút "Xóa tất cả".
- **Nhiều cookie cho mỗi domain**: Mỗi domain giờ đây có thể lưu trữ nhiều cookie khác nhau.
- **Tải lại tự động**: Trang web sẽ tự động tải lại sau khi đặt hoặc áp dụng cookie mới.
- **Hiển thị cấu trúc cookie**: Các cookie được hiển thị theo cấu trúc phân cấp, với domain ở cấp cao nhất và các cookie cụ thể bên dưới.
- **Áp dụng cookie riêng lẻ**: Người dùng có thể nhấp vào từng cookie cụ thể để áp dụng nó cho domain tương ứng.

## Chi tiết kỹ thuật

- Được xây dựng với Manifest V3 cho tiện ích mở rộng Chrome
- Sử dụng tập lệnh, activeTab, cookie và quyền lưu trữ của Chrome
- Triển khai các biện pháp bảo mật nội dung tốt nhất
- Sử dụng bộ nhớ cục bộ của Chrome để lưu lịch sử cookie
- Cấu trúc lưu trữ cookie đã được cải tiến để hỗ trợ nhiều cookie cho mỗi domain
- Sử dụng chrome.tabs.reload() để tải lại trang sau khi đặt cookie

## Trường hợp sử dụng

- Kiểm tra phát triển web
- Mô phỏng phiên
- Kiểm tra cá nhân hóa trải nghiệm người dùng
- Gỡ lỗi các tính năng phụ thuộc vào cookie
- Chuyển đổi nhanh giữa các trạng thái cookie khác nhau cho một miền
- Kiểm tra nhiều trạng thái cookie khác nhau cho cùng một domain

## Cài đặt

1. Sao chép kho lưu trữ này
2. Mở Chrome và điều hướng đến chrome://extensions/
3. Bật "Chế độ nhà phát triển"
4. Nhấp vào "Tải đã giải nén"