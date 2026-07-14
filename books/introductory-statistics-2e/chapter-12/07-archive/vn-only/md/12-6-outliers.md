## 12.6
 
Các điểm bất thường

Trong một số tập dữ liệu, có những giá trị **(các điểm dữ liệu quan sát được)** được gọi là các điểm bất thường. **Các điểm bất thường là các điểm dữ liệu quan sát được nằm xa đường bình phương tối thiểu.** Chúng có các "sai số" lớn, trong đó "sai số" hay phần dư là khoảng cách thẳng đứng từ đường thẳng đến điểm đó.

Các điểm bất thường cần được xem xét kỹ lưỡng. Đôi khi, vì lý do này hay lý do khác, chúng không nên được đưa vào phân tích dữ liệu. Có khả năng một điểm bất thường là kết quả của dữ liệu sai lệch. Những lần khác, một điểm bất thường có thể chứa thông tin có giá trị về quần thể đang được nghiên cứu và nên được giữ lại trong dữ liệu. Điều quan trọng là phải kiểm tra cẩn thận nguyên nhân khiến một điểm dữ liệu trở thành điểm bất thường.

Ngoài các điểm bất thường, một mẫu có thể chứa một hoặc một vài điểm được gọi là các điểm ảnh hưởng. Các điểm ảnh hưởng là các điểm dữ liệu quan sát được nằm xa các điểm dữ liệu quan sát được khác theo phương ngang. Những điểm này có thể có ảnh hưởng lớn đến độ dốc của đường hồi quy. Để bắt đầu xác định một điểm ảnh hưởng, bạn có thể loại bỏ nó khỏi tập dữ liệu và xem liệu độ dốc của đường hồi quy có thay đổi đáng kể hay không.

Máy tính và nhiều máy tính cầm tay có thể được sử dụng để xác định các điểm bất thường từ dữ liệu. Kết quả đầu ra của máy tính cho phân tích hồi quy thường sẽ xác định cả các điểm bất thường và các điểm ảnh hưởng để bạn có thể kiểm tra chúng.

### Nhận diện các điểm bất thường

Chúng ta có thể đoán các điểm bất thường bằng cách nhìn vào biểu đồ phân tán và đường phù hợp nhất. Tuy nhiên, chúng ta muốn có một số hướng dẫn về việc một điểm cần nằm cách xa bao nhiêu để được coi là điểm bất thường. **Theo quy tắc ngón tay cái, chúng ta có thể đánh dấu bất kỳ điểm nào nằm xa hơn hai độ lệch chuẩn phía trên hoặc phía dưới đường phù hợp nhất là một điểm bất thường**. Độ lệch chuẩn được sử dụng là độ lệch chuẩn của các phần dư hoặc sai số.

Chúng ta có thể thực hiện việc này một cách trực quan trên biểu đồ phân tán bằng cách vẽ thêm một cặp đường thẳng nằm cách đường phù hợp nhất hai độ lệch chuẩn phía trên và phía dưới. Bất kỳ điểm dữ liệu nào nằm ngoài cặp đường bổ sung này đều được đánh dấu là các điểm bất thường tiềm ẩn. Hoặc chúng ta có thể thực hiện việc này bằng số bằng cách tính toán từng phần dư và so sánh nó với hai lần độ lệch chuẩn. Trên máy tính TI-83, 83+ hoặc 84+, phương pháp đồ thị dễ dàng hơn. Quy trình đồ thị được hiển thị trước, sau đó là các tính toán bằng số. Thông thường, bạn chỉ cần sử dụng một trong các phương pháp này.

#### Bài tập

Trong [ví dụ về bài thi thứ ba/bài thi cuối kỳ](12-3-the-regression-equation), bạn có thể xác định xem có điểm bất thường hay không. Nếu có một điểm bất thường, như một bài tập, hãy xóa nó đi và khớp dữ liệu còn lại với một đường thẳng mới. Đối với ví dụ này, đường thẳng mới sẽ khớp với dữ liệu còn lại tốt hơn. Điều này có nghĩa là **SSE** sẽ nhỏ hơn và hệ số tương quan sẽ gần với 1 hoặc –1 hơn.

Xác định điểm bất thường tiềm ẩn trong biểu đồ phân tán. Độ lệch chuẩn của các phần dư hoặc sai số xấp xỉ 8,6.

*Hình 
12.21*

### Nhận diện bằng số các điểm bất thường

Trong [Bảng 12.6](12-6-outliers#element-4662), hai cột đầu tiên là dữ liệu bài thi thứ ba và bài thi cuối kỳ. Cột thứ ba hiển thị các giá trị *ŷ* dự đoán được tính từ đường phù hợp nhất: *ŷ* = –173,5 + 4,83*x*. Các phần dư, hay sai số, đã được tính toán trong cột thứ tư của bảng: giá trị *y* quan sát được − giá trị y dự đoán = *y* − *ŷ*.

*s* là độ lệch chuẩn của tất cả các giá trị *y* − *ŷ* = *ε* trong đó *n* = tổng số điểm dữ liệu. Nếu mỗi phần dư được tính toán và bình phương, và các kết quả được cộng lại, chúng ta sẽ có SSE. Độ lệch chuẩn của các phần dư được tính từ SSE như sau:

Chúng ta chia cho (*n* – 2) vì mô hình hồi quy liên quan đến hai ước lượng.

Thay vì tự tính giá trị của *s*, chúng ta có thể tìm *s* bằng máy tính hoặc máy tính cầm tay. Đối với ví dụ này, hàm LinRegTTest trên máy tính đã tìm thấy *s* = 16,4 là độ lệch chuẩn của các phần dư 35; 
–17; 
16; 
–6; 
–19; 
9; 
3; 
–1; 
–10; 
–9; 
–1
.

| *x* | *y* | *ŷ* | *y* – *ŷ* |
| --- | --- | --- | --- |
| 65 | 175 | 140 | 175 – 140 = 35 |
| 67 | 133 | 150 | 133 – 150= –17 |
| 71 | 185 | 169 | 185 – 169 = 16 |
| 71 | 163 | 169 | 163 – 169 = –6 |
| 66 | 126 | 145 | 126 – 145 = –19 |
| 75 | 198 | 189 | 198 – 189 = 9 |
| 67 | 153 | 150 | 153 – 150 = 3 |
| 70 | 163 | 164 | 163 – 164 = –1 |
| 71 | 159 | 169 | 159 – 169 = –10 |
| 69 | 151 | 160 | 151 – 160 = –9 |
| 69 | 159 | 160 | 159 – 160 = –1 |

Chúng ta đang tìm kiếm tất cả các điểm dữ liệu mà phần dư lớn hơn 2*s* = 2(16,4) = 32,8 hoặc nhỏ hơn –32,8. So sánh các giá trị này với các phần dư trong cột thứ tư của bảng. Điểm dữ liệu duy nhất như vậy là sinh viên có điểm 65 trong bài thi thứ ba và 175 trong bài thi cuối kỳ; phần dư cho sinh viên này là 35.

### Điểm bất thường ảnh hưởng như thế nào đến đường phù hợp nhất?

Về mặt số học và đồ thị, chúng ta đã xác định điểm (65, 175) là một điểm bất thường. Chúng ta nên kiểm tra lại dữ liệu cho điểm này để xem có vấn đề gì với dữ liệu hay không. Nếu có lỗi, chúng ta nên sửa lỗi nếu có thể, hoặc xóa dữ liệu. Nếu dữ liệu chính xác, chúng ta sẽ để nó trong tập dữ liệu. Đối với bài toán này, chúng ta sẽ giả định rằng chúng ta đã kiểm tra dữ liệu và thấy rằng dữ liệu bất thường này là một lỗi. Do đó, chúng ta sẽ tiếp tục và xóa điểm bất thường, để chúng ta có thể khám phá cách nó ảnh hưởng đến kết quả như một trải nghiệm học tập.

Tính toán một đường phù hợp nhất mới và hệ số tương quan sử dụng mười điểm còn lại:
Trên các máy tính TI-83, TI-83+, TI-84+, hãy xóa điểm bất thường khỏi L1 và L2. Sử dụng LinRegTTest, đường phù hợp nhất mới và hệ số tương quan là:

*ŷ* = –355,19 + 7,39*x* và *r* = 0,9121

Đường thẳng mới với *r* = 0,9121 có tương quan mạnh hơn so với ban đầu (*r* = 0,6631) vì *r* = 0,9121 gần với một hơn. Điều này có nghĩa là đường thẳng mới khớp tốt hơn với mười giá trị dữ liệu còn lại. Đường thẳng này có thể dự đoán điểm thi cuối kỳ tốt hơn dựa trên điểm thi thứ ba.

### Nhận diện bằng số các điểm bất thường: Tính toán *s* và tìm các điểm bất thường theo cách thủ công

Nếu bạn không có hàm LinRegTTest, thì bạn có thể tính toán điểm bất thường trong ví dụ đầu tiên bằng cách thực hiện các bước sau.

Đầu tiên, **bình phương mỗi |*y* – *ŷ*|**

Các bình phương là 
35^2; 
17^2; 
16^2; 
6^2; 
19^2; 
9^2; 
3^2; 
1^2; 
10^2; 
9^2; 
1^2

**Sau đó, cộng (tổng) tất cả các số hạng |*y* – *ŷ*| bình phương** bằng cách sử dụng công thức

Σ

i = 1

11

(

|
y
i

−

y
^

i

|

)

2

=

Σ

i = 1

11

ε
i

2

Σ

i = 1

11

(

|
y
i

−

y
^

i

|

)

2

=

Σ

i = 1

11

ε
i

2

 (Nhớ rằng *y*_i – *ŷ*_i = *ε*_i.)

= 35^2 + 17^2 + 16^2 + 6^2 + 19^2 + 9^2 + 3^2 + 1^2 + 10^2 + 9^2 + 1^2

= 2440 =  **SSE**. Kết quả, **SSE** là Tổng bình phương sai số.

**Tiếp theo, tính *s*, độ lệch chuẩn của tất cả các giá trị *y* – *ŷ* = *ε* trong đó *n* = tổng số điểm dữ liệu.**

Phép tính là s=

SSE
n–2

s=

SSE
n–2

.

Đối với bài toán về kỳ thi thứ ba/kỳ thi cuối khóa, s=

2440
11–2

=16.47
s=

2440
11–2

=16.47.

Tiếp theo, nhân *s* với 2:

(2)(16,47) = 32,94

32,94 cách giá trị trung bình của các giá trị *y* – *ŷ* là 2 độ lệch chuẩn.

Nếu chúng ta đo khoảng cách theo chiều dọc từ bất kỳ điểm dữ liệu nào đến điểm tương ứng trên đường phù hợp nhất và khoảng cách đó ít nhất là 2*s*, thì chúng ta sẽ coi điểm dữ liệu đó là "quá xa" so với đường phù hợp nhất. Chúng ta gọi điểm đó là điểm bất thường tiềm ẩn.

Đối với ví dụ này, nếu bất kỳ giá trị |*y* – *ŷ*| nào **ít nhất** là 32,94, thì điểm dữ liệu (*x*, *y*) tương ứng là một điểm bất thường tiềm ẩn.

Đối với bài toán về kỳ thi thứ ba/kỳ thi cuối khóa, tất cả các giá trị |*y* – *ŷ*| đều nhỏ hơn 31,29 ngoại trừ giá trị đầu tiên là 35.

35 > 31,29 Nghĩa là, |*y* – *ŷ*| ≥ (2)(s)

Điểm tương ứng với |*y* – *ŷ*| = 35 là (65, 175). **Do đó, điểm dữ liệu (65,175) là một điểm bất thường tiềm ẩn.** Đối với ví dụ này, chúng ta sẽ xóa nó đi. (Hãy nhớ rằng, chúng ta không phải lúc nào cũng xóa một điểm bất thường.)

Khi các điểm bất thường bị xóa, nhà nghiên cứu nên ghi lại rằng dữ liệu đã bị xóa và lý do tại sao, hoặc nhà nghiên cứu nên cung cấp kết quả cả khi có và không có dữ liệu đã xóa. Nếu dữ liệu bị sai và các giá trị đúng đã được biết (ví dụ: sinh viên thứ nhất thực tế đạt 70 điểm thay vì 65), thì có thể thực hiện hiệu chỉnh này cho dữ liệu.

Bước tiếp theo là tính toán một đường phù hợp nhất mới bằng cách sử dụng mười điểm còn lại. Đường phù hợp nhất mới và hệ số tương quan là:

*ŷ* = –355,19 + 7,39*x* và *r* = 0,9121

#### Bài tập

Sử dụng đường phù hợp nhất mới này (dựa trên mười điểm dữ liệu còn lại trong [ví dụ về kỳ thi thứ ba/kỳ thi cuối khóa](12-3-the-regression-equation)), một sinh viên nhận được 73 điểm trong kỳ thi thứ ba dự kiến sẽ nhận được bao nhiêu điểm trong kỳ thi cuối khóa? Kết quả này có giống với dự đoán được thực hiện bằng đường ban đầu không?

Các điểm dữ liệu cho biểu đồ từ [ví dụ về kỳ thi thứ ba/kỳ thi cuối khóa](12-3-the-regression-equation) như sau: (1, 5), (2, 7), (2, 6), (3, 9), (4, 12), (4, 13), (5, 18), (6, 19), (7, 12), và (7, 21). Loại bỏ điểm bất thường và tính toán lại đường phù hợp nhất. Tìm giá trị của *ŷ* khi *x* = 10.

Chỉ số giá tiêu dùng (CPI) đo lường sự thay đổi trung bình theo thời gian về giá cả mà người tiêu dùng thành thị phải trả cho hàng hóa và dịch vụ tiêu dùng. CPI ảnh hưởng đến hầu hết tất cả người Mỹ vì nhiều cách sử dụng của nó. Một trong những công dụng lớn nhất của nó là thước đo lạm phát. Bằng cách cung cấp thông tin về những thay đổi giá cả trong nền kinh tế quốc gia cho chính phủ, doanh nghiệp và người lao động, CPI giúp họ đưa ra các quyết định kinh tế. Tổng thống, Quốc hội và Hội đồng Dự trữ Liên bang sử dụng các xu hướng của CPI để xây dựng các chính sách tiền tệ và tài khóa. Trong bảng sau, *x* là năm và *y* là CPI.

| *x* | *y* | *x* | *y* |
| --- | --- | --- | --- |
| 1915 | 10,1 | 1979 | 72,6 |
| 1926 | 17,7 | 1980 | 82,4 |
| 1935 | 13,7 | 1986 | 109,6 |
| 1940 | 14,7 | 1991 | 130,7 |
| 1947 | 24,1 | 1999 | 166,6 |
| 1952 | 26,5 | 2010 | 219,2 |
| 1964 | 31,0 | 2020 | 258 |
| 1969 | 36,7 | 2023 | 299,2 |
| 1975 | 49,3 |  |  |

#### Bài tập

1. Vẽ biểu đồ phân tán của dữ liệu.
1. Tính toán đường bình phương tối thiểu. Viết phương trình dưới dạng *ŷ* = *a* + *bx*.
1. Vẽ đường thẳng trên biểu đồ phân tán.
1. Tìm hệ số tương quan. Nó có đáng kể không?
1. CPI trung bình cho năm 1990 là bao nhiêu?
Trong ví dụ này, hãy chú ý đến mô hình của các điểm so với đường thẳng. Mặc dù hệ số tương quan là đáng kể, nhưng mô hình trong biểu đồ phân tán cho thấy một đường cong sẽ là mô hình phù hợp hơn để sử dụng thay vì một đường thẳng. Trong ví dụ này, một nhà thống kê nên ưu tiên sử dụng các phương pháp khác để khớp một đường cong với dữ liệu này, thay vì mô hình hóa dữ liệu bằng đường thẳng mà chúng ta đã tìm thấy. Ngoài việc thực hiện các phép tính, việc xem biểu đồ phân tán khi quyết định xem mô hình tuyến tính có phù hợp hay không luôn là điều quan trọng.

Nếu bạn muốn xem thêm dữ liệu của nhiều năm, hãy truy cập trang web CPI của Cục Thống kê Lao động ftp://ftp.bls.gov/pub/special.requests/cpi/cpiai.txt; dữ liệu của chúng tôi được lấy từ cột có tiêu đề "Annual Avg." (cột thứ ba từ bên phải). Ví dụ, bạn có thể thêm dữ liệu của các năm gần đây hơn. Hãy thử thêm các năm gần đây: 2010: CPI = 219.2; 2020: CPI = 258,0; 2023: CPI = 299,2. Xem cách nó ảnh hưởng đến mô hình. (Kiểm tra: y⏜ =-5030+2.598xy⏜ =-5030+2.598x; r = 0.9067r = 0.9067. r có đáng kể không? Độ khớp có tốt hơn khi thêm các điểm mới không?)

Bảng sau đây cho thấy sự phát triển kinh tế được đo bằng thu nhập bình quân đầu người PCINC.

| Năm | PCINC | Năm | PCINC |
| --- | --- | --- | --- |
| 1870 | 340 | 1920 | 1050 |
| 1880 | 499 | 1930 | 1170 |
| 1890 | 592 | 1940 | 1364 |
| 1900 | 757 | 1950 | 1836 |
| 1910 | 927 | 1960 | 2132 |

1. Các biến độc lập và biến phụ thuộc là gì?
1. Vẽ biểu đồ phân tán.
1. Sử dụng hồi quy để tìm đường phù hợp nhất và hệ số tương quan.
1. Giải thích ý nghĩa của hệ số tương quan.
1. Có mối quan hệ tuyến tính giữa các biến không?
1. Tìm hệ số xác định và giải thích nó.
1. Độ dốc của phương trình hồi quy là bao nhiêu? Nó có nghĩa là gì?
1. Sử dụng đường phù hợp nhất để ước tính PCINC cho năm 1900, cho năm 2000.
1. Xác định xem có bất kỳ điểm bất thường nào không.
### Bảng các giá trị tới hạn 95% của hệ số tương quan mẫu

| Bậc tự do: *n* – 2 | Giá trị tới hạn: (+ và –) |
| --- | --- |
| 1 | 0,997 |
| 2 | 0,950 |
| 3 | 0,878 |
| 4 | 0,811 |
| 5 | 0,754 |
| 6 | 0,707 |
| 7 | 0,666 |
| 8 | 0,632 |
| 9 | 0,602 |
| 10 | 0,576 |
| 11 | 0,555 |
| 12 | 0,532 |
| 13 | 0,514 |
| 14 | 0,497 |
| 15 | 0,482 |
| 16 | 0,468 |
| 17 | 0,456 |
| 18 | 0,444 |
| 19 | 0,433 |
| 20 | 0,423 |
| 21 | 0,413 |
| 22 | 0,404 |
| 23 | 0,396 |
| 24 | 0,388 |
| 25 | 0,381 |
| 26 | 0,374 |
| 27 | 0,367 |
| 28 | 0,361 |
| 29 | 0,355 |
| 30 | 0,349 |
| 40 | 0,304 |
| 50 | 0,273 |
| 60 | 0,250 |
| 70 | 0,232 |
| 80 | 0,217 |
| 90 | 0,205 |
| 100 | 0,195 |
