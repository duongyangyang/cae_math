# BUỔI 9 — ĐƯỜNG THẲNG VÀ ĐƯỜNG TRÒN （直线与圆）

> **Module:** M3 · **Tỉ trọng đề thi:** ~19% (cùng hình học phẳng) · khoảng 8–10 câu
> **Tài liệu học tập, dùng trên lớp và tra cứu khi làm bài**

---

## 1. TỪ KHÓA NHẬN DẠNG ĐỀ

Đọc được từ khóa là xác định được dạng bài mà không cần dịch cả đề. Bảng dưới đây gom những từ khóa quyết định của chuyên đề này.

| Từ khóa | Nghĩa | Dạng bài tương ứng |
|:--------|:------|:-------------------|
| 斜率 | hệ số góc | Đọc hệ số góc từ phương trình, hoặc tìm hệ số góc qua hai điểm |
| 倾斜角 | góc nghiêng | Đổi hệ số góc sang góc, chú ý khoảng $[0^\circ, 180^\circ)$ |
| 截距 | khoảng chắn trên trục | Cho $y = 0$ tìm chắn trên trục hoành, cho $x = 0$ tìm chắn trên trục tung |
| 平行 | song song | Hai đường thẳng cùng hệ số góc và khác khoảng chắn |
| 垂直 | vuông góc | Tích hai hệ số góc bằng $-1$ |
| 重合 | trùng nhau | Cùng hệ số góc và cùng khoảng chắn |
| 交点 | giao điểm | Giải hệ hai phương trình đường thẳng |
| 垂直平分线 | đường trung trực | Qua trung điểm và vuông góc với đoạn thẳng |
| 点到直线的距离 | khoảng cách từ điểm đến đường thẳng | Thay tọa độ vào công thức khoảng cách |
| 圆心 | tâm đường tròn | Đọc tâm từ dạng chính tắc hoặc lấy nửa hệ số đổi dấu |
| 半径 | bán kính | Khai căn từ vế phải, hoặc dùng công thức tổng quát |
| 标准方程 | phương trình chính tắc | Dạng $(x-a)^2 + (y-b)^2 = r^2$ |
| 一般方程 | phương trình tổng quát | Dạng $x^2 + y^2 + Dx + Ey + F = 0$ |
| 相切 | tiếp xúc | Khoảng cách từ tâm đến đường thẳng bằng bán kính |
| 弦长 | độ dài dây cung | Dùng định lý Pythagoras với khoảng cách từ tâm |

**Chú ý.** Hai từ khóa 斜率 (hệ số góc) và 倾斜角 (góc nghiêng) liên hệ qua công thức $k = \tan\alpha$ nhưng khác nhau về khoảng giá trị. Đề cho góc nghiêng thì đổi sang hệ số góc mới viết được phương trình; đề cho hệ số góc thì đổi sang góc bằng cách tra bảng góc đặc biệt. Đọc nhầm hai từ này là mất điểm chắc chắn.

---

## 2. KIẾN THỨC TRỌNG TÂM

### 2.1. Hệ số góc và góc nghiêng

**Định nghĩa 1 — Hệ số góc.** Cho đường thẳng đi qua hai điểm $P_1(x_1, y_1)$ và $P_2(x_2, y_2)$ với $x_1 \ne x_2$. Hệ số góc của đường thẳng là

$$k = \frac{y_2 - y_1}{x_2 - x_1}$$

**Định nghĩa 2 — Góc nghiêng.** Góc nghiêng của đường thẳng là góc $\alpha$ tạo bởi chiều dương trục hoành và đường thẳng, đo ngược chiều kim đồng hồ, với $0^\circ \le \alpha < 180^\circ$.

**Tính chất 1 — Liên hệ giữa hệ số góc và góc nghiêng.**

$$k = \tan\alpha$$

| Hệ số góc | Góc nghiêng | Hướng của đường thẳng |
|:-----------|:-----------:|:----------------------|
| $k > 0$ | $0^\circ < \alpha < 90^\circ$ | Đi lên từ trái sang phải |
| $k = 0$ | $\alpha = 0^\circ$ | Nằm ngang |
| $k < 0$ | $90^\circ < \alpha < 180^\circ$ | Đi xuống từ trái sang phải |
| Không tồn tại | $\alpha = 90^\circ$ | Thẳng đứng |

**Chú ý.** Đường thẳng thẳng đứng có phương trình dạng $x = c$ và **không có hệ số góc**. Gặp dạng này thì không được viết $y = kx + b$, phải giữ nguyên dạng $x = c$.

**Cách nhanh.** Bốn góc nghiêng hay gặp trong đề: $k = \dfrac{\sqrt{3}}{3}$ cho $\alpha = 30^\circ$; $k = 1$ cho $\alpha = 45^\circ$; $k = \sqrt{3}$ cho $\alpha = 60^\circ$; $k = -1$ cho $\alpha = 135^\circ$. Nhớ bảng này thì đổi góc trong vài giây.

### 2.2. Các dạng phương trình đường thẳng

**Định nghĩa 3 — Năm dạng phương trình đường thẳng.** Cho đường thẳng đi qua điểm $(x_0, y_0)$ với hệ số góc $k$, chắn trên trục hoành là $a$ và chắn trên trục tung là $b$.

| Dạng | Phương trình | Dùng khi |
|:-----|:-------------|:---------|
| Điểm chắn góc | $y - y_0 = k(x - x_0)$ | Biết một điểm và hệ số góc |
| Chắn góc | $y = kx + b$ | Biết hệ số góc và khoảng chắn trên trục tung |
| Hai điểm | $\dfrac{y - y_1}{y_2 - y_1} = \dfrac{x - x_1}{x_2 - x_1}$ | Biết hai điểm phân biệt |
| Đoạn chắn | $\dfrac{x}{a} + \dfrac{y}{b} = 1$ | Biết cả hai khoảng chắn, với $ab \ne 0$ |
| Tổng quát | $Ax + By + C = 0$ | Dạng chuẩn của mọi đường thẳng |

**Chú ý.** Dạng điểm chắn góc không viết được cho đường thẳng thẳng đứng, dạng đoạn chắn không viết được cho đường thẳng đi qua gốc tọa độ hoặc song song với trục. Trong bốn đáp án trắc nghiệm, dạng tổng quát $Ax + By + C = 0$ luôn đúng cho mọi trường hợp.

**Tính chất 2 — Quan hệ giữa hai đường thẳng.** Cho hai đường thẳng $l_1: y = k_1x + b_1$ và $l_2: y = k_2x + b_2$.

$$l_1 \parallel l_2 \iff k_1 = k_2 \ \text{và} \ b_1 \ne b_2$$

$$l_1 \equiv l_2 \iff k_1 = k_2 \ \text{và} \ b_1 = b_2$$

$$l_1 \perp l_2 \iff k_1 \cdot k_2 = -1$$

**Tính chất 3 — Quan hệ giữa hai đường thẳng ở dạng tổng quát.** Cho $l_1: A_1x + B_1y + C_1 = 0$ và $l_2: A_2x + B_2y + C_2 = 0$.

$$l_1 \perp l_2 \iff A_1A_2 + B_1B_2 = 0$$

$$l_1 \parallel l_2 \iff A_1B_2 - A_2B_1 = 0 \ \text{và} \ A_1C_2 - A_2C_1 \ne 0$$

**Chú ý.** Công thức vuông góc ở dạng tổng quát $A_1A_2 + B_1B_2 = 0$ không cần đổi về dạng chắn góc, dùng nhanh hơn nhiều. Với dạng chắn góc thì nhớ tích hệ số góc bằng $-1$, và điều kiện này chỉ đúng khi cả hai hệ số góc đều tồn tại.

### 2.3. Khoảng cách và đường trung trực

**Định nghĩa 4 — Khoảng cách từ điểm đến đường thẳng.** Khoảng cách từ điểm $P(x_0, y_0)$ đến đường thẳng $\Delta: Ax + By + C = 0$ là

$$d = \frac{|Ax_0 + By_0 + C|}{\sqrt{A^2 + B^2}}$$

**Chú ý.** Công thức chỉ dùng được khi vế phải bằng $0$. Nếu đề cho dạng $y = kx + b$ thì phải chuyển về $kx - y + b = 0$ trước khi thay số.

**Chú ý.** Tử số có dấu giá trị tuyệt đối, mẫu số thì không. Bỏ dấu giá trị tuyệt đối ở tử là lỗi phổ biến nhất của dạng bài này, và nó chỉ sai khi điểm nằm về phía âm của đường thẳng.

**Định nghĩa 5 — Đường trung trực.** Đường trung trực của đoạn thẳng $AB$ là tập hợp các điểm cách đều $A$ và $B$. Đường này đi qua trung điểm của $AB$ và vuông góc với $AB$.

**Tính chất 4 — Quy trình viết đường trung trực.** Gọi $M$ là trung điểm của $AB$.

$$M = \left(\frac{x_A + x_B}{2}, \frac{y_A + y_B}{2}\right)$$

Hệ số góc của $AB$ là $k_{AB} = \dfrac{y_B - y_A}{x_B - x_A}$. Hệ số góc của đường trung trực là $k = -\dfrac{1}{k_{AB}}$. Phương trình cần tìm đi qua $M$ với hệ số góc $k$.

**Cách nhanh.** Có một cách kiểm tra không cần tính: đường trung trực phải đi qua trung điểm $M$. Thay tọa độ $M$ vào từng đáp án, chỉ giữ lại đáp án thỏa mãn. Cách này loại được hai đến ba phương án trong vài giây.

### 2.4. Đường tròn

**Định nghĩa 6 — Phương trình chính tắc của đường tròn.** Đường tròn tâm $I(a, b)$ bán kính $r > 0$ có phương trình

$$(x - a)^2 + (y - b)^2 = r^2$$

**Định nghĩa 7 — Phương trình tổng quát của đường tròn.**

$$x^2 + y^2 + Dx + Ey + F = 0$$

Phương trình này là một đường tròn khi và chỉ khi $D^2 + E^2 - 4F > 0$. Khi đó

$$I\left(-\frac{D}{2}, -\frac{E}{2}\right), \qquad r = \frac{1}{2}\sqrt{D^2 + E^2 - 4F}$$

**Cách nhanh.** Từ dạng tổng quát, tâm là nửa hệ số của $x$ và $y$ **đổi dấu**, còn bình phương bán kính là tổng bình phương hai tọa độ tâm trừ đi hệ số tự do. Không cần nhớ công thức căn: viết $r^2 = a^2 + b^2 - F$ rồi mới khai căn.

**Tính chất 5 — Vị trí tương đối giữa đường thẳng và đường tròn.** Cho đường tròn tâm $I$ bán kính $r$ và đường thẳng $\Delta$. Gọi $d$ là khoảng cách từ $I$ đến $\Delta$.

| So sánh | Vị trí tương đối | Số giao điểm |
|:--------|:-----------------|:------------:|
| $d < r$ | Cắt nhau | 2 |
| $d = r$ | Tiếp xúc | 1 |
| $d > r$ | Không giao nhau | 0 |

**Tính chất 6 — Độ dài dây cung.** Nếu đường thẳng cắt đường tròn tại hai điểm $A$, $B$ và $H$ là hình chiếu của tâm $I$ lên đường thẳng thì $H$ là trung điểm của $AB$, và

$$AB = 2\sqrt{r^2 - d^2}$$

**Nhận xét.** Công thức dây cung là hệ quả trực tiếp của định lý Pythagoras trong tam giác vuông $IHA$. Nhớ hình này thì không cần học thuộc công thức, vẽ nháp ra là suy được ngay.

**Chú ý.** Điều kiện $D^2 + E^2 - 4F > 0$ rất hay bị bỏ qua. Đề cho một phương trình dạng tổng quát kèm tham số và hỏi giá trị nào để phương trình **không** biểu diễn đường tròn thì phải dùng đúng điều kiện này.

---

## 3. CÁC DẠNG BÀI

### Dạng 1 — Viết phương trình đường thẳng thỏa điều kiện cho trước

**Cách nhận dạng.** Đề cho một điểm và một quan hệ (song song, vuông góc, đi qua điểm thứ hai) rồi hỏi phương trình đường thẳng. Từ khóa quyết định là 平行, 垂直, 经过.

**Cách làm.** Xác định hệ số góc của đường thẳng cần tìm, sau đó dùng dạng điểm chắn góc $y - y_0 = k(x - x_0)$ rồi chuyển về dạng tổng quát.

Với quan hệ song song: lấy nguyên hệ số góc của đường đã cho.

Với quan hệ vuông góc: lấy nghịch đảo đổi dấu của hệ số góc đường đã cho.

**Ví dụ 1.** Viết phương trình đường thẳng đi qua điểm $P(4, -3)$ và vuông góc với đường thẳng $3x - 5y + 6 = 0$.

**Giải.** Đường thẳng đã cho có hệ số góc $k_1 = \dfrac{3}{5}$. Hệ số góc của đường cần tìm là

$$k = -\frac{1}{k_1} = -\frac{5}{3}$$

Phương trình qua $P(4, -3)$ với hệ số góc $-\dfrac{5}{3}$:

$$y + 3 = -\frac{5}{3}(x - 4) \iff 3y + 9 = -5x + 20 \iff 5x + 3y - 11 = 0$$

---

### Dạng 2 — Xác định hệ số góc và góc nghiêng

**Cách nhận dạng.** Đề hỏi trực tiếp 斜率 hoặc 倾斜角, hoặc cho hai điểm và hỏi hệ số góc của đường thẳng nối chúng.

**Cách làm.** Đọc hệ số góc trực tiếp từ dạng chắn góc $y = kx + b$. Nếu đề cho dạng tổng quát $Ax + By + C = 0$ với $B \ne 0$ thì $k = -\dfrac{A}{B}$. Muốn ra góc nghiêng thì giải $k = \tan\alpha$ bằng bảng góc đặc biệt.

**Ví dụ 2.** Tìm góc nghiêng của đường thẳng $x - \sqrt{3}y + a = 0$.

**Giải.** Chuyển về dạng chắn góc: $\sqrt{3}y = x + a$, suy ra $y = \dfrac{1}{\sqrt{3}}x + \dfrac{a}{\sqrt{3}}$. Vậy $k = \dfrac{\sqrt{3}}{3}$.

Vì $k > 0$ nên góc nghiêng nằm trong khoảng $(0^\circ, 90^\circ)$. Từ $\tan\alpha = \dfrac{\sqrt{3}}{3}$ suy ra $\alpha = 30^\circ$.

**Chú ý.** Tham số $a$ không ảnh hưởng đến góc nghiêng, vì nó chỉ dịch đường thẳng lên xuống. Gặp tham số trong dạng bài này thì bỏ qua ngay, không cần biện luận.

---

### Dạng 3 — Xét vị trí tương đối của hai đường thẳng

**Cách nhận dạng.** Đề cho hai phương trình đường thẳng và hỏi chúng song song, vuông góc, trùng nhau hay cắt nhau. Từ khóa là 位置关系, 平行, 垂直, 重合.

**Cách làm.** Đưa cả hai về dạng chắn góc rồi so sánh hệ số góc. Nếu tích hai hệ số góc bằng $-1$ thì vuông góc. Nếu hai hệ số góc bằng nhau thì so tiếp khoảng chắn để phân biệt song song và trùng nhau. Nếu cần tọa độ giao điểm thì giải hệ hai phương trình.

**Ví dụ 3.** Xét vị trí tương đối của $l_1: y = -3x + 1$ và $l_2: y = -3x - 3$.

**Giải.** Hai hệ số góc bằng nhau: $k_1 = k_2 = -3$. Hai khoảng chắn khác nhau: $1 \ne -3$.

Vậy $l_1 \parallel l_2$.

**Nhận xét.** Khi hai hệ số góc bằng nhau, chỉ cần nhìn khoảng chắn là xong, không cần giải hệ. Chỉ khi hệ số góc khác nhau mới phải giải hệ để tìm giao điểm.

---

### Dạng 4 — Tính khoảng cách từ điểm đến đường thẳng

**Cách nhận dạng.** Đề cho tọa độ một điểm và phương trình một đường thẳng, hỏi 距离. Từ khóa là 点到直线的距离.

**Cách làm.** Chuyển đường thẳng về dạng $Ax + By + C = 0$, thay tọa độ điểm vào tử số, chia cho $\sqrt{A^2 + B^2}$.

**Ví dụ 4.** Tính khoảng cách từ điểm $P(2, -1)$ đến đường thẳng $3x - 4y + 5 = 0$.

**Giải.** Thay trực tiếp vào công thức:

$$d = \frac{|3 \cdot 2 - 4 \cdot (-1) + 5|}{\sqrt{3^2 + (-4)^2}} = \frac{|6 + 4 + 5|}{5} = \frac{15}{5} = 3$$

**Chú ý.** Mẫu số $\sqrt{A^2 + B^2}$ chỉ phụ thuộc đường thẳng, không phụ thuộc điểm. Gặp nhiều điểm cùng một đường thẳng thì tính mẫu số một lần rồi dùng lại.

---

### Dạng 5 — Tìm tâm và bán kính từ phương trình tổng quát

**Cách nhận dạng.** Đề cho phương trình dạng $x^2 + y^2 + Dx + Ey + F = 0$ và hỏi 圆心, 半径, hoặc hỏi giá trị tham số để bán kính bằng một số cho trước.

**Cách làm.** Tâm là $\left(-\dfrac{D}{2}, -\dfrac{E}{2}\right)$. Bình phương bán kính là $r^2 = \left(\dfrac{D}{2}\right)^2 + \left(\dfrac{E}{2}\right)^2 - F$.

**Ví dụ 5.** Tìm tâm và bán kính của đường tròn $x^2 + y^2 - 4x + 6y - 3 = 0$.

**Giải.** Hệ số $D = -4$, $E = 6$, $F = -3$.

$$I\left(-\frac{-4}{2}, -\frac{6}{2}\right) = (2, -3)$$

$$r^2 = 2^2 + 3^2 - (-3) = 4 + 9 + 3 = 16 \implies r = 4$$

**Bẫy.** Dấu của hệ số tự do $F$ hay bị xử lý sai. Trong công thức là **trừ** $F$, nên khi $F$ âm thì thành cộng. Đây là chỗ mất điểm phổ biến nhất của dạng bài này.

---

### Dạng 6 — Xét vị trí tương đối giữa đường thẳng và đường tròn

**Cách nhận dạng.** Đề cho một đường tròn và một đường thẳng, hỏi chúng cắt nhau, tiếp xúc hay không giao nhau; hoặc hỏi độ dài dây cung; hoặc hỏi giá trị tham số để đường thẳng tiếp xúc với đường tròn.

**Cách làm.** Tính khoảng cách $d$ từ tâm đến đường thẳng, so với bán kính $r$. Nếu đề hỏi độ dài dây cung thì dùng $AB = 2\sqrt{r^2 - d^2}$. Nếu đề hỏi tiếp xúc thì đặt $d = r$ rồi giải phương trình theo tham số.

**Ví dụ 6.** Xét vị trí tương đối của đường thẳng $3x + 4y - 5 = 0$ và đường tròn $x^2 + y^2 = 1$.

**Giải.** Đường tròn có tâm $O(0,0)$ và bán kính $r = 1$.

$$d = \frac{|3 \cdot 0 + 4 \cdot 0 - 5|}{\sqrt{3^2 + 4^2}} = \frac{5}{5} = 1$$

Vì $d = r = 1$ nên đường thẳng tiếp xúc với đường tròn.

**Nhận xét.** Ba trường hợp $d < r$, $d = r$, $d > r$ tương ứng với ba nhóm đáp án trong đề trắc nghiệm. Tính được $d$ rồi so với $r$ là đủ để chọn đáp án, không cần giải hệ tìm giao điểm.

---

### Dạng 7 — Viết phương trình đường trung trực của đoạn thẳng

**Cách nhận dạng.** Đề cho hai điểm $A$, $B$ và hỏi phương trình 垂直平分线 của đoạn $AB$.

**Cách làm.** Tính trung điểm $M$ của $AB$, tính hệ số góc $k_{AB}$, lấy hệ số góc vuông góc $k = -\dfrac{1}{k_{AB}}$, viết phương trình qua $M$.

**Ví dụ 7.** Viết phương trình đường trung trực của đoạn thẳng nối $A(1, 2)$ và $B(3, 4)$.

**Giải.** Trung điểm của $AB$ là

$$M\left(\frac{1+3}{2}, \frac{2+4}{2}\right) = (2, 3)$$

Hệ số góc của $AB$ là $k_{AB} = \dfrac{4-2}{3-1} = 1$. Hệ số góc của đường trung trực là $k = -1$.

Phương trình qua $M(2,3)$ với hệ số góc $-1$:

$$y - 3 = -(x - 2) \iff y - 3 = -x + 2 \iff x + y - 5 = 0$$

**Cách nhanh.** Thay tọa độ trung điểm $(2,3)$ vào bốn đáp án để loại trước. Chỉ đáp án $x + y - 5 = 0$ cho kết quả $0$. Cách này bỏ qua hoàn toàn việc tính hệ số góc.

---

## PHỤ LỤC — VỊ TRÍ CỦA CHUYÊN ĐỀ TRONG ĐỀ THI

Nhóm hình học giải tích gồm đường thẳng, đường tròn và conic, chiếm khoảng 8 đến 10 câu trong đề thi, tương đương 19 phần trăm. Đây là nhóm nội dung lớn thứ hai sau lượng giác.

| Dạng bài | Tần suất trong đề | Ghi chú |
|:---------|:-----------------:|:--------|
| Viết phương trình đường thẳng | Cao | Thường là câu dễ, làm trước |
| Hệ số góc và góc nghiêng | Trung bình | Chỉ cần bảng góc đặc biệt |
| Vị trí tương đối hai đường thẳng | Trung bình | Đọc hệ số góc là xong |
| Khoảng cách từ điểm đến đường thẳng | Cao | Công thức cố định, thay số |
| Tâm và bán kính đường tròn | Cao | Xuất hiện gần như mọi đề |
| Đường thẳng và đường tròn | Trung bình | Dùng khoảng cách so với bán kính |
| Đường trung trực | Thấp | Thay trung điểm vào đáp án là nhanh nhất |

Thời gian trung bình mỗi câu trong đề thi là 75 giây. Bốn dạng có tần suất cao ở bảng trên đều xử lý được trong khoảng 40 giây nếu nhận ra dạng ngay từ từ khóa.

---

*Tài liệu nội bộ, CAE SHANGHAI.*
