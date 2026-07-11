## 2.1
 
Biểu đồ thân và lá (Stemplot), biểu đồ đường và biểu đồ cột

Một loại biểu đồ đơn giản, **biểu đồ thân và lá** hay **stemplot**, xuất phát từ lĩnh vực phân tích dữ liệu khám phá. Đây là một lựa chọn tốt khi các tập dữ liệu nhỏ. Để tạo biểu đồ, hãy chia mỗi quan sát dữ liệu thành một thân và một lá. Lá bao gồm **chữ số có nghĩa cuối cùng**. Ví dụ, 23 có thân là hai và lá là ba. Số 432 có thân là 43 và lá là hai. Tương tự, số 5.432 có thân là 543 và lá là hai. Số thập phân 9,3 có thân là chín và lá là ba. Viết các thân theo một đường thẳng đứng từ nhỏ đến lớn. Vẽ một đường thẳng đứng bên phải các thân. Sau đó, viết các lá theo thứ tự tăng dần bên cạnh thân tương ứng của chúng.

Đối với lớp tiền giải tích mùa xuân của Giáo sư Dean, điểm số cho bài kiểm tra đầu tiên như sau (từ nhỏ đến lớn):

 33; 42; 49; 49; 53; 55; 55; 61; 63; 67; 68; 68; 69; 69; 72; 73; 74; 78; 80; 83; 88; 88; 88; 90; 92; 94; 94; 94; 94; 96; 100

| Thân | Lá |
| --- | --- |
| 3 | 3 |
| 4 | 2 9 9 |
| 5 | 3 5 5 |
| 6 | 1 3 7 8 8 9 9 |
| 7 | 2 3 4 8 |
| 8 | 0 3 8 8 8 |
| 9 | 0 2 4 4 4 4 6 |
| 10 | 0 |

Biểu đồ thân và lá cho thấy hầu hết điểm số rơi vào khoảng 60, 70, 80 và 90. Tám trong số 31 điểm số hoặc khoảng 26% (831)(831)(831) nằm trong khoảng 90 hoặc 100, một số lượng điểm A khá cao.

Đối với đội bóng rổ Park City, điểm số cho 30 trận gần nhất như sau (từ nhỏ đến lớn):

 32; 32; 33; 34; 38; 40; 42; 42; 43; 44; 46; 47; 47; 48; 48; 48; 49; 50; 50; 51; 52; 52; 52; 53; 54; 56; 57; 57; 60; 61

Hãy xây dựng một biểu đồ thân và lá cho dữ liệu này.

Biểu đồ thân và lá là một cách nhanh chóng để vẽ đồ thị dữ liệu và cung cấp một hình ảnh chính xác về dữ liệu. Bạn nên tìm kiếm một mô hình tổng thể và bất kỳ giá trị ngoại lệ nào. Một Điểm bất thường / Giá trị ngoại lai là một quan sát dữ liệu không phù hợp với phần còn lại của dữ liệu. Đôi khi nó được gọi là một **giá trị cực đoan.** Khi bạn vẽ đồ thị một giá trị ngoại lệ, nó sẽ có vẻ không khớp với mô hình của biểu đồ. Một số giá trị ngoại lệ là do sai sót (ví dụ: viết 50 thay vì 500) trong khi những giá trị khác có thể chỉ ra rằng có điều gì đó bất thường đang xảy ra. Cần có một số thông tin cơ bản để giải thích các giá trị ngoại lệ, vì vậy chúng ta sẽ đề cập chi tiết hơn về chúng sau.

Dữ liệu là khoảng cách (tính bằng km) từ nhà đến các siêu thị địa phương. Hãy tạo một biểu đồ thân và lá sử dụng dữ liệu:

1.1; 1.5; 2.3; 2.5; 2.7; 3.2; 3.3; 3.3; 3.5; 3.8; 4.0; 4.2; 4.5; 4.5; 4.7; 4.8; 5.5; 5.6; 6.5; 6.7; 12.3

#### Bài toán

Dữ liệu có vẻ có sự tập trung các giá trị nào không?

Các lá nằm bên phải dấu thập phân.

Dữ liệu sau đây cho thấy khoảng cách (tính bằng dặm) từ nhà của các sinh viên thống kê ngoài khuôn viên trường đến trường đại học. Hãy tạo một biểu đồ thân và lá sử dụng dữ liệu này và xác định bất kỳ giá trị ngoại lệ nào:

0.5; 0.7; 1.1; 1.2; 1.2; 1.3; 1.3; 1.5; 1.5; 1.7; 1.7; 1.8; 1.9; 2.0; 2.2; 2.5; 2.6; 2.8; 2.8; 2.8; 3.5; 3.8; 4.4; 4.8; 4.9; 5.2; 5.5; 5.7; 5.8; 8.0

#### Bài toán

Một **biểu đồ thân và lá song song** cho phép so sánh hai tập dữ liệu trong hai cột. Trong biểu đồ thân và lá song song, hai tập hợp lá chia sẻ cùng một thân. Các lá nằm ở bên trái và bên phải của các thân. [Bảng 2.3](2-1-stem-and-leaf-graphs-stemplots-line-graphs-and-bar-graphs#M01_Ch02_tbl005) và [Bảng 2.4](2-1-stem-and-leaf-graphs-stemplots-line-graphs-and-bar-graphs#M01_Ch02_tbl006) cho thấy độ tuổi của các tổng thống khi nhậm chức và khi qua đời. Hãy xây dựng một biểu đồ thân và lá song song sử dụng dữ liệu này.

| Tổng thống | Tuổi | Tổng thống | Tuổi | Tổng thống | Tuổi |
| --- | --- | --- | --- | --- | --- |
| Washington | 57 | Lincoln | 52 | Hoover | 54 |
| J. Adams | 61 | A. Johnson | 56 | F. Roosevelt | 51 |
| Jefferson | 57 | Grant | 46 | Truman | 60 |
| Madison | 57 | Hayes | 54 | Eisenhower | 62 |
| Monroe | 58 | Garfield | 49 | Kennedy | 43 |
| J. Q. Adams | 57 | Arthur | 51 | L. Johnson | 55 |
| Jackson | 61 | Cleveland | 47 | Nixon | 56 |
| Van Buren | 54 | B. Harrison | 55 | Ford | 61 |
| W. H. Harrison | 68 | Cleveland | 55 | Carter | 52 |
| Tyler | 51 | McKinley | 54 | Reagan | 69 |
| Polk | 49 | T. Roosevelt | 42 | G.H.W. Bush | 64 |
| Taylor | 64 | Taft | 51 | Clinton | 47 |
| Fillmore | 50 | Wilson | 56 | G. W. Bush | 54 |
| Pierce | 48 | Harding | 55 | Obama | 47 |
| Buchanan | 65 | Coolidge | 51 |  |  |

| Tổng thống | Tuổi | Tổng thống | Tuổi | Tổng thống | Tuổi |
| --- | --- | --- | --- | --- | --- |
| Washington | 67 | Lincoln | 56 | Hoover | 90 |
| J. Adams | 90 | A. Johnson | 66 | F. Roosevelt | 63 |
| Jefferson | 83 | Grant | 63 | Truman | 88 |
| Madison | 85 | Hayes | 70 | Eisenhower | 78 |
| Monroe | 73 | Garfield | 49 | Kennedy | 46 |
| J. Q. Adams | 80 | Arthur | 56 | L. Johnson | 64 |
| Jackson | 78 | Cleveland | 71 | Nixon | 81 |
| Van Buren | 79 | B. Harrison | 67 | Ford | 93 |
| W. H. Harrison | 68 | Cleveland | 71 | Reagan | 93 |
| Tyler | 71 | McKinley | 58 |  |  |
| Polk | 53 | T. Roosevelt | 60 |  |  |
| Taylor | 65 | Taft | 72 |  |  |
| Fillmore | 74 | Wilson | 67 |  |  |
| Pierce | 64 | Harding | 57 |  |  |
| Buchanan | 77 | Coolidge | 60 |  |  |

Bảng này cho thấy số trận thắng và thua mà đội Atlanta Hawks đã có trong 42 mùa giải. Hãy tạo một biểu đồ thân và lá song song về các trận thắng và thua này.

| Số trận thua | Số trận thắng | Mùa giải | Số trận thua | Số trận thắng | Mùa giải |
| --- | --- | --- | --- | --- | --- |
| 34 | 48 | 1 | 41 | 41 | 22 |
| 34 | 48 | 2 | 39 | 43 | 23 |
| 46 | 36 | 3 | 44 | 38 | 24 |
| 46 | 36 | 4 | 39 | 43 | 25 |
| 36 | 46 | 5 | 25 | 57 | 26 |
| 47 | 35 | 6 | 40 | 42 | 27 |
| 51 | 31 | 7 | 36 | 46 | 28 |
| 53 | 29 | 8 | 26 | 56 | 29 |
| 51 | 31 | 9 | 32 | 50 | 30 |
| 41 | 41 | 10 | 19 | 31 | 31 |
| 36 | 46 | 11 | 54 | 28 | 32 |
| 32 | 50 | 12 | 57 | 25 | 33 |
| 51 | 31 | 13 | 49 | 33 | 34 |
| 40 | 42 | 14 | 47 | 35 | 35 |
| 39 | 43 | 15 | 54 | 28 | 36 |
| 42 | 40 | 16 | 69 | 13 | 37 |
| 48 | 34 | 17 | 56 | 26 | 38 |
| 32 | 50 | 18 | 52 | 30 | 39 |
| 25 | 57 | 19 | 45 | 37 | 40 |
| 32 | 50 | 20 | 35 | 47 | 41 |
| 30 | 52 | 21 | 29 | 53 | 42 |

Một loại biểu đồ khác hữu ích cho các giá trị dữ liệu cụ thể là **biểu đồ đường**. Trong biểu đồ đường cụ thể được hiển thị trong [Ví dụ 2.4](2-1-stem-and-leaf-graphs-stemplots-line-graphs-and-bar-graphs#example4), **trục *x*** (trục ngang) bao gồm các **giá trị dữ liệu** và **trục *y*** (trục dọc) bao gồm các **điểm tần số**. Các điểm tần số được nối với nhau bằng các đoạn thẳng.

Trong một cuộc khảo sát, 40 phụ huynh được hỏi mỗi tuần một thiếu niên cần được nhắc nhở bao nhiêu lần để làm việc nhà. Kết quả được hiển thị trong [Bảng 2.7](2-1-stem-and-leaf-graphs-stemplots-line-graphs-and-bar-graphs#M01_Ch02_tbl008) và trong [Hình 2.2](2-1-stem-and-leaf-graphs-stemplots-line-graphs-and-bar-graphs#M01_Ch02_fig001).

| Số lần thanh thiếu niên được nhắc nhở | Tần số |
| --- | --- |
| 0 | 2 |
| 1 | 5 |
| 2 | 8 |
| 3 | 14 |
| 4 | 7 |
| 5 | 4 |

*Hình 
2.2*

Trong một cuộc khảo sát, 40 người được hỏi mỗi năm họ mang xe đi sửa bao nhiêu lần. Kết quả được hiển thị trong [Bảng 2.8](2-1-stem-and-leaf-graphs-stemplots-line-graphs-and-bar-graphs#M01_Ch02_tbl009). Hãy xây dựng một biểu đồ đường.

| Số lần trong cửa hàng | Tần số |
| --- | --- |
| 0 | 7 |
| 1 | 10 |
| 2 | 14 |
| 3 | 9 |

**Biểu đồ cột** bao gồm các cột tách biệt với nhau. Các cột có thể là hình chữ nhật hoặc các hộp hình chữ nhật (được sử dụng trong các biểu đồ ba chiều), và chúng có thể theo chiều dọc hoặc chiều ngang. **Biểu đồ cột** được hiển thị trong [Ví dụ 2.5](2-1-stem-and-leaf-graphs-stemplots-line-graphs-and-bar-graphs#example5) có các nhóm tuổi được thể hiện trên **trục *x*** và các tỷ lệ trên **trục *y***.

#### Bài toán

Tỷ lệ phần trăm người dùng TikTok tại Hoa Kỳ theo độ tuổi được hiển thị trong [Bảng 2.9](2-1-stem-and-leaf-graphs-stemplots-line-graphs-and-bar-graphs#M01_Ch02_tbl010). Hãy xây dựng một biểu đồ cột sử dụng dữ liệu này.

| Các nhóm tuổi | Tỷ lệ (%) người dùng TikTok |
| --- | --- |
| 10–19 | 32.5% |
| 20–29 | 29.5% |
| 30–39 | 16.4% |
| 40–49 | 13.9% |
| 50+ | 7.1% |

Dân số ở Park City bao gồm trẻ em, người lớn trong độ tuổi lao động và người về hưu. [Bảng 2.10](2-1-stem-and-leaf-graphs-stemplots-line-graphs-and-bar-graphs#M01_Ch02_tbl011) hiển thị ba nhóm tuổi, số lượng người trong thị trấn thuộc mỗi nhóm tuổi và tỷ lệ (%) người trong mỗi nhóm tuổi. Hãy xây dựng một biểu đồ cột hiển thị các tỷ lệ này.

| Các nhóm tuổi | Số người | Tỷ lệ quần thể |
| --- | --- | --- |
| Trẻ em | 67,059 | 19% |
| Người lớn trong độ tuổi lao động | 152,198 | 43% |
| Người về hưu | 131,662 | 38% |

#### Bài toán

Các cột trong [Bảng 2.11](2-1-stem-and-leaf-graphs-stemplots-line-graphs-and-bar-graphs#M01_Ch02_tbl012) hiển thị dữ liệu dự kiến cho năm 2030 về số lượng và tỷ lệ phần trăm học sinh tốt nghiệp trung học theo khu vực địa lý tại Hoa Kỳ. Hãy tạo một biểu đồ cột cho dữ liệu này với khu vực địa lý (dữ liệu định tính) trên trục *x* và tỷ lệ phần trăm học sinh tốt nghiệp trung học (dữ liệu định lượng) trên trục *y*.

| Khu vực | Số lượng sinh viên tốt nghiệp | Tỷ lệ phần trăm sinh viên tốt nghiệp |
| --- | --- | --- |
| Đông Bắc | 517,720 | 16.1% |
| Trung Tây | 695,170 | 21.6% |
| Miền Nam | 1,253,540 | 39.0% |
| Miền Tây | 749,400 | 23.3% |

Park City được chia thành sáu khu vực bầu cử. Bảng này hiển thị phần trăm tổng dân số cử tri đã đăng ký sống ở mỗi khu vực cũng như tổng phần trăm của toàn bộ dân số sống ở mỗi khu vực. Hãy xây dựng một biểu đồ cột hiển thị dân số cử tri đã đăng ký theo khu vực.

| Quận | Dân số cử tri đã đăng ký | Tổng dân số thành phố |
| --- | --- | --- |
| 1 | 15.5% | 19.4% |
| 2 | 12.2% | 15.6% |
| 3 | 9.8% | 9.0% |
| 4 | 17.4% | 18.5% |
| 5 | 22.8% | 20.7% |
| 6 | 22.3% | 16.8% |
