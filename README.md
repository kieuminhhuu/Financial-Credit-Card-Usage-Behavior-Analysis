# Financial-Credit-Card-Usage-Behavior-Analysis
# 1.	Project Overview 
-	Với sự phát triển của thị trường tài chính, việc hiểu rõ hơn về cách người dùng sử dụng thẻ tín dụng sẽ giúp các tổ chức tài chính tối ưu hóa các sản phẩm, đồng thời cung cấp các dịch vụ phù hợp hơn cho từng nhóm khách hàng. Dự án này tập trung vào việc phân tích hành vi sử dụng thẻ tín dụng của người dùng dựa trên các yếu tố nhân khẩu học để từ đó xác định các xu hướng chi tiêu, tỷ lệ sử dụng tín dụng và những yếu tố ảnh hưởng đến giá trị giao dịch cung cấp những insight có giá trị cho doanh nghiệp
# 2.	Objective
Phân tích hành vi sử dụng thẻ tín dụng của người dùng thông qua đặc điểm nhân khẩu học bao gồm:
  - **Giới tính**: đánh giá xem giới tính có ảnh hưởng như thế nào đến các hành vi sử dụng tín dụng, các chỉ số được xem xét:
    - Số lượng thẻ sở hữu
    - Tổng số tiền giao dịch
    - Số lượng giao dịch mỗi tháng 
    - Số lượng giao dịch mỗi năm
    - Giá trị giao dịch trung bình
    - Số lượng giao dịch theo giờ 
    - Số lượng giao dịch theo thứ trong tuần 
    - Số lượng giao dịch theo ngày trong tháng 
  - **Độ tuổi**: Tìm hiểu các xu hướng sử dụng tín dụng ở các nhóm tuổi khác nhau thông qua các chỉ số:
    - Tổng giao dịch của các nhóm độ tuổi 
    - Tổng giá trị giao dịch của các nhóm độ tuổi 
    - Tần suất giao dịch của các nhóm độ tuổi 
    - Giá trị giao dịch trung bình của các nhóm độ tuổi 
    - Số lượng thẻ tín dụng sở hữu bởi các nhóm độ tuổi
  - **Thu nhập**: Phân tích sự khác biệt trong cách thức sử dụng tín dụng giữa các nhóm thu nhập thông qua các chỉ số:
    - Tổng giao dịch của các nhóm thu nhập 
    - Tổng giá trị giao dịch của các nhóm thu nhập
    - Giá trị trung bình giao dịch của các nhóm thu nhập 
    - Số lượng thẻ sở hữu trung bình của các nhóm thu nhập
    - Tần suất giao dịch của các nhóm thu nhập
    - Tổng nợ của các nhóm thu nhập
    - Trung bình tỷ lệ nợ trên thu nhập(DTI) của các nhóm thu nhập
- Phân tích hành vi sử dụng thẻ tín dụng thông qua điểm tín dụng. Các chỉ số được phân tích:
  - Tổng số người dùng trong mỗi nhóm tín dụng
  - Tổng giao dịch từ các nhóm tín dụng
  - Tỷ lệ chi tiêu trên giới hạn tín dụng của các nhóm tín dụng
  - Giá trị chi tiêu trung bình của các nhóm tín dụng
  - Tần suất giao dịch trung bình của các nhóm tín dụng
  - Tỷ lệ nợ trên thu nhập của các nhóm tín dụng
- Kết hợp các đặc điểm:
 	- Mối quan hệ giữa nhóm tuổi, thu nhập và nợ
	- Mỗi quan hệ giữa độ tuổi và nợ
	- Mối quan hệ giữa độ tuổi và điểm tín dụng
# 3.  Dataset
- Dataset bao gồm thông tin về các giao dịch tín dụng, thông tin chủ thẻ, thông tin thẻ tín dụng trong **3 bảng**:
  - **Transaction**: chứa thông tin về các giao dịch tín dụng từ năm 2018 đến 2 tháng đầu năm 2020 gồm ID_Transaction, ID_User, ngày tháng năm thời gian giao dịch, số tiền giao dịch, vị trí giao dịch
  - **Users**: Chứa thông tin chủ thẻ tín dụng gồm: ID, Tên, Tuổi, Năm sinh, Giới tính, địa chỉ, thu nhập hàng năm, tổng nợ tín dụng, điểm tín dụng, số lượng thẻ tín dụng sở hữu
  - **Cards**: Chứa thông tin về các thẻ tín dụng gồm: ID_User, ID_Card, Loại thẻ, Số thẻ, ngày hết hạn, ngày đăng ký, Giới hạn tín dụng
# 4.  Insight


 
