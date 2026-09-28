# BUỔI 15 — THỐNG KÊ （统计）

> **Module:** M4 · **Tỉ trọng đề thi:** ~3% (cùng xác suất) · khoảng 1–2 câu
> **Tài liệu học tập, dùng trên lớp và tra cứu khi làm bài**

---

## 1. TỪ KHÓA NHẬN DẠNG ĐỀ

Đọc được từ khóa là xác định được dạng bài mà không cần dịch cả đề. Bảng dưới đây gom những từ khóa quyết định của chuyên đề này.

| Từ khóa | Nghĩa | Dạng bài tương ứng |
|:--------|:------|:-------------------|
| 平均数 | số trung bình cộng | Tính trung bình từ bảng số liệu |
| 加权平均数 | trung bình có trọng số | Trung bình khi các giá trị lặp lại |
| 中位数 | số trung vị | Tìm giá trị giữa của dãy đã sắp xếp |
| 众数 | số mốt | Tìm giá trị xuất hiện nhiều nhất |
| 方差 | phương sai | Đo mức phân tán của dữ liệu |
| 标准差 | độ lệch chuẩn | Căn bậc hai của phương sai |
| 极差 | khoảng biến thiên | Hiệu giữa giá trị lớn nhất và nhỏ nhất |
| 频数 | tần số | Số lần xuất hiện của một giá trị |
| 频率 | tần suất | Tỉ lệ giữa tần số và tổng số |
| 样本容量 | kích thước mẫu | Tổng số phần tử được khảo sát |
| 正态分布 | phân phối chuẩn | Áp dụng quy tắc thực nghiệm |
| 稳定 | ổn định | So sánh độ lệch chuẩn của hai tập |
| 变化趋势 | xu hướng biến đổi | Đọc bảng số liệu theo thời gian |
| 百分位数 | bách phân vị | Xác định vị trí chia dữ liệu |

**Chú ý.** Hai từ khóa 中位数 (trung vị) và 众数 (mốt) rất dễ lẫn vì cùng bắt đầu bằng chữ 数. Trung vị là giá trị **đứng giữa** dãy đã sắp xếp, còn mốt là giá trị **xuất hiện nhiều nhất**. Đọc nhầm hai từ này là mất điểm chắc chắn vì cả hai đều được tính ra một con số cụ thể.

**Chú ý.** 平均数 (trung bình) và 加权平均数 (trung bình có trọng số) khác nhau khi dữ liệu cho dưới dạng bảng. Gặp bảng có cột 频数 hoặc 人数 thì phải nhân giá trị với tần số rồi mới chia, không được cộng các giá trị rồi chia cho số dòng của bảng.

---

## 2. KIẾN THỨC TRỌNG TÂM

### 2.1. Các số đặc trưng của mẫu

**Định nghĩa 1 — Số trung bình cộng.** Cho mẫu số liệu gồm $n$ giá trị $x_1, x_2, \ldots, x_n$. Số trung bình cộng là

$$\bar{x} = \frac{x_1 + x_2 + \cdots + x_n}{n}$$

**Định nghĩa 2 — Số trung bình có trọng số.** Nếu giá trị $x_i$ xuất hiện với tần số $n_i$ và $n_1 + n_2 + \cdots + n_k = n$, thì

$$\bar{x} = \frac{n_1 x_1 + n_2 x_2 + \cdots + n_k x_k}{n}$$

**Chú ý.** Công thức trung bình có trọng số là công thức dùng nhiều nhất trong chuyên đề này. Đề cho bảng hai cột (giá trị và số người) thì luôn dùng công thức này, không dùng công thức ở Định nghĩa 1.

**Định nghĩa 3 — Số trung vị.** Sắp xếp mẫu theo thứ tự không giảm. Nếu số phần tử $n$ là số lẻ, số trung vị là giá trị ở vị trí thứ $\dfrac{n+1}{2}$. Nếu $n$ là số chẵn, số trung vị là trung bình cộng của hai giá trị ở vị trí $\dfrac{n}{2}$ và $\dfrac{n}{2} + 1$.

**Định nghĩa 4 — Số mốt.** Số mốt là giá trị xuất hiện với tần số lớn nhất trong mẫu. Một mẫu có thể có một mốt, nhiều mốt, hoặc không có mốt nào.

**Chú ý.** Điều kiện bắt buộc trước khi tìm trung vị là **phải sắp xếp dãy**. Đề rất hay cho dữ liệu xáo trộn, ví dụ 80, 85, 90, 75, 80, và học sinh lấy ngay phần tử giữa của dãy chưa sắp xếp.

**Định nghĩa 5 — Phương sai.** Phương sai của mẫu số liệu là

$$s^2 = \frac{(x_1 - \bar{x})^2 + (x_2 - \bar{x})^2 + \cdots + (x_n - \bar{x})^2}{n}$$

**Định nghĩa 6 — Độ lệch chuẩn.** Độ lệch chuẩn là căn bậc hai của phương sai:

$$s = \sqrt{s^2}$$

**Định nghĩa 7 — Khoảng biến thiên.** Khoảng biến thiên (极差) là hiệu giữa giá trị lớn nhất và giá trị nhỏ nhất của mẫu.

**Chú ý.** Đơn vị của phương sai là **bình phương** đơn vị của dữ liệu, còn đơn vị của độ lệch chuẩn **trùng** với đơn vị dữ liệu. Vì thế khi đề hỏi mức phân tán theo cùng đơn vị đo, phải dùng độ lệch chuẩn.

### 2.2. Tính chất của các số đặc trưng

**Tính chất 1 — Biến đổi cộng.** Nếu cộng thêm cùng một số $a$ vào mọi giá trị của mẫu thì số trung bình cộng tăng thêm $a$, còn phương sai và độ lệch chuẩn **không đổi**.

**Tính chất 2 — Biến đổi nhân.** Nếu nhân mọi giá trị của mẫu với cùng một số $k \neq 0$ thì số trung bình cộng nhân với $k$, phương sai nhân với $k^2$, độ lệch chuẩn nhân với $\lvert k \rvert$.

**Chú ý.** Tính chất 1 là công cụ cho đáp án trong vài giây. Đề cho trung bình cũ và phương sai cũ, yêu cầu tính sau khi cộng thêm điểm: trung bình cộng thêm, phương sai giữ nguyên. Không cần tính lại từng giá trị.

**Tính chất 3 — Ý nghĩa của phương sai.** Phương sai và độ lệch chuẩn đo mức độ phân tán của dữ liệu quanh số trung bình. Hai mẫu có cùng số trung bình thì mẫu nào có độ lệch chuẩn nhỏ hơn là mẫu ổn định hơn, tức các giá trị tập trung gần trung bình hơn.

**Tính chất 4 — Quan hệ giữa ba số đặc trưng.** Với phân phối chuẩn, số trung bình, số trung vị và số mốt **trùng nhau** và cùng nằm tại đỉnh của đường cong.

### 2.3. Phân phối chuẩn và quy tắc thực nghiệm

**Định nghĩa 8 — Phân phối chuẩn.** Phân phối chuẩn $N(\mu, \sigma^2)$ là phân phối của biến ngẫu nhiên liên tục có đồ thị là đường cong hình chuông đối xứng qua đường thẳng $x = \mu$. Tham số $\mu$ là số trung bình, $\sigma$ là độ lệch chuẩn.

**Tính chất 5 — Quy tắc thực nghiệm 68–95–99,7.** Với biến ngẫu nhiên $X$ có phân phối chuẩn:

$$P(\mu - \sigma < X < \mu + \sigma) \approx 68\%$$

$$P(\mu - 2\sigma < X < \mu + 2\sigma) \approx 95\%$$

$$P(\mu - 3\sigma < X < \mu + 3\sigma) \approx 99,7\%$$

**Tính chất 6 — Đối xứng của đường cong.** Đường cong chuông đối xứng qua đường thẳng $x = \mu$, nên

$$P(X < \mu - a) = P(X > \mu + a)$$

**Chú ý.** Tính chất 6 là chìa khóa xử lý nhóm câu hỏi phân phối chuẩn trong đề thi. Đề cho $P(X < 1,9) = 0,1$ với $\mu = 2$ và hỏi $P(X < 2,1)$: nhận ra $1,9$ và $2,1$ đối xứng qua $\mu = 2$, suy ra $P(X > 2,1) = 0,1$, do đó $P(X < 2,1) = 1 - 0,1 = 0,9$. Không cần tra bảng.

**Cách nhanh.** Muốn tính phần đuôi ngoài khoảng $\mu \pm 3\sigma$: tổng hai đuôi là $100\% - 99,7\% = 0,3\%$, mỗi đuôi bằng $0,15\%$. Với khoảng $\mu \pm 2\sigma$ thì mỗi đuôi bằng $\dfrac{100\% - 95\%}{2} = 2,5\%$.

---

## 3. CÁC DẠNG BÀI

### Dạng 1 — Tính trung bình, trung vị, mốt từ bảng số liệu

**Cách nhận dạng.** Đề cho một bảng hai cột hoặc một dãy số, hỏi 平均数, 中位数 hay 众数. Đây là dạng xuất hiện nhiều nhất trong chuyên đề.

**Cách làm.** Đọc kỹ đề hỏi số đặc trưng nào. Với trung bình, dùng công thức trung bình có trọng số khi dữ liệu ở dạng bảng. Với trung vị, sắp xếp dãy trước rồi xác định vị trí giữa. Với mốt, đếm tần số và lấy giá trị có tần số lớn nhất.

**Ví dụ 1.** Cho bảng chiều cao của 10 học sinh:

| Chiều cao (cm) | 160 | 165 | 170 | 175 | 180 |
|:---:|:---:|:---:|:---:|:---:|:---:|
| Số học sinh | 2 | 3 | 3 | 1 | 1 |

Tìm chiều cao trung bình.

**Giải.** Tổng số học sinh là $2 + 3 + 3 + 1 + 1 = 10$. Áp dụng công thức trung bình có trọng số:

$$\bar{x} = \frac{160 \cdot 2 + 165 \cdot 3 + 170 \cdot 3 + 175 \cdot 1 + 180 \cdot 1}{10} = \frac{1680}{10} = 168$$

Vậy chiều cao trung bình là $168$ cm.

**Bẫy.** Nếu cộng năm giá trị $160, 165, 170, 175, 180$ rồi chia cho $5$ sẽ được $170$, một đáp án nhiễu rất dễ chọn. Bảng có cột số người thì bắt buộc dùng trung bình có trọng số.

---

### Dạng 2 — Tính phương sai và độ lệch chuẩn

**Cách nhận dạng.** Đề cho một dãy số hoặc bảng tần số và hỏi 方差 (phương sai) hoặc 标准差 (độ lệch chuẩn). Đáp án thường là số thập phân.

**Cách làm.** Ba bước theo thứ tự: tính số trung bình, tính tổng bình phương các độ lệch, chia cho $n$. Nếu đề hỏi độ lệch chuẩn thì lấy thêm căn bậc hai.

**Ví dụ 2.** Tính phương sai của dãy số $7, 8, 10, 12, 13$.

**Giải.** Số trung bình:

$$\bar{x} = \frac{7 + 8 + 10 + 12 + 13}{5} = \frac{50}{5} = 10$$

Tổng bình phương các độ lệch:

$$(7-10)^2 + (8-10)^2 + (10-10)^2 + (12-10)^2 + (13-10)^2 = 9 + 4 + 0 + 4 + 9 = 26$$

Phương sai:

$$s^2 = \frac{26}{5} = 5{,}2$$

**Cách nhanh.** Với dãy có số trung bình là số nguyên đẹp, bình phương các độ lệch đều là số nguyên nhỏ nên cộng nhẩm được. Chọn trung bình làm gốc thay vì bình phương từng giá trị gốc giúp tránh số lớn.

---

### Dạng 3 — Bài toán biến đổi dữ liệu

**Cách nhận dạng.** Đề cho trung bình và phương sai của dữ liệu gốc, sau đó yêu cầu tìm trung bình hoặc phương sai của dữ liệu mới tạo bằng cách cộng thêm hoặc nhân với một số. Từ khóa: 都增加 (đều tăng thêm), 都减 (đều giảm), 都变为原来的 (đều thành gấp bấy nhiêu lần).

**Cách làm.** Dùng Tính chất 1 và Tính chất 2. Cộng thêm $a$: trung bình cộng thêm $a$, phương sai giữ nguyên. Nhân với $k$: trung bình nhân $k$, phương sai nhân $k^2$.

**Ví dụ 3.** Trung bình môn Toán của một lớp là $80$ điểm, phương sai là $25$. Nếu mỗi học sinh được cộng thêm $5$ điểm, tìm trung bình và phương sai mới.

**Giải.** Phép biến đổi là cộng thêm $5$ vào mọi giá trị, tức $a = 5$. Theo Tính chất 1, trung bình tăng thêm $5$ còn phương sai không đổi:

$$\bar{x}_{\text{mới}} = 80 + 5 = 85, \qquad s^2_{\text{mới}} = 25$$

**Chú ý.** Phương sai không đổi vì phép cộng chỉ **dịch chuyển** cả dãy số, không làm các giá trị xa nhau hơn. Học sinh hay chọn đáp án có phương sai $30$ vì nghĩ rằng "thêm điểm thì phải thay đổi".

---

### Dạng 4 — Đọc và lập bảng phân phối tần số

**Cách nhận dạng.** Đề cho bảng phân chia dữ liệu thành các khoảng (分数段, 身高范围) kèm số người, hỏi tần suất, tỉ lệ phần trăm, số người trong một khoảng, hoặc khoảng chứa trung vị.

**Cách làm.** Tổng số người là mẫu số chung. Tần suất của một khoảng bằng số người trong khoảng chia cho tổng số. Muốn tìm khoảng chứa trung vị, cộng dồn tần số cho đến khi vượt qua vị trí giữa của mẫu.

**Ví dụ 4.** Bảng phân phối điểm của 30 học sinh:

| Khoảng điểm | 60 - 69 | 70 - 79 | 80 - 89 | 90 - 100 |
|:---:|:---:|:---:|:---:|:---:|
| Số học sinh | 5 | 11 | 11 | 3 |

Tìm khoảng chứa số trung vị.

**Giải.** Mẫu có $30$ phần tử chẵn, số trung vị là trung bình cộng của giá trị thứ $15$ và thứ $16$ sau khi sắp xếp. Cộng dồn tần số: khoảng $60-69$ chứa các vị trí $1$ đến $5$; khoảng $70-79$ chứa các vị trí $6$ đến $16$.

Cả vị trí $15$ và $16$ đều nằm trong khoảng $70-79$, vậy khoảng chứa trung vị là $70-79$.

**Nhận xét.** Không cần biết giá trị cụ thể của từng học sinh, chỉ cần cộng dồn tần số để xác định vị trí. Đây là điểm khác biệt so với dữ liệu cho dưới dạng liệt kê.

---

### Dạng 5 — Áp dụng quy tắc thực nghiệm của phân phối chuẩn

**Cách nhận dạng.** Đề có cụm 正态分布 hoặc ký hiệu $N(\mu, \sigma^2)$, kèm câu hỏi về tỉ lệ phần trăm, số học sinh, hoặc xác suất trong một khoảng. Đề thường in kèm ba số $0,6827$; $0,9545$; $0,9973$.

**Cách làm.** Viết $\mu$ và $\sigma$ ra nháp. Biểu diễn hai đầu mút của khoảng đã cho dưới dạng $\mu \pm k\sigma$. Đối chiếu $k$ với $1$, $2$, $3$ rồi đọc tỉ lệ tương ứng. Nếu khoảng chỉ là một phía, lấy hiệu $100\%$ trừ phần giữa rồi chia đôi.

**Ví dụ 5.** Điểm một kỳ thi có phân phối chuẩn $N(102, 4^2)$. Tìm tỉ lệ thí sinh đạt trên $114$ điểm.

**Giải.** Ta có $\mu = 102$ và $\sigma = 4$. Đầu mút $114 = 102 + 12 = \mu + 3\sigma$.

Theo quy tắc thực nghiệm, khoảng $\mu \pm 3\sigma$ chứa $99,7\%$ dữ liệu, nên phần nằm ngoài khoảng này ở cả hai phía là $100\% - 99,7\% = 0,3\%$.

Do đường cong đối xứng, phần đuôi bên phải bằng nửa phần ngoài khoảng:

$$\frac{0,3\%}{2} = 0,15\%$$

Vậy khoảng $0,135\%$ thí sinh đạt trên $114$ điểm.

**Chú ý.** Kết quả phải nhỏ hơn $0,5\%$ vì $114$ đã cách trung bình tới ba lần độ lệch chuẩn. Đáp án nhiễu thường là $1,35\%$ hoặc $3,15\%$, tức quên chia đôi phần đuôi.

---

### Dạng 6 — So sánh mức độ phân tán của hai tập dữ liệu

**Cách nhận dạng.** Đề cho hai nhóm có cùng số trung bình nhưng khác phương sai hoặc độ lệch chuẩn, hỏi nhóm nào ổn định hơn, nhóm nào có thành tích đồng đều hơn, hoặc rút ra nhận xét đúng.

**Cách làm.** Độ lệch chuẩn nhỏ hơn ứng với dữ liệu tập trung hơn quanh trung bình, tức nhóm ổn định hơn. Không kết luận được gì về giá trị lớn nhất hay nhỏ nhất của hai nhóm nếu chỉ biết trung bình và độ lệch chuẩn.

**Ví dụ 6.** Hai nhóm học sinh có cùng điểm trung bình môn Toán. Nhóm A có phương sai nhỏ hơn nhóm B. Hỏi nhóm nào có thành tích ổn định hơn?

**Giải.** Phương sai đo mức phân tán quanh số trung bình. Phương sai nhỏ hơn nghĩa là các giá trị nằm gần trung bình hơn, tức mức độ dao động thấp hơn.

Vậy nhóm A có thành tích ổn định hơn.

**Bẫy.** Các đáp án kiểu "nhóm A có điểm cao nhất cao hơn" hoặc "nhóm B có điểm thấp nhất thấp hơn" đều không suy ra được từ dữ kiện phương sai. Phương sai không cho thông tin về giá trị cực trị.

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

Thời gian trung bình mỗi câu là **1 phút 15 giây**. Thống kê nằm ở nhóm câu cuối đề, mức độ chủ yếu là dễ và trung bình, nên đây là phần nên làm trọn vẹn điểm.

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

Thống kê chia chung nhóm 1 đến 2 câu với xác suất, trong đó xác suất thường chiếm một câu. Hai dạng hay gặp nhất của phần thống kê là tính số đặc trưng từ bảng tần số và áp dụng quy tắc thực nghiệm cho phân phối chuẩn.

---

*Tài liệu nội bộ, CAE SHANGHAI.*
