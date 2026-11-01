# E-commerce UI Improvement
## Bài tập buổi 1
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


## Bài tập buổi 2
## 1. Giới thiệu bài tập

Bài tập tiếp tục phát triển giao diện website thời trang RUBIES từ Buổi 1, tập trung thực hành HTML5 và CSS3. Nội dung cải thiện chính là bổ sung trang danh sách sản phẩm, tổ chức bố cục và hoàn thiện các hiệu ứng tương tác cơ bản.

## 2. Website tham khảo và khu vực cải tiến

- **Website tham khảo:** RUBIES – https://rubies.vn/
- **Khu vực Buổi 1:** Trang giỏ hàng.
- **Khu vực cải tiến Buổi 2:** Trang danh sách sản phẩm.

Trang danh sách sản phẩm được bổ sung nhằm hiển thị thông tin sản phẩm và chuẩn bị giao diện cho các chức năng tìm kiếm, lọc, sắp xếp và thêm vào giỏ hàng ở Buổi 3.

## 3. Kỹ thuật HTML5 và CSS3 đã thực hành

- **HTML5:** Sử dụng `header`, `nav`, `main`, `section`, `article`, `footer` để tổ chức nội dung.
- **CSS Selector:** Sử dụng bộ chọn class để định dạng các thành phần giao diện.
- **Box Model:** Áp dụng `margin`, `padding`, `border` để kiểm soát khoảng cách và đường viền.
- **Flexbox:** Sắp xếp các thành phần trong thanh công cụ tìm kiếm, lọc và sắp xếp.
- **CSS Grid:** Xây dựng bố cục danh sách sản phẩm theo hàng và cột.
- **Responsive:** Điều chỉnh giao diện phù hợp với các kích thước màn hình.
- **Hover và Focus:** Bổ sung hiệu ứng đổ bóng, nâng nhẹ thẻ sản phẩm và đường viền focus cho các thành phần tương tác.

## 4. Hướng dẫn chạy website

1. Tải repository về máy.
2. Mở thư mục dự án bằng Visual Studio Code.
3. Mở `index.html` bằng Live Server hoặc Live Preview để xem trang danh sách sản phẩm.
4. Mở `cart.html` để xem trang giỏ hàng.

Website sử dụng HTML và CSS cơ bản, không yêu cầu cài đặt thư viện bổ sung.

## 5. Những thay đổi đã thực hiện

- Bổ sung trang danh sách gồm bốn sản phẩm mẫu.
- Tạo thanh tìm kiếm, bộ lọc danh mục và công cụ sắp xếp ở mức giao diện.
- Sử dụng CSS Grid để bố trí các thẻ sản phẩm.
- Bổ sung hiệu ứng Hover và Focus.
- Điều chỉnh hiệu ứng Hover bằng cách tăng độ đổ bóng và tạo chuyển động nâng nhẹ.
- Kiểm tra giao diện tại các kích thước 1366px, 768px và 390px.

**Kết quả kiểm thử:** Các tiêu chí về hiển thị HTML, áp dụng CSS, hình ảnh, liên kết, bố cục và hiệu ứng tương tác đều đạt yêu cầu qua kiểm tra trên trình duyệt.

## 6. Công cụ AI và cách kiểm tra kết quả

Em sử dụng ChatGPT để hỗ trợ phân tích mã nguồn HTML/CSS, đề xuất cấu trúc giao diện, giải thích các thuộc tính CSS và hướng dẫn kiểm thử.

Sau khi tham khảo các đề xuất, em kiểm tra giao diện trên trình duyệt và điều chỉnh hiệu ứng Hover để thẻ sản phẩm nổi bật hơn. Các prompt tiêu biểu được ghi lại trong tệp `AI_USAGE.md`.

## 7. Repository và website

- **GitHub repository:** https://github.com/thaosuong137/ecommerce-ui-improvement..git
- **Website GitHub Pages:** https://thaosuong137.github.io/ecommerce-ui-improvement./