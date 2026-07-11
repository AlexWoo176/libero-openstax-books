## 11.3
 
Test of Independence

## 11.3
 
Kiểm định tính độc lập

Tests of independence involve using a contingency table of observed (data) values.

Các kiểm định tính độc lập liên quan đến việc sử dụng bảng ngẫu nhiên của các giá trị quan sát (dữ liệu).

The test statistic for a test of independence is similar to that of a goodness-of-fit test:

Thống kê kiểm định cho một kiểm định tính độc lập tương tự như kiểm định mức độ phù hợp:

where:

trong đó:

- *O* = observed values
- *O* = các giá trị quan sát
- *E* = expected values
- *E* = các giá trị kỳ vọng
- *i* = the number of rows in the table
- *i* = số hàng trong bảng
- *j* = the number of columns in the table
- *j* = số cột trong bảng
There are i⋅ ji⋅ j terms of the form 

(O–E)

2

E

(O–E)

2

E

.

Có i⋅ ji⋅ j số hạng dưới dạng 

(O–E)

2

E

(O–E)

2

E

.

**A test of independence determines whether two factors are independent or not.** You first encountered the term independence in [Probability Topics](3-introduction). As a review, consider the following example.

**Kiểm định tính độc lập xác định xem hai yếu tố có độc lập với nhau hay không.** Bạn đã gặp thuật ngữ độc lập lần đầu trong [Các chủ đề về xác suất](3-introduction). Để ôn tập, hãy xem xét ví dụ sau.

The expected value for each cell needs to be at least five in order for you to use this test.

Giá trị kỳ vọng cho mỗi ô cần phải đạt ít nhất là năm để bạn có thể sử dụng kiểm định này.

Suppose *A* = a speeding violation in the last year and *B* = a cell phone user while driving. If *A* and *B* are independent then *P*(*A* AND *B*) = *P*(*A*)*P*(*B*). *A* AND *B* is the event that a driver received a speeding violation last year and also used a cell phone while driving. Suppose, in a study of drivers who received speeding violations in the last year, and who used cell phone while driving, that 755 people were surveyed. Out of the 755, 70 had a speeding violation and 685 did not; 305 used cell phones while driving and 450 did not.

Giả sử *A* = vi phạm tốc độ trong năm qua và *B* = người sử dụng điện thoại di động khi lái xe. Nếu *A* và *B* độc lập thì *P*(*A* VÀ *B*) = *P*(*A*)*P*(*B*). *A* VÀ *B* là biến cố một tài xế nhận vé phạt vi phạm tốc độ trong năm qua và cũng sử dụng điện thoại di động khi lái xe. Giả sử, trong một nghiên cứu về các tài xế đã nhận vé phạt vi phạm tốc độ trong năm qua và sử dụng điện thoại di động khi lái xe, có 755 người được khảo sát. Trong số 755 người, 70 người có vi phạm tốc độ và 685 người không có; 305 người sử dụng điện thoại di động khi lái xe và 450 người không sử dụng.

Let *y* = expected number of drivers who used a cell phone while driving and received speeding violations.

Gọi *y* = số lượng tài xế dự kiến đã sử dụng điện thoại di động khi lái xe và nhận vé phạt vi phạm tốc độ.

If *A* and *B* are independent, then *P*(*A* AND *B*) = *P*(*A*)*P*(*B*). By substitution,

Nếu *A* và *B* độc lập, thì *P*(*A* VÀ *B*) = *P*(*A*)*P*(*B*). Bằng cách thay thế,

y

755

=(

70

755

)(

305

755

)

y

755

=(

70

755

)(

305

755

)

y

755

=(

70

755

)(

305

755

)

y

755

=(

70

755

)(

305

755

)

Solve for *y*: *y* = 

(70)(305)

755

=28.3

(70)(305)

755

=28.3

Giải cho *y*: *y* = 

(70)(305)

755

=28.3

(70)(305)

755

=28.3

About 28 people from the sample are expected to use cell phones while driving and to receive speeding violations.

Khoảng 28 người từ mẫu được dự kiến là có sử dụng điện thoại di động khi lái xe và nhận vé phạt vi phạm tốc độ.

In a test of independence, we state the null and alternative hypotheses in words. Since the contingency table consists of **two factors**, the null hypothesis states that the factors are **independent** and the alternative hypothesis states that they are **not independent (dependent)**. If we do a test of independence using the example, then the null hypothesis is:

Trong một kiểm định tính độc lập, chúng ta phát biểu giả thuyết không và đối thuyết bằng lời. Vì bảng ngẫu nhiên bao gồm **hai yếu tố**, giả thuyết không phát biểu rằng các yếu tố là **độc lập** và đối thuyết phát biểu rằng chúng **không độc lập (phụ thuộc)**. Nếu chúng ta thực hiện kiểm định tính độc lập bằng cách sử dụng ví dụ trên, thì giả thuyết không là:

*H_0*: Being a cell phone user while driving and receiving a speeding violation are independent events.

*H_0*: Việc là người sử dụng điện thoại di động khi lái xe và việc nhận vé phạt vi phạm tốc độ là các biến cố độc lập.

If the null hypothesis were true, we would expect about 28 people to use cell phones while driving and to receive a speeding violation.

Nếu giả thuyết không là đúng, chúng ta sẽ kỳ vọng khoảng 28 người sử dụng điện thoại di động khi lái xe và nhận vé phạt vi phạm tốc độ.

**The test of independence is always right-tailed** because of the calculation of the test statistic. If the expected and observed values are not close together, then the test statistic is very large and way out in the right tail of the chi-square curve, as it is in a goodness-of-fit.

**Kiểm định tính độc lập luôn là kiểm định đuôi phải** do cách tính toán thống kê kiểm định. Nếu các giá trị kỳ vọng và quan sát không gần nhau, thì thống kê kiểm định sẽ rất lớn và nằm xa về phía đuôi phải của đường cong khi bình phương, giống như trong kiểm định mức độ phù hợp.

The number of degrees of freedom for the test of independence is:

Số bậc tự do cho kiểm định tính độc lập là:

*df* = (number of columns - 1)(number of rows - 1)

*df* = (số cột - 1)(số hàng - 1)

The following formula calculates the **expected number** (*E*):

Công thức sau đây tính toán **số lượng kỳ vọng** (*E*):

A sample of 300 students is taken. Of the students surveyed, 50 were music students, while 250 were not. Ninety-seven were on the honor roll, while 203 were not. If we assume being a music student and being on the honor roll are independent events, what is the expected number of music students who are also on the honor roll?

Một mẫu gồm 300 sinh viên được lấy. Trong số các sinh viên được khảo sát, 50 người là sinh viên âm nhạc, trong khi 250 người không phải. Chín mươi bảy người nằm trong danh sách danh dự, trong khi 203 người không nằm trong danh sách đó. Nếu chúng ta giả định việc là sinh viên âm nhạc và việc nằm trong danh sách danh dự là các biến cố độc lập, thì số lượng sinh viên âm nhạc dự kiến cũng nằm trong danh sách danh dự là bao nhiêu?

In a volunteer group, adults 21 and older volunteer from one to nine hours each week to spend time with a disabled senior citizen. The program recruits among community college students, four-year college students, and nonstudents. In [Table 11.15](11-3-test-of-independence#table-73248) is a **sample** of the adult volunteers and the number of hours they volunteer per week.

Trong một nhóm tình nguyện, người lớn từ 21 tuổi trở lên tình nguyện từ một đến chín giờ mỗi tuần để dành thời gian cho một người cao tuổi khuyết tật. Chương trình tuyển chọn trong số sinh viên cao đẳng cộng đồng, sinh viên đại học bốn năm và những người không phải là sinh viên. Trong [Bảng 11.15](11-3-test-of-independence#table-73248) là một **mẫu** các tình nguyện viên người lớn và số giờ họ tình nguyện mỗi tuần.

| Type of Volunteer | Loại tình nguyện viên | 1–3 Hours | 1–3 Giờ | 4–6 Hours | 4–6 Giờ | 7–9 Hours | 7–9 Giờ | Row Total | Tổng hàng |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Community College Students | Sinh viên cao đẳng cộng đồng | 111 | 111 | 96 | 96 | 48 | 48 | 255 | 255 |
| Four-Year College Students | Sinh viên đại học bốn năm | 96 | 96 | 133 | 133 | 61 | 61 | 290 | 290 |
| Nonstudents | Người không phải sinh viên | 91 | 91 | 150 | 150 | 53 | 53 | 294 | 294 |
| Column Total | Tổng cột | 298 | 298 | 379 | 379 | 162 | 162 | 839 | 839 |

#### Problem

#### Bài tập

Is the number of hours volunteered **independent** of the type of volunteer?

Số giờ tình nguyện có **độc lập** với loại tình nguyện viên không?

The Bureau of Labor Statistics gathers data about employment in the United States. A sample is taken to calculate the number of U.S. citizens working in one of several industry sectors over time. [Table 11.17](11-3-test-of-independence#fs-idp61742592) shows the results:

Cục Thống kê Lao động thu thập dữ liệu về việc làm tại Hoa Kỳ. Một mẫu được lấy để tính toán số lượng công dân Hoa Kỳ làm việc trong một trong số các ngành công nghiệp theo thời gian. [Bảng 11.17](11-3-test-of-independence#fs-idp61742592) hiển thị kết quả:

| Industry Sector | Ngành công nghiệp | 2000 | 2000 | 2010 | 2010 | 2020 | 2020 | Total | Tổng |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Nonagriculture wage and salary | Việc làm hưởng lương và tiền công phi nông nghiệp | 13,243 | 13,243 | 13,044 | 13,044 | 15,018 | 15,018 | 41,305 | 41,305 |
| Goods-producing, excluding agriculture | Sản xuất hàng hóa, trừ nông nghiệp | 2,457 | 2,457 | 1,771 | 1,771 | 1,950 | 1,950 | 6,178 | 6,178 |
| Services-providing | Cung cấp dịch vụ | 10,786 | 10,786 | 11,273 | 11,273 | 13,068 | 13,068 | 35,127 | 35,127 |
| Agriculture, forestry, fishing, and hunting | Nông nghiệp, lâm nghiệp, đánh bắt và săn bắn | 240 | 240 | 214 | 214 | 201 | 201 | 655 | 655 |
| Nonagriculture self-employed and unpaid family worker | Tự doanh phi nông nghiệp và lao động gia đình không hưởng lương | 931 | 931 | 894 | 894 | 972 | 972 | 2,797 | 2,797 |
| Secondary wage and salary jobs in agriculture and private household industries | Việc làm hưởng lương và tiền công thứ cấp trong ngành nông nghiệp và hộ gia đình tư nhân | 14 | 14 | 11 | 11 | 11 | 11 | 36 | 36 |
| Secondary jobs as a self-employed or unpaid family worker | Việc làm thứ cấp với tư cách là người tự doanh hoặc lao động gia đình không hưởng lương | 196 | 196 | 144 | 144 | 152 | 152 | 492 | 492 |
| Total | Tổng | 27,867 | 27,867 | 27,351 | 27,351 | 31,372 | 31,372 | 86,590 | 86,590 |

We want to know if the change in the number of jobs is independent of the change in years. State the null and alternative hypotheses and the degrees of freedom.

Chúng ta muốn biết liệu sự thay đổi về số lượng việc làm có độc lập với sự thay đổi về năm hay không. Hãy phát biểu giả thuyết không, đối thuyết và bậc tự do.

De Anza College is interested in the relationship between anxiety level
        and the need to succeed in school. A random sample of 400 students took a test that measured
        anxiety level and need to succeed in school. [Table 11.18](11-3-test-of-independence#element-875) shows the
        results. De Anza College wants to know if anxiety level and need to succeed in school are
        independent events.

Trường Cao đẳng De Anza quan tâm đến mối quan hệ giữa mức độ lo âu và nhu cầu thành công trong học tập. Một mẫu ngẫu nhiên gồm 400 sinh viên đã thực hiện một bài kiểm tra đo lường mức độ lo âu và nhu cầu thành công trong học tập. [Bảng 11.18](11-3-test-of-independence#element-875) hiển thị kết quả. Trường Cao đẳng De Anza muốn biết liệu mức độ lo âu và nhu cầu thành công trong học tập có phải là các biến cố độc lập hay không.

| Need to Succeed in School | Nhu cầu thành công trong học tập | High 
Anxiety | Lo âu 
cao | Med-high 
Anxiety | Lo âu 
trung bình-cao | Medium 
Anxiety | Lo âu 
trung bình | Med-low 
Anxiety | Lo âu 
trung bình-thấp | Low 
Anxiety | Lo âu 
thấp | Row Total | Tổng hàng |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| High Need | Nhu cầu cao | 35 | 35 | 42 | 42 | 53 | 53 | 15 | 15 | 10 | 10 | 155 | 155 |
| Medium Need | Nhu cầu trung bình | 18 | 18 | 48 | 48 | 63 | 63 | 33 | 33 | 31 | 31 | 193 | 193 |
| Low Need | Nhu cầu thấp | 4 | 4 | 5 | 5 | 11 | 11 | 15 | 15 | 17 | 17 | 52 | 52 |
| Column Total | Tổng cột | 57 | 57 | 95 | 95 | 127 | 127 | 63 | 63 | 58 | 58 | 400 | 400 |

#### Problem

#### Bài tập

a. How many high anxiety level students are expected to have a high
            need to succeed in school?

a. Có bao nhiêu sinh viên có mức độ lo âu cao được kỳ vọng sẽ có nhu cầu thành công cao trong học tập?

#### Problem

#### Bài tập

b. If the two variables are independent, how many students do you
            expect to have a low need to succeed in school and a med-low level of anxiety?

b. Nếu hai biến là độc lập, bạn kỳ vọng có bao nhiêu sinh viên có nhu cầu thành công thấp trong học tập và mức độ lo âu trung bình-thấp?

Refer back to the information in [Try It  11.6](11-3-test-of-independence#fs-idm24618832). How many service providing jobs are there expected to be in 2020? How many nonagriculture wage and salary jobs are there expected to be in 2020?

Tham khảo lại thông tin trong [Thử sức 11.6](11-3-test-of-independence#fs-idm24618832). Dự kiến có bao nhiêu việc làm cung cấp dịch vụ vào năm 2020? Dự kiến có bao nhiêu việc làm hưởng lương và tiền công phi nông nghiệp vào năm 2020?
