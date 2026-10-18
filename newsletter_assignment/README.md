# Bài tập: Phối màu cho newsletter

Bộ bài nộp gồm hai trang HTML độc lập. Mỗi trang dùng Bootstrap 5.3.3 qua CDN, CSS tùy chỉnh bằng CSS variables và responsive cho màn hình nhỏ.

## File trong bộ bài

- `newsletter_version1.html` — phong cách SaaS tươi sáng, màu xanh dương chủ đạo.
- `newsletter_version2.html` — phong cách editorial, màu tím mận, xanh ngọc và nền kem.

## Bảng màu

### Version 1 — Bright teamwork
| Vai trò | HEX |
|---|---|
| Primary blue | `#0C66E4` |
| Primary dark | `#0747A6` |
| Navy / text | `#172B4D` |
| Green accent | `#36B37E` |
| Yellow accent | `#FFAB00` |
| Page background | `#F4F7FB` |
| Surface | `#FFFFFF` |

Định hướng phối màu: nhóm xanh dương gần nhau làm màu chính, điểm nhấn xanh lá và vàng cam cho trạng thái/nút bấm.

### Version 2 — Editorial contrast
| Vai trò | HEX |
|---|---|
| Plum | `#55406D` |
| Deep plum / text | `#29213A` |
| Teal | `#2A9D8F` |
| Coral | `#E76F51` |
| Golden accent | `#E9B44C` |
| Cream background | `#F6F0E8` |
| Surface | `#FFFCF7` |

Định hướng phối màu: nhóm tím trầm tạo nền biên tập, xanh ngọc và san hô tạo tương phản, vàng được dùng hạn chế cho CTA.

## Mở trang để xem

1. Tải xuống hoặc giải nén bộ file.
2. Mở `newsletter_version1.html` hoặc `newsletter_version2.html` bằng Chrome/Edge.
3. Cần kết nối Internet để tải Bootstrap từ CDN.

## Nộp bằng GitHub

1. Tạo repository mới trên GitHub.
2. Tải lên hai file HTML và `README.md`.
3. Dán URL repository vào phần nộp bài.

Nếu cần bản xem trực tiếp, có thể tạo hai Pen riêng trên CodePen và dán nội dung từng file HTML vào phần HTML (do CSS đang nằm trong thẻ `<style>` và Bootstrap được liên kết từ CDN).

## Adobe Color

Mở [Adobe Color — Color Wheel](https://color.adobe.com/create/color-wheel), nhập/đối chiếu các mã HEX trong bảng màu và thử các chế độ phối màu như Analogous hoặc Triadic. Kiểm tra thêm độ tương phản cho chữ và nền trước khi nộp. Bảng màu trong bộ file đã được tổ chức theo vai trò giao diện để dễ điều chỉnh trong `:root` của từng HTML.

## Những điểm đã làm

- Có header/nhãn thương hiệu, phần giới thiệu, nội dung chính, CTA và footer.
- Hai phiên bản có bảng màu, kiểu chữ và cảm nhận thị giác khác nhau.
- Dùng CSS variables để đổi màu tập trung trong `:root`.
- Có bố cục responsive, hiệu ứng hover nhẹ và các thuộc tính hỗ trợ accessibility như `aria-label`, `aria-labelledby`, `prefers-reduced-motion`.
