**RequirementAnalysis (RA):** Kết quả của bước phân tích yêu cầu phầm mềm (SRS) bao gồm: Biểu đồ use case tổng quan, biểu đồ use case phân rã nếu có, đặc tả các use case nghiệp vụ, từ điển thuật ngữ, đặc tả phụ trợ

## Homework01:
1. Tạo nhóm, repo
2. tạo các thư mục
3. Kết quả bước RA: thiết kế biểu đồ use case tổng quan và usecase phân rã các mức

=======================================

# Homework01: Git/Gibhub và Biểu đồ use case
## Tasks
 - Thiết kế biểu đồ use case tổng quan và phân rã use case
## Contributions
    - Vũ Hoàng Tuấn : Đại diện bên đưa ra yêu cầu
    - Ngô Đình Long: Thu thập yêu cầu, phân rã use case
    - Nguyễn Tất Thành: Thu thập yêu cầu, hoàn thành use case tổng quan
    - Trần Đoàn Vũ: Thu thập yêu cầu, hoàn thành use case tổng quan
## Revisions 
 - Bên A - đại diện công ty: gồm thành viên Vũ Hoàng Tuấn
 - Bên B - Các thành viên trong nhóm nhận yêu cầu thiết kế và xây dựng phần mềm cho bên A: các thành viên còn lại
 - Yêu cầu của bên A - Bài toán cần giải quyết: 
    Công ty TNHN&TM HN là một công ty chuyên về lĩnh vực lâm sản nằm tại một tỉnh miến núi phía bắc. Nơi đây có hoàn cảnh cư dân khá đặc biệt: người dân chiếm phần lớn là nông dân, thường có 2 - 3 vụ mùa mỗi năm, vào khoảng thời gian giao giữa các mùa vụ trong năm hoặc giữa các giai đoạn trong một mùa vụ là khoảng thời gian người nông dân rảnh rỗi và kiếm việc làm. Tận dụng đặc điểm nhân lực này công ty quyết định mỗi năm có 2-3 đợt tuyển dụng nhân viên - công nhân thời vụ tương ứng. 
    Công ty chia ra làm 4 bộ phận: *Vận chuyển*, *Nhiên liệu*, *Chế biến*, *Văn phòng*. Mỗi bộ phận có các **tiêu chí đánh giá** xét tuyển khác nhau và riêng bộ phận văn phòng có chu kỳ tuyển dụng khác. Cho đến hiện tại các giấy tờ liên quan đến việc xét tuyển cần phải lưu giữ với nhiều lí do khác nhau như chuyển đợt tuyển, lưu hồ sơ cho lần tuyển sau,... .Tuy nhiên, việc lưu giấy đang trở nên lỗi thời, ban giám đốc quyết định số hóa dữ liệu và chuyển sang làm việc trên máy tính sau khi nghiên cứu các phương án.

 - Xác định các nhóm đối tượng sử dụng: Thành viên ban tuyển dụng ==> Actor: *Ban tuyển dụng*. Cần có một thành viên cấp cao trong ban tuyển dụng cấp phát tài khoản cho các thành viên khác trong ban ==> Actor: *Quản trị viên (QTV)*, là một khái quát hóa của Actor *Ban tuyển dụng*
 - Xác định các chức năng chính: Quản lý các ứng viên tuyển dụng. ==> Use case: *Quản lý ứng viên*
 - Xác định chức năng của QTV: Có đầy đủ chức năng của Actor *Ban tuyển dụng*, có thêm chức năng quản lý tài khoản của hệ thống ==> Use case: *Quản lý tài khoản*;
 - Ngoài ra, nhận thấy việc lưu trữ các ứng viên trong mỗi bộ phận đều có các tiêu chí như điểm số các bài thi đầu vào, nhóm đề nghị thêm chức năng hỗ trợ tính toán, đưa ra, sắp xếp các ứng viên trong bộ phận dựa trên các tiêu chí sử dụng phương pháp ra quyết định đa thuộc tính TOPSIS hoặc ELECTRE ==> Use case: *Hỗ trợ lựa chọn ứng viên*