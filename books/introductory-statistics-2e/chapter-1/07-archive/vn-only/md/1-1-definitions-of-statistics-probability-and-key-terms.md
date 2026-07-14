## 1.1
 
Các định nghĩa về thống kê học, xác suất và các thuật ngữ chính

Khoa học về Thống kê học / Các đại lượng thống kê giải quyết việc thu thập, phân tích, diễn giải và trình bày Dữ liệu. Chúng ta nhìn thấy và sử dụng dữ liệu trong cuộc sống hàng ngày.

Trong lớp học của bạn, hãy thử bài tập này. Yêu cầu các thành viên trong lớp viết ra thời gian trung bình (tính bằng giờ, làm tròn đến nửa giờ gần nhất) mà họ ngủ mỗi đêm. Giảng viên của bạn sẽ ghi lại dữ liệu. Sau đó, hãy tạo một biểu đồ đơn giản (gọi là **biểu đồ chấm**) từ dữ liệu đó. Một biểu đồ chấm bao gồm một trục số và các dấu chấm (hoặc điểm) được đặt phía trên trục số. Ví dụ, hãy xem xét dữ liệu sau:

5; 
5,5; 
6; 
6; 
6; 
6,5; 
6,5; 
6,5; 
6,5; 
7; 
7; 
8; 
8; 
9

Biểu đồ chấm cho dữ liệu này sẽ như sau:

*Hình 
1.2*

Biểu đồ chấm của bạn trông giống hay khác với ví dụ? Tại sao? Nếu bạn thực hiện cùng một ví dụ trong một lớp học tiếng Anh với cùng số lượng sinh viên, bạn có nghĩ rằng kết quả sẽ giống nhau không? Tại sao có hoặc tại sao không?

Dữ liệu của bạn xuất hiện tập trung ở đâu? Bạn có thể giải thích sự tập trung đó như thế nào?

Các câu hỏi trên yêu cầu bạn phân tích và giải thích dữ liệu của mình. Với ví dụ này, bạn đã bắt đầu nghiên cứu về thống kê học.

Trong khóa học này, bạn sẽ học cách tổ chức và tóm tắt dữ liệu. Việc tổ chức và tóm tắt dữ liệu được gọi là Thống kê mô tả. Hai cách để tóm tắt dữ liệu là bằng cách vẽ biểu đồ và bằng cách sử dụng các con số (ví dụ: tìm giá trị trung bình). Sau khi bạn đã nghiên cứu về xác suất và các phân phối xác suất, bạn sẽ sử dụng các phương pháp chính thức để rút ra kết luận từ dữ liệu "tốt". Các phương pháp chính thức này được gọi là Thống kê suy luận. Suy luận thống kê sử dụng xác suất để xác định mức độ tự tin mà chúng ta có thể đạt được rằng các kết luận của mình là đúng.

Việc giải thích dữ liệu hiệu quả (suy luận) dựa trên các quy trình tốt để tạo ra dữ liệu và việc kiểm tra dữ liệu một cách thấu đáo. Bạn sẽ bắt gặp những gì có vẻ như là quá nhiều công thức toán học để giải thích dữ liệu. Mục tiêu của thống kê học không phải là thực hiện vô số phép tính bằng cách sử dụng các công thức, mà là để đạt được sự hiểu biết về dữ liệu của bạn. Các phép tính có thể được thực hiện bằng máy tính cầm tay hoặc máy tính cá nhân. Sự hiểu biết phải đến từ chính bạn. Nếu bạn có thể nắm vững các kiến thức cơ bản về thống kê học, bạn có thể tự tin hơn trong các quyết định mà bạn đưa ra trong cuộc sống.

### Xác suất

Xác suất là một công cụ toán học được sử dụng để nghiên cứu tính ngẫu nhiên. Nó giải quyết cơ hội (khả năng) xảy ra của một sự kiện. Ví dụ, nếu bạn tung một đồng xu **công bằng** bốn lần, kết quả có thể không phải là hai mặt ngửa và hai mặt sấp. Tuy nhiên, nếu bạn tung cùng đồng xu đó 4.000 lần, các kết quả sẽ gần với một nửa là mặt ngửa và một nửa là mặt sấp. Xác suất lý thuyết kỳ vọng của mặt ngửa trong bất kỳ lần tung nào là 121212 hoặc 0,5. Mặc dù kết quả của một vài lần lặp lại là không chắc chắn, nhưng có một quy luật ổn định về các kết quả khi có nhiều lần lặp lại. Sau khi đọc về nhà thống kê học người Anh Karl Pearson (Hệ số tương quan Pearson), người đã tung một đồng xu 24.000 lần với kết quả là 12.012 mặt ngửa, một trong những tác giả đã tung một đồng xu 2.000 lần. Kết quả là 996 mặt ngửa. Phân số 996200099620009962000 bằng 0,498, rất gần với 0,5, xác suất kỳ vọng.

Lý thuyết xác suất bắt đầu với việc nghiên cứu các trò chơi may rủi như bài poker. Các dự đoán được đưa ra dưới dạng xác suất. Để dự đoán khả năng xảy ra động đất, mưa, hoặc liệu bạn có đạt điểm A trong khóa học này hay không, chúng ta sử dụng xác suất. Các bác sĩ sử dụng xác suất để xác định khả năng một loại vắc-xin gây ra căn bệnh mà vắc-xin đó được cho là sẽ ngăn ngừa. Một nhà môi giới chứng khoán sử dụng xác suất để xác định tỷ suất lợi nhuận trên các khoản đầu tư của khách hàng. Bạn có thể sử dụng xác suất để quyết định xem có nên mua vé số hay không. Trong quá trình nghiên cứu thống kê học, bạn sẽ sử dụng sức mạnh của toán học thông qua các phép tính xác suất để phân tích và diễn giải dữ liệu của mình.

### Các thuật ngữ chính

Trong thống kê học, chúng ta thường muốn nghiên cứu một Tổng thể. Bạn có thể coi quần thể là một tập hợp các cá nhân, sự vật hoặc đối tượng đang được nghiên cứu. Để nghiên cứu quần thể, chúng ta chọn một Mẫu. Ý tưởng của việc Lấy mẫu là chọn một phần (hoặc tập con) của quần thể lớn hơn và nghiên cứu phần đó (mẫu) để thu thập thông tin về quần thể. Dữ liệu là kết quả của việc lấy mẫu từ một quần thể.

Vì việc kiểm tra toàn bộ quần thể tốn rất nhiều thời gian và tiền bạc, lấy mẫu là một kỹ thuật rất thiết thực. Nếu bạn muốn tính điểm trung bình chung tại trường của mình, việc chọn một mẫu sinh viên đang theo học tại trường là điều hợp lý. Dữ liệu thu thập được từ mẫu sẽ là điểm trung bình của các sinh viên đó. Trong các cuộc bầu cử tổng thống, các mẫu thăm dò ý kiến từ 1.000–2.000 người được thực hiện. Cuộc thăm dò ý kiến này được cho là đại diện cho quan điểm của người dân trên toàn quốc. Các nhà sản xuất đồ uống có ga đóng lon lấy các mẫu để xác định xem một lon 16 ounce có chứa đúng 16 ounce đồ uống có ga hay không.

Từ dữ liệu mẫu, chúng ta có thể tính toán một trị thống kê. Một Đại lượng thống kê là một con số đại diện cho một đặc tính của mẫu. Ví dụ, nếu chúng ta coi một lớp toán là một mẫu của quần thể tất cả các lớp toán, thì số điểm trung bình mà sinh viên đạt được trong lớp toán đó vào cuối kỳ là một ví dụ về trị thống kê. Trị thống kê là một ước lượng của tham số quần thể. Một Tham số là một đặc tính số học của toàn bộ quần thể mà có thể được ước lượng bởi một trị thống kê. Vì chúng ta đã coi tất cả các lớp toán là quần thể, nên số điểm trung bình mà mỗi sinh viên đạt được trên tất cả các lớp toán là một ví dụ về tham số.

Một trong những mối quan tâm chính trong lĩnh vực thống kê là mức độ chính xác mà một trị thống kê ước tính một tham số. Độ chính xác thực sự phụ thuộc vào việc mẫu đại diện cho quần thể tốt như thế nào. Mẫu phải chứa các đặc điểm của quần thể để trở thành một Mẫu đại diện. Chúng ta quan tâm đến cả trị thống kê của mẫu và tham số của quần thể trong thống kê suy luận. Trong một chương sau, chúng ta sẽ sử dụng trị thống kê của mẫu để kiểm tra tính hợp lệ của tham số quần thể đã được thiết lập.

Một Biến / Biến số, thường được ký hiệu bằng các chữ cái in hoa như *X* và *Y*, là một đặc điểm hoặc phép đo có thể được xác định cho mỗi thành viên của một quần thể. Các biến có thể là **biến định lượng** hoặc **biến phân loại**. Biến định lượng nhận các giá trị với các đơn vị bằng nhau như cân nặng tính bằng pound và thời gian tính bằng giờ. Biến phân loại đặt một người hoặc vật vào một danh mục. Nếu chúng ta để *X* bằng số điểm đạt được của một sinh viên toán vào cuối học kỳ, thì *X* là một biến định lượng. Nếu chúng ta để *Y* là đảng phái chính trị của một người, thì một số ví dụ về *Y* bao gồm Đảng Cộng hòa, Đảng Dân chủ và Đảng Độc lập. *Y* là một biến phân loại. Chúng ta có thể thực hiện một số phép toán với các giá trị của *X* (ví dụ: tính số điểm trung bình đạt được), nhưng việc thực hiện phép toán với các giá trị của *Y* là vô nghĩa (tính đảng phái trung bình là không có ý nghĩa).

Dữ liệu là các giá trị thực tế của biến. Chúng có thể là số hoặc là từ ngữ. **Datum** (điểm dữ liệu) là một giá trị đơn lẻ.

Hai từ thường xuất hiện trong thống kê là Trung bình và Tỷ lệ. Nếu bạn thực hiện ba bài kiểm tra trong các lớp toán của mình và đạt được điểm số 86, 75 và 92, bạn sẽ tính điểm trung bình của mình bằng cách cộng ba điểm kiểm tra lại và chia cho ba (điểm trung bình của bạn sẽ là 84,3 nếu làm tròn đến một chữ số thập phân). Nếu trong lớp toán của bạn có 40 sinh viên, trong đó 22 là nam và 18 là nữ, thì tỷ lệ sinh viên nam là 224022402240 và tỷ lệ sinh viên nữ là 184018401840. Số trung bình và tỷ lệ sẽ được thảo luận chi tiết hơn trong các chương sau.

Các từ "Trung bình" và "Trung bình" thường được sử dụng thay thế cho nhau. Việc thay thế từ này bằng từ kia là một thông lệ phổ biến. Thuật ngữ kỹ thuật là "số trung bình cộng", và "trung bình" về mặt kỹ thuật là một vị trí trung tâm. Tuy nhiên, trong thực tế giữa những người không phải là nhà thống kê, "trung bình" thường được chấp nhận cho "số trung bình cộng".

#### Bài tập

Xác định các thuật ngữ chính đề cập đến điều gì trong nghiên cứu sau đây. Chúng ta muốn biết số trung bình (mean) số tiền mà sinh viên năm nhất tại Trường Cao đẳng ABC chi cho đồ dùng học tập không bao gồm sách. Chúng ta đã khảo sát ngẫu nhiên 100 sinh viên năm nhất tại trường. Ba trong số những sinh viên đó đã chi lần lượt là $150, $200 và $225.

Xác định các thuật ngữ chính đề cập đến điều gì trong nghiên cứu sau đây. Chúng ta muốn biết số tiền trung bình (số trung bình) chi cho đồng phục học sinh mỗi năm của các gia đình có con theo học tại Knoll Academy. Chúng ta khảo sát ngẫu nhiên 100 gia đình có con trong trường. Ba trong số các gia đình này đã chi lần lượt là $65, $75 và $95.

#### Bài tập

Xác định các thuật ngữ chính đề cập đến điều gì trong nghiên cứu sau đây.

Một nghiên cứu đã được thực hiện tại một trường cao đẳng địa phương để phân tích điểm trung bình tích lũy trung bình của các sinh viên đã tốt nghiệp năm ngoái. Điền chữ cái của cụm từ mô tả đúng nhất từng mục dưới đây.

1. Quần thể_____ 2. Trị thống kê _____ 3. Tham số _____ 4. Mẫu _____ 5. Biến _____ 6. Dữ liệu _____

1. tất cả sinh viên đã theo học tại trường đại học vào năm ngoái
1. điểm trung bình tích lũy (GPA) của một sinh viên đã tốt nghiệp trường đại học vào năm ngoái
1. 3,65, 2,80, 1,50, 3,90
1. một nhóm sinh viên đã tốt nghiệp trường đại học vào năm ngoái, được chọn ngẫu nhiên
1. trung bình điểm trung bình tích lũy (GPA) của các sinh viên đã tốt nghiệp trường đại học vào năm ngoái
1. tất cả sinh viên đã tốt nghiệp trường đại học vào năm ngoái
1. trung bình điểm trung bình tích lũy (GPA) của các sinh viên trong nghiên cứu đã tốt nghiệp trường đại học vào năm ngoái
Xác định các thuật ngữ chính đề cập đến điều gì trong nghiên cứu sau đây.

Một cuộc khảo sát các vận động viên tại một trường đại học đã được thực hiện để nghiên cứu chiều cao của các vận động viên, tính bằng mét. Hãy điền chữ cái của cụm từ mô tả đúng nhất từng mục dưới đây.

1. Quần thể ____
1. Thống kê học ____
1. Tham số ____
1. Mẫu ____
1. Biến ____
1. Dữ liệu _____
1. chiều cao trung bình của các vận động viên trong trường đại học
1. chiều cao trung bình của các vận động viên trong cuộc khảo sát
1. tất cả các vận động viên trong trường đại học
1. tất cả sinh viên trong trường đại học
1. chiều cao của một vận động viên
1. một nhóm vận động viên được chọn ngẫu nhiên
1. 1,82, 1,76, 1,69, 1,93
#### Bài tập

Xác định các thuật ngữ chính đề cập đến điều gì trong nghiên cứu sau đây.

Là một phần của nghiên cứu được thiết kế để kiểm tra độ an toàn của ô tô điện, Ủy ban An toàn Giao thông Quốc gia đã thu thập và xem xét dữ liệu về tác động của một vụ va chạm lên các hình nhân thử nghiệm. Đây là tiêu chí mà họ đã sử dụng:

| Tốc độ khi xe va chạm | Vị trí của “người lái” (tức là hình nhân) |
| --- | --- |
| 35 dặm/giờ | Ghế trước |

Các xe có hình nhân ở ghế trước được cho va chạm vào tường với tốc độ 35 dặm một giờ. Chúng ta muốn biết tỷ lệ hình nhân ở ghế lái có thể bị chấn thương đầu nếu họ là người lái xe thực sự. Chúng ta bắt đầu với một mẫu ngẫu nhiên đơn giản gồm 75 chiếc xe.

Xác định các thuật ngữ chính đề cập đến điều gì trong nghiên cứu sau đây.

Một cuộc khảo sát được thực hiện để kiểm tra thời gian cần thiết để điện thoại di động sạc pin từ 50% đến 100%. Các tiêu chí được sử dụng để thu thập dữ liệu là:

| Công suất của bộ sạc được sử dụng | Loại điện thoại di động được sử dụng |
| --- | --- |
| 30 W | Android |

Chúng ta muốn biết tỷ lệ điện thoại di động Android được sạc đầy 100% trong vòng 30 phút. Chúng ta bắt đầu với một mẫu ngẫu nhiên đơn giản gồm 200 điện thoại di động.

#### Bài tập

Xác định các thuật ngữ chính đề cập đến điều gì trong nghiên cứu sau đây.

Một công ty bảo hiểm muốn xác định tỷ lệ của tất cả các bác sĩ y khoa đã từng tham gia vào một hoặc nhiều vụ kiện tụng sai sót chuyên môn. Công ty chọn ngẫu nhiên 500 bác sĩ từ một danh bạ chuyên nghiệp và xác định số lượng người trong mẫu đã từng tham gia vào một vụ kiện tụng sai sót chuyên môn.

Xác định các thuật ngữ chính đề cập đến điều gì trong nghiên cứu sau đây.

Một nghiên cứu được thực hiện bởi một hãng tin để tìm tỷ lệ của tất cả các tài xế xe tải không bị trừ điểm trên bằng lái của họ. Hãng tin chọn ngẫu nhiên 1000 tài xế xe tải từ danh bạ tài xế xe tải và xác định số lượng tài xế xe tải trong mẫu không bị trừ điểm trên bằng lái của họ.

Hãy thực hiện bài tập sau đây theo nhóm tối đa bốn người. Tìm quần thể, mẫu, tham số, trị thống kê, biến và dữ liệu cho nghiên cứu sau: Bạn muốn xác định số trung bình (mean) số ly sữa mà sinh viên đại học uống mỗi ngày. Giả sử hôm qua, trong lớp tiếng Anh của bạn, bạn đã hỏi năm sinh viên xem họ đã uống bao nhiêu ly sữa vào ngày hôm trước. Các câu trả lời là 1, 0, 1, 3 và 4 ly sữa.
