flowchart TD
    A((Start))
    B[Người dùng đăng nhập vào hệ thống]
    C[Người dùng tìm kiếm sách]
    D{Sách có sẵn?}
    E[Đăng ký mượn sách]
    F[Đặt trước sách]
    G[Xác nhận yêu cầu mượn sách]
    H{Mượn sách thành công?}
    I[Cập nhật trạng thái]
    J((End))

    A --> B
    B --> C
    C --> D

    D -- Có --> E
    D -- Không --> F

    E --> G
    F --> G

    G --> H

    H -- Thành công --> I
    H -- Không thành công --> J

    I --> J
