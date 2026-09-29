# ĐỀ KIỂM TRA ĐẦU VÀO — CSCA TIẾNG TRUNG KHOA HỌC (理科中文)

Đề xếp lớp cho học sinh mới, rút gọn từ đề thi chính thức CSCA 25.04.2026: 80 câu → **20 câu trong 30 phút**.

## Thông số

| Mục | Giá trị |
|:----|:--------|
| Nguồn đề gốc | CSCA 理科中文 25.04.2026 |
| Số câu | 20 |
| Thời gian | 30 phút |
| Trung bình | 90 giây/câu |
| Phân bố đáp án | A 5 · B 5 · C 5 · D 5 |
| Không dùng | từ điển |

## Phân bố nội dung

Đề giữ đúng sáu phần và tỉ lệ câu của đề thật:

| Phần | Nội dung | Đề thật | Đề này |
|:-----|:---------|:-------:|:------:|
| 1 | 识解汉字 — nhận diện chữ Hán | 10 | 3 |
| 2 | 选词填空 — điền từ (nhóm 1) | 15 | 4 |
| 3 | 近义反义词 — đồng nghĩa, trái nghĩa | 8 | 2 |
| 4 | 选词填空 — điền từ (nhóm 2) | 15 | 3 |
| 5 | 补全语句 — hoàn thành câu | 22 | 5 |
| 6 | 阅读理解 — đọc hiểu | 10 | 3 |

## Đặc điểm riêng của môn này

Toàn bộ ngữ liệu thuộc **lĩnh vực khoa học tự nhiên**: vật lý, hóa học, sinh học, toán. Đây là đặc trưng phân biệt 理科中文 với 文科中文 — học sinh phải đọc được thuật ngữ khoa học tiếng Trung (测量, 溶解, 过滤, 变量, 试剂), không chỉ tiếng Trung thông dụng.

Đề đo **năng lực đọc hiểu tiếng Trung trong ngữ cảnh khoa học**, không đo kiến thức khoa học. Câu 17 kiểm tra mẫu câu 与……无关 chứ không kiểm tra định luật bảo toàn khối lượng. Khi nhận xét kết quả, cần tách hai yếu tố này: một học sinh giỏi lý nhưng yếu tiếng Trung vẫn có thể sai nhiều câu.

## Cấu trúc thư mục

```
tieng-trung-khoa-hoc/
├── README.md               file này
├── de-bai.md, dap-an.md    nguồn markdown
├── latex/                  cae-style.tex, de-bai.tex, dap-an.tex, build.sh, images/
└── pdf/                    de-bai.pdf, dap-an.pdf
```

Biên dịch: `cd tieng-trung-khoa-hoc && ./latex/build.sh`

## Ghi chú kỹ thuật

`cae-style.tex` phải **giống hệt** ở cả ba môn (`toan/`, `vat-ly/`, `tieng-trung-khoa-hoc/`) và giống bản trong `classready/`. Khi sửa gói lệnh, chép cho cả ba rồi build lại từng môn.

Trang bìa lấy tên môn từ lệnh `\def\monhoc{...}` khai báo ở đầu mỗi file `.tex`. Thiếu dòng này thì bìa in nhầm "Môn Toán" — đây là lỗi đã từng xảy ra với môn Vật lý.

---

*Tài liệu nội bộ, CAE SHANGHAI.*
