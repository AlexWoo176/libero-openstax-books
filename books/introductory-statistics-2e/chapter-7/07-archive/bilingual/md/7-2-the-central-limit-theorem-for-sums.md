## 7.2
 
The Central Limit Theorem for Sums

## 7.2
 
Định lý giới hạn trung tâm cho các tổng

Suppose *X* is a random variable with a distribution that may be **known or unknown** (it can be any distribution) and suppose:

Giả sử *X* là một biến ngẫu nhiên với một phân phối có thể **đã biết hoặc chưa biết** (nó có thể là bất kỳ phân phối nào) và giả sử:

1. *μ_X* = the mean of *Î§*
1. *μ_X* = số trung bình của *Î§*
1. *σ_Î§* = the standard deviation of *X*
1. *σ_Î§* = độ lệch chuẩn của *X*
If you draw random samples of size *n*, then as *n* increases, the random variable Σ*X* consisting of sums tends to be normally distributed and Σ*Î§* ~ *N*((*n*)(*μ_Î§*), (

n

n

)(*σ_Î§*)).

Nếu bạn rút các mẫu ngẫu nhiên có kích thước *n*, thì khi *n* tăng lên, biến ngẫu nhiên Σ*X* bao gồm các tổng có xu hướng Có phân phối chuẩn và Σ*Î§* ~ *N*((*n*)(*μ_Î§*), (

n

n

)(*σ_Î§*)).

**The** central limit theorem for sums says that if you repeatedly draw samples of a given size (such as repeatedly rolling ten dice) and calculate the sum of each sample, these sums tend to follow a normal distribution. As sample sizes increase, the distribution of means more closely follows the normal distribution. **The normal distribution has a mean equal to the original mean multiplied by the sample size and a standard deviation equal to the original standard deviation multiplied by the square root of the sample size.**

**Định lý** Định lý giới hạn trung tâm cho tổng phát biểu rằng nếu bạn liên tục rút các mẫu có kích thước nhất định (chẳng hạn như liên tục gieo mười con xúc xắc) và tính tổng của mỗi mẫu, các tổng này có xu hướng tuân theo phân phối chuẩn. Khi kích thước mẫu tăng lên, phân phối của các số trung bình càng tuân theo phân phối chuẩn chặt chẽ hơn. **Phân phối chuẩn có số trung bình bằng số trung bình ban đầu nhân với kích thước mẫu và độ lệch chuẩn bằng độ lệch chuẩn ban đầu nhân với căn bậc hai của kích thước mẫu.**

The random variable Σ*X* has the following *z*-score associated with it:

Biến ngẫu nhiên Σ*X* có điểm *z* liên quan sau đây:

1. Σ*x* is one sum.
1. Σ*x* là một tổng.
1. z = 

Σx–(n)(
μ
X

)

(
n

)(
σ
X

)

z = 

Σx–(n)(
μ
X

)

(
n

)(
σ
X

)

(*n*)(*μ_X*) = the mean of Σ*X*(*n*)(*μ_X*) = số trung bình của Σ*X*

(
n

)(
σ
X

)

(
n

)(
σ
X

)
 = standard deviation of 

ΣX

ΣX

(
n

)(
σ
X

)

(
n

)(
σ
X

)
 = độ lệch chuẩn của 

ΣX

ΣX
To find probabilities for sums on the calculator, follow these steps.

Để tìm xác suất cho các tổng trên máy tính, hãy làm theo các bước sau.

2^nd `DISTR`

2:`normalcdf`

`normalcdf`(lower value of the area, upper value of the area, (*n*)(mean), (

n

n

)(standard deviation))

2^nd `DISTR`

2:`normalcdf`

`normalcdf`(giá trị thấp hơn của vùng, giá trị cao hơn của vùng, (*n*)(số trung bình), (

n

n

)(độ lệch chuẩn))

where:

trong đó:

- *mean* is the mean of the original distribution
- *số trung bình* là số trung bình của phân phối ban đầu
- *standard deviation* is the standard deviation of the original distribution
- *độ lệch chuẩn* là độ lệch chuẩn của phân phối gốc
- *sample size* = n
- Kích thước mẫu = n
An unknown distribution has a mean of 90 and a standard deviation of 15. A sample of size 80 is drawn randomly from the population.

Một phân phối chưa biết có số trung bình là 90 và độ lệch chuẩn là 15. Một mẫu có kích thước 80 được rút ngẫu nhiên từ quần thể.

#### Problem

#### Bài toán

1. Find the probability that the sum of the 80 values (or the total of the 80 values) is more than 7,500.
1. Tìm xác suất để tổng của 80 giá trị (hoặc tổng của 80 giá trị đó) lớn hơn 7,500.
1. Find the sum that is 1.5 standard deviations above the mean of the sums.
1. Tìm tổng lớn hơn số trung bình của các tổng là 1,5 độ lệch chuẩn.
An unknown distribution has a mean of 45 and a standard deviation of eight. A sample size of 50 is drawn randomly from the population. Find the probability that the sum of the 50 values is more than 2,400.

Một phân phối chưa biết có số trung bình là 45 và độ lệch chuẩn là tám. Một kích thước mẫu là 50 được rút ngẫu nhiên từ quần thể. Tìm xác suất để tổng của 50 giá trị lớn hơn 2,400.

To find percentiles for sums on the calculator, follow these steps.

Để tìm bách phân vị cho các tổng trên máy tính, hãy làm theo các bước sau.

`2^nd DIStR`

`3:invNorm`

*k* = invNorm (area to the left of *k*, (*n*)(mean), 

(
n

)

(
n

)
(standard deviation))

`2^nd DIStR`

`3:invNorm`

*k* = invNorm (diện tích bên trái của *k*, (*n*)(số trung bình), 

(
n

)

(
n

)
(độ lệch chuẩn))

where:

trong đó:

- *k* is the *k*^th percentile
- *k* là Bách phân vị thứ *k*
- *mean* is the mean of the original distribution
- *số trung bình* là số trung bình của phân phối gốc
- *standard deviation* is the standard deviation of the original distribution
- *độ lệch chuẩn* là độ lệch chuẩn của phân phối gốc
- *sample size* = *n*
- *kích thước mẫu* = *n*
#### Problem

#### Bài toán

In a recent study, it was reported that the mean age of iPad users is 34 years. Suppose the standard deviation is 15 years. The sample of size is 50.

Trong một nghiên cứu gần đây, có báo cáo rằng độ tuổi trung bình của người dùng iPad là 34 tuổi. Giả sử độ lệch chuẩn là 15 tuổi. Kích thước mẫu là 50.

1. What are the mean and standard deviation for the sum of the ages of iPad users? What is the distribution?
1. Số trung bình và độ lệch chuẩn cho tổng độ tuổi của người dùng iPad là bao nhiêu? Phân phối đó là gì?
1. Find the probability that the sum of the ages is between 1,500 and 1,800 years.
1. Tìm xác suất để tổng độ tuổi nằm trong khoảng từ 1.500 đến 1,800 năm.
1. Find the 80^th percentile for the sum of the 50 ages.
1. Tìm bách phân vị thứ 80 cho tổng của 50 độ tuổi.
In a recent study, it was reported that the mean age of iPad users is 35 years. Suppose the standard deviation is ten years. The sample size is 39.

Trong một nghiên cứu gần đây, có báo cáo rằng độ tuổi trung bình của người dùng iPad là 35 tuổi. Giả sử độ lệch chuẩn là mười tuổi. Kích thước mẫu là 39.

1. What are the mean and standard deviation for the sum of the ages of iPad users? What is the distribution?
1. Số trung bình và độ lệch chuẩn cho tổng độ tuổi của người dùng iPad là bao nhiêu? Phân phối đó là gì?
1. Find the probability that the sum of the ages is between 1,400 and 1,500 years.
1. Tìm xác suất để tổng độ tuổi nằm trong khoảng từ 1,400 đến 1.500 năm.
1. Find the 90^th percentile for the sum of the 39 ages.
1. Tìm bách phân vị thứ 90 cho tổng của 39 độ tuổi.
#### Problem

#### Bài toán

The mean number of minutes for app engagement by a tablet user is 8.2 minutes. Suppose the standard deviation is one minute. Take a sample of size 70.

Số phút trung bình cho việc tương tác với ứng dụng bởi một người dùng máy tính bảng là 8.2 phút. Giả sử độ lệch chuẩn là một phút. Lấy một mẫu có kích thước 70.

1. What are the mean and standard deviation for the sums?
1. Số trung bình và độ lệch chuẩn cho các tổng là bao nhiêu?
1. Find the 95^th percentile for the sum of the sample. Interpret this value in a complete sentence.
1. Tìm bách phân vị thứ 95 cho tổng của mẫu. Giải thích giá trị này trong một câu hoàn chỉnh.
1. Find the probability that the sum of the sample is at least ten hours.
1. Tìm xác suất để tổng của mẫu ít nhất là mười giờ.
The mean number of minutes for app engagement by a table use is 8.2 minutes. Suppose the standard deviation is one minute. Take a sample size of 70.

Số phút trung bình cho việc tương tác với ứng dụng bởi một người dùng máy tính bảng là 8.2 phút. Giả sử độ lệch chuẩn là một phút. Lấy một kích thước mẫu là 70.

1. What is the probability that the sum of the sample is between seven hours and ten hours? What does this mean in context of the problem?
1. Xác suất để tổng của mẫu nằm trong khoảng từ bảy giờ đến mười giờ là bao nhiêu? Điều này có ý nghĩa gì trong ngữ cảnh của bài toán?
1. Find the 84^th and 16^th percentiles for the sum of the sample. Interpret these values in context.
1. Tìm bách phân vị thứ 84 và thứ 16 cho tổng của mẫu. Giải thích các giá trị này trong ngữ cảnh.
