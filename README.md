# 🎧 Đọc Truyện Audio

Web app **1 file** đọc truyện online bằng giọng nói và **tự động chuyển chương** — chạy thẳng trên trình duyệt điện thoại, không cần cài đặt.

## Tính năng
- Dán link **một chương bất kỳ** → tự lấy nội dung sạch (bỏ menu, quảng cáo).
- **Đọc audio** bằng giọng có sẵn của thiết bị (Web Speech API), ưu tiên giọng tiếng Việt.
- **Tự next chương**: đọc hết chương tự chuyển và đọc tiếp.
- **Tốc độ tới 3x**, nút chọn nhanh, chỉnh cao độ, nghe thử giọng.
- **Nhảy tới chương bất kỳ** theo số.
- Highlight câu đang đọc, chạm để nhảy tới; giữ màn hình sáng khi nghe.
- Giao diện Tối / Sáng / Sepia, chỉnh cỡ chữ; nhớ tiến độ & cài đặt.

## Cách dùng
Mở trang (hoặc tải `index.html` về mở bằng trình duyệt), dán link chương, bấm **Tải**, rồi bấm **▶**.

## Cơ chế
Do trình duyệt chặn CORS, app lấy nội dung qua proxy công khai (ưu tiên [Jina Reader](https://jina.ai/reader)) và tự dò link chương kế; nếu không thấy sẽ suy ra theo số chương trong URL.

> Chỉ dùng cho mục đích đọc cá nhân; nội dung thuộc về các trang truyện nguồn.
