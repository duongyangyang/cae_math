# BUỔI 8 — HÌNH HỌC PHẲNG VÀ KHÔNG GIAN （平面几何与空间几何）

> **Module:** M3 · **Tỉ trọng đề thi:** ~19% (cùng hình học giải tích) · khoảng 8–10 câu
> **Tài liệu học tập, dùng trên lớp và tra cứu khi làm bài**

---

## 1. TỪ KHÓA NHẬN DẠNG ĐỀ

Đọc được từ khóa là xác định được dạng bài mà không cần dịch cả đề. Bảng dưới đây gom những từ khóa quyết định của chuyên đề này.

| Từ khóa | Nghĩa | Dạng bài tương ứng |
|:--------|:------|:-------------------|
| 三角形 | tam giác | Tính cạnh, góc, diện tích tam giác |
| 四边形 | tứ giác | Đa giác và tổng góc trong |
| 多边形 | đa giác | Tổng góc trong, đa giác đều |
| 正多边形 | đa giác đều | Cạnh, góc, diện tích đa giác đều |
| 周长 | chu vi | Tính chu vi hình phẳng |
| 面积 | diện tích | Tính diện tích hình phẳng |
| 内角 | góc trong | Tổng góc trong của đa giác |
| 相似 | đồng dạng | Tỉ số cạnh của hai tam giác đồng dạng |
| 全等 | bằng nhau | Hai tam giác bằng nhau |
| 直角三角形 | tam giác vuông | Dùng định lý Pythagoras |
| 勾股定理 | định lý Pythagoras | Tìm cạnh chưa biết của tam giác vuông |
| 表面积 | diện tích mặt | Diện tích toàn phần của khối |
| 体积 | thể tích | Thể tích khối |
| 正方体 | hình lập phương | Thể tích, đường chéo |
| 长方体 | hình hộp chữ nhật | Thể tích, diện tích mặt |
| 圆柱 | hình trụ | Thể tích, diện tích mặt |
| 圆锥 | hình nón | Thể tích, diện tích mặt |
| 球 | hình cầu | Thể tích, diện tích mặt |
| 母线 | đường sinh | Quan hệ đường sinh, bán kính, chiều cao của nón và trụ |
| 棱柱 | lăng trụ | Thể tích lăng trụ |
| 棱锥 | hình chóp | Thể tích hình chóp |

**Chú ý.** Hai từ khóa 表面积 (diện tích mặt) và 侧面积 (diện tích xung quanh) khác nhau. Đề hỏi 表面积 thì phải cộng cả mặt đáy; đề hỏi 侧面积 thì chỉ tính phần mặt bên. Với hình trụ bán kính $r$, chiều cao $h$: diện tích xung quanh là $2\pi r h$, còn diện tích toàn phần là $2\pi r h + 2\pi r^2$.

**Chú ý.** 对角线 là đường chéo. Với hình lập phương cạnh $a$, đường chéo mặt bằng $a\sqrt{2}$ còn đường chéo khối bằng $a\sqrt{3}$. Đề chỉ ghi 对角线 mà không nói rõ là đường chéo mặt hay đường chéo khối, phải đọc kỹ phần mô tả trong ngoặc: 连接不相邻的两个顶点 (nối hai đỉnh không kề nhau) là đường chéo khối.

---

## 2. KIẾN THỨC TRỌNG TÂM

### 2.1. Hình phẳng: tam giác và đa giác

**Tính chất 1 — Tổng góc trong của đa giác.** Đa giác lồi $n$ cạnh có tổng số đo các góc trong bằng $(n-2) \cdot 180^\circ$.

**Hệ quả.** Tổng góc trong của tứ giác là $360^\circ$, của ngũ giác là $540^\circ$, của lục giác là $720^\circ$.

**Tính chất 2 — Diện tích tam giác.** Với tam giác có cạnh đáy $a$ và chiều cao tương ứng $h$:

$$S = \frac{1}{2}ah$$

**Tính chất 3 — Công thức Heron.** Tam giác có ba cạnh $a, b, c$ và nửa chu vi $p = \dfrac{a+b+c}{2}$ có diện tích:

$$S = \sqrt{p(p-a)(p-b)(p-c)}$$

**Tính chất 4 — Diện tích tam giác đều.** Tam giác đều cạnh $a$ có diện tích $S = \dfrac{a^2\sqrt{3}}{4}$ và chiều cao $h = \dfrac{a\sqrt{3}}{2}$.

**Tính chất 5 — Bất đẳng thức tam giác.** Ba độ dài $a, b, c$ là ba cạnh của một tam giác khi và chỉ khi mỗi độ dài nhỏ hơn tổng hai độ dài còn lại:

$$a + b > c, \quad b + c > a, \quad c + a > b$$

**Chú ý.** Chỉ cần kiểm tra điều kiện với cạnh lớn nhất: nếu cạnh lớn nhất nhỏ hơn tổng hai cạnh kia thì hai điều kiện còn lại tự động đúng. Đây là cách kiểm tra nhanh trong phòng thi.

**Tính chất 6 — Định lý Pythagoras.** Tam giác vuông có hai cạnh góc vuông $a, b$ và cạnh huyền $c$:

$$a^2 + b^2 = c^2$$

**Chú ý.** Bộ ba Pythagoras hay gặp: $(3, 4, 5)$, $(5, 12, 13)$, $(6, 8, 10)$, $(8, 15, 17)$. Nhận ra bộ ba này thì khỏi tính căn.

**Tính chất 7 — Tam giác đồng dạng.** Hai tam giác đồng dạng khi chúng có các cặp góc tương ứng bằng nhau. Khi đó tỉ số các cạnh tương ứng bằng nhau:

$$\frac{a'}{a} = \frac{b'}{b} = \frac{c'}{c} = k$$

với $k$ là tỉ số đồng dạng. Tỉ số diện tích bằng $k^2$.

**Chú ý.** Đề cho 相似 (đồng dạng) thì lập ngay tỉ số cạnh, không cần vẽ hình. Cạnh tương ứng là cạnh đối diện với góc bằng nhau.

**Tính chất 8 — Tỉ số diện tích hai tam giác đồng dạng.** Hai tam giác đồng dạng với tỉ số đồng dạng $k$ có tỉ số diện tích bằng $k^2$.

### 2.2. Đường tròn

**Định nghĩa 1 — Đường tròn.** Đường tròn tâm $O$ bán kính $r$ là tập hợp các điểm cách $O$ một khoảng bằng $r$.

**Tính chất 9 — Chu vi và diện tích đường tròn.** Đường tròn bán kính $r$ có chu vi $C = 2\pi r$ và diện tích $S = \pi r^2$.

**Tính chất 10 — Số đo cung và diện tích hình quạt.** Trên đường tròn bán kính $r$, cung có số đo $n^\circ$ (hoặc góc ở tâm $\alpha$ radian) có:

$$l = \frac{n}{360} \cdot 2\pi r = \alpha r, \qquad S_{\text{quạt}} = \frac{n}{360} \cdot \pi r^2 = \frac{1}{2}\alpha r^2$$

**Tính chất 11 — Góc nội tiếp.** Góc nội tiếp chắn một cung có số đo bằng nửa số đo cung đó. Góc nội tiếp chắn nửa đường tròn là góc vuông.

**Chú ý.** Góc nội tiếp cùng chắn một cung thì bằng nhau. Đây là công cụ để chứng minh hai tam giác đồng dạng trong bài toán đường tròn.

**Tính chất 12 — Tiếp tuyến.** Tiếp tuyến của đường tròn vuông góc với bán kính tại tiếp điểm.

### 2.3. Hình không gian: thể tích và diện tích mặt

**Tính chất 13 — Hình hộp chữ nhật.** Hình hộp chữ nhật có ba kích thước $a, b, c$:

$$V = abc, \qquad S_{\text{toàn phần}} = 2(ab + bc + ca), \qquad d = \sqrt{a^2+b^2+c^2}$$

với $d$ là đường chéo của hình hộp.

**Tính chất 14 — Hình lập phương.** Hình lập phương cạnh $a$ là trường hợp riêng của hình hộp chữ nhật với $a = b = c$:

$$V = a^3, \qquad S_{\text{toàn phần}} = 6a^2, \qquad d = a\sqrt{3}$$

**Tính chất 15 — Hình trụ.** Hình trụ có bán kính đáy $r$ và chiều cao $h$:

$$V = \pi r^2 h, \qquad S_{\text{xung quanh}} = 2\pi r h, \qquad S_{\text{toàn phần}} = 2\pi r h + 2\pi r^2$$

**Tính chất 16 — Hình nón.** Hình nón có bán kính đáy $r$, chiều cao $h$ và đường sinh $l = \sqrt{r^2+h^2}$:

$$V = \frac{1}{3}\pi r^2 h, \qquad S_{\text{xung quanh}} = \pi r l, \qquad S_{\text{toàn phần}} = \pi r l + \pi r^2$$

**Chú ý.** Đường sinh $l$ là cạnh bên của nón, luôn lớn hơn cả $r$ và $h$. Đề cho 母线长 (độ dài đường sinh) chứ không phải chiều cao, muốn tính thể tích phải đổi về chiều cao bằng $h = \sqrt{l^2-r^2}$.

**Tính chất 17 — Hình cầu.** Hình cầu bán kính $R$:

$$V = \frac{4}{3}\pi R^3, \qquad S = 4\pi R^2$$

**Tính chất 18 — Hình chóp và lăng trụ.** Hình chóp có diện tích đáy $S$ và chiều cao $h$ có thể tích $V = \dfrac{1}{3}Sh$. Lăng trụ có cùng đáy và chiều cao có thể tích $V = Sh$.

**Chú ý.** Hệ số $\dfrac{1}{3}$ là điểm khác biệt duy nhất giữa chóp và lăng trụ. Đây là chỗ đề thi hay khai thác: cho đáy và chiều cao rồi hỏi thể tích, đáp án nhiễu thường là $Sh$ hoặc $\dfrac{1}{2}Sh$.

---

## 3. CÁC DẠNG BÀI

### Dạng 1 — Tính diện tích và chu vi hình phẳng

**Cách nhận dạng.** Đề có 面积 (diện tích) hoặc 周长 (chu vi) và cho các yếu tố như cạnh đáy, chiều cao, bán kính.

**Cách làm.** Xác định hình đang xét, chọn đúng công thức, thay số. Với tam giác không vuông và biết ba cạnh thì dùng Heron; biết hai cạnh và góc xen giữa thì dùng $S = \dfrac{1}{2}ab\sin C$.

**Ví dụ 1.** Tam giác có cạnh đáy $6$ và chiều cao tương ứng $5$. Tính diện tích.

**Giải.** Áp dụng $S = \dfrac{1}{2}ah$:

$$S = \frac{1}{2} \cdot 6 \cdot 5 = 15$$

---

### Dạng 2 — Tam giác đồng dạng, tìm cạnh chưa biết

**Cách nhận dạng.** Đề có 相似 (đồng dạng) hoặc cho hai tam giác có các góc bằng nhau, yêu cầu tìm độ dài cạnh.

**Cách làm.** Viết tỉ số các cạnh tương ứng theo đúng thứ tự đỉnh, lập phương trình rồi giải. Đỉnh tương ứng là đỉnh có góc bằng nhau đặt cùng vị trí trong tên tam giác.

**Ví dụ 2.** Tam giác $ABC$ đồng dạng với tam giác $DEF$ với tỉ số đồng dạng $k = 2$. Biết $AB = 3$. Tính $DE$.

**Giải.** Theo định nghĩa tỉ số đồng dạng $\dfrac{DE}{AB} = 2$, suy ra $DE = 2 \cdot 3 = 6$.

---

### Dạng 3 — Tam giác vuông và định lý Pythagoras

**Cách nhận dạng.** Đề có 直角三角形 (tam giác vuông) hoặc 直角 (góc vuông), yêu cầu tìm một cạnh khi biết hai cạnh.

**Cách làm.** Xác định cạnh huyền (cạnh đối diện góc vuông, luôn là cạnh dài nhất), rồi áp dụng $a^2+b^2 = c^2$. Nếu đề cho đường chéo của hình chữ nhật hoặc khoảng cách giữa hai điểm trong mặt phẳng, cũng đưa về tam giác vuông.

**Ví dụ 3.** Tam giác vuông có hai cạnh góc vuông là $3$ và $4$. Tính cạnh huyền.

**Giải.** Áp dụng $c^2 = a^2 + b^2$:

$$c^2 = 3^2 + 4^2 = 9 + 16 = 25 \implies c = 5$$

**Cách nhanh.** Bộ ba $(3,4,5)$ là bộ ba Pythagoras quen thuộc, không cần bấm máy. Ba bộ hay gặp nhất trong đề: $(3,4,5)$, $(5,12,13)$, $(8,15,17)$.

---

### Dạng 4 — Đa giác: tổng góc trong và đa giác đều

**Cách nhận dạng.** Đề có 内角 (góc trong), 多边形 (đa giác) hoặc 正多边形 (đa giác đều).

**Cách làm.** Tổng góc trong của đa giác $n$ cạnh là $(n-2) \cdot 180^\circ$. Với đa giác đều, mỗi góc trong bằng $\dfrac{(n-2) \cdot 180^\circ}{n}$.

**Ví dụ 4.** Tính tổng số đo các góc trong của một lục giác.

**Giải.** Lục giác có $n = 6$ cạnh, tổng góc trong là:

$$(6-2) \cdot 180^\circ = 4 \cdot 180^\circ = 720^\circ$$

---

### Dạng 5 — Đường tròn: chu vi, diện tích, cung và quạt

**Cách nhận dạng.** Đề có 圆 (đường tròn), 半径 (bán kính), 圆心 (tâm), 弧 (cung) hoặc 扇形 (hình quạt).

**Cách làm.** Chu vi $C = 2\pi r$, diện tích $S = \pi r^2$. Với cung và quạt, dùng tỉ lệ $\dfrac{n}{360}$ theo số đo cung.

**Ví dụ 5.** Đường tròn bán kính $3$. Tính chu vi và diện tích.

**Giải.** Chu vi $C = 2\pi \cdot 3 = 6\pi$. Diện tích $S = \pi \cdot 3^2 = 9\pi$.

---

### Dạng 6 — Thể tích và diện tích mặt của hình hộp, hình lập phương

**Cách nhận dạng.** Đề có 正方体 (hình lập phương), 长方体 (hình hộp chữ nhật), 体积 (thể tích) hoặc 表面积 (diện tích mặt).

**Cách làm.** Xác định hình, đọc ba kích thước, áp dụng công thức. Nhớ phân biệt đường chéo mặt $a\sqrt{2}$ và đường chéo khối $a\sqrt{3}$.

**Ví dụ 6.** Hình lập phương cạnh $2a$. Tính thể tích và đường chéo khối.

**Giải.** Thể tích $V = (2a)^3 = 8a^3$. Đường chéo khối $d = 2a\sqrt{3}$.

---

### Dạng 7 — Thể tích và diện tích mặt của hình trụ, hình nón, hình cầu

**Cách nhận dạng.** Đề có 圆柱 (hình trụ), 圆锥 (hình nón), 球 (hình cầu), 母线 (đường sinh).

**Cách làm.** Với trụ dùng $V = \pi r^2 h$ và $S_{\text{xq}} = 2\pi rh$. Với nón phải đổi đường sinh về chiều cao bằng $h = \sqrt{l^2-r^2}$ trước khi tính thể tích. Với cầu dùng $V = \dfrac{4}{3}\pi R^3$ và $S = 4\pi R^2$.

**Ví dụ 7.** Hình nón có bán kính đáy $3$ và đường sinh $5$. Tính thể tích.

**Giải.** Chiều cao $h = \sqrt{l^2-r^2} = \sqrt{25-9} = 4$. Thể tích:

$$V = \frac{1}{3}\pi \cdot 3^2 \cdot 4 = 12\pi$$

**Bẫy.** Dùng nhầm đường sinh $5$ làm chiều cao sẽ ra $15\pi$, là đáp án nhiễu có sẵn trong đề. Luôn đổi về chiều cao trước.

**Nhận xét.** Bộ ba $(3, 4, 5)$ xuất hiện ở cả đường sinh, chiều cao và bán kính của hình nón này: $r = 3$, $h = 4$, $l = 5$. Nhận ra bộ ba này thì không cần tính căn.

---

## PHỤ LỤC — BẢNG CÔNG THỨC TRA NHANH

| Hình | Thể tích | Diện tích mặt |
|:-----|:---------|:--------------|
| Hình hộp chữ nhật $a \times b \times c$ | $abc$ | $2(ab+bc+ca)$ |
| Hình lập phương cạnh $a$ | $a^3$ | $6a^2$ |
| Hình trụ bán kính $r$, cao $h$ | $\pi r^2 h$ | $2\pi rh + 2\pi r^2$ |
| Hình nón bán kính $r$, cao $h$, sinh $l$ | $\dfrac{1}{3}\pi r^2 h$ | $\pi rl + \pi r^2$ |
| Hình cầu bán kính $R$ | $\dfrac{4}{3}\pi R^3$ | $4\pi R^2$ |
| Hình chóp đáy $S$, cao $h$ | $\dfrac{1}{3}Sh$ | — |
| Lăng trụ đáy $S$, cao $h$ | $Sh$ | — |

---

*Tài liệu nội bộ, CAE SHANGHAI.*
