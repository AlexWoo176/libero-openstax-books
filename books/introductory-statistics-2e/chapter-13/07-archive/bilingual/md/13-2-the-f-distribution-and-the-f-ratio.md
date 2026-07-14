## 13.2
 
The F Distribution and the F-Ratio

## 13.2
 
Phân phối F và Tỷ số F

The distribution used for the hypothesis test is a new one. It is called the *F* distribution, named after Sir Ronald Fisher, an English statistician. The *F* statistic is a ratio (a fraction). There are two sets of degrees of freedom; one for the numerator and one for the denominator.

Phân phối được sử dụng cho kiểm định giả thuyết là một phân phối mới. Nó được gọi là *F* phân phối, được đặt tên theo Sir Ronald Fisher, một nhà thống kê người Anh. Thống kê *F* là một tỷ số (một phân số). Có hai tập hợp bậc tự do; một cho tử số và một cho mẫu số.

For example, if *F* follows an *F* distribution and the number of degrees of freedom for the numerator is four, and the number of degrees of freedom for the denominator is ten, then *F* ~ *F_4,10*.

Ví dụ, nếu *F* tuân theo một *F* phân phối và số bậc tự do cho tử số là bốn, và số bậc tự do cho mẫu số là mười, thì *F* ~ *F_4,10*.

The *F* distribution is derived from the Student's t-distribution. The values of the *F* distribution are squares of the corresponding values of the *t*-distribution. One-Way ANOVA expands the *t*-test for comparing more than two groups. The scope of that derivation is beyond the level of this course. It is preferable to use ANOVA when there are more than two groups instead of performing pairwise *t*-tests because performing multiple tests introduces the likelihood of making a Type 1 error.

Phân phối *F* được suy ra từ phân phối t của Student. Các giá trị của phân phối *F* là bình phương của các giá trị tương ứng của phân phối *t*. Phân tích phương sai một chiều (One-Way ANOVA) mở rộng kiểm định *t* để so sánh nhiều hơn hai nhóm. Phạm vi của phép suy dẫn đó nằm ngoài trình độ của khóa học này. Tốt hơn là nên sử dụng ANOVA khi có nhiều hơn hai nhóm thay vì thực hiện các kiểm định *t* theo cặp vì việc thực hiện nhiều kiểm định sẽ làm tăng khả năng mắc sai lầm loại I.

To calculate the *F* ratio, two estimates of the variance are made.

Để tính *F* tỷ số, hai ước lượng về phương sai được thực hiện.

1. Variance between samples**:** An estimate of *σ*^2 that is the variance of the sample means multiplied by *n* (when the sample sizes are the same.). If the samples are different sizes, the variance between samples is weighted to account for the different sample sizes. The variance is also called **variation due to treatment or explained variation.**
1. Phương sai giữa các mẫu**:** Một ước lượng của *σ*^2 là phương sai của các số trung bình mẫu nhân với *n* (khi các kích thước mẫu bằng nhau). Nếu các mẫu có kích thước khác nhau, phương sai giữa các mẫu được gán trọng số để tính đến các kích thước mẫu khác nhau. Phương sai này còn được gọi là **sự biến thiên do nghiệm thức hoặc sự biến thiên được giải thích.**
1. Variance within samples**:** An estimate of *σ*^2 that is the average of the sample variances (also known as a pooled variance). When the sample sizes are different, the variance within samples is weighted. The variance is also called the **variation due to error or unexplained variation.**
1. Phương sai trong nội bộ mẫu**:** Một ước lượng của *σ*^2 là số trung bình của các phương sai mẫu (còn được gọi là phương sai gộp). Khi các kích thước mẫu khác nhau, phương sai trong nội bộ mẫu được gán trọng số. Phương sai này còn được gọi là **sự biến thiên do sai số hoặc sự biến thiên không được giải thích.**
- *SS*_between = the sum of squares that represents the variation among the different samples
- *SS*_between = tổng các bình phương đại diện cho sự biến thiên giữa các mẫu khác nhau
- *SS*_within = the sum of squares that represents the variation within samples that is due to chance.
- *SS*_within = tổng các bình phương đại diện cho sự biến thiên trong nội bộ mẫu do ngẫu nhiên.
To find a "sum of squares" means to add together squared quantities that, in some
cases, may be weighted. We used sum of squares to calculate the sample variance and
the sample standard deviation in [Descriptive Statistics](2-introduction).

Để tìm "tổng các bình phương" có nghĩa là cộng các đại lượng bình phương lại với nhau, trong một số trường hợp, có thể được gán trọng số. Chúng ta đã sử dụng tổng các bình phương để tính phương sai mẫu và độ lệch chuẩn mẫu trong [Thống kê mô tả](2-introduction).

*MS* means "mean square." *MS*_between is the variance between groups, and *MS*_within is the variance within groups.

*MS* có nghĩa là "bình phương trung bình." *MS*_between là phương sai giữa các nhóm, và *MS*_within là phương sai trong nội bộ nhóm.

**Calculation of Sum of Squares and Mean Square**

**Tính toán Tổng các bình phương và Bình phương trung bình**

- *k* = the number of different groups
- *k* = số lượng các nhóm khác nhau
- *n_j* = the size of the *j^th* group
- *n_j* = kích thước của nhóm *j^th*
- *s_j* = the sum of the values in the *j^th* group
- *s_j* = tổng các giá trị trong nhóm *j^th*
- *n* = total number of all the values combined (total sample size: ∑*n_j*)
- *n* = tổng số tất cả các giá trị kết hợp (tổng kích thước mẫu: ∑*n_j*)
- *x* = one value: ∑*x* = ∑*s_j*
- *x* = một giá trị: ∑*x* = ∑*s_j*
- Sum of squares of all values from every group combined: ∑*x*^2
- Tổng các bình phương của tất cả các giá trị từ mọi nhóm kết hợp: ∑*x*^2
- Total sum of squares: SStotal=∑x2

(

∑x

)

2

n

SStotal=∑x2

(

∑x

)

2

n
- Tổng các bình phương: SStotal=∑x2

(

∑x

)

2

n

SStotal=∑x2

(

∑x

)

2

n
- Explained variation: sum of squares representing variation among the different samples: *SS*_between =  

∑[ 

(
s
j
)

2

n
j

 ]−

(∑
s
j

)

2

n

∑[ 

(
s
j
)

2

n
j

 ]−

(∑
s
j

)

2

n
- Sự biến thiên được giải thích: tổng các bình phương đại diện cho sự biến thiên giữa các mẫu khác nhau: *SS*_between = 

∑[ 

(
s
j
)

2

n
j

 ]−

(∑
s
j

)

2

n

∑[ 

(
s
j
)

2

n
j

 ]−

(∑
s
j

)

2

n
- Unexplained variation: sum of squares representing variation within samples due to chance:  

S
S

within

=S
S

total

–S
S

between

S
S

within

=S
S

total

–S
S

between
- Sự biến thiên không được giải thích: tổng các bình phương đại diện cho sự biến thiên trong nội bộ mẫu do ngẫu nhiên: 

S
S

within

=S
S

total

–S
S

between

S
S

within

=S
S

total

–S
S

between
- *df*'s for different groups (*df*'s for the numerator): dfbetweendfbetween = *k* – 1
- *df* cho các nhóm khác nhau (*df* cho tử số): dfbetweendfbetween = *k* – 1
- Equation for errors within samples (*df*'s for the denominator): *df*_within = *n* – *k*
- Phương trình cho các sai số trong nội bộ mẫu (*df* cho mẫu số): *df*_within = *n* – *k*
- Mean square (variance estimate) explained by the different groups: *MS*_between =  

S
S

between

df

between

S
S

between

df

between
- Bình phương trung bình (ước lượng phương sai) được giải thích bởi các nhóm khác nhau: *MS*_between = 

S
S

between

df

between

S
S

between

df

between
- Mean square (variance estimate) that is due to chance (unexplained): *MS*_within =  

S
S

within

d
f

within

S
S

within

d
f

within
- Bình phương trung bình (ước lượng phương sai) do ngẫu nhiên (không được giải thích): *MS*_within = 

S
S

within

d
f

within

S
S

within

d
f

within
*MS*_between and *MS*_within can be written as follows:

*MS*_between và *MS*_within có thể được viết như sau:

- M
S

between

=

S
S

between

d
f

between

=

S
S

between

k−1

M
S

between

=

S
S

between

d
f

between

=

S
S

between

k−1
- M
S

between

=

S
S

between

d
f

between

=

S
S

between

k−1

M
S

between

=

S
S

between

d
f

between

=

S
S

between

k−1
- M
S

within

=

S
S

within

d
f

within

=

S
S

within

n−k

M
S

within

=

S
S

within

d
f

within

=

S
S

within

n−k
- M
S

within

=

S
S

within

d
f

within

=

S
S

within

n−k

M
S

within

=

S
S

within

d
f

within

=

S
S

within

n−k
The one-way ANOVA test depends on the fact that *MS*_between can be influenced by population differences among means of the several groups. Since *MS*_within compares values of each group to its own group mean, the fact that group means might be different does not affect *MS*_within.

Kiểm định ANOVA một chiều phụ thuộc vào thực tế là *MS*_between có thể bị ảnh hưởng bởi sự khác biệt quần thể giữa các số trung bình của nhiều nhóm. Vì *MS*_within so sánh các giá trị của mỗi nhóm với số trung bình của chính nhóm đó, thực tế là các số trung bình nhóm có thể khác nhau không ảnh hưởng đến *MS*_within.

The null hypothesis says that all groups are samples from populations having the same normal distribution. The alternate hypothesis says that at least two of the sample groups come from populations with different normal distributions. If the null hypothesis is true, *MS*_between and *MS*_within should both estimate the same value.

Giả thuyết không cho rằng tất cả các nhóm đều là các mẫu từ các quần thể có cùng phân phối chuẩn. Đối thuyết cho rằng ít nhất hai trong số các nhóm mẫu đến từ các quần thể có phân phối chuẩn khác nhau. Nếu giả thuyết không đúng, *MS*_between và *MS*_within đều nên ước lượng cùng một giá trị.

The null hypothesis says that all the group population means are equal. The hypothesis of equal means implies that the populations have the same normal distribution, because it is assumed that the populations are normal and that they have equal variances.

Giả thuyết không cho rằng tất cả các số trung bình quần thể nhóm đều bằng nhau. Giả thuyết về các số trung bình bằng nhau ngụ ý rằng các quần thể có cùng phân phối chuẩn, vì giả định rằng các quần thể là chuẩn và chúng có các phương sai bằng nhau.

*F*-Ratio or *F* Statistic

F=

M
S

between

M
S

within

F=

M
S

between

M
S

within

*F*-Tỷ số hoặc *F* Thống kê

F=

M
S

between

M
S

within

F=

M
S

between

M
S

within

If *MS*_between and *MS*_within estimate the same value (following the belief that *H_0* is true), then the *F*-ratio should be approximately equal to one. Mostly, just sampling errors would contribute to variations away from one. As it turns out, *MS*_between consists of the population variance plus a variance produced from the differences between the samples. *MS*_within is an estimate of the population variance. Since variances are always positive, if the null hypothesis is false, *MS*_between will generally be larger than *MS*_within.Then the *F*-ratio will be larger than one. However, if the population effect is small, it is not unlikely that *MS*_within will be larger in a given sample.

Nếu *MS*_between và *MS*_within ước lượng cùng một giá trị (theo niềm tin rằng *H_0* là đúng), thì tỷ số *F* nên xấp xỉ bằng một. Phần lớn, chỉ các sai số chọn mẫu mới góp phần vào các biến thiên khác một. Hóa ra, *MS*_between bao gồm phương sai quần thể cộng với một phương sai được tạo ra từ sự khác biệt giữa các mẫu. *MS*_within là một ước lượng của phương sai quần thể. Vì các phương sai luôn dương, nếu giả thuyết không sai, *MS*_between thường sẽ lớn hơn *MS*_within. Khi đó tỷ số *F* sẽ lớn hơn một. Tuy nhiên, nếu hiệu ứng quần thể nhỏ, không loại trừ khả năng *MS*_within sẽ lớn hơn trong một mẫu nhất định.

The foregoing calculations were done with groups of different sizes. If the groups are the same size, the calculations simplify somewhat and the *F*-ratio can be written as:

Các tính toán trên được thực hiện với các nhóm có kích thước khác nhau. Nếu các nhóm có cùng kích thước, các tính toán sẽ đơn giản hóa phần nào và tỷ số *F* có thể được viết là:

*F*-Ratio Formula when the groups are the same size

F=

n⋅
s

x
¯

2

s
2

pooled

F=

n⋅
s

x
¯

2

s
2

pooled

Công thức tỷ số *F* khi các nhóm có cùng kích thước

F=

n⋅
s

x
¯

2

s
2

pooled

F=

n⋅
s

x
¯

2

s
2

pooled

- *n* = the sample size
- *n* = kích thước mẫu
- *df*_numerator = *k* – 1
- *df*_numerator = *k* – 1
- *df*_denominator = *n* – *k*
- *df*_denominator = *n* – *k*
- *s*^2 pooled = the mean of the sample variances (pooled variance)
- *s*^2 pooled = trung bình của các phương sai mẫu (phương sai gộp)
- s

x
¯

2

s

x
¯

2

  = the variance of the sample means
- s

x
¯

2

s

x
¯

2

 = phương sai của các trung bình mẫu
Data are typically put into a table for easy viewing.  One-Way ANOVA results are often displayed in this manner by computer software.

Dữ liệu thường được đưa vào bảng để dễ quan sát. Kết quả ANOVA một chiều thường được hiển thị theo cách này bởi phần mềm máy tính.

| Source of Variation | Nguồn biến thiên | Sum of Squares (*SS*) | Tổng các bình phương (*SS*) | Degrees of Freedom (*df*) | Bậc tự do (*df*) | Mean Square (*MS*) | Bình phương trung bình (*MS*) | *F* | *F* |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Factor 
(Between) | Nhân tố 
(Giữa các nhóm) | *SS*(Factor) | *SS*(Nhân tố) | *k* – 1 | *k* – 1 | *MS*(Factor) = *SS*(Factor)/(*k* – 1) | *MS*(Nhân tố) = *SS*(Nhân tố)/(*k* – 1) | *F* = *MS*(Factor)/*MS*(Error) | *F* = *MS*(Nhân tố)/*MS*(Sai số) |
| Error 
(Within) | Sai số 
(Trong nội bộ nhóm) | *SS*(Error) | *SS*(Sai số) | *n* – *k* | *n* – *k* | *MS*(Error) = *SS*(Error)/(*n* – *k*) | *MS*(Sai số) = *SS*(Sai số)/(*n* – *k*) |  |  |
| Total | Tổng | *SS*(Total) | *SS*(Tổng) | *n* – 1 | *n* – 1 |  |  |  |  |

Three different diet plans are to be tested for mean weight loss. The entries in the table are the weight losses for the different plans. The one-way ANOVA results are shown in [Table 13.2](13-2-the-f-distribution-and-the-f-ratio#eip-id2754369).

Ba kế hoạch ăn kiêng khác nhau sẽ được kiểm định về số trung bình giảm cân. Các mục trong bảng là mức giảm cân cho các kế hoạch khác nhau. Kết quả ANOVA một chiều được hiển thị trong [Bảng 13.2](13-2-the-f-distribution-and-the-f-ratio#eip-id2754369).

| Plan 1: *n*_1 = 4 | Kế hoạch 1: *n*_1 = 4 | Plan 2: *n*_2 = 3 | Kế hoạch 2: *n*_2 = 3 | Plan 3: *n*_3 = 3 | Kế hoạch 3: *n*_3 = 3 |
| --- | --- | --- | --- | --- | --- |
| 5 | 5 | 3.5 | 3,5 | 8 | 8 |
| 4.5 | 4,5 | 7 | 7 | 4 | 4 |
| 4 | 4 |  |  | 3.5 | 3,5 |
| 3 | 3 | 4.5 | 4,5 |  |  |

*s*_1 = 16.5, *s*_2 =15, *s*_3 = 15.5

*s*_1 = 16,5, *s*_2 =15, *s*_3 = 15,5

Following are the calculations needed to fill in the one-way ANOVA table. The table is used to conduct a hypothesis test.

Sau đây là các tính toán cần thiết để điền vào bảng ANOVA một chiều. Bảng được sử dụng để thực hiện kiểm định giả thuyết.

where *n*_1 = 4, *n*_2 = 3, *n*_3 = 3  and  *n* = *n*_1 + *n*_2 + *n*_3 = 10

trong đó *n*_1 = 4, *n*_2 = 3, *n*_3 = 3 và *n* = *n*_1 + *n*_2 + *n*_3 = 10

One-Way ANOVA Table:  The formulas for `*SS*(Total)`, `*SS*(Factor) = *SS*(Between) and *SS*(Error) = *SS*(Within)` as shown previously. The same information is provided by the TI calculator hypothesis test function `ANOVA` in STAT TESTS (syntax is `ANOVA(L1, L2, L3)` where L1, L2, L3 have the data from Plan 1, Plan 2, Plan 3 respectively).

Bảng ANOVA một chiều: Các công thức cho `*SS*(Total)`, `*SS*(Factor) = *SS*(Between) and *SS*(Error) = *SS*(Within)` như đã trình bày trước đó. Thông tin tương tự được cung cấp bởi chức năng kiểm định giả thuyết máy tính TI `ANOVA` trong STAT TESTS (cú pháp là `ANOVA(L1, L2, L3)` trong đó L1, L2, L3 có dữ liệu từ Kế hoạch 1, Kế hoạch 2, Kế hoạch 3 tương ứng).

| Source of Variation | Nguồn biến thiên | Sum of Squares (*SS*) | Tổng các bình phương (*SS*) | Degrees of Freedom (*df*) | Bậc tự do (*df*) | Mean Square (*MS*) | Bình phương trung bình (*MS*) | *F* | *F* |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Factor 
(Between) | Nhân tố 
(Giữa các nhóm) | *SS*(Factor) 
= *SS*(Between) 
= 2.2458 | *SS*(Nhân tố) 
= *SS*(Giữa các nhóm) 
= 2,2458 | *k* – 1 
= 3 groups – 1 
= 2 | *k* – 1 
= 3 nhóm – 1 
= 2 | *MS*(Factor) 
= *SS*(Factor)/(*k* – 1)
 = 2.2458/2 
= 1.1229 | *MS*(Nhân tố) 
= *SS*(Nhân tố)/(*k* – 1)
 = 2,2458/2 
= 1,1229 | *F* =
 *MS*(Factor)/*MS*(Error) 
= 1.1229/2.9792 
= 0.3769 | *F* =
 *MS*(Nhân tố)/*MS*(Sai số) 
= 1,1229/2,9792 
= 0,3769 |
| Error 
(Within) | Sai số 
(Trong nội bộ nhóm) | *SS*(Error) 
= *SS*(Within) 
= 20.8542 | *SS*(Sai số) 
= *SS*(Trong nội bộ) 
= 20,8542 | *n* – *k* 
= 10 total data – 3 groups 
= 7 | *n* – *k* 
= 10 dữ liệu tổng cộng – 3 nhóm 
= 7 | *MS*(Error) 
= *SS*(Error)/(*n* – *k*) 
= 20.8542/7 
= 2.9792 | *MS*(Sai số) 
= *SS*(Sai số)/(*n* – *k*) 
= 20,8542/7 
= 2,9792 |  |  |
| Total | Tổng | *SS*(Total) 
= 2.2458 + 20.8542 
= 23.1 | *SS*(Tổng) 
= 2,2458 + 20,8542 
= 23,1 | *n* – 1 
= 10 total data – 1 
= 9 | *n* – 1 
= 10 dữ liệu tổng cộng – 1 
= 9 |  |  |  |  |

As part of an experiment to see how different types of soil cover would affect slicing tomato production, Marist College students grew tomato plants under different soil cover conditions. Groups of three plants each had one of the following treatments

Là một phần của thí nghiệm để xem các loại che phủ đất khác nhau sẽ ảnh hưởng như thế nào đến sản lượng cà chua thái lát, sinh viên trường Marist College đã trồng cây cà chua trong các điều kiện che phủ đất khác nhau. Các nhóm gồm ba cây mỗi nhóm đã nhận một trong các nghiệm thức sau

- bare soil
- đất trống
- a commercial ground cover
- một loại vật liệu phủ đất thương mại
- black plastic
- nhựa đen
- straw
- rơm
- compost
- phân hữu cơ
All plants grew under the same conditions and were the same variety.  Students recorded the weight (in grams) of tomatoes produced by each of the *n* = 15 plants:

Tất cả các cây đều phát triển trong cùng điều kiện và cùng một giống. Sinh viên đã ghi lại trọng lượng (tính bằng gram) cà chua được sản xuất bởi mỗi cây trong số *n* = 15 cây:

| Bare: *n*_1 = 3 | Đất trống: *n*_1 = 3 | Ground Cover: *n*_2 = 3 | Vật liệu phủ đất: *n*_2 = 3 | Plastic: *n*_3 = 3 | Nhựa: *n*_3 = 3 | Straw: *n*_4 = 3 | Rơm: *n*_4 = 3 | Compost: *n*_5 = 3 | Phân hữu cơ: *n*_5 = 3 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 2,625 | 2,625 | 5,348 | 5,348 | 6,583 | 6,583 | 7,285 | 7,285 | 6,277 | 6,277 |
| 2,997 | 2,997 | 5,682 | 5,682 | 8,560 | 8,560 | 6,897 | 6,897 | 7,818 | 7,818 |
| 4,915 | 4,915 | 5,482 | 5,482 | 3,830 | 3,830 | 9,230 | 9,230 | 8,677 | 8,677 |

Create the one-way ANOVA table.

Tạo bảng ANOVA một chiều.

**The one-way ANOVA hypothesis test is always right-tailed** because larger *F*-values are way out in the right tail of the *F*-distribution curve and tend to make us reject *H_0*.

**Kiểm định giả thuyết ANOVA một chiều luôn là kiểm định phía bên phải** vì các giá trị *F* lớn hơn nằm xa ở đuôi bên phải của đường cong phân phối *F* và có xu hướng khiến chúng ta bác bỏ *H_0*.

### Notation

### Ký hiệu

The notation for the *F* distribution is *F* ~ *F*_*df*(*num*),*df*(*denom*)

Ký hiệu cho phân phối *F* là *F* ~ *F*_*df*(*num*),*df*(*denom*)

where *df*(*num*) = *df*_between and *df*(*denom*) = *df*_within

trong đó *df*(*num*) = *df*_between và *df*(*denom*) = *df*_within

The mean for the *F* distribution is  

μ=

df(denom)

df(denom)–2

μ=

df(denom)

df(denom)–2

Số trung bình cho phân phối *F* là 

μ=

df(denom)

df(denom)–2

μ=

df(denom)

df(denom)–2
