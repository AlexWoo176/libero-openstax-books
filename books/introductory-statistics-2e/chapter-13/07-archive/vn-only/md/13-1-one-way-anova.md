## 13.1
 
Phân tích phương sai một chiều

Mục đích của kiểm định phân tích phương sai một chiều (ANOVA) là xác định sự tồn tại của một khác biệt có ý nghĩa thống kê giữa các số trung bình của nhiều nhóm. Kiểm định này thực tế sử dụng phương sai để giúp xác định xem các số trung bình có bằng nhau hay không. Để thực hiện kiểm định ANOVA một chiều, cần phải thỏa mãn năm **giả định** cơ bản:

1. Mỗi quần thể mà từ đó một mẫu được lấy ra được giả định là có phân phối chuẩn.
1. Tất cả các mẫu đều được chọn ngẫu nhiên và độc lập.
1. Các quần thể được giả định là có các độ lệch chuẩn bằng nhau **(hoặc các phương sai bằng nhau)**.
1. Nhân tố là một biến phân loại.
1. Biến phản hồi là một biến định lượng.
### Giả thuyết không và đối thuyết

Giả thuyết không đơn giản là tất cả các số trung bình quần thể của các nhóm đều bằng nhau. Đối thuyết là có ít nhất một cặp số trung bình khác nhau. Ví dụ, nếu có *k* nhóm:

*H_0*: *μ*_1 = *μ*_2 = *μ*_3 = ... = *μ_k*

*H_a*: Ít nhất hai trong số các số trung bình nhóm *μ*_1, *μ*_2, *μ*_3, ..., *μ_k* không bằng nhau. Nghĩa là, *μ_i* ≠ *μ_j* với một số *i* ≠ *j*.

Các biểu đồ, một tập hợp các biểu đồ hộp đại diện cho sự phân phối của các giá trị với các số trung bình nhóm được biểu thị bằng một đường nằm ngang xuyên qua hộp, giúp hiểu rõ hơn về kiểm định giả thuyết. Trong biểu đồ đầu tiên (các biểu đồ hộp màu xanh dương), *H_0*: *μ_1* = *μ_2* = *μ_3* và ba quần thể có cùng sự phân phối nếu giả thuyết không là đúng. Phương sai của dữ liệu kết hợp xấp xỉ bằng phương sai của từng quần thể.

Nếu giả thuyết không sai, thì phương sai của dữ liệu kết hợp sẽ lớn hơn, điều này gây ra bởi các số trung bình khác nhau như được hiển thị trong biểu đồ thứ hai (các biểu đồ hộp màu xanh lá cây).

*Hình 
13.2
 
(a) *H_0* là đúng. Tất cả các số trung bình đều bằng nhau; các khác biệt là do sự biến thiên ngẫu nhiên. (b) *H_0* là không đúng. Các số trung bình không hoàn toàn bằng nhau; các khác biệt quá lớn để có thể là do sự biến thiên ngẫu nhiên.*
