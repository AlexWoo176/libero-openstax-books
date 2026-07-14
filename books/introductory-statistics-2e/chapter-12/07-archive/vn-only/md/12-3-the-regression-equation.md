## 12.3
 
Phương trình hồi quy

Dữ liệu hiếm khi khớp chính xác với một đường thẳng. Thông thường, bạn phải hài lòng với các dự đoán thô. Thông thường, bạn có một tập dữ liệu mà biểu đồ phân tán dường như **"khớp"** với một đường thẳng. Đây được gọi là Đường phù hợp nhất **hoặc** Đường hồi quy bình phương tối thiểu.

Nếu bạn biết chiều dài ngón út của một người, bạn có nghĩ rằng mình có thể dự đoán chiều cao của người đó không? Thu thập dữ liệu từ lớp học của bạn (chiều dài ngón út, tính bằng inch). Biến giải thích, *x*, là chiều dài ngón út và biến phản hồi, *y*, là chiều cao. Đối với mỗi tập dữ liệu, hãy vẽ các điểm trên giấy kẻ ô. Hãy làm cho biểu đồ của bạn đủ lớn và **sử dụng thước kẻ**. Sau đó, "bằng mắt thường", hãy vẽ một đường thẳng dường như "khớp" với dữ liệu. Đối với đường thẳng của bạn, hãy chọn hai điểm thuận tiện và sử dụng chúng để tìm hệ số góc của đường thẳng. Tìm điểm cắt *y* của đường thẳng bằng cách kéo dài đường thẳng của bạn để nó cắt trục *y*. Sử dụng các hệ số góc và điểm cắt *y*, hãy viết phương trình "phù hợp nhất" của bạn. Bạn có nghĩ rằng mọi người sẽ có cùng một phương trình không? Tại sao có hoặc tại sao không? Theo phương trình của bạn, chiều cao dự đoán cho chiều dài ngón út là 2,5 inch là bao nhiêu?

Một mẫu ngẫu nhiên gồm 11 sinh viên thống kê đã tạo ra dữ liệu sau, trong đó *x* là điểm thi lần thứ ba trên thang điểm 80, và *y* là điểm thi cuối kỳ trên thang điểm 200. Bạn có thể dự đoán điểm thi cuối kỳ của một sinh viên ngẫu nhiên nếu bạn biết điểm thi lần thứ ba không?

| x (điểm thi lần thứ ba) | y (điểm thi cuối kỳ) |
| --- | --- |
| 65 | 175 |
| 67 | 133 |
| 71 | 185 |
| 71 | 163 |
| 66 | 126 |
| 75 | 198 |
| 67 | 153 |
| 70 | 163 |
| 71 | 159 |
| 69 | 151 |
| 69 | 159 |

*Hình 
12.9
 
Biểu đồ phân tán hiển thị điểm số trong bài thi cuối kỳ dựa trên điểm số từ bài thi thứ ba.*

Thợ lặn SCUBA có thời gian lặn tối đa mà họ không được vượt quá khi đi đến các độ sâu khác nhau. Dữ liệu trong [Bảng 12.4](12-3-the-regression-equation#eip-idm70490496) hiển thị các độ sâu khác nhau với thời gian lặn tối đa tính bằng phút. Sử dụng máy tính của bạn để tìm đường hồi quy bình phương tối thiểu và dự đoán thời gian lặn tối đa cho độ sâu 110 feet.

| *X* (độ sâu tính bằng feet) | *Y* (thời gian lặn tối đa) |
| --- | --- |
| 50 | 80 |
| 60 | 55 |
| 70 | 45 |
| 80 | 35 |
| 90 | 25 |
| 100 | 22 |

Điểm thi lần thứ ba, *x*, là biến giải thích và điểm thi cuối kỳ, *y*, là biến phản hồi. Chúng ta sẽ vẽ một đường hồi quy "khớp" nhất với dữ liệu. Nếu mỗi bạn tự vẽ một đường thẳng "bằng mắt thường", các bạn sẽ vẽ ra những đường thẳng khác nhau. Chúng ta có thể sử dụng cái gọi là đường hồi quy bình phương tối thiểu để có được đường phù hợp nhất.

Hãy xem xét sơ đồ sau. Mỗi điểm dữ liệu có dạng (*x*, *y*) và mỗi điểm của đường phù hợp nhất sử dụng hồi quy tuyến tính bình phương tối thiểu có dạng (*x*, *ŷ*).

*ŷ* được đọc là **"*y* mũ"** và là **giá trị ước tính của *y***. Đó là giá trị của *y* thu được bằng cách sử dụng đường hồi quy. Nó thường không bằng với *y* từ dữ liệu.

*Hình 
12.10*

Thuật ngữ *y*_0 – *ŷ*_0 = *ε*_0 được gọi là **"sai số" hoặc** phần dư. Đây không phải là sai số theo nghĩa là một lỗi sai. Giá trị tuyệt đối của phần dư đo lường khoảng cách thẳng đứng giữa giá trị thực tế của *y* và giá trị ước tính của *y*. Nói cách khác, nó đo lường khoảng cách thẳng đứng giữa điểm dữ liệu thực tế và điểm dự đoán trên đường thẳng.

Nếu điểm dữ liệu quan sát nằm phía trên đường thẳng, phần dư là dương, và đường thẳng đánh giá thấp giá trị dữ liệu thực tế cho *y*. Nếu điểm dữ liệu quan sát nằm phía dưới đường thẳng, phần dư là âm, và đường thẳng đánh giá quá cao giá trị dữ liệu thực tế đó cho *y*.

Trong sơ đồ tại [Hình 12.10](12-3-the-regression-equation#linrgs_regeq2), *y*_0 – *ŷ*_0 = ε_0 là phần dư cho điểm được hiển thị. Ở đây điểm nằm phía trên đường thẳng và phần dư là dương.

*ε* = chữ cái Hy Lạp **epsilon**

Đối với mỗi điểm dữ liệu, bạn có thể tính toán các phần dư hoặc sai số, *y*_i - *ŷ*_i = *ε*_i cho *i* = 1, 2, 3, ..., 11.

Mỗi |*ε*| là một khoảng cách thẳng đứng.

Đối với ví dụ về điểm thi lần thứ ba và điểm thi cuối kỳ của 11 sinh viên thống kê, có 11 điểm dữ liệu. Do đó, có 11 giá trị *ε*. Nếu bạn bình phương mỗi ε và cộng lại, bạn sẽ có

Đây được gọi là Tổng bình phương sai số (SSE).

Sử dụng giải tích, bạn có thể xác định các giá trị của *a* và *b* làm cho **SSE** đạt cực tiểu. Khi bạn làm cho **SSE** đạt cực tiểu, bạn đã xác định được các điểm nằm trên đường phù hợp nhất. Hóa ra đường phù hợp nhất có phương trình:

trong đó 

a=
y
¯

−b
x
¯

a=
y
¯

−b
x
¯

 và 

b=

Σ(x−
x
¯

)(y−
y
¯

)

Σ

(x−
x
¯

)

2

b=

Σ(x−
x
¯

)(y−
y
¯

)

Σ

(x−
x
¯

)

2

.

Các giá trị trung bình mẫu của các giá trị *x* và các giá trị *y* lần lượt là 

x
¯

x
¯
 và 

y
¯

y
¯
. Đường phù hợp nhất luôn đi qua điểm 

(
x
¯

,
y
¯

)

(
x
¯

,
y
¯

)
.

Hệ số góc *b* có thể được viết là 

b=r(

s
y

s
x

)

b=r(

s
y

s
x

)
 trong đó *s*_*y* = độ lệch chuẩn của các giá trị *y* và *s*_*x* = độ lệch chuẩn của các giá trị *x*. *r* là hệ số tương quan, được thảo luận trong phần tiếp theo.

### Biểu đồ phần dư

Biểu đồ phần dư có thể được sử dụng để giúp xác định xem một tập dữ liệu (*x*, *y*) có tương quan tuyến tính hay không. Đối với mỗi điểm dữ liệu được sử dụng để tạo đường tương quan, một phần dư *y* - *ŷ* có thể được tính toán, trong đó y là giá trị quan sát được của biến phản hồi và *ŷ* là giá trị được dự đoán bởi đường tương quan. Sự khác biệt giữa các giá trị này được gọi là phần dư. Biểu đồ phần dư hiển thị biến giải thích *x* trên trục hoành và phần dư cho giá trị đó trên trục tung. Biểu đồ phần dư thường được hiển thị cùng với biểu đồ phân tán của dữ liệu. Trong khi biểu đồ phân tán của dữ liệu nên giống một đường thẳng, biểu đồ phần dư nên xuất hiện ngẫu nhiên, không có quy luật và không có giá trị ngoại lệ. Nó cũng nên cho thấy phương sai sai số không đổi, nghĩa là các phần dư không nên tăng (hoặc giảm) một cách nhất quán khi biến giải thích *x* tăng lên.

Biểu đồ phần dư có thể được tạo bằng StatCrunch hoặc máy tính TI. Biểu đồ sẽ xuất hiện ngẫu nhiên. Biểu đồ hộp của các phần dư cũng hữu ích để xác minh rằng không có giá trị ngoại lệ trong dữ liệu. Bằng cách quan sát biểu đồ phân tán của dữ liệu, biểu đồ phần dư và biểu đồ hộp của phần dư, cùng với hệ số tương quan tuyến tính, chúng ta thường có thể xác định xem liệu có hợp lý khi kết luận rằng dữ liệu có tương quan tuyến tính hay không.

#### VÍ DỤ:

Một chủ cửa hàng sử dụng hồi quy đường thẳng để ước tính số lượng ốc quế kem sẽ được bán trong một ngày dựa trên nhiệt độ vào buổi trưa. Chủ cửa hàng có dữ liệu trong khoảng thời gian 2 năm và đã chọn ngẫu nhiên chín ngày. Biểu đồ phân tán của dữ liệu được hiển thị, cùng với biểu đồ phần dư.

| Nhiệt độ ° F | Số kem ốc quế đã bán |
| --- | --- |
| 70 | 105 |
| 85 | 240 |
| 65 | 49 |
| 72 | 147 |
| 80 | 231 |
| 61 | 38 |
| 75 | 193 |
| 78 | 196 |
| 68 | 89 |

*Hình 
12.11
 
Biểu đồ phân tán của dữ liệu trông giống như một đường thẳng.*

*Hình 
12.12
 
Biểu đồ phần dư có vẻ ngẫu nhiên.*

### Tiêu chí bình phương tối thiểu cho sự phù hợp nhất

Quá trình khớp đường phù hợp nhất được gọi là **hồi quy tuyến tính**. Ý tưởng đằng sau việc tìm đường phù hợp nhất dựa trên giả định rằng dữ liệu được phân tán xung quanh một đường thẳng. Tiêu chí cho đường phù hợp nhất là tổng bình phương sai số (SSE) được cực tiểu hóa, nghĩa là làm cho nó nhỏ nhất có thể. Bất kỳ đường thẳng nào khác mà bạn chọn cũng sẽ có SSE cao hơn đường phù hợp nhất. Đường phù hợp nhất này được gọi là **đường hồi quy bình phương tối thiểu**.

Các bảng tính máy tính, phần mềm thống kê và nhiều máy tính có thể nhanh chóng tính toán đường phù hợp nhất và tạo biểu đồ. Các phép tính có xu hướng tẻ nhạt nếu thực hiện bằng tay. Hướng dẫn sử dụng máy tính TI-83, TI-83+ và TI-84+ để tìm đường phù hợp nhất và tạo biểu đồ phân tán được hiển thị ở cuối phần này.

VÍ DỤ ĐIỂM THI LẦN THỨ BA vs ĐIỂM THI CUỐI KỲ:
Biểu đồ của đường phù hợp nhất cho ví dụ về điểm thi lần thứ ba/điểm thi cuối kỳ như sau:

*Hình 
12.13*

Đường hồi quy bình phương tối thiểu (đường phù hợp nhất) cho ví dụ về điểm thi lần thứ ba/điểm thi cuối kỳ có phương trình:

Hãy nhớ rằng, việc vẽ biểu đồ phân tán trước tiên luôn quan trọng. Nếu biểu đồ phân tán chỉ ra rằng có mối quan hệ tuyến tính giữa các biến, thì việc sử dụng đường phù hợp nhất để đưa ra dự đoán cho *y* với *x* đã cho trong phạm vi của các giá trị *x* trong dữ liệu mẫu là hợp lý, **nhưng không nhất thiết cho các giá trị *x* nằm ngoài phạm vi đó.** Bạn có thể sử dụng đường thẳng để dự đoán điểm thi cuối kỳ cho một sinh viên đạt điểm 73 trong bài thi lần thứ ba. Bạn KHÔNG NÊN sử dụng đường thẳng để dự đoán điểm thi cuối kỳ cho một sinh viên đạt điểm 50 trong bài thi lần thứ ba, vì 50 không nằm trong phạm vi của các giá trị *x* trong dữ liệu mẫu, vốn nằm trong khoảng từ 65 đến 75.

### HIỂU VỀ HỆ SỐ GÓC

Hệ số góc của đường thẳng, *b*, mô tả cách các thay đổi trong các biến có liên quan với nhau. Điều quan trọng là phải giải thích hệ số góc của đường thẳng trong bối cảnh của tình huống được dữ liệu đại diện. Bạn sẽ có thể viết một câu giải thích hệ số góc bằng ngôn ngữ đơn giản.

**GIẢI THÍCH HỆ SỐ GÓC:** Hệ số góc của đường phù hợp nhất cho chúng ta biết biến phản hồi (*y*) thay đổi như thế nào cho mỗi đơn vị tăng lên của biến giải thích (*x*), tính trung bình.

VÍ DỤ ĐIỂM THI LẦN THỨ BA vs ĐIỂM THI CUỐI KỲHệ số góc: Hệ số góc của đường thẳng là *b* = 4,83.

Giải thích: Với mỗi một điểm tăng thêm trong bài thi lần thứ ba, điểm thi cuối kỳ tăng trung bình 4,83 điểm.

Sử dụng Hồi quy tuyến tính `T Test: LinRegTTest`

1. Trong trình chỉnh sửa danh sách `STAT`, hãy nhập dữ liệu X vào danh sách `L1` và dữ liệu Y vào danh sách `L2`, được ghép cặp sao cho các giá trị tương ứng (*x*,*y*) nằm cạnh nhau trong các danh sách. (Nếu một cặp giá trị cụ thể bị lặp lại, hãy nhập nó nhiều lần như số lần nó xuất hiện trong dữ liệu.)
1. Trên menu `STAT TESTS`, hãy cuộn xuống bằng con trỏ để chọn `LinRegTTest`. (Hãy cẩn thận chọn `LinRegTTest`, vì một số máy tính có thể có một mục khác gọi là LinRegTInt.)
1. Trên màn hình nhập LinRegTTest, hãy nhập: Xlist: L1 ; Ylist: L2 ; Freq: 1
1. Trên dòng tiếp theo, tại lời nhắc *β* hoặc *ρ*, hãy làm nổi bật "≠ 0" và nhấn ENTER
1. Để trống dòng "RegEq:"
1. Làm nổi bật Calculate và nhấn ENTER.
*Hình 
12.14*

Màn hình đầu ra chứa rất nhiều thông tin. Hiện tại chúng ta sẽ tập trung vào một vài mục từ đầu ra, và sẽ quay lại các mục khác sau.

Dòng thứ hai cho biết *y* = *a* + *bx*. Cuộn xuống để tìm các giá trị *a* = –173,513, và *b* = 4,8273; phương trình của đường phù hợp nhất là *ŷ* = –173,51 + 4,83*x*

Hai mục ở dưới cùng là *r*_2 = 0,43969 và *r* = 0,663. Hiện tại, chỉ cần lưu ý nơi tìm các giá trị này; chúng ta sẽ thảo luận về chúng trong hai phần tiếp theo.

Vẽ biểu đồ phân tán và đường hồi quy

1. Chúng ta đang giả định rằng dữ liệu X của bạn đã được nhập vào danh sách L1 và dữ liệu Y của bạn nằm trong danh sách L2
1. Nhấn 2nd STATPLOT ENTER để sử dụng Plot 1
1. Trên màn hình nhập cho PLOT 1, hãy làm nổi bật **On** và nhấn ENTER
1. Đối với TYPE: hãy làm nổi bật biểu tượng đầu tiên là biểu đồ phân tán (scatterplot) và nhấn ENTER
1. Chỉ định Xlist: L1 và Ylist: L2
1. Đối với Mark: việc bạn làm nổi bật biểu tượng nào không quan trọng.
1. Nhấn phím ZOOM và sau đó là số 9 (cho mục menu "ZoomStat"); máy tính sẽ điều chỉnh cửa sổ cho phù hợp với dữ liệu
1. Để vẽ đường phù hợp nhất, nhấn phím "Y=" và nhập phương trình –173,5 + 4.83X vào phương trình Y1. (Phím X nằm ngay bên trái phím STAT). Nhấn ZOOM 9 lần nữa để vẽ đồ thị.
1. Tùy chọn: Nếu bạn muốn thay đổi cửa sổ xem, nhấn phím WINDOW. Nhập cửa sổ mong muốn của bạn bằng cách sử dụng Xmin, Xmax, Ymin, Ymax
Một cách khác để vẽ đường thẳng sau khi bạn tạo biểu đồ phân tán là sử dụng LinRegTTest.

1. Đảm bảo rằng bạn đã thực hiện biểu đồ phân tán. Kiểm tra nó trên màn hình của bạn.
1. Đi đến LinRegTTest và nhập các danh sách.
1. Tại RegEq: nhấn VARS và di chuyển mũi tên sang Y-VARS. Nhấn 1 cho 1:Function. Nhấn 1 cho 1:Y1. Sau đó di chuyển mũi tên xuống Calculate và thực hiện tính toán cho đường phù hợp nhất.
1. Nhấn Y = (bạn sẽ thấy phương trình hồi quy).
1. Nhấn GRAPH. Đường thẳng sẽ được vẽ."
### Hệ số tương quan *r*

Ngoài việc nhìn vào biểu đồ phân tán và thấy rằng một đường thẳng có vẻ hợp lý, làm thế nào bạn có thể biết liệu đường thẳng đó có phải là một công cụ dự đoán tốt hay không? Sử dụng hệ số tương quan như một chỉ báo khác (ngoài biểu đồ phân tán) về độ mạnh của mối quan hệ giữa *x* và *y*.

**Hệ số tương quan, *r*, ** được Karl Pearson phát triển vào đầu những năm 1900, là một giá trị số cung cấp thước đo về độ mạnh và hướng của mối liên hệ tuyến tính giữa biến độc lập *x* và biến phụ thuộc *y*.

Hệ số tương quan được tính như sau

trong đó *n* = số lượng điểm dữ liệu.

Nếu bạn nghi ngờ có một mối quan hệ tuyến tính giữa *x* và *y*, thì *r* có thể đo lường mức độ mạnh mẽ của mối quan hệ tuyến tính đó.

GIÁ TRỊ của *r* cho chúng ta biết điều gì:

- Giá trị của *r* luôn nằm trong khoảng từ –1 đến +1: –1 ≤ *r* ≤ 1.
- Kích thước của hệ số tương quan *r* cho biết độ mạnh của mối quan hệ tuyến tính giữa *x* và *y*. Các giá trị của *r* gần bằng –1 hoặc +1 cho thấy mối quan hệ tuyến tính mạnh hơn giữa *x* và *y*.
- Nếu *r* = 0 thì có khả năng không có tương quan tuyến tính. Tuy nhiên, điều quan trọng là phải xem biểu đồ phân tán, vì dữ liệu thể hiện mô hình cong hoặc nằm ngang có thể có hệ số tương quan bằng 0.
- Nếu *r* = 1, có tương quan thuận hoàn hảo. Nếu *r* = –1, có tương quan nghịch hoàn hảo. Trong cả hai trường hợp này, tất cả các điểm dữ liệu gốc đều nằm trên một đường thẳng. Tất nhiên, trong thế giới thực, điều này thường sẽ không xảy ra.
DẤU của *r* cho chúng ta biết điều gì

- Giá trị dương của *r* có nghĩa là khi *x* tăng, *y* có xu hướng tăng và khi *x* giảm, *y* có xu hướng giảm **(tương quan thuận)**.
- Giá trị âm của *r* có nghĩa là khi *x* tăng, *y* có xu hướng giảm và khi *x* giảm, *y* có xu hướng tăng **(tương quan nghịch)**.
- Dấu của *r* giống với dấu của hệ số góc, *b*, của đường phù hợp nhất.
*Hình 
12.15
 
(a) Biểu đồ phân tán hiển thị dữ liệu có tương quan dương. 0 < *r* < 1 (b) Biểu đồ phân tán hiển thị dữ liệu có tương quan âm. –1 < *r* < 0 (c) Biểu đồ phân tán hiển thị dữ liệu có tương quan bằng không. *r* = 0*

Công thức cho *r* trông có vẻ đáng sợ. Tuy nhiên, các bảng tính trên máy tính, phần mềm thống kê và nhiều máy tính cầm tay có thể nhanh chóng tính toán *r*. Hệ số tương quan *r* là mục cuối cùng trên màn hình kết quả của LinRegTTest trên máy tính TI-83, TI-83+ hoặc TI-84+ (xem phần trước để biết hướng dẫn).

### Hệ số xác định

**Biến *r*^2 được gọi là** hệ số xác định và là bình phương của hệ số tương quan, nhưng thường được biểu thị dưới dạng phần trăm thay vì dạng thập phân. Nó có một cách giải thích trong bối cảnh của dữ liệu:

- r
2

r
2
, khi được biểu thị dưới dạng phần trăm, đại diện cho phần trăm biến thiên của biến phụ thuộc (được dự đoán) *y* có thể được giải thích bằng biến thiên của biến độc lập (giải thích) *x* sử dụng đường hồi quy (phù hợp nhất).
- 1 – 
r
2

r
2
, khi được biểu thị dưới dạng phần trăm, đại diện cho phần trăm biến thiên của *y* KHÔNG được giải thích bằng biến thiên của *x* sử dụng đường hồi quy. Điều này có thể được xem là sự phân tán của các điểm dữ liệu quan sát được xung quanh đường hồi quy.
Hãy xem xét [ví dụ về bài thi thứ ba/bài thi cuối kỳ](12-3-the-regression-equation#element-22) đã được giới thiệu trong phần trước

- Đường phù hợp nhất là: *ŷ* = –173,51 + 4.83x
- Hệ số tương quan là *r* = 0,6631
- Hệ số xác định là *r*^2 = 0,6631^2 = 0,4397
- **Giải thích về *r*^2 trong bối cảnh của ví dụ này:**
- Khoảng 44% biến thiên (0,4397 xấp xỉ 0,44) trong điểm thi cuối kỳ có thể được giải thích bằng biến thiên trong điểm thi của bài thi thứ ba, sử dụng đường hồi quy phù hợp nhất.
- Do đó, khoảng 56% biến thiên (1 – 0,44 = 0,56) trong điểm thi cuối kỳ KHÔNG thể được giải thích bằng biến thiên trong điểm thi của bài thi thứ ba, sử dụng đường hồi quy phù hợp nhất. (Điều này được thấy qua sự phân tán của các điểm xung quanh đường thẳng.)
