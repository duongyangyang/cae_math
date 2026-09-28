# ĐỀ KIỂM TRA ĐẦU VÀO — CSCA

Bộ đề xếp lớp cho học sinh mới, rút gọn từ đề thi chính thức CSCA: 48 câu trong 60 phút → **20 câu trong 30 phút**.

Mỗi môn giữ nguyên tỉ lệ phân bố theo nhóm nội dung của đề thật, nên kết quả phản ánh sát năng lực thực tế. Đáp án của cả hai đề đều phân bố đều **A 5 · B 5 · C 5 · D 5**, để học sinh đoán mò không có lợi thế.

## Các môn

| Môn | Nguồn đề gốc | Trạng thái |
|:----|:-------------|:-----------|
| [Toán](toan/) | CSCA 15.03.2026 | ✅ Đã có PDF |
| [Vật lý](vat-ly/) | CSCA 12.2025 | ✅ Đã có PDF |
| 理科中文 | CSCA 04.2026 | ⬜ Chưa soạn |
| 文科中文 | CSCA 06.2026 | ⬜ Chưa soạn |

## Thang đánh giá dùng chung

| Mức | Điểm | Xếp lớp đề xuất |
|:----|:----:|:----------------|
| Yếu | 5–9 | Cần học lại kiến thức nền trước khi vào chương trình |
| Trung bình | 10–13 | Vào chương trình chính, chú trọng các buổi đầu |
| Khá | 14–16 | Vào chương trình chính |
| Giỏi | 17–20 | Vào chương trình, tập trung kỹ năng thi và câu khó |

## Cấu trúc thư mục

```
test-placement/
├── toan/                     môn Toán
├── vat-ly/                   môn Vật lý
└── <môn>/                    mỗi môn một thư mục, cấu trúc giống nhau:
    ├── README.md             thông số đề, phân bố, lưu ý về đề gốc
    ├── de-bai.md, dap-an.md  nguồn markdown
    ├── latex/                cae-style.tex, de-bai.tex, dap-an.tex, build.sh, images/
    └── pdf/                  de-bai.pdf, dap-an.pdf
```

Biên dịch một môn: `cd <môn> && ./latex/build.sh`

`cae-style.tex` giống nhau ở mọi môn; trang bìa lấy tên môn từ lệnh `\def\monhoc{...}` khai báo ở đầu mỗi file `.tex`. Khi sửa gói lệnh, phải chép sang tất cả các môn và `classready/`.

---

*Tài liệu nội bộ — CAE SHANGHAI.*
