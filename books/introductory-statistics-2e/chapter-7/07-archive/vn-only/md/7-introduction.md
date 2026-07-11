*Hình 
7.1
 
Nếu bạn muốn tìm ra phân phối của số tiền lẻ mà mọi người mang theo trong túi, sử dụng định lý giới hạn trung tâm và giả định mẫu của bạn đủ lớn, bạn sẽ thấy rằng phân phối đó là phân phối chuẩn và có hình chuông. (nguồn: sửa đổi từ tác phẩm “american coins” của Paula R. Lively/ Flickr, CC BY 2.0)*

Đến cuối chương này, sinh viên sẽ có thể:

- Nhận biết các bài toán về định lý giới hạn trung tâm.
- Phân loại các bài toán đố liên tục theo phân phối của chúng.
- Áp dụng và diễn giải định lý giới hạn trung tâm cho số trung bình.
- Áp dụng và diễn giải định lý giới hạn trung tâm cho tổng.
## Giới thiệu

Tại sao chúng ta lại quan tâm nhiều đến số trung bình? Có hai lý do: chúng cung cấp cho chúng ta một cơ sở chung để so sánh và chúng dễ tính toán. Trong chương này, bạn sẽ nghiên cứu về số trung bình và **định lý giới hạn trung tâm**.

Định lý giới hạn trung tâm (viết tắt là clt) là một trong những ý tưởng mạnh mẽ và hữu ích nhất trong toàn bộ thống kê học. Có hai dạng thay thế của định lý này, và cả hai đều liên quan đến việc lấy các mẫu hữu hạn có kích thước *n* từ một quần thể có số trung bình đã biết, *μ*, và độ lệch chuẩn đã biết, *σ*. Dạng thay thế thứ nhất cho biết rằng nếu chúng ta thu thập các mẫu có kích thước *n* với một "*n* đủ lớn", tính số trung bình của mỗi mẫu và tạo một biểu đồ histogram của các số trung bình đó, thì biểu đồ thu được sẽ có xu hướng mang hình dạng chuông chuẩn xấp xỉ. Dạng thay thế thứ hai cho biết rằng nếu chúng ta tiếp tục thu thập các mẫu có kích thước *n* "đủ lớn", tính tổng của mỗi mẫu và tạo một biểu đồ histogram, thì biểu đồ thu được cũng sẽ có xu hướng mang hình dạng chuông chuẩn.

Kích thước mẫu *n* cần thiết để được coi là "đủ lớn" phụ thuộc vào quần thể gốc mà các mẫu được lấy ra (kích thước mẫu nên ít nhất là 30 hoặc dữ liệu nên đến từ một phân phối chuẩn). Nếu quần thể gốc không gần với phân phối chuẩn, thì cần nhiều quan sát hơn để các số trung bình hoặc tổng của mẫu có phân phối chuẩn. **Việc lấy mẫu được thực hiện có hoàn lại.**

Thật khó để nói quá về tầm quan trọng của định lý giới hạn trung tâm trong lý thuyết thống kê. Việc biết rằng dữ liệu, ngay cả khi phân phối của nó không phải là phân phối chuẩn, vẫn hoạt động theo một cách có thể dự đoán được là một công cụ mạnh mẽ.

Giả sử tám bạn trong số các bạn gieo một con xúc xắc cân đối mười lần, bảy bạn gieo hai con xúc xắc cân đối mười lần, chín bạn gieo năm con xúc xắc cân đối mười lần, và 11 bạn gieo mười con xúc xắc cân đối mười lần.

Mỗi lần một người gieo nhiều hơn một con xúc xắc, họ sẽ tính Trung bình mẫu của các mặt hiển thị. Ví dụ, một người có thể gieo năm con xúc xắc cân đối và nhận được 2, 2, 3, 4, 6 trong một lần gieo.

Số trung bình là 

2 + 2 + 3 + 4 + 6

5

2 + 2 + 3 + 4 + 6

5

 = 3.4. Con số 3.4 là một số trung bình khi gieo năm con xúc xắc cân đối. Người này sẽ gieo năm con xúc xắc đó thêm chín lần nữa và tính thêm chín số trung bình nữa để có tổng cộng mười số trung bình.

Giảng viên của bạn sẽ phát xúc xắc cho một vài người. Hãy gieo xúc xắc của bạn mười lần. Với mỗi lần gieo, hãy ghi lại các mặt và tìm số trung bình. Làm tròn đến 0.5 gần nhất.

Giảng viên của bạn (và có thể là cả bạn) sẽ tạo ra một biểu đồ (có thể là biểu đồ histogram) cho một con xúc xắc, một biểu đồ cho hai con xúc xắc, một biểu đồ cho năm con xúc xắc và một biểu đồ cho mười con xúc xắc. Vì "số trung bình" khi bạn gieo một con xúc xắc chỉ là mặt trên con xúc xắc đó, các **số trung bình** này dường như đại diện cho phân phối nào?

**Vẽ biểu đồ cho các số trung bình sử dụng hai con xúc xắc.** Các số trung bình mẫu có cho thấy bất kỳ loại mô hình nào không?

**Vẽ biểu đồ cho các số trung bình sử dụng năm con xúc xắc.** Bạn có thấy mô hình nào xuất hiện không?

**Cuối cùng, vẽ biểu đồ cho các số trung bình sử dụng mười con xúc xắc.** Bạn có thấy mô hình nào trên biểu đồ không? Bạn có thể kết luận gì khi tăng số lượng xúc xắc?

Khi số lượng xúc xắc được gieo tăng từ một lên hai, năm và mười, những điều sau đây đang xảy ra:

1. Số trung bình của các số trung bình mẫu vẫn xấp xỉ như cũ.
1. Độ phân tán của các số trung bình mẫu (độ lệch chuẩn của các số trung bình mẫu) trở nên nhỏ hơn.
1. Biểu đồ trông có vẻ dốc hơn và mỏng hơn.
Bạn vừa chứng minh định lý giới hạn trung tâm (clt).

Định lý giới hạn trung tâm cho bạn biết rằng khi bạn tăng số lượng xúc xắc, **các số trung bình mẫu có xu hướng tiến về một phân phối chuẩn (phân phối mẫu).**
