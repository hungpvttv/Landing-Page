# Landing page sự kiện

Site tĩnh (HTML + JSON), nội dung chỉnh qua PagesCMS.

## Giao diện
Mục "Giao diện" trên CMS chỉnh màu toàn trang, font chữ, kiểu và bo góc nút.

## Cấu trúc
- `index.html` – trang chủ, đọc dữ liệu từ `content/site.json`
- `content/site.json` – toàn bộ nội dung (PagesCMS sửa file này)
- `images/` – ảnh upload qua PagesCMS
- `.pages.yml` – cấu hình PagesCMS

## Triển khai
1. Tạo repo GitHub, đẩy toàn bộ thư mục này lên nhánh `main`.
2. Repo → Settings → Pages → Source: *Deploy from a branch* → `main` / `(root)`.
3. Vào https://app.pagescms.org, đăng nhập GitHub, chọn repo → mục "Nội dung landing page".
4. Mỗi lần bấm Save trên CMS sẽ commit vào repo, GitHub Pages tự cập nhật sau ~1 phút.

Tên miền riêng: thêm file `CNAME` chứa tên miền, rồi trỏ DNS về GitHub Pages.
