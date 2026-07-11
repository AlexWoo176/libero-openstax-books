## Chapter Review

## Ôn tập chương

In this module, we learned how to calculate the confidence interval for a single population mean where the population standard deviation is known. When estimating a population mean, the margin of error is called the error bound for a population mean (*EBM*). A confidence interval has the general form:

Trong mô-đun này, chúng ta đã học cách tính khoảng tin cậy cho số trung bình của một quần thể khi biết độ lệch chuẩn của quần thể. Khi ước lượng số trung bình của quần thể, sai số biên được gọi là giới hạn sai số cho số trung bình quần thể (*EBM*). Một khoảng tin cậy có dạng tổng quát là:

(lower bound, upper bound) = (point estimate – *EBM*, point estimate + *EBM*)

(giới hạn dưới, giới hạn trên) = (ước lượng điểm – *EBM*, ước lượng điểm + *EBM*)

The calculation of *EBM* depends on the size of the sample and the level of confidence desired. The confidence level is the percent of all possible samples that can be expected to include the true population parameter. As the confidence level increases, the corresponding *EBM* increases as well. As the sample size increases, the *EBM* decreases. By the central limit theorem,

Việc tính toán *EBM* phụ thuộc vào kích thước mẫu và mức độ tin cậy mong muốn. Mức độ tin cậy là tỷ lệ phần trăm của tất cả các mẫu có thể có mà chúng ta kỳ vọng sẽ bao gồm tham số thực của quần thể. Khi mức độ tin cậy tăng lên, *EBM* tương ứng cũng tăng theo. Khi kích thước mẫu tăng lên, *EBM* giảm xuống. Theo định lý giới hạn trung tâm,

EBM=z
σ

n

EBM=z
σ

n

EBM=z
σ

n

EBM=z
σ

n

Given a confidence interval, you can work backwards to find the error bound (*EBM*) or the sample mean. To find the error bound, find the difference of the upper bound of the interval and the mean. If you do not know the sample mean, you can find the error bound by calculating half the difference of the upper and lower bounds.  To find the sample mean given a confidence interval, find the difference of the upper bound and the error bound. If the error bound is unknown, then average the upper and lower bounds of the confidence interval to find the sample mean.

Với một khoảng tin cậy cho trước, bạn có thể tính ngược lại để tìm giới hạn sai số (*EBM*) hoặc số trung bình mẫu. Để tìm giới hạn sai số, hãy tính hiệu số giữa giới hạn trên của khoảng và số trung bình. Nếu bạn không biết số trung bình mẫu, bạn có thể tìm giới hạn sai số bằng cách tính một nửa hiệu số giữa giới hạn trên và giới hạn dưới. Để tìm số trung bình mẫu khi biết khoảng tin cậy, hãy tính hiệu số giữa giới hạn trên và giới hạn sai số. Nếu không biết giới hạn sai số, hãy tính trung bình cộng của giới hạn trên và giới hạn dưới của khoảng tin cậy để tìm số trung bình mẫu.

Sometimes researchers know in advance that they want to estimate a population mean within a specific margin of error for a given level of confidence. In that case, solve the *EBM* formula for *n* to discover the size of the sample that is needed to achieve this goal:

Đôi khi các nhà nghiên cứu biết trước rằng họ muốn ước lượng số trung bình quần thể trong một sai số biên cụ thể cho một mức độ tin cậy nhất định. Trong trường hợp đó, hãy giải công thức *EBM* theo *n* để tìm kích thước mẫu cần thiết nhằm đạt được mục tiêu này:

n= 

z
2

σ
2

EB
M
2

n= 

z
2

σ
2

EB
M
2

n= 

z
2

σ
2

EB
M
2

n= 

z
2

σ
2

EB
M
2

In many cases, the researcher does not know the population standard deviation, *σ*, of the measure being studied. In these cases, it is common to use the sample standard deviation, *s*, as an estimate of *σ*. The normal distribution creates accurate confidence intervals when *σ* is known, but it is not as accurate when *s* is used as an estimate. In this case, the Student’s t-distribution is much better. Define a t-score using the following formula:

Trong nhiều trường hợp, nhà nghiên cứu không biết độ lệch chuẩn của quần thể, *σ*, của đại lượng đang được nghiên cứu. Trong những trường hợp này, người ta thường sử dụng độ lệch chuẩn mẫu, *s*, làm ước lượng cho *σ*. Phân phối chuẩn tạo ra các khoảng tin cậy chính xác khi biết *σ*, nhưng nó không chính xác bằng khi sử dụng *s* làm ước lượng. Trong trường hợp này, phân phối Student t tốt hơn nhiều. Hãy xác định điểm t bằng công thức sau:

t= 

x
¯

− μ

s

n

t= 

x
¯

− μ

s

n

t= 

x
¯

− μ

s

n

t= 

x
¯

− μ

s

n

The *t*-score follows the Student’s t-distribution with *n* – 1 degrees of freedom. The confidence interval under this distribution is calculated with *EBM* = 

(

t

α
2

)
s

n

(

t

α
2

)
s

n

 where 

t

α
2

t

α
2

 is the *t*-score with area to the right equal to 

α
2

α
2

, *s* is the sample standard deviation, and *n* is the sample size. Use a table, calculator, or computer to find 

t

α
2

t

α
2

 for a given *α*.

Điểm *t* tuân theo phân phối Student t với *n* – 1 bậc tự do. Khoảng tin cậy theo phân phối này được tính với *EBM* = 

(

t

α
2

)
s

n

(

t

α
2

)
s

n

 trong đó 

t

α
2

t

α
2

 là điểm *t* với diện tích bên phải bằng 

α
2

α
2

, *s* là độ lệch chuẩn mẫu, và *n* là kích thước mẫu. Sử dụng bảng, máy tính hoặc máy tính cá nhân để tìm 

t

α
2

t

α
2

 cho một giá trị *α* cho trước.

Some statistical measures, like many survey questions, measure qualitative rather than quantitative data. In this case, the population parameter being estimated is a proportion. It is possible to create a confidence interval for the true population proportion following procedures similar to those used in creating confidence intervals for population means. The formulas are slightly different, but they follow the same reasoning.

Một số trị thống kê, giống như nhiều câu hỏi khảo sát, đo lường dữ liệu định tính thay vì dữ liệu định lượng. Trong trường hợp này, tham số quần thể đang được ước lượng là một tỷ lệ. Có thể tạo một khoảng tin cậy cho tỷ lệ quần thể thực bằng cách tuân theo các quy trình tương tự như quy trình được sử dụng để tạo khoảng tin cậy cho số trung bình quần thể. Các công thức có hơi khác một chút, nhưng chúng tuân theo cùng một lập luận.

Let p′p′ represent the sample proportion, *x/n*, where *x* represents the number of successes and *n* represents the sample size. Let q′q′ = 1 – p′p′. Then the confidence interval for a population proportion is given by the following formula:

Để p′p′ đại diện cho tỷ lệ mẫu, *x/n*, trong đó *x* đại diện cho số lần thành công và *n* đại diện cho kích thước mẫu. Để q′q′ = 1 – p′p′. Khi đó, khoảng tin cậy cho một tỷ lệ quần thể được đưa ra bởi công thức sau:

(lower bound, upper bound) 

=(
p
′

–EBP,
p
′

 +EBP)= (

p
′

–z

p
′

q
′

n

,
p
′

+z

p
′

q
′

n

)

=(
p
′

–EBP,
p
′

 +EBP)= (

p
′

–z

p
′

q
′

n

,
p
′

+z

p
′

q
′

n

)

(giới hạn dưới, giới hạn trên) 

=(
p
′

–EBP,
p
′

 +EBP)= (

p
′

–z

p
′

q
′

n

,
p
′

+z

p
′

q
′

n

)

=(
p
′

–EBP,
p
′

 +EBP)= (

p
′

–z

p
′

q
′

n

,
p
′

+z

p
′

q
′

n

)

The “plus four” method for calculating confidence intervals is an attempt to balance the error introduced by using estimates of the population proportion when calculating the standard deviation of the sampling distribution. Simply imagine four additional trials in the study; two are successes and two are failures. Calculate 

p
′

=

x+2

n+4

p
′

=

x+2

n+4

, and proceed to find the confidence interval. When sample sizes are small, this method has been demonstrated to provide more accurate confidence intervals than the standard formula used for larger samples.

Phương pháp “cộng bốn” để tính khoảng tin cậy là một nỗ lực nhằm cân bằng sai số gây ra do việc sử dụng các ước lượng của tỷ lệ quần thể khi tính độ lệch chuẩn của phân phối mẫu. Chỉ cần tưởng tượng thêm bốn phép thử trong nghiên cứu; hai là thành công và hai là thất bại. Tính 

p
′

=

x+2

n+4

p
′

=

x+2

n+4

, và tiến hành tìm khoảng tin cậy. Khi kích thước mẫu nhỏ, phương pháp này đã được chứng minh là cung cấp các khoảng tin cậy chính xác hơn so với công thức tiêu chuẩn được sử dụng cho các mẫu lớn hơn.
