## 5.3
 
The Exponential Distribution

## 5.3
 
Phân phối mũ

The exponential distribution is often concerned with the amount of time until some specific event occurs. For example, the amount of time (beginning now) until an earthquake occurs has an exponential distribution. Other examples include the length, in minutes, of long distance business telephone calls, and the amount of time, in months, a car battery lasts. It can be shown, too, that the value of the change that you have in your pocket or purse approximately follows an exponential distribution.

Phân phối mũ thường liên quan đến khoảng thời gian cho đến khi một biến cố cụ thể xảy ra. Ví dụ, khoảng thời gian (bắt đầu từ bây giờ) cho đến khi một trận động đất xảy ra tuân theo phân phối mũ. Các ví dụ khác bao gồm độ dài, tính bằng phút, của các cuộc gọi điện thoại đường dài trong kinh doanh, và khoảng thời gian, tính bằng tháng, mà một bình ắc quy ô tô có thể sử dụng được. Người ta cũng có thể chứng minh rằng giá trị tiền lẻ mà bạn có trong túi quần hoặc ví của mình xấp xỉ tuân theo phân phối mũ.

Values for an exponential random variable occur in the following way. There are fewer large values and more small values. For example, the amount of money customers spend in one trip to the supermarket follows an exponential distribution. There are more people who spend small amounts of money and fewer people who spend large amounts of money.

Các giá trị của một biến ngẫu nhiên theo phân phối mũ xuất hiện theo cách sau. Có ít giá trị lớn hơn và nhiều giá trị nhỏ hơn. Ví dụ, số tiền khách hàng chi tiêu trong một lần đi siêu thị tuân theo một phân phối mũ. Có nhiều người chi tiêu số tiền nhỏ và ít người chi tiêu số tiền lớn hơn.

Exponential distributions are commonly used in calculations of product reliability, or the length of time a product lasts.

Các phân phối mũ thường được sử dụng trong các tính toán về độ tin cậy của sản phẩm, hoặc khoảng thời gian một sản phẩm tồn tại.

Let *X* = amount of time (in minutes) a postal clerk spends with their customer. The time is known to have an exponential distribution with the average amount of time equal to four minutes.

Cho *X* = khoảng thời gian (tính bằng phút) mà một nhân viên bưu điện dành cho khách hàng của họ. Thời gian này được biết là có phân phối mũ với giá trị trung bình bằng bốn phút.

*X* is a continuous random variable since time is measured. It is given that *μ* = 4 minutes. To do any calculations, you must know *m*, the decay parameter.

*X* là một Biến ngẫu nhiên liên tục vì thời gian được đo lường. Cho biết *μ* = 4 phút. Để thực hiện bất kỳ tính toán nào, bạn phải biết *m*, tham số phân rã.

𝑚=1𝜇m=1μm=1μ. Therefore, 𝑚=14=0.25.m=14=0.25.m=14=0.25.

𝑚=1𝜇m=1μm=1μ. Do đó, 𝑚=14=0.25.m=14=0.25.m=14=0.25.

The standard deviation, *σ*, is the same as the mean. *μ* = *σ*

Độ lệch chuẩn, *σ*, giống như số trung bình. *μ* = *σ*

The distribution notation is *X* ~ *Exp*(*m*). Therefore, *X* ~ *Exp*(0.25).

Ký hiệu phân phối là *X* ~ *Exp*(*m*). Do đó, *X* ~ *Exp*(0.25).

The probability density function is *f*(*x*) = *me*^-*mx*. The number *e* = 2.71828182846... It is a number that is used often in mathematics. Scientific calculators have the key "*e^x*." If you enter one for *x*, the calculator will display the value *e*.

Hàm mật độ xác suất là *f*(*x*) = *me*^-*mx*. Số *e* = 2,71828182846... Đây là một con số thường được sử dụng trong toán học. Các máy tính khoa học có phím "*e^x*." Nếu bạn nhập một cho *x*, máy tính sẽ hiển thị giá trị *e*.

The curve is:

Đường cong là:

*f*(*x*) = 0.25*e*^–0.25*x* where *x* is at least zero and *m* = 0.25.

*f*(*x*) = 0,25*e*^–0,25*x* trong đó *x* ít nhất bằng không và *m* = 0,25.

For example, *f*(5) = 0.25*e*^(-0.25)(5) = 0.072. The value 0.072 is the height of the curve when *x* = 5. In [Example 5.8](5-3-the-exponential-distribution#fs-idm47363760) below, you will learn how to find probabilities using the decay parameter.

Ví dụ, *f*(5) = 0,25*e*^(-0,25)(5) = 0,072. Giá trị 0,072 là chiều cao của đường cong khi *x* = 5. Trong [Ví dụ 5.8](5-3-the-exponential-distribution#fs-idm47363760) dưới đây, bạn sẽ học cách tìm xác suất bằng cách sử dụng tham số phân rã.

The graph is as follows:

Đồ thị như sau:

*Figure 
5.22*

*Hình 
5.22*

Notice the graph is a declining curve. When *x* = 0,

Lưu ý đồ thị là một đường cong đi xuống. Khi *x* = 0,

*f*(*x*) = 0.25*e*^(−0.25)(0) = (0.25)(1) = 0.25 = *m*. The maximum value on the *y*-axis is *m*.

*f*(*x*) = 0,25*e*^(−0,25)(0) = (0,25)(1) = 0,25 = *m*. Giá trị cực đại trên trục *y* là *m*.

The amount of time spouses shop for anniversary cards can be modeled by an exponential distribution with the average amount of time equal to eight minutes. Write the distribution, state the probability density function, and graph the distribution.

Khoảng thời gian vợ chồng mua thiệp kỷ niệm có thể được mô hình hóa bằng phân phối mũ với số trung bình thời gian bằng tám phút. Hãy viết phân phối, nêu hàm mật độ xác suất và vẽ đồ thị phân phối.

#### Problem

#### Bài toán

a. Using the information in [Example 5.7](5-3-the-exponential-distribution#fs-idp58220144), find the probability that a clerk spends four to five minutes with a randomly selected customer.

a. Sử dụng thông tin trong [Ví dụ 5.7](5-3-the-exponential-distribution#fs-idp58220144), hãy tìm xác suất để một nhân viên dành bốn đến năm phút với một khách hàng được chọn ngẫu nhiên.

#### Problem

#### Bài toán

b. Half of all customers are finished within how long? (Find the 50^th percentile)

b. Một nửa số khách hàng được phục vụ xong trong vòng bao lâu? (Tìm bách phân vị thứ 50)

#### Problem

#### Bài toán

c. Which is larger, the mean or the median?

c. Giá trị nào lớn hơn, số trung bình hay trung vị?

The number of days ahead travelers purchase their airline tickets can be modeled by an exponential distribution with the average amount of time equal to 15 days. Find the probability that a traveler will purchase a ticket fewer than ten days in advance. How many days do half of all travelers wait?

Số ngày trước khi khách du lịch mua vé máy bay có thể được mô hình hóa bằng phân phối mũ với thời gian trung bình bằng 15 ngày. Tìm xác suất để một khách du lịch sẽ mua vé trước ít hơn mười ngày. Một nửa số khách du lịch đợi bao nhiêu ngày?

Have each class member count the change they have in their pocket or purse. Your instructor will record the amounts in dollars and cents. Construct a histogram of the data taken by the class. Use five intervals. Draw a smooth curve through the bars. The graph should look approximately exponential. Then calculate the mean.

Yêu cầu mỗi thành viên trong lớp đếm số tiền lẻ họ có trong túi hoặc ví. Giảng viên của bạn sẽ ghi lại số tiền đó bằng đô la và xu. Vẽ biểu đồ histogram của dữ liệu thu thập được từ lớp. Sử dụng năm khoảng. Vẽ một đường cong trơn qua các cột. Đồ thị sẽ trông gần giống như phân phối mũ. Sau đó tính số trung bình.

Let *X* = the amount of money a student in your class has in their pocket or purse.

Gọi *X* = số tiền mà một sinh viên trong lớp của bạn có trong túi hoặc ví của họ.

The distribution for *X* is approximately exponential with mean, *μ* = _______ and *m*  = _______. The standard deviation, *σ* = ________.

Phân phối của *X* xấp xỉ phân phối mũ với số trung bình, *μ* = _______ và *m* = _______. Độ lệch chuẩn, *σ* = ________.

Draw the appropriate exponential graph. You should label the x– and y–axes, the decay rate, and the mean. Shade the area that represents the probability that one student has less than $.40 in their pocket or purse. (Shade *P*(*x* < 0.40)).

Vẽ biểu đồ hàm mũ thích hợp. Bạn nên dán nhãn các trục x và y, tốc độ phân rã và số trung bình. Tô bóng vùng biểu diễn xác suất một sinh viên có ít hơn 0,40 đô la trong túi hoặc ví của họ. (Tô bóng *P*(*x* < 0.40)).

On the average, a certain computer part lasts ten years. The length of time the computer part lasts is exponentially distributed.

Tính trung bình, một linh kiện máy tính nhất định có tuổi thọ mười năm. Khoảng thời gian linh kiện máy tính đó hoạt động được tuân theo phân phối mũ.

#### Problem

#### Bài toán

a. What is the probability that a computer part lasts more than 7 years?

a. Xác suất để một linh kiện máy tính hoạt động lâu hơn 7 năm là bao nhiêu?

On the home screen, enter e^(-.1*7).

Trên màn hình chính, nhập e^(-.1*7).

*Figure 
5.25*

*Hình 
5.25*

#### Problem

#### Bài toán

b. On the average, how long would five computer parts last if they are used one after another?

b. Tính trung bình, năm linh kiện máy tính sẽ hoạt động được bao lâu nếu chúng được sử dụng nối tiếp nhau?

#### Problem

#### Bài toán

c. Eighty percent of computer parts last at most how long?

c. Tám mươi phần trăm các linh kiện máy tính hoạt động được tối đa bao lâu?

On the home screen, enter ln⁡(1–0.80)–0.1ln⁡(1–0.80)–0.1ln(1–0.80)–0.1

Trên màn hình chính, nhập ln⁡(1–0.80)–0.1ln⁡(1–0.80)–0.1ln(1–0.80)–0.1

#### Problem

#### Bài toán

d. What is the probability that a computer part lasts between nine and 11 years?

d. Xác suất để một linh kiện máy tính hoạt động trong khoảng từ chín đến 11 năm là bao nhiêu?

On the home screen, enter *e*^(–0.1*9) – *e*^(–0.1*11).

Trên màn hình chính, nhập *e*^(–0.1*9) – *e*^(–0.1*11).

On average, a pair of running shoes can last 18 months if used every day. The length of time running shoes last is exponentially distributed. What is the probability that a pair of running shoes last more than 15 months? On average, how long would six pairs of running shoes last if they are used one after the other? Eighty percent of running shoes last at most how long if used every day?

Trung bình, một đôi giày chạy bộ có thể dùng được 18 tháng nếu sử dụng hàng ngày. Khoảng thời gian sử dụng của giày chạy bộ tuân theo phân phối mũ. Xác suất để một đôi giày chạy bộ dùng được hơn 15 tháng là bao nhiêu? Trung bình, sáu đôi giày chạy bộ sẽ dùng được trong bao lâu nếu chúng được sử dụng lần lượt từng đôi một? Tám mươi phần trăm số giày chạy bộ dùng được tối đa trong bao lâu nếu sử dụng hàng ngày?

Suppose that the length of a phone call, in minutes, is an exponential random variable with decay parameter 112112112. If another person arrives at a public telephone just before you, find the probability that you will have to wait more than five minutes. Let *X*  = the length of a phone call, in minutes.

Giả sử rằng độ dài của một cuộc gọi điện thoại, tính bằng phút, là một biến ngẫu nhiên liên tục tuân theo phân phối mũ với tham số suy giảm 112112112. Nếu một người khác đến bốt điện thoại công cộng ngay trước bạn, hãy tìm xác suất để bạn phải đợi hơn năm phút. Gọi *X* = độ dài của một cuộc gọi điện thoại, tính bằng phút.

#### Problem

#### Bài tập

What is *m*, *μ*, and *σ*? The probability that you must wait more than five minutes is _______ .

*m*, *μ*, và *σ* là gì? Xác suất để bạn phải đợi hơn năm phút là _______ .

Suppose that the distance, in miles, that people are willing to commute to work is an exponential random variable with a decay parameter 120120120. Let *X* = the distance people are willing to commute in miles. What is *m*, *μ*, and *σ*? What is the probability that a person is willing to commute more than 25 miles?

Giả sử rằng khoảng cách, tính bằng dặm, mà mọi người sẵn sàng đi làm là một biến ngẫu nhiên liên tục tuân theo phân phối mũ với tham số suy giảm 120120120. Gọi *X* = khoảng cách mọi người sẵn sàng đi làm tính bằng dặm. *m*, *μ*, và *σ* là gì? Xác suất để một người sẵn sàng đi làm hơn 25 dặm là bao nhiêu?

The time spent waiting between events is often modeled using the exponential distribution. For example, suppose that an average of 30 customers per hour arrive at a store and the time between arrivals is exponentially distributed.

Thời gian chờ đợi giữa các biến cố thường được mô hình hóa bằng cách sử dụng phân phối mũ. Ví dụ, giả sử trung bình có 30 khách hàng mỗi giờ đến một cửa hàng và thời gian giữa các lần khách đến tuân theo phân phối mũ.

#### Problem

#### Bài tập

1. On average, how many minutes elapse between two successive arrivals?
1. Trung bình, bao nhiêu phút trôi qua giữa hai lần đến liên tiếp?
1. When the store first opens, how long on average does it take for three customers to arrive?
1. Khi cửa hàng mới mở, trung bình mất bao lâu để ba khách hàng đến nơi?
1. After a customer arrives, find the probability that it takes less than one minute for the next customer to arrive.
1. Sau khi một khách hàng đến, hãy tìm xác suất để khách hàng tiếp theo đến trong vòng chưa đầy một phút.
1. After a customer arrives, find the probability that it takes more than five minutes for the next customer to arrive.
1. Sau khi một khách hàng đến, hãy tìm xác suất để khách hàng tiếp theo đến sau hơn năm phút.
1. Seventy percent of the customers arrive within how many minutes of the previous customer?
1. Bảy mươi phần trăm khách hàng đến trong vòng bao nhiêu phút kể từ khách hàng trước đó?
1. Is an exponential distribution reasonable for this situation?
1. Phân phối mũ có hợp lý cho tình huống này không?
Suppose that on a certain stretch of highway, cars pass at an average rate of five cars per minute. Assume that the duration of time between successive cars follows the exponential distribution.

Giả sử rằng trên một đoạn đường cao tốc nhất định, ô tô đi qua với tốc độ trung bình là năm chiếc mỗi phút. Giả sử rằng khoảng thời gian giữa các xe liên tiếp tuân theo phân phối mũ.

1. On average, how many seconds elapse between two successive cars?
1. Trung bình, bao nhiêu giây trôi qua giữa hai chiếc xe liên tiếp?
1. After a car passes by, how long on average will it take for another seven cars to pass by?
1. Sau khi một chiếc xe đi qua, trung bình sẽ mất bao lâu để có thêm bảy chiếc xe nữa đi qua?
1. Find the probability that after a car passes by, the next car will pass within the next 20 seconds.
1. Tìm xác suất để sau khi một chiếc xe đi qua, chiếc xe tiếp theo sẽ đi qua trong vòng 20 giây tới.
1. Find the probability that after a car passes by, the next car will not pass for at least another 15 seconds.
1. Tìm xác suất để sau khi một chiếc xe đi qua, chiếc xe tiếp theo sẽ không đi qua trong ít nhất 15 giây nữa.
### Memorylessness of the Exponential Distribution

### Tính không nhớ của phân phối mũ

In [Example 5.7](5-3-the-exponential-distribution#fs-idp58220144) recall that the amount of time between customers is exponentially distributed with a mean of two minutes (*X* ~ *Exp* (0.5)). Suppose that five minutes have elapsed since the last customer arrived. Since an unusually long amount of time has now elapsed, it would seem to be more likely for a customer to arrive within the next minute. With the exponential distribution, this is not the case–the additional time spent waiting for the next customer does not depend on how much time has already elapsed since the last customer. This is referred to as the **memoryless property**. Specifically, the **memoryless property** says that

Trong [Ví dụ 5.7](5-3-the-exponential-distribution#fs-idp58220144), hãy nhớ lại rằng khoảng thời gian giữa các khách hàng tuân theo phân phối mũ với số trung bình là hai phút (*X* ~ *Exp* (0.5)). Giả sử rằng đã năm phút trôi qua kể từ khi khách hàng cuối cùng đến. Vì một khoảng thời gian dài bất thường đã trôi qua, có vẻ như khả năng một khách hàng đến trong phút tiếp theo sẽ cao hơn. Với phân phối mũ, điều này không xảy ra – thời gian chờ đợi thêm cho khách hàng tiếp theo không phụ thuộc vào việc đã bao nhiêu thời gian trôi qua kể từ khi khách hàng trước đó đến. Điều này được gọi là **tính chất không nhớ**. Cụ thể, **tính chất không nhớ** nói rằng

*P* (*X* > *r* + *t* | *X* > *r*) = *P* (*X* > *t*) for all *r* ≥ 0 and *t* ≥ 0

*P* (*X* > *r* + *t* | *X* > *r*) = *P* (*X* > *t*) với mọi *r* ≥ 0 và *t* ≥ 0

For example, if five minutes have elapsed since the last customer arrived, then the probability that more than one minute will elapse before the next customer arrives is computed by using *r* = 5 and *t* = 1 in the foregoing equation.

Ví dụ, nếu năm phút đã trôi qua kể từ khi khách hàng cuối cùng đến, thì xác suất để hơn một phút nữa trôi qua trước khi khách hàng tiếp theo đến được tính bằng cách sử dụng *r* = 5 và *t* = 1 trong phương trình trên.

*P*(*X* > 5 + 1 | *X* > 5) = *P*(*X* > 1) = 𝑒(–0.5)⁢(1)e(–0.5)⁢(1)e(–0.5)(1) ≈ 0.6065.

*P**X**X**P**X*𝑒(–0.5)⁢(1)e(–0.5)⁢(1)e(–0.5)(1)

*This is the same* probability as that of waiting more than one minute for a customer to arrive after the previous arrival.

*Đây là xác suất tương tự* như xác suất phải đợi hơn một phút để một khách hàng đến sau lần khách hàng trước đó đã đến.

The exponential distribution is often used to model the longevity of an electrical or mechanical device. In [Example 5.9](5-3-the-exponential-distribution#fs-idp51839440), the lifetime of a certain computer part has the exponential distribution with a mean of ten years (*X* ~ *Exp*(0.1)). The **memoryless property** says that knowledge of what has occurred in the past has no effect on future probabilities. In this case it means that an old part is not any more likely to break down at any particular time than a brand new part. In other words, the part stays as good as new until it suddenly breaks. For example, if the part has already lasted ten years, then the probability that it lasts another seven years is *P*(*X* > 17|*X* > 10) = *P*(*X* > 7) = 0.4966.

Phân phối mũ thường được sử dụng để mô hình hóa tuổi thọ của một thiết bị điện hoặc cơ khí. Trong [Ví dụ 5.9](5-3-the-exponential-distribution#fs-idp51839440), tuổi thọ của một linh kiện máy tính nhất định có phân phối mũ với trung bình là mười năm (*X* ~ *Exp*(0.1)). **Tính chất không nhớ** cho biết rằng việc biết những gì đã xảy ra trong quá khứ không có ảnh hưởng gì đến các xác suất trong tương lai. Trong trường hợp này, điều đó có nghĩa là một linh kiện cũ không có khả năng bị hỏng tại bất kỳ thời điểm cụ thể nào cao hơn so với một linh kiện hoàn toàn mới. Nói cách khác, linh kiện vẫn tốt như mới cho đến khi nó đột ngột bị hỏng. Ví dụ, nếu linh kiện đã hoạt động được mười năm, thì xác suất để nó hoạt động thêm bảy năm nữa là *P*(*X* > 17|*X* > 10) = *P*(*X* > 7) = 0.4966.

Refer to [Example 5.7](5-3-the-exponential-distribution#fs-idp58220144) where the time a postal clerk spends with a customer has an exponential distribution with a mean of four minutes. Suppose a customer has spent four minutes with a postal clerk. What is the probability that the customer will spend at least an additional three minutes with the postal clerk?

Tham khảo [Ví dụ 5.7](5-3-the-exponential-distribution#fs-idp58220144), nơi thời gian một nhân viên bưu điện dành cho một khách hàng có phân phối mũ với trung bình là bốn phút. Giả sử một khách hàng đã dành bốn phút với nhân viên bưu điện. Xác suất để khách hàng đó dành thêm ít nhất ba phút nữa với nhân viên bưu điện là bao nhiêu?

The decay parameter of *X* is *m* = 141414
= 0.25, so *X* ∼ *Exp*(0.25).

Tham số phân rã của *X* là *m* = 141414
= 0.25, vì vậy *X* ∼ *Exp*(0.25).

The cumulative distribution function is *P*(*X* < *x*) = 1 – *e*^–0.25*x*.

Hàm phân phối tích lũy là *P*(*X* < *x*) = 1 – *e*^–0.25*x*.

We want to find *P*(*X* > 7|*X* > 4). The **memoryless property** says that *P*(*X* > 7|*X* > 4) = *P* (*X* > 3), so we just need to find the probability that a customer spends more than three minutes with a postal clerk.

Chúng ta muốn tìm *P*(*X* > 7|*X* > 4). **Tính chất không nhớ** cho biết rằng *P*(*X* > 7|*X* > 4) = *P* (*X* > 3), vì vậy chúng ta chỉ cần tìm xác suất để một khách hàng dành hơn ba phút với nhân viên bưu điện.

This is *P*(*X* > 3) = 1 – *P* (*X* < 3) = 1 – (1 – *e*^–0.25⋅3) = *e*^–0.75 ≈ 0.4724.

Đây là *P*(*X* > 3) = 1 – *P* (*X* < 3) = 1 – (1 – *e*^–0.25⋅3) = *e*^–0.75 ≈ 0.4724.

*Figure 
5.31*

*Hình 
5.31*

1–(1–e^(–0.25*3)) = e^(–0.25*3).

1–(1–e^(–0.25*3)) = e^(–0.25*3).

Suppose that the longevity of a light bulb is exponential with a mean lifetime of eight years. If a bulb has already lasted 12 years, find the probability that it will last a total of over 19 years.

Giả sử tuổi thọ của một bóng đèn tuân theo phân phối mũ với tuổi thọ trung bình là tám năm. Nếu một bóng đèn đã hoạt động được 12 năm, hãy tìm xác suất để nó hoạt động tổng cộng hơn 19 năm.

### Relationship between the Poisson and the Exponential Distribution

### Mối quan hệ giữa phân phối Poisson và phân phối mũ

There is an interesting relationship between the exponential distribution and the Poisson distribution. Suppose that the time that elapses between two successive events follows the exponential distribution with a mean of *μ* units of time. Also assume that these times are independent, meaning that the time between events is not affected by the times between previous events. If these assumptions hold, then the number of events per unit time follows a Poisson distribution with mean *λ* = 1/μ. Recall from the chapter on [Discrete Random Variables](4-introduction) that if *X* has the Poisson distribution with mean *λ*, then 𝑃⁡(𝑋=𝑘)=𝜆𝑘⁢𝑒−𝜆𝑘!P⁡(X=k)=λk⁢e−λk!P(X=k)=λke−λk!. Conversely, if the number of events per unit time follows a Poisson distribution, then the amount of time between events follows the exponential distribution. (*k*! = *k**(*k*–1*)(*k*–2)*(*k*–3)*…3*2*1)

Có một mối quan hệ thú vị giữa phân phối mũ và phân phối Poisson. Giả sử thời gian trôi qua giữa hai biến cố liên tiếp tuân theo phân phối mũ với trung bình là *μ* đơn vị thời gian. Cũng giả định rằng các khoảng thời gian này là độc lập, nghĩa là thời gian giữa các biến cố không bị ảnh hưởng bởi thời gian giữa các biến cố trước đó. Nếu các giả định này đúng, thì số lượng biến cố trên mỗi đơn vị thời gian tuân theo phân phối Poisson với trung bình *λ* = 1/μ. Nhắc lại từ chương về [Biến ngẫu nhiên rời rạc](4-introduction) rằng nếu *X* có phân phối Poisson với trung bình *λ*, thì 𝑃⁡(𝑋=𝑘)=𝜆𝑘⁢𝑒−𝜆𝑘!P⁡(X=k)=λk⁢e−λk!P(X=k)=λke−λk!. Ngược lại, nếu số lượng biến cố trên mỗi đơn vị thời gian tuân theo phân phối Poisson, thì khoảng thời gian giữa các biến cố tuân theo phân phối mũ. (*k*! = *k**(*k*–1*)(*k*–2)*(*k*–3)*…3*2*1)

Suppose *X* has the Poisson distribution with mean *λ*. Compute *P*(*X* = *k*) by entering 2^nd, `VARS(DISTR)`, `C: poissonpdf(*λ*, *k*)`. To compute *P*(*X* ≤ *k*), enter 2^nd, `VARS (DISTR)`, `D:poissoncdf(*λ*, *k*)`.

Giả sử *X* có phân phối Poisson với trung bình *λ*. Tính *P*(*X* = *k*) bằng cách nhập 2^nd, `VARS(DISTR)`, `C: poissonpdf(*λ*, *k*)`. Để tính *P*(*X* ≤ *k*), nhập 2^nd, `VARS (DISTR)`, `D:poissoncdf(*λ*, *k*)`.

At a police station in a large city, calls come in at an average rate of four calls per minute. Assume that the time that elapses from one call to the next has the exponential distribution. Take note that we are concerned only with the rate at which calls come in, and we are ignoring the time spent on the phone. We must also assume that the times spent between calls are independent. This means that a particularly long delay between two calls does not mean that there will be a shorter waiting period for the next call. We may then deduce that the total number of calls received during a time period has the Poisson distribution.

Tại một đồn cảnh sát ở một thành phố lớn, các cuộc gọi đến với tốc độ trung bình là bốn cuộc gọi mỗi phút. Giả sử thời gian trôi qua từ cuộc gọi này đến cuộc gọi tiếp theo có phân phối mũ. Lưu ý rằng chúng ta chỉ quan tâm đến tốc độ các cuộc gọi đến và chúng ta bỏ qua thời gian dành cho việc đàm thoại. Chúng ta cũng phải giả định rằng thời gian giữa các cuộc gọi là độc lập. Điều này có nghĩa là một khoảng trễ đặc biệt dài giữa hai cuộc gọi không có nghĩa là sẽ có thời gian chờ ngắn hơn cho cuộc gọi tiếp theo. Sau đó, chúng ta có thể suy ra rằng tổng số cuộc gọi nhận được trong một khoảng thời gian tuân theo phân phối Poisson.

#### Problem

#### Bài tập

1. Find the average time between two successive calls.
1. Tìm thời gian trung bình giữa hai cuộc gọi liên tiếp.
1. Find the probability that after a call is received, the next call occurs in less than ten seconds.
1. Tìm xác suất để sau khi nhận được một cuộc gọi, cuộc gọi tiếp theo xảy ra trong vòng chưa đầy mười giây.
1. Find the probability that exactly five calls occur within a minute.
1. Tìm xác suất để có đúng năm cuộc gọi xảy ra trong vòng một phút.
1. Find the probability that less than five calls occur within a minute.
1. Tìm xác suất để có ít hơn năm cuộc gọi xảy ra trong vòng một phút.
1. Find the probability that more than 40 calls occur in an eight-minute period.
1. Tìm xác suất để có hơn 40 cuộc gọi xảy ra trong khoảng thời gian tám phút.
In a small city, the number of automobile accidents occur with a Poisson distribution at an average of three per week.

Tại một thành phố nhỏ, số vụ tai nạn ô tô xảy ra theo phân phối Poisson với trung bình là ba vụ mỗi tuần.

1. Calculate the probability that there are at most 2 accidents occur in any given week.
1. Tính xác suất để có tối đa 2 vụ tai nạn xảy ra trong bất kỳ tuần nào.
1. What is the probability that there is at least two weeks between any 2 accidents?
1. Xác suất để có ít nhất hai tuần giữa bất kỳ 2 vụ tai nạn là bao nhiêu?
