# UNIFIED PROCESS
- Là một phương pháp phát triển hệ thống trong đó quy định khi nào thì sử dụng các kỹ thuật UML và sử dụng chúng như thế nào trong quá trình phân tích và thiết kế
hệ thống.

- Tác giả: Booch, Jacobsen, Rumbaugh

- Là phương pháp hướng đối tượng

- Không phải là một quy trình phát triển phần mềm hoàn thiện
    - Không xét đến các vấn đề về phân bổ nhân lực, ngân quỹ, quản lý hợp đồng

    - Không quy định về các hoạt động bảo trì hay hỗ trợ khách hàng

    - Không xét đến các vấn đề tương tác giữa các dự án

## 4 Pha chính
#### Pha khởi tạo (Inception):
- Tương ứng giai đoạn lập kế hoạch

- Các bước liên quan:
    - Mô hình hoá giá trị kinh doanh của hệ thống (business modeling)

    - Xác định yêu cầu (requirements)

- Kết quả:
    - Phạm vi của dự án

    - Các yêu cầu và ràng buộc quan trọng

    - Kế hoạch dự án bước đầu

    - Miêu tả tính khả thi và rủi ro của dự án

    - Lựa chọn môi trường cần thiết để phát triển hệ thống

#### Pha phát triển (elaboration):
- Hoàn thiện mô hình kinh doanh, đánh giá lại rủi ro và hoàn thiện kế hoạch dự án.

- Các bước liên quan:
    - Phân tích (analysis)

    - Thiết kế (design)

- Kết quả:
    - Biểu đồ cấu trúc và chức năng UML

    - Phiên bản hoạt động đầu tiên của hệ thống

#### Pha xây dựng (construction):
- Tập trung chủ yếu vào lập trình hiện thực hoá hệ thống.

- Các bước liên quan:
    - Thực hiện (implementation)

    - Quản lý cấu hình và thay đổi (configuration and change management)

- Kết quả:
    - Phiên bản beta của hệ thống

#### Pha chuyển tiếp (transition):
- Tập trung chủ yếu vào kiểm thử và triển khai hệ thống.

- Các bước liên quan:
    - Kiểm tra (test)

    - Triển khai (deployment)

    - Quản lý cấu hình và thay đổi (configuration and change management)

- Kết quả:
    - Phiên bản cuối cùng (release) của hệ thống

    - Hướng dẫn sử dụng

    - Kế hoạch hỗ trợ khách hàng, kế hoạch nâng cấp hệ thống

## Các bước kỹ thuật (Engineering workflows):
#### Mô hình hoá giá trị kinh doanh của hệ thống (business modeling)
- Diễn ra chủ yếu trong pha khởi tạo

- Phát hiện vấn đề và xác định các dự án tiềm năng

- Xác định giá trị kinh doanh mà dự án đem lại

- Thu thập dữ liệu và mô hình hoá use case sử dụng có thể được sử dụng.

#### Xác định yêu cầu (determine the requirements)
- Xác định yêu cầu:
    - Yêu cầu chức năng

    - Yêu cầu phi chức năng

- Yêu cầu được thu thập từ người sử dụng, người quản lý người sử dụng, khách hàng

#### Phân tích (analysis)
-  Xây dựng các lược đồ sử dụng UML:
    - Lược đồ cấu trúc

    - Lược đồ chức năng

-  Xác định các lớp có thể sử dụng lại

-  Bước phân tích có thể được sử dụng lại bất kỳ lúc nào trong chu trình phát triển hệ thống

#### Thiết kế (design)
-  Chuyển từ mô hình phân tích sang mô hình thiết kế

-  Hoàn tất các bản thiết kế cụ thể của hệ thống:
    - Cơ sở dữ liệu

    - Sơ đồ lớp

    - Giao diện

    - Cấu trúc vật lý

#### Thực hiện (implementation)
- Lập trình hệ thống:
    - Xây dựng mã nguồn theo bản thiết kế, tích hợp các module

#### Kiểm tra (test)
- Kiểm tra tích hợp hệ thống, chức năng, khả năng chấp nhận của người sử dụng ...

- Việc kiểm tra đuợc tiến hành trong suốt quá trình phát triển của hệ thống

#### Môi trường phát triển (environment - deployment)
- Đóng gói phần mềm, phân phối, cài đặt và kiểm thử bản beta

## Các bước hỗ trợ (Supporting workflows):
#### Quản lý dự án (project management)
- Diễn ra trong suốt quá trình phát triển hệ thống

- Xác định và quản lý rủi ro

- Quản lý phạm vi dự án

- Quản lý về thời gian, chi phí...

#### Quản lý cấu hình và thay đổi
- Theo dõi và quản lý trạng thái và các phiên bản của hệ thống

- Quản lý việc thay đổi các phiên bản (người thay đổi, thời gian thay đổi...)

#### Quản lý môi trường phát triển (environment)
- Quản lý các công cụ và môi trường phát triển cần thiết cho dự án

- Ví dụ: Rational Rose, Microsoft project, Microsoft Visual C++...