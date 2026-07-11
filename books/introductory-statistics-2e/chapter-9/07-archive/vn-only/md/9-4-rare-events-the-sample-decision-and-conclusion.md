## 9.4
 
Các biến cố hiếm gặp, Mẫu, Quyết định và Kết luận

Việc xác định loại phân phối, kích thước mẫu và độ lệch chuẩn đã biết hoặc chưa biết có thể giúp bạn tìm ra cách thực hiện một kiểm định giả thuyết. Tuy nhiên, có một số yếu tố khác mà bạn nên xem xét khi thực hiện một kiểm định giả thuyết.

### Các biến cố hiếm gặp

Giả sử bạn đưa ra một giả định về một thuộc tính của tổng thể (giả định này là giả thuyết không). Sau đó, bạn thu thập dữ liệu mẫu một cách ngẫu nhiên. Nếu mẫu có các thuộc tính rất **khó có khả năng** xảy ra nếu giả định là đúng, thì bạn sẽ kết luận rằng giả định của bạn về tổng thể có lẽ là không chính xác. (Hãy nhớ rằng giả định của bạn chỉ là một giả định—đó không phải là một sự thật và nó có thể đúng hoặc không đúng. Nhưng dữ liệu mẫu của bạn là thật và dữ liệu đang cho bạn thấy một sự thật dường như mâu thuẫn với giả định của bạn.)

Ví dụ, Didi và Ali đang ở bữa tiệc sinh nhật của một người bạn rất giàu có. Họ vội vàng xếp hàng đầu tiên để lấy một phần thưởng từ một chiếc giỏ cao mà họ không thể nhìn vào bên trong vì họ sẽ bị bịt mắt. Có 200 quả bóng nhựa trong giỏ và Didi cùng Ali được cho biết rằng chỉ có một quả chứa tờ 100 đô la. Didi là người đầu tiên thò tay vào giỏ và lấy ra một quả bóng. Quả bóng của cô ấy chứa một tờ 100 đô la. Xác suất xảy ra điều này là 12001200 = 0.005. Vì điều này rất khó xảy ra, Ali hy vọng rằng những gì hai người họ được kể là sai và có nhiều tờ 100 đô la hơn trong giỏ. Một "biến cố hiếm gặp" đã xảy ra (Didi lấy được tờ 100 đô la) nên Ali nghi ngờ giả định về việc chỉ có một tờ 100 đô la trong giỏ.

### Sử dụng Mẫu để Kiểm định Giả thuyết không

Sử dụng dữ liệu mẫu để tính xác suất thực tế nhận được kết quả kiểm định, được gọi là *p*-giá trị. *p*-giá trị là **xác suất mà, nếu giả thuyết không là đúng, các kết quả từ một mẫu được chọn ngẫu nhiên khác sẽ cực đoan bằng hoặc cực đoan hơn các kết quả thu được từ mẫu đã cho.**

Một *p*-giá trị lớn được tính từ dữ liệu cho thấy rằng chúng ta không nên bác bỏ giả thuyết không. *p*-giá trị càng nhỏ, kết quả càng khó xảy ra, và bằng chứng chống lại giả thuyết không càng mạnh. Chúng ta sẽ bác bỏ giả thuyết không nếu bằng chứng chống lại nó là mạnh mẽ.

**Vẽ một đồ thị thể hiện *p*-giá trị. Kiểm định giả thuyết dễ thực hiện hơn nếu bạn sử dụng đồ thị vì bạn sẽ thấy vấn đề rõ ràng hơn.**

Giả sử một thợ làm bánh tuyên bố rằng chiều cao bánh mì của anh ta trung bình hơn 15 cm. Một số khách hàng của anh ta không tin anh ta. Để thuyết phục khách hàng rằng mình đúng, người thợ làm bánh quyết định thực hiện một kiểm định giả thuyết. Anh ta nướng 10 ổ bánh mì. Chiều cao trung bình của các ổ bánh mì mẫu là 17 cm. Người thợ làm bánh biết từ việc nướng hàng trăm ổ bánh mì rằng độ lệch chuẩn về chiều cao là 0.5 cm và phân phối chiều cao là chuẩn.

Giả thuyết không có thể là *H_0*: *μ* ≤ 15 Đối thuyết là *H_a*: *μ* > 15

Cụm từ **"lớn hơn"** được dịch là ">" nên "*μ* > 15" thuộc về đối thuyết. Giả thuyết không phải mâu thuẫn với đối thuyết.

Theo Định lý giới hạn trung tâm, phân phối của các trung bình mẫu, đối với các mẫu gồm 10 ổ bánh mì, sẽ là phân phối chuẩn với trung bình *μ* = 15 và độ lệch chuẩn 

σ

n

=

0.5

10

=0.16

σ

n

=

0.5

10

=0.16
.

Giả sử giả thuyết không là đúng (chiều cao trung bình của các ổ bánh mì không quá 15 cm). Vậy thì chiều cao trung bình (17 cm) được tính từ mẫu có lớn một cách bất ngờ không? Kiểm định giả thuyết hoạt động bằng cách đặt câu hỏi về mức độ **khó có khả năng** của trung bình mẫu nếu giả thuyết không là đúng. Đồ thị cho thấy trung bình mẫu nằm cách xa bao nhiêu trên đường cong chuẩn. *p*-giá trị là xác suất mà, nếu chúng ta lấy các mẫu khác, bất kỳ trung bình mẫu nào khác sẽ nằm cách xa ít nhất 17 cm.

**Khi đó, *p*-giá trị là xác suất mà một trung bình mẫu bằng hoặc lớn hơn 17 cm khi trung bình tổng thể, trên thực tế, là 15 cm.** Chúng ta có thể tính xác suất này bằng cách sử dụng phân phối chuẩn cho các giá trị trung bình.

*Hình 
9.2*

*p*-giá trị = *P*(

x
¯

x
¯
 > 17) xấp xỉ bằng 0.

Một *p*-giá trị xấp xỉ bằng 0 cho chúng ta biết rằng rất khó có khả năng một ổ bánh mì nở cao trung bình không quá 15 cm. Tức là, gần 0% trong tất cả các ổ bánh mì sẽ cao ít nhất 17 cm **hoàn toàn do NGẪU NHIÊN** nếu chiều cao trung bình của tổng thể thực sự là 15 cm. Vì kết quả 17 cm rất **khó xảy ra (nghĩa là nó không chỉ xảy ra do ngẫu nhiên)**, chúng ta kết luận rằng bằng chứng chống lại giả thuyết không là mạnh mẽ (chiều cao trung bình tối đa là 15 cm). Có đủ bằng chứng cho thấy chiều cao trung bình thực sự của tổng thể các ổ bánh mì của người thợ làm bánh là lớn hơn 15 cm.

Một phân phối chuẩn có độ lệch chuẩn là 1. Chúng ta muốn kiểm tra một tuyên bố rằng giá trị trung bình lớn hơn 12. Một mẫu gồm 36 phần tử được lấy với trung bình mẫu là 12.5.

*H_0*: *μ* ≤ 12

*H_a*: *μ* > 12

*p*-giá trị là 0.0013

Vẽ một đồ thị thể hiện *p*-giá trị.

### Quyết định và Kết luận

Một cách có hệ thống để đưa ra quyết định bác bỏ hay không bác bỏ giả thuyết không là so sánh *p*-giá trị và một **α đã được thiết lập trước hoặc định trước (còn gọi là "mức ý nghĩa")**. Một *α* đã được thiết lập trước là xác suất của một sai lầm loại I (bác bỏ giả thuyết không khi giả thuyết không là đúng). Nó có thể được hoặc không được cung cấp cho bạn ở đầu bài toán.

Khi bạn đưa ra **quyết định** bác bỏ hay không bác bỏ *H_0*, hãy làm như sau:

- Nếu *α* > *p*-giá trị, bác bỏ *H_0*. Kết quả của dữ liệu mẫu là có ý nghĩa. Có đủ bằng chứng để kết luận rằng *H_0* là một niềm tin không chính xác và rằng **đối thuyết**, *H_a*, có thể đúng.
- Nếu *α* ≤ *p*-giá trị, không bác bỏ *H_0*. Kết quả của dữ liệu mẫu là không có ý nghĩa. Không có đủ bằng chứng để kết luận rằng đối thuyết, *H_a*, có thể đúng.
- Khi bạn "không bác bỏ *H_0*", điều đó không có nghĩa là bạn nên tin rằng *H_0* là đúng. Nó chỉ đơn giản có nghĩa là dữ liệu mẫu đã **thất bại** trong việc cung cấp đủ bằng chứng để gây nghi ngờ nghiêm trọng về tính đúng đắn của *H_o*.
**Kết luận:** Sau khi bạn đưa ra quyết định, hãy viết một **kết luận** chu đáo về các giả thuyết theo bài toán đã cho.

Khi sử dụng *p*-giá trị để đánh giá một kiểm định giả thuyết, đôi khi hữu ích khi sử dụng mẹo ghi nhớ sau đây

Nếu *p*-giá trị thấp, giả thuyết không phải bị bác bỏ.

Nếu *p*-giá trị cao, giả thuyết không phải được giữ lại.

Mẹo ghi nhớ này liên hệ một *p*-giá trị nhỏ hơn mức alpha đã thiết lập (*p* thấp) với việc bác bỏ giả thuyết không và, tương tự, liên hệ một *p*-giá trị cao hơn mức alpha đã thiết lập (*p* cao) với việc không bác bỏ giả thuyết không.

#### Bài toán

Điền vào chỗ trống.

Bác bỏ giả thuyết không khi ______________________________________.

Kết quả của dữ liệu mẫu _____________________________________.

Không bác bỏ giả thuyết không khi __________________________________________.

Kết quả của dữ liệu mẫu ____________________________________________.

Phòng thí nghiệm di truyền It’s a Boy tuyên bố các quy trình của họ cải thiện khả năng sinh con trai. Kết quả của một kiểm định tỷ lệ tổng thể đơn như sau:

*H_0**p**H_a**p*

*α* = 0.01

*p*-giá trị = 0.025

Giải thích kết quả và đưa ra kết luận bằng các thuật ngữ đơn giản, không chuyên ngành.
