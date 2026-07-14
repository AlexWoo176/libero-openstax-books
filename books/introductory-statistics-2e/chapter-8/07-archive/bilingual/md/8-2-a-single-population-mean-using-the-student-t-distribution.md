## 8.2
 
A Single Population Mean using the Student t Distribution

## 8.2
 
Số trung bình của một quần thể sử dụng phân phối Student t

In practice, we rarely know the population standard deviation. In the past, when the sample size was large, this did not present a problem to statisticians. They used the sample standard deviation *s* as an estimate for *σ* and proceeded as before to calculate a confidence interval with close enough results. However, statisticians ran into problems when the sample size was small. A small sample size caused inaccuracies in the confidence interval.

Trong thực tế, chúng ta hiếm khi biết Độ lệch chuẩn của quần thể. Trước đây, khi kích thước mẫu lớn, điều này không gây khó khăn cho các nhà thống kê. Họ sử dụng độ lệch chuẩn mẫu *s* làm ước lượng cho *σ* và tiến hành tính toán Khoảng tin cậy như trước với kết quả đủ gần. Tuy nhiên, các nhà thống kê gặp vấn đề khi kích thước mẫu nhỏ. Kích thước mẫu nhỏ gây ra sự thiếu chính xác trong khoảng tin cậy.

William S. Gosset (1876–1937) of the Guinness brewery in Dublin, Ireland ran into this  problem. His experiments with hops and barley produced very few samples. Just replacing *σ* with *s* did not produce accurate results when he tried to calculate a confidence interval. He realized that he could not use a normal distribution for the calculation; he found that the actual distribution depends on the sample size. This problem led him to "discover" what is called the Student's t-distribution. The name comes from the fact that Gosset wrote under the pen name "Student."

William S. Gosset (1876–1937) làm việc tại nhà máy bia Guinness ở Dublin, Ireland đã gặp phải vấn đề này. Các thí nghiệm của ông với hoa bia và lúa mạch tạo ra rất ít mẫu. Việc chỉ thay thế *σ* bằng *s* không mang lại kết quả chính xác khi ông cố gắng tính toán khoảng tin cậy. Ông nhận ra rằng mình không thể sử dụng phân phối chuẩn cho việc tính toán; ông phát hiện ra rằng phân phối thực tế phụ thuộc vào kích thước mẫu. Vấn đề này đã dẫn ông đến việc "khám phá" ra cái gọi là Phân phối Student (phân phối t). Tên gọi này xuất phát từ việc Gosset viết dưới bút danh "Student".

Up until the mid-1970s, some statisticians used the normal distribution approximation for large sample sizes and used the Student's t-distribution only for sample sizes of at most 30. With graphing calculators and computers, the practice now is to use the Student's t-distribution whenever *s* is used as an estimate for *σ*.

Cho đến giữa những năm 1970, một số nhà thống kê đã sử dụng phép xấp xỉ Phân phối chuẩn cho các kích thước mẫu lớn và chỉ sử dụng phân phối Student's t cho các kích thước mẫu tối đa là 30. Với máy tính cầm tay đồ họa và máy tính cá nhân, thực tế hiện nay là sử dụng phân phối Student's t bất cứ khi nào *s* được sử dụng làm ước lượng cho *σ*.

If you draw a simple random sample of size *n* from a population that has an approximately normal distribution with mean *μ* and unknown population standard deviation *σ* and calculate the *t*-score *t* = 

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

, then the *t*-scores follow a **Student's t-distribution with *n* – 1 degrees of freedom**. The *t*-score has the same interpretation as the *z*-score. It measures how far 

x
¯

x
¯
 is from its mean *μ*. For each sample size *n*, there is a different Student's t-distribution.

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

The degrees of freedom, ***n* – 1**, come from the calculation of the sample standard deviation ***s***. This calculation requires *n* deviations 

(x–
x
¯

 values)

(x–
x
¯

 values)
. Because the sum of the deviations is zero, we can find the last deviation once we know the other ***n* – 1** deviations. The other ***n* – 1** deviations can change or vary freely. **We call the number *n* – 1 the degrees of freedom (df).**

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

- The graph for the Student's t-distribution is similar to the standard normal curve.
- Đồ thị cho phân phối t của Student tương tự như đường cong chuẩn tắc.
- The mean for the Student's t-distribution is zero and the distribution is symmetric about zero.
- Số trung bình cho phân phối t của Student là bằng không và phân phối này đối xứng qua không.
- The Student's t-distribution has more probability in its tails than the standard normal distribution because the spread of the t-distribution is greater than the spread of the standard normal. So the graph of the Student's t-distribution will be thicker in the tails and shorter in the center than the graph of the standard normal distribution.
- Phân phối t của Student có nhiều xác suất hơn ở các đuôi so với phân phối chuẩn tắc vì độ phân tán của phân phối t lớn hơn độ phân tán của phân phối chuẩn tắc. Vì vậy, đồ thị của phân phối t của Student sẽ dày hơn ở các đuôi và thấp hơn ở trung tâm so với đồ thị của phân phối chuẩn tắc.
- The exact shape of the Student's t-distribution depends on the degrees of freedom. As the degrees of freedom increases, the graph of Student's t-distribution becomes more like the graph of the standard normal distribution.
- Hình dạng chính xác của phân phối t của Student phụ thuộc vào bậc tự do. Khi bậc tự do tăng lên, đồ thị của phân phối t của Student trở nên giống với đồ thị của phân phối chuẩn tắc hơn.
- The underlying population of individual observations is assumed to be normally distributed with unknown population mean *μ* and unknown population standard deviation *σ*. The size of the underlying population is generally not relevant unless it is very small. If it is bell shaped (normal) then the assumption is met and doesn't need discussion. Random sampling is assumed, but that is a completely separate assumption from normality.
- Quần thể gốc của các quan sát cá biệt được giả định là phân phối chuẩn với số trung bình quần thể *μ* chưa biết và độ lệch chuẩn quần thể *σ* chưa biết. Kích thước của quần thể gốc thường không liên quan trừ khi nó rất nhỏ. Nếu nó có hình chuông (chuẩn) thì giả định đã được đáp ứng và không cần thảo luận thêm. Lấy mẫu ngẫu nhiên được giả định, nhưng đó là một giả định hoàn toàn tách biệt với tính chuẩn tắc.
Calculators and computers can easily calculate any Student's t-probabilities. The TI-83,83+, and 84+ have a tcdf function to find the probability for given values of *t*. The grammar for the tcdf command is tcdf(lower bound, upper bound, degrees of freedom). However for confidence intervals, we need to use **inverse** probability to find the value of *t* when we know the probability.

Máy tính và máy tính cá nhân có thể dễ dàng tính toán bất kỳ xác suất Student's t nào. Các dòng TI-83, 83+ và 84+ có hàm tcdf để tìm xác suất cho các giá trị *t* cho trước. Cú pháp cho lệnh tcdf là tcdf(cận dưới, cận trên, bậc tự do). Tuy nhiên, đối với khoảng tin cậy, chúng ta cần sử dụng xác suất **nghịch đảo** để tìm giá trị của *t* khi đã biết xác suất.

For the TI-84+ you can use the invT command on the DISTRibution menu. The invT command works similarly to the invnorm. The invT command requires two inputs: ** invT(area to the left, degrees of freedom)** The output is the t-score that corresponds to the area we specified. 

 The TI-83 and 83+ do not have the invT command. (The TI-89 has an inverse T command.)

Đối với TI-84+, bạn có thể sử dụng lệnh invT trên menu DISTRibution. Lệnh invT hoạt động tương tự như invnorm. Lệnh invT yêu cầu hai đầu vào: **invT(diện tích bên trái, bậc tự do)**. Đầu ra là điểm *t* tương ứng với diện tích mà chúng ta đã chỉ định. 

 Các dòng TI-83 và 83+ không có lệnh invT. (TI-89 có lệnh inverse T.)

A probability table for the Student's t-distribution can also be used.  The table gives t-scores that correspond to the confidence level (column) and degrees of freedom (row). (The TI-86 does not have an invT program or command, so if you are using that calculator, you need to use a probability table for the Student's t-Distribution.) When using a *t*-table, note that some tables are formatted to show the confidence level in the column headings, while the column headings in some tables may show only corresponding area in one or both tails.

A Student's t table (See [Appendix H Tables](h-tables)) gives *t*-scores given the degrees of freedom and the right-tailed probability. The table is very limited. **Calculators and computers can easily calculate any Student's  t-probabilities.**

Một bảng xác suất cho phân phối Student's t cũng có thể được sử dụng. Bảng này cung cấp các điểm *t* tương ứng với mức tin cậy (cột) và bậc tự do (hàng). (TI-86 không có chương trình hoặc lệnh invT, vì vậy nếu bạn đang sử dụng máy tính đó, bạn cần sử dụng bảng xác suất cho phân phối Student's t.) Khi sử dụng bảng *t*, lưu ý rằng một số bảng được định dạng để hiển thị mức tin cậy trong tiêu đề cột, trong khi tiêu đề cột ở một số bảng khác có thể chỉ hiển thị diện tích tương ứng ở một hoặc cả hai đuôi.

Bảng Student's t (Xem [Phụ lục H Các bảng](h-tables)) cung cấp các điểm *t* dựa trên bậc tự do và xác suất đuôi phải. Bảng này rất hạn chế. **Máy tính và máy tính cá nhân có thể dễ dàng tính toán bất kỳ xác suất Student's t nào.**

- *T ~ t_df* where *df* = *n* – 1.
- *T ~ t_df* trong đó *df* = *n* – 1.
- For example, if we have a sample of size *n* = 20 items, then we calculate the degrees of freedom as *df* = *n* - 1 = 20 - 1 = 19 and we write the distribution as *T ~ t_19*.
- Ví dụ, nếu chúng ta có một mẫu với kích thước *n* = 20 phần tử, thì chúng ta tính bậc tự do là *df* = *n* - 1 = 20 - 1 = 19 và chúng ta viết phân phối là *T ~ t_19*.
**If the population standard deviation is  not known**,  the error bound for a population mean is:

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
,
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

 is the *t*-score with area to the right equal to 

α
2

α
2

,
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
- use *df* = *n* – 1 degrees of freedom, and
- sử dụng *df* = *n* – 1 bậc tự do, và
- *s* = sample standard deviation.
- *s* = độ lệch chuẩn mẫu.
**The format for the confidence interval is:**

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

To calculate the confidence interval directly:

Press `STAT`.

Arrow over to `TESTS`.

Arrow down to `8:TInterval` and press `ENTER` (or just press 8).

Để tính khoảng tin cậy trực tiếp:

Nhấn `STAT`.

Di chuyển mũi tên sang `TESTS`.

Di chuyển mũi tên xuống `8:TInterval` và nhấn `ENTER` (hoặc chỉ cần nhấn 8).

#### Problem

#### Bài toán

Suppose you do a study of acupuncture to determine how effective it is in relieving pain. You measure sensory rates for 15 subjects with the results given. Use the sample data to construct a 95% confidence interval for the mean sensory rate for the population (assumed normal) from which you took the data.

The solution is shown step-by-step and by using the TI-83, 83+, or 84+ calculators.

Giả sử bạn thực hiện một nghiên cứu về châm cứu để xác định mức độ hiệu quả của nó trong việc giảm đau. Bạn đo tỷ lệ cảm giác cho 15 đối tượng với các kết quả được đưa ra. Sử dụng dữ liệu mẫu để xây dựng khoảng tin cậy 95% cho số trung bình tỷ lệ cảm giác của quần thể (giả định là phân phối chuẩn) mà bạn đã lấy dữ liệu.

Lời giải được trình bày từng bước và sử dụng máy tính TI-83, 83+ hoặc 84+.

You do a study of hypnotherapy to determine how effective it is in increasing the number of hours of sleep subjects get each night. You measure hours of sleep for 12 subjects with the following results. Construct a 95% confidence interval for the mean number of hours slept for the population (assumed normal) from which you took the data.

Bạn thực hiện một nghiên cứu về liệu pháp thôi miên để xác định mức độ hiệu quả của nó trong việc tăng số giờ ngủ mà các đối tượng có được mỗi đêm. Bạn đo số giờ ngủ của 12 đối tượng với các kết quả sau. Hãy xây dựng khoảng tin cậy 95% cho số trung bình giờ ngủ của quần thể (giả định là phân phối chuẩn) mà bạn đã lấy dữ liệu.

8.2; 9.1; 7.7; 8.6; 6.9; 11.2; 10.1; 9.9; 8.9; 9.2; 7.5; 10.5

8.2; 9,1; 7,7; 8.6; 6,9; 11,2; 10,1; 9,9; 8.9; 9,2; 7,5; 10,5

#### Problem

#### Bài toán

The Human Toxome Project (HTP) is working to understand the scope of industrial pollution in the human body. Industrial chemicals may enter the body through pollution or as ingredients in consumer products. The scientists at HTP tested cord blood samples for 20 newborn infants in the United States. The cord blood of the "In utero/newborn" group was tested for 430 industrial compounds, pollutants, and other chemicals, including chemicals linked to brain and nervous system toxicity, immune system toxicity, and reproductive toxicity, and fertility problems. There are health concerns about the effects of some chemicals on the brain and nervous system. [Table 8.3](8-2-a-single-population-mean-using-the-student-t-distribution#eip-222) shows how many of the targeted chemicals were found in each infant’s cord blood.

Dự án Human Toxome Project (HTP) đang nỗ lực tìm hiểu phạm vi ô nhiễm công nghiệp trong cơ thể con người. Các hóa chất công nghiệp có thể xâm nhập vào cơ thể thông qua ô nhiễm hoặc dưới dạng thành phần trong các sản phẩm tiêu dùng. Các nhà khoa học tại HTP đã kiểm tra các mẫu máu cuống rốn của 20 trẻ sơ sinh tại Hoa Kỳ. Máu cuống rốn của nhóm "Trong tử cung/trẻ sơ sinh" đã được kiểm tra 430 hợp chất công nghiệp, chất ô nhiễm và các hóa chất khác, bao gồm các hóa chất liên quan đến độc tính đối với não và hệ thần kinh, độc tính đối với hệ miễn dịch, độc tính đối với hệ sinh sản và các vấn đề về khả năng sinh sản. Có những lo ngại về sức khỏe đối với tác động của một số hóa chất lên não và hệ thần kinh. [Bảng 8.3](8-2-a-single-population-mean-using-the-student-t-distribution#eip-222) cho thấy có bao nhiêu hóa chất mục tiêu được tìm thấy trong máu cuống rốn của mỗi trẻ sơ sinh.

| 79 | 79 | 145 | 145 | 147 | 147 | 160 | 160 | 116 | 116 | 100 | 100 | 159 | 159 | 151 | 151 | 156 | 156 | 126 | 126 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 137 | 137 | 83 | 83 | 156 | 156 | 94 | 94 | 121 | 121 | 144 | 144 | 123 | 123 | 114 | 114 | 139 | 139 | 99 | 99 |

Use this sample data to construct a 90% confidence interval for the mean number of targeted industrial chemicals to be found in an in infant’s blood.

Sử dụng dữ liệu mẫu này để xây dựng khoảng tin cậy 90% cho số trung bình các hóa chất công nghiệp mục tiêu được tìm thấy trong máu của trẻ sơ sinh.

A random sample of statistics students were asked to estimate the total number of hours they spend watching television in an average week. The responses are recorded in [Table 8.4](8-2-a-single-population-mean-using-the-student-t-distribution#eip-672). Use this sample data to construct a 98% confidence interval for the mean number of hours statistics students will spend watching television in one week.

Một mẫu ngẫu nhiên các sinh viên thống kê được yêu cầu ước tính tổng số giờ họ dành ra để xem truyền hình trong một tuần trung bình. Các phản hồi được ghi lại trong [Bảng 8.4](8-2-a-single-population-mean-using-the-student-t-distribution#eip-672). Sử dụng dữ liệu mẫu này để xây dựng khoảng tin cậy 98% cho số trung bình các giờ mà sinh viên thống kê sẽ dành ra để xem truyền hình trong một tuần.

| 0 | 0 | 3 | 3 | 1 | 1 | 20 | 20 | 9 | 9 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 5 | 5 | 10 | 10 | 1 | 1 | 10 | 10 | 4 | 4 |
| 14 | 14 | 2 | 2 | 4 | 4 | 4 | 4 | 5 | 5 |
