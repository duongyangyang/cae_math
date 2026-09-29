# CÁC CHUYÊN ĐỀ TOÁN TRONG LUYỆN THI CSCA

Kho tài liệu biên soạn bởi **CAE SHANGHAI**, phục vụ công tác giảng dạy và ôn luyện môn Toán cho kỳ thi **CSCA (China Scholastic Competency Assessment)**.

> **Phạm vi repo:** chương trình giảng dạy hiện có **môn Toán** (20 buổi hoàn chỉnh). Kỳ thi CSCA còn có Vật lý, 理科中文 và 文科中文 — ba môn này đã có đề kiểm tra đầu vào và đề thi chính thức lưu trong `references/`, nhưng **chưa có chương trình giảng dạy** trong repo. Xem mục *Nguồn đề* bên dưới.

## Giới thiệu

Đề thi Toán CSCA gồm 48 câu trắc nghiệm, thời lượng 60 phút, thang điểm 100, được phân bố theo 4 module kiến thức chính. Bộ tài liệu này bám sát cấu trúc đề thi chính thức, triển khai thành 9 chuyên đề giảng dạy nhằm đảm bảo học sinh nắm chắc kiến thức nền, kỹ năng vận dụng và tư duy giải quyết vấn đề.

## Tổng quan cấu trúc repo

| Thư mục / File | Nội dung |
|---|---|
| `docs/` | Tài liệu chương trình: syllabus, tổng quan, phân tích đề cương |
| `latex/` | Template LaTeX chuẩn giáo trình và system prompt chuyển đổi `.md → .tex` |
| `classready/` | Tài liệu giảng dạy hoàn chỉnh theo từng buổi, tách riêng bản học sinh và bản giáo viên |
| `test-placement/` | Đề kiểm tra đầu vào rút gọn từ đề thi thật, ba môn Toán, Vật lý, 理科中文 |
| `question-bank/` | Kho đề markdown chuẩn hóa, phân theo 9 chuyên đề |
| `references/` | Đề thi chính thức bốn môn và đề luyện tập môn Toán |
| `.claude/skills/csca-tai-lieu/` | Quy trình soạn tài liệu, dùng cho các buổi tiếp theo |

**Quy trình biên soạn:** `classready/*.md` (nguồn) → `.tex` → biên dịch XeLaTeX → PDF bàn giao

## Tài liệu chương trình (`docs/`)

| File | Nội dung |
|---|---|
| `syllabus.md` | Đề cương chương trình: thông tin khóa học, chuẩn đầu ra, đánh giá, lịch trình 20 buổi |
| `overview.md` | Giới thiệu chung về kỳ thi CSCA và định hướng học Toán |
| `Math Syllabus Analysis.pdf` | Phân tích đề cương chính thức do đơn vị tổ chức thi công bố |

## Kho đề (`question-bank/`)

Kho đề gồm 9 chuyên đề, mỗi câu hỏi được gán nhãn chuyên đề, module, độ khó và nguồn. Nội dung câu hỏi bằng tiếng Trung, công thức LaTeX.

Mã câu hỏi theo format `CAE-M-CD{n}-{source}-{L}-{NNN}`. Chi tiết xem tại [`question-bank/README.md`](question-bank/README.md).

## Đề kiểm tra đầu vào (`test-placement/`)

Bộ đề xếp lớp cho học sinh mới, rút gọn từ đề thi chính thức theo tỉ lệ **48 câu / 60 phút → 20 câu / 30 phút**. Mỗi môn giữ nguyên tỉ lệ phân bố theo nhóm nội dung của đề thật, đáp án phân bố đều A 5 · B 5 · C 5 · D 5.

| Môn | Mã | Nguồn | Trạng thái |
|:----|:--:|:------|:-----------|
| [Toán](test-placement/toan/) | `TOAN` | CSCA 15.03.2026 | ✅ Đã có PDF |
| [Vật lý](test-placement/vat-ly/) | `VATLY` | CSCA 12.2025 | ✅ Đã có PDF |
| [Tiếng Trung khoa học](test-placement/tieng-trung-khoa-hoc/) | `TTKH` | CSCA 25.04.2026 | ✅ Đã có PDF |

Tên PDF mang mã tài liệu dạng `CAE-PT-<MÔN>-<SỐ>-<loại>.pdf`. Chi tiết thang đánh giá và cấu trúc thư mục xem tại [`test-placement/README.md`](test-placement/README.md).

## Nguồn đề (`references/`)

Đề thi chính thức sắp theo **môn**, trong mỗi môn chia theo **ngày thi**. Tên file dùng tiếng Việt/Anh, thống nhất `de-bai`, `dap-an`, `de-bai-va-dap-an`; hậu tố `-en` là bản tiếng Anh, `-sach` là bản đã xóa watermark.

```
references/de-thi-chinh-thuc/
├── toan/                    Toán
├── vat-ly/                  Vật lý
├── tieng-trung-khoa-hoc/    Tiếng Trung khoa học (理科中文)
└── tieng-trung-xa-hoi/      Tiếng Trung xã hội (文科中文)
```

Mỗi thư mục môn chia theo ngày thi, ví dụ `vat-ly/2026-03-15/de-bai.pdf`. Thư mục chỉ có một file thì để thẳng trong thư mục ngày.

| Thư mục | Nội dung |
|---|---|
| `references/de-thi-chinh-thuc/` | Đề thi chính thức bốn môn, sắp theo môn và ngày thi |
| `references/de-luyen-tap/toan/` | Đề luyện tập và đề mô phỏng môn Toán |
| `references/csca-toan-cam-nang-on-tap.pdf` | Cẩm nang ôn tập môn Toán |
| `references/cae-letterhead.docx`, `references/cae-logo.jpg` | Mẫu letterhead và logo dùng in tài liệu |

Chương trình giảng dạy hiện chỉ biên soạn **môn Toán**. Ba môn còn lại đã có đề kiểm tra đầu vào trong `test-placement/` và đề thi chính thức trong `references/`, nhưng chưa có chương trình giảng dạy tương ứng.

## Tiến độ cập nhật

**Chương trình giảng dạy: hoàn thành 20/20 buổi.** Mỗi buổi có đủ tài liệu học sinh và tài liệu giáo viên, đã chuyển sang `.tex` và biên dịch thành PDF. Chi tiết từng buổi xem tại [`classready/README.md`](classready/README.md).

| Loại buổi | Số buổi | Buổi |
|---|:---:|---|
| Nội dung | 12 | 1, 2, 3, 4, 5, 6, 8, 9, 10, 12, 14, 15 |
| Chữa đề | 6 | 7, 11, 13, 16, 18, 19 |
| Kỹ năng thi và ôn tập | 2 | 17, 20 |

Buổi 5, 6, 12, 15 có thêm đề kiểm tra cuối chuyên đề. Tổng cộng **118 PDF**.

| Hạng mục | Trạng thái |
|---|---|
| Chương trình 20 buổi (`classready/`) | ✅ Hoàn thành |
| Kho đề 9 chuyên đề (`question-bank/`) | ✅ Hoàn thành |
| Đề kiểm tra đầu vào — Toán | ✅ Đã có PDF |
| Đề kiểm tra đầu vào — Vật lý | ✅ Đã có PDF |
| Đề kiểm tra đầu vào — 理科中文 | ✅ Đã có PDF |
| Đề kiểm tra đầu vào — 文科中文 | ⬜ Chưa soạn |
| Chương trình giảng dạy Vật lý, 理科中文, 文科中文 | ⬜ Chưa soạn |
