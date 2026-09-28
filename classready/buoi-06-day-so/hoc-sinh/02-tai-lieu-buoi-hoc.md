# BUỔI 6 — DÃY SỐ （数列）

> **Module:** M2 · **Tỉ trọng đề thi:** ~13% · khoảng 5–8 câu
> **Tài liệu học tập, dùng trên lớp và tra cứu khi làm bài**

---

## 1. TỪ KHÓA NHẬN DẠNG ĐỀ

Đọc được từ khóa là xác định được dạng bài mà không cần dịch cả đề. Bảng dưới đây gom những từ khóa quyết định của chuyên đề này.

| Từ khóa | Nghĩa | Dạng bài tương ứng |
|:--------|:------|:-------------------|
| 等差数列 | cấp số cộng | Xác định $a_1$, $d$, tính $a_n$ hoặc $S_n$ |
| 等比数列 | cấp số nhân | Xác định $a_1$, $q$, tính $a_n$ hoặc $S_n$ |
| 公差 | công sai | Hiệu hai số hạng liên tiếp $d = a_{n+1} - a_n$ |
| 公比 | công bội | Tỉ hai số hạng liên tiếp $q = \dfrac{a_{n+1}}{a_n}$ |
| 首项 | số hạng đầu | Giá trị $a_1$ |
| 通项公式 | công thức số hạng tổng quát | Biểu thức của $a_n$ theo $n$ |
| 前n项和 | tổng $n$ số hạng đầu | Tính $S_n$ |
| 递推公式 | công thức truy hồi | Tính lần lượt từng số hạng |
| 无穷等比数列 | cấp số nhân lùi vô hạn | Điều kiện $\lvert q \rvert < 1$ và tổng vô hạn |
| 各项之和 | tổng các số hạng | Tính $S$ của cấp số nhân lùi vô hạn |
| 等差中项 | trung bình cộng | Ba số lập thành cấp số cộng |
| 等比中项 | trung bình nhân | Ba số lập thành cấp số nhân |
| 递增数列 | dãy số tăng | Xét dấu của $d$ hoặc $q$ |
| 斐波那契数列 | dãy Fibonacci | Nhận dạng dãy $1, 1, 2, 3, 5, 8, \ldots$ |

**Chú ý.** Hai cặp từ khóa quyết định cách xử lý là 等差数列 / 等比数列 và 公差 / 公比. Cấp số cộng dùng **phép trừ** để tìm công sai, cấp số nhân dùng **phép chia** để tìm công bội. Đọc nhầm loại cấp số là mất điểm ngay từ bước đầu.

---

## 2. KIẾN THỨC TRỌNG TÂM

### 2.1. Cấp số cộng

**Định nghĩa 1 — Cấp số cộng.** Dãy số $\{a_n\}$ là *cấp số cộng* khi kể từ số hạng thứ hai, mỗi số hạng bằng số hạng đứng ngay trước nó cộng với một hằng số $d$ không đổi:

$$a_{n+1} = a_n + d$$

Hằng số $d$ gọi là *công sai*.

**Tính chất 1 — Số hạng tổng quát.** Với cấp số cộng có số hạng đầu $a_1$ và công sai $d$:

$$a_n = a_1 + (n - 1)d$$

**Tính chất 2 — Tổng $n$ số hạng đầu.** Hai dạng tương đương:

$$S_n = \frac{n(a_1 + a_n)}{2} = na_1 + \frac{n(n-1)}{2}d$$

**Chú ý.** Dạng thứ nhất dùng khi biết số hạng cuối $a_n$, dạng thứ hai dùng khi chỉ biết $a_1$ và $d$. Nhìn đề để chọn dạng cho nhanh: có $a_n$ thì dùng dạng một.

**Tính chất 3 — Tính chất đối xứng.** Trong cấp số cộng, tổng hai số hạng có tổng chỉ số bằng nhau thì bằng nhau:

$$a_m + a_n = a_p + a_q \quad \text{khi} \quad m + n = p + q$$

**Hệ quả.** Số hạng giữa là trung bình cộng của hai số hạng cách đều nó: $a_k = \dfrac{a_{k-1} + a_{k+1}}{2}$.

**Cách nhanh.** Đề cho $a_2 + a_5 + a_8 = 21$ và hỏi $S_9$ thì ghép $a_2 + a_8 = 2a_5$, suy ra $3a_5 = 21$ tức $a_5 = 7$, rồi $S_9 = 9a_5 = 63$. Không cần tìm $a_1$ và $d$.

**Tính chất 4 — Ba số lập thành cấp số cộng.** Ba số $x, y, z$ lập thành cấp số cộng khi và chỉ khi

$$2y = x + z$$

**Chú ý.** Ở dạng này số hạng giữa là trung bình cộng, không phải trung bình nhân. Đây là chỗ đề hay gài bẫy với hai đáp án $\pm$ của căn bậc hai.

### 2.2. Cấp số nhân

**Định nghĩa 2 — Cấp số nhân.** Dãy số $\{a_n\}$ là *cấp số nhân* khi kể từ số hạng thứ hai, mỗi số hạng bằng số hạng đứng ngay trước nó nhân với một hằng số $q$ không đổi:

$$a_{n+1} = a_n \cdot q$$

Hằng số $q$ gọi là *công bội*.

**Tính chất 5 — Số hạng tổng quát.**

$$a_n = a_1 q^{n-1}$$

**Tính chất 6 — Tổng $n$ số hạng đầu.**

$$S_n = \frac{a_1(1 - q^n)}{1 - q} \quad (q \neq 1)$$

Khi $q = 1$ thì $S_n = na_1$.

**Chú ý.** Mẫu số $1 - q$ chứ không phải $q - 1$. Viết nhầm mẫu sẽ ra sai dấu toàn bộ đáp án. Có thể dùng dạng tương đương $S_n = \dfrac{a_1(q^n - 1)}{q - 1}$ để tránh nhầm.

**Tính chất 7 — Tính chất đối xứng.** Trong cấp số nhân, tích hai số hạng có tổng chỉ số bằng nhau thì bằng nhau:

$$a_m \cdot a_n = a_p \cdot a_q \quad \text{khi} \quad m + n = p + q$$

**Cách nhanh.** Đề cho $a_3 = 4$ và $a_5 a_7 = 36$ rồi hỏi $a_9$: vì $5 + 7 = 3 + 9$ nên $a_5 a_7 = a_3 a_9$, suy ra $a_9 = \dfrac{36}{4} = 9$. Không cần tìm $a_1$ và $q$.

**Tính chất 8 — Ba số lập thành cấp số nhân.** Ba số $x, y, z$ lập thành cấp số nhân khi và chỉ khi

$$y^2 = xz$$

**Chú ý.** Trung bình nhân $y = \pm\sqrt{xz}$ có hai giá trị. Nếu đề thêm điều kiện 各项都是正数 (các số hạng đều dương) thì chỉ lấy giá trị dương.

**Tính chất 9 — Cấp số nhân lùi vô hạn.** Cấp số nhân lùi vô hạn hội tụ khi và chỉ khi $|q| < 1$. Khi đó tổng của mọi số hạng là

$$S = \frac{a_1}{1 - q}$$

**Chú ý.** Điều kiện hội tụ là $|q| < 1$, tức $-1 < q < 1$. Đáp án $q \le 1$ sai vì bỏ sót trường hợp $q \le -1$ không hội tụ.

### 2.3. Dãy số cho bởi công thức truy hồi

**Định nghĩa 3 — Công thức truy hồi.** Dãy số cho bởi công thức truy hồi là dãy mà mỗi số hạng được tính từ một hay nhiều số hạng đứng trước, kèm theo giá trị của số hạng đầu.

**Tính chất 10 — Quan hệ giữa số hạng và tổng.** Với mọi dãy số, kể từ $n \ge 2$:

$$a_n = S_n - S_{n-1}$$

**Chú ý.** Công thức này biến đề cho $S_n$ thành bài toán tìm $a_n$. Đây là dạng bài phổ biến của chuyên đề: đề cho công thức tổng $S_n$ và hỏi một số hạng cụ thể.

**Cách nhanh.** Với $S_n = an^2 + bn$ thì $a_n = S_n - S_{n-1} = a(2n - 1) + b$, tức dãy là cấp số cộng với công sai $2a$.

---

## 3. CÁC DẠNG BÀI

### Dạng 1 — Xác định số hạng đầu và công sai của cấp số cộng

**Cách nhận dạng.** Đề cho hai điều kiện liên quan tới các số hạng cụ thể và yêu cầu tìm $a_1$, $d$, $a_n$ hoặc $S_n$.

**Cách làm.** Viết mỗi điều kiện thành phương trình theo $a_1$ và $d$ bằng công thức $a_n = a_1 + (n-1)d$, rồi giải hệ hai phương trình.

**Ví dụ 1.** Cho cấp số cộng có $a_1 = 3$ và $a_5 = 11$. Tìm $S_7$.

**Giải.** Từ $a_5 = a_1 + 4d$ suy ra $4d = 11 - 3 = 8$, vậy $d = 2$.

Với $S_7$ dùng dạng $S_n = na_1 + \dfrac{n(n-1)}{2}d$:

$$S_7 = 7 \cdot 3 + \frac{7 \cdot 6}{2} \cdot 2 = 21 + 42 = 63$$

---

### Dạng 2 — Xác định số hạng đầu và công bội của cấp số nhân

**Cách nhận dạng.** Đề cho hai điều kiện về các số hạng của cấp số nhân và yêu cầu tìm $a_1$, $q$, $a_n$ hoặc $S_n$.

**Cách làm.** Viết mỗi điều kiện theo $a_1$ và $q$ bằng $a_n = a_1 q^{n-1}$. Khi đề cho tỉ số của hai tổng liên tiếp, chia hai phương trình để triệt tiêu $a_1$ và tìm $q$ trước.

**Ví dụ 2.** Cho cấp số nhân có $a_1 = 2$, $q = 3$. Tìm $a_4$ và $S_3$.

**Giải.** Số hạng tổng quát: $a_4 = a_1 q^3 = 2 \cdot 27 = 54$.

Tổng ba số hạng đầu:

$$S_3 = \frac{a_1(1 - q^3)}{1 - q} = \frac{2(1 - 27)}{1 - 3} = \frac{2 \cdot (-26)}{-2} = 26$$

---

### Dạng 3 — Cho tổng $n$ số hạng đầu, tìm số hạng và công sai

**Cách nhận dạng.** Đề cho công thức của $S_n$ theo $n$ và hỏi một số hạng cụ thể, hoặc hỏi công sai.

**Cách làm.** Dùng $a_n = S_n - S_{n-1}$ cho $n \ge 2$, còn $a_1 = S_1$. Nếu đề hỏi công sai, tính $d = a_2 - a_1$.

**Ví dụ 3.** Cho $S_n = n^2 + 4n$. Tìm $a_3$.

**Giải.** Áp dụng $a_n = S_n - S_{n-1}$:

$$S_3 = 9 + 12 = 21, \qquad S_2 = 4 + 8 = 12$$

$$a_3 = S_3 - S_2 = 21 - 12 = 9$$

**Cách nhanh.** $S_n = n^2 + 4n$ có dạng $an^2 + bn$ với $a = 1$, $b = 4$, nên dãy là cấp số cộng với $d = 2a = 2$ và $a_1 = S_1 = 5$. Suy ra $a_3 = a_1 + 2d = 9$.

---

### Dạng 4 — Vận dụng tính chất đặc trưng của cấp số cộng

**Cách nhận dạng.** Đề cho tổng của vài số hạng đối xứng qua một số hạng giữa, hoặc cho ba số lập thành cấp số cộng, và yêu cầu tính giá trị biểu thức mà không cho $a_1$, $d$.

**Cách làm.** Dùng $a_m + a_n = a_p + a_q$ khi $m + n = p + q$. Với ba số hạng liên tiếp hoặc cách đều, ghép thành bội của số hạng giữa.

**Ví dụ 4.** Cho cấp số cộng thỏa mãn $a_3 + a_6 + a_8 + a_{11} = 12$. Tính $2a_9 - a_{11}$.

**Giải.** Ghép $a_3 + a_{11} = a_6 + a_8 = 2a_7$ nên tổng đã cho bằng $4a_7 = 12$, suy ra $a_7 = 3$.

Biến đổi biểu thức cần tính theo $a_7$ và $d$:

$$2a_9 - a_{11} = 2(a_7 + 2d) - (a_7 + 4d) = a_7 = 3$$

---

### Dạng 5 — Cấp số nhân lùi vô hạn

**Cách nhận dạng.** Đề có cụm 无穷等比数列 (cấp số nhân lùi vô hạn) hoặc 各项之和 (tổng các số hạng), kèm câu hỏi về điều kiện hội tụ hoặc tổng vô hạn.

**Cách làm.** Kiểm tra $|q| < 1$, sau đó áp dụng $S = \dfrac{a_1}{1 - q}$.

**Ví dụ 5.** Cho cấp số nhân lùi vô hạn có $a_1 = 8$, $q = \dfrac{1}{2}$. Tính tổng mọi số hạng.

**Giải.** Vì $|q| = \dfrac{1}{2} < 1$ nên chuỗi hội tụ. Áp dụng công thức:

$$S = \frac{a_1}{1 - q} = \frac{8}{1 - \dfrac{1}{2}} = 16$$

---

### Dạng 6 — Dãy số cho bởi công thức truy hồi

**Cách nhận dạng.** Đề có 递推公式 hoặc hệ thức liên hệ $a_{n+1}$ với $a_n$, kèm giá trị $a_1$. Đề thường hỏi một số hạng cụ thể với chỉ số nhỏ.

**Cách làm.** Thay lần lượt từng bước từ $a_1$ lên số hạng cần tìm. Không cần tìm công thức tổng quát khi chỉ số được hỏi nhỏ.

**Ví dụ 6.** Cho $a_1 = 1$ và $a_{n+1} = a_n + 2n$. Tìm $a_3$.

**Giải.** Thay $n = 1$: $a_2 = a_1 + 2 \cdot 1 = 1 + 2 = 3$.

Thay $n = 2$: $a_3 = a_2 + 2 \cdot 2 = 3 + 4 = 7$.

**Chú ý.** Số hạng $n$ trong hệ thức là chỉ số của số hạng đang tính, không phải của số hạng đã biết. Nhầm chỗ này cho kết quả sai.

---

### Dạng 7 — Bài toán thực tế vận dụng cấp số cộng và cấp số nhân

**Cách nhận dạng.** Đề mô tả một quá trình thay đổi đều theo bước: tăng đều một lượng không đổi (cấp số cộng) hoặc tăng theo tỉ lệ phần trăm không đổi (cấp số nhân).

**Cách làm.** Xác định số hạng đầu và công sai (hoặc công bội) từ lời văn, rồi áp dụng công thức số hạng tổng quát hoặc công thức tổng. Tăng đều theo phần trăm thì công bội là $q = 1 + r$, giảm theo phần trăm thì $q = 1 - r$.

**Ví dụ 7.** Một công ty có doanh thu năm đầu là $400$ vạn, mỗi năm sau tăng $50\%$ so với năm trước. Tính tổng doanh thu ba năm đầu.

**Giải.** Doanh thu lập thành cấp số nhân với $a_1 = 400$ và $q = 1 + 0{,}5 = 1{,}5$.

Tổng ba năm đầu:

$$S_3 = \frac{a_1(1 - q^3)}{1 - q} = \frac{400(1 - 3{,}375)}{1 - 1{,}5} = \frac{400 \cdot (-2{,}375)}{-0{,}5} = 1900$$

Vậy tổng doanh thu ba năm đầu là $1900$ vạn.

**Chú ý.** Tăng $50\%$ nghĩa là nhân với $1{,}5$, không phải nhân với $0{,}5$. Đây là lỗi phổ biến nhất ở dạng bài thực tế.

---

## PHỤ LỤC — BỐI CẢNH KỲ THI

### Cấu trúc đề thi CSCA môn Toán

| Đặc điểm | Thông số |
|:---------|:---------|
| Số câu | 48 câu trắc nghiệm |
| Thời gian | 60 phút |
| Thang điểm | 100 điểm |
| Ngôn ngữ | Tiếng Trung hoặc tiếng Anh (thí sinh chọn) |
| Máy tính | Không được dùng |

Thời gian trung bình mỗi câu là **1 phút 15 giây**. Mục tiêu của khóa học không phải giải được bài khó, mà là **nhận ra dạng bài trong vài giây và chọn đúng đáp án trong khoảng 40 giây**.

### Trọng số các nhóm nội dung

| Nhóm nội dung | Số câu | Tỉ trọng |
|:--------------|:------:|:--------:|
| Lượng giác | 8–11 | ~20% |
| Hình học giải tích | 8–10 | ~19% |
| **Dãy số** | **5–8** | **~13%** |
| Hàm số | 5–7 | ~13% |
| Tập hợp & bất đẳng thức | 4–6 | ~10% |
| Mũ & logarit | 3–5 | ~8% |
| Vector & số phức | 2–4 | ~6% |
| Xác suất & thống kê | 1–2 | ~3% |

Chuyên đề hôm nay chiếm khoảng 13% đề thi. Đây là chuyên đề có **công thức ít nhất** trong toàn bộ chương trình: chỉ bốn công thức cho cấp số cộng và bốn công thức cho cấp số nhân. Nhưng chính vì ít công thức nên đề khai thác rất sâu vào **tính chất đối xứng của các chỉ số**, đòi hỏi nhận ra quy luật thay vì thay số trực tiếp.

---

*Tài liệu nội bộ, CAE SHANGHAI.*
