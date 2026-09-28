# BUỔI 12 — VECTOR VÀ SỐ PHỨC （向量与复数）

> **Module:** M3 · **Tỉ trọng đề thi:** ~6% · khoảng 2–4 câu
> **Tài liệu học tập, dùng trên lớp và tra cứu khi làm bài**

---

## 1. TỪ KHÓA NHẬN DẠNG ĐỀ

Đọc được từ khóa là xác định được dạng bài mà không cần dịch cả đề. Bảng dưới đây gom những từ khóa quyết định của chuyên đề này.

| Từ khóa | Nghĩa | Dạng bài tương ứng |
|:--------|:------|:-------------------|
| 数量积 | tích vô hướng | Tính $a \cdot b$ từ tọa độ |
| 夹角 | góc | Tính góc giữa hai vector |
| 投影 | hình chiếu | Chiếu vector này lên phương vector kia |
| 模 | môđun | Tính độ dài vector hoặc môđun số phức |
| 垂直 | vuông góc | Tìm tham số để $a \cdot b = 0$ |
| 平行 / 共线 | song song / cùng phương | Tìm tham số để $x_1y_2 - x_2y_1 = 0$ |
| 中点 | trung điểm | Tọa độ trung điểm, trung tuyến |
| 实部 | phần thực | Đọc phần thực của số phức |
| 虚部 | phần ảo | Đọc phần ảo của số phức |
| 共轭复数 | số phức liên hợp | Đổi dấu phần ảo |
| 纯虚数 | số thuần ảo | Điều kiện: phần thực bằng 0 và phần ảo khác 0 |
| 虚数单位 | đơn vị ảo | Rút gọn lũy thừa của $i$ theo chu kì 4 |

**Chú ý.** Ba cặp từ khóa dễ đọc nhầm nhất:

| Cặp từ khóa | Khác nhau ở đâu |
|:------------|:----------------|
| 模 và 共轭复数 | 模 là một số thực không âm; 共轭复数 là một số phức |
| 纯虚数 và 虚数 | 纯虚数 bắt buộc phần thực bằng $0$; 虚数 chỉ cần phần ảo khác $0$ |
| 垂直 và 平行 | 垂直 dùng $a \cdot b = 0$; 平行 dùng $x_1y_2 = x_2y_1$ |

---

## 2. KIẾN THỨC TRỌNG TÂM

### 2.1. Vector trong mặt phẳng

**Định nghĩa 1 — Vector và môđun.** Vector là đại lượng có cả độ lớn và hướng. Vector $a = (x, y)$ có môđun $\lvert a \rvert = \sqrt{x^2 + y^2}$.

**Định nghĩa 2 — Tích vô hướng.** Với $a = (x_1, y_1)$ và $b = (x_2, y_2)$:

$$a \cdot b = x_1x_2 + y_1y_2 = \lvert a \rvert \lvert b \rvert \cos\theta$$

trong đó $\theta$ là góc giữa hai vector.

**Tính chất 1 — Các phép toán tọa độ.** Với $a = (x_1, y_1)$, $b = (x_2, y_2)$ và số thực $\lambda$:

$$a + b = (x_1 + x_2,\ y_1 + y_2), \qquad a - b = (x_1 - x_2,\ y_1 - y_2), \qquad \lambda a = (\lambda x_1,\ \lambda y_1)$$

**Tính chất 2 — Điều kiện vuông góc.** Với hai vector khác vector không:

$$a \perp b \iff a \cdot b = 0 \iff x_1x_2 + y_1y_2 = 0$$

**Tính chất 3 — Điều kiện song song.** Với $b$ khác vector không:

$$a \parallel b \iff x_1y_2 - x_2y_1 = 0$$

**Tính chất 4 — Công thức góc.** Góc $\theta$ giữa hai vector khác vector không xác định bởi:

$$\cos\theta = \frac{a \cdot b}{\lvert a \rvert \lvert b \rvert} = \frac{x_1x_2 + y_1y_2}{\sqrt{x_1^2 + y_1^2}\sqrt{x_2^2 + y_2^2}}$$

**Tính chất 5 — Hình chiếu.** Hình chiếu vô hướng của $a$ lên phương $b$ bằng:

$$\frac{a \cdot b}{\lvert b \rvert}$$

**Chú ý.** Hình chiếu là một **số** có thể âm, không phải một vector. Đề dùng chữ 投影 mà hỏi một giá trị trong bốn phương án số thì đó là hình chiếu vô hướng.

**Tính chất 6 — Tọa độ trung điểm.** Trung điểm $M$ của đoạn $AB$ với $A(x_1, y_1)$, $B(x_2, y_2)$ có tọa độ:

$$M = \left(\frac{x_1 + x_2}{2},\ \frac{y_1 + y_2}{2}\right)$$

**Chú ý.** Vector $\overrightarrow{AB} = B - A$, tức lấy tọa độ điểm cuối trừ tọa độ điểm đầu. Đảo thứ tự là sai dấu cả hai thành phần, và đây là lỗi mất điểm phổ biến nhất ở dạng tìm tọa độ điểm.

**Cách nhanh.** Hai vector cùng phương khi tỉ số các thành phần tương ứng bằng nhau. Với $a = (1,2)$, $b = (2,4)$: $\dfrac{2}{1} = \dfrac{4}{2} = 2$ nên cùng phương. Cách này nhanh hơn viết phương trình $x_1y_2 = x_2y_1$ nhưng phải kiểm tra trường hợp có thành phần bằng $0$.

### 2.2. Số phức

**Định nghĩa 3 — Số phức và các thành phần.** Số phức có dạng $z = a + bi$ với $a, b \in \mathbb{R}$ và $i^2 = -1$. Số $a$ gọi là **phần thực**, số $b$ gọi là **phần ảo**.

**Định nghĩa 4 — Số phức liên hợp.** Số phức liên hợp của $z = a + bi$ là $\overline{z} = a - bi$.

**Định nghĩa 5 — Môđun số phức.** Môđun của $z = a + bi$ là:

$$\lvert z \rvert = \sqrt{a^2 + b^2}$$

**Tính chất 7 — Bốn phép toán.** Với $z_1 = a + bi$ và $z_2 = c + di$:

$$z_1 \pm z_2 = (a \pm c) + (b \pm d)i$$

$$z_1 \cdot z_2 = (ac - bd) + (ad + bc)i$$

$$\frac{z_1}{z_2} = \frac{(a + bi)(c - di)}{c^2 + d^2} \quad (z_2 \ne 0)$$

**Tính chất 8 — Chu kì lũy thừa của $i$.** Với mọi số nguyên $n$:

$$i^{4n} = 1, \qquad i^{4n+1} = i, \qquad i^{4n+2} = -1, \qquad i^{4n+3} = -i$$

**Cách nhanh.** Chia số mũ cho $4$ và chỉ quan tâm số dư. Với $i^{2025}$: $2025 = 4 \times 506 + 1$ nên $i^{2025} = i$. Không cần viết chu kì ra giấy.

**Tính chất 9 — Các đẳng thức về môđun và liên hợp.**

$$z \cdot \overline{z} = \lvert z \rvert^2 = a^2 + b^2, \qquad \lvert \overline{z} \rvert = \lvert z \rvert, \qquad \overline{z_1 \cdot z_2} = \overline{z_1} \cdot \overline{z_2}$$

**Tính chất 10 — Điều kiện số thực và số thuần ảo.** Cho $z = a + bi$ với $a, b \in \mathbb{R}$:

$$z \in \mathbb{R} \iff b = 0; \qquad z \ \text{là số thuần ảo} \iff a = 0 \ \text{và} \ b \ne 0$$

**Bẫy.** Số thuần ảo yêu cầu **hai** điều kiện. Nếu chỉ đặt $a = 0$ mà quên $b \ne 0$, ta nhận luôn cả $z = 0$, mà số $0$ là số thực chứ không phải số thuần ảo.

**Chú ý.** Phần ảo của $z = a + bi$ là số thực $b$, **không phải** $bi$. Đề hỏi 虚部 thì đáp án là một số thực; phương án dạng $4i$ là phương án nhiễu.

**Cách nhanh.** Khi đề cho $z = \dfrac{a + bi}{c + di}$, đừng khai triển ngay. Nhân tử và mẫu với $c - di$ rồi tính $c^2 + d^2$ trước để biết mẫu số, sau đó mới rút gọn tử.

**Nhận xét.** Phép chia số phức và phép tính môđun là hai dạng chiếm phần lớn số câu về số phức trong đề thi thật. Cả hai đều chỉ dùng một công thức duy nhất, không đòi hỏi biến đổi sáng tạo.

---

## 3. CÁC DẠNG BÀI

### Dạng 1 — Tích vô hướng và góc giữa hai vector

**Cách nhận dạng.** Đề cho tọa độ hai vector và hỏi 数量积 (tích vô hướng), 夹角 (góc), hoặc 余弦值 (giá trị cosin).

**Cách làm.** Tính $a \cdot b = x_1x_2 + y_1y_2$, tính hai môđun, thay vào $\cos\theta = \dfrac{a \cdot b}{\lvert a \rvert \lvert b \rvert}$. Nếu đề cho độ dài và góc thì đi ngược lại: dùng $a \cdot b = \lvert a \rvert \lvert b \rvert \cos\theta$.

**Ví dụ 1.** Cho $u = (1, \sqrt{3})$ và $v = (\sqrt{3}, 1)$. Tìm góc giữa hai vector.

**Giải.** Tích vô hướng: $u \cdot v = 1 \cdot \sqrt{3} + \sqrt{3} \cdot 1 = 2\sqrt{3}$.

Hai môđun: $\lvert u \rvert = \sqrt{1 + 3} = 2$ và $\lvert v \rvert = \sqrt{3 + 1} = 2$.

$$\cos\theta = \frac{2\sqrt{3}}{2 \cdot 2} = \frac{\sqrt{3}}{2}$$

Vậy $\theta = 30^\circ$.

---

### Dạng 2 — Tìm tham số để hai vector vuông góc

**Cách nhận dạng.** Đề có tham số $k$, $m$, $t$ và cụm 垂直 (vuông góc).

**Cách làm.** Lập phương trình $x_1x_2 + y_1y_2 = 0$, giải phương trình bậc nhất hoặc bậc hai theo tham số. Chỉ cần một bước, không vẽ hình.

**Ví dụ 2.** Cho $a = (5, 1)$ và $b = (-2, 2k)$. Tìm $k$ để $a \perp b$.

**Giải.** Điều kiện vuông góc:

$$5 \cdot (-2) + 1 \cdot 2k = 0 \iff -10 + 2k = 0 \iff k = 5$$

---

### Dạng 3 — Tìm tham số để hai vector song song

**Cách nhận dạng.** Đề có cụm 平行 (song song) hoặc 共线 (cùng phương).

**Cách làm.** Lập phương trình $x_1y_2 - x_2y_1 = 0$. Với vector hai chiều, phương trình này là bậc nhất theo tham số và cho một nghiệm duy nhất. Với vector ba chiều thì xét tỉ số ba thành phần.

**Ví dụ 3.** Cho $a = (k, 1)$ và $b = (4, k)$. Tìm $k$ để $a \parallel b$.

**Giải.** Điều kiện song song:

$$k \cdot k - 4 \cdot 1 = 0 \iff k^2 = 4 \iff k = \pm 2$$

**Bẫy.** Đáp án chỉ ghi $k = 2$ là thiếu nghiệm âm. Phương trình bậc hai theo tham số luôn cho hai nghiệm, phải viết đủ.

---

### Dạng 4 — Môđun, hình chiếu và tọa độ trung điểm

**Cách nhận dạng.** Đề hỏi 模 (môđun), 投影 (hình chiếu), 中点 (trung điểm), hoặc cho tọa độ điểm đầu và vector rồi hỏi tọa độ điểm cuối.

**Cách làm.** Môđun dùng căn của tổng bình phương. Hình chiếu của $a$ lên $b$ bằng $\dfrac{a \cdot b}{\lvert b \rvert}$. Tọa độ điểm cuối bằng tọa độ điểm đầu cộng vector.

**Ví dụ 4.** Cho $\overrightarrow{AB} = (3, -6)$ và $A(-1, 2)$. Tìm tọa độ $B$.

**Giải.** Vì $\overrightarrow{AB} = B - A$ nên $B = A + \overrightarrow{AB}$:

$$B = (-1 + 3,\ 2 + (-6)) = (2, -4)$$

**Chú ý.** Công thức này viết dưới dạng tọa độ: điểm cuối bằng điểm đầu cộng vector. Nếu đề cho điểm cuối và hỏi điểm đầu thì làm phép trừ.

---

### Dạng 5 — Phép toán cộng, trừ, nhân, chia số phức

**Cách nhận dạng.** Đề cho hai hoặc ba số phức và yêu cầu tính $z_1 \pm z_2$, $z_1 z_2$, hoặc $\dfrac{z_1}{z_2}$.

**Cách làm.** Cộng trừ theo từng phần. Nhân như nhân đa thức rồi thay $i^2 = -1$. Chia bằng cách nhân tử và mẫu với số phức liên hợp của mẫu.

**Ví dụ 5.** Cho $z_1 = 4 - i$ và $z_2 = (2 + 5i)i$. Tính $z_1 - z_2$.

**Giải.** Trước hết rút gọn $z_2$:

$$z_2 = (2 + 5i)i = 2i + 5i^2 = 2i - 5 = -5 + 2i$$

$$z_1 - z_2 = (4 - i) - (-5 + 2i) = 9 - 3i$$

**Cách nhanh.** Luôn rút gọn số phức có chứa $i$ nhân bên ngoài trước khi thực hiện phép toán chính. Bỏ bước này là phải nhân hai lần.

---

### Dạng 6 — Phần thực, phần ảo, số phức liên hợp

**Cách nhận dạng.** Đề hỏi 实部, 虚部, 共轭复数, hoặc cho một biểu thức và hỏi phần ảo của kết quả.

**Cách làm.** Đưa số phức về dạng chuẩn $a + bi$ bằng cách thực hiện hết các phép toán, sau đó đọc trực tiếp $a$ và $b$.

**Ví dụ 6.** Cho $z = \dfrac{2+i}{1-i}$. Tìm số phức liên hợp $\overline{z}$.

**Giải.** Nhân tử và mẫu với $1 + i$:

$$z = \frac{(2+i)(1+i)}{(1-i)(1+i)} = \frac{2 + 2i + i + i^2}{1 - i^2} = \frac{1 + 3i}{2} = \frac{1}{2} + \frac{3}{2}i$$

$$\overline{z} = \frac{1}{2} - \frac{3}{2}i$$

---

### Dạng 7 — Tham số để số phức là số thực hoặc số thuần ảo

**Cách nhận dạng.** Đề cho $z$ chứa tham số $a$, $m$, $k$ và cụm 纯虚数 (thuần ảo) hoặc 实数 (số thực).

**Cách làm.** Đưa $z$ về dạng $a + bi$ với $a$ và $b$ là biểu thức chứa tham số, rồi áp dụng Tính chất 10. Số thuần ảo cần hai điều kiện, số thực chỉ cần một.

**Ví dụ 7.** Cho $z = (a + i)(1 - i)$. Tìm $a$ để $z$ là số thuần ảo.

**Giải.** Khai triển:

$$z = (a + i)(1 - i) = a - ai + i - i^2 = (a + 1) + (1 - a)i$$

Phần thực $a + 1$, phần ảo $1 - a$. Điều kiện số thuần ảo:

$$a + 1 = 0 \implies a = -1$$

Kiểm tra điều kiện thứ hai: $1 - (-1) = 2 \ne 0$ nên $a = -1$ thỏa mãn.

---

### Dạng 8 — Môđun số phức và lũy thừa của đơn vị ảo

**Cách nhận dạng.** Đề hỏi 模, $\lvert z \rvert$, $\lvert \overline{z} \rvert$, $z \cdot \overline{z}$, hoặc yêu cầu tính $i^n$ với $n$ lớn.

**Cách làm.** Với môđun, đưa $z$ về dạng $a + bi$ rồi tính $\sqrt{a^2 + b^2}$. Với $i^n$, chia $n$ cho $4$ và dùng số dư.

**Ví dụ 8.** Tính môđun của $z = -3 - 4i$.

**Giải.**

$$\lvert z \rvert = \sqrt{(-3)^2 + (-4)^2} = \sqrt{9 + 16} = 5$$

**Cách nhanh.** Bộ số $3$–$4$–$5$ và $5$–$12$–$13$ xuất hiện rất nhiều trong đề. Nhìn thấy phần thực và phần ảo là bội của $3$ và $4$ thì đọc ngay đáp án mà không cần bấm căn.

**Chú ý.** $\lvert \overline{z} \rvert = \lvert z \rvert$, nên đề hỏi môđun của số phức liên hợp thì tính môđun của $z$ gốc, không cần đổi dấu.

---

## PHỤ LỤC — CẤU TRÚC ĐỀ THI CSCA MÔN TOÁN

| Đặc điểm | Thông số |
|:---------|:---------|
| Số câu | 48 câu trắc nghiệm |
| Thời gian | 60 phút |
| Thang điểm | 100 điểm |
| Ngôn ngữ | Tiếng Trung hoặc tiếng Anh (thí sinh chọn) |
| Máy tính | Không được dùng |

Thời gian trung bình mỗi câu là **1 phút 15 giây**. Chuyên đề Vector và số phức chỉ chiếm 2–4 câu, nhưng đây là nhóm câu **dễ lấy điểm nhất** trong toàn đề: hầu hết chỉ cần một công thức và một phép thay số. Mục tiêu là xử lý mỗi câu trong khoảng 40 giây.

---

*Tài liệu nội bộ, CAE SHANGHAI.*
