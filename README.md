# Inkscape-VAS

Phần mềm nguồn mở tích hợp trong **Vietnews AI Studio (VAS)** — Vietnews phân phối lại đúng bản VAS dùng (mã băm SHA-256 khớp bản phát hành VAS đã ký),
kèm mã nguồn tương ứng và giấy phép. Bộ cài VAS tải từ đây trước, lỗi thì tải từ nhà phát triển gốc.

| Phần mềm | Phiên bản | Giấy phép | Bản phát hành |
|---|---|---|---|
| Inkscape (đồ hoạ vector: chữ, sơ đồ, đồ hoạ chuyển động; xuất PNG / PDF bằng lệnh) | 1.4.4 | GPL-3.0-or-later (thư viện đi kèm: LGPL / GPL / MIT…) | [inkscape-1.4.4](../../releases/tag/inkscape-1.4.4) |

Mỗi bản phát hành: tệp chạy gốc (không sửa), `nguon--…` mã nguồn tương ứng (theo danh mục `nguon/<id>.json`), `giay-phep--…`, `SHA256SUMS.txt`.
Bản phát hành do GitHub Actions tạo (`.github/workflows/publish.yml`): tải từ nguồn gốc, kiểm mã băm ghim, sai là không phát hành.

Bản quyền phần mềm thuộc các tác giả / cộng đồng của từng dự án. Yêu cầu mã nguồn: support@vietnews.com.vn
