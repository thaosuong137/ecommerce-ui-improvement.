# E-commerce UI Improvement
## 1. Giới thiệu

Dự án xây dựng giao diện giỏ hàng cải tiến cho website thời trang RUBIES bằng HTML5 và CSS3. Giao diện tập trung vào việc trình bày thông tin sản phẩm, các khoản chi phí và điều kiện áp dụng ưu đãi một cách rõ ràng, giúp khách hàng thuận tiện theo dõi đơn hàng trước khi thanh toán.

## 2. Website tham khảo

- Tên website: RUBIES
- URL: https://rubies.vn/
- Khu vực đã khảo sát: Trang chủ, danh mục sản phẩm, trang chi tiết sản phẩm, chức năng tìm kiếm và giỏ hàng.
- Khu vực lựa chọn cải tiến: Giao diện giỏ hàng 

## 3. Chức năng

- Hiển thị danh sách 4 sản phẩm mẫu với hình ảnh, tên và giá sản phẩm.
- Hiển thị thông tin kích thước, màu sắc và số lượng sản phẩm.
- Có các nút thao tác tăng/giảm số lượng và xóa sản phẩm.
- Hiển thị phần tóm tắt đơn hàng gồm tiền hàng, giảm giá, phí vận chuyển và tổng tạm tính.
- Có ô nhập mã ưu đãi, thông báo điều kiện giảm giá và nút thanh toán.
- Bố cục hỗ trợ màn hình máy tính và điện thoại.

Hiện tại Các nút thao tác chỉ được thiết kế về mặt giao diện, chưa có chức năng xử lý thực tế

## 4. Công nghệ

- HTML5: Xây dựng cấu trúc và nội dung trang web.
- CSS3: Thiết kế bố cục, màu sắc, khoảng cách và giao diện 

## 5. Cách chạy

1. Tải thư mục dự án về máy tính.
2. Mở thư mục `rubies-cart`.
3. Nhấp đúp vào file `index.html` để mở bằng trình duyệt.
4. Sử dụng Chrome DevTools để kiểm tra giao diện trên các kích thước màn hình khác nhau.

## 6. Cải tiến đã thực hiện

Vấn đề ban đầu Giao diện giỏ hàng RUBIES đã có thông tin sản phẩm, số lượng, đơn giá, thành tiền, tổng tiền và mã ưu đãi để sao chép. Tuy nhiên, các khoản giảm giá và phí vận chuyển chưa được phân tách rõ trong khu vực giỏ hàng, đồng thời chưa có ô nhập mã ưu đãi trực tiếp.

Phương án cải tiến:Thiết kế khu vực tóm tắt đơn hàng riêng biệt, bổ sung các dòng chi phí và ô nhập mã ưu đãi nhằm giúp khách hàng dễ theo dõi thông tin thanh toán.

Điều chỉnh cá nhân sau khi sử dụng AI hỗ trợ

- Chỉnh sửa nội dung thông báo mã giảm giá trong HTML để làm rõ điều kiện áp dụng ưu đãi.
- Thay đổi màu nền nút thanh toán thành màu hồng đất (`#B76E79`) và tăng độ bo góc bằng CSS nhằm tạo điểm nhấn trực quan.

## 7. Hỗ trợ từ AI

Gemini được sử dụng để hỗ trợ phân tích tổng thể website RUBIES, ChatGPT được sử dụng để hỗ trợ phân tích giao diện giỏ hàng, đề xuất bố cục, tạo mã nguồn ban đầu giải thích các thành phần HTML/CSS.

Sau khi nhận kết quả, em đã  đối chiếu các thông tin với website thực tế và chủ động điều chỉnh nội dung phù hợp và kiểm tra và chỉnh sửa giao diện đã tạo trên trình duyệt và VS Code.

Chi tiết quá trình sử dụng AI được trình bày trong file `AI_USAGE.md`.