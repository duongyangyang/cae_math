# ĐỀ KIỂM TRA ĐẦU VÀO — CSCA TOÁN

Đề xếp lớp cho học sinh mới, rút gọn từ đề thi chính thức CSCA ngày 15.03.2026 (48 câu → 20 câu).

| Thông số | Đề gốc | Đề rút gọn |
|:---------|:------:|:----------:|
| Số câu | 48 | 20 |
| Thời gian | 60 phút | 30 phút |
| Giây mỗi câu | 75 | 90 |
| Thang điểm | 100 | 20 |

Giữ nguyên **tỉ lệ phân bố theo nhóm nội dung** của đề thật, nên kết quả phản ánh sát năng lực thực tế.

## Phân bố

| Module | Số câu | Tỉ lệ |
|:-------|:------:|:-----:|
| M1 Tập hợp & bất đẳng thức | 2 | 10% |
| M2 Hàm số & dãy số | 10 | 50% |
| M3 Hình học & đại số | 7 | 35% |
| M4 Xác suất & thống kê | 1 | 5% |

M2 chiếm một nửa số câu — cao hơn đề cương chính thức (33%). Đây là đặc điểm của đề thi thật: phần Hàm số và Dãy số được khai thác nặng nhất.

Đáp án phân bố đều: **A 5 · B 5 · C 5 · D 5**, để học sinh đoán mò không có lợi thế.

## Thang đánh giá

| Mức | Điểm | Xếp lớp đề xuất |
|:----|:----:|:----------------|
| Yếu | 5–9 | Cần học lại kiến thức nền trước khi vào chương trình |
| Trung bình | 10–13 | Vào chương trình chính, chú trọng buổi 1–3 |
| Khá | 14–16 | Vào chương trình chính |
| Giỏi | 17–20 | Vào chương trình, tập trung kỹ năng thi và câu khó |

## Cấu trúc thư mục

```
test-placement/
├── de-bai.md, dap-an.md      nguồn markdown
├── latex/
│   ├── cae-style.tex         gói lệnh (dùng chung với classready/)
│   ├── images/letterhead.png
│   ├── de-bai.tex, dap-an.tex
│   └── build.sh
└── pdf/
    ├── de-bai.pdf            4 trang
    └── dap-an.pdf            6 trang
```

Biên dịch: `./latex/build.sh`

## Bốn câu lỗi trong đề gốc đã loại

| Câu | Lỗi |
|:---:|:----|
| 8 | Hàm ngược đúng là $y=-\dfrac{x+2}{2x-3}$ (đáp án b), nhưng đề ghi (d) |
| 19 | Phương án D viết $0{,}75-0{,}2>0{,}75-0{,}4$ — thiếu ký hiệu lũy thừa |
| 26 | Lời giải tính ra $\dfrac{1}{3}$ nhưng đáp án ghi $\dfrac{2}{9}$; không đáp án nào đúng |
| 46 | Trùng hoàn toàn câu 45, phương án là số vô nghĩa |

Khi dùng đề gốc 20260315 để luyện tập, cần bỏ bốn câu này.

---

*Tài liệu nội bộ — CAE SHANGHAI.*
