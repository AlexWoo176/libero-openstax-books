*Hình 
5.1
 
Chiều cao của những cây củ cải này là các biến ngẫu nhiên liên tục. (nguồn: sửa đổi từ tác phẩm “Củ cải (Raphanus sativus): Bệnh gỉ trắng do Albugo candida gây ra” bởi Scot Nelson/ Flickr, Phạm vi công cộng)*

Đến cuối chương này, sinh viên sẽ có thể:

- Nhận biết và hiểu các hàm mật độ xác suất liên tục nói chung.
- Nhận biết phân phối xác suất đều và áp dụng nó một cách thích hợp.
- Nhận biết phân phối xác suất mũ và áp dụng nó một cách thích hợp.
## Giới thiệu

Các biến ngẫu nhiên liên tục có nhiều ứng dụng. Số trung bình lượt đánh bóng trong môn bóng chày, điểm IQ, khoảng thời gian của một cuộc gọi đường dài, số tiền một người mang theo, khoảng thời gian hoạt động của một con chip máy tính và điểm SAT chỉ là một vài ví dụ. Lĩnh vực độ tin cậy phụ thuộc vào nhiều loại biến ngẫu nhiên liên tục khác nhau.

Các giá trị của biến ngẫu nhiên rời rạc và liên tục có thể gây nhầm lẫn. Ví dụ, nếu *X* bằng số dặm (làm tròn đến dặm gần nhất) bạn lái xe đi làm, thì *X* là một biến ngẫu nhiên rời rạc. Bạn đếm số dặm. Nếu *X* là khoảng cách bạn lái xe đi làm, thì bạn đo các giá trị của *X* và *X* là một biến ngẫu nhiên liên tục. Ví dụ thứ hai, nếu *X* bằng số lượng sách trong ba lô, thì *X* là một biến ngẫu nhiên rời rạc. Nếu *X* là trọng lượng của một cuốn sách, thì *X* là một biến ngẫu nhiên liên tục vì trọng lượng được đo lường. Cách xác định biến ngẫu nhiên là rất quan trọng.

### Các tính chất của phân phối xác suất liên tục

Đồ thị của một phân phối xác suất liên tục là một đường cong. Xác suất được biểu diễn bằng diện tích dưới đường cong đó.

Đường cong này được gọi là Hàm mật độ xác suất (viết tắt là **pdf**). Chúng ta sử dụng ký hiệu *f*(*x*) để biểu diễn đường cong này. *f*(*x*) là hàm số tương ứng với đồ thị; chúng ta sử dụng hàm mật độ *f*(*x*) để vẽ đồ thị của phân phối xác suất.

**Diện tích dưới đường cong** được cho bởi một hàm số khác gọi là **hàm phân phối tích lũy** (viết tắt là **cdf**). Hàm phân phối tích lũy được sử dụng để đánh giá xác suất dưới dạng diện tích.

- Các kết quả được đo lường, không phải đếm.
- Toàn bộ diện tích bên dưới đường cong và phía trên trục x bằng một.
- Xác suất được tìm thấy cho các khoảng của các giá trị *x* thay vì cho các giá trị *x* riêng lẻ.
- *P(c < x < d)* là xác suất mà biến ngẫu nhiên *X* nằm trong khoảng giữa các giá trị *c* và *d*. *P(c < x < d)* là diện tích bên dưới đường cong, phía trên trục *x*, nằm bên phải *c* và bên trái *d*.
- *P(x = c) =* 0 Xác suất để *x* nhận bất kỳ giá trị riêng lẻ nào bằng không. Diện tích bên dưới đường cong, phía trên trục *x*, và giữa *x* = *c* và *x* = *c* không có chiều rộng, và do đó không có diện tích (diện tích = 0). Vì xác suất bằng với diện tích, nên xác suất cũng bằng không.
- *P(c < x < d)* cũng giống như *P(c ≤ x ≤ d)* vì xác suất bằng với diện tích.
Chúng ta sẽ tìm diện tích biểu diễn xác suất bằng cách sử dụng hình học, công thức, công nghệ hoặc bảng xác suất. Nhìn chung, cần phải có giải tích để tìm diện tích dưới đường cong cho nhiều hàm mật độ xác suất. Khi chúng ta sử dụng các công thức để tìm diện tích trong giáo trình này, các công thức đó đã được tìm ra bằng cách sử dụng các kỹ thuật của giải tích tích phân. Tuy nhiên, vì hầu hết sinh viên theo học khóa học này chưa học giải tích, chúng ta sẽ không sử dụng giải tích trong giáo trình này.

Có rất nhiều phân phối xác suất liên tục. Khi sử dụng một phân phối xác suất liên tục để mô hình hóa xác suất, phân phối được chọn phải phù hợp để mô hình hóa và khớp với tình huống cụ thể theo cách tốt nhất.

Trong chương này và chương tiếp theo, chúng ta sẽ nghiên cứu phân phối đều, phân phối mũ và phân phối chuẩn. Các đồ thị sau đây minh họa các phân phối này.

*Hình 
5.2
 
Biểu đồ hiển thị Phân phối đều với diện tích giữa *x* = 3 và *x* = 6 được tô bóng để biểu thị xác suất mà giá trị của biến ngẫu nhiên *X* nằm trong khoảng từ ba đến sáu.*

*Hình 
5.3
 
Biểu đồ hiển thị Phân phối mũ với diện tích giữa *x* = 2 và *x* = 4 được tô bóng để biểu thị xác suất mà giá trị của biến ngẫu nhiên *X* nằm trong khoảng từ hai đến bốn.*

*Hình 
5.4
 
Biểu đồ hiển thị Phân phối chuẩn tắc với diện tích giữa *x* = 1 và *x* = 2 được tô bóng để biểu thị xác suất mà giá trị của biến ngẫu nhiên *X* nằm trong khoảng từ một đến hai.*
