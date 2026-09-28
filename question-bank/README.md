# Kho đề Toán CSCA

Kho đề được trích xuất từ bộ tài liệu "BỘ 8 ĐỀ TỰ LUYỆN THI CSCA TOÁN HỌC" của tác giả Đỗ Đức Thịnh.

## Cấu trúc

- 9 chuyên đề (theo `docs/syllabus.md`)
- Mỗi câu hỏi được gán nhãn: chuyên đề, module, độ khó, nguồn
- Nội dung câu hỏi bằng tiếng Trung, công thức LaTeX

## Mã câu hỏi

Format: `CAE-M-CD{n}-{source}-{L}-{NNN}`

| Thành phần | Ý nghĩa | Ví dụ |
|---|---|---|
| `CAE-M` | Môn Toán CSCA | cố định |
| `CD{n}` | Chuyên đề 1–9 | `CD1` |
| `{source}` | Nguồn: `08.{d}` (bộ 8 đề, đề số d 1–8), `LX1`/`LX2`/`LX3` (luyện tập 1/2/3) | `08.3`, `LX2` |
| `{L}` | Độ khó: `E`=Dễ, `M`=Trung bình, `H`=Khó | `E` |
| `{NNN}` | STT trong file chuyên đề, 3 chữ số, tăng dần | `007` |

Ví dụ: `CAE-M-CD1-08.1-E-001` — câu đầu tiên chuyên đề 1, từ đề 1, độ khó Dễ.

## Thống kê (8 đề + LX1 + LX2 + LX3, đã loại 14 câu cần ảnh, tổng 514 câu)

| Chuyên đề | 08.x | LX1 | LX2 | LX3 | Tổng |
|-----------|------|-----|-----|-----|------|
| CĐ1: Tập hợp | 32 | 3 | 5 | 5 | 45 |
| CĐ2: Bất đẳng thức | 54 | 3 | 4 | 2 | 63 |
| CĐ3: Dãy số | 15 | 5 | 4 | 4 | 28 |
| CĐ4: Hàm số | 107 | 11 | 9 | 10 | 137 |
| CĐ5: Hình học (1) | 45 | 5 | 5 | 7 | 62 |
| CĐ6: Hình học (2) | 23 | 5 | 4 | 2 | 34 |
| CĐ7: Đại số | 33 | 3 | 3 | 3 | 42 |
| CĐ8: Xác suất | 49 | 5 | 4 | 3 | 61 |
| CĐ9: Thống kê | 25 | 5 | 6 | 6 | 42 |
| **Tổng** | **383** | **45** | **44** | **42** | **514** |

Đã xóa 14 câu bắt buộc có ảnh (đồ thị, Venn, hình 3D, biểu đồ); 2 câu chỉ tham chiếu minh họa đã bỏ chữ "如图" và giữ lại.

## Độ khó phân bố

| Độ khó | Số câu | Tỉ lệ |
|--------|--------|--------|
| Dễ | 206 | 40.1% |
| Trung bình | 147 | 28.6% |
| Khó | 161 | 31.3% |

## Schema câu hỏi

```markdown
### CAE-M-CD{n}-08.{d}-{L}-{NNN}

<đề bài (LaTeX)>

A. <đáp án A>


B. <đáp án B>


C. <đáp án C>


D. <đáp án D>

**Đáp án:** <A|B|C|D>

---
```

- Header `###` chỉ chứa mã câu hỏi (không kèm tên chuyên đề/độ khó).
- Mỗi đáp án A/B/C/D nằm trên dòng riêng, cách nhau một dòng trống.
- Công thức LaTeX nằm trong `$...$`; giữa ký tự CJK và `$` luôn có khoảng trắng.

## Dữ liệu trung gian

Thư mục `_raw/` lưu dữ liệu trích xuất từ PDF nguồn (`de*-cauhoi.txt`, `de*-dapan.txt`) và các file luyện tập (`lianxi*.md`). Đây là dữ liệu trung gian phục vụ tái tạo kho đề, không phải nội dung giảng dạy.

## Ghi chú

- Đề gốc: BỘ 8 ĐỀ TỰ LUYỆN THI CSCA TOÁN HỌC (Đỗ Đức Thịnh), 8 đề mô phỏng (mỗi đề 48 câu, tổng 384 câu).
- Các câu 31,32 (dãy số) được chuyển từ mục "几何与代数" sang chuyên đề 3 (Dãy số) theo đúng nội dung.
- Công thức toán đã được chuẩn hóa LaTeX: `$\{x \mid ...\}$`, `$\complement_{U}$`, `$\frac{a}{b}$`, `$\sqrt{x}$`, `$\sin$`, `$\cos$`, `$\tan$`, `$\log$`, `$\ln$`, `$\mathbb{R}$`, `$\infty$`, v.v.
- Bảng phân phối tần số được trình bày dưới dạng Markdown table.
