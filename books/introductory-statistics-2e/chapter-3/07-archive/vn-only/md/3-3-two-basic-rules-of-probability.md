## 3.3
 
Hai quy tắc cơ bản của xác suất

Khi tính xác suất, có hai quy tắc cần xem xét để xác định xem hai biến cố là độc lập hay phụ thuộc và liệu chúng có xung khắc hay không.

### Quy tắc nhân

Nếu *A* và *B* là hai biến cố được xác định trên một Không gian mẫu, thì: *P*(*A* VÀ *B*) = *P*(*B*)*P*(*A*|*B*).

*P*(*A*|*B*𝑃⁡(𝐴 AND 𝐵)𝑃⁡(𝐵)P⁡(AB)P⁡(B)P(AB)P(B)

(Xác suất của *A* với điều kiện *B* bằng xác suất của *A* và *B* chia cho xác suất của *B*.)

Nếu *A* và *B* là các biến cố Độc lập, thì *P*(*A*|*B*) = *P*(*A*). Khi đó *P*(*A* VÀ *B*) = *P*(*A*|*B*)*P*(*B*) trở thành *P*(*A* VÀ *B*) = *P*(*A*)*P*(*B*).

### Quy tắc cộng

Nếu *A* và *B* được xác định trên một không gian mẫu, thì: *P*(*A* HOẶC *B*) = *P*(*A*) + *P*(*B*) - *P*(*A* VÀ *B*).

Nếu *A* và *B* là Xung khắc (Loại trừ lẫn nhau), thì *P*(*A* VÀ *B*) = 0. Khi đó *P*(*A* HOẶC *B*) = *P*(*A*) + *P*(*B*) - *P*(*A* VÀ *B*) trở thành *P*(*A* HOẶC *B*) = *P*(*A*) + *P*(*B*).

Klaus đang cố gắng chọn nơi để đi nghỉ mát. Hai lựa chọn của anh ấy là: A = New Zealand và B = Alaska

- Klaus chỉ đủ khả năng cho một kỳ nghỉ. Xác suất anh ấy chọn *A* là *P*(*A*) = 0,6 và xác suất anh ấy chọn *B* là *P*(*B*) = 0,35.
- *P*(*A* và *B*) = 0 vì Klaus chỉ đủ khả năng cho một kỳ nghỉ
- Do đó, xác suất anh ấy chọn New Zealand hoặc Alaska là *P*(*A* hoặc *B*) = *P*(*A*) + *P*(*B*) = 0,6 + 0,35 = 0,95. Lưu ý rằng xác suất anh ấy không chọn đi nghỉ ở bất cứ đâu phải là 0,05.
𝑃⁡(𝐴)⁢  = ⁢0.25P⁡(A)⁢ = ⁢0.25P(A) = 0.25𝑃⁡(𝐵)⁢  = ⁢0.65P⁡(B)⁢ = ⁢0.65P(B) = 0.65

- 𝑃⁡(𝐴 𝐴⁢𝑁⁢𝐷 𝐵)P⁡(A A⁢N⁢D B)P(A AND B)
- 𝑃⁡(𝐴 𝑂⁢𝑅 𝐵)P⁡(A O⁢R B)P(A OR B)
Carlos chơi bóng đá ở trường đại học. Cậu ấy ghi bàn 65% số lần sút. Carlos sẽ thực hiện hai cú sút liên tiếp trong trận đấu tới. *A* = biến cố Carlos thành công trong lần sút đầu tiên. *P*(*A*) = 0,65. *B* = biến cố Carlos thành công trong lần sút thứ hai. *P*(*B*) = 0,65. Carlos có xu hướng sút theo chuỗi. Xác suất cậu ấy ghi bàn thứ hai **VỚI ĐIỀU KIỆN** cậu ấy đã ghi bàn thứ nhất là 0,90.

#### Bài tập

a. Xác suất cậu ấy ghi được cả hai bàn là bao nhiêu?

b. Xác suất Carlos ghi được bàn thứ nhất hoặc bàn thứ hai là bao nhiêu?

c. *A* và *B* có độc lập không?

d. *A* và *B* có xung khắc không?

Helen chơi bóng rổ. Đối với các quả ném phạt, cô ấy thực hiện thành công 75% số lần ném. Bây giờ Helen phải thực hiện hai quả ném phạt. *C* = biến cố Helen thực hiện thành công quả ném đầu tiên. *P*(*C*) = 0,75. *D* = biến cố Helen thực hiện thành công quả ném thứ hai. *P*(*D*) = 0,75. Xác suất Helen thực hiện thành công quả ném phạt thứ hai với điều kiện cô ấy đã thực hiện thành công quả đầu tiên là 0,85. Xác suất Helen thực hiện thành công cả hai quả ném phạt là bao nhiêu?

Một đội bơi cộng đồng có **150** thành viên. **Bảy mươi lăm** thành viên là vận động viên bơi lội trình độ nâng cao. **Bốn mươi bảy** thành viên là vận động viên bơi lội trình độ trung cấp. Số còn lại là vận động viên bơi lội mới bắt đầu. **Bốn mươi** vận động viên bơi lội trình độ nâng cao tập luyện bốn lần một tuần. **Ba mươi** vận động viên bơi lội trình độ trung cấp tập luyện bốn lần một tuần. **Mười** vận động viên bơi lội mới bắt đầu tập luyện bốn lần một tuần. Giả sử một thành viên của đội bơi được chọn ngẫu nhiên.

#### Bài tập

a. Xác suất thành viên đó là vận động viên bơi lội mới bắt đầu là bao nhiêu?

b. Xác suất thành viên đó tập luyện bốn lần một tuần là bao nhiêu?

c. Xác suất thành viên đó là vận động viên bơi lội trình độ nâng cao và tập luyện bốn lần một tuần là bao nhiêu?

d. Xác suất một thành viên là vận động viên bơi lội trình độ nâng cao và là vận động viên bơi lội trình độ trung cấp là bao nhiêu? Việc là vận động viên bơi lội trình độ nâng cao và vận động viên bơi lội trình độ trung cấp có phải là các biến cố xung khắc không? Tại sao có hoặc tại sao không?

e. Việc là vận động viên bơi lội mới bắt đầu và tập luyện bốn lần một tuần có phải là các biến cố độc lập không? Tại sao có hoặc tại sao không?

Một trường học có 200 học sinh cuối cấp, trong đó 140 học sinh sẽ vào đại học vào năm tới. Bốn mươi học sinh sẽ đi làm ngay. Số còn lại đang nghỉ một năm (gap year). Năm mươi học sinh cuối cấp vào đại học có chơi thể thao. Ba mươi học sinh cuối cấp đi làm ngay có chơi thể thao. Năm học sinh cuối cấp nghỉ một năm có chơi thể thao. Xác suất để một học sinh cuối cấp nghỉ một năm là bao nhiêu?

Felicity theo học tại Modesto JC ở Modesto, CA. Xác suất Felicity đăng ký một lớp toán là 0,2 và xác suất cô ấy đăng ký một lớp diễn thuyết là 0,65. Xác suất cô ấy đăng ký một lớp toán VỚI ĐIỀU KIỆN cô ấy đăng ký lớp diễn thuyết là 0,25.

Đặt: *M* = lớp toán, *S* = lớp diễn thuyết, *M*|*S* = toán với điều kiện diễn thuyết

#### Bài tập

1. Xác suất để Felicity đăng ký học toán và diễn thuyết là bao nhiêu?

Tìm *P*(*M* và *S*) = *P*(*M*|*S*)*P*(*S*).
1. Xác suất để Felicity đăng ký các lớp toán hoặc lớp diễn thuyết là bao nhiêu?

Tìm *P*(*M* HOẶC *S*) = *P*(*M*) + *P*(*S*) - *P*(*M* VÀ *S*).
1. *M* và *S* có độc lập không? *P*(*M*|*S*) = *P*(*M*) phải không?
1. *M* và *S* có xung khắc không? *P*(*M* VÀ *S*) = 0 phải không?
Một sinh viên đến thư viện. Gọi các biến cố *B* = sinh viên mượn một cuốn sách và *D* = sinh viên mượn một đĩa DVD. Giả sử rằng *P*(*B*) = 0,40, *P*(*D*) = 0,30 và *P*(*D*|*B*) = 0,5.

1. Tìm *P*(*B* VÀ *D*).
1. Tìm *P*(*B* HOẶC *D*).
Các nghiên cứu cho thấy khoảng một trong bảy phụ nữ (xấp xỉ 14,3%) sống đến 90 tuổi sẽ mắc ung thư vú. Giả sử rằng trong số những phụ nữ mắc ung thư vú, kết quả xét nghiệm âm tính là 2% thời gian. Cũng giả sử rằng trong quần thể phụ nữ nói chung, xét nghiệm ung thư vú âm tính khoảng 85% thời gian. Gọi *B* = phụ nữ mắc ung thư vú và gọi *N* = xét nghiệm âm tính. Giả sử một phụ nữ được chọn ngẫu nhiên.

#### Bài tập

a. Xác suất người phụ nữ mắc ung thư vú là bao nhiêu? Xác suất người phụ nữ có kết quả xét nghiệm âm tính là bao nhiêu?

b. Với điều kiện người phụ nữ mắc ung thư vú, xác suất cô ấy có kết quả xét nghiệm âm tính là bao nhiêu?

c. Xác suất người phụ nữ mắc ung thư vú "và" có kết quả xét nghiệm âm tính là bao nhiêu?

d. Xác suất người phụ nữ mắc ung thư vú "hoặc" có kết quả xét nghiệm âm tính là bao nhiêu?

e. Việc mắc ung thư vú và có kết quả xét nghiệm âm tính có phải là các biến cố độc lập không?

f. Việc mắc ung thư vú và có kết quả xét nghiệm âm tính có phải là các biến cố xung khắc không?

Một trường học có 200 học sinh cuối cấp, trong đó 140 học sinh sẽ vào đại học vào năm tới. Bốn mươi học sinh sẽ đi làm trực tiếp. Số còn lại đang nghỉ một năm (gap year). Năm mươi học sinh cuối cấp vào đại học có chơi thể thao. Ba mươi học sinh đi làm trực tiếp có chơi thể thao. Năm học sinh nghỉ một năm có chơi thể thao. Xác suất để một học sinh cuối cấp vào đại học và chơi thể thao là bao nhiêu?

#### Bài tập

Tham khảo thông tin trong [Ví dụ 3.18](3-3-two-basic-rules-of-probability#example5). *P* = xét nghiệm dương tính.

1. Giả sử một phụ nữ bị ung thư vú, xác suất để cô ấy có kết quả xét nghiệm dương tính là bao nhiêu? Tìm *P*(*P*|*B*) = 1 - *P*(*N*|*B*).
1. Xác suất để một phụ nữ bị ung thư vú và có kết quả xét nghiệm dương tính là bao nhiêu? Tìm *P*(*B* VÀ *P*) = *P*(*P*|*B*)*P*(*B*).
1. Xác suất để một phụ nữ không bị ung thư vú là bao nhiêu? Tìm *P*(*B′*) = 1 - *P*(*B*).
1. Xác suất để một phụ nữ có kết quả xét nghiệm dương tính với ung thư vú là bao nhiêu? Tìm *P*(*P*) = 1 - *P*(*N*).
Một sinh viên đi đến thư viện. Gọi các biến cố *B* = sinh viên mượn một cuốn sách và *D* = sinh viên mượn một đĩa DVD. Giả sử rằng *P*(*B*) = 0,40, *P*(*D*) = 0,30 và *P*(*D*|*B*) = 0,5.

1. Tìm *P*(*B′*).
1. Tìm *P*(*D* VÀ *B*).
1. Tìm *P*(*B*|*D*).
1. Tìm *P*(*D* VÀ *B′*).
1. Tìm *P*(*D*|*B′*).
