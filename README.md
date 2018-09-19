#Timesheet platform

## Tổng quan:

Platform này được dùng để theo dõi và quản lý giờ và công việc của từng nhân viên và từng dự án.
Từ đó có thể tính trực tiếp được lương từ công việc của nhân viên.

## Chức năng

### Phân loại người dùng

* Đăng nhập vào hệ thống dựa trên vai trò hệ thống (system role). Bao gồm:
  1. admin
  2. user
* Phân biệt vai trò của nhân viên theo vai trò công ty (company role). Bao gồm:
  1. CEO
  2. CTO
  3. Engineer
  4. HR
  5. Sale
* Phân biệt vai trò của nhân viên theo từng dự án (project role). Bao gồm:
  1. Developer
  2. Project Manager

#### Admin

  Cho phép add, edit, delete một user khác.
  Được access vào hệ thống.

#### User

  Được access vào hệ thống.

#### CEO

  Được access xem toàn bộ thông tin từ hệ thống.

#### CTO

  Được access xem toàn bộ thông tin từ hệ thống nhưng các quyết định phải được approve bởi CEO.

#### Engineer

  Được access thông tin liên quan đến kỹ sư.

#### Sale

  Được access thông tin liên quan đến dự án.

#### HR

  Được access thông tin liên quan đến bộ phận nhân sự.

#### Developer

  Được access thông tin trên dự án đang làm.

#### Project Manager

  Được access thông tin trên dự án đang làm và đưa ra quyết định.

### Điền thông tin về dự án

  Dự án sẽ bao gồm thông tin về dự án, ngày khởi động, mô hình dự án, các thành viên và thông tin mô tả dự án.
  Mỗi dự án sẽ được chia thành các timesheet ứng với từng tháng.
  Mỗi tháng timesheet sẽ bao gồm các timesheet detail chứa thông tin ngày giờ và công việc của từng kỹ sư làm.
  Dựa vào thông tin của từng kỹ sư, dự án mà có thể tính lương trực tiếp theo thời gian thực đối với từng kỹ sư.
  Hệ thống vận hành dựa trên sự tin tưởng của từng kỹ sư cam kết với khối lượng công việc.
  Project Manager có thể dựa trên khối lượng công việc để đánh giá xem liệu kỹ sư có trung thực và hoàn thành công việc theo tiến độ hay không.

  Hệ thống có thể xuất file excel để có thể thống kế được chi phí và doanh thu lợi nhuận từ hoạt động kinh doanh của công ty.

  Hệ thống cho phép quản trị và lưu trữ một số dữ liệu chung như là các bài test của các dịch vụ thứ 3 như Upwork.
  Hệ thống cho phép bộ phận Sale có thể quản lý và khai thác nguồn thông tin các dự án để có thể đi sale tìm thêm dự án về.