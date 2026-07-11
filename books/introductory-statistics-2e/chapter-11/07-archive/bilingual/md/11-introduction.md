*Figure 
11.1
 
The chi-square distribution can be used to find relationships between two things, like grocery prices at different stores. (credit: modification of work “The first few times I used my Asda 'bag for life' I left the receipts in the bottom of the bag” by Pete/ Flickr, Public domain)*

*Hình 
11.1
 
Phân phối khi bình phương (χ2) có thể được sử dụng để tìm mối quan hệ giữa hai sự vật, như giá hàng tạp hóa tại các cửa hàng khác nhau. (nguồn ảnh: chỉnh sửa từ tác phẩm “The first few times I used my Asda 'bag for life' I left the receipts in the bottom of the bag” của Pete/ Flickr, Phạm vi công cộng)*

By the end of this chapter, the student should be able to:

Đến cuối chương này, sinh viên sẽ có thể:

- Interpret the chi-square probability distribution as the sample size
changes.
- Giải thích phân phối xác suất khi bình phương (χ2) khi kích thước mẫu thay đổi.
- Conduct and interpret chi-square goodness-of-fit hypothesis tests.
- Thực hiện và giải thích các kiểm định giả thuyết về kiểm định mức độ phù hợp khi bình phương (χ2).
- Conduct and interpret chi-square test of independence hypothesis
tests.
- Thực hiện và giải thích các kiểm định giả thuyết về kiểm định tính độc lập khi bình phương (χ2).
- Conduct and interpret chi-square homogeneity hypothesis tests.
- Thực hiện và giải thích các kiểm định giả thuyết về kiểm định tính đồng nhất khi bình phương (χ2).
- Conduct and interpret chi-square single variance hypothesis tests.
- Thực hiện và giải thích các kiểm định giả thuyết về kiểm định một phương sai khi bình phương (χ2).
## Introduction

## Giới thiệu

Have you ever wondered if lottery numbers were evenly distributed or if some numbers occurred with a greater frequency? How about if the types of movies people preferred were different across different age groups? What about if a coffee machine was dispensing approximately the same amount of coffee each time? You could answer these questions by conducting a hypothesis test.

Bạn đã bao giờ tự hỏi liệu các con số xổ số có được phân phối đều hay một số con số xuất hiện với tần suất lớn hơn không? Còn việc các loại phim mà mọi người ưa thích có khác nhau giữa các nhóm tuổi khác nhau thì sao? Hay liệu một chiếc máy pha cà phê có pha ra lượng cà phê xấp xỉ nhau mỗi lần không? Bạn có thể trả lời những câu hỏi này bằng cách thực hiện kiểm định giả thuyết.

You will now study a new distribution, one that is used to determine the answers to such questions. This distribution is called the chi-square distribution.

Bây giờ bạn sẽ nghiên cứu một phân phối mới, một phân phối được sử dụng để xác định câu trả lời cho những câu hỏi như vậy. Phân phối này được gọi là phân phối khi bình phương (χ2).

In this chapter, you will learn the three major applications of the chi-square distribution:

Trong chương này, bạn sẽ tìm hiểu ba ứng dụng chính của phân phối khi bình phương (χ2):

1. the goodness-of-fit test, which determines if data fit a particular distribution, such as in the lottery example
1. kiểm định mức độ phù hợp, giúp xác định xem dữ liệu có phù hợp với một phân phối cụ thể hay không, chẳng hạn như trong ví dụ về xổ số
1. the test of independence, which determines if events are independent, such as in the movie example
1. kiểm định tính độc lập, giúp xác định xem các biến cố có độc lập hay không, chẳng hạn như trong ví dụ về phim ảnh
1. the test of a single variance, which tests variability, such as in the coffee example
1. kiểm định một phương sai, giúp kiểm tra sự biến thiên, chẳng hạn như trong ví dụ về máy pha cà phê
Though the chi-square distribution depends on calculators or computers for most of the calculations, there is a table available (see [Appendix G NOTEs for the TI-83, 83+, 84, 84+ Calculators](g-notes-for-the-ti-83-83-84-84-calculators)). TI-83+ and TI-84 calculator instructions are included in the text.

Mặc dù phân phối khi bình phương (χ2) phụ thuộc vào máy tính hoặc máy tính cầm tay cho hầu hết các phép tính, nhưng vẫn có một bảng tra cứu sẵn (xem [Phụ lục G Lưu ý cho máy tính TI-83, 83+, 84, 84+](g-notes-for-the-ti-83-83-84-84-calculators)). Hướng dẫn sử dụng máy tính TI-83+ và TI-84 được bao gồm trong sách.

Look in the sports section of a newspaper or on the Internet for some sports data (baseball averages, basketball scores, golf tournament scores, football odds, swimming times, and the like). Plot a histogram and a boxplot using your data. See if you can determine a probability distribution that your data fits. Have a discussion with the class about your choice.

Hãy tìm trong mục thể thao của một tờ báo hoặc trên Internet để lấy một số dữ liệu thể thao (trung bình bóng chày, điểm số bóng rổ, điểm số giải đấu gôn, tỷ lệ cược bóng đá, thời gian bơi lội, v.v.). Vẽ biểu đồ histogram và biểu đồ hộp sử dụng dữ liệu của bạn. Xem liệu bạn có thể xác định một phân phối xác suất mà dữ liệu của bạn phù hợp hay không. Hãy thảo luận với cả lớp về lựa chọn của bạn.
