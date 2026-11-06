## phần 1

1. câu a có tích xanh, 1,240 upvotes, đăng 10/2024 còn mới, bình luận còn xác nhận chạy được trên windows 11. câu b không tích xanh, -2 upvotes, đăng từ 2012, bình luận còn cảnh báo làm hỏng mạng lan.

2. công nghệ đổi rất nhanh, cách cũ có thể không hợp phiên bản mới. áp dụng cách 12 năm trước trên windows 11 có thể làm mất kết nối mạng lan, hỏng hyper-v, làm trạm kiosk không chạy được.

## phần 2

3. bỏ qua phần mô tả câu hỏi dài, cuộn xuống phần answers, tìm câu có tích xanh hoặc upvotes cao nhất, đọc code trong khung màu xám. ở câu a thì chạy netstat -ano | findstr :8080 để tìm PID, rồi taskkill /PID <PID> /F để tắt tiến trình chiếm cổng.

4. nên xem trạng thái OPEN vì lỗi mới chưa được sửa. workaround là cách sửa tạm để chạy được trong lúc chờ nhà sản xuất ra bản sửa chính thức. workaround uy tín là comment có nhiều reactions 👍 ❤️, của người có xác nhận đã chạy được hoặc của người duy trì dự án (maintainer).
