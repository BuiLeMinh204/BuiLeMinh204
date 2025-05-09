# Chào mừng bạn đến với blog của mình
mình là Bùi Lê Minh - sinh viên khoa CNTT đại học Phenikaa
# Đề tài thư viện Celery
## Mục đích chính của thư viện Celery
Celery được thiết kế để xử lý các tác vụ bất đồng bộ (asynchronous tasks) và tác vụ nền (background jobs) trong ứng dụng Python. Cụ thể, các mục tiêu chính gồm:
### Tăng hiệu năng ứng dụng
Tách các công việc nặng hoặc chậm (ví dụ: gửi email, xử lý ảnh, phân tích dữ liệu, truy cập API) ra khỏi luồng xử lý chính. Giúp giao diện web phản hồi nhanh hơn, không bị chặn trong khi chờ các tác vụ đó hoàn thành.
### Hỗ trợ xử lý bất đồng bộ
Cho phép bạn gửi một công việc vào hàng đợi để xử lý sau mà không cần đợi nó hoàn tất.
### Xử lý phân tán và mở rộng
Có thể chạy nhiều worker trên nhiều máy chủ. Dễ dàng mở rộng quy mô nếu lượng công việc tăng.
### Giám sát và kiểm soát công việc
Hỗ trợ theo dõi trạng thái task, retry khi lỗi, timeout, ưu tiên task, v.v. Có thể kết hợp với Flower để có giao diện giám sát trực quan.

## Celery giải quyết vấn đề gì?
Celery được dùng để xử lý tác vụ bất đồng bộ và định kỳ, đặc biệt hữu ích khi:


git add .
git commit -m "update"
git push
