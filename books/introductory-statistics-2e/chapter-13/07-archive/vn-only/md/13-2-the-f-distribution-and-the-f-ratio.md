## 13.2
 
Phân phối F và Tỷ số F

Phân phối được sử dụng cho kiểm định giả thuyết là một phân phối mới. Nó được gọi là *F* phân phối, được đặt tên theo Sir Ronald Fisher, một nhà thống kê người Anh. Thống kê *F* là một tỷ số (một phân số). Có hai tập hợp bậc tự do; một cho tử số và một cho mẫu số.

Ví dụ, nếu *F* tuân theo một *F* phân phối và số bậc tự do cho tử số là bốn, và số bậc tự do cho mẫu số là mười, thì *F* ~ *F_4,10*.

Phân phối *F* được suy ra từ phân phối t của Student. Các giá trị của phân phối *F* là bình phương của các giá trị tương ứng của phân phối *t*. Phân tích phương sai một chiều (One-Way ANOVA) mở rộng kiểm định *t* để so sánh nhiều hơn hai nhóm. Phạm vi của phép suy dẫn đó nằm ngoài trình độ của khóa học này. Tốt hơn là nên sử dụng ANOVA khi có nhiều hơn hai nhóm thay vì thực hiện các kiểm định *t* theo cặp vì việc thực hiện nhiều kiểm định sẽ làm tăng khả năng mắc sai lầm loại I.

Để tính *F* tỷ số, hai ước lượng về phương sai được thực hiện.

1. Phương sai giữa các mẫu**:** Một ước lượng của *σ*^2 là phương sai của các số trung bình mẫu nhân với *n* (khi các kích thước mẫu bằng nhau). Nếu các mẫu có kích thước khác nhau, phương sai giữa các mẫu được gán trọng số để tính đến các kích thước mẫu khác nhau. Phương sai này còn được gọi là **sự biến thiên do nghiệm thức hoặc sự biến thiên được giải thích.**
1. Phương sai trong nội bộ mẫu**:** Một ước lượng của *σ*^2 là số trung bình của các phương sai mẫu (còn được gọi là phương sai gộp). Khi các kích thước mẫu khác nhau, phương sai trong nội bộ mẫu được gán trọng số. Phương sai này còn được gọi là **sự biến thiên do sai số hoặc sự biến thiên không được giải thích.**
- *SS*_between = tổng các bình phương đại diện cho sự biến thiên giữa các mẫu khác nhau
- *SS*_within = tổng các bình phương đại diện cho sự biến thiên trong nội bộ mẫu do ngẫu nhiên.
Để tìm "tổng các bình phương" có nghĩa là cộng các đại lượng bình phương lại với nhau, trong một số trường hợp, có thể được gán trọng số. Chúng ta đã sử dụng tổng các bình phương để tính phương sai mẫu và độ lệch chuẩn mẫu trong [Thống kê mô tả](2-introduction).

*MS* có nghĩa là "bình phương trung bình." *MS*_between là phương sai giữa các nhóm, và *MS*_within là phương sai trong nội bộ nhóm.

**Tính toán Tổng các bình phương và Bình phương trung bình**

- *k* = số lượng các nhóm khác nhau
- *n_j* = kích thước của nhóm *j^th*
- *s_j* = tổng các giá trị trong nhóm *j^th*
- *n* = tổng số tất cả các giá trị kết hợp (tổng kích thước mẫu: ∑*n_j*)
- *x* = một giá trị: ∑*x* = ∑*s_j*
- Tổng các bình phương của tất cả các giá trị từ mọi nhóm kết hợp: ∑*x*^2
- Tổng các bình phương: SStotal=∑x2

(

∑x

)

2

n

SStotal=∑x2

(

∑x

)

2

n
- Sự biến thiên được giải thích: tổng các bình phương đại diện cho sự biến thiên giữa các mẫu khác nhau: *SS*_between = 

∑[ 

(
s
j
)

2

n
j

 ]−

(∑
s
j

)

2

n

∑[ 

(
s
j
)

2

n
j

 ]−

(∑
s
j

)

2

n
- Sự biến thiên không được giải thích: tổng các bình phương đại diện cho sự biến thiên trong nội bộ mẫu do ngẫu nhiên: 

S
S

within

=S
S

total

–S
S

between

S
S

within

=S
S

total

–S
S

between
- *df* cho các nhóm khác nhau (*df* cho tử số): dfbetweendfbetween = *k* – 1
- Phương trình cho các sai số trong nội bộ mẫu (*df* cho mẫu số): *df*_within = *n* – *k*
- Bình phương trung bình (ước lượng phương sai) được giải thích bởi các nhóm khác nhau: *MS*_between = 

S
S

between

df

between

S
S

between

df

between
- Bình phương trung bình (ước lượng phương sai) do ngẫu nhiên (không được giải thích): *MS*_within = 

S
S

within

d
f

within

S
S

within

d
f

within
*MS*_between và *MS*_within có thể được viết như sau:

- M
S

between

=

S
S

between

d
f

between

=

S
S

between

k−1

M
S

between

=

S
S

between

d
f

between

=

S
S

between

k−1
- M
S

within

=

S
S

within

d
f

within

=

S
S

within

n−k

M
S

within

=

S
S

within

d
f

within

=

S
S

within

n−k
Kiểm định ANOVA một chiều phụ thuộc vào thực tế là *MS*_between có thể bị ảnh hưởng bởi sự khác biệt quần thể giữa các số trung bình của nhiều nhóm. Vì *MS*_within so sánh các giá trị của mỗi nhóm với số trung bình của chính nhóm đó, thực tế là các số trung bình nhóm có thể khác nhau không ảnh hưởng đến *MS*_within.

Giả thuyết không cho rằng tất cả các nhóm đều là các mẫu từ các quần thể có cùng phân phối chuẩn. Đối thuyết cho rằng ít nhất hai trong số các nhóm mẫu đến từ các quần thể có phân phối chuẩn khác nhau. Nếu giả thuyết không đúng, *MS*_between và *MS*_within đều nên ước lượng cùng một giá trị.

Giả thuyết không cho rằng tất cả các số trung bình quần thể nhóm đều bằng nhau. Giả thuyết về các số trung bình bằng nhau ngụ ý rằng các quần thể có cùng phân phối chuẩn, vì giả định rằng các quần thể là chuẩn và chúng có các phương sai bằng nhau.

*F*-Tỷ số hoặc *F* Thống kê

F=

M
S

between

M
S

within

F=

M
S

between

M
S

within

Nếu *MS*_between và *MS*_within ước lượng cùng một giá trị (theo niềm tin rằng *H_0* là đúng), thì tỷ số *F* nên xấp xỉ bằng một. Phần lớn, chỉ các sai số chọn mẫu mới góp phần vào các biến thiên khác một. Hóa ra, *MS*_between bao gồm phương sai quần thể cộng với một phương sai được tạo ra từ sự khác biệt giữa các mẫu. *MS*_within là một ước lượng của phương sai quần thể. Vì các phương sai luôn dương, nếu giả thuyết không sai, *MS*_between thường sẽ lớn hơn *MS*_within. Khi đó tỷ số *F* sẽ lớn hơn một. Tuy nhiên, nếu hiệu ứng quần thể nhỏ, không loại trừ khả năng *MS*_within sẽ lớn hơn trong một mẫu nhất định.

Các tính toán trên được thực hiện với các nhóm có kích thước khác nhau. Nếu các nhóm có cùng kích thước, các tính toán sẽ đơn giản hóa phần nào và tỷ số *F* có thể được viết là:

Công thức tỷ số *F* khi các nhóm có cùng kích thước

F=

n⋅
s

x
¯

2

s
2

pooled

F=

n⋅
s

x
¯

2

s
2

pooled

- *n* = kích thước mẫu
- *df*_numerator = *k* – 1
- *df*_denominator = *n* – *k*
- *s*^2 pooled = trung bình của các phương sai mẫu (phương sai gộp)
- s

x
¯

2

s

x
¯

2

 = phương sai của các trung bình mẫu
Dữ liệu thường được đưa vào bảng để dễ quan sát. Kết quả ANOVA một chiều thường được hiển thị theo cách này bởi phần mềm máy tính.

| Nguồn biến thiên | Tổng các bình phương (*SS*) | Bậc tự do (*df*) | Bình phương trung bình (*MS*) | *F* |
| --- | --- | --- | --- | --- |
| Nhân tố 
(Giữa các nhóm) | *SS*(Nhân tố) | *k* – 1 | *MS*(Nhân tố) = *SS*(Nhân tố)/(*k* – 1) | *F* = *MS*(Nhân tố)/*MS*(Sai số) |
| Sai số 
(Trong nội bộ nhóm) | *SS*(Sai số) | *n* – *k* | *MS*(Sai số) = *SS*(Sai số)/(*n* – *k*) |  |
| Tổng | *SS*(Tổng) | *n* – 1 |  |  |

Ba kế hoạch ăn kiêng khác nhau sẽ được kiểm định về số trung bình giảm cân. Các mục trong bảng là mức giảm cân cho các kế hoạch khác nhau. Kết quả ANOVA một chiều được hiển thị trong [Bảng 13.2](13-2-the-f-distribution-and-the-f-ratio#eip-id2754369).

| Kế hoạch 1: *n*_1 = 4 | Kế hoạch 2: *n*_2 = 3 | Kế hoạch 3: *n*_3 = 3 |
| --- | --- | --- |
| 5 | 3,5 | 8 |
| 4,5 | 7 | 4 |
| 4 |  | 3,5 |
| 3 | 4,5 |  |

*s*_1 = 16,5, *s*_2 =15, *s*_3 = 15,5

Sau đây là các tính toán cần thiết để điền vào bảng ANOVA một chiều. Bảng được sử dụng để thực hiện kiểm định giả thuyết.

trong đó *n*_1 = 4, *n*_2 = 3, *n*_3 = 3 và *n* = *n*_1 + *n*_2 + *n*_3 = 10

Bảng ANOVA một chiều: Các công thức cho `*SS*(Total)`, `*SS*(Factor) = *SS*(Between) and *SS*(Error) = *SS*(Within)` như đã trình bày trước đó. Thông tin tương tự được cung cấp bởi chức năng kiểm định giả thuyết máy tính TI `ANOVA` trong STAT TESTS (cú pháp là `ANOVA(L1, L2, L3)` trong đó L1, L2, L3 có dữ liệu từ Kế hoạch 1, Kế hoạch 2, Kế hoạch 3 tương ứng).

| Nguồn biến thiên | Tổng các bình phương (*SS*) | Bậc tự do (*df*) | Bình phương trung bình (*MS*) | *F* |
| --- | --- | --- | --- | --- |
| Nhân tố 
(Giữa các nhóm) | *SS*(Nhân tố) 
= *SS*(Giữa các nhóm) 
= 2,2458 | *k* – 1 
= 3 nhóm – 1 
= 2 | *MS*(Nhân tố) 
= *SS*(Nhân tố)/(*k* – 1)
 = 2,2458/2 
= 1,1229 | *F* =
 *MS*(Nhân tố)/*MS*(Sai số) 
= 1,1229/2,9792 
= 0,3769 |
| Sai số 
(Trong nội bộ nhóm) | *SS*(Sai số) 
= *SS*(Trong nội bộ) 
= 20,8542 | *n* – *k* 
= 10 dữ liệu tổng cộng – 3 nhóm 
= 7 | *MS*(Sai số) 
= *SS*(Sai số)/(*n* – *k*) 
= 20,8542/7 
= 2,9792 |  |
| Tổng | *SS*(Tổng) 
= 2,2458 + 20,8542 
= 23,1 | *n* – 1 
= 10 dữ liệu tổng cộng – 1 
= 9 |  |  |

Là một phần của thí nghiệm để xem các loại che phủ đất khác nhau sẽ ảnh hưởng như thế nào đến sản lượng cà chua thái lát, sinh viên trường Marist College đã trồng cây cà chua trong các điều kiện che phủ đất khác nhau. Các nhóm gồm ba cây mỗi nhóm đã nhận một trong các nghiệm thức sau

- đất trống
- một loại vật liệu phủ đất thương mại
- nhựa đen
- rơm
- phân hữu cơ
Tất cả các cây đều phát triển trong cùng điều kiện và cùng một giống. Sinh viên đã ghi lại trọng lượng (tính bằng gram) cà chua được sản xuất bởi mỗi cây trong số *n* = 15 cây:

| Đất trống: *n*_1 = 3 | Vật liệu phủ đất: *n*_2 = 3 | Nhựa: *n*_3 = 3 | Rơm: *n*_4 = 3 | Phân hữu cơ: *n*_5 = 3 |
| --- | --- | --- | --- | --- |
| 2,625 | 5,348 | 6,583 | 7,285 | 6,277 |
| 2,997 | 5,682 | 8,560 | 6,897 | 7,818 |
| 4,915 | 5,482 | 3,830 | 9,230 | 8,677 |

Tạo bảng ANOVA một chiều.

**Kiểm định giả thuyết ANOVA một chiều luôn là kiểm định phía bên phải** vì các giá trị *F* lớn hơn nằm xa ở đuôi bên phải của đường cong phân phối *F* và có xu hướng khiến chúng ta bác bỏ *H_0*.

### Ký hiệu

Ký hiệu cho phân phối *F* là *F* ~ *F*_*df*(*num*),*df*(*denom*)

trong đó *df*(*num*) = *df*_between và *df*(*denom*) = *df*_within

Số trung bình cho phân phối *F* là 

μ=

df(denom)

df(denom)–2

μ=

df(denom)

df(denom)–2
