F2 - Lập trình trên thiết bị di động

Sinh viên: Trịnh Phạm Xuân Nghi
MSSV: 231A010740
Môn học: Lập trình trên thiết bị di động

Nội dung bài làm

Repository gồm bài thực hành F2 và 2 bài nâng cao NC1, NC2.

1. F2_Chinh

Hoàn thành giao diện đăng nhập theo yêu cầu của bài F2

Sử dụng các widget bố cục trong Flutter như Column, Row, Expanded, Stack, Padding

Giao diện có khả năng thích ứng với kích thước màn hình

Sử dụng SingleChildScrollView để xử lý nội dung trên màn hình nhỏ

2. NC1 - Chế độ sáng/tối

Bổ sung Dark Theme cho ứng dụng

Có nút chuyển đổi giữa chế độ sáng và tối

Sử dụng ThemeMode để thay đổi giao diện

3. NC2 - Tách Widget

Tách các widget ra khỏi main.dart để code dễ quản lý hơn

Các widget được đặt trong thư mục lib/widgets/

Gồm:

header_banner.dart

profile_card.dart

stat_box.dart

Cấu trúc bài

F2_231A010740/
├── F2_Chinh/
├── Nc1_che do sang toi/
├── Nc2/
└── README.md

Chạy chương trình

Di chuyển vào thư mục bài muốn chạy, sau đó sử dụng:

flutter pub get
flutter run
