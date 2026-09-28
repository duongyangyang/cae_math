# BUỔI 3 — HÀM SỐ: BẬC HAI, MŨ, LOGARIT, ĐẠO HÀM （二次函数·指数·对数·导数）

> **Module:** M2 · **Tỉ trọng đề thi:** ~8% · khoảng 3–5 câu
> **Tài liệu học tập, dùng trên lớp và tra cứu khi làm bài**

---

## 1. TỪ KHÓA NHẬN DẠNG ĐỀ

Đọc được từ khóa là xác định được dạng bài mà không cần dịch cả đề. Bảng dưới đây gom những từ khóa quyết định của chuyên đề này.

| Từ khóa | Nghĩa | Dạng bài tương ứng |
|:--------|:------|:-------------------|
| 顶点 | đỉnh | Tọa độ đỉnh parabol, giá trị lớn nhất nhỏ nhất |
| 对称轴 | trục đối xứng | Xác định trục đối xứng $x = -\dfrac{b}{2a}$ |
| 开口方向 | hướng mở của parabol | Xét dấu hệ số $a$ |
| 最值 | giá trị lớn nhất, nhỏ nhất | Tìm cực trị trên đoạn |
| 单调区间 | khoảng đơn điệu | Xét dấu đạo hàm |
| 极值 | cực trị | Tìm điểm cực đại, cực tiểu |
| 切线 | tiếp tuyến | Viết phương trình tiếp tuyến |
| 切线斜率 | hệ số góc tiếp tuyến | Tính $f'(x_0)$ |
| 换底公式 | công thức đổi cơ số | Biến đổi logarit khác cơ số |
| 指数增长 | tăng theo cấp số nhân | Mô hình thực tế $a^t$ |
| 复利 | lãi kép | Mô hình $A(1+r)^n$ |
| 可导 | khả vi | Dùng định nghĩa đạo hàm |

**Chú ý.** Ba từ khóa 顶点, 最值, 单调区间 đều dẫn về cùng một công cụ là trục đối xứng $x = -\dfrac{b}{2a}$. Nhận ra parabol là biết ngay phải đi tìm trục đối xứng trước khi làm bất cứ việc gì.

---

## 2. KIẾN THỨC TRỌNG TÂM

### 2.1. Hàm số bậc hai

**Định nghĩa 1 — Hàm số bậc hai.** Hàm số có dạng $y = ax^2 + bx + c$ với $a \neq 0$. Đồ thị là một parabol.

**Tính chất 1 — Đỉnh và trục đối xứng.** Parabol $y = ax^2 + bx + c$ có:

$$x_{\text{đỉnh}} = -\frac{b}{2a}, \qquad y_{\text{đỉnh}} = \frac{4ac - b^2}{4a}$$

Trục đối xứng là đường thẳng $x = -\dfrac{b}{2a}$.

**Tính chất 2 — Hướng mở của parabol.** Nếu $a > 0$ parabol mở lên trên và đỉnh là điểm cực tiểu. Nếu $a < 0$ parabol mở xuống dưới và đỉnh là điểm cực đại.

**Chú ý.** Công thức đỉnh viết dưới dạng $y = a\left(x + \dfrac{b}{2a}\right)^2 + \dfrac{4ac - b^2}{4a}$ (phương pháp tách bình phương 配方法) dùng khi đề yêu cầu tường minh tọa độ đỉnh.

**Tính chất 3 — Giá trị lớn nhất, nhỏ nhất trên đoạn $[m, n]$.** Gọi $x_0 = -\dfrac{b}{2a}$. So sánh ba giá trị $f(m)$, $f(n)$, $f(x_0)$ nếu $x_0 \in [m, n]$, ngược lại chỉ so sánh $f(m)$ và $f(n)$. Giá trị lớn nhất là số lớn nhất, giá trị nhỏ nhất là số nhỏ nhất trong tập vừa lập.

**Chú ý.** Trên một khoảng mở, hàm bậc hai chỉ có giá trị nhỏ nhất (hoặc lớn nhất) khi đỉnh nằm trong khoảng đó. Đề dùng cụm 在区间 $[m,n]$ 上有最小值 thì luôn kiểm tra đỉnh có thuộc đoạn hay không trước.

**Bẫy.** Học sinh thường lấy ngay $y_{\text{đỉnh}}$ làm giá trị nhỏ nhất mà quên rằng đỉnh có thể nằm ngoài đoạn đang xét. Khi đó giá trị nhỏ nhất đạt tại một đầu mút.

### 2.2. Hàm số mũ

**Định nghĩa 2 — Hàm số mũ.** Hàm số dạng $y = a^x$ với $a > 0$ và $a \neq 1$.

**Tính chất 4 — Tập xác định và tập giá trị.** Tập xác định là $\mathbb{R}$. Tập giá trị là $(0, +\infty)$. Đồ thị luôn đi qua điểm $(0, 1)$ và nhận trục hoành làm tiệm cận ngang.

**Tính chất 5 — Đơn điệu.** Nếu $a > 1$ thì $a^x$ đồng biến trên $\mathbb{R}$. Nếu $0 < a < 1$ thì $a^x$ nghịch biến trên $\mathbb{R}$.

**Tính chất 6 — So sánh lũy thừa cùng cơ số.** Với $a > 1$: $a^x < a^y \iff x < y$. Với $0 < a < 1$: $a^x < a^y \iff x > y$.

**Chú ý.** Chiều bất đẳng thức đảo khi cơ số nhỏ hơn $1$. Đây là lỗi phổ biến nhất ở dạng so sánh mũ.

**Tính chất 7 — Phép toán lũy thừa.** Với $a, b > 0$ và $m, n \in \mathbb{R}$:

$$a^m \cdot a^n = a^{m+n}, \qquad \frac{a^m}{a^n} = a^{m-n}, \qquad (a^m)^n = a^{mn}, \qquad (ab)^n = a^n b^n$$

### 2.3. Hàm số logarit

**Định nghĩa 3 — Logarit.** Với $a > 0$, $a \neq 1$ và $N > 0$: $\log_a N = b \iff a^b = N$. Trong đó $a$ gọi là cơ số, $N$ gọi là số lấy logarit.

**Định nghĩa 4 — Hàm số logarit.** Hàm số dạng $y = \log_a x$ với $a > 0$, $a \neq 1$.

**Tính chất 8 — Tập xác định và tập giá trị.** Tập xác định là $(0, +\infty)$, tập giá trị là $\mathbb{R}$. Đồ thị luôn đi qua điểm $(1, 0)$.

**Tính chất 9 — Đơn điệu.** Nếu $a > 1$ thì $\log_a x$ đồng biến trên $(0, +\infty)$. Nếu $0 < a < 1$ thì $\log_a x$ nghịch biến trên $(0, +\infty)$.

**Tính chất 10 — Logarit của một tích, thương, lũy thừa.** Với $M, N > 0$:

$$\log_a(MN) = \log_a M + \log_a N, \qquad \log_a \frac{M}{N} = \log_a M - \log_a N$$

$$\log_a M^n = n \log_a M, \qquad \log_a 1 = 0, \qquad \log_a a = 1$$

**Tính chất 11 — Công thức đổi cơ số.**

$$\log_a N = \frac{\log_m N}{\log_m a}$$

**Hệ quả.** $\log_a b \cdot \log_b a = 1$ và $\log_{a^m} b^n = \dfrac{n}{m}\log_a b$.

**Chú ý.** Công thức đổi cơ số biến mọi logarit về cùng một cơ số, thường chọn cơ số $10$ hoặc $e$. Đề cho hai logarit khác cơ số thì bước đầu tiên luôn là đổi về cùng cơ số.

**Tính chất 12 — So sánh logarit cùng cơ số.** Với $a > 1$: $\log_a M < \log_a N \iff M < N$. Với $0 < a < 1$: $\log_a M < \log_a N \iff M > N$. Trong cả hai trường hợp đều cần $M, N > 0$.

**Bẫy.** Điều kiện $N > 0$ (真数大于零) là điều kiện bắt buộc khi giải phương trình và bất phương trình logarit. Bỏ điều kiện này sẽ nhận nghiệm ngoại lai.

### 2.4. Đạo hàm

**Định nghĩa 5 — Đạo hàm tại một điểm.** Đạo hàm của $f(x)$ tại $x_0$ là giới hạn

$$f'(x_0) = \lim_{\Delta x \to 0} \frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x}$$

nếu giới hạn này tồn tại.

**Tính chất 13 — Ý nghĩa hình học.** $f'(x_0)$ là hệ số góc của tiếp tuyến với đồ thị $y = f(x)$ tại điểm $(x_0, f(x_0))$.

**Tính chất 14 — Phương trình tiếp tuyến.** Tiếp tuyến tại điểm $(x_0, y_0)$ của đồ thị $y = f(x)$ có phương trình

$$y - y_0 = f'(x_0)(x - x_0)$$

**Tính chất 15 — Bảng đạo hàm cơ bản.**

| Hàm số | Đạo hàm |
|:-------|:--------|
| $C$ (hằng số) | $0$ |
| $x^\alpha$ | $\alpha x^{\alpha - 1}$ |
| $\sin x$ | $\cos x$ |
| $\cos x$ | $-\sin x$ |
| $e^x$ | $e^x$ |
| $a^x$ | $a^x \ln a$ |
| $\ln x$ | $\dfrac{1}{x}$ |
| $\log_a x$ | $\dfrac{1}{x \ln a}$ |
| $\sqrt{x}$ | $\dfrac{1}{2\sqrt{x}}$ |
| $\dfrac{1}{x}$ | $-\dfrac{1}{x^2}$ |

**Tính chất 16 — Các quy tắc đạo hàm.**

$$[u \pm v]' = u' \pm v', \qquad (uv)' = u'v + uv'$$

$$\left(\frac{u}{v}\right)' = \frac{u'v - uv'}{v^2}, \qquad (Cu)' = Cu'$$

**Tính chất 17 — Đạo hàm hàm hợp.** Nếu $y = f(u)$ và $u = g(x)$ thì

$$y'_x = f'(u) \cdot g'(x)$$

**Chú ý.** Với $y = \ln(1 + x^2)$, đặt $u = 1 + x^2$ thì $y' = \dfrac{1}{u} \cdot 2x = \dfrac{2x}{1 + x^2}$. Quy tắc hàm hợp là công cụ bắt buộc khi biểu thức trong logarit hoặc trong căn không phải là $x$ trần.

**Tính chất 18 — Đạo hàm và tính đơn điệu.** Trên khoảng $(a, b)$: nếu $f'(x) > 0$ với mọi $x$ thì $f$ đồng biến; nếu $f'(x) < 0$ với mọi $x$ thì $f$ nghịch biến.

**Tính chất 19 — Điều kiện cực trị.** Nếu $f'(x)$ đổi dấu từ dương sang âm khi qua $x_0$ thì $x_0$ là điểm cực đại. Nếu $f'(x)$ đổi dấu từ âm sang dương khi qua $x_0$ thì $x_0$ là điểm cực tiểu.

**Chú ý.** Điều kiện $f'(x_0) = 0$ chỉ là điều kiện cần, chưa đủ để $x_0$ là điểm cực trị. Phải kiểm tra dấu của $f'(x)$ hai bên $x_0$, hoặc dùng bảng biến thiên.

**Tính chất 20 — Giá trị lớn nhất, nhỏ nhất trên đoạn $[a, b]$.** So sánh các giá trị $f(x_1), f(x_2), \dots, f(x_n)$ tại các điểm có $f'(x) = 0$ với $f(a)$ và $f(b)$. Số lớn nhất trong đó là giá trị lớn nhất, số nhỏ nhất là giá trị nhỏ nhất.

**Chú ý.** Điểm tới hạn (驻点) là nghiệm của $f'(x) = 0$. Trên đoạn đóng, giá trị lớn nhất và nhỏ nhất chỉ có thể đạt tại điểm tới hạn hoặc tại hai đầu mút.

---

## 3. CÁC DẠNG BÀI

### Dạng 1 — Giá trị lớn nhất, nhỏ nhất của hàm bậc hai trên đoạn

**Cách nhận dạng.** Đề cho hàm $y = ax^2 + bx + c$ và một đoạn $[m, n]$, hỏi 最小值 hoặc 最大值. Cũng gặp dạng ngược: cho giá trị nhỏ nhất trên một khoảng, yêu cầu tìm tham số.

**Cách làm.** Tính $x_0 = -\dfrac{b}{2a}$. Nếu $x_0 \in [m, n]$, giá trị nhỏ nhất (khi $a > 0$) là $f(x_0)$; ngược lại giá trị nhỏ nhất đạt tại đầu mút gần $x_0$ hơn. Lập bảng so sánh ba giá trị $f(m)$, $f(n)$, $f(x_0)$ rồi kết luận.

**Ví dụ 1.** Cho $f(x) = x^2 - 2x + m$ có giá trị nhỏ nhất bằng $-1$ trên $[1, +\infty)$. Tìm $m$.

**Giải.** Trục đối xứng $x_0 = -\dfrac{-2}{2 \cdot 1} = 1$. Vì $a = 1 > 0$ nên hàm đồng biến trên $[1, +\infty)$, giá trị nhỏ nhất đạt tại $x = 1$.

$$f(1) = 1 - 2 + m = m - 1$$

Điều kiện $m - 1 = -1$ cho $m = 0$.

---

### Dạng 2 — Biến đổi biểu thức mũ và tính giá trị

**Cách nhận dạng.** Đề cho biểu thức chứa $a^x$ với điều kiện ràng buộc, hoặc cho giá trị của hàm mũ tại một điểm và yêu cầu tính tại điểm khác. Cũng gặp dạng so sánh hai lũy thừa.

**Cách làm.** Đưa các lũy thừa về cùng cơ số rồi dùng Tính chất 6 và Tính chất 7. Với dạng cho $f(x) = a^{kx}$ và $f(t) = v$, giải ra $a$ rồi thay vào biểu thức cần tính.

**Ví dụ 2.** Cho $f(x) = a^{3x}$ với $a > 0$, $a \neq 1$, biết $f(x)$ nghịch biến và $f(2) = \dfrac{1}{64}$. Tìm $a$.

**Giải.** Từ $f(2) = a^6 = \dfrac{1}{64} = 2^{-6}$ suy ra $a = 2$ hoặc $a = \dfrac{1}{2}$.

Điều kiện nghịch biến buộc $0 < a < 1$. Vậy $a = \dfrac{1}{2}$.

**Cách nhanh.** Điều kiện nghịch biến loại ngay một trong hai nghiệm, không cần thử lại.

---

### Dạng 3 — Biến đổi logarit và công thức đổi cơ số

**Cách nhận dạng.** Đề cho hai logarit khác cơ số, hoặc cho $\log_a b = m$ và yêu cầu tính $\log_a (b^n)$ hay $\log_{a^k} b$. Từ khóa 换底公式 xuất hiện trực tiếp.

**Cách làm.** Dùng Tính chất 10 đưa logarit của tích, thương, lũy thừa về tổng, hiệu, tích với hệ số. Nếu hai logarit khác cơ số, dùng Tính chất 11 đổi về cùng cơ số trước.

**Ví dụ 3.** Cho $\log_2 3 = a$. Tính $\log_2 9$.

**Giải.** Vì $9 = 3^2$ nên theo Tính chất 10:

$$\log_2 9 = \log_2 3^2 = 2\log_2 3 = 2a$$

---

### Dạng 4 — Phương trình và bất phương trình mũ, logarit

**Cách nhận dạng.** Đề có dạng $\log_a f(x) \le b$, $a^{f(x)} > a^{g(x)}$, hoặc yêu cầu tìm tập xác định của hàm chứa logarit.

**Cách làm.** Với logarit, đặt điều kiện $f(x) > 0$ trước rồi mới biến đổi. Với bất phương trình mũ và logarit, chú ý chiều bất đẳng thức đảo khi cơ số nhỏ hơn $1$ (Tính chất 6 và Tính chất 12). Cuối cùng giao nghiệm với điều kiện xác định.

**Ví dụ 4.** Giải bất phương trình $\log_2(x - 1) \le 1$.

**Giải.** Điều kiện xác định: $x - 1 > 0 \iff x > 1$.

Vì cơ số $2 > 1$ nên hàm đồng biến, bất phương trình tương đương:

$$x - 1 \le 2^1 = 2 \iff x \le 3$$

Giao với điều kiện $x > 1$: tập nghiệm là $(1, 3]$.

**Bẫy.** Nếu cơ số nhỏ hơn $1$, chiều bất đẳng thức phải đảo. Với $\log_{0.5}(x-1) \le 1$ thì nghiệm là $x \ge 3$, ngược lại hoàn toàn.

---

### Dạng 5 — Tính đạo hàm bằng bảng và các quy tắc

**Cách nhận dạng.** Đề yêu cầu tìm $f'(x)$ hoặc $f'(x_0)$ của một hàm cho sẵn. Hàm có thể là tích, thương, hoặc hàm hợp.

**Cách làm.** Nhận dạng cấu trúc hàm trước: nếu là tích dùng quy tắc $(uv)'$, nếu là thương dùng $\left(\dfrac{u}{v}\right)'$, nếu có biểu thức lồng bên trong dùng quy tắc hàm hợp. Với $f'(x_0)$, tính $f'(x)$ rồi thay số.

**Ví dụ 5.** Tính $f'(2)$ với $f(x) = \dfrac{x^2}{x - 1}$.

**Giải.** Dùng quy tắc thương với $u = x^2$, $v = x - 1$:

$$f'(x) = \frac{2x(x-1) - x^2 \cdot 1}{(x-1)^2} = \frac{2x^2 - 2x - x^2}{(x-1)^2} = \frac{x^2 - 2x}{(x-1)^2}$$

Thay $x = 2$: $f'(2) = \dfrac{4 - 4}{1} = 0$.

---

### Dạng 6 — Phương trình tiếp tuyến của đồ thị

**Cách nhận dạng.** Đề có cụm 切线方程 (phương trình tiếp tuyến) hoặc 切线斜率, thường kèm điểm $P(x_0, y_0)$.

**Cách làm.** Ba bước cố định: tính $y_0 = f(x_0)$; tính $k = f'(x_0)$; viết $y - y_0 = k(x - x_0)$ rồi rút gọn về dạng $y = kx + b$.

**Ví dụ 6.** Viết phương trình tiếp tuyến của $y = \ln x + x^2$ tại điểm có hoành độ $x = 1$.

**Giải.** Tung độ tiếp điểm: $y_0 = \ln 1 + 1 = 1$.

Đạo hàm $f'(x) = \dfrac{1}{x} + 2x$, suy ra hệ số góc $k = f'(1) = 1 + 2 = 3$.

Phương trình tiếp tuyến:

$$y - 1 = 3(x - 1) \iff y = 3x - 2$$

---

### Dạng 7 — Cực trị và tính đơn điệu bằng đạo hàm

**Cách nhận dạng.** Đề hỏi 单调递增区间 (khoảng đồng biến), 极大值 (cực đại), 极小值 (cực tiểu), hoặc cho hàm chứa tham số có cực trị tại điểm cho trước.

**Cách làm.** Tính $f'(x)$, giải $f'(x) = 0$ tìm điểm tới hạn, lập bảng xét dấu $f'(x)$ trên các khoảng, rồi kết luận. Với bài cho cực trị tại $x_0$, dùng hai điều kiện $f'(x_0) = 0$ và $f(x_0) = $ giá trị cực trị để lập hệ.

**Ví dụ 7.** Tìm cực trị của hàm $f(x) = x^3 - 3x$.

**Giải.** Đạo hàm $f'(x) = 3x^2 - 3 = 3(x - 1)(x + 1)$, cho $f'(x) = 0$ được $x = 1$ và $x = -1$.

| Khoảng | $(-\infty, -1)$ | $x = -1$ | $(-1, 1)$ | $x = 1$ | $(1, +\infty)$ |
|:-------|:---------------:|:--------:|:---------:|:-------:|:--------------:|
| $f'(x)$ | $+$ | $0$ | $-$ | $0$ | $+$ |
| $f(x)$ | tăng | cực đại | giảm | cực tiểu | tăng |

$$f(-1) = -1 + 3 = 2, \qquad f(1) = 1 - 3 = -2$$

Cực đại bằng $2$ tại $x = -1$, cực tiểu bằng $-2$ tại $x = 1$. Khoảng đồng biến là $(-\infty, -1)$ và $(1, +\infty)$.

**Cách nhanh.** Với hàm bậc ba $f(x) = ax^3 + bx^2 + cx + d$ có hai điểm tới hạn $x_1 < x_2$: điểm tới hạn bên trái là cực đại, bên phải là cực tiểu khi $a > 0$; ngược lại khi $a < 0$. Chỉ cần thay số vào $f$, không cần lập bảng dấu.

---

## PHỤ LỤC — BỐI CẢNH KỲ THI

### Vị trí chuyên đề trong đề thi

| Đặc điểm | Thông số |
|:---------|:---------|
| Số câu | 48 câu trắc nghiệm |
| Thời gian | 60 phút |
| Thang điểm | 100 điểm |
| Ngôn ngữ | Tiếng Trung hoặc tiếng Anh (thí sinh chọn) |
| Máy tính | Không được dùng |

Thời gian trung bình mỗi câu là **1 phút 15 giây**. Chuyên đề hôm nay chiếm khoảng 8% đề thi, tức 3 đến 5 câu.

### Trọng số các nhóm nội dung

| Nhóm nội dung | Số câu | Tỉ trọng |
|:--------------|:------:|:--------:|
| Lượng giác | 8–11 | ~20% |
| Hình học giải tích | 8–10 | ~19% |
| Dãy số | 5–8 | ~13% |
| Hàm số | 5–7 | ~13% |
| Tập hợp & bất đẳng thức | 4–6 | ~10% |
| **Mũ & logarit** | **3–5** | **~8%** |
| Vector & số phức | 2–4 | ~6% |
| Xác suất & thống kê | 1–2 | ~3% |

Nhóm mũ và logarit tuy nhỏ nhưng xuất hiện lồng trong bài tập hợp, bài tìm tập xác định, và bài bất phương trình của các chuyên đề khác. Bảng đạo hàm và công thức logarit phải thuộc lòng vì không được dùng máy tính.

---

*Tài liệu nội bộ, CAE SHANGHAI.*
