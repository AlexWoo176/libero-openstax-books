## 8.3
 
Tỷ lệ quần thể

Trong một năm bầu cử, chúng ta thấy các bài báo trên mặt báo nêu các khoảng tin cậy dưới dạng tỷ lệ hoặc phần trăm. Ví dụ, một cuộc thăm dò cho một ứng cử viên cụ thể đang tranh cử tổng thống có thể cho thấy ứng cử viên đó có 40% số phiếu bầu trong phạm vi ba điểm phần trăm (nếu mẫu đủ lớn). Thông thường, các cuộc thăm dò bầu cử được tính toán với độ tin cậy 95%, vì vậy, những người thăm dò sẽ tự tin 95% rằng tỷ lệ thực tế cử tri ủng hộ ứng cử viên đó sẽ nằm trong khoảng từ 0,37 đến 0,43: (0,40 – 0,03, 0,40 + 0,03).

Các nhà đầu tư trên thị trường chứng khoán quan tâm đến tỷ lệ thực tế các cổ phiếu tăng và giảm mỗi tuần. Các doanh nghiệp bán máy tính cá nhân quan tâm đến tỷ lệ các hộ gia đình ở Hoa Kỳ sở hữu máy tính cá nhân. Các khoảng tin cậy có thể được tính toán cho tỷ lệ thực tế các cổ phiếu tăng hoặc giảm mỗi tuần và cho tỷ lệ thực tế các hộ gia đình ở Hoa Kỳ sở hữu máy tính cá nhân.

Quy trình tìm khoảng tin cậy, kích thước mẫu, Giới hạn sai số và Độ tin cậy cho một tỷ lệ tương tự như đối với số trung bình quần thể, nhưng các công thức thì khác nhau.

**Làm thế nào để bạn biết mình đang giải quyết một bài toán về tỷ lệ?** Trước hết, **phân phối** cơ bản **là một** Phân phối nhị thức. (Không có đề cập đến số trung bình.) Nếu *X* là một biến ngẫu nhiên nhị thức, thì *X* ~ *B*(*n*, *p*) trong đó *n* là số phép thử và *p* là xác suất thành công. Để tạo thành một tỷ lệ, hãy lấy *X*, biến ngẫu nhiên cho số lần thành công và chia nó cho *n*, số lần thử (hoặc kích thước mẫu). Biến ngẫu nhiên p′p′ (đọc là "P phẩy") là tỷ lệ đó,

P
′

=
X
n

P
′

=
X
n

(Đôi khi biến ngẫu nhiên được ký hiệu là 

P
^

P
^
, đọc là "P mũ".)

Khi *n* lớn và *p* không gần bằng 0 hoặc 1, chúng ta có thể sử dụng Phân phối chuẩn để xấp xỉ phân phối nhị thức.

X~N(np,

npq

)

X~N(np,

npq

)

Nếu chúng ta chia biến ngẫu nhiên, số trung bình và độ lệch chuẩn cho *n*, chúng ta nhận được một phân phối chuẩn của các tỷ lệ với p′p′, được gọi là tỷ lệ ước tính, là biến ngẫu nhiên. (Nhớ rằng một tỷ lệ là số lần thành công chia cho *n*.)

X
n

=
P
′

~ N(

np

n

,

npq

n

)

X
n

=
P
′

~ N(

np

n

,

npq

n

)

Sử dụng đại số để đơn giản hóa: 

npq

n

=

pq

n

npq

n

=

pq

n

**p′p′ tuân theo một phân phối chuẩn cho các tỷ lệ**:
  Xn=P′~N(p,pqn)Xn=P′~N(p,pqn)

Khoảng tin cậy có dạng (p′p′ – *EBP*, p′p′ + *EBP*). *EBP* là giới hạn sai số cho tỷ lệ.

p′p′ = 

x
n

x
n

p′p′ = **tỷ lệ ước tính** của các lần thành công (p′p′ là một **ước lượng điểm** cho *p*, tỷ lệ thực tế.)

*x* = **số** lần thành công

*n* = kích thước của mẫu

**Sai số biên cho một tỷ lệ là**

EBP=(

z

α
2

)(

p
′

q
′

n

)

EBP=(

z

α
2

)(

p
′

q
′

n

)
 trong đó q′q′ = 1 – p′p′

Công thức này tương tự như công thức sai số biên cho số trung bình, ngoại trừ việc "độ lệch chuẩn phù hợp" là khác nhau. Đối với số trung bình, khi độ lệch chuẩn quần thể đã biết, độ lệch chuẩn phù hợp mà chúng ta sử dụng là 

σ

n

σ

n

. Đối với một tỷ lệ, độ lệch chuẩn phù hợp là 

p
q

n

p
q

n

.

Tuy nhiên, trong công thức sai số biên, chúng ta sử dụng 

p
′

q
′

n

p
′

q
′

n

 làm độ lệch chuẩn, thay vì 

p
q

n

p
q

n

.

Trong công thức sai số biên, **các tỷ lệ mẫu p′p′ và q′q′ là các ước lượng của các tỷ lệ quần thể chưa biết *p* và *q***. Các tỷ lệ ước lượng p′p′ và q′q′ được sử dụng vì *p* và *q* không được biết. Các tỷ lệ mẫu p′p′ và q′q′ được tính toán từ dữ liệu: p′p′ là tỷ lệ thành công ước lượng, và q′q′ là tỷ lệ thất bại ước lượng.

Khoảng tin cậy chỉ có thể được sử dụng nếu số lượng thành công np′np′ và số lượng thất bại nq′nq′ đều lớn hơn năm.

Đối với phân phối chuẩn của các tỷ lệ, công thức *z*-score như sau.

Nếu 

P
′

~N(

p,

pq

n

)

P
′

~N(

p,

pq

n

)
 thì công thức *z*-score là 

z=

p
′

−p

pq

n

z=

p
′

−p

pq

n

#### Bài toán

Giả sử một công ty nghiên cứu thị trường được thuê để ước tính tỷ lệ phần trăm người trưởng thành sống tại một thành phố lớn có điện thoại thông minh. Năm trăm cư dân trưởng thành được chọn ngẫu nhiên tại thành phố này được khảo sát để xác định xem họ có điện thoại thông minh hay không. Trong số 500 người được khảo sát, 421 người trả lời có - họ sở hữu điện thoại thông minh. Sử dụng mức tin cậy 95%, hãy tính toán một ước lượng khoảng tin cậy cho tỷ lệ thực sự của cư dân trưởng thành tại thành phố này có điện thoại thông minh.

Giả sử 250 người được chọn ngẫu nhiên được khảo sát để xác định xem họ có sở hữu máy tính bảng hay không. Trong số 250 người được khảo sát, 98 người báo cáo sở hữu máy tính bảng. Sử dụng mức tin cậy 95%, hãy tính toán một ước lượng khoảng tin cậy cho tỷ lệ thực sự của những người sở hữu máy tính bảng.

#### Bài toán

Cho một dự án lớp học, một sinh viên khoa học chính trị tại một trường đại học lớn muốn ước tính tỷ lệ phần trăm sinh viên là cử tri đã đăng ký. Anh ấy khảo sát 500 sinh viên và thấy rằng 300 người là cử tri đã đăng ký. Hãy tính khoảng tin cậy 90% cho tỷ lệ phần trăm thực sự của sinh viên là cử tri đã đăng ký, và giải thích khoảng tin cậy đó.

Một sinh viên thăm dò ý kiến trường học của họ để xem liệu học sinh trong khu học chánh có ủng hộ hay phản đối luật mới liên quan đến đồng phục học sinh hay không. Họ khảo sát 600 học sinh và thấy rằng 480 người phản đối luật mới.

a. Tính khoảng tin cậy 90% cho tỷ lệ phần trăm thực sự của học sinh phản đối luật mới, và giải thích khoảng tin cậy đó.

b. Trong một mẫu gồm 300 học sinh, 68% cho biết họ sở hữu iPod và điện thoại thông minh. Tính khoảng tin cậy 97% cho tỷ lệ phần trăm thực sự của học sinh sở hữu iPod và điện thoại thông minh.

### Khoảng tin cậy "Cộng bốn" cho *p*

Có một lượng sai số nhất định được đưa vào quá trình tính toán khoảng tin cậy cho một tỷ lệ. Vì chúng ta không biết tỷ lệ thực sự cho quần thể, chúng ta buộc phải sử dụng các ước lượng điểm để tính toán độ lệch chuẩn phù hợp của phân phối mẫu. Các nghiên cứu đã chỉ ra rằng việc ước tính độ lệch chuẩn thu được có thể bị sai sót.

May mắn thay, có một sự điều chỉnh đơn giản cho phép chúng ta tạo ra các khoảng tin cậy chính xác hơn. Chúng ta chỉ cần giả định rằng chúng ta có thêm bốn quan sát. Hai trong số các quan sát này là thành công và hai là thất bại. Khi đó, kích thước mẫu mới là *n* + 4, và số lượng thành công mới là *x* + 2.

Các nghiên cứu trên máy tính đã chứng minh hiệu quả của phương pháp này. Nó nên được sử dụng khi mức tin cậy mong muốn ít nhất là 90% và kích thước mẫu ít nhất là mười.

#### Bài toán

Một mẫu ngẫu nhiên gồm 25 sinh viên thống kê được hỏi: “Bạn có hút thuốc lá trong tuần qua không?” Sáu sinh viên báo cáo có hút thuốc trong tuần qua. Sử dụng phương pháp “cộng bốn” để tìm khoảng tin cậy 95% cho tỷ lệ thực sự của sinh viên thống kê hút thuốc.

Từ một mẫu ngẫu nhiên gồm 65 sinh viên năm nhất tại Đại học Bang, 31 sinh viên đã đăng ký chuyên ngành. Sử dụng phương pháp “cộng bốn” để tìm khoảng tin cậy 96% cho tỷ lệ thực sự của sinh viên năm nhất tại Đại học Bang đã đăng ký chuyên ngành.

#### Bài toán

Một công ty nghiên cứu thị trường đã thực hiện một cuộc khảo sát về khả năng mua xe điện trong số những người trưởng thành từ 18–29 tuổi. Trong một nhóm gồm 50 người trưởng thành từ 18–29 tuổi, 13 người cho biết họ sẽ cân nhắc việc mua xe điện. Sử dụng phương pháp “cộng bốn” để tìm khoảng tin cậy 90% cho tỷ lệ thực sự của những người trưởng thành từ 18–29 tuổi sẽ cân nhắc việc mua xe điện.

Cuộc khảo sát được tham chiếu trong [Ví dụ 8.13](8-3-a-population-proportion#eip-251) đã trao đổi với những người trưởng thành từ 18–29 tuổi trong các nhóm tập trung nhỏ hơn nhưng cũng phỏng vấn thêm các cá nhân qua điện thoại. Khi nghiên cứu hoàn tất, 588 người trưởng thành từ 18–29 tuổi đã trả lời câu hỏi về khả năng mua xe điện của họ, với 159 người nói rằng họ sẽ cân nhắc việc mua như vậy. Sử dụng phương pháp “cộng bốn” để tìm khoảng tin cậy 90% cho tỷ lệ thực sự của những người trưởng thành từ 18–29 tuổi sẽ cân nhắc việc mua xe điện dựa trên mẫu lớn hơn này. So sánh kết quả với các kết quả trong [Ví dụ 8.13](8-3-a-population-proportion#eip-251).

### Tính toán kích thước mẫu *n*

Nếu các nhà nghiên cứu mong muốn một sai số biên cụ thể, thì họ có thể sử dụng công thức giới hạn sai số để tính toán kích thước mẫu cần thiết.

Công thức giới hạn sai số cho một tỷ lệ quần thể là

- EBP=(

z

α
2

)(

p
′

q
′

n

)

EBP=(

z

α
2

)(

p
′

q
′

n

)
- Giải cho *n* cung cấp cho bạn một phương trình cho kích thước mẫu.
- n=

(

z

α
2

)

2

(
p
′

q
′

)

EB
P
2

n=

(

z

α
2

)

2

(
p
′

q
′

)

EB
P
2
#### Bài toán

Giả sử một công ty điện thoại di động muốn xác định tỷ lệ phần trăm hiện tại của khách hàng từ 50 tuổi trở lên sử dụng tin nhắn văn bản trên điện thoại di động của họ. Công ty nên khảo sát bao nhiêu khách hàng từ 50 tuổi trở lên để tự tin 90% rằng tỷ lệ ước tính (mẫu) nằm trong phạm vi ba điểm phần trăm so với tỷ lệ quần thể thực sự của khách hàng từ 50 tuổi trở lên sử dụng tin nhắn văn bản trên điện thoại di động của họ.

Giả sử một công ty tiếp thị internet muốn xác định tỷ lệ phần trăm hiện tại của khách hàng nhấp vào quảng cáo trên điện thoại thông minh của họ. Công ty nên khảo sát bao nhiêu khách hàng để tự tin 90% rằng tỷ lệ ước tính nằm trong phạm vi năm điểm phần trăm so với tỷ lệ quần thể thực sự của khách hàng nhấp vào quảng cáo trên điện thoại thông minh của họ?
