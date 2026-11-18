là bài tập làm quen với github của môn quản lý dự án công nghệ thông tin. 
Hướng dẫn sử dụng:
# Khởi tạo Git tại thư mục hiện tại
git init

# Thêm toàn bộ file vào khu vực chờ lưu
git add .

# Lưu lại phiên bản kèm ghi chú
git commit -m "Tai code lan dau"

# Kết nối với kho lưu trữ trên GitHub (thay URL bằng link repo của bạn)
git remote add origin https://github.com/ten-tai-khoan/ten-repo.git

# Đẩy code lên nhánh main
git push -u origin main
