# BÀI LÀM: ƯU TIÊN HÓA PRODUCT BACKLOG BẰNG MoSCoW CHO RIKKEIGO

## Phần 1 – Đề xuất 2 cách gán nhãn

Cách 1: Ưu tiên theo ý kiến các bên liên quan (Business Preference)

Gán nhãn dựa trên mức độ mong muốn của các bộ phận như Marketing, Chăm sóc khách hàng và Ban quản lý. Cách này đáp ứng nhu cầu của các bên nhưng dễ bị cảm tính, tranh cãi và thiếu thống nhất khi nhiều bộ phận cùng yêu cầu tính năng của mình là Must.

Cách 2: Ưu tiên theo giá trị phát hành và tính bắt buộc (Release-based MoSCoW)

Gán nhãn dựa trên việc hạng mục có thực sự bắt buộc để bản phát hành cuối Sprint tới hoạt động đúng nghiệp vụ hay không. Must phải là hạng mục không thể thiếu, không có giải pháp thay thế phù hợp; Should và Could có thể trì hoãn mà bản phát hành vẫn sử dụng được; Won't là hạng mục chưa thực hiện trong bản phát hành này.

## Phần 2 – So sánh hai cách gán nhãn

| Tiêu chí                                  | Cách 1: Theo ý kiến các bên                                                                     | Cách 2: Theo giá trị phát hành                                                                                       |
| ----------------------------------------- | ----------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------- |
| Khách quan khi nhiều bộ phận cùng đề xuất | (–) Mỗi bộ phận có lợi ích riêng, dễ xảy ra tranh cãi khi cùng muốn tính năng của mình là Must. | (+) Dựa trên tiêu chí chung về nghiệp vụ, khả năng thay thế và mục tiêu phát hành, hạn chế quyết định cảm tính.      |
| Bảo vệ hạng mục bắt buộc như #1           | (–) Lỗi thu sai tiền có thể bị xếp sau giao diện khuyến mãi nếu Marketing có tiếng nói lớn hơn. | (+) Lỗi tính sai cước ảnh hưởng trực tiếp đến tiền khách hàng nên được ưu tiên Must, không phụ thuộc ý kiến bộ phận. |

Kết luận: Chọn Cách 2 – Ưu tiên theo giá trị phát hành và tính bắt buộc. Cách này phù hợp với nguyên tắc MoSCoW vì Must được xác định theo nhu cầu tối thiểu của bản phát hành, không phải theo mức độ mong muốn của từng phòng ban.

## Phần 3 – Áp dụng MoSCoW cho 6 hạng mục

### 3.1. Gán nhãn và giải thích

| # | Hạng mục                                        | Điểm | Nhãn   | Lý do                                                                                                                 |
| - | ----------------------------------------------- | ---- | ------ | --------------------------------------------------------------------------------------------------------------------- |
| 1 | Sửa lỗi hiển thị sai cước sau khuyến mãi        | 2    | Must   | Đang thu sai tiền khách hàng, ảnh hưởng trực tiếp đến tính chính xác của nghiệp vụ thanh toán và uy tín ứng dụng.     |
| 2 | Áp mã khuyến mãi khi đặt xe                     | 2    | Must   | Là chức năng cốt lõi của chương trình Tháng khuyến mãi, cần có để khách hàng sử dụng ưu đãi trong bản phát hành.      |
| 3 | Thanh toán bằng ví RikkeiPay                    | 3    | Should | Khách hàng vẫn có thể thanh toán bằng tiền mặt, nên ví điện tử có thể triển khai ở bản phát hành sau.                 |
| 4 | Hẹn giờ đặt xe trước                            | 3    | Won't  | Không trực tiếp phục vụ mục tiêu khuyến mãi của đợt phát hành này; chủ động loại khỏi phạm vi để tập trung nguồn lực. |
| 5 | Chat với tài xế                                 | 3    | Should | Khách hàng vẫn có thể gọi điện cho tài xế, nên chức năng chat chưa phải điều kiện bắt buộc để phát hành.              |
| 6 | Giao diện trang trí cho chương trình khuyến mãi | 2    | Could  | Giúp tăng tính hấp dẫn về mặt hình ảnh nhưng thiếu giao diện trang trí riêng thì chương trình vẫn có thể hoạt động.   |

Lưu ý: Nhãn MoSCoW áp dụng cho bản phát hành cụ thể này, không có nghĩa hạng mục đó vĩnh viễn quan trọng hoặc không quan trọng.

### 3.2. Chốt phạm vi Sprint trong 10 điểm

## Kế hoạch Sprint

Đủ 10/10 điểm

Năng lực Sprint

### 10 điểm

7 điểm Must/Should được chọn, cộng 2 điểm Could và 1 điểm dự phòng không nằm trong 6 hạng mục.

Danh sách đưa vào Sprint

#1 – Sửa lỗi hiển thị sai cước

2 điểm · Must

#2 – Áp mã khuyến mãi

2 điểm · Must

#3 – Thanh toán bằng ví RikkeiPay

3 điểm · Should

Tổng điểm danh sách trên

# 7/10

Tỷ lệ Must trong Sprint:

Hai hạng mục Must có tổng cộng 2+2=42+2=42+2=4 điểm.

Tỷ lệ Must=410×100%=40%\text{Tỷ lệ Must}=\frac{4}{10}\times100\%=40\%Tỷ lệ Must=104×100%=40%

Tỷ lệ Must hiện tại là 40%, thấp hơn mức mục tiêu khoảng 60%. Vì vậy, cần xem lại phạm vi và năng lực thực tế trước khi chốt kế hoạch. Không nên tự động nâng hạng mục khác thành Must chỉ để đạt tỷ lệ 60%.

### 3.3. Thông báo cho các bên liên quan

* Marketing: Giao diện trang trí khuyến mãi (#6) được xếp Could; chương trình vẫn ưu tiên bảo đảm áp mã và tính cước chính xác.

* Chăm sóc khách hàng: Chat với tài xế (#5) được xếp Should vì chức năng gọi điện vẫn đáp ứng nhu cầu liên lạc hiện tại.

* Product Owner: Hẹn giờ đặt xe (#4) thuộc Won't trong bản phát hành này; sẽ được xem xét ở lần phát hành tiếp theo.

## Kết luận

Lan đề xuất Đức áp dụng cách gán nhãn theo giá trị phát hành và tính bắt buộc để hạn chế tranh cãi giữa các bộ phận. Hai hạng mục Must là sửa lỗi tính cước và áp mã khuyến mãi; các tính năng có giải pháp thay thế được xếp mức ưu tiên thấp hơn.

Điểm cần điều chỉnh trước khi nộp: Kế hoạch chọn 7/10 điểm và có tỷ lệ Must 40%, chưa đạt mục tiêu khoảng 60%. Nếu giảng viên yêu cầu Must gần 60% năng lực, cần rà soát lại tiêu chí Must và phạm vi Sprint thay vì chỉ giữ nguyên danh sách trên.
