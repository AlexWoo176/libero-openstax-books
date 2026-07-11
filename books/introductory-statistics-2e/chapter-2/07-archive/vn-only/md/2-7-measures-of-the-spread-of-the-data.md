## 2.7
 
Các thước đo độ phân tán của dữ liệu

Một đặc điểm quan trọng của bất kỳ tập dữ liệu nào là sự biến thiên trong dữ liệu đó. Trong một số tập dữ liệu, các giá trị dữ liệu tập trung gần số trung bình; trong các tập dữ liệu khác, các giá trị dữ liệu phân tán rộng hơn so với số trung bình. Thước đo phổ biến nhất về sự biến thiên, hay độ phân tán, là độ lệch chuẩn. Độ lệch chuẩn là một con số đo lường mức độ xa của các giá trị dữ liệu so với số trung bình của chúng.

### Độ lệch chuẩn

- cung cấp một thước đo bằng số về tổng mức độ biến thiên trong một tập dữ liệu, và
- có thể được sử dụng để xác định xem một giá trị dữ liệu cụ thể nằm gần hay xa số trung bình.
#### Độ lệch chuẩn cung cấp một thước đo về sự biến thiên tổng thể trong một tập dữ liệu

Độ lệch chuẩn luôn dương hoặc bằng không. Độ lệch chuẩn nhỏ khi tất cả dữ liệu tập trung gần số trung bình, thể hiện ít sự biến thiên hoặc độ phân tán. Độ lệch chuẩn lớn hơn khi các giá trị dữ liệu phân tán xa hơn so với số trung bình, thể hiện sự biến thiên nhiều hơn.

Giả sử rằng chúng ta đang nghiên cứu khoảng thời gian khách hàng chờ đợi tại quầy thanh toán ở siêu thị *A* và siêu thị *B*. Thời gian chờ trung bình tại cả hai siêu thị là năm phút. Tại siêu thị *A*, độ lệch chuẩn cho thời gian chờ là hai phút; tại siêu thị *B*, độ lệch chuẩn cho thời gian chờ là bốn phút.

Vì siêu thị *B* có độ lệch chuẩn cao hơn, chúng ta biết rằng có nhiều sự biến thiên hơn trong thời gian chờ tại siêu thị *B*. Nhìn chung, thời gian chờ tại siêu thị *B* phân tán xa hơn so với giá trị trung bình; thời gian chờ tại siêu thị *A* tập trung gần giá trị trung bình hơn.

#### Độ lệch chuẩn có thể được sử dụng để xác định xem một giá trị dữ liệu nằm gần hay xa số trung bình.

Giả sử rằng Rosa và Binh đều mua sắm tại siêu thị *A*. Rosa chờ tại quầy thanh toán trong bảy phút và Binh chờ trong một phút. Tại siêu thị *A*, thời gian chờ trung bình là năm phút và độ lệch chuẩn là hai phút. Độ lệch chuẩn có thể được sử dụng để xác định xem một giá trị dữ liệu nằm gần hay xa giá trị trung bình.

**Rosa chờ trong bảy phút:**

- Bảy lớn hơn số trung bình là năm hai phút; hai phút bằng một độ lệch chuẩn.
- Thời gian chờ bảy phút của Rosa **lớn hơn số trung bình** năm phút **là hai phút**.
- Thời gian chờ bảy phút của Rosa **cao hơn số trung bình** năm phút **một độ lệch chuẩn**.
**Binh chờ trong một phút.**

- Một nhỏ hơn số trung bình là năm bốn phút; bốn phút bằng hai độ lệch chuẩn.
- Thời gian chờ một phút của Binh **nhỏ hơn số trung bình** năm phút **là bốn phút**.
- Thời gian chờ một phút của Binh **thấp hơn số trung bình** năm phút **hai độ lệch chuẩn**.
- Một giá trị dữ liệu cách số trung bình hai độ lệch chuẩn chỉ nằm ở ranh giới của những gì mà nhiều nhà thống kê coi là xa số trung bình. Việc coi dữ liệu là xa số trung bình nếu nó cách xa hơn hai độ lệch chuẩn giống như một "quy tắc ngón tay cái" (quy tắc kinh nghiệm) hơn là một quy tắc cứng nhắc. Nhìn chung, hình dạng của phân phối dữ liệu ảnh hưởng đến lượng dữ liệu nằm xa hơn hai độ lệch chuẩn. (Bạn sẽ tìm hiểu thêm về điều này trong các chương sau.)
Trục số có thể giúp bạn hiểu về độ lệch chuẩn. Nếu chúng ta đặt năm và bảy trên một trục số, bảy nằm bên phải của năm. Khi đó, chúng ta nói rằng bảy cách **một** độ lệch chuẩn về phía **bên phải** của năm vì 5 + (1)(2) = 7.

Nếu một cũng là một phần của tập dữ liệu, thì một cách **hai** độ lệch chuẩn về phía **bên trái** của năm vì 5 + (–2)(2) = 1.

*Hình 
2.24*

- Nhìn chung, một **giá trị = số trung bình + (số lượng độ lệch chuẩn)(độ lệch chuẩn)**
- trong đó số lượng độ lệch chuẩn = số lượng độ lệch chuẩn
- số lượng độ lệch chuẩn không nhất thiết phải là một số nguyên
- Một **nhỏ hơn số trung bình** năm **hai độ lệch chuẩn** vì: 1 = 5 + (–2)(2).
Phương trình **giá trị = trung bình + (số lượng độ lệch chuẩn)(độ lệch chuẩn)** có thể được biểu diễn cho một mẫu và cho một quần thể.

- **mẫu:** 𝑥 = ̅̅̅̅̅𝑥 + (#𝑜⁢𝑓⁡𝑆⁢𝑇⁢𝐷⁢𝐸⁢𝑉)⁢(𝑠)x = x¯ + (#o⁢f⁡S⁢T⁢D⁢E⁢V)⁢(s)x = x¯ + (#ofSTDEV)(s)
- **Quần thể:** 𝑥=𝜇+(#𝑜⁢𝑓⁡𝑆⁢𝑇⁢𝐷⁢𝐸⁢𝑉)⁢(𝜎)x=μ+(#o⁢f⁡S⁢T⁢D⁢E⁢V)⁢(σ)x=μ+(#ofSTDEV)(σ)
Chữ cái thường *s* đại diện cho độ lệch chuẩn mẫu và chữ cái Hy Lạp *σ* (sigma, chữ thường) đại diện cho độ lệch chuẩn quần thể.

Ký hiệu ̅̅̅̅̅𝑥x¯x¯ là trung bình mẫu và ký hiệu Hy Lạp 𝜇μμ là trung bình quần thể.

#### Tính toán Độ lệch chuẩn

Nếu *x* là một số, thì hiệu số "*x* – trung bình" được gọi là **độ lệch** của nó. Trong một tập dữ liệu, có bao nhiêu phần tử thì có bấy nhiêu độ lệch. Các độ lệch được sử dụng để tính độ lệch chuẩn. Nếu các số thuộc về một quần thể, theo ký hiệu, một độ lệch là *x* – *μ*. Đối với dữ liệu mẫu, theo ký hiệu, một độ lệch là *x* – ̅̅̅̅̅𝑥x¯x¯.

Quy trình tính độ lệch chuẩn phụ thuộc vào việc các con số đó là toàn bộ quần thể hay là dữ liệu từ một mẫu. Các phép tính tương tự nhau nhưng không giống hệt nhau. Do đó, ký hiệu được sử dụng để đại diện cho độ lệch chuẩn phụ thuộc vào việc nó được tính từ quần thể hay từ mẫu. Chữ cái thường s đại diện cho độ lệch chuẩn mẫu và chữ cái Hy Lạp *σ* (sigma, chữ thường) đại diện cho độ lệch chuẩn quần thể. Nếu mẫu có cùng các đặc điểm với quần thể, thì s sẽ là một ước lượng tốt cho *σ*.

Để tính độ lệch chuẩn, trước tiên chúng ta cần tính phương sai. Phương sai là **trung bình của bình phương các độ lệch** (các giá trị *x* – ̅̅̅̅̅𝑥x¯x¯ đối với mẫu, hoặc các giá trị *x* – *μ* đối với quần thể). Ký hiệu *σ*^2 đại diện cho phương sai quần thể; độ lệch chuẩn quần thể *σ* là căn bậc hai của phương sai quần thể. Ký hiệu *s*^2 đại diện cho phương sai mẫu; độ lệch chuẩn mẫu *s* là căn bậc hai của phương sai mẫu. Bạn có thể coi độ lệch chuẩn là một dạng trung bình đặc biệt của các độ lệch.

Nếu các con số đến từ một cuộc điều tra toàn bộ **quần thể** chứ không phải một mẫu, khi chúng ta tính trung bình của các bình phương độ lệch để tìm phương sai, chúng ta chia cho *N*, là số lượng phần tử trong quần thể. Nếu dữ liệu đến từ một **mẫu** thay vì một quần thể, khi chúng ta tính trung bình của các bình phương độ lệch, chúng ta chia cho ***n* – 1**, ít hơn một đơn vị so với số lượng phần tử trong mẫu.

#### Các công thức cho Độ lệch chuẩn mẫu

- 𝑠=√𝛴⁢(𝑥−̅̅̅̅̅𝑥)2𝑛−1s=Σ⁢(x−x¯)2n−1s=Σ(x−x¯)2n−1 hoặc 𝑠=√𝛴⁢𝑓⁡(𝑥−̅̅̅̅̅𝑥)2𝑛−1s=Σ⁢f⁡(x−x¯)2n−1s=Σf(x−x¯)2n−1
- Đối với độ lệch chuẩn mẫu, mẫu số là ***n* - 1**, tức là kích thước mẫu TRỪ ĐI 1.
#### Các công thức cho Độ lệch chuẩn quần thể

- 𝜎⁢ = ⁢√𝛴⁢(𝑥−𝜇)2𝑁σ⁢ = ⁢Σ⁢(x−μ)2Nσ = Σ(x−μ)2N hoặc 𝜎⁢ = ⁢√𝛴⁢𝑓⁡(𝑥–𝜇)2𝑁σ⁢ = ⁢Σ⁢f⁡(x–μ)2Nσ = Σf(x–μ)2N
- Đối với độ lệch chuẩn quần thể, mẫu số là *N*, số lượng phần tử trong quần thể.
Trong các công thức này, *f* đại diện cho tần số xuất hiện của một giá trị. Ví dụ, nếu một giá trị xuất hiện một lần, *f* bằng một. Nếu một giá trị xuất hiện ba lần trong tập dữ liệu hoặc quần thể, *f* bằng ba.

### Sự biến thiên mẫu của trị thống kê

Trị thống kê của một phân phối mẫu đã được thảo luận trong [Thống kê mô tả: Các thước đo trung tâm của dữ liệu](2-5-measures-of-the-center-of-the-data). Mức độ biến thiên của trị thống kê từ mẫu này sang mẫu khác được gọi là sự biến thiên mẫu của trị thống kê. Bạn thường đo lường sự biến thiên mẫu của một trị thống kê bằng sai số chuẩn của nó. **Sai số chuẩn của giá trị trung bình** là một ví dụ về sai số chuẩn. Đó là một độ lệch chuẩn đặc biệt và được gọi là độ lệch chuẩn của phân phối mẫu của giá trị trung bình. Bạn sẽ tìm hiểu về sai số chuẩn của giá trị trung bình trong chương [Định lý giới hạn trung tâm](7-introduction) (không phải bây giờ). Ký hiệu cho sai số chuẩn của giá trị trung bình là 𝜎√𝑛σnσn, trong đó *σ* là độ lệch chuẩn của quần thể và n là kích thước của mẫu.

**Trong thực tế, HÃY SỬ DỤNG MÁY TÍNH CẦM TAY HOẶC PHẦN MỀM MÁY TÍNH ĐỂ TÍNH ĐỘ LỆCH CHUẨN.** Nếu bạn đang sử dụng máy tính TI-83, 83+, 84+, bạn cần chọn độ lệch chuẩn thích hợp *σ_x* hoặc *s_x* từ các trị thống kê tóm tắt. Chúng ta sẽ tập trung vào việc sử dụng và diễn giải thông tin mà độ lệch chuẩn cung cấp. Tuy nhiên, bạn nên nghiên cứu ví dụ từng bước sau đây để giúp bạn hiểu cách độ lệch chuẩn đo lường sự biến thiên so với số trung bình. (Các hướng dẫn sử dụng máy tính nằm ở cuối ví dụ này.)

Trong một lớp học lớp năm, giáo viên quan tâm đến số trung bình tuổi và độ lệch chuẩn mẫu của tuổi các học sinh. Dữ liệu sau đây là tuổi của một MẪU gồm *n* = 20 học sinh lớp năm. Tuổi được làm tròn đến nửa năm gần nhất:

9; 9.5; 9.5; 10; 10; 10; 10; 10.5; 10.5; 10.5; 10.5; 11; 11; 11; 11; 11; 11; 11.5; 11.5; 11.5;

Số trung bình tuổi là 10,53 năm, làm tròn đến hai chữ số thập phân.

Phương sai có thể được tính bằng cách sử dụng bảng. Sau đó, độ lệch chuẩn được tính bằng cách lấy căn bậc hai của phương sai. Chúng ta sẽ giải thích các phần của bảng sau khi tính *s*.

| Dữ liệu | Tần số | Độ lệch | *Độ lệch*^2 | (Tần số.)(*Độ lệch*^2) |
| --- | --- | --- | --- | --- |
| *x* | *f* | ( – ) | ( – ) | ()( – ) |
| 9 | 1 | 9 – 10.525 = –1.525 | (–1.525)^2 = 2.325625 | 1 × 2.325625 = 2.325625 |
| 9.5 | 2 | 9.5 – 10.525 = –1.025 | (–1.025)^2 = 1.050625 | 2 × 1.050625 = 2.101250 |
| 10 | 4 | 10 – 10.525 = –0.525 | (–0.525)^2 = 0.275625 | 4 × 0.275625 = 1.1025 |
| 10.5 | 4 | 10.5 – 10.525 = –0.025 | (–0.025)^2 = 0.000625 | 4 × 0.000625 = 0.0025 |
| 11 | 6 | 11 – 10.525 = 0.475 | (0.475)^2 = 0.225625 | 6 × 0.225625 = 1.35375 |
| 11.5 | 3 | 11.5 – 10.525 = 0.975 | (0.975)^2 = 0.950625 | 3 × 0.950625 = 2.851875 |
|  |  |  |  | Tổng là 9,7375 |

Phương sai mẫu, *s*^2, bằng tổng của cột cuối cùng (9,7375) chia cho tổng số giá trị dữ liệu trừ đi một (20 – 1):

𝑠2=9.737520−1=0.5125s2=9.737520−1=0.5125s2=9.737520−1=0.5125

**Độ lệch chuẩn mẫu** *s* bằng căn bậc hai của phương sai mẫu:

𝑠=√0.5125=0.715891,s=0.5125=0.715891,s=0.5125=0.715891, được làm tròn đến hai chữ số thập phân, *s* = 0,72.

**Thông thường, bạn thực hiện tính toán độ lệch chuẩn trên máy tính cầm tay hoặc máy tính của mình.** Các kết quả trung gian không được làm tròn. Điều này được thực hiện để đảm bảo độ chính xác.

#### Bài toán

- Đối với các bài toán sau, hãy nhớ rằng **giá trị = số trung bình + (số độ lệch chuẩn)(độ lệch chuẩn)**. Kiểm tra lại số trung bình và độ lệch chuẩn bằng máy tính cầm tay hoặc máy tính.
- Đối với một mẫu: *x* = ̅̅̅̅̅𝑥x¯x¯ + (số độ lệch chuẩn)(*s*)
- Đối với một quần thể: *x* = *μ* + (số độ lệch chuẩn)(*σ*)
- Đối với ví dụ này, hãy sử dụng *x* = ̅̅̅̅̅𝑥x¯x¯ + (số độ lệch chuẩn)(*s*) vì dữ liệu được lấy từ một mẫu
1. Kiểm tra lại số trung bình và độ lệch chuẩn trên máy tính cầm tay hoặc máy tính của bạn.
1. Tìm giá trị cao hơn số trung bình một độ lệch chuẩn. Tìm (̅̅̅̅̅𝑥x¯x¯ + 1s).
1. Tìm giá trị thấp hơn số trung bình hai độ lệch chuẩn. Tìm (̅̅̅̅̅𝑥x¯x¯ – 2s).
1. Tìm các giá trị cách số trung bình 1,5 độ lệch chuẩn **về cả hai phía** (thấp hơn và cao hơn).
Trong một đội bóng chày, tuổi của mỗi cầu thủ như sau:

21; 21; 22; 23; 24; 24; 25; 25; 28; 29; 29; 31; 32; 33; 33; 34; 35; 36; 36; 36; 36; 38; 38; 38; 40

Sử dụng máy tính cầm tay hoặc máy tính của bạn để tìm số trung bình và độ lệch chuẩn. Sau đó, tìm giá trị lớn hơn số trung bình hai độ lệch chuẩn.

#### Giải thích về cách tính độ lệch chuẩn được hiển thị trong bảng

Các độ lệch cho thấy dữ liệu phân tán như thế nào quanh số trung bình. Giá trị dữ liệu 11,5 cách xa số trung bình hơn so với giá trị dữ liệu 11, điều này được thể hiện qua các độ lệch 0,97 và 0,47. Độ lệch dương xảy ra khi giá trị dữ liệu lớn hơn số trung bình, trong khi độ lệch âm xảy ra khi giá trị dữ liệu nhỏ hơn số trung bình. Độ lệch là –1,525 đối với giá trị dữ liệu chín. **Nếu bạn cộng các độ lệch lại, tổng luôn bằng không.** (Đối với [Ví dụ 2.32](2-7-measures-of-the-spread-of-the-data#element-655), có *n* = 20 độ lệch.) Vì vậy, bạn không thể chỉ đơn giản cộng các độ lệch để có được độ phân tán của dữ liệu. Bằng cách bình phương các độ lệch, bạn làm cho chúng trở thành các số dương, và tổng cũng sẽ là số dương. Do đó, phương sai là trung bình của các độ lệch bình phương.

Phương sai là một thước đo bình phương và không có cùng đơn vị với dữ liệu. Việc lấy căn bậc hai sẽ giải quyết vấn đề này. Độ lệch chuẩn đo lường độ phân tán theo cùng đơn vị với dữ liệu.

Lưu ý rằng thay vì chia cho *n* = 20, phép tính đã chia cho *n* – 1 = 20 – 1 = 19 vì dữ liệu là một mẫu. Đối với phương sai **mẫu**, chúng ta chia cho kích thước mẫu trừ đi một (*n* – 1). Tại sao không chia cho *n*? Câu trả lời liên quan đến phương sai tổng thể. **Phương sai mẫu là một ước lượng của phương sai tổng thể.** Dựa trên toán học lý thuyết đằng sau các phép tính này, việc chia cho (*n* – 1) mang lại ước lượng tốt hơn về phương sai tổng thể.

Bạn nên tập trung vào những gì độ lệch chuẩn cho chúng ta biết về dữ liệu. Độ lệch chuẩn là một con số đo lường mức độ phân tán của dữ liệu so với số trung bình. Hãy để máy tính cầm tay hoặc máy tính thực hiện các phép tính số học.

Độ lệch chuẩn, *s* hoặc *σ*, bằng không hoặc lớn hơn không. Việc mô tả dữ liệu dựa trên sự phân tán được gọi là "sự biến thiên". Sự biến thiên trong dữ liệu phụ thuộc vào phương pháp thu thập kết quả; ví dụ, bằng cách đo lường hoặc bằng cách lấy mẫu ngẫu nhiên. Khi độ lệch chuẩn bằng không, không có sự phân tán; nghĩa là, tất cả các giá trị dữ liệu đều bằng nhau. Độ lệch chuẩn nhỏ khi tất cả dữ liệu tập trung gần số trung bình, và lớn hơn khi các giá trị dữ liệu cho thấy sự biến thiên nhiều hơn so với số trung bình. Khi độ lệch chuẩn lớn hơn nhiều so với không, các giá trị dữ liệu phân tán rất rộng quanh số trung bình; các giá trị ngoại lệ có thể làm cho *s* hoặc *σ* trở nên rất lớn.

Độ lệch chuẩn, khi mới được giới thiệu, có thể có vẻ không rõ ràng. Bằng cách vẽ biểu đồ dữ liệu của bạn, bạn có thể có "cảm nhận" tốt hơn về các độ lệch và độ lệch chuẩn. Bạn sẽ thấy rằng trong các phân phối đối xứng, độ lệch chuẩn có thể rất hữu ích nhưng trong các phân phối bị lệch, độ lệch chuẩn có thể không giúp ích được nhiều. Lý do là hai phía của một phân phối bị lệch có độ phân tán khác nhau. Trong một phân phối bị lệch, tốt hơn là nên xem xét tứ phân vị thứ nhất, trung vị, tứ phân vị thứ ba, giá trị nhỏ nhất và giá trị lớn nhất. Vì các con số có thể gây nhầm lẫn, **luôn vẽ biểu đồ dữ liệu của bạn**. Hãy hiển thị dữ liệu của bạn trong một biểu đồ histogram hoặc một biểu đồ hộp.

#### Bài toán

Sử dụng dữ liệu sau (điểm thi lần thứ nhất) từ lớp tiền giải tích mùa xuân của Giáo sư Dean:

33; 42; 49; 49; 53; 55; 55; 61;   63; 67; 68; 68; 69; 69; 72; 73;   74; 78; 80; 83; 88; 88; 88; 90;   92; 94; 94; 94; 94; 96; 100

1. Tạo một biểu đồ chứa dữ liệu, tần số, tần suất tương đối và tần suất tương đối lũy tích với ba chữ số thập phân.
1. Calculate the following to one decimal place using a TI-83+ or TI-84 calculator:
Trung bình mẫu
Độ lệch chuẩn mẫu
Trung vị
Tứ phân vị thứ nhất
Tứ phân vị thứ ba
*Khoảng biến thiên tứ phân vị (IQR)*
1. Vẽ biểu đồ hộp và biểu đồ histogram trên cùng một hệ trục. Đưa ra các nhận xét về biểu đồ hộp, biểu đồ histogram và bảng dữ liệu.
Râu trái dài trong biểu đồ hộp được phản ánh ở phía bên trái của biểu đồ histogram. Độ phân tán của điểm thi trong 50% thấp hơn lớn hơn (73 – 33 = 40) so với độ phân tán trong 50% cao hơn (100 – 73 = 27). Biểu đồ histogram, biểu đồ hộp và bảng đều phản ánh điều này. Có một số lượng đáng kể các điểm A và B (80, 90 và 100). Biểu đồ histogram cho thấy rõ điều này. Biểu đồ hộp cho chúng ta thấy rằng 50% điểm thi ở giữa (*IQR* = 29) là các điểm D, C và B. Biểu đồ hộp cũng cho chúng ta thấy rằng 25% điểm thi thấp nhất là các điểm D và F.

Dữ liệu sau đây cho thấy các loại thức ăn cho thú cưng khác nhau mà các cửa hàng trong khu vực cung cấp.

6; 6; 6; 6; 7; 7; 7; 7; 7; 8; 9; 9; 9; 9; 10; 10; 10; 10; 10; 11; 11; 11; 11; 12; 12; 12; 12; 12; 12;

Tính trung bình mẫu và độ lệch chuẩn mẫu đến một chữ số thập phân bằng cách sử dụng máy tính TI-83+ hoặc TI-84.

### Độ lệch chuẩn của bảng tần số ghép nhóm

𝑀⁢𝑒⁢𝑎⁢𝑛 𝑜⁢𝑓 𝐹⁡𝑟⁢𝑒⁢𝑞⁢𝑢⁢𝑒⁢𝑛⁢𝑐⁢𝑦 𝑇⁢𝑎⁢𝑏⁢𝑙⁢𝑒=∑𝑓⁡𝑚∑𝑓M⁢e⁢a⁢n o⁢f F⁡r⁢e⁢q⁢u⁢e⁢n⁢c⁢y T⁢a⁢b⁢l⁢e=∑f⁡m∑fMean of Frequency Table=∑fm∑f

𝑓=f=f=*m*

Cũng giống như việc chúng ta không thể tìm thấy số trung bình chính xác, chúng ta cũng không thể tìm thấy độ lệch chuẩn chính xác. Hãy nhớ rằng độ lệch chuẩn mô tả bằng số độ lệch kỳ vọng mà một giá trị dữ liệu có so với số trung bình. Nói một cách đơn giản, độ lệch chuẩn cho phép chúng ta so sánh mức độ "bất thường" của dữ liệu cá nhân so với số trung bình.

Tìm độ lệch chuẩn cho dữ liệu trong [Bảng 2.32](2-7-measures-of-the-spread-of-the-data#fs-idm67330768).

| Lớp | Tần số, 𝑓ff | Trung điểm, 𝑚mm | 𝑓 ⋅𝑚f⋅mf⋅m | ̅̅̅̅̅𝑥x¯x¯ | 𝑚 −̅̅̅̅̅𝑥m-x¯m-x¯ | (𝑚−̅̅̅̅̅𝑥)2(m-x¯)2(m-x¯)2 | 𝑓⁡(𝑚−̅̅̅̅̅𝑥)2f⁡(m-x¯)2f(m-x¯)2 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 0–2 | 1 | 1 | 1 | 7.58 | -6.58 | 43.2964 | 43.2964 |
| 3–5 | 6 | 4 | 24 | 7.58 | -3.58 | 12.8164 | 76.8984 |
| 6–8 | 10 | 7 | 70 | 7.58 | -0.58 | 0.3364 | 3.364 |
| 9–11 | 7 | 10 | 70 | 7.58 | 2.42 | 5.8564 | 40.9948 |
| 12–14 | 0 | 13 | 0 | 7.58 | 5.42 | 29.3764 | 0 |
| 15–17 | 2 | 16 | 32 | 7.58 | 8.42 | 70.8964 | 141.7928 |
| **TỔNG** (𝜮ΣΣ) | 26 |  | 197 |  |  |  | 306.3464 |

Các giá trị trong cột thứ hai, thứ ba và thứ tư của [Bảng 2.32](2-7-measures-of-the-spread-of-the-data#fs-idm67330768) được sử dụng để tính số trung bình của bảng tần số đã nhóm, giá trị trong cột thứ năm.

Sau khi tính ̅̅̅̅̅𝑥x¯x¯, hãy tìm hiệu số, 𝑚 −̅̅̅̅̅𝑥m-x¯m-x¯, cho mỗi trung điểm, 𝑚mm. Tiếp theo, bình phương mỗi hiệu số. Trong cột cuối cùng, hãy tính tích của tần số và bình phương hiệu số cho mỗi lớp.

Bảng này giúp dễ dàng sử dụng công thức để tính độ lệch chuẩn của một bảng tần số đã nhóm:

Mặc dù công thức không phức tạp, nhưng các phép tính này thường được thực hiện bằng công nghệ.

Tìm độ lệch chuẩn cho dữ liệu từ ví dụ trước

| Lớp | Tần số, *f* |
| --- | --- |
| 0–2 | 1 |
| 3–5 | 6 |
| 6–8 | 10 |
| 9–11 | 7 |
| 12–14 | 0 |
| 15–17 | 2 |

Đầu tiên, nhấn phím **STAT** và chọn **1:Edit**

*Hình 
2.26*

Nhập các giá trị trung điểm vào **L1** và các tần số vào **L2**

*Hình 
2.27*

Chọn **STAT**, **CALC**, và **1: 1-Var Stats**

*Hình 
2.28*

Chọn **2^nd** sau đó chọn **1**, rồi **2^nd** sau đó chọn **2 Enter**

*Hình 
2.29*

Bạn sẽ thấy hiển thị cả độ lệch chuẩn tổng thể, *σ_x*, và độ lệch chuẩn mẫu, *s_x*.

### So sánh các giá trị từ các tập dữ liệu khác nhau

Độ lệch chuẩn rất hữu ích khi so sánh các giá trị dữ liệu đến từ các tập dữ liệu khác nhau. Nếu các tập dữ liệu có số trung bình và độ lệch chuẩn khác nhau, thì việc so sánh trực tiếp các giá trị dữ liệu có thể gây hiểu lầm.

- Đối với mỗi giá trị dữ liệu, hãy tính xem giá trị đó cách số trung bình bao nhiêu độ lệch chuẩn.
- Sử dụng công thức: giá trị = số trung bình + (số lượng độ lệch chuẩn)(độ lệch chuẩn); giải tìm số lượng độ lệch chuẩn.
- #𝑜⁢𝑓⁡𝑆⁢𝑇⁢𝐷⁢𝐸⁢𝑉⁢𝑠=giá rị – trung bìnhđộ lệch chuẩn
- So sánh kết quả của phép tính này.
#ofSTDEVs thường được gọi là "*z*-score"; chúng ta có thể sử dụng ký hiệu *z*. Dưới dạng ký hiệu, các công thức trở thành:

| Mẫu | 𝑥xx̅̅̅̅̅𝑥x¯x¯*zs* | 𝑧=𝑥⁢ − ⁢̅̅̅̅̅𝑥𝑠z=x⁢ − ⁢x̅sz=x − x¯s |
| --- | --- | --- |
| Quần thể | 𝑥xx𝜇μμ*zσ* | 𝑧=𝑥⁢ − ⁢𝜇𝜎z=x⁢ − ⁢μσz=x − μσ |

#### Bài toán

Hai học sinh, John và Ali, từ các trường trung học khác nhau, muốn tìm ra ai có điểm trung bình (GPA) cao nhất khi so sánh với trường của mình. Học sinh nào có GPA cao nhất khi so sánh với trường của cậu ấy?

| Sinh viên | GPA | GPA trung bình của trường | Độ lệch chuẩn của trường |
| --- | --- | --- | --- |
| John | 2.85 | 3.0 | 0.7 |
| Ali | 77 | 80 | 10 |

Hai vận động viên bơi lội, Angie và Beth, từ các đội khác nhau, muốn tìm ra ai có thời gian bơi nhanh nhất cho cự ly 50 mét tự do khi so sánh với đội của mình. Vận động viên nào có thời gian nhanh nhất khi so sánh với đội của cô ấy?

| Vận động viên bơi lội | Thời gian (giây) | Thời gian trung bình của đội | Độ lệch chuẩn của đội |
| --- | --- | --- | --- |
| Angie | 26.2 | 27.2 | 0.8 |
| Beth | 27.3 | 30.1 | 1.4 |

Các danh sách sau đây đưa ra một vài sự thật cung cấp cái nhìn sâu sắc hơn về những gì độ lệch chuẩn cho chúng ta biết về sự phân phối của dữ liệu.

- Ít nhất 75% dữ liệu nằm trong phạm vi hai độ lệch chuẩn so với số trung bình.
- Ít nhất 89% dữ liệu nằm trong phạm vi ba độ lệch chuẩn so với số trung bình.
- Ít nhất 95% dữ liệu nằm trong phạm vi 4.5 độ lệch chuẩn so với số trung bình.
- Đây được gọi là Quy tắc Chebyshev.
- Xấp xỉ 68% dữ liệu nằm trong phạm vi một độ lệch chuẩn so với số trung bình.
- Xấp xỉ 95% dữ liệu nằm trong phạm vi hai độ lệch chuẩn so với số trung bình.
- Hơn 99% dữ liệu nằm trong phạm vi ba độ lệch chuẩn so với số trung bình.
- Điều này được gọi là Quy tắc thực nghiệm.
- Cần lưu ý rằng quy tắc này chỉ áp dụng khi hình dạng phân phối của dữ liệu có dạng hình chuông và đối xứng. Chúng ta sẽ tìm hiểu thêm về điều này khi nghiên cứu phân phối xác suất "Chuẩn" hoặc "Gaussian" trong các chương sau.
