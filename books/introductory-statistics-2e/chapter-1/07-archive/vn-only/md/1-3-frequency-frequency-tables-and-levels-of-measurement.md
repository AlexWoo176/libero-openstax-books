## 1.3
 
Tần số, Bảng tần số, và Các mức độ đo lường

Khi đã có một tập dữ liệu, bạn sẽ cần sắp xếp nó để có thể phân tích tần suất xuất hiện của mỗi dữ liệu trong tập hợp đó. Tuy nhiên, khi tính tần số, bạn có thể cần làm tròn các câu trả lời để chúng đạt độ chính xác cao nhất có thể.

### Các câu trả lời và Làm tròn số

Một cách đơn giản để làm tròn câu trả lời là lấy kết quả cuối cùng nhiều hơn một chữ số thập phân so với dữ liệu gốc. Chỉ làm tròn kết quả cuối cùng. Nếu có thể, đừng làm tròn bất kỳ kết quả trung gian nào. Nếu cần phải làm tròn các kết quả trung gian, hãy lấy ít nhất gấp đôi số chữ số thập phân so với kết quả cuối cùng. Ví dụ, số trung bình của ba điểm bài kiểm tra là bốn, sáu và chín là 6,3, được làm tròn đến hàng phần mười gần nhất, vì dữ liệu là các số nguyên. Hầu hết các câu trả lời sẽ được làm tròn theo cách này.

Không cần thiết phải rút gọn hầu hết các phân số trong khóa học này. Đặc biệt là trong [Các chủ đề về xác suất](3-introduction), chương về xác suất, việc để nguyên phân số chưa rút gọn sẽ hữu ích hơn.

### Các mức độ đo lường

Cách thức một tập dữ liệu được đo lường được gọi là Mức đo lường của nó. Các quy trình thống kê chính xác phụ thuộc vào việc nhà nghiên cứu có nắm rõ các mức độ đo lường hay không. Không phải mọi phép toán thống kê đều có thể được sử dụng cho mọi tập dữ liệu. Dữ liệu có thể được phân loại thành bốn mức độ đo lường. Đó là (từ mức thấp nhất đến cao nhất):

- **Mức độ đo lường thang đo định danh**
- **Mức độ đo lường thang đo thứ bậc**
- **Mức độ đo lường thang đo khoảng**
- **Mức độ đo lường thang đo tỷ lệ**
Dữ liệu được đo lường bằng Thang đo định danh là **dữ liệu định tính (phân loại)**. Các danh mục, màu sắc, tên gọi, nhãn dán và món ăn yêu thích cùng với các phản hồi có hoặc không là những ví dụ về dữ liệu ở mức độ định danh. Dữ liệu thang đo định danh không được sắp xếp theo thứ tự. Ví dụ, việc cố gắng phân loại mọi người theo món ăn yêu thích của họ không có ý nghĩa gì cả. Việc xếp pizza ở vị trí đầu tiên và sushi ở vị trí thứ hai không mang ý nghĩa gì.

Các công ty điện thoại thông minh là một ví dụ khác về dữ liệu thang đo định danh. Dữ liệu này là tên của các công ty sản xuất điện thoại thông minh, nhưng không có thứ tự nào được thống nhất cho các thương hiệu này, mặc dù mọi người có thể có sở thích cá nhân. Dữ liệu thang đo định danh không thể được sử dụng trong các phép tính.

Dữ liệu được đo lường bằng Thang đo thứ bậc tương tự như dữ liệu thang đo định danh nhưng có một sự khác biệt lớn. Dữ liệu thang đo thứ bậc có thể được sắp xếp theo thứ tự. Một ví dụ về dữ liệu thang đo thứ bậc là danh sách năm công viên quốc gia hàng đầu tại Hoa Kỳ. Năm công viên quốc gia hàng đầu tại Hoa Kỳ có thể được xếp hạng từ một đến năm nhưng chúng ta không thể đo lường sự khác biệt giữa các dữ liệu này.

Một ví dụ khác về việc sử dụng thang đo thứ bậc là một cuộc khảo sát về du thuyền, trong đó các phản hồi cho các câu hỏi về chuyến đi là “xuất sắc”, “tốt”, “đạt yêu cầu” và “không đạt yêu cầu”. Những phản hồi này được sắp xếp theo thứ tự từ phản hồi mong muốn nhất đến ít mong muốn nhất. Tuy nhiên, sự khác biệt giữa hai phần dữ liệu không thể đo lường được. Giống như dữ liệu thang đo định danh, dữ liệu thang đo thứ bậc không thể được sử dụng trong các phép tính.

Giống như dữ liệu được đo trên thang đo thứ bậc, dữ liệu được đo trên Thang đo khoảng có một thứ tự xác định. Trong khi dữ liệu thang đo thứ bậc là dữ liệu phân loại hoặc định tính, thì dữ liệu thang đo khoảng là dữ liệu số hoặc định lượng. Chúng ta có thể tính toán sự khác biệt giữa các giá trị được đo trên thang đo khoảng. Tuy nhiên, không có giá trị tối thiểu hoặc giá trị "không".

Các thang đo nhiệt độ như độ C (C) và độ F (F) được đo bằng cách sử dụng thang đo khoảng. Trong cả hai phép đo nhiệt độ này, 40° bằng 100° trừ đi 60°. Các sự khác biệt đều có ý nghĩa. Nhưng 0 độ không đại diện cho một giá trị tối thiểu. Trong cả hai thang đo, 0 không phải là nhiệt độ thấp nhất tuyệt đối. Các nhiệt độ như -10° F và -15° C vẫn tồn tại và lạnh hơn 0.

Dữ liệu được đo bằng cách sử dụng Thang đo tỷ lệ cung cấp nhiều thông tin nhất. Dữ liệu thang đo tỷ lệ giống như dữ liệu thang đo khoảng, nhưng có một giá trị tối thiểu và các tỷ lệ có thể được tính toán. Ví dụ, bốn điểm thi cuối kỳ môn thống kê trắc nghiệm là 80, 68, 20 và 92 (trên tổng số 100 điểm). Các bài thi này được chấm bằng máy.

Dữ liệu có thể được sắp xếp theo thứ tự từ thấp đến cao: 20, 68, 80, 92.

Sự khác biệt giữa các dữ liệu có ý nghĩa. Điểm số 92 lớn hơn điểm số 68 là 24 điểm. Các tỷ lệ có thể được tính toán. Điểm số tối thiểu là 0. Vì vậy, 80 gấp bốn lần 20. Điểm số 80 tốt gấp bốn lần điểm số 20.

### Tần số

Hai mươi sinh viên được hỏi họ làm việc bao nhiêu giờ mỗi ngày. Các phản hồi của họ, tính theo giờ, như sau: 
5; 
6; 
3; 
3; 
2; 
4; 
7; 
5; 
2; 
3; 
5; 
6; 
5; 
4; 
4; 
3; 
5; 
2; 
5; 
3
.

[Bảng 1.10](1-3-frequency-frequency-tables-and-levels-of-measurement#id10383738) liệt kê các giá trị dữ liệu khác nhau theo thứ tự tăng dần và tần số của chúng.

| GIÁ TRỊ DỮ LIỆU | TẦN SỐ |
| --- | --- |
| 2 | 3 |
| 3 | 5 |
| 4 | 3 |
| 5 | 6 |
| 6 | 2 |
| 7 | 1 |

Tần số là số lần một giá trị của dữ liệu xuất hiện. Theo [Bảng 1.10](1-3-frequency-frequency-tables-and-levels-of-measurement#id10383738), có ba sinh viên làm việc hai giờ, năm sinh viên làm việc ba giờ, và cứ tiếp tục như vậy. Tổng các giá trị trong cột tần số, 20, đại diện cho tổng số sinh viên có trong mẫu.

Tần suất tương đối là tỷ lệ (phân số hoặc tỷ lệ) của số lần một giá trị dữ liệu xuất hiện trong tập hợp tất cả các kết quả so với tổng số kết quả. Để tìm tần suất tương đối, hãy chia mỗi tần số cho tổng số sinh viên trong mẫu—trong trường hợp này là 20. Tần suất tương đối có thể được viết dưới dạng phân số, phần trăm hoặc số thập phân.

| GIÁ TRỊ DỮ LIỆU | TẦN SỐ | TẦN SUẤT TƯƠNG ĐỐI |
| --- | --- | --- |
| 2 | 3 | 320320320 hoặc 0,15 |
| 3 | 5 | 520520520 hoặc 0,25 |
| 4 | 3 | 320320320 hoặc 0,15 |
| 5 | 6 | 620620620 hoặc 0,30 |
| 6 | 2 | 220220220 hoặc 0,10 |
| 7 | 1 | 120120120 hoặc 0,05 |

Tổng các giá trị trong cột tần suất tương đối của [Bảng 1.11](1-3-frequency-frequency-tables-and-levels-of-measurement#id11177380) là 202020202020, hay 1.

Tần suất tương đối tích lũy là sự tích lũy của các tần suất tương đối trước đó. Để tìm tần suất tương đối lũy tích, hãy cộng tất cả các tần suất tương đối trước đó với tần suất tương đối của hàng hiện tại, như được hiển thị trong [Bảng 1.12](1-3-frequency-frequency-tables-and-levels-of-measurement#id10564302).

| GIÁ TRỊ DỮ LIỆU | TẦN SỐ | TẦN SUẤT 
TƯƠNG ĐỐI | TẦN SUẤT TƯƠNG ĐỐI 
LŨY TÍCH |
| --- | --- | --- | --- |
| 2 | 3 | 320320320 hoặc 0,15 | 0,15 |
| 3 | 5 | 520520520 hoặc 0,25 | 0,15 + 0,25 = 0,40 |
| 4 | 3 | 320320320 hoặc 0,15 | 0,40 + 0,15 = 0,55 |
| 5 | 6 | 620620620 hoặc 0,30 | 0,55 + 0,30 = 0,85 |
| 6 | 2 | 220220220 hoặc 0,10 | 0,85 + 0,10 = 0,95 |
| 7 | 1 | 120120120 hoặc 0,05 | 0,95 + 0,05 = 1.00 |

Mục cuối cùng của cột tần suất tương đối lũy tích là một, cho thấy rằng một trăm phần trăm dữ liệu đã được tích lũy.

Do làm tròn, cột tần suất tương đối có thể không phải lúc nào cũng cộng lại bằng một, và mục cuối cùng trong cột tần suất tương đối lũy tích có thể không phải là một. Tuy nhiên, mỗi giá trị đều phải gần bằng một.

[Bảng 1.13](1-3-frequency-frequency-tables-and-levels-of-measurement#id9703284) thể hiện chiều cao, tính bằng inch, của một mẫu gồm 100 cầu thủ bóng đá bán chuyên nghiệp.

| CHIỀU CAO 
(INCH) | TẦN SỐ | TẦN SUẤT 
TƯƠNG ĐỐI | TẦN SUẤT 
TƯƠNG ĐỐI 
LŨY TÍCH |
| --- | --- | --- | --- |
| 59,95–61,95 | 5 | 510051005100 = 0,05 | 0,05 |
| 61,95–63,95 | 3 | 310031003100 = 0,03 | 0,05 + 0,03 = 0,08 |
| 63,95–65,95 | 15 | 151001510015100 = 0,15 | 0,08 + 0,15 = 0,23 |
| 65,95–67,95 | 40 | 401004010040100 = 0,40 | 0,23 + 0,40 = 0,63 |
| 67,95–69,95 | 17 | 171001710017100 = 0,17 | 0,63 + 0,17 = 0,80 |
| 69,95–71,95 | 12 | 121001210012100 = 0,12 | 0,80 + 0,12 = 0,92 |
| 71,95–73,95 | 7 | 710071007100 = 0,07 | 0,92 + 0,07 = 0,99 |
| 73,95–75,95 | 1 | 110011001100 = 0,01 | 0,99 + 0,01 = 1.00 |
|  | **Tổng = 100** | **Tổng = 1,00** |  |

Dữ liệu trong bảng này đã được **nhóm** thành các khoảng sau:

- 59,95 đến 61,95 inch
- 61,95 đến 63,95 inch
- 63,95 đến 65,95 inch
- 65,95 đến 67,95 inch
- 67,95 đến 69,95 inch
- 69,95 đến 71,95 inch
- 71,95 đến 73,95 inch
- 73,95 đến 75,95 inch
Ví dụ này được sử dụng lại trong [Thống kê mô tả](2-introduction), nơi phương pháp được sử dụng để tính toán các khoảng sẽ được giải thích.

Trong mẫu này, có **năm** cầu thủ có chiều cao nằm trong khoảng 59,95–61,95 inch, **ba** cầu thủ có chiều cao nằm trong khoảng 61,95–63,95 inch, **15** cầu thủ có chiều cao nằm trong khoảng 63,95–65,95 inch, **40** cầu thủ có chiều cao nằm trong khoảng 65,95–67,95 inch, **17** cầu thủ có chiều cao nằm trong khoảng 67,95–69,95 inch, **12** cầu thủ có chiều cao nằm trong khoảng 69,95–71,95, **bảy** cầu thủ có chiều cao nằm trong khoảng 71,95–73,95, và **một** cầu thủ có chiều cao nằm trong khoảng 73,95–75,95. Tất cả các chiều cao đều nằm giữa các điểm cuối của một khoảng chứ không nằm tại các điểm cuối.

#### Bài tập

Từ [Bảng 1.13](1-3-frequency-frequency-tables-and-levels-of-measurement#id9703284), hãy tìm tỷ lệ phần trăm các chiều cao nhỏ hơn 65,95 inch.

[Bảng 1.14](1-3-frequency-frequency-tables-and-levels-of-measurement#fs-idm82680048) hiển thị lượng mưa hàng năm, tính bằng inch, trong một mẫu các thị trấn.

| Lượng mưa (Inch) | Tần số | Tần suất tương đối | Tần suất tương đối lũy tích |
| --- | --- | --- | --- |
| 2,95–4,97 | 6 | 650650650 = 0,12 | 0,12 |
| 4,97–6,99 | 7 | 750750750 = 0,14 | 0,12 + 0,14 = 0,26 |
| 6,99–9,01 | 15 | 155015501550 = 0,30 | 0,26 + 0,30 = 0,56 |
| 9,01–11,03 | 8 | 850850850 = 0,16 | 0,56 + 0,16 = 0,72 |
| 11,03–13,05 | 9 | 950950950 = 0,18 | 0,72 + 0,18 = 0,90 |
| 13,05–15,07 | 5 | 550550550 = 0,10 | 0,90 + 0,10 = 1.00 |
|  | Tổng = 50 | Tổng = 1,00 |  |

Từ [Bảng 1.14](1-3-frequency-frequency-tables-and-levels-of-measurement#fs-idm82680048), hãy tìm tỷ lệ phần trăm lượng mưa nhỏ hơn 9,01 inch.

#### Bài tập

Từ [Bảng 1.13](1-3-frequency-frequency-tables-and-levels-of-measurement#id9703284), hãy tìm tỷ lệ phần trăm chiều cao nằm trong khoảng từ 61,95 đến 65,95 inch.

Từ [Bảng 1.14](1-3-frequency-frequency-tables-and-levels-of-measurement#fs-idm82680048), hãy tìm tỷ lệ phần trăm lượng mưa nằm trong khoảng từ 6,99 đến 13,05 inch.

#### Bài tập

Sử dụng chiều cao của 100 cầu thủ bóng đá bán chuyên nghiệp trong [Bảng 1.13](1-3-frequency-frequency-tables-and-levels-of-measurement#id9703284). Điền vào các chỗ trống và kiểm tra câu trả lời của bạn.

1. Tỷ lệ phần trăm các chiều cao từ 67,95 đến 71,95 inch là: ____.
1. Tỷ lệ phần trăm các chiều cao từ 67,95 đến 73,95 inch là: ____.
1. Tỷ lệ phần trăm các chiều cao lớn hơn 65,95 inch là: ____.
1. Số lượng cầu thủ trong mẫu có chiều cao từ 61,95 đến 71,95 inch là: ____.
1. Chiều cao thuộc loại dữ liệu nào?
1. Hãy mô tả cách bạn có thể thu thập dữ liệu này (chiều cao) sao cho dữ liệu mang tính đại diện cho tất cả các cầu thủ bóng đá bán chuyên nghiệp.
Hãy nhớ rằng, bạn **đếm tần số**. Để tìm tần suất tương đối, hãy chia tần số cho tổng số giá trị dữ liệu. Để tìm tần suất tương đối lũy tích, hãy cộng tất cả các tần suất tương đối trước đó vào tần suất tương đối của hàng hiện tại.

Từ [Bảng 1.14](1-3-frequency-frequency-tables-and-levels-of-measurement#fs-idm82680048), hãy tìm số lượng thị trấn có lượng mưa từ 2,95 đến 9,01 inch.

Trong lớp học của bạn, hãy nhờ ai đó thực hiện một cuộc khảo sát về số lượng anh chị em mà mỗi sinh viên có. Tạo một bảng tần số. Thêm vào đó một cột tần suất tương đối và một cột tần suất tương đối lũy tích. Trả lời các câu hỏi sau:

1. Bao nhiêu phần trăm sinh viên trong lớp của bạn không có anh chị em ruột?
1. Bao nhiêu phần trăm sinh viên có từ một đến ba anh chị em?
1. Bao nhiêu phần trăm sinh viên có ít hơn ba anh chị em?
Mười chín người đã được hỏi họ đi làm bao nhiêu dặm mỗi ngày, làm tròn đến dặm gần nhất. Dữ liệu như sau: 
2; 
5; 
7; 
3; 
2; 
10; 
18; 
15; 
20; 
7; 
10; 
18; 
5; 
12; 
13; 
12; 
4; 
5; 
10
. [Bảng 1.15](1-3-frequency-frequency-tables-and-levels-of-measurement#id9833287) đã được tạo ra:

| DỮ LIỆU | TẦN SỐ | TẦN SUẤT 
TƯƠNG ĐỐI | TẦN SUẤT 
TƯƠNG ĐỐI 
LŨY TÍCH |
| --- | --- | --- | --- |
| 2 | 2 | 219219219 | 219219219 |
| 3 | 1 | 119119119 | 319319319 |
| 4 | 1 | 119119119 | 419419419 |
| 5 | 3 | 319319319 | 719719719 |
| 7 | 2 | 219219219 | 919919919 |
| 10 | 3 | 319319319 | 121912191219 |
| 12 | 2 | 219219219 | 141914191419 |
| 13 | 1 | 119119119 | 151915191519 |
| 15 | 1 | 119119119 | 161916191619 |
| 18 | 1 | 119119119 | 171917191719 |
| 20 | 1 | 119119119 | 191919191919 |

#### Bài tập

1. Bảng này có chính xác không? Nếu không chính xác, thì sai ở đâu?
1. Đúng hay Sai: Ba phần trăm số người được khảo sát đi làm quãng đường từ ba dặm trở xuống. Nếu phát biểu này không chính xác, thì nó nên là gì? Nếu bảng không chính xác, hãy thực hiện các chỉnh sửa.
1. Phân số nào biểu thị số người được khảo sát đi làm quãng đường năm hoặc bảy dặm?
1. Tỷ lệ số người được khảo sát đi làm quãng đường từ 12 dặm trở lên là bao nhiêu? Dưới 12 dặm? Từ năm đến 13 dặm (không bao gồm năm và 13 dặm)? Cột tần suất tương đối lũy tích sẽ là: 219,319,419,719,919,1219,1419,1519,1619,1819,1919219,319,419,719,919,1219,1419,1519,1619,1819,1919219,319,419,719,919,1219,1419,1519,1619,1819,1919
[Bảng 1.14](1-3-frequency-frequency-tables-and-levels-of-measurement#fs-idm82680048) thể hiện lượng mưa hàng năm, tính bằng inch, trong một mẫu các thị trấn. Phân số các thị trấn được khảo sát có lượng mưa từ 11,03 đến 13,05 inch mỗi năm là bao nhiêu?

[Bảng 1.16](1-3-frequency-frequency-tables-and-levels-of-measurement#fs-idm52810848) chứa dữ liệu về số năm công tác của 70 nhân viên liên bang.

| Số năm công tác | Số lượng nhân viên liên bang |
| --- | --- |
| 24 | 2 |
| 25 | 1 |
| 26 | 3 |
| 27 | 0 |
| 28 | 4 |
| 29 | 6 |
| 30 | 11 |
| 31 | 12 |
| 32 | 7 |
| 33 | 8 |
| 34 | 6 |
| 35 | 10 |

#### Bài tập

Trả lời các câu hỏi sau.

1. Tần số lũy tích cho số năm công tác từ 30 đến 35 năm (bao gồm cả hai đầu) là bao nhiêu?
1. Tần suất tương đối cho 30 năm công tác là bao nhiêu?
1. Tần suất tương đối cho 30 năm công tác trở xuống là bao nhiêu?
1. Tần suất tương đối cho 25 năm công tác trở lên là bao nhiêu?
[Bảng 1.17](1-3-frequency-frequency-tables-and-levels-of-measurement#fs-idm74902768) chứa tổng số vụ tai nạn giao thông xe cơ giới gây tử vong tại Hoa Kỳ trong khoảng thời gian 18 năm.

| Năm | Tổng số vụ tai nạn | Năm | Tổng số vụ tai nạn |
| --- | --- | --- | --- |
| Năm 1 | 36,254 | Năm 11 | 38,444 |
| Năm 2 | 37,241 | Năm 12 | 39,252 |
| Năm 3 | 37,494 | Năm 13 | 38,648 |
| Năm 4 | 37,324 | Năm 14 | 37,435 |
| Năm 5 | 37,107 | Năm 15 | 34,172 |
| Năm 6 | 37,140 | Năm 16 | 30,862 |
| Năm 7 | 37,526 | Năm 17 | 30,296 |
| Năm 8 | 37,862 | Năm 18 | 29,757 |
| Năm 9 | 38,491 | Tổng | 653,782 |
| Năm 10 | 38,477 |  |  |

Trả lời các câu hỏi sau.

1. Tần số tử vong được đo từ Năm 7 đến Năm 11 là bao nhiêu?
1. Bao nhiêu phần trăm số ca tử vong xảy ra sau Năm 13?
1. Tần suất tương đối của các ca tử vong xảy ra vào Năm 7 hoặc trước đó là bao nhiêu?
1. Tỷ lệ phần trăm các ca tử vong xảy ra vào Năm 18 là bao nhiêu?
1. Tần suất tương đối lũy tích cho Năm 13 là bao nhiêu? Hãy giải thích con số này cho bạn biết điều gì về dữ liệu.
