## 10.1
 
Hai số trung bình quần thể với các độ lệch chuẩn chưa biết

1. Hai mẫu độc lập là các mẫu ngẫu nhiên đơn giản từ hai quần thể riêng biệt.
1. For the two distinct populations:

nếu kích thước mẫu nhỏ, các phân phối là quan trọng (nên là phân phối chuẩn)
nếu kích thước mẫu lớn, các phân phối không quan trọng (không cần phải là phân phối chuẩn)
Kiểm định so sánh hai số trung bình quần thể độc lập với các độ lệch chuẩn quần thể chưa biết và có thể không bằng nhau được gọi là kiểm định t Aspin-Welch. Công thức bậc tự do được phát triển bởi Aspin-Welch.

Việc so sánh hai số trung bình quần thể là rất phổ biến. Sự khác biệt giữa hai mẫu phụ thuộc vào cả số trung bình và độ lệch chuẩn. Các số trung bình rất khác nhau có thể xảy ra do ngẫu nhiên nếu có sự biến thiên lớn giữa các mẫu riêng lẻ. Để tính đến sự biến thiên này, chúng ta lấy hiệu của các số trung bình mẫu, 

X
¯

1

X
¯

1
 – 

X
¯

2

X
¯

2
, và chia cho sai số chuẩn để chuẩn hóa sự khác biệt. Kết quả là một thống kê kiểm định t-score.

Vì chúng ta không biết các độ lệch chuẩn quần thể, chúng ta ước lượng chúng bằng cách sử dụng hai độ lệch chuẩn mẫu từ các mẫu độc lập của mình. Đối với kiểm định giả thuyết, chúng ta tính toán độ lệch chuẩn ước lượng, hay sai số chuẩn, của **sự khác biệt giữa các số trung bình mẫu**, 

X
¯

1

X
¯

1
 – 

X
¯

2

X
¯

2
.

Thống kê kiểm định (điểm *t*) được tính như sau:

- *s*_1 và *s*_2, các độ lệch chuẩn mẫu, lần lượt là các ước lượng của *σ*_1 và *σ*_2.
- *σ*_1 và *σ*_2 là các độ lệch chuẩn quần thể chưa biết.
- x
¯

1

x
¯

1

và

x
¯

2

x
¯

2

là các trung bình mẫu. *μ*_1 và *μ*_2 là các trung bình quần thể.
Số lượng bậc tự do (*df*) đòi hỏi một phép tính hơi phức tạp. Tuy nhiên, máy tính hoặc máy tính cầm tay có thể tính toán nó dễ dàng. *df* không phải lúc nào cũng là một số nguyên. Thống kê kiểm định được tính toán trước đó được xấp xỉ bởi phân phối Student *t* với *df* như sau:

Khi cả hai kích thước mẫu *n*_1 và *n*_2 đều từ năm trở lên, phép xấp xỉ Student *t* rất tốt. Lưu ý rằng các phương sai mẫu (*s*_1)^2 và (*s*_2)^2 không được gộp chung. (Nếu câu hỏi này xuất hiện, đừng gộp các phương sai lại.)

Bạn không cần phải tính toán thủ công. Máy tính hoặc phần mềm sẽ tính toán điều này một cách dễ dàng.

#### Các nhóm độc lập

Người ta tin rằng thời gian trung bình mà các bé trai và bé gái từ bảy đến 11 tuổi dành cho việc chơi thể thao mỗi ngày là như nhau. Một nghiên cứu đã được thực hiện và dữ liệu được thu thập, dẫn đến các dữ liệu trong [Bảng 10.1](10-1-two-population-means-with-unknown-standard-deviations#uid888). Mỗi quần thể đều có phân phối chuẩn.

|  | Kích thước mẫu | Số giờ trung bình chơi thể thao mỗi ngày | Độ lệch chuẩn mẫu |
| --- | --- | --- | --- |
| Nữ | 9 | 2 | 0.8660.866 |
| Nam | 16 | 3.2 | 1.00 |

#### Bài tập

Có sự khác biệt nào về thời gian trung bình mà các bé trai và bé gái từ bảy đến 11 tuổi chơi thể thao mỗi ngày không? Hãy kiểm định ở mức ý nghĩa 5%.

Hai mẫu được hiển thị trong [Bảng 10.2](10-1-two-population-means-with-unknown-standard-deviations#fs-idm99631856). Cả hai đều có phân phối chuẩn. Các số trung bình của hai quần thể được cho là như nhau. Có sự khác biệt nào về các số trung bình không? Hãy kiểm định ở mức ý nghĩa 5%.

|  | Kích thước mẫu | Trung bình mẫu | Độ lệch chuẩn mẫu |
| --- | --- | --- | --- |
| Quần thể A | 25 | 5 | 1 |
| Quần thể B | 16 | 4.7 | 1.2 |

Khi tổng kích thước mẫu lớn hơn 30 (*n*_1 + *n*_2 > 30), bạn có thể sử dụng phân phối chuẩn để xấp xỉ phân phối Student *t*. Tuy nhiên, hãy sử dụng phân phối Student *t* bất cứ khi nào có thể.

Một nghiên cứu được thực hiện bởi một nhóm cộng đồng tại hai trường đại học lân cận để xác định trường nào có sinh viên tốt nghiệp với nhiều lớp toán hơn. Trường A lấy mẫu 11 sinh viên tốt nghiệp. Số trung bình của họ là bốn lớp toán với độ lệch chuẩn là 1,5 lớp toán. Trường B lấy mẫu chín sinh viên tốt nghiệp. Số trung bình của họ là 3,5 lớp toán với độ lệch chuẩn là một lớp toán. Nhóm cộng đồng tin rằng một sinh viên tốt nghiệp từ trường A **đã học nhiều lớp toán hơn,** tính trung bình. Cả hai quần thể đều có phân phối chuẩn. Hãy kiểm định ở mức ý nghĩa 1%. Trả lời các câu hỏi sau.

#### Bài tập

a. Đây là kiểm định cho hai số trung bình hay hai tỷ lệ?

#### Bài tập

b. Các độ lệch chuẩn quần thể đã biết hay chưa biết?

#### Bài tập

c. Bạn sử dụng phân phối nào để thực hiện kiểm định?

#### Bài tập

d. Biến ngẫu nhiên là gì?

#### Bài tập

e. Các giả thuyết không và đối thuyết là gì? Viết các giả thuyết không và đối thuyết bằng lời và bằng ký hiệu.

#### Bài tập

f. Đây là kiểm định phía phải, phía trái hay hai phía?

#### Bài tập

g. p-giá trị *p* là bao nhiêu?

#### Bài tập

h. Bạn bác bỏ hay không bác bỏ giả thuyết không?

#### Bài tập

i. **Kết luận:**

Một nghiên cứu được thực hiện để xác định xem Công ty A có giữ chân nhân viên lâu hơn Công ty B hay không. Công ty A lấy mẫu 15 nhân viên, và thời gian trung bình họ làm việc tại công ty là năm năm với độ lệch chuẩn là 1,2. Công ty B lấy mẫu 20 nhân viên, và thời gian trung bình họ làm việc tại công ty là 4,5 năm với độ lệch chuẩn là 0,8. Các quần thể được phân phối chuẩn.

1. Các độ lệch chuẩn quần thể đã biết chưa?
1. Thực hiện một kiểm định giả thuyết phù hợp. Ở mức ý nghĩa 5%, kết luận của bạn là gì?
Một giáo sư tại một trường cao đẳng cộng đồng lớn muốn xác định xem có sự khác biệt nào về số trung bình điểm thi cuối kỳ giữa các sinh viên học khóa thống kê trực tuyến của ông và các sinh viên học lớp thống kê trực tiếp. Ông tin rằng số trung bình điểm thi cuối kỳ của lớp trực tuyến sẽ thấp hơn so với lớp trực tiếp. Liệu giáo sư có đúng không? 30 điểm thi cuối kỳ được chọn ngẫu nhiên từ mỗi nhóm được liệt kê trong [Bảng 10.3](10-1-two-population-means-with-unknown-standard-deviations#fs-idm34056944) và [Bảng 10.4](10-1-two-population-means-with-unknown-standard-deviations#fs-idm124378288).

| 67.6 | 41.2 | 85.3 | 55.9 | 82.4 | 91.2 | 73.5 | 94.1 | 64.7 | 64.7 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 70.6 | 38.2 | 61.8 | 88.2 | 70.6 | 58.8 | 91.2 | 73.5 | 82.4 | 35.5 |
| 94.1 | 88.2 | 64.7 | 55.9 | 88.2 | 97.1 | 85.3 | 61.8 | 79.4 | 79.4 |

| 77.9 | 95.3 | 81.2 | 74.1 | 98.8 | 88.2 | 85.9 | 92.9 | 87.1 | 88.2 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 69.4 | 57.6 | 69.4 | 67.1 | 97.6 | 85.9 | 88.2 | 91.8 | 78.8 | 71.8 |
| 98.8 | 61.2 | 92.9 | 90.6 | 97.6 | 100 | 95.3 | 83.5 | 92.9 | 89.4 |

#### Bài tập

Số trung bình điểm thi cuối kỳ của lớp trực tuyến có thấp hơn số trung bình điểm thi cuối kỳ của lớp trực tiếp không? Hãy kiểm định ở mức ý nghĩa 5%. Trả lời các câu hỏi sau:

1. Đây là kiểm định hai trung bình hay hai tỷ lệ?
1. Các độ lệch chuẩn quần thể đã biết hay chưa biết?
1. Bạn sử dụng phân phối nào để thực hiện kiểm định?
1. Biến ngẫu nhiên là gì?
1. Các giả thuyết không và đối thuyết là gì? Viết các giả thuyết không và đối thuyết bằng lời và bằng ký hiệu.
1. Đây là kiểm định một phía bên phải, bên trái, hay hai phía?
1. *p*-giá trị là bao nhiêu?
1. Bạn bác bỏ hay không bác bỏ giả thuyết không?
1. Tại mức ý nghĩa ___, từ dữ liệu mẫu, ______ (có/không có) đủ bằng chứng để kết luận rằng ______.
(Xem kết luận trong [Ví dụ 10.2](10-1-two-population-means-with-unknown-standard-deviations#element-968), và viết kết luận của bạn theo cách tương tự)

Trước tiên, hãy nhập dữ liệu cho mỗi nhóm vào hai danh sách (như L1 và L2). Nhấn `STAT`. Di chuyển sang `TESTS` và nhấn `4:2SampTTest`. Đảm bảo Data được tô sáng và nhấn `ENTER`. Di chuyển xuống và nhập `L1` cho danh sách thứ nhất và `L2` cho danh sách thứ hai. Di chuyển xuống *μ*_1: và di chuyển đến `<` *μ*_2 (nhỏ hơn). Nhấn `ENTER`. Di chuyển xuống Pooled: No. Nhấn `ENTER`. Di chuyển xuống `Calculate` và nhấn `ENTER`.

Hãy cẩn thận không để lẫn thông tin của Nhóm 1 và Nhóm 2!

Hai giáo sư, A và B, dạy các lớp cùng môn học. Điểm của 10 sinh viên từ mỗi lớp được chọn ngẫu nhiên. Điểm thi cuối kỳ của các sinh viên như sau:

Giáo sư A:

| 97 | 62 | 73 | 58 | 84 |
| --- | --- | --- | --- | --- |
| 74 | 66 | 93 | 73 | 85 |

Giáo sư B:

| 85 | 64 | 74 | 55 | 76 |
| --- | --- | --- | --- | --- |
| 67 | 72 | 84 | 71 | 98 |

Giáo sư A nói rằng số trung bình điểm của lớp họ cao hơn số trung bình của lớp giáo sư B. Liệu giáo sư A có đúng không? Hãy kiểm định ở mức ý nghĩa 5%. Trả lời các câu hỏi sau:

1. Đây là kiểm định hai trung bình hay hai tỷ lệ?
1. Các độ lệch chuẩn quần thể đã biết hay chưa biết?
1. Bạn sử dụng phân phối nào để thực hiện kiểm định?
1. Biến ngẫu nhiên là gì?
1. Các giả thuyết không và đối thuyết là gì? Viết các giả thuyết không và đối thuyết bằng lời và bằng ký hiệu.
1. Đây là kiểm định một phía bên phải, bên trái, hay hai phía?
1. *p*-giá trị là bao nhiêu?
1. Bạn bác bỏ hay không bác bỏ giả thuyết không?
1. Tại mức ý nghĩa ___, từ dữ liệu mẫu, ___ (có/không có) đủ bằng chứng để kết luận rằng ___.
Các tiêu chuẩn của Cohen về kích thước hiệu ứng nhỏ, trung bình và lớnCohen's *d* là một thước đo kích thước hiệu ứng dựa trên sự khác biệt giữa hai số trung bình. Cohen's *d*, được đặt tên theo nhà thống kê người Mỹ Jacob Cohen, đo lường sức mạnh tương đối của sự khác biệt giữa các số trung bình của hai quần thể dựa trên dữ liệu mẫu. Giá trị tính toán của kích thước hiệu ứng sau đó được so sánh với các tiêu chuẩn của Cohen về kích thước hiệu ứng nhỏ, trung bình và lớn.

| Kích thước hiệu ứng | *d* |
| --- | --- |
| Nhỏ | 0.2 |
| trung bình | 0.5 |
| Lớn | 0.8 |

Cohen's *d* là thước đo sự khác biệt giữa hai số trung bình chia cho độ lệch chuẩn gộp: 

d=

x
¯

1

–

x
¯

2

s

pooled

d=

x
¯

1

–

x
¯

2

s

pooled

 trong đó 

s

pooled

=

(
n
1

–1)
s
1
2

+(
n
2

–1)
s
2
2

n
1

+
n
2

–2

s

pooled

=

(
n
1

–1)
s
1
2

+(
n
2

–1)
s
2
2

n
1

+
n
2

–2

#### Bài tập

Tính Cohen's *d* cho [Ví dụ 10.2](10-1-two-population-means-with-unknown-standard-deviations#element-968). Kích thước hiệu ứng là nhỏ, trung bình hay lớn? Giải thích ý nghĩa của kích thước hiệu ứng đối với bài toán này.

Tính Cohen's *d* cho [Thử sức 10.2](10-1-two-population-means-with-unknown-standard-deviations#fs-idp145514592). Kích thước hiệu ứng là nhỏ, trung bình hay lớn? Giải thích ý nghĩa của kích thước hiệu ứng đối với bài toán này.

#### Bài tập

Tính Cohen's *d* cho [Ví dụ 10.3](10-1-two-population-means-with-unknown-standard-deviations#fs-idm22935408). Kích thước hiệu ứng là nhỏ, trung bình hay lớn? Giải thích ý nghĩa của kích thước hiệu ứng đối với bài toán này.

Weighted alpha là thước đo hiệu suất đã điều chỉnh rủi ro của cổ phiếu trong khoảng thời gian một năm. Một weighted alpha dương cao biểu thị một cổ phiếu có giá đã tăng, trong khi một weighted alpha dương nhỏ cho thấy giá cổ phiếu không thay đổi trong khoảng thời gian đó. Weighted alpha được sử dụng để xác định các công ty có xu hướng tăng hoặc giảm mạnh. Weighted alpha cho 30 cổ phiếu ngân hàng hàng đầu ở vùng đông bắc và phía tây theo xác định của Nasdaq vào ngày 24 tháng 5 năm 2013 được liệt kê lần lượt trong [Bảng 10.8](10-1-two-population-means-with-unknown-standard-deviations#fs-idm242901296) và [Bảng 10.9](10-1-two-population-means-with-unknown-standard-deviations#fs-idm167801152).

| 94.2 | 75.2 | 69.6 | 52.0 | 48.0 | 41.9 | 36.4 | 33.4 | 31.5 | 27.6 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 77.3 | 71.9 | 67.5 | 50.6 | 46.2 | 38.4 | 35.2 | 33.0 | 28.7 | 26.5 |
| 76.3 | 71.7 | 56.3 | 48.7 | 43.2 | 37.6 | 33.7 | 31.8 | 28.5 | 26.0 |

| 126.0 | 70.6 | 65.2 | 51.4 | 45.5 | 37.0 | 33.0 | 29.6 | 23.7 | 22.6 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 116.1 | 70.6 | 58.2 | 51.2 | 43.2 | 36.0 | 31.4 | 28.7 | 23.5 | 21.6 |
| 78.2 | 68.2 | 55.6 | 50.3 | 39.0 | 34.1 | 31.0 | 25.3 | 23.4 | 21.5 |

Có sự khác biệt nào về weighted alpha của 30 cổ phiếu ngân hàng hàng đầu ở vùng đông bắc và phía tây không? Hãy kiểm định ở mức ý nghĩa 5%. Trả lời các câu hỏi sau:

1. Đây là kiểm định hai trung bình hay hai tỷ lệ?
1. Các độ lệch chuẩn quần thể đã biết hay chưa biết?
1. Bạn sử dụng phân phối nào để thực hiện kiểm định?
1. Biến ngẫu nhiên là gì?
1. Các giả thuyết không và đối thuyết là gì? Viết các giả thuyết không và đối thuyết bằng lời và bằng ký hiệu.
1. Đây là kiểm định một phía bên phải, bên trái, hay hai phía?
1. *p*-giá trị là bao nhiêu?
1. Bạn bác bỏ hay không bác bỏ giả thuyết không?
1. Tại mức ý nghĩa ___, từ dữ liệu mẫu, ______ (có/không có) đủ bằng chứng để kết luận rằng ______.
1. Tính Cohen’s *d* và giải thích nó.
