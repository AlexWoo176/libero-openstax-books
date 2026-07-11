## 4.3
 
Phân phối nhị thức

Có ba đặc điểm của một phép thử Bernoulli.

1. Có một số lượng phép thử cố định. Hãy coi các phép thử là các lần lặp lại của một phép thử. Chữ cái *n* biểu thị số lượng phép thử.
1. Chỉ có hai kết quả có thể xảy ra, được gọi là "thành công" và "thất bại", cho mỗi phép thử. Chữ cái *p* biểu thị xác suất thành công trong một phép thử, và *q* biểu thị xác suất thất bại trong một phép thử. *p* + *q* = 1.
1. *n* phép thử là độc lập và được lặp lại trong các điều kiện giống hệt nhau. Vì *n* phép thử là độc lập, kết quả của một phép thử không giúp dự đoán kết quả của phép thử khác. Một cách diễn đạt khác là đối với mỗi phép thử riêng lẻ, xác suất *p* của thành công và xác suất *q* của thất bại vẫn giữ nguyên. Ví dụ, việc đoán ngẫu nhiên một câu hỏi đúng-sai về thống kê chỉ có hai kết quả. Nếu thành công là đoán đúng, thì thất bại là đoán sai. Giả sử Joe luôn đoán đúng bất kỳ câu hỏi đúng-sai nào về thống kê với xác suất *p* = 0,6. Khi đó, *q* = 0,4. Điều này có nghĩa là đối với mỗi câu hỏi đúng-sai về thống kê mà Joe trả lời, xác suất thành công (*p* = 0,6) và xác suất thất bại (*q* = 0,4) của anh ấy vẫn giữ nguyên.
Các kết quả của một phép thử Bernoulli tuân theo Phân phối xác suất nhị thức. Biến ngẫu nhiên *X* = số lần thành công thu được trong *n* phép thử độc lập.

Số trung bình, *μ*, và phương sai, *σ*^2, cho phân phối xác suất nhị thức là *μ* = *np* và *σ*^2 = *npq*. Khi đó, độ lệch chuẩn, *σ*, là *σ* = √𝑛⁢𝑝⁢𝑞n⁢p⁢qnpq.

Bất kỳ phép thử nào có các đặc điểm hai và ba và trong đó *n* = 1 được gọi là Phép thử Bernoulli (được đặt theo tên của Jacob Bernoulli, người đã nghiên cứu chúng rất kỹ lưỡng vào cuối những năm 1600). Một phép thử nhị thức diễn ra khi số lần thành công được đếm trong một hoặc nhiều phép thử Bernoulli.

Tại trường Cao đẳng ABC, tỷ lệ rút môn học từ một khóa vật lý cơ bản là 30% cho bất kỳ học kỳ nào. Điều này ngụ ý rằng, trong bất kỳ học kỳ nào, 70% sinh viên vẫn tiếp tục học trong suốt học kỳ đó. Một "thành công" có thể được định nghĩa là một cá nhân đã rút môn học. Biến ngẫu nhiên *X* = số lượng sinh viên rút khỏi lớp vật lý cơ bản được chọn ngẫu nhiên.

Hội đồng y tế tiểu bang lo ngại về lượng trái cây có sẵn trong các bữa trưa tại trường học. Bốn mươi tám phần trăm các trường trong tiểu bang cung cấp trái cây trong bữa trưa của họ mỗi ngày. Điều này ngụ ý rằng 52% không cung cấp. Trong trường hợp này, một "thành công" sẽ là gì?

Giả sử bạn chơi một trò chơi mà bạn chỉ có thể thắng hoặc thua. Xác suất bạn thắng bất kỳ trò chơi nào là 55%, và xác suất bạn thua là 45%. Mỗi trò chơi bạn chơi là độc lập. Nếu bạn chơi trò chơi đó 20 lần, hãy viết hàm mô tả xác suất bạn thắng 15 trong số 20 lần đó. Ở đây, nếu bạn định nghĩa *X* là số lần thắng, thì *X* nhận các giá trị 0, 1, 2, 3, ..., 20. Xác suất thành công là *p* = 0,55. Xác suất thất bại là *q* = 0,45. Số lần thử là *n* = 20. Câu hỏi về xác suất có thể được phát biểu dưới dạng toán học là *P*(*x* = 15).

Một huấn luyện viên đang dạy một chú cá heo được giải cứu cách bắt cá sống trước khi thả nó về tự nhiên. Xác suất chú cá heo bắt được cá thành công là 35%, và xác suất chú cá heo không bắt được cá thành công là 65%. Trong 20 lần thử, bạn muốn tìm xác suất chú cá heo thành công 12 lần. Hãy phát biểu câu hỏi về xác suất dưới dạng toán học.

#### Bài toán

Một đồng xu đã được thay đổi để trọng số kết quả từ 0,5 thành 0,25 và được tung 5 lần. Mỗi lần tung là độc lập. Xác suất để nhận được nhiều hơn 3 mặt ngửa là bao nhiêu? Gọi *X* = số mặt ngửa trong 5 lần tung đồng xu cân đối. *X* nhận các giá trị 0, 1, 2, 3, 4, 5. Vì đồng xu được thay đổi để dẫn đến *p* = 0,25, *q* là 0,75. Số lần thử là *n* = 5. Hãy phát biểu câu hỏi về xác suất dưới dạng toán học.

Trước tiên, hãy phát triển đầy đủ hàm mật độ xác suất và vẽ đồ thị hàm mật độ xác suất. Với hàm mật độ xác suất đã được phát triển đầy đủ, chúng ta có thể dễ dàng đọc lời giải cho câu hỏi 𝑃⁡(𝑥>3)P⁡(x>3)Px>3 mặt ngửa. 𝑃⁡(𝑥>3) =𝑃⁡(𝑥=4) +𝑃⁡(𝑥=5) =0.0146 +0.0007 =0.0153.P⁡(x>3)=P⁡(x=4)+P⁡(x=5)=0.0146+0.0007=0.0153.Px>3=Px=4+Px=5=0.0146+0.0007=0.0153. Chúng ta đã cộng hai xác suất riêng lẻ vì quy tắc cộng từ [Các chủ đề về xác suất](3-introduction).

[Hình 4.2](4-3-binomial-distribution#fig-00001) cũng cho phép chúng ta thấy mối liên hệ giữa hàm mật độ xác suất với xác suất và diện tích. Chúng ta cũng thấy trong [Hình 4.2](4-3-binomial-distribution#fig-00001) độ lệch của phân phối nhị thức khi p không bằng 0,5. Trong [Hình 4.2](4-3-binomial-distribution#fig-00001), phân phối bị lệch phải là kết quả của 𝜇 =𝑛⁢𝑝 =1.25μ=n⁢p=1.25μ=np=1.25 vì 𝑝 =0.25p=0.25p=0.25.

*Hình 
4.2*

Một con xúc xắc cân đối, sáu mặt được gieo mười lần. Mỗi lần gieo là độc lập. Bạn muốn tìm xác suất gieo được mặt một nhiều hơn ba lần. Hãy phát biểu câu hỏi về xác suất dưới dạng toán học.

Khoảng 70% sinh viên thống kê làm bài tập về nhà kịp thời để được thu và chấm điểm. Mỗi sinh viên làm bài tập về nhà một cách độc lập. Trong một lớp thống kê gồm 50 sinh viên, xác suất để ít nhất 40 sinh viên làm bài tập về nhà đúng hạn là bao nhiêu? Sinh viên được chọn ngẫu nhiên.

#### Bài toán

a. Đây là một bài toán nhị thức vì chỉ có thành công hoặc một __________, có một số lần thử cố định, và xác suất thành công là 0,70 cho mỗi lần thử.

b. Nếu chúng ta quan tâm đến số lượng sinh viên làm bài tập về nhà đúng hạn, thì chúng ta định nghĩa *X* như thế nào?

c. *x* nhận những giá trị nào?

d. "Thất bại" là gì, theo ngôn từ?

e. Nếu *p* + *q* = 1, thì *q* là gì?

f. Các từ "ít nhất" tương ứng với loại bất đẳng thức nào cho câu hỏi xác suất *P*(*x* ____ 40).

Sáu mươi lăm phần trăm mọi người vượt qua kỳ thi sát hạch lái xe của bang ngay lần thử đầu tiên. Một nhóm gồm 50 cá nhân đã tham gia kỳ thi lái xe được chọn ngẫu nhiên. Hãy đưa ra hai lý do tại sao đây là một bài toán nhị thức.

### Ký hiệu cho phân phối nhị thức: *B* = Hàm phân phối xác suất nhị thức

*X**B**n**p*

Đọc là "*X* là một biến ngẫu nhiên có phân phối xác suất nhị thức." Các tham số là *n* và *p*; *n* = số phép thử, *p* = xác suất thành công trong mỗi phép thử.

Người ta đã tuyên bố rằng khoảng 41% người lao động trưởng thành có bằng tốt nghiệp trung học phổ thông nhưng không theo đuổi bất kỳ chương trình giáo dục nào thêm. Nếu 20 người lao động trưởng thành được chọn ngẫu nhiên, hãy tìm xác suất để tối đa 12 người trong số họ có bằng tốt nghiệp trung học phổ thông nhưng không theo đuổi bất kỳ chương trình giáo dục nào thêm. Bạn kỳ vọng có bao nhiêu người lao động trưởng thành có bằng tốt nghiệp trung học phổ thông nhưng không theo đuổi bất kỳ chương trình giáo dục nào thêm?

Đặt *X* = số người lao động có bằng tốt nghiệp trung học phổ thông nhưng không theo đuổi bất kỳ chương trình giáo dục nào thêm.

*X* nhận các giá trị 0, 1, 2, ..., 20 trong đó *n* = 20, *p* = 0,41, và *q* = 1 – 0,41 = 0,59. *X* ~ *B*(20, 0,41)

Tìm *P*(*x* ≤ 12). *P*(*x* ≤ 12) = 0,9738. (máy tính hoặc máy tính cầm tay)

Vào 2^nd DISTR. Cú pháp cho các hướng dẫn như sau:

**Để tính (*x* = giá trị): binompdf(*n*, *p*, số)**
nếu "số" bị bỏ qua, kết quả là bảng xác suất nhị thức.

**Để tính *P*(*x* ≤ giá trị): binomcdf(*n*, *p*, số)** nếu "số" bị bỏ qua, kết quả là bảng xác suất nhị thức lũy tích.

**Đối với bài toán này: Sau khi bạn đã ở trong `2^nd DISTR`, hãy nhấn phím mũi tên xuống đến `binomcdf`. Nhấn `ENTER`. Nhập 20,0.41,12). Kết quả là *P*(*x* ≤ 12) = 0.9738.**

Nếu bạn muốn tìm *P*(*x* = 12), hãy sử dụng pdf (binompdf). Nếu bạn muốn tìm *P*(*x* > 12), hãy sử dụng 1 - binomcdf(20,0.41,12).

Xác suất để tối đa 12 công nhân có bằng tốt nghiệp trung học nhưng không theo đuổi bất kỳ chương trình giáo dục nào thêm là 0.9738.

Đồ thị của *X* ~ *B*(20, 0.41) như sau:

*Hình 
4.3*

Trục *y* chứa xác suất của *x*, trong đó *X* = số lượng công nhân chỉ có bằng tốt nghiệp trung học.

Số lượng công nhân trưởng thành mà bạn kỳ vọng có bằng tốt nghiệp trung học nhưng không theo đuổi bất kỳ chương trình giáo dục nào thêm chính là số trung bình, *μ* = *np* = (20)(0.41) = 8.2.

Công thức tính phương sai là σ^2 = *npq*. Độ lệch chuẩn là *σ* = √𝑛⁢𝑝⁢𝑞n⁢p⁢qnpq. 
*σ* = √(20)⁢(0.41)⁢(0.59)(20)⁢(0.41)⁢(0.59)(20)(0.41)(0.59) = 2.20.

Khoảng 32% sinh viên tham gia một chương trình tình nguyện cộng đồng bên ngoài trường học. Nếu 30 sinh viên được chọn ngẫu nhiên, hãy tìm xác suất để tối đa 14 người trong số họ tham gia một chương trình tình nguyện cộng đồng bên ngoài trường học. Sử dụng máy tính TI-83+ hoặc TI-84 để tìm câu trả lời.

#### Bài toán

Trong danh mục đồ dùng nghệ thuật *Jerry’s Artarama* năm 2013, có 560 trang. Tám trong số các trang đó giới thiệu các nghệ sĩ tiêu biểu. Giả sử chúng ta lấy mẫu ngẫu nhiên 100 trang. Gọi *X* = số trang giới thiệu các nghệ sĩ tiêu biểu.

1. *x* nhận những giá trị nào?
1. What is the probability distribution? Find the following probabilities:
  
xác suất để hai trang có các nghệ sĩ tiêu biểu
xác suất để có tối đa sáu trang có các nghệ sĩ tiêu biểu
xác suất để có nhiều hơn ba trang có các nghệ sĩ tiêu biểu.
1. Sử dụng các công thức, hãy tính (i) số trung bình và (ii) độ lệch chuẩn.
Theo một cuộc thăm dò của Gallup, 60% người trưởng thành Mỹ thích tiết kiệm hơn là chi tiêu. Gọi *X* = số người trưởng thành Mỹ trong một mẫu ngẫu nhiên gồm 50 người thích tiết kiệm hơn chi tiêu.

1. Phân phối xác suất cho *X* là gì?
1. Use your calculator to find the following probabilities:
  
xác suất để 25 người trưởng thành trong mẫu thích tiết kiệm hơn chi tiêu
xác suất để có tối đa 20 người trưởng thành thích tiết kiệm
xác suất để có hơn 30 người trưởng thành thích tiết kiệm
1. Sử dụng các công thức, hãy tính (i) số trung bình và (ii) độ lệch chuẩn của *X*.
Nguy cơ mắc ung thư suốt đời là khoảng một trên 67 (1.5%). Giả sử chúng ta lấy mẫu ngẫu nhiên 200 người. Gọi *X* = số người sẽ mắc ung thư.

#### Bài toán

1. Phân phối xác suất cho *X* là gì?
1. Sử dụng các công thức, hãy tính (i) số trung bình và (ii) độ lệch chuẩn của *X*.
1. Sử dụng máy tính của bạn để tìm xác suất có tối đa tám người mắc bệnh ung thư
1. Khả năng năm hay sáu người mắc bệnh ung thư sẽ cao hơn? Hãy biện luận câu trả lời của bạn bằng số liệu.
Trong một mùa giải NBA nhất định, một cầu thủ của đội Los Angeles Clippers có tỷ lệ ném bóng thành công cao nhất giải đấu. Cầu thủ này ghi điểm với 61.3% số cú ném của mình. Giả sử bạn chọn một mẫu ngẫu nhiên gồm 80 cú ném được thực hiện bởi cầu thủ này trong mùa giải. Gọi *X* = số cú ném ghi được điểm.

1. Phân phối xác suất cho *X* là gì?
1. Sử dụng các công thức, hãy tính (i) số trung bình và (ii) độ lệch chuẩn của *X*.
1. Sử dụng máy tính của bạn để tìm xác suất cầu thủ này ghi bàn với 60 trong số các cú sút này.
1. Tìm xác suất để cầu thủ này ghi bàn với hơn 50 trong số các cú sút này.
Ví dụ sau đây minh họa một bài toán **không** phải là nhị thức. Nó vi phạm điều kiện về tính độc lập. Trường Cao đẳng ABC có một hội đồng cố vấn sinh viên gồm mười nhân viên và sáu sinh viên. Hội đồng muốn chọn một chủ tịch và một thư ký. Xác suất để cả chủ tịch và thư ký đều là sinh viên là bao nhiêu? Tên của tất cả các thành viên hội đồng được cho vào một chiếc hộp, và hai cái tên được rút ra **không hoàn lại**. Cái tên được rút ra đầu tiên xác định chủ tịch và cái tên thứ hai xác định thư ký. Có hai phép thử. Tuy nhiên, các phép thử không độc lập vì kết quả của phép thử đầu tiên ảnh hưởng đến kết quả của phép thử thứ hai. Xác suất chọn được một sinh viên trong lần rút đầu tiên là 616616616. Xác suất chọn được một sinh viên trong lần rút thứ hai là 515515515, khi lần rút đầu tiên chọn được một sinh viên. Xác suất là 615615615, khi lần rút đầu tiên chọn được một nhân viên. Xác suất rút được tên của một sinh viên thay đổi cho mỗi phép thử và do đó, vi phạm điều kiện về tính độc lập.

Một đội bóng vợt đang chọn đội trưởng. Tên của tất cả các sinh viên năm cuối được cho vào một chiếc mũ, và ba cái tên đầu tiên được rút ra sẽ là đội trưởng. Các cái tên không được thay thế sau khi đã được rút ra (một người không thể làm hai đội trưởng). Bạn muốn xem liệu tất cả các đội trưởng có chơi cùng một vị trí hay không. Hãy nêu rõ đây có phải là nhị thức hay không và nêu lý do tại sao.
