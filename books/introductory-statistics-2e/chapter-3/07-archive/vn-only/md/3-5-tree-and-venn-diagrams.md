## 3.5
 
Sơ đồ cây và sơ đồ Venn

Đôi khi, khi các bài toán xác suất trở nên phức tạp, việc vẽ đồ thị cho tình huống đó có thể hữu ích. Sơ đồ cây và sơ đồ Venn là hai công cụ có thể được sử dụng để trực quan hóa và giải quyết các xác suất có điều kiện.

### Sơ đồ cây

Biểu đồ cây là một loại đồ thị đặc biệt được sử dụng để xác định các kết quả của một phép thử. Nó bao gồm các "nhánh" được dán nhãn bằng tần số hoặc xác suất. Sơ đồ cây có thể giúp một số bài toán xác suất trở nên dễ hình dung và giải quyết hơn. Ví dụ sau đây minh họa cách sử dụng sơ đồ cây.

Trong một chiếc bình, có 11 quả bóng. Ba quả bóng màu đỏ (*R*) và tám quả bóng màu xanh (*B*). Lấy hai quả bóng, mỗi lần một quả, **có hoàn lại**. "Có hoàn lại" nghĩa là bạn đặt quả bóng đầu tiên trở lại bình trước khi chọn quả bóng thứ hai. Sơ đồ cây sử dụng tần số hiển thị tất cả các kết quả có thể xảy ra như sau.

*Hình 
3.2
 
Tổng = 64 + 24 + 24 + 9 = 121*

Tập hợp các nhánh đầu tiên đại diện cho lần lấy thứ nhất. Tập hợp các nhánh thứ hai đại diện cho lần lấy thứ hai. Mỗi kết quả đều riêng biệt. Trên thực tế, chúng ta có thể liệt kê từng quả bóng đỏ là *R*1, *R*2, và *R*3 và từng quả bóng xanh là *B*1, *B*2, *B*3, *B*4, *B*5, *B*6, *B*7, và *B*8. Khi đó, chín kết quả *RR* có thể được viết là:

*R*1*R*1; 
*R*1*R*2; 
*R*1*R*3; 
*R*2*R*1; 
*R*2*R*2; 
*R*2*R*3; 
*R*3*R*1; 
*R*3*R*2; 
*R*3*R*3

Các kết quả khác cũng tương tự.

Có tổng cộng 11 quả bóng trong bình. Lấy hai quả bóng, mỗi lần một quả, có hoàn lại. Có 11(11) = 121 kết quả, đây là kích thước của Không gian mẫu.

#### Bài toán

a. Liệt kê 24 kết quả *BR*: *B*1*R*1, *B*1*R*2, *B*1*R*3, ...

b. Sử dụng sơ đồ cây, tính *P*(*RR*).

c. Sử dụng sơ đồ cây, tính *P*(*RB* hoặc *BR*).

d. Sử dụng sơ đồ cây, tính *P*(*R* ở lần rút thứ nhất và *B* ở lần rút thứ hai).

e. Sử dụng sơ đồ cây, tính *P*(*R* ở lần rút thứ hai với điều kiện *B* ở lần rút thứ nhất).

f. Sử dụng sơ đồ cây, tính *P*(*BB*).

g. Sử dụng sơ đồ cây, tính *P*(*B* ở lần rút thứ hai với điều kiện *R* ở lần rút thứ nhất).

Trong một bộ bài tiêu chuẩn, có 52 lá bài. 12 lá là lá hình (biến cố *F*) và 40 lá không phải lá hình (biến cố *N*). Rút hai lá bài, mỗi lần một lá, có hoàn lại. Tất cả các kết quả có thể xảy ra được hiển thị trong sơ đồ cây dưới dạng tần số. Sử dụng sơ đồ cây, hãy tính *P*(*FF*).

*Hình 
3.3*

Một chiếc bình có ba viên bi đỏ và tám viên bi xanh. Rút hai viên bi, mỗi lần một viên, lần này là không hoàn lại, từ chiếc bình. **"Không hoàn lại"** có nghĩa là bạn không bỏ viên bi đầu tiên trở lại trước khi chọn viên bi thứ hai. Dưới đây là sơ đồ cây cho tình huống này. Các nhánh được dán nhãn bằng xác suất thay vì tần số. Các con số ở cuối các nhánh được tính bằng cách nhân các con số trên hai nhánh tương ứng, ví dụ, (311)⁢(210)=6110(311)⁢(210)=6110(311)(210)=6110.

*Hình 
3.4
 
Tổng = 56+24+24+6110=110110=156+24+24+6110=110110=156+24+24+6110=110110=1*

Nếu bạn rút được một viên bi đỏ ở lần rút đầu tiên từ ba khả năng có thể rút được bi đỏ, thì còn lại hai viên bi đỏ để rút ở lần rút thứ hai. Bạn không bỏ lại hoặc thay thế viên bi đầu tiên sau khi đã rút nó. Bạn rút **không hoàn lại**, vì vậy ở lần rút thứ hai, còn lại mười viên bi trong bình.

Tính các xác suất sau đây bằng cách sử dụng sơ đồ cây.

#### Bài toán

a. () = ________

b. Điền vào chỗ trống:

*P*(*RB* HOẶC *BR*) = (311)⁢(810)⁢ + (___)(___) = ⁢48110(311)⁢(810)⁢ + (___)(___) = ⁢48110(311)(810) + (___)(___) = 48110

c. *P*(*R* ở lần 2|*B* ở lần 1) =

d. Điền vào chỗ trống.

*P*(*R* ở lần 1 VÀ *B* ở lần 2) = *P*(*RB*) = (___)(___) = 241102411024110

e. Tìm *P*(*BB*).

f. Tìm *P*(*B* ở lần 2|*R* ở lần 1).

Nếu chúng ta đang sử dụng các xác suất, chúng ta có thể dán nhãn sơ đồ cây theo cách tổng quát sau đây.

- *P*(*R*|*R*) ở đây có nghĩa là *P*(*R* ở lần 2|*R* ở lần 1)
- *P*(*B*|*R*) ở đây có nghĩa là *P*(*B* ở lần 2|*R* ở lần 1)
- *P*(*R*|*B*) ở đây có nghĩa là *P*(*R* ở lần 2|*B* ở lần 1)
- *P*(*B*|*B*) ở đây có nghĩa là *P*(*B* ở lần 2|*B* ở lần 1)
Trong một bộ bài tiêu chuẩn, có 52 lá bài. Mười hai lá bài là lá hình (*F*) và 40 lá bài không phải là lá hình (*N*). Rút hai lá bài, mỗi lần một lá, không hoàn lại. Sơ đồ cây được dán nhãn với tất cả các xác suất có thể xảy ra.

*Hình 
3.5*

1. Tìm *P*(*FN* HOẶC *NF*).
1. Tìm *P*(*N*|*F*).
1. Tìm *P*(tối đa một lá bài hình).

Gợi ý: "Tối đa một lá bài hình" nghĩa là không có hoặc có một lá bài hình.
1. Tìm *P*(ít nhất một lá bài hình).

Gợi ý: "Ít nhất một lá bài hình" nghĩa là có một hoặc hai lá bài hình.
Một đàn mèo con sẵn sàng để nhận nuôi tại Hội Nhân đạo có bốn con mèo mướp và năm con mèo đen. Một gia đình đến và chọn ngẫu nhiên hai con mèo (không hoàn lại) để nhận nuôi.

#### Bài toán

1. Xác suất để cả hai chú mèo con đều là mèo mướp là bao nhiêu?

a.(12)⁢(12)(12)⁢(12)(12)(12) b.(49)⁢(49)(49)⁢(49)(49)(49) c.(49)⁢(38)(49)⁢(38)(49)(38) d.(49)⁢(59)(49)⁢(59)(49)(59)
1. Xác suất để chọn được mỗi loại màu một chú mèo con là bao nhiêu?

a.(49)⁢(59)(49)⁢(59)(49)(59) b.(49)⁢(58)(49)⁢(58)(49)(58) c.(49)⁢(59)+(59)⁢(49)(49)⁢(59)+(59)⁢(49)(49)(59)+(59)(49)	d.(49)⁢(58)+(59)⁢(48)(49)⁢(58)+(59)⁢(48)(49)(58)+(59)(48)
1. Xác suất để chọn được một chú mèo mướp làm chú mèo con thứ hai khi chú mèo con đầu tiên được chọn là mèo đen là bao nhiêu?
1. Xác suất chọn được hai chú mèo con cùng màu là bao nhiêu?
Giả sử có bốn quả bóng đỏ và ba quả bóng vàng trong một chiếc hộp. Hai quả bóng được rút ra từ hộp mà không hoàn lại. Xác suất để chọn được mỗi màu một quả bóng là bao nhiêu?

### Sơ đồ Venn

Một Biểu đồ Venn là một hình ảnh biểu diễn các kết quả của một phép thử. Nó thường bao gồm một chiếc hộp đại diện cho không gian mẫu S cùng với các hình tròn hoặc hình bầu dục. Các hình tròn hoặc hình bầu dục đại diện cho các biến cố.

Giả sử một phép thử có các kết quả 1, 2, 3, ... , 12 trong đó mỗi kết quả có cơ hội xảy ra như nhau. Gọi biến cố *A* = {1, 2, 3, 4, 5, 6} và biến cố *B* = {6, 7, 8, 9}. Khi đó *A* VÀ *B* = {6} và *A* HOẶC *B* = {1, 2, 3, 4, 5, 6, 7, 8, 9}. Sơ đồ Venn như sau:

*Hình 
3.6*

Giả sử một phép thử có các kết quả đen, trắng, đỏ, cam, vàng, xanh lá, xanh dương và tím, trong đó mỗi kết quả có cơ hội xảy ra như nhau. Gọi biến cố *C* = {xanh lá, xanh dương, tím} và biến cố *P* = {đỏ, vàng, xanh dương}. Khi đó *C* VÀ *P* = {xanh dương} và *C* HOẶC *P* = {xanh lá, xanh dương, tím, đỏ, vàng}. Hãy vẽ một sơ đồ Venn biểu diễn tình huống này.

Gieo hai đồng xu cân đối. Gọi A = mặt ngửa xuất hiện ở đồng xu thứ nhất. Gọi B = mặt ngửa xuất hiện ở đồng xu thứ hai. Khi đó A = {HT, HH} và B = {TH, HH}. Do đó, A VÀ B = {HH}. A HOẶC B = {HT, HH, TH}.

Không gian mẫu khi bạn gieo hai đồng xu cân đối là *X* = {*HH*, *HT*, *TH*, *TT*}. Kết quả *HH* KHÔNG nằm trong *A* CŨNG KHÔNG nằm trong *B*. Sơ đồ Venn như sau:

*Hình 
3.7*

Gieo một con xúc xắc cân đối, sáu mặt. Gọi *A* = số chấm xuất hiện là số nguyên tố. Gọi *B* = số chấm xuất hiện là số lẻ. Khi đó *A* = {2, 3, 5} và *B* = {1, 3, 5}. Do đó, *A* VÀ *B* = {3, 5}. *A* HOẶC *B* = {1, 2, 3, 5}. Không gian mẫu cho việc gieo một con xúc xắc cân đối là *S* = {1, 2, 3, 4, 5, 6}. Hãy vẽ sơ đồ Venn biểu diễn tình huống này.

**Bốn mươi phần trăm** sinh viên tại một trường đại học địa phương tham gia một câu lạc bộ và **50%** làm việc bán thời gian. **Năm phần trăm** sinh viên làm việc bán thời gian và tham gia một câu lạc bộ. Hãy vẽ sơ đồ Venn thể hiện các mối quan hệ này. Gọi *C* = sinh viên tham gia câu lạc bộ và *PT* = sinh viên làm việc bán thời gian.

*Hình 
3.8*

Nếu một sinh viên được chọn ngẫu nhiên, hãy tìm

- xác suất sinh viên đó tham gia một câu lạc bộ. *P*(*C*) = 0.40
- xác suất sinh viên đó làm việc bán thời gian. *P*(*PT*) = 0.50
- xác suất sinh viên đó tham gia một câu lạc bộ VÀ làm việc bán thời gian. *P*(*C* VÀ *PT*) = 0.05
- ****𝑃⁡(𝐶|𝑃⁡𝑇)⁢ = ⁢𝑃⁡(𝐶 AND 𝑃⁡𝑇)𝑃⁡(𝑃⁡𝑇)⁢ = ⁢0.050.50⁢ = ⁢0.1P⁡(C|P⁡T)⁢ = ⁢P⁡(CP⁡T)P⁡(P⁡T)⁢ = ⁢⁢ = ⁢P(C|PT) = P(CPT)P(PT) =  =
- xác suất sinh viên đó tham gia một câu lạc bộ **HOẶC** làm việc bán thời gian. *P*(*C* HOẶC *PT*) = *P*(*C*) + *P*(*PT*) - *P*(*C* VÀ *PT*) = 0.40 + 0.50 - 0.05 = 0.85
Năm mươi phần trăm công nhân tại một nhà máy làm công việc thứ hai, 25% có vợ/chồng cũng đang đi làm, 5% làm công việc thứ hai và có vợ/chồng cũng đang đi làm. Hãy vẽ sơ đồ Venn thể hiện các mối quan hệ này. Gọi *W* = làm công việc thứ hai và *S* = vợ/chồng cũng đi làm.

#### Bài toán

Một người có nhóm máu O và yếu tố Rh âm tính (Rh-) có thể hiến máu cho bất kỳ người nào có bất kỳ nhóm máu nào. Bốn phần trăm người Mỹ gốc Phi có nhóm máu O và yếu tố Rh âm tính, 5−10% người Mỹ gốc Phi có yếu tố Rh-, và 51% có nhóm máu O.

*Hình 
3.9*

Hình tròn “O” đại diện cho những người Mỹ gốc Phi có nhóm máu O. Hình bầu dục “Rh-“ đại diện cho những người Mỹ gốc Phi có yếu tố Rh-.

Chúng ta sẽ lấy trung bình của 5% và 10% và sử dụng 7,5% làm tỷ lệ phần trăm người Mỹ gốc Phi có yếu tố Rh-. Gọi *O* = người Mỹ gốc Phi có nhóm máu O và *R* = người Mỹ gốc Phi có yếu tố Rh-.

1. *P*(*O*) = ___________
1. *P*(*R*) = ___________
1. *P*(*O* biến cố "và" *R*) = ___________
1. *P*(*O* biến cố "hoặc" *R*) = ____________
1. Trong sơ đồ Venn, hãy mô tả vùng chồng lấp bằng một câu hoàn chỉnh.
1. Trong sơ đồ Venn, hãy mô tả vùng nằm trong hình chữ nhật nhưng ở bên ngoài cả hình tròn và hình bầu dục bằng một câu hoàn chỉnh.
Trong một hiệu sách, xác suất khách hàng mua một cuốn tiểu thuyết là 0,6, và xác suất khách hàng mua một cuốn sách phi hư cấu là 0,4. Giả sử rằng xác suất khách hàng mua cả hai là 0,2.

1. Vẽ một sơ đồ Venn biểu diễn tình huống này.
1. Tìm xác suất để khách hàng mua tiểu thuyết hoặc sách phi hư cấu.
1. Trong sơ đồ Venn, hãy mô tả vùng chồng lấp bằng một câu hoàn chỉnh.
1. Giả sử một số khách hàng chỉ mua đĩa CD. Hãy vẽ một hình bầu dục trong sơ đồ Venn của bạn để biểu diễn biến cố này.
