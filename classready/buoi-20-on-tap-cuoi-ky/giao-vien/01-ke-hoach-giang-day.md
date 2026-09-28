# BUỔI 20 — KẾ HOẠCH GIẢNG DẠY

> **Hệ thống hóa toàn chương trình （总复习）**
> **Thời lượng:** 90 phút (40 + 10 nghỉ + 40), thực học 80 phút
>
> **Tài liệu này chỉ dành cho giáo viên.** Nội dung công thức và đề luyện đã có trong `../hoc-sinh/`, không lặp lại ở đây.

---

## MỤC TIÊU BUỔI HỌC

Học sinh rời buổi học với ba thứ: một bảng công thức đã tra lại và đánh dấu chỗ còn yếu, một danh sách lỗi cá nhân đã phân loại theo nhóm nội dung, và một kết quả đề luyện 20 câu có số đo thời gian từng câu.

Đây là buổi ôn tập, không có kiến thức mới. Giá trị của buổi nằm ở chỗ học sinh tự phát hiện nhóm nội dung nào mình còn hổng, chứ không nằm ở việc giáo viên giảng lại.

---

## PHÂN BỔ THỜI GIAN

| Hoạt động | Tỉ trọng | Thời lượng |
|:----------|:--------:|:----------:|
| Chữa bảng từ khóa và rà soát câu sai | 15\% | 12 phút |
| Hệ thống công thức 11 nhóm | 22\% | 18 phút |
| Dạng bài trọng tâm và lỗi thường gặp | 12\% | 10 phút |
| Đề luyện 20 câu có bấm giờ | 38\% | 30 phút |
| Chữa đề và chiến lược thi cuối kỳ | 13\% | 10 phút |

---

## KHỐI 1 — CHỮA BẢNG TỪ KHÓA VÀ RÀ SOÁT CÂU SAI (12 phút)

### Mục tiêu

Học sinh biết chính xác nhóm nội dung nào mình còn yếu, dựa trên số liệu của chính mình chứ không dựa trên cảm giác.

### Kịch bản

**Phút 1–5 · Chữa nhanh bảng từ khóa.** Đọc to từng từ khóa trong `../hoc-sinh/01-chuan-bi-bai.md`, học sinh đối chiếu cột Nghĩa đã điền. Không đi tuần tự 106 từ. Chỉ dừng ở những từ mà học sinh điền sai hoặc để trống, và ở bốn cặp từ dễ nhầm:

| Cặp từ khóa | Khác nhau ở đâu |
|:------------|:----------------|
| 恒成立 và 有解 | 恒成立 dùng điều kiện $\Delta$; 有解 so sánh với giá trị lớn nhất hoặc nhỏ nhất |
| 子集 và 真子集 | Có chữ 真 thì trừ $1$ |
| 互斥 và 相互独立 | Xung khắc cộng xác suất, độc lập nhân xác suất |
| 最大值 và 最小值 | 最大值 lấy biên trên của tập giá trị, 最小值 lấy biên dưới |

**Phút 6–12 · Phân loại bảng rà soát câu sai.** Yêu cầu học sinh đếm số dòng theo từng nhóm trong bảng ở Phần C và ghi bốn con số lên bảng theo cột. Cả lớp nhìn thấy ngay nhóm nào có nhiều lỗi nhất.

Chọn hai đến ba câu sai tiêu biểu, mỗi câu xử lý theo ba bước:

1. Hỏi: "Lúc làm câu này em đọc từ khóa nào trong đề?"
2. Chỉ ra từ khóa đúng đáng lẽ phải nhận ra.
3. Chốt cách xử lý trong 20 giây.

### Điểm cần chốt

Không phải mọi câu sai đều do thiếu kiến thức. Phần lớn câu sai đến từ ba nguyên nhân: đọc sai từ khóa, hết thời gian, hoặc bỏ qua một trường hợp đặc biệt. Ba nguyên nhân này có ba cách chữa khác nhau, nên phải phân loại trước khi chữa.

---

## KHỐI 2 — HỆ THỐNG CÔNG THỨC 11 NHÓM (18 phút)

### Mục tiêu

Học sinh tra lại được công thức của cả chương trình trong một tài liệu duy nhất, và đánh dấu được những công thức mình chưa nhớ.

### Kịch bản

Chiếu bảng công thức ở mục 1 của `../hoc-sinh/02-tai-lieu-buoi-hoc.md`. Phân bổ thời gian theo tỉ trọng đề thi, **không chia đều cho 11 nhóm**:

| Nhóm | Tỉ trọng đề thi | Thời gian |
|:-----|:---------------:|:---------:|
| 4 và 5 — Lượng giác | ~20\% | 5 phút |
| 7, 8, 9 — Hình học và conic | ~19\% | 4 phút |
| 2 và 3 — Hàm số | ~21\% | 3 phút |
| 6 — Dãy số | ~13\% | 2 phút |
| 1 — Tập hợp và bất đẳng thức | ~10\% | 2 phút |
| 10 — Vector và số phức | ~6\% | 1 phút |
| 11 — Xác suất và thống kê | ~3\% | 1 phút |

**Cách làm.** Với mỗi nhóm, đọc to tên công thức rồi yêu cầu học sinh nói nội dung trước khi chiếu đáp án. Công thức nào cả lớp im lặng thì đánh dấu và dành thêm 20 giây.

**Ba công thức phải chốt bằng được.** Ba công thức này xuất hiện ở nhiều nhóm khác nhau và hay bị nhớ sai:

1. **Chu kỳ hàm lượng giác.** $T = \dfrac{2\pi}{\lvert \omega \rvert}$, chia cho hệ số của $x$ chứ không phải nhân. Học sinh hay chọn $2\pi\omega$.
2. **Tiệm cận hyperbol.** $y = \pm\dfrac{b}{a}x$. Phương án đảo thành $\dfrac{a}{b}$ là bẫy phổ biến nhất của nhóm 9.
3. **Quy tắc ít nhất.** Từ khóa 至少 dùng biến cố đối: $1 - P(\text{không lần nào})$. Học sinh hay cộng xác suất từng trường hợp và tính sai.

### Lỗi học sinh hay mắc — cần cảnh báo trước

| Lỗi | Cách cảnh báo |
|:----|:--------------|
| Nhầm $T = \dfrac{2\pi}{\omega}$ với $T = 2\pi\omega$ | Viết to $\omega$ dưới mẫu lên bảng và để nguyên đến hết buổi |
| Nhầm $a^2 = b^2 + c^2$ của elip với $c^2 = a^2 + b^2$ của hyperbol | Nói rõ: elip thì trừ, hyperbol thì cộng |
| Nhầm dấu của $\cos(a+b)$ | $\cos$ đổi dấu, $\sin$ giữ dấu |
| Quên rằng nghiệm của mẫu luôn bị loại | Vẽ dấu ngoặc tròn ở nghiệm của mẫu trên trục số |

---

## KHỐI 3 — DẠNG BÀI TRỌNG TÂM VÀ LỖI THƯỜNG GẶP (10 phút)

### Mục tiêu

Học sinh nhận ra dạng bài trong vài giây đầu mà không cần dịch cả đề.

### Kịch bản

**Phút 1–6 · Mười lăm dạng bài.** Chiếu bảng dạng bài ở mục 2 của `../hoc-sinh/02-tai-lieu-buoi-hoc.md`. Không giảng lại cách giải từng dạng, học sinh đã học ở các buổi trước. Chỉ luyện phản xạ nhận dạng: đọc dấu hiệu, yêu cầu cả lớp nói to tên dạng.

Dừng lâu hơn ở bốn dạng xuất hiện nhiều nhất trong đề thi thật: **dạng 3** (tham số và điều kiện tập con), **dạng 8** (đơn điệu, cực trị, tiếp tuyến), **dạng 10** (hàm lượng giác và phương trình), **dạng 11** (cấp số cộng và cấp số nhân).

**Phút 7–10 · Bảng lỗi thường gặp.** Chiếu bảng lỗi ở mục 3. Yêu cầu học sinh tự đánh dấu những lỗi mình đã từng mắc trong bảng rà soát ở Phần C. Mục đích là để học sinh thấy lỗi của mình nằm trong danh sách lỗi chung, không phải lỗi riêng khó chữa.

### Thứ tự ưu tiên

Nếu hết thời gian, **không được cắt bốn dạng nêu trên**. Đây là bốn dạng chiếm tỉ trọng lớn nhất trong đề thi thật.

---

## KHỐI 4 — ĐỀ LUYỆN 20 CÂU CÓ BẤM GIỜ (30 phút)

### Mục tiêu

Học sinh áp dụng được bảng công thức và bảng lỗi trong điều kiện bấm giờ thật.

### Kịch bản

**Phút 1–2 · Phát đề.** Phát `../hoc-sinh/03-de-luyen-bam-gio.md`. Yêu cầu học sinh ghi giờ vào bảng cuối đề trong lúc làm, không ghi sau. Nhắc lại ngưỡng 90 giây: quá ngưỡng thì đánh dấu và chuyển câu.

**Phút 3–32 · Làm bài.** 30 phút cho 20 câu, tương ứng 90 giây mỗi câu, đúng bằng nhịp đề thi thật. Trong lúc học sinh làm, giáo viên đi quanh lớp và ghi lại ba hành vi:

- Học sinh dừng quá 90 giây ở một câu mà không chuyển.
- Học sinh giải đầy đủ thay vì thay đáp án vào đề.
- Học sinh để trống câu không làm được.

**Phút 33–40 · Chữa nhanh.** Đọc bảng đáp án, sau đó chữa bốn câu theo bốn nhóm nội dung khác nhau, mỗi câu một kỹ thuật:

| Câu | Nhóm nội dung | Điểm cần nói |
|:---:|:--------------|:-------------|
| 1 | Tập hợp | 列举法: thay $n = 0, 1, 2, 3$ lần lượt, chú ý $\mathbb{N}$ chứa $0$ |
| 6 | Bất đẳng thức | 1 trên giá trị tuyệt đối: lấy nghịch đảo đổi chiều, nghiệm của mẫu bị loại |
| 15 | Lượng giác | Gộp $a\sin x + b\cos x$: biên trên là $\sqrt{a^2 + b^2}$, đáp án trong 10 giây |
| 17 | Hình học không gian | $MN$ là đường kính thì tâm là trung điểm, bán kính bằng nửa độ dài $MN$ |

---

## ĐÁP ÁN ĐỀ LUYỆN 20 CÂU

### Bảng đáp án

| Câu | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 |
|:----|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:--:|
| Đáp án | C | A | A | B | A | D | B | B | D | C |

| Câu | 11 | 12 | 13 | 14 | 15 | 16 | 17 | 18 | 19 | 20 |
|:----|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| Đáp án | C | B | A | C | D | A | D | B | C | D |

Phân bố: A 5 câu, B 5 câu, C 5 câu, D 5 câu.

### Lời giải ngắn

**Câu 1 — Đáp án C.** (`CAE-M-CD1-08.4-E-014`) Thay $n = 0, 1, 2, 3$ vào $n^2 - 1$ được $-1, 0, 3, 8$. Chú ý $\mathbb{N}$ chứa $0$ nên $n = 0$ là giá trị hợp lệ.

**Câu 2 — Đáp án A.** (tự soạn) $\log_2 12 - \log_2 3 = \log_2 \dfrac{12}{3} = \log_2 4 = 2$.

**Câu 3 — Đáp án A.** (`CAE-M-CD7-08.3-M-007`) $a \times b = (2 \cdot 3 - (-1)(-1),\ (-1) \cdot 2 - 1 \cdot 3,\ 1 \cdot (-1) - 2 \cdot 2) = (5, -5, -5)$.

**Câu 4 — Đáp án B.** (tự soạn) Căn bậc hai cần $x - 2 \ge 0$; logarit cần $5 - x > 0$. Giao lại được $2 \le x < 5$.

**Câu 5 — Đáp án A.** (tự soạn) $a_{10} = a_1 + 9d = 3 + 9 \cdot 2 = 21$.

**Câu 6 — Đáp án D.** (`CAE-M-CD2-08.5-E-034`) $\dfrac{1}{\lvert 2x-1 \rvert} \ge 1 \iff 0 < \lvert 2x-1 \rvert \le 1$. Giải được $0 \le x \le 1$ và $x \ne \dfrac{1}{2}$. Nghiệm của mẫu bị loại nên hai đầu mút $\dfrac{1}{2}$ mở.

**Câu 7 — Đáp án B.** (tự soạn) $T = \dfrac{2\pi}{\lvert \omega \rvert} = \dfrac{2\pi}{3}$. Phương án A là kết quả của việc chia nhầm cho $2\omega$.

**Câu 8 — Đáp án B.** (`CAE-M-CD5-LX3-E-059`) $M$ là trung điểm $BC$ nên $M(3, 1, 2)$. Khoảng cách $AM$ bằng $\sqrt{4 + 1 + 4} = 3$.

**Câu 9 — Đáp án D.** (tự soạn) $y' = 3x^2 - 3$, thay $x = 1$ được $3 - 3 = 0$. Hệ số góc tiếp tuyến bằng $0$, tức tiếp tuyến nằm ngang.

**Câu 10 — Đáp án C.** (`CAE-M-CD7-08.7-M-024`) $z_1 = (2+3i)(1+i) = 2 + 2i + 3i + 3i^2 = -1 + 5i$. Cộng $z_2 = 1 - i$ được $4i$.

**Câu 11 — Đáp án C.** (tự soạn) Đây là công thức cộng đảo của $\sin$: $\sin 75^\circ\cos 15^\circ - \cos 75^\circ\sin 15^\circ = \sin(75^\circ - 15^\circ) = \sin 60^\circ = \dfrac{\sqrt{3}}{2}$.

**Câu 12 — Đáp án B.** (tự soạn) $y^2 = 8x$ có $2p = 8$, tức $p = 4$. Đường chuẩn là $x = -\dfrac{p}{2} = -2$.

**Câu 13 — Đáp án A.** (`CAE-M-CD2-08.6-E-036`) Với $a \ne 0$ thì $a^2 > 0$ với mọi $a$. Đáp án D sai vì điều kiện $a \ne 0$ loại trường hợp $a^2 = 0$.

**Câu 14 — Đáp án C.** (tự soạn) $a_4 = a_1q^3 = 3 \cdot 2^3 = 24$.

**Câu 15 — Đáp án D.** (tự soạn) $y = 3\sin x - 4\cos x$ có biên trên $\sqrt{3^2 + 4^2} = 5$. Đây là công thức cho đáp án trong 10 giây, không cần biến đổi.

**Câu 16 — Đáp án A.** (tự soạn) Phương trình $y = 2(x - 1) + 2 = 2x$. Thay $x = 1$ được $y = 2$, khớp với điểm đã cho.

**Câu 17 — Đáp án D.** (`CAE-M-CD5-08.8-H-044`) Trung điểm $MN$ là $(1, 2, 1)$; $\lvert MN \rvert = \sqrt{4^2 + 8^2 + 8^2} = 12$ nên bán kính bằng $6$. Phương trình $(x-1)^2 + (y-2)^2 + (z-1)^2 = 36$.

**Câu 18 — Đáp án B.** (tự soạn) $\cos^2\alpha = 1 - \sin^2\alpha = 1 - \dfrac{9}{25} = \dfrac{16}{25}$ nên $\cos\alpha = \pm\dfrac{4}{5}$. Vì $\alpha$ thuộc phần tư thứ hai, $\cos\alpha < 0$, chọn $-\dfrac{4}{5}$.

**Câu 19 — Đáp án C.** (`CAE-M-CD9-08.6-H-017`) Tổng bằng $280$, chia cho $7$ được $40$.

**Câu 20 — Đáp án D.** (tự soạn) Viết lại $(x-2)^2 + (y+1)^2 = 9$ nên tâm $(2, -1)$ và bán kính $\sqrt{9} = 3$.

### Câu cần chữa kỹ nếu học sinh làm sai nhiều

- **Câu 1**: quên rằng $\mathbb{N}$ chứa $0$, chỉ thay $n = 1, 2, 3$ và chọn D.
- **Câu 6**: lấy luôn $x = \dfrac{1}{2}$ nên chọn C thay vì D. Lỗi kinh điển của bất phương trình thương.
- **Câu 7**: nhân thay vì chia cho $\omega$, chọn C.
- **Câu 18**: quên dấu theo phần tư, chọn A.
- **Câu 20**: quên đổi dấu khi đọc tâm, tính nhầm bán kính.

---

## KHỐI 5 — CHIẾN LƯỢC THI CUỐI KỲ (10 phút)

### Mục tiêu

Học sinh rời buổi học với một kế hoạch cụ thể cho kỳ thi cuối kỳ, không phải một lời khuyên chung.

### Kịch bản

**Phút 1–4 · Ba vòng làm bài.** Chiếu bảng phân bổ thời gian ở mục 4 của `../hoc-sinh/02-tai-lieu-buoi-hoc.md`. Vẽ bảng ba vòng lên bảng: 30 phút cho vòng 1, 20 phút cho vòng 2, 10 phút cho vòng 3. Nhấn mạnh khoản tô đáp án 3 đến 4 phút phải nằm trong vòng 3.

**Phút 5–7 · Ba nguyên tắc bắt buộc.** Viết lên góc bảng và để nguyên đến khi học sinh ra về:

1. **90 giây không có hướng thì chuyển câu.**
2. **Không bao giờ để trống một câu.**
3. **Làm hết câu dễ trước, không kiểm tra lại câu đã chắc.**

**Phút 8–10 · Giữ tâm lý ổn định.** Trình bày mục 5 của `../hoc-sinh/02-tai-lieu-buoi-hoc.md`. Ba điểm cần nói rõ:

- Không học công thức mới trong 24 giờ cuối, chỉ đọc lại bảng công thức và bảng lỗi.
- Mười phút đầu đọc lướt toàn bộ đề và bắt đầu từ câu nhận ra dạng ngay, không làm theo thứ tự từ câu 1.
- Không so đáp án với bạn ngay sau giờ thi.

### Điểm cần chốt

Kết thúc buổi học, học sinh phải trả lời được: **"Trong 60 phút, em dành bao nhiêu phút cho vòng 1?"** Nếu cả lớp không trả lời được, nhắc lại con số 30 phút.

---

## DẶN DÒ CUỐI BUỔI

Buổi 20 không giao bài tập về nhà. Kiểm tra cuối kỳ được tổ chức trực tuyến trên hệ thống sau buổi này, chiếm 40\% điểm của khóa học.

Ba việc học sinh cần làm trước ngày thi:

1. Đọc lại bảng công thức ở mục 1 của `../hoc-sinh/02-tai-lieu-buoi-hoc.md` mỗi ngày một lần, không học thêm công thức mới.
2. Đọc lại bảng lỗi ở mục 3 và tự kiểm tra xem còn lỗi nào chưa sửa được.
3. Làm lại một đề tổng hợp 48 câu trong 60 phút, áp dụng đúng ba vòng và ngưỡng 90 giây.

---

## GHI CHÚ SAU BUỔI HỌC

*(Điền sau khi dạy xong, dùng để điều chỉnh cho các khóa sau.)*

| Nội dung | Ghi nhận |
|:---------|:---------|
| Thời gian thực tế từng khối | |
| Nhóm nội dung học sinh yếu nhất | |
| Câu trong đề luyện bị sai nhiều nhất | |
| Số câu trung bình làm được trong 30 phút | |
| Điều chỉnh cho lần dạy sau | |

---

*Tài liệu nội bộ, CAE SHANGHAI.*
