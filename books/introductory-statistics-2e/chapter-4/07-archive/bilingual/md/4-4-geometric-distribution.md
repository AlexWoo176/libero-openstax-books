## 4.4
 
Geometric Distribution

## 4.4
 
Phân phối hình học

There are four main characteristics of a geometric experiment.

Có bốn đặc điểm chính của một phép thử hình học.

1. A trial is repeated until a success occurs. Think of this as one or more Bernoulli trials with all failures except the last one, which is a success. In other words, you keep repeating what you are doing until the first success. Then you stop. For example, you throw a dart at a bullseye until you hit the bullseye. The first time you hit the bullseye is a "success," so you stop throwing the dart. It might take six tries until you hit the bullseye. You can think of the trials as failure, failure, failure, failure, failure, success, STOP. In theory, the number of trials could go on forever.
1. Một phép thử được lặp lại cho đến khi đạt được thành công. Hãy nghĩ về điều này như một hoặc nhiều phép thử Bernoulli với tất cả các kết quả là thất bại ngoại trừ lần cuối cùng, đó là một thành công. Nói cách khác, bạn tiếp tục lặp lại những gì bạn đang làm cho đến khi đạt được thành công đầu tiên. Sau đó bạn dừng lại. Ví dụ, bạn ném phi tiêu vào hồng tâm cho đến khi bạn trúng hồng tâm. Lần đầu tiên bạn trúng hồng tâm là một "thành công", vì vậy bạn ngừng ném phi tiêu. Có thể mất sáu lần thử cho đến khi bạn trúng hồng tâm. Bạn có thể coi các phép thử là thất bại, thất bại, thất bại, thất bại, thất bại, thành công, DỪNG LẠI. Về lý thuyết, số lần thử có thể kéo dài mãi mãi.
1. The repeated trials are independent of each other.
1. Các phép thử lặp lại độc lập với nhau.
1. The probability, p, of a success and the probability, q, of a failure is the same for each trial. 𝑝 +𝑞⁢  =1p+q⁢ =1p+q =1 and 𝑞 =1 −𝑝.q=1-p.q=1-p. For example, the probability of rolling a three when you throw one fair die is 1/61/61/6. This is true no matter how many times you roll the die. Suppose you want to know the probability of getting the first three on the fifth roll. On rolls one through four, you do not get a face with a three. The probability for each of the rolls is 𝑞 =5/6,q=5/6,q=5/6,  the probability of a failure. The probability of getting a first three on the fifth roll is 
  (5/6)⁢(5/6)⁢(5/6)⁢(5/6)⁢(1/6)⁢  = ⁢0.0804(5/6)⁢(5/6)⁢(5/6)⁢(5/6)⁢(1/6)⁢ = ⁢0.0804(5/6)(5/6)(5/6)(5/6)(1/6) = 0.0804
1. Xác suất p của một thành công và xác suất q của một thất bại là như nhau cho mỗi phép thử. 𝑝 +𝑞⁢  =1p+q⁢ =1p+q =1 và 𝑞 =1 −𝑝.q=1-p.q=1-p. Ví dụ, xác suất gieo được số ba khi bạn tung một con xúc xắc cân đối là 1/61/61/6. Điều này đúng bất kể bạn tung xúc xắc bao nhiêu lần. Giả sử bạn muốn biết xác suất nhận được số ba đầu tiên ở lần tung thứ năm. Ở các lần tung từ một đến bốn, bạn không nhận được mặt có số ba. Xác suất cho mỗi lần tung là 𝑞 =5/6,q=5/6,q=5/6, xác suất của một thất bại. Xác suất nhận được số ba đầu tiên ở lần tung thứ năm là (5/6)⁢(5/6)⁢(5/6)⁢(5/6)⁢(1/6)⁢  = ⁢0.0804(5/6)⁢(5/6)⁢(5/6)⁢(5/6)⁢(1/6)⁢ = ⁢0.0804(5/6)(5/6)(5/6)(5/6)(1/6) = 0.0804
1. The random variable X represents the number of the trial in which the first success occurs.  That is, X = the number of independent trials until the first success.
1. Biến ngẫu nhiên X đại diện cho số lần thử mà tại đó thành công đầu tiên xảy ra. Nghĩa là, X = số lần thử độc lập cho đến khi đạt được thành công đầu tiên.
The following are additional attributes of the geometric distribution:

Sau đây là các thuộc tính bổ sung của phân phối hình học:

1. The random variable is discrete. The random variable may be defined in two ways depending upon the analyst’s interest. In the example above for throwing a die, the question was “What is the probability that the first success will be on the fifth throw?” Alternatively, the question could be asked as “What is the probability that it takes four failures before a success?” We will see that each way of asking the question will alter the form of the geometric probability density function slightly and will change the mean and standard deviation of the geometric pdf.
1. Biến ngẫu nhiên này là rời rạc. Biến ngẫu nhiên có thể được định nghĩa theo hai cách tùy thuộc vào mối quan tâm của nhà phân tích. Trong ví dụ trên về việc gieo một con xúc xắc, câu hỏi là “Xác suất để lần thành công đầu tiên xảy ra ở lần gieo thứ năm là bao nhiêu?” Cách khác, câu hỏi có thể được đặt ra là “Xác suất để cần bốn lần thất bại trước khi có một lần thành công là bao nhiêu?” Chúng ta sẽ thấy rằng mỗi cách đặt câu hỏi sẽ làm thay đổi nhẹ dạng của hàm mật độ xác suất hình học và sẽ làm thay đổi số trung bình và độ lệch chuẩn của hàm phân phối xác suất hình học.
1. Implicit in the random variable is that the probability of a success is constant and therefore so is the probability of a failure. For flipping a coin this is obvious, but in experiments that require skill, such as hitting a baseball or throwing a dart, one might consider that learning during the experiment would alter the probability of a success. The geometric distribution cannot capture “learning” thus the historical probability of success is assumed to be constant.
1. Điều ẩn ý trong biến ngẫu nhiên là xác suất thành công là hằng số và do đó xác suất thất bại cũng vậy. Đối với việc tung đồng xu, điều này là hiển nhiên, nhưng trong các thực nghiệm đòi hỏi kỹ năng, chẳng hạn như đánh bóng chày hoặc ném phi tiêu, người ta có thể cho rằng việc học hỏi trong quá trình thực nghiệm sẽ làm thay đổi xác suất thành công. Phân phối hình học không thể nắm bắt được “sự học hỏi”, do đó xác suất thành công trong quá khứ được giả định là hằng số.
1. The geometric distribution is “memoryless.” There are very few probability density functions that are what is known as “memoryless,” and the Geometric distribution is the only one with a discrete random variable that is memoryless. As an example, historically Major League Baseball player Jones has a record of hitting the ball for at least an advance to first base with a probability of 0.20. Jones has not had a hit in his last 10 times at bat. What is the probability that Jones will get a hit in his third time at bat? The answer ignores his 10 previous failures. All events prior to the events in current time are irrelevant and thus are considered “memoryless.”
1. Phân phối hình học là “không có bộ nhớ”. Có rất ít hàm mật độ xác suất được gọi là “không có bộ nhớ”, và phân phối hình học là phân phối duy nhất có biến ngẫu nhiên rời rạc mà không có bộ nhớ. Ví dụ, trong lịch sử, cầu thủ Jones của giải Major League Baseball có thành tích đánh bóng để tiến ít nhất đến căn cứ thứ nhất với xác suất là 0,20. Jones đã không có cú đánh nào trong 10 lần đánh bóng gần nhất của mình. Xác suất để Jones có một cú đánh trong lần đánh bóng thứ ba của anh ấy là bao nhiêu? Câu trả lời bỏ qua 10 lần thất bại trước đó của anh ấy. Tất cả các biến cố trước các biến cố ở thời điểm hiện tại đều không liên quan và do đó được coi là “không có bộ nhớ”.
Formally: 𝑃⁡(𝑥=𝑛+𝑘|𝑥≥𝑘+1) =𝑃⁡(𝑥 =𝑛),P⁡(x=n+k|x≥k+1)=P⁡(x=n),Px=n+k|x≥k+1=P(x=n), where k = number of previous failures

Về mặt hình thức: 𝑃⁡(𝑥=𝑛+𝑘|𝑥≥𝑘+1) =𝑃⁡(𝑥 =𝑛),P⁡(x=n+k|x≥k+1)=P⁡(x=n),Px=n+k|x≥k+1=P(x=n), trong đó k = số lần thất bại trước đó

Jones’s probability of a hit begins anew each time he comes to bat. This feature of the geometric distribution results in a curious result: Drawing parts from a manufacturing process to test for parts that are defective, the geometric distribution begins with a clean slate each time the tests begin with no consideration of previous test results. More on this when we get to the exponential probability density function.

Xác suất trúng của Jones bắt đầu lại từ đầu mỗi khi anh ấy đến lượt đánh bóng. Đặc điểm này của phân phối hình học dẫn đến một kết quả thú vị: Khi lấy các bộ phận từ một quy trình sản xuất để kiểm tra xem có bộ phận nào bị lỗi hay không, phân phối hình học bắt đầu lại từ đầu mỗi khi các thử nghiệm bắt đầu mà không xem xét đến kết quả của các thử nghiệm trước đó. Chúng ta sẽ tìm hiểu thêm về điều này khi đến phần hàm mật độ xác suất mũ.

You play a game of chance that you can either win or lose (there are no other possibilities) **until** you lose. Your probability of losing is *p* = 0.57. What is the
probability that it takes five games until you lose? Let *X* = the number of games you play until you lose (includes the losing game). Then *X* takes on the values 1, 2, 3, ... (could go on indefinitely). The probability question is *P*(*x* = 5).

Bạn chơi một trò chơi may rủi mà bạn có thể thắng hoặc thua (không có khả năng nào khác) **cho đến khi** bạn thua. Xác suất thua của bạn là *p* = 0,57. Xác suất để bạn mất năm ván mới thua là bao nhiêu? Gọi *X* = số ván bạn chơi cho đến khi bạn thua (bao gồm cả ván thua). Khi đó *X* nhận các giá trị 1, 2, 3, ... (có thể tiếp tục vô hạn). Câu hỏi xác suất là *P*(*x* = 5).

You throw darts at a board until you hit the center area. Your probability of hitting the center area is *p* = 0.17. You want to find the probability that it takes eight throws until you hit the center. What values does *X* take on?

Bạn ném phi tiêu vào bảng cho đến khi trúng vùng trung tâm. Xác suất trúng vùng trung tâm của bạn là *p* = 0,17. Bạn muốn tìm xác suất để mất tám lần ném mới trúng tâm. *X* nhận những giá trị nào?

#### Problem

#### Bài toán

A safety engineer feels that 35% of all industrial accidents in the plant are caused by failure of employees to follow instructions. They decide to look at the accident reports (selected randomly and replaced in the pile after reading) **until** they find one that shows an accident caused by failure of employees to follow instructions. On average, how many reports would the safety engineer **expect** to look at until they find a report showing an accident caused by employee failure to follow instructions? What is the probability that the safety engineer will have to examine at least three reports until they find a report showing an accident caused by employee failure to follow instructions?

Một kỹ sư an toàn cho rằng 35% tổng số tai nạn công nghiệp tại nhà máy là do nhân viên không tuân thủ hướng dẫn. Họ quyết định xem xét các báo cáo tai nạn (được chọn ngẫu nhiên và thay thế vào chồng báo cáo sau khi đọc) **cho đến khi** họ tìm thấy một báo cáo cho thấy tai nạn do nhân viên không tuân thủ hướng dẫn. Trung bình, kỹ sư an toàn sẽ **kỳ vọng** phải xem bao nhiêu báo cáo cho đến khi họ tìm thấy một báo cáo cho thấy tai nạn do nhân viên không tuân thủ hướng dẫn? Xác suất để kỹ sư an toàn phải kiểm tra ít nhất ba báo cáo cho đến khi họ tìm thấy một báo cáo cho thấy tai nạn do nhân viên không tuân thủ hướng dẫn là bao nhiêu?

Let *X* = the number of accidents the safety engineer must examine **until** they find a report showing an accident caused by employee failure to follow instructions. *X* takes on the values 1, 2, 3, .... The first question asks you to find the **expected value** or the mean. The second question asks you to find *P*(*x* ≥ 3). ("At least" translates to a "greater than or equal to" symbol).

Gọi *X* = số lượng tai nạn mà kỹ sư an toàn phải kiểm tra **cho đến khi** họ tìm thấy một báo cáo cho thấy tai nạn do nhân viên không tuân thủ hướng dẫn. *X* nhận các giá trị 1, 2, 3, .... Câu hỏi đầu tiên yêu cầu bạn tìm **giá trị kỳ vọng** hoặc số trung bình. Câu hỏi thứ hai yêu cầu bạn tìm *P*(*x* ≥ 3). ("Ít nhất" được dịch thành ký hiệu "lớn hơn hoặc bằng").

An instructor feels that 15% of students get below a C on their final exam. They decide to look at final exams (selected randomly and replaced in the pile after reading) until they find one that shows a grade below a C. We want to know the probability that the instructor will have to examine at least ten exams until they find one with a grade below a C. What is the probability question stated mathematically?

Một giảng viên cho rằng 15% sinh viên đạt điểm dưới C trong kỳ thi cuối kỳ. Họ quyết định xem xét các bài thi cuối kỳ (được chọn ngẫu nhiên và thay thế vào chồng bài thi sau khi đọc) cho đến khi họ tìm thấy một bài thi có điểm dưới C. Chúng ta muốn biết xác suất để giảng viên phải kiểm tra ít nhất mười bài thi cho đến khi tìm thấy một bài có điểm dưới C. Câu hỏi xác suất được phát biểu dưới dạng toán học là gì?

Suppose that you are looking for a student at your college who lives within five miles of you. You know that 55% of the 25,000 students do live within five miles of you. You randomly contact students from the college **until** one says they live within five miles of you. What is the probability that you need to contact four people?

Giả sử bạn đang tìm một sinh viên tại trường đại học của mình sống trong phạm vi năm dặm quanh bạn. Bạn biết rằng 55% trong số 25.000 sinh viên sống trong phạm vi năm dặm quanh bạn. Bạn liên hệ ngẫu nhiên với các sinh viên từ trường đại học **cho đến khi** một người nói rằng họ sống trong phạm vi năm dặm quanh bạn. Xác suất để bạn cần liên hệ với bốn người là bao nhiêu?

This is a geometric problem because you may have a number of failures before you have the one success you desire. Also, the probability of a success stays the same each time you ask a student if they live within five miles of you. There is no definite number of trials (number of times you ask a student).

Đây là một bài toán hình học vì bạn có thể có một số lần thất bại trước khi đạt được thành công mà bạn mong muốn. Ngoài ra, xác suất thành công vẫn giữ nguyên mỗi khi bạn hỏi một sinh viên xem họ có sống trong phạm vi năm dặm quanh bạn hay không. Không có số lần thử nghiệm xác định (số lần bạn hỏi một sinh viên).

#### Problem

#### Bài tập

a. Let *X* = the number of ____________ you must ask ____________ one says yes.

a. Gọi *X* = số lượng ____________ bạn phải hỏi ____________ một người nói có.

b. What values does *X* take on?

b. *X* nhận những giá trị nào?

c. What are *p* and *q*?

c. *p* và *q* là gì?

d. The probability question is *P*(_______).

d. Câu hỏi xác suất là *P*(_______).

You need to find a store that carries a special printer ink. You know that of the stores that carry printer ink, 10% of them carry the special ink. You randomly call each store until one has the ink you need. What are *p* and *q*?

Bạn cần tìm một cửa hàng có bán loại mực in đặc biệt. Bạn biết rằng trong số các cửa hàng có bán mực in, 10% trong số đó có bán loại mực đặc biệt này. Bạn gọi điện ngẫu nhiên cho từng cửa hàng cho đến khi tìm được cửa hàng có loại mực bạn cần. *p* và *q* là gì?

### Notation for the Geometric: G = Geometric Probability Distribution Function

### Ký hiệu cho phân phối hình học: G = Hàm phân phối xác suất hình học

*X* ~ *G*(*p*)

*X**G**p*

Read this as "*X* is a random variable with a geometric distribution." The parameter is *p*; *p* = the probability of a success for each trial.

Đọc là "*X* là một biến ngẫu nhiên có Phân phối hình học." Tham số là *p*; *p* = xác suất thành công cho mỗi phép thử.

CASE I: Random Variable X Is Event of First Success

TRƯỜNG HỢP I: Biến ngẫu nhiên X là biến cố của lần thành công đầu tiên

In this case we ask, “What is the probability that we will have some number x of events of interest to us of failures before a success?”

Trong trường hợp này, chúng ta đặt câu hỏi: “Xác suất để chúng ta có một số x các biến cố mà chúng ta quan tâm là các thất bại trước khi có một thành công là bao nhiêu?”

The geometric pdf tells us the probability that the first occurrence of success requires x number of failure independent trials, each with probability (1 −𝑝)(1-p)(1-p). If the probability of success on each trial is *p*, then the probability that the *x*th trial (out of x trials) is the first success is:

Hàm phân phối xác suất (pdf) hình học cho chúng ta biết xác suất để lần thành công đầu tiên đòi hỏi x số lần thử thất bại độc lập, mỗi lần có xác suất (1 −𝑝)(1-p)(1-p). Nếu xác suất thành công trong mỗi phép thử là *p*, thì xác suất để phép thử thứ *x* (trong số x phép thử) là lần thành công đầu tiên là:

𝑃⁡(𝑋=𝑥) =(1−𝑝)𝑥−1⁢𝑝P⁡(X=x)=(1-p)x-1⁢pPX=x=(1-p)x-1p

𝑃⁡(𝑋=𝑥) =(1−𝑝)𝑥−1⁢𝑝P⁡(X=x)=(1-p)x-1⁢pPX=x=(1-p)x-1p

for 𝑥 =1, 2, 3, ....x=1, 2, 3, ....x=1, 2, 3, ....

đối với 𝑥 =1, 2, 3, ....x=1, 2, 3, ....x=1, 2, 3, ....

Like the binomial distribution, the geometric distribution has the parameters of the mean and standard deviation. The expected value of X, the mean for Case I, is 𝜇 =1𝑝.μ=1p.μ=1p. This tells us how many failed trials to expect until we get the first success. This count includes in the count of trials the trial that results in success. The above form of the geometric distribution is used for modeling the number of trials until the first success. The number of trials includes the one that is a success: x = all trials including the one that is a success. This can be seen in the form of the formula. If X = number of trials including the success, then we must multiply the probability of failure, (1 −𝑝)(1-p)(1-p), times the number of failures, that is 𝑥 −1x-1x-1. The standard deviation of Case I of the geometric distribution is:

Giống như phân phối nhị thức, phân phối hình học có các tham số là số trung bình và độ lệch chuẩn. Giá trị kỳ vọng của X, số trung bình cho Trường hợp I, là 𝜇 =1𝑝.μ=1p.μ=1p. Điều này cho chúng ta biết cần bao nhiêu phép thử thất bại trước khi đạt được thành công đầu tiên. Số đếm này bao gồm cả phép thử dẫn đến thành công trong tổng số các phép thử. Dạng trên của phân phối hình học được sử dụng để mô hình hóa số lượng phép thử cho đến khi có thành công đầu tiên. Số lượng phép thử bao gồm cả phép thử thành công: x = tất cả các phép thử bao gồm cả phép thử thành công. Điều này có thể thấy được trong dạng của công thức. Nếu X = số lượng phép thử bao gồm cả thành công, thì chúng ta phải nhân xác suất thất bại, (1 −𝑝)(1-p)(1-p), với số lần thất bại, đó là 𝑥 −1x-1x-1. Độ lệch chuẩn của Trường hợp I trong phân phối hình học là:

CASE II: Random Variable X Is Number of Failures BEFORE a Success

TRƯỜNG HỢP II: Biến ngẫu nhiên X là số lần thất bại TRƯỚC MỘT thành công

By contrast to Case I, the following form of the geometric distribution used for modeling number of failures until the first success is:

Ngược lại với Trường hợp I, dạng sau đây của phân phối hình học được sử dụng để mô hình hóa số lần thất bại cho đến khi có thành công đầu tiên là:

𝑃⁡(𝑋=𝑥) =(1−𝑝)𝑥⁢𝑝P⁡(X=x)=(1-p)x⁢pPX=x=(1-p)xp

𝑃⁡(𝑋=𝑥) =(1−𝑝)𝑥⁢𝑝P⁡(X=x)=(1-p)x⁢pPX=x=(1-p)xp

for 𝑥 =0, 1, 2, 3, ....x=0, 1, 2, 3, ....x=0, 1, 2, 3, ....

for 𝑥 =0, 1, 2, 3, ....x=0, 1, 2, 3, ....x=0, 1, 2, 3, ....

In this case the trial that is the success is not counted as a trial in the formula: x = number of failures. The expected value, the mean, of this distribution is 𝜇 =1−𝑝𝑝μ=1-ppμ=1-pp. This tells us how many failures to expect before we have a success. In either case, the sequence of probabilities is a geometric sequence. In Case II, the standard deviation parameter is: 𝜎 =√(1−𝑝𝑝).σ=(1-pp).σ=1-pp.

Trong trường hợp này, phép thử thành công không được tính là một phép thử trong công thức: x = số lần thất bại. Giá trị kỳ vọng, số trung bình, của phân phối này là 𝜇 =1−𝑝𝑝μ=1-ppμ=1-pp. Điều này cho chúng ta biết cần bao nhiêu lần thất bại trước khi có một thành công. Trong cả hai trường hợp, chuỗi xác suất là một cấp số nhân. Trong Trường hợp II, tham số độ lệch chuẩn là: 𝜎 =√(1−𝑝𝑝).σ=(1-pp).σ=1-pp.

*Figure 
4.4*

*Hình 
4.4*

The y-axis in [Figure 4.4](4-4-geometric-distribution#fig-00001) contains the probability of *x*, and the *x*-axis is the random number components tested. For example, at 𝑥 =1x=1x=1 the probability it will be found to be defective is 0.0196. With two components tested, the probability the second component is defective is graphed at a probability of 0.0196 at 𝑥 =2x=2x=2 on the x axis. For the probability that the third component is defective we find 𝑃⁡(𝑋=3) =0.019208.P⁡(X=3)=0.019208.PX=3=0.019208. (The first two are the same because of rounding in the computations.)

Trục y trong [Hình 4.4](4-4-geometric-distribution#fig-00001) chứa xác suất của *x*, và trục *x* là các thành phần số ngẫu nhiên được kiểm tra. Ví dụ, tại 𝑥 =1x=1x=1 xác suất nó được tìm thấy là bị lỗi là 0,0196. Với hai thành phần được kiểm tra, xác suất thành phần thứ hai bị lỗi được biểu diễn ở xác suất 0,0196 tại 𝑥 =2x=2x=2 trên trục x. Đối với xác suất thành phần thứ ba bị lỗi, chúng ta tìm thấy 𝑃⁡(𝑋=3) =0.019208.P⁡(X=3)=0.019208.PX=3=0.019208. (Hai giá trị đầu tiên giống nhau do làm tròn trong các phép tính.)

Notice on [Figure 4.4](4-4-geometric-distribution#fig-00001) that the probabilities decline by the same step down with each change in the value of x. This increment is called the common ratio. This exists for the geometric probability distribution uniquely. The common ratio, called r, can be calculated by dividing any value by the previous value, e.g., 𝑃⁡(𝑥=5)𝑃⁡(𝑥=4) =0.0184470.018823 =0.98.P⁡(x=5)P⁡(x=4)=0.0184470.018823=0.98.P(x=5)P(x=4)=0.0184470.018823=0.98.

Lưu ý trên [Hình 4.4](4-4-geometric-distribution#fig-00001) rằng các xác suất giảm theo cùng một bước với mỗi thay đổi trong giá trị của x. Mức tăng này được gọi là công bội. Điều này tồn tại duy nhất đối với phân phối xác suất hình học. Công bội, được gọi là r, có thể được tính bằng cách chia bất kỳ giá trị nào cho giá trị trước đó, ví dụ: 𝑃⁡(𝑥=5)𝑃⁡(𝑥=4) =0.0184470.018823 =0.98.P⁡(x=5)P⁡(x=4)=0.0184470.018823=0.98.P(x=5)P(x=4)=0.0184470.018823=0.98.

For this set of data, therefore, the common ratio is 0.98. The common ratio then multiplied by any other probability value will provide the next probability value in the sequence. For example, the probability that the sixth component tested is a failure is 0.018078. Check this using the formula from Case I. Now we have the 𝑃⁡(𝑥=6)P⁡(x=6)Px=6. Knowing this and the common ratio we can calculate the 𝑃⁡(𝑥=7)P⁡(x=7)Px=7 by simple multiplication: 𝑃⁡(𝑥=7) =(0.018078)⁢  * ⁢0.98 =0.017716,P⁡(x=7)=(0.018078)⁢ * ⁢0.98=0.017716,Px=7=0.018078 * 0.98=0.017716,, the same value we found earlier by using the geometric probability distribution. This common ratio increment is the same ratio between every number and is called a geometric progression and thus the name for this probability density function. Once the common ratio is calculated, any 𝑃⁡(𝑥=𝑥𝑎)P⁡(x=xa)Px=xa one desires to know can be easily found.

Do đó, đối với tập dữ liệu này, công bội là 0,98. Sau đó, công bội nhân với bất kỳ giá trị xác suất nào khác sẽ cung cấp giá trị xác suất tiếp theo trong chuỗi. Ví dụ, xác suất thành phần thứ sáu được kiểm tra là bị lỗi là 0,018078. Kiểm tra điều này bằng cách sử dụng công thức từ Trường hợp I. Bây giờ chúng ta có 𝑃⁡(𝑥=6)P⁡(x=6)Px=6. Biết được điều này và công bội, chúng ta có thể tính 𝑃⁡(𝑥=7)P⁡(x=7)Px=7 bằng phép nhân đơn giản: 𝑃⁡(𝑥=7) =(0.018078)⁢  * ⁢0.98 =0.017716,P⁡(x=7)=(0.018078)⁢ * ⁢0.98=0.017716,Px=7=0.018078 * 0.98=0.017716,, cùng một giá trị mà chúng ta đã tìm thấy trước đó bằng cách sử dụng phân phối xác suất hình học. Mức tăng công bội này là cùng một tỷ lệ giữa mọi số và được gọi là cấp số nhân, do đó có tên gọi cho hàm mật độ xác suất này. Khi công bội đã được tính, bất kỳ 𝑃⁡(𝑥=𝑥𝑎)P⁡(x=xa)Px=xa nào mà bạn muốn biết đều có thể dễ dàng tìm thấy.

The number of components that you would expect to test until you find the first defective component is the mean, 𝜇 =50μ=50μ=50 for this case of defective components. The formula for the mean of the geometric distribution for the random variable defined as number of failures before first success is 𝜇 =1𝑝 =10.02 =50μ=1p=10.02=50μ=1p=10.02=50

Số lượng thành phần mà bạn dự kiến sẽ kiểm tra cho đến khi tìm thấy thành phần bị lỗi đầu tiên là số trung bình, 𝜇 =50μ=50μ=50 cho trường hợp các thành phần bị lỗi này. Công thức tính số trung bình của phân phối hình học cho biến ngẫu nhiên được định nghĩa là số lần thất bại trước thành công đầu tiên là 𝜇 =1𝑝 =10.02 =50μ=1p=10.02=50μ=1p=10.02=50

See [Example 4.20](4-4-geometric-distribution#element-340) for an example where the geometric random variable is defined as number of trials until first success. The expected value of this formula for the geometric distribution will be different from this version of the distribution. Case II also has a variance, but this is changed from the Case I formula. This formula for the variance is:

Xem [Ví dụ 4.20](4-4-geometric-distribution#element-340) để biết ví dụ trong đó biến ngẫu nhiên hình học được định nghĩa là số lần thử cho đến khi có thành công đầu tiên. Giá trị kỳ vọng của công thức này cho phân phối hình học sẽ khác với phiên bản phân phối này. Trường hợp II cũng có phương sai, nhưng điều này đã thay đổi so với công thức Trường hợp I. Công thức tính phương sai này là:

𝑃⁡(𝑋=𝑥) =(1−𝑝)𝑥−1⁢𝑝P⁡(X=x)=(1-p)x-1⁢pPX=x=(1-p)x-1p

𝑃⁡(𝑋=𝑥) =(1−𝑝)𝑥−1⁢𝑝P⁡(X=x)=(1-p)x-1⁢pPX=x=(1-p)x-1p

for 𝑥⁢  = ⁢1, 2, 3, ....x⁢ = ⁢1, 2, 3, ....x = 1, 2, 3, ....

for 𝑥⁢  = ⁢1, 2, 3, ....x⁢ = ⁢1, 2, 3, ....x = 1, 2, 3, ....

Assume that the probability of a defective computer component is 0.02. Components are randomly selected. Find the probability that the first defect is caused by the seventh component tested. How many components do you expect to test until one is found to be defective?

Giả sử xác suất một linh kiện máy tính bị lỗi là 0,02. Các linh kiện được chọn ngẫu nhiên. Tìm xác suất lỗi đầu tiên được gây ra bởi linh kiện thứ bảy được kiểm tra. Bạn dự kiến sẽ kiểm tra bao nhiêu linh kiện cho đến khi tìm thấy một linh kiện bị lỗi?

Let *X* = the number of computer components tested until the first defect is found.

Gọi *X* = số linh kiện máy tính được kiểm tra cho đến khi tìm thấy lỗi đầu tiên.

*X* takes on the values 1, 2, 3, ... where *p* = 0.02.

*X* nhận các giá trị 1, 2, 3, ... trong đó *p* = 0,02.

Find *P*(*x* = 7). *P*(*x* = 7) = 0.0177.

Tìm *P*(*x* = 7). *P*(*x* = 7) = 0,0177.

To find the probability that *x* = 7,

Để tìm xác suất sao cho *x* = 7,

- Enter `2^nd, DISTR`
- Nhập `2^nd, DISTR`
- Scroll down and select `geometpdf`(
- Cuộn xuống và chọn `geometpdf`(
- Press `ENTER`
- Nhấn `ENTER`
- Enter 0.02, 7); press `ENTER` to see the result: *P*(*x* = 7) = 0.0177
- Nhập 0,02, 7); nhấn `ENTER` để xem kết quả: *P*(*x* = 7) = 0,0177
To find the probability that *x* ≤ 7, follow the same instructions EXCEPT select E:geometcdf(as the distribution function.

Để tìm xác suất sao cho *x* ≤ 7, hãy làm theo các hướng dẫn tương tự NGOẠI TRỪ việc chọn E:geometcdf( làm hàm phân phối.

The probability that the seventh component is the first defect is 0.0177.

Xác suất để linh kiện thứ bảy là linh kiện bị lỗi đầu tiên là 0,0177.

The formula for the variance is *σ*^2 = (1𝑝)⁢(1𝑝−1)(1p)⁢(1p−1)(1p)(1p−1) = (10.02)⁢(10.02−1)(10.02)⁢(10.02−1)(10.02)(10.02−1) = 2,450

Công thức tính phương sai là *σ*^2 = (1𝑝)⁢(1𝑝−1)(1p)⁢(1p−1)(1p)(1p−1) = (10.02)⁢(10.02−1)(10.02)⁢(10.02−1)(10.02)(10.02−1) = 2,450

The standard deviation is *σ* = √(1𝑝)⁢(1𝑝−1)(1p)⁢(1p−1)(1p)(1p−1) = √(10.⁢02)⁢(10.⁢02−1)(10.⁢02)⁢(10.⁢02−1)(10.02)(10.02−1) = 49.5

Độ lệch chuẩn là *σ* = √(1𝑝)⁢(1𝑝−1)(1p)⁢(1p−1)(1p)(1p−1) = √(10.⁢02)⁢(10.⁢02−1)(10.⁢02)⁢(10.⁢02−1)(10.02)(10.02−1) = 49,5

The probability of a defective steel rod is 0.01. Steel rods are selected at random. Find the probability that the first defect occurs on the ninth steel rod. Use the TI-83+ or TI-84 calculator to find the answer.

Xác suất một thanh thép bị lỗi là 0,01. Các thanh thép được chọn ngẫu nhiên. Tìm xác suất để lỗi đầu tiên xuất hiện ở thanh thép thứ chín. Sử dụng máy tính TI-83+ hoặc TI-84 để tìm câu trả lời.

#### Problem

#### Bài tập

The lifetime risk of developing cancer is about one in 67 (1.5%). Let *X* = the number of people you ask until one says they have cancer. Then *X* is a discrete random variable with a geometric distribution: 𝑋~𝐺⁡(167)X~G⁡(167)X~G167 or 𝑋~𝐺⁡(0.015)X~G⁡(0.015)X~G(0.015)

Nguy cơ mắc ung thư trong đời là khoảng một trên 67 (1,5%). Gọi *X* = số người bạn hỏi cho đến khi một người nói rằng họ bị ung thư. Khi đó *X* là một biến ngẫu nhiên rời rạc với phân phối hình học: 𝑋~𝐺⁡(167)X~G⁡(167)X~G167 hoặc 𝑋~𝐺⁡(0.015)X~G⁡(0.015)X~G(0.015)

1. What is the probability of that you ask ten people before one says they have cancer?
1. Xác suất để bạn hỏi mười người trước khi một người nói rằng họ bị ung thư là bao nhiêu?
1. What is the probability that you must ask 20 people?
1. Xác suất để bạn phải hỏi 20 người là bao nhiêu?
1. Find the (i) mean and (ii) standard deviation of *X*.
1. Tìm (i) số trung bình và (ii) độ lệch chuẩn của *X*.
The literacy rate for a nation measures the proportion of people age 15 and over who can read and write. The literacy rate for women in Afghanistan is 12%. Let *X* = the number of Afghani women you ask until one says that she is literate.

Tỷ lệ biết chữ của một quốc gia đo lường tỷ lệ những người từ 15 tuổi trở lên có thể đọc và viết. Tỷ lệ biết chữ của phụ nữ ở Afghanistan là 12%. Gọi *X* = số phụ nữ Afghanistan bạn hỏi cho đến khi một người nói rằng cô ấy biết chữ.

1. What is the probability distribution of *X*?
1. Phân phối xác suất của *X* là gì?
1. What is the probability that you ask five women before one says she is literate?
1. Xác suất để bạn hỏi năm người phụ nữ trước khi có một người nói rằng cô ấy biết chữ là bao nhiêu?
1. What is the probability that you must ask ten women?
1. Xác suất để bạn phải hỏi mười người phụ nữ là bao nhiêu?
1. Find the (i) mean and (ii) standard deviation of *X*.
1. Tìm (i) số trung bình và (ii) độ lệch chuẩn của *X*.
