# BUỔI 2 — LỜI GIẢI BÀI TẬP VỀ NHÀ

> **Hàm số: tính chất （函数的性质）**
>
> **Phiên bản:** 1.0.0, cập nhật 28.09.2026
> **Tài liệu giáo viên.** Dùng để chữa bài trên lớp và soạn đề kiểm tra. Học sinh chỉ nhận bảng đáp án (`../hoc-sinh/05-dap-an-bai-tap-ve-nha.md`).

---

## PHẦN D — BÀI TẬP VỀ NHÀ

### PHẦN BẮT BUỘC

#### Nhóm A — Tính chất hàm số

**Câu 1.** `CAE-M-CD4-08.2-E-017` — **Đáp án A**

**Giải.** Tập xác định: $|x| + 1 > 0$ với mọi $x$ nên biểu thức xác định trên $\mathbb{R}$. Tập $\mathbb{R}$ đối xứng qua $0$, thỏa điều kiện tiên quyết.

Tính $f(-x)$:

$$f(-x) = (-x)\ln(|-x| + 1) = -x\ln(|x| + 1) = -f(x)$$

Vậy $f$ là hàm lẻ.

**Cách nhanh.** Tích của hàm lẻ $x$ với hàm chẵn $\ln(|x|+1)$ cho hàm lẻ. Nhận ra quy tắc dấu của tích tiết kiệm cả bước biến đổi.

---

**Câu 2.** `CAE-M-CD4-08.1-M-015` — **Đáp án C**

**Giải.** Trên đoạn $[0, \pi]$, hàm $y = \sin x$ tăng trên $\left[0, \dfrac{\pi}{2}\right]$ và giảm trên $\left[\dfrac{\pi}{2}, \pi\right]$.

Giá trị lớn nhất đạt tại đỉnh $x = \dfrac{\pi}{2}$: $\sin\dfrac{\pi}{2} = 1$.

Giá trị nhỏ nhất đạt tại hai đầu mút: $\sin 0 = 0$ và $\sin\pi = 0$.

Vậy giá trị lớn nhất là $1$, giá trị nhỏ nhất là $0$.

**Bẫy.** Đáp án A là kết quả khi lấy miền giá trị của sin trên toàn trục số, nhưng đề giới hạn trên đoạn $[0,\pi]$ nên giá trị $-1$ không đạt được.

---

**Câu 3.** `CAE-M-CD4-08.3-E-029` — **Đáp án A**

**Giải.** Điều kiện căn ở mẫu: biểu thức dưới căn phải **dương** vì nằm ở mẫu.

$$x^2 - 3x + 2 > 0 \iff (x-1)(x-2) > 0 \iff x < 1 \ \text{hoặc} \ x > 2$$

Điều kiện logarit: $4 - x > 0 \iff x < 4$.

Giao hai điều kiện, giữ phần chung của $\big[(-\infty,1)\cup(2,+\infty)\big]$ với $(-\infty,4)$:

$$D = (-\infty, 1) \cup (2, 4)$$

**Chú ý.** Hai điểm $x = 1$ và $x = 2$ làm mẫu bằng $0$ nên bị loại. Nếu đặt điều kiện $\ge 0$ sẽ lấy nhầm hai điểm này.

---

**Câu 4.** `CAE-M-CD4-08.3-E-030` — **Đáp án B**

**Giải.** Tập xác định là $\mathbb{R}\setminus\{0\}$, đối xứng qua $0$.

$$f(-x) = \frac{\sin(-x)}{-x} = \frac{-\sin x}{-x} = \frac{\sin x}{x} = f(x)$$

Vậy $f$ là hàm chẵn.

**Nhận xét.** Thương của hai hàm lẻ là hàm chẵn. Hàm này là ví dụ kinh điển của hàm chẵn không phải đa thức, hay xuất hiện trong các câu hỏi lý thuyết.

---

**Câu 5.** `CAE-M-CD4-08.3-E-032` — **Đáp án C**

**Giải.** Đây là bài về đơn điệu của hàm bậc ba. Xét dấu đạo hàm $f'(x) = 3x^2 - 27 = 3(x^2 - 9)$.

Phương trình $f'(x) = 0$ có hai nghiệm $x = -3$ và $x = 3$. Hệ số $a = 3 > 0$ nên $f'(x) > 0$ ở ngoài khoảng hai nghiệm:

$$f'(x) > 0 \iff x < -3 \ \text{hoặc} \ x > 3$$

Vậy hàm đồng biến trên $(3, +\infty)$.

**Chú ý.** Đáp án A là khoảng nghịch biến, không phải đồng biến. Hàm bậc ba có hai cực trị thì chiều đơn điệu luân phiên: tăng, giảm, tăng.

---

**Câu 6.** `CAE-M-CD4-08.4-E-041` — **Đáp án B**

**Giải.** Hai hàm số được gọi là giống nhau khi có cùng tập xác định và cùng công thức giá trị trên tập đó.

- **A.** $f(x) = x$ có tập xác định $\mathbb{R}$; $g(x) = \dfrac{x^2}{x}$ có tập xác định $\mathbb{R}\setminus\{0\}$. Khác nhau. ✗
- **B.** $f(x) = |x|$ và $g(x) = \sqrt{x^2}$. Vì $\sqrt{x^2} = |x|$ với mọi $x \in \mathbb{R}$ và cả hai đều xác định trên $\mathbb{R}$, hai hàm giống nhau. ✓
- **C.** $f(x) = \sqrt{x^2-1}$ có tập xác định $(-\infty,-1]\cup[1,+\infty)$; $g(x)$ có tập xác định $[0,+\infty)$. Khác nhau. ✗
- **D.** $f(x) = 1$ có tập xác định $\mathbb{R}$; $g(x) = x^0$ có tập xác định $\mathbb{R}\setminus\{0\}$. Khác nhau. ✗

**Chú ý.** Đáp án D là bẫy kinh điển: $x^0 = 1$ đúng với mọi $x \neq 0$, nhưng tại $x = 0$ biểu thức $0^0$ không xác định.

---

**Câu 7.** `CAE-M-CD4-08.4-E-042` — **Đáp án C**

**Giải.** Hàm $g(x) = f(x-1)$ xác định khi và chỉ khi đối số của $f$ nằm trong tập xác định của $f$, tức $x - 1 \in [-2, 2]$.

Cộng $1$ vào cả ba vế:

$$-1 \le x \le 3$$

Vậy tập xác định của $g$ là $[-1, 3]$.

**Cách nhanh.** Dịch đồ thị sang phải $1$ đơn vị thì tập xác định cũng dịch sang phải $1$ đơn vị: $[-2,2]$ thành $[-1,3]$.

---

**Câu 8.** `CAE-M-CD4-08.4-E-044` — **Đáp án A**

**Giải.** Điều kiện logarit: biểu thức trong logarit phải dương.

$$x^2 - 4x + 3 > 0 \iff (x-1)(x-3) > 0$$

Vì hệ số bậc hai dương và dấu $> 0$, lấy ngoài khoảng hai nghiệm:

$$D = (-\infty, 1) \cup (3, +\infty)$$

**Bẫy.** Đáp án B là khoảng **trong** hai nghiệm, tương ứng với dấu $< 0$. Đọc kỹ chiều bất đẳng thức trước khi chọn khoảng.

---

**Câu 9.** `CAE-M-CD4-08.5-E-055` — **Đáp án C**

**Giải.** Với $x \neq \dfrac{1}{3}$, biểu thức $3x - 1$ nhận mọi giá trị thực khác $0$. Nghịch đảo của tập đó cũng là mọi số thực khác $0$.

$$\text{Tập giá trị} = (-\infty, 0) \cup (0, +\infty)$$

**Nhận xét.** Đáp án B là bẫy: giá trị $\dfrac{1}{3}$ bị loại là **đầu vào** của hàm, không phải đầu ra. Tập giá trị không liên quan đến giá trị làm mẫu bằng $0$.

---

**Câu 10.** `CAE-M-CD4-08.5-E-056` — **Đáp án B**

**Giải.** Hàm $f$ là hàm lẻ nên $f(-x) = -f(x)$, suy ra $f(-2) = -f(2)$.

Vì $2 > 0$ nên dùng công thức nhánh dương: $f(2) = 3(2)^2 + 1 = 13$.

$$f(-2) = -13$$

---

**Câu 11.** `CAE-M-CD4-08.5-E-060` — **Đáp án D**

**Giải.** Thay $x$ bằng $x - 1$ vào công thức $f(x) = 2^x$:

$$f(x-1) = 2^{x-1}$$

Dùng quy tắc lũy thừa $a^{m-n} = \dfrac{a^m}{a^n}$:

$$2^{x-1} = \frac{2^x}{2} = \frac{1}{2} \times 2^x$$

Vậy cả B và C đều đúng, hai biểu thức chỉ khác cách viết.

**Nhận xét.** Đề kiểm tra khả năng nhận ra hai biểu thức tương đương. Gặp đáp án dạng "B và C đều đúng", phải kiểm tra cả hai chứ không chọn đại một trong hai.

---

**Câu 12.** `CAE-M-CD4-08.5-M-068` — **Đáp án B**

**Giải.** Hệ số $\omega = -3$. Áp dụng $T = \dfrac{2\pi}{|\omega|}$:

$$T = \frac{2\pi}{|-3|} = \frac{2\pi}{3}$$

**Chú ý.** Dấu âm của $\omega$ không ảnh hưởng vì công thức dùng giá trị tuyệt đối. Pha $\dfrac{\pi}{3}$ cũng không ảnh hưởng, chỉ dịch đồ thị chứ không thay đổi chu kỳ.

---

**Câu 13.** `CAE-M-CD4-08.6-M-080` — **Đáp án D**

**Giải.** Kiểm tra từng hàm trên toàn $\mathbb{R}$:

- **A.** $f(x) = 2x - 1$ có hệ số góc $2 > 0$, là hàm tăng. ✗
- **B.** $f(x) = x$ có hệ số góc $1 > 0$, là hàm tăng. ✗
- **C.** $f(x) = e^x$ có cơ số $e > 1$, là hàm tăng. ✗
- **D.** $f(x) = 2^{-x} = \left(\dfrac{1}{2}\right)^x$ có cơ số $0 < \dfrac{1}{2} < 1$, là hàm giảm trên $\mathbb{R}$. ✓

**Cách nhanh.** Viết lại $2^{-x}$ thành lũy thừa với cơ số nhỏ hơn $1$ để nhận ra ngay chiều đơn điệu.

---

**Câu 14.** `CAE-M-CD4-08.7-E-082` — **Đáp án D**

**Giải.** Hàm số có hai ràng buộc. Điều kiện căn: $3x - 1 \ge 0 \implies x \ge \dfrac{1}{3}$.

Điều kiện phân thức: $x - 2 \neq 0 \implies x \neq 2$.

Giao hai điều kiện, giữ $\left[\dfrac{1}{3}, +\infty\right)$ và loại điểm $x = 2$:

$$D = \left[\dfrac{1}{3}, 2\right) \cup (2, +\infty)$$

**Bẫy.** Đáp án A là kết quả khi quên điều kiện mẫu khác $0$. Đáp án C sai vì đổi ngoặc vuông thành ngoặc tròn tại $\dfrac{1}{3}$, trong khi điều kiện căn là $\ge 0$ nên điểm đó được lấy.

---

**Câu 15.** `CAE-M-CD4-08.7-E-083` — **Đáp án C**

**Giải.** Kiểm tra từng hàm trên khoảng $(0, +\infty)$:

- **A.** $y = \dfrac{1}{x}$ là hàm giảm trên $(0, +\infty)$. ✗
- **B.** $y = -x^2$ có đỉnh tại $x = 0$, hệ số $a < 0$ nên giảm trên $(0, +\infty)$. ✗
- **C.** $y = \sqrt{x}$ là hàm tăng trên $[0, +\infty)$, do đó tăng trên $(0, +\infty)$. ✓
- **D.** $y = \cos x$ dao động tuần hoàn, không đơn điệu trên $(0, +\infty)$. ✗

---

**Câu 16.** `CAE-M-CD4-08.7-E-084` — **Đáp án D**

**Giải.** Hàm bậc hai $f(x) = x^2 - 10x + 10$ có $a = 1 > 0$ nên đạt giá trị nhỏ nhất tại đỉnh.

$$x_{\text{đỉnh}} = -\frac{-10}{2 \cdot 1} = 5$$

Đỉnh $x = 5$ nằm trong đoạn $[-10, 10]$, vậy giá trị nhỏ nhất trên đoạn là $f(5)$:

$$f(5) = 25 - 50 + 10 = -15$$

**Chú ý.** Phải kiểm tra đỉnh có thuộc đoạn không. Nếu đỉnh nằm ngoài, giá trị nhỏ nhất sẽ đạt tại đầu mút gần đỉnh hơn.

---

**Câu 17.** `CAE-M-CD4-08.2-E-019` — **Đáp án A**

**Giải.** Xét $f(x) = x^3 - 3x^2 + 2$ trên $[0,3]$. Đạo hàm $f'(x) = 3x^2 - 6x = 3x(x-2)$.

Phương trình $f'(x) = 0$ có hai nghiệm $x = 0$ và $x = 2$. Lập bảng giá trị tại các điểm tới hạn và hai đầu mút:

| $x$ | $0$ | $2$ | $3$ |
|:----|:---:|:---:|:---:|
| $f(x)$ | $2$ | $-2$ | $2$ |

Giá trị lớn nhất là $2$, giá trị nhỏ nhất là $-2$.

$$\max f + \min f = 2 + (-2) = 0$$

**Nhận xét.** Điểm $x = 0$ vừa là đầu mút vừa là nghiệm của đạo hàm, không cần xét riêng. Cần so sánh đủ ba giá trị vì cực trị địa phương có thể không phải cực trị toàn cục trên đoạn.

---

**Câu 18.** `CAE-M-CD4-08.8-E-095` — **Đáp án D**

**Giải.** Hàm số có ba ràng buộc. Điều kiện căn: $x^2 - 8x + 12 \ge 0 \iff (x-2)(x-6) \ge 0 \iff x \le 2$ hoặc $x \ge 6$.

Điều kiện logarit: $x - 5 > 0 \iff x > 5$.

Điều kiện mẫu khác $0$: $\ln(x-5) \neq 0 \iff x - 5 \neq 1 \iff x \neq 6$.

Giao ba điều kiện: phần chung của $\big[(-\infty,2]\cup[6,+\infty)\big]$ với $(5,+\infty)$ là $[6,+\infty)$. Loại tiếp điểm $x = 6$:

$$D = (6, +\infty)$$

**Bẫy.** Đây là dạng bài khó nhất của nhóm tập xác định vì có ba điều kiện, trong đó điều kiện mẫu chứa logarit. Đáp án A sai vì lấy cả điểm $x = 6$.

---

#### Nhóm B — Ôn tập tập hợp và bất đẳng thức

**Câu 19.** `CAE-M-CD1-08.1-E-005` — **Đáp án D**

**Giải.** Giải điều kiện $|x| < 2 \iff -2 < x < 2$. Vì $x \in \mathbb{Z}$ nên $A = \{-1, 0, 1\}$, có $n = 3$ phần tử.

Số tập con là $2^3 = 8$.

---

**Câu 20.** `CAE-M-CD1-08.5-E-019` — **Đáp án B**

**Giải.** Tập $A$: $x^2 - 4x + 3 = 0 \implies (x-1)(x-3) = 0 \implies A = \{1, 3\}$.

Phần bù trong $U = \{1,2,3,4,5\}$ là các phần tử của $U$ không thuộc $A$:

$$C_U A = \{2, 4, 5\}$$

---

**Câu 21.** `CAE-M-CD2-08.4-E-026` — **Đáp án C**

**Giải.** Điều kiện logarit: $x - 1 > 0 \iff x > 1$.

Vì cơ số $2 > 1$, hàm logarit đồng biến nên giữ nguyên chiều:

$$\log_2(x-1) \le 1 = \log_2 2 \iff x - 1 \le 2 \iff x \le 3$$

Giao với điều kiện xác định:

$$1 < x \le 3$$

**Chú ý.** Đáp án B là kết quả khi quên điều kiện $x > 1$. Với cơ số nhỏ hơn $1$ thì phải **đổi chiều** bất đẳng thức khi bỏ logarit.

---

**Câu 22.** `CAE-M-CD2-08.6-E-041` — **Đáp án A**

**Giải.** Đề dùng cụm 恒成立 (đúng với mọi $x$). Vì hệ số $a = 1 > 0$, chỉ cần điều kiện $\Delta < 0$:

$$\Delta = (-2)^2 - 4 \cdot 1 \cdot 2m = 4 - 8m < 0 \iff m > \frac{1}{2}$$

**Cách nhanh.** Gặp 恒成立 là dùng điều kiện $\Delta$, không cần biến đổi biểu thức. Gặp 有解 mới phải tìm giá trị nhỏ nhất hoặc lớn nhất.

---

**Câu 23.** `CAE-M-CD1-08.8-E-028` — **Đáp án B**

**Giải.** Điều kiện $5 < x \le 18$ với $x \in \mathbb{Z}$ cho tập $A = \{6, 7, \ldots, 18\}$.

Số phần tử: $18 - 6 + 1 = 13$.

Số tập con thực sự là $2^{13} - 1$.

**Bẫy.** Đáp án A ($2^{12}-1$) là kết quả khi đếm nhầm thành $12$ phần tử, thường do quên rằng đầu mút $18$ được lấy (dấu $\le$). Đọc kỹ ngoặc vuông và ngoặc tròn của hai đầu mút.

---

**Câu 24.** `CAE-M-CD2-08.6-E-038` — **Đáp án C**

**Giải.** Đặt $t = x - 2 > 0$, suy ra $x = t + 2$. Biểu thức trở thành:

$$x + \frac{1}{x-2} = t + 2 + \frac{1}{t} = \left(t + \frac{1}{t}\right) + 2$$

Áp dụng bất đẳng thức Cauchy cho hai số dương $t$ và $\dfrac{1}{t}$:

$$t + \frac{1}{t} \ge 2\sqrt{t \cdot \frac{1}{t}} = 2$$

Vậy biểu thức nhỏ nhất bằng $2 + 2 = 4$, dấu bằng xảy ra khi $t = 1$, tức $x = 3$.

**Chú ý.** Phải đổi biến để đưa về dạng Cauchy chuẩn. Áp dụng trực tiếp cho $x$ và $\dfrac{1}{x-2}$ sẽ sai vì tích không phải hằng số.

---

**Câu 25.** `CAE-M-CD2-08.5-E-032` — **Đáp án A**

**Giải.** Phân tích thành nhân tử: $x^3 - x^2 - 2x = x(x^2 - x - 2) = x(x+1)(x-2)$.

Ba nghiệm $\{-1, 0, 2\}$ chia trục số thành bốn khoảng. Hệ số bậc cao nhất dương nên dấu luân phiên, bắt đầu dấu $+$ ở khoảng ngoài cùng bên phải:

| Khoảng | Dấu tích |
|:-------|:--------:|
| $x < -1$ | $-$ |
| $-1 < x < 0$ | $+$ ✓ |
| $0 < x < 2$ | $-$ |
| $x > 2$ | $+$ ✓ |

Vì đề dùng dấu $\ge$, lấy cả ba nghiệm. Tập nghiệm:

$$[-1, 0] \cup [2, +\infty)$$

---

### PHẦN TỰ CHỌN

**Câu 1.** `CAE-M-CD4-08.4-M-045` — **Đáp án A**

**Giải.** Tập xác định $\mathbb{R}$ đối xứng qua $0$. Tính $f(-x)$:

$$f(-x) = (-x)^3 = -x^3 = -f(x)$$

Vậy $f$ là hàm lẻ. Mặt khác $y = x^3$ đồng biến trên $\mathbb{R}$ vì với $x_1 < x_2$ thì $x_1^3 < x_2^3$.

Vậy hàm vừa lẻ vừa đồng biến.

---

**Câu 2.** `CAE-M-CD4-08.8-E-101` — **Đáp án C**

**Giải.** Hệ số $\omega = 4$. Áp dụng $T = \dfrac{2\pi}{|\omega|}$:

$$T = \frac{2\pi}{4} = \frac{\pi}{2}$$

**Chú ý.** Hệ số $4$ nằm bên trong hàm sin nên ảnh hưởng trực tiếp đến chu kỳ. Pha $-\dfrac{\pi}{3}$ nằm ngoài nên không ảnh hưởng.

---

**Câu 3.** `CAE-M-CD4-LX3-H-136` — **Đáp án A**

**Giải.** Đặt $u = x + 1$, biểu thức trở thành $g(u) = u^2 + \cos u + a$.

Hàm $h(u) = u^2 + \cos u$ đạt giá trị nhỏ nhất tại $u = 0$: cả hai số hạng $u^2$ và $\cos u$ đều nhỏ nhất tại đó (vì $u^2 \ge 0$ và $\cos u \ge -1$ với dấu bằng tại $u = 0$).

$$h(0) = 0 + 1 = 1$$

Vậy giá trị nhỏ nhất của $f$ là $1 + a$. Đề cho giá trị này bằng $4$:

$$1 + a = 4 \implies a = 3$$

**Nhận xét.** Hai số hạng cùng đạt cực tiểu tại một điểm nên không cần khảo sát đạo hàm. Nhận ra điều này rút ngắn bài toán còn một dòng.

---

**Câu 4.** `CAE-M-CD4-08.2-M-024` — **Đáp án B**

**Giải.** Trên $[-\pi, 0]$, hàm $\sin x$ nhận giá trị trong $[-1, 0]$, nên $\sin^2 x$ nhận giá trị trong $[0, 1]$.

Giá trị lớn nhất của $\sin^2 x$ là $1$, đạt tại $x = -\dfrac{\pi}{2}$ (vì $\sin\left(-\dfrac{\pi}{2}\right) = -1$).

Vậy giá trị lớn nhất của $f(x) = \dfrac{\sin^2 x}{2}$ là $\dfrac{1}{2}$.

**Chú ý.** Bình phương làm mất dấu nên miền giá trị của $\sin^2 x$ vẫn là $[0,1]$ dù $x$ chỉ chạy trên nửa trục âm. Không được kết luận $\sin^2 x \le 0$.

---

**Câu 5.** `CAE-M-CD4-08.8-E-096` — **Đáp án D**

**Giải.** Kiểm tra từng hàm trên khoảng $(5, 10)$:

- **A.** $f(x) = x^2 - 12x + 30$ có đỉnh tại $x = 6$. Hàm giảm trên $(5,6)$ nhưng **tăng** trên $(6,10)$. Không giảm trên cả khoảng. ✗
- **B.** $f(x) = |x-8|$ có điểm gãy tại $x = 8$: giảm trên $(5,8)$, tăng trên $(8,10)$. ✗
- **C.** $f(x) = 2^{x-10}$ có cơ số $2 > 1$ nên tăng trên $\mathbb{R}$. ✗
- **D.** $f(x) = \log_{0.5}(x-4)$ có cơ số $0 < 0{,}5 < 1$ nên giảm trên tập xác định $(4, +\infty)$, do đó giảm trên $(5,10)$. ✓

**Chú ý.** Đáp án A và B đều có chiều đơn điệu đổi giữa khoảng. Đọc kỹ yêu cầu 在区间 (5,10) 上是减函数, tức phải giảm trên **toàn bộ** khoảng đó.

---

**Câu 6.** `CAE-M-CD4-LX2-H-126` — **Đáp án A**

**Giải.** Mẫu $3 - \cos x \ge 2 > 0$ với mọi $x$ nên tập xác định là $\mathbb{R}$, đối xứng qua $0$.

Tính $f(-x)$:

$$f(-x) = \frac{\sin(-x) - (-x)}{3 - \cos(-x)} = \frac{-\sin x + x}{3 - \cos x} = \frac{-(\sin x - x)}{3 - \cos x} = -f(x)$$

Vậy $f$ là hàm lẻ.

**Cách nhanh.** Tử là hiệu của hai hàm lẻ nên là hàm lẻ; mẫu là hàm chẵn và không triệt tiêu. Thương của hàm lẻ với hàm chẵn là hàm lẻ.

---

**Câu 7.** `CAE-M-CD4-08.6-E-069` — **Đáp án B**

**Giải.** Tập xác định $\mathbb{R}$ đối xứng qua $0$.

$$f(-x) = (-x)\cos(-x) = -x\cos x = -f(x)$$

Vậy $f$ là hàm lẻ.

**Cách nhanh.** Tích của hàm lẻ $x$ với hàm chẵn $\cos x$ là hàm lẻ.

---

**Câu 8.** `CAE-M-CD4-LX1-E-108` — **Đáp án D**

**Giải.** Hàm số có hai ràng buộc lồng nhau. Điều kiện căn: $\ln x \ge 0$.

Điều kiện logarit: $x > 0$.

Giải $\ln x \ge 0 \iff \ln x \ge \ln 1 \iff x \ge 1$ (vì cơ số $e > 1$).

Giao với $x > 0$, điều kiện $x \ge 1$ đã bao hàm điều kiện $x > 0$:

$$D = [1, +\infty)$$

**Bẫy.** Đáp án A chỉ xét điều kiện logarit mà bỏ điều kiện căn. Đây là dạng bài hai tầng: căn bọc ngoài logarit nên phải giải cả hai.

---

**Câu 9.** `CAE-M-CD4-LX3-M-133` — **Đáp án A**

**Giải.** Đặt $g(x) = x + \dfrac{1}{x}$. Với $x \neq 0$:

$$g(-x) = -x + \frac{1}{-x} = -\left(x + \frac{1}{x}\right) = -g(x)$$

Vậy $g$ là hàm lẻ. Giả thiết cho $F(x) = g(x)f(x)$ là hàm chẵn, tức $F(-x) = F(x)$:

$$g(-x)f(-x) = g(x)f(x) \implies -g(x)f(-x) = g(x)f(x)$$

Vì $f$ không đồng nhất bằng $0$ nên tồn tại $x_0$ với $f(x_0) \neq 0$, và tại đó $g(x_0) \neq 0$ (vì $g$ chỉ triệt tiêu tại $x = \pm i$, không thực). Rút gọn được $g(x)$:

$$-f(-x) = f(x) \implies f(-x) = -f(x)$$

Vậy $f$ là hàm lẻ.

**Nhận xét.** Quy tắc dấu của tích: lẻ $\times$ lẻ $=$ chẵn. Ở đây biết tích là chẵn và một nhân tử là lẻ, suy ra nhân tử còn lại phải là lẻ.

---

**Câu 10.** `CAE-M-CD4-LX2-H-127` — **Đáp án D**

**Giải.** Hàm $y = ax^3 - x$ có đạo hàm $y' = 3ax^2 - 1$.

Để hàm nghịch biến trên toàn $\mathbb{R}$, cần $y' \le 0$ với mọi $x$.

Xét $a = 0$: $y' = -1 < 0$ với mọi $x$, thỏa mãn.

Xét $a < 0$: $3ax^2 - 1 \le 0$ với mọi $x$ vì $3ax^2 \le 0$ và trừ thêm $1$, thỏa mãn.

Xét $a > 0$: khi $x$ lớn, $3ax^2 - 1 > 0$, hàm tăng, không thỏa mãn.

Vậy điều kiện là $a \le 0$.

**Chú ý.** Ba đáp án A, B, C đều là các giá trị dương cụ thể. Đề cho đáp án dạng điều kiện $a \le 0$ nên phải xét cả trường hợp $a = 0$, đây chính là điểm phân biệt với đáp án nhiễu.

---

**Câu 11.** `CAE-M-CD4-08.3-E-031` — **Đáp án B**

**Giải.** Đặt $y = \dfrac{x}{x^2+1}$. Vì $x^2 + 1 > 0$ với mọi $x$, nhân hai vế:

$$y(x^2 + 1) = x \iff yx^2 - x + y = 0$$

Phương trình này có nghiệm thực $x$ khi và chỉ khi $\Delta \ge 0$:

$$\Delta = 1 - 4y^2 \ge 0 \iff y^2 \le \frac{1}{4} \iff -\frac{1}{2} \le y \le \frac{1}{2}$$

Vậy giá trị lớn nhất là $\dfrac{1}{2}$, đạt tại $x = 1$.

**Cách nhanh.** Dùng bất đẳng thức Cauchy: $x^2 + 1 \ge 2|x|$ nên $\left|\dfrac{x}{x^2+1}\right| \le \dfrac{1}{2}$.

---

**Câu 12.** `CAE-M-CD4-LX1-E-111` — **Đáp án C**

**Giải.** Tập xác định là $\mathbb{R}\setminus\{0\}$. Tính đạo hàm:

$$y' = 2x - \frac{2}{x^2} = \frac{2x^3 - 2}{x^2} = \frac{2(x^3-1)}{x^2}$$

Vì $x^2 > 0$ với $x \neq 0$, dấu của $y'$ phụ thuộc vào $x^3 - 1$.

$$y' > 0 \iff x^3 > 1 \iff x > 1$$

Vậy hàm đồng biến trên $(1, +\infty)$.

**Bẫy.** Đáp án D là khoảng âm, nhưng trên $(-\infty,0)$ thì $x^3 < 1$ nên $y' < 0$, hàm **nghịch biến**. Kiểm tra dấu bằng một giá trị cụ thể nếu chưa chắc.

---

**Câu 13.** `CAE-M-CD4-LX2-H-125` — **Đáp án B**

**Giải.** Hàm $f(x) = \lg x + 2x - 5$ xác định trên $(0, +\infty)$ và đồng biến trên đó vì cả $\lg x$ và $2x$ đều tăng. Hàm đồng biến nên có tối đa một nghiệm.

Tính giá trị tại hai điểm nguyên liên tiếp:

$$f(2) = \lg 2 + 4 - 5 = \lg 2 - 1 < 0$$

$$f(3) = \lg 3 + 6 - 5 = \lg 3 + 1 > 0$$

Vì $f(2) < 0 < f(3)$ và hàm liên tục, nghiệm nằm trong khoảng $(2, 3)$.

$$k = 2$$

**Cách nhanh.** Không cần giải phương trình. Chỉ cần tìm hai số nguyên liên tiếp mà hàm đổi dấu, dựa vào tính liên tục và đơn điệu.

---

**Câu 14.** `CAE-M-CD4-08.5-E-058` — **Đáp án C**

**Giải.** Điều kiện hàm chẵn: $f(-x) = f(x)$ với mọi $x$.

$$f(-x) = (-x)^2 + 2a(-x) + a^2 + 1 = x^2 - 2ax + a^2 + 1$$

So sánh với $f(x) = x^2 + 2ax + a^2 + 1$:

$$x^2 - 2ax + a^2 + 1 = x^2 + 2ax + a^2 + 1 \implies -2ax = 2ax \implies 4ax = 0$$

Điều này đúng với mọi $x$ khi và chỉ khi $a = 0$.

**Cách nhanh.** Hàm bậc hai chẵn khi và chỉ khi hệ số của $x$ bằng $0$, tức trục đối xứng là trục tung.

---

**Câu 15.** `CAE-M-CD4-LX1-M-113` — **Đáp án C**

**Giải.** Hệ thức $f(2^x) = x$ cho biết $f$ là hàm ngược của hàm mũ cơ số $2$, tức $f(u) = \log_2 u$.

Tìm $x$ sao cho $2^x = 3$:

$$x = \log_2 3$$

Vậy $f(3) = \log_2 3$.

**Cách nhanh.** Không cần viết công thức tường minh của $f$. Chỉ cần giải $2^x = 3$ rồi thay vào vế phải.

---

## TỔNG KẾT LỖI THƯỜNG GẶP

Bảng chẩn đoán dùng khi chữa bài và khi soạn đề kiểm tra. Cột "Câu liên quan" trỏ tới `../hoc-sinh/03-bai-tap-ve-nha.md`.

| Lỗi | Câu liên quan | Cách cảnh báo học sinh |
|:----|:--------------|:-----------------------|
| Lấy hợp các điều kiện xác định thay vì giao | Câu 3, 14, 18 phần bắt buộc | Hàm số chỉ xác định khi **mọi** điều kiện đồng thời đúng, luôn giao |
| Biểu thức dưới căn nằm ở mẫu mà vẫn đặt dấu $\ge$ | Câu 3 phần bắt buộc | Căn ở mẫu thì mẫu phải khác $0$, điều kiện là dấu lớn hơn nghiêm ngặt |
| Quên điều kiện mẫu khác $0$ | Câu 14 phần bắt buộc | Viết điều kiện mẫu trước khi xét bất cứ điều kiện nào khác |
| Bỏ qua điều kiện của logarit bên trong căn | Câu 14 phần tự chọn | Đọc từ ngoài vào: căn trước, logarit sau, rồi giao lại |
| Tính $f(-x)$ trước khi kiểm tra tập xác định đối xứng | Câu 1, 4, 7 phần tự chọn | Tập xác định không đối xứng thì kết luận ngay là không chẵn không lẻ |
| Nhầm chu kỳ của sin với của tan | Câu 12 phần bắt buộc, Câu 10 phần tự chọn | Sin và cos dùng $\frac{2\pi}{\lvert\omega\rvert}$; tan và cot dùng $\frac{\pi}{\lvert\omega\rvert}$ |
| Lấy miền giá trị toàn trục số khi đề giới hạn trên đoạn | Câu 2 phần bắt buộc | Đọc kỹ khoảng giới hạn trước khi lấy giá trị lớn nhất, nhỏ nhất |
| Chỉ tính giá trị tại đỉnh mà bỏ qua hai đầu mút | Câu 16, 17 phần bắt buộc | Lập bảng giá trị tại đỉnh và hai đầu mút rồi so sánh |
| Nhầm tập giá trị với tập xác định của hàm phân thức | Câu 9 phần bắt buộc | Giá trị làm mẫu bằng $0$ là đầu vào bị loại, không phải đầu ra |
| Cho rằng hai hàm giống nhau chỉ cần cùng công thức | Câu 6 phần bắt buộc | Phải kiểm tra **cả** tập xác định, ví dụ $x$ và $\frac{x^2}{x}$ |
| Kết luận hàm không đổi chiều đơn điệu khi đề hỏi cả khoảng | Câu 13 phần tự chọn | Đọc kỹ cụm 在区间上是减函数, phải giảm trên toàn bộ khoảng |
| Quên trường hợp tham số bằng $0$ ở điều kiện đơn điệu toàn trục | Câu 15 phần tự chọn | Gặp $a \le 0$ thì luôn xét riêng $a = 0$ |

---

*Tài liệu nội bộ, CAE SHANGHAI.*
