# BUỔI 14 — KẾ HOẠCH GIẢNG DẠY

> **Xác suất （概率）**
> **Module:** M4 · **Tỉ trọng đề thi:** ~3% (cùng thống kê) · khoảng 1–2 câu
> **Thời lượng:** 90 phút (40 + 10 nghỉ + 40), thực học 80 phút
>
> **Tài liệu này chỉ dành cho giáo viên.** Nội dung lý thuyết và bài tập đã có trong `../hoc-sinh/`, không lặp lại ở đây.

---

## PHÂN BỔ THỜI GIAN

| Hoạt động | Tỉ trọng | Thời lượng |
|:----------|:--------:|:----------:|
| Chữa bài tập buổi 13 và bài chuẩn bị | 20% | 16 phút |
| Hệ thống hóa kiến thức trọng tâm | 30% | 24 phút |
| Đi các dạng bài trong chủ đề | 50% | 40 phút |

---

## KHỐI 1 — CHỮA BÀI TẬP VÀ BÀI CHUẨN BỊ (16 phút)

### Mục tiêu

Học sinh nhận ra ba lỗi của buổi trước vẫn còn tồn tại, và nắm được hai câu chuẩn bị hay sai nhất của buổi này trước khi vào bài mới.

### Kịch bản

**Phút 1–8 · Chữa BTVN buổi 13.** Buổi 13 là buổi chữa đề 3, tổng hợp hình học giải tích và đại số. Ba lỗi hay gặp nhất:

| Lỗi | Cách chữa nhanh |
|:----|:----------------|
| Nhầm dấu của tọa độ khi xác định tâm đường tròn từ phương trình tổng quát | Cho ví dụ $x^2 + y^2 - 6x + 8y - 11 = 0$, tâm là $(3, -4)$ chứ không phải $(-3, 4)$ |
| Lấy $\sqrt{b^2}$ làm $c$ khi tìm tiêu điểm elip | Viết lên bảng: $c^2 = a^2 - b^2$, phải bình phương trước khi trừ |
| Quên trường hợp tham số bằng $0$ ở bài tìm điều kiện xác định | Nhắc lại quy tắc của buổi 1: tham số ở hệ số thì luôn xét riêng giá trị $0$ |

**Phút 9–16 · Chữa bài tập chuẩn bị.** Chiếu bảng đáp án, sau đó chữa kỹ hai câu:

- **Câu 9** (`CAE-M-CD8-08.5-H-027`): đề cho 独立 (độc lập) nên nhân hai xác suất để tìm phần giao. Học sinh hay dùng công thức cộng xung khắc và chọn A hoặc D. Nhấn mạnh: 独立 thì **nhân**, 互斥 thì **cộng**, hai từ khóa này ngược nhau hoàn toàn.
- **Câu 10** (`CAE-M-CD8-LX1-M-053`): mẫu số là $4 \times 4 = 16$ chứ không phải $C_4^2 = 6$, vì $m$ và $n$ là hai lựa chọn độc lập. Học sinh hay dùng tổ hợp rồi chọn C.

### Điểm cần chốt

Kết thúc khối này học sinh phải nói được: **“互斥 thì cộng, 独立 thì nhân, 至少 thì lấy 1 trừ.”**

---

## KHỐI 2 — HỆ THỐNG HÓA KIẾN THỨC TRỌNG TÂM (24 phút)

### Mục tiêu

Học sinh nắm được 8 tính chất trong `../hoc-sinh/02-tai-lieu-buoi-hoc.md` mục 2, đặc biệt là ba công thức cộng, nhân và biến cố đối.

### Kịch bản

**Phút 1–6 · Từ khóa nhận dạng đề.** Đây là phần **quan trọng nhất của khối này**, không được cắt. Chiếu bảng 12 từ khóa. Với mỗi từ, yêu cầu học sinh đọc to phiên âm rồi nói nghĩa. Dừng lâu hơn ở ba cặp đối lập:

| Cặp từ khóa | Hướng xử lý ngược nhau |
|:------------|:-----------------------|
| 互斥 (xung khắc) và 相互独立 (độc lập) | Cộng thẳng so với nhân để tìm phần giao |
| 至少 (ít nhất) và 恰好 (đúng) | Đi qua biến cố đối so với đếm trực tiếp |
| 不放回 (không hoàn lại) và 有放回 (có hoàn lại) | Mẫu số giảm dần so với mẫu số giữ nguyên |

**Phút 7–12 · Xác suất cổ điển.** Trình bày Định nghĩa 5 và Tính chất 1. Không giảng lại khái niệm xác suất, học sinh đã biết. Nhấn mạnh công thức cổ điển biến bài toán thành **hai bài toán đếm**, và sai xác suất gần như luôn là sai ở mẫu số.

Dành 2 phút cho Tính chất 1 ($0 \le P(A) \le 1$) và hỏi cả lớp: “Thấy đáp án 1.5 trong bốn phương án thì kết luận được gì?”. Đây là kĩ năng loại đáp án nhiễu không cần tính.

**Phút 13–20 · Ba công thức tính xác suất.** Trình bày Tính chất 2 đến Tính chất 6. **Viết ba công thức lên góc bảng và để nguyên đến hết buổi**:

$$P(\overline{A}) = 1 - P(A), \qquad P(A \cup B) = P(A) + P(B) - P(A \cap B), \qquad P(A \cap B) = P(A) \cdot P(B) \ \text{(độc lập)}$$

Với Tính chất 6 (xác suất có điều kiện), giải thích bằng ví dụ cụ thể thay vì đọc công thức: nếu đã biết em đó thích bóng rổ thì mẫu số không còn là cả lớp mà chỉ là nhóm thích bóng rổ.

**Phút 21–24 · Quy tắc đếm.** Trình bày Tính chất 7 và 8. Nhấn mạnh cách phân biệt chỉnh hợp với tổ hợp: **đổi chỗ hai phần tử đã chọn có cho ra kết quả khác không**. Rút hai quả bóng cùng lúc thì không, dùng $C$. Lấy lần lượt thì có, dùng $A$.

### Lỗi học sinh hay mắc — cần cảnh báo trước

| Lỗi | Cách cảnh báo |
|:----|:--------------|
| Dùng công thức xung khắc cho biến cố độc lập | Viết to chữ 互斥 và 独立 lên bảng, nói rõ: xung khắc thì phần giao bằng $0$, độc lập thì phần giao bằng tích |
| Quên hệ số $C_n^k$ ở công thức Bernoulli | Nói trước: “$k$ lần thành công có thể rơi vào bất kì vị trí nào trong $n$ lần, nên luôn có hệ số đếm vị trí” |
| Chia nhầm mẫu số ở bài xác suất có điều kiện | Khoanh tròn cụm sau chữ 如果 trên đề, nói: “Mẫu số là nhóm này, không phải cả lớp” |
| Lấy $1$ trừ sai biến cố đối | Yêu cầu học sinh viết rõ biến cố đối bằng lời trước khi lấy $1$ trừ |

---

## KHỐI 3 — ĐI CÁC DẠNG BÀI (40 phút)

### Mục tiêu

Học sinh làm được 5 dạng bài, mỗi dạng nắm được **cách nhận dạng** từ đề, đây mới là đích của khối, không phải thuộc lời giải.

### Kịch bản

Năm dạng bài có trong `../hoc-sinh/02-tai-lieu-buoi-hoc.md` mục 3. Phân bổ khoảng 7 phút mỗi dạng theo cấu trúc cố định:

1. **Đọc đề mẫu** (30 giây): giáo viên đọc to đề tiếng Trung, yêu cầu học sinh chỉ ra từ khóa.
2. **Hỏi cách nhận dạng** (30 giây): “Dấu hiệu nào cho biết đây là dạng này?”
3. **Giảng phương pháp** (2 phút): trình bày các bước, không giải chi tiết.
4. **Học sinh làm tại chỗ** (3 phút): cho một câu tương tự, học sinh tự làm.
5. **Chữa nhanh** (1 phút): chốt đáp án và lỗi nếu có.

### Thứ tự ưu tiên

Nếu hết thời gian, **không được cắt Dạng 2, 3, 4**. Đây là ba dạng xuất hiện nhiều nhất trong đề thi thật:

| Dạng | Tần suất | Ghi chú |
|:-----|:--------:|:--------|
| Dạng 1 — Xác suất cổ điển | Trung bình | Có thể cắt ngắn nếu hết giờ |
| **Dạng 2 — Đếm bằng tổ hợp** | **Cao** | Ưu tiên giữ |
| **Dạng 3 — Biến cố đối, ít nhất** | **Cao** | Ưu tiên giữ |
| **Dạng 4 — Cộng, nhân, xác suất có điều kiện** | **Cao** | Ưu tiên giữ |
| Dạng 5 — Công thức Bernoulli | Thấp | Chỉ cần nhận dạng công thức |

### Câu dùng để luyện tại chỗ

| Dạng | Câu luyện | Mã câu |
|:-----|:----------|:-------|
| 1 | Gieo hai xúc xắc, tính xác suất tổng bằng $7$ | tự soạn |
| 2 | `CAE-M-CD8-08.1-H-004` | trong kho đề |
| 3 | `CAE-M-CD8-08.3-H-019` | trong kho đề |
| 4 | `CAE-M-CD8-08.5-H-027` | trong kho đề |
| 5 | `CAE-M-CD8-08.6-H-037` | trong kho đề |

---

## CHỐT BUỔI (5 phút cuối, nằm trong khối 3)

Chốt lại ba điểm, viết lên góc bảng và để nguyên khi học sinh ra về:

1. **互斥 thì cộng, 独立 thì nhân.**
2. **Thấy 至少 thì viết biến cố đối ra trước khi tính.**
3. **Mẫu số là nhóm đứng sau chữ 如果, không phải cả không gian mẫu.**

Dặn dò: BTVN gồm 25 câu bắt buộc + 15 câu tự chọn, nộp trước buổi 15. Buổi 15 học về thống kê; BTVN buổi này đã có 25\% nội dung ôn vector và số phức, 15\% ôn conic.

---

## ĐÁP ÁN BÀI TẬP CHUẨN BỊ

Dùng để chữa nhanh nếu cần. Lời giải chi tiết có trong `../hoc-sinh/04-dap-an-chuan-bi.md`.

| Câu | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 |
|:----|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:--:|
| Đáp án | A | D | A | C | B | C | B | A | C | D |

**Câu cần chữa kỹ nếu học sinh làm sai nhiều:** Câu 9 và Câu 10.

- **Câu 9** (`CAE-M-CD8-08.5-H-027`): lẫn 独立 (độc lập) với 互斥 (xung khắc). Học sinh nhân sai hoặc cộng sai.
- **Câu 10** (`CAE-M-CD8-LX1-M-053`): dùng $C_4^2 = 6$ làm mẫu số thay vì $4 \times 4 = 16$. Đây là bẫy phân biệt “chọn đồng thời” với “hai lựa chọn độc lập”.

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
