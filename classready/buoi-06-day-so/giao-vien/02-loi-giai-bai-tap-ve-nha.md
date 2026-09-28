# BUỔI 6 — LỜI GIẢI BÀI TẬP VỀ NHÀ

> **Dãy số （数列）**
>
> **Tài liệu giáo viên.** Dùng để chữa bài trên lớp và soạn đề kiểm tra. Học sinh chỉ nhận bảng đáp án (`../hoc-sinh/05-dap-an-bai-tap-ve-nha.md`).

---

## PHẦN D — BÀI TẬP VỀ NHÀ

### PHẦN BẮT BUỘC

#### Nhóm A — Dãy số: cấp số cộng và cấp số nhân

**Câu 1.** `CAE-M-CD3-08.3-E-004` — **Đáp án A**

**Giải.** Cộng hai phương trình để triệt tiêu $b_2$:

$$(b_1 + b_2) + (b_1 - b_2) = 3 + (-1) \implies 2b_1 = 2 \implies b_1 = 1$$

Thay lại $b_1 = 1$ vào $b_1 + b_2 = 3$ được $b_2 = 2$, vậy $q = \dfrac{b_2}{b_1} = 2$.

---

**Câu 2.** `CAE-M-CD3-08.6-E-010` — **Đáp án C**

**Giải.** Cấp số cộng với $a_1 = 1$, $d = 3$. Áp dụng $S_n = na_1 + \dfrac{n(n-1)}{2}d$:

$$S_n = n + \frac{3n(n-1)}{2} = \frac{2n + 3n^2 - 3n}{2} = \frac{3n^2 - n}{2}$$

---

**Câu 3.** `CAE-M-CD3-08.8-E-014` — **Đáp án C**

**Giải.** Đề cho 等差数列, tìm công sai bằng phép trừ:

$$d = \frac{a_7 - a_5}{7 - 5} = \frac{19 - 15}{2} = 2 \implies a_3 = a_5 - 2d = 15 - 4 = 11$$

---

**Câu 4.** `CAE-M-CD3-08.8-M-015` — **Đáp án D**

**Giải.** Đề cho 前 $n$ 项和 $S_n = n^2 + 4n$. Dùng $a_n = S_n - S_{n-1}$:

$$a_3 = S_3 - S_2 = (9 + 12) - (4 + 8) = 21 - 12 = 9$$

---

**Câu 5.** `CAE-M-CD3-LX1-E-016` — **Đáp án B**

**Giải.** Ba số lập thành 等差数列 khi số hạng giữa là trung bình cộng của hai số hạng hai đầu:

$$a = \frac{3 + 27}{2} = 15$$

---

**Câu 6.** `CAE-M-CD3-LX1-M-018` — **Đáp án C**

**Giải.** Số hạng chung thỏa mãn $3n + 1 = 4m - 1$, tức $3n + 2 = 4m$. Từ $3n \equiv 2 \pmod 4$ suy ra $n \equiv 2 \pmod 4$.

Viết $n = 4k + 2$ với $k \ge 0$, số hạng chung là $12k + 7$. Dãy $\{a_n\}$ là cấp số cộng với $a_1 = 7$, $d = 12$:

$$S_{20} = 20 \cdot 7 + \frac{20 \cdot 19}{2} \cdot 12 = 140 + 2280 = 2420$$

---

**Câu 7.** `CAE-M-CD3-LX3-E-025` — **Đáp án B**

**Giải.** Nhóm bốn số hạng đã cho thành hai cặp đối xứng quanh $a_7$:

$$a_3 + a_{11} = a_6 + a_8 = 2a_7$$

Vậy $4a_7 = 12$, suy ra $a_7 = 3$. Biểu thức cần tính:

$$2a_9 - a_{11} = 2(a_7 + 2d) - (a_7 + 4d) = a_7 = 3$$

---

**Câu 8.** `CAE-M-CD3-LX3-H-027` — **Đáp án D**

**Giải.** Từ $a_4 - a_1 = a_1(q^3 - 1) = 78$ và $S_3 = a_1(1 + q + q^2) = 39$. Chia vế theo vế và dùng $q^3 - 1 = (q - 1)(q^2 + q + 1)$:

$$q - 1 = \frac{78}{39} = 2 \implies q = 3, \qquad a_1 = \frac{39}{1 + 3 + 9} = 3$$

Vậy $a_n = 3 \cdot 3^{n-1} = 3^n$ và $b_n = \log_3 a_n = n$. Tổng mười số hạng đầu:

$$b_1 + b_2 + \cdots + b_{10} = 1 + 2 + \cdots + 10 = 55$$

---

**Câu 9.** `CAE-M-CD3-GV-E-101` — **Đáp án A**

**Giải.** Cấp số cộng với $a_1 = 2$, $d = 3$. Công thức số hạng tổng quát:

$$a_5 = a_1 + 4d = 2 + 12 = 14$$

---

**Câu 10.** `CAE-M-CD3-GV-E-105` — **Đáp án A**

**Giải.** Đề cho 等差数列 (cấp số cộng) và hai số hạng cách nhau bốn bước. Công sai tính bằng phép trừ:

$$d = \frac{a_7 - a_3}{7 - 3} = \frac{19 - 7}{4} = 3$$

---

**Câu 11.** `CAE-M-CD3-GV-E-110` — **Đáp án A**

**Giải.** Áp dụng công thức tổng $S_n = na_1 + \dfrac{n(n-1)}{2}d$ với $n = 10$, $a_1 = 1$:

$$100 = 10 \cdot 1 + \frac{10 \cdot 9}{2}d = 10 + 45d \implies 45d = 90 \implies d = 2$$

---

**Câu 12.** `CAE-M-CD3-GV-H-119` — **Đáp án D**

**Giải.** Công sai tính bằng phép trừ:

$$d = \frac{a_8 - a_4}{8 - 4} = \frac{20 - 8}{4} = 3 \implies a_1 = a_4 - 3d = 8 - 9 = -1$$

$$S_{10} = \frac{10(a_1 + a_{10})}{2} = 5(-1 + 26) = 125$$

---

**Câu 13.** `CAE-M-CD3-GV-H-120` — **Đáp án D**

**Giải.** Từ $S_5 = \dfrac{5(a_1 + a_5)}{2} = 55$ suy ra $a_1 + a_5 = 22$, vậy $a_1 = 22 - 15 = 7$ và

$$d = \frac{a_5 - a_1}{5 - 1} = \frac{15 - 7}{4} = 2 \implies a_{10} = a_5 + 5d = 15 + 10 = 25$$

---

#### Nhóm B — Lượng giác

**Câu 14.** `CAE-M-CD4-08.2-M-026` — **Đáp án C**

**Giải.** Hàm số liên tục tại $x = 0$ khi $a$ bằng giới hạn của hàm tại đó:

$$a = \lim_{x \to 0} \frac{\sin x}{x} = 1$$

---

**Câu 15.** `CAE-M-CD4-08.5-M-064` — **Đáp án A**

**Giải.** Đưa hằng số ra ngoài dấu tích phân rồi dùng nguyên hàm cơ bản:

$$\int \frac{1}{2}\cos x\,dx = \frac{1}{2}\int \cos x\,dx = \frac{1}{2}\sin x + C$$

---

**Câu 16.** `CAE-M-CD4-GV-E-201` — **Đáp án B**

**Giải.** Chu kỳ của hàm $y = \sin(\omega x)$ là $T = \dfrac{2\pi}{\lvert \omega \rvert}$. Với $\omega = 2$:

$$T = \frac{2\pi}{2} = \pi$$

---

**Câu 17.** `CAE-M-CD4-GV-E-202` — **Đáp án D**

**Giải.** Đây là 特殊角 (góc đặc biệt). Theo bảng giá trị lượng giác của góc đặc biệt:

$$\cos\frac{\pi}{3} = \frac{1}{2}$$

---

**Câu 18.** `CAE-M-CD4-GV-M-203` — **Đáp án C**

**Giải.** Đây là 特殊角. Theo bảng giá trị lượng giác của góc đặc biệt:

$$\tan\frac{\pi}{4} = 1$$

---

**Câu 19.** `CAE-M-CD4-GV-M-204` — **Đáp án A**

**Giải.** Đề hỏi 值域 (tập giá trị). Vì $-1 \le \sin x \le 1$ nên nhân ba vế với $3$:

$$-3 \le 3\sin x \le 3$$

Tập giá trị là $[-3, 3]$.

---

#### Nhóm C — Hàm số, mũ, logarit

**Câu 20.** `CAE-M-CD4-GV-E-211` — **Đáp án D**

**Giải.** Theo định nghĩa 对数 (logarit), $\log_a 1 = 0$ với mọi cơ số $a > 0$, $a \ne 1$:

$$\log_5 1 = 0$$

---

**Câu 21.** `CAE-M-CD4-08.6-M-078` — **Đáp án B**

**Giải.** Trên $(-1, 1)$ đồ thị nằm trên trục hoành nên tích phân dương và đóng góp trực tiếp vào diện tích. Trên $(1, 5)$ đồ thị nằm dưới trục hoành nên tích phân âm, phải đổi dấu mới thành diện tích.

$$S = \int_{-1}^{1} f(x)\,dx - \int_{1}^{5} f(x)\,dx$$

---

**Câu 22.** `CAE-M-CD4-GV-E-210` — **Đáp án C**

**Giải.** Đưa về cùng cơ số: $8 = 2^3$, do đó

$$\log_2 8 = \log_2 2^3 = 3$$

---

**Câu 23.** `CAE-M-CD4-GV-E-209` — **Đáp án B**

**Giải.** Tính 幂 (lũy thừa) trực tiếp:

$$2^3 = 2 \cdot 2 \cdot 2 = 8$$

---

#### Nhóm D — Ôn tập tích lũy

**Câu 24.** `CAE-M-CD1-LX2-H-040` — **Đáp án C**

**Giải.** Xét hai mệnh đề 甲 và 乙 trước. Cả hai đều tương đương với $A \subseteq B$, nên 甲 và 乙 luôn cùng đúng hoặc cùng sai.

Vì chỉ có đúng một mệnh đề không成立, mệnh đề đó phải là 丙 hoặc 丁. Mà 丁 tương đương với $\complement_U(A \cap B) = \complement_U A$, tức $A \cap B = A$, cũng tương đương $A \subseteq B$. Vậy 丁 cũng cùng nhóm với 甲 và 乙.

Chỉ còn 丙: $\complement_U B = \complement_U A$ tương đương $A = B$, là điều kiện mạnh hơn $A \subseteq B$. Khi $A \subset B$ thật sự thì 甲, 乙, 丁 đúng còn 丙 sai.

---

**Câu 25.** `CAE-M-CD1-LX3-H-045` — **Đáp án B**

**Giải.** Xét dấu của $x$ và $y$ theo bốn trường hợp. Ký hiệu $T = \dfrac{x}{\lvert x \rvert} + \dfrac{y}{\lvert y \rvert} + \dfrac{\lvert xy \rvert}{xy}$.

Với $x > 0, y > 0$: $T = 1 + 1 + 1 = 3$. Với $x > 0, y < 0$: $T = 1 - 1 - 1 = -1$. Với $x < 0, y > 0$: $T = -1 + 1 - 1 = -1$. Với $x < 0, y < 0$: $T = -1 - 1 + 1 = -1$.

Vậy $M = \{3, -1\}$, do đó $-1 \in M$.

---

### PHẦN TỰ CHỌN

#### Nhóm tự chọn — Dãy số

**Câu 1.** `CAE-M-CD3-08.5-M-007` — **Đáp án B**

**Giải.** Đề cho 前 $n$ 项和 (tổng $n$ số hạng đầu) $S_n = 3n^2 - 2n$. Dùng $a_n = S_n - S_{n-1}$ cho $n \ge 2$:

$$a_2 = S_2 - S_1 = (12 - 4) - (3 - 2) = 8 - 1 = 7$$

---

**Câu 2.** `CAE-M-CD3-GV-H-114` — **Đáp án B**

**Giải.** Áp dụng công thức tổng 等比数列 với $a_1 = 8$, $q = \dfrac{1}{2}$:

$$S_n = \frac{8\left(1 - \left(\frac{1}{2}\right)^n\right)}{1 - \frac{1}{2}} = 16\left(1 - \frac{1}{2^n}\right) = 15$$

$$1 - \frac{1}{2^n} = \frac{15}{16} \implies \frac{1}{2^n} = \frac{1}{16} \implies n = 4$$

---

**Câu 3.** `CAE-M-CD3-GV-E-106` — **Đáp án B**

**Giải.** Áp dụng công thức tổng của 等比数列 với $a_1 = 2$, $q = 3$:

$$S_3 = a_1 + a_1 q + a_1 q^2 = 2 + 6 + 18 = 26$$

---

**Câu 4.** `CAE-M-CD3-08.3-E-003` — **Đáp án B**

**Giải.** Hai phương trình theo $a_1$ và $d$:

$$a_2 + a_6 = 2a_1 + 6d = 10, \qquad a_3 = a_1 + 2d = 4$$

Từ phương trình thứ hai: $a_1 = 4 - 2d$. Thay vào phương trình đầu: $2(4 - 2d) + 6d = 10$, suy ra $8 + 2d = 10$, vậy $d = 1$ và $a_1 = 2$.

---

**Câu 5.** `CAE-M-CD3-LX2-M-022` — **Đáp án D**

**Giải.** Tính ba số hạng đầu từ công thức tổng:

$$a_1 = S_1 = 4^0 + t = 1 + t, \qquad a_2 = S_2 - S_1 = (4 + t) - (1 + t) = 3$$

$$a_3 = S_3 - S_2 = (16 + t) - (4 + t) = 12$$

Cấp số nhân nên $a_2^2 = a_1 a_3$, tức $9 = 12(1 + t)$, suy ra $1 + t = \dfrac{3}{4}$ và $t = -\dfrac{1}{4}$.

---

**Câu 6.** `CAE-M-CD3-08.5-M-009` — **Đáp án D**

**Giải.** Trong cấp số cộng, $a_m + a_n = 2a_1 + (m + n - 2)d$. Đẳng thức $a_m + a_n = a_p + a_q$ trở thành

$$2a_1 + (m+n-2)d = 2a_1 + (p+q-2)d \implies m + n = p + q$$

---

**Câu 7.** `CAE-M-CD3-08.4-M-005` — **Đáp án D**

**Giải.** Đề cho 递推公式 với chỉ số nhỏ nên thay lần lượt, không cần công thức tổng quát.

Với $n = 1$: $a_2 = a_1 + 2 \cdot 1 = 1 + 2 = 3$. Với $n = 2$: $a_3 = a_2 + 2 \cdot 2 = 3 + 4 = 7$.

---

**Câu 8.** `CAE-M-CD3-LX2-H-024` — **Đáp án A**

**Giải.** Gọi $a_1$ là số phù điêu tầng dưới cùng, các tầng tạo thành cấp số nhân công bội $2$:

$$4a_1 - 2a_1 = 16 \implies a_1 = 8$$

$$S_7 = 8 \cdot \frac{2^7 - 1}{2 - 1} = 8 \cdot 127 = 1016$$

---

**Câu 9.** `CAE-M-CD3-GV-H-117` — **Đáp án A**

**Giải.** Ba số hạng $a_1, a_3, a_5$ cách đều nên $a_1 + a_5 = 2a_3$, suy ra $3a_3 = 12$ và $a_3 = 4$. Tương tự $3a_4 = 18$ nên $a_4 = 6$.

Vậy $d = a_4 - a_3 = 2$ và $a_7 = a_4 + 3d = 6 + 6 = 12$.

---

**Câu 10.** `CAE-M-CD3-GV-H-107` — **Đáp án A**

**Giải.** Đề hỏi 最大值 (giá trị lớn nhất) của $S_n$ khi $d < 0$. Tổng là hàm bậc hai theo $n$:

$$S_n = 20n - \frac{3n(n-1)}{2} = -\frac{3}{2}n^2 + \frac{43}{2}n$$

Đỉnh parabol tại $n = \dfrac{43}{6} \approx 7{,}17$. Xét hai giá trị nguyên gần nhất:

$$S_7 = 140 - 63 = 77, \qquad S_8 = 160 - 84 = 76$$

Vậy giá trị lớn nhất là $77$.

---

**Câu 11.** `CAE-M-CD3-GV-H-109` — **Đáp án A**

**Giải.** Dùng tính chất 等比中项: bình phương mỗi số hạng bằng tích hai số hạng cách đều nó. Từ $a_3 = 4$, $a_5 = 16$ suy ra $a_4^2 = a_3 a_5 = 64$, vậy $a_4 = 8$ (các số hạng dương).

$$a_5^2 = a_4 a_6 \implies a_6 = \frac{256}{8} = 32, \qquad a_6^2 = a_5 a_7 \implies a_7 = \frac{1024}{16} = 64$$

---

**Câu 12.** `CAE-M-CD3-08.5-M-008` — **Đáp án C**

**Giải.** Đề hỏi 收敛条件 (điều kiện hội tụ) của 无穷等比数列. Chuỗi hội tụ khi và chỉ khi giá trị tuyệt đối của công bội nhỏ hơn $1$:

$$\lvert q \rvert < 1$$

---

**Câu 13.** `CAE-M-CD3-GV-M-103` — **Đáp án C**

**Giải.** Với $n \ge 2$, hiệu hai tổng liên tiếp cho số hạng thứ $n$:

$$a_4 = S_4 - S_3 = (2 \cdot 16 + 12) - (2 \cdot 9 + 9) = 44 - 27 = 17$$

---

**Câu 14.** `CAE-M-CD3-LX3-M-026` — **Đáp án C**

**Giải.** Tích năm số hạng đầu: $a_1 a_2 a_3 a_4 a_5 = a_1^5 q^{0+1+2+3+4} = a_1^5 q^{10}$. Với $q = 4$:

$$a_1^5 \cdot 4^{10} = 4^{10} \implies a_1^5 = 1 \implies a_1 = 1$$

$$a_4 a_6 = a_1^2 q^{3 + 5} = 1 \cdot 4^8 = 4^8$$

---

**Câu 15.** `CAE-M-CD3-08.7-M-013` — **Đáp án C**

**Giải.** Dãy $1, 1, 2, 3, 5, 8, \ldots$ có quy luật 递推公式 $a_n = a_{n-1} + a_{n-2}$: mỗi số hạng bằng tổng hai số hạng liền trước.

Đây là 斐波那契数列 (dãy Fibonacci). Dãy không phải cấp số cộng vì hiệu các số hạng thay đổi, cũng không phải cấp số nhân vì tỉ các số hạng thay đổi.

---

## TỔNG KẾT LỖI THƯỜNG GẶP

Bảng chẩn đoán dùng khi chữa bài và khi soạn đề kiểm tra. Cột "Câu liên quan" trỏ tới đề bài tập về nhà; các câu ghi "tự chọn" nằm ở phần tự chọn.

| Lỗi thường gặp | Dấu hiệu nhận biết | Câu liên quan |
|:--------------|:-------------------|:--------------|
| Nhầm cấp số cộng với cấp số nhân | Đề có 公差 mà học sinh đi tìm thương, hoặc ngược lại | Câu 1, Câu 2, Câu 9 |
| Dùng trung bình nhân khi đề hỏi trung bình cộng | Ba số lập thành cấp số cộng nhưng học sinh viết $y^2 = xz$ | Câu 5, Câu 6 |
| Nhầm mẫu $1 - q$ thành $q - 1$ | Kết quả tổng ra số âm hoặc sai dấu ở mẫu | Câu 3, Câu 8 |
| Bỏ sót điều kiện $\lvert q \rvert < 1$ | Đề có 无穷 nhưng học sinh áp thẳng công thức tổng vô hạn | Câu 2 tự chọn, Câu 12 tự chọn |
| Tính $a_n$ từ $S_n$ mà quên trường hợp $n = 1$ | Học sinh thay $n = 1$ vào $S_n - S_{n-1}$ rồi kết luận sai $a_1$ | Câu 4, Câu 13 tự chọn |
| Thay nhầm chỉ số trong công thức truy hồi | Số hạng thêm vào dùng chỉ số của số hạng trước thay vì số hạng đang tính | Câu 7 tự chọn |
| Lẫn chu kỳ của $\sin$ với của $\tan$ | Đề cho $\sin(\omega x)$ nhưng học sinh chia cho $\pi$ | Câu 16 |
| Nhầm tập giá trị của $\sin$ và $\cos$ | Kết luận $y = 3\sin x$ có tập giá trị $[-1, 1]$ | Câu 19 |
| Quên điều kiện xác định của hàm logarit | Cho rằng $\log_2(x - 1)$ xác định với mọi $x > 0$ | Câu 20, Câu 22 |
| Nhầm dấu khi tính diện tích hình phẳng | Lấy nguyên tích phân mà không tách đoạn đổi dấu | Câu 21 |

---

*Tài liệu nội bộ, CAE SHANGHAI.*
