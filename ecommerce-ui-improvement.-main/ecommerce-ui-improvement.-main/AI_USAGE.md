 AI Usage Log

 ## 1. Công cụ AI

Tên công cụ: ChatGPT (OpenAI) và Google Gemini

## 2. Mục đích sử dụng

Sử dụng AI để hỗ trợ phân tích giao diện website RUBIES, đề xuất phương án cải tiến giỏ hàng, xác định các thành phần HTML/CSS cần sử dụng và tạo mã nguồn giao diện responsive.

Ngoài ra, AI còn hỗ trợ giải thích cách chỉnh sửa mã nguồn và hướng dẫn kiểm tra website trên trình duyệt.

## 3. Prompt đã sử dụng
Prompt 1 - Hỗ trợ phân tích webiste 
"Bạn là chuyên gia phân tích nghiệp vụ và thiết kế trải nghiệm người dùng cho website thương mại điện tử.
Tôi đang khảo sát website: RUBIES và và đây là link website https://rubies.vn/?srsltid=AU7gw4Xs4FFnmnYIkkaqeuySEN74sOEUecqmIcTa8mGUIXz41vDctidV.
Hãy giúp tôi lập bảng phân tích các khu vực:
1. Trang chủ.
2. Danh mục sản phẩm.
3. Chi tiết sản phẩm.
4. Tìm kiếm.
5. Giỏ hàng.
Với mỗi khu vực, hãy nêu:
- Mục đích của chức năng.
- Thành phần giao diện cần có.
- Điểm thuận tiện đối với khách hàng.
- Một vấn đề có thể phát sinh.
- Một đề xuất cải tiến.
Không khẳng định những tính năng chưa được kiểm chứng.
Phân biệt rõ nhận xét dựa trên quan sát và đề xuất của AI."

Prompt 2 – Đề xuất phương án thiết kế

"Tôi đang thực hiện bài tập phát triển giao diện website thương mại điện tử bằng HTML5 và CSS3. Tôi muốn cải tiến khu vực giao diện giỏ hàng trên website RUBIES. Hiện trạng Giỏ hàng hiện tại đã hiển thị thông tin, hình ảnh sản phẩm, số lượng, đơn giá, thành tiền và tổng tiền, có chức năng xóa sản phẩm hoặc tăng giảm số lượng sản phẩm, nút thanh toán và nút tiếp tục mua hàng, có khung hiện mã giảm giá để khách hàng copy code nhưng giao diện chưa phân tách rõ các khoản giảm giá, phí vận chuyển và chưa có ô nhập mã ưu đãi trực tiếp.

Đối tượng sử dụng: khách hàng mua sắm trực tuyến tại Việt Nam.

Hãy đề xuất:
1. Bố cục giao diện.
2. Các thành phần HTML cần sử dụng.
3. Cách tổ chức CSS.
4. Cách hiển thị trên máy tính và điện thoại.
5. Những điểm cần kiểm tra về khả năng sử dụng.

Trước tiên, hãy giải thích phương án thiết kế. Chưa tạo toàn bộ mã nguồn cho đến khi tôi yêu cầu."

Prompt 3 – Tạo mã nguồn HTML5/CSS3

"Dựa trên phương án đã thống nhất, hãy tạo một trang giao diện thương mại điện tử bằng HTML5 và CSS3.

Yêu cầu:
- Giao diện có tiêu đề và khu vực sản phẩm.
- Có tối thiểu 4 sản phẩm mẫu.
- Mỗi sản phẩm có hình ảnh, tên, giá và nút thao tác.
- Bố cục phù hợp với màn hình máy tính và điện thoại.
- Mã HTML có cấu trúc rõ ràng.
- CSS được tách thành file riêng.
- Không sử dụng backend hoặc cơ sở dữ liệu.
- Không đưa thư viện hoặc thành phần không cần thiết vào dự án.

Giải thích cách chạy trang web và những phần tôi cần kiểm tra.

## 4. Kết quả AI đề xuất

AI đề xuất bố cục hai khu vực gồm danh sách sản phẩm và phần tóm tắt đơn hàng. Khu vực tóm tắt hiển thị tiền hàng, giảm giá, phí vận chuyển, mã ưu đãi và tổng tạm tính.

AI hỗ trợ tạo file HTML5, CSS3 riêng biệt và hình ảnh minh họa cho 4 sản phẩm mẫu. Giao diện được thiết kế để phù hợp với máy tính và điện thoại.

## 5. Kiểm tra và điều chỉnh

Sau khi nhận mã nguồn từ AI, em đã mở trang web trên trình duyệt để kiểm tra bố cục, hình ảnh sản phẩm, nội dung hiển thị và các thành phần của giỏ hàng.

Em nhận thấy cần cải thiện thêm hai điểm:

- Thông báo mã giảm giá: Điều chỉnh nội dung trong thẻ HTML `<p>` để khách hàng dễ nhận biết điều kiện áp dụng ưu đãi.
- Nút thanh toán Thay đổi thuộc tính CSS `background` sang màu hồng đất (`#B76E79`) và điều chỉnh `border-radius` để nút có góc bo tròn hơn, tạo điểm nhấn cho thao tác thanh toán.

## 6. Phần tôi hiểu và có thể giải thích

- HTML5: Sử dụng để tổ chức cấu trúc và nội dung trang web.
- Thẻ `<section>` và `<article>`: Phân chia các khu vực nội dung và thông tin sản phẩm.
- Thẻ `<img>`:** Hiển thị hình ảnh sản phẩm.
- Thẻ `<p>`:** Hiển thị thông tin giá, mô tả và thông báo ưu đãi.
- Thẻ `<button>`: Thể hiện các thao tác của người dùng trên giao diện.
- CSS Grid và Flexbox: Sắp xếp bố cục và căn chỉnh các thành phần.
- Media Queries: Điều chỉnh giao diện theo kích thước màn hình.
- Thuộc tính `background`: Thiết lập màu nền 
- Thuộc tính `border-radius`: Điều chỉnh độ bo tròn góc nút.
- Thuộc tính `color`:Thiết lập màu chữ 
