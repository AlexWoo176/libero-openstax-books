*Figure 
7.1
 
If you want to figure out the distribution of the change people carry in their pockets, using the central limit theorem and assuming your sample is large enough, you will find that the  distribution is normal and bell-shaped. (credit: modification of work “american coins” by Paula R. Lively/ Flickr, CC BY 2.0)*

*Hình 
7.1
 
Nếu bạn muốn tìm ra phân phối của số tiền lẻ mà mọi người mang theo trong túi, sử dụng định lý giới hạn trung tâm và giả định mẫu của bạn đủ lớn, bạn sẽ thấy rằng phân phối đó là phân phối chuẩn và có hình chuông. (nguồn: sửa đổi từ tác phẩm “american coins” của Paula R. Lively/ Flickr, CC BY 2.0)*

By the end of this chapter, the student should be able to:

Đến cuối chương này, sinh viên sẽ có thể:

- Recognize central limit theorem problems.
- Nhận biết các bài toán về định lý giới hạn trung tâm.
- Classify continuous word problems by their distributions.
- Phân loại các bài toán đố liên tục theo phân phối của chúng.
- Apply and interpret the central limit theorem for means.
- Áp dụng và diễn giải định lý giới hạn trung tâm cho số trung bình.
- Apply and interpret the central limit theorem for sums.
- Áp dụng và diễn giải định lý giới hạn trung tâm cho tổng.
## Introduction

## Giới thiệu

Why are we so concerned with means? Two reasons are: they give us a middle ground for comparison, and they are easy to calculate. In this chapter, you will study means and the **central limit theorem**.

Tại sao chúng ta lại quan tâm nhiều đến số trung bình? Có hai lý do: chúng cung cấp cho chúng ta một cơ sở chung để so sánh và chúng dễ tính toán. Trong chương này, bạn sẽ nghiên cứu về số trung bình và **định lý giới hạn trung tâm**.

The central limit theorem (clt for short) is one of the most powerful and useful ideas in all of statistics. There are two alternative forms of the theorem, and both alternatives are concerned with drawing finite samples size *n* from a population with a known mean, *μ*, and a known standard deviation, *σ*. The first alternative says that if we collect samples of size *n* with a "large enough *n*," calculate each sample's mean, and create a histogram of those means, then the resulting histogram will tend to have an approximate normal bell shape. The second alternative says that if we again collect samples of size *n* that are "large enough," calculate the sum of each sample and create a histogram, then the resulting histogram will again tend to have a normal bell-shape.

Định lý giới hạn trung tâm (viết tắt là clt) là một trong những ý tưởng mạnh mẽ và hữu ích nhất trong toàn bộ thống kê học. Có hai dạng thay thế của định lý này, và cả hai đều liên quan đến việc lấy các mẫu hữu hạn có kích thước *n* từ một quần thể có số trung bình đã biết, *μ*, và độ lệch chuẩn đã biết, *σ*. Dạng thay thế thứ nhất cho biết rằng nếu chúng ta thu thập các mẫu có kích thước *n* với một "*n* đủ lớn", tính số trung bình của mỗi mẫu và tạo một biểu đồ histogram của các số trung bình đó, thì biểu đồ thu được sẽ có xu hướng mang hình dạng chuông chuẩn xấp xỉ. Dạng thay thế thứ hai cho biết rằng nếu chúng ta tiếp tục thu thập các mẫu có kích thước *n* "đủ lớn", tính tổng của mỗi mẫu và tạo một biểu đồ histogram, thì biểu đồ thu được cũng sẽ có xu hướng mang hình dạng chuông chuẩn.

The size of the sample, *n*, that is required in order to be "large enough" depends on the original population from which the samples are drawn (the sample size should be at least 30 or the data should come from a normal distribution). If the original population is far from normal, then more observations are needed for the sample means or sums to be normal. **Sampling is done with replacement.**

Kích thước mẫu *n* cần thiết để được coi là "đủ lớn" phụ thuộc vào quần thể gốc mà các mẫu được lấy ra (kích thước mẫu nên ít nhất là 30 hoặc dữ liệu nên đến từ một phân phối chuẩn). Nếu quần thể gốc không gần với phân phối chuẩn, thì cần nhiều quan sát hơn để các số trung bình hoặc tổng của mẫu có phân phối chuẩn. **Việc lấy mẫu được thực hiện có hoàn lại.**

It would be difficult to overstate the importance of the central limit theorem in statistical theory. Knowing that data, even if its distribution is not normal, behaves in a predictable way is a powerful tool.

Thật khó để nói quá về tầm quan trọng của định lý giới hạn trung tâm trong lý thuyết thống kê. Việc biết rằng dữ liệu, ngay cả khi phân phối của nó không phải là phân phối chuẩn, vẫn hoạt động theo một cách có thể dự đoán được là một công cụ mạnh mẽ.

Suppose eight of you roll one fair die ten times, seven of you roll two fair dice ten times, nine of you roll five fair dice ten times, and 11 of you roll ten fair dice ten times.

Giả sử tám bạn trong số các bạn gieo một con xúc xắc cân đối mười lần, bảy bạn gieo hai con xúc xắc cân đối mười lần, chín bạn gieo năm con xúc xắc cân đối mười lần, và 11 bạn gieo mười con xúc xắc cân đối mười lần.

Each time a person rolls more than one die, they calculate the sample mean of the faces showing. For example, one person might roll five fair dice and get 2, 2, 3, 4, 6 on one roll.

Mỗi lần một người gieo nhiều hơn một con xúc xắc, họ sẽ tính Trung bình mẫu của các mặt hiển thị. Ví dụ, một người có thể gieo năm con xúc xắc cân đối và nhận được 2, 2, 3, 4, 6 trong một lần gieo.

The mean is 

2 + 2 + 3 + 4 + 6

5

2 + 2 + 3 + 4 + 6

5

 = 3.4. The 3.4 is one mean when five fair dice are rolled. This same person would roll the five dice nine more times and calculate nine more means for a total of ten means.

Số trung bình là 

2 + 2 + 3 + 4 + 6

5

2 + 2 + 3 + 4 + 6

5

 = 3.4. Con số 3.4 là một số trung bình khi gieo năm con xúc xắc cân đối. Người này sẽ gieo năm con xúc xắc đó thêm chín lần nữa và tính thêm chín số trung bình nữa để có tổng cộng mười số trung bình.

Your instructor will pass out the dice to several people. Roll your dice ten times. For each roll, record the faces, and find the mean. Round to the nearest 0.5.

Giảng viên của bạn sẽ phát xúc xắc cho một vài người. Hãy gieo xúc xắc của bạn mười lần. Với mỗi lần gieo, hãy ghi lại các mặt và tìm số trung bình. Làm tròn đến 0.5 gần nhất.

Your instructor (and possibly you) will produce one graph (it might be a histogram) for one die, one graph for two dice, one graph for five dice, and one graph for ten dice. Since the "mean" when you roll one die is just the face on the die, what distribution do these **means** appear to be representing?

Giảng viên của bạn (và có thể là cả bạn) sẽ tạo ra một biểu đồ (có thể là biểu đồ histogram) cho một con xúc xắc, một biểu đồ cho hai con xúc xắc, một biểu đồ cho năm con xúc xắc và một biểu đồ cho mười con xúc xắc. Vì "số trung bình" khi bạn gieo một con xúc xắc chỉ là mặt trên con xúc xắc đó, các **số trung bình** này dường như đại diện cho phân phối nào?

**Draw the graph for the means using two dice.** Do the sample means show any kind of pattern?

**Vẽ biểu đồ cho các số trung bình sử dụng hai con xúc xắc.** Các số trung bình mẫu có cho thấy bất kỳ loại mô hình nào không?

**Draw the graph for the means using five dice.** Do you see any pattern emerging?

**Vẽ biểu đồ cho các số trung bình sử dụng năm con xúc xắc.** Bạn có thấy mô hình nào xuất hiện không?

**Finally, draw the graph for the means using ten dice.** Do you see any pattern to the graph? What can you conclude as you increase the number of dice?

**Cuối cùng, vẽ biểu đồ cho các số trung bình sử dụng mười con xúc xắc.** Bạn có thấy mô hình nào trên biểu đồ không? Bạn có thể kết luận gì khi tăng số lượng xúc xắc?

As the number of dice rolled increases from one to two to five to ten, the following is happening:

Khi số lượng xúc xắc được gieo tăng từ một lên hai, năm và mười, những điều sau đây đang xảy ra:

1. The mean of the sample means remains approximately the same.
1. Số trung bình của các số trung bình mẫu vẫn xấp xỉ như cũ.
1. The spread of the sample means (the standard deviation of the sample means) gets smaller.
1. Độ phân tán của các số trung bình mẫu (độ lệch chuẩn của các số trung bình mẫu) trở nên nhỏ hơn.
1. The graph appears steeper and thinner.
1. Biểu đồ trông có vẻ dốc hơn và mỏng hơn.
You have just demonstrated the central limit theorem (clt).

Bạn vừa chứng minh định lý giới hạn trung tâm (clt).

The central limit theorem tells you that as you increase the number of dice, **the sample means  tend toward a normal distribution (the sampling distribution).**

Định lý giới hạn trung tâm cho bạn biết rằng khi bạn tăng số lượng xúc xắc, **các số trung bình mẫu có xu hướng tiến về một phân phối chuẩn (phân phối mẫu).**
