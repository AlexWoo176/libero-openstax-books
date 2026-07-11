## 10.4
 
Các mẫu ghép cặp hoặc mẫu cặp

Khi sử dụng kiểm định giả thuyết cho các mẫu ghép cặp hoặc mẫu cặp, các đặc điểm sau đây cần phải có:

1. Sử dụng lấy mẫu ngẫu nhiên đơn giản.
1. Kích thước mẫu thường nhỏ.
1. Hai phép đo (mẫu) được rút ra từ cùng một cặp cá thể hoặc đối tượng.
1. Các hiệu số được tính từ các mẫu ghép đôi hoặc mẫu cặp.
1. Các hiệu số tạo thành mẫu được sử dụng cho kiểm định giả thuyết.
1. Hoặc là các cặp ghép đôi có các hiệu số đến từ một quần thể có phân phối chuẩn, hoặc số lượng hiệu số đủ lớn để phân phối của số trung bình mẫu các hiệu số xấp xỉ chuẩn.
Trong một kiểm định giả thuyết cho các mẫu ghép cặp hoặc mẫu cặp, các đối tượng được ghép thành từng cặp và các hiệu số được tính toán. Các hiệu số này chính là dữ liệu. Số trung bình quần thể của các hiệu số, *μ_d*, sau đó được kiểm định bằng cách sử dụng kiểm định t-Student cho một số trung bình quần thể với *n* – 1 bậc tự do, trong đó *n* là số lượng các hiệu số.

#### Bài tập

** no-selfclose ** Một nghiên cứu đã được thực hiện để điều tra hiệu quả của thuật thôi miên trong việc giảm đau. Kết quả cho các đối tượng được chọn ngẫu nhiên được hiển thị trong [Bảng 10.14](10-4-matched-or-paired-samples#table-2345). Điểm số thấp hơn cho thấy ít đau hơn. Giá trị "trước" được ghép cặp với giá trị "sau" và các hiệu số được tính toán. Các hiệu số có phân phối chuẩn. Các phép đo cảm giác, trung bình, có thấp hơn sau khi thôi miên không? Hãy kiểm định ở mức ý nghĩa 5%.

| Đối tượng: | A | B | C | D | E | F | G | H |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Trước | 6.6 | 6.5 | 9.0 | 10.3 | 11.3 | 8.1 | 6.3 | 11.6 |
| Sau | 6.8 | 2.4 | 7.4 | 8.5 | 8.1 | 6.1 | 3.4 | 2.0 |

Đối với máy tính TI-83+ và TI-84, bạn có thể tính các hiệu số trước (**sau - trước**) và đưa các hiệu số vào một danh sách hoặc bạn có thể đưa dữ liệu **sau** vào danh sách thứ nhất và dữ liệu **trước** vào danh sách thứ hai. Sau đó, chuyển đến danh sách thứ ba và di chuyển lên trên tên danh sách. Nhập tên danh sách thứ 1 - tên danh sách thứ 2. Máy tính sẽ thực hiện phép trừ và bạn sẽ có các hiệu số trong danh sách thứ ba.

Sử dụng danh sách các hiệu số của bạn làm dữ liệu. Nhấn `STAT` và di chuyển sang `TESTS`. Nhấn `2:T-Test`. Di chuyển sang `Data` và nhấn `ENTER`. Di chuyển xuống và nhập `0` cho μ0μ0, tên của danh sách nơi bạn đã đặt dữ liệu, và `1` cho Freq:. Di chuyển xuống `μ`: và di chuyển sang `<` μ0μ0. Nhấn `ENTER`. Di chuyển xuống `Calculate` và nhấn `ENTER`. p-giá trị *p* là 0.0094, và thống kê kiểm định là -3.04. Thực hiện lại các hướng dẫn này ngoại trừ việc di chuyển đến `Draw` (thay vì `Calculate`). Nhấn `ENTER`.

Một nghiên cứu đã được thực hiện để điều tra xem một chế độ ăn kiêng mới hiệu quả như thế nào trong việc giảm cholesterol. Kết quả cho các đối tượng được chọn ngẫu nhiên được hiển thị trong bảng. Các hiệu số có phân phối chuẩn. Mức cholesterol của các đối tượng có thấp hơn trung bình sau khi ăn kiêng không? Hãy kiểm định ở mức 5%.

| Đối tượng | A | B | C | D | E | F | G | H | I |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Trước | 209 | 210 | 205 | 198 | 216 | 217 | 238 | 240 | 222 |
| Sau | 199 | 207 | 189 | 209 | 217 | 202 | 211 | 223 | 201 |

Một huấn luyện viên bóng mềm đại học quan tâm đến việc liệu lớp phát triển sức mạnh của trường đại học có làm tăng mức nâng tạ tối đa của các cầu thủ (tính bằng pound) hay không. Bốn cầu thủ đã tham gia nghiên cứu. Lượng tạ mà mỗi người có thể nâng được đã được ghi lại trước khi họ tham gia lớp phát triển sức mạnh. Sau khi hoàn thành lớp học, lượng tạ mà mỗi người có thể nâng được lại được đo một lần nữa. Dữ liệu như sau:

| Trọng lượng (tính bằng pound) | Cầu thủ 1 | Cầu thủ 2 | Cầu thủ 3 | Cầu thủ 4 |
| --- | --- | --- | --- | --- |
| Khối lượng tạ nâng được trước lớp học | 205 | 241 | 338 | 368 |
| Khối lượng tạ nâng được sau lớp học | 295 | 252 | 330 | 360 |

**Huấn luyện viên muốn biết liệu lớp phát triển sức mạnh có làm cho các cầu thủ khỏe hơn, trung bình hay không.**

Ghi lại dữ liệu **hiệu số**. Tính các hiệu số bằng cách trừ lượng tạ nâng được trước lớp học khỏi lượng tạ nâng được sau khi hoàn thành lớp học. Dữ liệu cho các hiệu số là: {90, 11, -8, -8}. Giả sử các hiệu số có phân phối chuẩn.

Sử dụng dữ liệu hiệu số, tính số trung bình mẫu và độ lệch chuẩn mẫu.

x¯d=21.3,sd=46.7x¯ &#175; d=21.3,sd=46.7

Dữ liệu được đưa ra ở đây cho thấy phân phối thực sự bị lệch phải. Hiệu số 90 có thể là một giá trị ngoại lệ cực đoan? Nó đang kéo số trung bình mẫu thành 21.3 (dương). Số trung bình của ba giá trị dữ liệu còn lại thực sự là âm.

Sử dụng dữ liệu hiệu số, đây trở thành một kiểm định cho một __________ (điền vào chỗ trống).

**Xác định biến ngẫu nhiên:** 

X
¯

d

X
¯

d

 hiệu số trung bình trong mức nâng tạ tối đa trên mỗi cầu thủ.

Phân phối cho kiểm định giả thuyết là *t_3*.

*H_0**μ_d**H_a**μ_d*

**Đồ thị:**

*Hình 
10.11*

**Tính p-giá trị *p*:** p-giá trị *p* là 0.2150

**Quyết định:** Nếu mức ý nghĩa là 5%, quyết định là không bác bỏ giả thuyết không, vì α < p-giá trị *p*.

**Kết luận là gì?**

Tại mức ý nghĩa 5%, từ dữ liệu mẫu, không có đủ bằng chứng để kết luận rằng lớp phát triển sức mạnh đã giúp các cầu thủ trở nên mạnh mẽ hơn, xét trên giá trị trung bình. Cần lưu ý rằng tập dữ liệu này bao gồm kích thước mẫu rất nhỏ, với khả năng có một giá trị ngoại lệ. Điều quan trọng là phải xác nhận rằng các cặp ghép đôi có các hiệu số đến từ một quần thể có phân phối chuẩn. Huấn luyện viên có thể muốn cân nhắc tăng kích thước mẫu của các cầu thủ trong nghiên cứu.

Một lớp luyện thi mới đã được thiết kế để cải thiện điểm thi SAT. Bốn học sinh đã được chọn ngẫu nhiên. Điểm số của họ trong hai bài thi thử đã được ghi lại, một trước khi học lớp này và một sau khi học. Dữ liệu được ghi lại trong [Bảng 10.18](10-4-matched-or-paired-samples#fs-idp42085840). Liệu điểm số trung bình có cao hơn sau khi học lớp này không? Hãy kiểm định ở mức 5%.

| Điểm SAT | Học sinh 1 | Học sinh 2 | Học sinh 3 | Học sinh 4 |
| --- | --- | --- | --- | --- |
| Điểm số trước lớp học | 1840 | 1960 | 1920 | 2150 |
| Điểm số sau lớp học | 1920 | 2160 | 2200 | 2100 |

Bảy học sinh lớp tám tại Trường Trung học Cơ sở Kennedy đã đo khoảng cách họ có thể đẩy tạ bằng tay thuận (tay viết) và tay yếu hơn (tay không viết). Các em nghĩ rằng mình có thể đẩy được khoảng cách bằng nhau với cả hai tay. Dữ liệu đã được thu thập và ghi lại trong [Bảng 10.19](10-4-matched-or-paired-samples#table-2535678).

| Khoảng cách (tính bằng feet) sử dụng | Học sinh 1 | Học sinh 2 | Sinh viên 3 | Sinh viên 4 | Sinh viên 5 | Sinh viên 6 | Sinh viên 7 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Tay thuận | 30 | 26 | 34 | 17 | 19 | 26 | 20 |
| Tay yếu hơn | 28 | 14 | 27 | 18 | 17 | 26 | 16 |

Thực hiện kiểm định giả thuyết để xác định xem sự khác biệt trung bình về khoảng cách giữa tay thuận và tay yếu hơn của các em học sinh có đáng kể hay không.

Ghi lại dữ liệu **hiệu số**. Tính các hiệu số bằng cách lấy khoảng cách của tay yếu hơn trừ đi khoảng cách của tay thuận. Dữ liệu cho các hiệu số là: {2, 12, 7, –1, 2, 0, 4}. Các hiệu số này có phân phối chuẩn.

Sử dụng dữ liệu hiệu số, tính số trung bình mẫu và độ lệch chuẩn mẫu. 

x
¯

d

x
¯

d

 = 3.71, 

s
d

s
d

 = 4.5.

**Biến ngẫu nhiên:** 

X
¯

d

X
¯

d

 = hiệu số trung bình về khoảng cách giữa hai tay.

**Phân phối cho kiểm định giả thuyết:** *t_6*

*H*:  = 0 *_a**μ* ≠ 0

**Đồ thị:**

*Hình 
10.12*

**Tính p-giá trị:** p-giá trị là 0.0716 (sử dụng trực tiếp dữ liệu).

(thống kê kiểm định = 2.18. p-giá trị = 0.0719 sử dụng 

(

x
¯

d

=3.71, 
s
d

=4.5.

)

(

x
¯

d

=3.71, 
s
d

=4.5.

)

**Quyết định:** Giả sử *α* = 0.05. Vì *α* < p-giá trị, không bác bỏ *H_0*.

**Kết luận:** Tại mức ý nghĩa 5%, từ dữ liệu mẫu, không có đủ bằng chứng để kết luận rằng có sự khác biệt giữa tay yếu hơn và tay thuận của các em học sinh trong việc đẩy tạ.

Năm cầu thủ bóng ném nghĩ rằng họ có thể ném cùng một khoảng cách bằng tay thuận (tay ném) và tay không thuận (tay bắt). Dữ liệu đã được thu thập và ghi lại trong [Bảng 10.20](10-4-matched-or-paired-samples#fs-idp26621360). Thực hiện kiểm định giả thuyết để xác định xem sự khác biệt trung bình về khoảng cách giữa tay thuận và tay không thuận có đáng kể hay không. Kiểm định ở mức 5%.

|  | Người chơi 1 | Người chơi 2 | Người chơi 3 | Người chơi 4 | Người chơi 5 |
| --- | --- | --- | --- | --- | --- |
| Tay thuận | 120 | 111 | 135 | 140 | 125 |
| Tay không thuận | 105 | 109 | 98 | 111 | 99 |
