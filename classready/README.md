# TÀI LIỆU GIẢNG DẠY — CHƯƠNG TRÌNH LUYỆN THI CSCA TOÁN

Thư mục chứa tài liệu hoàn chỉnh của từng buổi học, sẵn sàng đưa vào giảng dạy. Nội dung biên soạn theo `docs/syllabus.md` và tham chiếu `references/[0.2]CSCA数学备考指南.pdf`.

---

## Nguyên tắc tổ chức: tách theo người đọc

Mỗi buổi có **hai thư mục con**, phân biệt rõ tài liệu nào phát cho học sinh và tài liệu nào giáo viên giữ riêng. Khi giao bài, chỉ cần đưa cả thư mục `hoc-sinh/` — không sợ lộ file giáo viên.

```
buoi-XX-ten-buoi/
├── hoc-sinh/          ← phát cho học sinh
└── giao-vien/         ← chỉ giáo viên
```

### Quy tắc phân loại

| Nội dung | Thuộc về | Lý do |
|:---------|:---------|:------|
| Bảng từ vựng, đề dịch, bài tập chuẩn bị | `hoc-sinh/` | Học sinh làm trước buổi |
| Từ khóa nhận dạng, công thức, dạng bài, ví dụ | `hoc-sinh/` | Học sinh tra cứu khi làm bài |
| Đề bài tập về nhà | `hoc-sinh/` | Học sinh làm |
| Đáp án bài tập chuẩn bị | `hoc-sinh/` | Học sinh tự chấm trước buổi |
| Bảng đáp án bài tập về nhà | `hoc-sinh/` | Học sinh tự chấm sau khi làm xong |
| Lời giải chi tiết bài tập về nhà | `giao-vien/` | Giáo viên chữa trên lớp |
| Bảng lỗi thường gặp | `giao-vien/` | Công cụ chẩn đoán của giáo viên |
| Phân bổ thời gian, kịch bản giảng dạy | `giao-vien/` | Học sinh không cần biết |
| Mục tiêu sư phạm từng khối | `giao-vien/` | — |
| Danh sách câu luyện tại chỗ, thứ tự ưu tiên dạng bài | `giao-vien/` | — |
| Độ khó, phân bổ số câu, mã câu hỏi | `giao-vien/` | Thông tin vận hành |

### Vì sao tách đáp án làm hai file

Đáp án phần chuẩn bị và đáp án bài tập về nhà được mở ở **hai thời điểm khác nhau**: chuẩn bị làm trước buổi học, bài tập về nhà làm sau buổi và nộp trước buổi kế tiếp. Nếu gộp chung, học sinh mở file tra từ vựng sẽ nhìn thấy luôn lời giải 40 câu chưa làm.

Đáp án bài tập về nhà tách tiếp làm hai mức: học sinh nhận **bảng đáp án** để tự chấm, giáo viên giữ **lời giải chi tiết** để chữa bài.

---

## Cấu trúc theo loại buổi

### Buổi nội dung (1, 2, 3, 4, 6, 8, 9, 10, 12, 14, 15)

```
buoi-XX-ten-buoi/
├── hoc-sinh/
│   ├── 01-chuan-bi-bai.md          Học sinh làm TRƯỚC buổi học
│   ├── 02-tai-lieu-buoi-hoc.md     Từ khóa, công thức, dạng bài, ví dụ
│   ├── 03-bai-tap-ve-nha.md        BTVN sau buổi học
│   ├── 04-dap-an-chuan-bi.md       Đáp án prep — mở trước buổi
│   └── 05-dap-an-bai-tap-ve-nha.md Bảng đáp án BTVN — mở sau khi làm xong
└── giao-vien/
    ├── 01-ke-hoach-giang-day.md    Phân bổ giờ, kịch bản, lưu ý sư phạm
    └── 02-loi-giai-bai-tap-ve-nha.md  Lời giải chi tiết + bảng lỗi
```

### Buổi nội dung có kiểm tra cuối chuyên đề (5, 6, 12, 15)

```
buoi-XX-ten-buoi/
├── hoc-sinh/
│   ├── 01-chuan-bi-bai.md
│   ├── 02-tai-lieu-buoi-hoc.md
│   ├── 03-bai-tap-ve-nha.md
│   ├── 04-dap-an-chuan-bi.md
│   ├── 05-dap-an-bai-tap-ve-nha.md
│   └── 06-de-kiem-tra.md         Đề kiểm tra
└── giao-vien/
    ├── 01-ke-hoach-giang-day.md
    ├── 02-loi-giai-bai-tap-ve-nha.md
    └── 03-dap-an-kiem-tra.md     Đáp án + ma trận + hướng dẫn chấm
```

### Buổi chữa đề (7, 11, 13, 16, 18, 19)

```
buoi-XX-chua-de-N/
├── hoc-sinh/
│   ├── 01-de-bai.md              Đề học sinh làm trước buổi
│   └── 02-dap-an.md              Đáp án
└── giao-vien/
    └── 01-ke-hoach-chua-de.md    Kịch bản chữa theo phương thức phân tầng
```

### Buổi kỹ năng thi (17) và ôn tập (20)

```
buoi-XX-ten-buoi/
├── hoc-sinh/
│   ├── 01-chuan-bi-bai.md
│   ├── 02-tai-lieu-buoi-hoc.md
│   └── 03-bai-tap-ve-nha.md
└── giao-vien/
    └── 01-ke-hoach-giang-day.md
```

---

## Quy ước biên soạn

### Dựng khung một buổi mới

Không chép tay thư mục. Chạy script ở thư mục `classready/`:

```bash
python3 tao-buoi.py 5 luong-giac-ham-so-phuong-trinh
```

Script tạo `buoi-05-luong-giac-ham-so-phuong-trinh/` với đủ `hoc-sinh/`, `giao-vien/`, `latex/`, `pdf/giao-vien/`, và chép sẵn hạ tầng dùng chung (`cae-style.tex`, `build.sh`, `images/letterhead.png`, `scripts/`). Script không ghi đè thư mục đã tồn tại.

### Đồng bộ hạ tầng dùng chung

`cae-style.tex`, `build.sh` và các script phải **giống hệt nhau** ở mọi buổi. Khi sửa một file trong số đó, chạy:

```bash
cd classready
python3 dong-bo-hatang.py
```

Script chép hạ tầng từ buổi 1 sang 19 buổi còn lại, bỏ qua file đã giống. Dùng script thay vì chép tay: đã từng xảy ra việc chép tay xóa nhầm `cae-style.tex` ở vài buổi.

### Định dạng nội dung

File `.md` dùng đúng bộ tín hiệu quy định trong `latex/template.md`, để sau này chuyển sang LaTeX tự động được:

| Tín hiệu | Ý nghĩa |
|:---------|:--------|
| `**Từ vựng.**` | Bảng thuật ngữ Hán – Việt |
| `**Từ khóa nhận dạng.**` | Từ khóa đề bài → dạng bài tương ứng |
| `**Định nghĩa X — Tên.**` | Định nghĩa (khung xanh) |
| `**Tính chất X — Tên.**` | Định lý / tính chất (khung vàng) |
| `**Ví dụ X.**` + `**Giải.**` | Ví dụ minh họa (khung đen) |
| `**Dạng X — Tên dạng.**` | Dạng bài, kèm `**Cách nhận dạng.**` |
| `**Chú ý.**` | Lỗi thường gặp, không khung |
| `**Bài tập Câu X.**` | Mỗi câu một block riêng |

Hai script chuyển đổi (`md2tex-baitap.py`, `md2tex-luoigiai.py`) đọc **số buổi từ dòng `# BUỔI N — ...`** và **tên buổi từ dòng blockquote `> **Tên Việt （中文）**`**. Hai dòng này phải đúng định dạng ở mọi buổi, nếu không script báo lỗi và dừng.

### Bề ngang bảng

Bảng trong `.tex` dùng `tabular*{\linewidth}` để giãn hết vùng in, không dùng `tabular` thường (chỉ rộng bằng nội dung, trông lọt thỏm giữa trang). Sau khi sửa tay bảng trong file `.tex`, chạy lại:

```bash
python3 latex/scripts/rong-bang.py latex/*.tex
```

Script bỏ qua bảng đã đúng dạng nên chạy lại an toàn.

### Khối lượng bài tập

| Loại | Số câu | Tỉ lệ độ khó |
|:-----|:------:|:-------------|
| Bài tập chuẩn bị | 10 | 6 dễ / 3 trung bình / 1 khó |
| BTVN — bắt buộc | 25 | ~50% dễ / 30% trung bình / 20% khó |
| BTVN — tự chọn | 15 | ~15% dễ / 50% trung bình / 35% khó |

Phần tự chọn khó hơn rõ rệt so với phần bắt buộc. Mỗi buổi nội dung giao tổng cộng 40 câu BTVN.

### Nguồn câu hỏi

Câu hỏi lấy từ `question-bank/`. Mã câu (`CAE-M-CD{n}-{source}-{L}-{NNN}`) **chỉ ghi trong thư mục `giao-vien/`** — mã chứa nhãn độ khó, không nên cho học sinh thấy.

Câu do giáo viên tự soạn ghi mã `CAE-M-CD{n}-GV-{L}-{NNN}`.

**Toàn bộ đáp án phải được kiểm chứng trước khi đưa vào tài liệu.** Kho đề có câu sai đáp án và câu có nhiều hơn một đáp án đúng — đã phát hiện và loại bỏ trong quá trình biên soạn.

---

## Trạng thái biên soạn

| Buổi | Tên | Loại | Trạng thái |
|:----:|:----|:-----|:-----------|
| 1 | Tập hợp & bất đẳng thức | Nội dung | ✅ Đã chuyển .tex + PDF |
| 2 | Hàm số — tính chất | Nội dung | ✅ Đã chuyển .tex + PDF |
| 3 | Hàm số — bậc hai, mũ, logarit, đạo hàm | Nội dung | ✅ Đã chuyển .tex + PDF |
| 4 | Lượng giác — giá trị và công thức biến đổi | Nội dung | ✅ Đã chuyển .tex + PDF |
| 5 | Lượng giác — hàm số và phương trình | Nội dung + KT | ✅ Đã chuyển .tex + PDF |
| 6 | Dãy số | Nội dung + KT | ✅ Đã chuyển .tex + PDF |
| 7 | Chữa đề 1 | Chữa đề | ✅ Đã chuyển .tex + PDF |
| 8 | Hình học phẳng & không gian | Nội dung | ✅ Đã chuyển .tex + PDF |
| 9 | Đường thẳng và đường tròn | Nội dung | ✅ Đã chuyển .tex + PDF |
| 10 | Conic | Nội dung | ✅ Đã chuyển .tex + PDF |
| 11 | Chữa đề 2 | Chữa đề | ✅ Đã chuyển .tex + PDF |
| 12 | Vector và số phức | Nội dung + KT | ✅ Đã chuyển .tex + PDF |
| 13 | Chữa đề 3 | Chữa đề | ✅ Đã chuyển .tex + PDF |
| 14 | Xác suất | Nội dung | ✅ Đã chuyển .tex + PDF |
| 15 | Thống kê | Nội dung + KT | ✅ Đã chuyển .tex + PDF |
| 16 | Chữa đề 4 | Chữa đề | ✅ Đã chuyển .tex + PDF |
| 17 | Kỹ năng thi | Kỹ năng | ✅ Đã chuyển .tex + PDF |
| 18 | Chữa đề tổng hợp 1 | Chữa đề | ✅ Đã chuyển .tex + PDF |
| 19 | Chữa đề tổng hợp 2 | Chữa đề | ✅ Đã chuyển .tex + PDF |
| 20 | Ôn tập trước kiểm tra cuối kỳ | Ôn tập | ✅ Đã chuyển .tex + PDF |

*Chú thích: ⬜ Chưa bắt đầu · 🟡 Đang soạn · 🟢 Hoàn thiện `.md` · ✅ Đã chuyển `.tex` + PDF*

---

## Thay đổi so với syllabus hiện hành

**Buổi 8** được mở rộng thành *Hình học phẳng & không gian*, bổ sung phần diện tích mặt và thể tích của hình hộp, hình trụ, hình nón, hình cầu. Nội dung này có trong `references/[0.2]CSCA数学备考指南.pdf` (chương 9) nhưng chưa được đưa vào syllabus. Cần cập nhật lại `docs/syllabus.md` cho khớp.

## Kiểm tra trước khi bàn giao

Hai script kiểm tra, chạy trước khi bàn giao bất kỳ buổi nào:

```bash
# Lớp 1: kiểm tra nguồn .md (chạy trong thư mục buổi)
cd classready/buoi-XX-ten-buoi
python3 latex/scripts/kiem-tra.py

# Lớp 2: kiểm tra toàn bộ PDF của mọi buổi (chạy từ gốc repo)
python3 classready/kiem-tra-pdf.py
```

Lớp 1 bắt: dấu `**` lẻ, backtick chưa đóng, gạch dài trong câu văn, câu thiếu phương án, câu trùng giữa chuẩn bị và bài tập về nhà, và in phân bố đáp án A/B/C/D.

Lớp 1b — dò câu có hai phương án trùng giá trị (hai cách viết khác nhau nhưng cùng kết quả), chạy trong thư mục buổi:

```bash
python3 latex/scripts/kiem-tra-trung-phuong-an.py hoc-sinh/*.md giao-vien/*.md
```

Script chuẩn hóa LaTeX sang biểu thức sympy rồi thay số cùng một điểm cho cả bốn phương án, chỉ báo khi cặp phương án trùng ở mọi điểm thử. Không in gì là sạch.

Lớp 2 đo mọi PDF, bắt: ký hiệu markdown lọt ra bản in, lệnh LaTeX lộ, bảng tràn lề, chữ ngoài vùng an toàn, tiêu đề khung bị ghép đôi tiền tố ("Ví dụ Ví dụ 3"), và buổi không có ký tự Hán nào.

Lớp 2 cũng quét thẳng file `.tex` sinh tự động để bắt `%` chưa escape. Lỗi này **im lặng**: LaTeX ăn hết phần còn lại của dòng, đề bài mất nửa mà biên dịch vẫn báo thành công. Đã từng có ở buổi 3, 4.

Hai lớp này **không** phát hiện được lỗi font và lỗi bố cục. Với mỗi buổi mới, phải render ảnh từng trang và đọc ít nhất một lần.

---

*Tài liệu nội bộ — CAE SHANGHAI.*
