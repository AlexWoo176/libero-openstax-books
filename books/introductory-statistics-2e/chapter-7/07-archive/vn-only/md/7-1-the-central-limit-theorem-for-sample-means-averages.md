## 7.1
 
Định lý giới hạn trung tâm cho các số trung bình mẫu

Giả sử *X* là một biến ngẫu nhiên với một phân phối có thể đã biết hoặc chưa biết (nó có thể là bất kỳ phân phối nào). Sử dụng một chỉ số dưới khớp với biến ngẫu nhiên, giả sử:

1. *μ**_X* = số trung bình của *X*
1. *σ**_X* = độ lệch chuẩn của *X*
Nếu bạn lấy các mẫu ngẫu nhiên có kích thước *n*, thì khi *n* tăng lên, biến ngẫu nhiên 

x
¯

x
¯
 bao gồm các số trung bình mẫu có xu hướng Có phân phối chuẩn và

Định lý giới hạn trung tâm cho các số trung bình mẫu phát biểu rằng nếu bạn liên tục lấy các mẫu với kích thước nhất định (ví dụ như gieo mười con xúc xắc nhiều lần) và tính số trung bình của chúng, các số trung bình đó có xu hướng tuân theo một phân phối chuẩn (phân phối mẫu). Khi kích thước mẫu tăng lên, phân phối của các số trung bình càng bám sát phân phối chuẩn hơn. Phân phối chuẩn có cùng số trung bình với phân phối gốc và phương sai bằng phương sai gốc chia cho kích thước mẫu. Độ lệch chuẩn là căn bậc hai của phương sai, vì vậy độ lệch chuẩn của phân phối mẫu là độ lệch chuẩn của phân phối gốc chia cho căn bậc hai của *n*. Biến *n* là số lượng các giá trị được lấy trung bình cùng nhau, không phải số lần thực hiện phép thử.

Nói một cách chính thức hơn, nếu bạn lấy các mẫu ngẫu nhiên có kích thước *n*, phân phối của biến ngẫu nhiên 

X
¯

X
¯
, bao gồm các số trung bình mẫu, được gọi là **phân phối mẫu của số trung bình**. Phân phối mẫu của số trung bình tiến dần đến phân phối chuẩn khi *n*, Kích thước mẫu, tăng lên.

Biến ngẫu nhiên 

X
¯

X
¯
 có một điểm *z* khác liên quan đến nó so với biến ngẫu nhiên *X*. Số trung bình 

x
¯

x
¯
 là giá trị của 

X
¯

X
¯
 trong một mẫu.

*μ*_*X* là số trung bình của cả *X* và 

X
¯

X
¯
.

σx=σXn=σx=σXn= độ lệch chuẩn của 

X
¯

X
¯
 và được gọi là sai số chuẩn của số trung bình.

Để tìm xác suất cho các số trung bình trên máy tính, hãy làm theo các bước sau.

`2nd DISTR``2:normalcdf`

normalcdf(

lower value of the area, upper value of the area, mean, 

standard deviation

sample size

)

normalcdf(

lower value of the area, upper value of the area, mean, 

standard deviation

sample size

)

trong đó:

- *mean* là số trung bình của phân phối gốc
- *standard deviation* là độ lệch chuẩn của phân phối gốc
- *kích thước mẫu = **n*
Một phân phối chưa biết có số trung bình là 90 và độ lệch chuẩn là 15. Các mẫu có kích thước *n* = 25 được lấy ngẫu nhiên từ quần thể.

#### Bài toán

a. Tìm xác suất để Trung bình mẫu nằm trong khoảng từ 85 đến 92.

*Hình 
7.2*

`normalcdf`(giá trị thấp hơn, giá trị cao hơn, số trung bình, sai số chuẩn của số trung bình)

Danh sách tham số được viết tắt (giá trị thấp hơn, giá trị cao hơn, *μ*, 

σ

n

σ

n

)

`normalcdf`(85,92,90,

15

25

15

25

) = 0,6997

#### Bài toán

b. Tìm giá trị cao hơn hai độ lệch chuẩn so với giá trị kỳ vọng, 90, của số trung bình mẫu.

Một phân phối chưa biết có số trung bình là 45 và độ lệch chuẩn là tám. Các mẫu có kích thước *n* = 30 được rút ngẫu nhiên từ quần thể. Hãy tìm xác suất để số trung bình mẫu nằm trong khoảng từ 42 đến 50.

#### Bài toán

Khoảng thời gian, tính bằng giờ, để một nhóm người "trên 40 tuổi" chơi một trận bóng đá được phân phối chuẩn với **số trung bình là hai giờ** và **độ lệch chuẩn là 0,5 giờ**. Một **mẫu có kích thước *n* = 50** được rút ngẫu nhiên từ quần thể. Hãy tìm xác suất để **số trung bình mẫu** nằm trong khoảng từ 1,8 giờ đến 2,3 giờ.

Khoảng thời gian làm bài SAT của một nhóm học sinh được phân phối chuẩn với số trung bình là 2,5 giờ và độ lệch chuẩn là 0,25 giờ. Một mẫu có kích thước *n* = 60 được rút ngẫu nhiên từ quần thể. Hãy tìm xác suất để số trung bình mẫu nằm trong khoảng từ hai giờ đến ba giờ.

Để tìm các bách phân vị cho các số trung bình trên máy tính, hãy làm theo các bước sau.

`2^nd DIStR`

*k* = invNorm 

(

diện tích bên trái của k, trung bình, 

standard deviation

sample size

)

(

diện tích bên trái của k, trung bình, 

standard deviation

sample size

)

trong đó:

- *k* = bách phân vị thứ *k*
- *mean* là số trung bình của phân phối gốc
- *standard deviation* là độ lệch chuẩn của phân phối gốc
- *kích thước mẫu = **n*
#### Bài toán

Trong một nghiên cứu gần đây, có báo cáo rằng độ tuổi trung bình của người dùng iPad là 34 tuổi. Giả sử độ lệch chuẩn là 15 tuổi. Lấy một mẫu có kích thước *n* = 100.

1. Số trung bình và độ lệch chuẩn cho độ tuổi trung bình mẫu của người dùng iPad là bao nhiêu?
1. Phân phối trông như thế nào?
1. Hãy tìm xác suất để độ tuổi trung bình mẫu lớn hơn 30 tuổi (độ tuổi trung bình được báo cáo của người dùng iPad trong nghiên cứu cụ thể này).
1. Hãy tìm bách phân vị thứ 95 cho độ tuổi trung bình mẫu (làm tròn đến một chữ số thập phân).
Trong một bài báo trên Flurry Blog, một khoảng trống tiếp thị trò chơi cho nam giới trong độ tuổi từ 30 đến 40 đã được xác định. Bạn đang nghiên cứu một trò chơi khởi nghiệp nhắm vào nhóm nhân khẩu học 35 tuổi. Ý tưởng của bạn là phát triển một trò chơi chiến thuật mà nam giới từ cuối độ tuổi 20 đến cuối độ tuổi 30 có thể chơi được. Dựa trên dữ liệu của bài báo, nghiên cứu ngành cho thấy người chơi chiến thuật trung bình là 28 tuổi với độ lệch chuẩn là 4,8 tuổi. Bạn lấy một mẫu gồm 100 game thủ được chọn ngẫu nhiên. Nếu thị trường mục tiêu của bạn là những người từ 29 đến 35 tuổi, bạn có nên tiếp tục với chiến lược phát triển của mình không?

#### Bài toán

Số phút trung bình cho việc tương tác với ứng dụng của một người dùng iPad là 8,2 phút. Giả sử độ lệch chuẩn là một phút. Lấy một mẫu gồm 60 người.

1. Số trung bình và độ lệch chuẩn cho số phút trung bình mẫu cho việc tương tác với ứng dụng của một người dùng iPad là bao nhiêu?
1. Sai số chuẩn của số trung bình là bao nhiêu?
1. Hãy tìm bách phân vị thứ 90 cho thời gian trung bình mẫu tính bằng phút cho việc tương tác với ứng dụng của một người dùng iPad. Giải thích giá trị này trong một câu hoàn chỉnh.
1. Hãy tìm xác suất để số trung bình mẫu nằm trong khoảng từ tám phút đến 8,5 phút.
Các lon nước ngọt cola tuyên bố chứa 16 ounce. Các lượng trong một mẫu được đo và các trị thống kê là *n* = 34, 

x
¯

x
¯
 = 16,01 ounce. Nếu các lon được làm đầy sao cho *μ* = 16,00 ounce (như trên nhãn) và *σ* = 0,143 ounce, hãy tìm xác suất để một mẫu gồm 34 lon sẽ có lượng trung bình lớn hơn 16,01 ounce. Các kết quả có gợi ý rằng các lon được làm đầy với lượng lớn hơn 16 ounce không?
