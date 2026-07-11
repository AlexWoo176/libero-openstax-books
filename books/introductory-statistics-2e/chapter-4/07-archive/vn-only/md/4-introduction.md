*Hình 
4.1
 
Bạn có thể sử dụng xác suất và biến ngẫu nhiên rời rạc để tính toán khả năng sét đánh xuống mặt đất năm lần trong một trận giông bão kéo dài nửa giờ. (nguồn: chỉnh sửa từ tác phẩm “CG lightning strike” của Axel Rouvin/ Flickr, CC BY 2.0)*

Đến cuối chương này, sinh viên sẽ có thể:

- Nhận biết và hiểu các hàm phân phối xác suất rời rạc nói chung.
- Tính toán và diễn giải các giá trị kỳ vọng.
- Nhận biết phân phối xác suất nhị thức và áp dụng nó một cách phù hợp.
- Nhận biết phân phối xác suất Poisson và áp dụng nó một cách phù hợp.
- Nhận diện phân phối hình học và áp dụng nó một cách thích hợp.
- Nhận diện phân phối xác suất siêu bội và áp dụng nó một cách thích hợp.
- Phân loại các bài toán đố rời rạc theo phân phối của chúng.
## Giới thiệu

Một sinh viên làm một bài kiểm tra trắc nghiệm đúng-sai gồm mười câu hỏi. Vì lịch trình quá bận rộn, sinh viên đó không thể học bài và đoán ngẫu nhiên mỗi câu trả lời. Xác suất để sinh viên đó vượt qua bài kiểm tra với ít nhất 70% là bao nhiêu?

Người quản lý một đại lý ô tô có thể quan tâm đến sở thích màu sắc của những người mua xe mới. Giả sử trung bình đại lý bán được 20 chiếc xe mỗi tháng. Xác suất để một khách hàng thích xe màu đỏ là bao nhiêu?

Hai ví dụ này minh họa hai loại bài toán xác suất khác nhau liên quan đến các biến ngẫu nhiên rời rạc. Hãy nhớ rằng dữ liệu rời rạc là dữ liệu mà bạn có thể đếm được. Một Biến ngẫu nhiên mô tả các kết quả của một phép thử thống kê bằng lời. Các giá trị của một biến ngẫu nhiên có thể thay đổi theo mỗi lần lặp lại phép thử.

### Ký hiệu biến ngẫu nhiên

Các chữ cái in hoa như *X* hoặc *Y* biểu thị một biến ngẫu nhiên. Các chữ cái thường như *x* hoặc *y* biểu thị giá trị của một biến ngẫu nhiên. Nếu ***X* là một biến ngẫu nhiên, thì *X* được viết bằng lời, và *x* được đưa ra dưới dạng một con số.**

Ví dụ, gọi X = số mặt ngửa bạn nhận được khi tung ba đồng xu cân đối. Không gian mẫu cho việc tung ba đồng xu cân đối là TTT; THH; HTH; HHT; HTT; THT; TTH; HHH. Khi đó, x = 0, 1, 2, 3. X được viết bằng lời và x là một con số. Lưu ý rằng đối với ví dụ này, các giá trị x là các kết quả có thể đếm được. Vì bạn có thể đếm các giá trị khả dĩ mà X có thể nhận và các kết quả là ngẫu nhiên (các giá trị x là 0, 1, 2, 3), nên X là một biến ngẫu nhiên rời rạc.

Tung một đồng xu mười lần và ghi lại số mặt ngửa. Sau khi tất cả các thành viên trong lớp đã hoàn thành phép thử (tung một đồng xu mười lần và đếm số mặt ngửa), hãy điền vào [Bảng 4.1](4-introduction#M01_Ch04_tbl001). Gọi *X* = số mặt ngửa trong mười lần tung đồng xu.

| ***x*** | **Tần số của *x*** | **Tần suất tương đối của *x*** |
| --- | --- | --- |
|  |  |  |
|  |  |  |
|  |  |  |
|  |  |  |
|  |  |  |
|  |  |  |

1. (Các) giá trị nào của *x* xuất hiện với tần số cao nhất?
1. Nếu bạn tung đồng xu 1.000 lần, *x* có thể nhận những giá trị nào? Bạn nghĩ (các) giá trị nào của *x* sẽ xuất hiện với tần số cao nhất?
1. Tổng của cột tần suất tương đối bằng bao nhiêu?
