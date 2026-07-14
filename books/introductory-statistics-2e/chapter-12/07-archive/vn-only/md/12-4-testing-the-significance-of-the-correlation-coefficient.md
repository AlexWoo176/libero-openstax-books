## 12.4
 
Kiểm định ý nghĩa của hệ số tương quan

Hệ số tương quan, *r*, cho chúng ta biết về độ mạnh và hướng của mối quan hệ tuyến tính giữa *x* và *y*. Tuy nhiên, độ tin cậy của mô hình tuyến tính cũng phụ thuộc vào số lượng điểm dữ liệu quan sát được trong mẫu. Chúng ta cần xem xét cả giá trị của hệ số tương quan *r* và kích thước mẫu *n* cùng nhau.

Chúng ta thực hiện kiểm định giả thuyết về **"ý nghĩa của hệ số tương quan"** để quyết định xem liệu mối quan hệ tuyến tính trong dữ liệu mẫu có đủ mạnh để sử dụng làm mô hình cho mối quan hệ trong quần thể hay không.

Dữ liệu mẫu được sử dụng để tính toán *r*, hệ số tương quan cho mẫu. Nếu chúng ta có dữ liệu cho toàn bộ quần thể, chúng ta có thể tìm được hệ số tương quan quần thể. Nhưng vì chúng ta chỉ có dữ liệu mẫu, chúng ta không thể tính toán hệ số tương quan quần thể. Hệ số tương quan mẫu, *r*, là ước lượng của chúng ta về hệ số tương quan quần thể chưa biết.

- Ký hiệu cho hệ số tương quan quần thể là *ρ*, chữ cái Hy Lạp "rho."
- *ρ* = hệ số tương quan quần thể (chưa biết)
- *r* = hệ số tương quan mẫu (đã biết; được tính từ dữ liệu mẫu)
Kiểm định giả thuyết cho phép chúng ta quyết định xem giá trị của hệ số tương quan quần thể *ρ* là "gần bằng không" hay "khác biệt đáng kể so với không". Chúng ta quyết định điều này dựa trên hệ số tương quan mẫu *r* và kích thước mẫu *n*.

Nếu kiểm định kết luận rằng hệ số tương quan khác biệt đáng kể so với không, chúng ta nói rằng hệ số tương quan là "có ý nghĩa".

- Kết luận: Có đủ bằng chứng để kết luận rằng có một mối quan hệ tuyến tính đáng kể giữa *x* và *y* vì hệ số tương quan khác biệt đáng kể so với không.
- Ý nghĩa của kết luận: Có một mối quan hệ tuyến tính đáng kể giữa *x* và *y*. Chúng ta có thể sử dụng đường hồi quy để mô hình hóa mối quan hệ tuyến tính giữa *x* và *y* trong quần thể.
Nếu kiểm định kết luận rằng hệ số tương quan không khác biệt đáng kể so với không (nó gần bằng không), chúng ta nói rằng hệ số tương quan là "không có ý nghĩa".

- Kết luận: "Không có đủ bằng chứng để kết luận rằng có một mối quan hệ tuyến tính đáng kể giữa *x* và *y* vì hệ số tương quan không khác biệt đáng kể so với không."
- Ý nghĩa của kết luận: Không có mối quan hệ tuyến tính đáng kể giữa *x* và *y*. Do đó, chúng ta KHÔNG THỂ sử dụng đường hồi quy để mô hình hóa mối quan hệ tuyến tính giữa *x* và *y* trong quần thể.
- Nếu *r* có ý nghĩa và biểu đồ phân tán cho thấy xu hướng tuyến tính, đường này có thể được sử dụng để dự đoán giá trị của *y* đối với các giá trị của *x* nằm trong miền của các giá trị *x* đã quan sát được.
- Nếu *r* không có ý nghĩa HOẶC nếu biểu đồ phân tán không cho thấy xu hướng tuyến tính, thì không nên sử dụng đường này để dự đoán.
- Nếu *r* có ý nghĩa và nếu biểu đồ phân tán cho thấy xu hướng tuyến tính, đường này có thể KHÔNG phù hợp hoặc không đáng tin cậy để dự đoán BÊN NGOÀI miền của các giá trị *x* đã quan sát được trong dữ liệu.
### THỰC HIỆN KIỂM ĐỊNH GIẢ THUYẾT

- ** Giả thuyết không: *H_0*: *ρ* = 0 **
- **Đối thuyết: *H_a*: *ρ* ≠ 0**
Ý NGHĨA CỦA CÁC GIẢ THUYẾT BẰNG LỜI:

- **Giả thuyết không *H_0*:** Hệ số tương quan quần thể KHÔNG khác biệt đáng kể so với không. KHÔNG CÓ mối quan hệ tuyến tính (tương quan) đáng kể giữa *x* và *y* trong quần thể.
- **Đối thuyết *H_a*:** Hệ số tương quan quần thể KHÁC BIỆT ĐÁNG KỂ so với không. CÓ MỘT MỐI QUAN HỆ TUYẾN TÍNH ĐÁNG KỂ (tương quan) giữa *x* và *y* trong quần thể.
RÚT RA KẾT LUẬN:Có hai phương pháp để đưa ra quyết định. Hai phương pháp này tương đương nhau và cho cùng một kết quả.

- **Phương pháp 1: Sử dụng p-giá trị *p***
- **Phương pháp 2: Sử dụng bảng các giá trị tới hạn**
Trong chương này của cuốn sách, chúng ta sẽ luôn sử dụng mức ý nghĩa 5%, *α* = 0,05

Sử dụng phương pháp *p*-giá trị, bạn có thể chọn bất kỳ mức ý nghĩa phù hợp nào bạn muốn; bạn không bị giới hạn trong việc sử dụng *α* = 0,05. Nhưng bảng các giá trị tới hạn được cung cấp trong cuốn sách này giả định rằng chúng ta đang sử dụng mức ý nghĩa 5%, *α* = 0,05. (Nếu chúng ta muốn sử dụng một mức ý nghĩa khác 5% với phương pháp giá trị tới hạn, chúng ta sẽ cần các bảng giá trị tới hạn khác không được cung cấp trong cuốn sách này.)

#### PHƯƠNG PHÁP 1: Sử dụng *p*-giá trị để đưa ra quyết định

Để tính *p*-giá trị sử dụng `LinRegTTEST`:

Trên màn hình nhập liệu `LinRegTTEST`, tại dòng nhắc cho *β* hoặc *ρ*, hãy làm nổi bật "**≠ 0**"

Màn hình kết quả hiển thị p-value trên dòng ghi "p =".

(Hầu hết các phần mềm thống kê máy tính đều có thể tính được *p*-giá trị.)

- Quyết định: Bác bỏ giả thuyết không.
- Kết luận: "Có đủ bằng chứng để kết luận rằng có một mối quan hệ tuyến tính đáng kể giữa *x* và *y* vì hệ số tương quan khác biệt đáng kể so với không."
- Quyết định: KHÔNG BÁC BỎ giả thuyết không.
- Kết luận: "Không có đủ bằng chứng để kết luận rằng có một mối quan hệ tuyến tính đáng kể giữa *x* và *y* vì hệ số tương quan KHÔNG khác biệt đáng kể so với không."
- Bạn sẽ sử dụng công nghệ để tính toán p-giá trị *p*. Phần sau đây mô tả các phép tính để tính toán các thống kê kiểm định và p-giá trị *p*:
- p-giá trị *p* được tính toán bằng cách sử dụng phân phối *t* với *n* - 2 bậc tự do.
- Công thức cho thống kê kiểm định là 

t=

r

n−2

1−
r
2

t=

r

n−2

1−
r
2

. Giá trị của thống kê kiểm định, *t*, được hiển thị trong kết quả đầu ra của máy tính hoặc phần mềm cùng với p-giá trị *p*. Thống kê kiểm định *t* có cùng dấu với hệ số tương quan *r*.
- p-giá trị *p* là tổng diện tích ở cả hai đuôi.
Một cách thay thế để tính *p*-giá trị **(p)** được đưa ra bởi LinRegTTest là lệnh 2*tcdf(abs(t),10^99, n-2) trong 2nd DISTR.

- Hãy xem xét [ví dụ về bài thi thứ ba/bài thi cuối kỳ](12-3-the-regression-equation).
- Đường phù hợp nhất là: ŷ = -173,51 + 4,83*x* với *r* = 0,6631 và có *n* = 11 điểm dữ liệu.
- Đường hồi quy có thể được sử dụng để dự đoán không? **Với điểm bài thi thứ ba (giá trị *x*), chúng ta có thể sử dụng đường này để dự đoán điểm bài thi cuối kỳ (giá trị *y* được dự đoán) không?**
*H_0*: *ρ* = 0

*H_a*: *ρ* ≠ 0

*α* = 0,05

- p-giá trị *p* là 0,026 (từ LinRegTTest trên máy tính của bạn hoặc từ phần mềm máy tính).
- p-giá trị *p*, 0,026, nhỏ hơn mức ý nghĩa *α* = 0,05.
- Quyết định: Bác bỏ Giả thuyết không *H_0*
- Kết luận: Có đủ bằng chứng để kết luận rằng có một mối quan hệ tuyến tính đáng kể giữa điểm bài thi thứ ba (*x*) và điểm bài thi cuối kỳ (*y*) vì hệ số tương quan khác biệt đáng kể so với không.
**Vì *r* có ý nghĩa và biểu đồ phân tán cho thấy xu hướng tuyến tính, đường hồi quy có thể được sử dụng để dự đoán điểm thi cuối kỳ.**

#### PHƯƠNG PHÁP 2: Sử dụng bảng Giá trị tới hạn để đưa ra quyết định

Bảng [Giá trị tới hạn 95% của Hệ số tương quan mẫu](12-6-outliers) có thể được sử dụng để giúp bạn có ý tưởng tốt về việc liệu giá trị tính toán được của **rr có ý nghĩa hay không**. So sánh *r* với giá trị tới hạn thích hợp trong bảng. Nếu *r* không nằm giữa các giá trị tới hạn dương và âm, thì hệ số tương quan là có ý nghĩa. Nếu *r* có ý nghĩa, thì bạn có thể muốn sử dụng đường thẳng để dự đoán.

Giả sử bạn đã tính được *r* = 0,801 sử dụng *n* = 10 điểm dữ liệu. *df* = *n* - 2 = 10 - 2 = 8. Các giá trị tới hạn liên quan đến *df* = 8 là -0,632 và + 0,632. Nếu *r* < giá trị tới hạn âm hoặc *r* > giá trị tới hạn dương, thì *r* là có ý nghĩa. Vì *r* = 0,801 và 0,801 > 0,632, *r* là có ý nghĩa và đường thẳng có thể được sử dụng để dự đoán. Nếu bạn xem ví dụ này trên một trục số, nó sẽ giúp ích cho bạn.

*Hình 
12.16
 
*r* không có ý nghĩa giữa -0,632 và +0,632. *r* = 0,801 > +0,632. Do đó, *r* có ý nghĩa.*

Đối với một đường phù hợp nhất đã cho, bạn tính được *r* = 0,6501 sử dụng *n* = 12 điểm dữ liệu và giá trị tới hạn là 0,576. Đường thẳng có thể được sử dụng để dự đoán không? Tại sao có hoặc tại sao không?

Giả sử bạn đã tính được *r* = –0,624 với 14 điểm dữ liệu. *df* = 14 – 2 = 12. Các giá trị tới hạn là –0,532 và 0,532. Vì –0,624 < –0,532, *r* là có ý nghĩa và đường thẳng có thể được sử dụng để dự đoán

*Hình 
12.17
 
r = –0,624 < -0,532. Do đó, *r* có ý nghĩa.*

Đối với một đường phù hợp nhất đã cho, bạn tính được *r* = 0,5204 sử dụng *n* = 9 điểm dữ liệu, và giá trị tới hạn là 0,666. Đường thẳng có thể được sử dụng để dự đoán không? Tại sao có hoặc tại sao không?

Giả sử bạn đã tính được *r* = 0,776 và *n* = 6. *df* = 6 – 2 = 4. Các giá trị tới hạn là –0,811 và 0,811. Vì –0,811 < 0,776 < 0,811, *r* không có ý nghĩa, và đường thẳng không nên được sử dụng để dự đoán.

*Hình 
12.18
 
-0,811 < *r* = 0,776 < 0,811. Do đó, *r* không có ý nghĩa.*

Đối với một đường phù hợp nhất đã cho, bạn tính được *r* = –0,7204 sử dụng *n* = 8 điểm dữ liệu, và giá trị tới hạn là = 0,707. Đường thẳng có thể được sử dụng để dự đoán không? Tại sao có hoặc tại sao không?

### VÍ DỤ KỲ THI THỨ BA vs KỲ THI CUỐI KỲ: phương pháp giá trị tới hạn

Hãy xem xét [ví dụ về kỳ thi thứ ba/kỳ thi cuối kỳ](12-3-the-regression-equation).
Đường phù hợp nhất là: *ŷ* = –173,51+4,83*x* với *r* = 0,6631 và có *n* = 11 điểm dữ liệu. Đường hồi quy có thể được sử dụng để dự đoán không? **Với điểm thi thứ ba (giá trị *x*), chúng ta có thể sử dụng đường thẳng để dự đoán điểm thi cuối kỳ (giá trị *y* được dự đoán) không?**

- *H_0*: *ρ* = 0
- *H_a*: *ρ* ≠ 0
- *α* = 0,05
- Sử dụng bảng "Giá trị tới hạn 95%" cho *r* với *df* = *n* – 2 = 11 – 2 = 9.
- Các giá trị tới hạn là –0,602 và +0,602
- Vì 0,6631 > 0,602, *r* có ý nghĩa.
- Quyết định: Bác bỏ giả thuyết không.
- Kết luận: Có đủ bằng chứng để kết luận rằng có một mối quan hệ tuyến tính đáng kể giữa điểm bài thi thứ ba (*x*) và điểm bài thi cuối kỳ (*y*) vì hệ số tương quan khác biệt đáng kể so với không.
**Vì *r* có ý nghĩa và biểu đồ phân tán cho thấy xu hướng tuyến tính, đường hồi quy có thể được sử dụng để dự đoán điểm thi cuối kỳ.**

Giả sử bạn đã tính được các hệ số tương quan sau đây. Sử dụng bảng ở cuối chương, hãy xác định xem *r* có ý nghĩa hay không và đường phù hợp nhất liên quan đến mỗi *r* có thể được sử dụng để dự đoán giá trị *y* hay không. Nếu cần, hãy vẽ một trục số.

1. *r* = –0,567 và kích thước mẫu, *n*, là 19. *df* = *n* – 2 = 17. Giá trị tới hạn là –0,456. –0,567 < –0,456 nên *r* có ý nghĩa.
1. *r* = 0,708 và kích thước mẫu, *n*, là chín. *df* = *n* – 2 = 7. Giá trị tới hạn là 0,666. 0,708 > 0,666 nên *r* có ý nghĩa.
1. *r* = 0,134 và kích thước mẫu, *n*, là 14. *df* = 14 – 2 = 12. Giá trị tới hạn là 0,532. 0,134 nằm giữa –0,532 và 0,532 nên *r* không có ý nghĩa.
1. *r* = 0 và kích thước mẫu, *n*, là năm. Bất kể bậc tự do là bao nhiêu, *r* = 0 nằm giữa hai giá trị tới hạn nên *r* không có ý nghĩa.
Đối với một đường phù hợp nhất đã cho, bạn tính được *r* = 0 sử dụng *n* = 100 điểm dữ liệu. Đường thẳng có thể được sử dụng để dự đoán không? Tại sao có hoặc tại sao không?

### Các giả định trong kiểm định ý nghĩa của hệ số tương quan

Kiểm định ý nghĩa của hệ số tương quan đòi hỏi một số giả định nhất định về dữ liệu phải được thỏa mãn. Tiền đề của kiểm định này là dữ liệu là một mẫu các điểm quan sát được lấy từ một quần thể lớn hơn. Chúng ta chưa kiểm tra toàn bộ quần thể vì điều đó không thể hoặc không khả thi. Chúng ta đang kiểm tra mẫu để rút ra kết luận về việc liệu mối quan hệ tuyến tính mà chúng ta thấy giữa *x* và *y* trong dữ liệu mẫu có cung cấp bằng chứng đủ mạnh để chúng ta có thể kết luận rằng có một mối quan hệ tuyến tính giữa *x* và *y* trong quần thể hay không.

Phương trình đường hồi quy mà chúng ta tính toán từ dữ liệu mẫu đưa ra đường phù hợp nhất cho mẫu cụ thể của chúng ta. Chúng ta muốn sử dụng đường phù hợp nhất này cho mẫu như một ước lượng cho đường phù hợp nhất cho quần thể. Việc kiểm tra biểu đồ phân tán và kiểm định ý nghĩa của hệ số tương quan giúp chúng ta xác định xem liệu có phù hợp để làm điều này hay không.

- Mối quan hệ giữa các biến đang được tương quan nên là tuyến tính. Các điểm dữ liệu nên nằm dọc theo một mô hình đường thẳng xấp xỉ khi được vẽ dưới dạng các điểm dữ liệu (*x*, *y*) trên biểu đồ phân tán.
- Các giá trị *y* cho bất kỳ giá trị *x* cụ thể nào đều được phân phối chuẩn quanh đường thẳng. Điều này ngụ ý rằng có nhiều giá trị *y* nằm gần đường thẳng hơn là nằm xa hơn. Giả định (1) ngụ ý rằng các phân phối chuẩn này tập trung trên đường thẳng: số trung bình của các phân phối chuẩn này của các giá trị *y* nằm trên đường thẳng.
- Các độ lệch chuẩn của các giá trị *y* quần thể quanh đường thẳng là bằng nhau cho mỗi giá trị của *x*. Nói cách khác, mỗi phân phối chuẩn này của các giá trị *y* đều có cùng hình dạng và độ phân tán quanh đường thẳng.
- Các sai số phần dư độc lập với nhau (không có mô hình).
- Dữ liệu được tạo ra từ một mẫu ngẫu nhiên hoặc thực nghiệm ngẫu nhiên được thiết kế tốt.
*Hình 
12.19
 
Các giá trị *y* cho mỗi giá trị *x* được phân phối chuẩn quanh đường thẳng với cùng độ lệch chuẩn. Đối với mỗi giá trị *x*, số trung bình của các giá trị *y* nằm trên đường hồi quy. Nhiều giá trị *y* nằm gần đường thẳng hơn là nằm xa đường thẳng hơn.*
