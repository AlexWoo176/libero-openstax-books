## 2.4
 
Biểu đồ hộp

Sơ đồ hộp (còn được gọi là Sơ đồ hộp và nhánh hoặc biểu đồ hộp và râu) cung cấp một hình ảnh đồ họa tốt về sự tập trung của dữ liệu. Chúng cũng cho thấy các giá trị cực đoan cách xa phần lớn dữ liệu như thế nào. Một biểu đồ hộp được xây dựng từ năm giá trị: giá trị nhỏ nhất, tứ phân vị thứ nhất, trung vị, tứ phân vị thứ ba và giá trị lớn nhất. Chúng ta sử dụng các giá trị này để so sánh các giá trị dữ liệu khác gần với chúng như thế nào.

Để xây dựng một biểu đồ hộp, hãy sử dụng một trục số nằm ngang hoặc thẳng đứng và một hộp hình chữ nhật. Các giá trị dữ liệu nhỏ nhất và lớn nhất đánh dấu các điểm cuối của trục. Tứ phân vị thứ nhất đánh dấu một đầu của hộp và tứ phân vị thứ ba đánh dấu đầu kia của hộp. Khoảng **50 phần trăm dữ liệu ở giữa nằm bên trong hộp.** Các "râu" kéo dài từ các đầu của hộp đến các giá trị dữ liệu nhỏ nhất và lớn nhất. Trung vị hoặc tứ phân vị thứ hai có thể nằm giữa tứ phân vị thứ nhất và thứ ba, hoặc nó có thể là một trong hai, hoặc cả hai. Biểu đồ hộp cung cấp một hình ảnh nhanh chóng và tốt về dữ liệu.

Bạn có thể bắt gặp các biểu đồ hộp và râu có các dấu chấm đánh dấu các giá trị ngoại lệ. Trong những trường hợp đó, các râu không kéo dài đến các giá trị nhỏ nhất và lớn nhất.

Hãy xem xét lại tập dữ liệu này.

1; 
1; 
2; 
2; 
4; 
6; 
6,8; 
7,2; 
8; 
8,3; 
9; 
10; 
10; 
11,5

Tứ phân vị thứ nhất là hai, trung vị là bảy và tứ phân vị thứ ba là chín. Giá trị nhỏ nhất là một và giá trị lớn nhất là 11,5. Hình ảnh sau đây cho thấy biểu đồ hộp đã được xây dựng.

Xem hướng dẫn sử dụng máy tính trên [trang web TI](http://education.ti.com/educationportal/sites/US/sectionHome/support.html) hoặc trong phần phụ lục.

*Hình 
2.11*

Hai râu kéo dài từ tứ phân vị thứ nhất đến giá trị nhỏ nhất và từ tứ phân vị thứ ba đến giá trị lớn nhất. Trung vị được hiển thị bằng một đường nét đứt.

Điều quan trọng là phải bắt đầu biểu đồ hộp với một **trục số có chia tỷ lệ**. Nếu không, biểu đồ hộp có thể không hữu ích.

Dữ liệu sau đây là chiều cao của 40 sinh viên trong một lớp thống kê học.

59; 
60; 
61; 
62; 
62; 
63; 
63; 
64; 
64; 
64; 
65; 
65; 
65; 
65; 
65; 
65; 
65; 
65; 
65; 
66; 
66; 
67; 
67; 
68; 
68; 
69; 
70; 
70; 
70; 
70; 
70; 
71; 
71; 
72; 
72; 
73; 
74; 
74; 
75; 
77

Xây dựng một biểu đồ hộp với các thuộc tính sau; hướng dẫn sử dụng máy tính cho các giá trị nhỏ nhất và lớn nhất cũng như các tứ phân vị được trình bày sau ví dụ này.

- Giá trị tối thiểu = 59
- Giá trị tối đa = 77
- *Q*1: Tứ phân vị thứ nhất = 64,5
- *Q*2: Tứ phân vị thứ hai hoặc trung vị = 66
- *Q*3: Tứ phân vị thứ ba = 70
*Hình 
2.12*

1. Mỗi phần tư có khoảng 25% dữ liệu.
1. Độ phân tán của bốn phần tư lần lượt là 64.5 – 59 = 5.5 (phần tư thứ nhất), 66 – 64,5 = 1,5 (phần tư thứ hai), 70 – 66 = 4 (phần tư thứ ba), và 77 – 70 = 7 (phần tư thứ tư). Do đó, phần tư thứ hai có độ phân tán nhỏ nhất và phần tư thứ tư có độ phân tán lớn nhất.
1. Khoảng biến thiên = giá trị tối đa – giá trị tối thiểu = 77 – 59 = 18
1. Khoảng tứ phân vị: *IQR* = *Q*3 – *Q*1 = 70 – 64,5 = 5,5.
1. Khoảng 59–65 có hơn 25% dữ liệu, vì vậy nó chứa nhiều dữ liệu hơn khoảng từ 66 đến 70, vốn chỉ có 25% dữ liệu.
1. 50% ở giữa (một nửa ở giữa) của dữ liệu có phạm vi là 5,5 inch.
Để tìm giá trị nhỏ nhất, giá trị lớn nhất và các tứ phân vị:

Nhập dữ liệu vào trình chỉnh sửa danh sách (Nhấn `STAT 1:EDIT`). Nếu bạn cần xóa danh sách, hãy di chuyển mũi tên lên tên `L1`, nhấn CLEAR, sau đó di chuyển mũi tên xuống.

Nhập các giá trị dữ liệu vào danh sách `L1`.

Nhấn STAT và di chuyển mũi tên đến CALC. Nhấn `1:1-VarStats`. Nhập `L1`.

Nhấn ENTER.

Sử dụng các phím mũi tên lên và xuống để cuộn.

Giá trị nhỏ nhất = 59.

Giá trị lớn nhất = 77.

*Q*_1: Tứ phân vị thứ nhất = 64,5.

*Q*_2: Tứ phân vị thứ hai hoặc trung vị = 66.

*Q*_3: Tứ phân vị thứ ba = 70.

Để xây dựng biểu đồ hộp:

Nhấn `4:Plotsoff`. Nhấn ENTER.

Di chuyển mũi tên xuống dưới và sau đó sử dụng phím mũi tên phải để đi đến hình thứ năm, đó là biểu đồ hộp. Nhấn ENTER.

Di chuyển mũi tên xuống `Xlist: Press 2nd 1 for L1`

Di chuyển mũi tên xuống `Freq: Press ALPHA`. Nhấn 1.

Nhấn Zoom. `Press 9: ZoomStat`.

Nhấn TRACE và sử dụng các phím mũi tên để kiểm tra biểu đồ hộp.

Dữ liệu sau đây là số trang của 40 cuốn sách trên một kệ. Hãy xây dựng một biểu đồ hộp bằng máy tính đồ thị và nêu khoảng tứ phân vị.

136; 
140; 
178; 
190; 
205; 
215; 
217; 
218; 
232; 
234; 
240; 
255; 
270; 
275; 
290; 
301; 
303; 
315; 
317; 
318; 
326; 
333; 
343; 
349; 
360; 
369; 
377; 
388; 
391; 
392; 
398; 
400; 
402; 
405; 
408; 
422; 
429; 
450; 
475; 
512

Đối với một số tập dữ liệu, một vài giá trị trong số giá trị lớn nhất, giá trị nhỏ nhất, tứ phân vị thứ nhất, trung vị và tứ phân vị thứ ba có thể trùng nhau. Ví dụ, bạn có thể có một tập dữ liệu mà trong đó trung vị và tứ phân vị thứ ba bằng nhau. Trong trường hợp này, sơ đồ sẽ không có đường chấm bên trong hộp hiển thị trung vị. Phía bên phải của hộp sẽ hiển thị cả tứ phân vị thứ ba và trung vị. Ví dụ, nếu giá trị nhỏ nhất và tứ phân vị thứ nhất đều bằng một, trung vị và tứ phân vị thứ ba đều bằng năm, và giá trị lớn nhất là bảy, biểu đồ hộp sẽ trông như sau:

*Hình 
2.13*

Trong trường hợp này, ít nhất 25% các giá trị bằng một. Hai mươi lăm phần trăm các giá trị nằm trong khoảng từ một đến năm, bao gồm cả hai giá trị này. Ít nhất 25% các giá trị bằng năm. 25% các giá trị cao nhất nằm trong khoảng từ năm đến bảy, bao gồm cả hai giá trị này.

Điểm kiểm tra của một lớp thống kê đại học học vào ban ngày là:

99; 
56; 
78; 
55,5; 
32; 
90; 
80; 
81; 
56; 
59; 
45; 
77; 
84,5; 
84; 
70; 
72; 
68; 
32; 
79; 
90

Điểm kiểm tra của một lớp thống kê đại học được tổ chức vào buổi tối là:

98; 
78; 
68; 
83; 
81; 
89; 
88; 
76; 
65; 
45; 
98; 
90; 
80; 
84,5; 
85; 
79; 
78; 
98; 
90; 
79; 
81; 
25,5

#### Bài toán

1. Tìm các giá trị nhỏ nhất và lớn nhất, trung vị, cùng tứ phân vị thứ nhất và thứ ba cho lớp ban ngày.
1. Tìm các giá trị nhỏ nhất và lớn nhất, trung vị, cùng tứ phân vị thứ nhất và thứ ba cho lớp ban đêm.
1. Đối với mỗi tập dữ liệu, tỷ lệ phần trăm dữ liệu nằm giữa giá trị nhỏ nhất và tứ phân vị thứ nhất là bao nhiêu? Giữa tứ phân vị thứ nhất và trung vị? Giữa trung vị và tứ phân vị thứ ba? Giữa tứ phân vị thứ ba và giá trị lớn nhất? Tỷ lệ phần trăm dữ liệu nằm giữa tứ phân vị thứ nhất và giá trị lớn nhất là bao nhiêu?
1. Tạo một biểu đồ hộp cho mỗi tập dữ liệu. Sử dụng một trục số cho cả hai biểu đồ hộp.
1. Biểu đồ hộp nào có độ phân tán rộng nhất cho 50% dữ liệu ở giữa (dữ liệu nằm giữa tứ phân vị thứ nhất và thứ ba)? Điều này có ý nghĩa gì đối với tập dữ liệu đó khi so sánh với tập dữ liệu còn lại?
Tập dữ liệu sau đây hiển thị chiều cao tính bằng inch của các nam sinh trong một lớp học gồm 40 học sinh.

66; 66; 67; 67; 68; 68; 68; 68; 68; 69; 69; 69; 70; 71; 72; 72; 72; 73; 73; 74

Tập dữ liệu sau đây hiển thị chiều cao tính bằng inch của các nữ sinh trong một lớp học gồm 40 học sinh.

61; 61; 62; 62; 63; 63; 63; 65; 65; 65; 66; 66; 66; 67; 68; 68; 68; 69; 69; 69

Hãy xây dựng một biểu đồ hộp bằng máy tính đồ họa cho mỗi tập dữ liệu, và cho biết biểu đồ hộp nào có độ phân tán rộng hơn cho 50% dữ liệu ở giữa.

Vẽ biểu đồ hộp và râu cho các giá trị dữ liệu được hiển thị.

10; 10; 10; 15; 35; 75; 90; 95; 100; 175; 420; 490; 515; 515; 790

Năm con số được sử dụng để tạo một biểu đồ hộp và râu là:

- Min: 10
- *Q*_1: 15
- Med: 95
- *Q*_3: 490
- Max: 790
Biểu đồ sau đây hiển thị biểu đồ hộp và râu.

*Hình 
2.15*

Hãy thực hiện theo các bước bạn đã sử dụng để vẽ biểu đồ hộp và râu cho các giá trị dữ liệu được hiển thị.

0; 5; 5; 15; 30; 30; 45; 50; 50; 60; 75; 110; 140; 240; 330
