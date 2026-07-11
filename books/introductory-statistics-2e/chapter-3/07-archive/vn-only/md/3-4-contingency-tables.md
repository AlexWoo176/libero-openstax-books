## 3.4
 
Bảng ngẫu nhiên

Một Bảng tiếp liên cung cấp một cách thức trình bày dữ liệu có thể hỗ trợ việc tính toán xác suất. Bảng này giúp xác định các xác suất có điều kiện khá dễ dàng. Bảng hiển thị các giá trị mẫu liên quan đến hai biến khác nhau có thể phụ thuộc hoặc ngẫu nhiên với nhau. Sau này, chúng ta sẽ sử dụng lại các bảng ngẫu nhiên, nhưng theo một cách khác.

#### Bài toán

Giả sử một nghiên cứu về các vi phạm tốc độ và những người lái xe sử dụng điện thoại di động đã tạo ra dữ liệu giả định sau đây:

|  | Vi phạm tốc độ trong năm qua | Không vi phạm tốc độ trong năm qua | Tổng |
| --- | --- | --- | --- |
| Sử dụng điện thoại di động khi lái xe | 25 | 280 | 305 |
| Không sử dụng điện thoại di động khi lái xe | 45 | 405 | 450 |
| Tổng | 70 | 685 | 755 |

Tổng số người trong mẫu là 755. Tổng các hàng là 305 và 450. Tổng các cột là 70 và 685. Lưu ý rằng 305 + 450 = 755 và 70 + 685 = 755.

Tính các xác suất sau đây bằng cách sử dụng bảng.

a. Tìm *P*(Người lái xe là người sử dụng điện thoại di động).

b. Tìm *P*(người lái xe không có vi phạm trong năm qua).

c. Tìm *P*(Người lái xe không có vi phạm trong năm qua VÀ là người sử dụng điện thoại di động).

d. Tìm *P*(Người lái xe là người sử dụng điện thoại di động HOẶC người lái xe không có vi phạm trong năm qua).

e. Tìm *P*(Người lái xe là người sử dụng điện thoại di động VỚI ĐIỀU KIỆN người lái xe có vi phạm trong năm qua).

f. Tìm *P*(Người lái xe không có vi phạm năm ngoái VỚI ĐIỀU KIỆN người lái xe không phải là người sử dụng điện thoại di động)

[Bảng 3.4](3-4-contingency-tables#M05_ch03-tbl002) hiển thị số lượng vận động viên thực hiện giãn cơ trước khi tập luyện và số người bị chấn thương trong năm qua.

|  | Chấn thương trong năm qua | Không chấn thương trong năm qua | Tổng |
| --- | --- | --- | --- |
| Giãn cơ | 55 | 295 | 350 |
| Không giãn cơ | 231 | 219 | 450 |
| Tổng | 286 | 514 | 800 |

1. *P*(vận động viên khởi động trước khi tập luyện) là bao nhiêu?
1. *P*(vận động viên khởi động trước khi tập luyện|không bị chấn thương trong năm qua) là bao nhiêu?
[Bảng 3.5](3-4-contingency-tables#M05_ch03-tbl003) hiển thị một mẫu ngẫu nhiên gồm 100 người đi bộ đường dài và các khu vực đi bộ mà họ ưa thích.

| Giới tính | Đường bờ biển | Gần Hồ và Suối | Trên Đỉnh Núi | Tổng |
| --- | --- | --- | --- | --- |
| Phụ nữ | 18 | 16 |  | 45 |
| Nam giới |  |  | 14 | 55 |
| Tổng |  | 41 |  |  |

#### Bài toán

a. Hoàn thành bảng.

#### Bài toán

b. Các biến cố "là phụ nữ" và "ưa thích bờ biển" có phải là các biến cố độc lập không?

Đặt *F* = là phụ nữ và đặt *C* = ưa thích bờ biển.

1. Tìm *P*(*F* VÀ *C*).
1. Tìm *P*(*F*)*P*(*C*)
Hai con số này có giống nhau không? Nếu có, thì *F* và *C* là độc lập. Nếu không, thì *F* và *C* không độc lập.

#### Bài toán

c. Tìm xác suất một người là nam giới với điều kiện người đó thích đi bộ gần các hồ và suối. Đặt *M* = là nam giới, và đặt *L* = thích đi bộ gần các hồ và suối.

1. Từ nào cho bạn biết đây là một xác suất có điều kiện?
1. Điền vào chỗ trống và tính xác suất: *P*(___|___) = ___.
1. Không gian mẫu cho bài toán này có phải là tất cả 100 người đi bộ đường dài không? Nếu không, nó là gì?
#### Bài toán

d. Tìm xác suất một người là phụ nữ hoặc thích đi bộ trên các đỉnh núi. Đặt *F* = là phụ nữ, và đặt *P* = thích các đỉnh núi.

1. Tìm *P*(*F*).
1. Tìm *P*(*P*).
1. Tìm *P*(*F* và *P*).
1. Tìm *P*(*F* hoặc *P*).
[Bảng 3.7](3-4-contingency-tables#M05_ch03-tbl005) hiển thị một mẫu ngẫu nhiên gồm 200 người đi xe đạp và các tuyến đường họ ưa thích. Đặt *O* = lớn tuổi và *H* = đường đồi núi.

| Nhóm tuổi | Đường ven hồ | Đường đồi | Đường rừng | Tổng |
| --- | --- | --- | --- | --- |
| Trẻ tuổi hơn | 45 | 38 | 27 | 110 |
| Lớn tuổi hơn | 26 | 52 | 12 | 90 |
| Tổng | 71 | 90 | 39 | 200 |

1. Trong nhóm lớn tuổi hơn, xác suất để người đi xe đạp thích con đường đồi núi là bao nhiêu?
1. Các biến cố “lớn tuổi hơn” và “thích con đường đồi núi” có phải là các biến cố độc lập không?
Chú chuột Muddy sống trong một cái lồng có ba cánh cửa. Nếu Muddy đi ra bằng cánh cửa thứ nhất, xác suất nó bị con mèo Alissa bắt được là 151515 và xác suất nó không bị bắt là 454545. Nếu nó đi ra bằng cánh cửa thứ hai, xác suất nó bị Alissa bắt được là 141414 và xác suất nó không bị bắt là 343434. Xác suất Alissa bắt được Muddy khi nó đi ra từ cánh cửa thứ ba là 121212 và xác suất cô ấy không bắt được Muddy là 121212. Khả năng Muddy chọn bất kỳ cánh cửa nào trong ba cánh cửa là đồng khả năng, vì vậy xác suất chọn mỗi cánh cửa là 131313.

| Bị bắt hoặc không | Cửa số một | Cửa số hai | Cửa số ba | Tổng |
| --- | --- | --- | --- | --- |
| Bị bắt | 115115115 | 112112112 | 161616 |  |
| Không bị bắt | 415415415 | 312312312 | 161616 |  |
| Tổng |  |  |  | 1 |

- Mục đầu tiên 115 =(15)⁢(13)115=(15)⁢(13)115 = (15)(13) là *P*(Cửa Một VÀ Bị bắt)
- Mục 415 =(45)⁢(13)415=(45)⁢(13)415=(45)(13) là *P*(Cửa Một VÀ Không bị bắt)
Xác minh các mục còn lại.

#### Bài toán

a. Hoàn thành bảng ngẫu nhiên xác suất. Tính các giá trị cho các tổng. Xác minh rằng giá trị ở góc dưới bên phải là 1.

b. Xác suất để Alissa không bắt được Muddy là bao nhiêu?

c. Xác suất để Muddy chọn Cửa Một HOẶC Cửa Hai với điều kiện Muddy bị Alissa bắt là bao nhiêu?

Anna phải mua một chiếc xe mới. Cô ấy có hai lựa chọn, xe A và xe B. Anna chỉ có thể mua một chiếc xe. Xác suất Anna sẽ mua xe A là 𝑃⁡(𝐴)⁢  = ⁢0.25P⁡(A)⁢ = ⁢0.25P(A) = 0.25, và xác suất Anna sẽ mua xe B là 𝑃⁡(𝐵)⁢  = ⁢0.65P⁡(B)⁢ = ⁢0.65P(B) = 0.65. Hãy tìm:

- 𝑃⁡(𝐴 𝐴⁢𝑁⁢𝐷 𝐵)P⁡(A A⁢N⁢D B)P(A VÀ B)
- 𝑃⁡(𝐴 𝑂⁢𝑅 𝐵)P⁡(A O⁢R B)P(A HOẶC B)
[Bảng 3.10](3-4-contingency-tables#Ch03_M04_tbl007) chứa số lượng tội phạm trên 100.000 dân tại Hoa Kỳ trong khoảng thời gian vài năm.

| Năm | Cướp tài sản | Trộm cắp | Phá hoại | Phương tiện | Tổng |
| --- | --- | --- | --- | --- | --- |
| 1 | 145.7 | 732.1 | 29.7 | 314.7 |  |
| 2 | 133.1 | 717.7 | 29.1 | 259.2 |  |
| 3 | 119.3 | 701 | 27.7 | 239.1 |  |
| 4 | 113.7 | 702.2 | 26.8 | 229.6 |  |
| Tổng |  |  |  |  |  |

#### Bài toán

TỔNG mỗi cột và mỗi hàng. Tổng dữ liệu = 4.520,7

1. Tìm *P*(Năm 2 VÀ Cướp tài sản).
1. Tìm *P*(Năm 3 VÀ Đột nhập).
1. Tìm *P*(Năm 3 HOẶC Đột nhập).
1. Tìm *P*(Năm 4 | Phá hoại).
1. Tìm *P*(Phương tiện | Năm 1).
[Bảng 3.11](3-4-contingency-tables#M05_ch03-tbl009) liên hệ cân nặng và chiều cao của một nhóm cá nhân tham gia vào một nghiên cứu quan sát.

| Cân nặng/Chiều cao | Cao | Trung bình | Thấp | Tổng |
| --- | --- | --- | --- | --- |
| Thừa cân | 18 | 28 | 14 |  |
| Khoảng cân nặng điển hình | 20 | 51 | 28 |  |
| Thiếu cân | 12 | 25 | 9 |  |
| Các tổng |  |  |  |  |

1. Tìm tổng cho mỗi hàng và cột
1. Tìm xác suất để một cá nhân được chọn ngẫu nhiên từ nhóm này là Cao.
1. Tìm xác suất để một cá nhân được chọn ngẫu nhiên từ nhóm này là Thừa cân và Cao.
1. Tìm xác suất để một cá nhân được chọn ngẫu nhiên từ nhóm này là Cao với điều kiện cá nhân đó Thừa cân.
1. Tìm xác suất để một cá nhân được chọn ngẫu nhiên từ nhóm này là Thừa cân với điều kiện cá nhân đó Cao.
1. Tìm xác suất để một cá nhân được chọn ngẫu nhiên từ nhóm này là Cao và Nhẹ cân.
1. Các biến cố Thừa cân và Cao có độc lập không?
