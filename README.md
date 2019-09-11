# Apartment Management
Quản lý chung cư - Học kì 7 - Môn Công nghệ lập trình tích hợp

## Bài tập lớn
- Technology
    - ASMX
    - WCS - API

- Nhóm 13
- Tên đề tài: __Hệ thống quản lý chung cư__ 

- Gợi ý
    - Mỗi căn hộ - 1 hộ gia đình - thành viên trong gia đình.
    - Thêm, sửa, xóa một căn hộ khỏi chung cư.
    - Quản lý chung cư:
        - Quỹ: tổ chức ngày lễ, tết, trung thu
        - Thông báo:
            - Các thông báo đặc biệt tới các hộ gia đình
            - Vệ sinh
            - Đóng tiền
            - Diệt muỗi
            - Diệt côn trùng
            - Mất điện

## Stack
- Backend
    - Eclipse -> Tomcat Server
    - Spring Boot 
        - Maven: for library managerment
        - JPA - object relationship mapping
- Frontend
    - Angular 8
        - Material Design
- Database
    - MySQL 
- Phân công
    - Trello
- Repository
    - Github

## Chuẩn bị
| person | mission                                                        |
|:-------|:---------------------------------------------------------------|
| Hiếu   | viết document + chuẩn bị repo trên git + trello + vẽ prototype |
| Sơn    | Thiết kế CSDL                                                  |
| P.Kiên | Tạo base cho backend + tạo base cho frontend                   |
| T.Kiên | Vẽ giao diện                                                   |
| Mạnh   | Front end                                                      |

## REQUIREMENT

- Dashboard
    - Thống kê số căn hộ trong chung cư
        + Bao nhiêu căn hộ trống, bao nhiêu căn hộ có người
    - Thống kê số cư dân trong chung cư
        + Thống kê tổng số dân cư trong chung cư
    - Thống kê nhân viên
        + Số nhân viên bảo vệ, kế toán, lao công

- Quản lý nhân viên
    - Phòng ban
        + Lưu thông tin của phòng ban: trưởng phòng, tên phòng, vị trí phòng ...
    - Thông tin nhân viên
        + Thông tin nhân viên: các thông tin cơ bản
    - Chức vụ:
        + Chức vụ của nhân viên: có lương

- Quản lý căn hộ
    - Thông tin căn hộ(vật lý - m2, số phòng)
        + Thông tin vật lý của căn hộ - VD: m2, số phòng trong căn hộ, 1 phòng ăn, 2 phòng ngủ, 3 phòng wc
    - Cư dân
        + Thông tin của cư dân trong chung cư - VD: họ, tên, số điện thoại, email ...
    - Chi tiết căn hộ
        + Cho biết người nào ở phòng nào

- Kế toán
    - Điện:
        + In ra được hóa đơn điện 
    - Nước
        + In ra được hóa đơn nước
    - Dịch vụ
        + Hóa đơn dịch vụ: VD - trông xe, vệ sinh.

- Thông báo
    - Thông báo
        - Cắt điện, cắt nước
        - Diệt côn trùng, diệt muỗi
        - Các hộ chưa nộp tiền
        
- Thắc mắc
    - Thắc mắc
        - nhận email của cư dân trong trung cư