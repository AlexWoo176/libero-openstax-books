## 8.2
 
Số trung bình của một quần thể sử dụng phân phối Student t

Trong thực tế, chúng ta hiếm khi biết Độ lệch chuẩn của quần thể. Trước đây, khi kích thước mẫu lớn, điều này không gây khó khăn cho các nhà thống kê. Họ sử dụng độ lệch chuẩn mẫu *s* làm ước lượng cho *σ* và tiến hành tính toán Khoảng tin cậy như trước với kết quả đủ gần. Tuy nhiên, các nhà thống kê gặp vấn đề khi kích thước mẫu nhỏ. Kích thước mẫu nhỏ gây ra sự thiếu chính xác trong khoảng tin cậy.

William S. Gosset (1876–1937) làm việc tại nhà máy bia Guinness ở Dublin, Ireland đã gặp phải vấn đề này. Các thí nghiệm của ông với hoa bia và lúa mạch tạo ra rất ít mẫu. Việc chỉ thay thế *σ* bằng *s* không mang lại kết quả chính xác khi ông cố gắng tính toán khoảng tin cậy. Ông nhận ra rằng mình không thể sử dụng phân phối chuẩn cho việc tính toán; ông phát hiện ra rằng phân phối thực tế phụ thuộc vào kích thước mẫu. Vấn đề này đã dẫn ông đến việc "khám phá" ra cái gọi là Phân phối Student (phân phối t). Tên gọi này xuất phát từ việc Gosset viết dưới bút danh "Student".

Cho đến giữa những năm 1970, một số nhà thống kê đã sử dụng phép xấp xỉ Phân phối chuẩn cho các kích thước mẫu lớn và chỉ sử dụng phân phối Student's t cho các kích thước mẫu tối đa là 30. Với máy tính cầm tay đồ họa và máy tính cá nhân, thực tế hiện nay là sử dụng phân phối Student's t bất cứ khi nào *s* được sử dụng làm ước lượng cho *σ*.

Nếu bạn lấy một mẫu ngẫu nhiên đơn giản có kích thước *n* từ một quần thể có phân phối xấp xỉ chuẩn với số trung bình *μ* và độ lệch chuẩn quần thể chưa biết *σ*, sau đó tính điểm *t* theo công thức *t* = 

x
¯

–μ

(

s

n

)

x
¯

–μ

(

s

n

)

, thì các điểm *t* sẽ tuân theo **phân phối Student's t với *n* – 1 bậc tự do**. Điểm *t* có cùng cách diễn giải như Điểm chuẩn z (z-score). Nó đo lường khoảng cách từ 

x
¯

x
¯
 đến số trung bình *μ* của nó. Với mỗi kích thước mẫu *n*, sẽ có một phân phối Student's t khác nhau.

Bậc tự do, ***n* – 1**, xuất phát từ việc tính toán độ lệch chuẩn mẫu ***s***. Phép tính này yêu cầu *n* độ lệch 

(x–
x
¯

 values)

(x–
x
¯

 values)
. Vì tổng các độ lệch bằng không, chúng ta có thể tìm độ lệch cuối cùng khi đã biết ***n* – 1** độ lệch còn lại. ***n* – 1** độ lệch còn lại có thể thay đổi hoặc biến thiên tự do. **Chúng ta gọi số *n* – 1 là bậc tự do (df).**

- Đồ thị cho phân phối t của Student tương tự như đường cong chuẩn tắc.
- Số trung bình cho phân phối t của Student là bằng không và phân phối này đối xứng qua không.
- Phân phối t của Student có nhiều xác suất hơn ở các đuôi so với phân phối chuẩn tắc vì độ phân tán của phân phối t lớn hơn độ phân tán của phân phối chuẩn tắc. Vì vậy, đồ thị của phân phối t của Student sẽ dày hơn ở các đuôi và thấp hơn ở trung tâm so với đồ thị của phân phối chuẩn tắc.
- Hình dạng chính xác của phân phối t của Student phụ thuộc vào bậc tự do. Khi bậc tự do tăng lên, đồ thị của phân phối t của Student trở nên giống với đồ thị của phân phối chuẩn tắc hơn.
- Quần thể gốc của các quan sát cá biệt được giả định là phân phối chuẩn với số trung bình quần thể *μ* chưa biết và độ lệch chuẩn quần thể *σ* chưa biết. Kích thước của quần thể gốc thường không liên quan trừ khi nó rất nhỏ. Nếu nó có hình chuông (chuẩn) thì giả định đã được đáp ứng và không cần thảo luận thêm. Lấy mẫu ngẫu nhiên được giả định, nhưng đó là một giả định hoàn toàn tách biệt với tính chuẩn tắc.
Máy tính và máy tính cá nhân có thể dễ dàng tính toán bất kỳ xác suất Student's t nào. Các dòng TI-83, 83+ và 84+ có hàm tcdf để tìm xác suất cho các giá trị *t* cho trước. Cú pháp cho lệnh tcdf là tcdf(cận dưới, cận trên, bậc tự do). Tuy nhiên, đối với khoảng tin cậy, chúng ta cần sử dụng xác suất **nghịch đảo** để tìm giá trị của *t* khi đã biết xác suất.

Đối với TI-84+, bạn có thể sử dụng lệnh invT trên menu DISTRibution. Lệnh invT hoạt động tương tự như invnorm. Lệnh invT yêu cầu hai đầu vào: **invT(diện tích bên trái, bậc tự do)**. Đầu ra là điểm *t* tương ứng với diện tích mà chúng ta đã chỉ định. 

 Các dòng TI-83 và 83+ không có lệnh invT. (TI-89 có lệnh inverse T.)

Một bảng xác suất cho phân phối Student's t cũng có thể được sử dụng. Bảng này cung cấp các điểm *t* tương ứng với mức tin cậy (cột) và bậc tự do (hàng). (TI-86 không có chương trình hoặc lệnh invT, vì vậy nếu bạn đang sử dụng máy tính đó, bạn cần sử dụng bảng xác suất cho phân phối Student's t.) Khi sử dụng bảng *t*, lưu ý rằng một số bảng được định dạng để hiển thị mức tin cậy trong tiêu đề cột, trong khi tiêu đề cột ở một số bảng khác có thể chỉ hiển thị diện tích tương ứng ở một hoặc cả hai đuôi.

Bảng Student's t (Xem [Phụ lục H Các bảng](h-tables)) cung cấp các điểm *t* dựa trên bậc tự do và xác suất đuôi phải. Bảng này rất hạn chế. **Máy tính và máy tính cá nhân có thể dễ dàng tính toán bất kỳ xác suất Student's t nào.**

- *T ~ t_df* trong đó *df* = *n* – 1.
- Ví dụ, nếu chúng ta có một mẫu với kích thước *n* = 20 phần tử, thì chúng ta tính bậc tự do là *df* = *n* - 1 = 20 - 1 = 19 và chúng ta viết phân phối là *T ~ t_19*.
**Nếu độ lệch chuẩn của quần thể không được biết**, Giới hạn sai số cho trung bình tổng thể là:

- EBM=(

t

α
2

)(

s

n

)

EBM=(

t

α
2

)(

s

n

)
- t

σ
2

t

σ
2

 là điểm *t* với diện tích bên phải bằng 

α
2

α
2

,
- sử dụng *df* = *n* – 1 bậc tự do, và
- *s* = độ lệch chuẩn mẫu.
**Định dạng cho khoảng tin cậy là:**

(
x
¯

−EBM,
x
¯
+EBM)

(
x
¯

−EBM,
x
¯
+EBM)
.

Để tính khoảng tin cậy trực tiếp:

Nhấn `STAT`.

Di chuyển mũi tên sang `TESTS`.

Di chuyển mũi tên xuống `8:TInterval` và nhấn `ENTER` (hoặc chỉ cần nhấn 8).

#### Bài toán

Giả sử bạn thực hiện một nghiên cứu về châm cứu để xác định mức độ hiệu quả của nó trong việc giảm đau. Bạn đo tỷ lệ cảm giác cho 15 đối tượng với các kết quả được đưa ra. Sử dụng dữ liệu mẫu để xây dựng khoảng tin cậy 95% cho số trung bình tỷ lệ cảm giác của quần thể (giả định là phân phối chuẩn) mà bạn đã lấy dữ liệu.

Lời giải được trình bày từng bước và sử dụng máy tính TI-83, 83+ hoặc 84+.

Bạn thực hiện một nghiên cứu về liệu pháp thôi miên để xác định mức độ hiệu quả của nó trong việc tăng số giờ ngủ mà các đối tượng có được mỗi đêm. Bạn đo số giờ ngủ của 12 đối tượng với các kết quả sau. Hãy xây dựng khoảng tin cậy 95% cho số trung bình giờ ngủ của quần thể (giả định là phân phối chuẩn) mà bạn đã lấy dữ liệu.

8.2; 9.1; 7.7; 8.6; 6.9; 11.2; 10.1; 9.9; 8.9; 9.2; 7.5; 10.5

#### Bài toán

Dự án Human Toxome Project (HTP) đang nỗ lực tìm hiểu phạm vi ô nhiễm công nghiệp trong cơ thể con người. Các hóa chất công nghiệp có thể xâm nhập vào cơ thể thông qua ô nhiễm hoặc dưới dạng thành phần trong các sản phẩm tiêu dùng. Các nhà khoa học tại HTP đã kiểm tra các mẫu máu cuống rốn của 20 trẻ sơ sinh tại Hoa Kỳ. Máu cuống rốn của nhóm "Trong tử cung/trẻ sơ sinh" đã được kiểm tra 430 hợp chất công nghiệp, chất ô nhiễm và các hóa chất khác, bao gồm các hóa chất liên quan đến độc tính đối với não và hệ thần kinh, độc tính đối với hệ miễn dịch, độc tính đối với hệ sinh sản và các vấn đề về khả năng sinh sản. Có những lo ngại về sức khỏe đối với tác động của một số hóa chất lên não và hệ thần kinh. [Bảng 8.3](8-2-a-single-population-mean-using-the-student-t-distribution#eip-222) cho thấy có bao nhiêu hóa chất mục tiêu được tìm thấy trong máu cuống rốn của mỗi trẻ sơ sinh.

| 79 | 145 | 147 | 160 | 116 | 100 | 159 | 151 | 156 | 126 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 137 | 83 | 156 | 94 | 121 | 144 | 123 | 114 | 139 | 99 |

Sử dụng dữ liệu mẫu này để xây dựng khoảng tin cậy 90% cho số trung bình các hóa chất công nghiệp mục tiêu được tìm thấy trong máu của trẻ sơ sinh.

Một mẫu ngẫu nhiên các sinh viên thống kê được yêu cầu ước tính tổng số giờ họ dành ra để xem truyền hình trong một tuần trung bình. Các phản hồi được ghi lại trong [Bảng 8.4](8-2-a-single-population-mean-using-the-student-t-distribution#eip-672). Sử dụng dữ liệu mẫu này để xây dựng khoảng tin cậy 98% cho số trung bình các giờ mà sinh viên thống kê sẽ dành ra để xem truyền hình trong một tuần.

| 0 | 3 | 1 | 20 | 9 |
| --- | --- | --- | --- | --- |
| 5 | 10 | 1 | 10 | 4 |
| 14 | 2 | 4 | 4 | 5 |
