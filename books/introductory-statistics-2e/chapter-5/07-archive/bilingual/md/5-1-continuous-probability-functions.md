## 5.1
 
Continuous Probability Functions

## 5.1
 
Các hàm xác suất liên tục

We begin by defining a continuous probability density function. We use the function notation *f*(*x*). Intermediate algebra may have been your first formal introduction to functions. In the study of probability, the functions we study are special. We define the function *f*(*x*) so that the area between it and the x-axis is equal to a probability. Since the maximum probability is one, the maximum area is also one. **For continuous probability distributions, PROBABILITY = AREA.**

Chúng ta bắt đầu bằng việc định nghĩa hàm mật độ xác suất liên tục. Chúng ta sử dụng ký hiệu hàm *f*(*x*). Đại số trung cấp có lẽ là lần giới thiệu chính thức đầu tiên của bạn về các hàm số. Trong nghiên cứu về xác suất, các hàm mà chúng ta nghiên cứu là những hàm đặc biệt. Chúng ta định nghĩa hàm *f*(*x*) sao cho diện tích giữa nó và trục x bằng một xác suất. Vì xác suất tối đa là một, nên diện tích tối đa cũng là một. **Đối với các phân phối xác suất liên tục, XÁC SUẤT = DIỆN TÍCH.**

Consider the function
*f*(*x*) = 120120120 for 0 ≤ *x* ≤ 20. *x* = a real number. The graph of
*f*(*x*) = 120120120 is a horizontal line. However, since 0 ≤ *x* ≤ 20, *f*(*x*) is restricted to the portion between *x* = 0 and *x* = 20, inclusive.

Xét hàm số
*f*(*x*) = 120120120 với 0 ≤ *x* ≤ 20. *x* = một số thực. Đồ thị của
*f*(*x*) = 120120120 là một đường nằm ngang. Tuy nhiên, vì 0 ≤ *x* ≤ 20, *f*(*x*) bị giới hạn trong phần giữa *x* = 0 và *x* = 20, bao gồm cả hai đầu mút.

*Figure 
5.5*

*Hình 
5.5*

*f*(*x*) = 120120120 **for** 0 ≤ *x* ≤ 20.

*f*(*x*) = 120120120 **với** 0 ≤ *x* ≤ 20.

The graph of *f*(*x*) = 120120120 is a horizontal line segment when 0 ≤ *x* ≤ 20.

Đồ thị của *f*(*x*) = 120120120 là một đoạn thẳng nằm ngang khi 0 ≤ *x* ≤ 20.

The area between *f*(*x*) = 120120120 where 0 ≤ *x* ≤ 20 and the *x*-axis is the area of a rectangle with base = 20 and height = 120120120.

Diện tích giữa *f*(*x*) = 120120120 với 0 ≤ *x* ≤ 20 và trục *x* là diện tích của một hình chữ nhật có đáy = 20 và chiều cao = 120120120.

**Suppose we want to find the area between *f(**x*) = 120120120 and the *x*-axis where 0 < *x* < 2.**

**Giả sử chúng ta muốn tìm diện tích giữa *f(**x*) = 120120120 và trục *x* với 0 < *x* < 2.**

*Figure 
5.6*

*Hình 
5.6*

area of a rectangle = (base)(height).

diện tích hình chữ nhật = (đáy)(chiều cao).

The area corresponds to a probability. The probability that *x* is between zero and two is 0.1, which can be written mathematically as *P*(0 < *x* < 2) = *P*(*x* < 2) = 0.1.

Diện tích tương ứng với một xác suất. Xác suất để *x* nằm giữa không và hai là 0,1, có thể được viết dưới dạng toán học là *P*(0 < *x* < 2) = *P*(*x* < 2) = 0,1.

**Suppose we want to find the area between *f*(*x*) = 120120120 and the *x*-axis where 4 < *x* < 15.**

**Giả sử chúng ta muốn tìm diện tích giữa *f*(*x*) = 120120120 và trục *x* với 4 < *x* < 15.**

*Figure 
5.7*

*Hình 
5.7*

The area corresponds to the probability *P*(4 < *x* < 15) = 0.55.

Diện tích tương ứng với xác suất *P*(4 < *x* < 15) = 0,55.

Suppose we want to find *P*(*x* = 15). On an x-y graph, *x* = 15 is a vertical line. A vertical line has no width (or zero width). Therefore,  *P*(*x* = 15) = (base)(height) = (0)(120)(120)(120) = 0

Giả sử chúng ta muốn tìm *P*(*x* = 15). Trên đồ thị x-y, *x* = 15 là một đường thẳng đứng. Một đường thẳng đứng không có chiều rộng (hoặc chiều rộng bằng không). Do đó, *P*(*x* = 15) = (đáy)(chiều cao) = (0)(120)(120)(120) = 0

*Figure 
5.8*

*Hình 
5.8*

*P*(*X* ≤ *x*), which can also be written as *P*(*X* < *x*) for continuous distributions, is called the cumulative distribution function or CDF. Notice the "less than or equal to" symbol. We can also use the CDF to calculate *P*(*X* > *x*). The CDF gives "area to the left" and *P*(*X* > *x*) gives "area to the right." We calculate *P*(*X* > *x*) for continuous distributions as follows: *P*(*X* > *x*) = 1 – *P* (*X* < *x*).

*P*(*X* ≤ *x*), cũng có thể được viết là *P*(*X* < *x*) đối với các phân phối liên tục, được gọi là hàm phân phối tích lũy hay CDF. Hãy chú ý đến ký hiệu "nhỏ hơn hoặc bằng". Chúng ta cũng có thể sử dụng CDF để tính *P*(*X* > *x*). CDF cho biết "diện tích về phía bên trái" và *P*(*X* > *x*) cho biết "diện tích về phía bên phải". Chúng ta tính *P*(*X* > *x*) cho các phân phối liên tục như sau: *P*(*X* > *x*) = 1 – *P* (*X* < *x*).

*Figure 
5.9*

*Hình 
5.9*

Label the graph with
*f*(*x*) and *x*. Scale the *x* and *y* axes with the maximum *x* and *y* values. *f*(*x*) = 120120120, 0 ≤ *x* ≤ 20.

Gán nhãn cho biểu đồ với *f*(*x*) và *x*. Chia tỷ lệ các trục *x* và *y* với các giá trị *x* và *y* tối đa. *f*(*x*) = 120120120, 0 ≤ *x* ≤ 20.

To calculate the probability that *x* is between two values, look at the following graph. Shade the region between *x* = 2.3 and *x* = 12.7. Then calculate the shaded area of a rectangle.

Để tính xác suất mà *x* nằm giữa hai giá trị, hãy nhìn vào biểu đồ sau đây. Tô bóng vùng nằm giữa *x* = 2,3 và *x* = 12,7. Sau đó tính diện tích phần được tô bóng của hình chữ nhật.

*Figure 
5.10*

*Hình 
5.10*

Consider the function *f*(*x*) = 181818
 for 0 ≤ *x* ≤ 8. Draw the graph of *f*(*x*) and find *P*(2.5 < *x* < 7.5).

Xét hàm số *f*(*x*) = 181818 cho 0 ≤ *x* ≤ 8. Vẽ biểu đồ của *f*(*x*) và tìm *P*(2,5 < *x* < 7,5).
