STM32F401 Development Board



Bo mạch phát triển tùy chỉnh sử dụng vi điều khiển STM32F401, được thiết kế bằng phần mềm KiCad.



Tổng quan PCB

Mô hình PCB 3D



!\[3D PCB]("image\\KIT\_STM32F401.png")



Ảnh bo mạch thực tế:

!\[Bo mạch thực tế]("image\\V1.png")



Mô tả dự án



Dự án tập trung vào thiết kế sơ đồ nguyên lý (schematic) và thiết kế mạch in (PCB) cho một bo mạch phát triển dựa trên vi điều khiển STM32F401.



Bo mạch được phát triển nhằm phục vụ cho việc nghiên cứu hệ thống nhúng, phát triển firmware, giao tiếp ngoại vi, thử nghiệm phần cứng và xây dựng các ứng dụng điều khiển sử dụng vi điều khiển.



Tính năng chính

Thiết kế schematic và PCB hoàn toàn tùy chỉnh.

Sử dụng vi điều khiển dòng STM32F401.

Thiết kế và đi dây PCB bằng KiCad.

Kiểm tra mô hình 3D để đánh giá bố trí linh kiện và khả năng lắp ráp cơ khí.



Thông số phần cứng

Thông số	Giá trịVi điều khiển	STM32F401 Series

Phần mềm thiết kế PCB	KiCad

Thiết kế nguyên lý	KiCad Schematic Editor

Thiết kế PCB	KiCad PCB Editor

Kiểm tra 3D	KiCad 3D Viewer

Nguồn cấp	5VDC

Kích thước PCB	100mmx100mm

Số lớp PCB	2

Giao tiếp truyền thông	1xRS232(MAX3232), 1xRS485(MAX3485), 1xEthernet(W5500), 2ADC, 4xButton, 5xLed

Quy trình thiết kế

Thiết kế sơ đồ nguyên lý (Schematic).

Lựa chọn linh kiện và gán footprint.

Bố trí linh kiện và đi dây PCB.

Kiểm tra quy tắc thiết kế (DRC).

Công cụ sử dụng

KiCad: Thiết kế nguyên lý, thiết kế PCB, quản lý footprint và kiểm tra mô hình 3D.

Git: Quản lý phiên bản dự án cục bộ.

GitHub: Lưu trữ mã nguồn và tài liệu dự án trực tuyến.

Cấu trúc Repository

\*.kicad\_pro : Tệp cấu hình dự án KiCad.

\*.kicad\_sch : Thiết kế sơ đồ nguyên lý.

\*.kicad\_pcb : Thiết kế PCB.

images/ : Hình ảnh PCB và ảnh render 3D.

Trạng thái dự án



Hoàn thành đã kiểm thử các chức năng cơ bản
(Note cần sửa lại kết nối LCD D0/D1/D2/D3 -> D4/D5/D6/D7



Tác giả



Tạ Đức



GitHub: TaDuc-TD

