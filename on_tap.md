# Ghi chú ôn tập – SmartCampus

## 1. Hai lỗi cú pháp trong đoạn Markdown

**Lỗi 1 – Thiếu dòng phân cách trong bảng:** Ngay sau dòng tiêu đề `| Tính năng | Trạng thái |` phải có dòng phân cách như `| --- | --- |`; nếu thiếu, GitHub có thể không nhận đó là bảng Markdown.

**Lỗi 2 – Thiếu dấu cách trong Task List:** Các dòng `-[x]` và `-[ ]` phải được viết thành `- [x]` và `- [ ]`. Dấu cách sau dấu gạch ngang là bắt buộc để nhận đúng cú pháp danh sách công việc.

## 2. Đoạn Markdown đã sửa

```markdown
| Tính năng | Trạng thái |
| --- | --- |
| Tra cứu lịch học | Xong |
| Push notification | Đang làm |

- [x] Tra cứu lịch học
- [ ] Push notification
```

## 3. Điều rút ra sau bài thực hành

File `.md` là **văn bản thuần (plain text)**: mình gõ các ký hiệu như `#`, `**`, `-` hay dấu `|` ngay trong nội dung. Khi mở trên StackEdit hoặc GitHub, **Markdown Parser** đọc những ký hiệu đó và tạo ra tiêu đề, chữ đậm, bảng hay Task List ở giao diện hiển thị. Vì thế, chỉ một dòng phân cách hoặc một dấu cách bị thiếu cũng có thể làm kết quả render khác với mong muốn.
