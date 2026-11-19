# Hệ Thống Tài Khoản Kế Toán – Thông Tư 99/2025/TT-BTC
## Dành cho Doanh Nghiệp Sản Xuất · Hiệu lực từ 01/01/2026
### (Kèm Bảng Giải Thích Cơ Chế Ghi Nhận, Nguyên Tắc Nợ/Có & Bút Toán Trọng Yếu)

> **Căn cứ pháp lý:** Thông tư số 99/2025/TT-BTC do Bộ Tài chính ban hành, thay thế Thông tư 200/2014/TT-BTC. Hệ thống tài khoản được quy định tại **Phụ lục II** ban hành kèm theo Thông tư, áp dụng bắt buộc cho năm tài chính bắt đầu từ hoặc sau ngày **01/01/2026** (Điều 11, Thông tư 99/2025/TT-BTC).

---

## Tổng Quan Cấu Trúc Hệ Thống

| Cấp tài khoản | Số lượng |
| :--- | :--- |
| Tài khoản cấp 1 | **71** tài khoản |
| Tài khoản cấp 2 | **101** tài khoản |
| Tài khoản cấp 3 | **10** tài khoản |
| Tài khoản cấp 4 | **2** tài khoản |

So với Thông tư 200/2014/TT-BTC, hệ thống mới **giảm 5 tài khoản cấp 1** (từ 76 xuống còn 71) nhằm tinh gọn và tiệm cận với Chuẩn mực Báo cáo Tài chính Quốc tế (IFRS).

---

## Nguyên Tắc Vận Hành Chung Của Hệ Thống Tài Khoản Kế Toán

```
┌──────────────────────────────────────┬──────────────────────────────────────┐
│        BÊN NỢ (DEBIT / DR)           │        BÊN CÓ (CREDIT / CR)          │
├──────────────────────────────────────┼──────────────────────────────────────┤
│ (+) TĂNG: Tài sản (Loại 1, Loại 2)   │ (-) GIẢM: Tài sản (Loại 1, Loại 2)   │
│ (+) TĂNG: Chi phí (Loại 6, Loại 8)   │ (-) GIẢM: Chi phí / Kết chuyển sang 911│
│ (-) GIẢM: Nợ phải trả (Loại 3)       │ (+) TĂNG: Nợ phải trả (Loại 3)       │
│ (-) GIẢM: Vốn chủ sở hữu (Loại 4)    │ (+) TĂNG: Vốn chủ sở hữu (Loại 4)    │
│ (-) GIẢM: Doanh thu / Kết chuyển 911 │ (+) TĂNG: Doanh thu, Thu nhập (5, 7) │
├──────────────────────────────────────┼──────────────────────────────────────┤
│ SỐ DƯ ĐẦU KỲ / CUỐI KỲ: BÊN NỢ      │ SỐ DƯ ĐẦU KỲ / CUỐI KỲ: BÊN CÓ      │
│ (Áp dụng cho Tài sản Loại 1, 2)      │ (Áp dụng cho Nguồn vốn Loại 3, 4)    │
└──────────────────────────────────────┴──────────────────────────────────────┘
* Lưu ý đặc biệt: 
- Nhóm tài khoản điều chỉnh giảm tài sản (214 - Hao mòn TSCĐ, 229 - Dự phòng tổn thất tài sản): Mang tính chất ngược lại với tài sản (Tăng bên Có, Giảm bên Nợ, Số dư bên Có).
- Nhóm tài khoản điều chỉnh giảm vốn chủ sở hữu (419 - Cổ phiếu mua lại của chính mình): Tăng bên Nợ, Giảm bên Có, Số dư bên Nợ.
- Nhóm tài khoản lưỡng tính (131, 138, 331, 338, 421): Có thể có số dư bên Nợ hoặc bên Có (hoặc đồng thời cả hai bên trên chi tiết từng đối tượng).
- Tài khoản Doanh thu (Loại 5), Chi phí (Loại 6, 8), Thu nhập khác (Loại 7) và Xác định kết quả kinh doanh (Loại 9): Là các tài khoản tạm thời, cuối kỳ luôn kết chuyển hết, KHÔNG CÓ SỐ DƯ CUỐI KỲ.
```

---

## Phần 1 · Danh Mục Chi Tiết Toàn Bộ Tài Khoản Kế Toán & Cơ Chế Ghi Nhận

### I. Loại Tài Khoản Tài Sản Ngắn Hạn & Dài Hạn (Nhóm 1xx & 2xx)

#### 1.1 Tiền & Tương Đương Tiền
| STT | TK C1 | TK C2 | Tên Tài Khoản | Bản Chất & Số Dư | Cơ Chế Ghi Nhận Bên Nợ | Cơ Chế Ghi Nhận Bên Có | Bút Toán Đối Ứng Điển Hình |
| :---: | :---: | :---: | :--- | :--- | :--- | :--- | :--- |
| 01 | **111** | | **Tiền mặt** | Tài sản ngắn hạn.<br>Số dư: **Bên Nợ** (Phản ánh số tiền mặt tại quỹ). | - Thu tiền mặt nhập quỹ (thu tiền bán hàng, thu nợ KH, rút tiền gửi về quỹ, thu hồi tạm ứng).<br>- Phát hiện thừa quỹ khi kiểm kê. | - Xuất tiền mặt chi trả nhà cung cấp, tạm ứng, trả lương, nộp vào ngân hàng.<br>- Phát hiện thiếu quỹ khi kiểm kê. | - Rút TGNH về quỹ: Nợ 111 / Có 112<br>- Thu tiền bán hàng: Nợ 111 / Có 511, 3331<br>- Chi trả lương NLĐ: Nợ 334 / Có 111 |
| 02 | **112** | | **Tiền gửi không kỳ hạn** *(TT99 đổi tên từ TGNH)* | Tài sản ngắn hạn.<br>Số dư: **Bên Nợ** (Số tiền hiện có trên tài khoản thanh toán không kỳ hạn). | - Nhận tiền gửi vào ngân hàng (khách hàng thanh toán qua chuyển khoản, nộp tiền mặt, thu lãi tiền gửi không kỳ hạn). | - Trích tiền gửi thanh toán nợ người bán, nộp thuế ngân sách, trả lãi/nợ vay, chuyển khoản đầu tư. | - KH trả nợ qua ngân hàng: Nợ 112 / Có 131<br>- Nộp thuế điện tử: Nợ 333 / Có 112<br>- Trả nợ vay ngân hàng: Nợ 341 / Có 112 |
| 03 | **113** | | **Tiền đang chuyển** | Tài sản ngắn hạn.<br>Số dư: **Bên Nợ** (Số tiền đã làm thủ tục nhưng chưa nhận Giấy báo có/Nợ). | - Nộp tiền mặt/chuyển khoản vào ngân hàng nhưng chưa nhận được Giấy báo Có.<br>- Chuyển tiền chi trả nhưng ngân hàng chưa hạch toán xong. | - Nhận được Giấy báo Có của ngân hàng xác nhận tiền đã vào tài khoản.<br>- Tiền đã chuyển tới tài khoản người nhận. | - Đem tiền mặt nộp vào NH nhưng chưa có GBC: Nợ 113 / Có 111<br>- Khi nhận được GBC: Nợ 112 / Có 113 |

#### 1.2 Đầu Tư Tài Chính Ngắn Hạn & Giữ Đến Ngày Đáo Hạn
| STT | TK C1 | TK C2 | Tên Tài Khoản | Bản Chất & Số Dư | Cơ Chế Ghi Nhận Bên Nợ | Cơ Chế Ghi Nhận Bên Có | Bút Toán Đối Ứng Điển Hình |
| :---: | :---: | :---: | :--- | :--- | :--- | :--- | :--- |
| 04 | **121** | | **Chứng khoán kinh doanh** | Tài sản ngắn hạn.<br>Số dư: **Bên Nợ** (Giá gốc chứng khoán nắm giữ chờ tăng giá bán). | - Giá mua cổ phiếu, trái phiếu kinh doanh mua vào (bao gồm giá mua + chi phí giao dịch). | - Giá gốc chứng khoán kinh doanh bán ra (tính theo bình quân gia quyền hoặc FIFO). | - Mua cổ phiếu kinh doanh: Nợ 121 / Có 112<br>- Bán có lãi: Nợ 112 / Có 121 (giá gốc), Có 515 (lãi)<br>- Bán bị lỗ: Nợ 112, Nợ 635 (lỗ) / Có 121 |
| 05 | **128** | | **Đầu tư nắm giữ đến ngày đáo hạn** | Tài sản ngắn hạn/dài hạn.<br>Số dư: **Bên Nợ** (Giá trị khoản tiền gửi có kỳ hạn, cho vay, trái phiếu). | - Gửi tiền tiết kiệm có kỳ hạn tại ngân hàng.<br>- Cho vay các bên khác bằng tiền.<br>- Mua trái phiếu nắm giữ đến hạn thanh toán. | - Thu hồi tiền gửi có kỳ hạn khi đến hạn tất toán.<br>- Thu hồi nợ gốc cho vay.<br>- Thanh toán trái phiếu khi đáo hạn. | - Gửi tiết kiệm 6 tháng: Nợ 1281 / Có 112<br>- Cho đối tác vay tiền: Nợ 1283 / Có 112<br>- Thu hồi tiền gửi khi đáo hạn: Nợ 112 / Có 1281, Có 515 (lãi) |
| | | 1281 | *Tiền gửi có kỳ hạn* | | | | |
| | | 1282 | *Trái phiếu* | | | | |
| | | 1283 | *Cho vay* | | | | |
| | | 1288 | *Các khoản đầu tư khác* | | | | |

#### 1.3 Các Khoản Phải Thu
| STT | TK C1 | TK C2 | Tên Tài Khoản | Bản Chất & Số Dư | Cơ Chế Ghi Nhận Bên Nợ | Cơ Chế Ghi Nhận Bên Có | Bút Toán Đối Ứng Điển Hình |
| :---: | :---: | :---: | :--- | :--- | :--- | :--- | :--- |
| 06 | **131** | | **Phải thu của khách hàng** | Tài sản (Lưỡng tính).<br>Dư Nợ: Số nợ KH còn nợ DN.<br>Dư Có: Số tiền KH ứng trước tiền mua hàng. | - Số tiền phải thu khi xuất bán sản phẩm, hàng hóa, dịch vụ chưa thu tiền.<br>- Đánh giá lại tăng tỷ giá ngoại tệ cuối kỳ. | - Khách hàng thanh toán tiền mặt/chuyển khoản.<br>- Các khoản giảm giá, chiết khấu thương mại, hàng bán trả lại trừ vào nợ. | - Xuất bán thành phẩm trả chậm: Nợ 131 / Có 511, 3331<br>- Khách thanh toán: Nợ 112 / Có 131<br>- Khách trả trước tiền: Nợ 112 / Có 131 (Dư Có) |
| 07 | **133** | | **Thuế GTGT được khấu trừ** | Tài sản ngắn hạn.<br>Số dư: **Bên Nợ** (Số thuế GTGT đầu vào còn được khấu trừ, hoàn trả). | - Thuế GTGT đầu vào phát sinh khi mua vật tư, hàng hóa, TSCĐ có hóa đơn hợp lệ. | - Bù trừ với thuế GTGT đầu ra phải nộp trong kỳ (TK 3331).<br>- Hoàn thuế GTGT từ NSNN.<br>- Kết chuyển sang chi phí nếu không đủ điều kiện khấu trừ. | - Mua vật tư có VAT: Nợ 152, Nợ 1331 / Có 331<br>- Cuối tháng cấn trừ VAT: Nợ 3331 / Có 133 (min giữa 133 & 3331)<br>- Nhận tiền hoàn thuế: Nợ 112 / Có 133 |
| | | 1331 | *Thuế GTGT khấu trừ của HH, DV* | | | | |
| | | 1332 | *Thuế GTGT khấu trừ của TSCĐ* | | | | |
| 08 | **136** | | **Phải thu nội bộ** | Tài sản (theo dõi cấp công ty & chi nhánh trực thuộc).<br>Dư Nợ: Số nợ nội bộ phải thu. | - Cấp vốn kinh doanh cho đơn vị cấp dưới trực thuộc.<br>- Các khoản chi hộ, bán hộ cho các đơn vị nội bộ. | - Đơn vị nhận vốn nộp lại vốn hoặc chuyển lợi nhuận lên.<br>- Quyết toán các khoản thanh toán bù trừ nội bộ. | - Cấp vốn cho chi nhánh: Nợ 1361 / Có 112<br>- Nhận hoàn vốn từ chi nhánh: Nợ 112 / Có 1361 |
| 09 | **138** | | **Phải thu khác** | Tài sản (Lưỡng tính).<br>Dư Nợ: Các khoản phải thu ngoài thương mại.<br>Dư Có: Khoản đã thu lớn hơn phải thu. | - Giá trị tài sản thiếu chưa xác định nguyên nhân chờ xử lý (1381).<br>- Thuế TTĐB hàng NK được hoàn (1383 - mới TT99).<br>- Cho mượn tài sản, bồi thường, cổ tức/lợi nhuận được chia (1388). | - Kết chuyển tài sản thiếu vào chi phí hoặc bồi thường khi có quyết định xử lý.<br>- Nhận được tiền bồi thường, cổ tức hoặc quyết toán thuế TTĐB. | - Phát hiện thiếu kho NVL: Nợ 1381 / Có 152<br>- Quyết định trừ lương thủ kho: Nợ 334 / Có 1381<br>- Cổ tức được chia: Nợ 1388 / Có 515 |
| | | 1381 | *Tài sản thiếu chờ xử lý* | | | | |
| | | 1383 | *Thuế TTĐB của hàng nhập khẩu* *(Mới)* | | | | |
| | | 1388 | *Phải thu khác* | | | | |
| 10 | **141** | | **Tạm ứng** | Tài sản ngắn hạn.<br>Số dư: **Bên Nợ** (Số tiền tạm ứng cho nhân viên chưa quyết toán). | - Tạm ứng tiền mặt/chuyển khoản cho cán bộ nhân viên đi công tác, mua sắm vật tư. | - Quyết toán số tiền tạm ứng đã chi (theo hóa đơn, chứng từ hợp lệ).<br>- Số tiền tạm ứng thừa nộp lại quỹ hoặc trừ lương. | - Chi tiền tạm ứng đi công tác: Nợ 141 / Có 111<br>- Quyết toán công tác phí: Nợ 642, Nợ 133 / Có 141<br>- Nộp lại tiền tạm ứng thừa: Nợ 111 / Có 141 |

#### 1.4 Hàng Tồn Kho (Trọng Tâm Của Doanh Nghiệp Sản Xuất)
| STT | TK C1 | TK C2 | Tên Tài Khoản | Bản Chất & Số Dư | Cơ Chế Ghi Nhận Bên Nợ | Cơ Chế Ghi Nhận Bên Có | Bút Toán Đối Ứng Điển Hình |
| :---: | :---: | :---: | :--- | :--- | :--- | :--- | :--- |
| 11 | **151** | | **Hàng mua đang đi đường** | Tài sản ngắn hạn.<br>Số dư: **Bên Nợ** (Trị giá hàng hóa, NVL đã mua có hóa đơn nhưng chưa về nhập kho). | - Trị giá hàng mua đã thuộc quyền sở hữu của DN (hóa đơn về) nhưng hàng còn trên đường vận chuyển. | - Hàng về đến doanh nghiệp, làm thủ tục nhập kho (chuyển sang 152, 153, 156) hoặc giao thẳng cho khách. | - Cuối tháng hóa đơn về nhưng hàng chưa về: Nợ 151, Nợ 133 / Có 331<br>- Sang tháng hàng về nhập kho: Nợ 152 / Có 151 |
| 12 | **152** | | **Nguyên liệu, vật liệu** | Hàng tồn kho.<br>Số dư: **Bên Nợ** (Trị giá thực tế NVL hiện có tại kho). | - Trị giá NVL mua ngoài nhập kho (giá mua + chi phí vận chuyển, bốc xếp).<br>- Trị giá NVL tự chế hoàn thành nhập kho.<br>- NVL thừa kiểm kê phát hiện. | - Xuất kho NVL phục vụ trực tiếp sản xuất sản phẩm (621).<br>- Xuất kho cho phân xưởng (627), bán hàng (641), quản lý (642).<br>- Xuất trả lại người bán hoặc bán thẳng NVL. | - Nhập kho NVL mua vào: Nợ 152, Nợ 133 / Có 331, 112<br>- Xuất NVL sản xuất chính: Nợ 621 / Có 152<br>- Xuất NVL cho quản lý xưởng: Nợ 6272 / Có 152 |
| 13 | **153** | | **Công cụ, dụng cụ** | Hàng tồn kho.<br>Số dư: **Bên Nợ** (Trị giá thực tế CCDC tại kho). | - Nhập kho CCDC mua ngoài hoặc tự chế.<br>- CCDC phát hiện thừa khi kiểm kê kho. | - Xuất dùng CCDC cho sản xuất (loại 1 lần vào 627, hoặc phân bổ nhiều lần qua 242).<br>- Xuất bán hoặc trả lại người bán. | - Mua CCDC nhập kho: Nợ 153, Nợ 133 / Có 112<br>- Xuất dùng CCDC giá trị lớn: Nợ 242 / Có 153<br>- Định kỳ phân bổ: Nợ 627, 642 / Có 242 |
| 14 | **154** | | **Chi phí sản xuất, kinh doanh dở dang** | Hàng tồn kho trọng tâm.<br>Số dư: **Bên Nợ** (Chi phí sản xuất của sản phẩm dở dang chưa hoàn thành cuối kỳ). | - Tập hợp toàn bộ chi phí sản xuất trực tiếp phát sinh trong kỳ từ TK 621, 622, 623, 627.<br>- Chi phí thuê ngoài gia công chế biến sản phẩm. | - Giá thành sản xuất thực tế của sản phẩm hoàn thành nhập kho (155) hoặc giao bán thẳng (632).<br>- Chi phí NVL, nhân công vượt định mức đưa thẳng vào 632. | - Cuối kỳ kết chuyển chi phí: Nợ 154 / Có 621, Có 622, Có 627<br>- Nhập kho sản phẩm hoàn thành: Nợ 155 / Có 154<br>- Xuất bán thẳng không qua kho: Nợ 632 / Có 154 |
| 15 | **155** | | **Sản phẩm** *(TT99 đổi tên từ Thành phẩm)* | Hàng tồn kho.<br>Số dư: **Bên Nợ** (Trị giá sản phẩm sản xuất hoàn thành tồn kho). | - Trị giá sản phẩm sản xuất hoàn thành nhập kho từ phân xưởng (theo giá thành công xưởng).<br>- Sản phẩm gửi đại lý không bán được nhập lại kho. | - Xuất kho sản phẩm giao bán cho khách hàng (ghi nhận giá vốn 632).<br>- Xuất kho gửi bán đại lý (157).<br>- Xuất tiêu dùng nội bộ hoặc biếu tặng. | - Nhập kho SP hoàn thành: Nợ 155 / Có 154<br>- Xuất bán giao khách (ghi nhận giá vốn): Nợ 632 / Có 155<br>- Xuất gửi bán đại lý: Nợ 157 / Có 155 |
| 16 | **156** | | **Hàng hóa** | Hàng tồn kho thương mại.<br>Số dư: **Bên Nợ** (Trị giá hàng hóa mua về để bán tồn kho). | - Trị giá hàng hóa mua về nhập kho sẵn sàng bán lẻ/bán buôn.<br>- Hàng hóa bất động sản hoàn thành. | - Xuất kho hàng hóa bán cho khách (ghi nhận giá vốn 632).<br>- Xuất gửi bán, xuất chuyển kho. | - Mua hàng hóa về kho: Nợ 156, Nợ 133 / Có 331<br>- Xuất bán hàng hóa: Nợ 632 / Có 156 |
| 17 | **157** | | **Hàng gửi đi bán** | Hàng tồn kho.<br>Số dư: **Bên Nợ** (Trị giá sản phẩm, hàng hóa đã gửi cho khách/đại lý nhưng chưa xác định tiêu thụ). | - Xuất kho sản phẩm, hàng hóa gửi đi cho khách hàng hoặc đại lý nhận bán theo giá thỏa thuận. | - Khách hàng hoặc đại lý chấp nhận mua hàng (chuyển sang giá vốn 632).<br>- Khách hàng không mua, hàng gửi bán bị trả về nhập lại kho. | - Xuất gửi sản phẩm đi bán: Nợ 157 / Có 155<br>- Đại lý thông báo đã bán hàng: Nợ 632 / Có 157, đồng thời ghi Nợ 131 / Có 511, 3331 |
| 18 | **158** | | **Nguyên liệu, vật tư tại kho bảo thuế** *(Đổi tên TT99)* | Hàng tồn kho.<br>Số dư: **Bên Nợ** (Trị giá NVL nhập khẩu đưa vào kho bảo thuế). | - Nhập khẩu nguyên vật liệu đưa thẳng vào lưu giữ tại kho bảo thuế để phục vụ sản xuất hàng xuất khẩu. | - Xuất NVL từ kho bảo thuế đưa vào quy trình sản xuất (chuyển sang 152 hoặc 621). | - Nhập khẩu NVL vào kho bảo thuế: Nợ 158 / Có 331<br>- Xuất kho bảo thuế vào sản xuất: Nợ 621 / Có 158 |
| 19 | **171** | | **Giao dịch mua bán lại TPCP** | Tài sản tài chính ngắn hạn.<br>Số dư: **Bên Nợ** (Giá trị hợp đồng mua lại TPCP). | - Số tiền trả bên bán khi thực hiện hợp đồng mua lại trái phiếu Chính phủ (Repo). | - Số tiền nhận lại từ việc bán lại TPCP khi hợp đồng hết hạn. | - Chi tiền mua TPCP Repo: Nợ 171 / Có 112<br>- Thu tiền khi kết thúc hợp đồng: Nợ 112 / Có 171, Có 515 (lãi) |

#### 1.5 Tài Sản Cố Định, Tài Sản Sinh Học & Bất Động Sản Đầu Tư
| STT | TK C1 | TK C2/C3 | Tên Tài Khoản | Bản Chất & Số Dư | Cơ Chế Ghi Nhận Bên Nợ | Cơ Chế Ghi Nhận Bên Có | Bút Toán Đối Ứng Điển Hình |
| :---: | :---: | :---: | :--- | :--- | :--- | :--- | :--- |
| 20 | **211** | | **Tài sản cố định hữu hình** | Tài sản dài hạn.<br>Số dư: **Bên Nợ** (Nguyên giá toàn bộ TSCĐ hữu hình thuộc quyền sở hữu của DN). | - Nguyên giá TSCĐ hữu hình tăng do: mua sắm mới, tự xây dựng hoàn thành (kết chuyển từ 241), nhận góp vốn. | - Nguyên giá TSCĐ giảm do: thanh lý, nhượng bán, điều chuyển, mất mát hoặc chuyển thành BĐS đầu tư. | - Mua máy móc thiết bị: Nợ 211, Nợ 1332 / Có 112, 331<br>- Bàn giao công trình XDCB: Nợ 211 / Có 2412<br>- Thanh lý nhượng bán TSCĐ: Nợ 214 (hao mòn), Nợ 811 (GTCL) / Có 211 (nguyên giá) |
| 21 | **212** | | **TSCĐ thuê tài chính** | Tài sản dài hạn.<br>Số dư: **Bên Nợ** (Nguyên giá TSCĐ đi thuê tài chính). | - Nguyên giá TSCĐ thuê tài chính hình thành khi nhận bàn giao thiết bị từ công ty cho thuê tài chính. | - Giảm nguyên giá khi kết thúc hợp đồng thuê: trả lại tài sản, hoặc chuyển quyền sở hữu sang TSCĐ hữu hình (211). | - Nhận bàn giao máy móc thuê TC: Nợ 212 / Có 3412<br>- Kết thúc thuê, mua lại tài sản: Nợ 211 / Có 212 |
| 22 | **213** | | **Tài sản cố định vô hình** | Tài sản dài hạn.<br>Số dư: **Bên Nợ** (Nguyên giá TSCĐ vô hình như quyền sử dụng đất, phần mềm ERP, bằng sáng chế). | - Nguyên giá TSCĐ vô hình tăng do mua sắm, nhận quyền sử dụng đất, tự phát triển phần mềm thành công. | - Giảm nguyên giá TSCĐ vô hình do nhượng bán quyền sử dụng, hết thời gian bảo hộ, thanh lý bản quyền. | - Mua phần mềm quản trị ERP: Nợ 213, Nợ 1332 / Có 112<br>- Khấu hao hàng tháng: Nợ 6424 / Có 2143 |
| 23 | **214** | | **Hao mòn tài sản cố định** | Điều chỉnh giảm tài sản.<br>Số dư: **Bên Có** (Giá trị hao mòn lũy kế của TSCĐ tính đến thời điểm báo cáo). | - Giảm hao mòn lũy kế khi thanh lý, nhượng bán, chuyển nhượng TSCĐ hữu hình/vô hình/BĐS đầu tư. | - Trích khấu hao TSCĐ định kỳ hàng tháng tính vào chi phí sản xuất (627), chi phí bán hàng (641), chi phí QLDN (642). | - Trích KH máy phân xưởng: Nợ 6274 / Có 2141<br>- Trích KH xe văn phòng: Nợ 6424 / Có 2141<br>- Giảm hao mòn khi bán máy: Nợ 2141 / Có 211 |
| | | 2141 | *Hao mòn TSCĐ hữu hình* | | | | |
| | | 2142 | *Hao mòn TSCĐ thuê tài chính* | | | | |
| | | 2143 | *Hao mòn TSCĐ vô hình* | | | | |
| | | 2147 | *Hao mòn BĐS đầu tư* | | | | |
| 24 | **215** | | **Tài sản sinh học** *(Hoàn toàn mới TT99)* | Tài sản dài hạn/ngắn hạn.<br>Số dư: **Bên Nợ** (Nguyên giá đàn súc vật nuôi định kỳ, lấy thịt, cây trồng mùa vụ). | - Mua súc vật giống, chi phí nuôi trồng đến khi trưởng thành (vốn hóa).<br>- Tăng do sinh sản nội bộ hoặc nhận góp vốn. | - Giảm do bán sản phẩm, giết thịt lấy thịt đưa vào chế biến (chuyển sang 154 hoặc 632).<br>- Hao mòn súc vật nuôi định kỳ (215122). | - Mua bò sữa giống: Nợ 21511 / Có 112<br>- Chuyển bò trưởng thành cho sữa: Nợ 215121 / Có 21511<br>- Khấu hao định kỳ đàn bò: Nợ 627 / Có 215122 |
| | | 2151 | *Súc vật nuôi cho SP định kỳ* | | | | |
| | | 2152 | *Súc vật nuôi lấy SP một lần* | | | | |
| | | 2153 | *Cây trồng mùa vụ/lấy SP một lần* | | | | |
| 25 | **217** | | **Bất động sản đầu tư** | Tài sản dài hạn.<br>Số dư: **Bên Nợ** (Nguyên giá nhà xưởng, đất đai nắm giữ để cho thuê hoặc chờ tăng giá). | - Nguyên giá BĐS đầu tư tăng do mua ngoài hoặc chuyển đổi từ TSCĐ sang cho thuê hoạt động. | - Bán, thanh lý BĐS đầu tư hoặc chuyển đổi mục đích sang làm trụ sở hoạt động của công ty. | - Mua tòa nhà cho thuê: Nợ 217, Nợ 1332 / Có 112<br>- Trích khấu hao định kỳ: Nợ 632 / Có 2147 |

#### 1.6 Đầu Tư Tài Chính Dài Hạn & Dự Phòng Tổn Thất Tài Sản
| STT | TK C1 | TK C2 | Tên Tài Khoản | Bản Chất & Số Dư | Cơ Chế Ghi Nhận Bên Nợ | Cơ Chế Ghi Nhận Bên Có | Bút Toán Đối Ứng Điển Hình |
| :---: | :---: | :---: | :--- | :--- | :--- | :--- | :--- |
| 26 | **221** | | **Đầu tư vào công ty con** | Tài sản dài hạn.<br>Số dư: **Bên Nợ** (Giá gốc khoản đầu tư nắm giữ trên 50% quyền biểu quyết). | - Số tiền góp vốn thành lập công ty con hoặc mua cổ phần chi phối (>50% quyền biểu quyết). | - Thu hồi vốn khi giải thể, nhượng bán, thoái vốn khỏi công ty con. | - Mua 70% cổ phần công ty con: Nợ 221 / Có 112<br>- Thoái vốn thu tiền: Nợ 112 / Có 221, Có 515 (lãi) |
| 27 | **222** | | **Đầu tư vào CT liên doanh, liên kết** | Tài sản dài hạn.<br>Số dư: **Bên Nợ** (Giá gốc đầu tư nắm giữ từ 20% đến dưới 50% quyền biểu quyết). | - Góp vốn vào dự án liên doanh hoặc mua cổ phần công ty liên kết có ảnh hưởng đáng kể. | - Giảm do bán bớt vốn, thu hồi vốn góp liên doanh giải thể. | - Chuyển khoản góp vốn liên kết 30%: Nợ 222 / Có 112 |
| 28 | **228** | | **Đầu tư khác** | Tài sản dài hạn.<br>Số dư: **Bên Nợ** (Vốn góp dưới 20% quyền biểu quyết vào đơn vị khác). | - Đầu tư mua cổ phần doanh nghiệp khác dưới 20% quyền biểu quyết mang tính chất dài hạn. | - Thu hồi vốn hoặc bán khoản đầu tư. | - Góp vốn 5% vào công ty bạn: Nợ 2281 / Có 112 |
| 29 | **229** | | **Dự phòng tổn thất tài sản** | Điều chỉnh giảm tài sản.<br>Số dư: **Bên Có** (Tổng số dự phòng đã trích lập tính đến thời điểm báo cáo). | - Hoàn nhập số dự phòng đã trích lập kỳ trước khi giá trị tài sản phục hồi (ghi giảm chi phí).<br>- Xóa sổ nợ khó đòi bằng nguồn dự phòng. | - Trích lập bổ sung các khoản dự phòng cuối niên độ kế toán (ghi tăng chi phí tài chính, QLDN, giá vốn). | - Trích lập DP giảm giá HTK: Nợ 632 / Có 2294<br>- Trích lập DP nợ khó đòi: Nợ 6426 / Có 2293<br>- Trích lập DP tài sản sinh học (mới): Nợ 642 / Có 2295 |
| | | 2291 | *DP giảm giá chứng khoán KD* | | | | |
| | | 2292 | *DP tổn thất đầu tư vào ĐV khác* | | | | |
| | | 2293 | *DP phải thu khó đòi* | | | | |
| | | 2294 | *DP giảm giá hàng tồn kho* | | | | |
| | | 2295 | *DP tổn thất tài sản sinh học* *(Mới)* | | | | |

#### 1.7 Tài Sản Dở Dang & Tài Sản Khác
| STT | TK C1 | TK C2 | Tên Tài Khoản | Bản Chất & Số Dư | Cơ Chế Ghi Nhận Bên Nợ | Cơ Chế Ghi Nhận Bên Có | Bút Toán Đối Ứng Điển Hình |
| :---: | :---: | :---: | :--- | :--- | :--- | :--- | :--- |
| 30 | **241** | | **Xây dựng cơ bản dở dang** | Tài sản dài hạn.<br>Số dư: **Bên Nợ** (Chi phí mua sắm TSCĐ, xây lắp công trình chưa nghiệm thu bàn giao). | - Chi phí mua sắm TSCĐ phát sinh trước khi đưa vào vận hành (2411).<br>- Chi phí thi công xây dựng nhà máy, phân xưởng (2412).<br>- Chi phí cải tạo, nâng cấp mở rộng TSCĐ (2414 - mới TT99). | - Nghiệm thu bàn giao công trình XDCB đưa vào sử dụng (chuyển sang nguyên giá 211, 213, 217).<br>- Quyết toán chi phí cải tạo nâng cấp làm tăng nguyên giá TSCĐ. | - Tập hợp chi phí xây nhà xưởng: Nợ 2412, Nợ 1332 / Có 331<br>- Bàn giao nghiệm thu nhà xưởng: Nợ 211 / Có 2412<br>- Cải tạo nâng cấp dây chuyền: Nợ 2414 / Có 112, sau đó Nợ 211 / Có 2414 |
| | | 2411 | *Mua sắm TSCĐ* | | | | |
| | | 2412 | *Xây dựng cơ bản* | | | | |
| | | 2413 | *Sửa chữa, bảo dưỡng định kỳ TSCĐ* | | | | |
| | | 2414 | *Nâng cấp, cải tạo TSCĐ* *(Mới TT99)* | | | | |
| 31 | **242** | | **Chi phí chờ phân bổ** *(Đổi tên từ Chi phí trả trước)* | Tài sản ngắn hạn/dài hạn.<br>Số dư: **Bên Nợ** (Số chi phí đã chi trả liên quan đến nhiều kỳ kế toán chưa phân bổ hết). | - Các khoản chi phí thực tế đã thanh toán nhưng có tác dụng cho nhiều kỳ sản xuất kinh doanh (tiền thuê đất trả trước, công cụ xuất dùng dài hạn, chi phí bảo hiểm năm). | - Phân bổ dần từng tháng/quý vào chi phí sản xuất chung (627), chi phí bán hàng (641) hoặc quản lý doanh nghiệp (642). | - Trả trước tiền thuê xưởng 1 năm: Nợ 242, Nợ 133 / Có 112<br>- Phân bổ hàng tháng vào CP xưởng: Nợ 627 / Có 242 |
| 32 | **243** | | **Tài sản thuế TNDN hoãn lại** | Tài sản dài hạn.<br>Số dư: **Bên Nợ** (Thuế TNDN được hoàn lại trong tương lai do chênh lệch tạm thời được khấu trừ). | - Số thuế TNDN hoãn lại phát sinh khi chi phí kế toán trích trước lớn hơn chi phí thuế được trừ hiện tại (tạo khoản tiết kiệm thuế tương lai). | - Hoàn nhập tài sản thuế hoãn lại khi các khoản chênh lệch tạm thời được khấu trừ chuyển thành chi phí tính thuế thực tế. | - Ghi nhận tài sản thuế hoãn lại: Nợ 243 / Có 8212<br>- Khi hoàn nhập: Nợ 8212 / Có 243 |
| 33 | **244** | | **Ký quỹ, ký cược** *(Đổi tên TT99)* | Tài sản ngắn hạn/dài hạn.<br>Số dư: **Bên Nợ** (Số tiền gửi đi ký quỹ, ký cược bảo đảm hợp đồng). | - Xuất tiền chuyển đi đặt cọc thuê nhà xưởng, mở thư tín dụng L/C, ký quỹ dự thầu thi công công trình. | - Thu hồi lại tiền ký quỹ ký cược khi hoàn tất thanh lý hợp đồng hoặc hoàn thành nghĩa vụ. | - Đặt cọc thuê mặt bằng sản xuất: Nợ 244 / Có 112<br>- Thanh lý hợp đồng nhận lại tiền cọc: Nợ 112 / Có 244 |

---

### II. Loại Tài Khoản Nợ Phải Trả (Nhóm 3xx)

#### 2.1 Nợ Ngắn Hạn & Phải Trả Thương Mại
| STT | TK C1 | TK C2/C3 | Tên Tài Khoản | Bản Chất & Số Dư | Cơ Chế Ghi Nhận Bên Nợ | Cơ Chế Ghi Nhận Bên Có | Bút Toán Đối Ứng Điển Hình |
| :---: | :---: | :---: | :--- | :--- | :--- | :--- | :--- |
| 34 | **331** | | **Phải trả cho người bán** | Nợ phải trả (Lưỡng tính).<br>Dư Có: Số tiền còn nợ nhà cung cấp.<br>Dư Nợ: Số tiền đã ứng trước cho bên bán. | - Thanh toán nợ người bán bằng tiền mặt/tiền gửi.<br>- Ứng trước tiền hàng cho nhà cung cấp.<br>- Chiết khấu, giảm giá, hàng trả lại người bán chấp nhận trừ nợ. | - Số nợ phải trả phát sinh khi mua nguyên vật liệu, tài sản, dịch vụ chưa thanh toán. | - Mua NVL chưa trả tiền: Nợ 152, Nợ 133 / Có 331<br>- Chuyển khoản thanh toán người bán: Nợ 331 / Có 112<br>- Trả trước cho nhà cung cấp: Nợ 331 / Có 112 (Dư Nợ) |
| 35 | **332** | | **Phải trả cổ tức, lợi nhuận** *(Hoàn toàn mới TT99)* | Nợ phải trả.<br>Số dư: **Bên Có** (Số cổ tức, lợi nhuận đã công bố chia nhưng chưa thanh toán cho cổ đông). | - Chi trả cổ tức, lợi nhuận cho chủ sở hữu/cổ đông bằng tiền mặt, chuyển khoản. | - Số cổ tức, lợi nhuận phải trả theo Nghị quyết Đại hội đồng cổ đông / Hội đồng thành viên (trích từ TK 421). | - Nghị quyết công bố chia cổ tức: Nợ 421 / Có 332<br>- Chuyển khoản chi trả cổ tức cho cổ đông: Nợ 332 / Có 112 |
| 36 | **333** | | **Thuế và các khoản phải nộp Nhà nước** | Nợ phải trả (Lưỡng tính).<br>Dư Có: Số thuế còn nợ NSNN.<br>Dư Nợ: Số thuế đã nộp thừa vào NSNN. | - Số thuế thực tế đã nộp vào Kho bạc Nhà nước.<br>- Số thuế GTGT đầu vào được bù trừ với đầu ra (3331). | - Số thuế phải nộp phát sinh: thuế GTGT đầu ra bán hàng (3331), thuế TNDN (3334), thuế TNCN khấu trừ lương (3335), thuế tài nguyên (3336). | - Ghi nhận thuế GTGT đầu ra: Nợ 131 / Có 511, Có 33311<br>- Nộp thuế điện tử vào NSNN: Nợ 333 / Có 112<br>- Bù trừ thuế VAT cuối tháng: Nợ 3331 / Có 133 |
| | | 3331 | *Thuế GTGT phải nộp (33311: Đầu ra, 33312: Hàng NK)* | | | | |
| | | 3332 | *Thuế tiêu thụ đặc biệt* | | | | |
| | | 3333 | *Thuế xuất, nhập khẩu* | | | | |
| | | 3334 | *Thuế thu nhập doanh nghiệp* | | | | |
| | | 3335 | *Thuế thu nhập cá nhân* | | | | |
| | | 3336 | *Thuế tài nguyên* | | | | |
| | | 3337 | *Thuế nhà đất, tiền thuê đất* | | | | |
| | | 3338 | *Thuế BVMT và các thuế khác* | | | | |
| | | 3339 | *Phí, lệ phí và các khoản khác* | | | | |
| 37 | **334** | | **Phải trả người lao động** | Nợ phải trả.<br>Số dư: **Bên Có** (Tiền lương, thưởng còn nợ nhân viên chưa thanh toán). | - Thanh toán lương, ứng lương, thưởng cho nhân viên.<br>- Các khoản trừ vào lương: BHXH (10.5%), thuế TNCN, tạm ứng. | - Tính lương, tiền công, tiền thưởng và các khoản phụ cấp phải trả cho NLĐ (tập hợp vào chi phí 622, 627, 641, 642). | - Tính bảng lương tháng: Nợ 622 (công nhân), Nợ 627 (quản xưởng), Nợ 642 (văn phòng) / Có 334<br>- Trích trừ lương BHXH của NLĐ: Nợ 334 / Có 3383, 3384, 3386<br>- Chuyển khoản thanh toán lương: Nợ 334 / Có 112 |
| 38 | **335** | | **Chi phí phải trả** | Nợ phải trả.<br>Số dư: **Bên Có** (Các khoản chi phí đã trích trước vào chi phí sản xuất nhưng thực tế chưa phát sinh hóa đơn). | - Chi phí thực tế phát sinh được thanh toán hoặc hóa đơn về bù trừ cho khoản đã trích trước.<br>- Hoàn nhập chi phí trích trước thừa. | - Trích trước vào chi phí trong kỳ theo nguyên tắc phù hợp (tiền lãi vay trả sau, chi phí sửa chữa lớn TSCĐ định kỳ, hoa hồng bán hàng ước tính). | - Trích trước chi phí lãi vay hàng tháng: Nợ 635 / Có 335<br>- Khi ngân hàng thu lãi: Nợ 335 / Có 112<br>- Trích trước chi phí bảo dưỡng máy xưởng: Nợ 627 / Có 335 |
| 39 | **336** | | **Phải trả nội bộ** | Nợ phải trả (giữa công ty mẹ và chi nhánh).<br>Dư Có: Số tiền còn nợ các đơn vị trực thuộc. | - Chi nhánh nộp lại vốn điều hòa hoặc thanh toán các khoản chi trả hộ công ty mẹ. | - Nhận vốn kinh doanh công ty cấp trên rót xuống hoặc các khoản chi nhánh được hưởng. | - Chi nhánh nhận vốn từ công ty mẹ: Nợ 112 / Có 3361 |
| 40 | **337** | | **Thanh toán theo tiến độ HĐ xây dựng** | Nợ phải trả.<br>Số dư: **Bên Có** (Số tiền khách hàng đã thanh toán vượt quá doanh thu ghi nhận theo tiến độ hợp đồng). | - Doanh thu hợp đồng xây dựng được ghi nhận tương ứng với tiến độ công việc hoàn thành. | - Số tiền thanh toán theo hóa đơn xuất theo tiến độ quy định trong hợp đồng xây lắp. | - Xuất hóa đơn thu tiền theo tiến độ: Nợ 131 / Có 337, Có 33311 |
| 41 | **338** | | **Phải trả, phải nộp khác** | Nợ phải trả (Lưỡng tính).<br>Dư Có: Nghĩa vụ BHXH, KPCĐ, doanh thu nhận trước chờ phân bổ (3387). | - Nộp tiền BHXH, BHYT, BHTN, KPCĐ cho cơ quan chức năng.<br>- Phân bổ dần doanh thu chờ phân bổ (3387) sang doanh thu trong kỳ (511).<br>- Xử lý tài sản thừa (3381). | - Trích các khoản bảo hiểm theo lương (DN chịu 23.5%, NLĐ chịu 10.5%).<br>- Nhận trước tiền cho thuê tài sản nhiều kỳ (3387).<br>- Tài sản thừa phát hiện khi kiểm kê chờ xử lý (3381). | - Trích BHXH, BHYT, BHTN DN chịu: Nợ 622, 627, 642 / Có 3383, 3384, 3386<br>- Nộp BHXH qua ngân hàng: Nợ 3383, 3384, 3386 / Có 112<br>- Nhận trước tiền thuê xưởng 1 năm: Nợ 112 / Có 3387, 3331 |
| | | 3381 | *Tài sản thừa chờ giải quyết* | | | | |
| | | 3382 | *Kinh phí công đoàn* | | | | |
| | | 3383 | *Bảo hiểm xã hội* | | | | |
| | | 3384 | *Bảo hiểm y tế* | | | | |
| | | 3386 | *Bảo hiểm thất nghiệp* | | | | |
| | | 3387 | *Doanh thu chờ phân bổ* *(TT99 đổi tên)* | | | | |
| | | 3388 | *Phải trả, phải nộp khác* | | | | |

#### 2.2 Nợ Dài Hạn, Trái Phiếu & Ký Quỹ
| STT | TK C1 | TK C2 | Tên Tài Khoản | Bản Chất & Số Dư | Cơ Chế Ghi Nhận Bên Nợ | Cơ Chế Ghi Nhận Bên Có | Bút Toán Đối Ứng Điển Hình |
| :---: | :---: | :---: | :--- | :--- | :--- | :--- | :--- |
| 42 | **341** | | **Vay và nợ thuê tài chính** | Nợ phải trả dài/ngắn hạn.<br>Số dư: **Bên Có** (Dư nợ gốc các khoản đi vay ngân hàng và nợ thuê tài chính). | - Thanh toán nợ gốc tiền vay cho ngân hàng hoặc trả nợ gốc hợp đồng thuê tài chính định kỳ. | - Tiền vay giải ngân chuyển vào tài khoản tiền gửi hoặc giải ngân thẳng cho nhà cung cấp máy móc thiết bị. | - Vay ngân hàng mua máy móc: Nợ 211 / Có 3411<br>- Giải ngân vay về tài khoản: Nợ 112 / Có 3411<br>- Chuyển khoản trả nợ gốc: Nợ 3411 / Có 112 |
| | | 3411 | *Các khoản đi vay* | | | | |
| | | 3412 | *Nợ thuê tài chính* | | | | |
| 43 | **343** | | **Trái phiếu phát hành** | Nợ phải trả dài hạn.<br>Số dư: **Bên Có** (Mệnh giá và giá trị thực tế trái phiếu phát hành). | - Mua lại trái phiếu trước hạn hoặc thanh toán gốc trái phiếu khi đến hạn đáo hạn. | - Thu tiền từ việc phát hành trái phiếu thường hoặc trái phiếu chuyển đổi ra công chúng/riêng lẻ. | - Phát hành trái phiếu thu tiền: Nợ 112 / Có 34311 (Mệnh giá)<br>- Thanh toán gốc trái phiếu khi đến hạn: Nợ 34311 / Có 112 |
| 44 | **344** | | **Nhận ký quỹ, ký cược** | Nợ phải trả.<br>Số dư: **Bên Có** (Số tiền nhận đặt cọc, ký quỹ từ đại lý hoặc khách thuê tài sản). | - Trả lại tiền ký quỹ, đặt cọc cho khách hàng khi kết thúc hợp đồng.<br>- Trừ vào công nợ nếu khách vi phạm cam kết. | - Nhận tiền ký cược, đặt cọc bằng tiền gửi/tiền mặt từ các đại lý phân phối hoặc bên thuê nhà xưởng. | - Nhận tiền cọc mở đại lý: Nợ 112 / Có 344<br>- Hoàn cọc khi kết thúc đại lý: Nợ 344 / Có 112 |
| 45 | **347** | | **Thuế TNDN hoãn lại phải trả** | Nợ phải trả dài hạn.<br>Số dư: **Bên Có** (Số thuế TNDN sẽ phải nộp thêm trong tương lai do chênh lệch tạm thời chịu thuế). | - Hoàn nhập số thuế TNDN hoãn lại phải trả khi các khoản chênh lệch chịu thuế kết thúc. | - Ghi nhận thuế TNDN hoãn lại phát sinh trong kỳ làm tăng nghĩa vụ thuế tương lai. | - Phát sinh chênh lệch chịu thuế: Nợ 8212 / Có 347<br>- Hoàn nhập: Nợ 347 / Có 8212 |

#### 2.3 Các Quỹ Dự Phòng & Phúc Lợi
| STT | TK C1 | TK C2 | Tên Tài Khoản | Bản Chất & Số Dư | Cơ Chế Ghi Nhận Bên Nợ | Cơ Chế Ghi Nhận Bên Có | Bút Toán Đối Ứng Điển Hình |
| :---: | :---: | :---: | :--- | :--- | :--- | :--- | :--- |
| 46 | **352** | | **Dự phòng phải trả** | Nợ phải trả.<br>Số dư: **Bên Có** (Các khoản dự phòng bảo hành sản phẩm, tái cơ cấu ước tính). | - Chi phí bảo hành thực tế phát sinh trong thời gian bảo hành sản phẩm.<br>- Hoàn nhập dự phòng bảo hành thừa khi hết hạn bảo hành. | - Trích lập dự phòng bảo hành sản phẩm bán ra theo tỷ lệ ước tính doanh thu (ghi nhận vào 6415/641). | - Trích lập DP bảo hành sản phẩm: Nợ 641 / Có 3521<br>- Khách mang SP lỗi đến bảo hành sửa chữa: Nợ 3521 / Có 152, 111 |
| 47 | **353** | | **Quỹ khen thưởng, phúc lợi** | Nợ phải trả / Quỹ phúc lợi.<br>Số dư: **Bên Có** (Số quỹ hiện còn chưa chi dùng cho đời sống NLĐ). | - Chi tiền thưởng định kỳ, lễ tết cho cán bộ nhân viên.<br>- Chi các hoạt động phúc lợi (nghỉ mát, trợ cấp khó khăn, mua sắm TSCĐ dùng cho phúc lợi). | - Trích lập quỹ từ lợi nhuận sau thuế chưa phân phối theo quyết định của ĐHĐCĐ (TK 421). | - Trích lập quỹ từ LNST: Nợ 421 / Có 3531, 3532<br>- Chi tiền thưởng Tết: Nợ 3531 / Có 334, rồi Nợ 334 / Có 111 |
| 48 | **356** | | **Quỹ phát triển KH&CN** | Quỹ đặc thù.<br>Số dư: **Bên Có** (Quỹ khoa học công nghệ chưa sử dụng hết). | - Chi cho các hoạt động nghiên cứu phát triển công nghệ sản xuất, mua sắm thiết bị nghiên cứu. | - Trích lập quỹ phát triển KH&CN tính trực tiếp vào chi phí hoạt động theo tỷ lệ quy định. | - Trích lập quỹ: Nợ 642 / Có 3561<br>- Chi phí đề tài nghiên cứu công nghệ mới: Nợ 3561 / Có 112 |
| 49 | **357** | | **Quỹ bình ổn giá** | Quỹ quản lý giá.<br>Số dư: **Bên Có** (Áp dụng cho doanh nghiệp kinh doanh mặt hàng bình ổn theo quy định Nhà nước). | - Xuất quỹ hỗ trợ bình ổn giá theo quyết định của cơ quan nhà nước có thẩm quyền. | - Trích lập quỹ bình ổn giá theo cơ chế điều hành giá của Nhà nước. | - Trích quỹ: Nợ 632 / Có 357<br>- Sử dụng quỹ bình ổn: Nợ 357 / Có 511 |

---

### III. Loại Tài Khoản Vốn Chủ Sở Hữu (Nhóm 4xx)

| STT | TK C1 | TK C2/C3 | Tên Tài Khoản | Bản Chất & Số Dư | Cơ Chế Ghi Nhận Bên Nợ | Cơ Chế Ghi Nhận Bên Có | Bút Toán Đối Ứng Điển Hình |
| :---: | :---: | :---: | :--- | :--- | :--- | :--- | :--- |
| 50 | **411** | | **Vốn đầu tư của chủ sở hữu** | Vốn chủ sở hữu.<br>Số dư: **Bên Có** (Tổng số vốn góp thực tế của các cổ đông, thành viên theo giấy phép ĐKKD). | - Giảm vốn điều lệ do trả bớt vốn góp cho chủ sở hữu, hủy bỏ cổ phiếu quỹ mua lại. | - Nhận vốn góp thành lập doanh nghiệp hoặc tăng vốn điều lệ từ các cổ đông bằng tiền, TSCĐ. | - Cổ đông chuyển tiền góp vốn: Nợ 112 / Có 4111<br>- Góp vốn bằng xe chuyên chở: Nợ 211 / Có 4111<br>- Phát hành cổ phiếu có thặng dư: Nợ 112 / Có 4111 (mệnh giá), Có 4112 (thặng dư) |
| | | 4111 | *Vốn góp của CSH (41111: CP phổ thông, 41112: CP ưu đãi)* | | | | |
| | | 4112 | *Thặng dư vốn cổ phần* | | | | |
| | | 4113 | *Quyền chọn chuyển đổi trái phiếu* | | | | |
| | | 4118 | *Vốn khác* | | | | |
| 51 | **412** | | **Chênh lệch đánh giá lại tài sản** | Vốn chủ sở hữu (Lưỡng tính).<br>Dư Có: Đánh giá tăng tài sản.<br>Dư Nợ: Đánh giá giảm tài sản. | - Ghi nhận chênh lệch giảm giá trị tài sản khi đánh giá lại theo quyết định Nhà nước.<br>- Kết chuyển chênh lệch tăng vào vốn CSH. | - Ghi nhận chênh lệch tăng giá trị tài sản khi đánh giá lại tài sản đưa đi góp vốn liên doanh, cổ phần hóa. | - Đánh giá tăng giá trị TSCĐ: Nợ 211 / Có 412<br>- Đánh giá giảm TSCĐ: Nợ 412 / Có 211 |
| 52 | **413** | | **Chênh lệch tỷ giá hối đoái** | Vốn chủ sở hữu (Lưỡng tính).<br>Dư Có: Lãi chênh lệch tỷ giá chưa xử lý.<br>Dư Nợ: Lỗ chênh lệch tỷ giá chưa xử lý. | - Kết chuyển khoản lỗ tỷ giá chưa thực hiện phát sinh từ việc đánh giá lại ngoại tệ của các dự án ĐTXDCB trước hoạt động. | - Kết chuyển khoản lãi tỷ giá chưa thực hiện của dự án ĐTXDCB trong giai đoạn trước hoạt động. | - Chênh lệch tỷ giá giai đoạn XDCB trước hoạt động: Nợ 112 / Có 413 (hoặc ngược lại) |
| 53 | **414** | | **Quỹ đầu tư phát triển** | Vốn chủ sở hữu.<br>Số dư: **Bên Có** (Số quỹ tích lũy từ lợi nhuận sau thuế để tái đầu tư mở rộng sản xuất). | - Sử dụng quỹ bổ sung vốn điều lệ của công ty (chuyển sang 4111) theo Nghị quyết ĐHĐCĐ. | - Trích lập quỹ đầu tư phát triển từ lợi nhuận sau thuế chưa phân phối (TK 421). | - Trích lập quỹ từ LNST: Nợ 421 / Có 414<br>- Chuyển quỹ tăng vốn điều lệ: Nợ 414 / Có 4111 |
| 54 | **418** | | **Các quỹ khác thuộc VCSH** | Vốn chủ sở hữu.<br>Số dư: **Bên Có** (Các quỹ dự trữ tài chính theo điều lệ công ty). | - Sử dụng quỹ khác theo điều lệ công ty phê duyệt. | - Trích lập từ LNST (TK 421). | - Trích lập quỹ khác: Nợ 421 / Có 418 |
| 55 | **419** | | **Cổ phiếu mua lại của chính mình** *(TT99 đổi tên từ Cổ phiếu quỹ)* | Điều chỉnh giảm VCSH.<br>Số dư: **Bên Nợ** (Giá trị thực tế mua lại cổ phiếu do chính doanh nghiệp phát hành). | - Giá trị thực tế bỏ ra mua lại cổ phiếu của chính mình đang lưu hành trên thị trường. | - Hủy bỏ cổ phiếu mua lại (ghi giảm vốn điều lệ 4111).<br>- Tái phát hành ra thị trường thu tiền. | - Chi tiền mua lại cổ phiếu của chính mình: Nợ 419 / Có 112<br>- Hủy cổ phiếu mua lại: Nợ 4111 / Có 419 (chênh lệch ghi vào 4112) |
| 56 | **421** | | **Lợi nhuận sau thuế chưa phân phối** | Vốn chủ sở hữu (Lưỡng tính).<br>Dư Có: Lãi lũy kế chưa phân phối.<br>Dư Nợ: Lỗ lũy kế chưa bù đắp. | - Kết chuyển số lỗ hoạt động SXKD trong kỳ từ TK 911.<br>- Phân phối lợi nhuận: chia cổ tức (332), trích lập các quỹ (414, 353). | - Kết chuyển số lãi thuần hoạt động SXKD trong kỳ từ TK 911 (Nợ 911 / Có 421). | - Kết chuyển lãi trong kỳ: Nợ 911 / Có 4212<br>- Trích chia cổ tức cho cổ đông: Nợ 421 / Có 332<br>- Trích quỹ đầu tư phát triển: Nợ 421 / Có 414 |
| | | 4211 | *LNST chưa phân phối năm trước* | | | | |
| | | 4212 | *LNST chưa phân phối năm nay* | | | | |

---

### IV. Loại Tài Khoản Doanh Thu (Nhóm 5xx)

*(Các tài khoản doanh thu không có số dư cuối kỳ – tập hợp bên Có, kết chuyển bên Nợ sang 911)*

| STT | TK C1 | Tên Tài Khoản | Bản Chất | Cơ Chế Ghi Nhận Bên Nợ | Cơ Chế Ghi Nhận Bên Có | Bút Toán Đối Ứng Điển Hình |
| :---: | :---: | :--- | :--- | :--- | :--- | :--- |
| 57 | **511** | **Doanh thu bán hàng và CCDV** | Doanh thu hoạt động cốt lõi.<br>**Không có số dư cuối kỳ**. | - Kết chuyển các khoản giảm trừ doanh thu (521).<br>- Cuối kỳ kết chuyển toàn bộ doanh thu thuần sang TK 911 để xác định kết quả kinh doanh. | - Doanh thu xuất bán sản phẩm, hàng hóa hoàn thành bàn giao cho khách hàng (không bao gồm thuế gián thu).<br>- Doanh thu dịch vụ gia công, vận tải. | - Bán thành phẩm chưa thu tiền: Nợ 131 / Có 511, Có 33311<br>- Kết chuyển giảm trừ: Nợ 511 / Có 521<br>- Cuối kỳ kết chuyển DT thuần: Nợ 511 / Có 911 |
| 58 | **515** | **Doanh thu hoạt động tài chính** | Doanh thu tài chính.<br>**Không có số dư cuối kỳ**. | - Cuối kỳ kết chuyển toàn bộ doanh thu tài chính phát sinh trong kỳ sang TK 911. | - Lãi tiền gửi ngân hàng, lãi cho vay (128).<br>- Cổ tức, lợi nhuận được chia.<br>- Lãi chênh lệch tỷ giá hối đoái đã thực hiện và đánh giá lại cuối kỳ.<br>- Lãi bán chứng khoán kinh doanh (121). | - Thu lãi tiền gửi định kỳ: Nợ 112 / Có 515<br>- Đánh giá lại lãi tỷ giá nợ phải thu: Nợ 131 / Có 515<br>- Cuối kỳ kết chuyển: Nợ 515 / Có 911 |
| 59 | **521** | **Các khoản giảm trừ doanh thu** | Tài khoản điều chỉnh giảm doanh thu.<br>**Không có số dư cuối kỳ**. | - Phát sinh các khoản chiết khấu thương mại cho khách mua số lượng lớn.<br>- Giảm giá hàng bán do lỗi quy cách phẩm chất.<br>- Hàng bán bị trả lại nhập kho. | - Cuối kỳ kết chuyển toàn bộ số chiết khấu thương mại, giảm giá, hàng bán bị trả lại sang giảm trừ doanh thu (TK 511). | - Chiết khấu thương mại cho khách hàng: Nợ 521, Nợ 33311 / Có 131<br>- Hàng bị trả lại nhập kho: Nợ 521, Nợ 33311 / Có 131, đồng thời Nợ 155 / Có 632<br>- Kết chuyển giảm trừ doanh thu: Nợ 511 / Có 521 |

---

### V. Loại Tài Khoản Chi Phí Sản Xuất, Kinh Doanh (Nhóm 6xx)

*(Nhóm cốt lõi sống còn của doanh nghiệp sản xuất – Không có số dư cuối kỳ)*

#### 5.1 Chi Phí Sản Xuất Trực Tiếp & Phân Xưởng
| STT | TK C1 | TK C2 | Tên Tài Khoản | Bản Chất | Cơ Chế Ghi Nhận Bên Nợ | Cơ Chế Ghi Nhận Bên Có | Bút Toán Đối Ứng Điển Hình |
| :---: | :---: | :---: | :--- | :--- | :--- | :--- | :--- |
| 60 | **621** | | **Chi phí nguyên liệu, vật liệu trực tiếp** | Chi phí sản xuất trực tiếp.<br>**Không có số dư cuối kỳ**. | - Trị giá thực tế của NVL chính, NVL phụ xuất kho đưa trực tiếp vào chế tạo sản phẩm của phân xưởng. | - Trị giá NVL dùng không hết nhập lại kho (Có 152).<br>- Trị giá phế liệu thu hồi (Có 152).<br>- Cuối kỳ kết chuyển toàn bộ vào TK 154 để tính giá thành sản phẩm. | - Xuất thép, sợi, nhựa sản xuất: Nợ 621 / Có 152<br>- NVL không dùng hết nhập lại: Nợ 152 / Có 621<br>- Cuối kỳ kết chuyển tính giá thành: Nợ 154 / Có 621 |
| 61 | **622** | | **Chi phí nhân công trực tiếp** | Chi phí sản xuất trực tiếp.<br>**Không có số dư cuối kỳ**. | - Tiền lương, phụ cấp phải trả trực tiếp cho công nhân đứng máy sản xuất sản phẩm.<br>- Các khoản trích BHXH, BHYT, BHTN, KPCĐ (23.5%) DN chịu tính trên lương công nhân. | - Cuối kỳ kết chuyển chi phí nhân công trực tiếp sang TK 154 để tính giá thành sản phẩm.<br>- Phần chi phí nhân công vượt công suất bình thường kết chuyển thẳng sang giá vốn 632. | - Tính lương công nhân sản xuất: Nợ 622 / Có 334<br>- Trích bảo hiểm tính theo lương: Nợ 622 / Có 338 (3382, 3383, 3384, 3386)<br>- Cuối kỳ kết chuyển tính giá thành: Nợ 154 / Có 622 |
| 62 | **623** | | **Chi phí sử dụng máy thi công** | Chi phí công trình xây lắp.<br>**Không có số dư cuối kỳ**. | - Chi phí lương thợ điều khiển máy, nhiên liệu xăng dầu, khấu hao máy thi công tại công trình xây lắp. | - Cuối kỳ kết chuyển vào chi phí xây lắp dở dang (TK 154) để tính giá thành công trình. | - Lương thợ máy: Nợ 6231 / Có 334<br>- Nhiên liệu máy thi công: Nợ 6232 / Có 152, 112<br>- Cuối kỳ kết chuyển: Nợ 154 / Có 623 |
| 63 | **627** | | **Chi phí sản xuất chung** | Chi phí phục vụ sản xuất tại phân xưởng.<br>**Không có số dư cuối kỳ**. | - Lương quản đốc, nhân viên kỹ thuật phân xưởng (6271).<br>- Chi phí vật liệu bảo dưỡng máy (6272), công cụ dụng cụ xưởng (6273).<br>- Khấu hao nhà xưởng, máy móc (6274).<br>- Tiền điện, nước, dịch vụ mua ngoài tại phân xưởng (6277). | - Các khoản ghi giảm chi phí sản xuất chung.<br>- Cuối kỳ kết chuyển chi phí SXC cố định đạt công suất và chi phí SXC biến đổi sang TK 154 tính giá thành.<br>- Phần chi phí SXC cố định không được phân bổ (do công suất thấp) ghi thẳng vào 632. | - Khấu hao máy móc phân xưởng: Nợ 6274 / Có 2141<br>- Lương nhân viên quản xưởng: Nợ 6271 / Có 334<br>- Tiền điện xưởng sản xuất: Nợ 6277, Nợ 1331 / Có 331<br>- Kết chuyển chi phí SXC vào giá thành: Nợ 154 / Có 627 |
| | | 6271 | *Chi phí nhân viên phân xưởng* | | | | |
| | | 6272 | *Chi phí vật liệu* | | | | |
| | | 6273 | *Chi phí dụng cụ sản xuất* | | | | |
| | | 6274 | *Chi phí khấu hao TSCĐ* | | | | |
| | | 6275 | *Thuế, phí, lệ phí* | | | | |
| | | 6277 | *Chi phí dịch vụ mua ngoài* | | | | |
| | | 6278 | *Chi phí bằng tiền khác* | | | | |

#### 5.2 Giá Vốn, Chi Phí Thương Mại & Tài Chính
| STT | TK C1 | TK C2 | Tên Tài Khoản | Bản Chất | Cơ Chế Ghi Nhận Bên Nợ | Cơ Chế Ghi Nhận Bên Có | Bút Toán Đối Ứng Điển Hình |
| :---: | :---: | :---: | :--- | :--- | :--- | :--- | :--- |
| 64 | **632** | | **Giá vốn hàng bán** | Chi phí kinh doanh trọng điểm.<br>**Không có số dư cuối kỳ**. | - Giá thành thực tế của sản phẩm xuất kho giao bán cho khách hàng trong kỳ (Nợ 632 / Có 155).<br>- Giá trị hàng hóa xuất bán (Có 156).<br>- Chi phí sản xuất vượt định mức bình thường.<br>- Trích lập dự phòng giảm giá HTK (Có 2294). | - Hoàn nhập dự phòng giảm giá hàng tồn kho cuối năm.<br>- Giá vốn của sản phẩm, hàng hóa bị khách hàng trả lại nhập kho (ghi giảm 632, Có 155).<br>- Cuối kỳ kết chuyển toàn bộ giá vốn sang TK 911 để tính lãi/lỗ. | - Ghi nhận giá vốn SP xuất bán: Nợ 632 / Có 155<br>- Hàng bán bị trả lại nhập kho: Nợ 155 / Có 632<br>- Cuối kỳ kết chuyển giá vốn: Nợ 911 / Có 632 |
| 65 | **635** | | **Chi phí tài chính** | Chi phí tài chính.<br>**Không có số dư cuối kỳ**. | - Chi phí lãi vay vốn sản xuất kinh doanh trả định kỳ hoặc trích trước.<br>- Lỗ chênh lệch tỷ giá hối đoái phát sinh trong kỳ hoặc đánh giá lại cuối năm.<br>- Chiết khấu thanh toán dành cho khách hàng trả sớm.<br>- Trích lập dự phòng giảm giá chứng khoán kinh doanh, tổn thất đầu tư. | - Hoàn nhập dự phòng đầu tư tài chính.<br>- Các khoản giảm chi phí tài chính.<br>- Cuối kỳ kết chuyển toàn bộ chi phí tài chính sang TK 911. | - Trả lãi vay ngân hàng hàng tháng: Nợ 635 / Có 112<br>- Dành chiết khấu thanh toán cho khách trả nợ sớm: Nợ 635 / Có 131<br>- Cuối kỳ kết chuyển CP tài chính: Nợ 911 / Có 635 |
| 66 | **641** | | **Chi phí bán hàng** | Chi phí hoạt động thương mại.<br>**Không có số dư cuối kỳ**. | - Lương nhân viên kinh doanh, bán hàng, tiếp thị (6411).<br>- Bao bì đóng gói sản phẩm xuất xưởng (6412).<br>- Khấu hao xe chuyên chở giao hàng (6414).<br>- Chi phí vận chuyển, tiếp thị, quảng cáo, hội chợ triển lãm (6417).<br>- Trích trước chi phí bảo hành sản phẩm (Có 352). | - Các khoản giảm trừ chi phí bán hàng (bồi thường, bớt giá).<br>- Cuối kỳ kết chuyển chi phí bán hàng sang TK 911 để xác định kết quả kinh doanh. | - Lương nhân viên bán hàng: Nợ 6411 / Có 334<br>- Tiền thuê xe vận chuyển hàng đi bán: Nợ 6417, Nợ 133 / Có 331<br>- Cuối kỳ kết chuyển CP bán hàng: Nợ 911 / Có 641 |
| | | 6411 | *Chi phí nhân viên* | | | | |
| | | 6412 | *Chi phí vật liệu, bao bì* | | | | |
| | | 6413 | *Chi phí dụng cụ, đồ dùng* | | | | |
| | | 6414 | *Chi phí khấu hao TSCĐ* | | | | |
| | | 6415 | *Thuế, phí, lệ phí* | | | | |
| | | 6417 | *Chi phí dịch vụ mua ngoài* | | | | |
| | | 6418 | *Chi phí bằng tiền khác* | | | | |
| 67 | **642** | | **Chi phí quản lý doanh nghiệp** | Chi phí quản lý chung.<br>**Không có số dư cuối kỳ**. | - Lương ban giám đốc, khối phòng ban kế toán, nhân sự, IT (6421).<br>- Khấu hao trụ sở văn phòng, máy tính (6424).<br>- Văn phòng phẩm, vật tư văn phòng (6423).<br>- Trích lập dự phòng nợ phải thu khó đòi (6426 - Có 2293).<br>- Thuế môn bài, phí lệ phí hành chính (6425). | - Hoàn nhập dự phòng phải thu khó đòi.<br>- Giảm chi phí quản lý.<br>- Cuối kỳ kết chuyển toàn bộ chi phí quản lý doanh nghiệp sang TK 911. | - Lương nhân viên khối quản lý: Nợ 6421 / Có 334<br>- Trích khấu hao văn phòng công ty: Nợ 6424 / Có 2141<br>- Nợ khó đòi trích lập dự phòng: Nợ 6426 / Có 2293<br>- Cuối kỳ kết chuyển CP QLDN: Nợ 911 / Có 642 |
| | | 6421 | *Chi phí nhân viên quản lý* | | | | |
| | | 6422 | *Chi phí vật liệu quản lý* | | | | |
| | | 6423 | *Chi phí đồ dùng văn phòng* | | | | |
| | | 6424 | *Chi phí khấu hao TSCĐ* | | | | |
| | | 6425 | *Thuế, phí và lệ phí* | | | | |
| | | 6426 | *Chi phí dự phòng* | | | | |
| | | 6427 | *Chi phí dịch vụ mua ngoài* | | | | |
| | | 6428 | *Chi phí bằng tiền khác* | | | | |

---

### VI. Loại Tài Khoản Thu Nhập Khác, Chi Phí Khác & Thuế TNDN (Nhóm 7xx & 8xx)

| STT | TK C1 | TK C2/C3 | Tên Tài Khoản | Bản Chất | Cơ Chế Ghi Nhận Bên Nợ | Cơ Chế Ghi Nhận Bên Có | Bút Toán Đối Ứng Điển Hình |
| :---: | :---: | :---: | :--- | :--- | :--- | :--- | :--- |
| 68 | **711** | | **Thu nhập khác** | Thu nhập ngoài kinh doanh chính.<br>**Không có số dư cuối kỳ**. | - Cuối kỳ kết chuyển toàn bộ thu nhập khác phát sinh sang TK 911 để xác định kết quả kinh doanh. | - Thu thanh lý, nhượng bán TSCĐ (giá bán chưa VAT).<br>- Thu tiền phạt vi phạm hợp đồng kinh tế từ đối tác.<br>- Xóa sổ các khoản nợ phải trả không tìm ra chủ nợ.<br>- Quà biếu, tài trợ nhận được. | - Bán thanh lý máy móc thu tiền: Nợ 112 / Có 711, Có 33311<br>- Thu tiền phạt nhà cung cấp vi phạm tiến độ: Nợ 112 / Có 711<br>- Cuối kỳ kết chuyển: Nợ 711 / Có 911 |
| 69 | **811** | | **Chi phí khác** | Chi phí ngoài kinh doanh chính.<br>**Không có số dư cuối kỳ**. | - Giá trị còn lại của TSCĐ thanh lý, nhượng bán và chi phí phục vụ tháo dỡ thanh lý.<br>- Bị phạt vi phạm hành chính, phạt vi phạm hợp đồng kinh tế.<br>- Chi ủng hộ từ thiện, tài trợ theo chính sách công ty. | - Cuối kỳ kết chuyển toàn bộ chi phí khác sang TK 911 để tính lãi/lỗ kinh doanh. | - Giá trị còn lại TSCĐ thanh lý: Nợ 811, Nợ 214 / Có 211<br>- Nộp phạt vi phạm hợp đồng giao trễ hàng: Nợ 811 / Có 112<br>- Cuối kỳ kết chuyển: Nợ 911 / Có 811 |
| 70 | **821** | | **Chi phí thuế thu nhập doanh nghiệp** | Chi phí thuế TNDN.<br>**Không có số dư cuối kỳ**. | - Số thuế TNDN hiện hành phải nộp tính trên thu nhập chịu thuế năm nay (82111).<br>- Số thuế TNDN bổ sung theo cơ chế thuế tối thiểu toàn cầu (82112 - mới TT99).<br>- Chi phí thuế TNDN hoãn lại phát sinh trong năm (8212). | - Số thuế TNDN hiện hành được điều chỉnh giảm khi quyết toán lại năm trước.<br>- Kết chuyển chi phí thuế TNDN sang TK 911 cuối kỳ. | - Tạm nộp/Tính thuế TNDN phải nộp: Nợ 82111 / Có 3334<br>- Doanh nghiệp đa quốc gia ghi nhận thuế tối thiểu toàn cầu: Nợ 82112 / Có 3334<br>- Cuối kỳ kết chuyển chi phí thuế: Nợ 911 / Có 821 |
| | | 8211 | *Chi phí thuế TNDN hiện hành* | | | | |
| | | | 82111: *Theo Luật Thuế TNDN* | | | | |
| | | | 82112: *Thuế tối thiểu toàn cầu* *(Mới)* | | | | |
| | | 8212 | *Chi phí thuế TNDN hoãn lại* | | | | |

---

### VII. Loại Tài Khoản Xác Định Kết Quả Kinh Doanh (Nhóm 9xx)

| STT | TK C1 | Tên Tài Khoản | Bản Chất | Cơ Chế Ghi Nhận Bên Nợ | Cơ Chế Ghi Nhận Bên Có | Bút Toán Đối Ứng Điển Hình |
| :---: | :---: | :--- | :--- | :--- | :--- | :--- |
| 71 | **911** | **Xác định kết quả kinh doanh** | Tài khoản trung gian đối ứng tổng hợp.<br>**Không có số dư cuối kỳ**. | - Kết chuyển Giá vốn hàng bán (từ 632).<br>- Kết chuyển Chi phí tài chính (từ 635).<br>- Kết chuyển Chi phí bán hàng (từ 641).<br>- Kết chuyển Chi phí QLDN (từ 642).<br>- Kết chuyển Chi phí khác (từ 811).<br>- Kết chuyển Chi phí thuế TNDN (từ 821).<br>- **Kết chuyển số LÃI THUẦN sang TK 4212 (Nợ 911 / Có 4212)**. | - Kết chuyển Doanh thu thuần bán hàng & CCDV (từ 511).<br>- Kết chuyển Doanh thu hoạt động tài chính (từ 515).<br>- Kết chuyển Thu nhập khác (từ 711).<br>- **Kết chuyển số LỖ THUẦN sang TK 4212 (Nợ 4212 / Có 911)**. | - Kết chuyển toàn bộ doanh thu: Nợ 511, 515, 711 / Có 911<br>- Kết chuyển toàn bộ chi phí: Nợ 911 / Có 632, 635, 641, 642, 811, 821<br>- Kết chuyển lãi kinh doanh: Nợ 911 / Có 4212<br>- Kết chuyển lỗ kinh doanh: Nợ 4212 / Có 911 |

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
- Doanh nghiệp nhận vốn góp ──► ghi **Nợ 111/112 / Có 411**
- Vay ngân hàng ──► ghi **Nợ 111/112 / Có 3411**
- Mua nguyên vật liệu trả tiền ngay ──► ghi **Nợ 152 / Có 111** (hoặc 112)
- Mua chịu nguyên vật liệu ──► ghi **Nợ 152 / Có 331**
- Mua TSCĐ ──► ghi **Nợ 211 / Có 111/112/331**

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
- **Bước 2a – Xuất NVL vào sản xuất:** Xuất kho NVL ──► ghi **Nợ 621 / Có 152**
- **Bước 2b – Tính lương nhân công trực tiếp:** Phát sinh lương ──► ghi **Nợ 622 / Có 334**; trích bảo hiểm phần DN chịu ──► ghi **Nợ 622 / Có 338**
- **Bước 2c – Tập hợp chi phí sản xuất chung (627):** Khấu hao TSCĐ ──► ghi **Nợ 6274 / Có 214**; lương quản xưởng ──► ghi **Nợ 6271 / Có 334**; điện nước xưởng ──► ghi **Nợ 6277 / Có 331**
- **Bước 2d – Kết chuyển tính giá thành:** Cuối kỳ: **Nợ 154 / Có 621, 622, 627**
- **Bước 2e – Nhập kho sản phẩm:** Khi sản phẩm hoàn thành ──► ghi **Nợ 155 / Có 154**

---

### Giai Đoạn 3 · Tiêu Thụ Sản Phẩm & Doanh Thu
```
[155 Sản phẩm]  ──►  [632 Giá vốn hàng bán]  ──►  [911 XĐKQ]
                ──►  [157 Hàng gửi đi bán]    ──►  [632]  (khi xác nhận bán)

[131 Phải thu KH]  ──►  [511 Doanh thu]       ──►  [911 XĐKQ]
[111/112 Tiền]     ──►  [511 Doanh thu]
                         [3331 Thuế GTGT ĐR]
```
**Giải thích:**
- **Bước 3a – Xuất kho sản phẩm để bán:** Ghi nhận giá vốn ──► **Nợ 632 / Có 155**
- **Bước 3b – Ghi nhận doanh thu:** Bán hàng thu tiền ngay ──► ghi **Nợ 111, 112 / Có 511, 33311**; bán chịu ──► ghi **Nợ 131 / Có 511, 33311**
- **Bước 3c – Chi phí bán hàng & quản lý:** Chi phí bán hàng ──► ghi **Nợ 641 / Có 334, 111, 331…**; Chi phí QLDN ──► ghi **Nợ 642 / Có 334, 111, 331…**

---

### Giai Đoạn 4 · Thu Tiền & Thanh Toán Công Nợ
```
[131 Phải thu KH]  ──►  [111/112 Tiền]  ──►  [331 Phải trả NB]
                                         ──►  [334 Phải trả NLĐ]
                                         ──►  [333 Thuế phải nộp]
                                         ──►  [341 Trả nợ vay]
```
**Giải thích:**
- Thu tiền khách hàng ──► **Nợ 111/112 / Có 131**
- Trả nhà cung cấp ──► **Nợ 331 / Có 111/112**
- Trả lương ──► **Nợ 334 / Có 111/112**
- Nộp thuế GTGT ──► **Nợ 3331 / Có 112** (sau khi bù trừ với 133)
- Nộp thuế TNDN ──► **Nợ 3334 / Có 112**

---

### Giai Đoạn 5 · Xác Định Kết Quả Kinh Doanh & Phân Phối Lợi Nhuận
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
- Cuối kỳ, kết chuyển toàn bộ doanh thu, thu nhập vào **911**: **Nợ 511, 515, 711 / Có 911**
- Kết chuyển toàn bộ chi phí vào **911**: **Nợ 911 / Có 632, 641, 642, 635, 811, 821**
- Nếu có **lãi thuần**: **Nợ 911 / Có 4212**
- Nếu bị **lỗ thuần**: **Nợ 4212 / Có 911**
- Quyết định chia cổ tức từ lãi sau thuế: **Nợ 421 / Có 332** *(Tài khoản 332 mới của TT99)*

---

### Sơ Đồ Tổng Hợp – Toàn Bộ Chu Kỳ Kế Toán Doanh Nghiệp Sản Xuất
```
┌────────────────────────────────────────────────────────────────────────────────────────┐
│                        DÒNG CHẢY KẾ TOÁN DOANH NGHIỆP SẢN XUẤT                         │
│                               (Thông tư 99/2025/TT-BTC)                                │
└────────────────────────────────────────────────────────────────────────────────────────┘

  VỐN / TÀI TRỢ                  CHUẨN BỊ ĐẦU VÀO              SẢN XUẤT
  ─────────────                  ────────────────              ──────────
  411 Vốn CSH      ──►           152 NVL           ──►         621 CP NVL TT  ──┐
  341 Vay NH       ──►  111      153 CCDC          ──►         622 CP NC TT   ──┼──► 154  ──► 155
  331 Phải trả NB  ──►  112      211 TSCĐ          ──►         627 CP SXC     ──┘    dở       SP
                                 214 Hao mòn                                         dang
                                 215 TS Sinh học

  TIÊU THỤ                       DOANH THU / CP                KẾT QUẢ KINH DOANH
  ──────────                     ──────────────                ──────────────────
  155 Sản phẩm     ──►  632      511 Doanh thu     ──►         911 XĐKQ      ──► 4212
  157 Hàng gửi     ──►  GVHB     515 DT Tài chính  ──►  911                  Lãi/Lỗ
  131 Phải thu     ──►  511      711 Thu nhập khác ──►
  111, 112 Tiền    ──►  511      641 CP Bán hàng   ──►         (Nếu Lãi: Nợ 911 / Có 4212)
  3331 Thuế GTGT                 642 CP Quản lý    ──►         (Nếu Lỗ:  Nợ 4212 / Có 911)
                                 635 CP Tài chính  ──►
                                 811 CP Khác       ──►
                                 821 Thuế TNDN     ──►

  PHÂN PHỐI LỢI NHUẬN            NGHĨA VỤ THUẾ & LAO ĐỘNG
  ───────────────────            ────────────────────────
  421 ──► 332 Trả cổ tức         133 Thuế GTGT ĐV  ◄── Bù trừ ──► 33311 Thuế GTGT ĐR
  421 ──► 414 Quỹ ĐTPT           334 Lương         ──► 3383, 3384, 3386 (Bảo hiểm)
                                 3334 Thuế TNDN    ──► 112 (Nộp ngân sách nhà nước)
```

---

## Phần 3 · Bảng Đối Chiếu Điểm Mới Của Thông Tư 99 So Với Thông Tư 200

| Số hiệu TK | Thay đổi | Nội dung thay đổi | Ý nghĩa quản trị & bản chất kế toán |
| :---: | :---: | :--- | :--- |
| **112** | Đổi tên | *Tiền gửi Ngân hàng* ──► **Tiền gửi không kỳ hạn** | Làm rõ bản chất thanh toán không kỳ hạn, phân định rõ ràng với khoản tiền gửi có kỳ hạn đầu tư nắm giữ đến ngày đáo hạn (TK 1281). |
| **128** | Chi tiết hóa | Quy định rõ 1281, 1282, 1283, 1288 | Phân định rành mạch các công cụ tài chính theo mục đích nắm giữ và kỳ hạn sinh lời. |
| **1383** | Thêm mới | **Thuế TTĐB của hàng nhập khẩu** | Tách riêng nghĩa vụ và quyền lợi thuế TTĐB của hàng nhập khẩu được khấu trừ/hoàn lại, tránh nhập nhằng vào TK 1388. |
| **155** | Đổi tên | *Thành phẩm* ──► **Sản phẩm** | Thuật ngữ chuẩn hóa, bỏ tài khoản chi tiết 1551, 1557; bao quát cả sản phẩm hoàn thành dịch vụ và sản phẩm chế tạo vật chất. |
| **158** | Đổi tên | *Hàng hoá kho bảo thuế* ──► **Nguyên liệu, vật tư tại kho bảo thuế** | Chuẩn xác tính chất phục vụ sản xuất hàng xuất khẩu của doanh nghiệp chế xuất, sản xuất gia công quốc tế. |
| **215** | **Bổ sung mới** | **Tài sản sinh học** (2151, 2152, 2153 và cấp 3, 4) | Bổ sung theo tiệm cận chuẩn mực quốc tế **IAS 41 (Nông nghiệp)**, theo dõi riêng súc vật nuôi định kỳ (bò sữa), cây trồng mùa vụ, súc vật lấy thịt. |
| **2295** | **Bổ sung mới** | **Dự phòng tổn thất tài sản sinh học** | Dự phòng tổn thất cho tài sản sinh học khi giá trị thị trường hoặc giá trị thuần thu hồi sụt giảm do dịch bệnh, thời tiết. |
| **2414** | Thêm mới | **Nâng cấp, cải tạo TSCĐ** | Tách bạch giữa sửa chữa bảo dưỡng định kỳ (2413 - tính vào CP trong kỳ) và cải tạo nâng cấp lớn đủ điều kiện vốn hóa tăng nguyên giá (2414). |
| **242** | Đổi tên | *Chi phí trả trước* ──► **Chi phí chờ phân bổ** | Chuẩn hóa thuật ngữ phù hợp với bản chất kinh tế: các chi phí đã phát sinh đang chờ phân bổ dần vào chi phí các kỳ kinh doanh. |
| **244** | Đổi tên | *Cầm cố, thế chấp, ký quỹ, ký cược* ──► **Ký quỹ, ký cược** | Bỏ thuật ngữ cầm cố, thế chấp khỏi tài khoản tài sản này vì cầm cố thế chấp tài sản được thuyết minh riêng theo hợp đồng tín dụng. |
| **332** | **Bổ sung mới** | **Phải trả cổ tức, lợi nhuận** | Trước đây theo dõi trong 3388, nay tách riêng TK 332 giúp minh bạch thông tin tài chính đối với các cổ đông và nhà đầu tư. |
| **3387** | Đổi tên | *Doanh thu chưa thực hiện* ──► **Doanh thu chờ phân bổ** | Thể hiện bản chất dòng tiền nhận trước đang chờ được kết chuyển sang doanh thu theo nguyên tắc dồn tích và phù hợp. |
| **419** | Đổi tên | *Cổ phiếu quỹ* ──► **Cổ phiếu mua lại của chính mình** | Đồng bộ với khái niệm của Luật Doanh nghiệp hiện hành (Luật Doanh nghiệp quy định khi mua lại cổ phiếu phải làm thủ tục giảm vốn điều lệ). |
| **82112** | Thêm mới | **Chi phí thuế TNDN bổ sung theo thuế tối thiểu toàn cầu** | Phục vụ Nghị quyết của Quốc hội về việc áp dụng thuế TNDN bổ sung theo quy định chống xói mòn cơ sở thuế toàn cầu (Pillar 2). |
| **611, 631** | **Loại bỏ** | *TK Mua hàng* và *TK Giá thành sản xuất* | Loại bỏ phương pháp kiểm kê định kỳ phức tạp trong quy trình sản xuất, thống nhất quản trị chi phí theo phương pháp kê khai thường xuyên hiện đại. |
| **417, 441, 461, 466** | **Loại bỏ** | Các quỹ hỗ trợ, nguồn vốn ĐTXDCB, kinh phí sự nghiệp | Bỏ các tài khoản mang tính chất bao cấp/doanh nghiệp nhà nước cũ, tinh giản bộ máy tài chính doanh nghiệp. |

---

## Phần 4 · Hướng Dẫn Vận Hành Cho Doanh Nghiệp Sản Xuất

1. **Chuyển đổi phương pháp hạch toán hàng tồn kho:** Do TT99 đã loại bỏ hoàn toàn TK 611 (Mua hàng) và TK 631 (Giá thành sản xuất), các doanh nghiệp bắt buộc áp dụng phương pháp **Kê khai thường xuyên** thông qua các TK `152, 153, 154, 155, 621, 622, 627, 632`.
2. **Cập nhật danh mục hệ số kho và phần mềm ERP:**
   - Đổi mã và tên gọi: TK 155 thành *Sản phẩm*, TK 242 thành *Chi phí chờ phân bổ*, TK 3387 thành *Doanh thu chờ phân bổ*.
   - Khai báo bổ sung TK 332 (Phải trả cổ tức) để tách độc lập khỏi TK 3388.
   - Doanh nghiệp nông - lâm - thủy sản tiến hành tạo mới phân hệ TK 215 và TK 2295 để quản lý tài sản sinh học.
3. **Phân loại sửa chữa vs nâng cấp TSCĐ:** Rà soát kỹ giữa TK 2413 (Bảo dưỡng thường niên) và TK 2414 (Cải tạo làm tăng công suất, kéo dài thời gian sử dụng hữu ích) để vốn hóa chính xác.

---
*Tài liệu này được biên soạn và chuẩn hóa toàn diện căn cứ theo Thông tư số 99/2025/TT-BTC của Bộ Tài chính và Hệ thống Chuẩn mực Kế toán Việt Nam (VAS).*