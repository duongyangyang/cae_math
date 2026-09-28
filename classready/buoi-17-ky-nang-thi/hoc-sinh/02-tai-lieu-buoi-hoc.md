# BUỔI 17 — KỸ NĂNG THI （考试技巧）

> **Kỹ năng làm bài trắc nghiệm dưới áp lực thời gian**
> **Phiên bản:** 1.0.0, cập nhật 28.09.2026

---

## 1. TÍNH NHẨM VÀ ƯỚC LƯỢNG

Đề CSCA không cho dùng máy tính. Mọi phép tính đều phải làm trong đầu hoặc trên giấy nháp, và phải xong trong vài chục giây. Phần này gom những kỹ thuật tính nhanh dùng được nhiều nhất.

**Tính chất 1 — Bình phương số tận cùng bằng 5.** Với số có dạng $10a + 5$:

$$(10a+5)^2 = 100a(a+1) + 25$$

Lấy chữ số hàng chục nhân với số liền sau nó, viết kết quả rồi ghép thêm $25$ vào cuối.

**Ví dụ 1.** Tính $35^2$ và $85^2$.

**Giải.** Với $35$: chữ số hàng chục là $3$, số liền sau là $4$, tích $3 \cdot 4 = 12$. Ghép thêm $25$ được $1225$.

Với $85$: $8 \cdot 9 = 72$, ghép thêm $25$ được $7225$.

**Tính chất 2 — Nhân nhanh bằng hiệu hai bình phương.** Với hai số cùng cách đều một mốc $a$:

$$(a-b)(a+b) = a^2 - b^2$$

**Ví dụ 2.** Tính $97 \cdot 103$ và $52 \cdot 48$.

**Giải.** Hai thừa số cùng cách $100$ một khoảng $3$, nên $97 \cdot 103 = 100^2 - 3^2 = 10000 - 9 = 9991$.

Hai thừa số cùng cách $50$ một khoảng $2$, nên $52 \cdot 48 = 50^2 - 2^2 = 2500 - 4 = 2496$.

**Tính chất 3 — Chặn khoảng cho căn bậc hai.** Muốn ước lượng $\sqrt{n}$, tìm hai số chính phương liên tiếp $k^2 \le n < (k+1)^2$. Khi đó $k \le \sqrt{n} < k+1$, và càng gần $k^2$ thì căn càng gần $k$.

**Ví dụ 3.** Ước lượng $\sqrt{57}$ và $\sqrt{130}$.

**Giải.** Vì $49 \le 57 < 64$ nên $7 < \sqrt{57} < 8$. Do $57$ gần $49$ hơn $64$, giá trị nằm ở khoảng $7,5$: cụ thể $\sqrt{57} \approx 7,55$.

Vì $121 \le 130 < 144$ nên $11 < \sqrt{130} < 12$. Do $130$ gần $121$ hơn $144$, giá trị khoảng $11,4$.

**Tính chất 4 — Chặn khoảng cho logarit.** Muốn ước lượng $\log_a N$, tìm hai lũy thừa liên tiếp của $a$ bao quanh $N$. Khi đó giá trị logarit nằm giữa hai số mũ đó.

**Ví dụ 4.** Ước lượng $\log_2 12$ và $\log_3 20$.

**Giải.** Vì $2^3 = 8 < 12 < 16 = 2^4$ nên $3 < \log_2 12 < 4$. Giá trị gần $3,6$.

Vì $3^2 = 9 < 20 < 27 = 3^3$ nên $2 < \log_3 20 < 3$. Do $20$ gần $27$ hơn $9$, giá trị khoảng $2,7$.

**Tính chất 5 — Mốc lũy thừa cần nhớ.** Bốn mốc dùng lại nhiều lần trong đề:

$$2^{10} = 1024 \approx 10^3, \qquad 2^{20} \approx 10^6, \qquad 3^5 = 243, \qquad 5^3 = 125$$

**Ví dụ 5.** So sánh $2^{33}$ với $10^{10}$.

**Giải.** Viết $2^{33} = 2^{30} \cdot 2^3 = (2^{10})^3 \cdot 8 \approx (10^3)^3 \cdot 8 = 8 \cdot 10^9$.

Vì $8 \cdot 10^9 < 10 \cdot 10^9 = 10^{10}$ nên $2^{33} < 10^{10}$.

**Tính chất 6 — Giá trị lượng giác đặc biệt.** Bảng giá trị tại các góc $0^\circ$, $30^\circ$, $45^\circ$, $60^\circ$, $90^\circ$ dùng để kiểm tra đáp án, không dùng để tra khi giải phương trình.

| Góc | $0^\circ$ | $30^\circ$ | $45^\circ$ | $60^\circ$ | $90^\circ$ |
|:----|:---------:|:----------:|:----------:|:----------:|:----------:|
| $\sin$ | $0$ | $\dfrac{1}{2}$ | $\dfrac{\sqrt{2}}{2}$ | $\dfrac{\sqrt{3}}{2}$ | $1$ |
| $\cos$ | $1$ | $\dfrac{\sqrt{3}}{2}$ | $\dfrac{\sqrt{2}}{2}$ | $\dfrac{1}{2}$ | $0$ |
| $\tan$ | $0$ | $\dfrac{\sqrt{3}}{3}$ | $1$ | $\sqrt{3}$ | không xác định |

**Chú ý.** Ba hằng số căn cần nhớ chính xác vì chúng xuất hiện trong đáp án: $\sqrt{2} \approx 1,414$, $\sqrt{3} \approx 1,732$, $\sqrt{5} \approx 2,236$. Nhầm $\sqrt{3}$ với $1,5$ là chọn sai đáp án ở dạng so sánh.

**Chú ý.** Khi ước lượng, chỉ cần biết giá trị nằm giữa hai mốc nào. Đáp án trắc nghiệm thường cách nhau đủ xa để một khoảng ước lượng thô đã loại được ba phương án sai.

---

## 2. ĐỌC ĐỀ NHANH

Phần lớn thời gian mất đi không nằm ở chỗ giải, mà ở chỗ đọc sai yêu cầu. Một câu đọc nhầm từ khóa thì dù biến đổi đúng vẫn ra đáp án sai. Phần này luyện cách tách yêu cầu chính ra khỏi dữ kiện nhiễu.

**Tính chất 7 — Ba tầng của một câu hỏi tiếng Trung.** Mỗi câu có ba tầng: tầng dữ kiện mở đầu bằng 已知 (cho biết) hoặc 设 (đặt); tầng yêu cầu chứa động từ hỏi như 求 (tìm), 等于 (bằng), 是 (là); và tầng phương án. Chỉ cần đọc tầng dữ kiện và tầng yêu cầu, bỏ qua mọi mệnh đề mô tả thêm.

**Tính chất 8 — Từ khóa phủ định đảo ngược yêu cầu.** Bốn từ khóa này biến câu hỏi "chọn cái đúng" thành "chọn cái sai":

| Từ khóa | Nghĩa | Yêu cầu thật |
|:--------|:------|:-------------|
| 不正确 | không đúng | Tìm phương án sai |
| 错误 | sai | Tìm phương án sai |
| 不一定成立 | không nhất thiết đúng | Tìm phương án có phản ví dụ |
| 不相等 | không bằng nhau | Tìm cặp khác nhau |

**Ví dụ 6.** Đọc câu sau và xác định yêu cầu thật.

已知集合 $A=\{a,b,c\}$，则下列不正确的关系是（ ）

**Giải.** Dữ kiện là $A = \{a, b, c\}$. Từ khóa 不正确 nghĩa là "không đúng", nên yêu cầu là tìm phương án **sai**.

Ba phương án $a \in A$, $\{a\} \subseteq A$, $\varnothing \subseteq A$ đều đúng. Phương án $c \notin A$ sai vì $c$ là phần tử của $A$. Đáp án là $c \notin A$.

Nếu đọc thành "tìm quan hệ đúng" thì sẽ chọn nhầm một trong ba phương án đầu.

**Tính chất 9 — Cặp từ khóa ngược hướng xử lý.** Hai cặp từ khóa dưới đây có hình thức giống nhau nhưng cách làm trái ngược:

| Cặp từ khóa | Cách xử lý |
|:------------|:-----------|
| 恒成立 (đúng với mọi $x$) | Dùng điều kiện $\Delta$, tức là buộc cả đường cong nằm một phía |
| 有解 (có nghiệm) | Tìm giá trị nhỏ nhất hoặc lớn nhất của biểu thức |
| 充分条件 (điều kiện đủ) | Kiểm tra $P \Rightarrow Q$ |
| 必要条件 (điều kiện cần) | Kiểm tra $Q \Rightarrow P$ |

**Ví dụ 7.** Đọc câu sau và cho biết cần dùng điều kiện gì.

若关于 $x$ 的不等式 $x^2 + (m-1)x + 1 > 0$ 对于一切实数 $x$ 恒成立，则实数 $m$ 的取值范围是（ ）

**Giải.** Cụm 对于一切实数 $x$ 恒成立 nghĩa là "đúng với mọi số thực $x$". Với hệ số $a = 1 > 0$, điều kiện là $\Delta < 0$.

$$\Delta = (m-1)^2 - 4 < 0 \iff (m-1)^2 < 4 \iff -1 < m < 3$$

Đáp án là $(-1, 3)$.

**Tính chất 10 — Từ khóa giới hạn phạm vi.** Ba từ khóa này thu hẹp tập nghiệm và hay bị bỏ sót:

| Từ khóa | Nghĩa | Ảnh hưởng |
|:--------|:------|:----------|
| 整数 | số nguyên | Nghiệm phải là số nguyên, không lấy khoảng liên tục |
| 正实数 | số thực dương | Loại giá trị $0$ và giá trị âm |
| 定义域 | tập xác định | Phải kiểm tra điều kiện mẫu và căn trước khi biến đổi |

**Chú ý.** Đọc câu hỏi trước, đọc dữ kiện sau. Thói quen đọc tuần tự từ đầu làm mắt bám vào những mệnh đề mô tả không dùng đến, trong khi yêu cầu thật nằm ở cuối câu.

**Chú ý.** Đề CSCA có một số câu chứa dữ kiện thừa có chủ đích. Nếu một dữ kiện không xuất hiện trong bất kỳ bước biến đổi nào, hãy kiểm tra lại xem mình đã đọc đúng yêu cầu chưa, chứ không phải cố dùng nó bằng mọi giá.

---

## 3. KỸ THUẬT TRẮC NGHIỆM

Bốn phương án là một nguồn thông tin. Khi giải trực tiếp tốn thời gian, hãy khai thác chính các phương án để tìm đáp án.

**Tính chất 11 — Thay đáp án vào đề.** Với phương trình, bất phương trình hoặc hệ điều kiện, thay từng phương án vào đề và kiểm tra. Cách này biến bài giải thành bốn phép kiểm tra, thường nhanh hơn giải một lần.

**Ví dụ 8.** Giải nhanh bất phương trình $3x^2 - 2x - 1 < 0$ bằng cách thay giá trị.

A. $\left(-\dfrac{1}{3}, 1\right)$

B. $\left(-1, \dfrac{1}{3}\right)$

C. $(-\infty, -\dfrac{1}{3}) \cup (1, +\infty)$

D. $(-\infty, -1) \cup \left(\dfrac{1}{3}, +\infty\right)$

**Giải.** Lấy $x = 0$ thay vào: $3 \cdot 0 - 2 \cdot 0 - 1 = -1 < 0$, đúng. Vậy $x = 0$ phải nằm trong tập nghiệm.

Phương án A chứa $0$. Phương án B chứa $0$. Phương án C và D đều không chứa $0$, loại cả hai.

Lấy $x = \dfrac{1}{2}$ thay vào: $\dfrac{3}{4} - 1 - 1 = -\dfrac{5}{4} < 0$, đúng. Phương án B không chứa $\dfrac{1}{2}$, loại.

Đáp án là A.

Hai phép thử loại được ba phương án. Không cần giải phương trình bậc hai.

**Tính chất 12 — Loại trừ theo dấu và độ lớn.** Trước khi tính, đọc phương án để tìm hai dấu hiệu loại trừ:

| Dấu hiệu | Cách loại |
|:---------|:----------|
| Dấu của kết quả | Nếu đáp án phải dương thì loại mọi phương án âm |
| Bậc độ lớn | Nếu kết quả cỡ vài đơn vị thì loại phương án cỡ hàng trăm |
| Số phương án đảo ngược | Phương án có dạng đảo tử mẫu là bẫy thường gặp |

**Ví dụ 9.** Tìm tiệm cận của hyperbol $\dfrac{x^2}{16} - \dfrac{y^2}{9} = 1$ mà không viết phương trình.

A. $y = \pm\dfrac{3}{4}x$

B. $y = \pm\dfrac{4}{3}x$

C. $y = \pm\dfrac{16}{9}x$

D. $y = \pm\dfrac{9}{16}x$

**Giải.** Công thức tiệm cận của hyperbol dạng $\dfrac{x^2}{a^2} - \dfrac{y^2}{b^2} = 1$ là $y = \pm\dfrac{b}{a}x$.

Hai dấu hiệu loại trừ: hệ số phải là căn của tỉ số $\dfrac{9}{16}$, tức là $\dfrac{3}{4}$ chứ không phải $\dfrac{16}{9}$ hay $\dfrac{9}{16}$, nên loại C và D. Hệ số phải nhỏ hơn $1$ vì $b = 3 < a = 4$, nên loại B là phương án đảo ngược.

Đáp án là A.

**Tính chất 13 — Kiểm tra bằng giá trị đặc biệt.** Với biểu thức đúng với mọi giá trị của biến, chỉ cần thử một giá trị thuận tiện để loại phương án. Ba giá trị dùng nhiều nhất là $x = 0$, $x = 1$, $x = -1$.

**Ví dụ 10.** Biết $a > b > 0$. Phương án nào đúng?

A. $a^2 < b^2$

B. $\dfrac{1}{a} > \dfrac{1}{b}$

C. $a - b < 0$

D. $\dfrac{a}{b} > 1$

**Giải.** Lấy $a = 2$, $b = 1$ thay vào từng phương án.

A cho $4 < 1$, sai. B cho $\dfrac{1}{2} > 1$, sai. C cho $1 < 0$, sai. D cho $2 > 1$, đúng.

Đáp án là D.

**Tính chất 14 — Ước lượng để loại phương án số.** Khi đáp án là số, ước lượng kết quả về một khoảng rồi chỉ tính chính xác nếu còn lại từ hai phương án trở lên.

**Ví dụ 11.** Tìm tiêu điểm của parabol $y^2 = -12x$.

A. $(3, 0)$

B. $(0, 3)$

C. $(-3, 0)$

D. $(0, -3)$

**Giải.** Parabol dạng $y^2 = 2px$ có tiêu điểm trên trục hoành, nên loại B và D vì chúng có tung độ khác $0$.

Dấu của $2p$ là âm nên tiêu điểm nằm về phía âm của trục hoành, loại A.

Còn lại C. Kiểm tra: $2p = -12$ nên $\dfrac{p}{2} = -3$, tiêu điểm $(-3, 0)$.

**Tính chất 15 — Kiểm tra bằng đơn vị và cấu trúc công thức.** Với câu hỏi công thức, đọc cấu trúc của đáp án trước khi tính. Một công thức đúng phải chứa đủ các đại lượng của đề và đúng bậc.

**Ví dụ 12.** Một hình trụ có bán kính đáy $r$ và chiều cao $h$. Diện tích toàn phần là biểu thức nào?

A. $2\pi rh$

B. $2\pi r^2 + 2\pi rh$

C. $\pi r^2 + 2\pi rh$

D. $\pi r^2 h$

**Giải.** Diện tích toàn phần gồm hai đáy và mặt xung quanh, nên phải có số hạng chứa $r^2$ và số hạng chứa $rh$.

Phương án A chỉ có mặt xung quanh, thiếu hai đáy. Phương án D là công thức thể tích, sai đơn vị. Phương án C chỉ có một đáy.

Đáp án là B.

**Tính chất 16 — Khi không giải được.** Bốn bước xử lý theo thứ tự, dừng ở bước nào có kết quả:

1. Loại phương án sai về dấu, bậc hoặc đơn vị.
2. Thay một giá trị đặc biệt vào đề và vào các phương án còn lại.
3. Thay ngược từng phương án còn lại vào đề.
4. Nếu vẫn còn từ hai phương án, chọn phương án có dạng công thức chuẩn nhất và chuyển sang câu khác.

**Chú ý.** Không bao giờ để trống một câu. Xác suất chọn đúng khi đoán là $25\%$, và sau khi loại được hai phương án thì lên $50\%$. Một câu để trống là mất chắc chắn $25\%$ cơ hội.

**Chú ý.** Phương án có dạng "không xác định", "không có giá trị nào", "vô nghiệm" xuất hiện với tần suất thấp hơn ba phương án còn lại, nhưng không được loại trừ máy móc. Chỉ loại khi đã kiểm tra điều kiện xác định của đề.

---

## 4. QUẢN LÝ THỜI GIAN

Đề có 48 câu trong 60 phút, trung bình 75 giây mỗi câu. Không có cách nào làm hết 48 câu ở mức độ cẩn thận như làm bài kiểm tra trên lớp. Phần này là chiến lược phân bổ thời gian.

**Tính chất 17 — Chia 60 phút thành ba vòng.**

| Vòng | Thời gian | Nhiệm vụ | Mục tiêu |
|:----:|:---------:|:---------|:---------|
| Vòng 1 | 30 phút | Làm mọi câu nhận ra dạng trong 10 giây đầu | Xong khoảng 30 câu |
| Vòng 2 | 20 phút | Quay lại các câu đã đánh dấu | Xong thêm 12 đến 15 câu |
| Vòng 3 | 10 phút | Tô đáp án, kiểm tra câu bỏ trống, soát lỗi ghi | Không còn ô trống |

**Tính chất 18 — Ngưỡng bỏ qua một câu.** Đặt đồng hồ ở mốc 90 giây cho mỗi câu. Hết 90 giây mà chưa có hướng giải, đánh dấu câu đó và chuyển ngay sang câu sau.

**Tính chất 19 — Ba dấu hiệu nên bỏ qua ngay.** Gặp một trong ba dấu hiệu này, chuyển câu:

| Dấu hiệu | Lý do |
|:---------|:------|
| Đề chứa từ ba tham số trở lên và yêu cầu biện luận | Số trường hợp cần xét vượt quá 90 giây |
| Đề yêu cầu dựng hình hoặc đọc đồ thị phức tạp | Không có hình vẽ chính xác thì không kiểm chứng được |
| Đề có dữ kiện dài trên bốn dòng | Thời gian đọc đề đã chiếm hết ngân sách câu |

**Tính chất 20 — Quy tắc đánh dấu.** Dùng ba ký hiệu riêng trên phiếu nháp, không dùng thêm ký hiệu nào khác:

| Ký hiệu | Nghĩa | Hành động ở vòng 2 |
|:-------:|:------|:-------------------|
| Để trống | Đã làm chắc chắn | Không quay lại |
| Dấu hỏi | Đã chọn nhưng chưa chắc | Kiểm tra lại nếu còn thời gian |
| Dấu sao | Chưa làm được | Làm lại từ đầu, tối đa 60 giây |

**Chú ý.** Vòng 1 quan trọng hơn hai vòng sau. Câu dễ làm ở vòng 1 tốn 30 giây, nhưng nếu để đến vòng 3 thì tốn 60 giây vì lúc đó đã mệt và phải đọc lại đề từ đầu. Làm hết câu dễ trước là cách tăng điểm nhanh nhất.

**Chú ý.** Không kiểm tra lại câu đã làm chắc chắn khi còn câu chưa làm. Sửa một câu đúng thành sai vì do dự là lỗi tốn điểm nhiều nhất trong phòng thi.

**Chú ý.** Thời gian tô đáp án chiếm khoảng 3 đến 4 phút cho 48 câu. Phải trừ khoản này ra khỏi 60 phút ngay từ đầu, không được để nó nằm ngoài kế hoạch.

---

## 5. THỰC HÀNH TRONG BUỔI

Đề luyện gồm 20 câu trong 30 phút, in trong `03-de-luyen-bam-gio.md`.

Cách làm bài:

1. Bấm đồng hồ 30 phút, không tạm dừng.
2. Ghi thời gian từng câu vào bảng ở cuối đề.
3. Hết giờ dừng bút ngay, kể cả còn câu chưa làm.
4. Đối chiếu đáp án và đếm số câu làm được trong từng mốc 60 giây, 90 giây, trên 90 giây.

**Chú ý.** Mục tiêu của đề luyện này không phải điểm số, mà là đo tốc độ. Một câu làm đúng trong 100 giây có giá trị thấp hơn một câu làm đúng trong 40 giây, vì trong đề thật thời gian đó phải lấy từ câu khác.

---

*Tài liệu nội bộ, CAE SHANGHAI.*
