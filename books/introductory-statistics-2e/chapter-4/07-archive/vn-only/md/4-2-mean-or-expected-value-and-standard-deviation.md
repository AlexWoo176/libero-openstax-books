## 4.2
 
Số trung bình hoặc Giá trị kỳ vọng và Độ lệch chuẩn

Giá trị kỳ vọng thường được gọi là trung bình hoặc số trung bình "dài hạn". Điều này có nghĩa là về lâu dài khi thực hiện một phép thử lặp đi lặp lại, bạn sẽ **kỳ vọng** đạt được giá trị trung bình này.

Bạn tung một đồng xu và ghi lại kết quả. Xác suất để kết quả là mặt ngửa là bao nhiêu? Nếu bạn tung một đồng xu hai lần, liệu xác suất có cho bạn biết rằng các lần tung này sẽ dẫn đến một mặt ngửa và một mặt sấp không? Bạn có thể tung một đồng xu cân đối mười lần và ghi lại chín lần mặt ngửa. Như bạn đã học trong [Các chủ đề về xác suất](3-introduction), xác suất không mô tả các kết quả ngắn hạn của một phép thử. Nó cung cấp thông tin về những gì có thể kỳ vọng trong dài hạn. Để chứng minh điều này, Karl Pearson đã từng tung một đồng xu cân đối 24.000 lần! Ông đã ghi lại kết quả của mỗi lần tung và thu được mặt ngửa 12.012 lần. **Trong thí nghiệm của mình, Pearson đã minh họa Luật số lớn**.

**Luật số lớn** phát biểu rằng, khi số lượng phép thử trong một thí nghiệm xác suất tăng lên, sự khác biệt giữa xác suất lý thuyết của một biến cố và tần suất tương đối sẽ tiến dần về không **(xác suất lý thuyết và tần suất tương đối ngày càng tiến lại gần nhau hơn)**. Khi đánh giá các kết quả dài hạn của các thí nghiệm thống kê, chúng ta thường muốn biết kết quả “trung bình”. “Giá trị trung bình dài hạn” này được gọi là Trung bình hoặc Giá trị kỳ vọng của phép thử và được ký hiệu bằng chữ cái Hy Lạp *μ*. Nói cách khác, sau khi thực hiện nhiều phép thử của một thí nghiệm, bạn sẽ kỳ vọng đạt được giá trị trung bình này.

Số trung bình, *μ*, của một hàm xác suất rời rạc chính là giá trị kỳ vọng.

Độ lệch chuẩn, *σ*, của hàm phân phối xác suất là căn bậc hai của phương sai.

Khi tất cả các kết quả trong phân phối xác suất đều đồng khả năng, các công thức này trùng khớp với số trung bình và độ lệch chuẩn của tập hợp các kết quả có thể xảy ra.

Để tìm giá trị kỳ vọng hoặc trung bình dài hạn, *μ*, chỉ cần nhân mỗi giá trị của biến ngẫu nhiên với xác suất tương ứng của nó và cộng các tích lại với nhau.

Một đội bóng đá chơi bóng không, một hoặc hai ngày một tuần. Xác suất họ chơi không ngày là 0,2, xác suất họ chơi một ngày là 0,5 và xác suất họ chơi hai ngày là 0,3. Hãy tìm trung bình dài hạn hoặc giá trị kỳ vọng, *μ*, của số ngày mỗi tuần đội bóng chơi bóng.

Để giải bài toán, trước tiên hãy đặt biến ngẫu nhiên *X* = số ngày đội bóng chơi bóng mỗi tuần. *X* nhận các giá trị 0, 1, 2. Xây dựng bảng hàm phân phối xác suất bằng cách thêm một cột *x***P*(*x*). Trong cột này, bạn sẽ nhân mỗi giá trị *x* với xác suất của nó.

| *x* | *P*(*x*) | *x***P*(*x*) |
| --- | --- | --- |
| 0 | 0,2 | (0)(0,2) = 0 |
| 1 | 0,5 | (1)(0,5) = 0,5 |
| 2 | 0,3 | (2)(0,3) = 0,6 |

Cộng cột cuối cùng *x***P*(*x*) để tìm trung bình dài hạn hoặc giá trị kỳ vọng: (0)(0,2) + (1)(0,5) + (2)(0,3) = 0 + 0,5 + 0,6 = 1,1.

Giá trị kỳ vọng là 1,1. Đội bóng đá, trung bình, dự kiến sẽ chơi bóng đá 1,1 ngày mỗi tuần. Con số 1,1 là số trung bình dài hạn hoặc giá trị kỳ vọng nếu đội bóng đá chơi bóng đá tuần này qua tuần khác. Chúng ta nói *μ* = 1,1.

Một khách hàng đặt 1, 2, hoặc 3 chai nước. Xác suất đặt 1 chai là 0,6, xác suất đặt 2 chai là 0,3, và xác suất đặt 3 chai là 0,1. Hãy tìm số trung bình dài hạn hoặc giá trị kỳ vọng, μ, của số lượng chai mà một khách hàng sẽ đặt.

Hãy tìm giá trị kỳ vọng của số lần tiếng khóc của trẻ sơ sinh đánh thức cha mẹ sau nửa đêm. Giá trị kỳ vọng là số lần dự kiến mỗi tuần mà tiếng khóc của trẻ sơ sinh đánh thức cha mẹ sau nửa đêm. Hãy tính cả độ lệch chuẩn của biến này.

| *x* | *P*(*x*) | *x***P*(*x*) | (*x* – *μ*)^2 ⋅ *P*(*x*) |
| --- | --- | --- | --- |
| 0 | *P*(*x* = 0) =  250250250 | (0)(250)(250)(250) = 0 | (0 – 2,1)^2 ⋅ 0,04 = 0,1764 |
| 1 | *P*(*x* = 1) = (1150)(1150)(1150) | (1)(1150)(1150)(1150) = 115011501150 | (1 – 2,1)^2 ⋅ 0,22 = 0,2662 |
| 2 | *P*(*x* = 2) = 235023502350 | (2)(2350)(2350)(2350) = 465046504650 | (2 – 2,1)^2 ⋅ 0,46 = 0,0046 |
| 3 | *P*(*x* = 3) = 950950950 | (3)(950)(950)(950) = 275027502750 | (3 – 2,1)^2 ⋅ 0,18 = 0,1458 |
| 4 | *P*(*x* = 4) = 450450450 | (4)(450)(450)(450) = 165016501650 | (4 – 2,1)^2 ⋅ 0,08 = 0,2888 |
| 5 | *P*(*x* = 5) = 150150150 | (5)(150)(150)(150) = 550550550 | (5 – 2,1)^2 ⋅ 0,02 = 0,1682 |

Cộng các giá trị trong cột thứ ba của bảng để tìm giá trị kỳ vọng của *X*: 
*μ* = Giá trị kỳ vọng = 105501055010550 = 2,1

Sử dụng *μ* để hoàn thành bảng. Cột thứ tư của bảng này sẽ cung cấp các giá trị bạn cần để tính độ lệch chuẩn. Với mỗi giá trị *x*, hãy nhân bình phương độ lệch của nó với xác suất của nó. (Mỗi độ lệch có định dạng *x* – *μ*).

Cộng các giá trị trong cột thứ tư của bảng:

0,1764 + 0,2662 + 0,0046 + 0,1458 + 0,2888 + 0,1682 = 1,05

Độ lệch chuẩn của *X* là căn bậc hai của tổng này: *σ* = √1.051.051.05 ≈ 1,0247

Một nhà nghiên cứu bệnh viện quan tâm đến số lần trung bình một bệnh nhân sau phẫu thuật sẽ gọi y tá trong một ca trực 12 giờ. Đối với một mẫu ngẫu nhiên gồm 50 bệnh nhân, thông tin sau đây đã được thu thập. Giá trị kỳ vọng là bao nhiêu?

| *x* | *P*(*x*) |
| --- | --- |
| 0 | *P*(*x* = 0) = 450450450 |
| 1 | *P*(*x* = 1) = 850850850 |
| 2 | *P*(*x* = 2) = 165016501650 |
| 3 | *P*(*x* = 3) = 145014501450 |
| 4 | *P*(*x* = 4) = 650650650 |
| 5 | *P*(*x* = 5) = 250250250 |

Giả sử bạn chơi một trò chơi may rủi trong đó năm con số được chọn từ 0, 1, 2, 3, 4, 5, 6, 7, 8, 9. Một máy tính chọn ngẫu nhiên năm con số từ không đến chín có hoàn lại. Bạn trả 2 đô la để chơi và có thể thu lợi nhuận 100.000 đô la nếu bạn khớp tất cả năm con số theo thứ tự (bạn nhận lại 2 đô la của mình cộng với 100.000 đô la). Về lâu dài, lợi nhuận **kỳ vọng** của bạn khi chơi trò chơi này là bao nhiêu?

Để thực hiện bài toán này, hãy lập một bảng giá trị kỳ vọng cho số tiền bạn có thể thu lợi nhuận.

Gọi *X* = số tiền bạn thu lợi nhuận. Các giá trị của *x* không phải là 0, 1, 2, 3, 4, 5, 6, 7, 8, 9. Vì bạn quan tâm đến lợi nhuận (hoặc thua lỗ) của mình, các giá trị của *x* là 100.000 đô la và −2 đô la.

Để thắng, bạn phải chọn đúng tất cả năm con số, theo thứ tự. Xác suất chọn đúng một con số là 110110110 vì có mười con số. Bạn có thể chọn một con số nhiều hơn một lần. Xác suất chọn đúng tất cả năm con số và theo thứ tự là

Do đó, xác suất thắng là 0,00001 và xác suất thua là

Bảng giá trị kỳ vọng như sau:

|  | *x* | *P*(*x*) | *x***P*(*x*) |
| --- | --- | --- | --- |
| Thua lỗ | –2 | 0,99999 | (–2)(0,99999) = –1,99998 |
| Lợi nhuận | 100,000 | 0,00001 | (100000)(0,00001) = 1 |

Vì –0,99998 xấp xỉ –1, bạn sẽ, trung bình, dự kiến mất khoảng 1 đô la cho mỗi trò chơi bạn chơi. Tuy nhiên, mỗi lần bạn chơi, bạn hoặc mất 2 đô la hoặc thu lợi nhuận 100.000 đô la. 1 đô la đó là mức THUA LỖ trung bình hoặc kỳ vọng cho mỗi trò chơi sau khi chơi trò chơi này lặp đi lặp lại.

Bạn đang chơi một trò chơi may rủi, trong đó bốn lá bài được rút ra từ một bộ bài tiêu chuẩn gồm 52 lá. Bạn đoán chất của mỗi lá bài trước khi nó được rút ra. Các lá bài được thay thế vào bộ bài sau mỗi lần rút. Bạn trả $1 để chơi. Nếu bạn đoán đúng chất mỗi lần, bạn sẽ nhận lại số tiền của mình và được thêm $256. Giá trị kỳ vọng của bạn khi chơi trò chơi này trong dài hạn là bao nhiêu?

Giả sử bạn chơi một trò chơi với một đồng xu không cân đối. Bạn chơi mỗi ván bằng cách tung đồng xu một lần. *P*(ngửa) = 232323 và *P*(sấp) = 131313. Nếu bạn tung ra mặt ngửa, bạn trả $6. Nếu bạn tung ra mặt sấp, bạn thắng $10. Nếu bạn chơi trò chơi này nhiều lần, liệu bạn có thu được lợi nhuận không?

#### Bài tập

a. Xác định một biến ngẫu nhiên *X*.

b. Hoàn thành bảng giá trị kỳ vọng sau đây.

|  | *x* |  |  |
| --- | --- | --- | --- |
| THẮNG | 10 | 131313 |  |
| THUA |  |  | –123–123–123 |

c. Giá trị kỳ vọng *μ* là bao nhiêu? Bạn có thu được lợi nhuận không?

Giả sử bạn chơi một trò chơi với một vòng quay. Bạn chơi mỗi ván bằng cách quay vòng quay một lần. *P*(đỏ) = 252525, *P*(xanh dương) = 252525, và *P*(xanh lá) = 151515. Nếu kim dừng ở màu đỏ, bạn trả $10. Nếu kim dừng ở màu xanh dương, bạn không mất tiền cũng không thắng gì cả. Nếu kim dừng ở màu xanh lá, bạn thắng $10. Hoàn thành bảng giá trị kỳ vọng sau đây.

|  | *x* | *P*(*x*) |  |
| --- | --- | --- | --- |
| Đỏ |  |  | –205–205–205 |
| Xanh dương |  | 252525 |  |
| Xanh lá | 10 |  |  |

Giống như dữ liệu, các phân phối xác suất cũng có độ lệch chuẩn. Để tính độ lệch chuẩn (*σ*) của một phân phối xác suất, hãy tìm từng độ lệch so với giá trị kỳ vọng của nó, bình phương độ lệch đó, nhân với xác suất tương ứng, cộng các tích lại và lấy căn bậc hai. Để hiểu cách thực hiện phép tính, hãy xem bảng về số ngày mỗi tuần mà một đội bóng đá nam chơi bóng. Để tìm độ lệch chuẩn, hãy cộng các mục trong cột có nhãn (*x* – *μ*)^2*P*(*x*) và lấy căn bậc hai.

| *x* | *P*(*x*) | *x***P*(*x*) | (*x* – *μ*)^2*P*(*x*) |
| --- | --- | --- | --- |
| 0 | 0,2 | (0)(0,2) = 0 | (0 – 1,1)^2(0,2) = 0,242 |
| 1 | 0,5 | (1)(0,5) = 0,5 | (1 – 1,1)^2(0,5) = 0,005 |
| 2 | 0,3 | (2)(0,3) = 0,6 | (2 – 1,1)^2(0,3) = 0,243 |

Cộng cột cuối cùng trong bảng. 0.242 + 0.005 + 0.243 = 0.490. Độ lệch chuẩn là căn bậc hai của 0,49, hay *σ* = √0.490.490.49 = 0,7

Thông thường đối với các phân phối xác suất, chúng ta sử dụng máy tính cầm tay hoặc máy tính để bàn để tính *μ* và *σ* nhằm giảm sai số làm tròn. Đối với một số phân phối xác suất, có các công thức rút gọn để tính *μ* và *σ*.

#### Bài toán

Tung một con xúc xắc cân đối, sáu mặt hai lần. Gọi *X* = số mặt xuất hiện số chẵn. Hãy lập một bảng giống như [Bảng 4.11](4-2-mean-or-expected-value-and-standard-deviation#fs-idm71508016) và tính số trung bình *μ* và độ lệch chuẩn *σ* của *X*.

Hai chồng thẻ được đặt trên bàn. Mỗi chồng có các thẻ được đánh số từ 1 đến 8. Một thẻ từ mỗi chồng được rút ra. Gọi *X* = số lượng thẻ hiển thị số lẻ. Hãy lập một bảng giống như Bảng 4.11 và tính số trung bình µ và độ lệch chuẩn σ của *X*.

#### Bài toán

Vào lúc 9:30 tối ngày 11 tháng 5 năm 2013, xác suất xảy ra hoạt động địa chấn vừa phải (một trận động đất vừa phải) trong 48 giờ tiếp theo ở Iran là khoảng 21,42%. Giả sử bạn đặt cược rằng một trận động đất vừa phải sẽ xảy ra ở Iran trong khoảng thời gian này. Nếu bạn thắng cược, bạn thắng $50. Nếu bạn thua cược, bạn trả $20. Gọi *X* = số tiền lợi nhuận từ một lần đặt cược.

*P*(thắng) = *P*(một trận động đất vừa phải sẽ xảy ra) = 21,42%

*P*(thua) = *P*(một trận động đất vừa phải sẽ *không* xảy ra) = 100% – 21,42%

Nếu bạn đặt cược nhiều lần, liệu bạn có thu được lợi nhuận không? Hãy giải thích câu trả lời của bạn bằng một câu hoàn chỉnh sử dụng các con số. Độ lệch chuẩn của *X* là bao nhiêu? Hãy lập một bảng tương tự như [Bảng 4.12](4-2-mean-or-expected-value-and-standard-deviation#element-226) và [Bảng 4.13](4-2-mean-or-expected-value-and-standard-deviation#fs-idm21999584) để giúp bạn trả lời những câu hỏi này.

Vào lúc 9:30 tối ngày 11 tháng 5 năm 2013, xác suất xảy ra hoạt động địa chấn vừa phải (một trận động đất vừa phải) trong 48 giờ tiếp theo ở Nhật Bản là khoảng 1,08%. Như trong [Ví dụ 4.8](4-2-mean-or-expected-value-and-standard-deviation#example1.8), bạn đặt cược rằng một trận động đất vừa phải sẽ xảy ra ở Nhật Bản trong khoảng thời gian này. Nếu bạn thắng cược, bạn thắng $100. Nếu bạn thua cược, bạn trả $10. Gọi *X* = số tiền lợi nhuận từ một lần đặt cược. Hãy tìm số trung bình và độ lệch chuẩn của *X*.

Một số hàm xác suất rời rạc phổ biến hơn là nhị thức, hình học, siêu bội và Poisson. Hầu hết các khóa học cơ bản không bao gồm phân phối hình học, siêu bội và Poisson. Giảng viên của bạn sẽ cho bạn biết nếu họ muốn bao gồm các phân phối này.

Hàm phân phối xác suất là một mô hình. Bạn cố gắng khớp một bài toán xác suất vào một **mô hình** hoặc phân phối để thực hiện các tính toán cần thiết. Các phân phối này là những công cụ giúp việc giải các bài toán xác suất trở nên dễ dàng hơn. Mỗi phân phối có những đặc điểm riêng biệt. Việc tìm hiểu các đặc điểm này cho phép bạn phân biệt giữa các phân phối khác nhau.
