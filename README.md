# admeX Ratecard GitHub Pages

## Cách deploy
1. Upload `index.html`, `README.md` và thư mục `assets` lên repo GitHub.
2. Vào Settings → Pages.
3. Source: Deploy from a branch.
4. Branch: main, folder: /root.
5. Save và chờ GitHub Pages tạo link.

Website chạy HTML/CSS/JS thuần, không cần backend/API.


## v17 update
- Cột Chi tiết tại RATECARD TỔNG HỢP đã được chuyển thành deep link nội bộ để mở đúng tab ratecard tương ứng.
- Các link danh sách vị trí nội bộ trong bảng tổng hợp cũng trỏ về đúng tab list tương ứng.

## v18 update
- Ẩn công thức Excel trong bảng và hiển thị giá trị đã tính.
- Format lại các số lớn theo nhóm hàng nghìn để bảng đơn giá/thành tiền dễ đọc hơn.
- Số công thức đã thay: 3225; số ô số đã format: 6340.

## v19 update
- Rà soát currency theo file Excel `Bang tong hop gia ban Digital OOH_revised_ver2.3.xlsx`.
- Các ô định dạng USD trong Excel giữ ký hiệu `$` và dấu phẩy hàng nghìn.
- Các ô VND giữ định dạng nhóm hàng nghìn kiểu Việt Nam.
- Đã cập nhật 381 ô USD, 7 ô VND, 100 ô công thức có giá trị tính toán; còn lại 0 công thức literal được làm sạch.
