## 11.6
 
Test of a Single Variance

## 11.6
 
Kiểm định một phương sai

A test of a single variance assumes that the underlying distribution is **normal**. The null and alternative hypotheses are stated in terms of the population variance (or population standard deviation). The test statistic is:

Kiểm định một phương sai giả định rằng phân phối cơ sở là **phân phối chuẩn**. Giả thuyết không và đối thuyết được phát biểu dựa trên phương sai tổng thể (hoặc độ lệch chuẩn tổng thể). Thống kê kiểm định là:

where:

trong đó:

- *n* = the total number of data
- *n* = tổng số dữ liệu
- *s*^2 = sample variance
- *s*^2 = phương sai mẫu
- *σ*^2 = population variance
- *σ*^2 = phương sai tổng thể
You may think of *s* as the random variable in this test. The number of degrees of freedom is *df* = *n* - 1. **A test of a single variance may be right-tailed, left-tailed, or two-tailed.** [Example 11.10](11-6-test-of-a-single-variance#element-174) will show you how to set up the null and alternative hypotheses. The null and alternative hypotheses contain statements about the population variance.

Bạn có thể coi *s* là biến ngẫu nhiên trong kiểm định này. Số bậc tự do là *df* = *n* - 1. **Kiểm định một phương sai có thể là kiểm định phía phải, phía trái hoặc hai phía.** [Ví dụ 11.10](11-6-test-of-a-single-variance#element-174) sẽ chỉ cho bạn cách thiết lập giả thuyết không và đối thuyết. Giả thuyết không và đối thuyết chứa các phát biểu về phương sai tổng thể.

#### Problem

#### Bài tập

Math instructors are not only interested in how their students do on exams, on average, but how the exam scores vary. To many instructors, the variance (or standard deviation) may be more important than the average.

Các giảng viên toán không chỉ quan tâm đến kết quả trung bình của sinh viên trong các kỳ thi, mà còn quan tâm đến mức độ biến thiên của điểm thi. Đối với nhiều giảng viên, phương sai (hoặc độ lệch chuẩn) có thể quan trọng hơn giá trị trung bình.

Suppose a math instructor believes that the standard deviation for his final exam is five points. One of his
best students thinks otherwise. The student claims that the standard deviation is more than five points. If the student were to conduct a hypothesis test, what would the null and alternative hypotheses be?

Giả sử một giảng viên toán tin rằng độ lệch chuẩn cho bài thi cuối kỳ của mình là năm điểm. Một trong những sinh viên giỏi nhất của ông lại nghĩ khác. Sinh viên này cho rằng độ lệch chuẩn lớn hơn năm điểm. Nếu sinh viên đó thực hiện một kiểm định giả thuyết, giả thuyết không và đối thuyết sẽ là gì?

A SCUBA instructor wants to record the collective depths each of his students dives during their checkout. He is interested in how the depths vary, even though everyone should have been at the same depth. He believes the standard deviation is three feet. His assistant thinks the standard deviation is less than three feet. If the instructor were to conduct a test, what would the null and alternative hypotheses be?

Một huấn luyện viên lặn SCUBA muốn ghi lại độ sâu tập thể mà mỗi học viên của mình lặn trong quá trình kiểm tra. Ông quan tâm đến việc độ sâu biến thiên như thế nào, mặc dù lẽ ra mọi người đều phải ở cùng một độ sâu. Ông tin rằng độ lệch chuẩn là ba feet. Trợ lý của ông lại nghĩ rằng độ lệch chuẩn nhỏ hơn ba feet. Nếu huấn luyện viên thực hiện một kiểm định, giả thuyết không và đối thuyết sẽ là gì?

#### Problem

#### Bài tập

With individual lines at its various windows, a post office finds that the standard deviation for normally distributed waiting times for customers on Friday afternoon is 7.2 minutes. The post office experiments with a single, main waiting line and finds that for a random sample of 25 customers, the waiting times for customers have a standard deviation of 3.5 minutes.

Với các hàng đợi riêng lẻ tại các cửa sổ khác nhau, một bưu điện nhận thấy rằng độ lệch chuẩn của thời gian chờ đợi được phân phối chuẩn của khách hàng vào chiều thứ Sáu là 7,2 phút. Bưu điện thử nghiệm với một hàng đợi chính duy nhất và nhận thấy rằng đối với một mẫu ngẫu nhiên gồm 25 khách hàng, thời gian chờ đợi của khách hàng có độ lệch chuẩn là 3,5 phút.

With a significance level of 5%, test the claim that **a single line causes lower variation
among waiting times (shorter waiting times) for customers**.

Với mức ý nghĩa 5%, hãy kiểm định khẳng định rằng **một hàng đợi duy nhất làm giảm sự biến thiên giữa các thời gian chờ đợi (thời gian chờ đợi ngắn hơn) đối với khách hàng**.

The FCC conducts broadband speed tests to measure how much data per second passes between a consumer’s computer and the internet. At a certain point in time, the standard deviation of Internet speeds across Internet Service Providers (ISPs) was 12.2 percent. Suppose a sample of 15 ISPs is taken, and the standard deviation is 13.2. An analyst claims that the standard deviation of speeds is more than what was reported. State the null and alternative hypotheses, compute the degrees of freedom, the test statistic, sketch the graph of the *p*-value, and draw a conclusion. Test at the 1% significance level.

FCC thực hiện các bài kiểm tra tốc độ băng thông rộng để đo lường lượng dữ liệu mỗi giây truyền giữa máy tính của người tiêu dùng và internet. Tại một thời điểm nhất định, độ lệch chuẩn của tốc độ Internet giữa các Nhà cung cấp dịch vụ Internet (ISP) là 12,2 phần trăm. Giả sử một mẫu gồm 15 ISP được lấy và độ lệch chuẩn là 13,2. Một nhà phân tích khẳng định rằng độ lệch chuẩn của tốc độ lớn hơn mức đã báo cáo. Hãy phát biểu giả thuyết không và đối thuyết, tính bậc tự do, thống kê kiểm định, phác thảo đồ thị của p-giá trị và đưa ra kết luận. Kiểm định ở mức ý nghĩa 1%.
