*Figure 
8.1
 
Have you ever wondered what the average number of M&Ms in a bag at the grocery store is? You can use confidence intervals to answer this question. (credit: modification of work “sweet, orange, food, green, red, color, brown, blue, colorful, yellow, chocolate, snack, dessert, toy, plain, candy, sweetness, treat, confectionery, coated, m ms, hard shell, snack food, jelly bean”/ Pxhere, Public Domain)*

*Hình 
8.1
 
Bạn đã bao giờ tự hỏi số trung bình các viên kẹo M&M trong một túi tại cửa hàng tạp hóa là bao nhiêu chưa? Bạn có thể sử dụng các khoảng tin cậy để trả lời câu hỏi này. (nguồn: chỉnh sửa từ tác phẩm “sweet, orange, food, green, red, color, brown, blue, colorful, yellow, chocolate, snack, dessert, toy, plain, candy, sweetness, treat, confectionery, coated, m ms, hard shell, snack food, jelly bean” / Pxhere, Phạm vi công cộng)*

By the end of this chapter, the student should be able to:

Đến cuối chương này, sinh viên sẽ có thể:

- Calculate and interpret confidence intervals for estimating a population mean and a population proportion.
- Tính toán và diễn giải các khoảng tin cậy để ước lượng số trung bình quần thể và tỷ lệ quần thể.
- Interpret the Student's t probability distribution as the sample size changes.
- Diễn giải phân phối xác suất t của Student khi kích thước mẫu thay đổi.
- Discriminate between problems applying the normal and the Student's *t* distributions.
- Phân biệt giữa các bài toán áp dụng phân phối chuẩn và phân phối *t* của Student.
- Calculate the sample size required to estimate a population mean and a population proportion given a desired confidence level and margin of error.
- Tính toán kích thước mẫu cần thiết để ước lượng số trung bình quần thể và tỷ lệ quần thể dựa trên mức độ tin cậy và sai số biên mong muốn.
## Introduction

## Giới thiệu

Suppose you were trying to determine the mean rent of a two-bedroom apartment in your town. You might look in the classified section of the newspaper, write down several rents listed, and average them together. You would have obtained a point estimate of the true mean. If you are trying to determine the percentage of times you make a basket when shooting a basketball, you might count the number of shots you make and divide that by the number of shots you attempted. In this case, you would have obtained a point estimate for the true proportion.

Giả sử bạn đang cố gắng xác định số trung bình tiền thuê một căn hộ hai phòng ngủ trong thị trấn của bạn. Bạn có thể xem phần rao vặt của tờ báo, ghi lại một vài mức giá thuê được liệt kê và tính trung bình cộng của chúng. Bạn sẽ thu được một ước lượng điểm của số trung bình thực tế. Nếu bạn đang cố gắng xác định tỷ lệ phần trăm số lần bạn ném bóng trúng rổ khi chơi bóng rổ, bạn có thể đếm số lần ném trúng và chia cho tổng số lần bạn đã ném. Trong trường hợp này, bạn sẽ thu được một ước lượng điểm cho tỷ lệ thực tế.

We use sample data to make generalizations about an unknown population. This part of statistics is called inferential statistics.  **The sample data help us to make an estimate of a population parameter**. We realize that the point estimate is most likely not the exact value of the population parameter, but close to it. After calculating point estimates, we construct interval estimates, called confidence intervals.

Chúng ta sử dụng dữ liệu mẫu để đưa ra các khái quát về một quần thể chưa biết. Phần này của thống kê học được gọi là Thống kê suy luận. **Dữ liệu mẫu giúp chúng ta đưa ra ước lượng về một Tham số quần thể**. Chúng ta nhận ra rằng ước lượng điểm rất có thể không phải là giá trị chính xác của tham số quần thể, nhưng nó gần với giá trị đó. Sau khi tính toán các ước lượng điểm, chúng ta xây dựng các ước lượng khoảng, được gọi là khoảng tin cậy.

In this chapter, you will learn to construct and interpret confidence intervals. You will also learn a new distribution, the Student's-t, and how it is used with these intervals. Throughout the chapter, it is important to keep in mind that the confidence interval is a random variable. It is the population parameter that is fixed.

Trong chương này, bạn sẽ học cách xây dựng và diễn giải các khoảng tin cậy. Bạn cũng sẽ học một phân phối mới, phân phối t của Student, và cách sử dụng nó với các khoảng này. Trong suốt chương, điều quan trọng cần ghi nhớ là khoảng tin cậy là một biến ngẫu nhiên. Chính tham số quần thể mới là giá trị cố định.

If you worked in the marketing department of an entertainment company, you might be interested in the mean number of songs a consumer downloads a month from Apple Music. If so, you could conduct a survey and calculate the sample mean, 

x
¯

x
¯
, and the sample standard deviation, *s*. You would use 

x
¯

x
¯
 to estimate the population mean and *s* to estimate the population standard deviation. The sample mean, 

x
¯

x
¯
, is the point estimate for the population mean, *μ*. The sample standard deviation, *s*, is the point estimate for the population standard deviation, *σ*.

Nếu bạn làm việc trong bộ phận tiếp thị của một công ty giải trí, bạn có thể quan tâm đến số trung bình các bài hát mà một người tiêu dùng tải xuống mỗi tháng từ Apple Music. Nếu vậy, bạn có thể tiến hành một cuộc khảo sát và tính số trung bình mẫu, 

x
¯

x
¯
, và độ lệch chuẩn mẫu, *s*. Bạn sẽ sử dụng 

x
¯

x
¯
 để ước lượng số trung bình quần thể và *s* để ước lượng độ lệch chuẩn quần thể. Số trung bình mẫu, 

x
¯

x
¯
, là Ước lượng điểm cho số trung bình quần thể, *μ*. Độ lệch chuẩn mẫu, *s*, là ước lượng điểm cho độ lệch chuẩn quần thể, *σ*.

Each of 

x
¯

x
¯
 and *s* is called a statistic.

Mỗi giá trị trong 

x
¯

x
¯
 và *s* được gọi là một trị thống kê.

A confidence interval is another type of estimate but, instead of being just one number, it is an interval of numbers. It provides a range of reasonable values in which we expect the population parameter to fall. There is no guarantee that a given confidence interval does capture the parameter, but there is a predictable probability of success.

Khoảng tin cậy là một loại ước lượng khác nhưng thay vì chỉ là một con số, nó là một khoảng các con số. Nó cung cấp một phạm vi các giá trị hợp lý mà chúng ta kỳ vọng tham số quần thể sẽ nằm trong đó. Không có gì đảm bảo rằng một khoảng tin cậy nhất định sẽ chứa tham số, nhưng có một xác suất thành công có thể dự đoán được.

Suppose, for the Apple Music example, we do not know the population mean *μ*, but we do know that the population standard deviation is *σ* = 1 and our sample size is 100. Then, by the central limit theorem, the standard deviation for the sample mean is

Giả sử, đối với ví dụ về Apple Music, chúng ta không biết số trung bình quần thể *μ*, nhưng chúng ta biết rằng độ lệch chuẩn quần thể là *σ* = 1 và kích thước mẫu của chúng ta là 100. Khi đó, theo định lý giới hạn trung tâm, độ lệch chuẩn cho số trung bình mẫu là

The Empirical Rule, which applies to bell-shaped distributions, says that in approximately 95% of the samples, the sample mean, 

x
¯

x
¯
, will be within two standard deviations of the population mean *μ*. For our Apple Music example, two standard deviations is (2)(0.1) = 0.2. The sample mean 

x
¯

x
¯
 is likely to be within 0.2 units of *μ*.

Quy tắc thực nghiệm, áp dụng cho các phân phối có hình chuông, cho biết rằng trong khoảng 95% các mẫu, số trung bình mẫu, 

x
¯

x
¯
, sẽ nằm trong phạm vi hai độ lệch chuẩn của số trung bình quần thể *μ*. Đối với ví dụ về Apple Music của chúng ta, hai độ lệch chuẩn là (2)(0.1) = 0.2. Số trung bình mẫu 

x
¯

x
¯
 có khả năng nằm trong phạm vi 0.2 đơn vị so với *μ*.

Because 

x
¯

x
¯
 is within 0.2 units of *μ*, which is unknown, then *μ* is likely to be within 0.2 units
of 

x
¯

x
¯
 in 95% of the samples. The population mean *μ* is contained in an interval whose lower number is calculated by taking the sample mean and subtracting two standard deviations (2)(0.1) and whose upper number is calculated by taking the sample mean and adding two standard deviations. In other words, *μ* is between 

x
¯

 − 0.2

x
¯

 − 0.2
 and 

x
¯

 + 0.2

x
¯

 + 0.2
 in 95% of all the samples.

Vì 

x
¯

x
¯
 nằm trong phạm vi 0.2 đơn vị so với *μ* (giá trị chưa biết), nên *μ* có khả năng nằm trong phạm vi 0.2 đơn vị so với 

x
¯

x
¯
 trong 95% các mẫu. Số trung bình quần thể *μ* nằm trong một khoảng có số dưới được tính bằng cách lấy số trung bình mẫu trừ đi hai độ lệch chuẩn (2)(0.1) và số trên được tính bằng cách lấy số trung bình mẫu cộng với hai độ lệch chuẩn. Nói cách khác, *μ* nằm giữa 

x
¯

 − 0.2

x
¯

 − 0.2
 và 

x
¯

 + 0.2

x
¯

 + 0.2
 trong 95% tất cả các mẫu.

For the Apple Music example, suppose that a sample produced a sample mean 

x
¯

 = 2

x
¯

 = 2
. Then the unknown population mean *μ* is between

Đối với ví dụ về Apple Music, giả sử một mẫu tạo ra số trung bình mẫu 

x
¯

 = 2

x
¯

 = 2
. Khi đó, số trung bình quần thể chưa biết *μ* nằm giữa

x
¯

−0.2=2−0.2=1.8

x
¯

−0.2=2−0.2=1.8
 and 

x
¯

+0.2=2+0.2=2.2

x
¯

+0.2=2+0.2=2.2

x
¯

−0.2=2−0.2=1.8

x
¯

−0.2=2−0.2=1.8
 và 

x
¯

+0.2=2+0.2=2.2

x
¯

+0.2=2+0.2=2.2

We say that we are **95% confident** that the unknown population mean number of songs downloaded from Apple Music per month is between 1.8 and 2.2. **The 95% confidence interval is (1.8, 2.2).**

Chúng ta nói rằng chúng ta **tin cậy 95%** rằng số trung bình quần thể chưa biết về số bài hát được tải xuống từ Apple Music mỗi tháng nằm trong khoảng từ 1.8 đến 2.2. **Khoảng tin cậy 95% là (1.8, 2.2).**

The 95% confidence interval implies two possibilities. Either the interval (1.8, 2.2) contains the true mean *μ* or our sample produced an 

x
¯

x
¯
 that is not within 0.2 units of the true mean *μ*. The first possibility happens for 95% of well-chosen samples. It is important to remember that the second possibility happens for 5% of samples, even though correct procedures are followed.

Khoảng tin cậy 95% ngụ ý hai khả năng. Hoặc là khoảng (1.8, 2.2) chứa số trung bình thực tế *μ*, hoặc mẫu của chúng ta tạo ra một 

x
¯

x
¯
 không nằm trong phạm vi 0.2 đơn vị so với số trung bình thực tế *μ*. Khả năng thứ nhất xảy ra đối với 95% các mẫu được chọn tốt. Điều quan trọng cần nhớ là khả năng thứ hai xảy ra đối với 5% các mẫu, ngay cả khi các quy trình chính xác đã được tuân thủ.

Remember that a confidence interval is created for an unknown population parameter like the population mean, *μ*. Confidence intervals for some parameters have the form:

Hãy nhớ rằng một khoảng tin cậy được tạo ra cho một tham số quần thể chưa biết như số trung bình quần thể, *μ*. Các khoảng tin cậy cho một số tham số có dạng:

**(point estimate – margin of error, point estimate + ** margin of error**)**

**(ước lượng điểm – sai số biên, ước lượng điểm + ** Biên độ lỗi**)**

The margin of error depends on the confidence level or percentage of confidence and the standard error of the mean.

Sai số biên phụ thuộc vào mức độ tin cậy hoặc tỷ lệ phần trăm tin cậy và sai số chuẩn của số trung bình.

When you read newspapers and journals, some reports will use the phrase "margin of error." Other reports will not use that phrase, but include a confidence interval as the point estimate plus or minus the margin of error. These are two ways of expressing the same concept.

Khi bạn đọc báo và tạp chí, một số báo cáo sẽ sử dụng cụm từ "sai số biên". Các báo cáo khác sẽ không sử dụng cụm từ đó, nhưng bao gồm một khoảng tin cậy dưới dạng ước lượng điểm cộng hoặc trừ sai số biên. Đây là hai cách diễn đạt cùng một khái niệm.

Although the text only covers symmetrical confidence intervals, there are non-symmetrical confidence intervals (for example, a confidence interval for the standard deviation).

Mặc dù tài liệu này chỉ đề cập đến các khoảng tin cậy đối xứng, nhưng vẫn có các khoảng tin cậy không đối xứng (ví dụ: khoảng tin cậy cho độ lệch chuẩn).

Have your instructor record the number of meals each student in your class eats out in a week. Assume that the standard deviation is known to be three meals. Construct an approximate 95% confidence interval for the true mean number of meals students eat out each week.

Hãy nhờ giảng viên của bạn ghi lại số bữa ăn mà mỗi sinh viên trong lớp bạn ăn ngoài mỗi tuần. Giả sử rằng độ lệch chuẩn được biết là ba bữa. Hãy xây dựng một khoảng tin cậy xấp xỉ 95% cho số trung bình thực tế các bữa ăn mà sinh viên ăn ngoài mỗi tuần.

1. Calculate the sample mean.
1. Tính số trung bình mẫu.
1. Let *σ* = 3 and *n* = the number of students surveyed.
1. Cho *σ* = 3 và *n* = số sinh viên được khảo sát.
1. Construct the interval 

(

x
¯

−2

’

σ

n

, 
x
¯

 + 
2
’

σ

n

)

(

x
¯

−2

’

σ

n

, 
x
¯

 + 
2
’

σ

n

)
.
1. Xây dựng khoảng 

(

x
¯

−2

’

σ

n

, 
x
¯

 + 
2
’

σ

n

)

(

x
¯

−2

’

σ

n

, 
x
¯

 + 
2
’

σ

n

)
.
We say we are approximately 95% confident that the true mean number of meals that students eat out in a week is between __________ and ___________.

Chúng ta nói rằng chúng ta tin cậy khoảng 95% rằng số trung bình thực tế các bữa ăn mà sinh viên ăn ngoài trong một tuần nằm trong khoảng từ __________ đến ___________.
