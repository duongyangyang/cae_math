# BUỔI 15 — ĐÁP ÁN ĐỀ KIỂM TRA CUỐI CHUYÊN ĐỀ XÁC SUẤT VÀ THỐNG KÊ

> **Xác suất và Thống kê （概率与统计）**
>
> **Tài liệu giáo viên.** Học sinh làm đề trong `../hoc-sinh/06-de-kiem-tra.md`. Thời gian 35 phút, 24 câu.

---

## BẢNG ĐÁP ÁN

| Câu | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 |
|:----|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Đáp án | B | A | D | B | C | C | B | A | C | B | C | C |
| Câu | 13 | 14 | 15 | 16 | 17 | 18 | 19 | 20 | 21 | 22 | 23 | 24 |
|:----|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Đáp án | A | B | A | B | C | D | A | D | A | D | D | D |

**Phân bố độ khó:** 14 câu dễ, 7 câu trung bình, 3 câu khó.
**Phân bố theo buổi:** 12 câu buổi 15 (thống kê), 12 câu buổi 14 (xác suất).

---

## LỜI GIẢI NGẮN

**Câu 1.** `CAE-M-CD9-08.1-H-001` — **Đáp án B**

Tổng năm giá trị là $80 + 96 + 98 + 92 + 84 = 450$. Số trung bình cộng:

$$\bar{x} = \frac{450}{5} = 90$$

---

**Câu 2.** `CAE-M-CD8-08.6-H-033` — **Đáp án A**

Gọi $A$ là biến cố "thích bóng đá" và $B$ là biến cố "thích bóng rổ". Đề cho $P(A) = 0,6$, $P(B) = 0,3$ và $P(A \cap B) = 0,1$.

Xác suất có điều kiện:

$$P(A|B) = \frac{P(A \cap B)}{P(B)} = \frac{0,1}{0,3} = \frac{1}{3}$$

---

**Câu 3.** `CAE-M-CD9-08.2-H-004` — **Đáp án D**

Cộng thêm $5$ vào mọi giá trị thì số trung bình tăng thêm $5$, còn phương sai **không đổi** vì phép cộng chỉ dịch chuyển cả dãy số.

$$\bar{x}_{\text{mới}} = 85, \qquad s^2_{\text{mới}} = 25$$

---

**Câu 4.** `CAE-M-CD8-08.5-H-028` — **Đáp án B**

Biến cố đối của "xảy ra" là "không xảy ra", và hai xác suất có tổng bằng $1$:

$$P(\overline{A}) = 1 - p$$

---

**Câu 5.** `CAE-M-CD9-08.2-H-005` — **Đáp án C**

Số mốt là giá trị có tần số lớn nhất. Tần số lần lượt là $5$, $10$, $15$, $5$, lớn nhất là $15$ ứng với giá trị $30$ (đơn vị: 件).

**Chú ý.** Không lấy $40$ dù đây là giá trị lớn nhất. Mốt xét **tần số**, không xét độ lớn của giá trị.

---

**Câu 6.** `CAE-M-CD8-08.5-H-029` — **Đáp án C**

Công thức Bayes:

$$P(A|B) = \frac{P(B|A) \cdot P(A)}{P(B)}$$

**Chú ý.** Đáp án B thiếu mẫu $P(B)$, đáp án A nhầm sang công thức xác suất của hai biến cố độc lập.

---

**Câu 7.** `CAE-M-CD9-08.1-H-002` — **Đáp án B**

Mẫu có $10$ phần tử chẵn nên số trung vị là trung bình cộng của giá trị thứ $5$ và thứ $6$. Dãy đã sắp xếp là $50, 52, 55, 58, 60, 60, 62, 65, 68, 70$, hai giá trị giữa đều bằng $60$.

$$\frac{60 + 60}{2} = 60$$

---

**Câu 8.** `CAE-M-CD8-08.3-H-018` — **Đáp án A**

Gọi tổng số bóng là $n$. Từ $P(\text{đỏ}) = \dfrac{6}{n} = \dfrac{2}{5}$ suy ra $n = 15$. Số bóng xanh:

$$15 - 6 = 9$$

---

**Câu 9.** `CAE-M-CD9-08.3-H-009` — **Đáp án C**

Tổng số học sinh là $10 + 25 + 15 = 50$. Nhóm $160 \le h < 170$ có $25$ học sinh:

$$\frac{25}{50} = 0{,}5$$

---

**Câu 10.** `CAE-M-CD8-08.4-H-023` — **Đáp án B**

Hai biến cố xung khắc nên $P(A \cap B) = 0$:

$$P(A \cup B) = 0,6 + 0,3 = 0,9$$

---

**Câu 11.** `CAE-M-CD9-08.7-H-018` — **Đáp án C**

Học sinh đạt từ $70$ điểm trở lên gồm ba khoảng cuối: $20 + 15 + 5 = 40$ trên tổng $50$ em:

$$\frac{40}{50} = 80\%$$

---

**Câu 12.** `CAE-M-CD8-LX2-M-056` — **Đáp án C**

Tắt $3$ trong $5$ đèn có $C_5^3 = 10$ cách, đều đồng khả năng. Cần đếm số cách mà $2$ đèn còn sáng không kề nhau.

Hai đèn sáng không kề nhau, xếp vào $5$ vị trí. Số cách chọn $2$ vị trí không kề trong $5$ vị trí là $C_5^2 - 4 = 10 - 4 = 6$.

$$P = \frac{6}{10} = 0,6$$

---

**Câu 13.** `CAE-M-CD8-08.8-H-046` — **Đáp án A**

Dùng biến cố đối: "ít hơn $2$ nam" gồm $0$ nam hoặc $1$ nam. Số cách chọn $5$ người từ $25$ người là $C_{25}^5$.

Số cách chọn $0$ nam (tức $5$ nữ) là $C_{15}^5$. Số cách chọn $1$ nam và $4$ nữ là $C_{10}^1 C_{15}^4$.

Vậy xác suất có ít nhất $2$ nam:

$$P = 1 - \frac{C_{15}^5 + C_{10}^1 C_{15}^4}{C_{25}^5}$$

---

**Câu 14.** `CAE-M-CD8-08.5-H-025` — **Đáp án B**

Số cách chọn $2$ người từ $5$ người là $C_5^2 = 10$. Số cách chọn có A là $C_4^1 = 4$:

$$P = \frac{4}{10} = \frac{2}{5}$$

---

**Câu 15.** `CAE-M-CD9-08.8-H-022` — **Đáp án A**

Dãy đã sắp xếp có $10$ phần tử, số trung vị là trung bình cộng của giá trị thứ $5$ và thứ $6$, cả hai đều bằng $85$.

$$\frac{85 + 85}{2} = 85$$

---

**Câu 16.** `CAE-M-CD8-08.3-H-016` — **Đáp án B**

Dùng biến cố đối: "không trúng lần nào" có xác suất $0,9^3$. Vậy xác suất trúng ít nhất một lần là

$$1 - 0,9^3$$

---

**Câu 17.** `CAE-M-CD9-08.2-H-007` — **Đáp án C**

Biểu đồ thích hợp nhất để hiển thị tỉ lệ phần trăm của các nhóm trong một tổng thể là biểu đồ tròn (饼图, còn gọi là 扇形图).

---

**Câu 18.** `CAE-M-CD8-08.6-H-034` — **Đáp án D**

Mọi biến cố đều có xác suất nằm trong đoạn $[0, 1]$. Biến cố chắc chắn có xác suất $1$, biến cố không thể có xác suất $0$.

---

**Câu 19.** `CAE-M-CD9-08.4-H-013` — **Đáp án A**

Đếm tần số: số $80$ xuất hiện $3$ lần, $85$ xuất hiện $2$ lần, các giá trị còn lại $1$ lần. Vậy số mốt là $80$.

---

**Câu 20.** `CAE-M-CD8-LX1-E-052` — **Đáp án D**

Mỗi lần rút có $2$ kết quả (đỏ hoặc đen), rút $3$ lần có hoàn lại nên số điểm mẫu:

$$2^3 = 8$$

---

**Câu 21.** `CAE-M-CD9-08.6-H-016` — **Đáp án A**

Kích thước mẫu càng lớn thì các số đặc trưng của mẫu càng gần các số đặc trưng tương ứng của tổng thể.

---

**Câu 22.** `CAE-M-CD8-LX1-H-054` — **Đáp án D**

Từ $n(A \cup B) = 8$ suy ra $n(AB) = 6 + 4 - 8 = 2$, vậy $P(AB) = \dfrac{2}{12} = \dfrac{1}{6}$ (đáp án A đúng).

$P(A \cup B) = \dfrac{8}{12} = \dfrac{2}{3}$ (đáp án B đúng). Số phần tử của $\overline{A}B$ là $4 - 2 = 2$, nên $P(\overline{A}B) = \dfrac{2}{12} = \dfrac{1}{6}$ (đáp án C đúng).

Phần tử của $\overline{A}\overline{B}$ là $12 - 8 = 4$, nên $P(\overline{A}\overline{B}) = \dfrac{4}{12} = \dfrac{1}{3}$, khác $\dfrac{2}{3}$. Vậy đáp án D sai.

---

**Câu 23.** `CAE-M-CD9-08.5-H-014` — **Đáp án D**

Biểu đồ thân lá vẫn thể hiện được phân bố của dữ liệu (độ tập trung, khoảng biến thiên, hình dạng phân bố), nên phát biểu "không thể hiện được phân bố" là sai.

---

**Câu 24.** `CAE-M-CD9-08.2-H-006` — **Đáp án D**

Phương sai đo mức độ phân tán (离散程度) của dữ liệu quanh số trung bình.

**Chú ý.** Đáp án A nhầm sang khái niệm đo xu hướng tập trung; đáp án C sai vì đơn vị của phương sai là bình phương đơn vị dữ liệu, chỉ độ lệch chuẩn mới cùng đơn vị với dữ liệu gốc.

---

*Tài liệu nội bộ, CAE SHANGHAI.*
