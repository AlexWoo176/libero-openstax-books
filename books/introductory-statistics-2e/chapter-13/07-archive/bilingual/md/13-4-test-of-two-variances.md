## 13.4
 
Test of Two Variances

## 13.4
 
Kiểm định hai phương sai

Another of the uses of the *F* distribution is testing two variances. It is often desirable to compare two variances rather than two averages. For instance, college administrators would like two college professors grading exams to have the same variation in their grading. In order for a lid to fit a container, the variation in the lid and the container should be the same. A supermarket might be interested in the variability of check-out times for two checkers.

Một trong những ứng dụng khác của phân phối *F* là kiểm định hai phương sai. Việc so sánh hai phương sai thường được ưu tiên hơn so với việc so sánh hai giá trị trung bình. Ví dụ, các nhà quản lý trường đại học muốn hai giảng viên chấm bài thi có cùng mức độ biến thiên trong cách chấm điểm của họ. Để một chiếc nắp vừa khít với hộp, độ biến thiên của nắp và hộp phải giống nhau. Một siêu thị có thể quan tâm đến độ biến thiên thời gian thanh toán của hai nhân viên thu ngân.

In order to perform a *F* test of two variances, it is important that the following are true:

Để thực hiện kiểm định *F* cho hai phương sai, điều quan trọng là các điều kiện sau phải đúng:

1. The populations from which the two samples are drawn are normally distributed.
1. Các quần thể mà từ đó hai mẫu được rút ra có phân phối chuẩn.
1. The two populations are independent of each other.
1. Hai quần thể độc lập với nhau.
Unlike most other tests in this book, the *F* test for equality of two variances is very sensitive to deviations from normality. If the two distributions are not normal, the test can give higher *p*-values than it should, or lower ones, in ways that are unpredictable. Many texts suggest that students not use this test at all, but in the interest of completeness we include it here.

Không giống như hầu hết các kiểm định khác trong cuốn sách này, kiểm định *F* về sự bằng nhau của hai phương sai rất nhạy cảm với các sai lệch so với phân phối chuẩn. Nếu hai phân phối không phải là phân phối chuẩn, kiểm định có thể đưa ra các p-giá trị *p* cao hơn hoặc thấp hơn mức cần thiết theo những cách không thể dự đoán trước. Nhiều tài liệu khuyên sinh viên không nên sử dụng kiểm định này, nhưng vì mục đích hoàn thiện, chúng tôi đưa nó vào đây.

Suppose we sample randomly from two independent normal populations. Let 

σ
1
2

σ
1
2

 and 

σ
2
2

σ
2
2

 be the population variances and 

s
1
2

s
1
2

 and 

s
2
2

s
2
2

 be the sample variances. Let the
sample sizes be *n*_1 and *n*_2. Since we are interested in comparing the two sample variances, we use the *F* ratio:

Giả sử chúng ta lấy mẫu ngẫu nhiên từ hai quần thể độc lập có phân phối chuẩn. Gọi 

σ
1
2

σ
1
2

 và 

σ
2
2

σ
2
2

 là các phương sai quần thể, và 

s
1
2

s
1
2

 và 

s
2
2

s
2
2

 là các phương sai mẫu. Gọi kích thước mẫu là *n*_1 và *n*_2. Vì chúng ta quan tâm đến việc so sánh hai phương sai mẫu, chúng ta sử dụng tỷ số *F*:

F=

[ 

(
s
1

)

2

(
σ
1

)

2

 ]

[ 

(
s
2

)

2

(
σ
2

)

2

 ]

F=

[ 

(
s
1

)

2

(
σ
1

)

2

 ]

[ 

(
s
2

)

2

(
σ
2

)

2

 ]

F=

[ 

(
s
1

)

2

(
σ
1

)

2

 ]

[ 

(
s
2

)

2

(
σ
2

)

2

 ]

F=

[ 

(
s
1

)

2

(
σ
1

)

2

 ]

[ 

(
s
2

)

2

(
σ
2

)

2

 ]

*F* has the distribution *F* ~ *F*(*n*_1 – 1, *n*_2 – 1)

*F* có phân phối *F* ~ *F*(*n*_1 – 1, *n*_2 – 1)

where *n*_1 – 1 are the degrees of freedom for the numerator and *n*_2 – 1 are the degrees of freedom for the denominator.

trong đó *n*_1 – 1 là bậc tự do cho tử số và *n*_2 – 1 là bậc tự do cho mẫu số.

If the null hypothesis is 

σ
1
2

=
σ
2
2

σ
1
2

=
σ
2
2

, then the *F* Ratio becomes 

F=

[ 

(
s
1

)

2

(
σ
1

)

2

 ]

[ 

(
s
2

)

2

(
σ
2

)

2

 ]

=

(
s
1

)

2

(
s
2

)

2

F=

[ 

(
s
1

)

2

(
σ
1

)

2

 ]

[ 

(
s
2

)

2

(
σ
2

)

2

 ]

=

(
s
1

)

2

(
s
2

)

2

.

Nếu giả thuyết không là 

σ
1
2

=
σ
2
2

σ
1
2

=
σ
2
2

, thì Tỷ số *F* trở thành 

F=

[ 

(
s
1

)

2

(
σ
1

)

2

 ]

[ 

(
s
2

)

2

(
σ
2

)

2

 ]

=

(
s
1

)

2

(
s
2

)

2

F=

[ 

(
s
1

)

2

(
σ
1

)

2

 ]

[ 

(
s
2

)

2

(
σ
2

)

2

 ]

=

(
s
1

)

2

(
s
2

)

2

.

The *F* ratio could also be 

(
s
2

)

2

(
s
1

)

2

(
s
2

)

2

(
s
1

)

2

.

 It depends on *H_a* and on which sample variance is larger.

Tỷ số *F* cũng có thể là 

(
s
2

)

2

(
s
1

)

2

(
s
2

)

2

(
s
1

)

2

.

 Điều này phụ thuộc vào *H_a* và vào việc phương sai mẫu nào lớn hơn.

If the two populations have equal variances, then 

s
1
2

s
1
2

 and 

s
2
2

s
2
2

 are close in value and 

F=

(
s
1

)

2

(
s
2

)

2

F=

(
s
1

)

2

(
s
2

)

2

 is close to one. But if the two population variances are very different, 

s
1
2

s
1
2

 and 

s
2
2

s
2
2

 tend to be very different, too. Choosing 

s
1
2

s
1
2

 as the larger sample variance causes the ratio 

(
s
1

)

2

(
s
2

)

2

(
s
1

)

2

(
s
2

)

2

 to be greater than one. If 

s
1
2

s
1
2

 and 

s
2
2

s
2
2

 are far apart, then 

F=

(
s
1

)

2

(
s
2

)

2

F=

(
s
1

)

2

(
s
2

)

2

 is a large number.

Nếu hai quần thể có phương sai bằng nhau, thì 

s
1
2

s
1
2

 và 

s
2
2

s
2
2

 có giá trị gần nhau và 

F=

(
s
1

)

2

(
s
2

)

2

F=

(
s
1

)

2

(
s
2

)

2

 gần bằng một. Nhưng nếu hai phương sai quần thể rất khác nhau, 

s
1
2

s
1
2

 và 

s
2
2

s
2
2

 cũng có xu hướng rất khác nhau. Việc chọn 

s
1
2

s
1
2

 là phương sai mẫu lớn hơn sẽ làm cho tỷ số 

(
s
1

)

2

(
s
2

)

2

(
s
1

)

2

(
s
2

)

2

 lớn hơn một. Nếu 

s
1
2

s
1
2

 và 

s
2
2

s
2
2

 cách xa nhau, thì 

F=

(
s
1

)

2

(
s
2

)

2

F=

(
s
1

)

2

(
s
2

)

2

 là một số lớn.

Therefore, if *F* is close to one, the evidence favors the null hypothesis (the two population variances are equal). But if *F* is much larger than one, then the evidence is against the null hypothesis. **A test of two variances may be left, right, or two-tailed.**

Do đó, nếu *F* gần bằng một, bằng chứng ủng hộ giả thuyết không (hai phương sai quần thể bằng nhau). Nhưng nếu *F* lớn hơn nhiều so với một, thì bằng chứng chống lại giả thuyết không. **Kiểm định hai phương sai có thể là kiểm định phía trái, phía phải hoặc hai phía.**

#### Problem

#### Bài tập

Two college instructors are interested in whether or not there is any variation in the way they grade math exams. They each grade the same set of 30 exams. The first instructor's grades have a variance of 52.3. The second instructor's grades have a variance of 89.9. Test the claim that the first instructor's variance is smaller. (In most colleges, it is desirable for the variances of exam grades to be nearly the same among instructors.) The level of significance is 10%.

Hai giảng viên đại học quan tâm đến việc liệu có bất kỳ sự biến thiên nào trong cách họ chấm bài thi toán hay không. Mỗi người chấm cùng một bộ 30 bài thi. Điểm của giảng viên thứ nhất có phương sai là 52,3. Điểm của giảng viên thứ hai có phương sai là 89,9. Hãy kiểm định khẳng định rằng phương sai của giảng viên thứ nhất nhỏ hơn. (Ở hầu hết các trường đại học, phương sai điểm thi giữa các giảng viên nên gần như bằng nhau). Mức ý nghĩa là 10%.

The New York Choral Society divides its singers who are men up into four categories from highest voices to lowest: Tenor1, Tenor2, Bass1, Bass2. In the table are heights of the men in the Tenor1 and Bass2 groups. One suspects that taller men will have lower voices, and that the variance of height may go up with the lower voices as well. Do we have good evidence that the variance of the heights of singers in each of these two groups (Tenor1 and Bass2) are different?

Hiệp hội Hợp xướng New York chia các ca sĩ nam thành bốn loại từ giọng cao nhất đến thấp nhất: Tenor1, Tenor2, Bass1, Bass2. Trong bảng là chiều cao của các nam ca sĩ trong nhóm Tenor1 và Bass2. Người ta nghi ngờ rằng những người đàn ông cao hơn sẽ có giọng trầm hơn, và phương sai chiều cao cũng có thể tăng lên cùng với các giọng trầm hơn. Chúng ta có bằng chứng tốt cho thấy phương sai chiều cao của các ca sĩ trong mỗi nhóm này (Tenor1 và Bass2) là khác nhau không?

| Tenor1 | Tenor1 | Bass2 | Bass2 | Tenor 1 | Tenor 1 | Bass 2 | Bass 2 | Tenor 1 | Tenor 1 | Bass 2 | Bass 2 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 69 | 69 | 72 | 72 | 67 | 67 | 72 | 72 | 68 | 68 | 67 | 67 |
| 72 | 72 | 75 | 75 | 70 | 70 | 74 | 74 | 67 | 67 | 70 | 70 |
| 71 | 71 | 67 | 67 | 65 | 65 | 70 | 70 | 64 | 64 | 70 | 70 |
| 66 | 66 | 75 | 75 | 72 | 72 | 66 | 66 |  |  | 69 | 69 |
| 76 | 76 | 74 | 74 | 70 | 70 | 68 | 68 |  |  | 72 | 72 |
| 74 | 74 | 72 | 72 | 68 | 68 | 75 | 75 |  |  | 71 | 71 |
| 71 | 71 | 72 | 72 | 64 | 64 | 68 | 68 |  |  | 74 | 74 |
| 66 | 66 | 74 | 74 | 73 | 73 | 70 | 70 |  |  | 75 | 75 |
| 68 | 68 | 72 | 72 | 66 | 66 | 72 | 72 |  |  |  |  |
