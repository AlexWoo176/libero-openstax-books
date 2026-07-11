## 13.1
 
One-Way ANOVA

## 13.1
 
Phân tích phương sai một chiều

The purpose of a one-way ANOVA test is to determine the existence of a statistically significant difference among several group means. The test actually uses variances to help determine if the means are equal or not. In order to perform a one-way ANOVA test, there are five basic **assumptions** to be fulfilled:

Mục đích của kiểm định phân tích phương sai một chiều (ANOVA) là xác định sự tồn tại của một khác biệt có ý nghĩa thống kê giữa các số trung bình của nhiều nhóm. Kiểm định này thực tế sử dụng phương sai để giúp xác định xem các số trung bình có bằng nhau hay không. Để thực hiện kiểm định ANOVA một chiều, cần phải thỏa mãn năm **giả định** cơ bản:

1. Each population from which a sample is taken is assumed to be normal.
1. Mỗi quần thể mà từ đó một mẫu được lấy ra được giả định là có phân phối chuẩn.
1. All samples are randomly selected and independent.
1. Tất cả các mẫu đều được chọn ngẫu nhiên và độc lập.
1. The populations are assumed to have equal standard deviations **(or variances)**.
1. Các quần thể được giả định là có các độ lệch chuẩn bằng nhau **(hoặc các phương sai bằng nhau)**.
1. The factor is a categorical variable.
1. Nhân tố là một biến phân loại.
1. The response is a numerical variable.
1. Biến phản hồi là một biến định lượng.
### The Null and Alternative Hypotheses

### Giả thuyết không và đối thuyết

The null hypothesis is simply that all the group population means are the same. The alternative hypothesis is that at least one pair of means is different. For example, if there are *k* groups:

Giả thuyết không đơn giản là tất cả các số trung bình quần thể của các nhóm đều bằng nhau. Đối thuyết là có ít nhất một cặp số trung bình khác nhau. Ví dụ, nếu có *k* nhóm:

*H_0*: *μ*_1 = *μ*_2 = *μ*_3 = ... = *μ_k*

*H_0*: *μ*_1 = *μ*_2 = *μ*_3 = ... = *μ_k*

*H_a*: At least two of the group means *μ*_1, *μ*_2, *μ*_3, ..., *μ_k* are not equal. That is, *μ_i* ≠ *μ_j* for some *i* ≠ *j*.

*H_a*: Ít nhất hai trong số các số trung bình nhóm *μ*_1, *μ*_2, *μ*_3, ..., *μ_k* không bằng nhau. Nghĩa là, *μ_i* ≠ *μ_j* với một số *i* ≠ *j*.

The graphs, a set of box plots representing the distribution of values with the group means indicated by a horizontal line through the box, help in the understanding of the hypothesis test. In the first graph (blue box plots), *H_0*: *μ_1* = *μ_2* = *μ_3* and the three populations have the same distribution if the null hypothesis is true.  The variance of the combined data is approximately the same as the variance of each of the populations.

Các biểu đồ, một tập hợp các biểu đồ hộp đại diện cho sự phân phối của các giá trị với các số trung bình nhóm được biểu thị bằng một đường nằm ngang xuyên qua hộp, giúp hiểu rõ hơn về kiểm định giả thuyết. Trong biểu đồ đầu tiên (các biểu đồ hộp màu xanh dương), *H_0*: *μ_1* = *μ_2* = *μ_3* và ba quần thể có cùng sự phân phối nếu giả thuyết không là đúng. Phương sai của dữ liệu kết hợp xấp xỉ bằng phương sai của từng quần thể.

If the null hypothesis is false, then the variance of the combined data is larger which is caused by the different means as shown in the second graph (green box plots).

Nếu giả thuyết không sai, thì phương sai của dữ liệu kết hợp sẽ lớn hơn, điều này gây ra bởi các số trung bình khác nhau như được hiển thị trong biểu đồ thứ hai (các biểu đồ hộp màu xanh lá cây).

*Figure 
13.2
 
(a) *H_0* is true. All means are the same; the differences are due to random variation. (b) *H_0* is not true. The means are not all the same; the differences are too large to be due to random variation.*

*Hình 
13.2
 
(a) *H_0* là đúng. Tất cả các số trung bình đều bằng nhau; các khác biệt là do sự biến thiên ngẫu nhiên. (b) *H_0* là không đúng. Các số trung bình không hoàn toàn bằng nhau; các khác biệt quá lớn để có thể là do sự biến thiên ngẫu nhiên.*
