## 12.6
 
Outliers

## 12.6
 
Các điểm bất thường

In some data sets, there are values **(observed data points)** called outliers. **Outliers are observed data points that are far from the least squares line.** They have large "errors", where the "error" or residual is the vertical distance from the line to the point.

Trong một số tập dữ liệu, có những giá trị **(các điểm dữ liệu quan sát được)** được gọi là các điểm bất thường. **Các điểm bất thường là các điểm dữ liệu quan sát được nằm xa đường bình phương tối thiểu.** Chúng có các "sai số" lớn, trong đó "sai số" hay phần dư là khoảng cách thẳng đứng từ đường thẳng đến điểm đó.

Outliers need to be examined closely. Sometimes, for some reason or another, they should not be included in the analysis of the data. It is possible that an outlier is a result of erroneous data. Other times, an outlier may
hold valuable information about the population under study and should remain included in the data. The key is to examine carefully what causes a data point to be an outlier.

Các điểm bất thường cần được xem xét kỹ lưỡng. Đôi khi, vì lý do này hay lý do khác, chúng không nên được đưa vào phân tích dữ liệu. Có khả năng một điểm bất thường là kết quả của dữ liệu sai lệch. Những lần khác, một điểm bất thường có thể chứa thông tin có giá trị về quần thể đang được nghiên cứu và nên được giữ lại trong dữ liệu. Điều quan trọng là phải kiểm tra cẩn thận nguyên nhân khiến một điểm dữ liệu trở thành điểm bất thường.

Besides outliers, a sample may contain one or a few points that are called influential points. Influential points are observed data points that are far from the other observed data points in the horizontal direction. These points may have a big effect on the slope of the regression line. To begin to identify an influential point, you can remove it from the data set and see if the slope of the regression line is changed significantly.

Ngoài các điểm bất thường, một mẫu có thể chứa một hoặc một vài điểm được gọi là các điểm ảnh hưởng. Các điểm ảnh hưởng là các điểm dữ liệu quan sát được nằm xa các điểm dữ liệu quan sát được khác theo phương ngang. Những điểm này có thể có ảnh hưởng lớn đến độ dốc của đường hồi quy. Để bắt đầu xác định một điểm ảnh hưởng, bạn có thể loại bỏ nó khỏi tập dữ liệu và xem liệu độ dốc của đường hồi quy có thay đổi đáng kể hay không.

Computers and many calculators can be used to identify outliers from the data. Computer output for regression analysis will often identify both outliers and influential points so that you can examine them.

Máy tính và nhiều máy tính cầm tay có thể được sử dụng để xác định các điểm bất thường từ dữ liệu. Kết quả đầu ra của máy tính cho phân tích hồi quy thường sẽ xác định cả các điểm bất thường và các điểm ảnh hưởng để bạn có thể kiểm tra chúng.

### Identifying Outliers

### Nhận diện các điểm bất thường

We could guess at outliers by looking at a graph of the scatterplot and best fit-line. However, we would like some guideline as to how far away a point needs to be in order to be considered an outlier. ** As a rough rule of thumb, we can flag any point that is located further than two standard deviations above or below the best-fit line as an outlier**. The standard deviation used is the standard deviation of the residuals or errors.

Chúng ta có thể đoán các điểm bất thường bằng cách nhìn vào biểu đồ phân tán và đường phù hợp nhất. Tuy nhiên, chúng ta muốn có một số hướng dẫn về việc một điểm cần nằm cách xa bao nhiêu để được coi là điểm bất thường. **Theo quy tắc ngón tay cái, chúng ta có thể đánh dấu bất kỳ điểm nào nằm xa hơn hai độ lệch chuẩn phía trên hoặc phía dưới đường phù hợp nhất là một điểm bất thường**. Độ lệch chuẩn được sử dụng là độ lệch chuẩn của các phần dư hoặc sai số.

We can do this visually in the scatter plot by drawing an extra pair of lines that are two standard deviations above and below the best-fit line. Any data points that are outside this extra pair of lines are flagged as potential outliers. Or we can do this numerically by calculating each residual and comparing it to twice the standard deviation. On the TI-83, 83+, or 84+, the graphical approach is easier. The graphical procedure is shown first, followed by the numerical calculations. You would generally need to use only one of these methods.

Chúng ta có thể thực hiện việc này một cách trực quan trên biểu đồ phân tán bằng cách vẽ thêm một cặp đường thẳng nằm cách đường phù hợp nhất hai độ lệch chuẩn phía trên và phía dưới. Bất kỳ điểm dữ liệu nào nằm ngoài cặp đường bổ sung này đều được đánh dấu là các điểm bất thường tiềm ẩn. Hoặc chúng ta có thể thực hiện việc này bằng số bằng cách tính toán từng phần dư và so sánh nó với hai lần độ lệch chuẩn. Trên máy tính TI-83, 83+ hoặc 84+, phương pháp đồ thị dễ dàng hơn. Quy trình đồ thị được hiển thị trước, sau đó là các tính toán bằng số. Thông thường, bạn chỉ cần sử dụng một trong các phương pháp này.

#### Problem

#### Bài tập

In the [third exam/final exam example](12-3-the-regression-equation), you can determine if there is an outlier or not. If there is an outlier, as an exercise, delete it and fit the remaining data to a new line. For this example, the new line ought to fit the remaining data better. This means the **SSE** should be smaller and the correlation coefficient ought to be closer to 1 or –1.

Trong [ví dụ về bài thi thứ ba/bài thi cuối kỳ](12-3-the-regression-equation), bạn có thể xác định xem có điểm bất thường hay không. Nếu có một điểm bất thường, như một bài tập, hãy xóa nó đi và khớp dữ liệu còn lại với một đường thẳng mới. Đối với ví dụ này, đường thẳng mới sẽ khớp với dữ liệu còn lại tốt hơn. Điều này có nghĩa là **SSE** sẽ nhỏ hơn và hệ số tương quan sẽ gần với 1 hoặc –1 hơn.

Identify the potential outlier in the scatter plot. The standard deviation of the residuals or errors is approximately 8.6.

Xác định điểm bất thường tiềm ẩn trong biểu đồ phân tán. Độ lệch chuẩn của các phần dư hoặc sai số xấp xỉ 8,6.

*Figure 
12.21*

*Hình 
12.21*

### Numerical Identification of Outliers

### Nhận diện bằng số các điểm bất thường

In [Table 12.6](12-6-outliers#element-4662), the first two columns are the third-exam and final-exam data. The third column shows the predicted *ŷ* values calculated from the line of best fit: *ŷ* = –173.5 + 4.83*x*. The residuals, or errors, have been calculated in the fourth column of the table: observed *y* value−predicted y value = *y* − *ŷ*.

Trong [Bảng 12.6](12-6-outliers#element-4662), hai cột đầu tiên là dữ liệu bài thi thứ ba và bài thi cuối kỳ. Cột thứ ba hiển thị các giá trị *ŷ* dự đoán được tính từ đường phù hợp nhất: *ŷ* = –173,5 + 4,83*x*. Các phần dư, hay sai số, đã được tính toán trong cột thứ tư của bảng: giá trị *y* quan sát được − giá trị y dự đoán = *y* − *ŷ*.

*s* is the standard deviation of all the *y* − *ŷ* = *ε* values where *n* = the total number of data points. If each residual is calculated and squared, and the results are added, we get the SSE. The standard deviation of the residuals is calculated from the SSE as:

*s* là độ lệch chuẩn của tất cả các giá trị *y* − *ŷ* = *ε* trong đó *n* = tổng số điểm dữ liệu. Nếu mỗi phần dư được tính toán và bình phương, và các kết quả được cộng lại, chúng ta sẽ có SSE. Độ lệch chuẩn của các phần dư được tính từ SSE như sau:

We divide by (*n* – 2) because the regression model involves two estimates.

Chúng ta chia cho (*n* – 2) vì mô hình hồi quy liên quan đến hai ước lượng.

Rather than calculate the value of *s* ourselves, we can find *s* using the computer or calculator. For this example, the calculator function LinRegTTest found *s* = 16.4 as the standard deviation of the residuals 35; 
–17; 
16; 
–6; 
–19; 
9; 
3; 
–1; 
–10; 
–9; 
–1
.

Thay vì tự tính giá trị của *s*, chúng ta có thể tìm *s* bằng máy tính hoặc máy tính cầm tay. Đối với ví dụ này, hàm LinRegTTest trên máy tính đã tìm thấy *s* = 16,4 là độ lệch chuẩn của các phần dư 35; 
–17; 
16; 
–6; 
–19; 
9; 
3; 
–1; 
–10; 
–9; 
–1
.

| *x* | *x* | *y* | *y* | *ŷ* | *ŷ* | *y* – *ŷ* | *y* – *ŷ* |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 65 | 65 | 175 | 175 | 140 | 140 | 175 – 140 = 35 | 175 – 140 = 35 |
| 67 | 67 | 133 | 133 | 150 | 150 | 133 – 150= –17 | 133 – 150= –17 |
| 71 | 71 | 185 | 185 | 169 | 169 | 185 – 169 = 16 | 185 – 169 = 16 |
| 71 | 71 | 163 | 163 | 169 | 169 | 163 – 169 = –6 | 163 – 169 = –6 |
| 66 | 66 | 126 | 126 | 145 | 145 | 126 – 145 = –19 | 126 – 145 = –19 |
| 75 | 75 | 198 | 198 | 189 | 189 | 198 – 189 = 9 | 198 – 189 = 9 |
| 67 | 67 | 153 | 153 | 150 | 150 | 153 – 150 = 3 | 153 – 150 = 3 |
| 70 | 70 | 163 | 163 | 164 | 164 | 163 – 164 = –1 | 163 – 164 = –1 |
| 71 | 71 | 159 | 159 | 169 | 169 | 159 – 169 = –10 | 159 – 169 = –10 |
| 69 | 69 | 151 | 151 | 160 | 160 | 151 – 160 = –9 | 151 – 160 = –9 |
| 69 | 69 | 159 | 159 | 160 | 160 | 159 – 160 = –1 | 159 – 160 = –1 |

We are looking for all data points for which the residual is greater than 2*s* = 2(16.4) = 32.8 or less than –32.8. Compare these values to the residuals in column four of the table. The only such data point is the student who had a grade of 65 on the third exam and 175 on the final exam; the residual for this student is 35.

Chúng ta đang tìm kiếm tất cả các điểm dữ liệu mà phần dư lớn hơn 2*s* = 2(16,4) = 32,8 hoặc nhỏ hơn –32,8. So sánh các giá trị này với các phần dư trong cột thứ tư của bảng. Điểm dữ liệu duy nhất như vậy là sinh viên có điểm 65 trong bài thi thứ ba và 175 trong bài thi cuối kỳ; phần dư cho sinh viên này là 35.

### How does the outlier affect the best fit line?

### Điểm bất thường ảnh hưởng như thế nào đến đường phù hợp nhất?

Numerically and graphically, we have identified the point (65, 175) as an outlier. We should re-examine the data for this point to see if there are any problems with the data. If there is an error, we should fix the error if possible, or delete the data. If the data is correct, we would leave it in the data set. For this problem, we will suppose that we examined the data and found that this outlier data was an error. Therefore we will continue on and delete the outlier, so that we can explore how it affects the results, as a learning experience.

Về mặt số học và đồ thị, chúng ta đã xác định điểm (65, 175) là một điểm bất thường. Chúng ta nên kiểm tra lại dữ liệu cho điểm này để xem có vấn đề gì với dữ liệu hay không. Nếu có lỗi, chúng ta nên sửa lỗi nếu có thể, hoặc xóa dữ liệu. Nếu dữ liệu chính xác, chúng ta sẽ để nó trong tập dữ liệu. Đối với bài toán này, chúng ta sẽ giả định rằng chúng ta đã kiểm tra dữ liệu và thấy rằng dữ liệu bất thường này là một lỗi. Do đó, chúng ta sẽ tiếp tục và xóa điểm bất thường, để chúng ta có thể khám phá cách nó ảnh hưởng đến kết quả như một trải nghiệm học tập.

Compute a new best-fit line and correlation coefficient using the ten remaining points:
On the TI-83, TI-83+, TI-84+ calculators, delete the outlier from L1 and L2. Using the LinRegTTest, the new line of best fit and the correlation coefficient are:

Tính toán một đường phù hợp nhất mới và hệ số tương quan sử dụng mười điểm còn lại:
Trên các máy tính TI-83, TI-83+, TI-84+, hãy xóa điểm bất thường khỏi L1 và L2. Sử dụng LinRegTTest, đường phù hợp nhất mới và hệ số tương quan là:

*ŷ* = –355.19 + 7.39*x* and *r* = 0.9121

*ŷ* = –355,19 + 7,39*x* và *r* = 0,9121

The new line with *r* = 0.9121 is a stronger correlation than the original (*r* = 0.6631) because *r* = 0.9121 is closer to one. This means that the new line is a better fit to the ten remaining data values. The line can better predict the final exam score given the third exam score.

Đường thẳng mới với *r* = 0,9121 có tương quan mạnh hơn so với ban đầu (*r* = 0,6631) vì *r* = 0,9121 gần với một hơn. Điều này có nghĩa là đường thẳng mới khớp tốt hơn với mười giá trị dữ liệu còn lại. Đường thẳng này có thể dự đoán điểm thi cuối kỳ tốt hơn dựa trên điểm thi thứ ba.

### Numerical Identification of Outliers: Calculating *s* and Finding Outliers Manually

### Nhận diện bằng số các điểm bất thường: Tính toán *s* và tìm các điểm bất thường theo cách thủ công

If you do not have the function LinRegTTest, then you can calculate the outlier in the first example by doing the following.

First, **square each |*y* – *ŷ*|**

Nếu bạn không có hàm LinRegTTest, thì bạn có thể tính toán điểm bất thường trong ví dụ đầu tiên bằng cách thực hiện các bước sau.

Đầu tiên, **bình phương mỗi |*y* – *ŷ*|**

The squares are 
35^2; 
17^2; 
16^2; 
6^2; 
19^2; 
9^2; 
3^2; 
1^2; 
10^2; 
9^2; 
1^2

Các bình phương là 
35^2; 
17^2; 
16^2; 
6^2; 
19^2; 
9^2; 
3^2; 
1^2; 
10^2; 
9^2; 
1^2

**Then, add (sum) all the |*y* – *ŷ*| squared terms** using the formula

**Sau đó, cộng (tổng) tất cả các số hạng |*y* – *ŷ*| bình phương** bằng cách sử dụng công thức

Σ

i = 1

11

(

|
y
i

−

y
^

i

|

)

2

=

Σ

i = 1

11

ε
i

2

Σ

i = 1

11

(

|
y
i

−

y
^

i

|

)

2

=

Σ

i = 1

11

ε
i

2

 (Recall that *y*_i – *ŷ*_i = *ε*_i.)

Σ

i = 1

11

(

|
y
i

−

y
^

i

|

)

2

=

Σ

i = 1

11

ε
i

2

Σ

i = 1

11

(

|
y
i

−

y
^

i

|

)

2

=

Σ

i = 1

11

ε
i

2

 (Nhớ rằng *y*_i – *ŷ*_i = *ε*_i.)

= 35^2 + 17^2 + 16^2 + 6^2 + 19^2 + 9^2 + 3^2 + 1^2 + 10^2 + 9^2 + 1^2

= 35^2 + 17^2 + 16^2 + 6^2 + 19^2 + 9^2 + 3^2 + 1^2 + 10^2 + 9^2 + 1^2

= 2440 =  **SSE**. The result, **SSE** is the Sum of Squared Errors.

= 2440 =  **SSE**. Kết quả, **SSE** là Tổng bình phương sai số.

**Next, calculate *s*, the standard deviation of all the *y* – *ŷ* = *ε* values where *n* = the total number of data points.**

**Tiếp theo, tính *s*, độ lệch chuẩn của tất cả các giá trị *y* – *ŷ* = *ε* trong đó *n* = tổng số điểm dữ liệu.**

The calculation is s=

SSE
n–2

s=

SSE
n–2

.

Phép tính là s=

SSE
n–2

s=

SSE
n–2

.

For the third exam/final exam problem, s=

2440
11–2

=16.47
s=

2440
11–2

=16.47.

Đối với bài toán về kỳ thi thứ ba/kỳ thi cuối khóa, s=

2440
11–2

=16.47
s=

2440
11–2

=16.47.

Next, multiply *s* by 2:

(2)(16.47) = 32.94

32.94 is 2 standard deviations away from the mean of the *y* – *ŷ* values.

Tiếp theo, nhân *s* với 2:

(2)(16,47) = 32,94

32,94 cách giá trị trung bình của các giá trị *y* – *ŷ* là 2 độ lệch chuẩn.

If we were to measure the vertical distance from any data point to the corresponding point on the line of best fit and that distance is at least 2*s*, then we would consider the data point to be "too far" from the line of best fit. We call that point a potential outlier.

Nếu chúng ta đo khoảng cách theo chiều dọc từ bất kỳ điểm dữ liệu nào đến điểm tương ứng trên đường phù hợp nhất và khoảng cách đó ít nhất là 2*s*, thì chúng ta sẽ coi điểm dữ liệu đó là "quá xa" so với đường phù hợp nhất. Chúng ta gọi điểm đó là điểm bất thường tiềm ẩn.

For the example, if any of the |*y* – *ŷ*| values are **at least** 32.94, the corresponding (*x*, *y*) data point is a potential outlier.

Đối với ví dụ này, nếu bất kỳ giá trị |*y* – *ŷ*| nào **ít nhất** là 32,94, thì điểm dữ liệu (*x*, *y*) tương ứng là một điểm bất thường tiềm ẩn.

For the third exam/final exam problem, all the |*y* – *ŷ*|'s are less than 31.29 except for the first one which is 35.

Đối với bài toán về kỳ thi thứ ba/kỳ thi cuối khóa, tất cả các giá trị |*y* – *ŷ*| đều nhỏ hơn 31,29 ngoại trừ giá trị đầu tiên là 35.

35 > 31.29 That is, |*y* – *ŷ*| ≥ (2)(s)

35 > 31,29 Nghĩa là, |*y* – *ŷ*| ≥ (2)(s)

The point which corresponds to |*y* – *ŷ*| = 35 is (65, 175). **Therefore, the data point (65,175) is a potential outlier.** For this example, we will delete it. (Remember, we do not always delete an outlier.)

Điểm tương ứng với |*y* – *ŷ*| = 35 là (65, 175). **Do đó, điểm dữ liệu (65,175) là một điểm bất thường tiềm ẩn.** Đối với ví dụ này, chúng ta sẽ xóa nó đi. (Hãy nhớ rằng, chúng ta không phải lúc nào cũng xóa một điểm bất thường.)

When outliers are deleted, the researcher should either record that data was deleted, and why, or the researcher should provide results both with and without the deleted data. If data is erroneous and the correct values are known (e.g., student one actually scored a 70 instead of a 65), then this correction can be made to the data.

Khi các điểm bất thường bị xóa, nhà nghiên cứu nên ghi lại rằng dữ liệu đã bị xóa và lý do tại sao, hoặc nhà nghiên cứu nên cung cấp kết quả cả khi có và không có dữ liệu đã xóa. Nếu dữ liệu bị sai và các giá trị đúng đã được biết (ví dụ: sinh viên thứ nhất thực tế đạt 70 điểm thay vì 65), thì có thể thực hiện hiệu chỉnh này cho dữ liệu.

The next step is to compute a new best-fit line using the ten remaining
points. The new line of best fit and the correlation coefficient are:

Bước tiếp theo là tính toán một đường phù hợp nhất mới bằng cách sử dụng mười điểm còn lại. Đường phù hợp nhất mới và hệ số tương quan là:

*ŷ* = –355.19 + 7.39*x* and *r* = 0.9121

*ŷ* = –355,19 + 7,39*x* và *r* = 0,9121

#### Problem

#### Bài tập

Using this new line of best fit (based on the remaining ten data points  in the [third exam/final exam example](12-3-the-regression-equation)), what would a student who receives a 73 on the third exam expect to receive on the final exam? Is this the same as the prediction made using the original line?

Sử dụng đường phù hợp nhất mới này (dựa trên mười điểm dữ liệu còn lại trong [ví dụ về kỳ thi thứ ba/kỳ thi cuối khóa](12-3-the-regression-equation)), một sinh viên nhận được 73 điểm trong kỳ thi thứ ba dự kiến sẽ nhận được bao nhiêu điểm trong kỳ thi cuối khóa? Kết quả này có giống với dự đoán được thực hiện bằng đường ban đầu không?

The data points for the graph from the [third exam/final exam example](12-3-the-regression-equation) are as follows: (1, 5), (2, 7), (2, 6), (3, 9), (4, 12), (4, 13), (5, 18), (6, 19), (7, 12), and (7, 21). Remove the outlier and recalculate the line of best fit. Find the value of *ŷ* when *x* = 10.

Các điểm dữ liệu cho biểu đồ từ [ví dụ về kỳ thi thứ ba/kỳ thi cuối khóa](12-3-the-regression-equation) như sau: (1, 5), (2, 7), (2, 6), (3, 9), (4, 12), (4, 13), (5, 18), (6, 19), (7, 12), và (7, 21). Loại bỏ điểm bất thường và tính toán lại đường phù hợp nhất. Tìm giá trị của *ŷ* khi *x* = 10.

The Consumer Price Index (CPI) measures the average change over time in the prices paid by urban consumers for consumer goods and services. The CPI affects nearly all Americans because of the many ways it is used. One of its biggest uses is as a measure of inflation. By providing information about price changes in the Nation's economy to government, business, and labor, the CPI helps them to make economic decisions. The President, Congress, and the Federal Reserve Board use the CPI's trends to formulate monetary and fiscal policies.  In the following table, *x* is the year and *y* is the CPI.

Chỉ số giá tiêu dùng (CPI) đo lường sự thay đổi trung bình theo thời gian về giá cả mà người tiêu dùng thành thị phải trả cho hàng hóa và dịch vụ tiêu dùng. CPI ảnh hưởng đến hầu hết tất cả người Mỹ vì nhiều cách sử dụng của nó. Một trong những công dụng lớn nhất của nó là thước đo lạm phát. Bằng cách cung cấp thông tin về những thay đổi giá cả trong nền kinh tế quốc gia cho chính phủ, doanh nghiệp và người lao động, CPI giúp họ đưa ra các quyết định kinh tế. Tổng thống, Quốc hội và Hội đồng Dự trữ Liên bang sử dụng các xu hướng của CPI để xây dựng các chính sách tiền tệ và tài khóa. Trong bảng sau, *x* là năm và *y* là CPI.

| *x* | *x* | *y* | *y* | *x* | *x* | *y* | *y* |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1915 | 1915 | 10.1 | 10,1 | 1979 | 1979 | 72.6 | 72,6 |
| 1926 | 1926 | 17.7 | 17,7 | 1980 | 1980 | 82.4 | 82,4 |
| 1935 | 1935 | 13.7 | 13,7 | 1986 | 1986 | 109.6 | 109,6 |
| 1940 | 1940 | 14.7 | 14,7 | 1991 | 1991 | 130.7 | 130,7 |
| 1947 | 1947 | 24.1 | 24,1 | 1999 | 1999 | 166.6 | 166,6 |
| 1952 | 1952 | 26.5 | 26,5 | 2010 | 2010 | 219.2 | 219,2 |
| 1964 | 1964 | 31.0 | 31,0 | 2020 | 2020 | 258 | 258 |
| 1969 | 1969 | 36.7 | 36,7 | 2023 | 2023 | 299.2 | 299,2 |
| 1975 | 1975 | 49.3 | 49,3 |  |  |  |  |

#### Problem

#### Bài tập

1. Draw a scatterplot of the data.
1. Vẽ biểu đồ phân tán của dữ liệu.
1. Calculate the least squares line. Write the equation in the form *ŷ* = *a* + *bx*.
1. Tính toán đường bình phương tối thiểu. Viết phương trình dưới dạng *ŷ* = *a* + *bx*.
1. Draw the line on the scatterplot.
1. Vẽ đường thẳng trên biểu đồ phân tán.
1. Find the correlation coefficient. Is it significant?
1. Tìm hệ số tương quan. Nó có đáng kể không?
1. What is the average CPI for the year 1990?
1. CPI trung bình cho năm 1990 là bao nhiêu?
In the example, notice the pattern of the points compared to the line.  Although the correlation coefficient is significant, the pattern in the scatterplot indicates that a curve would be a more appropriate model to use than a line.  In this example, a statistician should prefer to use other methods to fit a curve to this data, rather than model the data with the line we found. In addition to doing the calculations, it is always important to look at the scatterplot when deciding whether a linear model is appropriate.

Trong ví dụ này, hãy chú ý đến mô hình của các điểm so với đường thẳng. Mặc dù hệ số tương quan là đáng kể, nhưng mô hình trong biểu đồ phân tán cho thấy một đường cong sẽ là mô hình phù hợp hơn để sử dụng thay vì một đường thẳng. Trong ví dụ này, một nhà thống kê nên ưu tiên sử dụng các phương pháp khác để khớp một đường cong với dữ liệu này, thay vì mô hình hóa dữ liệu bằng đường thẳng mà chúng ta đã tìm thấy. Ngoài việc thực hiện các phép tính, việc xem biểu đồ phân tán khi quyết định xem mô hình tuyến tính có phù hợp hay không luôn là điều quan trọng.

If you are interested in seeing more years of data, visit the Bureau of Labor Statistics CPI website ftp://ftp.bls.gov/pub/special.requests/cpi/cpiai.txt; our data is taken from the column entitled "Annual Avg." (third column from the right). For example you could add more current years of data. Try adding the more recent years: 2010: CPI = 219.2; 2020: CPI = 258.0; 2023: CPI = 299.2. See how it affects the model. (Check: y⏜ =-5030+2.598xy⏜ =-5030+2.598x; r = 0.9067r = 0.9067. Is r significant? Is the fit better with the addition of the new points?)

Nếu bạn muốn xem thêm dữ liệu của nhiều năm, hãy truy cập trang web CPI của Cục Thống kê Lao động ftp://ftp.bls.gov/pub/special.requests/cpi/cpiai.txt; dữ liệu của chúng tôi được lấy từ cột có tiêu đề "Annual Avg." (cột thứ ba từ bên phải). Ví dụ, bạn có thể thêm dữ liệu của các năm gần đây hơn. Hãy thử thêm các năm gần đây: 2010: CPI = 219.2; 2020: CPI = 258,0; 2023: CPI = 299,2. Xem cách nó ảnh hưởng đến mô hình. (Kiểm tra: y⏜ =-5030+2.598xy⏜ =-5030+2.598x; r = 0.9067r = 0.9067. r có đáng kể không? Độ khớp có tốt hơn khi thêm các điểm mới không?)

The following table shows economic development measured in per capita income PCINC.

Bảng sau đây cho thấy sự phát triển kinh tế được đo bằng thu nhập bình quân đầu người PCINC.

| Year | Năm | PCINC | PCINC | Year | Năm | PCINC | PCINC |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1870 | 1870 | 340 | 340 | 1920 | 1920 | 1050 | 1050 |
| 1880 | 1880 | 499 | 499 | 1930 | 1930 | 1170 | 1170 |
| 1890 | 1890 | 592 | 592 | 1940 | 1940 | 1364 | 1364 |
| 1900 | 1900 | 757 | 757 | 1950 | 1950 | 1836 | 1836 |
| 1910 | 1910 | 927 | 927 | 1960 | 1960 | 2132 | 2132 |

1. What are the independent and dependent variables?
1. Các biến độc lập và biến phụ thuộc là gì?
1. Draw a scatter plot.
1. Vẽ biểu đồ phân tán.
1. Use regression to find the line of best fit and the correlation coefficient.
1. Sử dụng hồi quy để tìm đường phù hợp nhất và hệ số tương quan.
1. Interpret the significance of the correlation coefficient.
1. Giải thích ý nghĩa của hệ số tương quan.
1. Is there a linear relationship between the variables?
1. Có mối quan hệ tuyến tính giữa các biến không?
1. Find the coefficient of determination and interpret it.
1. Tìm hệ số xác định và giải thích nó.
1. What is the slope of the regression equation? What does it mean?
1. Độ dốc của phương trình hồi quy là bao nhiêu? Nó có nghĩa là gì?
1. Use the line of best fit to estimate PCINC for 1900, for 2000.
1. Sử dụng đường phù hợp nhất để ước tính PCINC cho năm 1900, cho năm 2000.
1. Determine if there are any outliers.
1. Xác định xem có bất kỳ điểm bất thường nào không.
### 95% Critical Values of the Sample Correlation Coefficient Table

### Bảng các giá trị tới hạn 95% của hệ số tương quan mẫu

| Degrees of Freedom: *n* – 2 | Bậc tự do: *n* – 2 | Critical Values: (+ and –) | Giá trị tới hạn: (+ và –) |
| --- | --- | --- | --- |
| 1 | 1 | 0.997 | 0,997 |
| 2 | 2 | 0.950 | 0,950 |
| 3 | 3 | 0.878 | 0,878 |
| 4 | 4 | 0.811 | 0,811 |
| 5 | 5 | 0.754 | 0,754 |
| 6 | 6 | 0.707 | 0,707 |
| 7 | 7 | 0.666 | 0,666 |
| 8 | 8 | 0.632 | 0,632 |
| 9 | 9 | 0.602 | 0,602 |
| 10 | 10 | 0.576 | 0,576 |
| 11 | 11 | 0.555 | 0,555 |
| 12 | 12 | 0.532 | 0,532 |
| 13 | 13 | 0.514 | 0,514 |
| 14 | 14 | 0.497 | 0,497 |
| 15 | 15 | 0.482 | 0,482 |
| 16 | 16 | 0.468 | 0,468 |
| 17 | 17 | 0.456 | 0,456 |
| 18 | 18 | 0.444 | 0,444 |
| 19 | 19 | 0.433 | 0,433 |
| 20 | 20 | 0.423 | 0,423 |
| 21 | 21 | 0.413 | 0,413 |
| 22 | 22 | 0.404 | 0,404 |
| 23 | 23 | 0.396 | 0,396 |
| 24 | 24 | 0.388 | 0,388 |
| 25 | 25 | 0.381 | 0,381 |
| 26 | 26 | 0.374 | 0,374 |
| 27 | 27 | 0.367 | 0,367 |
| 28 | 28 | 0.361 | 0,361 |
| 29 | 29 | 0.355 | 0,355 |
| 30 | 30 | 0.349 | 0,349 |
| 40 | 40 | 0.304 | 0,304 |
| 50 | 50 | 0.273 | 0,273 |
| 60 | 60 | 0.250 | 0,250 |
| 70 | 70 | 0.232 | 0,232 |
| 80 | 80 | 0.217 | 0,217 |
| 90 | 90 | 0.205 | 0,205 |
| 100 | 100 | 0.195 | 0,195 |
