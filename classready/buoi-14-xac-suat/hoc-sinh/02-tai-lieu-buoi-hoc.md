# BUỔI 14 — XÁC SUẤT （概率）

> **Module:** M4 · **Tỉ trọng đề thi:** ~3% (cùng thống kê) · khoảng 1–2 câu
> **Tài liệu học tập, dùng trên lớp và tra cứu khi làm bài**

---

## 1. TỪ KHÓA NHẬN DẠNG ĐỀ

Đọc được từ khóa là xác định được dạng bài mà không cần dịch cả đề. Bảng dưới đây gom những từ khóa quyết định của chuyên đề này.

| Từ khóa | Nghĩa | Dạng bài tương ứng |
|:--------|:------|:-------------------|
| 概率 | xác suất | Câu hỏi cơ bản, mọi dạng bài đều có |
| 随机抽取 | chọn ngẫu nhiên | Xác suất cổ điển, đếm kết quả thuận lợi |
| 从中随机取出 | lấy ngẫu nhiên từ đó | Rút bóng, rút thẻ, chọn người |
| 至少 | ít nhất | Dùng biến cố đối, tính $1-P(\overline{A})$ |
| 至多 | nhiều nhất | Cộng xác suất các trường hợp rời nhau |
| 恰好 | đúng, vừa đúng | Đếm chính xác bằng tổ hợp |
| 互斥 | xung khắc | Cộng trực tiếp $P(A)+P(B)$ |
| 对立事件 | biến cố đối | $P(A)+P(\overline{A})=1$ |
| 相互独立 | độc lập với nhau | Nhân xác suất $P(A)\cdot P(B)$ |
| 不放回 | không hoàn lại | Mẫu số giảm dần sau mỗi lần lấy |
| 有放回 | có hoàn lại | Mẫu số giữ nguyên mỗi lần lấy |
| 条件概率 | xác suất có điều kiện | $P(A \mid B)$ |

**Chú ý.** Ba từ khóa quyết định toàn bộ hướng giải: 互斥 (xung khắc) cho phép cộng thẳng hai xác suất; 相互独立 (độc lập) cho phép nhân thẳng hai xác suất; 至少 (ít nhất) thì không tính trực tiếp mà đi qua biến cố đối. Đọc sai một trong ba từ này là chọn sai công thức ngay từ dòng đầu.

**Chú ý.** 不放回 và 有放回 khác nhau ở mẫu số. Đề không ghi gì thì hiểu ngầm là 不放回 (không hoàn lại), tức mẫu số giảm đi sau mỗi lần lấy.

---

## 2. KIẾN THỨC TRỌNG TÂM

### 2.1. Phép thử, không gian mẫu và biến cố

**Định nghĩa 1 — Phép thử ngẫu nhiên.** Phép thử ngẫu nhiên là phép thử mà ta không đoán trước được kết quả, nhưng biết được tập hợp mọi kết quả có thể xảy ra.

**Định nghĩa 2 — Không gian mẫu.** Không gian mẫu $\Omega$ là tập hợp mọi kết quả có thể xảy ra của một phép thử.

**Định nghĩa 3 — Biến cố.** Biến cố $A$ là một tập con của không gian mẫu $\Omega$. Biến cố $\Omega$ gọi là biến cố chắc chắn, biến cố $\varnothing$ gọi là biến cố không thể.

**Định nghĩa 4 — Biến cố đối.** Biến cố đối của $A$, kí hiệu $\overline{A}$, là tập hợp các kết quả thuộc $\Omega$ mà không thuộc $A$.

**Chú ý.** Trong đề thi, biến cố thường được phát biểu bằng lời, ví dụ 抽到女生 (chọn được học sinh nữ). Việc đầu tiên là chuyển phát biểu đó thành một tập hợp kết quả cụ thể, rồi mới đếm.

### 2.2. Xác suất cổ điển

**Định nghĩa 5 — Xác suất cổ điển.** Khi không gian mẫu có hữu hạn phần tử và mọi kết quả đều có khả năng xảy ra như nhau, xác suất của biến cố $A$ là:

$$P(A) = \frac{\text{số kết quả thuận lợi cho } A}{\text{số phần tử của } \Omega}$$

**Chú ý.** Công thức này biến bài toán xác suất thành hai bài toán đếm. Sai xác suất gần như luôn là sai ở bước đếm mẫu số, không phải sai công thức. Luôn tự hỏi: tổng số kết quả là bao nhiêu, có tính đến thứ tự hay không.

**Tính chất 1 — Ba tính chất cơ bản.**

$$0 \le P(A) \le 1, \qquad P(\Omega) = 1, \qquad P(\varnothing) = 0$$

**Chú ý.** Đáp án lớn hơn $1$ hoặc nhỏ hơn $0$ trong đề trắc nghiệm là đáp án nhiễu, loại được ngay mà không cần tính. Gặp 1.5 hay 1.4 trong bốn phương án thì đó là phương án sai chắc chắn.

### 2.3. Các công thức tính xác suất

**Tính chất 2 — Biến cố đối.**

$$P(\overline{A}) = 1 - P(A)$$

**Chú ý.** Đây là công thức đắt giá nhất của chuyên đề. Mọi bài toán chứa từ 至少 (ít nhất) đều đi theo hướng: chuyển sang biến cố đối là 一件都不 (không có cái nào), tính xác suất đó bằng phép nhân, rồi lấy $1$ trừ đi. Đếm trực tiếp “ít nhất một” phải chia thành nhiều trường hợp, rất dễ sót.

**Tính chất 3 — Công thức cộng cho biến cố xung khắc.** Nếu $A$ và $B$ xung khắc (không thể cùng xảy ra) thì:

$$P(A \cup B) = P(A) + P(B)$$

**Tính chất 4 — Công thức cộng tổng quát.** Với hai biến cố bất kì:

$$P(A \cup B) = P(A) + P(B) - P(A \cap B)$$

**Chú ý.** Khi đề cho 互斥 thì phần giao bằng $0$ và công thức tổng quát thu về công thức xung khắc. Khi đề cho cả hai xác suất riêng lẻ lẫn xác suất giao, phải dùng công thức tổng quát; dùng nhầm công thức xung khắc là lỗi phổ biến nhất của chuyên đề này.

**Tính chất 5 — Biến cố độc lập.** Hai biến cố $A$ và $B$ độc lập khi và chỉ khi:

$$P(A \cap B) = P(A) \cdot P(B)$$

**Hệ quả.** Nếu $A$ và $B$ độc lập thì:

$$P(A \cup B) = 1 - P(\overline{A}) \cdot P(\overline{B})$$

**Chú ý.** Hệ quả này là dạng gộp của hai bước: đi qua biến cố đối rồi dùng tính độc lập để nhân. Đề cho hai xác suất riêng lẻ và hỏi 至少通过一门 (ít nhất đạt một môn) thì áp dụng thẳng, không cần suy luận thêm.

**Tính chất 6 — Xác suất có điều kiện.** Xác suất của $A$ với điều kiện $B$ đã xảy ra là:

$$P(A \mid B) = \frac{P(A \cap B)}{P(B)}$$

**Hệ quả.** $P(A \cap B) = P(A \mid B) \cdot P(B)$.

**Chú ý.** Cụm 如果随机选出一位喜欢打篮球的学生，那么这位学生也喜欢踢足球 (nếu chọn ngẫu nhiên một học sinh thích bóng rổ, thì xác suất em đó cũng thích bóng đá) chính là xác suất có điều kiện. Mẫu số không còn là cả lớp mà là số học sinh thích bóng rổ. Đây là chỗ hay nhầm mẫu số nhất.

### 2.4. Quy tắc đếm

**Tính chất 7 — Hoán vị, chỉnh hợp, tổ hợp.** Với $n$ phần tử phân biệt:

| Phép đếm | Công thức | Dùng khi |
|:---------|:----------|:---------|
| Hoán vị | $P_n = n!$ | Sắp xếp toàn bộ $n$ phần tử, có thứ tự |
| Chỉnh hợp | $A_n^k = \dfrac{n!}{(n-k)!}$ | Chọn $k$ phần tử và sắp thứ tự |
| Tổ hợp | $C_n^k = \dfrac{n!}{k!(n-k)!}$ | Chọn $k$ phần tử, không quan tâm thứ tự |

**Chú ý.** Câu hỏi quyết định dùng chỉnh hợp hay tổ hợp là: đổi chỗ hai phần tử đã chọn có cho ra kết quả khác không. Rút hai quả bóng cùng lúc thì không phân biệt thứ tự, dùng $C$. Lấy lần lượt quả thứ nhất rồi quả thứ hai thì có phân biệt, dùng $A$. Chọn nhầm sẽ lệch mẫu số một khoảng đúng bằng $k!$.

**Cách nhanh.** Hai công thức hay dùng nhất khi đếm:

$$C_n^1 = n, \qquad C_n^2 = \frac{n(n-1)}{2}$$

Với bài rút hai vật, mẫu số gần như luôn là $\dfrac{n(n-1)}{2}$. Tính nhẩm được ngay, không cần viết giai thừa.

**Tính chất 8 — Công thức Bernoulli.** Thực hiện $n$ lần phép thử độc lập, xác suất thành công mỗi lần đều bằng $p$. Xác suất có đúng $k$ lần thành công là:

$$P = C_n^k \, p^k (1-p)^{n-k}$$

**Chú ý.** Dấu hiệu nhận dạng là 每次抽奖是相互独立的 (mỗi lần là độc lập) cộng với 恰好 $k$ 次 (đúng $k$ lần). Nhân với $C_n^k$ vì $k$ lần thành công có thể rơi vào bất kì vị trí nào trong $n$ lần. Quên hệ số $C_n^k$ là lỗi chính của dạng này.

---

## 3. CÁC DẠNG BÀI

### Dạng 1 — Xác suất cổ điển đếm trực tiếp

**Cách nhận dạng.** Đề cho một phép thử có số kết quả hữu hạn và ít, ví dụ gieo xúc xắc, tung đồng xu, rút thẻ. Câu hỏi thường kèm 概率 (xác suất) và một điều kiện mô tả bằng lời.

**Cách làm.** Liệt kê không gian mẫu bằng cách đếm số kết quả, rồi đếm số kết quả thuận lợi. Với hai lần gieo xúc xắc, mẫu số là $6 \times 6 = 36$. Với ba lần tung đồng xu, mẫu số là $2^3 = 8$.

**Ví dụ 1.** Gieo một xúc xắc hai lần. Tính xác suất tổng số chấm của hai lần bằng $7$.

**Giải.** Không gian mẫu gồm $6 \times 6 = 36$ kết quả. Các cặp có tổng bằng $7$ là:

$$(1,6), (2,5), (3,4), (4,3), (5,2), (6,1)$$

Có $6$ kết quả thuận lợi.

$$P = \frac{6}{36} = \frac{1}{6}$$

---

### Dạng 2 — Dùng tổ hợp để đếm kết quả thuận lợi

**Cách nhận dạng.** Đề rút nhiều vật cùng lúc từ một tập hợp, hoặc chọn một nhóm người từ một danh sách. Các từ khóa đi kèm là 从中随机取出 (lấy ngẫu nhiên từ đó), 随机选出 (chọn ngẫu nhiên ra), 恰好 (đúng).

**Cách làm.** Mẫu số là số cách chọn toàn bộ theo yêu cầu, thường là $C_n^k$. Tử số là tích các số cách chọn từng nhóm con, ví dụ chọn $a$ vật loại một và $b$ vật loại hai thì tử số là $C_{n_1}^{a} \cdot C_{n_2}^{b}$.

**Ví dụ 2.** Một hộp có $3$ quả bóng đỏ, $2$ quả trắng và $4$ quả xanh. Lấy ngẫu nhiên $3$ quả. Tính xác suất lấy được ba quả khác màu nhau.

**Giải.** Tổng số cách lấy $3$ quả từ $9$ quả:

$$C_9^3 = \frac{9 \cdot 8 \cdot 7}{6} = 84$$

Để ba quả khác màu, mỗi màu lấy đúng một quả. Số cách thuận lợi:

$$C_3^1 \cdot C_2^1 \cdot C_4^1 = 3 \cdot 2 \cdot 4 = 24$$

$$P = \frac{24}{84} = \frac{2}{7}$$

**Cách nhanh.** Với ba nhóm và mỗi nhóm lấy đúng một vật, tử số luôn là tích số lượng của ba nhóm. Không cần viết tổ hợp, chỉ cần nhân ba số $3$, $2$, $4$ là ra $24$.

---

### Dạng 3 — Biến cố đối cho bài toán ít nhất

**Cách nhận dạng.** Đề có chữ 至少 (ít nhất) hoặc 至少有一 (có ít nhất một). Đây là dấu hiệu rõ nhất và cũng là dạng xuất hiện nhiều nhất trong đề thật.

**Cách làm.** Đặt $A$ là biến cố cần tính. Biến cố đối $\overline{A}$ là không có kết quả nào thỏa mãn, tức là trường hợp toàn bộ đều không đạt. Tính $P(\overline{A})$ bằng phép nhân (vì các lần độc lập), rồi lấy $1$ trừ đi.

**Ví dụ 3.** Một xưởng sản xuất có tỉ lệ sản phẩm đạt chuẩn là $98\%$. Lấy ngẫu nhiên $2$ sản phẩm. Tính xác suất có ít nhất một sản phẩm đạt chuẩn.

**Giải.** Gọi $A$ là biến cố “có ít nhất một sản phẩm đạt chuẩn”. Biến cố đối $\overline{A}$ là “cả hai sản phẩm đều không đạt chuẩn”.

Tỉ lệ không đạt chuẩn là $1 - 0.98 = 0.02$. Vì hai lần lấy độc lập:

$$P(\overline{A}) = 0.02 \times 0.02 = 0.0004$$

$$P(A) = 1 - 0.0004 = 0.9996$$

**Bẫy.** Đáp án nhiễu hay đặt ở dạng $1 - 0.98^2$ (tức lấy đối của “cả hai đều đạt” thay vì đối của “cả hai đều không đạt”). Đọc kĩ biến cố đối đang mô tả cái gì trước khi lấy $1$ trừ.

---

### Dạng 4 — Công thức cộng, công thức nhân và xác suất có điều kiện

**Cách nhận dạng.** Đề cho hai biến cố và hỏi $P(A \cup B)$ hoặc $P(A \cap B)$, kèm một trong hai từ khóa 互斥 (xung khắc) hoặc 相互独立 (độc lập). Biến thể khó hơn cho thêm một điều kiện đã biết, nhận ra qua cụm 如果随机选出一位……那么 (nếu chọn ngẫu nhiên một…… thì).

**Cách làm.** Đọc từ khóa để chọn công thức. Xung khắc thì cộng thẳng. Độc lập thì nhân để tìm phần giao, rồi áp công thức tổng quát. Nếu đề đã cho phần giao thì luôn dùng công thức tổng quát. Với biến thể có điều kiện, xác định lại mẫu số là nhóm đứng sau chữ 如果, rồi áp $P(A \mid B) = \dfrac{P(A \cap B)}{P(B)}$.

**Ví dụ 4.** Biết $P(A) = 0.4$ và $P(B) = 0.5$, hai biến cố độc lập. Tính $P(A \cup B)$.

**Giải.** Vì $A$ và $B$ độc lập:

$$P(A \cap B) = 0.4 \times 0.5 = 0.2$$

Áp dụng công thức cộng tổng quát:

$$P(A \cup B) = 0.4 + 0.5 - 0.2 = 0.7$$

**Cách nhanh.** Với hai biến cố độc lập, dùng thẳng $P(A \cup B) = 1 - P(\overline{A}) \cdot P(\overline{B})$:

$$P(A \cup B) = 1 - 0.6 \times 0.5 = 1 - 0.3 = 0.7$$

Hai cách cho cùng kết quả, nhưng cách đi qua biến cố đối ít bước hơn và ít sai dấu hơn.

**Ví dụ 5.** Một lớp có $60\%$ học sinh thích bóng đá, $30\%$ thích bóng rổ và $10\%$ thích cả hai. Chọn ngẫu nhiên một học sinh thích bóng rổ. Tính xác suất em đó cũng thích bóng đá.

**Giải.** Gọi $A$ là “thích bóng đá”, $B$ là “thích bóng rổ”. Đề cho $P(A \cap B) = 0.1$ và $P(B) = 0.3$. Cần tính $P(A \mid B)$.

$$P(A \mid B) = \frac{0.1}{0.3} = \frac{1}{3}$$

**Bẫy.** Đáp án nhiễu thường là $0.1$ (lấy luôn phần giao) hoặc $\dfrac{0.1}{0.6}$ (chia nhầm cho nhóm bóng đá). Mẫu số phải là xác suất của nhóm đứng sau chữ 如果.

---

### Dạng 5 — Công thức Bernoulli cho đúng $k$ lần thành công

**Cách nhận dạng.** Đề lặp lại một phép thử $n$ lần độc lập với cùng một xác suất thành công, và hỏi xác suất có đúng $k$ lần thành công. Từ khóa là 恰好 $k$ 次 (đúng $k$ lần) cộng với 相互独立 (độc lập).

**Cách làm.** Xác định $n$, $k$, $p$ rồi áp thẳng $C_n^k \, p^k (1-p)^{n-k}$. Hệ số $C_n^k$ là phần dễ quên nhất.

**Ví dụ 6.** Một đề kiểm tra có $10$ câu trắc nghiệm, mỗi câu có $4$ phương án và chỉ một phương án đúng. Một học sinh chọn ngẫu nhiên cả $10$ câu. Tính xác suất em đó đúng đúng $3$ câu.

**Giải.** Mỗi câu là một phép thử độc lập với xác suất đúng $p = \dfrac{1}{4}$ và xác suất sai $1 - p = \dfrac{3}{4}$. Cần đúng $k = 3$ trong $n = 10$ câu.

$$P = C_{10}^3 \left(\frac{1}{4}\right)^3 \left(\frac{3}{4}\right)^7$$

**Nhận xét.** Đề thi chỉ hỏi biểu thức chứ không yêu cầu tính ra số, vì kết quả là một phân số lớn. Nhận ra điều này để không mất thời gian khai triển.

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

Thời gian trung bình mỗi câu là **1 phút 15 giây**. Xác suất là nhóm nội dung nhỏ nhưng các câu ở mức dễ, nên đây là phần nên làm trọn vẹn điểm thay vì bỏ qua.

### Trọng số các nhóm nội dung

| Nhóm nội dung | Số câu | Tỉ trọng |
|:--------------|:------:|:--------:|
| Lượng giác | 8–11 | ~20\% |
| Hình học giải tích | 8–10 | ~19\% |
| Dãy số | 5–8 | ~13\% |
| Hàm số | 5–7 | ~13\% |
| Tập hợp & bất đẳng thức | 4–6 | ~10\% |
| Mũ & logarit | 3–5 | ~8\% |
| Vector & số phức | 2–4 | ~6\% |
| **Xác suất & thống kê** | **1–2** | **~3\%** |

Xác suất và thống kê chia nhau khoảng 1 đến 2 câu trong mỗi đề, trong đó xác suất thường chiếm một câu. Dạng hay gặp nhất là bài toán ít nhất và bài toán rút vật dùng tổ hợp.

---

*Tài liệu nội bộ, CAE SHANGHAI.*
