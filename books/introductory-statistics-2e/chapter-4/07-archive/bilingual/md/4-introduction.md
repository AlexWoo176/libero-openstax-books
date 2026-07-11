*Figure 
4.1
 
You can use probability and discrete random variables to calculate the likelihood of lightning striking the ground five times during a half-hour thunderstorm. (credit: modification of work “CG lightning strike” by Axel Rouvin/ Flickr, CC BY 2.0)*

*Hình 
4.1
 
Bạn có thể sử dụng xác suất và biến ngẫu nhiên rời rạc để tính toán khả năng sét đánh xuống mặt đất năm lần trong một trận giông bão kéo dài nửa giờ. (nguồn: chỉnh sửa từ tác phẩm “CG lightning strike” của Axel Rouvin/ Flickr, CC BY 2.0)*

By the end of this chapter, the student should be able to:

Đến cuối chương này, sinh viên sẽ có thể:

- Recognize and understand discrete probability distribution functions, in general.
- Nhận biết và hiểu các hàm phân phối xác suất rời rạc nói chung.
- Calculate and interpret expected values.
- Tính toán và diễn giải các giá trị kỳ vọng.
- Recognize the binomial probability distribution and apply it appropriately.
- Nhận biết phân phối xác suất nhị thức và áp dụng nó một cách phù hợp.
- Recognize the Poisson probability distribution and apply it appropriately.
- Nhận biết phân phối xác suất Poisson và áp dụng nó một cách phù hợp.
- Recognize the geometric probability distribution and apply it appropriately.
- Nhận diện phân phối hình học và áp dụng nó một cách thích hợp.
- Recognize the hypergeometric probability distribution and apply it appropriately.
- Nhận diện phân phối xác suất siêu bội và áp dụng nó một cách thích hợp.
- Classify discrete word problems by their distributions.
- Phân loại các bài toán đố rời rạc theo phân phối của chúng.
## Introduction

## Giới thiệu

A student takes a ten-question, true-false quiz. Because the student had such a busy schedule, they could not study and guesses randomly at each answer. What is the probability of the student passing the test with at least a 70%?

Một sinh viên làm một bài kiểm tra trắc nghiệm đúng-sai gồm mười câu hỏi. Vì lịch trình quá bận rộn, sinh viên đó không thể học bài và đoán ngẫu nhiên mỗi câu trả lời. Xác suất để sinh viên đó vượt qua bài kiểm tra với ít nhất 70% là bao nhiêu?

The manager of an auto dealership might be interested in the color preferences for new car buyers. Suppose on average the dealership sells 20 cars per month. What is the probability that a customer prefers red cars?

Người quản lý một đại lý ô tô có thể quan tâm đến sở thích màu sắc của những người mua xe mới. Giả sử trung bình đại lý bán được 20 chiếc xe mỗi tháng. Xác suất để một khách hàng thích xe màu đỏ là bao nhiêu?

These two examples illustrate two different types of probability problems involving discrete random variables. Recall that discrete data are data that you can count. A random variable describes the outcomes of a statistical experiment in words. The values of a random variable can vary with each repetition of an experiment.

Hai ví dụ này minh họa hai loại bài toán xác suất khác nhau liên quan đến các biến ngẫu nhiên rời rạc. Hãy nhớ rằng dữ liệu rời rạc là dữ liệu mà bạn có thể đếm được. Một Biến ngẫu nhiên mô tả các kết quả của một phép thử thống kê bằng lời. Các giá trị của một biến ngẫu nhiên có thể thay đổi theo mỗi lần lặp lại phép thử.

### Random Variable Notation

### Ký hiệu biến ngẫu nhiên

Upper case letters such as *X* or *Y* denote a random variable. Lower case letters like *x* or *y* denote the value of a random variable. If  ***X* is a random variable, then *X* is written in words, and *x* is given as a number.**

Các chữ cái in hoa như *X* hoặc *Y* biểu thị một biến ngẫu nhiên. Các chữ cái thường như *x* hoặc *y* biểu thị giá trị của một biến ngẫu nhiên. Nếu ***X* là một biến ngẫu nhiên, thì *X* được viết bằng lời, và *x* được đưa ra dưới dạng một con số.**

For example, let *X* = the number of heads you get when you toss three fair coins. The sample space for the toss of three fair coins is *TTT*; *THH*; *HTH*; *HHT*; *HTT*; *THT*; *TTH*; *HHH*. Then, *x* = 0, 1, 2, 3. *X* is in words and *x* is a number. Notice that for this example, the *x* values are countable outcomes. Because you can count the possible values that *X* can take on and the outcomes are random (the *x* values 0, 1, 2, 3), *X* is a discrete random variable.

Ví dụ, gọi *X* = số mặt ngửa bạn nhận được khi tung ba đồng xu cân đối. Không gian mẫu cho việc tung ba đồng xu cân đối là *TTT*; *THH*; *HTH*; *HHT*; *HTT*; *THT*; *TTH*; *HHH*. Khi đó, *x* = 0, 1, 2, 3. *X* được viết bằng lời và *x* là một con số. Lưu ý rằng đối với ví dụ này, các giá trị *x* là các kết quả có thể đếm được. Vì bạn có thể đếm các giá trị khả dĩ mà *X* có thể nhận và các kết quả là ngẫu nhiên (các giá trị *x* là 0, 1, 2, 3), nên *X* là một biến ngẫu nhiên rời rạc.

Toss a coin ten times and record the number of heads. After all members of the class have completed the experiment (tossed a coin ten times and counted the number of heads), fill in [Table 4.1](4-introduction#M01_Ch04_tbl001). Let *X* = the number of heads in ten tosses of the coin.

Tung một đồng xu mười lần và ghi lại số mặt ngửa. Sau khi tất cả các thành viên trong lớp đã hoàn thành phép thử (tung một đồng xu mười lần và đếm số mặt ngửa), hãy điền vào [Bảng 4.1](4-introduction#M01_Ch04_tbl001). Gọi *X* = số mặt ngửa trong mười lần tung đồng xu.

| ***x*** | ***x*** | **Frequency of *x*** | **Tần số của *x*** | **Relative Frequency of *x*** | **Tần suất tương đối của *x*** |
| --- | --- | --- | --- | --- | --- |
|  |  |  |  |  |  |
|  |  |  |  |  |  |
|  |  |  |  |  |  |
|  |  |  |  |  |  |
|  |  |  |  |  |  |
|  |  |  |  |  |  |

1. Which value(s) of *x* occurred most frequently?
1. (Các) giá trị nào của *x* xuất hiện với tần số cao nhất?
1. If you tossed the coin 1,000 times, what values could *x* take on? Which value(s) of *x* do you think would occur most frequently?
1. Nếu bạn tung đồng xu 1.000 lần, *x* có thể nhận những giá trị nào? Bạn nghĩ (các) giá trị nào của *x* sẽ xuất hiện với tần số cao nhất?
1. What does the relative frequency column sum to?
1. Tổng của cột tần suất tương đối bằng bao nhiêu?
