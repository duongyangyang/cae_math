# TÀI LIỆU GIẢNG DẠY — CHƯƠNG TRÌNH LUYỆN THI CSCA TOÁN

Thư mục chứa tài liệu hoàn chỉnh của từng buổi học, sẵn sàng đưa vào giảng dạy. Mỗi buổi là một thư mục riêng, tổ chức theo loại hoạt động.

Nội dung biên soạn theo `docs/syllabus.md` và tham chiếu `references/[0.2]CSCA数学备考指南.pdf`.

---

## Cấu trúc thư mục

Mỗi loại buổi có một bộ file riêng, phản ánh đúng hoạt động của buổi đó.

### Buổi nội dung (1, 2, 3, 4, 6, 8, 9, 10, 12, 14, 15)

```
buoi-XX-ten-buoi/
├── 01-chuan-bi-bai.md      Học sinh làm TRƯỚC buổi học
├── 02-noi-dung-buoi.md     Tài liệu giảng dạy trên lớp
├── 03-bai-tap-ve-nha.md    BTVN sau buổi học
└── 04-dap-an.md            Đáp án + lời giải chi tiết
```

### Buổi nội dung có kiểm tra cuối chuyên đề (5, 6, 12, 15)

```
buoi-XX-ten-buoi/
├── 01-chuan-bi-bai.md
├── 02-noi-dung-buoi.md
├── 03-bai-tap-ve-nha.md
├── 04-dap-an.md
├── 05-de-kiem-tra.md       Đề kiểm tra cuối chuyên đề
└── 06-dap-an-kiem-tra.md   Đáp án đề kiểm tra
```

### Buổi chữa đề (7, 11, 13, 16, 18, 19)

```
buoi-XX-chua-de-N/
├── 01-de-bai.md            Đề học sinh làm trước buổi
├── 02-noi-dung-buoi.md     Kịch bản chữa đề theo phương thức phân tầng
└── 03-dap-an.md            Đáp án + lời giải
```

### Buổi kỹ năng thi (17) và ôn tập (20)

```
buoi-XX-ten-buoi/
├── 01-chuan-bi-bai.md
├── 02-noi-dung-buoi.md
└── 03-bai-tap-ve-nha.md
```

---

## Quy ước biên soạn

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

### Khối lượng bài tập

| Loại | Số câu | Tỉ lệ độ khó |
|:-----|:------:|:-------------|
| Bài tập chuẩn bị | 10 | 6 dễ / 3 trung bình / 1 khó |
| BTVN — bắt buộc | 25 | ~50% dễ / 30% trung bình / 20% khó |
| BTVN — tự chọn | 15 | ~15% dễ / 50% trung bình / 35% khó |

Phần tự chọn khó hơn rõ rệt so với phần bắt buộc. Mỗi buổi nội dung giao tổng cộng 40 câu BTVN.

### Nguồn câu hỏi

Câu hỏi lấy từ `question-bank/`, giữ nguyên mã câu (`CAE-M-CD{n}-{source}-{L}-{NNN}`) để truy vết. Câu do giáo viên tự soạn ghi mã `CAE-M-CD{n}-GV-{L}-{NNN}`.

**Toàn bộ đáp án phải được kiểm chứng trước khi đưa vào tài liệu.** Kho đề có câu sai đáp án và câu có nhiều hơn một đáp án đúng — đã phát hiện và loại bỏ trong quá trình biên soạn.

---

## Trạng thái biên soạn

| Buổi | Tên | Loại | Trạng thái |
|:----:|:----|:-----|:-----------|
| 1 | Tập hợp & bất đẳng thức | Nội dung | 🟢 Hoàn thiện |
| 2 | Hàm số — tính chất | Nội dung | ⬜ Chưa bắt đầu |
| 3 | Hàm số — bậc hai, mũ, logarit, đạo hàm | Nội dung | ⬜ Chưa bắt đầu |
| 4 | Lượng giác — giá trị và công thức biến đổi | Nội dung | ⬜ Chưa bắt đầu |
| 5 | Lượng giác — hàm số và phương trình | Nội dung + KT | ⬜ Chưa bắt đầu |
| 6 | Dãy số | Nội dung + KT | ⬜ Chưa bắt đầu |
| 7 | Chữa đề 1 | Chữa đề | ⬜ Chưa bắt đầu |
| 8 | Hình học phẳng & không gian | Nội dung | ⬜ Chưa bắt đầu |
| 9 | Đường thẳng và đường tròn | Nội dung | ⬜ Chưa bắt đầu |
| 10 | Conic | Nội dung | ⬜ Chưa bắt đầu |
| 11 | Chữa đề 2 | Chữa đề | ⬜ Chưa bắt đầu |
| 12 | Vector và số phức | Nội dung + KT | ⬜ Chưa bắt đầu |
| 13 | Chữa đề 3 | Chữa đề | ⬜ Chưa bắt đầu |
| 14 | Xác suất | Nội dung | ⬜ Chưa bắt đầu |
| 15 | Thống kê | Nội dung + KT | ⬜ Chưa bắt đầu |
| 16 | Chữa đề 4 | Chữa đề | ⬜ Chưa bắt đầu |
| 17 | Kỹ năng thi | Kỹ năng | ⬜ Chưa bắt đầu |
| 18 | Chữa đề tổng hợp 1 | Chữa đề | ⬜ Chưa bắt đầu |
| 19 | Chữa đề tổng hợp 2 | Chữa đề | ⬜ Chưa bắt đầu |
| 20 | Ôn tập trước kiểm tra cuối kỳ | Ôn tập | ⬜ Chưa bắt đầu |

*Chú thích: ⬜ Chưa bắt đầu · 🟡 Đang soạn · 🟢 Hoàn thiện `.md` · ✅ Đã chuyển `.tex` + PDF*

---

## Thay đổi so với syllabus hiện hành

**Buổi 8** được mở rộng thành *Hình học phẳng & không gian*, bổ sung phần diện tích mặt và thể tích của hình hộp, hình trụ, hình nón, hình cầu. Nội dung này có trong `references/[0.2]CSCA数学备考指南.pdf` (chương 9) nhưng chưa được đưa vào syllabus. Cần cập nhật lại `docs/syllabus.md` cho khớp.

---

*Tài liệu nội bộ — CAE SHANGHAI.*
