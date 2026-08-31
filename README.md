# CÁC CHUYÊN ĐỀ TOÁN TRONG LUYỆN THI CSCA

Kho tài liệu biên soạn bởi **CAE VIỆT NAM**, phục vụ công tác giảng dạy và ôn luyện môn Toán cho kỳ thi **CSCA (China Standard Curriculum Assessment)**.

## Giới thiệu

Đề thi Toán CSCA gồm 48 câu trắc nghiệm, thời lượng 60 phút, thang điểm 100, được phân bố theo 4 module kiến thức chính. Bộ tài liệu này bám sát cấu trúc đề thi chính thức, triển khai thành 9 chuyên đề giảng dạy nhằm đảm bảo học sinh nắm chắc kiến thức nền, kỹ năng vận dụng và tư duy giải quyết vấn đề.

> **Nguồn tài liệu gốc:** [Google Drive – CAE Math CSCA](#) *(cập nhật link khi có)*

## Tổng quan cấu trúc repo

| Thư mục / File | Nội dung |
|---|---|
| `source/` | Chứa các thư mục con theo từng chuyên đề; mỗi thư mục lưu tài liệu giảng dạy dạng `.md`, kèm hình ảnh, bảng biểu minh họa (nếu có) |
| `latex/` | Chứa template LaTeX chuẩn giáo trình, system prompt để chuyển đổi `.md → .tex`, và các file `.tex` đã biên soạn |
| `classready/` | Chứa tài liệu hoàn thiện ở dạng `.pdf`, sẵn sàng in ấn/sử dụng trên lớp |
| `tableofcontent.md` | Mục lục tổng thể của toàn bộ chương trình, đối chiếu với cấu trúc đề thi CSCA |
| `overview.md` | Giới thiệu chung về kỳ thi CSCA và định hướng học Toán |

**Quy trình biên soạn:** `source/*.md` → (áp dụng `latex/system_prompt.md`) → `latex/*.tex` → biên dịch → `classready/*.pdf`

## Tiến độ cập nhật

| Chuyên đề | Trạng thái | Ghi chú |
|---|---|---|
| Tổng quan về Toán trong CSCA | 🟡 Đang soạn | — |
| CĐ1: Tập hợp (集合) | ✅ Đã chuyển `.tex` + PDF | Test pipeline thành công |
| CĐ2: Bất đẳng thức (不等式) | ⬜ Chưa bắt đầu | — |
| CĐ3: Dãy số (数列) | ⬜ Chưa bắt đầu | — |
| CĐ4: Hàm số (函数) | ⬜ Chưa bắt đầu | — |
| CĐ5: Hình học (几何) (1) | ⬜ Chưa bắt đầu | — |
| CĐ6: Hình học (几何) (2) | ⬜ Chưa bắt đầu | — |
| CĐ7: Đại số (代数) | ⬜ Chưa bắt đầu | — |
| CĐ8: Xác suất (概率) | ⬜ Chưa bắt đầu | — |
| CĐ9: Thống kê (统计) | ⬜ Chưa bắt đầu | — |

*Chú thích: ⬜ Chưa bắt đầu · 🟡 Đang soạn · 🟢 Hoàn thiện `.md` · ✅ Đã chuyển `.tex` + PDF*
