# -Exercise--Invalid_number_notification
[Bài tập] Hiển thị thông báo nếu người dùng nhập số bất hợp lệ
Mục tiêu
Luyện tập sử dụng try-catch để xử lý ngoại lệ.

Mô tả
Viết một ứng dụng máy tính đơn giản, cho phép thực hiện các phép Cộng, Trừ, Nhân, Chia.

Ứng dụng hiển thị thông báo nếu người dùng nhập số bất hợp lệ.

Hướng dẫn
Bước 1: Tạo phương thức calc

Tạo phương thức calc với đầu vào là 2 số nguyên x và y. In ra kết quả Cộng, Trừ, Nhân, Chia.

Khi y = 0 hoặc x=y=0 sẽ xuất hiện thông báo lỗi ngoại lệ.

Bước 2: Xây dựng mẫu account hợp lệ

x=5, y=5;
x=0, y=1
Bước 3: Xây dựng mẫu account không hợp lệ

y=0;
x=0, y=0;
Bước 4: Chạy chương trình và kiểm tra kết quả

※Với x= 5, y=5;

Tổng x + y = 10

Hiệu x - y = 0

Tích x * y = 25

Thương x / y = 1

※ Với x = 0, y = 1;

Tổng x + y = 1

Hiệu x - y = -1

Tích x * y = 0

Thương x / y = 0

※ Với y = 0 hoặc x=y=0;

Xảy ra ngoại lệ: / by zero