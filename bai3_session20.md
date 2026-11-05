# 1. Phân tích 
- Input: Mã dự phòng (Backup Codes) được lưu trữ an toàn ngoại tuyến
- Process: Nhập mã dự phòng vào hệ thống AWS -> Hệ thống xác thực danh tính -> Vô hiệu hóa mã đã dùng -> Thu hồi quyền của thiết bị cũ -> Cài đặt Google Authenticator trên thiết bị mới và cấp bộ mã dự phòng mới
- Output: Khôi phục quyền truy cập an toàn, cô lập thiết bị đã mất
# 2. Giải thích 
- Nếu điện thoại bị mất và mở khóa được, kẻ xấu lập tức có toàn bộ mã dự phòng
- Các ứng dụng sao lưu ảnh tự động lên đám mây (Google Photos, iCloud) có thể bị rò rỉ nếu tài khoản Cloud bị xâm nhập