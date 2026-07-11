## 9.3
 
Phân phối xác suất cần thiết cho Kiểm định giả thuyết

Trước đó trong khóa học, chúng ta đã thảo luận về phân phối mẫu. Các phân phối cụ thể được liên kết với các loại kiểm định giả thuyết khác nhau.

Bảng sau đây tóm tắt các kiểm định giả thuyết khác nhau và các phân phối xác suất tương ứng sẽ được sử dụng để thực hiện kiểm định (dựa trên các giả định được trình bày dưới đây):

| Loại Kiểm định giả thuyết | Tham số tổng thể | Giá trị ước lượng (ước lượng điểm) | Phân phối xác suất được sử dụng |
| --- | --- | --- | --- |
| Kiểm định giả thuyết cho trung bình, khi độ lệch chuẩn tổng thể đã biết | Trung bình tổng thể μμ | Trung bình mẫu x¯x¯ | Phân phối chuẩn, 
  X¯~N(μX,σXn)X¯~N(μX,σXn) |
| Kiểm định giả thuyết cho trung bình, khi độ lệch chuẩn tổng thể chưa biết và phân phối của trung bình mẫu xấp xỉ chuẩn | Trung bình tổng thể μμ | Trung bình mẫu x¯x¯ | Phân phối Student (phân phối t), tdftdf |
| Kiểm định giả thuyết cho tỷ lệ | Tỷ lệ tổng thể pp | Tỷ lệ mẫu p'p' | Phân phối chuẩn,
  P'~N(p,p·qn)P'~N(p,p·qn) |

### Giả định

Khi bạn thực hiện một kiểm định giả thuyết về một trung bình tổng thể duy nhất *μ* sử dụng phân phối chuẩn (thường được gọi là kiểm định z), bạn lấy một mẫu ngẫu nhiên đơn giản từ tổng thể. Tổng thể bạn đang kiểm định là có phân phối chuẩn, hoặc kích thước mẫu của bạn đủ lớn. Bạn biết giá trị của độ lệch chuẩn tổng thể, mà trên thực tế, hiếm khi được biết.

Khi bạn thực hiện kiểm định giả thuyết về một trung bình tổng thể duy nhất *μ* sử dụng Phân phối Student (phân phối t) (thường được gọi là kiểm định *t*), có những giả định cơ bản cần được đáp ứng để kiểm định hoạt động đúng cách. Dữ liệu của bạn phải là một mẫu ngẫu nhiên đơn giản đến từ một tổng thể có phân phối xấp xỉ chuẩn. Bạn sử dụng độ lệch chuẩn mẫu để xấp xỉ độ lệch chuẩn tổng thể. (Lưu ý rằng nếu kích thước mẫu đủ lớn, kiểm định *t* sẽ hoạt động ngay cả khi tổng thể không có phân phối xấp xỉ chuẩn).

Khi bạn thực hiện kiểm định giả thuyết về một tỷ lệ tổng thể duy nhất *p*, bạn lấy một mẫu ngẫu nhiên đơn giản từ tổng thể. Bạn phải đáp ứng các điều kiện cho một phân phối nhị thức: có một số lượng *n* phép thử độc lập nhất định, kết quả của bất kỳ phép thử nào là thành công hoặc thất bại, và mỗi phép thử có cùng xác suất thành công *p*. Hình dạng của phân phối nhị thức cần phải tương tự như hình dạng của phân phối chuẩn. Để đảm bảo điều này, các đại lượng *np* và *nq* phải lớn hơn năm (np>5 np>5  và nq>5 nq>5 ). Khi đó, phân phối nhị thức của một tỷ lệ mẫu (ước lượng) có thể được xấp xỉ bằng phân phối chuẩn với μ=p μ=p  và σ=pqnσ=pqn. Hãy nhớ rằng q=1-pq=1-p.
