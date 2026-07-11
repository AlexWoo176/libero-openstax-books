## 11.3
 
Kiểm định tính độc lập

Các kiểm định tính độc lập liên quan đến việc sử dụng bảng ngẫu nhiên của các giá trị quan sát (dữ liệu).

Thống kê kiểm định cho một kiểm định tính độc lập tương tự như kiểm định mức độ phù hợp:

trong đó:

- *O* = các giá trị quan sát
- *E* = các giá trị kỳ vọng
- *i* = số hàng trong bảng
- *j* = số cột trong bảng
Có i⋅ ji⋅ j số hạng dưới dạng 

(O–E)

2

E

(O–E)

2

E

.

**Kiểm định tính độc lập xác định xem hai yếu tố có độc lập với nhau hay không.** Bạn đã gặp thuật ngữ độc lập lần đầu trong [Các chủ đề về xác suất](3-introduction). Để ôn tập, hãy xem xét ví dụ sau.

Giá trị kỳ vọng cho mỗi ô cần phải đạt ít nhất là năm để bạn có thể sử dụng kiểm định này.

Giả sử *A* = vi phạm tốc độ trong năm qua và *B* = người sử dụng điện thoại di động khi lái xe. Nếu *A* và *B* độc lập thì *P*(*A* VÀ *B*) = *P*(*A*)*P*(*B*). *A* VÀ *B* là biến cố một tài xế nhận vé phạt vi phạm tốc độ trong năm qua và cũng sử dụng điện thoại di động khi lái xe. Giả sử, trong một nghiên cứu về các tài xế đã nhận vé phạt vi phạm tốc độ trong năm qua và sử dụng điện thoại di động khi lái xe, có 755 người được khảo sát. Trong số 755 người, 70 người có vi phạm tốc độ và 685 người không có; 305 người sử dụng điện thoại di động khi lái xe và 450 người không sử dụng.

Gọi *y* = số lượng tài xế dự kiến đã sử dụng điện thoại di động khi lái xe và nhận vé phạt vi phạm tốc độ.

Nếu *A* và *B* độc lập, thì *P*(*A* VÀ *B*) = *P*(*A*)*P*(*B*). Bằng cách thay thế,

y

755

=(

70

755

)(

305

755

)

y

755

=(

70

755

)(

305

755

)

Giải cho *y*: *y* = 

(70)(305)

755

=28.3

(70)(305)

755

=28.3

Khoảng 28 người từ mẫu được dự kiến là có sử dụng điện thoại di động khi lái xe và nhận vé phạt vi phạm tốc độ.

Trong một kiểm định tính độc lập, chúng ta phát biểu giả thuyết không và đối thuyết bằng lời. Vì bảng ngẫu nhiên bao gồm **hai yếu tố**, giả thuyết không phát biểu rằng các yếu tố là **độc lập** và đối thuyết phát biểu rằng chúng **không độc lập (phụ thuộc)**. Nếu chúng ta thực hiện kiểm định tính độc lập bằng cách sử dụng ví dụ trên, thì giả thuyết không là:

*H_0*: Việc là người sử dụng điện thoại di động khi lái xe và việc nhận vé phạt vi phạm tốc độ là các biến cố độc lập.

Nếu giả thuyết không là đúng, chúng ta sẽ kỳ vọng khoảng 28 người sử dụng điện thoại di động khi lái xe và nhận vé phạt vi phạm tốc độ.

**Kiểm định tính độc lập luôn là kiểm định đuôi phải** do cách tính toán thống kê kiểm định. Nếu các giá trị kỳ vọng và quan sát không gần nhau, thì thống kê kiểm định sẽ rất lớn và nằm xa về phía đuôi phải của đường cong khi bình phương, giống như trong kiểm định mức độ phù hợp.

Số bậc tự do cho kiểm định tính độc lập là:

*df* = (số cột - 1)(số hàng - 1)

Công thức sau đây tính toán **số lượng kỳ vọng** (*E*):

Một mẫu gồm 300 sinh viên được lấy. Trong số các sinh viên được khảo sát, 50 người là sinh viên âm nhạc, trong khi 250 người không phải. Chín mươi bảy người nằm trong danh sách danh dự, trong khi 203 người không nằm trong danh sách đó. Nếu chúng ta giả định việc là sinh viên âm nhạc và việc nằm trong danh sách danh dự là các biến cố độc lập, thì số lượng sinh viên âm nhạc dự kiến cũng nằm trong danh sách danh dự là bao nhiêu?

Trong một nhóm tình nguyện, người lớn từ 21 tuổi trở lên tình nguyện từ một đến chín giờ mỗi tuần để dành thời gian cho một người cao tuổi khuyết tật. Chương trình tuyển chọn trong số sinh viên cao đẳng cộng đồng, sinh viên đại học bốn năm và những người không phải là sinh viên. Trong [Bảng 11.15](11-3-test-of-independence#table-73248) là một **mẫu** các tình nguyện viên người lớn và số giờ họ tình nguyện mỗi tuần.

| Loại tình nguyện viên | 1–3 Giờ | 4–6 Giờ | 7–9 Giờ | Tổng hàng |
| --- | --- | --- | --- | --- |
| Sinh viên cao đẳng cộng đồng | 111 | 96 | 48 | 255 |
| Sinh viên đại học bốn năm | 96 | 133 | 61 | 290 |
| Người không phải sinh viên | 91 | 150 | 53 | 294 |
| Tổng cột | 298 | 379 | 162 | 839 |

#### Bài tập

Số giờ tình nguyện có **độc lập** với loại tình nguyện viên không?

Cục Thống kê Lao động thu thập dữ liệu về việc làm tại Hoa Kỳ. Một mẫu được lấy để tính toán số lượng công dân Hoa Kỳ làm việc trong một trong số các ngành công nghiệp theo thời gian. [Bảng 11.17](11-3-test-of-independence#fs-idp61742592) hiển thị kết quả:

| Ngành công nghiệp | 2000 | 2010 | 2020 | Tổng |
| --- | --- | --- | --- | --- |
| Việc làm hưởng lương và tiền công phi nông nghiệp | 13,243 | 13,044 | 15,018 | 41,305 |
| Sản xuất hàng hóa, trừ nông nghiệp | 2,457 | 1,771 | 1,950 | 6,178 |
| Cung cấp dịch vụ | 10,786 | 11,273 | 13,068 | 35,127 |
| Nông nghiệp, lâm nghiệp, đánh bắt và săn bắn | 240 | 214 | 201 | 655 |
| Tự doanh phi nông nghiệp và lao động gia đình không hưởng lương | 931 | 894 | 972 | 2,797 |
| Việc làm hưởng lương và tiền công thứ cấp trong ngành nông nghiệp và hộ gia đình tư nhân | 14 | 11 | 11 | 36 |
| Việc làm thứ cấp với tư cách là người tự doanh hoặc lao động gia đình không hưởng lương | 196 | 144 | 152 | 492 |
| Tổng | 27,867 | 27,351 | 31,372 | 86,590 |

Chúng ta muốn biết liệu sự thay đổi về số lượng việc làm có độc lập với sự thay đổi về năm hay không. Hãy phát biểu giả thuyết không, đối thuyết và bậc tự do.

Trường Cao đẳng De Anza quan tâm đến mối quan hệ giữa mức độ lo âu và nhu cầu thành công trong học tập. Một mẫu ngẫu nhiên gồm 400 sinh viên đã thực hiện một bài kiểm tra đo lường mức độ lo âu và nhu cầu thành công trong học tập. [Bảng 11.18](11-3-test-of-independence#element-875) hiển thị kết quả. Trường Cao đẳng De Anza muốn biết liệu mức độ lo âu và nhu cầu thành công trong học tập có phải là các biến cố độc lập hay không.

| Nhu cầu thành công trong học tập | Lo âu 
cao | Lo âu 
trung bình-cao | Lo âu 
trung bình | Lo âu 
trung bình-thấp | Lo âu 
thấp | Tổng hàng |
| --- | --- | --- | --- | --- | --- | --- |
| Nhu cầu cao | 35 | 42 | 53 | 15 | 10 | 155 |
| Nhu cầu trung bình | 18 | 48 | 63 | 33 | 31 | 193 |
| Nhu cầu thấp | 4 | 5 | 11 | 15 | 17 | 52 |
| Tổng cột | 57 | 95 | 127 | 63 | 58 | 400 |

#### Bài tập

a. Có bao nhiêu sinh viên có mức độ lo âu cao được kỳ vọng sẽ có nhu cầu thành công cao trong học tập?

#### Bài tập

b. Nếu hai biến là độc lập, bạn kỳ vọng có bao nhiêu sinh viên có nhu cầu thành công thấp trong học tập và mức độ lo âu trung bình-thấp?

Tham khảo lại thông tin trong [Thử sức 11.6](11-3-test-of-independence#fs-idm24618832). Dự kiến có bao nhiêu việc làm cung cấp dịch vụ vào năm 2020? Dự kiến có bao nhiêu việc làm hưởng lương và tiền công phi nông nghiệp vào năm 2020?
