## 12.2
 
Scatter Plots

## 12.2
 
Biểu đồ phân tán

Before we take up the discussion of linear regression and correlation, we need to examine a way to display the relation between two variables *x* and *y*. The most common and easiest way is a **scatter plot**. The following example illustrates a scatter plot.

Trước khi chúng ta thảo luận về hồi quy tuyến tính và tương quan, chúng ta cần xem xét một cách để hiển thị mối quan hệ giữa hai biến *x* và *y*. Cách phổ biến và dễ dàng nhất là **biểu đồ phân tán**. Ví dụ sau đây minh họa một biểu đồ phân tán.

An educational researcher collects data on the vocabulary size of children as a function of age. The data is shown in Table 12.1. Is there a relationship between age and vocabulary size for young children? Construct a scatter plot. Let *x* = Child’s Age, and let *y* = Vocabulary Size.

Một nhà nghiên cứu giáo dục thu thập dữ liệu về vốn từ vựng của trẻ em theo độ tuổi. Dữ liệu được hiển thị trong Bảng 12.1. Có mối quan hệ nào giữa độ tuổi và vốn từ vựng ở trẻ nhỏ không? Hãy xây dựng một biểu đồ phân tán. Cho *x* = Độ tuổi của trẻ, và cho *y* = Vốn từ vựng.

| Age (years) | Độ tuổi (năm) | Vocabulary Size (number of words) | Vốn từ vựng (số lượng từ) |
| --- | --- | --- | --- |
| 3 | 3 | 655 | 655 |
| 4 | 4 | 1098 | 1098 |
| 6 | 6 | 2463 | 2463 |
| 7 | 7 | 3195 | 3195 |

*Figure 
12.5*

*Hình 
12.5*

1. Enter your X data into list L1 and your Y data into list L2.
1. Nhập dữ liệu X của bạn vào danh sách L1 và dữ liệu Y của bạn vào danh sách L2.
1. Press 2nd `STATPLOT ENTER` to use Plot 1.  On the input screen for PLOT 1, highlight On and press `ENTER`. (Make sure the other plots are OFF.)
1. Nhấn 2nd `STATPLOT ENTER` để sử dụng Plot 1. Trên màn hình nhập liệu cho PLOT 1, hãy làm nổi bật On và nhấn `ENTER`. (Đảm bảo các biểu đồ khác đang ở chế độ OFF.)
1. For TYPE: highlight the very first icon, which is the scatter plot, and press `ENTER`.
1. Đối với TYPE: hãy làm nổi bật biểu tượng đầu tiên, đó là biểu đồ phân tán, và nhấn `ENTER`.
1. For Xlist:, enter `L1` ENTER and for Ylist: `L2` ENTER.
1. Đối với Xlist:, nhập `L1` ENTER và đối với Ylist: `L2` ENTER.
1. For Mark: it does not matter which symbol you highlight, but the square is the easiest to see. Press `ENTER`.
1. Đối với Mark: không quan trọng bạn làm nổi bật biểu tượng nào, nhưng hình vuông là dễ nhìn nhất. Nhấn `ENTER`.
1. Make sure there are no other equations that could be plotted.  Press Y = and clear any equations out.
1. Đảm bảo không có phương trình nào khác có thể được vẽ. Nhấn Y = và xóa sạch mọi phương trình.
1. Press the `ZOOM` key and then the number 9 (for menu item "ZoomStat") ; the calculator will fit the window to the data.  You can press WINDOW to see the scaling of the axes.
1. Nhấn phím `ZOOM` và sau đó là số 9 (cho mục menu "ZoomStat"); máy tính sẽ điều chỉnh cửa sổ cho phù hợp với dữ liệu. Bạn có thể nhấn WINDOW để xem tỷ lệ của các trục.
Amelia plays basketball for her high school. She wants to improve to play at the college level. She notices that the number of points she scores in a game goes up in response to the number of hours she practices her jump shot each week. She records the following data:

Amelia chơi bóng rổ cho trường trung học của cô ấy. Cô ấy muốn cải thiện kỹ năng để chơi ở cấp đại học. Cô ấy nhận thấy rằng số điểm cô ghi được trong một trận đấu tăng lên tương ứng với số giờ cô luyện tập cú ném nhảy mỗi tuần. Cô ấy ghi lại dữ liệu sau:

| *X* (hours practicing jump shot) | *X* (giờ luyện tập cú ném nhảy) | *Y* (points scored in a game) | *Y* (số điểm ghi được trong một trận đấu) |
| --- | --- | --- | --- |
| 5 | 5 | 15 | 15 |
| 7 | 7 | 22 | 22 |
| 9 | 9 | 28 | 28 |
| 10 | 10 | 31 | 31 |
| 11 | 11 | 33 | 33 |
| 12 | 12 | 36 | 36 |

Construct a scatter plot and state if what Amelia thinks appears to be true.

Hãy xây dựng một biểu đồ phân tán và cho biết liệu những gì Amelia nghĩ có vẻ đúng hay không.

A scatter plot shows the **direction** of a relationship between the variables. A clear direction happens when there is either:

Biểu đồ phân tán cho thấy **hướng** của mối quan hệ giữa các biến. Một hướng rõ ràng xảy ra khi có một trong hai trường hợp sau:

- High values of one variable occurring with high values of the other variable or low values of one variable occurring with low values of the other variable.
- Các giá trị cao của một biến xảy ra cùng với các giá trị cao của biến kia hoặc các giá trị thấp của một biến xảy ra cùng với các giá trị thấp của biến kia.
- High values of one variable occurring with low values of the other variable.
- Các giá trị cao của một biến xảy ra cùng với các giá trị thấp của biến kia.
You can determine the **strength** of the relationship by looking at the scatter plot and seeing how close the points are to a line, a power function, an exponential function,
or to some other type of function.  For a linear relationship there is an exception. Consider a scatter plot where all the points fall on a horizontal line providing a "perfect fit." The horizontal line would in fact show no relationship.

Bạn có thể xác định **độ mạnh** của mối quan hệ bằng cách nhìn vào biểu đồ phân tán và xem các điểm gần với một đường thẳng, một hàm lũy thừa, một hàm mũ, hoặc một loại hàm số nào khác như thế nào. Đối với mối quan hệ tuyến tính, có một ngoại lệ. Hãy xem xét một biểu đồ phân tán nơi tất cả các điểm nằm trên một đường nằm ngang, tạo ra một "sự khớp hoàn hảo". Đường nằm ngang thực tế sẽ cho thấy không có mối quan hệ nào.

When you look at a scatterplot, you want to notice the **overall pattern** and any **deviations** from the pattern. The following scatterplot examples illustrate these concepts.

Khi bạn nhìn vào một biểu đồ phân tán, bạn nên chú ý đến **mô hình tổng thể** và bất kỳ **độ lệch** nào so với mô hình đó. Các ví dụ về biểu đồ phân tán sau đây minh họa các khái niệm này.

*Figure 
12.6*

*Hình 
12.6*

*Figure 
12.7*

*Hình 
12.7*

*Figure 
12.8*

*Hình 
12.8*

In this chapter, we are interested in scatter plots that show a linear pattern. Linear patterns are quite common. The linear relationship is strong if the points are close to a straight line,  except in the case of a horizontal line where there is no relationship. If we think that the points show a linear relationship, we would like to draw a line on the scatter plot. This line can be calculated through a process called linear regression. However, we only calculate a regression line if one of the variables helps to explain or predict the other variable. If *x* is the independent variable and *y* the dependent variable,
then we can use a regression line to predict *y* for a given value of *x*

Trong chương này, chúng ta quan tâm đến các biểu đồ phân tán cho thấy mô hình tuyến tính. Các mô hình tuyến tính khá phổ biến. Mối quan hệ tuyến tính là mạnh nếu các điểm gần với một đường thẳng, ngoại trừ trường hợp đường nằm ngang nơi không có mối quan hệ nào. Nếu chúng ta nghĩ rằng các điểm cho thấy một mối quan hệ tuyến tính, chúng ta muốn vẽ một đường thẳng trên biểu đồ phân tán. Đường thẳng này có thể được tính toán thông qua một quy trình gọi là hồi quy tuyến tính. Tuy nhiên, chúng ta chỉ tính toán đường hồi quy nếu một trong các biến giúp giải thích hoặc dự đoán biến kia. Nếu *x* là biến độc lập và *y* là biến phụ thuộc, thì chúng ta có thể sử dụng đường hồi quy để dự đoán *y* cho một giá trị cho trước của *x*.
