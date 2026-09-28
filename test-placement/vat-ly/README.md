# ĐỀ KIỂM TRA ĐẦU VÀO — CSCA VẬT LÝ

Đề xếp lớp cho học sinh mới, rút gọn từ đề thi chính thức CSCA tháng 12.2025 (48 câu → 20 câu).

| Thông số | Đề gốc | Đề rút gọn |
|:---------|:------:|:----------:|
| Số câu | 48 | 20 |
| Thời gian | 60 phút | 30 phút |
| Giây mỗi câu | 75 | 90 |
| Thang điểm | 100 | 20 |

Giữ nguyên tỉ lệ phân bố theo nhóm nội dung của đề thật, nên kết quả phản ánh sát năng lực thực tế.

## Phân bố

| Phần | Số câu | Tỉ lệ |
|:-----|:------:|:-----:|
| Cơ học | 9 | 45% |
| Điện từ | 5 | 25% |
| Dao động, sóng, quang, nhiệt | 6 | 30% |

Cơ học chiếm gần một nửa số câu, đúng như trọng số của đề thật.

Đáp án phân bố đều: **A 5 · B 5 · C 5 · D 5**, để học sinh đoán mò không có lợi thế.

## Thang đánh giá

| Mức | Điểm | Xếp lớp đề xuất |
|:----|:----:|:----------------|
| Yếu | 5–9 | Cần học lại kiến thức nền trước khi vào chương trình |
| Trung bình | 10–13 | Vào chương trình chính, chú trọng phần Cơ học |
| Khá | 14–16 | Vào chương trình chính |
| Giỏi | 17–20 | Vào chương trình, tập trung kỹ năng thi và câu khó |

## Cấu trúc thư mục

```
vat-ly/
├── de-bai.md, dap-an.md      nguồn markdown
├── latex/
│   ├── cae-style.tex         gói lệnh (dùng chung với classready/ và toan/)
│   ├── images/letterhead.png
│   ├── de-bai.tex, dap-an.tex
│   └── build.sh
└── pdf/
    ├── de-bai.pdf            3 trang
    └── dap-an.pdf            5 trang
```

Biên dịch: `./latex/build.sh`

## Lưu ý khi dùng đề gốc tháng 12.2025

**Câu 43 có đáp án sai.** Đề ghi A (200 m/s), nhưng tính đúng phải là B (100 m/s). Đạn xuyên hai tấm gỗ giống hệt nhau, mỗi tấm hấp thụ cùng một lượng động năng:

$$\frac{1}{2}m(700^2 - 500^2) = \frac{1}{2}m(500^2 - v_2^2) \implies v_2 = 100 \text{ m/s}$$

**Chín câu phụ thuộc hình vẽ**, không dùng được nếu tách khỏi đề gốc: câu 13, 16, 25, 37, 38, 40, 45, 46, 47.

**Năm câu lỗi trích xuất** (ký tự hỏng khi chuyển từ PDF): câu 12, 26, 27, 35, 39.

---

*Tài liệu nội bộ — CAE SHANGHAI.*
