# CÁC CHUYÊN ĐỀ TOÁN TRONG LUYỆN THI CSCA

Kho tài liệu biên soạn bởi **CAE SHANGHAI**, phục vụ công tác giảng dạy và ôn luyện môn Toán cho kỳ thi **CSCA (China Scholastic Competency Assessment)**.

> **Phạm vi repo:** môn Toán. Kỳ thi CSCA còn có Vật lý, 理科中文 và 文科中文 — đề thi của ba môn này nằm trong `references/de-thi-chinh-thuc/` nhưng **chưa có chương trình giảng dạy** trong repo. Xem mục *Nguồn đề* bên dưới.

## Giới thiệu

Đề thi Toán CSCA gồm 48 câu trắc nghiệm, thời lượng 60 phút, thang điểm 100, được phân bố theo 4 module kiến thức chính. Bộ tài liệu này bám sát cấu trúc đề thi chính thức, triển khai thành 9 chuyên đề giảng dạy nhằm đảm bảo học sinh nắm chắc kiến thức nền, kỹ năng vận dụng và tư duy giải quyết vấn đề.

## Tổng quan cấu trúc repo

| Thư mục / File | Nội dung |
|---|---|
| `docs/` | Tài liệu chương trình: syllabus, tổng quan, phân tích đề cương |
| `source/` | Tài liệu giảng dạy dạng `.md` theo từng chuyên đề (đã chuyển sang `classready/`) |
| `latex/` | Template LaTeX chuẩn giáo trình và system prompt chuyển đổi `.md → .tex` |
| `classready/` | Tài liệu giảng dạy hoàn chỉnh theo từng buổi, tách riêng bản học sinh và bản giáo viên |
| `test-placement/` | Đề kiểm tra đầu vào rút gọn từ đề thi thật |
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

## Nguồn đề (`references/`)

| Thư mục | Nội dung |
|---|---|
| `references/de-thi-chinh-thuc/12-6月数学/` | Đề thi CSCA **môn Toán** chính thức, sắp theo tháng thi |
| `references/de-thi-chinh-thuc/12-4月物理/` | Đề thi CSCA **môn Vật lý** chính thức |
| `references/de-thi-chinh-thuc/12-4月理科中文/` | Đề thi CSCA **理科中文** (Khoa học tự nhiên – tiếng Trung) |
| `references/de-thi-chinh-thuc/12-6月文科中文/` | Đề thi CSCA **文科中文** (Khoa học xã hội – tiếng Trung) |
| `references/de-luyen-tap/` | Đề luyện tập và đề mô phỏng môn Toán |
| `references/[0.2]CSCA数学备考指南.pdf` | Cẩm nang ôn tập môn Toán |

Repo này hiện chỉ biên soạn **môn Toán**. Ba môn còn lại (Vật lý, 理科中文, 文科中文) có đề trong `references/` nhưng chưa có chương trình giảng dạy tương ứng.

## Tiến độ cập nhật

| Chuyên đề | Trạng thái | Ghi chú |
|---|---|---|
| Tổng quan về Toán trong CSCA | 🟡 Đang soạn | — |
| CĐ1: Tập hợp (集合) | ⬜ Chưa bắt đầu | Bản cũ đã xóa, soạn lại theo cấu trúc mới |
| CĐ2: Bất đẳng thức (不等式) | ⬜ Chưa bắt đầu | — |
| CĐ3: Dãy số (数列) | ⬜ Chưa bắt đầu | — |
| CĐ4: Hàm số (函数) | ⬜ Chưa bắt đầu | — |
| CĐ5: Hình học (几何) (1) | ⬜ Chưa bắt đầu | — |
| CĐ6: Hình học (几何) (2) | ⬜ Chưa bắt đầu | — |
| CĐ7: Đại số (代数) | ⬜ Chưa bắt đầu | — |
| CĐ8: Xác suất (概率) | ⬜ Chưa bắt đầu | — |
| CĐ9: Thống kê (统计) | ⬜ Chưa bắt đầu | — |

*Chú thích: ⬜ Chưa bắt đầu · 🟡 Đang soạn · 🟢 Hoàn thiện `.md` · ✅ Đã chuyển `.tex` + PDF*
