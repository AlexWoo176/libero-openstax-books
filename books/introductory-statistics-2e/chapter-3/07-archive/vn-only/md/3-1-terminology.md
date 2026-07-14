## 3.1
 
Thuật ngữ

Xác suất là một thước đo liên quan đến mức độ chắc chắn của chúng ta về các kết quả của một phép thử hoặc hoạt động cụ thể. Một Thí nghiệm là một hoạt động có kế hoạch được thực hiện trong các điều kiện được kiểm soát. Nếu kết quả không được xác định trước, thì phép thử đó được gọi là phép thử **ngẫu nhiên**. Tung một đồng xu cân đối hai lần là một ví dụ về một phép thử.

Kết quả của một phép thử được gọi là một Kết cục / Kết quả. Không gian mẫu của một phép thử là tập hợp tất cả các kết quả có thể xảy ra. Ba cách để biểu diễn không gian mẫu là: liệt kê các kết quả có thể xảy ra, tạo sơ đồ cây, hoặc tạo sơ đồ Venn. Chữ cái in hoa *S* được sử dụng để ký hiệu không gian mẫu. Ví dụ, nếu bạn tung một đồng xu cân đối, *S* = {*H*, *T*} trong đó *H* = mặt ngửa và *T* = mặt sấp là các kết quả.

Một Biến cố là bất kỳ sự kết hợp nào của các kết quả. Các chữ cái in hoa như *A* và *B* đại diện cho các biến cố. Ví dụ, nếu phép thử là tung một đồng xu cân đối, biến cố *A* có thể là nhận được tối đa một mặt ngửa. Xác suất của một biến cố *A* được viết là *P*(*A*).

Xác suất của bất kỳ kết quả nào là Tần suất tương đối dài hạn của kết quả đó. **Các xác suất nằm trong khoảng từ không đến một, bao gồm cả hai giá trị này** (nghĩa là, không, một và tất cả các số nằm giữa các giá trị này). *P*(*A*) = 0 có nghĩa là biến cố *A* không bao giờ có thể xảy ra. *P*(*A*) = 1 có nghĩa là biến cố *A* luôn luôn xảy ra. *P*(*A*) = 0,5 có nghĩa là biến cố *A* có khả năng xảy ra hoặc không xảy ra là như nhau. Ví dụ, nếu bạn tung một đồng xu cân đối nhiều lần (từ 20 đến 2.000 đến 20.000 lần), tần suất tương đối của mặt ngửa sẽ tiến dần đến 0,5 (xác suất của mặt ngửa).

Đồng khả năng có nghĩa là mỗi kết quả của một phép thử xảy ra với xác suất bằng nhau. Ví dụ, nếu bạn gieo một con xúc xắc sáu mặt Công bằng / Cân bằng, mỗi mặt (1, 2, 3, 4, 5, hoặc 6) đều có khả năng xảy ra như nhau. Nếu bạn tung một đồng xu cân đối, mặt Ngửa (*H*) và mặt Sấp (*T*) có khả năng xảy ra như nhau. Nếu bạn đoán ngẫu nhiên câu trả lời cho một câu hỏi đúng/sai trong bài kiểm tra, bạn có khả năng chọn một câu trả lời đúng hoặc một câu trả lời sai là như nhau.

**Để tính xác suất của một biến cố *A* khi tất cả các kết quả trong không gian mẫu đều đồng khả năng**, hãy đếm số lượng kết quả cho biến cố *A* và chia cho tổng số kết quả trong không gian mẫu. Ví dụ, nếu bạn tung một đồng xu 10 xu cân đối và một đồng xu 5 xu cân đối, không gian mẫu là {*HH*, *TH*, *HT*, *TT*} trong đó *T* = mặt sấp và *H* = mặt ngửa. Không gian mẫu có bốn kết quả. *A* = nhận được một mặt ngửa. Có hai kết quả thỏa mãn điều kiện này {*HT*, *TH*}, vì vậy *P*(*A*) = 242424 = 0,5.

Giả sử bạn gieo một con xúc xắc sáu mặt cân đối, với các số {1, 2, 3, 4, 5, 6} trên các mặt của nó. Gọi biến cố *E* = gieo được một số ít nhất là năm. Có hai kết quả {5, 6}. *P*(*E*) = 262626. Nếu bạn chỉ gieo xúc xắc vài lần, bạn sẽ không ngạc nhiên nếu kết quả quan sát được của bạn không khớp với xác suất. Nếu bạn gieo xúc xắc một số lần rất lớn, bạn sẽ mong đợi rằng, nhìn chung, 262626 số lần gieo sẽ dẫn đến kết quả là "ít nhất là năm". Bạn sẽ không mong đợi chính xác 262626. Tần suất tương đối dài hạn của việc đạt được kết quả này sẽ tiến gần đến xác suất lý thuyết là 262626 khi số lần lặp lại ngày càng lớn.

Đặc điểm quan trọng này của các phép thử xác suất được gọi là Luật số lớn, phát biểu rằng khi số lần lặp lại của một phép thử tăng lên, tần suất tương đối thu được trong phép thử có xu hướng ngày càng gần với xác suất lý thuyết. Mặc dù các kết quả không xảy ra theo bất kỳ mô hình hoặc thứ tự cố định nào, nhìn chung, tần suất tương đối quan sát được trong dài hạn sẽ tiến gần đến xác suất lý thuyết. (Từ **thực nghiệm** thường được sử dụng thay cho từ quan sát được.)

Điều quan trọng cần nhận ra là trong nhiều tình huống, các kết quả không có khả năng xảy ra như nhau. Một đồng xu hoặc con xúc xắc có thể Không công bằng, hoặc **bị chệch**. Hai giáo sư toán học ở châu Âu đã cho sinh viên thống kê của họ kiểm tra đồng xu một Euro của Bỉ và phát hiện ra rằng trong 250 lần thử, mặt ngửa xuất hiện 56% thời gian và mặt sấp xuất hiện 44% thời gian. Dữ liệu dường như cho thấy đồng xu này không phải là đồng xu cân đối; cần nhiều lần lặp lại hơn để đưa ra kết luận chính xác hơn về sự chệch như vậy. Một số con xúc xắc có thể bị chệch. Hãy nhìn vào những con xúc xắc trong một trò chơi bạn có ở nhà; các chấm trên mỗi mặt thường là những lỗ nhỏ được khắc ra và sau đó sơn lên để làm cho các chấm có thể nhìn thấy được. Con xúc xắc của bạn có thể bị chệch hoặc không; có khả năng các kết quả có thể bị ảnh hưởng bởi sự khác biệt nhỏ về trọng lượng do số lượng lỗ khác nhau trên các mặt. Các sòng bạc đánh bạc kiếm được rất nhiều tiền dựa trên kết quả từ việc gieo xúc xắc, vì vậy xúc xắc sòng bạc được làm khác đi để loại bỏ sự chệch. Xúc xắc sòng bạc có các mặt phẳng; các lỗ được lấp đầy hoàn toàn bằng sơn có cùng mật độ với vật liệu làm ra con xúc xắc để mỗi mặt có khả năng xảy ra như nhau. Sau này chúng ta sẽ học các kỹ thuật để sử dụng khi làm việc với xác suất cho các biến cố không có khả năng xảy ra như nhau.

Biến cố "HOẶC":Một kết quả nằm trong biến cố *A* HOẶC *B* nếu kết quả đó nằm trong *A* hoặc nằm trong *B* hoặc nằm trong cả *A* và *B*.
Biến cố A HOẶC B cũng có thể được viết là A Hợp B, với ký hiệu như sau:
𝐴 ∪𝐵A∪BA∪B
Ví dụ, gọi A = {1, 2, 3, 4, 5} và B = {4, 5, 6, 7, 8}.
Khi đó 𝐴 ∪𝐵A∪BA∪B = {1, 2, 3, 4, 5, 6, 7, 8}. Lưu ý rằng 4 và 5 KHÔNG được liệt kê hai lần.

Biến cố "VÀ":Một kết quả nằm trong biến cố *A* VÀ *B* nếu kết quả đó nằm trong cả *A* và *B* cùng một lúc.
Biến cố *A* VÀ *B* cũng có thể được viết là *A* Giao *B*, với ký hiệu như sau:
𝐴 ∩𝐵A∩BA∩B
Ví dụ, gọi *A* và *B* lần lượt là {1, 2, 3, 4, 5} và {4, 5, 6, 7, 8}.
Khi đó 𝐴 ∩𝐵A∩BA∩B= {4, 5}.

Biến cố bù của A được ký hiệu là *A′* (đọc là "*A* phẩy"). *A′* bao gồm tất cả các kết quả **KHÔNG** nằm trong *A*. Lưu ý rằng *P*(*A*) + *P*(*A′*) = 1. Ví dụ, gọi *S* = {1, 2, 3, 4, 5, 6} và gọi *A* = {1, 2, 3, 4}. Khi đó, *A′* = {5, 6}. *P*(*A*) = 464646, *P*(*A′*) = 262626, và *P*(*A*) + *P*(*A′*) = 46+2646+2646 + 26 = 1

Xác suất
 có điều kiện
 của
 *A*
 khi biết
 *B*
 được viết là
 *P*
 (
 *A*
 |
 *B*
 ).
 *P*
 (
 *A*
 |
 *B*
 ) là xác suất để biến cố
 *A*
 xảy ra khi biết biến cố
 *B*
 đã xảy ra rồi.
 **Điều kiện thu hẹp không gian mẫu**
 . Chúng ta tính xác suất của
 *A*
 từ không gian mẫu đã được thu hẹp
 *B*
 . Công thức để tính
 *P*
 (
 *A*
 |
 *B*
 ) là
 *P*
 (
 *A*
 |
 *B*
 ) =
 
P⁡(A VÀ B)P⁡(B)P(A VÀ B)P(B)

 trong đó
 *P*
 (
 *B*
 ) lớn hơn 0.

Ví dụ, giả sử chúng ta gieo một con xúc xắc sáu mặt cân đối. Không gian mẫu *S* = {1, 2, 3, 4, 5, 6}. Gọi *A* = mặt là 2 hoặc 3 và *B* = mặt là số chẵn (2, 4, 6). Để tính *P*(*A*|*B*), chúng ta đếm số lượng kết quả 2 hoặc 3 trong không gian mẫu *B* = {2, 4, 6}. Sau đó, chúng ta chia số đó cho số lượng kết quả *B* (thay vì *S*).

Chúng ta nhận được cùng một kết quả bằng cách sử dụng công thức. Hãy nhớ rằng *S* có sáu kết quả.

*P**A**B*𝑃⁡(𝐴VÀ 𝐵)𝑃⁡(𝐵)=(số kết quả là 2 oặc 3 à hẵn trong 𝑆)6(số kết quả hẵn trong 𝑆)6=1636=13P⁡(AVÀB)P⁡(B)=(số kết quả là 2 hoặc 3 và chẵn trong S)6(số kết quả là chẵn trong S)6=1636=13P(AVÀB)P(B)=(số kết quả là 2 hoặc 3 và chẵn trong S)6(số kết quả là chẵn trong S)6=1636=13

Hiểu về Thuật ngữ và Ký hiệuĐiều quan trọng là phải đọc kỹ từng bài toán để suy nghĩ và hiểu các biến cố là gì. Hiểu cách diễn đạt là bước đầu tiên rất quan trọng trong việc giải các bài toán xác suất. Hãy đọc lại bài toán nhiều lần nếu cần thiết. Xác định rõ biến cố quan tâm. Xác định xem có điều kiện nào được nêu trong cách diễn đạt cho thấy xác suất là có điều kiện hay không; hãy xác định cẩn thận điều kiện đó, nếu có.

#### Bài toán

Không gian mẫu *S* là các số nguyên bắt đầu từ một và nhỏ hơn 20.

1. *S* = _____________________________
Gọi biến cố *A* = các số chẵn và biến cố *B* = các số lớn hơn 13.
1. *A* = _____________________, *B* = _____________________
1. *P*(*A*) = _____________, *P*(*B*) = ________________
1. *A* và *B* = ____________________, *A* hoặc *B* = ________________
1. *P*(*A* và *B*) = _________, *P*(*A* hoặc *B*) = _____________
1. *A′* = _____________, *P*(*A′*) = _____________
1. *P*(*A*) + *P*(*A′*) = ____________
1. *P*(*A*|*B*) = ___________, *P*(*B*|*A*) = _____________; các xác suất này có bằng nhau không?
Không gian mẫu *S* là tất cả các cặp có thứ tự của hai số nguyên, số thứ nhất từ một đến ba và số thứ hai từ một đến bốn (Ví dụ: (1, 4)).

1. *S* = _____________________________

Gọi biến cố *A* = tổng là số chẵn và biến cố *B* = số đầu tiên là số nguyên tố.
1. *A* = _____________________, *B* = _____________________
1. *P*(*A*) = _____________, *P*(*B*) = ________________
1. *A* và *B* = ____________________, *A* hoặc *B* = ________________
1. *P*(*A* và *B*) = _________, *P*(*A* hoặc *B*) = _____________
1. *B′* = _____________, *P*(*B′*) = _____________
1. *P*(*A*) + *P*(*A′*) = ____________
1. *P*(*A*|*B*) = ___________, *P*(*B*|*A*) = _____________; các xác suất này có bằng nhau không?
#### Bài toán

Một con xúc xắc cân đối, sáu mặt được gieo. Hãy mô tả không gian mẫu *S*, xác định từng biến cố sau đây bằng một tập con của *S* và tính xác suất của nó (một kết quả là số chấm xuất hiện).

1. Biến cố *T* = kết quả là hai.
1. Biến cố *A* = kết quả là một số chẵn.
1. Biến cố *B* = kết quả nhỏ hơn bốn.
1. Biến cố đối của *A*.
1. *A* VỚI ĐIỀU KIỆN *B*
1. *B* VỚI ĐIỀU KIỆN *A*
1. *A* VÀ *B*
1. *A* HOẶC *B*
1. *A* HOẶC *B′*
1. Biến cố *N* = kết quả là một số nguyên tố.
1. Biến cố *I* = kết quả là bảy.
Một số được chọn ngẫu nhiên từ 1 đến 10. Hãy mô tả không gian mẫu *S*, xác định từng biến cố sau đây bằng một tập con của S, và tính xác suất của nó (một kết quả là số được chọn).

1. Biến cố *F* = kết quả là 5.
1. Biến cố *A* = con số lớn hơn 6.
1. Biến cố *B* = con số là số lẻ.
1. Biến cố đối của biến cố *B*.
1. *A* VỚI ĐIỀU KIỆN *B*.
1. *B* VỚI ĐIỀU KIỆN *A*.
1. *A* HOẶC *B*.
1. *A’* HOẶC *B*.
1. Biến cố *P* = kết quả là một hợp số.
1. Biến cố *M* = số đó là bội số của 3.
[Bảng 3.1](3-1-terminology#ch03_M02-tbl001) mô tả phân phối của một mẫu ngẫu nhiên *S* gồm 100 cá nhân, được tổ chức theo giới tính khi sinh và việc họ thuận tay phải hay tay trái.

|  | Thuận tay phải | Thuận tay trái |
| --- | --- | --- |
| Nam giới | 43 | 9 |
| Nữ giới | 44 | 4 |

#### Bài toán

Hãy ký hiệu các biến cố *M* = đối tượng là nam, *F* = đối tượng là nữ, *R* = đối tượng thuận tay phải, *L* = đối tượng thuận tay trái. Hãy tính các xác suất sau:

1. *P*(*M*)
1. *P*(*F*)
1. *P*(*R*)
1. *P*(*L*)
1. *P*(*M* VÀ *R*)
1. *P*(*F* VÀ *L*)
1. *P*(*M* HOẶC *F*)
1. *P*(*M* HOẶC *R*)
1. *P*(*F* HOẶC *L*)
1. *P*(*M'*)
1. *P*(*R*|*M*)
1. *P*(*F*|*L*)
1. *P*(*L*|*F*)
Bảng mô tả phân phối của một mẫu ngẫu nhiên S gồm 100 cá nhân, được tổ chức theo giới tính và việc họ thích trà hay cà phê.

|  | **Trà** | **Cà phê** |
| --- | --- | --- |
| **Nam giới** | 22 | 26 |
| **Nữ giới** | 16 | 36 |

Hãy ký hiệu các biến cố *M* = đối tượng là nam, *W* = đối tượng là nữ, *T* = đối tượng thích trà, và *C* = đối tượng thích cà phê. Hãy tính các xác suất sau:

1. *P*(*M*)
1. *P*(*W*)
1. *P*(*T*)
1. *P*(*C*)
1. *P*(*M* biến cố "và" *T*)
1. *P*(*W* biến cố "và" *C*)
1. *P*(*M* biến cố "hoặc" *W*)
1. *P*(*M* biến cố "hoặc" *T*)
1. *P*(*W* biến cố "hoặc" *C*)
1. *P*(*M*')
1. *P*(*T*|*M*)
1. *P*(*W*|*C*)
1. *P*(*C*|*W*)
