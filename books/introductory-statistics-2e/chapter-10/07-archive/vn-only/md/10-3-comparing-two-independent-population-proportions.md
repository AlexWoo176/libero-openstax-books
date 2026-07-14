## 10.3
 
So sánh hai tỷ lệ quần thể độc lập

Khi thực hiện kiểm định giả thuyết so sánh hai tỷ lệ quần thể độc lập, các đặc điểm sau đây cần phải có:

1. Hai mẫu độc lập là các mẫu ngẫu nhiên đơn giản và độc lập với nhau.
1. Số lượng thành công ít nhất là năm, và số lượng thất bại ít nhất là năm, cho mỗi mẫu.
1. Các tài liệu nghiên cứu ngày càng khẳng định rằng quần thể phải lớn gấp ít nhất mười hoặc 20 lần kích thước mẫu. Điều này giúp ngăn chặn việc lấy mẫu quá mức từ mỗi quần thể và gây ra kết quả không chính xác.
Việc so sánh hai tỷ lệ, cũng giống như so sánh hai số trung bình, là điều phổ biến. Nếu hai tỷ lệ ước lượng khác nhau, điều đó có thể là do sự khác biệt trong các quần thể hoặc do ngẫu nhiên. Kiểm định giả thuyết có thể giúp xác định liệu sự khác biệt trong các tỷ lệ ước lượng có phản ánh sự khác biệt trong các tỷ lệ quần thể hay không.

Giống như trường hợp sự khác biệt giữa các số trung bình mẫu, chúng ta xây dựng một phân phối mẫu cho sự khác biệt giữa các tỷ lệ mẫu:

p'A=XAnAp'A=XAnA và p'B=XBnBp'B=XBnB là các tỷ lệ mẫu cho hai tập dữ liệu đang xét XAXA và XBXB.

Sự khác biệt của hai tỷ lệ tuân theo một phân phối chuẩn xấp xỉ. Thông thường, giả thuyết không phát biểu rằng hai tỷ lệ là như nhau. Nghĩa là, *H_0*: *p_A* = *p_B*. Để thực hiện kiểm định, chúng ta sử dụng tỷ lệ gộp chung, *p_c*.

#### Bài tập

Hai loại thuốc trị mề đay đang được thử nghiệm để xác định xem có **sự khác biệt về tỷ lệ phản ứng của bệnh nhân trưởng thành hay không. Hai mươi** người trong một **mẫu ngẫu nhiên gồm 200** người trưởng thành được dùng thuốc A vẫn còn bị mề đay 30 phút sau khi uống thuốc. **Mười hai** người trong một **mẫu ngẫu nhiên khác gồm 200 người trưởng thành** được dùng thuốc B vẫn còn bị mề đay 30 phút sau khi uống thuốc. Hãy kiểm định ở mức ý nghĩa 1%.

Hai loại van đang được thử nghiệm để xác định xem có sự khác biệt về dung sai áp suất hay không. Mười lăm trong một mẫu ngẫu nhiên gồm 100 van loại *A* bị nứt dưới áp suất 4,500 psi. Sáu trong một mẫu ngẫu nhiên gồm 100 van loại *B* bị nứt dưới áp suất 4,500 psi. Hãy kiểm định ở mức ý nghĩa 5%.

#### Bài tập

Một nghiên cứu đã được thực hiện về sự khác biệt giới tính liên quan đến việc sử dụng dây an toàn trên xe cơ giới. Nhà nghiên cứu tin rằng tỷ lệ phụ nữ không thắt dây an toàn thấp hơn tỷ lệ nam giới không thắt dây an toàn. Dữ liệu thu thập đại diện cho một mẫu ngẫu nhiên người trưởng thành tại Hoa Kỳ và được tóm tắt trong [Bảng 10.12](10-3-comparing-two-independent-population-proportions#fs-idm29483888). Liệu tỷ lệ phụ nữ không thắt dây an toàn có thấp hơn tỷ lệ nam giới không thắt dây an toàn không? Hãy kiểm định ở mức ý nghĩa 1%.

|  | Nam | Nữ |
| --- | --- | --- |
| Không thắt dây an toàn | 183 | 156 |
| Tổng số người được khảo sát | 2231 | 2169 |

Một cuộc khảo sát đã được thực hiện về đồ uống ưa thích là trà. Dữ liệu thu thập được tóm tắt trong bảng. Liệu tỷ lệ nam giới thích trà có nhiều hơn tỷ lệ nữ giới thích trà không? Hãy kiểm định ở mức ý nghĩa 1%.

| Nam | Nữ |
| --- | --- |
| **Thích trà** | 16 |
| **Tổng số được khảo sát** | 230 |

Nhấn STAT. Di chuyển sang TESTS và nhấn 6:2-PropZTest. Di chuyển xuống và nhập 156 cho x1, 2169 cho n1, 183 cho x2, và 2231 cho n2. Di chuyển xuống p1: và di chuyển đến less than p2. Nhấn `ENTER`. Di chuyển xuống Calculate và nhấn ENTER. p-giá trị *p* là *P* = 0,1045 và thống kê kiểm định là *z* = -1,256.

#### Bài tập

Một công ty tiếp thị tuyên bố rằng tỷ lệ người trẻ tuổi sở hữu xe điện lớn hơn tỷ lệ người lớn tuổi sở hữu xe điện. Một mẫu ngẫu nhiên người lớn tại Hoa Kỳ đã được lấy, và kết quả khảo sát cho thấy những điều sau:

- Trong một mẫu gồm 232 người lớn tuổi (từ 35 tuổi trở lên), 5% sở hữu xe điện.
- Trong một mẫu gồm 1,343 người trẻ tuổi (từ 34 tuổi trở xuống), 10% sở hữu xe điện.
Kiểm định ở mức ý nghĩa 5%. Liệu tỷ lệ người trẻ tuổi có lớn hơn tỷ lệ người lớn tuổi liên quan đến việc sở hữu xe điện không?

TI-83+ và TI-84: Nhấn `STAT`. Di chuyển sang TESTS và nhấn 6:2-PropZTest. Di chuyển xuống và nhập 135 cho x1, 1343 cho n1, 12 cho x2, và 232 cho n2. Di chuyển xuống p1: và di chuyển đến greater than p2. Nhấn `ENTER`. Di chuyển xuống Calculate và nhấn `ENTER`. P-giá trị là P = 0,0092 và thống kê kiểm định là Z = 2,33.

Một nhà nghiên cứu chính phủ đang điều tra xem liệu có sự khác biệt trong việc sử dụng mũ bảo hiểm của người đi xe máy ở các khu vực địa lý khác nhau đối với những bang mà luật pháp yêu cầu đội mũ bảo hiểm. Nghiên cứu cho thấy đối với người đi xe máy ở vùng Đông Bắc Hoa Kỳ, 7622 trong số 113,231 người không đội mũ bảo hiểm. Ở vùng Đông Nam Hoa Kỳ, 7439 trong số 104,873 người không đội mũ bảo hiểm. Hãy kiểm định ở mức ý nghĩa 5%. Trả lời các câu hỏi sau:

a. Đây là kiểm định hai số trung bình hay hai tỷ lệ?

b. Bạn sử dụng phân phối nào để thực hiện kiểm định?

c. Biến ngẫu nhiên là gì?

d. Giả thuyết không và đối thuyết là gì? Viết giả thuyết không và đối thuyết dưới dạng ký hiệu.

e. Đây là kiểm định đuôi phải, đuôi trái hay hai đuôi?

f. p-value là gì?

g. Bạn bác bỏ hay không bác bỏ giả thuyết không?

h. Tại mức ý nghĩa ___, từ dữ liệu mẫu, ______ (có/không có) đủ bằng chứng để kết luận rằng ____________.
