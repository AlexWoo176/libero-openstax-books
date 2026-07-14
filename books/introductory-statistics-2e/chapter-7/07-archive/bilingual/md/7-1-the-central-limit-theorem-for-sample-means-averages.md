## 7.1
 
The Central Limit Theorem for Sample Means (Averages)

## 7.1
 
Định lý giới hạn trung tâm cho các số trung bình mẫu

Suppose *X* is a random variable with a distribution that may be known or unknown (it can be any distribution). Using a subscript that matches the random variable, suppose:

Giả sử *X* là một biến ngẫu nhiên với một phân phối có thể đã biết hoặc chưa biết (nó có thể là bất kỳ phân phối nào). Sử dụng một chỉ số dưới khớp với biến ngẫu nhiên, giả sử:

1. *μ**_X* = the mean of *X*
1. *μ**_X* = số trung bình của *X*
1. *σ**_X* = the standard deviation of *X*
1. *σ**_X* = độ lệch chuẩn của *X*
If you draw random samples of size *n*, then as *n* increases, the random variable 

x
¯

x
¯
 which consists of sample means, tends to be normally distributed and

Nếu bạn lấy các mẫu ngẫu nhiên có kích thước *n*, thì khi *n* tăng lên, biến ngẫu nhiên 

x
¯

x
¯
 bao gồm các số trung bình mẫu có xu hướng Có phân phối chuẩn và

The central limit theorem for sample means says that if you repeatedly draw samples of a given size (such as repeatedly rolling ten dice) and calculate their means, those means tend to follow a normal distribution (the sampling distribution). As sample sizes increase, the distribution of means more closely follows the normal distribution. The normal distribution has the same mean as the original distribution and a variance that equals the original variance divided by the sample size. Standard deviation is the square root of variance, so the standard deviation of the sampling distribution is the standard deviation of the original distribution divided by the square root of *n*. The variable *n* is the number of values that are averaged together, not the number of times the experiment is done.

Định lý giới hạn trung tâm cho các số trung bình mẫu phát biểu rằng nếu bạn liên tục lấy các mẫu với kích thước nhất định (ví dụ như gieo mười con xúc xắc nhiều lần) và tính số trung bình của chúng, các số trung bình đó có xu hướng tuân theo một phân phối chuẩn (phân phối mẫu). Khi kích thước mẫu tăng lên, phân phối của các số trung bình càng bám sát phân phối chuẩn hơn. Phân phối chuẩn có cùng số trung bình với phân phối gốc và phương sai bằng phương sai gốc chia cho kích thước mẫu. Độ lệch chuẩn là căn bậc hai của phương sai, vì vậy độ lệch chuẩn của phân phối mẫu là độ lệch chuẩn của phân phối gốc chia cho căn bậc hai của *n*. Biến *n* là số lượng các giá trị được lấy trung bình cùng nhau, không phải số lần thực hiện phép thử.

To put it more formally, if you draw random samples of size *n*, the distribution of the random variable 

X
¯

X
¯
, which consists of sample means, is called the **sampling distribution of the mean**. The sampling distribution of the mean approaches a normal distribution as *n*, the sample size, increases.

Nói một cách chính thức hơn, nếu bạn lấy các mẫu ngẫu nhiên có kích thước *n*, phân phối của biến ngẫu nhiên 

X
¯

X
¯
, bao gồm các số trung bình mẫu, được gọi là **phân phối mẫu của số trung bình**. Phân phối mẫu của số trung bình tiến dần đến phân phối chuẩn khi *n*, Kích thước mẫu, tăng lên.

The random variable 

X
¯

X
¯
 has a different *z*-score associated with it from that of the random variable *X*. The mean 

x
¯

x
¯
 is the value of 

X
¯

X
¯
 in one sample.

Biến ngẫu nhiên 

X
¯

X
¯
 có một điểm *z* khác liên quan đến nó so với biến ngẫu nhiên *X*. Số trung bình 

x
¯

x
¯
 là giá trị của 

X
¯

X
¯
 trong một mẫu.

*μ*_*X* is the average of both *X* and 

X
¯

X
¯
.

*μ*_*X* là số trung bình của cả *X* và 

X
¯

X
¯
.

σx=σXn=σx=σXn= standard deviation of 

X
¯

X
¯
 and is called the standard error of the mean.

σx=σXn=σx=σXn= độ lệch chuẩn của 

X
¯

X
¯
 và được gọi là sai số chuẩn của số trung bình.

To find probabilities for means on the calculator, follow these steps.

Để tìm xác suất cho các số trung bình trên máy tính, hãy làm theo các bước sau.

`2nd DISTR`
`2:normalcdf`

`2nd DISTR``2:normalcdf`

normalcdf(

lower value of the area, upper value of the area, mean, 

standard deviation

sample size

)

normalcdf(

lower value of the area, upper value of the area, mean, 

standard deviation

sample size

)

normalcdf(

lower value of the area, upper value of the area, mean, 

standard deviation

sample size

)

normalcdf(

lower value of the area, upper value of the area, mean, 

standard deviation

sample size

)

where:

trong đó:

- *mean* is the mean of the original distribution
- *mean* là số trung bình của phân phối gốc
- *standard deviation* is the standard deviation of the original distribution
- *standard deviation* là độ lệch chuẩn của phân phối gốc
- *sample size* = *n*
- *kích thước mẫu = **n*
An unknown distribution has a mean of 90 and a standard deviation of 15. Samples of size *n* = 25 are drawn randomly from the population.

Một phân phối chưa biết có số trung bình là 90 và độ lệch chuẩn là 15. Các mẫu có kích thước *n* = 25 được lấy ngẫu nhiên từ quần thể.

#### Problem

#### Bài toán

a. Find the probability that the sample mean is between 85 and 92.

a. Tìm xác suất để Trung bình mẫu nằm trong khoảng từ 85 đến 92.

*Figure 
7.2*

*Hình 
7.2*

`normalcdf`(lower value, upper value, mean, standard error of the mean)

`normalcdf`(giá trị thấp hơn, giá trị cao hơn, số trung bình, sai số chuẩn của số trung bình)

The parameter list is abbreviated (lower value, upper value, *μ*, 

σ

n

σ

n

)

Danh sách tham số được viết tắt (giá trị thấp hơn, giá trị cao hơn, *μ*, 

σ

n

σ

n

)

`normalcdf`(85,92,90,

15

25

15

25

) = 0.6997

`normalcdf`(85,92,90,

15

25

15

25

) = 0,6997

#### Problem

#### Bài toán

b. Find the value that is two standard deviations above the expected value, 90, of the sample mean.

b. Tìm giá trị cao hơn hai độ lệch chuẩn so với giá trị kỳ vọng, 90, của số trung bình mẫu.

An unknown distribution has a mean of 45 and a standard deviation of eight. Samples of size *n* = 30 are drawn randomly from the population. Find the probability that the sample mean is between 42 and 50.

Một phân phối chưa biết có số trung bình là 45 và độ lệch chuẩn là tám. Các mẫu có kích thước *n* = 30 được rút ngẫu nhiên từ quần thể. Hãy tìm xác suất để số trung bình mẫu nằm trong khoảng từ 42 đến 50.

#### Problem

#### Bài toán

The length of time, in hours, it takes an "over 40" group of people to play one soccer match is normally distributed with a **mean of two hours** and a **standard deviation of 0.5 hours**. A **sample of size *n* = 50** is drawn randomly from the population. Find the probability that the **sample mean** is between 1.8 hours and 2.3 hours.

Khoảng thời gian, tính bằng giờ, để một nhóm người "trên 40 tuổi" chơi một trận bóng đá được phân phối chuẩn với **số trung bình là hai giờ** và **độ lệch chuẩn là 0,5 giờ**. Một **mẫu có kích thước *n* = 50** được rút ngẫu nhiên từ quần thể. Hãy tìm xác suất để **số trung bình mẫu** nằm trong khoảng từ 1,8 giờ đến 2,3 giờ.

The length of time taken on the SAT for a group of students is normally distributed with a mean of 2.5 hours and a standard deviation of 0.25 hours. A sample size of *n* = 60 is drawn randomly from the population. Find the probability that the sample mean is between two hours and three hours.

Khoảng thời gian làm bài SAT của một nhóm học sinh được phân phối chuẩn với số trung bình là 2,5 giờ và độ lệch chuẩn là 0,25 giờ. Một mẫu có kích thước *n* = 60 được rút ngẫu nhiên từ quần thể. Hãy tìm xác suất để số trung bình mẫu nằm trong khoảng từ hai giờ đến ba giờ.

To find percentiles for means on the calculator, follow these steps.

Để tìm các bách phân vị cho các số trung bình trên máy tính, hãy làm theo các bước sau.

`2^nd DIStR`

`3:invNorm`

`2^nd DIStR`

*k* = invNorm

(

area to the left of k, mean, 

standard deviation

sample size

)

(

area to the left of k, mean, 

standard deviation

sample size

)

*k* = invNorm 

(

diện tích bên trái của k, trung bình, 

standard deviation

sample size

)

(

diện tích bên trái của k, trung bình, 

standard deviation

sample size

)

where:

trong đó:

- *k* = the *k*^th percentile
- *k* = bách phân vị thứ *k*
- *mean* is the mean of the original distribution
- *mean* là số trung bình của phân phối gốc
- *standard deviation* is the standard deviation of the original distribution
- *standard deviation* là độ lệch chuẩn của phân phối gốc
- *sample size* = *n*
- *kích thước mẫu = **n*
#### Problem

#### Bài toán

In a recent study, it was reported that the mean age of iPad users is 34 years. Suppose the standard deviation is 15 years. Take a sample of size *n* = 100.

Trong một nghiên cứu gần đây, có báo cáo rằng độ tuổi trung bình của người dùng iPad là 34 tuổi. Giả sử độ lệch chuẩn là 15 tuổi. Lấy một mẫu có kích thước *n* = 100.

1. What are the mean and standard deviation for the sample mean ages of iPad users?
1. Số trung bình và độ lệch chuẩn cho độ tuổi trung bình mẫu của người dùng iPad là bao nhiêu?
1. What does the distribution look like?
1. Phân phối trông như thế nào?
1. Find the probability that the sample mean age is more than 30 years (the reported mean age of iPad users in this particular study).
1. Hãy tìm xác suất để độ tuổi trung bình mẫu lớn hơn 30 tuổi (độ tuổi trung bình được báo cáo của người dùng iPad trong nghiên cứu cụ thể này).
1. Find the 95^th percentile for the sample mean age (to one decimal place).
1. Hãy tìm bách phân vị thứ 95 cho độ tuổi trung bình mẫu (làm tròn đến một chữ số thập phân).
In an article on Flurry Blog, a gaming marketing gap for men between the ages of 30 and 40 is identified. You are researching a startup game targeted at the 35-year-old demographic. Your idea is to develop a strategy game that can be played by men from their late 20s through their late 30s. Based on the article’s data, industry research shows that the average strategy player is 28 years old with a standard deviation of 4.8 years. You take a sample of 100 randomly selected gamers. If your target market is 29- to 35-year-olds, should you continue with your development strategy?

Trong một bài báo trên Flurry Blog, một khoảng trống tiếp thị trò chơi cho nam giới trong độ tuổi từ 30 đến 40 đã được xác định. Bạn đang nghiên cứu một trò chơi khởi nghiệp nhắm vào nhóm nhân khẩu học 35 tuổi. Ý tưởng của bạn là phát triển một trò chơi chiến thuật mà nam giới từ cuối độ tuổi 20 đến cuối độ tuổi 30 có thể chơi được. Dựa trên dữ liệu của bài báo, nghiên cứu ngành cho thấy người chơi chiến thuật trung bình là 28 tuổi với độ lệch chuẩn là 4,8 tuổi. Bạn lấy một mẫu gồm 100 game thủ được chọn ngẫu nhiên. Nếu thị trường mục tiêu của bạn là những người từ 29 đến 35 tuổi, bạn có nên tiếp tục với chiến lược phát triển của mình không?

#### Problem

#### Bài toán

The mean number of minutes for app engagement by an iPad user is 8.2 minutes. Suppose the standard deviation is one minute. Take a sample of 60.

Số phút trung bình cho việc tương tác với ứng dụng của một người dùng iPad là 8,2 phút. Giả sử độ lệch chuẩn là một phút. Lấy một mẫu gồm 60 người.

1. What are the mean and standard deviation for the sample mean number of minutes for app engagement by an iPad user?
1. Số trung bình và độ lệch chuẩn cho số phút trung bình mẫu cho việc tương tác với ứng dụng của một người dùng iPad là bao nhiêu?
1. What is the standard error of the mean?
1. Sai số chuẩn của số trung bình là bao nhiêu?
1. Find the 90^th percentile for the sample mean time of minutes for app engagement by an iPad user. Interpret this value in a complete sentence.
1. Hãy tìm bách phân vị thứ 90 cho thời gian trung bình mẫu tính bằng phút cho việc tương tác với ứng dụng của một người dùng iPad. Giải thích giá trị này trong một câu hoàn chỉnh.
1. Find the probability that the sample mean is between eight minutes and 8.5 minutes.
1. Hãy tìm xác suất để số trung bình mẫu nằm trong khoảng từ tám phút đến 8,5 phút.
Cans of a cola beverage claim to contain 16 ounces. The amounts in a sample are measured and the statistics are *n* = 34, 

x
¯

x
¯
 = 16.01 ounces. If the cans are filled so that *μ* = 16.00 ounces (as labeled) and *σ* = 0.143 ounces, find the probability that a sample of 34 cans will have an average amount greater than 16.01 ounces. Do the results suggest that cans are filled with an amount greater than 16 ounces?

Các lon nước ngọt cola tuyên bố chứa 16 ounce. Các lượng trong một mẫu được đo và các trị thống kê là *n* = 34, 

x
¯

x
¯
 = 16,01 ounce. Nếu các lon được làm đầy sao cho *μ* = 16,00 ounce (như trên nhãn) và *σ* = 0,143 ounce, hãy tìm xác suất để một mẫu gồm 34 lon sẽ có lượng trung bình lớn hơn 16,01 ounce. Các kết quả có gợi ý rằng các lon được làm đầy với lượng lớn hơn 16 ounce không?
