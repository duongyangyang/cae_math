# BUỔI 5 — LƯỢNG GIÁC: HÀM SỐ VÀ PHƯƠNG TRÌNH （三角函数的图像与方程）

> **Module:** M2 · **Tỉ trọng đề thi:** ~20% (cả chuyên đề Lượng giác) · khoảng 8–11 câu
> **Tài liệu học tập, dùng trên lớp và tra cứu khi làm bài**

---

## 1. TỪ KHÓA NHẬN DẠNG ĐỀ

Đọc được từ khóa là xác định được dạng bài mà không cần dịch cả đề. Bảng dưới đây gom những từ khóa quyết định của chuyên đề này.

| Từ khóa | Nghĩa | Dạng bài tương ứng |
|:--------|:------|:-------------------|
| 最小正周期 | chu kỳ dương nhỏ nhất | Tìm chu kỳ của hàm số lượng giác |
| 周期 | chu kỳ | Xác định chu kỳ từ biểu thức |
| 值域 | tập giá trị | Tìm khoảng giá trị của $y$ |
| 最大值 | giá trị lớn nhất | Tìm giá trị lớn nhất của hàm số |
| 最小值 | giá trị nhỏ nhất | Tìm giá trị nhỏ nhất của hàm số |
| 定义域 | tập xác định | Tìm điều kiện để hàm số có nghĩa |
| 奇函数 | hàm số lẻ | Kiểm tra $f(-x) = -f(x)$ |
| 偶函数 | hàm số chẵn | Kiểm tra $f(-x) = f(x)$ |
| 单调区间 | khoảng đơn điệu | Tìm khoảng tăng, khoảng giảm |
| 增函数 | hàm số tăng | Hàm đồng biến trên khoảng cho trước |
| 减函数 | hàm số giảm | Hàm nghịch biến trên khoảng cho trước |
| 对称 | đối xứng | Xác định trục hoặc tâm đối xứng của đồ thị |
| 解方程 | giải phương trình | Tìm nghiệm của phương trình lượng giác |
| 解集 | tập nghiệm | Viết nghiệm dưới dạng tập hợp |
| 零点 | điểm không | Nghiệm của phương trình $f(x) = 0$ |
| 振幅 | biên độ | Hệ số $A$ trong $y = A\sin(\omega x + \varphi)$ |

**Chú ý.** Hai từ khóa 最大值 (lớn nhất) và 最小值 (nhỏ nhất) quyết định toàn bộ hướng làm. Gặp 最大值 thì lấy biên trên của tập giá trị, gặp 最小值 thì lấy biên dưới. Đọc nhầm là chọn sai đáp án dù biết cách giải.

**Chú ý.** Từ khóa 最小正周期 có chữ 最小 (nhỏ nhất) ở đầu. Hàm $\sin$ và $\cos$ có vô số chu kỳ, đề luôn hỏi chu kỳ **dương nhỏ nhất**. Công thức cho $y = A\sin(\omega x + \varphi)$ là $T = \dfrac{2\pi}{|\omega|}$.

---

## 2. KIẾN THỨC TRỌNG TÂM

### 2.1. Tập xác định, tập giá trị và chu kỳ

**Định nghĩa 1 — Hàm số tuần hoàn.** Hàm số $y = f(x)$ được gọi là *tuần hoàn* nếu tồn tại số $T \neq 0$ sao cho với mọi $x$ thuộc tập xác định, $f(x + T) = f(x)$.

**Định nghĩa 2 — Chu kỳ dương nhỏ nhất.** Số $T > 0$ nhỏ nhất thỏa mãn $f(x + T) = f(x)$ được gọi là *chu kỳ dương nhỏ nhất* của hàm số tuần hoàn.

**Chú ý.** Đề thi luôn hỏi 最小正周期 (chu kỳ dương nhỏ nhất) chứ không hỏi chu kỳ chung. Hàm $\sin$ nhận mọi bội của $2\pi$ làm chu kỳ, nhưng chỉ có duy nhất một chu kỳ dương nhỏ nhất.

**Tính chất 1 — Bảng tóm tắt ba hàm số lượng giác.**

| Hàm số | Tập xác định | Tập giá trị | Chu kỳ dương nhỏ nhất | Tính chẵn lẻ |
|:-------|:-------------|:------------|:---------------------:|:-------------|
| $y = \sin x$ | $\mathbb{R}$ | $[-1, 1]$ | $2\pi$ | lẻ |
| $y = \cos x$ | $\mathbb{R}$ | $[-1, 1]$ | $2\pi$ | chẵn |
| $y = \tan x$ | $x \neq \dfrac{\pi}{2} + k\pi$ | $\mathbb{R}$ | $\pi$ | lẻ |

**Tính chất 2 — Chu kỳ của hàm số dạng $y = A\sin(\omega x + \varphi)$.** Với $\omega \neq 0$:

$$T = \frac{2\pi}{|\omega|}$$

Với $y = A\tan(\omega x + \varphi)$: $T = \dfrac{\pi}{|\omega|}$.

**Chú ý.** Chu kỳ **không phụ thuộc** vào biên độ $A$ và pha ban đầu $\varphi$. Chỉ hệ số $\omega$ của $x$ quyết định chu kỳ. Đây là lý do đề hay cho $A$ và $\varphi$ phức tạp để gây nhiễu.

**Cách nhanh.** Công thức nhớ gọn: chu kỳ bằng $2\pi$ chia cho hệ số đứng trước $x$. Với $\tan$ thì thay $2\pi$ bằng $\pi$. Không cần biến đổi biểu thức.

**Tính chất 3 — Tính chẵn lẻ.** Hàm $\sin$ và $\tan$ là hàm lẻ: $\sin(-x) = -\sin x$, $\tan(-x) = -\tan x$. Hàm $\cos$ là hàm chẵn: $\cos(-x) = \cos x$.

**Tính chất 4 — Tập giá trị của hàm bậc nhất theo sin và cos.** Hàm $y = a\sin x + b\cos x$ có tập giá trị là $\left[-\sqrt{a^2 + b^2},\ \sqrt{a^2 + b^2}\right]$.

**Cách nhanh.** Giá trị lớn nhất của $a\sin x + b\cos x$ là $\sqrt{a^2 + b^2}$, giá trị nhỏ nhất là $-\sqrt{a^2 + b^2}$. Với $\sin x + \cos x$ có $a = b = 1$ nên giá trị lớn nhất là $\sqrt{2}$. Công thức này cho đáp án trong vài giây, không cần biến đổi thành $\sqrt{2}\sin\left(x + \dfrac{\pi}{4}\right)$.

**Tính chất 5 — Tập giá trị của hàm bậc hai theo sin hoặc cos.** Với $y = a\sin^2 x + b\sin x + c$, đặt $t = \sin x$ với $t \in [-1, 1]$. Bài toán trở thành tìm giá trị lớn nhất, nhỏ nhất của hàm bậc hai $y = at^2 + bt + c$ trên đoạn $[-1, 1]$.

**Chú ý.** Đỉnh của parabol $t_0 = -\dfrac{b}{2a}$ có thể nằm **ngoài** đoạn $[-1, 1]$. Phải so sánh $t_0$ với hai đầu mút trước khi kết luận, không được thay $t_0$ một cách máy móc.

### 2.2. Đồ thị và tính đơn điệu

**Tính chất 6 — Tính đơn điệu của hàm $\sin$ và $\cos$.**

| Hàm số | Khoảng đồng biến | Khoảng nghịch biến |
|:-------|:-----------------|:-------------------|
| $y = \sin x$ | $\left[-\dfrac{\pi}{2} + 2k\pi,\ \dfrac{\pi}{2} + 2k\pi\right]$ | $\left[\dfrac{\pi}{2} + 2k\pi,\ \dfrac{3\pi}{2} + 2k\pi\right]$ |
| $y = \cos x$ | $[-\pi + 2k\pi,\ 2k\pi]$ | $[2k\pi,\ \pi + 2k\pi]$ |
| $y = \tan x$ | $\left(-\dfrac{\pi}{2} + k\pi,\ \dfrac{\pi}{2} + k\pi\right)$ | không có |

**Chú ý.** Hàm $\tan$ đồng biến trên **từng khoảng** xác định của nó, nhưng **không** đồng biến trên toàn tập xác định. Đây là bẫy rất hay gặp khi đề hỏi tính đơn điệu của $\tan$.

**Tính chất 7 — Tính đối xứng của đồ thị.** Đồ thị $y = \cos x$ nhận trục $Oy$ làm trục đối xứng. Đồ thị $y = \sin x$ và $y = \tan x$ nhận gốc tọa độ $O$ làm tâm đối xứng.

**Nhận xét.** Tính đối xứng và tính chẵn lẻ là hai cách phát biểu của cùng một sự kiện. Đồ thị hàm chẵn đối xứng qua trục tung, đồ thị hàm lẻ đối xứng qua gốc tọa độ.

### 2.3. Phương trình lượng giác cơ bản

**Định nghĩa 3 — Phương trình lượng giác cơ bản.** Phương trình lượng giác cơ bản là phương trình có dạng $\sin x = m$, $\cos x = m$, $\tan x = m$ hoặc $\cot x = m$, trong đó vế trái chỉ chứa một hàm lượng giác của ẩn $x$ và vế phải là một hằng số.

**Chú ý.** Điều kiện $|m| \le 1$ chỉ áp dụng cho $\sin x = m$ và $\cos x = m$. Phương trình $\tan x = m$ và $\cot x = m$ có nghiệm với mọi giá trị thực của $m$.

**Tính chất 8 — Công thức nghiệm của bốn phương trình cơ bản.**

$$\sin x = m \ (|m| \le 1) \iff x = \arcsin m + 2k\pi \ \text{hoặc} \ x = \pi - \arcsin m + 2k\pi$$

$$\cos x = m \ (|m| \le 1) \iff x = \pm\arccos m + 2k\pi$$

$$\tan x = m \iff x = \arctan m + k\pi$$

$$\cot x = m \iff x = \text{arccot}\, m + k\pi$$

Trong mọi công thức, $k \in \mathbb{Z}$.

**Chú ý.** Phương trình $\sin$ có **hai họ nghiệm**, phương trình $\cos$ gộp được thành một họ với dấu $\pm$, phương trình $\tan$ và $\cot$ chỉ có **một họ**. Nhớ sai số họ nghiệm là mất điểm chắc chắn.

**Chú ý.** Điều kiện $|m| \le 1$ là bắt buộc với $\sin$ và $\cos$. Đề hỏi giá trị nào **không thể** là $\sin\alpha$ thì chỉ cần so sánh giá trị đó với $1$. Số nào lớn hơn $1$ về giá trị tuyệt đối thì loại.

**Tính chất 9 — Giá trị đặc biệt cần nhớ.**

| Phương trình | Nghiệm trên một chu kỳ |
|:-------------|:-----------------------|
| $\sin x = 0$ | $x = k\pi$ |
| $\sin x = 1$ | $x = \dfrac{\pi}{2} + 2k\pi$ |
| $\sin x = -1$ | $x = -\dfrac{\pi}{2} + 2k\pi$ |
| $\cos x = 0$ | $x = \dfrac{\pi}{2} + k\pi$ |
| $\cos x = 1$ | $x = 2k\pi$ |
| $\cos x = -1$ | $x = \pi + 2k\pi$ |
| $\tan x = 0$ | $x = k\pi$ |

**Tính chất 10 — Phương trình bậc hai theo một hàm lượng giác.** Với phương trình dạng $a\sin^2 x + b\sin x + c = 0$, đặt $t = \sin x$ với điều kiện $t \in [-1, 1]$, giải phương trình bậc hai theo $t$, rồi loại nghiệm nằm ngoài đoạn $[-1, 1]$.

**Chú ý.** Sau khi giải ra $t$, **luôn phải kiểm tra** $t \in [-1, 1]$ trước khi giải tiếp $x$. Nghiệm $t$ nằm ngoài đoạn này không cho nghiệm $x$ nào.

---

## 3. CÁC DẠNG BÀI

### Dạng 1 — Xác định chu kỳ của hàm số lượng giác

**Cách nhận dạng.** Đề có từ khóa 最小正周期 (chu kỳ dương nhỏ nhất) hoặc 周期 (chu kỳ). Hàm số cho dưới dạng $y = A\sin(\omega x + \varphi)$, $y = A\cos(\omega x + \varphi)$ hoặc $y = A\tan(\omega x + \varphi)$.

**Cách làm.** Đọc hệ số $\omega$ đứng trước $x$. Với $\sin$ và $\cos$, chu kỳ là $\dfrac{2\pi}{|\omega|}$. Với $\tan$, chu kỳ là $\dfrac{\pi}{|\omega|}$. Biên độ $A$ và pha $\varphi$ không ảnh hưởng đến kết quả.

**Ví dụ 1.** Tìm chu kỳ dương nhỏ nhất của hàm số $y = 3\sin\left(2x + \dfrac{\pi}{6}\right)$.

**Giải.** Hệ số của $x$ là $\omega = 2$. Áp dụng công thức $T = \dfrac{2\pi}{|\omega|}$:

$$T = \frac{2\pi}{2} = \pi$$

Biên độ $A = 3$ và pha $\dfrac{\pi}{6}$ không ảnh hưởng đến chu kỳ.

**Nhận xét.** Với hàm $y = \cos\left(\dfrac{x}{3} + \dfrac{\pi}{6}\right)$, hệ số $\omega = \dfrac{1}{3}$ nên chu kỳ là $\dfrac{2\pi}{1/3} = 6\pi$. Hệ số càng nhỏ thì chu kỳ càng lớn.

---

### Dạng 2 — Xét tính chẵn lẻ của hàm số lượng giác

**Cách nhận dạng.** Đề có từ khóa 奇函数 (hàm lẻ) hoặc 偶函数 (hàm chẵn), yêu cầu xác định tính chẵn lẻ của một hàm số có chứa $\sin$, $\cos$ hoặc $\tan$.

**Cách làm.** Tính $f(-x)$ rồi so sánh với $f(x)$ và $-f(x)$. Nếu $f(-x) = f(x)$ thì hàm chẵn; nếu $f(-x) = -f(x)$ thì hàm lẻ; nếu không rơi vào trường hợp nào thì hàm không chẵn không lẻ.

**Ví dụ 2.** Xét tính chẵn lẻ của hàm số $f(x) = \dfrac{\sin x}{x}$.

**Giải.** Tập xác định là $\mathbb{R} \setminus \{0\}$, đối xứng qua gốc tọa độ. Tính:

$$f(-x) = \frac{\sin(-x)}{-x} = \frac{-\sin x}{-x} = \frac{\sin x}{x} = f(x)$$

Vậy $f(x)$ là hàm chẵn.

**Nhận xét.** Tích của hai hàm lẻ là hàm chẵn, tích của hàm lẻ với hàm chẵn là hàm lẻ. Với $f(x) = x\sin x$: $x$ lẻ, $\sin x$ lẻ, nên tích là hàm chẵn. Quy tắc này cho đáp án ngay mà không cần tính.

---

### Dạng 3 — Tìm giá trị lớn nhất, nhỏ nhất của hàm số lượng giác

**Cách nhận dạng.** Đề có từ khóa 最大值 hoặc 最小值, hàm số cho dưới dạng $y = A\sin(\omega x + \varphi) + B$ hoặc $y = A\cos(\omega x + \varphi) + B$.

**Cách làm.** Dùng $|\sin| \le 1$ và $|\cos| \le 1$. Biểu thức $A\sin(\omega x + \varphi)$ có giá trị lớn nhất $|A|$ và nhỏ nhất $-|A|$. Cộng thêm hằng số $B$ vào cả hai đầu.

**Ví dụ 3.** Tìm giá trị lớn nhất và nhỏ nhất của $y = 2\sin\left(2x - \dfrac{\pi}{6}\right) + 1$.

**Giải.** Vì $-1 \le \sin\left(2x - \dfrac{\pi}{6}\right) \le 1$ nên nhân với $2$:

$$-2 \le 2\sin\left(2x - \frac{\pi}{6}\right) \le 2$$

Cộng $1$ vào cả ba vế:

$$-1 \le y \le 3$$

Vậy giá trị lớn nhất là $3$, giá trị nhỏ nhất là $-1$.

**Chú ý.** Với hàm $y = 3 - 2\cos x$, biểu thức $-2\cos x$ có giá trị lớn nhất $2$ (khi $\cos x = -1$) và nhỏ nhất $-2$ (khi $\cos x = 1$). Giá trị lớn nhất của $y$ là $3 + 2 = 5$. Dấu trừ trước biên độ làm đảo chiều, đây là chỗ dễ sai nhất.

---

### Dạng 4 — Giá trị lớn nhất, nhỏ nhất của biểu thức $a\sin x + b\cos x$

**Cách nhận dạng.** Đề cho hàm số dạng tổng của một bội số $\sin x$ và một bội số $\cos x$ cùng bậc nhất, yêu cầu tìm giá trị lớn nhất hoặc nhỏ nhất.

**Cách làm.** Dùng công thức $\max = \sqrt{a^2 + b^2}$ và $\min = -\sqrt{a^2 + b^2}$ với hàm $y = a\sin x + b\cos x$.

**Ví dụ 4.** Tìm giá trị lớn nhất của hàm số $y = \sin x + \sqrt{3}\cos x$.

**Giải.** Áp dụng công thức với $a = 1$, $b = \sqrt{3}$:

$$\max y = \sqrt{1^2 + (\sqrt{3})^2} = \sqrt{1 + 3} = \sqrt{4} = 2$$

**Cách nhanh.** Công thức $\sqrt{a^2 + b^2}$ cho đáp án trong khoảng 5 giây. Kiểm chứng bằng cách gộp: $y = 2\sin\left(x + \dfrac{\pi}{3}\right)$, giá trị lớn nhất là $2$.

---

### Dạng 5 — Giải phương trình lượng giác cơ bản

**Cách nhận dạng.** Đề có từ khóa 解方程 (giải phương trình) hoặc 解集 (tập nghiệm), phương trình chỉ chứa một hàm lượng giác bậc nhất.

**Cách làm.** Đưa phương trình về dạng $\sin x = m$, $\cos x = m$ hoặc $\tan x = m$. Nếu đề giới hạn khoảng nghiệm thì viết họ nghiệm tổng quát rồi chọn các giá trị $k$ nằm trong khoảng đó.

**Ví dụ 5.** Giải phương trình $2\sin x - 1 = 0$ trên đoạn $[0, 2\pi]$.

**Giải.** Chuyển vế: $\sin x = \dfrac{1}{2}$.

Trên $[0, 2\pi]$, phương trình có hai nghiệm:

$$x = \frac{\pi}{6}, \qquad x = \frac{5\pi}{6}$$

**Chú ý.** Nếu đề không giới hạn khoảng, đáp án phải viết dưới dạng họ nghiệm: $x = \dfrac{\pi}{6} + 2k\pi$ hoặc $x = \dfrac{5\pi}{6} + 2k\pi$. Đọc kỹ đề có đoạn $[0, 2\pi]$ hay không trước khi kết luận.

---

### Dạng 6 — Giải phương trình bậc hai theo một hàm lượng giác

**Cách nhận dạng.** Phương trình có chứa $\sin^2 x$, $\cos^2 x$ hoặc tích hai hàm lượng giác, ví dụ $2\cos^2 x - 3\cos x + 1 = 0$.

**Cách làm.** Đặt $t$ bằng hàm lượng giác xuất hiện, kèm điều kiện $t \in [-1, 1]$ với $\sin$ và $\cos$. Giải phương trình bậc hai theo $t$, loại nghiệm nằm ngoài $[-1, 1]$, rồi giải phương trình lượng giác cơ bản cho từng nghiệm $t$ còn lại.

**Ví dụ 6.** Giải phương trình $2\cos^2 x - 3\cos x + 1 = 0$.

**Giải.** Đặt $t = \cos x$ với $t \in [-1, 1]$. Phương trình trở thành:

$$2t^2 - 3t + 1 = 0 \iff (2t - 1)(t - 1) = 0 \iff t = \frac{1}{2} \ \text{hoặc} \ t = 1$$

Cả hai nghiệm đều thuộc $[-1, 1]$ nên đều nhận.

Với $t = \dfrac{1}{2}$: $\cos x = \dfrac{1}{2} \iff x = \pm\dfrac{\pi}{3} + 2k\pi$.

Với $t = 1$: $\cos x = 1 \iff x = 2k\pi$.

**Bẫy.** Nếu giải ra $t = 2$ hoặc $t = -3$ thì phải loại ngay, vì $\cos x$ không thể nhận giá trị ngoài $[-1, 1]$. Bỏ bước kiểm tra này là mất điểm.

---

### Dạng 7 — Tìm khoảng đơn điệu của hàm số lượng giác

**Cách nhận dạng.** Đề có từ khóa 单调区间 (khoảng đơn điệu), 增函数 (hàm tăng) hoặc 减函数 (hàm giảm), yêu cầu xác định khoảng tăng giảm.

**Cách làm.** Đưa biểu thức bên trong hàm lượng giác về khoảng đồng biến hoặc nghịch biến chuẩn của $\sin$ hoặc $\cos$, rồi giải bất phương trình theo $x$.

**Ví dụ 7.** Tìm khoảng đồng biến của hàm số $y = 3\sin\left(2x - \dfrac{\pi}{3}\right)$.

**Giải.** Hàm $\sin u$ đồng biến khi $-\dfrac{\pi}{2} \le u \le \dfrac{\pi}{2}$. Đặt $u = 2x - \dfrac{\pi}{3}$:

$$-\frac{\pi}{2} + 2k\pi \le 2x - \frac{\pi}{3} \le \frac{\pi}{2} + 2k\pi$$

Cộng $\dfrac{\pi}{3}$ vào cả ba vế:

$$-\frac{\pi}{6} + 2k\pi \le 2x \le \frac{5\pi}{6} + 2k\pi$$

Chia cho $2$:

$$-\frac{\pi}{12} + k\pi \le x \le \frac{5\pi}{12} + k\pi$$

Vậy khoảng đồng biến là $\left[-\dfrac{\pi}{12} + k\pi,\ \dfrac{5\pi}{12} + k\pi\right]$ với $k \in \mathbb{Z}$.

**Chú ý.** Hệ số $\omega = 2$ chia cả hai đầu mút, nên khoảng đồng biến có độ dài $\dfrac{\pi}{2}$, đúng bằng nửa chu kỳ $\pi$. Kiểm tra độ dài này để phát hiện lỗi chia sai.

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
| **Lượng giác** | **8–11** | **~20%** |
| Hình học giải tích | 8–10 | ~19% |
| Dãy số | 5–8 | ~13% |
| Hàm số | 5–7 | ~13% |
| Tập hợp & bất đẳng thức | 4–6 | ~10% |
| Mũ & logarit | 3–5 | ~8% |
| Vector & số phức | 2–4 | ~6% |
| Xác suất & thống kê | 1–2 | ~3% |

Chuyên đề hôm nay cùng với buổi 4 chiếm khoảng 20% đề thi, nhóm nội dung lớn nhất. Trong 8–11 câu lượng giác, phần hàm số và phương trình chiếm khoảng một nửa, tức 4–6 câu.

---

*Tài liệu nội bộ, CAE SHANGHAI.*
