## 2.2
 
Biểu đồ histogram, đa giác tần số và biểu đồ chuỗi thời gian

Đối với hầu hết các công việc bạn thực hiện trong cuốn sách này, bạn sẽ sử dụng biểu đồ histogram để hiển thị dữ liệu. Một ưu điểm của biểu đồ histogram là nó có thể hiển thị dễ dàng các tập dữ liệu lớn. Một quy tắc chung là sử dụng biểu đồ histogram khi tập dữ liệu bao gồm 100 giá trị trở lên.

Một Biểu đồ tần số bao gồm các cột liên tục (liền kề). Nó có cả trục ngang và trục dọc. Trục ngang được dán nhãn với nội dung mà dữ liệu đại diện (ví dụ: khoảng cách từ nhà bạn đến trường). Trục dọc được dán nhãn là Tần số hoặc Tần suất tương đối (hoặc tần suất phần trăm hoặc xác suất). Biểu đồ sẽ có cùng hình dạng với bất kỳ nhãn nào. Biểu đồ histogram (giống như biểu đồ thân lá) có thể cho bạn biết hình dạng của dữ liệu, tâm và sự biến thiên của dữ liệu.

Tần suất tương đối bằng tần số của một giá trị dữ liệu quan sát được chia cho tổng số giá trị dữ liệu trong mẫu. (Hãy nhớ rằng, tần số được định nghĩa là số lần một câu trả lời xuất hiện.) Nếu:

- *f* = tần số
- *n* = tổng số giá trị dữ liệu (hoặc tổng của các tần số riêng lẻ), và
- *RF* = tần suất tương đối,
thì:

Ví dụ, nếu ba sinh viên trong một lớp tiếng Anh gồm 40 sinh viên đạt từ 90% đến 100%, thì, <newline count="1"/>*f* = 3, *n* = 40, và *RF* = 𝑓𝑛fnfn = 340340340 = 0.075. 7.5% số sinh viên đạt 90–100%. 90–100% là các phép đo định lượng.

**Để xây dựng một biểu đồ histogram**, trước tiên hãy quyết định số lượng **cột** hoặc Các khoảng, còn được gọi là các lớp, đại diện cho dữ liệu. Nhiều biểu đồ histogram bao gồm từ năm đến 15 cột hoặc lớp để rõ ràng. Cần phải chọn số lượng cột. Chọn một điểm bắt đầu cho khoảng đầu tiên nhỏ hơn giá trị dữ liệu nhỏ nhất. Một **điểm bắt đầu thuận tiện** là một giá trị thấp hơn được lấy thêm một chữ số thập phân so với giá trị có nhiều chữ số thập phân nhất. Ví dụ, nếu giá trị có nhiều chữ số thập phân nhất là 6.1 và đây là giá trị nhỏ nhất, một điểm bắt đầu thuận tiện là 6.05 (6.1 – 0.05 = 6.05). Chúng ta nói rằng 6.05 có độ chính xác cao hơn. Nếu giá trị có nhiều chữ số thập phân nhất là 2.23 và giá trị thấp nhất là 1.5, một điểm bắt đầu thuận tiện là 1.495 (1.5 – 0.005 = 1.495). Nếu giá trị có nhiều chữ số thập phân nhất là 3.234 và giá trị thấp nhất là 1.0, một điểm bắt đầu thuận tiện là 0.9995 (1.0 – 0.0005 = 0.9995). Nếu tất cả dữ liệu đều là số nguyên và giá trị nhỏ nhất là hai, thì một điểm bắt đầu thuận tiện là 1.5 (2 – 0.5 = 1.5). Ngoài ra, khi điểm bắt đầu và các ranh giới khác được lấy thêm một chữ số thập phân, sẽ không có giá trị dữ liệu nào rơi vào ranh giới. Hai ví dụ tiếp theo sẽ đi sâu vào chi tiết về cách xây dựng biểu đồ histogram sử dụng dữ liệu liên tục và cách tạo biểu đồ histogram sử dụng dữ liệu rời rạc.

Dữ liệu sau đây là chiều cao (tính bằng inch, làm tròn đến nửa inch gần nhất) của 100 cầu thủ bóng đá bán chuyên nghiệp. Chiều cao là dữ liệu **liên tục**, vì chiều cao được đo lường.

60; 60.5; 61; 61; 61.5

63.5; 63.5; 63.5

64; 64; 64; 64; 64; 64; 64; 64.5; 64.5; 64.5; 64.5; 64.5; 64.5; 64.5; 64.5

66; 66; 66; 66; 66; 66; 66; 66; 66; 66; 66.5; 66.5; 66.5; 66.5; 66.5; 66.5; 66.5; 66.5; 66.5; 66.5; 66.5; 67; 67; 67; 67; 67; 67; 67; 67; 67; 67; 67; 67; 67.5; 67.5; 67.5; 67.5; 67.5; 67.5; 67.5

68; 68; 69; 69; 69; 69; 69; 69; 69; 69; 69; 69; 69.5; 69.5; 69.5; 69.5; 69.5

70; 70; 70; 70; 70; 70; 70.5; 70.5; 70.5; 71; 71; 71

72; 72; 72; 72.5; 72.5; 73; 73.5

74

Giá trị dữ liệu nhỏ nhất là 60. Vì dữ liệu có nhiều chữ số thập phân nhất có một chữ số thập phân (ví dụ: 61.5), chúng ta muốn điểm bắt đầu của mình có hai chữ số thập phân. Vì các số 0.5, 0.05, 0.005, v.v. là các số thuận tiện, hãy sử dụng 0.05 và trừ nó khỏi 60, giá trị nhỏ nhất, để có điểm bắt đầu thuận tiện.

60 – 0.05 = 59.95, chính xác hơn, ví dụ, 61.5 một chữ số thập phân. Vậy điểm bắt đầu là 59.95.

Giá trị lớn nhất là 74, vì vậy 74 + 0.05 = 74.05 là giá trị kết thúc.

Tiếp theo, tính độ rộng của mỗi cột hoặc khoảng lớp. Để tính độ rộng này, hãy lấy giá trị kết thúc trừ đi điểm bắt đầu và chia cho số lượng cột (bạn phải chọn số lượng cột mà bạn muốn). Giả sử bạn chọn tám cột.

Chúng ta sẽ làm tròn lên thành hai và làm cho mỗi cột hoặc khoảng lớp rộng hai đơn vị. Làm tròn lên thành hai là một cách để ngăn giá trị rơi vào ranh giới. Làm tròn đến số tiếp theo thường là cần thiết ngay cả khi nó đi ngược lại các quy tắc làm tròn tiêu chuẩn. Đối với ví dụ này, sử dụng 1.76 làm độ rộng cũng sẽ hiệu quả. Một hướng dẫn được một số người tuân theo cho số lượng cột hoặc khoảng lớp là lấy căn bậc hai của số lượng giá trị dữ liệu và sau đó làm tròn đến số nguyên gần nhất, nếu cần. Ví dụ, nếu có 150 giá trị dữ liệu, hãy lấy căn bậc hai của 150 và làm tròn thành 12 cột hoặc khoảng.

Các ranh giới là:

- 59.95
- 59.95 + 2 = 61.95
- 61.95 + 2 = 63.95
- 63.95 + 2 = 65.95
- 65.95 + 2 = 67.95
- 67.95 + 2 = 69.95
- 69.95 + 2 = 71.95
- 71.95 + 2 = 73.95
- 73.95 + 2 = 75.95
Các chiều cao từ 60 đến 61.5 inch nằm trong khoảng 59.95–61.95. Các chiều cao là 63.5 nằm trong khoảng 61.95–63.95. Các chiều cao từ 64 đến 64.5 nằm trong khoảng 63.95–65.95. Các chiều cao từ 66 đến 67.5 nằm trong khoảng 65.95–67.95. Các chiều cao từ 68 đến 69.5 nằm trong khoảng 67.95–69.95. Các chiều cao từ 70 đến 71 nằm trong khoảng 69.95–71.95. Các chiều cao từ 72 đến 73.5 nằm trong khoảng 71.95–73.95. Chiều cao 74 nằm trong khoảng 73.95–75.95.

Biểu đồ histogram sau đây hiển thị chiều cao trên trục *x* và tần suất tương đối trên trục *y*.

*Hình 
2.5*

Dữ liệu sau đây là cỡ giày của 50 sinh viên. Các kích cỡ là dữ liệu rời rạc vì cỡ giày chỉ được đo bằng các đơn vị nguyên và nửa đơn vị. Hãy xây dựng một biểu đồ histogram và tính độ rộng của mỗi cột hoặc khoảng lớp. Giả sử bạn chọn sáu cột.

9; 9; 9.5; 9.5; 10; 10; 10; 10; 10; 10; 10.5; 10.5; 10.5; 10.5; 10.5; 10.5; 10.5; 10.5

11; 11; 11; 11; 11; 11; 11; 11; 11; 11; 11; 11; 11; 11.5; 11.5; 11.5; 11.5; 11.5; 11.5; 11.5

12; 12; 12; 12; 12; 12; 12; 12.5; 12.5; 12.5; 12.5; 14

Tạo một biểu đồ histogram cho dữ liệu sau: số lượng sách được mua bởi 50 sinh viên đại học bán thời gian tại trường ABC. Số lượng sách là **dữ liệu rời rạc**, vì sách được đếm.

1; 1; 1; 1; 1; 1; 1; 1; 1; 1; 1

2; 2; 2; 2; 2; 2; 2; 2; 2; 2

3; 3; 3; 3; 3; 3; 3; 3; 3; 3; 3; 3; 3; 3; 3; 3

4; 4; 4; 4; 4; 4

5; 5; 5; 5; 5

6; 6

Mười một sinh viên mua một cuốn sách. Mười sinh viên mua hai cuốn sách. Mười sáu sinh viên mua ba cuốn sách. Sáu sinh viên mua bốn cuốn sách. Năm sinh viên mua năm cuốn sách. Hai sinh viên mua sáu cuốn sách.

Vì dữ liệu là các số nguyên, hãy trừ 0.5 khỏi 1, giá trị dữ liệu nhỏ nhất và cộng 0.5 vào 6, giá trị lớn nhất. Khi đó điểm bắt đầu là 0.5 và giá trị kết thúc là 6.5.

#### Bài toán

Tiếp theo, tính độ rộng của mỗi cột hoặc khoảng lớp. Nếu dữ liệu là rời rạc và không có quá nhiều giá trị khác nhau, độ rộng đặt các giá trị dữ liệu vào giữa cột hoặc khoảng lớp là thuận tiện nhất. Vì dữ liệu bao gồm các số 1, 2, 3, 4, 5, 6 và điểm bắt đầu là 0.5, độ rộng bằng một đặt số 1 vào giữa khoảng từ 0.5 đến 1.5, số 2 vào giữa khoảng từ 1.5 đến 2.5, số 3 vào giữa khoảng từ 2.5 đến 3.5, số 4 vào giữa khoảng từ _______ đến _______, số 5 vào giữa khoảng từ _______ đến _______, và số _______ vào giữa khoảng từ _______ đến _______ .

Tính số lượng cột như sau:

trong đó 1 là độ rộng của một cột. Do đó, số cột = 6.

Biểu đồ histogram sau đây hiển thị số lượng sách trên trục *x* và tần suất trên trục *y*.

*Hình 
2.6*

Đi đến [Phụ lục G CÁC LƯU Ý cho máy tính TI-83, 83+, 84, 84+](g-notes-for-the-ti-83-83-84-84-calculators). Có hướng dẫn sử dụng máy tính để nhập dữ liệu và tạo biểu đồ histogram tùy chỉnh. Hãy tạo biểu đồ histogram cho [Ví dụ 2.8](2-2-histograms-frequency-polygons-and-time-series-graphs#exampid2).

- Nhấn Y=. Nhấn CLEAR để xóa bất kỳ phương trình nào.
- Nhấn `STAT 1:EDIT`. Nếu `L1` có dữ liệu trong đó, hãy di chuyển mũi tên lên tên `L1`, nhấn CLEAR và sau đó di chuyển mũi tên xuống. Nếu cần, hãy làm tương tự cho `L2`.
- Vào `L1`, nhập 1, 2, 3, 4, 5, 6.
- Vào `L2`, nhập 11, 10, 16, 6, 5, 2.
- Nhấn WINDOW. Thiết lập `Xmin = .5`, `Xmax = 6.5`, `Xscl = (6.5 – .5)/6`, `Ymin = –1`, `Ymax = 20`, `Yscl = 1`, `Xres = 1`.
- Nhấn 2^nd Y=. Bắt đầu bằng cách nhấn `4:Plotsoff` ENTER.
- Nhấn 2^nd Y=. Nhấn `1:Plot1`. Nhấn ENTER. Di chuyển mũi tên xuống TYPE. Di chuyển mũi tên đến hình thứ 3 (biểu đồ histogram). Nhấn ENTER.
- Di chuyển mũi tên xuống Xlist: Nhập L1 (2^nd 1). Di chuyển mũi tên xuống Freq. Nhập L2 (2^nd 2).
- Nhấn GRAPH.
- Sử dụng phím TRACE và các phím mũi tên để kiểm tra biểu đồ histogram.
Dữ liệu sau đây là số môn thể thao mà 50 vận động viên sinh viên tham gia. Số môn thể thao là dữ liệu rời rạc vì các môn thể thao được đếm.

1; 1; 1; 1; 1; 1; 1; 1; 1; 1; 1; 1; 1; 1; 1; 1; 1; 1; 1; 1
  
2; 2; 2; 2; 2; 2; 2; 2; 2; 2; 2; 2; 2; 2; 2; 2; 2; 2; 2; 2; 2; 2
  
3; 3; 3; 3; 3; 3; 3; 3
  
20 vận động viên sinh viên chơi một môn thể thao. 22 vận động viên sinh viên chơi hai môn thể thao. Tám vận động viên sinh viên chơi ba môn thể thao.

*Điền vào chỗ trống cho câu sau.* Vì dữ liệu bao gồm các số 1, 2, 3 và điểm bắt đầu là 0,5, độ rộng là một sẽ đặt số 1 vào giữa khoảng từ 0,5 đến _____, số 2 vào giữa khoảng từ _____ đến _____, và số 3 vào giữa khoảng từ _____ đến _____.

#### Bài toán

Sử dụng tập dữ liệu này, hãy xây dựng một biểu đồ histogram.

| Số giờ các bạn cùng lớp của tôi dành để chơi trò chơi điện tử vào cuối tuần |
| --- |
| 9.95 |
| 19.5 |
| 5.5 |
| 23 |
| 20 |

Dữ liệu sau đây đại diện cho số lượng nhân viên tại các nhà hàng khác nhau ở Thành phố New York. Sử dụng dữ liệu này, hãy tạo một biểu đồ histogram.

22; 35; 15; 26; 
40; 28; 18; 20; 
25; 34; 39; 42; 
24; 22; 19; 27; 
22; 34; 40; 20; 
38; và 28

Sử dụng 10–19 làm khoảng đầu tiên.

Hãy đếm số tiền (tiền giấy và tiền lẻ) trong túi hoặc ví của bạn. Giảng viên của bạn sẽ ghi lại các số tiền đó. Cả lớp hãy cùng xây dựng một biểu đồ histogram hiển thị dữ liệu này. Hãy thảo luận xem bạn nghĩ bao nhiêu khoảng là phù hợp. Bạn có thể muốn thử nghiệm với số lượng các khoảng.

### Đa giác tần số

Đa giác tần số tương tự như biểu đồ đường, và cũng giống như cách biểu đồ đường giúp dữ liệu liên tục dễ dàng giải thích bằng hình ảnh, đa giác tần số cũng làm được như vậy.

Để xây dựng một đa giác tần số, trước tiên hãy kiểm tra dữ liệu và quyết định số lượng các khoảng, hoặc các khoảng lớp, để sử dụng trên trục *x* và trục *y*. Sau khi chọn các phạm vi phù hợp, hãy bắt đầu vẽ các điểm dữ liệu. Sau khi tất cả các điểm đã được vẽ, hãy vẽ các đoạn thẳng để nối chúng lại với nhau.

Một đa giác tần số đã được xây dựng từ bảng tần số dưới đây.

| Cận dưới | Cận trên | Tần số | Tần số lũy tích |
| --- | --- | --- | --- |
| 49.5 | 59.5 | 5 | 5 |
| 59.5 | 69.5 | 10 | 15 |
| 69.5 | 79.5 | 30 | 45 |
| 79.5 | 89.5 | 40 | 85 |
| 89.5 | 99.5 | 15 | 100 |

*Hình 
2.8*

Nhãn đầu tiên trên trục *x* là 44,5. Điều này đại diện cho một khoảng kéo dài từ 39,5 đến 49,5. Vì điểm kiểm tra thấp nhất là 54,5, khoảng này chỉ được sử dụng để cho phép biểu đồ chạm vào trục *x*. Điểm được dán nhãn 54,5 đại diện cho khoảng tiếp theo, hoặc khoảng “thực” đầu tiên từ bảng, và chứa năm điểm số. Lập luận này được áp dụng cho từng khoảng còn lại với điểm 104,5 đại diện cho khoảng từ 99,5 đến 109,5. Một lần nữa, khoảng này không chứa dữ liệu và chỉ được sử dụng để biểu đồ chạm vào trục *x*. Nhìn vào biểu đồ, chúng ta nói rằng phân phối này bị Lệch (phân phối lệch) vì một bên của biểu đồ không phản chiếu bên kia.

Hãy xây dựng một đa giác tần số về độ tuổi nhậm chức của các Tổng thống Hoa Kỳ được hiển thị trong [Bảng 2.15](2-2-histograms-frequency-polygons-and-time-series-graphs#fs-idp36852784).

| Tuổi khi nhậm chức | Tần số |
| --- | --- |
| 41.5–46.5 | 4 |
| 46.5–51.5 | 11 |
| 51.5–56.5 | 14 |
| 56.5–61.5 | 9 |
| 61.5–66.5 | 4 |
| 66.5–71.5 | 2 |

Các đa giác tần số rất hữu ích để so sánh các phân phối. Điều này đạt được bằng cách chồng các đa giác tần số được vẽ cho các tập dữ liệu khác nhau lên nhau.

Chúng ta sẽ xây dựng một đa giác tần số chồng lấp so sánh các điểm số từ [Ví dụ 2.10](2-2-histograms-frequency-polygons-and-time-series-graphs#example4) với điểm số cuối cùng của sinh viên.

| Cận dưới | Cận trên | Tần số | Tần số lũy tích |
| --- | --- | --- | --- |
| 49.5 | 59.5 | 5 | 5 |
| 59.5 | 69.5 | 10 | 15 |
| 69.5 | 79.5 | 30 | 45 |
| 79.5 | 89.5 | 40 | 85 |
| 89.5 | 99.5 | 15 | 100 |

| Cận dưới | Cận trên | Tần số | Tần số lũy tích |
| --- | --- | --- | --- |
| 49.5 | 59.5 | 10 | 10 |
| 59.5 | 69.5 | 10 | 20 |
| 69.5 | 79.5 | 30 | 50 |
| 79.5 | 89.5 | 45 | 95 |
| 89.5 | 99.5 | 5 | 100 |

*Hình 
2.9*

Chúng ta sẽ xây dựng một đa giác tần số chồng lấp so sánh các điểm số từ [Ví dụ 2.11](2-2-histograms-frequency-polygons-and-time-series-graphs#fs-idp21707856) với điểm kiểm tra cuối cùng của sinh viên trong môn đại số.

| **Cận dưới** | **Cận trên** | **Tần số** | **Tần số lũy tích** |
| --- | --- | --- | --- |
| 49.5 | 59.5 | 10 | 10 |
| 59.5 | 69.5 | 5 | 15 |
| 69.5 | 79.5 | 40 | 55 |
| 79.5 | 89.5 | 35 | 90 |
| 89.5 | 99.5 | 10 | 100 |

### Xây dựng biểu đồ chuỗi thời gian

Giả sử chúng ta muốn nghiên cứu phạm vi nhiệt độ của một khu vực trong cả một tháng. Mỗi ngày vào buổi trưa, chúng ta ghi lại nhiệt độ và viết vào nhật ký. Nhiều nghiên cứu thống kê có thể được thực hiện với dữ liệu này. Chúng ta có thể tìm số trung bình hoặc trung vị nhiệt độ trong tháng. Chúng ta có thể xây dựng một biểu đồ histogram hiển thị số ngày mà nhiệt độ đạt đến một phạm vi giá trị nhất định. Tuy nhiên, tất cả các phương pháp này đều bỏ qua một phần dữ liệu mà chúng ta đã thu thập.

Một đặc điểm của dữ liệu mà chúng ta có thể muốn xem xét là thời gian. Vì mỗi ngày được ghép cặp với chỉ số nhiệt độ cho ngày đó, chúng ta không cần phải coi dữ liệu là ngẫu nhiên. Thay vào đó, chúng ta có thể sử dụng thời gian đã cho để áp đặt một thứ tự thời gian lên dữ liệu. Một biểu đồ nhận ra thứ tự này và hiển thị nhiệt độ thay đổi như thế nào khi tháng trôi qua được gọi là biểu đồ chuỗi thời gian.

Để xây dựng một biểu đồ chuỗi thời gian, chúng ta phải xem xét cả hai phần của Tập dữ liệu theo cặp. Chúng ta bắt đầu với một hệ tọa độ Descartes tiêu chuẩn. Trục ngang được sử dụng để vẽ ngày hoặc các khoảng thời gian, và trục dọc được sử dụng để vẽ các giá trị của biến mà chúng ta đang đo lường. Bằng cách này, chúng ta làm cho mỗi điểm trên biểu đồ tương ứng với một ngày và một đại lượng được đo. Các điểm trên biểu đồ thường được nối bằng các đường thẳng theo thứ tự chúng xảy ra.

#### Bài toán

Dữ liệu sau đây cho thấy Chỉ số Giá Tiêu dùng Hàng năm, mỗi tháng, trong mười năm. Hãy xây dựng một biểu đồ chuỗi thời gian chỉ cho dữ liệu Chỉ số Giá Tiêu dùng Hàng năm.

| Năm | Tháng 1 | Tháng 2 | Tháng 3 | Tháng 4 | Tháng 5 | Tháng 6 | Tháng 7 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| **1** | 181.7 | 183.1 | 184.2 | 183.8 | 183.5 | 183.7 | 183.9 |
| **2** | 185.2 | 186.2 | 187.4 | 188.0 | 189.1 | 189.7 | 189.4 |
| **3** | 190.7 | 191.8 | 193.3 | 194.6 | 194.4 | 194.5 | 195.4 |
| **4** | 198.3 | 198.7 | 199.8 | 201.5 | 202.5 | 202.9 | 203.5 |
| **5** | 202.416 | 203.499 | 205.352 | 206.686 | 207.949 | 208.352 | 208.299 |
| **6** | 211.080 | 211.693 | 213.528 | 214.823 | 216.632 | 218.815 | 219.964 |
| **7** | 211.143 | 212.193 | 212.709 | 213.240 | 213.856 | 215.693 | 215.351 |
| **8** | 216.687 | 216.741 | 217.631 | 218.009 | 218.178 | 217.965 | 218.011 |
| **9** | 220.223 | 221.309 | 223.467 | 224.906 | 225.964 | 225.722 | 225.922 |
| **10** | 226.665 | 227.663 | 229.392 | 230.085 | 229.815 | 229.478 | 229.104 |

| Năm | Tháng 8 | Tháng 9 | Tháng 10 | Tháng 11 | Tháng 12 | Hàng năm |
| --- | --- | --- | --- | --- | --- | --- |
| **1** | 184.6 | 185.2 | 185.0 | 184.5 | 184.3 | 184.0 |
| **2** | 189.5 | 189.9 | 190.9 | 191.0 | 190.3 | 188.9 |
| **3** | 196.4 | 198.8 | 199.2 | 197.6 | 196.8 | 195.3 |
| **4** | 203.9 | 202.9 | 201.8 | 201.5 | 201.8 | 201.6 |
| **5** | 207.917 | 208.490 | 208.936 | 210.177 | 210.036 | 207.342 |
| **6** | 219.086 | 218.783 | 216.573 | 212.425 | 210.228 | 215.303 |
| **7** | 215.834 | 215.969 | 216.177 | 216.330 | 215.949 | 214.537 |
| **8** | 218.312 | 218.439 | 218.711 | 218.803 | 219.179 | 218.056 |
| **9** | 226.545 | 226.889 | 226.421 | 226.230 | 225.672 | 224.939 |
| **10** | 230.379 | 231.407 | 231.317 | 230.221 | 229.601 | 229.594 |

Bảng sau đây là một phần của tập dữ liệu từ [www.worldbank.org](https://www.worldbank.org). Sử dụng bảng để xây dựng một biểu đồ chuỗi thời gian cho lượng khí thải CO_2 của Hoa Kỳ.

| Năm | Ukraine | Vương quốc Anh | Hoa Kỳ |
| --- | --- | --- | --- |
| 1 | 352,259 | 540,640 | 5,681,664 |
| 2 | 343,121 | 540,409 | 5,790,761 |
| 3 | 339,029 | 541,990 | 5,826,394 |
| 4 | 327,797 | 542,045 | 5,737,615 |
| 5 | 328,357 | 528,631 | 5,828,697 |
| 6 | 323,657 | 522,247 | 5,656,839 |
| 7 | 272,176 | 474,579 | 5,299,563 |

#### Các ứng dụng của biểu đồ chuỗi thời gian

Biểu đồ chuỗi thời gian là công cụ quan trọng trong các ứng dụng khác nhau của thống kê. Khi ghi lại các giá trị của cùng một biến trong một khoảng thời gian dài, đôi khi rất khó để nhận ra bất kỳ xu hướng hoặc mô hình nào. Tuy nhiên, một khi các điểm dữ liệu tương tự được hiển thị bằng đồ thị, một số đặc điểm sẽ nổi bật lên. Biểu đồ chuỗi thời gian giúp các xu hướng dễ dàng được phát hiện.

### Cách KHÔNG nói dối bằng thống kê

It is important to remember that the main reason we develop many methods to present data is to develop insights into the subject that the observations represent. We want to get a "feel" for the data. Are the observations very similar or are they spread out over a wide range of values, are they clustered at one end of the spectrum or are they evenly distributed, etc. We are trying to get a visual picture of the numerical data. Soon we will develop formal mathematical measures for the data, but our visual graphical presentations can say a lot. Unfortunately, they can also say a lot that is distracting, confusing, and completely misleading about the impression the image leaves. Many years ago, Darrell Huff wrote the book How to Lie with Statistics. The book has been printed more than 25 times and has sold more than one and a half million copies. His point is sharp and uses many real-world examples designed to mislead. He wanted to make people aware of that deception, but perhaps more importantly, to educate so that others do not make the same mistakes inadvertently.

Một lần nữa, mục tiêu là khai sáng bằng các hình ảnh trực quan kể câu chuyện của dữ liệu. Biểu đồ tròn có một số vấn đề phổ biến khi được sử dụng để truyền tải thông điệp của dữ liệu. Quá nhiều miếng bánh sẽ làm người đọc choáng ngợp. Có lẽ chỉ nên có năm hoặc sáu danh mục để đưa ra ý tưởng về tầm quan trọng tương đối của từng miếng. Xét cho cùng, đây là mục tiêu của biểu đồ tròn: tập hợp con nào quan trọng nhất so với các tập hợp khác. Nếu có nhiều thành phần hơn mức này thì có lẽ một cách tiếp cận thay thế sẽ tốt hơn hoặc có lẽ một số có thể được hợp nhất thành danh mục "khác". Biểu đồ tròn không thể hiển thị những thay đổi theo thời gian, mặc dù chúng ta thấy điều này được thử nghiệm quá thường xuyên. Trong các tài liệu tài chính của liên bang, tiểu bang và thành phố, biểu đồ tròn thường được trình bày để hiển thị các thành phần doanh thu có sẵn cho cơ quan quản lý để phân bổ: thuế thu nhập, thuế bán hàng, thuế phương tiện cơ giới, v.v. Bản thân điều này là thông tin thú vị và có thể được thực hiện tốt với một biểu đồ tròn. Sai lầm xảy ra khi hai năm được đặt cạnh nhau. Vì tổng doanh thu thay đổi theo từng năm, nhưng kích thước của biểu đồ tròn là cố định, nên không có thông tin thực sự nào được cung cấp và kích thước tương đối của từng miếng bánh không thể được so sánh một cách có ý nghĩa.

Biểu đồ histogram có thể rất hữu ích trong việc hiểu dữ liệu. Nếu được trình bày đúng cách, chúng có thể là một cách trực quan nhanh chóng để trình bày xác suất của các danh mục khác nhau bằng cách so sánh trực quan đơn giản các diện tích tương đối trong mỗi danh mục. Ở đây, sai lầm, dù có chủ đích hay không, là thay đổi độ rộng của các danh mục. Tất nhiên, điều này làm cho việc so sánh với các danh mục khác trở nên bất khả thi. Nó làm tăng thêm tầm quan trọng của danh mục có độ rộng mở rộng vì nó có diện tích lớn hơn, một cách không phù hợp, và do đó về mặt hình ảnh "nói rằng" danh mục đó có xác suất xảy ra cao hơn.

Biểu đồ chuỗi thời gian có lẽ là loại bị lạm dụng nhiều nhất. Một biểu đồ của một biến nào đó theo thời gian không bao giờ nên được trình bày trên các trục thay đổi giữa chừng trên trang, dù là theo chiều dọc hay chiều ngang. Có lẽ khung thời gian được thay đổi từ năm sang tháng. Có lẽ điều này là để tiết kiệm không gian hoặc vì dữ liệu hàng tháng không có sẵn cho những năm đầu. Trong cả hai trường hợp, điều này làm rối loạn cách trình bày và phá hủy bất kỳ giá trị nào của biểu đồ. Nếu điều này không được thực hiện để cố tình gây nhầm lẫn cho người đọc, thì chắc chắn đó là công việc lười biếng hoặc cẩu thả.

Thay đổi đơn vị đo lường của trục có thể làm phẳng một sự sụt giảm hoặc làm nổi bật nó. Nếu bạn muốn hiển thị những thay đổi lớn, hãy đo biến đó bằng các đơn vị nhỏ, xu thay vì hàng ngàn đô la. Và tất nhiên để tiếp tục sự gian lận, hãy đảm bảo rằng trục không bắt đầu tại không, không. Nếu nó bắt đầu tại không, không, thì sẽ trở nên rõ ràng rằng trục đã bị thao túng.

Có lẽ bạn có một khách hàng lo ngại về sự biến thiên của danh mục đầu tư mà bạn quản lý. Một cách dễ dàng để trình bày dữ liệu là sử dụng các khoảng thời gian dài trên biểu đồ chuỗi thời gian. Sử dụng tháng hoặc tốt hơn là quý thay vì dữ liệu hàng ngày hoặc hàng tuần. Nếu điều đó không làm giảm sự biến thiên thì hãy mở rộng trục thời gian so với trục tỷ lệ hoàn vốn hoặc định giá danh mục đầu tư. Nếu bạn muốn hiển thị sự tăng trưởng ấn tượng "nhanh chóng", hãy thu nhỏ trục thời gian. Bất kỳ sự tăng trưởng tích cực nào cũng sẽ hiển thị trực quan các tỷ lệ tăng trưởng "cao". Lưu ý rằng nếu sự tăng trưởng là tiêu cực thì thủ thuật này sẽ cho thấy danh mục đầu tư đang sụp đổ với tốc độ đáng kinh ngạc.

Một lần nữa, mục tiêu của thống kê mô tả là truyền tải những hình ảnh trực quan có ý nghĩa kể câu chuyện của dữ liệu. Thao túng có chủ đích là gian lận và phi đạo đức ở mức tồi tệ nhất, nhưng ngay cả ở mức tốt nhất, việc mắc những loại sai lầm này sẽ dẫn đến sự nhầm lẫn từ phía phân tích.
