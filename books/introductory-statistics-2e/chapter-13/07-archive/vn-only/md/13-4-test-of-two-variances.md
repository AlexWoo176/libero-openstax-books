## 13.4
 
Kiểm định hai phương sai

Một trong những ứng dụng khác của phân phối *F* là kiểm định hai phương sai. Việc so sánh hai phương sai thường được ưu tiên hơn so với việc so sánh hai giá trị trung bình. Ví dụ, các nhà quản lý trường đại học muốn hai giảng viên chấm bài thi có cùng mức độ biến thiên trong cách chấm điểm của họ. Để một chiếc nắp vừa khít với hộp, độ biến thiên của nắp và hộp phải giống nhau. Một siêu thị có thể quan tâm đến độ biến thiên thời gian thanh toán của hai nhân viên thu ngân.

Để thực hiện kiểm định *F* cho hai phương sai, điều quan trọng là các điều kiện sau phải đúng:

1. Các quần thể mà từ đó hai mẫu được rút ra có phân phối chuẩn.
1. Hai quần thể độc lập với nhau.
Không giống như hầu hết các kiểm định khác trong cuốn sách này, kiểm định *F* về sự bằng nhau của hai phương sai rất nhạy cảm với các sai lệch so với phân phối chuẩn. Nếu hai phân phối không phải là phân phối chuẩn, kiểm định có thể đưa ra các p-giá trị *p* cao hơn hoặc thấp hơn mức cần thiết theo những cách không thể dự đoán trước. Nhiều tài liệu khuyên sinh viên không nên sử dụng kiểm định này, nhưng vì mục đích hoàn thiện, chúng tôi đưa nó vào đây.

Giả sử chúng ta lấy mẫu ngẫu nhiên từ hai quần thể độc lập có phân phối chuẩn. Gọi 

σ
1
2

σ
1
2

 và 

σ
2
2

σ
2
2

 là các phương sai quần thể, và 

s
1
2

s
1
2

 và 

s
2
2

s
2
2

 là các phương sai mẫu. Gọi kích thước mẫu là *n*_1 và *n*_2. Vì chúng ta quan tâm đến việc so sánh hai phương sai mẫu, chúng ta sử dụng tỷ số *F*:

F=

[ 

(
s
1

)

2

(
σ
1

)

2

 ]

[ 

(
s
2

)

2

(
σ
2

)

2

 ]

F=

[ 

(
s
1

)

2

(
σ
1

)

2

 ]

[ 

(
s
2

)

2

(
σ
2

)

2

 ]

*F* có phân phối *F* ~ *F*(*n*_1 – 1, *n*_2 – 1)

trong đó *n*_1 – 1 là bậc tự do cho tử số và *n*_2 – 1 là bậc tự do cho mẫu số.

Nếu giả thuyết không là 

σ
1
2

=
σ
2
2

σ
1
2

=
σ
2
2

, thì Tỷ số *F* trở thành 

F=

[ 

(
s
1

)

2

(
σ
1

)

2

 ]

[ 

(
s
2

)

2

(
σ
2

)

2

 ]

=

(
s
1

)

2

(
s
2

)

2

F=

[ 

(
s
1

)

2

(
σ
1

)

2

 ]

[ 

(
s
2

)

2

(
σ
2

)

2

 ]

=

(
s
1

)

2

(
s
2

)

2

.

Tỷ số *F* cũng có thể là 

(
s
2

)

2

(
s
1

)

2

(
s
2

)

2

(
s
1

)

2

.

 Điều này phụ thuộc vào *H_a* và vào việc phương sai mẫu nào lớn hơn.

Nếu hai quần thể có phương sai bằng nhau, thì 

s
1
2

s
1
2

 và 

s
2
2

s
2
2

 có giá trị gần nhau và 

F=

(
s
1

)

2

(
s
2

)

2

F=

(
s
1

)

2

(
s
2

)

2

 gần bằng một. Nhưng nếu hai phương sai quần thể rất khác nhau, 

s
1
2

s
1
2

 và 

s
2
2

s
2
2

 cũng có xu hướng rất khác nhau. Việc chọn 

s
1
2

s
1
2

 là phương sai mẫu lớn hơn sẽ làm cho tỷ số 

(
s
1

)

2

(
s
2

)

2

(
s
1

)

2

(
s
2

)

2

 lớn hơn một. Nếu 

s
1
2

s
1
2

 và 

s
2
2

s
2
2

 cách xa nhau, thì 

F=

(
s
1

)

2

(
s
2

)

2

F=

(
s
1

)

2

(
s
2

)

2

 là một số lớn.

Do đó, nếu *F* gần bằng một, bằng chứng ủng hộ giả thuyết không (hai phương sai quần thể bằng nhau). Nhưng nếu *F* lớn hơn nhiều so với một, thì bằng chứng chống lại giả thuyết không. **Kiểm định hai phương sai có thể là kiểm định phía trái, phía phải hoặc hai phía.**

#### Bài tập

Hai giảng viên đại học quan tâm đến việc liệu có bất kỳ sự biến thiên nào trong cách họ chấm bài thi toán hay không. Mỗi người chấm cùng một bộ 30 bài thi. Điểm của giảng viên thứ nhất có phương sai là 52,3. Điểm của giảng viên thứ hai có phương sai là 89,9. Hãy kiểm định khẳng định rằng phương sai của giảng viên thứ nhất nhỏ hơn. (Ở hầu hết các trường đại học, phương sai điểm thi giữa các giảng viên nên gần như bằng nhau). Mức ý nghĩa là 10%.

Hiệp hội Hợp xướng New York chia các ca sĩ nam thành bốn loại từ giọng cao nhất đến thấp nhất: Tenor1, Tenor2, Bass1, Bass2. Trong bảng là chiều cao của các nam ca sĩ trong nhóm Tenor1 và Bass2. Người ta nghi ngờ rằng những người đàn ông cao hơn sẽ có giọng trầm hơn, và phương sai chiều cao cũng có thể tăng lên cùng với các giọng trầm hơn. Chúng ta có bằng chứng tốt cho thấy phương sai chiều cao của các ca sĩ trong mỗi nhóm này (Tenor1 và Bass2) là khác nhau không?

| Tenor1 | Bass2 | Tenor 1 | Bass 2 | Tenor 1 | Bass 2 |
| --- | --- | --- | --- | --- | --- |
| 69 | 72 | 67 | 72 | 68 | 67 |
| 72 | 75 | 70 | 74 | 67 | 70 |
| 71 | 67 | 65 | 70 | 64 | 70 |
| 66 | 75 | 72 | 66 |  | 69 |
| 76 | 74 | 70 | 68 |  | 72 |
| 74 | 72 | 68 | 75 |  | 71 |
| 71 | 72 | 64 | 68 |  | 74 |
| 66 | 74 | 73 | 70 |  | 75 |
| 68 | 72 | 66 | 72 |  |  |
