## 2.1
 
Stem-and-Leaf Graphs (Stemplots), Line Graphs, and Bar Graphs

## 2.1
 
Biểu đồ thân và lá (Stemplot), biểu đồ đường và biểu đồ cột

One simple graph, the **stem-and-leaf graph** or **stemplot**, comes from the field of exploratory data analysis. It is a good choice when the data sets are small. To create the plot, divide each observation of data into a stem and a leaf. The leaf consists of a **final significant digit**. For example, 23 has stem two and leaf three. The number 432 has stem 43 and leaf two. Likewise, the number 5,432 has stem 543 and leaf two. The decimal 9.3 has stem nine and leaf three. Write the stems in a vertical line from smallest to largest. Draw a vertical line to the right of the stems. Then write the leaves in increasing order next to their corresponding stem.

Một loại biểu đồ đơn giản, **biểu đồ thân và lá** hay **stemplot**, xuất phát từ lĩnh vực phân tích dữ liệu khám phá. Đây là một lựa chọn tốt khi các tập dữ liệu nhỏ. Để tạo biểu đồ, hãy chia mỗi quan sát dữ liệu thành một thân và một lá. Lá bao gồm **chữ số có nghĩa cuối cùng**. Ví dụ, 23 có thân là hai và lá là ba. Số 432 có thân là 43 và lá là hai. Tương tự, số 5.432 có thân là 543 và lá là hai. Số thập phân 9,3 có thân là chín và lá là ba. Viết các thân theo một đường thẳng đứng từ nhỏ đến lớn. Vẽ một đường thẳng đứng bên phải các thân. Sau đó, viết các lá theo thứ tự tăng dần bên cạnh thân tương ứng của chúng.

For Professor Dean's spring pre-calculus class, scores for the first exam were as follows (smallest to largest):

 33; 42; 49; 49; 53; 55; 55; 61; 63; 67; 68; 68; 69; 69; 72; 73; 74; 78; 80; 83; 88; 88; 88; 90; 92; 94; 94; 94; 94; 96; 100

Đối với lớp tiền giải tích mùa xuân của Giáo sư Dean, điểm số cho bài kiểm tra đầu tiên như sau (từ nhỏ đến lớn):

 33; 42; 49; 49; 53; 55; 55; 61; 63; 67; 68; 68; 69; 69; 72; 73; 74; 78; 80; 83; 88; 88; 88; 90; 92; 94; 94; 94; 94; 96; 100

| Stem | Thân | Leaf | Lá |
| --- | --- | --- | --- |
| 3 | 3 | 3 | 3 |
| 4 | 4 | 2 9 9 | 2 9 9 |
| 5 | 5 | 3 5 5 | 3 5 5 |
| 6 | 6 | 1 3 7 8 8 9 9 | 1 3 7 8 8 9 9 |
| 7 | 7 | 2 3 4 8 | 2 3 4 8 |
| 8 | 8 | 0 3 8 8 8 | 0 3 8 8 8 |
| 9 | 9 | 0 2 4 4 4 4 6 | 0 2 4 4 4 4 6 |
| 10 | 10 | 0 | 0 |

The stemplot shows that most scores fell in the 60s, 70s, 80s, and 90s.  Eight out of the 31 scores or approximately 26% (831)(831)(831) were in the 90s or 100, a fairly high number of As.

Biểu đồ thân và lá cho thấy hầu hết điểm số rơi vào khoảng 60, 70, 80 và 90. Tám trong số 31 điểm số hoặc khoảng 26% (831)(831)(831) nằm trong khoảng 90 hoặc 100, một số lượng điểm A khá cao.

For the Park City basketball team, scores for the last 30 games were as follows (smallest to largest):

 32; 32; 33; 34; 38; 40; 42; 42; 43; 44; 46; 47; 47; 48; 48; 48; 49; 50; 50; 51; 52; 52; 52; 53; 54; 56; 57; 57; 60; 61

Construct a stem plot for the data.

Đối với đội bóng rổ Park City, điểm số cho 30 trận gần nhất như sau (từ nhỏ đến lớn):

 32; 32; 33; 34; 38; 40; 42; 42; 43; 44; 46; 47; 47; 48; 48; 48; 49; 50; 50; 51; 52; 52; 52; 53; 54; 56; 57; 57; 60; 61

Hãy xây dựng một biểu đồ thân và lá cho dữ liệu này.

The stemplot is a quick way to graph data and gives an exact picture of the data. You want to look for an overall pattern and any outliers. An outlier is an observation of data that does not fit the rest of the data. It is sometimes called an **extreme value.** When you graph an outlier, it will appear not to fit the pattern of the graph. Some outliers are due to mistakes (for example, writing down 50 instead of 500) while others may indicate that something unusual is happening. It takes some background information to explain outliers, so we will cover them in more detail later.

Biểu đồ thân và lá là một cách nhanh chóng để vẽ đồ thị dữ liệu và cung cấp một hình ảnh chính xác về dữ liệu. Bạn nên tìm kiếm một mô hình tổng thể và bất kỳ giá trị ngoại lệ nào. Một Điểm bất thường / Giá trị ngoại lai là một quan sát dữ liệu không phù hợp với phần còn lại của dữ liệu. Đôi khi nó được gọi là một **giá trị cực đoan.** Khi bạn vẽ đồ thị một giá trị ngoại lệ, nó sẽ có vẻ không khớp với mô hình của biểu đồ. Một số giá trị ngoại lệ là do sai sót (ví dụ: viết 50 thay vì 500) trong khi những giá trị khác có thể chỉ ra rằng có điều gì đó bất thường đang xảy ra. Cần có một số thông tin cơ bản để giải thích các giá trị ngoại lệ, vì vậy chúng ta sẽ đề cập chi tiết hơn về chúng sau.

The data are the distances (in kilometers) from a home to local supermarkets. Create a stemplot using the data:

1.1; 1.5; 2.3; 2.5; 2.7; 3.2; 3.3; 3.3; 3.5; 3.8; 4.0; 4.2; 4.5; 4.5; 4.7; 4.8; 5.5; 5.6; 6.5; 6.7; 12.3

Dữ liệu là khoảng cách (tính bằng km) từ nhà đến các siêu thị địa phương. Hãy tạo một biểu đồ thân và lá sử dụng dữ liệu:

1.1; 1.5; 2.3; 2.5; 2.7; 3.2; 3.3; 3.3; 3.5; 3.8; 4.0; 4.2; 4.5; 4.5; 4.7; 4.8; 5.5; 5.6; 6.5; 6.7; 12.3

#### Problem

#### Bài toán

Do the data seem to have any concentration of values?

Dữ liệu có vẻ có sự tập trung các giá trị nào không?

The leaves are to the right of the decimal.

Các lá nằm bên phải dấu thập phân.

The following data show the distances (in miles) from the homes of off-campus statistics students to the college. Create a stem plot using the data and identify any outliers:

Dữ liệu sau đây cho thấy khoảng cách (tính bằng dặm) từ nhà của các sinh viên thống kê ngoài khuôn viên trường đến trường đại học. Hãy tạo một biểu đồ thân và lá sử dụng dữ liệu này và xác định bất kỳ giá trị ngoại lệ nào:

0.5; 0.7; 1.1; 1.2; 1.2; 1.3; 1.3; 1.5; 1.5; 1.7; 1.7; 1.8; 1.9; 2.0; 2.2; 2.5; 2.6; 2.8; 2.8; 2.8; 3.5; 3.8; 4.4; 4.8; 4.9; 5.2; 5.5; 5.7; 5.8; 8.0

0.5; 0.7; 1.1; 1.2; 1.2; 1.3; 1.3; 1.5; 1.5; 1.7; 1.7; 1.8; 1.9; 2.0; 2.2; 2.5; 2.6; 2.8; 2.8; 2.8; 3.5; 3.8; 4.4; 4.8; 4.9; 5.2; 5.5; 5.7; 5.8; 8.0

#### Problem

#### Bài toán

A **side-by-side stem-and-leaf plot** allows a comparison of the two data sets in two columns. In a side-by-side stem-and-leaf plot, two sets of leaves share the same stem. The leaves are to the left and the right of the stems. [Table 2.3](2-1-stem-and-leaf-graphs-stemplots-line-graphs-and-bar-graphs#M01_Ch02_tbl005) and [Table 2.4](2-1-stem-and-leaf-graphs-stemplots-line-graphs-and-bar-graphs#M01_Ch02_tbl006) show the ages of presidents at their inauguration and at their death. Construct a side-by-side stem-and-leaf plot using this data.

Một **biểu đồ thân và lá song song** cho phép so sánh hai tập dữ liệu trong hai cột. Trong biểu đồ thân và lá song song, hai tập hợp lá chia sẻ cùng một thân. Các lá nằm ở bên trái và bên phải của các thân. [Bảng 2.3](2-1-stem-and-leaf-graphs-stemplots-line-graphs-and-bar-graphs#M01_Ch02_tbl005) và [Bảng 2.4](2-1-stem-and-leaf-graphs-stemplots-line-graphs-and-bar-graphs#M01_Ch02_tbl006) cho thấy độ tuổi của các tổng thống khi nhậm chức và khi qua đời. Hãy xây dựng một biểu đồ thân và lá song song sử dụng dữ liệu này.

| President | Tổng thống | Age | Tuổi | President | Tổng thống | Age | Tuổi | President | Tổng thống | Age | Tuổi |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Washington | Washington | 57 | 57 | Lincoln | Lincoln | 52 | 52 | Hoover | Hoover | 54 | 54 |
| J. Adams | J. Adams | 61 | 61 | A. Johnson | A. Johnson | 56 | 56 | F. Roosevelt | F. Roosevelt | 51 | 51 |
| Jefferson | Jefferson | 57 | 57 | Grant | Grant | 46 | 46 | Truman | Truman | 60 | 60 |
| Madison | Madison | 57 | 57 | Hayes | Hayes | 54 | 54 | Eisenhower | Eisenhower | 62 | 62 |
| Monroe | Monroe | 58 | 58 | Garfield | Garfield | 49 | 49 | Kennedy | Kennedy | 43 | 43 |
| J. Q. Adams | J. Q. Adams | 57 | 57 | Arthur | Arthur | 51 | 51 | L. Johnson | L. Johnson | 55 | 55 |
| Jackson | Jackson | 61 | 61 | Cleveland | Cleveland | 47 | 47 | Nixon | Nixon | 56 | 56 |
| Van Buren | Van Buren | 54 | 54 | B. Harrison | B. Harrison | 55 | 55 | Ford | Ford | 61 | 61 |
| W. H. Harrison | W. H. Harrison | 68 | 68 | Cleveland | Cleveland | 55 | 55 | Carter | Carter | 52 | 52 |
| Tyler | Tyler | 51 | 51 | McKinley | McKinley | 54 | 54 | Reagan | Reagan | 69 | 69 |
| Polk | Polk | 49 | 49 | T. Roosevelt | T. Roosevelt | 42 | 42 | G.H.W. Bush | G.H.W. Bush | 64 | 64 |
| Taylor | Taylor | 64 | 64 | Taft | Taft | 51 | 51 | Clinton | Clinton | 47 | 47 |
| Fillmore | Fillmore | 50 | 50 | Wilson | Wilson | 56 | 56 | G. W. Bush | G. W. Bush | 54 | 54 |
| Pierce | Pierce | 48 | 48 | Harding | Harding | 55 | 55 | Obama | Obama | 47 | 47 |
| Buchanan | Buchanan | 65 | 65 | Coolidge | Coolidge | 51 | 51 |  |  |  |  |

| President | Tổng thống | Age | Tuổi | President | Tổng thống | Age | Tuổi | President | Tổng thống | Age | Tuổi |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Washington | Washington | 67 | 67 | Lincoln | Lincoln | 56 | 56 | Hoover | Hoover | 90 | 90 |
| J. Adams | J. Adams | 90 | 90 | A. Johnson | A. Johnson | 66 | 66 | F. Roosevelt | F. Roosevelt | 63 | 63 |
| Jefferson | Jefferson | 83 | 83 | Grant | Grant | 63 | 63 | Truman | Truman | 88 | 88 |
| Madison | Madison | 85 | 85 | Hayes | Hayes | 70 | 70 | Eisenhower | Eisenhower | 78 | 78 |
| Monroe | Monroe | 73 | 73 | Garfield | Garfield | 49 | 49 | Kennedy | Kennedy | 46 | 46 |
| J. Q. Adams | J. Q. Adams | 80 | 80 | Arthur | Arthur | 56 | 56 | L. Johnson | L. Johnson | 64 | 64 |
| Jackson | Jackson | 78 | 78 | Cleveland | Cleveland | 71 | 71 | Nixon | Nixon | 81 | 81 |
| Van Buren | Van Buren | 79 | 79 | B. Harrison | B. Harrison | 67 | 67 | Ford | Ford | 93 | 93 |
| W. H. Harrison | W. H. Harrison | 68 | 68 | Cleveland | Cleveland | 71 | 71 | Reagan | Reagan | 93 | 93 |
| Tyler | Tyler | 71 | 71 | McKinley | McKinley | 58 | 58 |  |  |  |  |
| Polk | Polk | 53 | 53 | T. Roosevelt | T. Roosevelt | 60 | 60 |  |  |  |  |
| Taylor | Taylor | 65 | 65 | Taft | Taft | 72 | 72 |  |  |  |  |
| Fillmore | Fillmore | 74 | 74 | Wilson | Wilson | 67 | 67 |  |  |  |  |
| Pierce | Pierce | 64 | 64 | Harding | Harding | 57 | 57 |  |  |  |  |
| Buchanan | Buchanan | 77 | 77 | Coolidge | Coolidge | 60 | 60 |  |  |  |  |

The table shows the number of wins and losses the Atlanta Hawks have had in 42 seasons. Create a side-by-side stemand-leaf plot of these wins and losses.

Bảng này cho thấy số trận thắng và thua mà đội Atlanta Hawks đã có trong 42 mùa giải. Hãy tạo một biểu đồ thân và lá song song về các trận thắng và thua này.

| Losses | Số trận thua | Wins | Số trận thắng | Season | Mùa giải | Losses | Số trận thua | Wins | Số trận thắng | Season | Mùa giải |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 34 | 34 | 48 | 48 | 1 | 1 | 41 | 41 | 41 | 41 | 22 | 22 |
| 34 | 34 | 48 | 48 | 2 | 2 | 39 | 39 | 43 | 43 | 23 | 23 |
| 46 | 46 | 36 | 36 | 3 | 3 | 44 | 44 | 38 | 38 | 24 | 24 |
| 46 | 46 | 36 | 36 | 4 | 4 | 39 | 39 | 43 | 43 | 25 | 25 |
| 36 | 36 | 46 | 46 | 5 | 5 | 25 | 25 | 57 | 57 | 26 | 26 |
| 47 | 47 | 35 | 35 | 6 | 6 | 40 | 40 | 42 | 42 | 27 | 27 |
| 51 | 51 | 31 | 31 | 7 | 7 | 36 | 36 | 46 | 46 | 28 | 28 |
| 53 | 53 | 29 | 29 | 8 | 8 | 26 | 26 | 56 | 56 | 29 | 29 |
| 51 | 51 | 31 | 31 | 9 | 9 | 32 | 32 | 50 | 50 | 30 | 30 |
| 41 | 41 | 41 | 41 | 10 | 10 | 19 | 19 | 31 | 31 | 31 | 31 |
| 36 | 36 | 46 | 46 | 11 | 11 | 54 | 54 | 28 | 28 | 32 | 32 |
| 32 | 32 | 50 | 50 | 12 | 12 | 57 | 57 | 25 | 25 | 33 | 33 |
| 51 | 51 | 31 | 31 | 13 | 13 | 49 | 49 | 33 | 33 | 34 | 34 |
| 40 | 40 | 42 | 42 | 14 | 14 | 47 | 47 | 35 | 35 | 35 | 35 |
| 39 | 39 | 43 | 43 | 15 | 15 | 54 | 54 | 28 | 28 | 36 | 36 |
| 42 | 42 | 40 | 40 | 16 | 16 | 69 | 69 | 13 | 13 | 37 | 37 |
| 48 | 48 | 34 | 34 | 17 | 17 | 56 | 56 | 26 | 26 | 38 | 38 |
| 32 | 32 | 50 | 50 | 18 | 18 | 52 | 52 | 30 | 30 | 39 | 39 |
| 25 | 25 | 57 | 57 | 19 | 19 | 45 | 45 | 37 | 37 | 40 | 40 |
| 32 | 32 | 50 | 50 | 20 | 20 | 35 | 35 | 47 | 47 | 41 | 41 |
| 30 | 30 | 52 | 52 | 21 | 21 | 29 | 29 | 53 | 53 | 42 | 42 |

Another type of graph that is useful for specific data values is a **line graph**. In the particular line graph shown in [Example 2.4](2-1-stem-and-leaf-graphs-stemplots-line-graphs-and-bar-graphs#example4), the ***x*-axis** (horizontal axis) consists of **data values** and the ***y*-axis** (vertical axis) consists of **frequency points**. The frequency points are connected  using line segments.

Một loại biểu đồ khác hữu ích cho các giá trị dữ liệu cụ thể là **biểu đồ đường**. Trong biểu đồ đường cụ thể được hiển thị trong [Ví dụ 2.4](2-1-stem-and-leaf-graphs-stemplots-line-graphs-and-bar-graphs#example4), **trục *x*** (trục ngang) bao gồm các **giá trị dữ liệu** và **trục *y*** (trục dọc) bao gồm các **điểm tần số**. Các điểm tần số được nối với nhau bằng các đoạn thẳng.

In a survey, 40 parents were asked how many times per week a teenager must be reminded to do their chores. The results are shown in [Table 2.7](2-1-stem-and-leaf-graphs-stemplots-line-graphs-and-bar-graphs#M01_Ch02_tbl008) and in [Figure 2.2](2-1-stem-and-leaf-graphs-stemplots-line-graphs-and-bar-graphs#M01_Ch02_fig001).

Trong một cuộc khảo sát, 40 phụ huynh được hỏi mỗi tuần một thiếu niên cần được nhắc nhở bao nhiêu lần để làm việc nhà. Kết quả được hiển thị trong [Bảng 2.7](2-1-stem-and-leaf-graphs-stemplots-line-graphs-and-bar-graphs#M01_Ch02_tbl008) và trong [Hình 2.2](2-1-stem-and-leaf-graphs-stemplots-line-graphs-and-bar-graphs#M01_Ch02_fig001).

| Number of times
teenager is reminded | Số lần thanh thiếu niên được nhắc nhở | Frequency | Tần số |
| --- | --- | --- | --- |
| 0 | 0 | 2 | 2 |
| 1 | 1 | 5 | 5 |
| 2 | 2 | 8 | 8 |
| 3 | 3 | 14 | 14 |
| 4 | 4 | 7 | 7 |
| 5 | 5 | 4 | 4 |

*Figure 
2.2*

*Hình 
2.2*

In a survey, 40 people were asked how many times per year they had their car in the shop for repairs. The results are shown in [Table 2.8](2-1-stem-and-leaf-graphs-stemplots-line-graphs-and-bar-graphs#M01_Ch02_tbl009). Construct a line graph.

Trong một cuộc khảo sát, 40 người được hỏi mỗi năm họ mang xe đi sửa bao nhiêu lần. Kết quả được hiển thị trong [Bảng 2.8](2-1-stem-and-leaf-graphs-stemplots-line-graphs-and-bar-graphs#M01_Ch02_tbl009). Hãy xây dựng một biểu đồ đường.

| Number of times in shop | Số lần trong cửa hàng | Frequency | Tần số |
| --- | --- | --- | --- |
| 0 | 0 | 7 | 7 |
| 1 | 1 | 10 | 10 |
| 2 | 2 | 14 | 14 |
| 3 | 3 | 9 | 9 |

**Bar graphs** consist of bars that are separated from each other. The bars can be rectangles or they can be rectangular boxes (used in three-dimensional plots), and they can be vertical or horizontal. The **bar graph** shown in [Example 2.5](2-1-stem-and-leaf-graphs-stemplots-line-graphs-and-bar-graphs#example5) has age groups represented on the ***x*-axis** and proportions on the ***y*-axis**.

**Biểu đồ cột** bao gồm các cột tách biệt với nhau. Các cột có thể là hình chữ nhật hoặc các hộp hình chữ nhật (được sử dụng trong các biểu đồ ba chiều), và chúng có thể theo chiều dọc hoặc chiều ngang. **Biểu đồ cột** được hiển thị trong [Ví dụ 2.5](2-1-stem-and-leaf-graphs-stemplots-line-graphs-and-bar-graphs#example5) có các nhóm tuổi được thể hiện trên **trục *x*** và các tỷ lệ trên **trục *y***.

#### Problem

#### Bài toán

The percentage of U.S.-based TikTok users by age is shown in [Table 2.9](2-1-stem-and-leaf-graphs-stemplots-line-graphs-and-bar-graphs#M01_Ch02_tbl010). Construct a bar graph using this data.

Tỷ lệ phần trăm người dùng TikTok tại Hoa Kỳ theo độ tuổi được hiển thị trong [Bảng 2.9](2-1-stem-and-leaf-graphs-stemplots-line-graphs-and-bar-graphs#M01_Ch02_tbl010). Hãy xây dựng một biểu đồ cột sử dụng dữ liệu này.

| Age groups | Các nhóm tuổi | Proportion (%) of TikTok users | Tỷ lệ (%) người dùng TikTok |
| --- | --- | --- | --- |
| 10–19 | 10–19 | 32.5% | 32.5% |
| 20–29 | 20–29 | 29.5% | 29.5% |
| 30–39 | 30–39 | 16.4% | 16.4% |
| 40–49 | 40–49 | 13.9% | 13.9% |
| 50+ | 50+ | 7.1% | 7.1% |

The population in Park City is made up of children, working-age adults, and retirees. [Table 2.10](2-1-stem-and-leaf-graphs-stemplots-line-graphs-and-bar-graphs#M01_Ch02_tbl011) shows the three age groups, the number of people in the town from each age group, and the proportion (%) of people in each age group. Construct a bar graph showing the proportions.

Dân số ở Park City bao gồm trẻ em, người lớn trong độ tuổi lao động và người về hưu. [Bảng 2.10](2-1-stem-and-leaf-graphs-stemplots-line-graphs-and-bar-graphs#M01_Ch02_tbl011) hiển thị ba nhóm tuổi, số lượng người trong thị trấn thuộc mỗi nhóm tuổi và tỷ lệ (%) người trong mỗi nhóm tuổi. Hãy xây dựng một biểu đồ cột hiển thị các tỷ lệ này.

| Age groups | Các nhóm tuổi | Number of people | Số người | Proportion of population | Tỷ lệ quần thể |
| --- | --- | --- | --- | --- | --- |
| Children | Trẻ em | 67,059 | 67,059 | 19% | 19% |
| Working-age adults | Người lớn trong độ tuổi lao động | 152,198 | 152,198 | 43% | 43% |
| Retirees | Người về hưu | 131,662 | 131,662 | 38% | 38% |

#### Problem

#### Bài toán

The columns in [Table 2.11](2-1-stem-and-leaf-graphs-stemplots-line-graphs-and-bar-graphs#M01_Ch02_tbl012) show the projected data for the year 2030 for the number and percentages of high school graduates by geographic region in the United States.  Create a bar graph for this data with the geographic region (qualitative data) on the *x*-axis and the percentage of high school data (quantitative data) on the *y*-axis.

Các cột trong [Bảng 2.11](2-1-stem-and-leaf-graphs-stemplots-line-graphs-and-bar-graphs#M01_Ch02_tbl012) hiển thị dữ liệu dự kiến cho năm 2030 về số lượng và tỷ lệ phần trăm học sinh tốt nghiệp trung học theo khu vực địa lý tại Hoa Kỳ. Hãy tạo một biểu đồ cột cho dữ liệu này với khu vực địa lý (dữ liệu định tính) trên trục *x* và tỷ lệ phần trăm học sinh tốt nghiệp trung học (dữ liệu định lượng) trên trục *y*.

| Region | Khu vực | Number of Graduates | Số lượng sinh viên tốt nghiệp | Percentage of Graduates | Tỷ lệ phần trăm sinh viên tốt nghiệp |
| --- | --- | --- | --- | --- | --- |
| Northeast | Đông Bắc | 517,720 | 517,720 | 16.1% | 16.1% |
| Midwest | Trung Tây | 695,170 | 695,170 | 21.6% | 21.6% |
| South | Miền Nam | 1,253,540 | 1,253,540 | 39.0% | 39.0% |
| West | Miền Tây | 749,400 | 749,400 | 23.3% | 23.3% |

Park city is broken down into six voting districts. The table shows the percent of the total registered voter population that lives in each district as well as the percent total of the entire population that lives in each district. Construct a bar graph that shows the registered voter population by district.

Park City được chia thành sáu khu vực bầu cử. Bảng này hiển thị phần trăm tổng dân số cử tri đã đăng ký sống ở mỗi khu vực cũng như tổng phần trăm của toàn bộ dân số sống ở mỗi khu vực. Hãy xây dựng một biểu đồ cột hiển thị dân số cử tri đã đăng ký theo khu vực.

| District | Quận | Registered voter population | Dân số cử tri đã đăng ký | Overall city population | Tổng dân số thành phố |
| --- | --- | --- | --- | --- | --- |
| 1 | 1 | 15.5% | 15.5% | 19.4% | 19.4% |
| 2 | 2 | 12.2% | 12.2% | 15.6% | 15.6% |
| 3 | 3 | 9.8% | 9.8% | 9.0% | 9.0% |
| 4 | 4 | 17.4% | 17.4% | 18.5% | 18.5% |
| 5 | 5 | 22.8% | 22.8% | 20.7% | 20.7% |
| 6 | 6 | 22.3% | 22.3% | 16.8% | 16.8% |
