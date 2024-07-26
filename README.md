# 1. Khái niệm
- Network Access Control (kiểm soát truy cập mạng): là một khái niệm quan trọng trong lĩnh vực bảo mật mạng, giúp quản lý và kiểm soát quyền truy cập vào hệ thống thông qua việc áp dụng các chính sách (policy) trên các thiết bị và người dùng của mạng doanh nghiệp.
- Trong mô hình Truy cập mạng Zero Trust, NAC đóng vai trò chủ chốt. Khi một thiết bị kết nối vào mạng, nó không được phép truy cập vào bất kỳ tài nguyên nào cho đến khi tuân thủ các chính sách xác định trước đó, bao gồm cấp độ bảo vệ chống virus, cập nhật hệ thống và cấu hình. Chỉ khi thiết bị đáp ứng các chính sách này, nó mới được phép truy cập vào tài nguyên mạng và Internet theo các chính sách mà hệ thống NAC đã xác định.
- Với Network Access Control, các doanh nghiệp có khả năng kiểm soát chặt chẽ quyền truy cập vào mạng, đảm bảo rằng chỉ những thiết bị và người dùng đáng tin cậy mới được phép kết nối. Điều này giúp ngăn chặn các mối đe dọa từ bên ngoài, bảo vệ thông tin quan trọng và đảm bảo an toàn cho hệ thống mạng của doanh nghiệp.
- Phân loại: NAC có 2 loại chính:
  - Pre-admission: được sử dụng để kiểm tra và phê duyệt các thiết bị và người dùng được phép truy cập vào mạng.
  - Post-admission: được sử dụng để cấp quyền cho một thiết bị hoặc người dùng đã được xác thực trước đó nhưng đang cố gắng truy cập vào một khu vực mới hoặc khu vực khác của mạng mà họ chưa được cho phép.
# 2. Tầm quan trọng của NAC
- Cải thiện bảo mật: NAC cung cấp khả năng giám sát tất cả các thiết bị được sử dụng trong tổ chức nên nó tăng cường bảo mật khi xác thực người dùng và thiết bị ngay khi họ truy cập mạng nội bộ. Khả năng giám sát hoạt động mạng và ngay lập tức chặn những hành vi trái phép hoặc bất thường đồng nghĩa với việc giảm thiểu các mối đe dọa từ phần mềm độc hại và các cuộc tấn công mạng khác.
- Các chính sách thực thi linh động: Giải pháp hỗ trợ thực thi chính sách dựa trên RADIUS mà không cần yêu cầu thay đổi VLAN và hỗ trợ tích hợp Layer 3 không yêu cầu xác thực 802.1X.
- Contextual Intelligence (nhận thức ngữ cảnh): Nhận thức toàn diện hơn về ngữ cảnh thiết bị trong hệ thống mạng, chia sẽ thông tin với các giải pháp bảo mật bên thứ ba như SIEM, Firewal, IPS/IDS để có thể tự động hóa quy trình đảm bảo an ninh bảo mật trong doanh nghiệp.
- Cài đặt, đào tạo, triển khai và hỗ trợ từ xa: Giải pháp triển khai đơn giản, có thể hỗ trợ cài đặt và triển khai từ xa; hỗ trợ proactive monitoring 24×7, sao lưu mỗi ngày, nâng cấp phần mềm, phát hiện và giải quyết sự cố.
- Tiết kiệm chi phí: Việc tự động theo dõi và bảo vệ các thiết bị trên quy mô lớn giúp tiết kiệm chi phí cho các tổ chức vì cần ít tài nguyên CNTT hơn. Hơn nữa, việc chặn truy cập trái phép hoặc một cuộc tấn công đang bị nghi ngờ là phần mềm độc hại sẽ giúp các công ty tránh khỏi những tổn thất tài chính có thể xảy ra.
# 3. Cách NAC bảo vệ hệ thống
- Giới hạn quyền truy cập mạng của người dùng và các vùng mạng cụ thể.
- Ngăn chặn truy cập dữ liệu bởi nhân viên không được cấp quyền và tội phạm mạng.
- Chặn quyền truy cập từ các thiết bị đầu cuối (ví dụ: điện thoại di động) không tuân thủ chính sách bảo mật doanh nghiệp.
- Nhận dạng và lập hồ sơ người dùng và thiết bị của họ để bảo vệ họ khỏi mã độc.
- Tích hợp với các giải pháp bảo mật bên thứ ba như SIEM, Firewal, IPS/IDS để có thể tự động hóa quy trình đảm bảo an ninh bảo mật trong doanh nghiệp thông qua API, RESTful, tạo nên hệ thống với khả năng bảo mật mạnh mẽ.
- NAC có thể từ chối quyền truy cập mạng vào các thiết bị không tuân thủ, đặt chúng vào khu vực cách ly hoặc chỉ cấp cho chúng quyền truy cập hạn chế vào tài nguyên máy tính, do đó giữ cho các nút không an toàn không lây nhiễm vào mạng.
- NAC thu thập thông tin chi tiết theo thời gian thực và so sánh ngữ cảnh thiết bị để đưa ra các quyết định áp dụng chính sách chính xác và tức thời.
- Tự động hóa ứng phó sự cố.
# 4. Các tính năng của NAC
- Phát hiện: Xác định người dùng và thiết bị mới truy cập vào mạng nội bộ.
- Xác thực: Kiểm tra thông tin xác thực của người dùng trước khi cho phép họ truy cập mạng.
- Đánh giá: Kiểm tra các điểm cuối về việc tuân thủ các chính sách mạng và lỗ hổng của chúng.
- Authorize: Cho phép hoặc từ chối truy cập vào mạng dựa trên kết quả của các bước xác thực và đánh giá.
- Giám sát: Theo dõi hoạt động của các thiết bị trong mạng ngay khi được kết nối.
- Cách ly: cách ly các điểm cuối có vấn đề để ngăn chúng làm hỏng mạng hoặc lấy dữ liệu nhạy cảm.
# 5. Demo
