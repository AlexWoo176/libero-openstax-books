## 5.3
 
Phân phối mũ

Phân phối mũ thường liên quan đến khoảng thời gian cho đến khi một biến cố cụ thể xảy ra. Ví dụ, khoảng thời gian (bắt đầu từ bây giờ) cho đến khi một trận động đất xảy ra tuân theo phân phối mũ. Các ví dụ khác bao gồm độ dài, tính bằng phút, của các cuộc gọi điện thoại đường dài trong kinh doanh, và khoảng thời gian, tính bằng tháng, mà một bình ắc quy ô tô có thể sử dụng được. Người ta cũng có thể chứng minh rằng giá trị tiền lẻ mà bạn có trong túi quần hoặc ví của mình xấp xỉ tuân theo phân phối mũ.

Các giá trị của một biến ngẫu nhiên theo phân phối mũ xuất hiện theo cách sau. Có ít giá trị lớn hơn và nhiều giá trị nhỏ hơn. Ví dụ, số tiền khách hàng chi tiêu trong một lần đi siêu thị tuân theo một phân phối mũ. Có nhiều người chi tiêu số tiền nhỏ và ít người chi tiêu số tiền lớn hơn.

Các phân phối mũ thường được sử dụng trong các tính toán về độ tin cậy của sản phẩm, hoặc khoảng thời gian một sản phẩm tồn tại.

Cho *X* = khoảng thời gian (tính bằng phút) mà một nhân viên bưu điện dành cho khách hàng của họ. Thời gian này được biết là có phân phối mũ với giá trị trung bình bằng bốn phút.

*X* là một Biến ngẫu nhiên liên tục vì thời gian được đo lường. Cho biết *μ* = 4 phút. Để thực hiện bất kỳ tính toán nào, bạn phải biết *m*, tham số phân rã.

𝑚=1𝜇m=1μm=1μ. Do đó, 𝑚=14=0.25.m=14=0.25.m=14=0.25.

Độ lệch chuẩn, *σ*, giống như số trung bình. *μ* = *σ*

Ký hiệu phân phối là *X* ~ *Exp*(*m*). Do đó, *X* ~ *Exp*(0,25).

Hàm mật độ xác suất là *f*(*x*) = *me*^-*mx*. Số *e* = 2,71828182846... Đây là một con số thường được sử dụng trong toán học. Các máy tính khoa học có phím "*e^x*." Nếu bạn nhập một cho *x*, máy tính sẽ hiển thị giá trị *e*.

Đường cong là:

*f*(*x*) = 0,25*e*^–0,25*x* trong đó *x* ít nhất bằng không và *m* = 0,25.

Ví dụ, *f*(5) = 0,25*e*^(-0,25)(5) = 0,072. Giá trị 0,072 là chiều cao của đường cong khi *x* = 5. Trong [Ví dụ 5.8](5-3-the-exponential-distribution#fs-idm47363760) dưới đây, bạn sẽ học cách tìm xác suất bằng cách sử dụng tham số phân rã.

Đồ thị như sau:

*Hình 
5.22*

Lưu ý đồ thị là một đường cong đi xuống. Khi *x* = 0,

*f*(*x*) = 0,25*e*^(−0,25)(0) = (0,25)(1) = 0,25 = *m*. Giá trị cực đại trên trục *y* là *m*.

Khoảng thời gian vợ chồng mua thiệp kỷ niệm có thể được mô hình hóa bằng phân phối mũ với số trung bình thời gian bằng tám phút. Hãy viết phân phối, nêu hàm mật độ xác suất và vẽ đồ thị phân phối.

#### Bài toán

a. Sử dụng thông tin trong [Ví dụ 5.7](5-3-the-exponential-distribution#fs-idp58220144), hãy tìm xác suất để một nhân viên dành bốn đến năm phút với một khách hàng được chọn ngẫu nhiên.

#### Bài toán

b. Một nửa số khách hàng được phục vụ xong trong vòng bao lâu? (Tìm bách phân vị thứ 50)

#### Bài toán

c. Giá trị nào lớn hơn, số trung bình hay trung vị?

Số ngày trước khi khách du lịch mua vé máy bay có thể được mô hình hóa bằng phân phối mũ với thời gian trung bình bằng 15 ngày. Tìm xác suất để một khách du lịch sẽ mua vé trước ít hơn mười ngày. Một nửa số khách du lịch đợi bao nhiêu ngày?

Yêu cầu mỗi thành viên trong lớp đếm số tiền lẻ họ có trong túi hoặc ví. Giảng viên của bạn sẽ ghi lại số tiền đó bằng đô la và xu. Vẽ biểu đồ histogram của dữ liệu thu thập được từ lớp. Sử dụng năm khoảng. Vẽ một đường cong trơn qua các cột. Đồ thị sẽ trông gần giống như phân phối mũ. Sau đó tính số trung bình.

Gọi *X* = số tiền mà một sinh viên trong lớp của bạn có trong túi hoặc ví của họ.

Phân phối của *X* xấp xỉ phân phối mũ với số trung bình, *μ* = _______ và *m* = _______. Độ lệch chuẩn, *σ* = ________.

Vẽ biểu đồ hàm mũ thích hợp. Bạn nên dán nhãn các trục x và y, tốc độ phân rã và số trung bình. Tô bóng vùng biểu diễn xác suất một sinh viên có ít hơn 0,40 đô la trong túi hoặc ví của họ. (Tô bóng *P*(*x* < 0,40)).

Tính trung bình, một linh kiện máy tính nhất định có tuổi thọ mười năm. Khoảng thời gian linh kiện máy tính đó hoạt động được tuân theo phân phối mũ.

#### Bài toán

a. Xác suất để một linh kiện máy tính hoạt động lâu hơn 7 năm là bao nhiêu?

Trên màn hình chính, nhập e^(-.1*7).

*Hình 
5.25*

#### Bài toán

b. Tính trung bình, năm linh kiện máy tính sẽ hoạt động được bao lâu nếu chúng được sử dụng nối tiếp nhau?

#### Bài toán

c. Tám mươi phần trăm các linh kiện máy tính hoạt động được tối đa bao lâu?

Trên màn hình chính, nhập ln⁡(1–0.80)–0.1ln⁡(1–0.80)–0.1ln(1–0.80)–0.1

#### Bài toán

d. Xác suất để một linh kiện máy tính hoạt động trong khoảng từ chín đến 11 năm là bao nhiêu?

Trên màn hình chính, nhập *e*^(–0,1*9) – *e*^(–0,1*11).

Trung bình, một đôi giày chạy bộ có thể dùng được 18 tháng nếu sử dụng hàng ngày. Khoảng thời gian sử dụng của giày chạy bộ tuân theo phân phối mũ. Xác suất để một đôi giày chạy bộ dùng được hơn 15 tháng là bao nhiêu? Trung bình, sáu đôi giày chạy bộ sẽ dùng được trong bao lâu nếu chúng được sử dụng lần lượt từng đôi một? Tám mươi phần trăm số giày chạy bộ dùng được tối đa trong bao lâu nếu sử dụng hàng ngày?

Giả sử rằng độ dài của một cuộc gọi điện thoại, tính bằng phút, là một biến ngẫu nhiên liên tục tuân theo phân phối mũ với tham số suy giảm 112112112. Nếu một người khác đến bốt điện thoại công cộng ngay trước bạn, hãy tìm xác suất để bạn phải đợi hơn năm phút. Gọi *X* = độ dài của một cuộc gọi điện thoại, tính bằng phút.

#### Bài tập

*m*, *μ*, và *σ* là gì? Xác suất để bạn phải đợi hơn năm phút là _______ .

Giả sử rằng khoảng cách, tính bằng dặm, mà mọi người sẵn sàng đi làm là một biến ngẫu nhiên liên tục tuân theo phân phối mũ với tham số suy giảm 120120120. Gọi *X* = khoảng cách mọi người sẵn sàng đi làm tính bằng dặm. *m*, *μ*, và *σ* là gì? Xác suất để một người sẵn sàng đi làm hơn 25 dặm là bao nhiêu?

Thời gian chờ đợi giữa các biến cố thường được mô hình hóa bằng cách sử dụng phân phối mũ. Ví dụ, giả sử trung bình có 30 khách hàng mỗi giờ đến một cửa hàng và thời gian giữa các lần khách đến tuân theo phân phối mũ.

#### Bài tập

1. Trung bình, bao nhiêu phút trôi qua giữa hai lần đến liên tiếp?
1. Khi cửa hàng mới mở, trung bình mất bao lâu để ba khách hàng đến nơi?
1. Sau khi một khách hàng đến, hãy tìm xác suất để khách hàng tiếp theo đến trong vòng chưa đầy một phút.
1. Sau khi một khách hàng đến, hãy tìm xác suất để khách hàng tiếp theo đến sau hơn năm phút.
1. Bảy mươi phần trăm khách hàng đến trong vòng bao nhiêu phút kể từ khách hàng trước đó?
1. Phân phối mũ có hợp lý cho tình huống này không?
Giả sử rằng trên một đoạn đường cao tốc nhất định, ô tô đi qua với tốc độ trung bình là năm chiếc mỗi phút. Giả sử rằng khoảng thời gian giữa các xe liên tiếp tuân theo phân phối mũ.

1. Trung bình, bao nhiêu giây trôi qua giữa hai chiếc xe liên tiếp?
1. Sau khi một chiếc xe đi qua, trung bình sẽ mất bao lâu để có thêm bảy chiếc xe nữa đi qua?
1. Tìm xác suất để sau khi một chiếc xe đi qua, chiếc xe tiếp theo sẽ đi qua trong vòng 20 giây tới.
1. Tìm xác suất để sau khi một chiếc xe đi qua, chiếc xe tiếp theo sẽ không đi qua trong ít nhất 15 giây nữa.
### Tính không nhớ của phân phối mũ

Trong [Ví dụ 5.7](5-3-the-exponential-distribution#fs-idp58220144), hãy nhớ lại rằng khoảng thời gian giữa các khách hàng tuân theo phân phối mũ với số trung bình là hai phút (*X* ~ *Exp* (0,5)). Giả sử rằng đã năm phút trôi qua kể từ khi khách hàng cuối cùng đến. Vì một khoảng thời gian dài bất thường đã trôi qua, có vẻ như khả năng một khách hàng đến trong phút tiếp theo sẽ cao hơn. Với phân phối mũ, điều này không xảy ra – thời gian chờ đợi thêm cho khách hàng tiếp theo không phụ thuộc vào việc đã bao nhiêu thời gian trôi qua kể từ khi khách hàng trước đó đến. Điều này được gọi là **tính chất không nhớ**. Cụ thể, **tính chất không nhớ** nói rằng

*P* (*X* > *r* + *t* | *X* > *r*) = *P* (*X* > *t*) với mọi *r* ≥ 0 và *t* ≥ 0

Ví dụ, nếu năm phút đã trôi qua kể từ khi khách hàng cuối cùng đến, thì xác suất để hơn một phút nữa trôi qua trước khi khách hàng tiếp theo đến được tính bằng cách sử dụng *r* = 5 và *t* = 1 trong phương trình trên.

*P**X**X**P**X*𝑒(–0.5)⁢(1)e(–0.5)⁢(1)e(–0.5)(1)

*Đây là xác suất tương tự* như xác suất phải đợi hơn một phút để một khách hàng đến sau lần khách hàng trước đó đã đến.

Phân phối mũ thường được sử dụng để mô hình hóa tuổi thọ của một thiết bị điện hoặc cơ khí. Trong [Ví dụ 5.9](5-3-the-exponential-distribution#fs-idp51839440), tuổi thọ của một linh kiện máy tính nhất định có phân phối mũ với trung bình là mười năm (*X* ~ *Exp*(0,1)). **Tính chất không nhớ** cho biết rằng việc biết những gì đã xảy ra trong quá khứ không có ảnh hưởng gì đến các xác suất trong tương lai. Trong trường hợp này, điều đó có nghĩa là một linh kiện cũ không có khả năng bị hỏng tại bất kỳ thời điểm cụ thể nào cao hơn so với một linh kiện hoàn toàn mới. Nói cách khác, linh kiện vẫn tốt như mới cho đến khi nó đột ngột bị hỏng. Ví dụ, nếu linh kiện đã hoạt động được mười năm, thì xác suất để nó hoạt động thêm bảy năm nữa là *P*(*X* > 17|*X* > 10) = *P*(*X* > 7) = 0,4966.

Tham khảo [Ví dụ 5.7](5-3-the-exponential-distribution#fs-idp58220144), nơi thời gian một nhân viên bưu điện dành cho một khách hàng có phân phối mũ với trung bình là bốn phút. Giả sử một khách hàng đã dành bốn phút với nhân viên bưu điện. Xác suất để khách hàng đó dành thêm ít nhất ba phút nữa với nhân viên bưu điện là bao nhiêu?

Tham số phân rã của *X* là *m* = 141414
= 0,25, vì vậy *X* ∼ *Exp*(0,25).

Hàm phân phối tích lũy là *P*(*X* < *x*) = 1 – *e*^–0,25*x*.

Chúng ta muốn tìm *P*(*X* > 7|*X* > 4). **Tính chất không nhớ** cho biết rằng *P*(*X* > 7|*X* > 4) = *P* (*X* > 3), vì vậy chúng ta chỉ cần tìm xác suất để một khách hàng dành hơn ba phút với nhân viên bưu điện.

Đây là *P*(*X* > 3) = 1 – *P* (*X* < 3) = 1 – (1 – *e*^–0,25⋅3) = *e*^–0,75 ≈ 0,4724.

*Hình 
5.31*

1–(1–e^(–0,25*3)) = e^(–0,25*3).

Giả sử tuổi thọ của một bóng đèn tuân theo phân phối mũ với tuổi thọ trung bình là tám năm. Nếu một bóng đèn đã hoạt động được 12 năm, hãy tìm xác suất để nó hoạt động tổng cộng hơn 19 năm.

### Mối quan hệ giữa phân phối Poisson và phân phối mũ

Có một mối quan hệ thú vị giữa phân phối mũ và phân phối Poisson. Giả sử thời gian trôi qua giữa hai biến cố liên tiếp tuân theo phân phối mũ với trung bình là *μ* đơn vị thời gian. Cũng giả định rằng các khoảng thời gian này là độc lập, nghĩa là thời gian giữa các biến cố không bị ảnh hưởng bởi thời gian giữa các biến cố trước đó. Nếu các giả định này đúng, thì số lượng biến cố trên mỗi đơn vị thời gian tuân theo phân phối Poisson với trung bình *λ* = 1/μ. Nhắc lại từ chương về [Biến ngẫu nhiên rời rạc](4-introduction) rằng nếu *X* có phân phối Poisson với trung bình *λ*, thì 𝑃⁡(𝑋=𝑘)=𝜆𝑘⁢𝑒−𝜆𝑘!P⁡(X=k)=λk⁢e−λk!P(X=k)=λke−λk!. Ngược lại, nếu số lượng biến cố trên mỗi đơn vị thời gian tuân theo phân phối Poisson, thì khoảng thời gian giữa các biến cố tuân theo phân phối mũ. (*k*! = *k**(*k*–1*)(*k*–2)*(*k*–3)*…3*2*1)

Giả sử *X* có phân phối Poisson với trung bình *λ*. Tính *P*(*X* = *k*) bằng cách nhập 2^nd, `VARS(DISTR)`, `C: poissonpdf(*λ*, *k*)`. Để tính *P*(*X* ≤ *k*), nhập 2^nd, `VARS (DISTR)`, `D:poissoncdf(*λ*, *k*)`.

Tại một đồn cảnh sát ở một thành phố lớn, các cuộc gọi đến với tốc độ trung bình là bốn cuộc gọi mỗi phút. Giả sử thời gian trôi qua từ cuộc gọi này đến cuộc gọi tiếp theo có phân phối mũ. Lưu ý rằng chúng ta chỉ quan tâm đến tốc độ các cuộc gọi đến và chúng ta bỏ qua thời gian dành cho việc đàm thoại. Chúng ta cũng phải giả định rằng thời gian giữa các cuộc gọi là độc lập. Điều này có nghĩa là một khoảng trễ đặc biệt dài giữa hai cuộc gọi không có nghĩa là sẽ có thời gian chờ ngắn hơn cho cuộc gọi tiếp theo. Sau đó, chúng ta có thể suy ra rằng tổng số cuộc gọi nhận được trong một khoảng thời gian tuân theo phân phối Poisson.

#### Bài tập

1. Tìm thời gian trung bình giữa hai cuộc gọi liên tiếp.
1. Tìm xác suất để sau khi nhận được một cuộc gọi, cuộc gọi tiếp theo xảy ra trong vòng chưa đầy mười giây.
1. Tìm xác suất để có đúng năm cuộc gọi xảy ra trong vòng một phút.
1. Tìm xác suất để có ít hơn năm cuộc gọi xảy ra trong vòng một phút.
1. Tìm xác suất để có hơn 40 cuộc gọi xảy ra trong khoảng thời gian tám phút.
Tại một thành phố nhỏ, số vụ tai nạn ô tô xảy ra theo phân phối Poisson với trung bình là ba vụ mỗi tuần.

1. Tính xác suất để có tối đa 2 vụ tai nạn xảy ra trong bất kỳ tuần nào.
1. Xác suất để có ít nhất hai tuần giữa bất kỳ 2 vụ tai nạn là bao nhiêu?
