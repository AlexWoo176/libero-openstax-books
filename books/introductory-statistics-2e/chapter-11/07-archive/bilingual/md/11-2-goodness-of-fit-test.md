## 11.2
 
Goodness-of-Fit Test

## 11.2
 
Kiểm định mức độ phù hợp

In this type of hypothesis test, you determine whether the data **"fit"** a particular distribution or not. For example, you may suspect your unknown data fit a binomial distribution. You use a chi-square test (meaning the distribution for the hypothesis test is chi-square) to determine if there is a fit or not. **The null and the alternative hypotheses for this test may be written in sentences or may be stated as equations or inequalities.**

Trong loại kiểm định giả thuyết này, bạn xác định xem dữ liệu có **"phù hợp"** với một phân phối cụ thể nào đó hay không. Ví dụ, bạn có thể nghi ngờ rằng dữ liệu chưa biết của mình phù hợp với phân phối nhị thức. Bạn sử dụng kiểm định khi bình phương (nghĩa là phân phối cho kiểm định giả thuyết là phân phối khi bình phương) để xác định xem có sự phù hợp hay không. **Giả thuyết không và đối thuyết cho kiểm định này có thể được viết thành câu hoặc được trình bày dưới dạng phương trình hoặc bất đẳng thức.**

The test statistic for a goodness-of-fit test is:

Thống kê kiểm định cho kiểm định mức độ phù hợp là:

where:

trong đó:

- *O* = observed values (data)
- *O* = các giá trị quan sát (dữ liệu)
- *E* = expected values (from theory)
- *E* = các giá trị kỳ vọng (từ lý thuyết)
- *k* = the number of different data cells or categories
- *k* = số lượng các ô dữ liệu hoặc danh mục khác nhau
**The observed values are the data values and the expected values are the values you would expect to get if the null hypothesis were true.** There are *n* terms of the form 

(O−E)

2

E

(O−E)

2

E

.

**Các giá trị quan sát là các giá trị dữ liệu và các giá trị kỳ vọng là các giá trị bạn mong đợi nhận được nếu giả thuyết không là đúng.** Có *n* số hạng dưới dạng 

(O−E)

2

E

(O−E)

2

E

.

The number of degrees of freedom is *df* = (number of categories – 1).

Số bậc tự do là *df* = (số lượng danh mục – 1).

**The goodness-of-fit test is almost always right-tailed.** If the observed values and the corresponding expected values are not close to each other, then the test statistic can get very large and will be way out in the right tail of the chi-square curve.

**Kiểm định mức độ phù hợp hầu như luôn là kiểm định phía bên phải.** Nếu các giá trị quan sát và các giá trị kỳ vọng tương ứng không gần nhau, thì thống kê kiểm định có thể trở nên rất lớn và sẽ nằm xa về phía đuôi bên phải của đường cong khi bình phương.

The expected value for each cell needs to be at least five in order for you to use this test.

Giá trị kỳ vọng cho mỗi ô cần phải đạt ít nhất là năm để bạn có thể sử dụng kiểm định này.

Absenteeism of college students from math classes is a major concern to math instructors because missing class appears to increase the drop rate. Suppose that a study was done to determine if the actual student absenteeism rate follows faculty perception. The faculty expected that a group of 100 students would miss class according to [Table 11.1](11-2-goodness-of-fit-test#M03_Ch03_tbl001).

Việc sinh viên đại học nghỉ học các lớp toán là một mối quan tâm lớn đối với các giảng viên toán vì việc vắng mặt có vẻ làm tăng tỷ lệ bỏ học. Giả sử một nghiên cứu đã được thực hiện để xác định xem tỷ lệ vắng mặt thực tế của sinh viên có tuân theo nhận định của giảng viên hay không. Giảng viên kỳ vọng rằng một nhóm 100 sinh viên sẽ nghỉ học theo [Bảng 11.1](11-2-goodness-of-fit-test#M03_Ch03_tbl001).

| Number of absences per term | Số ngày vắng mặt mỗi học kỳ | Expected number of students | Số lượng sinh viên kỳ vọng |
| --- | --- | --- | --- |
| 0–2 | 0–2 | 50 | 50 |
| 3–5 | 3–5 | 30 | 30 |
| 6–8 | 6–8 | 12 | 12 |
| 9–11 | 9–11 | 6 | 6 |
| 12+ | 12+ | 2 | 2 |

A random survey across all mathematics courses was then done to determine the actual number **(observed)** of absences in a course. The chart in [Table 11.2](11-2-goodness-of-fit-test#M03_Ch03_tbl002) displays the results of that survey.

Một cuộc khảo sát ngẫu nhiên trên tất cả các khóa học toán sau đó đã được thực hiện để xác định số lượng thực tế **(quan sát)** các buổi vắng mặt trong một khóa học. Biểu đồ trong [Bảng 11.2](11-2-goodness-of-fit-test#M03_Ch03_tbl002) hiển thị kết quả của cuộc khảo sát đó.

| Number of absences per term | Số ngày vắng mặt mỗi học kỳ | Actual number of students | Số lượng sinh viên thực tế |
| --- | --- | --- | --- |
| 0–2 | 0–2 | 35 | 35 |
| 3–5 | 3–5 | 40 | 40 |
| 6–8 | 6–8 | 20 | 20 |
| 9–11 | 9–11 | 1 | 1 |
| 12+ | 12+ | 4 | 4 |

Determine the null and alternative hypotheses needed to conduct a goodness-of-fit test.

Xác định giả thuyết không và đối thuyết cần thiết để thực hiện kiểm định mức độ phù hợp.

***H_0*:** Student absenteeism **fits** faculty perception.

***H_0*:** Việc vắng mặt của sinh viên **phù hợp với** nhận định của giảng viên.

The alternative hypothesis is the opposite of the null hypothesis.

Đối thuyết là ngược lại với giả thuyết không.

***H_a*:** Student absenteeism **does not fit** faculty perception.

***H_a*:** Việc vắng mặt của sinh viên **không phù hợp với** nhận định của giảng viên.

#### Problem

#### Bài tập

a. Can you use the information as it appears in the charts to conduct the goodness-of-fit test?

a. Bạn có thể sử dụng thông tin như xuất hiện trong các biểu đồ để thực hiện kiểm định mức độ phù hợp không?

#### Problem

#### Bài tập

b. What is the number of degrees of freedom (*df*)?

b. Số bậc tự do (*df*) là bao nhiêu?

A factory manager needs to understand how many products are defective versus how many are produced. The number of expected defects is listed in [Table 11.5](11-2-goodness-of-fit-test#M03_Ch03_tbl005).

Một quản lý nhà máy cần hiểu có bao nhiêu sản phẩm bị lỗi so với bao nhiêu sản phẩm được sản xuất. Số lượng lỗi kỳ vọng được liệt kê trong [Bảng 11.5](11-2-goodness-of-fit-test#M03_Ch03_tbl005).

| Number produced | Số lượng sản xuất | Number defective | Số lượng lỗi |
| --- | --- | --- | --- |
| 0–100 | 0–100 | 5 | 5 |
| 101–200 | 101–200 | 6 | 6 |
| 201–300 | 201–300 | 7 | 7 |
| 301–400 | 301–400 | 8 | 8 |
| 401–500 | 401–500 | 10 | 10 |

A random sample was taken to determine the actual number of defects. [Table 11.6](11-2-goodness-of-fit-test#M03_Ch03_tbl006) shows the results of the survey.

Một mẫu ngẫu nhiên đã được lấy để xác định số lượng lỗi thực tế. [Bảng 11.6](11-2-goodness-of-fit-test#M03_Ch03_tbl006) hiển thị kết quả của cuộc khảo sát.

| Number produced | Số lượng sản xuất | Number defective | Số lượng lỗi |
| --- | --- | --- | --- |
| 0–100 | 0–100 | 5 | 5 |
| 101–200 | 101–200 | 7 | 7 |
| 201–300 | 201–300 | 8 | 8 |
| 301–400 | 301–400 | 9 | 9 |
| 401–500 | 401–500 | 11 | 11 |

State the null and alternative hypotheses needed to conduct a goodness-of-fit test, and state the degrees of freedom.

Phát biểu giả thuyết không và đối thuyết cần thiết để thực hiện kiểm định mức độ phù hợp, và nêu số bậc tự do.

#### Problem

#### Bài tập

Employers want to know which days of the week employees are absent in a five-day work week. Most employers would like to believe that employees are absent equally during the week. Suppose a random sample of 60 managers were asked on which day of the week they had the highest number of employee absences. The results were distributed as in [Table 11.7](11-2-goodness-of-fit-test#M03_Ch03_tbl007). For the population of employees, do the days for the highest number of absences occur with equal frequencies during a five-day work week? Test at a 5% significance level.

Các nhà tuyển dụng muốn biết nhân viên thường vắng mặt vào những ngày nào trong tuần làm việc năm ngày. Hầu hết các nhà tuyển dụng đều muốn tin rằng nhân viên vắng mặt đều đặn trong suốt cả tuần. Giả sử một mẫu ngẫu nhiên gồm 60 quản lý được hỏi vào ngày nào trong tuần họ có số lượng nhân viên vắng mặt cao nhất. Các kết quả được phân phối như trong [Bảng 11.7](11-2-goodness-of-fit-test#M03_Ch03_tbl007). Đối với quần thể nhân viên, liệu các ngày có số lượng vắng mặt cao nhất có xảy ra với tần suất bằng nhau trong một tuần làm việc năm ngày không? Hãy kiểm định ở mức ý nghĩa 5%.

|  |  | Monday | Thứ Hai | Tuesday | Thứ Ba | Wednesday | Thứ Tư | Thursday | Thứ Năm | Friday | Thứ Sáu |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Number of Absences | Số ngày nghỉ học | 15 | 15 | 12 | 12 | 9 | 9 | 9 | 9 | 15 | 15 |

Teachers want to know which night each week their students are doing most of their homework. Most teachers think that students do homework equally throughout the week. Suppose a random sample of 56 students were asked on which night of the week they did the most homework. The results were distributed as in [Table 11.8](11-2-goodness-of-fit-test#M03_Ch03_tbl008).

Giáo viên muốn biết mỗi tuần học sinh của họ làm bài tập về nhà nhiều nhất vào đêm nào. Hầu hết giáo viên nghĩ rằng học sinh làm bài tập về nhà đều đặn trong suốt cả tuần. Giả sử một mẫu ngẫu nhiên gồm 56 học sinh được hỏi vào đêm nào trong tuần họ làm bài tập về nhà nhiều nhất. Kết quả được phân phối như trong [Bảng 11.8](11-2-goodness-of-fit-test#M03_Ch03_tbl008).

|  |  | Sunday | Chủ Nhật | Monday | Thứ Hai | Tuesday | Thứ Ba | Wednesday | Thứ Tư | Thursday | Thứ Năm | Friday | Thứ Sáu | Saturday | Thứ Bảy |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Number of Students | Số lượng sinh viên | 11 | 11 | 8 | 8 | 10 | 10 | 7 | 7 | 10 | 10 | 5 | 5 | 5 | 5 |

From the population of students, do the nights for the highest number of students doing the majority of their homework occur with equal frequencies during a week? What type of hypothesis test should you use?

Từ quần thể học sinh, liệu các đêm có số lượng học sinh làm phần lớn bài tập về nhà cao nhất có xảy ra với tần suất bằng nhau trong một tuần không? Bạn nên sử dụng loại kiểm định giả thuyết nào?

One study indicates that the number of streaming services that American families have is distributed (this is the **given** distribution for the American population) as in [Table 11.9](11-2-goodness-of-fit-test#M03_Ch03_tbl009).

Một nghiên cứu chỉ ra rằng số lượng dịch vụ phát trực tuyến mà các gia đình Mỹ có được phân phối (đây là phân phối **đã cho** đối với quần thể người Mỹ) như trong [Bảng 11.9](11-2-goodness-of-fit-test#M03_Ch03_tbl009).

| Number of Streaming Services | Số lượng dịch vụ phát trực tuyến | Percent | Phần trăm |
| --- | --- | --- | --- |
| 0 | 0 | 10 | 10 |
| 1 | 1 | 16 | 16 |
| 2 | 2 | 55 | 55 |
| 3 | 3 | 11 | 11 |
| 4+ | 4+ | 8 | 8 |

The table contains expected (*E*) percents.

Bảng chứa các phần trăm kỳ vọng (*E*).

A random sample of 600 families in the far western United States resulted in the data in [Table 11.10](11-2-goodness-of-fit-test#M03_Ch03_tbl010).

Một mẫu ngẫu nhiên gồm 600 gia đình ở vùng viễn tây Hoa Kỳ đã dẫn đến dữ liệu trong [Bảng 11.10](11-2-goodness-of-fit-test#M03_Ch03_tbl010).

| Number of Streaming Services | Số lượng dịch vụ phát trực tuyến | Frequency | Tần số |
| --- | --- | --- | --- |
| 0 | 0 | 66 | 66 |
| 1 | 1 | 119 | 119 |
| 2 | 2 | 340 | 340 |
| 3 | 3 | 60 | 60 |
| 4+ | 4+ | 15 | 15 |
|  |  | Total = 600 | Tổng = 600 |

The table contains observed (*O*) frequency values.

Bảng chứa các giá trị tần số quan sát (*O*).

#### Problem

#### Bài tập

At the 1% significance level, does it appear that the distribution "number of streaming services" of far western United States families is different from the distribution for the American population as a whole?

Tại mức ý nghĩa 1%, liệu có vẻ như phân phối "số lượng dịch vụ phát trực tuyến" của các gia đình ở vùng viễn tây Hoa Kỳ khác với phân phối của toàn bộ quần thể người Mỹ không?

The expected percentage of the number of pets students have in their homes is distributed (this is the given distribution for the student population of the United States) as in [Table 11.12](11-2-goodness-of-fit-test#fs-idm147763264).

Phần trăm kỳ vọng về số lượng thú cưng mà học sinh có trong nhà được phân phối (đây là phân phối đã cho đối với quần thể học sinh Hoa Kỳ) như trong [Bảng 11.12](11-2-goodness-of-fit-test#fs-idm147763264).

| Number of Pets | Số lượng thú cưng | Percent | Phần trăm |
| --- | --- | --- | --- |
| 0 | 0 | 18 | 18 |
| 1 | 1 | 25 | 25 |
| 2 | 2 | 30 | 30 |
| 3 | 3 | 18 | 18 |
| 4+ | 4+ | 9 | 9 |

A random sample of 1,000 students from the Eastern United States resulted in the data in [Table 11.13](11-2-goodness-of-fit-test#fs-idm64242624).

Một mẫu ngẫu nhiên gồm 1,000 học sinh từ miền Đông Hoa Kỳ đã dẫn đến dữ liệu trong [Bảng 11.13](11-2-goodness-of-fit-test#fs-idm64242624).

| Number of Pets | Số lượng thú cưng | Frequency | Tần số |
| --- | --- | --- | --- |
| 0 | 0 | 210 | 210 |
| 1 | 1 | 240 | 240 |
| 2 | 2 | 320 | 320 |
| 3 | 3 | 140 | 140 |
| 4+ | 4+ | 90 | 90 |

At the 1% significance level, does it appear that the distribution “number of pets” of students in the Eastern United States is different from the distribution for the United States student population as a whole? What is the *p*-value?

Tại mức ý nghĩa 1%, liệu có vẻ như phân phối “số lượng thú cưng” của học sinh ở miền Đông Hoa Kỳ khác với phân phối của toàn bộ quần thể học sinh Hoa Kỳ không? p-giá trị *p* là bao nhiêu?

#### Problem

#### Bài tập

Suppose you flip two coins 100 times. The results are 20 *HH*, 27 *HT*, 30 *TH*, and 23 *TT*. Are the coins fair? Test at a 5% significance level.

Giả sử bạn tung hai đồng xu 100 lần. Kết quả là 20 *HH*, 27 *HT*, 30 *TH* và 23 *TT*. Các đồng xu có cân đối không? Kiểm định ở mức ý nghĩa 5%.

Students in a social studies class hypothesize that the literacy rates across the world for every region are 82%. [Table 11.14](11-2-goodness-of-fit-test#fs-idm84960960) shows the actual literacy rates across the world broken down by region. What are the test statistic and the degrees of freedom?

Các sinh viên trong một lớp học nghiên cứu xã hội đưa ra giả thuyết rằng tỷ lệ biết chữ trên toàn thế giới cho mọi khu vực là 82%. [Bảng 11.14](11-2-goodness-of-fit-test#fs-idm84960960) hiển thị tỷ lệ biết chữ thực tế trên toàn thế giới được phân tách theo khu vực. Thống kê kiểm định và bậc tự do là bao nhiêu?

| MDG Region | Khu vực MDG | Adult Literacy Rate (%) | Tỷ lệ biết chữ ở người lớn (%) |
| --- | --- | --- | --- |
| Developed Regions | Các khu vực phát triển | 99.0 | 99,0 |
| Commonwealth of Independent States | Cộng đồng các quốc gia độc lập | 99.5 | 99,5 |
| Northern Africa | Bắc Phi | 67.3 | 67,3 |
| Sub-Saharan Africa | Châu Phi cận Sahara | 62.5 | 62,5 |
| Latin America and the Caribbean | Mỹ Latinh và vùng Caribe | 91.0 | 91,0 |
| Eastern Asia | Đông Á | 93.8 | 93,8 |
| Southern Asia | Nam Á | 61.9 | 61,9 |
| South-Eastern Asia | Đông Nam Á | 91.9 | 91,9 |
| Western Asia | Tây Á | 84.5 | 84,5 |
| Oceania | Châu Đại Dương | 66.4 | 66,4 |
