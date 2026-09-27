# TEMPLATE VIẾT NỘI DUNG CHUYÊN ĐỀ TOÁN — CAE VIỆT NAM

> **Mục đích:** Đây là hướng dẫn cấu trúc để biên soạn nội dung chuyên đề toán dưới dạng Markdown. Khi chuyển sang `.tex`, mỗi loại nội dung sẽ tương ứng đúng với môi trường LaTeX, giúp quá trình chuyển đổi ít lỗi nhất.
>
> **Nguyên tắc chung:**
> - Mọi công thức toán học đặt trong dấu `$...$` (inline) hoặc `$$...$$` (display).
> - Mỗi phần nội dung **bắt đầu bằng tín hiệu in đậm đúng loại** (được ghi rõ bên dưới).
> - Chỉ **3 loại nội dung quan trọng** có khung: **Định nghĩa**, **Định lý/Tính chất**, **Ví dụ**. Mọi thứ khác (chứng minh, chú ý, text thường) viết thành đoạn văn bình thường, **không khung**.
> - Không tự ý đặt tiêu đề `##` bên trong một block nội dung.

---

## CẤU TRÚC CHUNG (Tương ứng với `\chapter`)

Mỗi file `.md` = **một chuyên đề** = **một `\chapter`** trong file `.tex`.

```
# TÊN CHUYÊN ĐỀ （中文名）

> **Module:** Tên module đề thi  
> **Tỉ trọng:** XX%

---

## 1. Kiến thức trọng tâm
...
## 2. Ví dụ minh họa
...
## 3. Bài tập tự luyện
...
## 4. Phân bố độ khó trong đề thi *(tùy chọn)*
...
```

---

## ĐỊNH DẠNG TỪNG LOẠI NỘI DUNG

### 1. ĐỊNH NGHĨA (`dinhnghia` — CÓ KHUNG, viền xanh)

**Tín hiệu nhận biết:** Block bắt đầu bằng **`**Định nghĩa.**`**, **`**Định nghĩa X.**`** hoặc **`**Định nghĩa X.Y — Tên.**`**

```markdown
**Định nghĩa 1 — Tập hợp.** Tập hợp $A$ được gọi là _tập hợp con_ của $B$ (kí hiệu $A \subseteq B$) khi và chỉ khi mọi phần tử của $A$ đều là phần tử của $B$.

**Định nghĩa 3.1.** Hàm số $f: A \to B$ là quy tắc gán mỗi phần tử $a \in A$ đúng một phần tử $f(a) \in B$.
```

**Quy tắc:**
- Từ **"Định nghĩa"** phải là **từ đầu tiên** trong block, in đậm (`**...**`).
- Phần sau từ "Định nghĩa" (trước dấu chấm) là **nhãn tùy chọn**: có thể là số (`3.1`) hoặc số kèm tên (`1 — Tập hợp`).
- Nếu có nhiều định nghĩa liên tiếp, mỗi định nghĩa viết thành **block riêng**, cách nhau một dòng trống.

---

### 2. ĐỊNH LÝ / TÍNH CHẤT (`dinhly` — CÓ KHUNG, viền vàng)

**Tín hiệu nhận biết:** Block bắt đầu bằng **`**Định lý.**`**, **`**Định lý X.Y.**`**, **`**Tính chất.**`** hoặc **`**Tính chất X.**`**

```markdown
**Định lý 2.1.** Tổng hai số chẵn vẫn là số chẵn.

**Tính chất 1 — Giao hoán.** $A \cup B = B \cup A$ và $A \cap B = B \cap A$.
```

**Quy tắc:**
- **"Định lý"** hoặc **"Tính chất"** là **từ đầu tiên**, in đậm.
- Nếu có **hệ quả** hoặc **quan sát**, viết thành block mới, bắt đầu bằng **`**Hệ quả.**`** hoặc **`**Quan sát.**`**.

### 2.1. CHỨNG MINH (`proof` — KHÔNG khung, viết BÊN DƯỚI định lý)

**Tín hiệu nhận biết:** Block bắt đầu bằng **`**Chứng minh.**`**, đặt **ngay sau block Định lý**, là một block **riêng biệt** (cách nhau một dòng trống).

```markdown
**Định lý 2.1.** Tổng hai số chẵn vẫn là số chẵn.

**Chứng minh.** Gọi $a = 2m$, $b = 2n$ với $m, n \in \mathbb{Z}$. Khi đó $a + b = 2(m+n)$, nên $a + b$ là số chẵn. $\blacksquare$
```

**Quy tắc:**
- **Chứng minh phải nằm NGOÀI khung Định lý** — là block riêng, viết bên dưới block Định lý, **không** viết chung vào trong block Định lý.
- Bắt đầu bằng **`**Chứng minh.**`** in đậm, kết thúc bằng `$\blacksquare$` (dấu hiệu hình thức trong `.md`; khi chuyển sang `.tex` **bỏ dấu này** vì môi trường `proof` tự chèn).
- Block Chứng minh **phải nằm ngay sau** block Định lý tương ứng — không chèn block khác vào giữa.

---

### 3. VÍ DỤ MINH HỌA (`vidu` — CÓ KHUNG, viền đen)

**Tín hiệu nhận biết:** Block bắt đầu bằng **`**Ví dụ.**`** hoặc **`**Ví dụ X.**`**

```markdown
**Ví dụ 1.** Giải phương trình $x^2 + 2x - 3 = 0$.

**Giải.** Ta có:
$$x^2 + 2x - 3 = 0 \iff (x-1)(x+3) = 0$$
$$\Rightarrow x = 1 \quad \text{hoặc} \quad x = -3.$$
```

**Quy tắc:**
- **`Ví dụ.`** hoặc **`Ví dụ X.`** là **từ đầu tiên**, in đậm.
- Phần lời giải bắt đầu bằng **`**Giải.**`** hoặc **`**Lời giải.**`** (in đậm) — phần này nằm **trong cùng block** với ví dụ (khác với Chứng minh, nằm ngoài Định lý).
- Công thức display dùng `$$...$$`, mỗi công thức trên một dòng riêng.
- Các bước giải có thể viết xen kẽ văn bản và công thức.

---

### 4. CHÚ Ý / LƯU Ý (KHÔNG khung — đoạn văn thường)

**Tín hiệu nhận biết:** Block bắt đầu bằng **`**Chú ý.**`** hoặc **`**Lưu ý.**`**

```markdown
**Chú ý.** Khi viết tập hợp con, cần phân biệt $A \subseteq B$ (cho phép $A = B$) và $A \subset B$ (không cho phép $A = B$). Đây là lỗi thường gặp.
```

**Quy tắc:**
- **KHÔNG có khung** — đây là đoạn văn bình thường, chỉ có tiền tố in đậm.
- Đoạn ngắn gọn, tập trung vào lỗi thường gặp hoặc mẹo giải nhanh.

---

### 5. BÀI TẬP TỰ LUYỆN (`baitap` — MỖI CÂU MỘT Ô RIÊNG, viền xanh)

**Tín hiệu nhận biết:** Mỗi câu bài tập là **một block riêng**, bắt đầu bằng **`**Bài tập Câu X.**`**

```markdown
**Bài tập Câu 1.** Chứng minh rằng $\sqrt{2}$ là số vô lý.

**Bài tập Câu 2.** Cho tam giác $ABC$ có $AB = 5$, $BC = 7$, $CA = 8$. Tính diện tích tam giác.

**Bài tập Câu 3.** Tìm tất cả các số nguyên $n$ sao cho $n^2 + n + 1$ là số nguyên tố.
```

**Quy tắc:**
- **Mỗi câu một block riêng** — KHÔNG gom nhiều câu vào một danh sách đánh số như trước.
- **`Bài tập Câu X.`** in đậm ở đầu block; X là số thứ tự câu.
- Các block cách nhau một dòng trống. Khi chuyển sang `.tex`, mỗi block thành một ô `\begin{baitap}[Câu X]...\end{baitap}` riêng.
- **Không** đặt nội dung giải/đáp án trong cùng block — đáp án nếu có thì ở phần riêng.

---

## PHẦN TEXT THƯỜNG (không đặt trong khung)

**Tín hiệu:** Đây là các đoạn văn bản **không** bắt đầu bằng một trong các tín hiệu trên (`Định nghĩa.`, `Định lý.`, `Ví dụ.`, `Bài tập Câu X.`). Riêng block bắt đầu bằng `**Chú ý.**`/`**Lưu ý.**` cũng thuộc nhóm text thường (chỉ thêm tiền tố đậm, vẫn không có khung).

```markdown
Trong phần này, chúng ta sẽ tìm hiểu về lý thuyết tập hợp — nền tảng của toàn bộ toán học hiện đại. Tập hợp là một trong những khái niệm cơ bản nhất.

Sau khi đã nắm định nghĩa, ta chuyển sang các tính chất cơ bản của phép toán tập hợp.

## 2. Ví dụ minh họa

**Ví dụ 1.** Cho $A = \{1, 2, 3\}$, $B = \{2, 3, 4\}$, tìm $A \cup B$ và $A \cap B$.

**Giải.** Ta có $A \cup B = \{1, 2, 3, 4\}$ và $A \cap B = \{2, 3\}$.
```

**Quy tắc:**
- Text thường **không cần tín hiệu đặc biệt** — chỉ viết bình thường, công thức trong `$...$`.
- Khi chuyển sang `.tex`, text thường được đặt **ngoài** các môi trường tcolorbox, nằm trực tiếp trong phần nội dung của `\section`.

---

## CẤU TRÚC SECTION (Tương ứng với `\section`)

Mỗi chuyên đề nên có **ba section chính** theo thứ tự:

| Số thứ tự | Tên section | Nội dung |
|:---------:|:-----------|:--------|
| 1 | **Kiến thức trọng tâm** | Định nghĩa, định lý/tính chất (+ chứng minh ngoài khung), chú ý |
| 2 | **Ví dụ minh họa** | Các ví dụ có lời giải chi tiết |
| 3 | **Bài tập tự luyện** | Các câu bài tập, mỗi câu một ô |

Section tùy chọn: **Phân bố độ khó trong đề thi** (đặt cuối, dạng bảng).

---

## ĐẶT SỐ / NHÃN CHO ĐỊNH NGHĨA / ĐỊNH LÝ / VÍ DỤ

Nhãn đặt ngay sau tên loại, trước dấu chấm, có thể theo một trong hai kiểu:

```
**Định nghĩa 3.1.** ...                (kiểu số)
**Định nghĩa 1 — Tập hợp.** ...       (kiểu số — tên)
**Định lý 1 — Giao hoán.** ...
**Ví dụ 1.** ...
**Bài tập Câu 1.** ...
```

- Con số nên khớp với số `\chapter` trong `.tex` (Chuyên đề 3 → `3.1`, `3.2`, ...). Kiểu "số — tên" thường dùng khi đánh số lại từ 1 trong chuyên đề.

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

## LƯU Ý QUAN TRỌNG KHI BIÊN SOẠN

1. **KHÔNG** đặt `$...$` hoặc `$$...$$` bên trong tín hiệu in đậm (`**...**`).
   - ✅ `**Định nghĩa.** Tập hợp $A$ được gọi là ...`
   - ❌ `**Định nghĩa. Tập hợp $A$ được gọi là ...**`

2. **Chứng minh nằm NGOÀI khung Định lý**: block `**Chứng minh.**` là block riêng, đặt **ngay dưới** block `**Định lý...**`, không viết chung vào trong block Định lý.

3. **Mỗi block là một đơn vị riêng biệt**, cách nhau một dòng trống — không nhập nhằng hai block liền nhau.

4. **Chỉ 3 loại có khung**: Định nghĩa, Định lý/Tính chất, Ví dụ. Chú ý, chứng minh, text thường đều là đoạn văn không khung.

5. **Bài tập: mỗi câu một block** `**Bài tập Câu X.**` — không gom thành danh sách `1. 2. 3.` trong một block.

6. **Công thức display** nên viết riêng dòng, không đặt giữa câu.

7. **Độ dài ví dụ / bài tập:** Mỗi ví dụ nên đủ ngắn để hiển thị trong một khung, không quá dài dòng.

---

## MẪU HOÀN CHỈNH (Copy-paste rồi sửa nội dung)

```markdown
# TÊN CHUYÊN ĐỀ （中文名）

> **Module:** Tên module đề thi  
> **Tỉ trọng:** XX%

---

## 1. Kiến thức trọng tâm

**Định nghĩa 1 — Tập hợp.** [Viết định nghĩa ở đây].

**Định nghĩa 2 — Tập con.** [Viết định nghĩa khác ở đây].

**Định lý 1 — Giao hoán.** [Viết định lý ở đây].

**Chứng minh.** [Viết chứng minh ở đây — block riêng, dưới định lý, ngoài khung]. $\blacksquare$

**Tính chất 2 — Kết hợp.** [Viết tính chất ở đây].

**Chú ý.** [Viết chú ý / lỗi thường gặp ở đây — đoạn văn thường, không khung].

[Text thường: đoạn văn giải thích thêm, nối tiếp giữa các block, không cần đánh dấu gì đặc biệt].

## 2. Ví dụ minh họa

**Ví dụ 1.** [Đề bài ví dụ].

**Giải.** [Lời giải chi tiết, có công thức display].

$$
\text{công thức display ở đây}
$$

## 3. Bài tập tự luyện

**Bài tập Câu 1.** [Đề bài câu 1].

**Bài tập Câu 2.** [Đề bài câu 2].

**Bài tập Câu 3.** [Đề bài câu 3].

## 4. Phân bố độ khó trong đề thi

| Mức độ | Dễ | Trung bình | Khó |
|:-------|:--:|:----------:|:---:|
| Số câu | XX | XX | XX |
```

---

## MAPPING TỪ MARKDOWN SANG LATEX (cho người chuyển đổi)

| Markdown signal | LaTeX | Ghi chú |
|:----------------|:------|:--------|
| `**Định nghĩa [nhãn].**` ... | `\begin{dinhnghia}[nhãn]...\end{dinhnghia}` | **Có khung** viền xanh |
| `**Định lý [nhãn].**` / `**Tính chất [nhãn].**` ... | `\begin{dinhly}[nhãn]...\end{dinhly}` | **Có khung** viền vàng |
| `**Chứng minh.** ... $\blacksquare$` | `\begin{proof}...\end{proof}` | **Ngoài khung**, ngay dưới `dinhly`; bỏ `$\blacksquare$` khi chuyển (proof tự chèn dấu ■) |
| `**Ví dụ [nhãn].**` ... **`Giải.`** ... | `\begin{vidu}[nhãn]...\end{vidu}` | **Có khung** viền đen; phần Giải nằm trong cùng khung |
| `**Chú ý.**` / `**Lưu ý.**` ... | `\textbf{Chú ý.} ...` | **Không khung** — đoạn văn thường |
| `**Bài tập Câu X.**` ... | `\begin{baitap}[Câu X]...\end{baitap}` | **Mỗi câu một ô riêng**, viền xanh |
| Text thường (không có tín hiệu) | Viết trực tiếp trong `\section` | **Không khung** — điểm mấu chốt |

**Font dùng trong bản in (XeLaTeX, đã cấu hình sẵn trong template):** Libertinus Serif (thân bài), Libertinus Math (công thức), Segoe UI (tiêu đề), Microsoft YaHei (thuật ngữ Hán).
