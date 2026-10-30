## Phần 1 – Hybrid Workflow

1. **Có mất file không?** Không. Auto Sync luôn đẩy bản mới nhất lên Cloud, nên chỉ cần đăng nhập máy khác là tải lại được.
2. **3 bước Auto Sync:**
   - Cài Google Drive for Desktop / OneDrive và đăng nhập.
   - Chọn thư mục dự án để đồng bộ.
   - Mọi người lưu file thẳng vào thư mục đó và kiểm tra có tick xanh.
3. **Xóa nhầm 2 trang:** dùng **Version History** → chọn bản trước lúc xóa → **Restore this version**.
4. **Sai lầm:** đồng bộ file rác (`node_modules`) và file nặng không liên quan (phim 4K). Cách xử lý: chỉ sync file làm việc, loại trừ `node_modules`, để phim ngoài thư mục đồng bộ.

## Phần 2 – Phân quyền

| File | Quyền | Phạm vi | Lý do |
| --- | --- | --- | --- |
| Báo cáo (giảng viên) | **Viewer** | **Restricted** | Chỉ đọc, không sửa đè được |
| Slide (5 người) | **Editor** | **Restricted** | Cả nhóm cùng sửa, người ngoài không vào được |
| Góp ý (anh khóa trên) | **Commenter** | **Restricted** | Chỉ để lại nhận xét |
| Thông tin cá nhân | **Viewer** (chỉ người cần) | **Restricted** | Có CCCD, SĐT nên khóa chặt nhất |

**Quy tắc Cờ Đỏ:** file có dữ liệu cá nhân thì không bao giờ dùng `Anyone with the link` + `Editor`. Ai có link cũng xem, sửa, xóa, sao chép được, dữ liệu lộ ra thì không thu hồi được.

**2 thao tác Settings cho Slide:**
- Tắt "Editors can change permissions and share" (không cho tự mời người lạ).
- Tắt tùy chọn tải xuống/in/sao chép cho Viewer và Commenter.

## Phần 3 – Giao tiếp

**3 vấn đề:**
1. Vi phạm **No-Hello** ("có ai rảnh không" mà không nói việc gì).
2. **Tin nhắn không phân luồng** (ảnh mèo lẫn với công việc).
3. **Spam `@all` giờ khuya** (23:47).

**Channel đề xuất:** `#thong-bao` (deadline), `#thao-luan-bao-cao` (công việc), `#tan-gau` (trò chuyện).

**Tin nhắn của Lan viết lại:**
> Chào cả nhóm, em là Lan. Em đang làm mục 2.3 "Phân tích yêu cầu" và chưa biết nên vẽ Use Case cho *Sinh viên* hay *Quản trị viên* trước. File: [link]. Em cần chốt trước 12h trưa mai, mọi người trả lời trong thread này giúp em nhé, cảm ơn!

**Tin 23:47 viết lại (Schedule Send 8h sáng mai):**
> Chào buổi sáng! Hôm nay là hạn nộp báo cáo (chốt 20:00). Còn thiếu:
> - @Lan: mục 2.3
> - @Hoa: phần Thiết kế giao diện
>
> Xong thì thả ✅ vào tin này nhé.

## Phần 4 – Thông báo `#thong-bao`

> Chào cả nhóm, mình vừa cập nhật:
> 1. ✅ Đã bật **Auto Sync** cho thư mục dự án, từ giờ lưu file thẳng vào đó, không gửi qua Zalo nữa.
> 2. ✅ Đã chia sẻ file báo cáo cho giảng viên với quyền **Viewer / Restricted**.
> 3. ⚠️ Còn thiếu: @Lan hoàn thiện mục 2.3, @Hoa bổ sung phần Thiết kế giao diện, trước 20:00 hôm nay nhé.

*Tên người và deadline là ví dụ, hãy thay bằng thông tin thật của nhóm.*
