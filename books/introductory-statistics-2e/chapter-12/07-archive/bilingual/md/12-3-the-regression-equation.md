## 12.3
 
The Regression Equation

## 12.3
 
Phương trình hồi quy

Data rarely fit a straight line exactly. Usually, you must be satisfied with rough
predictions. Typically, you have a set of data whose scatter plot appears to **"fit"** a
straight line. This is called a Line of Best Fit **or** Least-Squares Line.

Dữ liệu hiếm khi khớp chính xác với một đường thẳng. Thông thường, bạn phải hài lòng với các dự đoán thô. Thông thường, bạn có một tập dữ liệu mà biểu đồ phân tán dường như **"khớp"** với một đường thẳng. Đây được gọi là Đường phù hợp nhất **hoặc** Đường hồi quy bình phương tối thiểu.

If you know a person's pinky (smallest) finger length, do you think you could predict that
person's height? Collect data from your class (pinky finger length, in inches). The
independent variable, *x*, is pinky finger length and the dependent variable, *y*, is height. For each set of data, plot the points on graph paper. Make your graph big enough and **use a ruler**. Then "by eye" draw a line that appears to "fit" the data. For your line, pick two convenient points and use them to find the slope of the line. Find the *y*-intercept of the line by extending your line so it crosses the *y*-axis. Using the slopes and the *y*-intercepts, write your equation of "best fit." Do you think everyone will have the same equation? Why or why not? According to your equation, what is the predicted height for a pinky length of 2.5 inches?

Nếu bạn biết chiều dài ngón út của một người, bạn có nghĩ rằng mình có thể dự đoán chiều cao của người đó không? Thu thập dữ liệu từ lớp học của bạn (chiều dài ngón út, tính bằng inch). Biến giải thích, *x*, là chiều dài ngón út và biến phản hồi, *y*, là chiều cao. Đối với mỗi tập dữ liệu, hãy vẽ các điểm trên giấy kẻ ô. Hãy làm cho biểu đồ của bạn đủ lớn và **sử dụng thước kẻ**. Sau đó, "bằng mắt thường", hãy vẽ một đường thẳng dường như "khớp" với dữ liệu. Đối với đường thẳng của bạn, hãy chọn hai điểm thuận tiện và sử dụng chúng để tìm hệ số góc của đường thẳng. Tìm điểm cắt *y* của đường thẳng bằng cách kéo dài đường thẳng của bạn để nó cắt trục *y*. Sử dụng các hệ số góc và điểm cắt *y*, hãy viết phương trình "phù hợp nhất" của bạn. Bạn có nghĩ rằng mọi người sẽ có cùng một phương trình không? Tại sao có hoặc tại sao không? Theo phương trình của bạn, chiều cao dự đoán cho chiều dài ngón út là 2,5 inch là bao nhiêu?

A random sample of 11 statistics students produced the following data, where *x* is the third exam score out of 80, and *y* is the final exam score out of 200. Can you predict the final exam score of a random student if you know the third exam score?

Một mẫu ngẫu nhiên gồm 11 sinh viên thống kê đã tạo ra dữ liệu sau, trong đó *x* là điểm thi lần thứ ba trên thang điểm 80, và *y* là điểm thi cuối kỳ trên thang điểm 200. Bạn có thể dự đoán điểm thi cuối kỳ của một sinh viên ngẫu nhiên nếu bạn biết điểm thi lần thứ ba không?

| x (third exam score) | x (điểm thi lần thứ ba) | y (final exam score) | y (điểm thi cuối kỳ) |
| --- | --- | --- | --- |
| 65 | 65 | 175 | 175 |
| 67 | 67 | 133 | 133 |
| 71 | 71 | 185 | 185 |
| 71 | 71 | 163 | 163 |
| 66 | 66 | 126 | 126 |
| 75 | 75 | 198 | 198 |
| 67 | 67 | 153 | 153 |
| 70 | 70 | 163 | 163 |
| 71 | 71 | 159 | 159 |
| 69 | 69 | 151 | 151 |
| 69 | 69 | 159 | 159 |

*Figure 
12.9
 
Scatter plot showing the scores on the final exam based on scores from the third exam.*

*Hình 
12.9
 
Biểu đồ phân tán hiển thị điểm số trong bài thi cuối kỳ dựa trên điểm số từ bài thi thứ ba.*

SCUBA divers have maximum dive times they cannot exceed when going to different depths. The data in [Table 12.4](12-3-the-regression-equation#eip-idm70490496) show different depths with the maximum dive times in minutes. Use your calculator to find the least squares regression line and predict the maximum dive time for 110 feet.

Thợ lặn SCUBA có thời gian lặn tối đa mà họ không được vượt quá khi đi đến các độ sâu khác nhau. Dữ liệu trong [Bảng 12.4](12-3-the-regression-equation#eip-idm70490496) hiển thị các độ sâu khác nhau với thời gian lặn tối đa tính bằng phút. Sử dụng máy tính của bạn để tìm đường hồi quy bình phương tối thiểu và dự đoán thời gian lặn tối đa cho độ sâu 110 feet.

| *X* (depth in feet) | *X* (độ sâu tính bằng feet) | *Y* (maximum dive time) | *Y* (thời gian lặn tối đa) |
| --- | --- | --- | --- |
| 50 | 50 | 80 | 80 |
| 60 | 60 | 55 | 55 |
| 70 | 70 | 45 | 45 |
| 80 | 80 | 35 | 35 |
| 90 | 90 | 25 | 25 |
| 100 | 100 | 22 | 22 |

The third exam score, *x*, is the independent variable and the final exam score, *y*, is the dependent variable. We will plot a regression line that best "fits" the data. If each of you were to fit a line "by eye," you would draw different lines. We can use what is called a least-squares regression line to obtain the best fit line.

Điểm thi lần thứ ba, *x*, là biến giải thích và điểm thi cuối kỳ, *y*, là biến phản hồi. Chúng ta sẽ vẽ một đường hồi quy "khớp" nhất với dữ liệu. Nếu mỗi bạn tự vẽ một đường thẳng "bằng mắt thường", các bạn sẽ vẽ ra những đường thẳng khác nhau. Chúng ta có thể sử dụng cái gọi là đường hồi quy bình phương tối thiểu để có được đường phù hợp nhất.

Consider the following diagram. Each point of data is of the the form (*x*, *y*) and each point of the line of best fit using least-squares linear regression has the form (*x*, *ŷ*).

Hãy xem xét sơ đồ sau. Mỗi điểm dữ liệu có dạng (*x*, *y*) và mỗi điểm của đường phù hợp nhất sử dụng hồi quy tuyến tính bình phương tối thiểu có dạng (*x*, *ŷ*).

The *ŷ* is read **"*y* hat"** and is the **estimated value of *y***. It is the value of *y* obtained using the regression line. It is not generally equal to *y* from data.

*ŷ* được đọc là **"*y* mũ"** và là **giá trị ước tính của *y***. Đó là giá trị của *y* thu được bằng cách sử dụng đường hồi quy. Nó thường không bằng với *y* từ dữ liệu.

*Figure 
12.10*

*Hình 
12.10*

The term *y*_0 – *ŷ*_0 = *ε*_0 is called the **"error" or** residual. It is not an error in the sense of a mistake. The absolute value of a residual measures the vertical distance between the actual value of *y* and the estimated value of *y*. In other words, it measures the vertical distance between the actual data point and the predicted point on the line.

Thuật ngữ *y*_0 – *ŷ*_0 = *ε*_0 được gọi là **"sai số" hoặc** phần dư. Đây không phải là sai số theo nghĩa là một lỗi sai. Giá trị tuyệt đối của phần dư đo lường khoảng cách thẳng đứng giữa giá trị thực tế của *y* và giá trị ước tính của *y*. Nói cách khác, nó đo lường khoảng cách thẳng đứng giữa điểm dữ liệu thực tế và điểm dự đoán trên đường thẳng.

If the observed data point lies above the line, the residual is positive, and the line underestimates the actual data value for *y*.  If the observed data point lies below the line, the residual is negative, and the line overestimates that actual data value for *y*.

Nếu điểm dữ liệu quan sát nằm phía trên đường thẳng, phần dư là dương, và đường thẳng đánh giá thấp giá trị dữ liệu thực tế cho *y*. Nếu điểm dữ liệu quan sát nằm phía dưới đường thẳng, phần dư là âm, và đường thẳng đánh giá quá cao giá trị dữ liệu thực tế đó cho *y*.

In the diagram in [Figure 12.10](12-3-the-regression-equation#linrgs_regeq2), *y*_0 – *ŷ*_0 = ε_0 is the residual for the point shown. Here the point lies above the line and the residual is positive.

Trong sơ đồ tại [Hình 12.10](12-3-the-regression-equation#linrgs_regeq2), *y*_0 – *ŷ*_0 = ε_0 là phần dư cho điểm được hiển thị. Ở đây điểm nằm phía trên đường thẳng và phần dư là dương.

*ε* = the Greek letter **epsilon**

*ε* = chữ cái Hy Lạp **epsilon**

For each data point, you can calculate the residuals or errors, *y*_i - *ŷ*_i = *ε*_i for *i* = 1, 2, 3, ..., 11.

Đối với mỗi điểm dữ liệu, bạn có thể tính toán các phần dư hoặc sai số, *y*_i - *ŷ*_i = *ε*_i cho *i* = 1, 2, 3, ..., 11.

Each |*ε*| is a vertical distance.

Mỗi |*ε*| là một khoảng cách thẳng đứng.

For the example about the third exam scores and the final exam scores for the 11 statistics students, there are 11 data points. Therefore, there are 11 *ε* values. If you square each ε and add, you get

Đối với ví dụ về điểm thi lần thứ ba và điểm thi cuối kỳ của 11 sinh viên thống kê, có 11 điểm dữ liệu. Do đó, có 11 giá trị *ε*. Nếu bạn bình phương mỗi ε và cộng lại, bạn sẽ có

This is called the Sum of Squared Errors (SSE).

Đây được gọi là Tổng bình phương sai số (SSE).

Using calculus, you can determine the values of *a* and *b* that make the **SSE** a minimum. When you make the **SSE** a
minimum, you have determined the points that are on the line of best fit. It turns out that
the line of best fit has the equation:

Sử dụng giải tích, bạn có thể xác định các giá trị của *a* và *b* làm cho **SSE** đạt cực tiểu. Khi bạn làm cho **SSE** đạt cực tiểu, bạn đã xác định được các điểm nằm trên đường phù hợp nhất. Hóa ra đường phù hợp nhất có phương trình:

where 

a=
y
¯

−b
x
¯

a=
y
¯

−b
x
¯

 and 

b=

Σ(x−
x
¯

)(y−
y
¯

)

Σ

(x−
x
¯

)

2

b=

Σ(x−
x
¯

)(y−
y
¯

)

Σ

(x−
x
¯

)

2

.

trong đó 

a=
y
¯

−b
x
¯

a=
y
¯

−b
x
¯

 và 

b=

Σ(x−
x
¯

)(y−
y
¯

)

Σ

(x−
x
¯

)

2

b=

Σ(x−
x
¯

)(y−
y
¯

)

Σ

(x−
x
¯

)

2

.

The sample means of the *x* values and the *y* values are 

x
¯

x
¯
 and 

y
¯

y
¯
, respectively. The best fit line always passes through the point 

(
x
¯

,
y
¯

)

(
x
¯

,
y
¯

)
.

Các giá trị trung bình mẫu của các giá trị *x* và các giá trị *y* lần lượt là 

x
¯

x
¯
 và 

y
¯

y
¯
. Đường phù hợp nhất luôn đi qua điểm 

(
x
¯

,
y
¯

)

(
x
¯

,
y
¯

)
.

The slope *b* can be written as 

b=r(

s
y

s
x

)

b=r(

s
y

s
x

)
 where *s*_*y* = the standard deviation of the *y* values and *s*_*x* = the standard deviation of the *x* values. *r* is the correlation
coefficient, which is discussed in the next section.

Hệ số góc *b* có thể được viết là 

b=r(

s
y

s
x

)

b=r(

s
y

s
x

)
 trong đó *s*_*y* = độ lệch chuẩn của các giá trị *y* và *s*_*x* = độ lệch chuẩn của các giá trị *x*. *r* là hệ số tương quan, được thảo luận trong phần tiếp theo.

### Residuals Plots

### Biểu đồ phần dư

A residuals plot can be used to help determine if a set of (*x*, *y*) data is linearly correlated. For each data point used to create the correlation line, a residual *y* - *ŷ* can be calculated, where y is the observed value of the response variable and *ŷ* is the value predicted by the correlation line. The difference between these values is called the residual. A residuals plot shows the explanatory variable *x* on the horizontal axis and the residual for that value on the vertical axis. The residuals plot is often shown together with a scatter plot of the data. While a scatter plot of the data should resemble a straight line, a residuals plot should appear random, with no pattern and no outliers. It should also show constant error variance, meaning the residuals should not consistently increase (or decrease) as the explanatory variable *x* increases.

Biểu đồ phần dư có thể được sử dụng để giúp xác định xem một tập dữ liệu (*x*, *y*) có tương quan tuyến tính hay không. Đối với mỗi điểm dữ liệu được sử dụng để tạo đường tương quan, một phần dư *y* - *ŷ* có thể được tính toán, trong đó y là giá trị quan sát được của biến phản hồi và *ŷ* là giá trị được dự đoán bởi đường tương quan. Sự khác biệt giữa các giá trị này được gọi là phần dư. Biểu đồ phần dư hiển thị biến giải thích *x* trên trục hoành và phần dư cho giá trị đó trên trục tung. Biểu đồ phần dư thường được hiển thị cùng với biểu đồ phân tán của dữ liệu. Trong khi biểu đồ phân tán của dữ liệu nên giống một đường thẳng, biểu đồ phần dư nên xuất hiện ngẫu nhiên, không có quy luật và không có giá trị ngoại lệ. Nó cũng nên cho thấy phương sai sai số không đổi, nghĩa là các phần dư không nên tăng (hoặc giảm) một cách nhất quán khi biến giải thích *x* tăng lên.

A residuals plot can be created using StatCrunch or a TI calculator. The plot should appear random. A box plot of the residuals is also helpful to verify that there are no outliers in the data. By observing the scatter plot of the data, the residuals plot, and the box plot of residuals, together with the linear correlation coefficient, we can usually determine if it is reasonable to conclude that the data are linearly correlated.

Biểu đồ phần dư có thể được tạo bằng StatCrunch hoặc máy tính TI. Biểu đồ sẽ xuất hiện ngẫu nhiên. Biểu đồ hộp của các phần dư cũng hữu ích để xác minh rằng không có giá trị ngoại lệ trong dữ liệu. Bằng cách quan sát biểu đồ phân tán của dữ liệu, biểu đồ phần dư và biểu đồ hộp của phần dư, cùng với hệ số tương quan tuyến tính, chúng ta thường có thể xác định xem liệu có hợp lý khi kết luận rằng dữ liệu có tương quan tuyến tính hay không.

#### EXAMPLE:

#### VÍ DỤ:

A shop owner uses a straight-line regression to estimate the number of ice cream cones that would be sold in a day based on the temperature at noon. The owner has data for a 2-year period and chose nine days at random. A scatter plot of the data is shown, together with a residuals plot.

Một chủ cửa hàng sử dụng hồi quy đường thẳng để ước tính số lượng ốc quế kem sẽ được bán trong một ngày dựa trên nhiệt độ vào buổi trưa. Chủ cửa hàng có dữ liệu trong khoảng thời gian 2 năm và đã chọn ngẫu nhiên chín ngày. Biểu đồ phân tán của dữ liệu được hiển thị, cùng với biểu đồ phần dư.

| Temperature ° F | Nhiệt độ ° F | Ice cream cones sold | Số kem ốc quế đã bán |
| --- | --- | --- | --- |
| 70 | 70 | 105 | 105 |
| 85 | 85 | 240 | 240 |
| 65 | 65 | 49 | 49 |
| 72 | 72 | 147 | 147 |
| 80 | 80 | 231 | 231 |
| 61 | 61 | 38 | 38 |
| 75 | 75 | 193 | 193 |
| 78 | 78 | 196 | 196 |
| 68 | 68 | 89 | 89 |

*Figure 
12.11
 
Scatter plot of the data looks like a straight line.*

*Hình 
12.11
 
Biểu đồ phân tán của dữ liệu trông giống như một đường thẳng.*

*Figure 
12.12
 
Residuals plot appears random.*

*Hình 
12.12
 
Biểu đồ phần dư có vẻ ngẫu nhiên.*

### Least Squares Criteria for Best Fit

### Tiêu chí bình phương tối thiểu cho sự phù hợp nhất

The process of fitting the best-fit line is called **linear regression**. The idea behind finding the best-fit line is based on the assumption that the data are scattered about a straight line. The criteria for the best fit line is that the sum of the squared errors (SSE) is minimized, that is, made as small as possible. Any other line you might choose would have a higher SSE than the best fit line. This best fit line is called the ** least-squares regression line **.

Quá trình khớp đường phù hợp nhất được gọi là **hồi quy tuyến tính**. Ý tưởng đằng sau việc tìm đường phù hợp nhất dựa trên giả định rằng dữ liệu được phân tán xung quanh một đường thẳng. Tiêu chí cho đường phù hợp nhất là tổng bình phương sai số (SSE) được cực tiểu hóa, nghĩa là làm cho nó nhỏ nhất có thể. Bất kỳ đường thẳng nào khác mà bạn chọn cũng sẽ có SSE cao hơn đường phù hợp nhất. Đường phù hợp nhất này được gọi là **đường hồi quy bình phương tối thiểu**.

Computer spreadsheets, statistical software, and many calculators can quickly calculate the best-fit line and create the graphs. The calculations tend to be tedious if done by hand. Instructions to use the TI-83, TI-83+, and TI-84+ calculators to find the best-fit line and create a scatterplot are shown at the end of this section.

Các bảng tính máy tính, phần mềm thống kê và nhiều máy tính có thể nhanh chóng tính toán đường phù hợp nhất và tạo biểu đồ. Các phép tính có xu hướng tẻ nhạt nếu thực hiện bằng tay. Hướng dẫn sử dụng máy tính TI-83, TI-83+ và TI-84+ để tìm đường phù hợp nhất và tạo biểu đồ phân tán được hiển thị ở cuối phần này.

THIRD EXAM vs FINAL EXAM EXAMPLE:
The graph of the line of best fit for the third-exam/final-exam example is as follows:

VÍ DỤ ĐIỂM THI LẦN THỨ BA vs ĐIỂM THI CUỐI KỲ:
Biểu đồ của đường phù hợp nhất cho ví dụ về điểm thi lần thứ ba/điểm thi cuối kỳ như sau:

*Figure 
12.13*

*Hình 
12.13*

The least squares regression line (best-fit line) for the third-exam/final-exam example has the equation:

Đường hồi quy bình phương tối thiểu (đường phù hợp nhất) cho ví dụ về điểm thi lần thứ ba/điểm thi cuối kỳ có phương trình:

Remember, it is always important to plot a scatter diagram first. If the scatter plot indicates that there is a linear relationship between the variables, then it is reasonable to use a best fit line to make predictions for *y* given *x* within the domain of *x*-values in the sample data, **but not necessarily for *x*-values outside that domain.** You could use the line to predict the final exam score for a student who earned a grade of 73 on the third exam. You should NOT use the line to predict the final exam score for a student who earned a grade of 50 on the third exam, because 50 is not within the domain of the *x*-values in the sample data, which are between 65 and 75.

Hãy nhớ rằng, việc vẽ biểu đồ phân tán trước tiên luôn quan trọng. Nếu biểu đồ phân tán chỉ ra rằng có mối quan hệ tuyến tính giữa các biến, thì việc sử dụng đường phù hợp nhất để đưa ra dự đoán cho *y* với *x* đã cho trong phạm vi của các giá trị *x* trong dữ liệu mẫu là hợp lý, **nhưng không nhất thiết cho các giá trị *x* nằm ngoài phạm vi đó.** Bạn có thể sử dụng đường thẳng để dự đoán điểm thi cuối kỳ cho một sinh viên đạt điểm 73 trong bài thi lần thứ ba. Bạn KHÔNG NÊN sử dụng đường thẳng để dự đoán điểm thi cuối kỳ cho một sinh viên đạt điểm 50 trong bài thi lần thứ ba, vì 50 không nằm trong phạm vi của các giá trị *x* trong dữ liệu mẫu, vốn nằm trong khoảng từ 65 đến 75.

### UNDERSTANDING SLOPE

### HIỂU VỀ HỆ SỐ GÓC

The slope of the line, *b*, describes how changes in the variables are related. It is important to interpret the slope of the line in the context of the situation represented by the data. You should be able to write a sentence interpreting the slope in plain English.

Hệ số góc của đường thẳng, *b*, mô tả cách các thay đổi trong các biến có liên quan với nhau. Điều quan trọng là phải giải thích hệ số góc của đường thẳng trong bối cảnh của tình huống được dữ liệu đại diện. Bạn sẽ có thể viết một câu giải thích hệ số góc bằng ngôn ngữ đơn giản.

**INTERPRETATION OF THE SLOPE:** The slope of the best-fit line tells us how the dependent variable (*y*) changes for every one unit increase in the independent (*x*) variable, on average.

**GIẢI THÍCH HỆ SỐ GÓC:** Hệ số góc của đường phù hợp nhất cho chúng ta biết biến phản hồi (*y*) thay đổi như thế nào cho mỗi đơn vị tăng lên của biến giải thích (*x*), tính trung bình.

THIRD EXAM vs FINAL EXAM EXAMPLESlope: The slope of the line is *b* = 4.83.

Interpretation: For a one-point increase in the score on the third exam, the final exam score increases by 4.83 points, on average.

VÍ DỤ ĐIỂM THI LẦN THỨ BA vs ĐIỂM THI CUỐI KỲHệ số góc: Hệ số góc của đường thẳng là *b* = 4,83.

Giải thích: Với mỗi một điểm tăng thêm trong bài thi lần thứ ba, điểm thi cuối kỳ tăng trung bình 4,83 điểm.

Using the Linear Regression `T Test: LinRegTTest`

Sử dụng Hồi quy tuyến tính `T Test: LinRegTTest`

1. In the `STAT` list editor, enter the X data in list `L1` and the Y data in list `L2`, paired so that the corresponding (*x*,*y*) values are next to each other in the lists. (If a particular pair of values is repeated, enter it as many times as it appears in the data.)
1. Trong trình chỉnh sửa danh sách `STAT`, hãy nhập dữ liệu X vào danh sách `L1` và dữ liệu Y vào danh sách `L2`, được ghép cặp sao cho các giá trị tương ứng (*x*,*y*) nằm cạnh nhau trong các danh sách. (Nếu một cặp giá trị cụ thể bị lặp lại, hãy nhập nó nhiều lần như số lần nó xuất hiện trong dữ liệu.)
1. On the `STAT TESTS` menu, scroll down with the cursor to select the `LinRegTTest`. (Be careful to select `LinRegTTest`, as some calculators may also have a different item called LinRegTInt.)
1. Trên menu `STAT TESTS`, hãy cuộn xuống bằng con trỏ để chọn `LinRegTTest`. (Hãy cẩn thận chọn `LinRegTTest`, vì một số máy tính có thể có một mục khác gọi là LinRegTInt.)
1. On the LinRegTTest input screen enter: Xlist: L1 ; Ylist: L2 ; Freq: 1
1. Trên màn hình nhập LinRegTTest, hãy nhập: Xlist: L1 ; Ylist: L2 ; Freq: 1
1. On the next line, at the prompt *β* or *ρ*, highlight "≠ 0" and press ENTER
1. Trên dòng tiếp theo, tại lời nhắc *β* hoặc *ρ*, hãy làm nổi bật "≠ 0" và nhấn ENTER
1. Leave the line for "RegEq:" blank
1. Để trống dòng "RegEq:"
1. Highlight Calculate and press ENTER.
1. Làm nổi bật Calculate và nhấn ENTER.
*Figure 
12.14*

*Hình 
12.14*

The output screen contains a lot of information. For now we will focus on a few items from the output, and will return later to the other items.

The second line says *y* = *a* + *bx*. Scroll down to find the values *a* = –173.513, and *b* = 4.8273; the equation of the best fit line is *ŷ* = –173.51 + 4.83*x*

The two items at the bottom are *r*_2 = 0.43969 and *r* = 0.663. For now, just note where to find these values; we will discuss them in the next two sections.

Màn hình đầu ra chứa rất nhiều thông tin. Hiện tại chúng ta sẽ tập trung vào một vài mục từ đầu ra, và sẽ quay lại các mục khác sau.

Dòng thứ hai cho biết *y* = *a* + *bx*. Cuộn xuống để tìm các giá trị *a* = –173,513, và *b* = 4,8273; phương trình của đường phù hợp nhất là *ŷ* = –173,51 + 4,83*x*

Hai mục ở dưới cùng là *r*_2 = 0,43969 và *r* = 0,663. Hiện tại, chỉ cần lưu ý nơi tìm các giá trị này; chúng ta sẽ thảo luận về chúng trong hai phần tiếp theo.

Graphing the Scatterplot and Regression Line

Vẽ biểu đồ phân tán và đường hồi quy

1. We are assuming your X data is already entered in list L1 and your Y data is in list L2
1. Chúng ta đang giả định rằng dữ liệu X của bạn đã được nhập vào danh sách L1 và dữ liệu Y của bạn nằm trong danh sách L2
1. Press 2nd STATPLOT ENTER to use Plot 1
1. Nhấn 2nd STATPLOT ENTER để sử dụng Plot 1
1. On the input screen for PLOT 1, highlight **On**, and press ENTER
1. Trên màn hình nhập cho PLOT 1, hãy làm nổi bật **On** và nhấn ENTER
1. For TYPE: highlight the very first icon which is the scatterplot and press ENTER
1. Đối với TYPE: hãy làm nổi bật biểu tượng đầu tiên là biểu đồ phân tán (scatterplot) và nhấn ENTER
1. Indicate Xlist: L1 and Ylist: L2
1. Chỉ định Xlist: L1 và Ylist: L2
1. For Mark: it does not matter which symbol you highlight.
1. Đối với Mark: việc bạn làm nổi bật biểu tượng nào không quan trọng.
1. Press the ZOOM key and then the number 9 (for menu item "ZoomStat") ; the calculator will fit the window to the data
1. Nhấn phím ZOOM và sau đó là số 9 (cho mục menu "ZoomStat"); máy tính sẽ điều chỉnh cửa sổ cho phù hợp với dữ liệu
1. To graph the best-fit line, press the "Y=" key and type the equation –173.5 + 4.83X into equation Y1. (The X key is immediately left of the STAT key). Press ZOOM 9 again to graph it.
1. Để vẽ đường phù hợp nhất, nhấn phím "Y=" và nhập phương trình –173.5 + 4.83X vào phương trình Y1. (Phím X nằm ngay bên trái phím STAT). Nhấn ZOOM 9 lần nữa để vẽ đồ thị.
1. Optional: If you want to change the viewing window, press the WINDOW key.  Enter your desired window using Xmin, Xmax, Ymin, Ymax
1. Tùy chọn: Nếu bạn muốn thay đổi cửa sổ xem, nhấn phím WINDOW. Nhập cửa sổ mong muốn của bạn bằng cách sử dụng Xmin, Xmax, Ymin, Ymax
Another way to graph the line after you create a scatter plot is to use LinRegTTest.

Một cách khác để vẽ đường thẳng sau khi bạn tạo biểu đồ phân tán là sử dụng LinRegTTest.

1. Make sure you have done the scatter plot. Check it on your screen.
1. Đảm bảo rằng bạn đã thực hiện biểu đồ phân tán. Kiểm tra nó trên màn hình của bạn.
1. Go to LinRegTTest and enter the lists.
1. Đi đến LinRegTTest và nhập các danh sách.
1. At RegEq: press VARS and arrow over to Y-VARS. Press 1 for 1:Function. Press 1 for 1:Y1. Then arrow down to Calculate and do the calculation for the line of best fit.
1. Tại RegEq: nhấn VARS và di chuyển mũi tên sang Y-VARS. Nhấn 1 cho 1:Function. Nhấn 1 cho 1:Y1. Sau đó di chuyển mũi tên xuống Calculate và thực hiện tính toán cho đường phù hợp nhất.
1. Press Y = (you will see the regression equation).
1. Nhấn Y = (bạn sẽ thấy phương trình hồi quy).
1. Press GRAPH. The line will be drawn."
1. Nhấn GRAPH. Đường thẳng sẽ được vẽ."
### The Correlation Coefficient *r*

### Hệ số tương quan *r*

Besides looking at the scatter plot and seeing that a line seems reasonable, how can you tell if the line is a good predictor? Use the correlation coefficient as another indicator (besides the scatterplot) of the strength of the relationship between *x* and *y*.

Ngoài việc nhìn vào biểu đồ phân tán và thấy rằng một đường thẳng có vẻ hợp lý, làm thế nào bạn có thể biết liệu đường thẳng đó có phải là một công cụ dự đoán tốt hay không? Sử dụng hệ số tương quan như một chỉ báo khác (ngoài biểu đồ phân tán) về độ mạnh của mối quan hệ giữa *x* và *y*.

The **correlation coefficient, *r*, ** developed by Karl Pearson in the early 1900s, is numerical and provides a measure of strength and direction of the linear association between the independent variable *x* and the dependent variable *y*.

**Hệ số tương quan, *r*, ** được Karl Pearson phát triển vào đầu những năm 1900, là một giá trị số cung cấp thước đo về độ mạnh và hướng của mối liên hệ tuyến tính giữa biến độc lập *x* và biến phụ thuộc *y*.

The correlation coefficient is calculated as

Hệ số tương quan được tính như sau

where *n* = the number of data points.

trong đó *n* = số lượng điểm dữ liệu.

If you suspect a linear relationship between *x* and *y*, then *r* can measure how strong the linear relationship is.

Nếu bạn nghi ngờ có một mối quan hệ tuyến tính giữa *x* và *y*, thì *r* có thể đo lường mức độ mạnh mẽ của mối quan hệ tuyến tính đó.

What the VALUE of *r* tells us:

GIÁ TRỊ của *r* cho chúng ta biết điều gì:

- The value of *r* is always between –1 and +1: –1 ≤ *r* ≤ 1.
- Giá trị của *r* luôn nằm trong khoảng từ –1 đến +1: –1 ≤ *r* ≤ 1.
- The size of the correlation *r* indicates the strength of the linear relationship between *x* and *y*. Values of *r* close to –1 or to +1 indicate a stronger linear relationship between *x* and *y*.
- Kích thước của hệ số tương quan *r* cho biết độ mạnh của mối quan hệ tuyến tính giữa *x* và *y*. Các giá trị của *r* gần bằng –1 hoặc +1 cho thấy mối quan hệ tuyến tính mạnh hơn giữa *x* và *y*.
- If *r* = 0 there is likely no linear correlation. It is important to view the scatterplot, however, because data that exhibit a curved or horizontal pattern may have a correlation of 0.
- Nếu *r* = 0 thì có khả năng không có tương quan tuyến tính. Tuy nhiên, điều quan trọng là phải xem biểu đồ phân tán, vì dữ liệu thể hiện mô hình cong hoặc nằm ngang có thể có hệ số tương quan bằng 0.
- If *r* = 1, there is perfect positive correlation. If *r* = –1, there is perfect negative correlation. In both these cases, all of the original data points lie on a straight line. Of course,in the real world, this will not generally happen.
- Nếu *r* = 1, có tương quan thuận hoàn hảo. Nếu *r* = –1, có tương quan nghịch hoàn hảo. Trong cả hai trường hợp này, tất cả các điểm dữ liệu gốc đều nằm trên một đường thẳng. Tất nhiên, trong thế giới thực, điều này thường sẽ không xảy ra.
What the SIGN of *r* tells us

DẤU của *r* cho chúng ta biết điều gì

- A positive value of *r* means that when *x* increases, *y* tends to increase and when *x* decreases, *y* tends to decrease **(positive correlation)**.
- Giá trị dương của *r* có nghĩa là khi *x* tăng, *y* có xu hướng tăng và khi *x* giảm, *y* có xu hướng giảm **(tương quan thuận)**.
- A negative value of *r* means that when *x* increases, *y* tends to decrease and when *x* decreases, *y* tends to increase **(negative correlation)**.
- Giá trị âm của *r* có nghĩa là khi *x* tăng, *y* có xu hướng giảm và khi *x* giảm, *y* có xu hướng tăng **(tương quan nghịch)**.
- The sign of *r* is the same as the sign of the slope, *b*, of the best-fit line.
- Dấu của *r* giống với dấu của hệ số góc, *b*, của đường phù hợp nhất.
*Figure 
12.15
 
(a) A scatter plot showing data with a positive correlation. 0 < *r* < 1 (b) A scatter plot showing data with a negative correlation. –1 < *r* < 0 (c) A scatter plot showing data with zero correlation. *r* = 0*

*Hình 
12.15
 
(a) Biểu đồ phân tán hiển thị dữ liệu có tương quan dương. 0 < *r* < 1 (b) Biểu đồ phân tán hiển thị dữ liệu có tương quan âm. –1 < *r* < 0 (c) Biểu đồ phân tán hiển thị dữ liệu có tương quan bằng không. *r* = 0*

The formula for *r* looks formidable. However, computer spreadsheets, statistical software, and many calculators can quickly calculate *r*. The correlation coefficient *r* is the bottom item in the output screens for the LinRegTTest on the TI-83, TI-83+, or TI-84+ calculator (see previous section for instructions).

Công thức cho *r* trông có vẻ đáng sợ. Tuy nhiên, các bảng tính trên máy tính, phần mềm thống kê và nhiều máy tính cầm tay có thể nhanh chóng tính toán *r*. Hệ số tương quan *r* là mục cuối cùng trên màn hình kết quả của LinRegTTest trên máy tính TI-83, TI-83+ hoặc TI-84+ (xem phần trước để biết hướng dẫn).

### The Coefficient of Determination

### Hệ số xác định

**The variable *r*^2 is called the** coefficient of determination and is the square of the correlation coefficient, but is usually stated as a percent, rather than in decimal form. It has an interpretation in the context of the data:

**Biến *r*^2 được gọi là** hệ số xác định và là bình phương của hệ số tương quan, nhưng thường được biểu thị dưới dạng phần trăm thay vì dạng thập phân. Nó có một cách giải thích trong bối cảnh của dữ liệu:

- r
2

r
2
, when expressed as a percent, represents the percent of variation in the dependent (predicted) variable *y* that can be explained by variation in the independent (explanatory) variable *x* using the regression (best-fit) line.
- r
2

r
2
, khi được biểu thị dưới dạng phần trăm, đại diện cho phần trăm biến thiên của biến phụ thuộc (được dự đoán) *y* có thể được giải thích bằng biến thiên của biến độc lập (giải thích) *x* sử dụng đường hồi quy (phù hợp nhất).
- 1 – 
r
2

r
2
, when expressed as a percentage, represents the percent of variation in *y* that is NOT explained by variation in *x* using the regression line. This can be seen as the scattering of the observed data points about the regression line.
- 1 – 
r
2

r
2
, khi được biểu thị dưới dạng phần trăm, đại diện cho phần trăm biến thiên của *y* KHÔNG được giải thích bằng biến thiên của *x* sử dụng đường hồi quy. Điều này có thể được xem là sự phân tán của các điểm dữ liệu quan sát được xung quanh đường hồi quy.
Consider the [third exam/final exam example](12-3-the-regression-equation#element-22) introduced in the previous section

Hãy xem xét [ví dụ về bài thi thứ ba/bài thi cuối kỳ](12-3-the-regression-equation#element-22) đã được giới thiệu trong phần trước

- The line of best fit is: *ŷ* = –173.51 + 4.83x
- Đường phù hợp nhất là: *ŷ* = –173.51 + 4.83x
- The correlation coefficient is *r* = 0.6631
- Hệ số tương quan là *r* = 0.6631
- The coefficient of determination is *r*^2 = 0.6631^2 = 0.4397
- Hệ số xác định là *r*^2 = 0.6631^2 = 0.4397
- **Interpretation of *r*^2 in the context of this example:**
- **Giải thích về *r*^2 trong bối cảnh của ví dụ này:**
- Approximately 44% of the variation (0.4397 is approximately 0.44) in the final-exam grades can be explained by the variation in the grades on the third exam, using the best-fit regression line.
- Khoảng 44% biến thiên (0.4397 xấp xỉ 0.44) trong điểm thi cuối kỳ có thể được giải thích bằng biến thiên trong điểm thi của bài thi thứ ba, sử dụng đường hồi quy phù hợp nhất.
- Therefore, approximately 56% of the variation (1 – 0.44 = 0.56) in the final exam grades can NOT be explained by the variation in the grades on the third exam, using the best-fit regression line. (This is seen as the scattering of the points about the line.)
- Do đó, khoảng 56% biến thiên (1 – 0.44 = 0.56) trong điểm thi cuối kỳ KHÔNG thể được giải thích bằng biến thiên trong điểm thi của bài thi thứ ba, sử dụng đường hồi quy phù hợp nhất. (Điều này được thấy qua sự phân tán của các điểm xung quanh đường thẳng.)
