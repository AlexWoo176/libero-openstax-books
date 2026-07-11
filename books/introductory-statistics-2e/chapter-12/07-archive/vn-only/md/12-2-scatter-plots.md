## 12.2
 
Biểu đồ phân tán

Trước khi chúng ta thảo luận về hồi quy tuyến tính và tương quan, chúng ta cần xem xét một cách để hiển thị mối quan hệ giữa hai biến *x* và *y*. Cách phổ biến và dễ dàng nhất là **biểu đồ phân tán**. Ví dụ sau đây minh họa một biểu đồ phân tán.

Một nhà nghiên cứu giáo dục thu thập dữ liệu về vốn từ vựng của trẻ em theo độ tuổi. Dữ liệu được hiển thị trong Bảng 12.1. Có mối quan hệ nào giữa độ tuổi và vốn từ vựng ở trẻ nhỏ không? Hãy xây dựng một biểu đồ phân tán. Cho *x* = Độ tuổi của trẻ, và cho *y* = Vốn từ vựng.

| Độ tuổi (năm) | Vốn từ vựng (số lượng từ) |
| --- | --- |
| 3 | 655 |
| 4 | 1098 |
| 6 | 2463 |
| 7 | 3195 |

*Hình 
12.5*

1. Nhập dữ liệu X của bạn vào danh sách L1 và dữ liệu Y của bạn vào danh sách L2.
1. Nhấn 2nd `STATPLOT ENTER` để sử dụng Plot 1. Trên màn hình nhập liệu cho PLOT 1, hãy làm nổi bật On và nhấn `ENTER`. (Đảm bảo các biểu đồ khác đang ở chế độ OFF.)
1. Đối với TYPE: hãy làm nổi bật biểu tượng đầu tiên, đó là biểu đồ phân tán, và nhấn `ENTER`.
1. Đối với Xlist:, nhập `L1` ENTER và đối với Ylist: `L2` ENTER.
1. Đối với Mark: không quan trọng bạn làm nổi bật biểu tượng nào, nhưng hình vuông là dễ nhìn nhất. Nhấn `ENTER`.
1. Đảm bảo không có phương trình nào khác có thể được vẽ. Nhấn Y = và xóa sạch mọi phương trình.
1. Nhấn phím `ZOOM` và sau đó là số 9 (cho mục menu "ZoomStat"); máy tính sẽ điều chỉnh cửa sổ cho phù hợp với dữ liệu. Bạn có thể nhấn WINDOW để xem tỷ lệ của các trục.
Amelia chơi bóng rổ cho trường trung học của cô ấy. Cô ấy muốn cải thiện kỹ năng để chơi ở cấp đại học. Cô ấy nhận thấy rằng số điểm cô ghi được trong một trận đấu tăng lên tương ứng với số giờ cô luyện tập cú ném nhảy mỗi tuần. Cô ấy ghi lại dữ liệu sau:

| *X* (giờ luyện tập cú ném nhảy) | *Y* (số điểm ghi được trong một trận đấu) |
| --- | --- |
| 5 | 15 |
| 7 | 22 |
| 9 | 28 |
| 10 | 31 |
| 11 | 33 |
| 12 | 36 |

Hãy xây dựng một biểu đồ phân tán và cho biết liệu những gì Amelia nghĩ có vẻ đúng hay không.

Biểu đồ phân tán cho thấy **hướng** của mối quan hệ giữa các biến. Một hướng rõ ràng xảy ra khi có một trong hai trường hợp sau:

- Các giá trị cao của một biến xảy ra cùng với các giá trị cao của biến kia hoặc các giá trị thấp của một biến xảy ra cùng với các giá trị thấp của biến kia.
- Các giá trị cao của một biến xảy ra cùng với các giá trị thấp của biến kia.
Bạn có thể xác định **độ mạnh** của mối quan hệ bằng cách nhìn vào biểu đồ phân tán và xem các điểm gần với một đường thẳng, một hàm lũy thừa, một hàm mũ, hoặc một loại hàm số nào khác như thế nào. Đối với mối quan hệ tuyến tính, có một ngoại lệ. Hãy xem xét một biểu đồ phân tán nơi tất cả các điểm nằm trên một đường nằm ngang, tạo ra một "sự khớp hoàn hảo". Đường nằm ngang thực tế sẽ cho thấy không có mối quan hệ nào.

Khi bạn nhìn vào một biểu đồ phân tán, bạn nên chú ý đến **mô hình tổng thể** và bất kỳ **độ lệch** nào so với mô hình đó. Các ví dụ về biểu đồ phân tán sau đây minh họa các khái niệm này.

*Hình 
12.6*

*Hình 
12.7*

*Hình 
12.8*

Trong chương này, chúng ta quan tâm đến các biểu đồ phân tán cho thấy mô hình tuyến tính. Các mô hình tuyến tính khá phổ biến. Mối quan hệ tuyến tính là mạnh nếu các điểm gần với một đường thẳng, ngoại trừ trường hợp đường nằm ngang nơi không có mối quan hệ nào. Nếu chúng ta nghĩ rằng các điểm cho thấy một mối quan hệ tuyến tính, chúng ta muốn vẽ một đường thẳng trên biểu đồ phân tán. Đường thẳng này có thể được tính toán thông qua một quy trình gọi là hồi quy tuyến tính. Tuy nhiên, chúng ta chỉ tính toán đường hồi quy nếu một trong các biến giúp giải thích hoặc dự đoán biến kia. Nếu *x* là biến độc lập và *y* là biến phụ thuộc, thì chúng ta có thể sử dụng đường hồi quy để dự đoán *y* cho một giá trị cho trước của *x*.
