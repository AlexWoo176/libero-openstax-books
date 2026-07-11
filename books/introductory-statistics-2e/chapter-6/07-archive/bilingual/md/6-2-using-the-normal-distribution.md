## 6.2
 
Using the Normal Distribution

## 6.2
 
Sử dụng phân phối chuẩn

The shaded area in the following graph indicates the area to the left of *x*. This area is represented by the probability *P*(*X* < *x*). Normal tables, computers, and calculators provide or calculate the probability *P*(*X* < *x*).

Phần diện tích được tô bóng trong đồ thị sau đây biểu thị diện tích ở bên trái của *x*. Diện tích này được biểu diễn bằng xác suất *P*(*X* < *x*). Các bảng phân phối chuẩn, máy tính và máy tính cầm tay cung cấp hoặc tính toán xác suất *P*(*X* < *x*).

*Figure 
6.4*

*Hình 
6.4*

The area to the right is then
*P
*(
*X
* >
*x
*) = 1 –
*P
*(
*X
* <
*x
*). Remember,
*P
*(
*X
* <
*x
*) =
Area to the left
 of the vertical line through
*x
*.
*P
*(
*X
* >
*x
*) = 1 –
*P
*(
*X
* <
*x
*) =
Area to the right
 of the vertical line through
*x
*.
*P
*(
*X
* <
*x
*) is the same as
*P
*(
*X
* ≤
*x
*) and
*P
*(
*X
* >
*x
*) is the same as
*P
*(
*X
* ≥
*x
*) for continuous distributions.

Khi đó, diện tích bên phải là
*P
*(
*X
* >
*x
*) = 1 –
*P
*(
*X
* <
*x
*). Hãy nhớ rằng,
*P
*(
*X
* <
*x
*) =
Diện tích bên trái đường thẳng đứng đi qua
*x
*.
*P
*(
*X
* >
*x
*) = 1 –
*P
*(
*X
* <
*x
*) =
Diện tích bên phải đường thẳng đứng đi qua
*x
*.
*P
*(
*X
* <
*x
*) tương tự như
*P
*(
*X
* ≤
*x
*) và
*P
*(
*X
* >
*x
*) tương tự như
*P
*(
*X
* ≥
*x
*) đối với các phân phối liên tục.

### Calculations of Probabilities

### Tính toán các xác suất

Probabilities are calculated using technology. There are instructions given as necessary for the TI-83+ and TI-84 calculators.

Các xác suất được tính toán bằng cách sử dụng công nghệ. Có các hướng dẫn cần thiết dành cho máy tính cầm tay TI-83+ và TI-84.

To calculate the probability, use the probability tables provided in [Appendix H Tables](h-tables)  without the use of technology. The tables include instructions for how to use them.

Để tính xác suất, hãy sử dụng các bảng xác suất được cung cấp trong [Phụ lục H: Các bảng](h-tables) mà không cần sử dụng công nghệ. Các bảng này bao gồm hướng dẫn cách sử dụng chúng.

If the area to the left is 0.0228, then the area to the right is 1 – 0.0228 = 0.9772.

Nếu diện tích bên trái là 0.0228 thì diện tích bên phải là 1 – 0.0228 = 0.9772.

If the area to the left of *x* is 0.012, then what is the area to the right?

Nếu diện tích bên trái của *x* là 0.012, thì diện tích bên phải là bao nhiêu?

The final exam scores in a statistics class were normally distributed with a mean of 63 and a standard deviation of five.

Điểm thi cuối kỳ của một lớp học thống kê có phân phối chuẩn với số trung bình là 63 và độ lệch chuẩn là 5.

#### Problem

#### Bài toán

a. Find the probability that a randomly selected student scored more than 65 on the exam.

a. Tìm xác suất để một học sinh được chọn ngẫu nhiên có điểm thi lớn hơn 65.

Find the percentile for a student scoring 65:

Tìm bách phân vị cho một học sinh đạt điểm 65:

*Press `2nd Distr`

*Press `2:normalcdf`(

*Enter lower bound, upper bound, mean, standard deviation followed by )

*Press `ENTER`.

For this Example, the steps are

`2nd Distr`

`2:normalcdf`(65,1,2nd EE,99,63,5) `ENTER`

The probability that a selected student scored more than 65 is 0.3446.
To find the probability that a selected student scored *more than* 65, subtract the percentile from 1.

*Nhấn `2nd Distr`

*Nhấn `2:normalcdf`(

*Nhập giới hạn dưới, giới hạn trên, số trung bình, độ lệch chuẩn theo sau bởi )

*Nhấn `ENTER`.

Đối với Ví dụ này, các bước là

`2nd Distr`

`2:normalcdf`(65,1,2nd EE,99,63,5) `ENTER`

Xác suất để một học sinh được chọn đạt điểm trên 65 là 0.3446.
Để tìm xác suất một học sinh được chọn đạt điểm *trên* 65, hãy lấy 1 trừ đi bách phân vị.

#### Problem

#### Bài toán

b. Find the probability that a randomly selected student scored less than 85.

b. Tìm xác suất để một học sinh được chọn ngẫu nhiên đạt điểm dưới 85.

#### Problem

#### Bài toán

c. Find the 90^th percentile (that is, find the score *k* that has 90% of the scores below *k* and 10% of the scores above *k*).

c. Tìm bách phân vị thứ 90 (nghĩa là tìm điểm số *k* sao cho có 90% số điểm dưới *k* và 10% số điểm trên *k*).

`invNorm` in `2nd DISTR`. invNorm(area to the left, mean, standard deviation)

For this problem, invNorm(0.90,63,5) = 69.4

`invNorm` trong `2nd DISTR`. invNorm(diện tích bên trái, số trung bình, độ lệch chuẩn)

Đối với bài toán này, invNorm(0.90,63,5) = 69.4

#### Problem

#### Bài toán

d. Find the 70^th percentile (that is, find the score *k* such that 70% of scores are below *k* and 30% of the scores are above *k*).

d. Tìm bách phân vị thứ 70 (nghĩa là tìm điểm số *k* sao cho 70% số điểm dưới *k* và 30% số điểm trên *k*).

The golf scores for a school team were normally distributed with a mean of 68 and a standard deviation of three.

Điểm chơi golf của một đội tuyển trường học được phân phối chuẩn với số trung bình là 68 và độ lệch chuẩn là 3.

Find the probability that a randomly selected golfer scored less than 65.

Tìm xác suất để một người chơi golf được chọn ngẫu nhiên đạt điểm dưới 65.

A personal computer is used for office work at home, research, communication, personal finances, education, entertainment, social networking, and a myriad of other things. Suppose that the average number of hours a household personal computer is used for entertainment is two hours per day. Assume the times for entertainment are normally distributed and the standard deviation for the times is half an hour.

Máy tính cá nhân được sử dụng cho công việc văn phòng tại nhà, nghiên cứu, giao tiếp, tài chính cá nhân, giáo dục, giải trí, mạng xã hội và vô số việc khác. Giả sử số giờ trung bình một máy tính cá nhân của hộ gia đình được sử dụng để giải trí là hai giờ mỗi ngày. Giả định thời gian giải trí được phân phối chuẩn và độ lệch chuẩn của thời gian này là nửa giờ.

#### Problem

#### Bài toán

a. Find the probability that a household personal computer is used for entertainment between 1.8 and 2.75 hours per day.

a. Tìm xác suất để một máy tính cá nhân của hộ gia đình được sử dụng để giải trí từ 1.8 đến 2.75 giờ mỗi ngày.

#### Problem

#### Bài toán

b. Find the maximum number of hours per day that the bottom quartile of households uses a personal computer for entertainment.

b. Tìm số giờ tối đa mỗi ngày mà nhóm tứ phân vị dưới của các hộ gia đình sử dụng máy tính cá nhân để giải trí.

The golf scores for a school team were normally distributed with a mean of 68 and a standard deviation of three. Find the probability that a golfer scored between 66 and 70.

Điểm chơi golf của một đội tuyển trường học được phân phối chuẩn với số trung bình là 68 và độ lệch chuẩn là 3. Tìm xác suất để một người chơi golf đạt điểm từ 66 đến 70.

In the United States the ages 13 to 55+ of smartphone users approximately follow a normal distribution with approximate mean and standard deviation of 36.9 years and 13.9 years, respectively.

Tại Hoa Kỳ, độ tuổi từ 13 đến 55+ của người dùng điện thoại thông minh xấp xỉ tuân theo phân phối chuẩn với số trung bình và độ lệch chuẩn xấp xỉ lần lượt là 36.9 tuổi và 13.9 tuổi.

#### Problem

#### Bài toán

a. Determine the probability that a random smartphone user in the age range 13 to 55+ is between 23 and 64.7 years old.

a. Xác định xác suất để một người dùng điện thoại thông minh ngẫu nhiên trong độ tuổi từ 13 đến 55+ có độ tuổi từ 23 đến 64.7 tuổi.

b. Determine the probability that a randomly selected smartphone user in the age range 13 to 55+ is at most 50.8 years old.

b. Xác định xác suất để một người dùng điện thoại thông minh được chọn ngẫu nhiên trong độ tuổi từ 13 đến 55+ có độ tuổi tối đa là 50.8 tuổi.

c. Find the 80^th percentile of this distribution, and interpret it in a complete sentence.

c. Tìm bách phân vị thứ 80 của phân phối này, và giải thích ý nghĩa của nó bằng một câu hoàn chỉnh.

Use the information in [Example 6.10](6-2-using-the-normal-distribution#eip-562) to answer the following questions.

Sử dụng thông tin trong [Ví dụ 6.10](6-2-using-the-normal-distribution#eip-562) để trả lời các câu hỏi sau.

1. Find the 30^th percentile, and interpret it in a complete sentence.
1. Tìm bách phân vị thứ 30^th, và giải thích ý nghĩa của nó bằng một câu hoàn chỉnh.
1. What is the probability that the age of a randomly selected smartphone user in the range 13 to 55+ is less than 27 years old.
1. Xác suất để tuổi của một người dùng điện thoại thông minh được chọn ngẫu nhiên trong khoảng từ 13 đến 55+ nhỏ hơn 27 tuổi là bao nhiêu.
In the United States the ages 13 to 55+ of smartphone users approximately follow a normal distribution with approximate mean and standard deviation of 36.9 years and 13.9 years respectively. Using this information, answer the following questions (round answers to one decimal place).

Tại Hoa Kỳ, độ tuổi từ 13 đến 55+ của người dùng điện thoại thông minh xấp xỉ tuân theo phân phối chuẩn với số trung bình và độ lệch chuẩn xấp xỉ lần lượt là 36.9 tuổi và 13.9 tuổi. Sử dụng thông tin này, hãy trả lời các câu hỏi sau (làm tròn câu trả lời đến một chữ số thập phân).

#### Problem

#### Bài toán

a. Calculate the interquartile range (*IQR*).

a. Tính khoảng tứ phân vị (*IQR*).

b. Forty percent of the smartphone users from 13 to 55+ are at least what age?

b. Bốn mươi phần trăm người dùng điện thoại thông minh từ 13 đến 55+ tuổi có độ tuổi ít nhất là bao nhiêu?

Two thousand students took an exam. The scores on the exam have an approximate normal distribution with a mean *μ* = 81 points and standard deviation *σ* = 15 points.

Hai nghìn học sinh đã tham gia một kỳ thi. Điểm số của kỳ thi có phân phối xấp xỉ chuẩn với số trung bình *μ* = 81 điểm và độ lệch chuẩn *σ* = 15 điểm.

1. Calculate the first- and third-quartile scores for this exam.
1. Tính điểm số của tứ phân vị thứ nhất và thứ ba cho kỳ thi này.
1. The middle 50% of the exam scores are between what two values?
1. 50% số điểm thi ở giữa nằm trong khoảng hai giá trị nào?
A citrus farmer who grows mandarin oranges finds that the diameters of mandarin oranges harvested on his farm follow a normal distribution with a mean diameter of 5.85 cm and a standard deviation of 0.24 cm.

Một người trồng cam quýt nhận thấy đường kính của những quả cam quýt thu hoạch trên trang trại của mình tuân theo phân phối chuẩn với đường kính trung bình là 5,85 cm và độ lệch chuẩn là 0,24 cm.

#### Problem

#### Bài toán

a. Find the probability that a randomly selected mandarin orange from this farm has a diameter larger than 6.0 cm. Sketch the graph.

a. Tìm xác suất để một quả cam quýt được chọn ngẫu nhiên từ trang trại này có đường kính lớn hơn 6,0 cm. Vẽ phác thảo đồ thị.

b. The middle 20% of mandarin oranges from this farm have diameters between ______ and ______.

b. 20% số quả cam quýt ở giữa từ trang trại này có đường kính trong khoảng từ ______ đến ______.

c.	Find the 90^th percentile for the diameters of mandarin oranges, and interpret it in a complete sentence.

c.	Tìm bách phân vị thứ 90^th cho đường kính của quả cam quýt, và giải thích ý nghĩa của nó bằng một câu hoàn chỉnh.

Using the information from [Example 6.12](6-2-using-the-normal-distribution#eip-662), answer the following:

Sử dụng thông tin từ [Ví dụ 6.12](6-2-using-the-normal-distribution#eip-662), hãy trả lời các câu hỏi sau:

1. The middle 40% of mandarin oranges from this farm are between ______ and ______.
1. 40% số quả cam quýt ở giữa từ trang trại này nằm trong khoảng từ ______ đến ______.
1. Find the 16^th percentile and interpret it in a complete sentence.
1. Tìm bách phân vị thứ 16^th và giải thích ý nghĩa của nó bằng một câu hoàn chỉnh.
