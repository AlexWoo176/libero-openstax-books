## Chapter Review

## Ôn tập chương

The probability density function (pdf) is used to describe probabilities for continuous random variables. The area under the density curve between two points corresponds to the probability that the variable falls between those two values. In other words, the area under the density curve between points *a* and *b* is equal to *P*(*a* < *x* < *b*). The cumulative distribution function (cdf) gives the probability as an area. If *X* is a continuous random variable, the probability density function (pdf), *f*(*x*), is used to draw the graph of the probability distribution. The total area under the graph of *f*(*x*) is one. The area under the graph of *f*(*x*) and between values *a* and *b* gives the probability *P*(*a* < *x* < *b*).

Hàm mật độ xác suất (pdf) được sử dụng để mô tả các xác suất cho các biến ngẫu nhiên liên tục. Diện tích dưới đường cong mật độ giữa hai điểm tương ứng với xác suất mà biến đó rơi vào giữa hai giá trị đó. Nói cách khác, diện tích dưới đường cong mật độ giữa các điểm *a* và *b* bằng *P*(*a* < *x* < *b*). Hàm phân phối tích lũy (cdf) đưa ra xác suất dưới dạng một diện tích. Nếu *X* là một biến ngẫu nhiên liên tục, hàm mật độ xác suất (pdf), *f*(*x*), được sử dụng để vẽ đồ thị của phân phối xác suất. Tổng diện tích dưới đồ thị của *f*(*x*) bằng một. Diện tích dưới đồ thị của *f*(*x*) và nằm giữa các giá trị *a* và *b* cho ta xác suất *P*(*a* < *x* < *b*).

*Figure 
5.35*

*Hình 
5.35*

The cumulative distribution function (cdf) of *X* is defined by *P* (*X* ≤ *x*). It is a function of *x* that gives the probability that the random variable is less than or equal to *x*.

Hàm phân phối tích lũy (cdf) của *X* được xác định bởi *P* (*X* ≤ *x*). Đây là một hàm của *x* cho biết xác suất mà biến ngẫu nhiên nhỏ hơn hoặc bằng *x*.

If *X* has a uniform distribution where *a* < *x* < *b* or *a* ≤ *x* ≤ *b*, then *X* takes on values between *a* and *b* (may include *a* and *b*). All values *x* are equally likely. We write *X* ∼ *U*(*a*, *b*). The mean of *X* is 𝜇=𝑎+𝑏2μ=a+b2μ=a+b2. The standard deviation of *X* is 𝜎=√(𝑏−𝑎)212σ=(b−a)212σ=(b−a)212. The probability density function of *X* is 𝑓⁡(𝑥)=1𝑏−𝑎f⁡(x)=1b−af(x)=1b−a for *a* ≤ *x* ≤ *b*. The cumulative distribution function of *X* is *P*(*X* ≤ *x*) = 𝑥−𝑎𝑏−𝑎x−ab−ax−ab−a. *X* is continuous.

Nếu *X* có phân phối đều trong đó *a* < *x* < *b* hoặc *a* ≤ *x* ≤ *b*, thì *X* nhận các giá trị giữa *a* và *b* (có thể bao gồm cả *a* và *b*). Tất cả các giá trị *x* đều đồng khả năng. Chúng ta viết *X* ∼ *U*(*a*, *b*). Số trung bình của *X* là 𝜇=𝑎+𝑏2μ=a+b2μ=a+b2. Độ lệch chuẩn của *X* là 𝜎=√(𝑏−𝑎)212σ=(b−a)212σ=(b−a)212. Hàm mật độ xác suất của *X* là 𝑓⁡(𝑥)=1𝑏−𝑎f⁡(x)=1b−af(x)=1b−a với *a* ≤ *x* ≤ *b*. Hàm phân phối tích lũy của *X* là *P*(*X* ≤ *x*) = 𝑥−𝑎𝑏−𝑎x−ab−ax−ab−a. *X* là biến liên tục.

*Figure 
5.36*

*Hình 
5.36*

The probability *P*(*c* < *X* < *d*) may be found by computing the area under *f*(*x*), between *c* and *d*. Since the corresponding area is a rectangle, the area may be found simply by multiplying the width and the height.

Xác suất *P*(*c* < *X* < *d*) có thể được tìm thấy bằng cách tính diện tích dưới *f*(*x*), nằm giữa *c* và *d*. Vì diện tích tương ứng là một hình chữ nhật, diện tích có thể được tìm thấy đơn giản bằng cách nhân chiều rộng với chiều cao.

If *X* has an **exponential distribution** with mean *μ*, then the **decay parameter** is *m* = 1𝜇1μ1μ, and we write *X* ∼ *Exp*(*m*) where *x* ≥ 0 and *m* > 0 . The probability density function of *X* is *f*(*x*) = *me^-mx* (or equivalently 𝑓⁡(𝑥)=1𝜇⁢𝑒−𝑥/𝜇f⁡(x)=1μ⁢e−x/μf(x)=1μe−x/μ. The cumulative distribution function of *X* is *P*(*X* ≤ *x*) = 1 – *e*^–*mx*.

Nếu *X* có **phân phối mũ** với số trung bình *μ*, thì **tham số suy giảm** là *m* = 1𝜇1μ1μ, và chúng ta viết *X* ∼ *Exp*(*m*) trong đó *x* ≥ 0 và *m* > 0. Hàm mật độ xác suất của *X* là *f*(*x*) = *me^-mx* (hoặc tương đương 𝑓⁡(𝑥)=1𝜇⁢𝑒−𝑥/𝜇f⁡(x)=1μ⁢e−x/μf(x)=1μe−x/μ. Hàm phân phối tích lũy của *X* là *P*(*X* ≤ *x*) = 1 – *e*^–*mx*.

The exponential distribution has the **memoryless property**, which says that future probabilities do not depend on any past information. Mathematically, it says that *P*(*X* > *x* + *k*|*X* > *x*) = *P*(*X* > *k*).

Phân phối mũ có **tính chất không nhớ**, nghĩa là các xác suất trong tương lai không phụ thuộc vào bất kỳ thông tin nào trong quá khứ. Về mặt toán học, điều này có nghĩa là *P*(*X* > *x* + *k*|*X* > *x*) = *P*(*X* > *k*).

If *T* represents the waiting time between events, and if *T* ∼ *Exp*(*λ*), then the number of events *X* per unit time follows the Poisson distribution with mean *λ*. The probability density function of *X* is P⁢(𝑋=𝑘)=𝜆𝑘⁢𝑒−𝑘𝑘!P⁢(X=k)=λk⁢e−kk!P(X=k)=λke−kk!. This may be computed using a TI-83, 83+, 84, 84+ calculator with the command poissonpdf(*λ*, *k*). The cumulative distribution function *P*(*X* ≤ *k*) may be computed using the TI-83, 83+,84, 84+ calculator with the command poissoncdf(*λ*, *k*).

Nếu *T* đại diện cho thời gian chờ đợi giữa các biến cố, và nếu *T* ∼ *Exp*(*λ*), thì số lượng biến cố *X* trên mỗi đơn vị thời gian tuân theo phân phối Poisson với số trung bình *λ*. Hàm mật độ xác suất của *X* là P⁢(𝑋=𝑘)=𝜆𝑘⁢𝑒−𝑘𝑘!P⁢(X=k)=λk⁢e−kk!P(X=k)=λke−kk!. Điều này có thể được tính toán bằng máy tính TI-83, 83+, 84, 84+ với lệnh poissonpdf(*λ*, *k*). Hàm phân phối tích lũy *P*(*X* ≤ *k*) có thể được tính toán bằng máy tính TI-83, 83+, 84, 84+ với lệnh poissoncdf(*λ*, *k*).
