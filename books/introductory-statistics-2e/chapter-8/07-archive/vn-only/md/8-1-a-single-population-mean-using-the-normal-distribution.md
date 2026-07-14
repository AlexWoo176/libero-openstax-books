## 8.1
 
Số trung bình một quần thể sử dụng phân phối chuẩn

Một khoảng tin cậy cho số trung bình quần thể, khi biết độ lệch chuẩn quần thể, dựa trên kết luận của Định lý Giới hạn Trung tâm rằng phân phối mẫu của các số trung bình mẫu tuân theo một phân phối xấp xỉ chuẩn. Giả sử mẫu của chúng ta có số trung bình là 

x
¯

 = 10

x
¯

 = 10
 và chúng ta đã xây dựng khoảng tin cậy 90% (5, 15) trong đó *EBM* = 5.

### Tính toán khoảng tin cậy

Để xây dựng một khoảng tin cậy cho một số trung bình quần thể chưa biết *μ*, **khi biết độ lệch chuẩn quần thể**, chúng ta cần 

x
¯

x
¯
 làm ước lượng cho *μ* và chúng ta cần biên độ sai số. Ở đây, biên độ sai số (*EBM*) được gọi là Giới hạn sai số cho trung bình tổng thể (viết tắt là ***EBM***). Số trung bình mẫu 

x
¯

x
¯
 là **ước lượng điểm** của số trung bình quần thể chưa biết *μ*.

**Ước lượng khoảng tin cậy sẽ có dạng:**

(ước lượng điểm - giới hạn sai số, ước lượng điểm + giới hạn sai số) hoặc, dưới dạng ký hiệu, (

x
¯

–EBM,
x
¯

+EBM

x
¯

–EBM,
x
¯

+EBM
)

Biên độ sai số (*EBM*) phụ thuộc vào Độ tin cậy (viết tắt là ***CL***). Mức tin cậy thường được coi là xác suất mà ước lượng khoảng tin cậy được tính toán sẽ chứa tham số quần thể thực. Tuy nhiên, chính xác hơn khi nói rằng mức tin cậy là phần trăm các khoảng tin cậy chứa tham số quần thể thực khi các mẫu lặp lại được lấy. Thông thường, người xây dựng khoảng tin cậy sẽ chọn mức tin cậy từ 90% trở lên vì họ muốn chắc chắn một cách hợp lý về các kết luận của mình.

Có một xác suất khác được gọi là alpha (*α*). *α* liên quan đến mức tin cậy, *CL*. *α* là xác suất mà khoảng này không chứa tham số quần thể chưa biết.
    
Về mặt toán học, *α* + *CL* = 1.

- Giả sử chúng ta đã thu thập dữ liệu từ một mẫu. Chúng ta biết số trung bình mẫu nhưng chúng ta không biết số trung bình cho toàn bộ quần thể.
- Số trung bình mẫu là bảy, và biên sai số cho số trung bình là 2,5.
x
¯

x
¯
 = 7 và *EBM* = 2,5

Khoảng tin cậy là (7 – 2,5, 7 + 2,5), và tính toán các giá trị cho kết quả (4,5, 9,5).

Nếu mức tin cậy (*CL*) là 95%, thì chúng ta nói rằng, "Chúng ta ước tính với độ tin cậy 95% rằng giá trị thực của số trung bình quần thể nằm trong khoảng từ 4,5 đến 9,5."

Giả sử chúng ta có dữ liệu từ một mẫu. Số trung bình mẫu là 15, và giới hạn sai số cho số trung bình là 3,2.

Ước lượng khoảng tin cậy cho số trung bình quần thể là bao nhiêu?

Một khoảng tin cậy cho số trung bình quần thể với độ lệch chuẩn đã biết dựa trên thực tế là các số trung bình mẫu tuân theo một phân phối xấp xỉ chuẩn. Giả sử mẫu của chúng ta có số trung bình là 

x
¯

x
¯
 = 10, và chúng ta đã xây dựng khoảng tin cậy 90% (5, 15) trong đó *EBM* = 5.

Để có được khoảng tin cậy 90%, chúng ta phải bao gồm 90% phần trung tâm của xác suất phân phối chuẩn. Nếu chúng ta bao gồm 90% phần trung tâm, chúng ta sẽ loại bỏ tổng cộng *α* = 10% ở cả hai đuôi, hoặc 5% ở mỗi đuôi, của phân phối chuẩn.

*Hình 
8.2*

Để lấy được 90% phần trung tâm, chúng ta phải đi ra 1,645 "độ lệch chuẩn" ở mỗi bên của số trung bình mẫu đã tính toán. Giá trị 1,645 là *z*-score từ một phân phối xác suất chuẩn tắc đặt một diện tích 0,90 ở trung tâm, một diện tích 0,05 ở đuôi xa bên trái và một diện tích 0,05 ở đuôi xa bên phải.

Điều quan trọng là "độ lệch chuẩn" được sử dụng phải phù hợp với tham số mà chúng ta đang ước tính, vì vậy trong phần này, chúng ta cần sử dụng độ lệch chuẩn áp dụng cho các số trung bình mẫu, đó là 

σ

n

σ

n

. Phân số 

σ

n

σ

n

 thường được gọi là "sai số chuẩn của số trung bình" để phân biệt rõ ràng độ lệch chuẩn của một số trung bình với độ lệch chuẩn quần thể *σ*.

- X
¯

X
¯
 được phân phối chuẩn, nghĩa là, 

X
¯

X
¯
 ~ *N*

(

μ
X

,
σ

n

)

(

μ
X

,
σ

n

)
.
- **Khi biết độ lệch chuẩn quần thể *σ*, chúng ta sử dụng phân phối chuẩn để tính biên sai số.**
#### Tính toán khoảng tin cậy

Để xây dựng một ước tính khoảng tin cậy cho một số trung bình quần thể chưa biết, chúng ta cần dữ liệu từ một mẫu ngẫu nhiên. Các bước để xây dựng và diễn giải khoảng tin cậy là:

- Tính số trung bình mẫu 

x
¯

x
¯
 từ dữ liệu mẫu. Hãy nhớ rằng, trong phần này chúng ta đã biết độ lệch chuẩn quần thể *σ*.
- Tìm điểm *z* tương ứng với mức độ tin cậy.
- Tính biên sai số *EBM*.
- Xây dựng khoảng tin cậy.
- Viết một câu diễn giải ước tính trong bối cảnh tình huống của bài toán. (Giải thích ý nghĩa của khoảng tin cậy, bằng ngôn từ của bài toán.)
Trước tiên, chúng ta sẽ xem xét chi tiết từng bước, sau đó minh họa quy trình bằng một số ví dụ.

#### Tìm điểm *z* cho mức tin cậy đã cho

Khi chúng ta biết độ lệch chuẩn quần thể *σ*, chúng ta sử dụng một phân phối chuẩn tắc để tính toán biên độ sai số EBM và xây dựng khoảng tin cậy. Chúng ta cần tìm giá trị của *z* sao cho diện tích bằng với mức tin cậy (ở dạng thập phân) nằm ở giữa phân phối chuẩn tắc *Z* ~ *N*(0, 1).

Mức tin cậy, *CL*, là diện tích ở giữa của phân phối chuẩn tắc. *CL* = 1 – *α*, vì vậy *α* là diện tích được chia đều giữa hai đuôi. Mỗi đuôi chứa một diện tích bằng 

α
2

α
2

.

Z-score có diện tích bên phải là 

α
2

α
2

 được ký hiệu là 

z

α
2

z

α
2

.

Ví dụ, khi *CL* = 0,95, *α* = 0,05 và 

α
2

α
2

 = 0,025; chúng ta viết 

z

α
2

z

α
2

 = *z*_0,025.

Diện tích bên phải của *z*_0,025 là 0,025 và diện tích bên trái của *z*_0,025 là 1 – 0,025 = 0,975.

z

α
2

 = 
z

0.025

 = 1.96

z

α
2

 = 
z

0.025

 = 1.96
, sử dụng máy tính, máy tính cá nhân hoặc bảng xác suất chuẩn tắc.

`invNorm`(0,975, 0, 1) = 1,96

Hãy nhớ sử dụng diện tích bên TRÁI của 

z

α
2

z

α
2

; trong chương này, hai đầu vào cuối cùng trong lệnh invNorm là 0, 1, vì bạn đang sử dụng một phân phối chuẩn tắc *Z* ~ *N*(0, 1).

#### Viết phần diễn giải

Việc diễn giải cần nêu rõ mức tin cậy (*CL*), giải thích tham số quần thể nào đang được ước tính (ở đây là **số trung bình quần thể**), và nêu khoảng tin cậy (cả hai điểm cuối). "Chúng ta ước tính với độ tin cậy ___% rằng số trung bình quần thể thực sự (bao gồm bối cảnh của bài toán) nằm trong khoảng từ ___ đến ___ (bao gồm các đơn vị thích hợp)."

Giả sử điểm số các bài kiểm tra thống kê được phân phối chuẩn với một số trung bình quần thể chưa biết và độ lệch chuẩn quần thể là ba điểm. Một mẫu ngẫu nhiên gồm 36 điểm số được lấy và cho số trung bình mẫu (điểm số trung bình mẫu) là 68. Hãy tìm một ước tính khoảng tin cậy cho điểm số trung bình quần thể của bài kiểm tra (điểm trung bình của tất cả các bài kiểm tra).

#### Bài toán

Hãy tìm khoảng tin cậy 90% cho số trung bình thực (quần thể) của điểm số bài kiểm tra thống kê.

Giả sử thời gian giao bánh pizza trung bình được phân phối chuẩn với một số trung bình quần thể chưa biết và độ lệch chuẩn quần thể là sáu phút. Một mẫu ngẫu nhiên gồm 28 nhà hàng giao bánh pizza được lấy và có thời gian giao hàng trung bình mẫu là 36 phút.

Hãy tìm một ước tính khoảng tin cậy 90% cho thời gian giao hàng trung bình quần thể.

Tỷ lệ hấp thụ riêng (SAR) cho điện thoại di động đo lường lượng năng lượng tần số vô tuyến (RF) được hấp thụ bởi cơ thể người dùng khi sử dụng thiết bị cầm tay. Mỗi điện thoại di động đều phát ra năng lượng RF. Các mẫu điện thoại khác nhau có các phép đo SAR khác nhau. Để nhận được chứng nhận từ Ủy ban Truyền thông Liên bang (FCC) để bán tại Hoa Kỳ, mức SAR cho một chiếc điện thoại di động không được quá 1,6 watt trên mỗi kilôgam. [Bảng 8.1](8-1-a-single-population-mean-using-the-normal-distribution#M02_CH08-tbl001) hiển thị mức SAR cao nhất cho một lựa chọn ngẫu nhiên các mẫu điện thoại di động được đo bởi FCC.

| Dữ liệu SAR cho một mẫu gồm 30 điện thoại di động |
| --- |
| 1,11 |
| 1,48 |
| 1,43 |
| 1,3 |
| 1,09 |
| 0,455 |
| 1,41 |
| 0,82 |
| 0,78 |
| 1,25 |

#### Bài toán

Hãy tìm khoảng tin cậy 98% cho số trung bình thực (quần thể) của Tỷ lệ hấp thụ riêng (SARs) cho điện thoại di động. Giả sử rằng độ lệch chuẩn quần thể là *σ* = 0,337.

[Bảng 8.2](8-1-a-single-population-mean-using-the-normal-distribution#M02_CH08-tbl002) hiển thị một mẫu ngẫu nhiên khác gồm 20 mẫu điện thoại di động. Sử dụng dữ liệu này để tính toán khoảng tin cậy 93% cho số trung bình SAR thực sự cho điện thoại di động được chứng nhận sử dụng tại Hoa Kỳ. Như trước đây, giả sử rằng độ lệch chuẩn quần thể là *σ* = 0,337.

| Dữ liệu SAR cho một mẫu gồm 20 điện thoại di động |
| --- |
| 1,48 |
| 0,8 |
| 1,15 |
| 1,36 |
| 0,77 |
| 0,462 |
| 1,36 |
| 1,39 |
| 1,3 |
| 0,7 |

Hãy chú ý sự khác biệt trong các khoảng tin cậy được tính toán trong [Ví dụ 8.3](8-1-a-single-population-mean-using-the-normal-distribution#example3) và bài tập [Thử sức](8-1-a-single-population-mean-using-the-normal-distribution#fs-idp77326048) sau đây. Các khoảng này khác nhau vì một số lý do: chúng được tính toán từ các mẫu khác nhau, các mẫu có kích thước khác nhau, và các khoảng được tính toán cho các mức độ tin cậy khác nhau. Mặc dù các khoảng này khác nhau, chúng không đưa ra thông tin mâu thuẫn. Ảnh hưởng của những thay đổi loại này là chủ đề của phần tiếp theo trong chương này.

#### Thay đổi mức tin cậy hoặc kích thước mẫu

#### Bài toán

Giả sử chúng ta thay đổi bài toán gốc trong [Ví dụ 8.2](8-1-a-single-population-mean-using-the-normal-distribution#eip-id1171257291379) bằng cách sử dụng mức tin cậy 95%. Hãy tìm khoảng tin cậy 95% cho số trung bình thực (quần thể) của điểm số bài kiểm tra thống kê.

Chúng ta ước tính với độ tin cậy 95% rằng số trung bình quần thể thực sự cho tất cả các điểm thi thống kê nằm trong khoảng từ 67,02 đến 68,98.

Giải thích về Mức độ tin cậy 95%:
    Chín mươi lăm phần trăm tất cả các khoảng tin cậy được xây dựng theo cách này đều chứa giá trị thực của số trung bình quần thể điểm thi thống kê.

So sánh các kết quả:
    Khoảng tin cậy 90% là (67,18, 68,82). Khoảng tin cậy 95% là (67,02, 68,98). Khoảng tin cậy 95% rộng hơn. Nếu bạn nhìn vào các biểu đồ, vì diện tích 0,95 lớn hơn diện tích 0,90, nên việc khoảng tin cậy 95% rộng hơn là điều hợp lý. Để tự tin hơn rằng khoảng tin cậy thực sự chứa giá trị thực của số trung bình quần thể cho tất cả các điểm thi thống kê, khoảng tin cậy nhất thiết phải rộng hơn.

*Hình 
8.5*

**Tóm tắt: Ảnh hưởng của việc thay đổi Mức độ tin cậy**

- Việc tăng mức độ tin cậy sẽ làm tăng biên sai số, khiến khoảng tin cậy rộng hơn.
- Việc giảm mức độ tin cậy sẽ làm giảm biên sai số, khiến khoảng tin cậy hẹp hơn.
Hãy xem lại bài tập [Thử sức](8-1-a-single-population-mean-using-the-normal-distribution#fs-idm85249264) về giao pizza. Độ lệch chuẩn quần thể là sáu phút và số trung bình mẫu thời gian giao hàng là 36 phút. Sử dụng kích thước mẫu là 20. Tìm ước tính khoảng tin cậy 95% cho số trung bình thực sự của thời gian giao pizza.

Giả sử chúng ta thay đổi bài toán gốc trong [Ví dụ 8.2](8-1-a-single-population-mean-using-the-normal-distribution#eip-id1171257291379) để xem điều gì xảy ra với biên sai số nếu kích thước mẫu bị thay đổi.

#### Bài toán

Giữ nguyên mọi thứ ngoại trừ kích thước mẫu. Sử dụng mức độ tin cậy 90% ban đầu. Điều gì xảy ra với biên sai số và khoảng tin cậy nếu chúng ta tăng kích thước mẫu và sử dụng *n* = 100 thay vì *n* = 36? Điều gì xảy ra nếu chúng ta giảm kích thước mẫu xuống *n* = 25 thay vì *n* = 36?

- x
¯

x
¯
 = 68
- *EBM* = 

(

z

α
2

)(

σ

n

)

(

z

α
2

)(

σ

n

)
- *σ* = 3; Mức độ tin cậy là 90% (*CL*=0,90); 

z

α
2

z

α
2

 = *z*_0,05 = 1,645.
Tóm tắt: Ảnh hưởng của việc thay đổi Kích thước mẫu

- Việc tăng kích thước mẫu làm cho biên sai số giảm xuống, khiến khoảng tin cậy hẹp hơn.
- Việc giảm kích thước mẫu làm cho biên sai số tăng lên, khiến khoảng tin cậy rộng hơn.
Hãy xem lại bài tập [Thử sức](8-1-a-single-population-mean-using-the-normal-distribution#fs-idm85249264) về giao pizza. Số trung bình thời gian giao hàng là 36 phút và độ lệch chuẩn quần thể là sáu phút. Giả sử kích thước mẫu được thay đổi thành 50 nhà hàng với cùng số trung bình mẫu. Tìm ước tính khoảng tin cậy 90% cho số trung bình quần thể thời gian giao hàng.

### Tính ngược để tìm giới hạn sai số hoặc số trung bình mẫu

Khi chúng ta tính toán một khoảng tin cậy, chúng ta tìm số trung bình mẫu, tính toán biên sai số và sử dụng chúng để tính khoảng tin cậy. Tuy nhiên, đôi khi khi đọc các nghiên cứu thống kê, nghiên cứu đó có thể chỉ nêu khoảng tin cậy. Nếu chúng ta biết khoảng tin cậy, chúng ta có thể tính ngược lại để tìm cả biên sai số và số trung bình mẫu.

- Từ giá trị cận trên của khoảng, trừ đi số trung bình mẫu,
- HOẶC, từ giá trị cận trên của khoảng, trừ đi giá trị cận dưới. Sau đó chia hiệu số này cho hai.
- Trừ biên sai số khỏi giá trị cận trên của khoảng tin cậy,
- HOẶC, tính số trung bình của các điểm đầu mút cận trên và cận dưới của khoảng tin cậy.
Lưu ý rằng có hai phương pháp để thực hiện mỗi phép tính. Bạn có thể chọn phương pháp dễ sử dụng hơn với thông tin bạn biết.

Giả sử chúng ta biết rằng một khoảng tin cậy là **(67,18, 68,82)** và chúng ta muốn tìm biên sai số. Chúng ta có thể biết rằng số trung bình mẫu là 68, hoặc có lẽ nguồn của chúng ta chỉ đưa ra khoảng tin cậy và không cho chúng ta biết giá trị của số trung bình mẫu.

#### Tính giới hạn sai số:

- Nếu chúng ta biết số trung bình mẫu là 68: *EBM* = 68,82 – 68 = 0,82.
- Nếu chúng ta không biết số trung bình mẫu: *EBM* = 

(68.82−67.18)

2

(68.82−67.18)

2

 = 0,82.
#### Tính số trung bình mẫu:

- Nếu chúng ta biết biên sai số:
    

x
¯

x
¯
 = 68,82 – 0,82 = 68
- Nếu chúng ta không biết biên sai số: 

x
¯

x
¯
 = 

(67.18+68.82)

2

(67.18+68.82)

2

 = 68.
Giả sử chúng ta biết rằng một khoảng tin cậy là (42,12, 47,88). Hãy tìm biên sai số và số trung bình mẫu.

### Tính toán kích thước mẫu *n*

Nếu các nhà nghiên cứu mong muốn một biên sai số cụ thể, thì họ có thể sử dụng công thức biên sai số để tính kích thước mẫu cần thiết.

Công thức biên sai số cho số trung bình quần thể khi biết độ lệch chuẩn quần thể là 
*EBM* = 

(

z

α
2

)(

σ

n

)

(

z

α
2

)(

σ

n

)
.

Công thức cho kích thước mẫu là *n* = 

z
2

σ
2

EB
M
2

z
2

σ
2

EB
M
2

, được tìm thấy bằng cách giải công thức biên sai số cho *n*.

Trong công thức này, *z* là 

z

α
2

z

α
2

, tương ứng với mức độ tin cậy mong muốn. Một nhà nghiên cứu đang lập kế hoạch cho một nghiên cứu muốn có một mức độ tin cậy và biên sai số xác định có thể sử dụng công thức này để tính toán kích thước mẫu cần thiết cho nghiên cứu.

Độ lệch chuẩn quần thể cho độ tuổi của sinh viên Foothill College là 15 năm. Nếu chúng ta muốn tự tin 95% rằng số trung bình mẫu độ tuổi nằm trong khoảng hai năm so với số trung bình quần thể thực sự về độ tuổi của sinh viên Foothill College, thì cần phải khảo sát bao nhiêu sinh viên Foothill College được chọn ngẫu nhiên?

- Từ bài toán, chúng ta biết rằng *σ* = 15 và *EBM* = 2.
- *z* = *z*_0,025 = 1,96, vì mức độ tin cậy là 95%.
- *n* = 

z
2

σ
2

EB
M
2

z
2

σ
2

EB
M
2

 = 

(

1.96

)

2

(

15

)

2

2
2

(

1.96

)

2

(

15

)

2

2
2

 = 216,09 sử dụng phương trình kích thước mẫu.
- Sử dụng *n* = 217: Luôn làm tròn kết quả LÊN số nguyên cao hơn tiếp theo để đảm bảo rằng kích thước mẫu đủ lớn.
Do đó, cần khảo sát 217 sinh viên Foothill College để tự tin 95% rằng chúng ta nằm trong khoảng hai năm so với số trung bình quần thể thực sự về độ tuổi của sinh viên Foothill College.

Độ lệch chuẩn quần thể cho chiều cao của các cầu thủ bóng rổ trung học là ba inch. Nếu chúng ta muốn tự tin 95% rằng số trung bình mẫu chiều cao nằm trong khoảng một inch so với số trung bình quần thể thực sự về chiều cao, thì cần phải khảo sát bao nhiêu học sinh được chọn ngẫu nhiên?
