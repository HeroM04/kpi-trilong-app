# KPI Trí Long — bản phát hành app & hướng dẫn sử dụng

- **Releases**: mỗi lần Codemagic build app Android xong sẽ đăng `kpi-trilong.apk`
  và `phien-ban.json` vào đây. App của nhân viên đọc bản mới nhất để tự hỏi
  "Cập nhật / Để sau". Không xóa bản phát hành mới nhất.
- **docs/**: trang hướng dẫn sử dụng (GitHub Pages). App mở trang này từ menu
  "Hướng dẫn sử dụng" và nút (?) trên thanh tiêu đề. Mỗi mục có `id` riêng
  (`#cham-cong`, `#dao-tao`…) — đổi `id` thì sửa cả `lib/core/utils/huong_dan.dart`
  trong app.

Kho này chỉ chứa file phát hành và trang hướng dẫn, không có mã nguồn.
