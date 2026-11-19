Implementation Plan
Kế Hoạch Triển Khai Toàn Diện (Full Implementation Plan)
Chuẩn Hóa Hệ Thống Tài Khoản & Bản Đồ Dòng Chảy Kế Toán (Thông Tư 99/2025/TT-BTC)

1. Tổng Quan Mục Tiêu Dự Án

Dự án nhằm mục đích thiết lập hệ thống tài liệu và công cụ trực quan hóa hoàn chỉnh cho công tác kế toán doanh nghiệp sản xuất theo Thông tư 99/2025/TT-BTC (thay thế Thông tư 200/2014/TT-BTC, có hiệu lực từ 01/01/2026), gắn liền với các Chuẩn mực Kế toán Việt Nam (VAS).

Dự án gồm 3 hạng mục bàn giao chính:

Tệp Markdown 1 (Cập nhật): Hệ Thống Tài Khoản Kế Toán – Thông Tư 99 2025 TT-BTC.md — Bổ sung cột/mục cơ chế ghi nhận (Bản chất Nợ/Có, số dư, nghiệp vụ đối ứng chủ yếu) cho toàn bộ 71 tài khoản cấp 1 và hệ thống tài khoản cấp 2, cấp 3 quan trọng.
Tệp Markdown 2 (Tạo mới): Workflow_Ke_Toan_Chi_Tiet_Va_Co_So_Ghi_Nhan.md — Cẩm nang chuyên sâu giải thích dòng chảy kế toán theo chu trình sản xuất kinh doanh, làm rõ "Tại sao ghi nhận như vậy?" dựa trên các nguyên tắc kế toán cốt lõi (Cơ sở dồn tích, Phù hợp, Thận trọng, Giá gốc, v.v.) và căn cứ VAS/Thông tư 99.
Ứng Dụng Web Trực Quan (Tạo mới): mindmap_flowchart.html (chạy offline độc lập với HTML5/CSS3/JavaScript thuần, hỗ trợ vis-network hoặc SVG canvas) kết hợp Sơ đồ tư duy cây tương tác (Interactive Mindmap) ở phía trên và Bảng tra cứu Workflow chi tiết từng bút toán kèm giải thích ở phía dưới. 2. Chi Tiết Các Giai Đoạn Thực Hiện
Giai Đoạn 1: Chuẩn Hóa Cơ Chế Tài Khoản Theo Thông Tư 99/2025/TT-BTC

Thời gian dự kiến: Bước chuẩn bị logic

Rà soát danh mục 71 tài khoản cấp 1 từ Loại 1 đến Loại 9.
Xác định rõ nguyên tắc biến động:
Tài sản (Loại 1, 2): Tăng bên Nợ, Giảm bên Có, Số dư bên Nợ (Trừ TK lưỡng dụng 131, 138 và TK điều chỉnh giảm tài sản 214, 229 có số dư bên Có).
Nợ phải trả & Vốn CSH (Loại 3, 4): Tăng bên Có, Giảm bên Nợ, Số dư bên Có (Trừ TK lưỡng dụng 331, 338 và TK điều chỉnh giảm VCSH 419 mang số dư Nợ).
Doanh thu, Thu nhập (Loại 5, 7): Tăng bên Có, Giảm/Kết chuyển bên Nợ, Không có số dư cuối kỳ.
Chi phí (Loại 6, 8): Phát sinh tăng bên Nợ, Giảm/Kết chuyển bên Có, Không có số dư cuối kỳ.
Xác định kết quả kinh doanh (Loại 9 - 911): Tập hợp chi phí bên Nợ, doanh thu bên Có, kết chuyển sang 421, không có số dư.
Làm nổi bật các điểm mới của TT 99:
TK 112 (Tiền gửi không kỳ hạn), TK 128 (Đầu tư nắm giữ đến ngày đáo hạn)
TK 1383 (Thuế TTĐB hàng nhập khẩu)
TK 155 (Sản phẩm - gom gọn, đổi tên), TK 158 (Nguyên liệu, vật tư kho bảo thuế)
TK 215 & TK 2295 (Tài sản sinh học và dự phòng tổn thất tài sản sinh học)
TK 2414 (Nâng cấp, cải tạo TSCĐ tách riêng)
TK 242 (Đổi tên thành Chi phí chờ phân bổ)
TK 332 (Phải trả cổ tức, lợi nhuận - tách riêng)
TK 419 (Cổ phiếu mua lại của chính mình)
TK 82112 (Chi phí thuế TNDN bổ sung theo thuế tối thiểu toàn cầu)
Loại bỏ hoàn toàn TK 611, 631, 417, 441, 461, 466.
Giai Đoạn 2: Nâng Cấp File Markdown 1

Mục tiêu: Cập nhật nội dung Hệ Thống Tài Khoản Kế Toán – Thông Tư 99 2025 TT-BTC.md

Định dạng: Cải tiến các bảng danh mục thành cấu trúc chuẩn: | TK Cấp 1 | TK Cấp 2/3 | Tên Tài Khoản | Bản Chất & Số Dư | Cơ Chế Ghi Nhận Bên Nợ | Cơ Chế Ghi Nhận Bên Có | Bút Toán Đối Ứng Điển Hình |
Đảm bảo diễn giải ngắn gọn, chuẩn xác thuật ngữ kế toán nhưng cực kỳ trực quan, dễ ứng dụng khi tra cứu nhanh.
Giai Đoạn 3: Xây Dựng File Markdown 2 (Workflow_Ke_Toan_Chi_Tiet_Va_Co_So_Ghi_Nhan.md)

Mục tiêu: Thiết lập tài liệu chuyên khảo giải thích bản chất kinh tế và cơ sở lý luận theo từng chu trình:

Chu Trình 1: Mua Sắm Yếu Tố Đầu Vào & Công Nợ Phải Trả (P2P - Procure to Pay)
Cơ sở ghi nhận: Nguyên tắc Giá gốc (Historical Cost) & Cơ sở dồn tích (Accrual Basis).
Tại sao thuế GTGT đầu vào ghi nhận vào TK 133 mà không cộng vào giá trị hàng mua? (VAS 02 & Luật Thuế GTGT).
Chi phí trả trước/chờ phân bổ (TK 242): Tại sao không hạch toán ngay vào chi phí trong kỳ? (Nguyên tắc Phù hợp - Matching Principle).
Chu Trình 2: Sản Xuất & Tính Giá Thành Sản Phẩm (Cost Accounting & Manufacturing)
Dòng chuyển dịch chi phí: TK 621, 622, 627
→
→ TK 154
→
→ TK 155.
Tại sao chi phí trên định mức bình thường không được tính vào giá thành mà phải đưa thẳng vào GVHB (TK 632)? (Cơ sở chuẩn mực VAS 02).
Phương pháp kết chuyển và cơ chế tài khoản dở dang.
Chu Trình 3: Quản Lý Tài Sản Cố Định, Tài Sản Sinh Học & Dự Phòng
Tiêu chuẩn ghi nhận TSCĐ hữu hình (VAS 03), trích khấu hao (TK 214) và cơ sở hao mòn kinh tế.
Cơ chế tài sản sinh học (TK 215) mới theo Thông tư 99: Súc vật nuôi, cây trồng mùa vụ, đánh giá giá trị thuần có thể thực hiện được hoặc giá trị hợp lý.
Nguyên tắc Thận trọng (Prudence) trong việc lập dự phòng (TK 229: 2291, 2292, 2293, 2294, 2295).
Chu Trình 4: Bán Hàng, Giao Nhận & Doanh Thu - Thu Tiền (O2C - Order to Cash)
5 điều kiện ghi nhận doanh thu theo VAS 14 và thời điểm chuyển giao phần lớn rủi ro, lợi ích gắn liền với quyền sở hữu.
Tại sao phải ghi nhận đồng thời Doanh thu (511) và Giá vốn (632)? (Nguyên tắc Phù hợp - Matching Principle).
Xử lý chiết khấu thương mại, giảm giá, hàng bán bị trả lại (TK 521).
Chu Trình 5: Tiền Lương & Các Khoản Trích Theo Lương
Chi phí nhân công trực tiếp (622), nhân viên phân xưởng (6271), bán hàng (6411), quản lý (6421)
↔
↔ TK 334.
Trách nhiệm của người lao động vs. Doanh nghiệp (BHXH, BHYT, BHTN, KPCĐ qua TK 338).
Chu Trình 6: Cuối Kỳ - Khóa Sổ, Kết Chuyển, Thuế & Xác Định Kết Quả Kinh Doanh (Record to Report)
Bản chất trung gian của TK 911 (Không có số dư, chỉ phục vụ đối chiếu và kết chuyển lãi/lỗ sang 421).
Cơ sở tính thuế TNDN hiện hành và thuế TNDN hoãn lại (VAS 17 & TK 821, 243, 347).
Điểm mới thuế tối thiểu toàn cầu (Pillar 2 - TK 82112).
Giai Đoạn 4: Phát Triển Web Trực Quan HTML/CSS/JS (mindmap_flowchart.html)

Mục tiêu: Công cụ hỗ trợ người dùng tương tác trực tiếp trên trình duyệt, không cần cài đặt thêm server hay build tool phức tạp.

Công nghệ: HTML5, CSS3 hiện đại (Giao diện Dark/Light Mode, font Inter/Roboto thanh lịch), JavaScript thuần nhúng thư viện đồ thị trực quan mạnh mẽ (vis-network qua CDN hoặc SVG dynamic rendering) đảm bảo mượt mà.
Tính năng nổi bật:
Interactive Mindmap Tree (Sơ đồ tư duy dạng cây phía trên):
Nút gốc: Doanh Nghiệp Sản Xuất (TT 99/2025/TT-BTC).
Phân nhánh 9 loại tài khoản và các luồng quy trình kinh doanh (Mua hàng, Sản xuất, Bán hàng, Tiền tệ, Kết quả kinh doanh).
Hỗ trợ Zoom, Pan, Click vào từng nút để mở rộng / thu gọn chi tiết và xem giải thích tóm tắt ngay lập tức.
Bảng Tra Cứu Workflow Tương Tác (Phía dưới):
Thanh tìm kiếm tức thì theo mã TK (ví dụ: 154, 621, 331) hoặc từ khóa (ví dụ: xuất kho, giá vốn, khấu hao).
Bộ lọc theo Chu trình kinh doanh (P2P, Manufacturing, O2C, Payroll, Period End).
Cột thể hiện: Bước thực hiện, Bút toán Nợ/Có, Chứng từ gốc căn cứ, Bản chất kế toán & Chuẩn mực VAS/TT 99 tham chiếu.
Hiển Thị Responsive: Thân thiện trên cả máy tính để bàn, tablet và màn hình lớn. 3. Kế Hoạch Bàn Giao & Thứ Tự Thực Thi
STT Nhiệm Vụ Kết Quả Đầu Ra
1 Cập nhật File MD 1 C:\Users\Acer\Desktop\VAS\Hệ Thống Tài Khoản Kế Toán – Thông Tư 99 2025 TT-BTC.md
2 Viết mới File MD 2 C:\Users\Acer\Desktop\VAS\Workflow_Ke_Toan_Chi_Tiet_Va_Co_So_Ghi_Nhan.md
3 Xây dựng Web App Trực quan C:\Users\Acer\Desktop\VAS\mindmap_flowchart.html
4 Kiểm thử & Hướng dẫn sử dụng Mở trực tiếp trên trình duyệt máy tính và kiểm tra toàn bộ luồng dữ liệu

Vui lòng nhấn Proceed hoặc gửi phản hồi nếu bạn muốn bổ sung bất kỳ điểm nhấn nghiệp vụ nào trước khi tôi tiến hành cập nhật mã nguồn và các tệp ti

# Hệ Thống Tài Khoản Kế Toán – Thông Tư 99/2025/TT-BTC

## Dành cho Doanh Nghiệp Sản Xuất · Hiệu lực từ 01/01/2026

> **Căn cứ pháp lý:** Thông tư 99/2025/TT-BTC do Bộ Tài chính ban hành, thay thế Thông tư 200/2014/TT-BTC. Hệ thống tài khoản được quy định tại **Phụ lục II** ban hành kèm theo Thông tư, áp dụng bắt buộc cho năm tài chính bắt đầu từ hoặc sau ngày **01/01/2026** (Điều 11, Thông tư 99/2025/TT-BTC).

---

## Tổng Quan Cấu Trúc Hệ Thống

| Cấp tài khoản   | Số lượng          |
| --------------- | ----------------- |
| Tài khoản cấp 1 | **71** tài khoản  |
| Tài khoản cấp 2 | **101** tài khoản |
| Tài khoản cấp 3 | **10** tài khoản  |
| Tài khoản cấp 4 | **2** tài khoản   |

So với Thông tư 200/2014/TT-BTC, hệ thống mới **giảm 5 tài khoản cấp 1** (từ 76 xuống còn 71).

---

## Phần 1 · Danh Mục Toàn Bộ Tài Khoản Kế Toán

### I. Loại Tài Khoản Tài Sản

_(Nhóm 1xx – phản ánh toàn bộ tài sản doanh nghiệp đang kiểm soát)_

#### 1.1 Tiền & Tương Đương Tiền

| STT | TK Cấp 1 | TK Cấp 2 | Tên Tài Khoản                                             |
| --- | -------- | -------- | --------------------------------------------------------- |
| 01  | **111**  |          | Tiền mặt                                                  |
| 02  | **112**  |          | Tiền gửi không kỳ hạn _(đổi tên từ "Tiền gửi Ngân hàng")_ |
| 03  | **113**  |          | Tiền đang chuyển                                          |

#### 1.2 Đầu Tư Tài Chính Ngắn Hạn

| STT | TK Cấp 1 | TK Cấp 2 | Tên Tài Khoản                                  |
| --- | -------- | -------- | ---------------------------------------------- |
| 04  | **121**  |          | Chứng khoán kinh doanh                         |
| 05  | **128**  |          | Đầu tư nắm giữ đến ngày đáo hạn                |
|     |          | 1281     | Tiền gửi có kỳ hạn                             |
|     |          | 1282     | Trái phiếu                                     |
|     |          | 1283     | Cho vay                                        |
|     |          | 1288     | Các khoản đầu tư khác nắm giữ đến ngày đáo hạn |

#### 1.3 Các Khoản Phải Thu

| STT | TK Cấp 1 | TK Cấp 2 | Tên Tài Khoản                                               |
| --- | -------- | -------- | ----------------------------------------------------------- |
| 06  | **131**  |          | Phải thu của khách hàng                                     |
| 07  | **133**  |          | Thuế GTGT được khấu trừ                                     |
|     |          | 1331     | Thuế GTGT được khấu trừ của hàng hóa, dịch vụ               |
|     |          | 1332     | Thuế GTGT được khấu trừ của TSCĐ                            |
| 08  | **136**  |          | Phải thu nội bộ                                             |
|     |          | 1361     | Vốn kinh doanh ở đơn vị trực thuộc                          |
|     |          | 1362     | Phải thu nội bộ về chênh lệch tỷ giá                        |
|     |          | 1363     | Phải thu nội bộ về chi phí đi vay đủ điều kiện được vốn hoá |
|     |          | 1368     | Phải thu nội bộ khác                                        |
| 09  | **138**  |          | Phải thu khác                                               |
|     |          | 1381     | Tài sản thiếu chờ xử lý                                     |
|     |          | 1383     | Thuế TTĐB của hàng nhập khẩu _(mới trong TT99)_             |
|     |          | 1388     | Phải thu khác                                               |
| 10  | **141**  |          | Tạm ứng                                                     |

#### 1.4 Hàng Tồn Kho _(quan trọng với doanh nghiệp sản xuất)_

| STT | TK Cấp 1 | TK Cấp 2 | Tên Tài Khoản                                                               |
| --- | -------- | -------- | --------------------------------------------------------------------------- |
| 11  | **151**  |          | Hàng mua đang đi đường                                                      |
| 12  | **152**  |          | Nguyên liệu, vật liệu                                                       |
| 13  | **153**  |          | Công cụ, dụng cụ                                                            |
| 14  | **154**  |          | Chi phí sản xuất, kinh doanh dở dang                                        |
| 15  | **155**  |          | Sản phẩm _(đổi tên từ "Thành phẩm")_                                        |
| 16  | **156**  |          | Hàng hóa                                                                    |
| 17  | **157**  |          | Hàng gửi đi bán                                                             |
| 18  | **158**  |          | Nguyên liệu, vật tư tại kho bảo thuế _(đổi tên từ "Hàng hoá kho bảo thuế")_ |
| 19  | **171**  |          | Giao dịch mua, bán lại trái phiếu chính phủ                                 |

#### 1.5 Tài Sản Cố Định

| STT | TK Cấp 1 | TK Cấp 2 | TK Cấp 3   | Tên Tài Khoản                                             |
| --- | -------- | -------- | ---------- | --------------------------------------------------------- |
| 20  | **211**  |          |            | Tài sản cố định hữu hình                                  |
| 21  | **212**  |          |            | Tài sản cố định thuê tài chính                            |
| 22  | **213**  |          |            | Tài sản cố định vô hình                                   |
| 23  | **214**  |          |            | Hao mòn tài sản cố định                                   |
|     |          | 2141     |            | Hao mòn TSCĐ hữu hình                                     |
|     |          | 2142     |            | Hao mòn TSCĐ thuê tài chính                               |
|     |          | 2143     |            | Hao mòn TSCĐ vô hình                                      |
|     |          | 2147     |            | Hao mòn bất động sản đầu tư                               |
| 24  | **215**  |          |            | **Tài sản sinh học** _(bổ sung hoàn toàn mới trong TT99)_ |
|     |          | 2151     |            | Súc vật nuôi cho sản phẩm định kỳ                         |
|     |          |          | 21511      | Súc vật chưa đạt giai đoạn trưởng thành                   |
|     |          |          | 21512      | Súc vật đạt giai đoạn trưởng thành                        |
|     |          |          | _(215121)_ | _(Nguyên giá – cấp 4)_                                    |
|     |          |          | _(215122)_ | _(Giá trị khấu hao lũy kế – cấp 4)_                       |
|     |          | 2152     |            | Súc vật nuôi lấy sản phẩm một lần                         |
|     |          | 2153     |            | Cây trồng theo mùa vụ hoặc lấy sản phẩm một lần           |

#### 1.6 Bất Động Sản & Đầu Tư Dài Hạn

| STT | TK Cấp 1 | TK Cấp 2 | Tên Tài Khoản                              |
| --- | -------- | -------- | ------------------------------------------ |
| 25  | **217**  |          | Bất động sản đầu tư                        |
| 26  | **221**  |          | Đầu tư vào công ty con                     |
| 27  | **222**  |          | Đầu tư vào công ty liên doanh, liên kết    |
| 28  | **228**  |          | Đầu tư khác                                |
|     |          | 2281     | Đầu tư góp vốn vào đơn vị khác             |
|     |          | 2288     | Đầu tư khác                                |
| 29  | **229**  |          | Dự phòng tổn thất tài sản                  |
|     |          | 2291     | Dự phòng giảm giá chứng khoán kinh doanh   |
|     |          | 2292     | Dự phòng tổn thất đầu tư vào đơn vị khác   |
|     |          | 2293     | Dự phòng phải thu khó đòi                  |
|     |          | 2294     | Dự phòng giảm giá hàng tồn kho             |
|     |          | 2295     | Dự phòng tổn thất tài sản sinh học _(mới)_ |

#### 1.7 Tài Sản Dở Dang & Khác

| STT | TK Cấp 1 | TK Cấp 2 | Tên Tài Khoản                                                      |
| --- | -------- | -------- | ------------------------------------------------------------------ |
| 30  | **241**  |          | Xây dựng cơ bản dở dang                                            |
|     |          | 2411     | Mua sắm TSCĐ                                                       |
|     |          | 2412     | Xây dựng cơ bản                                                    |
|     |          | 2413     | Sửa chữa, bảo dưỡng định kỳ TSCĐ                                   |
|     |          | 2414     | Nâng cấp, cải tạo TSCĐ _(mới trong TT99)_                          |
| 31  | **242**  |          | Chi phí chờ phân bổ _(đổi tên từ "Chi phí trả trước")_             |
| 32  | **243**  |          | Tài sản thuế thu nhập hoãn lại                                     |
| 33  | **244**  |          | Ký quỹ, ký cược _(đổi tên từ "Cầm cố, thế chấp, ký quỹ, ký cược")_ |

---

### II. Loại Tài Khoản Nợ Phải Trả

_(Nhóm 3xx – phản ánh nghĩa vụ tài chính của doanh nghiệp)_

#### 2.1 Nợ Ngắn Hạn – Phải Trả Thương Mại

| STT | TK Cấp 1 | TK Cấp 2 | TK Cấp 3 | Tên Tài Khoản                                                       |
| --- | -------- | -------- | -------- | ------------------------------------------------------------------- |
| 34  | **331**  |          |          | Phải trả cho người bán                                              |
| 35  | **332**  |          |          | **Phải trả cổ tức, lợi nhuận** _(bổ sung mới hoàn toàn trong TT99)_ |
| 36  | **333**  |          |          | Thuế và các khoản phải nộp Nhà nước                                 |
|     |          | 3331     |          | Thuế GTGT phải nộp                                                  |
|     |          |          | 33311    | Thuế GTGT đầu ra                                                    |
|     |          |          | 33312    | Thuế GTGT hàng nhập khẩu                                            |
|     |          | 3332     |          | Thuế tiêu thụ đặc biệt                                              |
|     |          | 3333     |          | Thuế xuất, nhập khẩu                                                |
|     |          | 3334     |          | Thuế thu nhập doanh nghiệp                                          |
|     |          | 3335     |          | Thuế thu nhập cá nhân                                               |
|     |          | 3336     |          | Thuế tài nguyên                                                     |
|     |          | 3337     |          | Thuế nhà đất, tiền thuê đất                                         |
|     |          | 3338     |          | Thuế bảo vệ môi trường và các loại thuế khác                        |
|     |          |          | 33381    | Thuế bảo vệ môi trường                                              |
|     |          |          | 33382    | Các loại thuế khác                                                  |
|     |          | 3339     |          | Phí, lệ phí và các khoản phải nộp khác                              |
| 37  | **334**  |          |          | Phải trả người lao động                                             |
| 38  | **335**  |          |          | Chi phí phải trả                                                    |
| 39  | **336**  |          |          | Phải trả nội bộ                                                     |
|     |          | 3361     |          | Phải trả nội bộ về vốn kinh doanh                                   |
|     |          | 3362     |          | Phải trả nội bộ về chênh lệch tỷ giá                                |
|     |          | 3363     |          | Phải trả nội bộ về chi phí đi vay đủ điều kiện được vốn hoá         |
|     |          | 3368     |          | Phải trả nội bộ khác                                                |
| 40  | **337**  |          |          | Thanh toán theo tiến độ hợp đồng xây dựng                           |
| 41  | **338**  |          |          | Phải trả, phải nộp khác                                             |
|     |          | 3381     |          | Tài sản thừa chờ giải quyết                                         |
|     |          | 3382     |          | Kinh phí công đoàn                                                  |
|     |          | 3383     |          | Bảo hiểm xã hội                                                     |
|     |          | 3384     |          | Bảo hiểm y tế                                                       |
|     |          | 3386     |          | Bảo hiểm thất nghiệp                                                |
|     |          | 3387     |          | Doanh thu chờ phân bổ _(đổi tên trong TT99)_                        |
|     |          | 3388     |          | Phải trả, phải nộp khác                                             |

#### 2.2 Nợ Dài Hạn

| STT | TK Cấp 1 | TK Cấp 2 | Tên Tài Khoản                   |
| --- | -------- | -------- | ------------------------------- |
| 42  | **341**  |          | Vay và nợ thuê tài chính        |
|     |          | 3411     | Các khoản đi vay                |
|     |          | 3412     | Nợ thuê tài chính               |
| 43  | **343**  |          | Trái phiếu phát hành            |
|     |          | 3431     | Trái phiếu thường               |
|     |          | 3432     | Trái phiếu chuyển đổi           |
| 44  | **344**  |          | Nhận ký quỹ, ký cược            |
| 45  | **347**  |          | Thuế thu nhập hoãn lại phải trả |

#### 2.3 Dự Phòng & Quỹ

| STT | TK Cấp 1 | TK Cấp 2 | Tên Tài Khoản                            |
| --- | -------- | -------- | ---------------------------------------- |
| 46  | **352**  |          | Dự phòng phải trả                        |
|     |          | 3521     | Dự phòng bảo hành sản phẩm hàng hóa      |
|     |          | 3522     | Dự phòng bảo hành công trình xây dựng    |
|     |          | 3523     | Dự phòng tái cơ cấu doanh nghiệp         |
|     |          | 3525     | Dự phòng phải trả khác                   |
| 47  | **353**  |          | Quỹ khen thưởng, phúc lợi                |
|     |          | 3531     | Quỹ khen thưởng                          |
|     |          | 3532     | Quỹ phúc lợi                             |
|     |          | 3533     | Quỹ phúc lợi đã hình thành TSCĐ          |
|     |          | 3534     | Quỹ thưởng ban quản lý điều hành công ty |
| 48  | **356**  |          | Quỹ phát triển khoa học và công nghệ     |
|     |          | 3561     | Quỹ phát triển khoa học và công nghệ     |
|     |          | 3562     | Quỹ phát triển KH&CN đã hình thành TSCĐ  |
| 49  | **357**  |          | Quỹ bình ổn giá                          |

---

### III. Loại Tài Khoản Vốn Chủ Sở Hữu

_(Nhóm 4xx – phản ánh nguồn vốn của chủ sở hữu)_

| STT | TK Cấp 1 | TK Cấp 2 | TK Cấp 3 | Tên Tài Khoản                                                 |
| --- | -------- | -------- | -------- | ------------------------------------------------------------- |
| 50  | **411**  |          |          | Vốn đầu tư của chủ sở hữu                                     |
|     |          | 4111     |          | Vốn góp của chủ sở hữu                                        |
|     |          |          | 41111    | Cổ phiếu phổ thông có quyền biểu quyết                        |
|     |          |          | 41112    | Cổ phiếu ưu đãi                                               |
|     |          | 4112     |          | Thặng dư vốn cổ phần                                          |
|     |          | 4113     |          | Quyền chọn chuyển đổi trái phiếu                              |
|     |          | 4118     |          | Vốn khác                                                      |
| 51  | **412**  |          |          | Chênh lệch đánh giá lại tài sản                               |
| 52  | **413**  |          |          | Chênh lệch tỷ giá hối đoái                                    |
| 53  | **414**  |          |          | Quỹ đầu tư phát triển                                         |
| 54  | **418**  |          |          | Các quỹ khác thuộc vốn chủ sở hữu                             |
| 55  | **419**  |          |          | Cổ phiếu mua lại của chính mình _(đổi tên từ "Cổ phiếu quỹ")_ |
| 56  | **421**  |          |          | Lợi nhuận sau thuế chưa phân phối                             |
|     |          | 4211     |          | Lợi nhuận sau thuế chưa phân phối năm trước                   |
|     |          | 4212     |          | Lợi nhuận sau thuế chưa phân phối năm nay                     |

---

### IV. Loại Tài Khoản Doanh Thu

_(Nhóm 5xx – phản ánh doanh thu thuần của doanh nghiệp)_

| STT | TK Cấp 1 | Tên Tài Khoản                          |
| --- | -------- | -------------------------------------- |
| 57  | **511**  | Doanh thu bán hàng và cung cấp dịch vụ |
| 58  | **515**  | Doanh thu hoạt động tài chính          |
| 59  | **521**  | Các khoản giảm trừ doanh thu           |

---

### V. Loại Tài Khoản Chi Phí Sản Xuất, Kinh Doanh

_(Nhóm 6xx – **nhóm cốt lõi** với doanh nghiệp sản xuất)_

#### 5.1 Chi Phí Sản Xuất Trực Tiếp

| STT | TK Cấp 1 | TK Cấp 2 | Tên Tài Khoản                           |
| --- | -------- | -------- | --------------------------------------- |
| 60  | **621**  |          | Chi phí nguyên liệu, vật liệu trực tiếp |
| 61  | **622**  |          | Chi phí nhân công trực tiếp             |
| 62  | **623**  |          | Chi phí sử dụng máy thi công            |
|     |          | 6231     | Chi phí nhân công                       |
|     |          | 6232     | Chi phí nguyên, vật liệu                |
|     |          | 6233     | Chi phí dụng cụ sản xuất                |
|     |          | 6234     | Chi phí khấu hao máy thi công           |
|     |          | 6237     | Chi phí dịch vụ mua ngoài               |
|     |          | 6238     | Chi phí bằng tiền khác                  |
| 63  | **627**  |          | Chi phí sản xuất chung                  |
|     |          | 6271     | Chi phí nhân viên phân xưởng            |
|     |          | 6272     | Chi phí vật liệu                        |
|     |          | 6273     | Chi phí dụng cụ sản xuất                |
|     |          | 6274     | Chi phí khấu hao TSCĐ                   |
|     |          | 6275     | Thuế, phí, lệ phí                       |
|     |          | 6277     | Chi phí dịch vụ mua ngoài               |
|     |          | 6278     | Chi phí bằng tiền khác                  |

#### 5.2 Chi Phí Thương Mại & Tài Chính

| STT | TK Cấp 1 | TK Cấp 2 | Tên Tài Khoản                |
| --- | -------- | -------- | ---------------------------- |
| 64  | **632**  |          | Giá vốn hàng bán             |
| 65  | **635**  |          | Chi phí tài chính            |
| 66  | **641**  |          | Chi phí bán hàng             |
|     |          | 6411     | Chi phí nhân viên            |
|     |          | 6412     | Chi phí vật liệu, bao bì     |
|     |          | 6413     | Chi phí dụng cụ, đồ dùng     |
|     |          | 6414     | Chi phí khấu hao TSCĐ        |
|     |          | 6415     | Thuế, phí, lệ phí            |
|     |          | 6417     | Chi phí dịch vụ mua ngoài    |
|     |          | 6418     | Chi phí bằng tiền khác       |
| 67  | **642**  |          | Chi phí quản lý doanh nghiệp |
|     |          | 6421     | Chi phí nhân viên quản lý    |
|     |          | 6422     | Chi phí vật liệu quản lý     |
|     |          | 6423     | Chi phí đồ dùng văn phòng    |
|     |          | 6424     | Chi phí khấu hao TSCĐ        |
|     |          | 6425     | Thuế, phí và lệ phí          |
|     |          | 6426     | Chi phí dự phòng             |
|     |          | 6427     | Chi phí dịch vụ mua ngoài    |
|     |          | 6428     | Chi phí bằng tiền khác       |

---

### VI. Loại Tài Khoản Thu Nhập Khác & Chi Phí Khác

| STT | TK Cấp 1 | TK Cấp 2 | TK Cấp 3 | Tên Tài Khoản                                               |
| --- | -------- | -------- | -------- | ----------------------------------------------------------- |
| 68  | **711**  |          |          | Thu nhập khác                                               |
| 69  | **811**  |          |          | Chi phí khác                                                |
| 70  | **821**  |          |          | Chi phí thuế thu nhập doanh nghiệp                          |
|     |          | 8211     |          | Chi phí thuế TNDN hiện hành                                 |
|     |          |          | 82111    | Chi phí thuế TNDN theo Luật thuế TNDN                       |
|     |          |          | 82112    | Chi phí thuế TNDN bổ sung – thuế tối thiểu toàn cầu _(mới)_ |
|     |          | 8212     |          | Chi phí thuế TNDN hoãn lại                                  |

---

### VII. Tài Khoản Xác Định Kết Quả Kinh Doanh

| STT | TK Cấp 1 | Tên Tài Khoản               |
| --- | -------- | --------------------------- |
| 71  | **911**  | Xác định kết quả kinh doanh |

---

## Phần 2 · Tree Map – Dòng Chảy Kế Toán Doanh Nghiệp Sản Xuất

> **Mục tiêu:** Hiểu dòng tiền và bút toán sẽ đi qua những tài khoản nào, theo thứ tự thời gian thực tế phát sinh trong một chu kỳ sản xuất – kinh doanh.

---

### Giai Đoạn 1 · Huy Động Vốn & Mua Sắm Đầu Vào

```
[411 Vốn chủ sở hữu]  ──►  [111/112 Tiền]  ──►  [152 Nguyên vật liệu]
[341 Vay ngân hàng]   ──►  [111/112 Tiền]  ──►  [153 Công cụ, dụng cụ]
                                              ──►  [211 TSCĐ hữu hình]
                                              ──►  [331 Phải trả người bán]
```

**Giải thích:**

- Doanh nghiệp nhận vốn góp → ghi **Nợ 111/112 / Có 411**
- Vay ngân hàng → ghi **Nợ 111/112 / Có 3411**
- Mua nguyên vật liệu trả tiền ngay → ghi **Nợ 152 / Có 111** (hoặc 112)
- Mua chịu nguyên vật liệu → ghi **Nợ 152 / Có 331**
- Mua TSCĐ → ghi **Nợ 211 / Có 111/112/331**

---

### Giai Đoạn 2 · Quy Trình Sản Xuất

```
[152 Nguyên vật liệu]  ──►  [621 CP NVL trực tiếp]  ──┐
[334 Phải trả NLĐ]    ──►  [622 CP nhân công TT]    ──┤
[214 Hao mòn TSCĐ]    ──►  [627 CP sản xuất chung]  ──┤
[153 CC, DC]          ──►  [627 CP sản xuất chung]  ──┤
                                                       ▼
                                        [154 Chi phí SX dở dang]
                                                       │
                                                       ▼
                                              [155 Sản phẩm]
```

**Giải thích chi tiết từng bước:**

**Bước 2a – Xuất NVL vào sản xuất:**

- Xuất kho NVL → ghi **Nợ 621 / Có 152**

**Bước 2b – Tính lương nhân công trực tiếp:**

- Phát sinh lương → ghi **Nợ 622 / Có 334**
- Trích BHXH, BHYT, BHTN (phần DN chịu) → ghi **Nợ 622 / Có 3383, 3384, 3386**

**Bước 2c – Tập hợp chi phí sản xuất chung (627):**

- Khấu hao TSCĐ phân xưởng → ghi **Nợ 6274 / Có 214**
- Lương nhân viên phân xưởng → ghi **Nợ 6271 / Có 334**
- Vật liệu phụ → ghi **Nợ 6272 / Có 152**
- Điện, nước, dịch vụ mua ngoài → ghi **Nợ 6277 / Có 331/111**

**Bước 2d – Kết chuyển vào tài khoản dở dang:**

- Cuối kỳ: **Nợ 154 / Có 621, 622, 627** (kết chuyển toàn bộ CP sản xuất)

**Bước 2e – Nhập kho thành phẩm:**

- Khi sản phẩm hoàn thành → ghi **Nợ 155 / Có 154**

---

### Giai Đoạn 3 · Tiêu Thụ Sản Phẩm

```
[155 Sản phẩm]  ──►  [632 Giá vốn hàng bán]  ──►  [911 XĐKQ]
                ──►  [157 Hàng gửi đi bán]    ──►  [632]  (khi xác nhận bán)

[131 Phải thu KH]  ──►  [511 Doanh thu]       ──►  [911 XĐKQ]
[111/112 Tiền]     ──►  [511 Doanh thu]
                         [3331 Thuế GTGT ĐR]
```

**Giải thích:**

**Bước 3a – Xuất kho sản phẩm để bán:**

- Ghi nhận giá vốn → **Nợ 632 / Có 155**

**Bước 3b – Ghi nhận doanh thu:**

- Bán hàng thu tiền ngay → ghi **Nợ 111 / Có 511, 3331**
- Bán chịu → ghi **Nợ 131 / Có 511, 3331**

**Bước 3c – Chi phí bán hàng & quản lý:**

- Chi phí bán hàng → ghi **Nợ 641 / Có 334, 111, 331…**
- Chi phí QLDN → ghi **Nợ 642 / Có 334, 111, 331…**

---

### Giai Đoạn 4 · Thu Tiền & Thanh Toán Công Nợ

```
[131 Phải thu KH]  ──►  [111/112 Tiền]  ──►  [331 Phải trả NB]
                                         ──►  [334 Phải trả NLĐ]
                                         ──►  [333 Thuế phải nộp]
                                         ──►  [341 Trả nợ vay]
```

**Giải thích:**

- Thu tiền khách hàng → **Nợ 111/112 / Có 131**
- Trả nhà cung cấp → **Nợ 331 / Có 111/112**
- Trả lương → **Nợ 334 / Có 111**
- Nộp thuế VAT → **Nợ 3331 / Có 111** (sau bù trừ với 133)
- Nộp thuế TNDN → **Nợ 3334 / Có 111**

---

### Giai Đoạn 5 · Xác Định Kết Quả Kinh Doanh

```
[511 Doanh thu]       ──►  [911 XĐKQ]  ──►  [421 Lợi nhuận chưa PP]
[515 DT tài chính]   ──►  [911]
[711 Thu nhập khác]  ──►  [911]

[632 Giá vốn HB]     ──►  [911]  (kết chuyển CP)
[641 CP bán hàng]    ──►  [911]
[642 CP QLDN]        ──►  [911]
[635 CP tài chính]   ──►  [911]
[811 CP khác]        ──►  [911]
[821 CP thuế TNDN]   ──►  [911]
```

**Giải thích:**

- Cuối kỳ, kết chuyển doanh thu vào **911**: **Nợ 511 / Có 911**
- Kết chuyển chi phí vào **911**: **Nợ 911 / Có 632, 641, 642…**
- Nếu có **lãi**: **Nợ 911 / Có 421**
- Nếu có **lỗ**: **Nợ 421 / Có 911**

---

### Sơ Đồ Tổng Hợp – Toàn Bộ Chu Kỳ Sản Xuất

```
┌─────────────────────────────────────────────────────────────────────┐
│                    DÒNG CHẢY KẾ TOÁN DNSXKD                        │
│                   (Thông tư 99/2025/TT-BTC)                         │
└─────────────────────────────────────────────────────────────────────┘

  VỐN / TÀI TRỢ            CHUẨN BỊ ĐẦU VÀO         SẢN XUẤT
  ─────────────            ────────────────          ──────────
  411 Vốn CSH   ──►        152 NVL        ──►        621 CP NVL TT
  341 Vay NH    ──►  111   153 CCDC       ──►  154   622 CP NC TT    ──►  155
  331 Phải trả  ──►  112   211 TSCĐ       ──►  dở    627 CP SX chung        SP
                           214 Hao mòn    ──►  dang
                           TSCĐ

  TIÊU THỤ                 DOANH THU / CP              KQKD
  ──────────               ──────────────              ─────
  155 Sản phẩm ──►  632    511 Doanh thu  ──►          911 XĐKQ  ──►  421
  157 Hàng gửi      GVHB  515 DT TC      ──►  911              Lợi nhuận
  131 Phải thu ──►  511    641 CP BH      ──►
  111 Tiền     ──►  511    642 CP QLDN    ──►
  3331 Thuế VT            635 CP TC      ──►
                           821 CP thuế    ──►

  THANH TOÁN              NGHĨA VỤ NHÀ NƯỚC
  ──────────              ──────────────────
  131 → 111/112           133 Thuế GTGT DV ◄── bù trừ ──► 3331 Thuế GTGT ĐR
  331 ← 111/112           334 → 3383/3384/3386 (BHXH, BHYT, BHTN)
  334 ← 111               3334 Thuế TNDN → 111 (nộp)
  3331 → 111 (sau bù trừ)
```

---

## Phần 3 · Bảng Đối Chiếu Điểm Mới So Với Thông Tư 200

| Số hiệu TK             | Thay đổi         | Nội dung                                                                   |
| ---------------------- | ---------------- | -------------------------------------------------------------------------- |
| **112**                | Đổi tên          | Tiền gửi Ngân hàng → **Tiền gửi không kỳ hạn**                             |
| **138**                | Thêm TK cấp 2    | Bổ sung **1383** – Thuế TTĐB hàng nhập khẩu                                |
| **155**                | Đổi tên          | Thành phẩm → **Sản phẩm** (bỏ TK chi tiết 1551, 1557)                      |
| **158**                | Đổi tên          | Hàng hoá kho bảo thuế → **Nguyên liệu, vật tư tại kho bảo thuế**           |
| **215**                | **Bổ sung mới**  | Tài sản sinh học (gồm TK cấp 2: 2151, 2152, 2153 và cấp 3, cấp 4)          |
| **229**                | Thêm TK cấp 2    | Bổ sung **2295** – Dự phòng tổn thất tài sản sinh học                      |
| **241**                | Thêm TK cấp 2    | Bổ sung **2414** – Nâng cấp, cải tạo TSCĐ                                  |
| **242**                | Đổi tên          | Chi phí trả trước → **Chi phí chờ phân bổ**                                |
| **244**                | Đổi tên          | Cầm cố, thế chấp, ký quỹ, ký cược → **Ký quỹ, ký cược**                    |
| **332**                | **Bổ sung mới**  | Phải trả cổ tức, lợi nhuận                                                 |
| **338**                | Đổi tên TK cấp 2 | 3387: Doanh thu chờ phân bổ (thay cho tên cũ)                              |
| **419**                | Đổi tên          | Cổ phiếu quỹ → **Cổ phiếu mua lại của chính mình**                         |
| **821**                | Thêm TK cấp 3    | Bổ sung **82112** – Chi phí thuế TNDN bổ sung theo thuế tối thiểu toàn cầu |
| **417, 441, 461, 466** | **Loại bỏ**      | Các TK quỹ hỗ trợ, nguồn vốn ĐTXDCB, nguồn kinh phí sự nghiệp              |
| **611, 631**           | **Loại bỏ**      | TK Mua hàng và Giá thành sản xuất (không còn trong TT99)                   |

---

## Phần 4 · Lưu Ý Quan Trọng Khi Áp Dụng

### 4.1 Thời Hạn Áp Dụng

- Thông tư 99/2025/TT-BTC có **hiệu lực từ 01/01/2026**
- Áp dụng bắt buộc cho **năm tài chính bắt đầu từ hoặc sau 01/01/2026** (Điều 11)
- Thay thế hoàn toàn Thông tư 200/2014/TT-BTC

### 4.2 Điểm Chú Ý Cho Doanh Nghiệp Sản Xuất

1. **TK 155 (Sản phẩm)** thay cho TK 155 (Thành phẩm) – cần cập nhật danh mục kho
2. **TK 611 và 631 bị loại bỏ** – doanh nghiệp đang dùng phương pháp kiểm kê định kỳ cần chuyển sang phương pháp kê khai thường xuyên hoặc điều chỉnh quy trình
3. **TK 215 (Tài sản sinh học)** – áp dụng cho doanh nghiệp chăn nuôi, trồng trọt
4. **TK 2414** – nâng cấp, cải tạo TSCĐ: trước đây hạch toán vào 241, nay có TK riêng
5. **TK 332** – phải trả cổ tức/lợi nhuận: trước đây hạch toán trong 338, nay tách riêng minh bạch hơn
6. **TK 82112** – thuế TNDN tối thiểu toàn cầu (Pillar 2): áp dụng cho doanh nghiệp đa quốc gia có doanh thu ≥ 750 triệu EUR

### 4.3 Hồ Sơ Lưu Trữ

- Toàn bộ tài liệu đối chiếu, bảng chuyển đổi tài khoản cần lưu trữ **tối thiểu 10 năm** để phục vụ kiểm toán và thanh tra thuế

---

_Tài liệu này được tổng hợp từ Phụ lục II – Hệ thống tài khoản kế toán doanh nghiệp ban hành kèm theo Thông tư 99/2025/TT-BTC. Mọi trích dẫn số hiệu tài khoản đều căn cứ trực tiếp từ văn bản pháp quy._
