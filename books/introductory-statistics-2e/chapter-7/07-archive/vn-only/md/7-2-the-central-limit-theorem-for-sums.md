## 7.2
 
Định lý giới hạn trung tâm cho các tổng

Giả sử *X* là một biến ngẫu nhiên với một phân phối có thể **đã biết hoặc chưa biết** (nó có thể là bất kỳ phân phối nào) và giả sử:

1. *μ_X* = số trung bình của *Î§*
1. *σ_Î§* = độ lệch chuẩn của *X*
Nếu bạn rút các mẫu ngẫu nhiên có kích thước *n*, thì khi *n* tăng lên, biến ngẫu nhiên Σ*X* bao gồm các tổng có xu hướng Có phân phối chuẩn và Σ*Î§* ~ *N*((*n*)(*μ_Î§*), (

n

n

)(*σ_Î§*)).

**Định lý** Định lý giới hạn trung tâm cho tổng phát biểu rằng nếu bạn liên tục rút các mẫu có kích thước nhất định (chẳng hạn như liên tục gieo mười con xúc xắc) và tính tổng của mỗi mẫu, các tổng này có xu hướng tuân theo phân phối chuẩn. Khi kích thước mẫu tăng lên, phân phối của các số trung bình càng tuân theo phân phối chuẩn chặt chẽ hơn. **Phân phối chuẩn có số trung bình bằng số trung bình ban đầu nhân với kích thước mẫu và độ lệch chuẩn bằng độ lệch chuẩn ban đầu nhân với căn bậc hai của kích thước mẫu.**

Biến ngẫu nhiên Σ*X* có điểm *z* liên quan sau đây:

1. Σ*x* là một tổng.
1. z = 

Σx–(n)(
μ
X

)

(
n

)(
σ
X

)

z = 

Σx–(n)(
μ
X

)

(
n

)(
σ
X

)

(*n*)(*μ_X*) = số trung bình của Σ*X*

(
n

)(
σ
X

)

(
n

)(
σ
X

)
 = độ lệch chuẩn của 

ΣX

ΣX
Để tìm xác suất cho các tổng trên máy tính, hãy làm theo các bước sau.

2^nd `DISTR`

2:`normalcdf`

`normalcdf`(giá trị thấp hơn của vùng, giá trị cao hơn của vùng, (*n*)(số trung bình), (

n

n

)(độ lệch chuẩn))

trong đó:

- *số trung bình* là số trung bình của phân phối ban đầu
- *độ lệch chuẩn* là độ lệch chuẩn của phân phối gốc
- Kích thước mẫu = n
Một phân phối chưa biết có số trung bình là 90 và độ lệch chuẩn là 15. Một mẫu có kích thước 80 được rút ngẫu nhiên từ quần thể.

#### Bài toán

1. Tìm xác suất để tổng của 80 giá trị (hoặc tổng của 80 giá trị đó) lớn hơn 7,500.
1. Tìm tổng lớn hơn số trung bình của các tổng là 1,5 độ lệch chuẩn.
Một phân phối chưa biết có số trung bình là 45 và độ lệch chuẩn là tám. Một kích thước mẫu là 50 được rút ngẫu nhiên từ quần thể. Tìm xác suất để tổng của 50 giá trị lớn hơn 2,400.

Để tìm bách phân vị cho các tổng trên máy tính, hãy làm theo các bước sau.

`2^nd DIStR`

`3:invNorm`

*k* = invNorm (diện tích bên trái của *k*, (*n*)(số trung bình), 

(
n

)

(
n

)
(độ lệch chuẩn))

trong đó:

- *k* là Bách phân vị thứ *k*
- *số trung bình* là số trung bình của phân phối gốc
- *độ lệch chuẩn* là độ lệch chuẩn của phân phối gốc
- *kích thước mẫu* = *n*
#### Bài toán

Trong một nghiên cứu gần đây, có báo cáo rằng độ tuổi trung bình của người dùng iPad là 34 tuổi. Giả sử độ lệch chuẩn là 15 tuổi. Kích thước mẫu là 50.

1. Số trung bình và độ lệch chuẩn cho tổng độ tuổi của người dùng iPad là bao nhiêu? Phân phối đó là gì?
1. Tìm xác suất để tổng độ tuổi nằm trong khoảng từ 1.500 đến 1,800 năm.
1. Tìm bách phân vị thứ 80 cho tổng của 50 độ tuổi.
Trong một nghiên cứu gần đây, có báo cáo rằng độ tuổi trung bình của người dùng iPad là 35 tuổi. Giả sử độ lệch chuẩn là mười tuổi. Kích thước mẫu là 39.

1. Số trung bình và độ lệch chuẩn cho tổng độ tuổi của người dùng iPad là bao nhiêu? Phân phối đó là gì?
1. Tìm xác suất để tổng độ tuổi nằm trong khoảng từ 1,400 đến 1.500 năm.
1. Tìm bách phân vị thứ 90 cho tổng của 39 độ tuổi.
#### Bài toán

Số phút trung bình cho việc tương tác với ứng dụng bởi một người dùng máy tính bảng là 8.2 phút. Giả sử độ lệch chuẩn là một phút. Lấy một mẫu có kích thước 70.

1. Số trung bình và độ lệch chuẩn cho các tổng là bao nhiêu?
1. Tìm bách phân vị thứ 95 cho tổng của mẫu. Giải thích giá trị này trong một câu hoàn chỉnh.
1. Tìm xác suất để tổng của mẫu ít nhất là mười giờ.
Số phút trung bình cho việc tương tác với ứng dụng bởi một người dùng máy tính bảng là 8.2 phút. Giả sử độ lệch chuẩn là một phút. Lấy một kích thước mẫu là 70.

1. Xác suất để tổng của mẫu nằm trong khoảng từ bảy giờ đến mười giờ là bao nhiêu? Điều này có ý nghĩa gì trong ngữ cảnh của bài toán?
1. Tìm bách phân vị thứ 84 và thứ 16 cho tổng của mẫu. Giải thích các giá trị này trong ngữ cảnh.
