# TEMPLATE BIÊN SOẠN CHUYÊN ĐỀ TOÁN — CAE SHANGHAI

> **Mục đích:** Hướng dẫn cấu trúc để biên soạn nội dung chuyên đề toán dưới dạng Markdown. Khi chuyển sang `.tex`, mỗi loại nội dung tương ứng với một môi trường LaTeX đã định nghĩa sẵn.
>
> **Nguyên tắc chung:**
> - Mọi công thức toán học đặt trong `$...$` (inline) hoặc `$$...$$` (display).
> - Mỗi phần nội dung **bắt đầu bằng tín hiệu in đậm đúng loại** (ghi rõ bên dưới).
> - Chỉ **3 loại nội dung** có khung: **Định nghĩa**, **Định lý/Tính chất**, **Ví dụ**. Các loại khác viết thành đoạn văn thường, không khung.
> - Không đặt tiêu đề `##` bên trong một block nội dung.

---

## CẤU TRÚC CHUNG

Mỗi file `.md` = **một chuyên đề** = **một `\chapter`** trong file `.tex`.

```
# TÊN CHUYÊN ĐỀ （中文名）

> **Module:** M1 / M2 / M3 / M4
> **Tỉ trọng đề thi:** XX%

---

## 1. Từ vựng và từ khóa nhận dạng đề
...
## 2. Hệ thống hóa kiến thức trọng tâm
...
## 3. Các dạng bài
...
## 4. Bài tập về nhà
...
```

Chương trình không dạy lý thuyết từ đầu: học sinh đã có kiến thức nền từ bậc phổ thông. Mục 2 vì vậy chỉ **hệ thống hóa** công thức cần nhớ và từ khóa nhận dạng đề, không trình bày lại lý thuyết đầy đủ.

---

## ĐỊNH DẠNG TỪNG LOẠI NỘI DUNG

### 1. TỪ VỰNG (KHÔNG khung — đoạn văn thường)

**Tín hiệu nhận biết:** Block bắt đầu bằng **`**Từ vựng.**`**

```markdown
**Từ vựng.** 交集 (giao), 并集 (hợp), 补集 (phần bù), 解集 (tập nghiệm), 取值范围 (khoảng giá trị).
```

**Quy tắc:**
- **`Từ vựng.`** là từ đầu tiên, in đậm.
- Liệt kê thuật ngữ Hán kèm nghĩa tiếng Việt trong ngoặc, phân tách bằng dấu phẩy.
- Nên gom theo nhóm chủ đề con, mỗi nhóm một block riêng.

---

### 2. TỪ KHÓA NHẬN DẠNG ĐỀ (KHÔNG khung — đoạn văn thường)

**Tín hiệu nhận biết:** Block bắt đầu bằng **`**Từ khóa nhận dạng.**`**

```markdown
**Từ khóa nhận dạng.** Gặp 恒成立 (đúng với mọi giá trị của biến) → bài toán tìm khoảng tham số.
```

**Quy tắc:**
- **`Từ khóa nhận dạng.`** là từ đầu tiên, in đậm.
- Mỗi block nêu một từ khóa và dạng bài tương ứng, cách nhau bằng dấu `→`.

---

### 3. ĐỊNH NGHĨA (`dinhnghia` — CÓ KHUNG, viền xanh)

**Tín hiệu nhận biết:** Block bắt đầu bằng **`**Định nghĩa.**`**, **`**Định nghĩa X.**`** hoặc **`**Định nghĩa X.Y — Tên.**`**

```markdown
**Định nghĩa 1 — Tập hợp.** Tập hợp $A$ được gọi là _tập hợp con_ của $B$ (kí hiệu $A \subseteq B$) khi và chỉ khi mọi phần tử của $A$ đều là phần tử của $B$.
```

**Quy tắc:**
- Từ **"Định nghĩa"** phải là **từ đầu tiên** trong block, in đậm.
- Phần sau từ "Định nghĩa" (trước dấu chấm) là **nhãn tùy chọn**: có thể là số (`3.1`) hoặc số kèm tên (`1 — Tập hợp`).
- Nhiều định nghĩa liên tiếp thì mỗi định nghĩa là **block riêng**, cách nhau một dòng trống.

---

### 4. ĐỊNH LÝ / TÍNH CHẤT (`dinhly` — CÓ KHUNG, viền vàng)

**Tín hiệu nhận biết:** Block bắt đầu bằng **`**Định lý.**`**, **`**Định lý X.Y.**`**, **`**Tính chất.**`** hoặc **`**Tính chất X.**`**

```markdown
**Tính chất 1 — Giao hoán.** $A \cup B = B \cup A$ và $A \cap B = B \cap A$.
```

**Quy tắc:**
- **"Định lý"** hoặc **"Tính chất"** là **từ đầu tiên**, in đậm.
- Nếu có **hệ quả** hoặc **quan sát**, viết thành block mới, bắt đầu bằng **`**Hệ quả.**`** hoặc **`**Quan sát.**`**.

### 4.1. CHỨNG MINH (`proof` — KHÔNG khung, đặt dưới định lý)

**Tín hiệu nhận biết:** Block bắt đầu bằng **`**Chứng minh.**`**, đặt **ngay sau** block Định lý, là một block **riêng biệt**.

```markdown
**Chứng minh.** Gọi $a = 2m$, $b = 2n$ với $m, n \in \mathbb{Z}$. Khi đó $a + b = 2(m+n)$, nên $a + b$ là số chẵn. $\blacksquare$
```

**Quy tắc:**
- **Chứng minh nằm NGOÀI khung Định lý** — block riêng, viết bên dưới, không viết chung vào trong khung.
- Bắt đầu bằng **`**Chứng minh.**`** in đậm, kết thúc bằng `$\blacksquare$` (khi chuyển sang `.tex` thì bỏ dấu này vì môi trường `proof` tự chèn).
- Block Chứng minh **phải nằm ngay sau** block Định lý tương ứng.

---

### 5. VÍ DỤ MINH HỌA (`vidu` — CÓ KHUNG, viền đen)

**Tín hiệu nhận biết:** Block bắt đầu bằng **`**Ví dụ.**`** hoặc **`**Ví dụ X.**`**

```markdown
**Ví dụ 1.** Giải phương trình $x^2 + 2x - 3 = 0$.

**Giải.** Ta có $x^2 + 2x - 3 = 0 \iff (x-1)(x+3) = 0$, suy ra $x = 1$ hoặc $x = -3$.
```

**Quy tắc:**
- **`Ví dụ.`** hoặc **`Ví dụ X.`** là **từ đầu tiên**, in đậm.
- Phần lời giải bắt đầu bằng **`**Giải.**`** hoặc **`**Lời giải.**`** (in đậm) — nằm **trong cùng block** với ví dụ.
- Công thức display dùng `$$...$$`, mỗi công thức trên một dòng riêng.

---

### 6. DẠNG BÀI (KHÔNG khung — dùng \subsection*)

**Tín hiệu nhận biết:** Block bắt đầu bằng **`**Dạng X — Tên dạng.**`**

```markdown
**Dạng 1 — Phép toán trên tập hợp.** Cho các tập hợp dưới dạng mô tả tính chất, tìm giao, hợp hoặc phần bù.

**Cách nhận dạng.** Đề cho từ hai tập hợp trở lên và yêu cầu tìm tập hợp mới.

**Ví dụ.** Cho $A = \{x \mid -1 \le x < 10\}$ và $B = \{x \mid x \ge 2\}$. Tìm $A \cap B$.
```

**Quy tắc:**
- **`Dạng X — Tên dạng.`** là **từ đầu tiên**, in đậm.
- Nêu rõ **cách nhận dạng** dạng bài đó từ đề — đây là nội dung cốt lõi của chương trình.
- Kèm một ví dụ ngắn ngay trong block.

---

### 7. CHÚ Ý / LƯU Ý (KHÔNG khung — đoạn văn thường)

**Tín hiệu nhận biết:** Block bắt đầu bằng **`**Chú ý.**`** hoặc **`**Lưu ý.**`**

```markdown
**Chú ý.** Khi viết tập hợp con, cần phân biệt $A \subseteq B$ (cho phép $A = B$) và $A \subset B$ (không cho phép $A = B$). Đây là lỗi thường gặp.
```

**Quy tắc:**
- **KHÔNG có khung** — đoạn văn bình thường, chỉ có tiền tố in đậm.
- Ngắn gọn, tập trung vào lỗi thường gặp hoặc kỹ thuật xử lý nhanh.

---

### 8. BÀI TẬP (`baitap` — MỖI CÂU MỘT Ô RIÊNG, viền xanh)

**Tín hiệu nhận biết:** Mỗi câu bài tập là **một block riêng**, bắt đầu bằng **`**Bài tập Câu X.**`**

```markdown
**Bài tập Câu 1.** Cho $A = \{1, 2, 3\}$ và $B = \{2, 3, 4\}$. Tìm $A \cup B$.
```

**Quy tắc:**
- **Mỗi câu một block riêng** — không gom nhiều câu vào một danh sách đánh số.
- **`Bài tập Câu X.`** in đậm ở đầu block; X là số thứ tự câu.
- Các block cách nhau một dòng trống. Khi chuyển sang `.tex`, mỗi block thành một ô `\begin{baitap}[Câu X]...\end{baitap}`.
- **Không** đặt đáp án trong cùng block.

---

## PHẦN TEXT THƯỜNG (không đặt trong khung)

**Tín hiệu:** Các đoạn văn bản **không** bắt đầu bằng một trong các tín hiệu trên. Riêng block bắt đầu bằng `**Chú ý.**`/`**Lưu ý.**` cũng thuộc nhóm này.

```markdown
Trong chuyên đề này, ta hệ thống lại các phép toán tập hợp và các dạng bài thường gặp trong đề thi.

Sau khi nắm các phép toán cơ bản, ta chuyển sang dạng bài đếm số tập con.
```

**Quy tắc:**
- Text thường **không cần tín hiệu đặc biệt** — viết bình thường, công thức trong `$...$`.
- Khi chuyển sang `.tex`, text thường đặt **ngoài** các môi trường tcolorbox, nằm trực tiếp trong `\section`.

---

## CẤU TRÚC SECTION

Mỗi chuyên đề có **bốn section chính** theo thứ tự:

| Số thứ tự | Tên section | Nội dung |
|:---------:|:-----------|:--------|
| 1 | **Từ vựng và từ khóa nhận dạng đề** | Thuật ngữ Hán, từ khóa đề bài và dạng bài tương ứng |
| 2 | **Hệ thống hóa kiến thức trọng tâm** | Định nghĩa, định lý/tính chất, công thức cần nhớ, chú ý |
| 3 | **Các dạng bài** | Mỗi dạng bài kèm cách nhận dạng và ví dụ |
| 4 | **Bài tập về nhà** | Chia hai phần bắt buộc và tự chọn |

---

## ĐẶT SỐ / NHÃN

Nhãn đặt ngay sau tên loại, trước dấu chấm:

```
**Định nghĩa 3.1.** ...
**Định nghĩa 1 — Tập hợp.** ...
**Tính chất 1 — Giao hoán.** ...
**Dạng 1 — Phép toán trên tập hợp.** ...
**Ví dụ 1.** ...
**Bài tập Câu 1.** ...
```

Con số nên khớp với số `\chapter` trong `.tex` (Chuyên đề 3 → `3.1`, `3.2`, ...). Kiểu "số — tên" dùng khi đánh số lại từ 1 trong chuyên đề.

---

## CÔNG THỨC TOÁN HỌC

| Loại | Ký hiệu Markdown | Ví dụ |
|:-----|:-----------------|:------|
| Inline (trong dòng) | `$...$` | `$a^2 + b^2 = c^2$` |
| Display (cả dòng) | `$$...$$` | `$$\int_0^1 x^2 \, dx = \frac{1}{3}$$` |
| Align nhiều dòng | `$$\begin{aligned}...\end{aligned}$$` | Xem ví dụ bên dưới |

**Ví dụ align:**
```
$$\begin{aligned}
  (x+1)^2 &= x^2 + 2x + 1 \\
           &= (x^2 + 2x) + 1
\end{aligned}$$
```

**Ký tự đặc biệt cần escaped trong LaTeX:**

| Ký hiệu | Viết trong Markdown |
|:--------|:---------------------|
| $\leq$ | `\leq` |
| $\geq$ | `\geq` |
| $\neq$ | `\neq` |
| $\Rightarrow$ | `\Rightarrow` |
| $\iff$ | `\iff` |
| $\forall$ | `\forall` |
| $\exists$ | `\exists` |
| $\mathbb{Z}$ | `\mathbb{Z}` |
| $\blacksquare$ (hết chứng minh) | `\blacksquare` |

---

## LƯU Ý KHI BIÊN SOẠN

1. **KHÔNG** đặt `$...$` hoặc `$$...$$` bên trong tín hiệu in đậm (`**...**`).
   - ✅ `**Định nghĩa.** Tập hợp $A$ được gọi là ...`
   - ❌ `**Định nghĩa. Tập hợp $A$ được gọi là ...**`

2. **Chứng minh nằm NGOÀI khung Định lý** — block riêng, đặt ngay dưới block `**Định lý...**`.

3. **Mỗi block là một đơn vị riêng biệt**, cách nhau một dòng trống.

4. **Chỉ 3 loại có khung**: Định nghĩa, Định lý/Tính chất, Ví dụ. Các loại khác — Từ vựng, Từ khóa nhận dạng, Dạng bài, Chú ý, Chứng minh, text thường — đều là đoạn văn không khung.

5. **Bài tập: mỗi câu một block** `**Bài tập Câu X.**` — không gom thành danh sách `1. 2. 3.`.

6. **Công thức display** viết riêng dòng, không đặt giữa câu.

7. **Độ dài ví dụ / bài tập:** đủ ngắn để hiển thị trong một khung.

8. **Thuật ngữ Hán** giữ nguyên dạng gốc, không phiên âm, không dịch — để học sinh đối chiếu với đề thi.

---

## MẪU HOÀN CHỈNH

```markdown
# CHUYÊN ĐỀ 1: TẬP HỢP （集合）

> **Module:** M1
> **Tỉ trọng đề thi:** ~10%

---

## 1. Từ vựng và từ khóa nhận dạng đề

**Từ vựng.** 集合 (tập hợp), 元素 (phần tử), 子集 (tập con), 交集 (giao), 并集 (hợp), 补集 (phần bù).

**Từ khóa nhận dạng.** Gặp 取值范围 (khoảng giá trị) → bài toán tìm khoảng tham số.

## 2. Hệ thống hóa kiến thức trọng tâm

**Định nghĩa 1 — Tập hợp.** [Viết định nghĩa].

**Tính chất 1 — Giao hoán.** [Viết tính chất].

**Chứng minh.** [Viết chứng minh — block riêng, ngoài khung]. $\blacksquare$

**Chú ý.** [Lỗi thường gặp — đoạn văn thường, không khung].

## 3. Các dạng bài

**Dạng 1 — Phép toán trên tập hợp.** [Mô tả dạng bài].

**Cách nhận dạng.** [Dấu hiệu nhận biết từ đề].

**Ví dụ.** [Ví dụ ngắn].

## 4. Bài tập về nhà

**Bắt buộc.**

**Bài tập Câu 1.** [Đề bài].

**Bài tập Câu 2.** [Đề bài].

**Tự chọn.**

**Bài tập Câu 1.** [Đề bài].
```

---

## MAPPING SANG LATEX

| Markdown signal | LaTeX | Ghi chú |
|:----------------|:------|:--------|
| `**Từ vựng.**` ... | Đoạn văn có `\textbf{Từ vựng.}` | Không dùng môi trường riêng |
| `**Từ khóa nhận dạng.**` ... | Đoạn văn có `\textbf{Từ khóa nhận dạng.}` | Không dùng môi trường riêng |
| `**Định nghĩa [nhãn].**` ... | `\begin{dinhnghia}[nhãn]...\end{dinhnghia}` | Có khung, viền xanh |
| `**Định lý [nhãn].**` / `**Tính chất [nhãn].**` ... | `\begin{dinhly}[nhãn]...\end{dinhly}` | Có khung, viền vàng |
| `**Chứng minh.**` ... `$\blacksquare$` | `\begin{proof}...\end{proof}` | Ngoài khung, ngay dưới `dinhly`; bỏ `$\blacksquare$` |
| `**Ví dụ [nhãn].**` ... **`Giải.`** ... | `\begin{vidu}[nhãn]...\end{vidu}` | Có khung, viền đen |
| `**Dạng X — Tên dạng.**` ... | `\subsection*{Dạng X — Tên dạng}` kèm đoạn văn | Không dùng môi trường riêng |
| `**Chú ý.**` / `**Lưu ý.**` ... | `\textbf{Chú ý.} ...` | Không khung |
| `**Bài tập Câu X.**` ... | `\begin{baitap}[Câu X]...\end{baitap}` | Mỗi câu một ô riêng |
| Text thường | Viết trực tiếp trong `\section` | Không khung |

**Font dùng trong bản in (XeLaTeX, đã cấu hình trong template):** Libertinus Serif (thân bài), Libertinus Math (công thức), Segoe UI (tiêu đề), Microsoft YaHei (thuật ngữ Hán).
