# CÁC CHUYÊN ĐỀ TOÁN TRONG LUYỆN THI CSCA

Kho tài liệu biên soạn bởi **CAE SHANGHAI**, phục vụ công tác giảng dạy và ôn luyện môn Toán cho kỳ thi **CSCA (China Scholastic Competency Assessment)**.

## Giới thiệu

Đề thi Toán CSCA gồm 48 câu trắc nghiệm, thời lượng 60 phút, thang điểm 100, được phân bố theo 4 module kiến thức chính. Bộ tài liệu này bám sát cấu trúc đề thi chính thức, triển khai thành 9 chuyên đề giảng dạy nhằm đảm bảo học sinh nắm chắc kiến thức nền, kỹ năng vận dụng và tư duy giải quyết vấn đề.

> **Nguồn tài liệu gốc:** [Google Drive – CAE Math CSCA](#) *(cập nhật link khi có)*

## Tổng quan cấu trúc repo

| Thư mục / File | Nội dung |
|---|---|
| `docs/` | Tài liệu chương trình: syllabus, tổng quan, phân tích đề cương |
| `source/` | Tài liệu giảng dạy dạng `.md` theo từng chuyên đề, kèm hình ảnh, bảng biểu minh họa (nếu có) |
| `latex/` | Template LaTeX chuẩn giáo trình, system prompt để chuyển đổi `.md → .tex`, và các file `.tex` đã biên soạn |
| `classready/` | Tài liệu hoàn thiện ở dạng `.pdf`, sẵn sàng in ấn/sử dụng trên lớp |
| `question-bank/` | Kho đề markdown chuẩn hóa, phân theo 9 chuyên đề |
| `references/` | Đề thi chính thức và đề luyện tập dùng làm nguồn biên soạn |

**Quy trình biên soạn:** `source/*.md` → (áp dụng `latex/system_prompt.md`) → `latex/*.tex` → biên dịch → `classready/*.pdf`

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
| `references/de-thi-chinh-thuc/` | Đề thi CSCA môn Toán chính thức, sắp theo tháng thi |
| `references/de-luyen-tap/` | Đề luyện tập và đề mô phỏng dùng cho biên soạn và chữa đề |

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
