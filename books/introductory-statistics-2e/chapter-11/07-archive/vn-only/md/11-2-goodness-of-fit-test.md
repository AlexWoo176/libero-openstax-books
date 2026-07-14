## 11.2
 
Kiểm định mức độ phù hợp

Trong loại kiểm định giả thuyết này, bạn xác định xem dữ liệu có **"phù hợp"** với một phân phối cụ thể nào đó hay không. Ví dụ, bạn có thể nghi ngờ rằng dữ liệu chưa biết của mình phù hợp với phân phối nhị thức. Bạn sử dụng kiểm định khi bình phương (nghĩa là phân phối cho kiểm định giả thuyết là phân phối khi bình phương) để xác định xem có sự phù hợp hay không. **Giả thuyết không và đối thuyết cho kiểm định này có thể được viết thành câu hoặc được trình bày dưới dạng phương trình hoặc bất đẳng thức.**

Thống kê kiểm định cho kiểm định mức độ phù hợp là:

trong đó:

- *O* = các giá trị quan sát (dữ liệu)
- *E* = các giá trị kỳ vọng (từ lý thuyết)
- *k* = số lượng các ô dữ liệu hoặc danh mục khác nhau
**Các giá trị quan sát là các giá trị dữ liệu và các giá trị kỳ vọng là các giá trị bạn mong đợi nhận được nếu giả thuyết không là đúng.** Có *n* số hạng dưới dạng 

(O−E)

2

E

(O−E)

2

E

.

Số bậc tự do là *df* = (số lượng danh mục – 1).

**Kiểm định mức độ phù hợp hầu như luôn là kiểm định phía bên phải.** Nếu các giá trị quan sát và các giá trị kỳ vọng tương ứng không gần nhau, thì thống kê kiểm định có thể trở nên rất lớn và sẽ nằm xa về phía đuôi bên phải của đường cong khi bình phương.

Giá trị kỳ vọng cho mỗi ô cần phải đạt ít nhất là năm để bạn có thể sử dụng kiểm định này.

Việc sinh viên đại học nghỉ học các lớp toán là một mối quan tâm lớn đối với các giảng viên toán vì việc vắng mặt có vẻ làm tăng tỷ lệ bỏ học. Giả sử một nghiên cứu đã được thực hiện để xác định xem tỷ lệ vắng mặt thực tế của sinh viên có tuân theo nhận định của giảng viên hay không. Giảng viên kỳ vọng rằng một nhóm 100 sinh viên sẽ nghỉ học theo [Bảng 11.1](11-2-goodness-of-fit-test#M03_Ch03_tbl001).

| Số ngày vắng mặt mỗi học kỳ | Số lượng sinh viên kỳ vọng |
| --- | --- |
| 0–2 | 50 |
| 3–5 | 30 |
| 6–8 | 12 |
| 9–11 | 6 |
| 12+ | 2 |

Một cuộc khảo sát ngẫu nhiên trên tất cả các khóa học toán sau đó đã được thực hiện để xác định số lượng thực tế **(quan sát)** các buổi vắng mặt trong một khóa học. Biểu đồ trong [Bảng 11.2](11-2-goodness-of-fit-test#M03_Ch03_tbl002) hiển thị kết quả của cuộc khảo sát đó.

| Số ngày vắng mặt mỗi học kỳ | Số lượng sinh viên thực tế |
| --- | --- |
| 0–2 | 35 |
| 3–5 | 40 |
| 6–8 | 20 |
| 9–11 | 1 |
| 12+ | 4 |

Xác định giả thuyết không và đối thuyết cần thiết để thực hiện kiểm định mức độ phù hợp.

***H_0*:** Việc vắng mặt của sinh viên **phù hợp với** nhận định của giảng viên.

Đối thuyết là ngược lại với giả thuyết không.

***H_a*:** Việc vắng mặt của sinh viên **không phù hợp với** nhận định của giảng viên.

#### Bài tập

a. Bạn có thể sử dụng thông tin như xuất hiện trong các biểu đồ để thực hiện kiểm định mức độ phù hợp không?

#### Bài tập

b. Số bậc tự do (*df*) là bao nhiêu?

Một quản lý nhà máy cần hiểu có bao nhiêu sản phẩm bị lỗi so với bao nhiêu sản phẩm được sản xuất. Số lượng lỗi kỳ vọng được liệt kê trong [Bảng 11.5](11-2-goodness-of-fit-test#M03_Ch03_tbl005).

| Số lượng sản xuất | Số lượng lỗi |
| --- | --- |
| 0–100 | 5 |
| 101–200 | 6 |
| 201–300 | 7 |
| 301–400 | 8 |
| 401–500 | 10 |

Một mẫu ngẫu nhiên đã được lấy để xác định số lượng lỗi thực tế. [Bảng 11.6](11-2-goodness-of-fit-test#M03_Ch03_tbl006) hiển thị kết quả của cuộc khảo sát.

| Số lượng sản xuất | Số lượng lỗi |
| --- | --- |
| 0–100 | 5 |
| 101–200 | 7 |
| 201–300 | 8 |
| 301–400 | 9 |
| 401–500 | 11 |

Phát biểu giả thuyết không và đối thuyết cần thiết để thực hiện kiểm định mức độ phù hợp, và nêu số bậc tự do.

#### Bài tập

Các nhà tuyển dụng muốn biết nhân viên thường vắng mặt vào những ngày nào trong tuần làm việc năm ngày. Hầu hết các nhà tuyển dụng đều muốn tin rằng nhân viên vắng mặt đều đặn trong suốt cả tuần. Giả sử một mẫu ngẫu nhiên gồm 60 quản lý được hỏi vào ngày nào trong tuần họ có số lượng nhân viên vắng mặt cao nhất. Các kết quả được phân phối như trong [Bảng 11.7](11-2-goodness-of-fit-test#M03_Ch03_tbl007). Đối với quần thể nhân viên, liệu các ngày có số lượng vắng mặt cao nhất có xảy ra với tần suất bằng nhau trong một tuần làm việc năm ngày không? Hãy kiểm định ở mức ý nghĩa 5%.

|  | Thứ Hai | Thứ Ba | Thứ Tư | Thứ Năm | Thứ Sáu |
| --- | --- | --- | --- | --- | --- |
| Số ngày nghỉ học | 15 | 12 | 9 | 9 | 15 |

Giáo viên muốn biết mỗi tuần học sinh của họ làm bài tập về nhà nhiều nhất vào đêm nào. Hầu hết giáo viên nghĩ rằng học sinh làm bài tập về nhà đều đặn trong suốt cả tuần. Giả sử một mẫu ngẫu nhiên gồm 56 học sinh được hỏi vào đêm nào trong tuần họ làm bài tập về nhà nhiều nhất. Kết quả được phân phối như trong [Bảng 11.8](11-2-goodness-of-fit-test#M03_Ch03_tbl008).

|  | Chủ Nhật | Thứ Hai | Thứ Ba | Thứ Tư | Thứ Năm | Thứ Sáu | Thứ Bảy |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Số lượng sinh viên | 11 | 8 | 10 | 7 | 10 | 5 | 5 |

Từ quần thể học sinh, liệu các đêm có số lượng học sinh làm phần lớn bài tập về nhà cao nhất có xảy ra với tần suất bằng nhau trong một tuần không? Bạn nên sử dụng loại kiểm định giả thuyết nào?

Một nghiên cứu chỉ ra rằng số lượng dịch vụ phát trực tuyến mà các gia đình Mỹ có được phân phối (đây là phân phối **đã cho** đối với quần thể người Mỹ) như trong [Bảng 11.9](11-2-goodness-of-fit-test#M03_Ch03_tbl009).

| Số lượng dịch vụ phát trực tuyến | Phần trăm |
| --- | --- |
| 0 | 10 |
| 1 | 16 |
| 2 | 55 |
| 3 | 11 |
| 4+ | 8 |

Bảng chứa các phần trăm kỳ vọng (*E*).

Một mẫu ngẫu nhiên gồm 600 gia đình ở vùng viễn tây Hoa Kỳ đã dẫn đến dữ liệu trong [Bảng 11.10](11-2-goodness-of-fit-test#M03_Ch03_tbl010).

| Số lượng dịch vụ phát trực tuyến | Tần số |
| --- | --- |
| 0 | 66 |
| 1 | 119 |
| 2 | 340 |
| 3 | 60 |
| 4+ | 15 |
|  | Tổng = 600 |

Bảng chứa các giá trị tần số quan sát (*O*).

#### Bài tập

Tại mức ý nghĩa 1%, liệu có vẻ như phân phối "số lượng dịch vụ phát trực tuyến" của các gia đình ở vùng viễn tây Hoa Kỳ khác với phân phối của toàn bộ quần thể người Mỹ không?

Phần trăm kỳ vọng về số lượng thú cưng mà học sinh có trong nhà được phân phối (đây là phân phối đã cho đối với quần thể học sinh Hoa Kỳ) như trong [Bảng 11.12](11-2-goodness-of-fit-test#fs-idm147763264).

| Số lượng thú cưng | Phần trăm |
| --- | --- |
| 0 | 18 |
| 1 | 25 |
| 2 | 30 |
| 3 | 18 |
| 4+ | 9 |

Một mẫu ngẫu nhiên gồm 1,000 học sinh từ miền Đông Hoa Kỳ đã dẫn đến dữ liệu trong [Bảng 11.13](11-2-goodness-of-fit-test#fs-idm64242624).

| Số lượng thú cưng | Tần số |
| --- | --- |
| 0 | 210 |
| 1 | 240 |
| 2 | 320 |
| 3 | 140 |
| 4+ | 90 |

Tại mức ý nghĩa 1%, liệu có vẻ như phân phối “số lượng thú cưng” của học sinh ở miền Đông Hoa Kỳ khác với phân phối của toàn bộ quần thể học sinh Hoa Kỳ không? p-giá trị *p* là bao nhiêu?

#### Bài tập

Giả sử bạn tung hai đồng xu 100 lần. Kết quả là 20 *HH*, 27 *HT*, 30 *TH* và 23 *TT*. Các đồng xu có cân đối không? Kiểm định ở mức ý nghĩa 5%.

Các sinh viên trong một lớp học nghiên cứu xã hội đưa ra giả thuyết rằng tỷ lệ biết chữ trên toàn thế giới cho mọi khu vực là 82%. [Bảng 11.14](11-2-goodness-of-fit-test#fs-idm84960960) hiển thị tỷ lệ biết chữ thực tế trên toàn thế giới được phân tách theo khu vực. Thống kê kiểm định và bậc tự do là bao nhiêu?

| Khu vực MDG | Tỷ lệ biết chữ ở người lớn (%) |
| --- | --- |
| Các khu vực phát triển | 99,0 |
| Cộng đồng các quốc gia độc lập | 99,5 |
| Bắc Phi | 67,3 |
| Châu Phi cận Sahara | 62,5 |
| Mỹ Latinh và vùng Caribe | 91,0 |
| Đông Á | 93,8 |
| Nam Á | 61,9 |
| Đông Nam Á | 91,9 |
| Tây Á | 84,5 |
| Châu Đại Dương | 66,4 |
