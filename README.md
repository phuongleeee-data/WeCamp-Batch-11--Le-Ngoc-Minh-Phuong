#SESSION 1: INTRODUCTION TO PROGRAMMING 5 & JS ESSENTIALS
Date: 21/04/2026
Program: NAB WeCamp batch 11
Author: Lê Ngọc Minh Phương

I. Tư duy lập trình & Cách máy tính vận hành
Quy trình thực thi code:
   Write code: Viết bằng ngôn ngữ bậc cao (JavaScript).
   Interpreter (Dịch từng dòng)/Compiler (Dịch hết 1 lần): Trình thông dịch/ biên dịch chuyển mã thành chỉ thị máy.
   CPU: Thực thi kết quả dưới dạng nhị phân (0 và 1).
   Output: Kết quả (Website mở, file được lưu, tin nhắn hiện lên).

II. JavaScript Essentials
1. Tại sao lại là JavaScript?
   Là ngôn ngữ của trình duyệt và ứng dụng hiện tại.
   Thân thiện với mhuoiwf mới chuyển ngành.
   Công cụ tốt nhất để luyện tập tư duy DSA (Cấu trúc dữ liệu & Giải thuật)

2. Biến & Kiểu dữ liệu
   Khai báo: var, let, const.
   Kiểu dữ liệu cơ bản: number, string, boolean, undefined, null
   Kiểm tra kiểu dữ liệu: sử dụng toán tử typeof()

3. Toán tử (Operators)
   Loại,Ví dụ,Kết quả
Số học,10 % 3,1 (Chia lấy dư)
So sánh tương đối,"5 == ""5""",true (Chỉ xét giá trị)
So sánh nghiêm ngặt,"5 === ""5""",false (Xét cả kiểu dữ liệu)
Logic AND,age >= 19 && hasID,true nếu cả hai đều đúng
Logic OR,age >= 21 || hasID,true nếu ít nhất một cái đúng

III. Command Line Interface (CLI)
Sử dụng dòng lệnh giúp kỹ sư tương tác với hệ thống macOS nhanh và mạnh mẽ hơn.
Command,Chức năng
pwd,Xem vị trí thư mục hiện tại
ls -la,Liệt kê tất cả file (bao gồm file ẩn)
cd [path],Di chuyển đến thư mục (VD: cd ~/downloads)
cd ..,Quay lại thư mục cha
mkdir [tên],Tạo thư mục mới
touch [tên],Tạo file mới (VD: index.js)
cat [tên],Xem nhanh nội dung file
rm [tên],Xóa file

IV. Git & Version control
Quản lý phiên bản là kỹ năng sống còn để theo dõi lịch sử code và làm việc nhóm.

1. Khái niệm cốt lõi
   Repository (Repo): Kho chứa dự án
   Staging Area: Khu vực chuẩn bị trước khi lưu chính thức
   Commit: Một ảnh chụp (snapshot) của mã nguồn tại thời điểm
   Branch: Một nhánh độc lập để phát triển tính năng mới

2. Các lệnh Git cơ bản:
git init: Khởi tạo Git cho thư mục.

git add .: Đưa toàn bộ thay đổi vào Staging Area.

git commit -m "mess": Lưu lại thay đổi kèm ghi chú có ý nghĩa.

git checkout -b [tên]: Tạo và chuyển sang nhánh mới.

git merge [tên]: Gộp code từ nhánh phụ vào nhánh chính.
