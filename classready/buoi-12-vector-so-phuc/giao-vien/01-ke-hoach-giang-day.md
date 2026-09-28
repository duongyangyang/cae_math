# BUỔI 12 — KẾ HOẠCH GIẢNG DẠY

> **Vector và số phức （向量与复数）**
> **Module:** M3 · **Tỉ trọng đề thi:** ~6% · khoảng 2–4 câu
> **Thời lượng:** 90 phút (40 + 10 nghỉ + 40), thực học 80 phút
>
> **Tài liệu này chỉ dành cho giáo viên.** Nội dung lý thuyết và bài tập đã có trong `../hoc-sinh/`, không lặp lại ở đây.

---

## PHÂN BỔ THỜI GIAN

| Hoạt động | Tỉ trọng | Thời lượng |
|:----------|:--------:|:----------:|
| Chữa bài tập buổi 11 | 20% | 16 phút |
| Hệ thống hóa kiến thức trọng tâm | 30% | 24 phút |
| Đi các dạng bài trong chủ đề | 50% | 40 phút |

---

## KHỐI 1 — CHỮA BÀI TẬP BUỔI 11 (16 phút)

### Mục tiêu

Học sinh nhận ra ba lỗi lặp lại nhiều nhất ở nhóm hình học giải tích: đọc sai dạng phương trình đường tròn, quên điều kiện xác định của căn, và nhầm tiêu điểm của elip với tiêu điểm của hyperbol.

### Kịch bản

**Phút 1–6 · Chữa ba câu sai nhiều nhất.** Chọn câu theo bảng đáp án buổi 11. Với mỗi câu, chỉ viết lời giải lên bảng trong 90 giây, phần còn lại dành cho việc chỉ ra **chỗ học sinh chọn sai và vì sao**.

**Phút 7–11 · Ba lỗi hệ thống.** Viết lên góc bảng và để nguyên đến hết buổi:

1. **Nhầm tiêu điểm elip và hyperbol.** Elip dùng $c^2 = a^2 - b^2$, hyperbol dùng $c^2 = a^2 + b^2$. Cách nhớ: hyperbol "cộng thêm" vì nó mở rộng vô hạn.
2. **Quên đổi dấu khi đọc tâm đường tròn.** Từ $x^2 + y^2 - 2ax - 2by + c = 0$, tâm là $(a, b)$ chứ không phải $(-a, -b)$.
3. **Bỏ điều kiện xác định khi bình phương.** Với bất phương trình chứa căn, đặt điều kiện **trước** khi bình phương.

**Phút 12–16 · Chuyển tiếp sang buổi 12.** Nói rõ: chuyên đề hôm nay chỉ chiếm 2–4 câu nhưng là **nhóm câu dễ lấy điểm nhất** trong đề, vì mỗi câu chỉ cần một công thức. Đây là phần học sinh không được phép mất điểm.

### Điểm cần chốt

Kết thúc khối này, học sinh phải trả lời được: **"Elip dùng công thức nào để tìm $c$, hyperbol dùng công thức nào?"**

---

## KHỐI 2 — HỆ THỐNG HÓA KIẾN THỨC TRỌNG TÂM (24 phút)

### Mục tiêu

Học sinh nắm được 10 tính chất trong `../hoc-sinh/02-tai-lieu-buoi-hoc.md` mục 2, đặc biệt là ba công thức dùng nhiều nhất: tích vô hướng theo tọa độ, điều kiện vuông góc và song song, và phép chia số phức.

### Kịch bản

**Phút 1–6 · Từ khóa nhận dạng đề.** Chiếu bảng 12 từ khóa. Với mỗi từ, yêu cầu học sinh đọc to phiên âm rồi nói nghĩa, mục đích là luyện phản xạ nhìn chữ Hán. Dừng lâu hơn ở ba cặp dễ lẫn: 模 và 共轭复数, 纯虚数 và 虚数, 垂直 và 平行.

**Phút 7–13 · Vector.** Trình bày Định nghĩa 1–2 và Tính chất 1–6. Nhấn mạnh hai công thức quyết định:

$$a \perp b \iff x_1x_2 + y_1y_2 = 0; \qquad a \parallel b \iff x_1y_2 - x_2y_1 = 0$$

Viết hai công thức này cạnh nhau trên bảng và khoanh tròn sự khác nhau: một cái **cộng**, một cái **trừ**. Đây là nguồn gốc của phần lớn lỗi sai ở dạng tìm tham số.

Dành 2 phút cho công thức hình chiếu $\dfrac{a \cdot b}{\lvert b \rvert}$ và hỏi cả lớp: "Hình chiếu là số hay vector?" Học sinh phải trả lời được là **số**.

**Phút 14–20 · Số phức.** Trình bày Định nghĩa 3–5 và Tính chất 7–10. Dạy phép chia số phức bằng một câu thần chú duy nhất: **"nhân tử và mẫu với liên hợp của mẫu"**. Không cần chứng minh, chỉ cần thành thạo.

Với Tính chất 8 (chu kì của $i$), yêu cầu học sinh tính nhẩm $i^{2025}$ trong 10 giây. Nếu ai chưa làm được, nhắc lại mẹo chia cho $4$ lấy dư.

**Phút 21–24 · Ba công thức tra nhanh.** Chiếu và yêu cầu học sinh chép vào đầu trang tài liệu:

| Bài toán | Công thức |
|:---------|:----------|
| Môđun số phức | $\lvert a + bi \rvert = \sqrt{a^2 + b^2}$ |
| Điểm cuối của vector | $B = A + \overrightarrow{AB}$ |
| Tọa độ trung điểm | $\left(\dfrac{x_1+x_2}{2}, \dfrac{y_1+y_2}{2}\right)$ |

### Lỗi học sinh hay mắc — cần cảnh báo trước

| Lỗi | Cách cảnh báo |
|:----|:--------------|
| Lẫn công thức vuông góc và song song | Viết hai công thức cạnh nhau, khoanh tròn dấu cộng và dấu trừ |
| Đọc phần ảo là $bi$ thay vì $b$ | Nói rõ: 虚部 là **số thực**, phương án có chữ $i$ là phương án nhiễu |
| Quên điều kiện $b \ne 0$ ở số thuần ảo | Nhắc: $z = 0$ là số thực, không phải số thuần ảo |
| Đảo dấu khi tìm điểm đầu từ điểm cuối | Viết công thức $B = A + \overrightarrow{AB}$ và yêu cầu học sinh chép lại |

---

## KHỐI 3 — ĐI CÁC DẠNG BÀI (40 phút)

### Mục tiêu

Học sinh làm được 8 dạng bài, mỗi dạng nắm được **cách nhận dạng** từ đề, đây mới là đích của khối, không phải thuộc lời giải.

### Kịch bản

Tám dạng bài có trong `../hoc-sinh/02-tai-lieu-buoi-hoc.md` mục 3. Phân bổ 5 phút mỗi dạng theo cấu trúc cố định:

1. **Đọc đề mẫu** (30 giây): giáo viên đọc to đề tiếng Trung, yêu cầu học sinh chỉ ra từ khóa.
2. **Hỏi cách nhận dạng** (30 giây): "Dấu hiệu nào cho biết đây là dạng này?"
3. **Giảng phương pháp** (2 phút): trình bày các bước, không giải chi tiết.
4. **Học sinh làm tại chỗ** (1 phút 30 giây): cho một câu tương tự, học sinh tự làm.
5. **Chữa nhanh** (30 giây): chốt đáp án và lỗi nếu có.

### Thứ tự ưu tiên

Nếu hết thời gian, **không được cắt Dạng 1, 5, 7**. Đây là ba dạng xuất hiện nhiều nhất trong đề thi thật:

| Dạng | Tần suất | Ghi chú |
|:-----|:--------:|:--------|
| **Dạng 1 — Tích vô hướng và góc** | **Cao** | Ưu tiên giữ |
| Dạng 2 — Tham số để vuông góc | Trung bình | Có thể cắt ngắn |
| Dạng 3 — Tham số để song song | Trung bình | Có thể cắt ngắn |
| Dạng 4 — Môđun, hình chiếu, trung điểm | Trung bình | — |
| **Dạng 5 — Phép toán số phức** | **Cao** | Ưu tiên giữ |
| Dạng 6 — Phần thực, phần ảo, liên hợp | Trung bình | — |
| **Dạng 7 — Tham số để thuần ảo** | **Cao** | Ưu tiên giữ |
| Dạng 8 — Môđun và lũy thừa $i$ | Trung bình | Học sinh thường làm nhanh |

### Câu dùng để luyện tại chỗ

| Dạng | Câu luyện | Mã câu |
|:-----|:----------|:-------|
| 1 | `CAE-M-CD7-08.2-M-005` | trong kho đề |
| 2 | `CAE-M-CD7-08.1-M-001` | trong kho đề |
| 3 | Cho $a = (1,2)$, $b = (3,m)$. Tìm $m$ để $a \parallel b$ | tự soạn |
| 4 | `CAE-M-CD7-LX2-E-037` | trong kho đề |
| 5 | `CAE-M-CD7-08.7-M-024` | trong kho đề |
| 6 | `CAE-M-CD7-08.2-H-006` | trong kho đề |
| 7 | `CAE-M-CD7-08.1-H-002` | trong kho đề |
| 8 | `CAE-M-CD7-08.3-H-010` | trong kho đề |

---

## CHỐT BUỔI (5 phút cuối, nằm trong khối 3)

Chốt lại bốn điểm, viết lên góc bảng và để nguyên khi học sinh ra về:

1. **Vuông góc thì cộng, song song thì trừ.**
2. **Chia số phức: nhân tử và mẫu với liên hợp của mẫu.**
3. **Phần ảo là số thực, không kèm $i$.**
4. **Điểm cuối bằng điểm đầu cộng vector.**

Dặn dò: BTVN gồm 25 câu bắt buộc + 15 câu tự chọn, nộp trước buổi 13. Phần tự chọn khó hơn rõ rệt, chỉ làm sau khi xong phần bắt buộc. Nhắc trước: **buổi sau là buổi chữa đề 3**, học sinh cần ôn lại toàn bộ nhóm Hình học và Đại số trước khi vào buổi.

Nói rõ với học sinh về bài kiểm tra cuối chuyên đề: đề 24 câu, 35 phút, phủ bốn buổi 8, 9, 10 và 12. Đây là bài tính điểm, làm nghiêm túc.

---

## ĐÁP ÁN BÀI TẬP CHUẨN BỊ

Dùng để chữa nhanh nếu cần. Lời giải chi tiết có trong `../hoc-sinh/04-dap-an-chuan-bi.md`.

| Câu | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 |
|:----|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:--:|
| Đáp án | B | A | D | B | A | C | A | B | C | B |

**Câu cần chữa kỹ nếu học sinh làm sai nhiều:** Câu 8 và Câu 10.

- **Câu 8** (`CAE-M-CD7-08.6-M-020`): học sinh hay bỏ qua phương án có thành phần bằng $0$ vì tỉ số không xác định. Phải xét riêng.
- **Câu 10** (`CAE-M-CD7-08.2-H-006`): bẫy kinh điển: tính ra $z$ rồi quên đổi dấu phần ảo để lấy liên hợp. Học sinh chọn A thay vì B.

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
