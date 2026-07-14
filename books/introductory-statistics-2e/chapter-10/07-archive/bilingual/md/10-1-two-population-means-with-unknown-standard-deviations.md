## 10.1
 
Two Population Means with Unknown Standard Deviations

## 10.1
 
Hai số trung bình quần thể với các độ lệch chuẩn chưa biết

1. The two independent samples are simple random samples from two distinct populations.
1. Hai mẫu độc lập là các mẫu ngẫu nhiên đơn giản từ hai quần thể riêng biệt.
1. For the two distinct populations:

if the sample sizes are small, the distributions are important (should be normal)nếu kích thước mẫu nhỏ, các phân phối là quan trọng (nên là phân phối chuẩn)
if the sample sizes are large, the distributions are not important (need not be normal)nếu kích thước mẫu lớn, các phân phối không quan trọng (không cần phải là phân phối chuẩn)
The test comparing two independent population means with unknown and possibly unequal population standard deviations is called the Aspin-Welch t-test.  The degrees of freedom formula was developed by Aspin-Welch.

Kiểm định so sánh hai số trung bình quần thể độc lập với các độ lệch chuẩn quần thể chưa biết và có thể không bằng nhau được gọi là kiểm định t Aspin-Welch. Công thức bậc tự do được phát triển bởi Aspin-Welch.

The comparison of two population means is very common. A difference between the two samples depends on both the means and the standard deviations. Very different means can occur by chance if there is great variation among the individual samples. In order to account for the variation, we take the difference of the sample means,

X
¯

1

X
¯

1
 – 

X
¯

2

X
¯

2
, and divide by the standard error in order to standardize the difference. The result is a t-score test statistic.

Việc so sánh hai số trung bình quần thể là rất phổ biến. Sự khác biệt giữa hai mẫu phụ thuộc vào cả số trung bình và độ lệch chuẩn. Các số trung bình rất khác nhau có thể xảy ra do ngẫu nhiên nếu có sự biến thiên lớn giữa các mẫu riêng lẻ. Để tính đến sự biến thiên này, chúng ta lấy hiệu của các số trung bình mẫu, 

X
¯

1

X
¯

1
 – 

X
¯

2

X
¯

2
, và chia cho sai số chuẩn để chuẩn hóa sự khác biệt. Kết quả là một thống kê kiểm định t-score.

Because we do not know the population standard deviations, we estimate them using the two sample standard deviations from our independent samples. For the hypothesis test, we calculate the estimated standard deviation, or standard error, of **the difference in sample means**, 

X
¯

1

X
¯

1
 – 

X
¯

2

X
¯

2
.

Vì chúng ta không biết các độ lệch chuẩn quần thể, chúng ta ước lượng chúng bằng cách sử dụng hai độ lệch chuẩn mẫu từ các mẫu độc lập của mình. Đối với kiểm định giả thuyết, chúng ta tính toán độ lệch chuẩn ước lượng, hay sai số chuẩn, của **sự khác biệt giữa các số trung bình mẫu**, 

X
¯

1

X
¯

1
 – 

X
¯

2

X
¯

2
.

The test statistic (*t*-score) is calculated as follows:

Thống kê kiểm định (điểm *t*) được tính như sau:

- *s*_1 and *s*_2, the sample standard deviations, are estimates of *σ*_1 and *σ*_2, respectively.
- *s*_1 và *s*_2, các độ lệch chuẩn mẫu, lần lượt là các ước lượng của *σ*_1 và *σ*_2.
- *σ*_1 and *σ*_2 are the unknown population standard deviations.
- *σ*_1 và *σ*_2 là các độ lệch chuẩn quần thể chưa biết.
- x
¯

1

x
¯

1

and

x
¯

2

x
¯

2

are the sample means. *μ*_1 and *μ*_2 are the population means.
- x
¯

1

x
¯

1

và

x
¯

2

x
¯

2

là các trung bình mẫu. *μ*_1 và *μ*_2 là các trung bình quần thể.
The number of degrees of freedom (*df*) requires a somewhat complicated calculation. However, a computer or calculator calculates it easily. The *df* are not always a whole number. The test statistic calculated previously is approximated by the Student's *t*-distribution with *df* as follows:

Số lượng bậc tự do (*df*) đòi hỏi một phép tính hơi phức tạp. Tuy nhiên, máy tính hoặc máy tính cầm tay có thể tính toán nó dễ dàng. *df* không phải lúc nào cũng là một số nguyên. Thống kê kiểm định được tính toán trước đó được xấp xỉ bởi phân phối Student *t* với *df* như sau:

When both sample sizes *n*_1 and *n*_2 are five or larger, the Student's *t* approximation is very good. Notice that the sample variances (*s*_1)^2 and (*s*_2)^2 are not pooled. (If the question comes up, do not pool the variances.)

Khi cả hai kích thước mẫu *n*_1 và *n*_2 đều từ năm trở lên, phép xấp xỉ Student *t* rất tốt. Lưu ý rằng các phương sai mẫu (*s*_1)^2 và (*s*_2)^2 không được gộp chung. (Nếu câu hỏi này xuất hiện, đừng gộp các phương sai lại.)

It is not necessary to compute this by hand. A calculator or computer easily computes it.

Bạn không cần phải tính toán thủ công. Máy tính hoặc phần mềm sẽ tính toán điều này một cách dễ dàng.

#### Independent groups

#### Các nhóm độc lập

The average amount of time boys and girls aged seven to 11 spend playing sports each day is believed to be the same. A study is done and data are collected, resulting in the data in [Table 10.1](10-1-two-population-means-with-unknown-standard-deviations#uid888). Each populations has a normal distribution.

Người ta tin rằng thời gian trung bình mà các bé trai và bé gái từ bảy đến 11 tuổi dành cho việc chơi thể thao mỗi ngày là như nhau. Một nghiên cứu đã được thực hiện và dữ liệu được thu thập, dẫn đến các dữ liệu trong [Bảng 10.1](10-1-two-population-means-with-unknown-standard-deviations#uid888). Mỗi quần thể đều có phân phối chuẩn.

|  |  | Sample Size | Kích thước mẫu | Average Number of Hours Playing Sports Per Day | Số giờ trung bình chơi thể thao mỗi ngày | Sample Standard Deviation | Độ lệch chuẩn mẫu |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Girls | Nữ | 9 | 9 | 2 | 2 | 0.8660.866 | 0.8660.866 |
| Boys | Nam | 16 | 16 | 3.2 | 3,2 | 1.00 | 1,00 |

#### Problem

#### Bài tập

Is there a difference in the mean amount of time boys and girls aged seven to 11 play sports each day? Test at the 5% level of significance.

Có sự khác biệt nào về thời gian trung bình mà các bé trai và bé gái từ bảy đến 11 tuổi chơi thể thao mỗi ngày không? Hãy kiểm định ở mức ý nghĩa 5%.

Two samples are shown in [Table 10.2](10-1-two-population-means-with-unknown-standard-deviations#fs-idm99631856). Both have normal distributions. The means for the two populations are thought to be the same. Is there a difference in the means? Test at the 5% level of significance.

Hai mẫu được hiển thị trong [Bảng 10.2](10-1-two-population-means-with-unknown-standard-deviations#fs-idm99631856). Cả hai đều có phân phối chuẩn. Các số trung bình của hai quần thể được cho là như nhau. Có sự khác biệt nào về các số trung bình không? Hãy kiểm định ở mức ý nghĩa 5%.

|  |  | Sample Size | Kích thước mẫu | Sample Mean | Trung bình mẫu | Sample Standard Deviation | Độ lệch chuẩn mẫu |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Population A | Quần thể A | 25 | 25 | 5 | 5 | 1 | 1 |
| Population B | Quần thể B | 16 | 16 | 4.7 | 4,7 | 1.2 | 1,2 |

When the sum of the sample sizes is larger than 30 (*n*_1 + *n*_2 > 30) you can use the normal distribution to approximate the Student's *t*. Use the Student's *t* distribution, however, whenever possible.

Khi tổng kích thước mẫu lớn hơn 30 (*n*_1 + *n*_2 > 30), bạn có thể sử dụng phân phối chuẩn để xấp xỉ phân phối Student *t*. Tuy nhiên, hãy sử dụng phân phối Student *t* bất cứ khi nào có thể.

A study is done by a community group in two neighboring colleges to determine which one graduates students with more math classes. College A samples 11 graduates. Their average is four math classes with a standard deviation of 1.5 math classes. College B samples nine graduates. Their average is 3.5 math classes with a standard deviation of one math class. The community group believes that a student who graduates from college A **has taken more math classes,** on the average. Both populations have a normal distribution. Test at a 1% significance level. Answer the following questions.

Một nghiên cứu được thực hiện bởi một nhóm cộng đồng tại hai trường đại học lân cận để xác định trường nào có sinh viên tốt nghiệp với nhiều lớp toán hơn. Trường A lấy mẫu 11 sinh viên tốt nghiệp. Số trung bình của họ là bốn lớp toán với độ lệch chuẩn là 1,5 lớp toán. Trường B lấy mẫu chín sinh viên tốt nghiệp. Số trung bình của họ là 3,5 lớp toán với độ lệch chuẩn là một lớp toán. Nhóm cộng đồng tin rằng một sinh viên tốt nghiệp từ trường A **đã học nhiều lớp toán hơn,** tính trung bình. Cả hai quần thể đều có phân phối chuẩn. Hãy kiểm định ở mức ý nghĩa 1%. Trả lời các câu hỏi sau.

#### Problem

#### Bài tập

a. Is this a test of two means or two proportions?

a. Đây là kiểm định cho hai số trung bình hay hai tỷ lệ?

#### Problem

#### Bài tập

b. Are the populations standard deviations known or unknown?

b. Các độ lệch chuẩn quần thể đã biết hay chưa biết?

#### Problem

#### Bài tập

c. Which distribution do you use to perform the test?

c. Bạn sử dụng phân phối nào để thực hiện kiểm định?

#### Problem

#### Bài tập

d. What is the random variable?

d. Biến ngẫu nhiên là gì?

#### Problem

#### Bài tập

e. What are the null and alternate hypotheses? Write the null and alternate hypotheses in words and in symbols.

e. Các giả thuyết không và đối thuyết là gì? Viết các giả thuyết không và đối thuyết bằng lời và bằng ký hiệu.

#### Problem

#### Bài tập

f. Is this test right-, left-, or two-tailed?

f. Đây là kiểm định phía phải, phía trái hay hai phía?

#### Problem

#### Bài tập

g. What is the *p*-value?

g. p-giá trị *p* là bao nhiêu?

#### Problem

#### Bài tập

h. Do you reject or not reject the null hypothesis?

h. Bạn bác bỏ hay không bác bỏ giả thuyết không?

#### Problem

#### Bài tập

i. **Conclusion:**

i. **Kết luận:**

A study is done to determine if Company A retains its workers longer than Company B. Company A samples 15 workers, and their average time with the company is five years with a standard deviation of 1.2. Company B samples 20 workers, and their average time with the company is 4.5 years with a standard deviation of 0.8. The populations are normally distributed.

Một nghiên cứu được thực hiện để xác định xem Công ty A có giữ chân nhân viên lâu hơn Công ty B hay không. Công ty A lấy mẫu 15 nhân viên, và thời gian trung bình họ làm việc tại công ty là năm năm với độ lệch chuẩn là 1,2. Công ty B lấy mẫu 20 nhân viên, và thời gian trung bình họ làm việc tại công ty là 4,5 năm với độ lệch chuẩn là 0,8. Các quần thể được phân phối chuẩn.

1. Are the population standard deviations known?
1. Các độ lệch chuẩn quần thể đã biết chưa?
1. Conduct an appropriate hypothesis test. At the 5% significance level, what is your conclusion?
1. Thực hiện một kiểm định giả thuyết phù hợp. Ở mức ý nghĩa 5%, kết luận của bạn là gì?
A professor at a large community college wanted to determine whether there is a difference in the means of final exam scores between students who took his statistics course online and the students who took his face-to-face statistics class.  He believed that the mean of the final exam scores for the online class would be lower than that of the face-to-face class.  Was the professor correct? The randomly selected 30 final exam scores from each group are listed in [Table 10.3](10-1-two-population-means-with-unknown-standard-deviations#fs-idm34056944) and [Table 10.4](10-1-two-population-means-with-unknown-standard-deviations#fs-idm124378288).

Một giáo sư tại một trường cao đẳng cộng đồng lớn muốn xác định xem có sự khác biệt nào về số trung bình điểm thi cuối kỳ giữa các sinh viên học khóa thống kê trực tuyến của ông và các sinh viên học lớp thống kê trực tiếp. Ông tin rằng số trung bình điểm thi cuối kỳ của lớp trực tuyến sẽ thấp hơn so với lớp trực tiếp. Liệu giáo sư có đúng không? 30 điểm thi cuối kỳ được chọn ngẫu nhiên từ mỗi nhóm được liệt kê trong [Bảng 10.3](10-1-two-population-means-with-unknown-standard-deviations#fs-idm34056944) và [Bảng 10.4](10-1-two-population-means-with-unknown-standard-deviations#fs-idm124378288).

| 67.6 | 67,6 | 41.2 | 41,2 | 85.3 | 85,3 | 55.9 | 55,9 | 82.4 | 82,4 | 91.2 | 91,2 | 73.5 | 73,5 | 94.1 | 94,1 | 64.7 | 64,7 | 64.7 | 64,7 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 70.6 | 70,6 | 38.2 | 38,2 | 61.8 | 61,8 | 88.2 | 88,2 | 70.6 | 70,6 | 58.8 | 58,8 | 91.2 | 91,2 | 73.5 | 73,5 | 82.4 | 82,4 | 35.5 | 35,5 |
| 94.1 | 94,1 | 88.2 | 88,2 | 64.7 | 64,7 | 55.9 | 55,9 | 88.2 | 88,2 | 97.1 | 97,1 | 85.3 | 85,3 | 61.8 | 61,8 | 79.4 | 79,4 | 79.4 | 79,4 |

| 77.9 | 77,9 | 95.3 | 95,3 | 81.2 | 81,2 | 74.1 | 74,1 | 98.8 | 98,8 | 88.2 | 88,2 | 85.9 | 85,9 | 92.9 | 92,9 | 87.1 | 87,1 | 88.2 | 88,2 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 69.4 | 69,4 | 57.6 | 57,6 | 69.4 | 69,4 | 67.1 | 67,1 | 97.6 | 97,6 | 85.9 | 85,9 | 88.2 | 88,2 | 91.8 | 91,8 | 78.8 | 78,8 | 71.8 | 71,8 |
| 98.8 | 98,8 | 61.2 | 61,2 | 92.9 | 92,9 | 90.6 | 90,6 | 97.6 | 97,6 | 100 | 100 | 95.3 | 95,3 | 83.5 | 83,5 | 92.9 | 92,9 | 89.4 | 89,4 |

#### Problem

#### Bài tập

Is the mean of the Final Exam scores of the online class lower than the mean of the Final Exam scores of the face-to-face class? Test at a 5% significance level. Answer the following questions:

Số trung bình điểm thi cuối kỳ của lớp trực tuyến có thấp hơn số trung bình điểm thi cuối kỳ của lớp trực tiếp không? Hãy kiểm định ở mức ý nghĩa 5%. Trả lời các câu hỏi sau:

1. Is this a test of two means or two proportions?
1. Đây là kiểm định hai trung bình hay hai tỷ lệ?
1. Are the population standard deviations known or unknown?
1. Các độ lệch chuẩn quần thể đã biết hay chưa biết?
1. Which distribution do you use to perform the test?
1. Bạn sử dụng phân phối nào để thực hiện kiểm định?
1. What is the random variable?
1. Biến ngẫu nhiên là gì?
1. What are the null and alternative hypotheses?  Write the null and alternative hypotheses in words and in symbols.
1. Các giả thuyết không và đối thuyết là gì? Viết các giả thuyết không và đối thuyết bằng lời và bằng ký hiệu.
1. Is this test right, left, or two tailed?
1. Đây là kiểm định một phía bên phải, bên trái, hay hai phía?
1. What is the *p*-value?
1. *p*-giá trị là bao nhiêu?
1. Do you reject or not reject the null hypothesis?
1. Bạn bác bỏ hay không bác bỏ giả thuyết không?
1. At the ___ level of significance, from the sample data, there ______ (is/is not) sufficient evidence to conclude that ______.
1. Tại mức ý nghĩa ___, từ dữ liệu mẫu, ______ (có/không có) đủ bằng chứng để kết luận rằng ______.
(See the conclusion in [Example 10.2](10-1-two-population-means-with-unknown-standard-deviations#element-968), and write yours in a similar fashion)

(Xem kết luận trong [Ví dụ 10.2](10-1-two-population-means-with-unknown-standard-deviations#element-968), và viết kết luận của bạn theo cách tương tự)

First put the data for each group into two lists (such as L1 and L2). Press `STAT`. Arrow over to `TESTS` and press `4:2SampTTest`. Make sure Data is highlighted and press `ENTER`. Arrow down and enter `L1` for the first list and `L2` for the second list. Arrow down to *μ*_1: and arrow to `<` *μ*_2 (less than). Press `ENTER`. Arrow down to Pooled: No. Press `ENTER`. Arrow down to `Calculate` and press `ENTER`.

Trước tiên, hãy nhập dữ liệu cho mỗi nhóm vào hai danh sách (như L1 và L2). Nhấn `STAT`. Di chuyển sang `TESTS` và nhấn `4:2SampTTest`. Đảm bảo Data được tô sáng và nhấn `ENTER`. Di chuyển xuống và nhập `L1` cho danh sách thứ nhất và `L2` cho danh sách thứ hai. Di chuyển xuống *μ*_1: và di chuyển đến `<` *μ*_2 (nhỏ hơn). Nhấn `ENTER`. Di chuyển xuống Pooled: No. Nhấn `ENTER`. Di chuyển xuống `Calculate` và nhấn `ENTER`.

Be careful not to mix up the information for Group 1 and Group 2!

Hãy cẩn thận không để lẫn thông tin của Nhóm 1 và Nhóm 2!

Two professors, A and B, teach classes on the same subjects. Scores of 10 students from each class are selected randomly. The final exam scores of the students are as follows:

Hai giáo sư, A và B, dạy các lớp cùng môn học. Điểm của 10 sinh viên từ mỗi lớp được chọn ngẫu nhiên. Điểm thi cuối kỳ của các sinh viên như sau:

Professor A:

Giáo sư A:

| 97 | 97 | 62 | 62 | 73 | 73 | 58 | 58 | 84 | 84 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 74 | 74 | 66 | 66 | 93 | 93 | 73 | 73 | 85 | 85 |

Professor B:

Giáo sư B:

| 85 | 85 | 64 | 64 | 74 | 74 | 55 | 55 | 76 | 76 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 67 | 67 | 72 | 72 | 84 | 84 | 71 | 71 | 98 | 98 |

Professor A says that the mean score of their class is more than the mean of professor B’s class. Is professor A correct? Test at a 5% significance level. Answer the following questions:

Giáo sư A nói rằng số trung bình điểm của lớp họ cao hơn số trung bình của lớp giáo sư B. Liệu giáo sư A có đúng không? Hãy kiểm định ở mức ý nghĩa 5%. Trả lời các câu hỏi sau:

1. Is this a test of two means or two proportions?
1. Đây là kiểm định hai trung bình hay hai tỷ lệ?
1. Are the population standard deviations known or unknown?
1. Các độ lệch chuẩn quần thể đã biết hay chưa biết?
1. Which distribution do you use to perform the test?
1. Bạn sử dụng phân phối nào để thực hiện kiểm định?
1. What is the random variable?
1. Biến ngẫu nhiên là gì?
1. What are the null and alternative hypotheses? Write the null and alternative hypotheses in words and in symbols.
1. Các giả thuyết không và đối thuyết là gì? Viết các giả thuyết không và đối thuyết bằng lời và bằng ký hiệu.
1. Is this test right-, left-, or two-tailed?
1. Đây là kiểm định một phía bên phải, bên trái, hay hai phía?
1. What is the *p*-value?
1. *p*-giá trị là bao nhiêu?
1. Do you reject or not reject the null hypothesis?
1. Bạn bác bỏ hay không bác bỏ giả thuyết không?
1. At the ___ level of significance, from the sample data, there ___ (is/is not) sufficient evidence to conclude that ___.
1. Tại mức ý nghĩa ___, từ dữ liệu mẫu, ___ (có/không có) đủ bằng chứng để kết luận rằng ___.
Cohen's Standards for Small, Medium, and Large Effect SizesCohen's *d* is a measure of effect size based on the differences between two means. Cohen’s *d*, named for United States statistician Jacob Cohen, measures the relative strength of the differences between the means of two populations based on sample data. The calculated value of effect size is then compared to Cohen’s standards of small, medium, and large effect sizes.

Các tiêu chuẩn của Cohen về kích thước hiệu ứng nhỏ, trung bình và lớnCohen's *d* là một thước đo kích thước hiệu ứng dựa trên sự khác biệt giữa hai số trung bình. Cohen's *d*, được đặt tên theo nhà thống kê người Mỹ Jacob Cohen, đo lường sức mạnh tương đối của sự khác biệt giữa các số trung bình của hai quần thể dựa trên dữ liệu mẫu. Giá trị tính toán của kích thước hiệu ứng sau đó được so sánh với các tiêu chuẩn của Cohen về kích thước hiệu ứng nhỏ, trung bình và lớn.

| Size of effect | Kích thước hiệu ứng | *d* | *d* |
| --- | --- | --- | --- |
| Small | Nhỏ | 0.2 | 0,2 |
| medium | trung bình | 0.5 | 0,5 |
| Large | Lớn | 0.8 | 0,8 |

Cohen's *d* is the measure of the difference between two means divided by the pooled standard deviation: 

d=

x
¯

1

–

x
¯

2

s

pooled

d=

x
¯

1

–

x
¯

2

s

pooled

 where 

s

pooled

=

(
n
1

–1)
s
1
2

+(
n
2

–1)
s
2
2

n
1

+
n
2

–2

s

pooled

=

(
n
1

–1)
s
1
2

+(
n
2

–1)
s
2
2

n
1

+
n
2

–2

Cohen's *d* là thước đo sự khác biệt giữa hai số trung bình chia cho độ lệch chuẩn gộp: 

d=

x
¯

1

–

x
¯

2

s

pooled

d=

x
¯

1

–

x
¯

2

s

pooled

 trong đó 

s

pooled

=

(
n
1

–1)
s
1
2

+(
n
2

–1)
s
2
2

n
1

+
n
2

–2

s

pooled

=

(
n
1

–1)
s
1
2

+(
n
2

–1)
s
2
2

n
1

+
n
2

–2

#### Problem

#### Bài tập

Calculate Cohen’s *d* for [Example 10.2](10-1-two-population-means-with-unknown-standard-deviations#element-968). Is the size of the effect small, medium, or large? Explain what the size of the effect means for this problem.

Tính Cohen's *d* cho [Ví dụ 10.2](10-1-two-population-means-with-unknown-standard-deviations#element-968). Kích thước hiệu ứng là nhỏ, trung bình hay lớn? Giải thích ý nghĩa của kích thước hiệu ứng đối với bài toán này.

Calculate Cohen’s *d* for [Try It  10.2](10-1-two-population-means-with-unknown-standard-deviations#fs-idp145514592). Is the size of the effect small, medium, or large? Explain what the size of the effect means for this problem.

Tính Cohen's *d* cho [Thử sức 10.2](10-1-two-population-means-with-unknown-standard-deviations#fs-idp145514592). Kích thước hiệu ứng là nhỏ, trung bình hay lớn? Giải thích ý nghĩa của kích thước hiệu ứng đối với bài toán này.

#### Problem

#### Bài tập

Calculate Cohen’s *d* for [Example 10.3](10-1-two-population-means-with-unknown-standard-deviations#fs-idm22935408). Is the size of the effect small, medium or large? Explain what the size of the effect means for this problem.

Tính Cohen's *d* cho [Ví dụ 10.3](10-1-two-population-means-with-unknown-standard-deviations#fs-idm22935408). Kích thước hiệu ứng là nhỏ, trung bình hay lớn? Giải thích ý nghĩa của kích thước hiệu ứng đối với bài toán này.

Weighted alpha is a measure of risk-adjusted performance of stocks over a period of a year. A high positive weighted alpha signifies a stock whose price has risen while a small positive weighted alpha indicates an unchanged stock price during the time period. Weighted alpha is used to identify companies with strong upward or downward trends. The weighted alpha for the top 30 stocks of banks in the northeast and in the west as identified by Nasdaq on May 24, 2013 are listed in [Table 10.8](10-1-two-population-means-with-unknown-standard-deviations#fs-idm242901296) and [Table 10.9](10-1-two-population-means-with-unknown-standard-deviations#fs-idm167801152), respectively.

Weighted alpha là thước đo hiệu suất đã điều chỉnh rủi ro của cổ phiếu trong khoảng thời gian một năm. Một weighted alpha dương cao biểu thị một cổ phiếu có giá đã tăng, trong khi một weighted alpha dương nhỏ cho thấy giá cổ phiếu không thay đổi trong khoảng thời gian đó. Weighted alpha được sử dụng để xác định các công ty có xu hướng tăng hoặc giảm mạnh. Weighted alpha cho 30 cổ phiếu ngân hàng hàng đầu ở vùng đông bắc và phía tây theo xác định của Nasdaq vào ngày 24 tháng 5 năm 2013 được liệt kê lần lượt trong [Bảng 10.8](10-1-two-population-means-with-unknown-standard-deviations#fs-idm242901296) và [Bảng 10.9](10-1-two-population-means-with-unknown-standard-deviations#fs-idm167801152).

| 94.2 | 94,2 | 75.2 | 75,2 | 69.6 | 69,6 | 52.0 | 52,0 | 48.0 | 48,0 | 41.9 | 41,9 | 36.4 | 36,4 | 33.4 | 33,4 | 31.5 | 31,5 | 27.6 | 27,6 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 77.3 | 77,3 | 71.9 | 71,9 | 67.5 | 67,5 | 50.6 | 50,6 | 46.2 | 46,2 | 38.4 | 38,4 | 35.2 | 35,2 | 33.0 | 33,0 | 28.7 | 28,7 | 26.5 | 26,5 |
| 76.3 | 76,3 | 71.7 | 71,7 | 56.3 | 56,3 | 48.7 | 48,7 | 43.2 | 43,2 | 37.6 | 37,6 | 33.7 | 33,7 | 31.8 | 31,8 | 28.5 | 28,5 | 26.0 | 26,0 |

| 126.0 | 126,0 | 70.6 | 70,6 | 65.2 | 65,2 | 51.4 | 51,4 | 45.5 | 45,5 | 37.0 | 37,0 | 33.0 | 33,0 | 29.6 | 29,6 | 23.7 | 23,7 | 22.6 | 22,6 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 116.1 | 116,1 | 70.6 | 70,6 | 58.2 | 58,2 | 51.2 | 51,2 | 43.2 | 43,2 | 36.0 | 36,0 | 31.4 | 31,4 | 28.7 | 28,7 | 23.5 | 23,5 | 21.6 | 21,6 |
| 78.2 | 78,2 | 68.2 | 68,2 | 55.6 | 55,6 | 50.3 | 50,3 | 39.0 | 39,0 | 34.1 | 34,1 | 31.0 | 31,0 | 25.3 | 25,3 | 23.4 | 23,4 | 21.5 | 21,5 |

Is there a difference in the weighted alpha of the top 30 stocks of banks in the northeast and in the west? Test at a 5% significance level. Answer the following questions:

Có sự khác biệt nào về weighted alpha của 30 cổ phiếu ngân hàng hàng đầu ở vùng đông bắc và phía tây không? Hãy kiểm định ở mức ý nghĩa 5%. Trả lời các câu hỏi sau:

1. Is this a test of two means or two proportions?
1. Đây là kiểm định hai trung bình hay hai tỷ lệ?
1. Are the population standard deviations known or unknown?
1. Các độ lệch chuẩn quần thể đã biết hay chưa biết?
1. Which distribution do you use to perform the test?
1. Bạn sử dụng phân phối nào để thực hiện kiểm định?
1. What is the random variable?
1. Biến ngẫu nhiên là gì?
1. What are the null and alternative hypotheses? Write the null and alternative hypotheses in words and in symbols.
1. Các giả thuyết không và đối thuyết là gì? Viết các giả thuyết không và đối thuyết bằng lời và bằng ký hiệu.
1. Is this test right, left, or two tailed?
1. Đây là kiểm định một phía bên phải, bên trái, hay hai phía?
1. What is the *p*-value?
1. *p*-giá trị là bao nhiêu?
1. Do you reject or not reject the null hypothesis?
1. Bạn bác bỏ hay không bác bỏ giả thuyết không?
1. At the ___ level of significance, from the sample data, there ______ (is/is not) sufficient evidence to conclude that ______.
1. Tại mức ý nghĩa ___, từ dữ liệu mẫu, ______ (có/không có) đủ bằng chứng để kết luận rằng ______.
1. Calculate Cohen’s *d* and interpret it.
1. Tính Cohen’s *d* và giải thích nó.
