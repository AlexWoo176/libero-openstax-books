## 11.4
 
Test for Homogeneity

## 11.4
 
Kiểm định tính đồng nhất

The goodness–of–fit test can be used to decide whether a population fits a given distribution, but it will not suffice to decide whether two populations follow the same unknown distribution. A different test, called the test for homogeneity, can be used to draw a conclusion about whether two populations have the same distribution. To calculate the test statistic for a test for homogeneity, follow the same procedure as with the test of independence.

Kiểm định mức độ phù hợp có thể được sử dụng để quyết định xem một quần thể có khớp với một phân phối nhất định hay không, nhưng nó sẽ không đủ để quyết định xem hai quần thể có tuân theo cùng một phân phối chưa biết hay không. Một kiểm định khác, được gọi là kiểm định tính đồng nhất, có thể được sử dụng để đưa ra kết luận về việc liệu hai quần thể có cùng phân phối hay không. Để tính toán thống kê kiểm định cho kiểm định tính đồng nhất, hãy thực hiện theo quy trình tương tự như với kiểm định tính độc lập.

The expected value for each cell needs to be at least five in order for you to use this test.

Giá trị kỳ vọng cho mỗi ô cần phải ít nhất là năm để bạn có thể sử dụng kiểm định này.

Hypotheses
*H_0*: The distributions of the two populations are the same.

*H_a*:  The distributions of the two populations are not the same.

Các giả thuyết
*H_0*: Các phân phối của hai quần thể là như nhau.

*H_a*: Các phân phối của hai quần thể không như nhau.

Test StatisticUse a   χ 2  χ 2   test statistic.  It is computed in the same way as the test for independence.

Thống kê kiểm địnhSử dụng thống kê kiểm định   χ 2  χ 2 . Nó được tính theo cách tương tự như kiểm định tính độc lập.

Degrees of Freedom (*df*)*df* = number of columns - 1

Bậc tự do (*df*)*df* = số cột - 1

RequirementsAll values in the table must be greater than or equal to five.

Yêu cầuTất cả các giá trị trong bảng phải lớn hơn hoặc bằng năm.

Common UsesComparing two populations. For example:  men vs. women, before vs. after, east vs. west. The variable is categorical with more than two possible response values.

Các ứng dụng phổ biếnSo sánh hai quần thể. Ví dụ: nam so với nữ, trước so với sau, đông so với tây. Biến là biến phân loại với nhiều hơn hai giá trị phản hồi có thể.

#### Problem

#### Bài tập

Do men and women college students have the same distribution of living arrangements?  Use a level of significance of 0.05. Suppose that 250 randomly selected men college students and 300 randomly selected women college students were asked about their living arrangements: dormitory, apartment, with parents, other. The results are shown in [Table 11.19](11-4-test-for-homogeneity#eip-924). Do male and female college students have the same distribution of living arrangements?

Sinh viên đại học nam và nữ có cùng phân phối về điều kiện sống không? Sử dụng mức ý nghĩa 0,05. Giả sử rằng 250 sinh viên đại học nam được chọn ngẫu nhiên và 300 sinh viên đại học nữ được chọn ngẫu nhiên đã được hỏi về điều kiện sống của họ: ký túc xá, căn hộ, ở cùng cha mẹ, khác. Kết quả được hiển thị trong [Bảng 11.19](11-4-test-for-homogeneity#eip-924). Sinh viên đại học nam và nữ có cùng phân phối về điều kiện sống không?

|  |  | Dormitory | Ký túc xá | Apartment | Căn hộ | With Parents | Ở cùng cha mẹ | Other | Khác |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| **Men** | **Nam** | 72 | 72 | 84 | 84 | 49 | 49 | 45 | 45 |
| **Women** | **Nữ** | 91 | 91 | 86 | 86 | 88 | 88 | 35 | 35 |

Do families and singles have the same distribution of cars? Use a level of significance of 0.05. Suppose that 100 randomly selected families and 200 randomly selected singles were asked what type of car they drove: sport, sedan, hatchback, truck, van/SUV. The results are shown in [Table 11.20](11-4-test-for-homogeneity#eip-idm93309648). Do families and singles have the same distribution of cars? Test at a level of significance of 0.05.

Các gia đình và người độc thân có cùng phân phối về xe hơi không? Sử dụng mức ý nghĩa 0,05. Giả sử rằng 100 gia đình được chọn ngẫu nhiên và 200 người độc thân được chọn ngẫu nhiên đã được hỏi họ lái loại xe nào: thể thao, sedan, hatchback, xe tải, xe van/SUV. Kết quả được hiển thị trong [Bảng 11.20](11-4-test-for-homogeneity#eip-idm93309648). Các gia đình và người độc thân có cùng phân phối về xe hơi không? Kiểm định tại mức ý nghĩa 0,05.

|  |  | Sport | Thể thao | Sedan | Sedan | Hatchback | Hatchback | Truck | Xe tải | Van/SUV | Xe van/SUV |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Family | Gia đình | 5 | 5 | 15 | 15 | 35 | 35 | 17 | 17 | 28 | 28 |
| Single | Độc thân | 45 | 45 | 65 | 65 | 37 | 37 | 46 | 46 | 7 | 7 |

#### Problem

#### Bài tập

Both before and after a recent earthquake, surveys were conducted asking voters which of the three candidates they planned on voting for in the upcoming city council election. Has there been a change since the earthquake? Use a level of significance of 0.05. [Table 11.21](11-4-test-for-homogeneity#eip-422) shows the results of the survey. Has there been a change in the distribution of voter preferences since the earthquake?

Cả trước và sau một trận động đất gần đây, các cuộc khảo sát đã được thực hiện để hỏi cử tri xem họ dự định bỏ phiếu cho ứng cử viên nào trong cuộc bầu cử hội đồng thành phố sắp tới. Đã có sự thay đổi nào kể từ sau trận động đất không? Sử dụng mức ý nghĩa 0,05. [Bảng 11.21](11-4-test-for-homogeneity#eip-422) hiển thị kết quả của cuộc khảo sát. Đã có sự thay đổi nào trong phân phối ưu tiên của cử tri kể từ sau trận động đất không?

|  |  | **Perez** | **Perez** | **Chung** | **Chung** | **Stevens** | **Stevens** |
| --- | --- | --- | --- | --- | --- | --- | --- |
| **Before** | **Trước** | 167 | 167 | 128 | 128 | 135 | 135 |
| **After** | **Sau** | 214 | 214 | 197 | 197 | 225 | 225 |

Ivy League schools receive many applications, but only some can be accepted. At the schools listed in [Table 11.22](11-4-test-for-homogeneity#fs-idm19368736), two types of applications are accepted: regular and early decision.

Các trường Ivy League nhận được rất nhiều đơn đăng ký, nhưng chỉ một số có thể được chấp nhận. Tại các trường được liệt kê trong [Bảng 11.22](11-4-test-for-homogeneity#fs-idm19368736), hai loại đơn đăng ký được chấp nhận: thông thường và quyết định sớm.

| Application Type Accepted | Loại đơn đăng ký được chấp nhận | Brown | Brown | Columbia | Columbia | Cornell | Cornell | Dartmouth | Dartmouth | Penn | Penn | Yale | Yale |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Regular | Thông thường | 2,115 | 2,115 | 1,792 | 1,792 | 5,306 | 5,306 | 1,734 | 1,734 | 2,685 | 2,685 | 1,245 | 1,245 |
| Early Decision | Quyết định sớm | 577 | 577 | 627 | 627 | 1,228 | 1,228 | 444 | 444 | 1,195 | 1,195 | 761 | 761 |

We want to know if the number of regular applications accepted follows the same distribution as the number of early applications accepted. State the null and alternative hypotheses, the degrees of freedom and the test statistic, sketch the graph of the *p*-value, and draw a conclusion about the test of homogeneity.

Chúng ta muốn biết liệu số lượng đơn đăng ký thông thường được chấp nhận có tuân theo cùng một phân phối với số lượng đơn đăng ký sớm được chấp nhận hay không. Hãy nêu giả thuyết không và đối thuyết, bậc tự do và thống kê kiểm định, phác thảo đồ thị của p-giá trị, và đưa ra kết luận về kiểm định tính đồng nhất.
