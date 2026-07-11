*Figure 
12.1
 
Linear regression and correlation can help you determine if an auto mechanic’s salary is related to his work experience. (credit: modification of work “USPS commissions local repair-shop for some needed work on its older trucks” by Joshua Rothhaas/ Flickr, CC BY 2.0)*

*Hình 
12.1
 
Hồi quy tuyến tính và tương quan có thể giúp bạn xác định liệu mức lương của một thợ cơ khí ô tô có liên quan đến kinh nghiệm làm việc của anh ta hay không. (nguồn ảnh: chỉnh sửa từ tác phẩm “USPS commissions local repair-shop for some needed work on its older trucks” của Joshua Rothhaas/ Flickr, CC BY 2.0)*

By the end of this chapter, the student should be able to:

Đến cuối chương này, sinh viên sẽ có thể:

- Discuss basic ideas of linear regression and correlation.
- Thảo luận về các ý tưởng cơ bản của hồi quy tuyến tính và tương quan.
- Create and interpret a line of best fit.
- Tạo và diễn giải đường phù hợp nhất.
- Calculate and interpret the correlation coefficient.
- Tính toán và diễn giải hệ số tương quan.
- Calculate and interpret outliers.
- Tính toán và diễn giải các giá trị ngoại lệ.
## Introduction

## Giới thiệu

Professionals often want to know how two or more numeric variables are related. For example, is there a relationship between the grade on the second math exam a student takes and the grade on the final exam? If there is a relationship, what is the relationship and how strong is it?

Các chuyên gia thường muốn biết hai hoặc nhiều biến định lượng có liên quan với nhau như thế nào. Ví dụ, liệu có mối quan hệ nào giữa điểm số bài kiểm tra toán thứ hai và điểm thi cuối kỳ của một sinh viên hay không? Nếu có mối quan hệ, thì đó là mối quan hệ gì và mức độ mạnh yếu ra sao?

In another example, your income may be determined by your education, your profession, your years of experience, and your ability. The amount you pay a repair person for labor is often determined by an initial amount plus an hourly fee.

Trong một ví dụ khác, thu nhập của bạn có thể được quyết định bởi trình độ học vấn, nghề nghiệp, số năm kinh nghiệm và năng lực của bạn. Số tiền bạn trả cho thợ sửa chữa tiền công thường được xác định bằng một khoản phí ban đầu cộng với phí theo giờ.

The type of data described in the examples is bivariate data — "bi" for two variables. In reality, statisticians use multivariate data, meaning many variables.

Loại dữ liệu được mô tả trong các ví dụ trên là dữ liệu Hai biến — "bi" nghĩa là hai biến. Trong thực tế, các nhà thống kê sử dụng dữ liệu Nhiều biến, nghĩa là nhiều biến số.

In this chapter, you will be studying the simplest form of regression, "linear regression" with one independent variable (*x*). This involves data that fits a line in two dimensions. You will also study correlation which measures how strong the relationship is.

Trong chương này, bạn sẽ nghiên cứu dạng đơn giản nhất của hồi quy, "hồi quy tuyến tính" với một biến độc lập (*x*). Điều này liên quan đến dữ liệu phù hợp với một đường thẳng trong không gian hai chiều. Bạn cũng sẽ nghiên cứu tương quan, thước đo mức độ mạnh yếu của mối quan hệ.
