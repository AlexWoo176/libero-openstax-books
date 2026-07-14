*Figure 
10.1
 
If you want to test a claim that involves two groups (the types of breakfasts eaten east and west of the Mississippi River) you can use a slightly different technique when conducting a hypothesis test. (credit: modification of work “scrambled egg, toast and home-made berry jam (no added sugar) for breakfast” by Chloe Lim/ Flickr, CC BY 2.0)*

*Hình 
10.1
 
Nếu bạn muốn kiểm định một khẳng định liên quan đến hai nhóm (các loại bữa sáng được ăn ở phía đông và phía tây sông Mississippi), bạn có thể sử dụng một kỹ thuật hơi khác khi thực hiện kiểm định giả thuyết. (nguồn ảnh: chỉnh sửa từ tác phẩm “scrambled egg, toast and home-made berry jam (no added sugar) for breakfast” của Chloe Lim/ Flickr, CC BY 2,0)*

By the end of this chapter, the student should be able to:

Đến cuối chương này, sinh viên sẽ có thể:

- Classify hypothesis tests by type.
- Phân loại các kiểm định giả thuyết theo loại.
- Conduct and interpret hypothesis tests for two population means, population standard deviations known.
- Thực hiện và diễn giải các kiểm định giả thuyết cho hai số trung bình quần thể, khi đã biết độ lệch chuẩn quần thể.
- Conduct and interpret hypothesis tests for two population means, population standard deviations unknown.
- Thực hiện và diễn giải các kiểm định giả thuyết cho hai số trung bình quần thể, khi chưa biết độ lệch chuẩn quần thể.
- Conduct and interpret hypothesis tests for two population proportions.
- Thực hiện và diễn giải các kiểm định giả thuyết cho hai tỷ lệ quần thể.
- Conduct and interpret hypothesis tests for matched or paired samples.
- Thực hiện và diễn giải các kiểm định giả thuyết cho các mẫu ghép đôi hoặc cặp.
## Introduction

## Giới thiệu

Studies often compare two groups. For example, researchers are interested in the effect aspirin has in preventing heart attacks. Over the last few years, newspapers and magazines have reported various aspirin studies involving two groups. Typically, one group is given aspirin and the other group is given a placebo. Then, the heart attack rate is studied over several years.

Các nghiên cứu thường so sánh hai nhóm. Ví dụ, các nhà nghiên cứu quan tâm đến tác dụng của aspirin trong việc ngăn ngừa các cơn đau tim. Trong vài năm qua, báo chí và tạp chí đã đưa tin về nhiều nghiên cứu khác nhau về aspirin liên quan đến hai nhóm. Thông thường, một nhóm được cho dùng aspirin và nhóm kia được cho dùng giả dược. Sau đó, tỷ lệ đau tim được nghiên cứu trong vài năm.

There are other situations that deal with the comparison of two groups. For example, studies compare various diet and exercise programs. Politicians compare the proportion of individuals from different income brackets who might vote for them. Students are interested in whether SAT or GRE preparatory courses really help raise their scores.

Có những tình huống khác liên quan đến việc so sánh hai nhóm. Ví dụ, các nghiên cứu so sánh nhiều chương trình ăn kiêng và tập thể dục khác nhau. Các chính trị gia so sánh tỷ lệ cá nhân từ các nhóm thu nhập khác nhau có thể bỏ phiếu cho họ. Sinh viên quan tâm đến việc liệu các khóa học luyện thi SAT hoặc GRE có thực sự giúp nâng cao điểm số của họ hay không.

You have learned to conduct hypothesis tests on single means and single proportions. You will expand upon that in this chapter. You will compare two means or two proportions to each other. The general procedure is still the same, just expanded.

Bạn đã học cách thực hiện kiểm định giả thuyết cho một số trung bình và một tỷ lệ. Bạn sẽ mở rộng kiến thức đó trong chương này. Bạn sẽ so sánh hai số trung bình hoặc hai tỷ lệ với nhau. Quy trình tổng quát vẫn như cũ, chỉ là được mở rộng hơn.

To compare two means or two proportions, you work with two groups. The groups are classified either as **independent** or matched pairs. Independent groups consist of two samples that are independent, that is, sample values selected from one population are not related in any way to sample values selected from the other population. **Matched pairs** consist of two samples that are dependent. The parameter tested using matched pairs is the population mean. The parameters tested using independent groups are either population means or population proportions.

Để so sánh hai số trung bình hoặc hai tỷ lệ, bạn làm việc với hai nhóm. Các nhóm được phân loại là **độc lập** hoặc Cặp ghép đôi. Các nhóm độc lập bao gồm hai mẫu độc lập, nghĩa là các giá trị mẫu được chọn từ quần thể này không liên quan theo bất kỳ cách nào đến các giá trị mẫu được chọn từ quần thể kia. **Cặp ghép đôi** bao gồm hai mẫu phụ thuộc. Tham số được kiểm định bằng cách sử dụng cặp ghép đôi là số trung bình quần thể. Các tham số được kiểm định bằng cách sử dụng các nhóm độc lập là số trung bình quần thể hoặc tỷ lệ quần thể.

This chapter relies on either a calculator or a computer to calculate the degrees of freedom, the test statistics, and *p*-values. TI-83+ and TI-84 instructions are included as well as the test statistic formulas. When using a TI-83+ or TI-84 calculator, we do not need to separate two population means, independent groups, or population variances unknown into large and small sample sizes. However, most statistical computer software has the ability to differentiate these tests.

Chương này dựa vào máy tính cầm tay hoặc máy tính để bàn để tính bậc tự do, các thống kê kiểm định và *p*-giá trị. Hướng dẫn cho máy tính TI-83+ và TI-84 được bao gồm cùng với các công thức thống kê kiểm định. Khi sử dụng máy tính TI-83+ hoặc TI-84, chúng ta không cần phải tách biệt hai số trung bình quần thể, các nhóm độc lập hoặc các phương sai quần thể chưa biết thành các kích thước mẫu lớn và nhỏ. Tuy nhiên, hầu hết các phần mềm thống kê trên máy tính đều có khả năng phân biệt các kiểm định này.

This chapter deals with the following hypothesis tests:

Chương này đề cập đến các kiểm định giả thuyết sau:

- Test of two population means.
- Kiểm định hai số trung bình quần thể.
- Test of two population proportions.
- Kiểm định hai tỷ lệ quần thể.
- Test of the population mean of differences of measures for paired individuals or objects.
- Kiểm định số trung bình quần thể của các hiệu số đo lường cho các cá nhân hoặc đối tượng được ghép đôi.
