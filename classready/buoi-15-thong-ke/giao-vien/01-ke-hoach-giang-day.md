# BUỔI 15 — KẾ HOẠCH GIẢNG DẠY

> **Thống kê （统计）**
> **Module:** M4 · **Tỉ trọng đề thi:** ~3% (cùng xác suất) · khoảng 1–2 câu
> **Thời lượng:** 90 phút (40 + 10 nghỉ + 40), thực học 80 phút
>
> **Tài liệu này chỉ dành cho giáo viên.** Nội dung lý thuyết và bài tập đã có trong `../hoc-sinh/`, không lặp lại ở đây.

---

## PHÂN BỔ THỜI GIAN

| Hoạt động | Tỉ trọng | Thời lượng |
|:----------|:--------:|:----------:|
| Chữa bài tập buổi 14 (xác suất) | 15% | 12 phút |
| Hệ thống hóa kiến thức trọng tâm | 30% | 24 phút |
| Đi các dạng bài trong chủ đề | 45% | 36 phút |
| Chốt buổi và giao bài | 10% | 8 phút |

Buổi 15 là buổi cuối của chuyên đề Xác suất và Thống kê, đồng thời là buổi trước kỳ kiểm tra cuối chuyên đề. Mười hai phút đầu dùng để chữa nhanh BTVN buổi 14, tập trung vào nhóm bài toán dùng biến cố đối.

---

## KHỐI 1 — CHỮA BÀI TẬP BUỔI 14 (12 phút)

### Mục tiêu

Học sinh nhớ lại hai kỹ thuật chủ lực của buổi trước trước khi bước sang phần thống kê: dùng tổ hợp để đếm kết quả thuận lợi, và dùng biến cố đối cho bài toán "ít nhất".

### Kịch bản

**Phút 1–6 · Chữa hai câu học sinh sai nhiều nhất.** Chọn câu theo bảng đáp án `../hoc-sinh/05-dap-an-bai-tap-ve-nha.md` của buổi 14 và thống kê bài nộp. Hai lỗi hay gặp nhất là quên trừ phần giao khi hai biến cố không xung khắc, và nhầm giữa "xác suất có ít nhất một" với tích các xác suất.

**Phút 7–10 · Chốt hai công thức.** Viết lên bảng và để nguyên đến hết buổi:

$$P(A \cup B) = P(A) + P(B) - P(A \cap B)$$

$$P(\text{ít nhất một}) = 1 - P(\text{không có phần tử nào})$$

**Phút 11–12 · Cầu nối sang thống kê.** Nêu ngắn: xác suất trả lời câu hỏi "khả năng xảy ra là bao nhiêu", còn thống kê trả lời câu hỏi "bộ dữ liệu này nói lên điều gì". Hai phần dùng chung một nhóm câu cuối đề.

---

## KHỐI 2 — HỆ THỐNG HÓA KIẾN THỨC TRỌNG TÂM (24 phút)

### Mục tiêu

Học sinh nắm được tám định nghĩa và sáu tính chất trong `../hoc-sinh/02-tai-lieu-buoi-hoc.md` mục 2, đặc biệt là công thức trung bình có trọng số, quy trình tính phương sai, và quy tắc thực nghiệm $68$–$95$–$99,7$.

### Kịch bản

**Phút 1–6 · Từ khóa nhận dạng đề.** Đây là phần **quan trọng nhất của khối này**, không được cắt. Chiếu bảng 14 từ khóa. Với mỗi từ, yêu cầu học sinh đọc to phiên âm rồi nói nghĩa, mục đích là luyện phản xạ nhìn chữ Hán. Dừng lâu hơn ở cặp 中位数 / 众数 vì hai từ cùng bắt đầu bằng chữ 数 và rất dễ lẫn.

**Phút 7–12 · Các số đặc trưng.** Trình bày Định nghĩa 1–7. Nhấn mạnh hai điểm:

- Công thức trung bình có trọng số là công thức dùng nhiều nhất trong chuyên đề. Đề cho bảng hai cột thì bắt buộc dùng công thức này.
- Điều kiện bắt buộc trước khi tìm trung vị là **phải sắp xếp dãy**. Đề rất hay cho dữ liệu xáo trộn.

Với phương sai, viết quy trình ba bước lên bảng: tính trung bình, bình phương từng độ lệch, chia cho $n$. Yêu cầu cả lớp nhắc lại quy trình trước khi chuyển sang phần sau.

**Phút 13–17 · Tính chất biến đổi dữ liệu.** Trình bày Tính chất 1 và Tính chất 2. Đây là nguồn của cả một dạng bài trong đề thi nên phải chốt bằng câu dễ nhớ: **cộng thêm thì phương sai không đổi, nhân lên thì phương sai nhân bình phương**.

Hỏi cả lớp: "Nếu mỗi học sinh được cộng thêm $5$ điểm thì phương sai thay đổi thế nào?" Nếu lớp trả lời sai, giải thích bằng trục số: phép cộng dịch cả dãy sang phải, khoảng cách giữa các điểm không đổi.

**Phút 18–24 · Phân phối chuẩn.** Trình bày Định nghĩa 8, Tính chất 5 và Tính chất 6. **Vẽ đường cong chuông lên bảng và để nguyên đến hết buổi**, đánh dấu ba khoảng $\mu \pm \sigma$, $\mu \pm 2\sigma$, $\mu \pm 3\sigma$ cùng các tỉ lệ $68\%$, $95\%$, $99,7\%$.

Nhấn mạnh Tính chất 6 (đối xứng): đây là chìa khóa xử lý nhóm câu phân phối chuẩn mà không cần tra bảng. Lấy ví dụ ngay: $\mu = 2$, cho $P(X < 1,9) = 0,1$, hỏi $P(X < 2,1)$. Vì $1,9$ và $2,1$ đối xứng qua $\mu$ nên đáp án là $1 - 0,1 = 0,9$.

### Lỗi học sinh hay mắc — cần cảnh báo trước

| Lỗi | Cách cảnh báo |
|:----|:--------------|
| Lấy trung bình cộng của các giá trị trong bảng, bỏ qua cột tần số | Nói trước: "Bảng có cột số người thì phải nhân rồi mới chia" |
| Tìm trung vị trên dãy chưa sắp xếp | Yêu cầu học sinh viết chữ "sắp xếp" lên đầu bài làm trước khi tính |
| Nhầm 中位数 (trung vị) với 众数 (mốt) | Viết to hai chữ lên bảng, chỉ rõ: trung vị là giá trị **đứng giữa**, mốt là giá trị **xuất hiện nhiều nhất** |
| Quên chia đôi phần đuôi khi tính tỉ lệ ngoài khoảng $\mu \pm k\sigma$ | Vẽ hai đuôi đối xứng trên đường cong, nói: "Ngoài khoảng thì chia hai, một bên chỉ lấy một nửa" |
| Nghĩ rằng cộng thêm điểm làm phương sai thay đổi | Dùng trục số minh họa phép dịch chuyển |

---

## KHỐI 3 — ĐI CÁC DẠNG BÀI (36 phút)

### Mục tiêu

Học sinh làm được 6 dạng bài, mỗi dạng nắm được **cách nhận dạng** từ đề, đây mới là đích của khối, không phải thuộc lời giải.

### Kịch bản

Sáu dạng bài có trong `../hoc-sinh/02-tai-lieu-buoi-hoc.md` mục 3. Phân bổ khoảng 6 phút mỗi dạng theo cấu trúc cố định:

1. **Đọc đề mẫu** (30 giây): giáo viên đọc to đề tiếng Trung, yêu cầu học sinh chỉ ra từ khóa.
2. **Hỏi cách nhận dạng** (30 giây): "Dấu hiệu nào cho biết đây là dạng này?"
3. **Giảng phương pháp** (2 phút): trình bày các bước, không giải chi tiết.
4. **Học sinh làm tại chỗ** (2 phút): cho một câu tương tự, học sinh tự làm.
5. **Chữa nhanh** (1 phút): chốt đáp án và lỗi nếu có.

### Thứ tự ưu tiên

Nếu hết thời gian, **không được cắt Dạng 1, 2, 5**. Đây là ba dạng xuất hiện nhiều nhất trong đề thi thật:

| Dạng | Tần suất | Ghi chú |
|:-----|:--------:|:--------|
| **Dạng 1 — Trung bình, trung vị, mốt** | **Cao** | Ưu tiên giữ |
| **Dạng 2 — Phương sai, độ lệch chuẩn** | **Cao** | Ưu tiên giữ |
| Dạng 3 — Biến đổi dữ liệu | Trung bình | Có thể cắt ngắn nếu hết giờ |
| Dạng 4 — Bảng phân phối tần số | Trung bình | Học sinh thường làm nhanh |
| **Dạng 5 — Quy tắc thực nghiệm** | **Cao** | Ưu tiên giữ |
| Dạng 6 — So sánh độ phân tán | Trung bình | Có thể cắt ngắn nếu hết giờ |

### Câu dùng để luyện tại chỗ

| Dạng | Câu luyện | Mã câu |
|:-----|:----------|:-------|
| 1 | Bảng chiều cao 10 học sinh, tìm trung bình và trung vị | tự soạn |
| 2 | Dãy $7, 8, 10, 12, 13$, tìm phương sai | tự soạn |
| 3 | Trung bình $80$, phương sai $25$, cộng thêm $5$ điểm | tự soạn |
| 4 | `CAE-M-CD9-08.3-H-008` | trong kho đề |
| 5 | `CAE-M-CD9-LX1-M-029` | trong kho đề |
| 6 | `CAE-M-CD9-08.4-H-010` | trong kho đề |

---

## KHỐI 4 — CHỐT BUỔI VÀ GIAO BÀI (8 phút)

Chốt lại ba điểm, viết lên góc bảng và để nguyên khi học sinh ra về:

1. **Bảng có cột tần số thì dùng trung bình có trọng số.**
2. **Tìm trung vị phải sắp xếp dãy trước.**
3. **Cộng thêm không đổi phương sai, nhân lên thì phương sai nhân bình phương.**

Dặn dò: BTVN gồm 25 câu bắt buộc + 15 câu tự chọn, nộp trước buổi 16. Phần bắt buộc có 13 câu thống kê, 6 câu xác suất, 4 câu vector và số phức, 2 câu ôn tập tích lũy.

**Thông báo kiểm tra.** Buổi sau là buổi chữa đề, nhưng trước đó học sinh phải làm **đề kiểm tra cuối chuyên đề Xác suất và Thống kê** trong `../hoc-sinh/06-de-kiem-tra.md`: 24 câu, 35 phút, không dùng máy tính, phủ cả buổi 14 và buổi 15. Nhắc học sinh tự bấm giờ khi làm.

---

## ĐÁP ÁN BÀI TẬP CHUẨN BỊ

Dùng để chữa nhanh nếu cần. Lời giải chi tiết có trong `../hoc-sinh/04-dap-an-chuan-bi.md`.

| Câu | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 |
|:----|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:--:|
| Đáp án | B | C | C | B | A | C | B | C | A | D |

**Câu cần chữa kỹ nếu học sinh làm sai nhiều:** Câu 5, Câu 6 và Câu 9.

- **Câu 5** (`CAE-M-CD9-LX1-E-026`): học sinh hay quên bình phương độ lệch, chỉ cộng độ lệch nên ra phương sai bằng $0$.
- **Câu 6** (`CAE-M-CD9-08.4-H-012`): bẫy bỏ qua cột số người, lấy trung bình cộng của năm giá trị chiều cao.
- **Câu 9** (`CAE-M-CD9-LX2-E-032`): quên chia đôi phần đuôi, chọn đáp án $1,35\%$ thay vì $0,135\%$.

---

## GHI CHÚ SAU BUỔI HỌC

*(Điền sau khi dạy xong, dùng để điều chỉnh buổi sau và các buổi lặp lại.)*

| Nội dung | Ghi nhận |
|:---------|:---------|
| Thời gian thực tế từng khối | |
| Dạng bài học sinh yếu nhất | |
| Câu hỏi học sinh hỏi nhiều | |
| Điều chỉnh cho lần dạy sau | |

---

*Tài liệu nội bộ, CAE SHANGHAI.*
