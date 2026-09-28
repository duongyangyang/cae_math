# BUỔI 10 — CONIC （圆锥曲线）

> **Module:** M3 · **Tỉ trọng đề thi:** ~19% (cùng hai buổi hình học) · khoảng 8–10 câu
> **Tài liệu học tập, dùng trên lớp và tra cứu khi làm bài**

---

## 1. TỪ KHÓA NHẬN DẠNG ĐỀ

Đọc được từ khóa là xác định được dạng bài mà không cần dịch cả đề. Bảng dưới đây gom những từ khóa quyết định của chuyên đề này.

| Từ khóa | Nghĩa | Dạng bài tương ứng |
|:--------|:------|:-------------------|
| 椭圆 | elip | Bài toán về elip |
| 双曲线 | hyperbol | Bài toán về hyperbol |
| 抛物线 | parabol | Bài toán về parabol |
| 焦点 | tiêu điểm | Tìm tọa độ tiêu điểm |
| 焦距 | tiêu cự | Độ dài $2c$, suy ra $c$ |
| 离心率 | tâm sai | Tính $e = \dfrac{c}{a}$ |
| 渐近线 | tiệm cận | Chỉ có ở hyperbol, $y = \pm\dfrac{b}{a}x$ |
| 准线 | đường chuẩn | Chỉ có ở parabol |
| 长轴、短轴 | trục lớn, trục nhỏ | Độ dài $2a$, $2b$ của elip |
| 实轴、虚轴 | trục thực, trục ảo | Độ dài $2a$, $2b$ của hyperbol |
| 标准方程 | phương trình chính tắc | Lập phương trình từ dữ kiện |
| 开口方向 | hướng mở | Parabol mở theo chiều nào |
| 焦半径 | bán kính qua tiêu | Khoảng cách từ điểm trên conic tới tiêu điểm |
| 通径 | trục thông | Dây cung vuông góc trục thực qua tiêu điểm |

**Chú ý.** Ba từ khóa 渐近线, 准线 và 离心率 đủ để xác định đề đang hỏi về conic nào: 渐近线 chỉ xuất hiện ở hyperbol, 准线 chỉ xuất hiện ở parabol, còn 离心率 có ở cả ba. Thấy 渐近线 thì không cần đọc phần còn lại của đề để biết công thức phải dùng.

---

## 2. KIẾN THỨC TRỌNG TÂM

### 2.1. Elip

**Định nghĩa 1 — Elip.** Tập hợp các điểm $M$ trong mặt phẳng sao cho tổng khoảng cách tới hai điểm cố định $F_1$, $F_2$ bằng một hằng số $2a$ lớn hơn $F_1F_2$:

$$MF_1 + MF_2 = 2a \quad (2a > 2c)$$

Hai điểm $F_1$, $F_2$ gọi là tiêu điểm, khoảng cách $F_1F_2 = 2c$ gọi là tiêu cự.

**Tính chất 1 — Phương trình chính tắc của elip.** Tiêu điểm nằm trên trục hoành:

$$\frac{x^2}{a^2} + \frac{y^2}{b^2} = 1 \quad (a > b > 0)$$

Tiêu điểm $F_1(-c, 0)$ và $F_2(c, 0)$, trong đó $b^2 = a^2 - c^2$, tức $a^2 = b^2 + c^2$.

Tiêu điểm nằm trên trục tung:

$$\frac{y^2}{a^2} + \frac{x^2}{b^2} = 1 \quad (a > b > 0)$$

Tiêu điểm $F_1(0, -c)$ và $F_2(0, c)$.

**Chú ý.** Mẫu số lớn hơn luôn là $a^2$, và tiêu điểm nằm trên trục ứng với mẫu lớn hơn đó. Trong $\dfrac{x^2}{9} + \dfrac{y^2}{16} = 1$, mẫu $16$ lớn hơn nằm dưới $y^2$, nên trục lớn là trục tung và tiêu điểm có dạng $(0, \pm c)$.

**Tính chất 2 — Các yếu tố của elip.** Với $\dfrac{x^2}{a^2} + \dfrac{y^2}{b^2} = 1$:

| Yếu tố | Giá trị |
|:-------|:--------|
| Trục lớn | $2a$ |
| Trục nhỏ | $2b$ |
| Tiêu cự | $2c$, với $c^2 = a^2 - b^2$ |
| Tâm sai | $e = \dfrac{c}{a}$, và $0 < e < 1$ |
| Bán kính qua tiêu | $MF_1 = a + ex$, $MF_2 = a - ex$ |

**Chú ý.** $e$ càng gần $0$ thì elip càng tròn, $e$ càng gần $1$ thì elip càng dẹt. Nhớ chiều này để loại đáp án nhanh: đề cho $e = \dfrac{1}{2}$ thì elip dẹt vừa phải, không thể có $e > 1$.

### 2.2. Hyperbol

**Định nghĩa 2 — Hyperbol.** Tập hợp các điểm $M$ sao cho giá trị tuyệt đối của hiệu hai khoảng cách tới hai tiêu điểm bằng hằng số $2a$ nhỏ hơn $F_1F_2$:

$$|MF_1 - MF_2| = 2a \quad (0 < 2a < 2c)$$

**Tính chất 3 — Phương trình chính tắc của hyperbol.** Tiêu điểm trên trục hoành:

$$\frac{x^2}{a^2} - \frac{y^2}{b^2} = 1 \quad (a > 0, b > 0)$$

Tiêu điểm $F_1(-c, 0)$, $F_2(c, 0)$, với $c^2 = a^2 + b^2$.

Tiêu điểm trên trục tung:

$$\frac{y^2}{a^2} - \frac{x^2}{b^2} = 1 \quad (a > 0, b > 0)$$

Tiêu điểm $F_1(0, -c)$, $F_2(0, c)$.

**Bẫy.** Elip có $a^2 = b^2 + c^2$ (cộng để ra $a$), hyperbol có $c^2 = a^2 + b^2$ (cộng để ra $c$). Dấu cộng đổi chỗ, và đây là lỗi mất điểm phổ biến nhất của cả chuyên đề.

**Tính chất 4 — Tiệm cận của hyperbol.** Với $\dfrac{x^2}{a^2} - \dfrac{y^2}{b^2} = 1$, hai đường tiệm cận là:

$$y = \pm\frac{b}{a}x$$

Với $\dfrac{y^2}{a^2} - \dfrac{x^2}{b^2} = 1$, hai đường tiệm cận là:

$$y = \pm\frac{a}{b}x$$

**Cách nhanh.** Cách nhớ không cần thuộc công thức: cho vế phải của phương trình chính tắc bằng $0$, tức $\dfrac{x^2}{a^2} - \dfrac{y^2}{b^2} = 0$, rồi giải ra $y$. Với $\dfrac{x^2}{16} - \dfrac{y^2}{9} = 0$ được $y = \pm\dfrac{3}{4}x$. Cách này đúng cho cả hai trường hợp và không bao giờ lẫn $a$ với $b$.

**Tính chất 5 — Các yếu tố của hyperbol.** Với $\dfrac{x^2}{a^2} - \dfrac{y^2}{b^2} = 1$:

| Yếu tố | Giá trị |
|:-------|:--------|
| Trục thực | $2a$ |
| Trục ảo | $2b$ |
| Tiêu cự | $2c$, với $c^2 = a^2 + b^2$ |
| Tâm sai | $e = \dfrac{c}{a}$, và $e > 1$ |
| Tiệm cận | $y = \pm\dfrac{b}{a}x$ |

**Chú ý.** $e > 1$ với mọi hyperbol, $0 < e < 1$ với mọi elip, $e = 1$ với mọi parabol. Ba khoảng giá trị này là cách kiểm tra đáp án trong hai giây: nếu đề hỏi tâm sai của hyperbol mà đáp án nhỏ hơn $1$ thì loại ngay.

### 2.3. Parabol

**Định nghĩa 3 — Parabol.** Tập hợp các điểm $M$ cách đều một điểm cố định $F$ (tiêu điểm) và một đường thẳng cố định $l$ (đường chuẩn) không đi qua $F$:

$$MF = d(M, l)$$

**Tính chất 6 — Bốn dạng phương trình chính tắc của parabol.** Đỉnh đều tại gốc tọa độ $O(0, 0)$.

| Phương trình | Hướng mở | Tiêu điểm $F$ | Đường chuẩn $l$ |
|:-------------|:---------|:--------------|:----------------|
| $y^2 = 2px$ $(p > 0)$ | sang phải | $\left(\dfrac{p}{2}, 0\right)$ | $x = -\dfrac{p}{2}$ |
| $y^2 = -2px$ $(p > 0)$ | sang trái | $\left(-\dfrac{p}{2}, 0\right)$ | $x = \dfrac{p}{2}$ |
| $x^2 = 2py$ $(p > 0)$ | lên trên | $\left(0, \dfrac{p}{2}\right)$ | $y = -\dfrac{p}{2}$ |
| $x^2 = -2py$ $(p > 0)$ | xuống dưới | $\left(0, -\dfrac{p}{2}\right)$ | $y = \dfrac{p}{2}$ |

**Cách nhanh.** Bình phương ở vế trái là biến nào thì trục đối xứng là trục còn lại. $y^2$ đứng một mình nghĩa là trục đối xứng $Ox$ và tiêu điểm nằm trên trục hoành. Còn dấu trừ ở vế phải quyết định hướng mở: dấu trừ thì mở về phía âm.

**Tính chất 7 — Bán kính qua tiêu của parabol.** Với $y^2 = 2px$ và điểm $P(x_0, y_0)$ trên parabol:

$$PF = x_0 + \frac{p}{2}$$

**Chú ý.** Công thức này đọc trực tiếp từ định nghĩa: khoảng cách từ $P$ tới tiêu điểm bằng khoảng cách từ $P$ tới đường chuẩn $x = -\dfrac{p}{2}$, mà khoảng cách đó là $x_0 + \dfrac{p}{2}$. Không cần dựng hình.

**Tính chất 8 — Đường chuẩn và tiêu điểm đối xứng qua đỉnh.** Với parabol có đỉnh tại gốc tọa độ, tiêu điểm $F\left(\dfrac{p}{2}, 0\right)$ và đường chuẩn $x = -\dfrac{p}{2}$ cách đều đỉnh $O$ về hai phía.

### 2.4. Quan hệ giữa ba đường conic

**Tính chất 9 — Phân loại bằng tâm sai.** Cả ba đường conic đều là tập hợp điểm có tỉ số khoảng cách tới tiêu điểm và tới đường chuẩn bằng một hằng số $e$:

| Giá trị của $e$ | Đường conic |
|:----------------|:------------|
| $0 < e < 1$ | Elip |
| $e = 1$ | Parabol |
| $e > 1$ | Hyperbol |

**Chú ý.** Đây là câu hỏi lý thuyết hay gặp ở mức dễ và là cách kiểm tra đáp án nhanh nhất cho mọi bài tính tâm sai.

**Tính chất 10 — Nhận dạng conic từ phương trình bậc hai.** Cho phương trình dạng $Ax^2 + By^2 = C$ với $A$, $B$, $C$ đều khác $0$:

| Điều kiện | Đường conic |
|:----------|:------------|
| $A$, $B$, $C$ cùng dấu | Elip |
| $A$, $B$ trái dấu, $C \neq 0$ | Hyperbol |
| $A = 0$ hoặc $B = 0$, $C \neq 0$ | Parabol |

**Bẫy.** Với elip, ba hệ số $A$, $B$, $C$ cùng dấu là điều kiện cần nhưng chưa đủ: còn phải kiểm tra mẫu số sau khi chia về $1$ có khác nhau hay không. Phương trình $\dfrac{x^2}{k+1} + \dfrac{y^2}{1-k} = 1$ biểu diễn elip khi $-1 < k < 1$, nhưng tại $k = 0$ phương trình thành $x^2 + y^2 = 1$, tức đường tròn chứ không phải elip theo nghĩa chặt.

---

## 3. CÁC DẠNG BÀI

### Dạng 1 — Từ phương trình chính tắc xác định tiêu điểm, tâm sai, độ dài các trục

**Cách nhận dạng.** Đề cho sẵn phương trình dạng $\dfrac{x^2}{m} + \dfrac{y^2}{n} = 1$ hoặc $\dfrac{x^2}{m} - \dfrac{y^2}{n} = 1$ và hỏi tiêu điểm, tâm sai, trục lớn, trục nhỏ.

**Cách làm.** So sánh với phương trình chính tắc để đọc ra $a^2$ và $b^2$. Nhớ mẫu lớn hơn là $a^2$ với elip, còn với hyperbol $a^2$ là mẫu của số hạng mang dấu cộng. Tính $c$ theo đúng công thức của từng đường, rồi suy ra các yếu tố còn lại.

**Ví dụ 1.** Tìm tiêu điểm và tâm sai của elip $\dfrac{x^2}{25} + \dfrac{y^2}{9} = 1$.

**Giải.** Mẫu $25$ lớn hơn nằm dưới $x^2$ nên $a^2 = 25$, $b^2 = 9$, trục lớn nằm trên trục hoành.

$$c^2 = a^2 - b^2 = 25 - 9 = 16 \implies c = 4$$

Tiêu điểm là $(\pm 4, 0)$. Tâm sai:

$$e = \frac{c}{a} = \frac{4}{5}$$

**Bẫy.** Đáp án nhiễu của dạng này thường là $(\pm 3, 0)$, lấy nhầm $b$ làm $c$ vì thấy $\sqrt{9} = 3$. Phải tính $c^2 = a^2 - b^2$ chứ không được lấy căn của $b^2$.

---

### Dạng 2 — Xác định đường tiệm cận của hyperbol

**Cách nhận dạng.** Đề có chữ 渐近线 (tiệm cận) hoặc cho phương trình hyperbol rồi hỏi đường thẳng mà đồ thị tiến sát.

**Cách làm.** Cho vế phải của phương trình chính tắc bằng $0$ rồi giải ra $y$. Với $\dfrac{x^2}{a^2} - \dfrac{y^2}{b^2} = 1$ kết quả là $y = \pm\dfrac{b}{a}x$. Không cần nhớ công thức riêng cho trường hợp tiêu điểm trên trục tung.

**Ví dụ 2.** Tìm phương trình các đường tiệm cận của hyperbol $\dfrac{x^2}{16} - \dfrac{y^2}{9} = 1$.

**Giải.** Cho vế phải bằng $0$:

$$\frac{x^2}{16} - \frac{y^2}{9} = 0 \iff \frac{y^2}{9} = \frac{x^2}{16} \iff y^2 = \frac{9}{16}x^2$$

$$y = \pm\frac{3}{4}x$$

**Chú ý.** Hai đáp án nhiễu hay gặp là $y = \pm\dfrac{4}{3}x$ (đảo ngược tỉ số) và $y = \pm\dfrac{9}{16}x$ (quên lấy căn). Viết rõ bước lấy căn để tránh cả hai.

---

### Dạng 3 — Xác định tiêu điểm và đường chuẩn của parabol

**Cách nhận dạng.** Đề cho phương trình dạng $y^2 = mx$ hoặc $x^2 = my$ và hỏi 焦点 (tiêu điểm) hoặc 准线 (đường chuẩn).

**Cách làm.** Đưa phương trình về dạng chuẩn $y^2 = 2px$ hoặc $x^2 = 2py$ để đọc ra $p$. Tiêu điểm cách đỉnh một khoảng $\dfrac{p}{2}$ về phía mở, đường chuẩn cách đỉnh một khoảng $\dfrac{p}{2}$ về phía đối diện.

**Ví dụ 3.** Tìm tiêu điểm của parabol $y = 4x^2$.

**Giải.** Trước hết đưa về dạng chuẩn. Chia hai vế cho $4$:

$$x^2 = \frac{y}{4}$$

So sánh với $x^2 = 2py$ được $2p = \dfrac{1}{4}$, suy ra $p = \dfrac{1}{8}$.

Parabol mở lên trên nên tiêu điểm nằm trên trục tung, cách đỉnh một khoảng $\dfrac{p}{2} = \dfrac{1}{16}$:

$$F\left(0, \frac{1}{16}\right)$$

**Bẫy.** Hệ số $4$ trong $y = 4x^2$ chính là $2p$ sau khi đảo vế, không phải $p$. Đọc thẳng $p = 4$ sẽ cho tiêu điểm $(0, 1)$, sai. Luôn đưa về dạng $x^2 = 2py$ trước khi đọc tham số.

---

### Dạng 4 — Từ dữ kiện hình học lập phương trình chính tắc của conic

**Cách nhận dạng.** Đề cho tiêu điểm, tiêu cự, tâm sai, điểm mà conic đi qua, hoặc phương trình tiệm cận, rồi yêu cầu viết 标准方程 (phương trình chính tắc).

**Cách làm.** Xác định trục chứa tiêu điểm để chọn dạng phương trình, sau đó tìm $a$ và $b$. Với elip dùng $a^2 = b^2 + c^2$, với hyperbol dùng $c^2 = a^2 + b^2$. Dùng điểm mà conic đi qua bằng cách thay tọa độ vào phương trình để lập phương trình theo ẩn còn lại.

**Ví dụ 4.** Lập phương trình chính tắc của elip có hai tiêu điểm $F_1(-3, 0)$, $F_2(3, 0)$ và đi qua điểm $P(5, 0)$.

**Giải.** Tiêu điểm nằm trên trục hoành nên phương trình có dạng $\dfrac{x^2}{a^2} + \dfrac{y^2}{b^2} = 1$ với $a > b > 0$.

Từ tiêu điểm được $c = 3$. Điểm $P(5, 0)$ thuộc elip nên thay vào phương trình:

$$\frac{25}{a^2} + \frac{0}{b^2} = 1 \implies a^2 = 25 \implies a = 5$$

$$b^2 = a^2 - c^2 = 25 - 9 = 16$$

Vậy phương trình là $\dfrac{x^2}{25} + \dfrac{y^2}{16} = 1$.

**Cách nhanh.** Điểm $P$ nằm trên trục hoành và là đỉnh của elip, nên đọc ngay $a = 5$ mà không cần thay vào phương trình. Nhận ra điểm cho trước là đỉnh thì tiết kiệm cả một bước biến đổi.

---

### Dạng 5 — Nhận dạng conic từ phương trình cho trước

**Cách nhận dạng.** Đề cho một phương trình bậc hai hai ẩn và hỏi đó là đường gì, hoặc hỏi điều kiện của tham số để phương trình biểu diễn một loại conic cụ thể.

**Cách làm.** Đưa phương trình về dạng $Ax^2 + By^2 = C$. Nếu $A$ và $B$ cùng dấu và cùng dấu với $C$ thì là elip; nếu $A$ và $B$ trái dấu thì là hyperbol; nếu một trong hai hệ số bằng $0$ thì là parabol.

**Ví dụ 5.** Phương trình $4x^2 + 9y^2 = 36$ biểu diễn đường conic nào?

**Giải.** Chia hai vế cho $36$ để vế phải bằng $1$:

$$\frac{x^2}{9} + \frac{y^2}{4} = 1$$

Hai mẫu số đều dương và khác nhau, đây là phương trình chính tắc của elip với $a^2 = 9$, $b^2 = 4$.

**Chú ý.** Nếu sau khi chia mà hai mẫu số bằng nhau, phương trình biểu diễn đường tròn. Đây là trường hợp đặc biệt của elip và đề hay khai thác khi hỏi điều kiện của tham số.

---

### Dạng 6 — Bài toán tổng hợp conic kết hợp khoảng cách và diện tích

**Cách nhận dạng.** Đề cho điểm nằm trên conic cùng một điều kiện về khoảng cách, chu vi hoặc diện tích, yêu cầu tính một đại lượng.

**Cách làm.** Viết tọa độ điểm theo tham số của conic, dùng công thức khoảng cách để lập phương trình, rồi tính đại lượng cần tìm. Với bài hỏi diện tích tam giác tạo bởi hai tiêu điểm và một điểm trên elip, nhớ rằng đáy là tiêu cự $2c$ và chiều cao là trị tuyệt đối tung độ của điểm.

**Ví dụ 6.** Cho elip $\dfrac{x^2}{16} + \dfrac{y^2}{7} = 1$ với hai tiêu điểm $F_1$, $F_2$. Điểm $P$ thuộc elip và cách gốc tọa độ một khoảng bằng $3$. Tính diện tích tam giác $PF_1F_2$.

**Giải.** Từ phương trình được $a^2 = 16$, $b^2 = 7$, suy ra $c^2 = 16 - 7 = 9$, tức $c = 3$ và tiêu cự $F_1F_2 = 6$.

Gọi $P(x_0, y_0)$. Điều kiện $OP = 3$ cho $x_0^2 + y_0^2 = 9$. Thay vào phương trình elip:

$$\frac{x_0^2}{16} + \frac{y_0^2}{7} = 1$$

Nhân hai vế với $112$: $7x_0^2 + 16y_0^2 = 112$. Thay $x_0^2 = 9 - y_0^2$:

$$7(9 - y_0^2) + 16y_0^2 = 112 \implies 63 + 9y_0^2 = 112 \implies y_0^2 = \frac{49}{9} \implies |y_0| = \frac{7}{3}$$

Diện tích tam giác:

$$S = \frac{1}{2} \cdot F_1F_2 \cdot |y_0| = \frac{1}{2} \cdot 6 \cdot \frac{7}{3} = 7$$

**Nhận xét.** Không cần tìm $x_0$ vì diện tích chỉ phụ thuộc $|y_0|$. Dừng lại ở $y_0^2$ là đủ, tiết kiệm một bước giải.

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

Thời gian trung bình mỗi câu là **1 phút 15 giây**. Conic là chuyên đề có tỉ lệ câu khó cao nhất trong đề, nên chiến lược là làm hết các câu hỏi tiêu điểm, tâm sai và tiệm cận trước, để dành thời gian cho nhóm câu khó hơn.

### Trọng số các nhóm nội dung

| Nhóm nội dung | Số câu | Tỉ trọng |
|:--------------|:------:|:--------:|
| Lượng giác | 8–11 | ~20% |
| **Hình học giải tích** | **8–10** | **~19%** |
| Dãy số | 5–8 | ~13% |
| Hàm số | 5–7 | ~13% |
| Tập hợp & bất đẳng thức | 4–6 | ~10% |
| Mũ & logarit | 3–5 | ~8% |
| Vector & số phức | 2–4 | ~6% |
| Xác suất & thống kê | 1–2 | ~3% |

Ba buổi hình học (buổi 8, 9, 10) chia nhau nhóm hình học giải tích với khoảng 8 đến 10 câu. Trong đó conic chiếm phần lớn vì mỗi đề thi thật thường có từ 3 đến 4 câu trực tiếp về elip, hyperbol hoặc parabol.

---

*Tài liệu nội bộ, CAE SHANGHAI.*
