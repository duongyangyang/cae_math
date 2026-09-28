# BUỔI 6 — ĐÁP ÁN ĐỀ KIỂM TRA CUỐI CHUYÊN ĐỀ HÀM SỐ VÀ DÃY SỐ

> **Hàm số và Dãy số （函数与数列）**
>
> **Tài liệu giáo viên.** Học sinh làm đề trong `../hoc-sinh/06-de-kiem-tra.md`. Thời gian 35 phút, 24 câu.

---

## BẢNG ĐÁP ÁN

| Câu | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 |
|:----|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| Đáp án | D | D | B | C | B | C | D | B | A | B | C | B |

| Câu | 13 | 14 | 15 | 16 | 17 | 18 | 19 | 20 | 21 | 22 | 23 | 24 |
|:----|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| Đáp án | C | B | C | A | C | A | A | A | A | D | D | D |


**Phân bố độ khó:** 10 câu dễ, 7 câu trung bình, 7 câu khó.
**Phân bố theo buổi:** 6 câu buổi 2 (tính chất hàm số), 10 câu buổi 3 (bậc hai, mũ, logarit, đạo hàm), 8 câu buổi 6 (dãy số).

---

## LỜI GIẢI NGẮN

**Câu 1.** `CAE-M-CD4-08.1-E-001` — **Đáp án D**

**Giải.** Với $x > 0$ thì $x + \dfrac{1}{x} \ge 2$; với $x < 0$ thì $x + \dfrac{1}{x} \le -2$. Khi $x$ tiến tới $0^-$, biểu thức tiến tới $-\infty$.

Vậy biểu thức không có 最小值 (giá trị nhỏ nhất) trên $\mathbb{R} \setminus \{0\}$.

---

**Câu 2.** `CAE-M-CD4-08.2-M-025` — **Đáp án D**

**Giải.** Quãng đường là 定积分 của vận tốc:

$$s = \int_0^2 (2t + 3)\,dt = \left[t^2 + 3t\right]_0^2 = 4 + 6 = 10 \text{ m}$$

---

**Câu 3.** `CAE-M-CD3-GV-H-108` — **Đáp án B**

**Giải.** Đây là 无穷等比数列 (cấp số nhân lùi vô hạn). Vì $\lvert q \rvert = \dfrac{1}{2} < 1$ nên chuỗi hội tụ và tổng tính theo công thức:

$$S = \frac{a_1}{1 - q} = \frac{8}{1 - \frac{1}{2}} = 16$$

---

**Câu 4.** `CAE-M-CD4-GV-E-205` — **Đáp án C**

**Giải.** Theo định nghĩa 对数, $\log_a a = 1$ với mọi cơ số $a > 0$, $a \ne 1$:

$$\log_7 7 = 1$$

---

**Câu 5.** `CAE-M-CD4-08.6-M-079` — **Đáp án B**

**Giải.** Điều kiện xác định: $1 - x^2 \ge 0$. Xét phương trình $x = \sqrt{1 - x^2}$ với $x \ge 0$:

$$x^2 = 1 - x^2 \implies 2x^2 = 1 \implies x = \frac{\sqrt{2}}{2}$$

Giá trị này thỏa mãn điều kiện, và $x < 0$ không cho nghiệm vì vế trái âm còn vế phải không âm. Vậy hàm số có đúng $1$ 零点 (nghiệm).

---

**Câu 6.** `CAE-M-CD4-08.7-E-089` — **Đáp án C**

**Giải.** Phân tích tử thành nhân tử rồi 约分 (rút gọn) để khử dạng vô định $\dfrac{0}{0}$:

$$\lim_{x \to 3} \frac{x^2 - 9}{x - 3} = \lim_{x \to 3} \frac{(x - 3)(x + 3)}{x - 3} = \lim_{x \to 3}(x + 3) = 6$$

---

**Câu 7.** `CAE-M-CD3-08.7-E-012` — **Đáp án D**

**Giải.** Cấp số nhân với $b_1 = 4$, $q = 3$. Công thức số hạng tổng quát:

$$b_4 = b_1 q^3 = 4 \cdot 27 = 108$$

---

**Câu 8.** `CAE-M-CD4-08.1-E-008` — **Đáp án B**

**Giải.** Parabol $y = x^2 + x - 2$ cắt trục hoành tại $x = -2$ và $x = 1$. Trên đoạn $[-2, 1]$ đồ thị nằm dưới trục hoành, nên diện tích là

$$S = \left\lvert \int_{-2}^{1}(x^2 + x - 2)\,dx \right\rvert = \left\lvert \frac{9}{2} \right\rvert = \frac{9}{2}$$

---

**Câu 9.** `CAE-M-CD4-LX2-M-123` — **Đáp án A**

**Giải.** Hàm $f(x) = x^2 - 2kx$ có 对称轴 (trục đối xứng) $x = k$. Trên $\mathbb{N}$, hàm số 单调递增 (đồng biến) khi và chỉ khi trục đối xứng nằm bên trái hoặc tại điểm đầu:

$$k \le 0$$

---

**Câu 10.** `CAE-M-CD4-LX1-E-110` — **Đáp án B**

**Giải.** Theo định nghĩa đạo hàm tại một điểm, giới hạn đã cho chính là $f'(x_0)$. Vậy $f'(x_0) = \dfrac{3}{2}$.

---

**Câu 11.** `CAE-M-CD3-GV-H-118` — **Đáp án C**

**Giải.** Từ $a_4 = a_1 q^3$ suy ra $16 = 2q^3$, vậy $q = 2$. Áp dụng công thức tổng:

$$S_5 = \frac{2(2^5 - 1)}{2 - 1} = 2 \cdot 31 = 62$$

---

**Câu 12.** `CAE-M-CD4-08.1-E-007` — **Đáp án B**

**Giải.** Tìm 原函数 rồi thay cận:

$$\int_0^1 (3x^2 + 1)\,dx = \left[x^3 + x\right]_0^1 = 1 + 1 = 2$$

---

**Câu 13.** `CAE-M-CD4-GV-E-214` — **Đáp án C**

**Giải.** Hàm 对数 xác định khi biểu thức trong logarit dương:

$$x - 1 > 0 \implies x > 1$$

Vậy 定义域 (tập xác định) là $(1, +\infty)$.

---

**Câu 14.** `CAE-M-CD4-LX2-E-122` — **Đáp án B**

**Giải.** 平均变化率 (tốc độ biến thiên trung bình) trên $[x_1, x_2]$ chính là hệ số góc của đường thẳng $AB$:

$$k_{AB} = \frac{y_2 - y_1}{x_2 - x_1} = \sqrt{3}$$

Vì $k = \tan\alpha = \sqrt{3}$ nên 倾斜角 (góc nghiêng) $\alpha = \dfrac{\pi}{3}$.

---

**Câu 15.** `CAE-M-CD3-GV-H-104` — **Đáp án C**

**Giải.** Vì $a_2 + a_3 = q(a_1 + a_2)$ nên

$$q = \frac{a_2 + a_3}{a_1 + a_2} = \frac{12}{6} = 2$$

Từ $a_1 + a_2 = a_1(1 + q) = 6$ suy ra $a_1 = 2$.

$$a_4 = a_1 q^3 = 2 \cdot 8 = 16$$

---

**Câu 16.** `CAE-M-CD4-LX1-M-115` — **Đáp án A**

**Giải.** Hệ số góc của tiếp tuyến bằng $f'(1)$. Tiếp tuyến đi qua hai điểm $(1, 3)$ và $(0, 2)$ nên

$$f'(1) = \frac{3 - 2}{1 - 0} = 1 > 0$$

---

**Câu 17.** `CAE-M-CD4-GV-M-215` — **Đáp án C**

**Giải.** Hàm 奇函数 (hàm lẻ) thỏa mãn $f(-x) = -f(x)$ với mọi $x$ trong tập xác định.

Với $y = x^3$: $(-x)^3 = -x^3$, thỏa mãn. Các hàm $y = x^2$, $y = \lvert x \rvert$ là hàm chẵn, còn $y = x + 1$ không chẵn không lẻ.

---

**Câu 18.** `CAE-M-CD4-08.7-M-090` — **Đáp án A**

**Giải.** Dùng bảng 原函数 cơ bản cho từng số hạng:

$$\int (3x^2 + 3e^x + 2)\,dx = x^3 + 3e^x + 2x + C$$

---

**Câu 19.** `CAE-M-CD3-GV-H-113` — **Đáp án A**

**Giải.** Ba số hạng $a_2, a_5, a_8$ cách đều nhau nên theo 性质 của cấp số cộng:

$$a_2 + a_8 = 2a_5 \implies a_2 + a_5 + a_8 = 3a_5 = 21 \implies a_5 = 7$$

Tổng $S_9$ có số hạng giữa là $a_5$:

$$S_9 = \frac{9(a_1 + a_9)}{2} = 9 \cdot \frac{a_1 + a_9}{2} = 9a_5 = 63$$

---

**Câu 20.** `CAE-M-CD4-08.3-M-038` — **Đáp án A**

**Giải.** Tìm 原函数 trước: $f(x) = x^3 - x + C$. Dùng điều kiện $f(1) = 0$:

$$1 - 1 + C = 0 \implies C = 0 \implies f(x) = x^3 - x$$

---

**Câu 21.** `CAE-M-CD4-GV-E-206` — **Đáp án A**

**Giải.** Hàm số $f(x) = 2x + 1$ có hệ số góc $2 > 0$ nên 单调递增 (đồng biến) trên $\mathbb{R}$, tức là 增函数.

---

**Câu 22.** `CAE-M-CD3-GV-H-115` — **Đáp án D**

**Giải.** Từ $a_4 = a_1 + 3d$ suy ra $10 = 1 + 3d$, vậy $d = 3$. Áp dụng công thức tổng:

$$S_{10} = \frac{10(a_1 + a_{10})}{2} = 5(1 + 28) = 145$$

---

**Câu 23.** `CAE-M-CD3-GV-H-116` — **Đáp án D**

**Giải.** Đề cho 递推公式 với chỉ số nhỏ nên thay lần lượt, không cần công thức tổng quát.

$$a_2 = a_1 + 1 = 2, \quad a_3 = a_2 + 2 = 4, \quad a_4 = a_3 + 3 = 7, \quad a_5 = a_4 + 4 = 11$$

---

**Câu 24.** `CAE-M-CD3-LX1-H-019` — **Đáp án D**

**Giải.** Gọi ba cạnh là $a$, $aq$, $aq^2$ với $a > 0$, $q > 0$. Điều kiện 三角形 (bất đẳng thức tam giác): tổng hai cạnh nhỏ hơn cạnh lớn nhất phải lớn hơn cạnh còn lại.

Nếu $q \ge 1$: cạnh lớn nhất là $aq^2$, cần $a + aq > aq^2$, tức $q^2 - q - 1 < 0$, suy ra $q < \dfrac{1 + \sqrt{5}}{2}$.

Nếu $q < 1$: cạnh lớn nhất là $a$, cần $aq + aq^2 > a$, tức $q^2 + q - 1 > 0$, suy ra $q > \dfrac{-1 + \sqrt{5}}{2}$.

Vậy $q \in \left(\dfrac{-1 + \sqrt{5}}{2}, \dfrac{1 + \sqrt{5}}{2}\right)$.

---
