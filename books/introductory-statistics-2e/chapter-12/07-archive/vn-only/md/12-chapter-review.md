## Ôn tập chương

Loại liên kết cơ bản nhất là liên kết tuyến tính. Loại mối quan hệ này có thể được xác định theo đại số bằng các phương trình được sử dụng, theo số liệu với các giá trị dữ liệu thực tế hoặc dự đoán, hoặc theo đồ thị từ một đường cong được vẽ. (Các đường thẳng được phân loại là các đường cong thẳng.) Về mặt đại số, một phương trình tuyến tính thường có dạng ***y = mx + b***, trong đó ***m*** và ***b*** là các hằng số, ***x*** là biến độc lập, ***y*** là biến phụ thuộc. Trong bối cảnh thống kê, một phương trình tuyến tính được viết dưới dạng ***y = a + bx***, trong đó ***a*** và ***b*** là các hằng số. Dạng này được sử dụng để giúp người đọc phân biệt bối cảnh thống kê với bối cảnh đại số. Trong phương trình *y = a + bx*, hằng số *b*, được gọi là hệ số, đại diện cho **độ dốc**. Hằng số a được gọi là điểm cắt *y*.

**Độ dốc của một đường thẳng** là một giá trị mô tả tốc độ thay đổi giữa biến độc lập và biến phụ thuộc. **Độ dốc** cho chúng ta biết biến phụ thuộc (*y*) thay đổi như thế nào cho mỗi đơn vị tăng lên của biến độc lập (*x*), tính trung bình. **Điểm cắt *y*** được sử dụng để mô tả biến phụ thuộc khi biến độc lập bằng không.

Biểu đồ phân tán là những đồ thị đặc biệt hữu ích khi chúng ta muốn xem liệu có mối quan hệ tuyến tính giữa các điểm dữ liệu hay không. Chúng chỉ ra cả hướng của mối quan hệ giữa các biến *x* và các biến *y*, cũng như độ mạnh của mối quan hệ đó. Chúng ta tính toán độ mạnh của mối quan hệ giữa một biến độc lập và một biến phụ thuộc bằng cách sử dụng hồi quy tuyến tính.

Một đường hồi quy, hay đường phù hợp nhất, có thể được vẽ trên biểu đồ phân tán và được sử dụng để dự đoán kết quả cho các biến *x* và *y* trong một tập dữ liệu hoặc dữ liệu mẫu nhất định. Có một vài cách để tìm đường hồi quy, nhưng thông thường đường hồi quy bình phương tối thiểu được sử dụng vì nó tạo ra một đường đồng nhất. Phần dư, còn được gọi là “sai số”, đo lường khoảng cách từ giá trị thực tế của *y* và giá trị ước tính của *y*. Tổng bình phương sai số, khi được đặt ở mức tối thiểu, sẽ tính toán các điểm trên đường phù hợp nhất. Các đường hồi quy có thể được sử dụng để dự đoán các giá trị trong tập dữ liệu đã cho, nhưng không nên được sử dụng để đưa ra dự đoán cho các giá trị nằm ngoài tập dữ liệu đó.

Hệ số tương quan *r* đo lường độ mạnh của liên kết tuyến tính giữa *x* và *y*. Biến *r* phải nằm trong khoảng từ –1 đến +1. Khi *r* dương, *x* và *y* sẽ có xu hướng cùng tăng hoặc cùng giảm. Khi *r* âm, *x* sẽ tăng và *y* sẽ giảm, hoặc ngược lại, *x* sẽ giảm và *y* sẽ tăng. Hệ số xác định *r*^2 bằng bình phương của hệ số tương quan. Khi được biểu thị dưới dạng phần trăm, *r*^2 đại diện cho phần trăm biến thiên trong biến phụ thuộc *y* có thể được giải thích bởi sự biến thiên trong biến độc lập *x* bằng cách sử dụng đường hồi quy.

Hồi quy tuyến tính là một quy trình để khớp một đường thẳng có dạng *ŷ* = *a* + *bx* vào dữ liệu. Các điều kiện cho hồi quy là:

- **Tuyến tính** Trong quần thể, có một mối quan hệ tuyến tính mô hình hóa giá trị trung bình của *y* cho các giá trị khác nhau của *x*.
- **Độc lập** Các phần dư được giả định là độc lập.
- **Chuẩn** Các giá trị *y* được phân phối chuẩn cho bất kỳ giá trị nào của *x*.
- **Phương sai bằng nhau** Độ lệch chuẩn của các giá trị *y* là bằng nhau cho mỗi giá trị *x*.
- **Ngẫu nhiên** Dữ liệu được tạo ra từ một mẫu ngẫu nhiên hoặc thực nghiệm ngẫu nhiên được thiết kế tốt.
Độ dốc ***b*** và điểm cắt ***a*** của đường bình phương tối thiểu ước tính độ dốc *β* và điểm cắt *α* của đường hồi quy quần thể (thực). Để ước tính độ lệch chuẩn quần thể của *y*, *σ*, hãy sử dụng độ lệch chuẩn của phần dư, *s*. 

s=

SEE

n−2

s=

SEE

n−2

. Biến *ρ* (rho) là hệ số tương quan quần thể. Để kiểm định giả thuyết không *H*_0: *ρ* = *giá trị giả định*, hãy sử dụng kiểm định t hồi quy tuyến tính. Giả thuyết không phổ biến nhất là *H*_0: *ρ* = 0, cho thấy không có mối quan hệ tuyến tính giữa *x* và *y* trong quần thể. Chức năng máy tính TI-83, 83+, 84, 84+ LinRegTTest có thể thực hiện kiểm định này (STATS TESTS LinRegTTest).

Sau khi xác định sự hiện diện của một hệ số tương quan mạnh và tính toán đường phù hợp nhất, bạn có thể sử dụng đường hồi quy bình phương tối thiểu để đưa ra các dự đoán về dữ liệu của mình.

Để xác định xem một điểm có phải là giá trị ngoại lệ hay không, hãy thực hiện một trong các cách sau:

1. Input the following equations into the TI 83, 83+,84, 84+:
        

y
1

=a+bx

y
2

=a+bx+2s

y
3

=a+bx−2s

y
1

=a+bx

y
2

=a+bx+2s

y
3

=a+bx−2s

 trong đó s là độ lệch chuẩn của phần dưNếu bất kỳ điểm nào nằm trên y_2 hoặc dưới y_3 thì điểm đó được coi là một giá trị ngoại lệ.
1. Sử dụng các phần dư và so sánh giá trị tuyệt đối của chúng với 2*s* trong đó *s* là độ lệch chuẩn của phần dư. Nếu giá trị tuyệt đối của bất kỳ phần dư nào lớn hơn hoặc bằng 2*s*, thì điểm tương ứng là một giá trị ngoại lệ.
1. Lưu ý: Chức năng máy tính LinRegTTest (STATS TESTS LinRegTTest) tính toán *s*.
