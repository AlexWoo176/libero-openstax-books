## 8.3
 
A Population Proportion

## 8.3
 
Tỷ lệ quần thể

During an election year, we see articles in the newspaper that state confidence intervals in terms of proportions or percentages. For example, a poll for a particular candidate running for president might show that the candidate has 40% of the vote within three percentage points  (if the sample is large enough). Often, election polls are calculated with 95% confidence, so, the pollsters would be 95% confident that the true proportion of voters who favored the candidate would be between 0.37 and 0.43: (0.40 – 0.03,0.40 + 0.03).

Trong một năm bầu cử, chúng ta thấy các bài báo trên mặt báo nêu các khoảng tin cậy dưới dạng tỷ lệ hoặc phần trăm. Ví dụ, một cuộc thăm dò cho một ứng cử viên cụ thể đang tranh cử tổng thống có thể cho thấy ứng cử viên đó có 40% số phiếu bầu trong phạm vi ba điểm phần trăm (nếu mẫu đủ lớn). Thông thường, các cuộc thăm dò bầu cử được tính toán với độ tin cậy 95%, vì vậy, những người thăm dò sẽ tự tin 95% rằng tỷ lệ thực tế cử tri ủng hộ ứng cử viên đó sẽ nằm trong khoảng từ 0,37 đến 0,43: (0,40 – 0,03, 0,40 + 0,03).

Investors in the stock market are interested in the true proportion of stocks that go up and down each week. Businesses that sell personal computers are interested in the proportion of households in the United States that own personal computers. Confidence intervals can be calculated for the true proportion of stocks that go up or down each week and for the true proportion of households in the United States that own personal computers.

Các nhà đầu tư trên thị trường chứng khoán quan tâm đến tỷ lệ thực tế các cổ phiếu tăng và giảm mỗi tuần. Các doanh nghiệp bán máy tính cá nhân quan tâm đến tỷ lệ các hộ gia đình ở Hoa Kỳ sở hữu máy tính cá nhân. Các khoảng tin cậy có thể được tính toán cho tỷ lệ thực tế các cổ phiếu tăng hoặc giảm mỗi tuần và cho tỷ lệ thực tế các hộ gia đình ở Hoa Kỳ sở hữu máy tính cá nhân.

The procedure to find the confidence interval, the sample size, the error bound, and the confidence level for a proportion is similar to that for the population mean, but the
 formulas are different.

Quy trình tìm khoảng tin cậy, kích thước mẫu, Giới hạn sai số và Độ tin cậy cho một tỷ lệ tương tự như đối với số trung bình quần thể, nhưng các công thức thì khác nhau.

**How do you know you are dealing with a proportion problem?** First, the underlying **distribution is a** binomial distribution. (There is no mention of a mean or average.) If *X* is a binomial random variable, then *X* ~ *B*(*n*, *p*)  where *n* is the number of trials and *p* is the probability of a success. To form a proportion, take *X*, the random variable for the number of successes and divide it by *n*, the number of trials (or the sample size). The random variable p′p′ (read "P prime") is that proportion,

**Làm thế nào để bạn biết mình đang giải quyết một bài toán về tỷ lệ?** Trước hết, **phân phối** cơ bản **là một** Phân phối nhị thức. (Không có đề cập đến số trung bình.) Nếu *X* là một biến ngẫu nhiên nhị thức, thì *X* ~ *B*(*n*, *p*) trong đó *n* là số phép thử và *p* là xác suất thành công. Để tạo thành một tỷ lệ, hãy lấy *X*, biến ngẫu nhiên cho số lần thành công và chia nó cho *n*, số lần thử (hoặc kích thước mẫu). Biến ngẫu nhiên p′p′ (đọc là "P phẩy") là tỷ lệ đó,

P
′

=
X
n

P
′

=
X
n

P
′

=
X
n

P
′

=
X
n

(Sometimes the random variable is denoted as 

P
^

P
^
, read "P hat".)

(Đôi khi biến ngẫu nhiên được ký hiệu là 

P
^

P
^
, đọc là "P mũ".)

When *n* is large and *p* is not close to zero or one, we can use the normal distribution to approximate the binomial.

Khi *n* lớn và *p* không gần bằng 0 hoặc 1, chúng ta có thể sử dụng Phân phối chuẩn để xấp xỉ phân phối nhị thức.

X~N(np,

npq

)

X~N(np,

npq

)

X~N(np,

npq

)

X~N(np,

npq

)

If we divide the random variable, the mean, and the standard
deviation by *n*, we get a normal distribution of proportions with p′p′, called the
estimated proportion, as the random variable. (Recall that a proportion as the
number of successes divided by *n*.)

Nếu chúng ta chia biến ngẫu nhiên, số trung bình và độ lệch chuẩn cho *n*, chúng ta nhận được một phân phối chuẩn của các tỷ lệ với p′p′, được gọi là tỷ lệ ước tính, là biến ngẫu nhiên. (Nhớ rằng một tỷ lệ là số lần thành công chia cho *n*.)

X
n

=
P
′

~ N(

np

n

,

npq

n

)

X
n

=
P
′

~ N(

np

n

,

npq

n

)

X
n

=
P
′

~ N(

np

n

,

npq

n

)

X
n

=
P
′

~ N(

np

n

,

npq

n

)

Using algebra to simplify : 

npq

n

=

pq

n

npq

n

=

pq

n

Sử dụng đại số để đơn giản hóa: 

npq

n

=

pq

n

npq

n

=

pq

n

**p′p′ follows a normal distribution for proportions**:
  Xn=P′~N(p,pqn)Xn=P′~N(p,pqn)

**p′p′ tuân theo một phân phối chuẩn cho các tỷ lệ**:
  Xn=P′~N(p,pqn)Xn=P′~N(p,pqn)

The confidence interval has the form (p′p′ – *EBP*, p′p′ + *EBP*). *EBP* is error bound for the proportion.

Khoảng tin cậy có dạng (p′p′ – *EBP*, p′p′ + *EBP*). *EBP* là giới hạn sai số cho tỷ lệ.

p′p′ = 

x
n

x
n

p′p′

x
n

x
n

p′p′ = the **estimated proportion** of successes (p′p′ is a **point estimate** for *p*, the true proportion.)

p′p′ = **tỷ lệ ước tính** của các lần thành công (p′p′ là một **ước lượng điểm** cho *p*, tỷ lệ thực tế.)

*x* = the **number** of successes

*x* = **số** lần thành công

*n* = the size of the sample

*n* = kích thước của mẫu

**The error bound for a proportion is**

**Sai số biên cho một tỷ lệ là**

EBP=(

z

α
2

)(

p
′

q
′

n

)

EBP=(

z

α
2

)(

p
′

q
′

n

)
 where q′q′ = 1 – p′p′

EBP=(

z

α
2

)(

p
′

q
′

n

)

EBP=(

z

α
2

)(

p
′

q
′

n

)
 trong đó q′q′ = 1 – p′p′

This formula is similar to the error bound formula for a mean, except that the "appropriate standard deviation" is different. For a mean, when the population standard deviation is known, the appropriate standard deviation that we use is 

σ

n

σ

n

. For a proportion, the appropriate standard deviation is 

p
q

n

p
q

n

.

Công thức này tương tự như công thức sai số biên cho số trung bình, ngoại trừ việc "độ lệch chuẩn phù hợp" là khác nhau. Đối với số trung bình, khi độ lệch chuẩn quần thể đã biết, độ lệch chuẩn phù hợp mà chúng ta sử dụng là 

σ

n

σ

n

. Đối với một tỷ lệ, độ lệch chuẩn phù hợp là 

p
q

n

p
q

n

.

However, in the error bound formula, we use
  

p
′

q
′

n

p
′

q
′

n

 as the standard deviation, instead of 

p
q

n

p
q

n

.

Tuy nhiên, trong công thức sai số biên, chúng ta sử dụng 

p
′

q
′

n

p
′

q
′

n

 làm độ lệch chuẩn, thay vì 

p
q

n

p
q

n

.

In the error bound formula, the ** sample proportions p′p′ and q′q′ are estimates of the unknown population proportions *p* and *q***. The estimated proportions p′p′ and q′q′ are used because *p* and *q* are not known. The sample proportions p′p′ and q′q′ are calculated from the data: p′p′ is the estimated proportion of successes, and q′q′ is the estimated proportion of failures.

Trong công thức sai số biên, **các tỷ lệ mẫu p′p′ và q′q′ là các ước lượng của các tỷ lệ quần thể chưa biết *p* và *q***. Các tỷ lệ ước lượng p′p′ và q′q′ được sử dụng vì *p* và *q* không được biết. Các tỷ lệ mẫu p′p′ và q′q′ được tính toán từ dữ liệu: p′p′ là tỷ lệ thành công ước lượng, và q′q′ là tỷ lệ thất bại ước lượng.

The confidence interval can be used only if the number of successes np′np′ and the number of failures nq′nq′ are both greater than five.

Khoảng tin cậy chỉ có thể được sử dụng nếu số lượng thành công np′np′ và số lượng thất bại nq′nq′ đều lớn hơn năm.

For the normal distribution of proportions, the *z*-score formula is as follows.

Đối với phân phối chuẩn của các tỷ lệ, công thức *z*-score như sau.

If 

P
′

~N(

p,

pq

n

)

P
′

~N(

p,

pq

n

)
 then the *z*-score formula is 

z=

p
′

−p

pq

n

z=

p
′

−p

pq

n

Nếu 

P
′

~N(

p,

pq

n

)

P
′

~N(

p,

pq

n

)
 thì công thức *z*-score là 

z=

p
′

−p

pq

n

z=

p
′

−p

pq

n

#### Problem

#### Bài toán

Suppose that a market research firm is hired to estimate the percent of adults living in a large city who have smartphones.  Five hundred randomly selected adult residents in this city are surveyed to determine whether they have smartphones. Of
  the 500 people surveyed, 421 responded yes - they own smartphones. Using a 95% confidence level, compute a confidence interval estimate for the true proportion of adult residents of this city who have smartphones.

Giả sử một công ty nghiên cứu thị trường được thuê để ước tính tỷ lệ phần trăm người trưởng thành sống tại một thành phố lớn có điện thoại thông minh. Năm trăm cư dân trưởng thành được chọn ngẫu nhiên tại thành phố này được khảo sát để xác định xem họ có điện thoại thông minh hay không. Trong số 500 người được khảo sát, 421 người trả lời có - họ sở hữu điện thoại thông minh. Sử dụng mức tin cậy 95%, hãy tính toán một ước lượng khoảng tin cậy cho tỷ lệ thực sự của cư dân trưởng thành tại thành phố này có điện thoại thông minh.

Suppose 250 randomly selected people are surveyed to determine if they own a tablet. Of the 250 surveyed, 98 reported owning a tablet. Using a 95% confidence level, compute a confidence interval estimate for the true proportion of people who own tablets.

Giả sử 250 người được chọn ngẫu nhiên được khảo sát để xác định xem họ có sở hữu máy tính bảng hay không. Trong số 250 người được khảo sát, 98 người báo cáo sở hữu máy tính bảng. Sử dụng mức tin cậy 95%, hãy tính toán một ước lượng khoảng tin cậy cho tỷ lệ thực sự của những người sở hữu máy tính bảng.

#### Problem

#### Bài toán

For a class project, a political science student at a large university wants to estimate the percent of students who are registered voters. He surveys 500 students and finds that 300 are registered voters. Compute a 90% confidence interval for the true percent of students who are registered voters, and interpret the confidence interval.

Cho một dự án lớp học, một sinh viên khoa học chính trị tại một trường đại học lớn muốn ước tính tỷ lệ phần trăm sinh viên là cử tri đã đăng ký. Anh ấy khảo sát 500 sinh viên và thấy rằng 300 người là cử tri đã đăng ký. Hãy tính khoảng tin cậy 90% cho tỷ lệ phần trăm thực sự của sinh viên là cử tri đã đăng ký, và giải thích khoảng tin cậy đó.

A student polls their school to see if students in the school district are for or against the new legislation regarding school uniforms. They survey 600 students and finds that 480 are against the new legislation.

Một sinh viên thăm dò ý kiến trường học của họ để xem liệu học sinh trong khu học chánh có ủng hộ hay phản đối luật mới liên quan đến đồng phục học sinh hay không. Họ khảo sát 600 học sinh và thấy rằng 480 người phản đối luật mới.

a. Compute a 90% confidence interval for the true percent of students who are against the new legislation, and interpret the confidence interval.

a. Tính khoảng tin cậy 90% cho tỷ lệ phần trăm thực sự của học sinh phản đối luật mới, và giải thích khoảng tin cậy đó.

b. In a sample of 300 students, 68% said they own an iPod and a smart phone. Compute a 97% confidence interval for the true percent of students who own an iPod and a smartphone.

b. Trong một mẫu gồm 300 học sinh, 68% cho biết họ sở hữu iPod và điện thoại thông minh. Tính khoảng tin cậy 97% cho tỷ lệ phần trăm thực sự của học sinh sở hữu iPod và điện thoại thông minh.

### “Plus Four” Confidence Interval for *p*

### Khoảng tin cậy "Cộng bốn" cho *p*

There is a certain amount of error introduced into the process of calculating a confidence interval for a proportion. Because we do not know the true proportion for the population, we are forced to use point estimates to calculate the appropriate standard deviation of the sampling distribution. Studies have shown that the resulting estimation of the standard deviation can be flawed.

Có một lượng sai số nhất định được đưa vào quá trình tính toán khoảng tin cậy cho một tỷ lệ. Vì chúng ta không biết tỷ lệ thực sự cho quần thể, chúng ta buộc phải sử dụng các ước lượng điểm để tính toán độ lệch chuẩn phù hợp của phân phối mẫu. Các nghiên cứu đã chỉ ra rằng việc ước tính độ lệch chuẩn thu được có thể bị sai sót.

Fortunately, there is a simple adjustment that allows us to produce more accurate confidence intervals. We simply pretend that we have four additional observations. Two of these observations are successes and two are failures. The new sample size, then, is *n* + 4, and the new count of successes is *x* + 2.

May mắn thay, có một sự điều chỉnh đơn giản cho phép chúng ta tạo ra các khoảng tin cậy chính xác hơn. Chúng ta chỉ cần giả định rằng chúng ta có thêm bốn quan sát. Hai trong số các quan sát này là thành công và hai là thất bại. Khi đó, kích thước mẫu mới là *n* + 4, và số lượng thành công mới là *x* + 2.

Computer studies have demonstrated the effectiveness of this method. It should be used when the confidence level desired is at least 90% and the sample size is at least ten.

Các nghiên cứu trên máy tính đã chứng minh hiệu quả của phương pháp này. Nó nên được sử dụng khi mức tin cậy mong muốn ít nhất là 90% và kích thước mẫu ít nhất là mười.

#### Problem

#### Bài toán

A random sample of 25 statistics students was asked: “Have you smoked a cigarette in the past week?” Six students reported smoking within the past week. Use the “plus-four” method to find a 95% confidence interval for the true proportion of statistics students who smoke.

Một mẫu ngẫu nhiên gồm 25 sinh viên thống kê được hỏi: “Bạn có hút thuốc lá trong tuần qua không?” Sáu sinh viên báo cáo có hút thuốc trong tuần qua. Sử dụng phương pháp “cộng bốn” để tìm khoảng tin cậy 95% cho tỷ lệ thực sự của sinh viên thống kê hút thuốc.

Out of a random sample of 65 first-year students at State University, 31 students have declared a major. Use the “plus-four” method to find a 96% confidence interval for the true proportion of first-year students at State University who have declared a major.

Từ một mẫu ngẫu nhiên gồm 65 sinh viên năm nhất tại Đại học Bang, 31 sinh viên đã đăng ký chuyên ngành. Sử dụng phương pháp “cộng bốn” để tìm khoảng tin cậy 96% cho tỷ lệ thực sự của sinh viên năm nhất tại Đại học Bang đã đăng ký chuyên ngành.

#### Problem

#### Bài toán

A marketing research firm conducted a survey regarding the potential purchase of electric vehicles among adults aged 18–29. In a group of 50 adults aged 18–29, 13 of them reported they would consider the purchase of an electric vehicle. Use the “plus four” method to find a 90% confidence interval for the true proportion of adults aged 18–29 who would consider the purchase of an electric vehicle.

Một công ty nghiên cứu thị trường đã thực hiện một cuộc khảo sát về khả năng mua xe điện trong số những người trưởng thành từ 18–29 tuổi. Trong một nhóm gồm 50 người trưởng thành từ 18–29 tuổi, 13 người cho biết họ sẽ cân nhắc việc mua xe điện. Sử dụng phương pháp “cộng bốn” để tìm khoảng tin cậy 90% cho tỷ lệ thực sự của những người trưởng thành từ 18–29 tuổi sẽ cân nhắc việc mua xe điện.

The survey referenced in [Example 8.13](8-3-a-population-proportion#eip-251) talked to adults aged 18–29 in smaller focus groups but also interviewed additional individuals over the phone. When the study was complete, 588 adults aged 18–29 had answered the question about their potential purchase of an electric vehicle with 159 saying that they would consider such a purchase. Use the “plus-four” method to find a 90% confidence interval for the true proportion of adults aged 18–29 who would consider the purchase of an electric vehicle based on this larger sample. Compare the results to those in [Example 8.13](8-3-a-population-proportion#eip-251).

Cuộc khảo sát được tham chiếu trong [Ví dụ 8.13](8-3-a-population-proportion#eip-251) đã trao đổi với những người trưởng thành từ 18–29 tuổi trong các nhóm tập trung nhỏ hơn nhưng cũng phỏng vấn thêm các cá nhân qua điện thoại. Khi nghiên cứu hoàn tất, 588 người trưởng thành từ 18–29 tuổi đã trả lời câu hỏi về khả năng mua xe điện của họ, với 159 người nói rằng họ sẽ cân nhắc việc mua như vậy. Sử dụng phương pháp “cộng bốn” để tìm khoảng tin cậy 90% cho tỷ lệ thực sự của những người trưởng thành từ 18–29 tuổi sẽ cân nhắc việc mua xe điện dựa trên mẫu lớn hơn này. So sánh kết quả với các kết quả trong [Ví dụ 8.13](8-3-a-population-proportion#eip-251).

### Calculating the Sample Size *n*

### Tính toán kích thước mẫu *n*

If researchers desire a specific margin of error, then they can use the error bound formula to calculate the required sample size.

Nếu các nhà nghiên cứu mong muốn một sai số biên cụ thể, thì họ có thể sử dụng công thức giới hạn sai số để tính toán kích thước mẫu cần thiết.

The error bound formula for a population proportion is

Công thức giới hạn sai số cho một tỷ lệ quần thể là

- EBP=(

z

α
2

)(

p
′

q
′

n

)

EBP=(

z

α
2

)(

p
′

q
′

n

)
- EBP=(

z

α
2

)(

p
′

q
′

n

)

EBP=(

z

α
2

)(

p
′

q
′

n

)
- Solving for *n* gives you an equation for the sample size.
- Giải cho *n* cung cấp cho bạn một phương trình cho kích thước mẫu.
- n=

(

z

α
2

)

2

(
p
′

q
′

)

EB
P
2

n=

(

z

α
2

)

2

(
p
′

q
′

)

EB
P
2
- n=

(

z

α
2

)

2

(
p
′

q
′

)

EB
P
2

n=

(

z

α
2

)

2

(
p
′

q
′

)

EB
P
2
#### Problem

#### Bài toán

Suppose a mobile phone company wants to determine the current percentage of customers aged 50+ who use text messaging on their cell phones. How many customers aged 50+ should the company survey in order to be 90% confident that the estimated (sample) proportion is within three percentage points of the true population proportion of customers aged 50+ who use text messaging on their cell phones.

Giả sử một công ty điện thoại di động muốn xác định tỷ lệ phần trăm hiện tại của khách hàng từ 50 tuổi trở lên sử dụng tin nhắn văn bản trên điện thoại di động của họ. Công ty nên khảo sát bao nhiêu khách hàng từ 50 tuổi trở lên để tự tin 90% rằng tỷ lệ ước tính (mẫu) nằm trong phạm vi ba điểm phần trăm so với tỷ lệ quần thể thực sự của khách hàng từ 50 tuổi trở lên sử dụng tin nhắn văn bản trên điện thoại di động của họ.

Suppose an internet marketing company wants to determine the current percentage of customers who click on ads on their smartphones. How many customers should the company survey in order to be 90% confident that the estimated proportion is within five percentage points of the true population proportion of customers who click on ads on their smartphones?

Giả sử một công ty tiếp thị internet muốn xác định tỷ lệ phần trăm hiện tại của khách hàng nhấp vào quảng cáo trên điện thoại thông minh của họ. Công ty nên khảo sát bao nhiêu khách hàng để tự tin 90% rằng tỷ lệ ước tính nằm trong phạm vi năm điểm phần trăm so với tỷ lệ quần thể thực sự của khách hàng nhấp vào quảng cáo trên điện thoại thông minh của họ?
