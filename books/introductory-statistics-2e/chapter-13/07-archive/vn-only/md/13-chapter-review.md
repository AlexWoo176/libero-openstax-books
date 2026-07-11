## Câu hỏi ôn tập chương

Phân tích phương sai mở rộng việc so sánh hai nhóm thành nhiều nhóm, mỗi nhóm là một mức của một biến phân loại (nhân tố). Các mẫu từ mỗi nhóm là độc lập và phải được chọn ngẫu nhiên từ các quần thể có phân phối chuẩn với các phương sai bằng nhau. Chúng ta kiểm định giả thuyết không về sự bằng nhau của các giá trị trung bình của biến phản hồi trong mọi nhóm so với đối thuyết rằng một hoặc nhiều giá trị trung bình nhóm khác biệt với các nhóm còn lại. Một kiểm định giả thuyết phân tích phương sai một chiều xác định xem liệu nhiều giá trị trung bình quần thể có bằng nhau hay không. Phân phối cho kiểm định này là phân phối *F* với hai bậc tự do khác nhau.

1. Mỗi quần thể mà từ đó một mẫu được lấy ra được giả định là có phân phối chuẩn.
1. Tất cả các mẫu đều được chọn ngẫu nhiên và độc lập.
1. Các quần thể được giả định là có các độ lệch chuẩn (hoặc phương sai) bằng nhau.
Phân tích phương sai so sánh các giá trị trung bình của một biến phản hồi cho nhiều nhóm. ANOVA so sánh sự biến thiên trong nội bộ mỗi nhóm với sự biến thiên của giá trị trung bình của mỗi nhóm. Tỷ số của hai giá trị này là trị thống kê *F* từ một phân phối *F* với (số lượng nhóm – 1) là bậc tự do của tử số và (số lượng quan sát – số lượng nhóm) là bậc tự do của mẫu số. Các trị thống kê này được tóm tắt trong bảng ANOVA.

Đồ thị của phân phối *F* luôn dương và bị lệch phải, mặc dù hình dạng có thể là dạng gò hoặc dạng mũ tùy thuộc vào sự kết hợp của bậc tự do tử số và mẫu số. Trị thống kê *F* là tỷ số của một thước đo sự biến thiên trong các giá trị trung bình nhóm so với một thước đo tương tự về sự biến thiên trong nội bộ các nhóm. Nếu giả thuyết không là đúng, thì tử số sẽ nhỏ so với mẫu số. Kết quả sẽ là một trị thống kê *F* nhỏ, và diện tích dưới đường cong *F* về phía bên phải sẽ lớn, đại diện cho một p-giá trị *p* lớn. Khi giả thuyết không về các giá trị trung bình nhóm bằng nhau là sai, thì tử số sẽ lớn so với mẫu số, tạo ra một trị thống kê *F* lớn và một diện tích nhỏ (p-giá trị *p* nhỏ) về phía bên phải của trị thống kê dưới đường cong *F*.

Khi dữ liệu có kích thước nhóm không bằng nhau (dữ liệu không cân bằng), thì các kỹ thuật từ [13.2 Phân phối F và Tỷ số F](13-2-the-f-distribution-and-the-f-ratio) cần được sử dụng cho các tính toán thủ công. Tuy nhiên, trong trường hợp dữ liệu cân bằng (các nhóm có cùng kích thước), các tính toán đơn giản dựa trên giá trị trung bình và phương sai nhóm có thể được sử dụng. Tất nhiên, trong thực tế, phần mềm thường được sử dụng trong phân tích. Như trong bất kỳ phân tích nào, các loại đồ thị khác nhau nên được sử dụng kết hợp với các kỹ thuật số học. Luôn luôn quan sát dữ liệu của bạn!

Kiểm định *F* cho sự bằng nhau của hai phương sai dựa nhiều vào giả định về các phân phối chuẩn. Kiểm định này không đáng tin cậy nếu giả định này không được đáp ứng. Nếu cả hai phân phối đều là chuẩn, thì tỷ số của hai phương sai mẫu được phân phối như một trị thống kê *F*, với bậc tự do tử số và mẫu số ít hơn một so với kích thước mẫu của hai nhóm tương ứng. Một kiểm định giả thuyết **kiểm định hai phương sai** xác định xem liệu hai phương sai có bằng nhau hay không. Phân phối cho kiểm định giả thuyết này là phân phối *F* với hai bậc tự do khác nhau.

1. Các quần thể mà từ đó hai mẫu được rút ra có phân phối chuẩn.
1. Hai quần thể độc lập với nhau.
