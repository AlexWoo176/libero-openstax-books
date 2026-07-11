*Figure 
5.1
 
The heights of these radish plants are continuous random variables. (credit: modification of work “Radish (Raphanus sativus): White rust caused by Albugo candida” by Scot Nelson/ Flickr, Public Domain)*

*Hình 
5.1
 
Chiều cao của những cây củ cải này là các biến ngẫu nhiên liên tục. (nguồn: sửa đổi từ tác phẩm “Củ cải (Raphanus sativus): Bệnh gỉ trắng do Albugo candida gây ra” bởi Scot Nelson/ Flickr, Phạm vi công cộng)*

By the end of this chapter, the student should be able to:

Đến cuối chương này, sinh viên sẽ có thể:

- Recognize and understand continuous probability density functions in general.
- Nhận biết và hiểu các hàm mật độ xác suất liên tục nói chung.
- Recognize the uniform probability distribution and apply it appropriately.
- Nhận biết phân phối xác suất đều và áp dụng nó một cách thích hợp.
- Recognize the exponential probability distribution and apply it appropriately.
- Nhận biết phân phối xác suất mũ và áp dụng nó một cách thích hợp.
## Introduction

## Giới thiệu

Continuous random variables have many applications. Baseball batting averages, IQ scores, the length of time a long distance telephone call lasts, the amount of money a person carries, the length of time a computer chip lasts, and SAT scores are just a few. The field of reliability depends on a variety of continuous random variables.

Các biến ngẫu nhiên liên tục có nhiều ứng dụng. Số trung bình lượt đánh bóng trong môn bóng chày, điểm IQ, khoảng thời gian của một cuộc gọi đường dài, số tiền một người mang theo, khoảng thời gian hoạt động của một con chip máy tính và điểm SAT chỉ là một vài ví dụ. Lĩnh vực độ tin cậy phụ thuộc vào nhiều loại biến ngẫu nhiên liên tục khác nhau.

The values of discrete and continuous random variables can be ambiguous. For example, if *X* is equal to the number of miles (to the nearest mile) you drive to work, then *X* is a discrete random variable. You count the miles. If *X* is the distance you drive to work, then you measure values of *X* and *X* is a continuous random variable. For a second example, if *X* is equal to the number of books in a backpack, then *X* is a discrete random variable. If *X* is the weight of a book, then *X* is a continuous random variable because weights are measured. How the random variable is defined is very important.

Các giá trị của biến ngẫu nhiên rời rạc và liên tục có thể gây nhầm lẫn. Ví dụ, nếu *X* bằng số dặm (làm tròn đến dặm gần nhất) bạn lái xe đi làm, thì *X* là một biến ngẫu nhiên rời rạc. Bạn đếm số dặm. Nếu *X* là khoảng cách bạn lái xe đi làm, thì bạn đo các giá trị của *X* và *X* là một biến ngẫu nhiên liên tục. Ví dụ thứ hai, nếu *X* bằng số lượng sách trong ba lô, thì *X* là một biến ngẫu nhiên rời rạc. Nếu *X* là trọng lượng của một cuốn sách, thì *X* là một biến ngẫu nhiên liên tục vì trọng lượng được đo lường. Cách xác định biến ngẫu nhiên là rất quan trọng.

### Properties of Continuous Probability Distributions

### Các tính chất của phân phối xác suất liên tục

The graph of a continuous probability distribution is a curve. Probability is represented by area under the curve.

Đồ thị của một phân phối xác suất liên tục là một đường cong. Xác suất được biểu diễn bằng diện tích dưới đường cong đó.

The curve is called the probability density function (abbreviated as **pdf**). We use the symbol *f*(*x*) to represent the curve. *f*(*x*) is the function that corresponds to the graph; we use the density function *f*(*x*) to draw the graph of the probability distribution.

Đường cong này được gọi là Hàm mật độ xác suất (viết tắt là **pdf**). Chúng ta sử dụng ký hiệu *f*(*x*) để biểu diễn đường cong này. *f*(*x*) là hàm số tương ứng với đồ thị; chúng ta sử dụng hàm mật độ *f*(*x*) để vẽ đồ thị của phân phối xác suất.

**Area under the curve** is given by a different function called the  **cumulative distribution function ** (abbreviated as **cdf**). The cumulative distribution function is used to evaluate probability as area.

**Diện tích dưới đường cong** được cho bởi một hàm số khác gọi là **hàm phân phối tích lũy** (viết tắt là **cdf**). Hàm phân phối tích lũy được sử dụng để đánh giá xác suất dưới dạng diện tích.

- The outcomes are measured, not counted.
- Các kết quả được đo lường, không phải đếm.
- The entire area under the curve and above the x-axis is equal to one.
- Toàn bộ diện tích bên dưới đường cong và phía trên trục x bằng một.
- Probability is found for intervals of *x* values rather than for individual *x* values.
- Xác suất được tìm thấy cho các khoảng của các giá trị *x* thay vì cho các giá trị *x* riêng lẻ.
- *P(c < x < d)* is the probability that the random variable *X* is in the interval between the values *c* and *d*. *P(c < x < d)* is the area under the curve, above the *x*-axis, to the right of *c* and the left of *d*.
- *P(c < x < d)* là xác suất mà biến ngẫu nhiên *X* nằm trong khoảng giữa các giá trị *c* và *d*. *P(c < x < d)* là diện tích bên dưới đường cong, phía trên trục *x*, nằm bên phải *c* và bên trái *d*.
- *P(x = c) =* 0 The probability that *x* takes on any single individual value is zero. The area below the curve, above the *x*-axis, and between *x* = *c* and *x* = *c* has no width, and therefore no area (area = 0). Since the probability is equal to the area, the probability is also zero.
- *P(x = c) =* 0 Xác suất để *x* nhận bất kỳ giá trị riêng lẻ nào bằng không. Diện tích bên dưới đường cong, phía trên trục *x*, và giữa *x* = *c* và *x* = *c* không có chiều rộng, và do đó không có diện tích (diện tích = 0). Vì xác suất bằng với diện tích, nên xác suất cũng bằng không.
- *P(c < x < d)* is the same as *P(c ≤ x ≤ d)* because probability is equal to area.
- *P(c < x < d)* cũng giống như *P(c ≤ x ≤ d)* vì xác suất bằng với diện tích.
We will find the area that represents probability by using geometry, formulas, technology, or probability tables.  In general, calculus is needed to find the area under the curve for many probability density functions.  When we use formulas to find the area in this textbook, the formulas were found by using the techniques of integral calculus.  However, because most students taking this course have not studied calculus, we will not be using calculus in this textbook.

Chúng ta sẽ tìm diện tích biểu diễn xác suất bằng cách sử dụng hình học, công thức, công nghệ hoặc bảng xác suất. Nhìn chung, cần phải có giải tích để tìm diện tích dưới đường cong cho nhiều hàm mật độ xác suất. Khi chúng ta sử dụng các công thức để tìm diện tích trong giáo trình này, các công thức đó đã được tìm ra bằng cách sử dụng các kỹ thuật của giải tích tích phân. Tuy nhiên, vì hầu hết sinh viên theo học khóa học này chưa học giải tích, chúng ta sẽ không sử dụng giải tích trong giáo trình này.

There are many continuous probability distributions. When using a continuous probability distribution to model probability, the distribution used is selected to model and fit the particular situation in the best way.

Có rất nhiều phân phối xác suất liên tục. Khi sử dụng một phân phối xác suất liên tục để mô hình hóa xác suất, phân phối được chọn phải phù hợp để mô hình hóa và khớp với tình huống cụ thể theo cách tốt nhất.

In this chapter and the next, we will study the uniform distribution, the exponential distribution, and the normal distribution. The following graphs illustrate these distributions.

Trong chương này và chương tiếp theo, chúng ta sẽ nghiên cứu phân phối đều, phân phối mũ và phân phối chuẩn. Các đồ thị sau đây minh họa các phân phối này.

*Figure 
5.2
 
The graph shows a Uniform Distribution with the area between *x* = 3 and *x* = 6 shaded to represent the probability that the value of the random variable *X* is in the interval between three and six.*

*Hình 
5.2
 
Biểu đồ hiển thị Phân phối đều với diện tích giữa *x* = 3 và *x* = 6 được tô bóng để biểu thị xác suất mà giá trị của biến ngẫu nhiên *X* nằm trong khoảng từ ba đến sáu.*

*Figure 
5.3
 
The graph shows an Exponential Distribution with the area between *x* = 2 and *x* = 4 shaded to represent the probability that the value of the random variable *X* is in the interval between two and four.*

*Hình 
5.3
 
Biểu đồ hiển thị Phân phối mũ với diện tích giữa *x* = 2 và *x* = 4 được tô bóng để biểu thị xác suất mà giá trị của biến ngẫu nhiên *X* nằm trong khoảng từ hai đến bốn.*

*Figure 
5.4
 
The graph shows the Standard Normal Distribution with the area between *x* = 1 and *x* = 2 shaded to represent the probability that the value of the random variable *X* is in the interval between one and two.*

*Hình 
5.4
 
Biểu đồ hiển thị Phân phối chuẩn tắc với diện tích giữa *x* = 1 và *x* = 2 được tô bóng để biểu thị xác suất mà giá trị của biến ngẫu nhiên *X* nằm trong khoảng từ một đến hai.*
