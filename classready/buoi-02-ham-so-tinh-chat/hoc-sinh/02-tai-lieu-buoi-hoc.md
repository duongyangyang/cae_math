# BUỔI 2 — HÀM SỐ: TÍNH CHẤT （函数的性质）

> **Module:** M2 · **Tỉ trọng đề thi:** ~13% · khoảng 5–7 câu
> **Phiên bản:** 1.0.0, cập nhật 28.09.2026
> **Tài liệu học tập, dùng trên lớp và tra cứu khi làm bài**

---

## 1. TỪ KHÓA NHẬN DẠNG ĐỀ

Đọc được từ khóa là xác định được dạng bài mà không cần dịch cả đề. Bảng dưới đây gom những từ khóa quyết định của chuyên đề này.

| Từ khóa | Nghĩa | Dạng bài tương ứng |
|:--------|:------|:-------------------|
| 定义域 | tập xác định | Tìm điều kiện để hàm số có nghĩa |
| 值域 | tập giá trị | Tìm khoảng giá trị của $y$ |
| 单调性 | tính đơn điệu | Xét tăng giảm của hàm số |
| 增函数 | hàm số tăng | Chọn hàm đồng biến trên khoảng cho trước |
| 减函数 | hàm số giảm | Chọn hàm nghịch biến trên khoảng cho trước |
| 单调递增区间 | khoảng đồng biến | Tìm khoảng hàm số tăng |
| 奇函数 | hàm số lẻ | Kiểm tra $f(-x) = -f(x)$ |
| 偶函数 | hàm số chẵn | Kiểm tra $f(-x) = f(x)$ |
| 奇偶性 | tính chẵn lẻ | Phân loại hàm số theo chẵn, lẻ, không chẵn không lẻ |
| 周期 | chu kỳ | Tìm chu kỳ của hàm số |
| 最小正周期 | chu kỳ dương nhỏ nhất | Tính $T$ của hàm lượng giác |
| 分段函数 | hàm số cho bởi nhiều công thức | Tính giá trị hàm số tại một điểm |
| 最大值 / 最小值 | giá trị lớn nhất / nhỏ nhất | Tìm cực trị trên một khoảng |
| 零点 | nghiệm của phương trình $f(x)=0$ | Đếm số nghiệm |

**Chú ý.** Ba từ khóa quyết định cách xử lý là 定义域, 奇偶性 và 单调性. Gặp 定义域 thì viết ngay hệ điều kiện (mẫu khác $0$, biểu thức dưới căn không âm, biểu thức trong logarit dương) rồi giao lại. Gặp 奇偶性 thì kiểm tra tập xác định có đối xứng qua gốc tọa độ hay không **trước** khi tính $f(-x)$.

---

## 2. KIẾN THỨC TRỌNG TÂM

### 2.1. Hàm số và tập xác định

**Định nghĩa 1 — Hàm số.** Cho tập hợp $D \subset \mathbb{R}$. Hàm số $f$ xác định trên $D$ là một quy tắc đặt tương ứng mỗi số $x \in D$ với đúng một số $y \in \mathbb{R}$. Tập $D$ gọi là *tập xác định*, tập các giá trị $y$ gọi là *tập giá trị*.

**Tính chất 1 — Ba điều kiện xác định thường gặp.**

| Biểu thức | Điều kiện |
|:----------|:----------|
| $\dfrac{1}{g(x)}$ | $g(x) \neq 0$ |
| $\sqrt{g(x)}$ (bậc chẵn) | $g(x) \ge 0$ |
| $\log_a g(x)$ | $g(x) > 0$ |

**Chú ý.** Khi hàm số có nhiều điều kiện, phải **giao** tất cả các điều kiện lại, không hợp. Sai lầm phổ biến là lấy hợp rồi ra một khoảng rộng hơn thực tế.

**Ví dụ 1.** Tìm tập xác định của $f(x) = \sqrt{x - 4} + \log_2(5 - x)$.

**Giải.** Điều kiện căn: $x - 4 \ge 0 \implies x \ge 4$. Điều kiện logarit: $5 - x > 0 \implies x < 5$.

Giao hai điều kiện:

$$D = [4, 5)$$

---

### 2.2. Tính đơn điệu

**Định nghĩa 2 — Hàm số đồng biến.** Hàm số $f$ *đồng biến* (增函数) trên khoảng $D$ nếu với mọi $x_1, x_2 \in D$ mà $x_1 < x_2$ thì $f(x_1) < f(x_2)$. Đồ thị đi lên từ trái sang phải.

**Định nghĩa 3 — Hàm số nghịch biến.** Hàm số $f$ *nghịch biến* (减函数) trên khoảng $D$ nếu với mọi $x_1, x_2 \in D$ mà $x_1 < x_2$ thì $f(x_1) > f(x_2)$. Đồ thị đi xuống từ trái sang phải.

**Tính chất 2 — Đơn điệu của các hàm cơ bản.**

| Hàm số | Tập xác định | Đơn điệu |
|:-------|:-------------|:---------|
| $y = ax + b$ | $\mathbb{R}$ | tăng nếu $a > 0$, giảm nếu $a < 0$ |
| $y = x^2$ | $\mathbb{R}$ | giảm trên $(-\infty, 0)$, tăng trên $(0, +\infty)$ |
| $y = x^3$ | $\mathbb{R}$ | tăng trên $\mathbb{R}$ |
| $y = \sqrt{x}$ | $[0, +\infty)$ | tăng trên $[0, +\infty)$ |
| $y = \dfrac{1}{x}$ | $\mathbb{R}\setminus\{0\}$ | giảm trên từng khoảng xác định |
| $y = a^x$ | $\mathbb{R}$ | tăng nếu $a > 1$, giảm nếu $0 < a < 1$ |
| $y = \log_a x$ | $(0, +\infty)$ | tăng nếu $a > 1$, giảm nếu $0 < a < 1$ |

**Bẫy.** Hàm $y = \dfrac{1}{x}$ giảm trên từng khoảng $(-\infty,0)$ và $(0,+\infty)$ nhưng **không** giảm trên toàn tập xác định. Đề hay khai thác nhầm lẫn này.

**Tính chất 3 — Đơn điệu của hàm chứa giá trị tuyệt đối.** Hàm $y = a|x - x_0|$ với $a > 0$ nghịch biến trên $(-\infty, x_0]$ và đồng biến trên $[x_0, +\infty)$. Điểm gãy của đồ thị nằm tại $x = x_0$.

---

### 2.3. Tính chẵn lẻ

**Định nghĩa 4 — Hàm số chẵn.** Hàm số $f$ gọi là *hàm chẵn* (偶函数) nếu tập xác định đối xứng qua gốc tọa độ và với mọi $x$ trong tập xác định thì $f(-x) = f(x)$. Đồ thị nhận trục tung làm trục đối xứng.

**Định nghĩa 5 — Hàm số lẻ.** Hàm số $f$ gọi là *hàm lẻ* (奇函数) nếu tập xác định đối xứng qua gốc tọa độ và với mọi $x$ trong tập xác định thì $f(-x) = -f(x)$. Đồ thị nhận gốc tọa độ làm tâm đối xứng.

**Tính chất 4 — Điều kiện tiên quyết.** Muốn xét chẵn lẻ, tập xác định phải đối xứng qua $0$. Nếu tập xác định không đối xứng thì kết luận ngay là không chẵn không lẻ, không cần tính $f(-x)$.

**Tính chất 5 — Quy tắc dấu của tích và thương.**

| Phép toán | Kết quả |
|:----------|:--------|
| chẵn $\times$ chẵn | chẵn |
| lẻ $\times$ lẻ | chẵn |
| chẵn $\times$ lẻ | lẻ |

**Chú ý.** Hàm $f(x) = 0$ với tập xác định đối xứng vừa là hàm chẵn vừa là hàm lẻ. Đây là trường hợp duy nhất như vậy, và là bẫy của các câu hỏi lý thuyết.

**Ví dụ 2.** Xét tính chẵn lẻ của $f(x) = x\ln(|x| + 1)$.

**Giải.** Tập xác định là $\mathbb{R}$ (vì $|x| + 1 > 0$ với mọi $x$), đối xứng qua $0$.

Tính $f(-x)$:

$$f(-x) = (-x)\ln(|-x| + 1) = -x\ln(|x| + 1) = -f(x)$$

Vậy $f$ là hàm lẻ.

---

### 2.4. Tính tuần hoàn

**Định nghĩa 6 — Hàm số tuần hoàn.** Hàm số $f$ gọi là *tuần hoàn* với chu kỳ $T \neq 0$ nếu với mọi $x$ trong tập xác định thì $x + T$ cũng thuộc tập xác định và $f(x + T) = f(x)$. Số dương $T$ nhỏ nhất thỏa mãn gọi là *chu kỳ dương nhỏ nhất* (最小正周期).

**Tính chất 6 — Chu kỳ của hàm lượng giác.** Với $A \neq 0$ và $\omega \neq 0$:

$$y = A\sin(\omega x + \varphi), \quad y = A\cos(\omega x + \varphi) \implies T = \frac{2\pi}{|\omega|}$$

$$y = A\tan(\omega x + \varphi), \quad y = A\cot(\omega x + \varphi) \implies T = \frac{\pi}{|\omega|}$$

**Cách nhanh.** Hệ số $A$ và pha $\varphi$ không ảnh hưởng đến chu kỳ, chỉ có $\omega$ quyết định. Dấu âm trước $\omega$ cũng không ảnh hưởng vì công thức dùng $|\omega|$.

---

### 2.5. Giá trị lớn nhất, nhỏ nhất

**Định nghĩa 7 — Giá trị lớn nhất và nhỏ nhất.** Số $M$ gọi là *giá trị lớn nhất* của $f$ trên $D$ nếu $f(x) \le M$ với mọi $x \in D$ và tồn tại $x_0 \in D$ sao cho $f(x_0) = M$. Định nghĩa giá trị nhỏ nhất tương tự với chiều bất đẳng thức đảo lại.

**Tính chất 7 — Miền giá trị của hàm lượng giác.** Với mọi $x$:

$$-1 \le \sin x \le 1, \qquad -1 \le \cos x \le 1$$

**Tính chất 8 — Đỉnh parabol.** Hàm $f(x) = ax^2 + bx + c$ với $a > 0$ đạt giá trị nhỏ nhất tại $x = -\dfrac{b}{2a}$. Với $a < 0$ hàm đạt giá trị lớn nhất tại điểm đó.

**Chú ý.** Trên một đoạn cho trước, phải so sánh giá trị tại đỉnh với giá trị tại hai đầu mút. Đỉnh có thể nằm ngoài đoạn, khi đó cực trị đạt tại đầu mút.

**Tính chất 9 — Bất đẳng thức Cauchy với tổng bình phương.** Nếu $a^2 + b^2 = R^2$ thì giá trị lớn nhất của $pa + qb$ là $R\sqrt{p^2 + q^2}$. Đây là công thức cho đáp án trong vài giây, không cần biến đổi.

**Ví dụ 3.** Tìm giá trị lớn nhất của $f(x) = \sin x + \cos x$.

**Giải.** Áp dụng Tính chất 9 với $p = q = 1$ và $R = 1$ (vì $\sin^2 x + \cos^2 x = 1$):

$$\max f = \sqrt{1^2 + 1^2} = \sqrt{2}$$

---

## 3. CÁC DẠNG BÀI

### Dạng 1 — Tìm tập xác định của hàm số nhiều điều kiện

**Cách nhận dạng.** Đề hỏi 定义域 và hàm số chứa từ hai loại ràng buộc trở lên: căn thức, phân thức, logarit kết hợp.

**Cách làm.** Viết từng điều kiện riêng theo Tính chất 1, giải từng điều kiện về dạng khoảng, rồi **giao** các khoảng lại. Không quên điều kiện mẫu khác $0$ nằm bên trong căn.

**Ví dụ 4.** Tìm tập xác định của $f(x) = \dfrac{1}{\sqrt{x^2 - 3x + 2}} + \ln(4 - x)$.

**Giải.** Điều kiện căn ở mẫu: biểu thức dưới căn phải **dương** (vì nằm ở mẫu, không được bằng $0$):

$$x^2 - 3x + 2 > 0 \iff (x-1)(x-2) > 0 \iff x < 1 \ \text{hoặc} \ x > 2$$

Điều kiện logarit: $4 - x > 0 \iff x < 4$.

Giao hai điều kiện:

$$D = (-\infty, 1) \cup (2, 4)$$

**Bẫy.** Biểu thức dưới căn nằm ở **mẫu** thì điều kiện là dấu $>$ nghiêm ngặt, không phải $\ge$. Nếu chỉ đặt $\ge 0$ sẽ lấy nhầm hai điểm $x = 1$ và $x = 2$ vào tập xác định.

---

### Dạng 2 — Xét tính chẵn lẻ theo định nghĩa

**Cách nhận dạng.** Đề hỏi 奇函数, 偶函数, 奇偶性, hoặc hỏi 是奇函数的是 (hàm nào là hàm lẻ).

**Cách làm.** Bước 1: tìm tập xác định, kiểm tra đối xứng qua $0$. Bước 2: tính $f(-x)$ và rút gọn. Bước 3: so sánh với $f(x)$ và $-f(x)$.

**Ví dụ 5.** Xét tính chẵn lẻ của $f(x) = \dfrac{\sin x}{x}$.

**Giải.** Tập xác định là $\mathbb{R} \setminus \{0\}$, đối xứng qua $0$.

$$f(-x) = \frac{\sin(-x)}{-x} = \frac{-\sin x}{-x} = \frac{\sin x}{x} = f(x)$$

Vậy $f$ là hàm chẵn.

---

### Dạng 3 — Xác định tập giá trị

**Cách nhận dạng.** Đề hỏi 值域 và hàm số thuộc nhóm cơ bản: mũ, logarit, phân thức bậc nhất, lượng giác.

**Cách làm.** Dùng bảng đơn điệu và miền giá trị của hàm cơ bản. Với hàm phân thức dạng $\dfrac{1}{g(x)}$, tập giá trị là $\mathbb{R}$ trừ giá trị mà $y$ không thể đạt được.

**Ví dụ 6.** Tìm tập giá trị của $f(x) = \dfrac{1}{3x - 1}$.

**Giải.** Với mọi $x \neq \dfrac{1}{3}$, biểu thức $3x - 1$ nhận mọi giá trị thực khác $0$. Do đó $\dfrac{1}{3x-1}$ nhận mọi giá trị thực khác $0$.

$$\text{Tập giá trị} = (-\infty, 0) \cup (0, +\infty)$$

---

### Dạng 4 — Xét tính đơn điệu và tìm khoảng đơn điệu

**Cách nhận dạng.** Đề hỏi 单调递增区间, 增函数, 减函数, hoặc yêu cầu chọn hàm đồng biến trên một khoảng cho trước.

**Cách làm.** Với hàm cơ bản, tra bảng Tính chất 2. Với hàm bậc hai, xác định tọa độ đỉnh rồi chia khoảng theo đỉnh. Với hàm chứa giá trị tuyệt đối, tìm điểm gãy rồi chia khoảng theo điểm đó.

**Ví dụ 7.** Tìm khoảng đồng biến của $y = 2|x - 1|$.

**Giải.** Điểm gãy tại $x = 1$. Với $x \ge 1$: $y = 2(x-1) = 2x - 2$, hệ số góc dương nên hàm tăng. Với $x \le 1$: $y = 2(1-x) = -2x + 2$, hệ số góc âm nên hàm giảm.

$$y \ \text{đồng biến trên} \ [1, +\infty)$$

---

### Dạng 5 — Xét tính tuần hoàn

**Cách nhận dạng.** Đề hỏi 最小正周期 hoặc 周期 của hàm lượng giác.

**Cách làm.** Đọc hệ số $\omega$ trong biểu thức $\omega x + \varphi$, áp dụng $T = \dfrac{2\pi}{|\omega|}$ với sin và cos, $T = \dfrac{\pi}{|\omega|}$ với tan và cot. Bỏ qua hệ số biên độ và pha.

**Ví dụ 8.** Tìm chu kỳ dương nhỏ nhất của $f(x) = \sin\!\left(-3x + \dfrac{\pi}{3}\right)$.

**Giải.** Hệ số $\omega = -3$, áp dụng $T = \dfrac{2\pi}{|-3|}$:

$$T = \frac{2\pi}{3}$$

---

### Dạng 6 — Tìm giá trị lớn nhất, nhỏ nhất trên một khoảng

**Cách nhận dạng.** Đề hỏi 最大值, 最小值, 最大值为, hoặc hỏi tổng của giá trị lớn nhất và nhỏ nhất.

**Cách làm.** Với hàm bậc hai: tính tọa độ đỉnh, kiểm tra đỉnh có nằm trong khoảng không, so sánh với hai đầu mút. Với hàm lượng giác: dùng miền giá trị $[-1,1]$. Với biểu thức dạng $pa + qb$ ràng buộc $a^2 + b^2 = R^2$: dùng Tính chất 9.

**Ví dụ 9.** Tìm giá trị nhỏ nhất của $f(x) = x^2 - 10x + 10$ trên đoạn $[-10, 10]$.

**Giải.** Tọa độ đỉnh: $x = -\dfrac{-10}{2} = 5$, thuộc đoạn $[-10, 10]$.

$$f(5) = 25 - 50 + 10 = -15$$

Kiểm tra hai đầu mút: $f(-10) = 100 + 100 + 10 = 210$ và $f(10) = 100 - 100 + 10 = 10$. Cả hai đều lớn hơn $-15$.

$$\min f = -15$$

---

### Dạng 7 — Tính giá trị hàm số cho bởi nhiều công thức

**Cách nhận dạng.** Đề cho 分段函数 với hai nhánh và hỏi giá trị tại một điểm, hoặc hỏi $f(f(a))$.

**Cách làm.** Xác định giá trị của biến thuộc nhánh nào, dùng công thức của nhánh đó. Với $f(f(a))$, tính từ trong ra ngoài: tính $f(a)$ trước, rồi dùng kết quả đó làm đầu vào cho lần tính thứ hai.

**Ví dụ 10.** Cho $f(x) = \begin{cases} x + 5, & x < 7 \\ x^2 - 3x + 3, & x \ge 7 \end{cases}$. Tính $f(f(6))$.

**Giải.** Tính $f(6)$: vì $6 < 7$ nên dùng nhánh thứ nhất, $f(6) = 6 + 5 = 11$.

Tính $f(11)$: vì $11 \ge 7$ nên dùng nhánh thứ hai, $f(11) = 121 - 33 + 3 = 91$.

$$f(f(6)) = 91$$

**Nhận xét.** Với $f(f(a))$, giá trị trung gian $f(a)$ có thể rơi vào nhánh khác với nhánh của $a$. Ở đây $6$ dùng nhánh thứ nhất nhưng $11$ lại dùng nhánh thứ hai. Đọc kỹ điều kiện của từng nhánh ở mỗi bước.

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
| Dãy số | 5–8 | ~13% |
| **Hàm số** | **5–7** | **~13%** |
| Tập hợp & bất đẳng thức | 4–6 | ~10% |
| Mũ & logarit | 3–5 | ~8% |
| Vector & số phức | 2–4 | ~6% |
| Xác suất & thống kê | 1–2 | ~3% |

Chuyên đề hôm nay chiếm khoảng 13% đề thi. Đây là chuyên đề có số câu biến thiên rộng nhất trong đề: câu hỏi về 定义域 và 奇偶性 xuất hiện gần như mọi đề vì chúng là bước chuẩn bị cho các bài về đạo hàm, logarit và lượng giác ở các buổi sau.

---

*Tài liệu nội bộ, CAE SHANGHAI.*
