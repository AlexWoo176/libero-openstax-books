## 4.4
 
Phân phối hình học

Có bốn đặc điểm chính của một phép thử hình học.

1. Một phép thử được lặp lại cho đến khi đạt được thành công. Hãy nghĩ về điều này như một hoặc nhiều phép thử Bernoulli với tất cả các kết quả là thất bại ngoại trừ lần cuối cùng, đó là một thành công. Nói cách khác, bạn tiếp tục lặp lại những gì bạn đang làm cho đến khi đạt được thành công đầu tiên. Sau đó bạn dừng lại. Ví dụ, bạn ném phi tiêu vào hồng tâm cho đến khi bạn trúng hồng tâm. Lần đầu tiên bạn trúng hồng tâm là một "thành công", vì vậy bạn ngừng ném phi tiêu. Có thể mất sáu lần thử cho đến khi bạn trúng hồng tâm. Bạn có thể coi các phép thử là thất bại, thất bại, thất bại, thất bại, thất bại, thành công, DỪNG LẠI. Về lý thuyết, số lần thử có thể kéo dài mãi mãi.
1. Các phép thử lặp lại độc lập với nhau.
1. Xác suất p của một thành công và xác suất q của một thất bại là như nhau cho mỗi phép thử. 𝑝 +𝑞⁢  =1p+q⁢ =1p+q =1 và 𝑞 =1 −𝑝.q=1-p.q=1-p. Ví dụ, xác suất gieo được số ba khi bạn tung một con xúc xắc cân đối là 1/61/61/6. Điều này đúng bất kể bạn tung xúc xắc bao nhiêu lần. Giả sử bạn muốn biết xác suất nhận được số ba đầu tiên ở lần tung thứ năm. Ở các lần tung từ một đến bốn, bạn không nhận được mặt có số ba. Xác suất cho mỗi lần tung là 𝑞 =5/6,q=5/6,q=5/6, xác suất của một thất bại. Xác suất nhận được số ba đầu tiên ở lần tung thứ năm là (5/6)⁢(5/6)⁢(5/6)⁢(5/6)⁢(1/6)⁢  = ⁢0.0804(5/6)⁢(5/6)⁢(5/6)⁢(5/6)⁢(1/6)⁢ = ⁢0.0804(5/6)(5/6)(5/6)(5/6)(1/6) = 0.0804
1. Biến ngẫu nhiên X đại diện cho số lần thử mà tại đó thành công đầu tiên xảy ra. Nghĩa là, X = số lần thử độc lập cho đến khi đạt được thành công đầu tiên.
Sau đây là các thuộc tính bổ sung của phân phối hình học:

1. Biến ngẫu nhiên này là rời rạc. Biến ngẫu nhiên có thể được định nghĩa theo hai cách tùy thuộc vào mối quan tâm của nhà phân tích. Trong ví dụ trên về việc gieo một con xúc xắc, câu hỏi là “Xác suất để lần thành công đầu tiên xảy ra ở lần gieo thứ năm là bao nhiêu?” Cách khác, câu hỏi có thể được đặt ra là “Xác suất để cần bốn lần thất bại trước khi có một lần thành công là bao nhiêu?” Chúng ta sẽ thấy rằng mỗi cách đặt câu hỏi sẽ làm thay đổi nhẹ dạng của hàm mật độ xác suất hình học và sẽ làm thay đổi số trung bình và độ lệch chuẩn của hàm phân phối xác suất hình học.
1. Điều ẩn ý trong biến ngẫu nhiên là xác suất thành công là hằng số và do đó xác suất thất bại cũng vậy. Đối với việc tung đồng xu, điều này là hiển nhiên, nhưng trong các thực nghiệm đòi hỏi kỹ năng, chẳng hạn như đánh bóng chày hoặc ném phi tiêu, người ta có thể cho rằng việc học hỏi trong quá trình thực nghiệm sẽ làm thay đổi xác suất thành công. Phân phối hình học không thể nắm bắt được “sự học hỏi”, do đó xác suất thành công trong quá khứ được giả định là hằng số.
1. Phân phối hình học là “không có bộ nhớ”. Có rất ít hàm mật độ xác suất được gọi là “không có bộ nhớ”, và phân phối hình học là phân phối duy nhất có biến ngẫu nhiên rời rạc mà không có bộ nhớ. Ví dụ, trong lịch sử, cầu thủ Jones của giải Major League Baseball có thành tích đánh bóng để tiến ít nhất đến căn cứ thứ nhất với xác suất là 0,20. Jones đã không có cú đánh nào trong 10 lần đánh bóng gần nhất của mình. Xác suất để Jones có một cú đánh trong lần đánh bóng thứ ba của anh ấy là bao nhiêu? Câu trả lời bỏ qua 10 lần thất bại trước đó của anh ấy. Tất cả các biến cố trước các biến cố ở thời điểm hiện tại đều không liên quan và do đó được coi là “không có bộ nhớ”.
Về mặt hình thức: 𝑃⁡(𝑥=𝑛+𝑘|𝑥≥𝑘+1) =𝑃⁡(𝑥 =𝑛),P⁡(x=n+k|x≥k+1)=P⁡(x=n),Px=n+k|x≥k+1=P(x=n), trong đó k = số lần thất bại trước đó

Xác suất trúng của Jones bắt đầu lại từ đầu mỗi khi anh ấy đến lượt đánh bóng. Đặc điểm này của phân phối hình học dẫn đến một kết quả thú vị: Khi lấy các bộ phận từ một quy trình sản xuất để kiểm tra xem có bộ phận nào bị lỗi hay không, phân phối hình học bắt đầu lại từ đầu mỗi khi các thử nghiệm bắt đầu mà không xem xét đến kết quả của các thử nghiệm trước đó. Chúng ta sẽ tìm hiểu thêm về điều này khi đến phần hàm mật độ xác suất mũ.

Bạn chơi một trò chơi may rủi mà bạn có thể thắng hoặc thua (không có khả năng nào khác) **cho đến khi** bạn thua. Xác suất thua của bạn là *p* = 0,57. Xác suất để bạn mất năm ván mới thua là bao nhiêu? Gọi *X* = số ván bạn chơi cho đến khi bạn thua (bao gồm cả ván thua). Khi đó *X* nhận các giá trị 1, 2, 3, ... (có thể tiếp tục vô hạn). Câu hỏi xác suất là *P*(*x* = 5).

Bạn ném phi tiêu vào bảng cho đến khi trúng vùng trung tâm. Xác suất trúng vùng trung tâm của bạn là *p* = 0,17. Bạn muốn tìm xác suất để mất tám lần ném mới trúng tâm. *X* nhận những giá trị nào?

#### Bài toán

Một kỹ sư an toàn cho rằng 35% tổng số tai nạn công nghiệp tại nhà máy là do nhân viên không tuân thủ hướng dẫn. Họ quyết định xem xét các báo cáo tai nạn (được chọn ngẫu nhiên và thay thế vào chồng báo cáo sau khi đọc) **cho đến khi** họ tìm thấy một báo cáo cho thấy tai nạn do nhân viên không tuân thủ hướng dẫn. Trung bình, kỹ sư an toàn sẽ **kỳ vọng** phải xem bao nhiêu báo cáo cho đến khi họ tìm thấy một báo cáo cho thấy tai nạn do nhân viên không tuân thủ hướng dẫn? Xác suất để kỹ sư an toàn phải kiểm tra ít nhất ba báo cáo cho đến khi họ tìm thấy một báo cáo cho thấy tai nạn do nhân viên không tuân thủ hướng dẫn là bao nhiêu?

Gọi *X* = số lượng tai nạn mà kỹ sư an toàn phải kiểm tra **cho đến khi** họ tìm thấy một báo cáo cho thấy tai nạn do nhân viên không tuân thủ hướng dẫn. *X* nhận các giá trị 1, 2, 3, .... Câu hỏi đầu tiên yêu cầu bạn tìm **giá trị kỳ vọng** hoặc số trung bình. Câu hỏi thứ hai yêu cầu bạn tìm *P*(*x* ≥ 3). ("Ít nhất" được dịch thành ký hiệu "lớn hơn hoặc bằng").

Một giảng viên cho rằng 15% sinh viên đạt điểm dưới C trong kỳ thi cuối kỳ. Họ quyết định xem xét các bài thi cuối kỳ (được chọn ngẫu nhiên và thay thế vào chồng bài thi sau khi đọc) cho đến khi họ tìm thấy một bài thi có điểm dưới C. Chúng ta muốn biết xác suất để giảng viên phải kiểm tra ít nhất mười bài thi cho đến khi tìm thấy một bài có điểm dưới C. Câu hỏi xác suất được phát biểu dưới dạng toán học là gì?

Giả sử bạn đang tìm một sinh viên tại trường đại học của mình sống trong phạm vi năm dặm quanh bạn. Bạn biết rằng 55% trong số 25.000 sinh viên sống trong phạm vi năm dặm quanh bạn. Bạn liên hệ ngẫu nhiên với các sinh viên từ trường đại học **cho đến khi** một người nói rằng họ sống trong phạm vi năm dặm quanh bạn. Xác suất để bạn cần liên hệ với bốn người là bao nhiêu?

Đây là một bài toán hình học vì bạn có thể có một số lần thất bại trước khi đạt được thành công mà bạn mong muốn. Ngoài ra, xác suất thành công vẫn giữ nguyên mỗi khi bạn hỏi một sinh viên xem họ có sống trong phạm vi năm dặm quanh bạn hay không. Không có số lần thử nghiệm xác định (số lần bạn hỏi một sinh viên).

#### Bài tập

a. Gọi *X* = số lượng ____________ bạn phải hỏi ____________ một người nói có.

b. *X* nhận những giá trị nào?

c. *p* và *q* là gì?

d. Câu hỏi xác suất là *P*(_______).

Bạn cần tìm một cửa hàng có bán loại mực in đặc biệt. Bạn biết rằng trong số các cửa hàng có bán mực in, 10% trong số đó có bán loại mực đặc biệt này. Bạn gọi điện ngẫu nhiên cho từng cửa hàng cho đến khi tìm được cửa hàng có loại mực bạn cần. *p* và *q* là gì?

### Ký hiệu cho phân phối hình học: G = Hàm phân phối xác suất hình học

*X**G**p*

Đọc là "*X* là một biến ngẫu nhiên có Phân phối hình học." Tham số là *p*; *p* = xác suất thành công cho mỗi phép thử.

TRƯỜNG HỢP I: Biến ngẫu nhiên X là biến cố của lần thành công đầu tiên

Trong trường hợp này, chúng ta đặt câu hỏi: “Xác suất để chúng ta có một số x các biến cố mà chúng ta quan tâm là các thất bại trước khi có một thành công là bao nhiêu?”

Hàm phân phối xác suất (pdf) hình học cho chúng ta biết xác suất để lần thành công đầu tiên đòi hỏi x số lần thử thất bại độc lập, mỗi lần có xác suất (1 −𝑝)(1-p)(1-p). Nếu xác suất thành công trong mỗi phép thử là *p*, thì xác suất để phép thử thứ *x* (trong số x phép thử) là lần thành công đầu tiên là:

𝑃⁡(𝑋=𝑥) =(1−𝑝)𝑥−1⁢𝑝P⁡(X=x)=(1-p)x-1⁢pPX=x=(1-p)x-1p

đối với 𝑥 =1, 2, 3, ....x=1, 2, 3, ....x=1, 2, 3, ....

Giống như phân phối nhị thức, phân phối hình học có các tham số là số trung bình và độ lệch chuẩn. Giá trị kỳ vọng của X, số trung bình cho Trường hợp I, là 𝜇 =1𝑝.μ=1p.μ=1p. Điều này cho chúng ta biết cần bao nhiêu phép thử thất bại trước khi đạt được thành công đầu tiên. Số đếm này bao gồm cả phép thử dẫn đến thành công trong tổng số các phép thử. Dạng trên của phân phối hình học được sử dụng để mô hình hóa số lượng phép thử cho đến khi có thành công đầu tiên. Số lượng phép thử bao gồm cả phép thử thành công: x = tất cả các phép thử bao gồm cả phép thử thành công. Điều này có thể thấy được trong dạng của công thức. Nếu X = số lượng phép thử bao gồm cả thành công, thì chúng ta phải nhân xác suất thất bại, (1 −𝑝)(1-p)(1-p), với số lần thất bại, đó là 𝑥 −1x-1x-1. Độ lệch chuẩn của Trường hợp I trong phân phối hình học là:

TRƯỜNG HỢP II: Biến ngẫu nhiên X là số lần thất bại TRƯỚC MỘT thành công

Ngược lại với Trường hợp I, dạng sau đây của phân phối hình học được sử dụng để mô hình hóa số lần thất bại cho đến khi có thành công đầu tiên là:

𝑃⁡(𝑋=𝑥) =(1−𝑝)𝑥⁢𝑝P⁡(X=x)=(1-p)x⁢pPX=x=(1-p)xp

for 𝑥 =0, 1, 2, 3, ....x=0, 1, 2, 3, ....x=0, 1, 2, 3, ....

Trong trường hợp này, phép thử thành công không được tính là một phép thử trong công thức: x = số lần thất bại. Giá trị kỳ vọng, số trung bình, của phân phối này là 𝜇 =1−𝑝𝑝μ=1-ppμ=1-pp. Điều này cho chúng ta biết cần bao nhiêu lần thất bại trước khi có một thành công. Trong cả hai trường hợp, chuỗi xác suất là một cấp số nhân. Trong Trường hợp II, tham số độ lệch chuẩn là: 𝜎 =√(1−𝑝𝑝).σ=(1-pp).σ=1-pp.

*Hình 
4.4*

Trục y trong [Hình 4.4](4-4-geometric-distribution#fig-00001) chứa xác suất của *x*, và trục *x* là các thành phần số ngẫu nhiên được kiểm tra. Ví dụ, tại 𝑥 =1x=1x=1 xác suất nó được tìm thấy là bị lỗi là 0,0196. Với hai thành phần được kiểm tra, xác suất thành phần thứ hai bị lỗi được biểu diễn ở xác suất 0,0196 tại 𝑥 =2x=2x=2 trên trục x. Đối với xác suất thành phần thứ ba bị lỗi, chúng ta tìm thấy 𝑃⁡(𝑋=3) =0.019208.P⁡(X=3)=0.019208.PX=3=0.019208. (Hai giá trị đầu tiên giống nhau do làm tròn trong các phép tính.)

Lưu ý trên [Hình 4.4](4-4-geometric-distribution#fig-00001) rằng các xác suất giảm theo cùng một bước với mỗi thay đổi trong giá trị của x. Mức tăng này được gọi là công bội. Điều này tồn tại duy nhất đối với phân phối xác suất hình học. Công bội, được gọi là r, có thể được tính bằng cách chia bất kỳ giá trị nào cho giá trị trước đó, ví dụ: 𝑃⁡(𝑥=5)𝑃⁡(𝑥=4) =0.0184470.018823 =0.98.P⁡(x=5)P⁡(x=4)=0.0184470.018823=0.98.P(x=5)P(x=4)=0.0184470.018823=0.98.

Do đó, đối với tập dữ liệu này, công bội là 0,98. Sau đó, công bội nhân với bất kỳ giá trị xác suất nào khác sẽ cung cấp giá trị xác suất tiếp theo trong chuỗi. Ví dụ, xác suất thành phần thứ sáu được kiểm tra là bị lỗi là 0,018078. Kiểm tra điều này bằng cách sử dụng công thức từ Trường hợp I. Bây giờ chúng ta có 𝑃⁡(𝑥=6)P⁡(x=6)Px=6. Biết được điều này và công bội, chúng ta có thể tính 𝑃⁡(𝑥=7)P⁡(x=7)Px=7 bằng phép nhân đơn giản: 𝑃⁡(𝑥=7) =(0.018078)⁢  * ⁢0.98 =0.017716,P⁡(x=7)=(0.018078)⁢ * ⁢0.98=0.017716,Px=7=0.018078 * 0.98=0.017716,, cùng một giá trị mà chúng ta đã tìm thấy trước đó bằng cách sử dụng phân phối xác suất hình học. Mức tăng công bội này là cùng một tỷ lệ giữa mọi số và được gọi là cấp số nhân, do đó có tên gọi cho hàm mật độ xác suất này. Khi công bội đã được tính, bất kỳ 𝑃⁡(𝑥=𝑥𝑎)P⁡(x=xa)Px=xa nào mà bạn muốn biết đều có thể dễ dàng tìm thấy.

Số lượng thành phần mà bạn dự kiến sẽ kiểm tra cho đến khi tìm thấy thành phần bị lỗi đầu tiên là số trung bình, 𝜇 =50μ=50μ=50 cho trường hợp các thành phần bị lỗi này. Công thức tính số trung bình của phân phối hình học cho biến ngẫu nhiên được định nghĩa là số lần thất bại trước thành công đầu tiên là 𝜇 =1𝑝 =10.02 =50μ=1p=10.02=50μ=1p=10.02=50

Xem [Ví dụ 4.20](4-4-geometric-distribution#element-340) để biết ví dụ trong đó biến ngẫu nhiên hình học được định nghĩa là số lần thử cho đến khi có thành công đầu tiên. Giá trị kỳ vọng của công thức này cho phân phối hình học sẽ khác với phiên bản phân phối này. Trường hợp II cũng có phương sai, nhưng điều này đã thay đổi so với công thức Trường hợp I. Công thức tính phương sai này là:

𝑃⁡(𝑋=𝑥) =(1−𝑝)𝑥−1⁢𝑝P⁡(X=x)=(1-p)x-1⁢pPX=x=(1-p)x-1p

for 𝑥⁢  = ⁢1, 2, 3, ....x⁢ = ⁢1, 2, 3, ....x = 1, 2, 3, ....

Giả sử xác suất một linh kiện máy tính bị lỗi là 0,02. Các linh kiện được chọn ngẫu nhiên. Tìm xác suất lỗi đầu tiên được gây ra bởi linh kiện thứ bảy được kiểm tra. Bạn dự kiến sẽ kiểm tra bao nhiêu linh kiện cho đến khi tìm thấy một linh kiện bị lỗi?

Gọi *X* = số linh kiện máy tính được kiểm tra cho đến khi tìm thấy lỗi đầu tiên.

*X* nhận các giá trị 1, 2, 3, ... trong đó *p* = 0,02.

Tìm *P*(*x* = 7). *P*(*x* = 7) = 0,0177.

Để tìm xác suất sao cho *x* = 7,

- Nhập `2^nd, DISTR`
- Cuộn xuống và chọn `geometpdf`(
- Nhấn `ENTER`
- Nhập 0,02, 7); nhấn `ENTER` để xem kết quả: *P*(*x* = 7) = 0,0177
Để tìm xác suất sao cho *x* ≤ 7, hãy làm theo các hướng dẫn tương tự NGOẠI TRỪ việc chọn E:geometcdf( làm hàm phân phối.

Xác suất để linh kiện thứ bảy là linh kiện bị lỗi đầu tiên là 0,0177.

Công thức tính phương sai là *σ*^2 = (1𝑝)⁢(1𝑝−1)(1p)⁢(1p−1)(1p)(1p−1) = (10.02)⁢(10.02−1)(10.02)⁢(10.02−1)(10.02)(10.02−1) = 2,450

Độ lệch chuẩn là *σ* = √(1𝑝)⁢(1𝑝−1)(1p)⁢(1p−1)(1p)(1p−1) = √(10.⁢02)⁢(10.⁢02−1)(10.⁢02)⁢(10.⁢02−1)(10.02)(10.02−1) = 49,5

Xác suất một thanh thép bị lỗi là 0,01. Các thanh thép được chọn ngẫu nhiên. Tìm xác suất để lỗi đầu tiên xuất hiện ở thanh thép thứ chín. Sử dụng máy tính TI-83+ hoặc TI-84 để tìm câu trả lời.

#### Bài tập

Nguy cơ mắc ung thư trong đời là khoảng một trên 67 (1,5%). Gọi *X* = số người bạn hỏi cho đến khi một người nói rằng họ bị ung thư. Khi đó *X* là một biến ngẫu nhiên rời rạc với phân phối hình học: 𝑋~𝐺⁡(167)X~G⁡(167)X~G167 hoặc 𝑋~𝐺⁡(0.015)X~G⁡(0.015)X~G(0.015)

1. Xác suất để bạn hỏi mười người trước khi một người nói rằng họ bị ung thư là bao nhiêu?
1. Xác suất để bạn phải hỏi 20 người là bao nhiêu?
1. Tìm (i) số trung bình và (ii) độ lệch chuẩn của *X*.
Tỷ lệ biết chữ của một quốc gia đo lường tỷ lệ những người từ 15 tuổi trở lên có thể đọc và viết. Tỷ lệ biết chữ của phụ nữ ở Afghanistan là 12%. Gọi *X* = số phụ nữ Afghanistan bạn hỏi cho đến khi một người nói rằng cô ấy biết chữ.

1. Phân phối xác suất của *X* là gì?
1. Xác suất để bạn hỏi năm người phụ nữ trước khi có một người nói rằng cô ấy biết chữ là bao nhiêu?
1. Xác suất để bạn phải hỏi mười người phụ nữ là bao nhiêu?
1. Tìm (i) số trung bình và (ii) độ lệch chuẩn của *X*.
