## 9.3
 
Probability Distribution Needed for Hypothesis Testing

## 9.3
 
Phân phối xác suất cần thiết cho Kiểm định giả thuyết

Earlier in the course, we discussed sampling distributions. Particular distributions are associated with various types of hypothesis testing.

Trước đó trong khóa học, chúng ta đã thảo luận về phân phối mẫu. Các phân phối cụ thể được liên kết với các loại kiểm định giả thuyết khác nhau.

The following table summarizes various hypothesis tests and corresponding probability distributions that will be used to conduct the test (based on the assumptions shown below):

Bảng sau đây tóm tắt các kiểm định giả thuyết khác nhau và các phân phối xác suất tương ứng sẽ được sử dụng để thực hiện kiểm định (dựa trên các giả định được trình bày dưới đây):

| Type of Hypothesis Test | Loại Kiểm định giả thuyết | Population Parameter | Tham số tổng thể | Estimated value (point estimate) | Giá trị ước lượng (ước lượng điểm) | Probability Distribution Used | Phân phối xác suất được sử dụng |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Hypothesis test for the mean, when the population standard deviation is known | Kiểm định giả thuyết cho trung bình, khi độ lệch chuẩn tổng thể đã biết | Population mean μμ | Trung bình tổng thể μμ | Sample mean x¯x¯ | Trung bình mẫu x¯x¯ | Normal distribution, 
  X¯~N(μX,σXn)X¯~N(μX,σXn) | Phân phối chuẩn, 
  X¯~N(μX,σXn)X¯~N(μX,σXn) |
| Hypothesis test for the mean, when the population standard deviation is unknown and the distribution of the sample mean is approximately normal | Kiểm định giả thuyết cho trung bình, khi độ lệch chuẩn tổng thể chưa biết và phân phối của trung bình mẫu xấp xỉ chuẩn | Population mean μμ | Trung bình tổng thể μμ | Sample mean x¯x¯ | Trung bình mẫu x¯x¯ | Student’s t-distribution, tdftdf | Phân phối Student (phân phối t), tdftdf |
| Hypothesis test for proportions | Kiểm định giả thuyết cho tỷ lệ | Population proportion pp | Tỷ lệ tổng thể pp | Sample proportion p'p' | Tỷ lệ mẫu p'p' | Normal distribution,
  P'~N(p,p·qn)P'~N(p,p·qn) | Phân phối chuẩn,
  P'~N(p,p·qn)P'~N(p,p·qn) |

### Assumptions

### Giả định

When you perform a hypothesis test of a single population mean *μ* using a normal distribution (often called a z-test), you take a simple random sample from the population. The population you are testing is normally distributed, or your sample size is sufficiently large. You know the value of the population standard deviation, which, in reality, is rarely known.

Khi bạn thực hiện một kiểm định giả thuyết về một trung bình tổng thể duy nhất *μ* sử dụng phân phối chuẩn (thường được gọi là kiểm định z), bạn lấy một mẫu ngẫu nhiên đơn giản từ tổng thể. Tổng thể bạn đang kiểm định là có phân phối chuẩn, hoặc kích thước mẫu của bạn đủ lớn. Bạn biết giá trị của độ lệch chuẩn tổng thể, mà trên thực tế, hiếm khi được biết.

When you perform a hypothesis test of a single population mean *μ* using a Student's t-distribution (often called a *t*-test), there are fundamental assumptions that need to be met in order for the test to work properly. Your data should be a simple random sample that comes from a population that is approximately normally distributed. You use the sample standard deviation to approximate the population standard deviation. (Note that if the sample size is sufficiently large, a *t*-test will work even if the population is not approximately normally distributed).

Khi bạn thực hiện kiểm định giả thuyết về một trung bình tổng thể duy nhất *μ* sử dụng Phân phối Student (phân phối t) (thường được gọi là kiểm định *t*), có những giả định cơ bản cần được đáp ứng để kiểm định hoạt động đúng cách. Dữ liệu của bạn phải là một mẫu ngẫu nhiên đơn giản đến từ một tổng thể có phân phối xấp xỉ chuẩn. Bạn sử dụng độ lệch chuẩn mẫu để xấp xỉ độ lệch chuẩn tổng thể. (Lưu ý rằng nếu kích thước mẫu đủ lớn, kiểm định *t* sẽ hoạt động ngay cả khi tổng thể không có phân phối xấp xỉ chuẩn).

When you perform a hypothesis test of a single population proportion *p*, you take a simple random sample from the population. You must meet the conditions for a binomial distribution: there are a certain number *n* of independent trials, the outcomes of any trial are success or failure, and each trial has the same probability of a success *p*. The shape of the binomial distribution needs to be similar to the shape of the normal distribution. To ensure this, the quantities *np* and *nq* must both be greater than five (np>5 np>5  and nq>5 nq>5 ). Then the binomial distribution of a sample (estimated) proportion can be approximated by the normal distribution with μ=p μ=p   and σ=pqnσ=pqn. Remember that q=1-pq=1-p.

Khi bạn thực hiện kiểm định giả thuyết về một tỷ lệ tổng thể duy nhất *p*, bạn lấy một mẫu ngẫu nhiên đơn giản từ tổng thể. Bạn phải đáp ứng các điều kiện cho một phân phối nhị thức: có một số lượng *n* phép thử độc lập nhất định, kết quả của bất kỳ phép thử nào là thành công hoặc thất bại, và mỗi phép thử có cùng xác suất thành công *p*. Hình dạng của phân phối nhị thức cần phải tương tự như hình dạng của phân phối chuẩn. Để đảm bảo điều này, các đại lượng *np* và *nq* phải lớn hơn năm (np>5 np>5  và nq>5 nq>5 ). Khi đó, phân phối nhị thức của một tỷ lệ mẫu (ước lượng) có thể được xấp xỉ bằng phân phối chuẩn với μ=p μ=p  và σ=pqnσ=pqn. Hãy nhớ rằng q=1-pq=1-p.
