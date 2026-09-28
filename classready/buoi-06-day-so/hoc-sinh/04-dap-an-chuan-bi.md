# BUỔI 6 — ĐÁP ÁN BÀI TẬP CHUẨN BỊ

> **Dãy số （数列）**
>
> Mở file này **sau khi đã tự tra từ vựng và làm 10 câu bài tập chuẩn bị**. Dùng để đối chiếu trước khi vào buổi học.

---

## BẢNG ĐÁP ÁN 10 CÂU CHUẨN BỊ

### Bài tập chuẩn bị

| Câu | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 |
|:----|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:--:|
| Đáp án | C | A | D | D | B | B | C | B | A | A |

---

## PHẦN A — BẢNG TỪ VỰNG

### Nhóm 1 — Cấp số cộng

| STT | Thuật ngữ | Nghĩa |
|:---:|:----------|:------|
| 1 | 等差数列 | cấp số cộng |
| 2 | 公差 | công sai |
| 3 | 首项 | số hạng đầu |
| 4 | 通项公式 | công thức số hạng tổng quát |
| 5 | 前n项和 | tổng $n$ số hạng đầu |
| 6 | 末项 | số hạng cuối |
| 7 | 等差中项 | trung bình cộng (trung tỉ của cấp số cộng) |
| 8 | 递增数列 | dãy số tăng |

### Nhóm 2 — Cấp số nhân

| STT | Thuật ngữ | Nghĩa |
|:---:|:----------|:------|
| 9 | 等比数列 | cấp số nhân |
| 10 | 公比 | công bội |
| 11 | 等比中项 | trung bình nhân |
| 12 | 正数项 | các số hạng dương |
| 13 | 无穷等比数列 | cấp số nhân lùi vô hạn |
| 14 | 收敛 | hội tụ |
| 15 | 公比绝对值 | giá trị tuyệt đối của công bội |
| 16 | 各项之和 | tổng các số hạng |

### Nhóm 3 — Dãy số và công thức truy hồi

| STT | Thuật ngữ | Nghĩa |
|:---:|:----------|:------|
| 17 | 数列 | dãy số |
| 18 | 项 | số hạng |
| 19 | 第n项 | số hạng thứ $n$ |
| 20 | 递推公式 | công thức truy hồi |
| 21 | 前n项 | $n$  số hạng đầu |
| 22 | 数列的项数 | số số hạng của dãy |
| 23 | 斐波那契数列 | dãy Fibonacci |
| 24 | 整数 | số nguyên |

---

## PHẦN B — BẢN DỊCH

**Câu 1 — mẫu.** Cho cấp số cộng $\{a_n\}$ có số hạng đầu $a_1 = 2$, công sai $d = 3$, khi đó $a_5$ bằng ( )

**Câu 2.** Cho cấp số nhân $\{a_n\}$ có tổng $n$ số hạng đầu $S_n = 4^{n-1} + t$, khi đó kết luận nào sau đây đúng ( )

**Câu 3.** Cho dãy số $\{a_n\}$ thỏa mãn $a_1 = 1$, $a_{n+1} = a_n + 2n$, khi đó $a_3$ bằng ( )

---

## PHẦN C — LỜI GIẢI 10 CÂU CHUẨN BỊ

**Câu 1.** `CAE-M-CD3-LX1-H-020` — **Đáp án C**

**Giải.** Từ $a_3 = a_1 + 2d = 4$ và $T_6 = 6a_1 + 15d = 27$ suy ra $a_1 = 2$, $d = 1$. Vậy $T_{11} = 11 \cdot 2 + 55 = 77$.

Dãy $\{b_n\}$: $b_1 = b_2 = 1$ và $b_{n+1} = b_1 + \cdots + b_n$. Suy ra $b_3 = 2$, $b_4 = 4$, $b_5 = 8$, tức $b_n = 2^{n-2}$ với $n \ge 2$. Tổng mười một số hạng đầu:

$$b_1 + b_2 + \cdots + b_{11} = 1 + (1 + 2 + 4 + \cdots + 512) = 1 + 1023 = 1024$$

Vậy tổng cần tìm là $77 + 1024 = 1101$.

---

**Câu 2.** `CAE-M-CD3-GV-M-112` — **Đáp án A**

**Giải.** Áp dụng công thức tổng 等比数列 với $a_1 = 1$, $q = 3$:

$$S_n = \frac{3^n - 1}{3 - 1} = \frac{3^n - 1}{2} = 40 \implies 3^n - 1 = 80 \implies 3^n = 81 \implies n = 4$$

---

**Câu 3.** `CAE-M-CD3-08.5-E-006` — **Đáp án D**

**Giải.** Đề cho 通项公式 (công thức số hạng tổng quát) $a_n = n^2 + 1$. Thay $n = 4$:

$$a_4 = 4^2 + 1 = 17$$

---

**Câu 4.** `CAE-M-CD3-LX1-E-017` — **Đáp án D**

**Giải.** Dùng tính chất 等比中项: bình phương mỗi số hạng bằng tích hai số hạng cách đều nó.

Từ $a_5 \cdot a_7 = a_6^2 = 36$ suy ra $a_6 = 6$ (các số hạng dương). Từ $a_3 a_9 = a_6^2$:

$$a_9 = \frac{36}{a_3} = \frac{36}{4} = 9$$

---

**Câu 5.** `CAE-M-CD3-LX2-M-023` — **Đáp án B**

**Giải.** Từ $S_3 = S_{10}$ suy ra tổng các số hạng từ $a_4$ đến $a_{10}$ bằng $0$. Nhóm bảy số hạng này thành ba cặp đối xứng quanh $a_7$:

$$a_4 + a_{10} = a_5 + a_9 = a_6 + a_8 = 2a_7$$

Vậy $6a_7 + a_7 = 7a_7 = 0$, suy ra $a_7 = 0$. Tương tự, $S_6 = S_k$ nghĩa là tổng từ $a_7$ đến $a_k$ bằng $0$. Vì $a_7 = 0$ và tổng đối xứng, giá trị duy nhất $k \ne 6$ thỏa mãn là $k = 7$.

---

**Câu 6.** `CAE-M-CD3-GV-M-102` — **Đáp án B**

**Giải.** Cấp số nhân với $a_1 = 3$, $q = 2$. Công thức số hạng tổng quát:

$$a_4 = a_1 q^3 = 3 \cdot 8 = 24$$

---

**Câu 7.** `CAE-M-CD3-08.6-E-011` — **Đáp án C**

**Giải.** Ba số $x, y, z$ lập thành 等比数列 khi và chỉ khi bình phương số hạng giữa bằng tích hai số hạng hai đầu:

$$y^2 = xz$$

Đây là 等比中项 (trung bình nhân) của $x$ và $z$.

---

**Câu 8.** `CAE-M-CD3-GV-E-111` — **Đáp án B**

**Giải.** Vì các số hạng đều dương nên $q > 0$. Từ $a_4 = a_2 q^2$ suy ra $16 = 4q^2$, vậy $q = 2$.

$$a_1 = \frac{a_2}{q} = 2, \qquad a_3 = a_2 q = 8 \implies a_1 + a_3 = 2 + 8 = 10$$

---

**Câu 9.** `CAE-M-CD3-LX2-E-021` — **Đáp án A**

**Giải.** Từ $a_1 + a_9 = 10$ và tính chất đối xứng chỉ số, $a_1 + a_9 = 2a_5$, suy ra $a_5 = 5$. Từ $S_{11} = 11a_6 = 66$ suy ra $a_6 = 6$.

$$d = a_6 - a_5 = 1$$

---

**Câu 10.** `CAE-M-CD3-08.2-E-002` — **Đáp án A**

**Giải.** Đề cho 等比数列 (cấp số nhân) với $b_1 = 1$, $b_5 = 16$. Từ công thức số hạng tổng quát $b_5 = b_1 q^4$ suy ra $q^4 = 16$, vậy $q = 2$ (lấy $q > 0$ vì các số hạng đều dương).

$$b_3 = b_1 q^2 = 1 \cdot 4 = 4 \implies b_1 + b_3 = 1 + 4 = 5$$

---

*Tài liệu nội bộ, CAE SHANGHAI.*
