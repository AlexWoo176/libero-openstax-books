## 4.3
 
Binomial Distribution

## 4.3
 
Phân phối nhị thức

There are three characteristics of a binomial experiment.

Có ba đặc điểm của một phép thử Bernoulli.

1. There are a fixed number of trials. Think of trials as repetitions of an experiment. The letter *n* denotes the number of trials.
1. Có một số lượng phép thử cố định. Hãy coi các phép thử là các lần lặp lại của một phép thử. Chữ cái *n* biểu thị số lượng phép thử.
1. There are only two possible outcomes, called "success" and "failure," for each trial. The letter *p* denotes the probability of a success on one trial, and *q* denotes the probability of a failure on one trial. *p* + *q* = 1.
1. Chỉ có hai kết quả có thể xảy ra, được gọi là "thành công" và "thất bại", cho mỗi phép thử. Chữ cái *p* biểu thị xác suất thành công trong một phép thử, và *q* biểu thị xác suất thất bại trong một phép thử. *p* + *q* = 1.
1. The *n* trials are independent and are repeated using identical conditions. Because the *n* trials are independent, the outcome of one trial does not help in predicting the outcome of another trial. Another way of saying this is that for each individual trial, the probability, *p*, of a success and probability, *q*, of a failure remain the same. For example, randomly guessing at a true-false statistics question has only two outcomes. If a success is guessing correctly, then a failure is guessing incorrectly. Suppose Joe always guesses correctly on any statistics true-false question with probability *p* = 0.6. Then, *q* = 0.4. This means that for every true-false statistics question Joe answers, his probability of success (*p* = 0.6) and his probability of failure (*q* = 0.4) remain the same.
1. *n* phép thử là độc lập và được lặp lại trong các điều kiện giống hệt nhau. Vì *n* phép thử là độc lập, kết quả của một phép thử không giúp dự đoán kết quả của phép thử khác. Một cách diễn đạt khác là đối với mỗi phép thử riêng lẻ, xác suất *p* của thành công và xác suất *q* của thất bại vẫn giữ nguyên. Ví dụ, việc đoán ngẫu nhiên một câu hỏi đúng-sai về thống kê chỉ có hai kết quả. Nếu thành công là đoán đúng, thì thất bại là đoán sai. Giả sử Joe luôn đoán đúng bất kỳ câu hỏi đúng-sai nào về thống kê với xác suất *p* = 0,6. Khi đó, *q* = 0,4. Điều này có nghĩa là đối với mỗi câu hỏi đúng-sai về thống kê mà Joe trả lời, xác suất thành công (*p* = 0,6) và xác suất thất bại (*q* = 0,4) của anh ấy vẫn giữ nguyên.
The outcomes of a binomial experiment fit a binomial probability distribution. The random variable *X* = the number of successes obtained in the *n* independent trials.

Các kết quả của một phép thử Bernoulli tuân theo Phân phối xác suất nhị thức. Biến ngẫu nhiên *X* = số lần thành công thu được trong *n* phép thử độc lập.

The mean, *μ*, and variance, *σ*^2, for the binomial probability distribution are *μ* = *np* and *σ*^2 = *npq*. The standard deviation, *σ*, is then *σ* = √𝑛⁢𝑝⁢𝑞n⁢p⁢qnpq.

Số trung bình, *μ*, và phương sai, *σ*^2, cho phân phối xác suất nhị thức là *μ* = *np* và *σ*^2 = *npq*. Khi đó, độ lệch chuẩn, *σ*, là *σ* = √𝑛⁢𝑝⁢𝑞n⁢p⁢qnpq.

Any experiment that has characteristics two and three and where *n* = 1 is called a Bernoulli Trial (named after Jacob Bernoulli who, in the late 1600s, studied them extensively). A binomial experiment takes place when the number of successes is counted in one or more Bernoulli Trials.

Bất kỳ phép thử nào có các đặc điểm hai và ba và trong đó *n* = 1 được gọi là Phép thử Bernoulli (được đặt theo tên của Jacob Bernoulli, người đã nghiên cứu chúng rất kỹ lưỡng vào cuối những năm 1600). Một phép thử nhị thức diễn ra khi số lần thành công được đếm trong một hoặc nhiều phép thử Bernoulli.

At ABC College, the withdrawal rate from an elementary physics course is 30% for any given term. This implies that, for any given term, 70% of the students stay in the class for the entire term. A "success" could be defined as an individual who withdrew. The random variable *X* = the number of students who withdraw from the randomly selected elementary physics class.

Tại trường Cao đẳng ABC, tỷ lệ rút môn học từ một khóa vật lý cơ bản là 30% cho bất kỳ học kỳ nào. Điều này ngụ ý rằng, trong bất kỳ học kỳ nào, 70% sinh viên vẫn tiếp tục học trong suốt học kỳ đó. Một "thành công" có thể được định nghĩa là một cá nhân đã rút môn học. Biến ngẫu nhiên *X* = số lượng sinh viên rút khỏi lớp vật lý cơ bản được chọn ngẫu nhiên.

The state health board is concerned about the amount of fruit available in school lunches. Forty-eight percent of schools in the state offer fruit in their lunches every day. This implies that 52% do not. What would a "success" be in this case?

Hội đồng y tế tiểu bang lo ngại về lượng trái cây có sẵn trong các bữa trưa tại trường học. Bốn mươi tám phần trăm các trường trong tiểu bang cung cấp trái cây trong bữa trưa của họ mỗi ngày. Điều này ngụ ý rằng 52% không cung cấp. Trong trường hợp này, một "thành công" sẽ là gì?

Suppose you play a game that you can only either win or lose. The probability that you win any game is 55%, and the probability that you lose is 45%. Each game you play is independent. If you play the game 20 times, write the function that describes the probability that you win 15 of the 20 times. Here, if you define *X* as the number of wins, then *X* takes on the values 0, 1, 2, 3, ..., 20. The probability of a success is *p* = 0.55. The probability of a failure is *q* = 0.45. The number of trials is *n* = 20. The probability question can be stated mathematically as *P*(*x* = 15).

Giả sử bạn chơi một trò chơi mà bạn chỉ có thể thắng hoặc thua. Xác suất bạn thắng bất kỳ trò chơi nào là 55%, và xác suất bạn thua là 45%. Mỗi trò chơi bạn chơi là độc lập. Nếu bạn chơi trò chơi đó 20 lần, hãy viết hàm mô tả xác suất bạn thắng 15 trong số 20 lần đó. Ở đây, nếu bạn định nghĩa *X* là số lần thắng, thì *X* nhận các giá trị 0, 1, 2, 3, ..., 20. Xác suất thành công là *p* = 0,55. Xác suất thất bại là *q* = 0,45. Số lần thử là *n* = 20. Câu hỏi về xác suất có thể được phát biểu dưới dạng toán học là *P*(*x* = 15).

A trainer is teaching a rescued dolphin to catch live fish before returning it to the wild. The probability that the dolphin successfully catches a fish is 35%, and the probability that the dolphin does not successfully catch the fish is 65%. Out of 20 attempts, you want to find the probability that the dolphin succeeds 12 times. State the probability question mathematically.

Một huấn luyện viên đang dạy một chú cá heo được giải cứu cách bắt cá sống trước khi thả nó về tự nhiên. Xác suất chú cá heo bắt được cá thành công là 35%, và xác suất chú cá heo không bắt được cá thành công là 65%. Trong 20 lần thử, bạn muốn tìm xác suất chú cá heo thành công 12 lần. Hãy phát biểu câu hỏi về xác suất dưới dạng toán học.

#### Problem

#### Bài toán

A coin has been altered to weight the outcome from 0.5 to 0.25 and flipped 5 times. Each flip is independent. What is the probability of getting more than 3 heads? Let *X* = the number of heads in 5 flips of the fair coin. *X* takes on the values 0, 1, 2, 3, 4, 5. Since the coin is altered to result in *p* = 0.25, *q* is 0.75. The number of trials is *n* = 5. State the probability question mathematically.

Một đồng xu đã được thay đổi để trọng số kết quả từ 0,5 thành 0,25 và được tung 5 lần. Mỗi lần tung là độc lập. Xác suất để nhận được nhiều hơn 3 mặt ngửa là bao nhiêu? Gọi *X* = số mặt ngửa trong 5 lần tung đồng xu cân đối. *X* nhận các giá trị 0, 1, 2, 3, 4, 5. Vì đồng xu được thay đổi để dẫn đến *p* = 0,25, *q* là 0,75. Số lần thử là *n* = 5. Hãy phát biểu câu hỏi về xác suất dưới dạng toán học.

First develop fully the probability density function and graph the probability density function. With the fully developed probability density function we can simply read the solution to the question 𝑃⁡(𝑥>3)P⁡(x>3)Px>3 heads. 𝑃⁡(𝑥>3) =𝑃⁡(𝑥=4) +𝑃⁡(𝑥=5) =0.0146 +0.0007 =0.0153.P⁡(x>3)=P⁡(x=4)+P⁡(x=5)=0.0146+0.0007=0.0153.Px>3=Px=4+Px=5=0.0146+0.0007=0.0153. We have added the two individual probabilities because of the addition rule from [Probability Topics](3-introduction).

Trước tiên, hãy phát triển đầy đủ hàm mật độ xác suất và vẽ đồ thị hàm mật độ xác suất. Với hàm mật độ xác suất đã được phát triển đầy đủ, chúng ta có thể dễ dàng đọc lời giải cho câu hỏi 𝑃⁡(𝑥>3)P⁡(x>3)Px>3 mặt ngửa. 𝑃⁡(𝑥>3) =𝑃⁡(𝑥=4) +𝑃⁡(𝑥=5) =0.0146 +0.0007 =0.0153.P⁡(x>3)=P⁡(x=4)+P⁡(x=5)=0.0146+0.0007=0.0153.Px>3=Px=4+Px=5=0.0146+0.0007=0.0153. Chúng ta đã cộng hai xác suất riêng lẻ vì quy tắc cộng từ [Các chủ đề về xác suất](3-introduction).

[Figure 4.2](4-3-binomial-distribution#fig-00001) also allows us to see the link between the probability density function and probability and area. We also see in [Figure 4.2](4-3-binomial-distribution#fig-00001) the skew of the binomial distribution when p is not equal to 0.5. In [Figure 4.2](4-3-binomial-distribution#fig-00001) the distribution is skewed right as a result of 𝜇 =𝑛⁢𝑝 =1.25μ=n⁢p=1.25μ=np=1.25 because 𝑝 =0.25p=0.25p=0.25.

[Hình 4.2](4-3-binomial-distribution#fig-00001) cũng cho phép chúng ta thấy mối liên hệ giữa hàm mật độ xác suất với xác suất và diện tích. Chúng ta cũng thấy trong [Hình 4.2](4-3-binomial-distribution#fig-00001) độ lệch của phân phối nhị thức khi p không bằng 0,5. Trong [Hình 4.2](4-3-binomial-distribution#fig-00001), phân phối bị lệch phải là kết quả của 𝜇 =𝑛⁢𝑝 =1.25μ=n⁢p=1.25μ=np=1.25 vì 𝑝 =0.25p=0.25p=0.25.

*Figure 
4.2*

*Hình 
4.2*

A fair, six-sided die is rolled ten times. Each roll is independent. You want to find the probability of rolling a one more than three times. State the probability question mathematically.

Một con xúc xắc cân đối, sáu mặt được gieo mười lần. Mỗi lần gieo là độc lập. Bạn muốn tìm xác suất gieo được mặt một nhiều hơn ba lần. Hãy phát biểu câu hỏi về xác suất dưới dạng toán học.

Approximately 70% of statistics students do their homework in time for it to be collected and graded. Each student does homework independently. In a statistics class of 50 students, what is the probability that at least 40 will do their homework on time? Students are selected randomly.

Khoảng 70% sinh viên thống kê làm bài tập về nhà kịp thời để được thu và chấm điểm. Mỗi sinh viên làm bài tập về nhà một cách độc lập. Trong một lớp thống kê gồm 50 sinh viên, xác suất để ít nhất 40 sinh viên làm bài tập về nhà đúng hạn là bao nhiêu? Sinh viên được chọn ngẫu nhiên.

#### Problem

#### Bài toán

a. This is a binomial problem because there is only a success or a __________, there are a fixed number of trials, and the probability of a success is 0.70 for each trial.

a. Đây là một bài toán nhị thức vì chỉ có thành công hoặc một __________, có một số lần thử cố định, và xác suất thành công là 0,70 cho mỗi lần thử.

b. If we are interested in the number of students who do their homework on time, then how do we define *X*?

b. Nếu chúng ta quan tâm đến số lượng sinh viên làm bài tập về nhà đúng hạn, thì chúng ta định nghĩa *X* như thế nào?

c. What values does *x* take on?

c. *x* nhận những giá trị nào?

d. What is a "failure," in words?

d. "Thất bại" là gì, theo ngôn từ?

e. If *p* + *q* = 1, then what is *q*?

e. Nếu *p* + *q* = 1, thì *q* là gì?

f. The words "at least" translate as what kind of inequality for the probability question *P*(*x* ____ 40).

f. Các từ "ít nhất" tương ứng với loại bất đẳng thức nào cho câu hỏi xác suất *P*(*x* ____ 40).

Sixty-five percent of people pass the state driver’s exam on the first try. A group of 50 individuals who have taken the driver’s exam is randomly selected. Give two reasons why this is a binomial problem.

Sáu mươi lăm phần trăm mọi người vượt qua kỳ thi sát hạch lái xe của bang ngay lần thử đầu tiên. Một nhóm gồm 50 cá nhân đã tham gia kỳ thi lái xe được chọn ngẫu nhiên. Hãy đưa ra hai lý do tại sao đây là một bài toán nhị thức.

### Notation for the Binomial: *B* = Binomial Probability Distribution Function

### Ký hiệu cho phân phối nhị thức: *B* = Hàm phân phối xác suất nhị thức

*X* ~ *B*(*n*, *p*)

*X**B**n**p*

Read this as "*X* is a random variable with a binomial distribution." The parameters are *n* and *p*; *n* = number of trials, *p* = probability of a success on each trial.

Đọc là "*X* là một biến ngẫu nhiên có phân phối xác suất nhị thức." Các tham số là *n* và *p*; *n* = số phép thử, *p* = xác suất thành công trong mỗi phép thử.

It has been stated that about 41% of adult workers have a high school diploma but do not pursue any further education. If 20 adult workers are randomly selected, find the probability that at most 12 of them have a high school diploma but do not pursue any further education. How many adult workers do you expect to have a high school diploma but do not pursue any further education?

Người ta đã tuyên bố rằng khoảng 41% người lao động trưởng thành có bằng tốt nghiệp trung học phổ thông nhưng không theo đuổi bất kỳ chương trình giáo dục nào thêm. Nếu 20 người lao động trưởng thành được chọn ngẫu nhiên, hãy tìm xác suất để tối đa 12 người trong số họ có bằng tốt nghiệp trung học phổ thông nhưng không theo đuổi bất kỳ chương trình giáo dục nào thêm. Bạn kỳ vọng có bao nhiêu người lao động trưởng thành có bằng tốt nghiệp trung học phổ thông nhưng không theo đuổi bất kỳ chương trình giáo dục nào thêm?

Let *X* = the number of workers who have a high school diploma but do not pursue any further education.

Đặt *X* = số người lao động có bằng tốt nghiệp trung học phổ thông nhưng không theo đuổi bất kỳ chương trình giáo dục nào thêm.

*X* takes on the values 0, 1, 2, ..., 20 where *n* = 20, *p* = 0.41, and *q* = 1 – 0.41 = 0.59. *X* ~ *B*(20, 0.41)

*X* nhận các giá trị 0, 1, 2, ..., 20 trong đó *n* = 20, *p* = 0,41, và *q* = 1 – 0,41 = 0,59. *X* ~ *B*(20, 0,41)

Find *P*(*x* ≤ 12). *P*(*x* ≤ 12) = 0.9738. (calculator or computer)

Tìm *P*(*x* ≤ 12). *P*(*x* ≤ 12) = 0,9738. (máy tính hoặc máy tính cầm tay)

Go into 2^nd DISTR. The syntax for the instructions are as follows:

Vào 2^nd DISTR. Cú pháp cho các hướng dẫn như sau:

**To calculate (*x* = value): binompdf(*n*, *p*, number)**
if "number" is left out, the result is the binomial probability table.

**To calculate *P*(*x* ≤ value): binomcdf(*n*, *p*, number)** if "number" is left out, the result is the cumulative binomial probability table.

**For this problem: After you are in `2^nd DISTR`, arrow down to `binomcdf`. Press `ENTER`. Enter 20,0.41,12). The result is *P*(*x* ≤ 12) = 0.9738.**

**Để tính (*x* = giá trị): binompdf(*n*, *p*, số)**
nếu "số" bị bỏ qua, kết quả là bảng xác suất nhị thức.

**Để tính *P*(*x* ≤ giá trị): binomcdf(*n*, *p*, số)** nếu "số" bị bỏ qua, kết quả là bảng xác suất nhị thức lũy tích.

**Đối với bài toán này: Sau khi bạn đã ở trong `2^nd DISTR`, hãy nhấn phím mũi tên xuống đến `binomcdf`. Nhấn `ENTER`. Nhập 20,0,41,12). Kết quả là *P*(*x* ≤ 12) = 0,9738.**

If you want to find *P*(*x* = 12), use the pdf (binompdf). If you want to find *P*(*x* > 12), use 1 - binomcdf(20,0.41,12).

Nếu bạn muốn tìm *P*(*x* = 12), hãy sử dụng pdf (binompdf). Nếu bạn muốn tìm *P*(*x* > 12), hãy sử dụng 1 - binomcdf(20,0,41,12).

The probability that at most 12 workers have a high school diploma but do not pursue any further education is 0.9738.

Xác suất để tối đa 12 công nhân có bằng tốt nghiệp trung học nhưng không theo đuổi bất kỳ chương trình giáo dục nào thêm là 0,9738.

The graph of *X* ~ *B*(20, 0.41) is as follows:

Đồ thị của *X* ~ *B*(20, 0,41) như sau:

*Figure 
4.3*

*Hình 
4.3*

The *y*-axis contains the probability of *x*, where *X* = the number of workers who have only a high school diploma.

Trục *y* chứa xác suất của *x*, trong đó *X* = số lượng công nhân chỉ có bằng tốt nghiệp trung học.

The number of adult workers that you expect to have a high school diploma but not pursue any further education is the mean, *μ* = *np* = (20)(0.41) = 8.2.

Số lượng công nhân trưởng thành mà bạn kỳ vọng có bằng tốt nghiệp trung học nhưng không theo đuổi bất kỳ chương trình giáo dục nào thêm chính là số trung bình, *μ* = *np* = (20)(0,41) = 8,2.

The formula for the variance is σ^2 = *npq*. The standard deviation is *σ* = √𝑛⁢𝑝⁢𝑞n⁢p⁢qnpq. 
*σ* = √(20)⁢(0.41)⁢(0.59)(20)⁢(0.41)⁢(0.59)(20)(0.41)(0.59) = 2.20.

Công thức tính phương sai là σ^2 = *npq*. Độ lệch chuẩn là *σ* = √𝑛⁢𝑝⁢𝑞n⁢p⁢qnpq. 
*σ* = √(20)⁢(0.41)⁢(0.59)(20)⁢(0.41)⁢(0.59)(20)(0.41)(0.59) = 2,20.

About 32% of students participate in a community volunteer program outside of school. If 30 students are selected at random, find the probability that at most 14 of them participate in a community volunteer program outside of school. Use the TI-83+ or TI-84 calculator to find the answer.

Khoảng 32% sinh viên tham gia một chương trình tình nguyện cộng đồng bên ngoài trường học. Nếu 30 sinh viên được chọn ngẫu nhiên, hãy tìm xác suất để tối đa 14 người trong số họ tham gia một chương trình tình nguyện cộng đồng bên ngoài trường học. Sử dụng máy tính TI-83+ hoặc TI-84 để tìm câu trả lời.

#### Problem

#### Bài toán

In the 2013 *Jerry’s Artarama* art supplies catalog, there are 560 pages. Eight of the pages feature signature artists. Suppose we randomly sample 100 pages. Let *X* = the number of pages that feature signature artists.

Trong danh mục đồ dùng nghệ thuật *Jerry’s Artarama* năm 2013, có 560 trang. Tám trong số các trang đó giới thiệu các nghệ sĩ tiêu biểu. Giả sử chúng ta lấy mẫu ngẫu nhiên 100 trang. Gọi *X* = số trang giới thiệu các nghệ sĩ tiêu biểu.

1. What values does *x* take on?
1. *x* nhận những giá trị nào?
1. What is the probability distribution? Find the following probabilities:
  
the probability that two pages feature signature artistsxác suất để hai trang có các nghệ sĩ tiêu biểu
the probability that at most six pages feature signature artistsxác suất để có tối đa sáu trang có các nghệ sĩ tiêu biểu
the probability that more than three pages feature signature artists.xác suất để có nhiều hơn ba trang có các nghệ sĩ tiêu biểu.
1. Using the formulas, calculate the (i) mean and (ii) standard deviation.
1. Sử dụng các công thức, hãy tính (i) số trung bình và (ii) độ lệch chuẩn.
According to a Gallup poll, 60% of American adults prefer saving over spending. Let *X* = the number of American adults out of a random sample of 50 who prefer saving to spending.

Theo một cuộc thăm dò của Gallup, 60% người trưởng thành Mỹ thích tiết kiệm hơn là chi tiêu. Gọi *X* = số người trưởng thành Mỹ trong một mẫu ngẫu nhiên gồm 50 người thích tiết kiệm hơn chi tiêu.

1. What is the probability distribution for *X*?
1. Phân phối xác suất cho *X* là gì?
1. Use your calculator to find the following probabilities:
  
the probability that 25 adults in the sample prefer saving over spendingxác suất để 25 người trưởng thành trong mẫu thích tiết kiệm hơn chi tiêu
the probability that at most 20 adults prefer savingxác suất để có tối đa 20 người trưởng thành thích tiết kiệm
the probability that more than 30 adults prefer savingxác suất để có hơn 30 người trưởng thành thích tiết kiệm
1. Using the formulas, calculate the (i) mean and (ii) standard deviation of *X*.
1. Sử dụng các công thức, hãy tính (i) số trung bình và (ii) độ lệch chuẩn của *X*.
The lifetime risk of developing cancer is about one in 67 (1.5%). Suppose we randomly sample 200 people. Let *X* = the number of people who will develop cancer.

Nguy cơ mắc ung thư suốt đời là khoảng một trên 67 (1,5%). Giả sử chúng ta lấy mẫu ngẫu nhiên 200 người. Gọi *X* = số người sẽ mắc ung thư.

#### Problem

#### Bài toán

1. What is the probability distribution for *X*?
1. Phân phối xác suất cho *X* là gì?
1. Using the formulas, calculate the (i) mean and (ii) standard deviation of *X*.
1. Sử dụng các công thức, hãy tính (i) số trung bình và (ii) độ lệch chuẩn của *X*.
1. Use your calculator to find the probability that at most eight people develop cancer
1. Sử dụng máy tính của bạn để tìm xác suất có tối đa tám người mắc bệnh ung thư
1. Is it more likely that five or six people will develop cancer? Justify your answer numerically.
1. Khả năng năm hay sáu người mắc bệnh ung thư sẽ cao hơn? Hãy biện luận câu trả lời của bạn bằng số liệu.
During a certain NBA season, a player for the Los Angeles Clippers had the highest field goal completion rate in the league. This player scored with 61.3% of his shots. Suppose you choose a random sample of 80 shots made by this player during the season. Let *X* = the number of shots that scored points.

Trong một mùa giải NBA nhất định, một cầu thủ của đội Los Angeles Clippers có tỷ lệ ném bóng thành công cao nhất giải đấu. Cầu thủ này ghi điểm với 61,3% số cú ném của mình. Giả sử bạn chọn một mẫu ngẫu nhiên gồm 80 cú ném được thực hiện bởi cầu thủ này trong mùa giải. Gọi *X* = số cú ném ghi được điểm.

1. What is the probability distribution for *X*?
1. Phân phối xác suất cho *X* là gì?
1. Using the formulas, calculate the (i) mean and (ii) standard deviation of *X*.
1. Sử dụng các công thức, hãy tính (i) số trung bình và (ii) độ lệch chuẩn của *X*.
1. Use your calculator to find the probability that this player scored with 60 of these shots.
1. Sử dụng máy tính của bạn để tìm xác suất cầu thủ này ghi bàn với 60 trong số các cú sút này.
1. Find the probability that this player scored with more than 50 of these shots.
1. Tìm xác suất để cầu thủ này ghi bàn với hơn 50 trong số các cú sút này.
The following example illustrates a problem that is **not** binomial. It violates the condition of independence. ABC College has a student advisory committee made up of ten staff members and six students. The committee wishes to choose a chairperson and a recorder. What is the probability that the chairperson and recorder are both students? The names of all committee members are put into a box, and two names are drawn **without replacement**. The first name drawn determines the chairperson and the second name the recorder. There are two trials. However, the trials are not independent because the outcome of the first trial affects the outcome of the second trial. The probability of a student on the first draw is 616616616. The probability of a student on the second draw is 515515515, when the first draw selects a student. The probability is 615615615, when the first draw selects a staff member. The probability of drawing a student's name changes for each of the trials and, therefore, violates the condition of independence.

Ví dụ sau đây minh họa một bài toán **không** phải là nhị thức. Nó vi phạm điều kiện về tính độc lập. Trường Cao đẳng ABC có một hội đồng cố vấn sinh viên gồm mười nhân viên và sáu sinh viên. Hội đồng muốn chọn một chủ tịch và một thư ký. Xác suất để cả chủ tịch và thư ký đều là sinh viên là bao nhiêu? Tên của tất cả các thành viên hội đồng được cho vào một chiếc hộp, và hai cái tên được rút ra **không hoàn lại**. Cái tên được rút ra đầu tiên xác định chủ tịch và cái tên thứ hai xác định thư ký. Có hai phép thử. Tuy nhiên, các phép thử không độc lập vì kết quả của phép thử đầu tiên ảnh hưởng đến kết quả của phép thử thứ hai. Xác suất chọn được một sinh viên trong lần rút đầu tiên là 616616616. Xác suất chọn được một sinh viên trong lần rút thứ hai là 515515515, khi lần rút đầu tiên chọn được một sinh viên. Xác suất là 615615615, khi lần rút đầu tiên chọn được một nhân viên. Xác suất rút được tên của một sinh viên thay đổi cho mỗi phép thử và do đó, vi phạm điều kiện về tính độc lập.

A lacrosse team is selecting a captain. The names of all the seniors are put into a hat, and the first three that are drawn will be the captains. The names are not replaced once they are drawn (one person cannot be two captains). You want to see if the captains all play the same position. State whether this is binomial or not and state why.

Một đội bóng vợt đang chọn đội trưởng. Tên của tất cả các sinh viên năm cuối được cho vào một chiếc mũ, và ba cái tên đầu tiên được rút ra sẽ là đội trưởng. Các cái tên không được thay thế sau khi đã được rút ra (một người không thể làm hai đội trưởng). Bạn muốn xem liệu tất cả các đội trưởng có chơi cùng một vị trí hay không. Hãy nêu rõ đây có phải là nhị thức hay không và nêu lý do tại sao.
