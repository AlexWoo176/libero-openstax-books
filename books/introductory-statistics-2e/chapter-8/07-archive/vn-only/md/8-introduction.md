*Hình 
8.1
 
Bạn đã bao giờ tự hỏi số trung bình các viên kẹo M&M trong một túi tại cửa hàng tạp hóa là bao nhiêu chưa? Bạn có thể sử dụng các khoảng tin cậy để trả lời câu hỏi này. (nguồn: chỉnh sửa từ tác phẩm “sweet, orange, food, green, red, color, brown, blue, colorful, yellow, chocolate, snack, dessert, toy, plain, candy, sweetness, treat, confectionery, coated, m ms, hard shell, snack food, jelly bean” / Pxhere, Phạm vi công cộng)*

Đến cuối chương này, sinh viên sẽ có thể:

- Tính toán và diễn giải các khoảng tin cậy để ước lượng số trung bình quần thể và tỷ lệ quần thể.
- Diễn giải phân phối xác suất t của Student khi kích thước mẫu thay đổi.
- Phân biệt giữa các bài toán áp dụng phân phối chuẩn và phân phối *t* của Student.
- Tính toán kích thước mẫu cần thiết để ước lượng số trung bình quần thể và tỷ lệ quần thể dựa trên mức độ tin cậy và sai số biên mong muốn.
## Giới thiệu

Giả sử bạn đang cố gắng xác định số trung bình tiền thuê một căn hộ hai phòng ngủ trong thị trấn của bạn. Bạn có thể xem phần rao vặt của tờ báo, ghi lại một vài mức giá thuê được liệt kê và tính trung bình cộng của chúng. Bạn sẽ thu được một ước lượng điểm của số trung bình thực tế. Nếu bạn đang cố gắng xác định tỷ lệ phần trăm số lần bạn ném bóng trúng rổ khi chơi bóng rổ, bạn có thể đếm số lần ném trúng và chia cho tổng số lần bạn đã ném. Trong trường hợp này, bạn sẽ thu được một ước lượng điểm cho tỷ lệ thực tế.

Chúng ta sử dụng dữ liệu mẫu để đưa ra các khái quát về một quần thể chưa biết. Phần này của thống kê học được gọi là Thống kê suy luận. **Dữ liệu mẫu giúp chúng ta đưa ra ước lượng về một Tham số quần thể**. Chúng ta nhận ra rằng ước lượng điểm rất có thể không phải là giá trị chính xác của tham số quần thể, nhưng nó gần với giá trị đó. Sau khi tính toán các ước lượng điểm, chúng ta xây dựng các ước lượng khoảng, được gọi là khoảng tin cậy.

Trong chương này, bạn sẽ học cách xây dựng và diễn giải các khoảng tin cậy. Bạn cũng sẽ học một phân phối mới, phân phối t của Student, và cách sử dụng nó với các khoảng này. Trong suốt chương, điều quan trọng cần ghi nhớ là khoảng tin cậy là một biến ngẫu nhiên. Chính tham số quần thể mới là giá trị cố định.

Nếu bạn làm việc trong bộ phận tiếp thị của một công ty giải trí, bạn có thể quan tâm đến số trung bình các bài hát mà một người tiêu dùng tải xuống mỗi tháng từ Apple Music. Nếu vậy, bạn có thể tiến hành một cuộc khảo sát và tính số trung bình mẫu, 

x
¯

x
¯
, và độ lệch chuẩn mẫu, *s*. Bạn sẽ sử dụng 

x
¯

x
¯
 để ước lượng số trung bình quần thể và *s* để ước lượng độ lệch chuẩn quần thể. Số trung bình mẫu, 

x
¯

x
¯
, là Ước lượng điểm cho số trung bình quần thể, *μ*. Độ lệch chuẩn mẫu, *s*, là ước lượng điểm cho độ lệch chuẩn quần thể, *σ*.

Mỗi giá trị trong 

x
¯

x
¯
 và *s* được gọi là một trị thống kê.

Khoảng tin cậy là một loại ước lượng khác nhưng thay vì chỉ là một con số, nó là một khoảng các con số. Nó cung cấp một phạm vi các giá trị hợp lý mà chúng ta kỳ vọng tham số quần thể sẽ nằm trong đó. Không có gì đảm bảo rằng một khoảng tin cậy nhất định sẽ chứa tham số, nhưng có một xác suất thành công có thể dự đoán được.

Giả sử, đối với ví dụ về Apple Music, chúng ta không biết số trung bình quần thể *μ*, nhưng chúng ta biết rằng độ lệch chuẩn quần thể là *σ* = 1 và kích thước mẫu của chúng ta là 100. Khi đó, theo định lý giới hạn trung tâm, độ lệch chuẩn cho số trung bình mẫu là

Quy tắc thực nghiệm, áp dụng cho các phân phối có hình chuông, cho biết rằng trong khoảng 95% các mẫu, số trung bình mẫu, 

x
¯

x
¯
, sẽ nằm trong phạm vi hai độ lệch chuẩn của số trung bình quần thể *μ*. Đối với ví dụ về Apple Music của chúng ta, hai độ lệch chuẩn là (2)(0.1) = 0.2. Số trung bình mẫu 

x
¯

x
¯
 có khả năng nằm trong phạm vi 0.2 đơn vị so với *μ*.

Vì 

x
¯

x
¯
 nằm trong phạm vi 0.2 đơn vị so với *μ* (giá trị chưa biết), nên *μ* có khả năng nằm trong phạm vi 0.2 đơn vị so với 

x
¯

x
¯
 trong 95% các mẫu. Số trung bình quần thể *μ* nằm trong một khoảng có số dưới được tính bằng cách lấy số trung bình mẫu trừ đi hai độ lệch chuẩn (2)(0.1) và số trên được tính bằng cách lấy số trung bình mẫu cộng với hai độ lệch chuẩn. Nói cách khác, *μ* nằm giữa 

x
¯

 − 0.2

x
¯

 − 0.2
 và 

x
¯

 + 0.2

x
¯

 + 0.2
 trong 95% tất cả các mẫu.

Đối với ví dụ về Apple Music, giả sử một mẫu tạo ra số trung bình mẫu 

x
¯

 = 2

x
¯

 = 2
. Khi đó, số trung bình quần thể chưa biết *μ* nằm giữa

x
¯

−0.2=2−0.2=1.8

x
¯

−0.2=2−0.2=1.8
 và 

x
¯

+0.2=2+0.2=2.2

x
¯

+0.2=2+0.2=2.2

Chúng ta nói rằng chúng ta **tin cậy 95%** rằng số trung bình quần thể chưa biết về số bài hát được tải xuống từ Apple Music mỗi tháng nằm trong khoảng từ 1.8 đến 2.2. **Khoảng tin cậy 95% là (1.8, 2.2).**

Khoảng tin cậy 95% ngụ ý hai khả năng. Hoặc là khoảng (1.8, 2.2) chứa số trung bình thực tế *μ*, hoặc mẫu của chúng ta tạo ra một 

x
¯

x
¯
 không nằm trong phạm vi 0.2 đơn vị so với số trung bình thực tế *μ*. Khả năng thứ nhất xảy ra đối với 95% các mẫu được chọn tốt. Điều quan trọng cần nhớ là khả năng thứ hai xảy ra đối với 5% các mẫu, ngay cả khi các quy trình chính xác đã được tuân thủ.

Hãy nhớ rằng một khoảng tin cậy được tạo ra cho một tham số quần thể chưa biết như số trung bình quần thể, *μ*. Các khoảng tin cậy cho một số tham số có dạng:

**(ước lượng điểm – sai số biên, ước lượng điểm + ** Biên độ lỗi**)**

Sai số biên phụ thuộc vào mức độ tin cậy hoặc tỷ lệ phần trăm tin cậy và sai số chuẩn của số trung bình.

Khi bạn đọc báo và tạp chí, một số báo cáo sẽ sử dụng cụm từ "sai số biên". Các báo cáo khác sẽ không sử dụng cụm từ đó, nhưng bao gồm một khoảng tin cậy dưới dạng ước lượng điểm cộng hoặc trừ sai số biên. Đây là hai cách diễn đạt cùng một khái niệm.

Mặc dù tài liệu này chỉ đề cập đến các khoảng tin cậy đối xứng, nhưng vẫn có các khoảng tin cậy không đối xứng (ví dụ: khoảng tin cậy cho độ lệch chuẩn).

Hãy nhờ giảng viên của bạn ghi lại số bữa ăn mà mỗi sinh viên trong lớp bạn ăn ngoài mỗi tuần. Giả sử rằng độ lệch chuẩn được biết là ba bữa. Hãy xây dựng một khoảng tin cậy xấp xỉ 95% cho số trung bình thực tế các bữa ăn mà sinh viên ăn ngoài mỗi tuần.

1. Tính số trung bình mẫu.
1. Cho *σ* = 3 và *n* = số sinh viên được khảo sát.
1. Xây dựng khoảng 

(

x
¯

−2

’

σ

n

, 
x
¯

 + 
2
’

σ

n

)

(

x
¯

−2

’

σ

n

, 
x
¯

 + 
2
’

σ

n

)
.
Chúng ta nói rằng chúng ta tin cậy khoảng 95% rằng số trung bình thực tế các bữa ăn mà sinh viên ăn ngoài trong một tuần nằm trong khoảng từ __________ đến ___________.
