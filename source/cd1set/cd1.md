# CHUYÊN ĐỀ 1: TẬP HỢP

## TỔNG QUÁT

Tập hợp là khái niệm nền tảng của Toán học hiện đại, xuất hiện trong hầu hết các lĩnh vực từ số học, đại số đến giải tích và xác suất. Trong khuôn khổ kỳ thi CSCA, Tập hợp thuộc **Module 1 — Tập hợp & Bất đẳng thức**, chiếm khoảng **4 câu hỏi (~8\% tổng đề thi)**.

**Kiến thức trọng tâm** gồm ba trụ cột chính:

1. **Khái niệm cơ bản:** tập hợp, phần tử, tập con, tập rỗng, hai tập hợp bằng nhau. Phân biệt được ký hiệu $\in$ (thuộc) và $\subset$ (tập con). Nắm vững cách biểu diễn tập hợp: liệt kê phần tử và mô tả tính chất đặc trưng.

2. **Các phép toán trên tập hợp:** phép hợp $\cup$, phép giao $\cap$, phép hiệu $\setminus$, phép lấy phần bù $C_U A$. Thành thạo các tính chất: giao hoán, kết hợp, phân phối, luật De Morgan. Kỹ năng sử dụng biểu đồ Venn để minh họa và giải quyết bài toán tập hợp là yêu cầu bắt buộc.

3. **Tập hợp số:** nhận biết và phân biệt các tập số $\mathbb{N}, \mathbb{Z}, \mathbb{Q}, \mathbb{R}$. Biểu diễn tập hợp trên trục số thực, đặc biệt là các tập dạng khoảng, đoạn, nửa khoảng — kỹ năng này là cầu nối trực tiếp sang chuyên đề **Bất đẳng thức**.

**Trong đề thi CSCA**, các câu hỏi về Tập hợp thường ở mức độ **Dễ đến Trung bình**, tập trung vào phép toán tập hợp cơ bản và bài toán đếm phần tử bằng biểu đồ Venn. Học sinh cần làm nhanh và chính xác, dành thời gian cho các module khó hơn.

## TỪ VỰNG QUAN TRỌNG

| # | Thuật ngữ Tiếng Việt | Thuật ngữ Tiếng Trung | Pinyin (gợi ý) |
|---|---|---|---|
| 1 | Tập hợp | 集合 | jíhé |
| 2 | Phần tử | 元素 | yuánsù |
| 3 | Thuộc (về) | 属于 | shǔyú |
| 4 | Tập con | 子集 | zǐjí |
| 5 | Tập con thực sự | 真子集 | zhēnzǐjí |
| 6 | Tập rỗng | 空集 | kōngjí |
| 7 | Hợp (của hai tập hợp) | 并集 | bìngjí |
| 8 | Giao (của hai tập hợp) | 交集 | jiāojí |
| 9 | Hiệu (của hai tập hợp) | 差集 | chājí |
| 10 | Phần bù | 补集 | bǔjí |
| 11 | Tập vũ trụ / Tập toàn thể | 全集 | quánjí |
| 12 | Biểu đồ Venn | 文氏图 | wénshìtú |
| 13 | Lực lượng (số phần tử) | 基数 | jīshù |
| 14 | Tập hữu hạn | 有限集 | yǒuxiànjí |
| 15 | Tập vô hạn | 无限集 | wúxiànjí |
| 16 | Tích Descartes | 笛卡尔积 | díkǎ'ěr jī |
| 17 | Số tự nhiên | 自然数 | zìránshù |
| 18 | Số nguyên | 整数 | zhěngshù |
| 19 | Số hữu tỉ | 有理数 | yǒulǐshù |
| 20 | Số thực | 实数 | shíshù |

## KIẾN THỨC VÀ BÀI TẬP VÍ DỤ

### 1. Định nghĩa

**Định nghĩa 1 (Tập hợp — Set).** Tập hợp là một khái niệm cơ bản, không định nghĩa chính thức, dùng để chỉ một nhóm các đối tượng xác định. Mỗi đối tượng trong tập hợp được gọi là một *phần tử* (element).

Ký hiệu: $a \in A$ nghĩa là "$a$ thuộc tập $A$"; $a \notin A$ nghĩa là "$a$ không thuộc tập $A$".

Hai cách biểu diễn tập hợp:
- **Liệt kê:** $A = \{1, 2, 3, 4, 5\}$
- **Mô tả tính chất:** $A = \{x \in \mathbb{N} \mid x \leq 5\}$

**Định nghĩa 2 (Tập con — Subset).** Tập $A$ được gọi là *tập con* của tập $B$, ký hiệu $A \subset B$, nếu mọi phần tử của $A$ đều là phần tử của $B$:

$$A \subset B \iff (\forall x \in A \Rightarrow x \in B)$$

Nếu $A \subset B$ và $A \neq B$, ta nói $A$ là *tập con thực sự* (proper subset) của $B$, ký hiệu $A \subsetneq B$.

**Định nghĩa 3 (Tập rỗng — Empty Set).** Tập rỗng, ký hiệu $\varnothing$, là tập hợp không chứa phần tử nào. Tập rỗng là tập con của mọi tập hợp.

### 2. Các phép toán trên tập hợp

Cho hai tập hợp $A$ và $B$ trong tập vũ trụ $U$:

| Phép toán | Ký hiệu | Định nghĩa |
|---|---|---|
| Hợp (Union) | $A \cup B$ | $A \cup B = \{x \mid x \in A \text{ hoặc } x \in B\}$ |
| Giao (Intersection) | $A \cap B$ | $A \cap B = \{x \mid x \in A \text{ và } x \in B\}$ |
| Hiệu (Difference) | $A \setminus B$ | $A \setminus B = \{x \mid x \in A \text{ và } x \notin B\}$ |
| Phần bù (Complement) | $C_U A$ | $C_U A = U \setminus A = \{x \in U \mid x \notin A\}$ |

### 3. Tính chất của các phép toán

**Tính chất 1 (Giao hoán).** $A \cup B = B \cup A;\quad A \cap B = B \cap A$

**Tính chất 2 (Kết hợp).** $(A \cup B) \cup C = A \cup (B \cup C);\quad (A \cap B) \cap C = A \cap (B \cap C)$

**Tính chất 3 (Phân phối).** $A \cap (B \cup C) = (A \cap B) \cup (A \cap C);\quad A \cup (B \cap C) = (A \cup B) \cap (A \cup C)$

**Tính chất 4 (Luật De Morgan).** $C_U(A \cup B) = C_U A \cap C_U B;\quad C_U(A \cap B) = C_U A \cup C_U B$

**Tính chất 5 (Công thức đếm phần tử).** Với tập hữu hạn $A, B$, ký hiệu $n(A)$ là số phần tử của $A$:

$$n(A \cup B) = n(A) + n(B) - n(A \cap B)$$

$$n(A \cup B \cup C) = n(A) + n(B) + n(C) - n(A \cap B) - n(B \cap C) - n(C \cap A) + n(A \cap B \cap C)$$

### 4. Ví dụ minh họa

**Ví dụ 1.** Cho tập vũ trụ $U = \{1, 2, 3, 4, 5, 6, 7, 8, 9, 10\}$ và hai tập con:
$A = \{1, 2, 3, 4, 5\}$, $B = \{4, 5, 6, 7\}$.

Hãy xác định:
a) $A \cup B$, $A \cap B$, $A \setminus B$, $B \setminus A$
b) $C_U A$, $C_U B$
c) Kiểm tra luật De Morgan: $C_U(A \cup B) = C_U A \cap C_U B$

**Lời giải.**

a) 
- $A \cup B = \{1, 2, 3, 4, 5, 6, 7\}$
- $A \cap B = \{4, 5\}$
- $A \setminus B = \{1, 2, 3\}$
- $B \setminus A = \{6, 7\}$

b) 
- $C_U A = U \setminus A = \{6, 7, 8, 9, 10\}$
- $C_U B = U \setminus B = \{1, 2, 3, 8, 9, 10\}$

c) 
- $C_U(A \cup B) = U \setminus \{1, 2, 3, 4, 5, 6, 7\} = \{8, 9, 10\}$
- $C_U A \cap C_U B = \{6, 7, 8, 9, 10\} \cap \{1, 2, 3, 8, 9, 10\} = \{8, 9, 10\}$
- Vậy $C_U(A \cup B) = C_U A \cap C_U B$ (đúng).

---

**Ví dụ 2.** Trong một lớp học có 40 học sinh, có 25 học sinh giỏi Toán, 20 học sinh giỏi Văn, và 12 học sinh giỏi cả hai môn. Hỏi:
a) Có bao nhiêu học sinh giỏi ít nhất một môn?
b) Có bao nhiêu học sinh không giỏi môn nào?

**Lời giải.**

Gọi $T$ là tập hợp học sinh giỏi Toán, $V$ là tập hợp học sinh giỏi Văn.

Ta có: $n(T) = 25$, $n(V) = 20$, $n(T \cap V) = 12$, $n(U) = 40$.

a) Số học sinh giỏi ít nhất một môn:
$$n(T \cup V) = n(T) + n(V) - n(T \cap V) = 25 + 20 - 12 = 33$$

b) Số học sinh không giỏi môn nào:
$$n(U) - n(T \cup V) = 40 - 33 = 7$$

## BÀI TẬP TỰ LUYỆN

**Câu 1.** Cho hai tập hợp $A = \{x \in \mathbb{N} \mid 2 \leq x < 7\}$ và $B = \{x \in \mathbb{N} \mid x \text{ là ước của } 12\}$. Tập hợp $A \cap B$ là:

A. $\{2, 3, 4, 6\}$
B. $\{1, 2, 3, 4, 6\}$
C. $\{2, 3, 6\}$
D. $\{3, 4, 6\}$

**Câu 2.** Cho tập $A = \{x \in \mathbb{R} \mid -3 \leq x < 5\}$ và $B = \{x \in \mathbb{R} \mid x > 1\}$. Tập hợp $A \setminus B$ là:

A. $[-3; 1]$
B. $[-3; 1)$
C. $(-3; 1]$
D. $(1; 5)$

**Câu 3.** Một lớp có 50 học sinh, trong đó 30 học sinh thích bóng đá, 25 học sinh thích cầu lông, và 10 học sinh không thích cả hai môn. Số học sinh thích cả hai môn là:

A. 5
B. 10
C. 15
D. 20

**Câu 4.** Cho ba tập hợp $A = \{1, 2, 3, 4\}$, $B = \{3, 4, 5, 6\}$, $C = \{1, 3, 5, 7\}$. Tập hợp $(A \cap B) \cup C$ là:

A. $\{1, 3, 5, 7\}$
B. $\{1, 3, 4, 5, 7\}$
C. $\{1, 3, 5\}$
D. $\{3, 4, 5, 7\}$

**Câu 5.** Cho $A = \{x \in \mathbb{Z} \mid |x| \leq 2\}$ và $B = \{x \in \mathbb{N} \mid x^2 - 3x + 2 = 0\}$. Khẳng định nào sau đây đúng?

A. $A \subset B$
B. $B \subset A$
C. $A = B$
D. $A \cap B = \varnothing$