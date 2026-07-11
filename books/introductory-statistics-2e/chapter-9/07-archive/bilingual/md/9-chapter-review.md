## Chapter Review

## Ôn tập chương

In a **hypothesis test**, sample data is evaluated in order to arrive at a decision about some type of claim. If certain conditions about the sample are satisfied, then the claim can be evaluated for a population. In a hypothesis test, we:

Trong một **kiểm định giả thuyết**, dữ liệu mẫu được đánh giá để đi đến quyết định về một loại khẳng định nào đó. Nếu các điều kiện nhất định về mẫu được thỏa mãn, thì khẳng định đó có thể được đánh giá cho một tổng thể. Trong một kiểm định giả thuyết, chúng ta:

1. Evaluate the **null hypothesis**, typically denoted with *H_0*. The null is not rejected unless the hypothesis test shows otherwise. The null statement must always contain some form of equality (=, ≤ or ≥)
1. Đánh giá **giả thuyết không**, thường được ký hiệu là *H_0*. Giả thuyết không không bị bác bỏ trừ khi kiểm định giả thuyết cho thấy điều ngược lại. Phát biểu giả thuyết không phải luôn chứa một dạng đẳng thức (=, ≤ hoặc ≥).
1. Always write the **alternative hypothesis**, typically denoted with *H_a* or *H_1*, using less than, greater than, or not equals symbols, i.e., (≠, >, or <).
1. Luôn viết **đối thuyết**, thường được ký hiệu là *H_a* hoặc *H_1*, sử dụng các ký hiệu nhỏ hơn, lớn hơn, hoặc không bằng, tức là (≠, >, hoặc <).
1. If we reject the null hypothesis, then we can assume there is enough evidence to support the alternative hypothesis.
1. Nếu chúng ta bác bỏ giả thuyết không, thì chúng ta có thể giả định rằng có đủ bằng chứng để ủng hộ đối thuyết.
1. Never state that a claim is proven true or false. Keep in mind the underlying fact that hypothesis testing is based on probability laws; therefore, we can talk only in terms of non-absolute certainties.
1. Không bao giờ khẳng định rằng một giả thuyết được chứng minh là đúng hay sai. Hãy ghi nhớ thực tế cơ bản rằng kiểm định giả thuyết dựa trên các quy luật xác suất; do đó, chúng ta chỉ có thể nói về các mức độ chắc chắn không tuyệt đối.
In every hypothesis test, the outcomes are dependent on a correct interpretation of the data. Incorrect calculations or misunderstood summary statistics can yield errors that affect the results. A **Type I** error occurs when a true null hypothesis is rejected. A **Type II error** occurs when a false null hypothesis is not rejected.

Trong mọi kiểm định giả thuyết, các kết cục phụ thuộc vào việc diễn giải đúng dữ liệu. Các tính toán không chính xác hoặc hiểu sai các đại lượng thống kê mô tả có thể dẫn đến những sai lầm ảnh hưởng đến kết quả. Một **sai lầm loại I** xảy ra khi một giả thuyết không đúng bị bác bỏ. Một **sai lầm loại II** xảy ra khi một giả thuyết không sai không bị bác bỏ.

The probabilities of these errors are denoted by the Greek letters *α* and *β*, for a Type I and a Type II error respectively. The power of the test, 1 ’ *β*, quantifies the likelihood that a test will yield the correct result of a true alternative hypothesis being accepted. A high power is desirable.

Xác suất của các sai lầm này được ký hiệu bằng các chữ cái Hy Lạp *α* và *β*, tương ứng cho sai lầm loại I và sai lầm loại II. Công suất của kiểm định, 1 – *β*, định lượng khả năng một kiểm định sẽ đưa ra kết quả đúng khi một đối thuyết đúng được chấp nhận. Công suất cao là điều đáng mong đợi.

In order for a hypothesis test’s results to be generalized to a population, certain requirements must be satisfied.

Để kết quả của một kiểm định giả thuyết có thể được tổng quát hóa cho một tổng thể, một số yêu cầu nhất định phải được thỏa mãn.

When testing for a single population mean:

Khi kiểm định cho một trung bình tổng thể:

1. A Student's *t*-test should be used if the data come from a simple, random sample and the population is approximately normally distributed, or the sample size is large, with an unknown standard deviation.
1. Một kiểm định *t* của Student nên được sử dụng nếu dữ liệu đến từ một mẫu ngẫu nhiên đơn giản và tổng thể xấp xỉ phân phối chuẩn, hoặc kích thước mẫu lớn, với độ lệch chuẩn chưa biết.
1. The normal test will work if the data come from a simple, random sample and the population
      is approximately normally distributed, or the sample size is large, with a known standard
      deviation.
1. Kiểm định chuẩn sẽ hoạt động nếu dữ liệu đến từ một mẫu ngẫu nhiên đơn giản và tổng thể xấp xỉ phân phối chuẩn, hoặc kích thước mẫu lớn, với độ lệch chuẩn đã biết.
When testing a single population proportion use a normal test for a single population proportion if the data comes from a simple, random sample, fill the requirements for a binomial distribution, and the mean number of successes and the mean number of failures satisfy the conditions: *np* > 5 and *nq* > 5 where *n* is the sample size, *p* is the probability of a success, and *q* is the probability of a failure.

Khi kiểm định một tỷ lệ tổng thể, hãy sử dụng kiểm định chuẩn cho một tỷ lệ tổng thể nếu dữ liệu đến từ một mẫu ngẫu nhiên đơn giản, thỏa mãn các yêu cầu cho phân phối nhị thức, và số trung bình các trường hợp thành công và số trung bình các trường hợp thất bại thỏa mãn các điều kiện: *np* > 5 và *nq* > 5, trong đó *n* là kích thước mẫu, *p* là xác suất thành công, và *q* là xác suất thất bại.

When the probability of an event occurring is low, and it happens, it is called a rare event. Rare events are important to consider in hypothesis testing because they can inform your willingness not to reject or to reject a null hypothesis. To test a null hypothesis, find the *p*-value for the sample data and graph the results. When deciding whether or not to reject the null the hypothesis, keep these two parameters in mind:

Khi xác suất xảy ra của một biến cố là thấp, và nó xảy ra, thì đó được gọi là một biến cố hiếm. Các biến cố hiếm rất quan trọng cần xem xét trong kiểm định giả thuyết vì chúng có thể cung cấp thông tin cho sự sẵn lòng của bạn trong việc không bác bỏ hoặc bác bỏ một giả thuyết không. Để kiểm định một giả thuyết không, hãy tìm *p*-giá trị cho dữ liệu mẫu và vẽ biểu đồ kết quả. Khi quyết định có bác bỏ giả thuyết không hay không, hãy ghi nhớ hai tham số này:

1. *α* > *p*-value, reject the null hypothesis
1. *α* > *p*-giá trị, bác bỏ giả thuyết không
1. *α* ≤ *p*-value, do not reject the null hypothesis
1. *α* ≤ *p*-giá trị, không bác bỏ giả thuyết không
The hypothesis test itself has an established process. This can be summarized as follows:

Bản thân kiểm định giả thuyết có một quy trình đã được thiết lập. Quy trình này có thể được tóm tắt như sau:

1. Determine *H_0* and *H_a*. Remember, they are contradictory.
1. Xác định *H_0* và *H_a*. Hãy nhớ rằng, chúng mâu thuẫn với nhau.
1. Determine the random variable.
1. Xác định biến ngẫu nhiên.
1. Determine the distribution for the test.
1. Xác định phân phối cho kiểm định.
1. Draw a graph, calculate the test statistic, and use the test statistic to calculate the
*p*-value. (A *z*-score and a *t*-score are examples of test statistics.)
1. Vẽ biểu đồ, tính toán thống kê kiểm định, và sử dụng thống kê kiểm định để tính *p*-giá trị. (Điểm chuẩn *z* và điểm chuẩn *t* là các ví dụ về thống kê kiểm định.)
1. Compare the preconceived *α* with the *p*-value, make a decision (reject or do not reject *H_0*), and write a clear conclusion using English sentences.
1. So sánh *α* đã định trước với *p*-giá trị, đưa ra quyết định (bác bỏ hoặc không bác bỏ *H_0*), và viết một kết luận rõ ràng bằng các câu tiếng Anh.
Notice that in performing the hypothesis test, you use *α* and not *β*. *β* is needed to help determine the sample size of the data that is used in calculating the *p*-value. Remember that the quantity 1 ’ *β* is called the **Power of the Test**. A high power is desirable. If the power is too low, statisticians typically increase the sample size while keeping *α* the same. If the power is low, the null hypothesis might not be rejected when it should be.

Lưu ý rằng khi thực hiện kiểm định giả thuyết, bạn sử dụng *α* chứ không phải *β*. *β* cần thiết để giúp xác định kích thước mẫu của dữ liệu được sử dụng trong việc tính toán *p*-giá trị. Hãy nhớ rằng đại lượng 1 – *β* được gọi là **Công suất của kiểm định**. Công suất cao là điều đáng mong đợi. Nếu công suất quá thấp, các nhà thống kê thường tăng kích thước mẫu trong khi giữ nguyên *α*. Nếu công suất thấp, giả thuyết không có thể không bị bác bỏ khi lẽ ra nó phải bị bác bỏ.
