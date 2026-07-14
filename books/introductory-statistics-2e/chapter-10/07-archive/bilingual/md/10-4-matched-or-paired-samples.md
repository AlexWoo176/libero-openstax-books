## 10.4
 
Matched or Paired Samples

## 10.4
 
Các mẫu ghép cặp hoặc mẫu cặp

When using a hypothesis test for matched or paired samples, the following characteristics should be present:

Khi sử dụng kiểm định giả thuyết cho các mẫu ghép cặp hoặc mẫu cặp, các đặc điểm sau đây cần phải có:

1. Simple random sampling is used.
1. Sử dụng lấy mẫu ngẫu nhiên đơn giản.
1. Sample sizes are often small.
1. Kích thước mẫu thường nhỏ.
1. Two measurements (samples) are drawn from the same pair of individuals or objects.
1. Hai phép đo (mẫu) được rút ra từ cùng một cặp cá thể hoặc đối tượng.
1. Differences are calculated from the matched or paired samples.
1. Các hiệu số được tính từ các mẫu ghép đôi hoặc mẫu cặp.
1. The differences form the sample that is used for the hypothesis test.
1. Các hiệu số tạo thành mẫu được sử dụng cho kiểm định giả thuyết.
1. Either the matched pairs have differences that come from a population that is normal or the number of differences is sufficiently large so that distribution of the sample mean of differences is approximately normal.
1. Hoặc là các cặp ghép đôi có các hiệu số đến từ một quần thể có phân phối chuẩn, hoặc số lượng hiệu số đủ lớn để phân phối của số trung bình mẫu các hiệu số xấp xỉ chuẩn.
In a hypothesis test for matched or paired samples, subjects are matched in pairs and differences are calculated. The differences are the data. The population mean for the differences, *μ_d*, is then tested using a Student's-t test for a single population mean with *n* – 1 degrees of freedom, where *n* is the number of differences.

Trong một kiểm định giả thuyết cho các mẫu ghép cặp hoặc mẫu cặp, các đối tượng được ghép thành từng cặp và các hiệu số được tính toán. Các hiệu số này chính là dữ liệu. Số trung bình quần thể của các hiệu số, *μ_d*, sau đó được kiểm định bằng cách sử dụng kiểm định t-Student cho một số trung bình quần thể với *n* – 1 bậc tự do, trong đó *n* là số lượng các hiệu số.

#### Problem

#### Bài tập

** no-selfclose ** A study was conducted to investigate the effectiveness of hypnotism in reducing pain. Results for randomly selected subjects are shown in [Table 10.14](10-4-matched-or-paired-samples#table-2345). A lower score indicates less pain. The "before" value is matched to an "after" value and the differences are calculated. The differences have a normal distribution. Are the sensory measurements, on average, lower after hypnotism? Test at a 5% significance level.

** no-selfclose ** Một nghiên cứu đã được thực hiện để điều tra hiệu quả của thuật thôi miên trong việc giảm đau. Kết quả cho các đối tượng được chọn ngẫu nhiên được hiển thị trong [Bảng 10.14](10-4-matched-or-paired-samples#table-2345). Điểm số thấp hơn cho thấy ít đau hơn. Giá trị "trước" được ghép cặp với giá trị "sau" và các hiệu số được tính toán. Các hiệu số có phân phối chuẩn. Các phép đo cảm giác, trung bình, có thấp hơn sau khi thôi miên không? Hãy kiểm định ở mức ý nghĩa 5%.

| Subject: | Đối tượng: | A | A | B | B | C | C | D | D | E | E | F | F | G | G | H | H |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Before | Trước | 6.6 | 6,6 | 6.5 | 6,5 | 9.0 | 9,0 | 10.3 | 10.3 | 11.3 | 11,3 | 8.1 | 8,1 | 6.3 | 6,3 | 11.6 | 11,6 |
| After | Sau | 6.8 | 6,8 | 2.4 | 2,4 | 7.4 | 7,4 | 8.5 | 8,5 | 8.1 | 8,1 | 6.1 | 6,1 | 3.4 | 3,4 | 2.0 | 2,0 |

For the TI-83+ and TI-84 calculators, you can either calculate the differences ahead of time (**after - before**) and put the differences into a list or you can put the **after** data into a first list and the **before** data into a second list. Then go to a third list and arrow up to the name. Enter 1^st list name - 2^nd list name. The calculator will do the subtraction, and you will have the differences in the third list.

Đối với máy tính TI-83+ và TI-84, bạn có thể tính các hiệu số trước (**sau - trước**) và đưa các hiệu số vào một danh sách hoặc bạn có thể đưa dữ liệu **sau** vào danh sách thứ nhất và dữ liệu **trước** vào danh sách thứ hai. Sau đó, chuyển đến danh sách thứ ba và di chuyển lên trên tên danh sách. Nhập tên danh sách thứ 1 - tên danh sách thứ 2. Máy tính sẽ thực hiện phép trừ và bạn sẽ có các hiệu số trong danh sách thứ ba.

Use your list of differences as the data. Press `STAT` and arrow over to `TESTS`. Press `2:T-Test`. Arrow over to `Data` and press `ENTER`. Arrow down and enter `0` for μ0μ0, the name of the list where you put the data, and `1` for Freq:. Arrow down to `μ`: and arrow over to `<` μ0μ0. Press `ENTER`. Arrow down to `Calculate` and press `ENTER`. The *p*-value is 0.0094, and the test statistic is -3.04. Do these instructions again except, arrow to `Draw` (instead of `Calculate`). Press `ENTER`.

Sử dụng danh sách các hiệu số của bạn làm dữ liệu. Nhấn `STAT` và di chuyển sang `TESTS`. Nhấn `2:T-Test`. Di chuyển sang `Data` và nhấn `ENTER`. Di chuyển xuống và nhập `0` cho μ0μ0, tên của danh sách nơi bạn đã đặt dữ liệu, và `1` cho Freq:. Di chuyển xuống `μ`: và di chuyển sang `<` μ0μ0. Nhấn `ENTER`. Di chuyển xuống `Calculate` và nhấn `ENTER`. p-giá trị *p* là 0,0094, và thống kê kiểm định là -3,04. Thực hiện lại các hướng dẫn này ngoại trừ việc di chuyển đến `Draw` (thay vì `Calculate`). Nhấn `ENTER`.

A study was conducted to investigate how effective a new diet was in lowering cholesterol. Results for the randomly selected subjects are shown in the table. The differences have a normal distribution. Are the subjects’ cholesterol levels lower on average after the diet? Test at the 5% level.

Một nghiên cứu đã được thực hiện để điều tra xem một chế độ ăn kiêng mới hiệu quả như thế nào trong việc giảm cholesterol. Kết quả cho các đối tượng được chọn ngẫu nhiên được hiển thị trong bảng. Các hiệu số có phân phối chuẩn. Mức cholesterol của các đối tượng có thấp hơn trung bình sau khi ăn kiêng không? Hãy kiểm định ở mức 5%.

| Subject | Đối tượng | A | A | B | B | C | C | D | D | E | E | F | F | G | G | H | H | I | I |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Before | Trước | 209 | 209 | 210 | 210 | 205 | 205 | 198 | 198 | 216 | 216 | 217 | 217 | 238 | 238 | 240 | 240 | 222 | 222 |
| After | Sau | 199 | 199 | 207 | 207 | 189 | 189 | 209 | 209 | 217 | 217 | 202 | 202 | 211 | 211 | 223 | 223 | 201 | 201 |

A college softball coach was interested in whether the college's strength development class increased their players' maximum lift (in pounds). Four players participated in the study. The amount of weight they could each lift was recorded before they took the strength development class. After completing the class, the amount of weight they could each lift was again measured. The data are as follows:

Một huấn luyện viên bóng mềm đại học quan tâm đến việc liệu lớp phát triển sức mạnh của trường đại học có làm tăng mức nâng tạ tối đa của các cầu thủ (tính bằng pound) hay không. Bốn cầu thủ đã tham gia nghiên cứu. Lượng tạ mà mỗi người có thể nâng được đã được ghi lại trước khi họ tham gia lớp phát triển sức mạnh. Sau khi hoàn thành lớp học, lượng tạ mà mỗi người có thể nâng được lại được đo một lần nữa. Dữ liệu như sau:

| Weight (in pounds) | Trọng lượng (tính bằng pound) | Player 1 | Cầu thủ 1 | Player 2 | Cầu thủ 2 | Player 3 | Cầu thủ 3 | Player 4 | Cầu thủ 4 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Amount of weight lifted prior to the class | Khối lượng tạ nâng được trước lớp học | 205 | 205 | 241 | 241 | 338 | 338 | 368 | 368 |
| Amount of weight lifted after the class | Khối lượng tạ nâng được sau lớp học | 295 | 295 | 252 | 252 | 330 | 330 | 360 | 360 |

**The coach wants to know if the strength development class makes the players stronger, on average.**

Record the **differences** data. Calculate the differences by subtracting the amount of weight lifted prior to the class from the weight lifted after completing the class. The data for the differences are: {90, 11, -8, -8}. Assume the differences have a normal distribution.

**Huấn luyện viên muốn biết liệu lớp phát triển sức mạnh có làm cho các cầu thủ khỏe hơn, trung bình hay không.**

Ghi lại dữ liệu **hiệu số**. Tính các hiệu số bằng cách trừ lượng tạ nâng được trước lớp học khỏi lượng tạ nâng được sau khi hoàn thành lớp học. Dữ liệu cho các hiệu số là: {90, 11, -8, -8}. Giả sử các hiệu số có phân phối chuẩn.

Using the differences data, calculate the sample mean and the sample standard deviation.

Sử dụng dữ liệu hiệu số, tính số trung bình mẫu và độ lệch chuẩn mẫu.

x¯d=21.3,sd=46.7x¯ &#175; d=21.3,sd=46.7

x¯d=21.3,sd=46.7x¯ &#175; d=21.3,sd=46.7

The data given here would indicate that the distribution is actually right-skewed. The difference 90 may be an extreme outlier? It is pulling the sample mean to be 21.3 (positive). The means of the other three data values are actually negative.

Dữ liệu được đưa ra ở đây cho thấy phân phối thực sự bị lệch phải. Hiệu số 90 có thể là một giá trị ngoại lệ cực đoan? Nó đang kéo số trung bình mẫu thành 21,3 (dương). Số trung bình của ba giá trị dữ liệu còn lại thực sự là âm.

Using the difference data, this becomes a test of a single __________ (fill in the blank).

Sử dụng dữ liệu hiệu số, đây trở thành một kiểm định cho một __________ (điền vào chỗ trống).

**Define the random variable:** 

X
¯

d

X
¯

d

 mean difference in the maximum lift per player.

**Xác định biến ngẫu nhiên:** 

X
¯

d

X
¯

d

 hiệu số trung bình trong mức nâng tạ tối đa trên mỗi cầu thủ.

The distribution for the hypothesis test is *t_3*.

Phân phối cho kiểm định giả thuyết là *t_3*.

*H_0*: *μ_d* ≤ 0, *H_a*: *μ_d* > 0

*H_0*: *μ_d* ≤ 0, *H_a*: *μ_d* > 0

**Graph:**

**Đồ thị:**

*Figure 
10.11*

*Hình 
10.11*

**Calculate the *p*-value:** The *p*-value is 0.2150

**Tính p-giá trị *p*:** p-giá trị *p* là 0,2150

**Decision:** If the level of significance is 5%, the decision is not to reject the null hypothesis, because α < *p*-value.

**Quyết định:** Nếu mức ý nghĩa là 5%, quyết định là không bác bỏ giả thuyết không, vì α < p-giá trị *p*.

**What is the conclusion?**

**Kết luận là gì?**

At a 5% level of significance, from the sample data, there is not sufficient evidence to conclude that the strength development class helped to make the players stronger, on average. It should be noted that this data set consists of a very small sample size, with the possibility of an outlier data value. It is important to confirm that the matched pairs have differences that come from a population that is normal. The coach may want to consider increasing the sample size of players in the study.

Tại mức ý nghĩa 5%, từ dữ liệu mẫu, không có đủ bằng chứng để kết luận rằng lớp phát triển sức mạnh đã giúp các cầu thủ trở nên mạnh mẽ hơn, xét trên giá trị trung bình. Cần lưu ý rằng tập dữ liệu này bao gồm kích thước mẫu rất nhỏ, với khả năng có một giá trị ngoại lệ. Điều quan trọng là phải xác nhận rằng các cặp ghép đôi có các hiệu số đến từ một quần thể có phân phối chuẩn. Huấn luyện viên có thể muốn cân nhắc tăng kích thước mẫu của các cầu thủ trong nghiên cứu.

A new prep class was designed to improve SAT test scores. Four students were selected at random. Their scores on two practice exams were recorded, one before the class and one after. The data recorded in [Table 10.18](10-4-matched-or-paired-samples#fs-idp42085840). Are the scores, on average, higher after the class? Test at a 5% level.

Một lớp luyện thi mới đã được thiết kế để cải thiện điểm thi SAT. Bốn học sinh đã được chọn ngẫu nhiên. Điểm số của họ trong hai bài thi thử đã được ghi lại, một trước khi học lớp này và một sau khi học. Dữ liệu được ghi lại trong [Bảng 10.18](10-4-matched-or-paired-samples#fs-idp42085840). Liệu điểm số trung bình có cao hơn sau khi học lớp này không? Hãy kiểm định ở mức 5%.

| SAT Scores | Điểm SAT | Student 1 | Học sinh 1 | Student 2 | Học sinh 2 | Student 3 | Học sinh 3 | Student 4 | Học sinh 4 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Score before class | Điểm số trước lớp học | 1840 | 1840 | 1960 | 1960 | 1920 | 1920 | 2150 | 2150 |
| Score after class | Điểm số sau lớp học | 1920 | 1920 | 2160 | 2160 | 2200 | 2200 | 2100 | 2100 |

Seven eighth graders at Kennedy Middle School measured how far they could push the shot-put with their dominant (writing) hand and their weaker (non-writing) hand. They thought that they could push equal distances with either hand. The data were collected and recorded in [Table 10.19](10-4-matched-or-paired-samples#table-2535678).

Bảy học sinh lớp tám tại Trường Trung học Cơ sở Kennedy đã đo khoảng cách họ có thể đẩy tạ bằng tay thuận (tay viết) và tay yếu hơn (tay không viết). Các em nghĩ rằng mình có thể đẩy được khoảng cách bằng nhau với cả hai tay. Dữ liệu đã được thu thập và ghi lại trong [Bảng 10.19](10-4-matched-or-paired-samples#table-2535678).

| Distance (in feet) using | Khoảng cách (tính bằng feet) sử dụng | Student 1 | Học sinh 1 | Student 2 | Học sinh 2 | Student 3 | Sinh viên 3 | Student 4 | Sinh viên 4 | Student 5 | Sinh viên 5 | Student 6 | Sinh viên 6 | Student 7 | Sinh viên 7 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Dominant Hand | Tay thuận | 30 | 30 | 26 | 26 | 34 | 34 | 17 | 17 | 19 | 19 | 26 | 26 | 20 | 20 |
| Weaker Hand | Tay yếu hơn | 28 | 28 | 14 | 14 | 27 | 27 | 18 | 18 | 17 | 17 | 26 | 26 | 16 | 16 |

Conduct a hypothesis test to determine whether the mean difference in distances between the children’s dominant versus weaker hands is significant.

Thực hiện kiểm định giả thuyết để xác định xem sự khác biệt trung bình về khoảng cách giữa tay thuận và tay yếu hơn của các em học sinh có đáng kể hay không.

Record the **differences** data. Calculate the differences by subtracting the distances with the weaker hand from the distances with the dominant hand. The data for the differences are: {2, 12, 7, –1, 2, 0, 4}. The differences have a normal distribution.

Ghi lại dữ liệu **hiệu số**. Tính các hiệu số bằng cách lấy khoảng cách của tay yếu hơn trừ đi khoảng cách của tay thuận. Dữ liệu cho các hiệu số là: {2, 12, 7, –1, 2, 0, 4}. Các hiệu số này có phân phối chuẩn.

Using the differences data, calculate the sample mean and the sample standard deviation. 

x
¯

d

x
¯

d

 = 3.71, 

s
d

s
d

 = 4.5.

Sử dụng dữ liệu hiệu số, tính số trung bình mẫu và độ lệch chuẩn mẫu. 

x
¯

d

x
¯

d

 = 3,71, 

s
d

s
d

 = 4,5.

**Random variable:** 

X
¯

d

X
¯

d

 = mean difference in the distances between the hands.

**Biến ngẫu nhiên:** 

X
¯

d

X
¯

d

 = hiệu số trung bình về khoảng cách giữa hai tay.

**Distribution for the hypothesis test:** *t_6*

**Phân phối cho kiểm định giả thuyết:** *t_6*

*H*_0: *μ_d* = 0 *H**_a*: *μ**_d* ≠ 0

*H*:  = 0 *_a**μ* ≠ 0

**Graph:**

**Đồ thị:**

*Figure 
10.12*

*Hình 
10.12*

**Calculate the *p*-value:** The *p*-value is 0.0716 (using the data directly).

**Tính p-giá trị:** p-giá trị là 0,0716 (sử dụng trực tiếp dữ liệu).

(test statistic = 2.18.  *p*-value = 0.0719 using 

(

x
¯

d

=3.71, 
s
d

=4.5.

)

(

x
¯

d

=3.71, 
s
d

=4.5.

)

(thống kê kiểm định = 2,18. p-giá trị = 0,0719 sử dụng 

(

x
¯

d

=3.71, 
s
d

=4.5.

)

(

x
¯

d

=3.71, 
s
d

=4.5.

)

**Decision:** Assume *α* = 0.05. Since *α* < *p*-value, Do not reject *H_0*.

**Quyết định:** Giả sử *α* = 0,05. Vì *α* < p-giá trị, không bác bỏ *H_0*.

**Conclusion:**  At the 5% level of significance, from the sample data, there is not sufficient evidence to conclude that there is a difference in the children’s weaker and dominant hands to push the shot-put.

**Kết luận:** Tại mức ý nghĩa 5%, từ dữ liệu mẫu, không có đủ bằng chứng để kết luận rằng có sự khác biệt giữa tay yếu hơn và tay thuận của các em học sinh trong việc đẩy tạ.

Five ball players think they can throw the same distance with their dominant hand (throwing) and off-hand (catching hand). The data were collected and recorded in [Table 10.20](10-4-matched-or-paired-samples#fs-idp26621360). Conduct a hypothesis test to determine whether the mean difference in distances between the dominant and off-hand is significant. Test at the 5% level.

Năm cầu thủ bóng ném nghĩ rằng họ có thể ném cùng một khoảng cách bằng tay thuận (tay ném) và tay không thuận (tay bắt). Dữ liệu đã được thu thập và ghi lại trong [Bảng 10.20](10-4-matched-or-paired-samples#fs-idp26621360). Thực hiện kiểm định giả thuyết để xác định xem sự khác biệt trung bình về khoảng cách giữa tay thuận và tay không thuận có đáng kể hay không. Kiểm định ở mức 5%.

|  |  | Player 1 | Người chơi 1 | Player 2 | Người chơi 2 | Player 3 | Người chơi 3 | Player 4 | Người chơi 4 | Player 5 | Người chơi 5 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Dominant Hand | Tay thuận | 120 | 120 | 111 | 111 | 135 | 135 | 140 | 140 | 125 | 125 |
| Off-hand | Tay không thuận | 105 | 105 | 109 | 109 | 98 | 98 | 111 | 111 | 99 | 99 |
