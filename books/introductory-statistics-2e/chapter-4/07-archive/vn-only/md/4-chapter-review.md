## Ôn tập chương

Các đặc điểm của một hàm phân phối xác suất (PDF) cho một biến ngẫu nhiên rời rạc như sau:

1. Mỗi xác suất nằm trong khoảng từ không đến một, bao gồm cả hai đầu mút (*bao gồm cả hai đầu mút* nghĩa là tính cả số không và số một).
1. Tổng các xác suất bằng một.
Giá trị kỳ vọng, hay số trung bình, của một biến ngẫu nhiên rời rạc dự đoán các kết quả dài hạn của một phép thử thống kê đã được lặp lại nhiều lần. Độ lệch chuẩn của một phân phối xác suất được sử dụng để đo lường sự biến thiên của các kết quả có thể xảy ra.

Một phép thử thống kê có thể được phân loại là một phép thử nhị thức nếu các điều kiện sau được đáp ứng:

1. Có một số lượng phép thử cố định, *n*.
1. Chỉ có hai kết quả có thể xảy ra, được gọi là "thành công" và "thất bại" cho mỗi phép thử. Chữ cái *p* ký hiệu xác suất thành công trong một phép thử và *q* ký hiệu xác suất thất bại trong một phép thử.
1. *n* phép thử này là các biến cố độc lập và được lặp lại trong các điều kiện giống hệt nhau.
Các kết quả của một phép thử nhị thức phù hợp với một phân phối xác suất nhị thức. Biến ngẫu nhiên *X* = số lần thành công thu được trong *n* phép thử độc lập. Số trung bình của *X* có thể được tính bằng công thức *μ* = *np*, và độ lệch chuẩn được cho bởi công thức σ =  √𝑛⁢𝑝⁢𝑞 n⁢p⁢q npq.

Có ba đặc điểm của một phép thử hình học:

1. Có một hoặc nhiều phép thử Bernoulli với tất cả đều là thất bại ngoại trừ phép thử cuối cùng, đó là một thành công.
1. Về lý thuyết, số lượng phép thử có thể kéo dài mãi mãi. Phải có ít nhất một phép thử.
1. Xác suất *p* của một thành công và xác suất *q* của một thất bại là như nhau cho mỗi phép thử.
Trong một phép thử hình học, định nghĩa biến ngẫu nhiên rời rạc *X* là số lần thử độc lập cho đến lần thành công đầu tiên. Chúng ta nói rằng X có một phân phối hình học và viết *X* ~ *G*(*p*) trong đó *p* là xác suất thành công trong một phép thử đơn lẻ.

Số trung bình của phân phối hình học *X* ~ *G*(*p*) là *μ* = 1𝑝1p1p và độ lệch chuẩn là 𝜎⁢√(1−𝑝)𝑝2σ⁢(1−p)p2σ(1−p)p2 = √1𝑝⁢(1𝑝−1)1p⁢(1p−1)1p(1p−1).

Một Thí nghiệm siêu hình học là một phép thử thống kê với các tính chất sau:

1. Bạn lấy các mẫu từ hai nhóm.
1. Bạn quan tâm đến một nhóm quan tâm, được gọi là nhóm thứ nhất.
1. Bạn lấy mẫu không hoàn lại từ các nhóm đã kết hợp.
1. Mỗi lần chọn không độc lập, vì việc lấy mẫu là không hoàn lại.
1. Bạn không làm việc với các phép thử Bernoulli.
Các kết quả của một phép thử siêu bội tuân theo phân phối xác suất siêu bội. Biến ngẫu nhiên *X* = số lượng các phần tử từ nhóm quan tâm. Phân phối của *X* được ký hiệu là *X* ~ *H*(*r*, *b*, *n*), trong đó *r* = kích thước của nhóm quan tâm (nhóm thứ nhất), *b* = kích thước của nhóm thứ hai, và *n* = kích thước của mẫu được chọn. Theo đó 
*n* ≤ *r* + *b*. Số trung bình của *X* là *μ* = 𝑛⁢𝑟𝑟 + 𝑏n⁢rr + bnrr + b và độ lệch chuẩn là *σ* = √𝑟⁢𝑏⁢𝑛⁡(𝑟 + 𝑏 − 𝑛)(𝑟 + 𝑏)2 (𝑟 + 𝑏−1)r⁢b⁢n⁡(r + b − n)(r + b)2 (r + b−1)rbn(r + b − n)(r + b)2 (r + b−1).

Một Phân phối xác suất Poisson của một biến ngẫu nhiên rời rạc đưa ra xác suất của một số lượng các biến cố xảy ra trong một khoảng thời gian hoặc không gian cố định, nếu các biến cố này xảy ra với một tốc độ trung bình đã biết và độc lập với thời gian kể từ biến cố cuối cùng. Phân phối Poisson có thể được sử dụng để xấp xỉ phân phối nhị thức, nếu xác suất thành công là "nhỏ" (nhỏ hơn hoặc bằng 0,05) và số lượng phép thử là "lớn" (lớn hơn hoặc bằng 20).
