# [Thực hành 01] Phân tích hạn chế của mô hình Waterfall - Dự án MediBook

> 👤 **Học viên:** Đỗ Hoàng Sơn | **Mã SV:** PTIT-HCM-066
> 🏫 **Môn học:** IT206-K25-Agile-va-Scrum

---

## Nhiệm vụ 1: Bảng 5 giai đoạn Waterfall của dự án MediBook

Dưới đây là bảng chi tiết 5 giai đoạn tuần tự của dự án MediBook, thể hiện rõ tiến độ và thời điểm khách hàng tiếp cận được phần mềm chạy thực tế theo đặc thù cứng nhắc của mô hình Waterfall.

- Quy mô nhân sự: 8 thành viên (1 PM, 1 BA, 4 Dev, 2 Tester).
- Tổng ngân sách ban đầu: 1.800.000.000đ với đơn giá 25.000.000đ / người / tháng.

| Giai đoạn | Thời gian | Sản phẩm bàn giao | Khách hàng có nhìn thấy phần mềm chạy được không |
| --- | --- | --- | --- |
| Thu thập yêu cầu & SRS | 05/01 - 20/02 | Tài liệu SRS 120 trang | Không |
| Thiết kế UI/UX & Kiến trúc | 21/02 - 25/03 | Bản vẽ thiết kế & Sơ đồ kiến trúc | Không |
| Lập trình tính năng | 26/03 - 31/05 | Mã nguồn các tính năng | Không |
| Kiểm thử & Review | 01/06 - 25/06 | Bản chạy được đầu tiên (Test build) | Có |
| Triển khai & Go-live | 26/06 - 05/07 | Hệ thống vận hành thực tế | Có |

## Nhiệm vụ 2: Xác định khoảng mù thông tin

Theo mốc thời gian của dự án MediBook, ngày 01/06 là thời điểm khách hàng lần đầu tiên nhìn thấy bản phần mềm chạy được (bắt đầu giai đoạn kiểm thử).

Tính từ ngày khởi động dự án là 05/01 đến mốc 01/06, ta có tổng số ngày là 147 ngày. Đây chính là khoảng thời gian khách hàng hoàn toàn mù thông tin về sản phẩm thực tế, chỉ làm việc trên tài liệu giấy tờ tĩnh.

- Mốc khởi động: 05/01
- Mốc khách hàng thấy phần mềm: 01/06
- Kết quả khoang_mu_thong_tin: 147 ngày

## Nhiệm vụ 3: Phân tích chi phí phát sinh và ngân sách mới

Vào ngày 01/06, Bộ Y tế ban hành quy định mới khiến toàn bộ luồng lưu trữ hồ sơ bệnh án điện tử phải làm lại, ước tính kéo dài thêm 3 tháng cho toàn đội ngũ.

Dựa trên công thức nhân sự nhân chi phí nhân số tháng, ta tính được các chỉ số tài chính mới như sau:

- Chi phí phát sinh = 8 (người) * 25.000.000 (đ/người/tháng) * 3 (tháng) = 600.000.000đ.
- Tổng ngân sách mới = 1.800.000.000đ + 600.000.000đ = 2.400.000.000đ.
- Tỷ lệ vượt ngân sách = 600.000.000 / 1.800.000.000 = 33,3%.

## Nhiệm vụ 4: Phân tích 3 hạn chế cốt lõi của Waterfall trên MediBook

Mô hình Waterfall bộc lộ rõ 3 điểm yếu chí mạng khi đối diện với sự thay đổi thực tế từ phía cơ quan quản lý nhà nước vào ngày 01/06.

- 1. Tính cứng nhắc: Giai đoạn thiết kế và lập trình đã đóng băng từ tháng 03 đến cuối tháng 05, hệ thống không cho phép quay lại chỉnh sửa yêu cầu mà phải đợi đến khi xong toàn bộ mới phát hiện sai lệch.
- 2. Phản hồi muộn: Mãi đến ngày 01/06 (sau 147 ngày làm việc âm thầm từ 05/01), khách hàng mới nhận được bản chạy thử đầu tiên và lúc này các quy định mới buộc phải đập đi làm lại toàn bộ luồng dữ liệu.
- 3. Rủi ro cao và đội chi phí: Sự chậm trễ phản hồi và tính tuần tự bắt buộc team phải mất thêm 3 tháng, làm phát sinh thêm chính xác 600.000.000đ, đẩy tỷ lệ vượt ngân sách lên mức 33,3%.

---

## 📁 Danh sách tệp tin nộp bài trong Repository
- 📝 `btth1.docx`: Báo cáo tài liệu phân tích nghiệp vụ hoàn chỉnh.
