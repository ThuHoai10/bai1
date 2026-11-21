
# 🏋️ GYM X - HỆ THỐNG QUẢN LÝ PHÒNG GYM

## 1. Giới thiệu dự án
**Gym X** là hệ thống quản lý phòng tập thể hình được xây dựng nhằm hỗ trợ số hóa và tối ưu hóa các hoạt động quản lý, vận hành phòng gym.
Hệ thống cung cấp các chức năng quản lý hội viên, gói tập, huấn luyện viên, lịch tập, điểm danh, thanh toán và thống kê báo cáo. Qua đó, hỗ trợ nhân viên và quản trị viên quản lý hoạt động phòng tập một cách hiệu quả, chính xác và thuận tiện hơn.
Dự án hướng đến việc giảm thiểu các thao tác quản lý thủ công, tập trung dữ liệu trên một hệ thống thống nhất và nâng cao trải nghiệm sử dụng cho hội viên.

## 2. Mục tiêu dự án
- Xây dựng hệ thống quản lý thông tin hội viên tập trung.
- Hỗ trợ quản lý các gói tập và quá trình đăng ký gói tập.
- Quản lý thông tin huấn luyện viên và lịch làm việc.
- Hỗ trợ hội viên đặt lịch tập với huấn luyện viên.
- Theo dõi quá trình điểm danh và lịch sử tập luyện.
- Quản lý thông tin thanh toán và lịch sử giao dịch.
- Cung cấp thông báo và báo cáo phục vụ công tác quản lý.

## 3. Các chức năng chính
### 3.1. Quản lý hội viên
- Thêm, sửa, xem và quản lý thông tin hội viên.
- Tìm kiếm và lọc danh sách hội viên.
- Theo dõi trạng thái hội viên.
- Quản lý thông tin và lịch sử tập luyện.

### 3.2. Quản lý gói tập
- Thêm, sửa, xóa và xem thông tin các gói tập.
- Quản lý thời hạn gói tập (3 tháng, 6 tháng, 12 tháng).
- Quản lý giá và quyền lợi của từng gói tập.
- Theo dõi tình trạng đăng ký và thời hạn sử dụng gói tập.

### 3.3. Quản lý huấn luyện viên
- Quản lý thông tin huấn luyện viên.
- Theo dõi lịch làm việc.
- Phân công huấn luyện viên.
- Quản lý tình trạng sẵn sàng và lịch tập của huấn luyện viên.

### 3.4. Quản lý lịch tập và đặt lịch
- Xem lịch tập khả dụng.
- Đặt lịch tập với huấn luyện viên.
- Cập nhật và quản lý thông tin lịch đặt.
- Theo dõi trạng thái đặt lịch.

### 3.5. Quản lý điểm danh
- Ghi nhận thông tin check-in và check-out của hội viên.
- Hỗ trợ nhận diện khuôn mặt trong quá trình điểm danh.
- Lưu trữ lịch sử điểm danh.
- Theo dõi tần suất tập luyện của hội viên.

### 3.6. Quản lý thanh toán
- Quản lý các khoản thanh toán đăng ký gói tập.
- Ghi nhận và lưu trữ thông tin giao dịch.
- Theo dõi trạng thái thanh toán.
- Tra cứu lịch sử thanh toán.

### 3.7. Quản lý thông báo
- Gửi thông báo về tình trạng và thời hạn gói tập.
- Nhắc nhở lịch tập đã đặt.
- Thông báo về tình trạng thanh toán.
- Cập nhật các thông tin liên quan đến hội viên.

### 3.8. Thống kê và báo cáo
- Thống kê số lượng hội viên.
- Theo dõi tình hình đăng ký các gói tập.
- Tổng hợp doanh thu và thông tin thanh toán.
- Theo dõi tình hình hoạt động của phòng gym.

## 4. Đối tượng sử dụng
Hệ thống hỗ trợ các nhóm người dùng sau:
| Đối tượng | Vai trò và quyền hạn |
|---|---|
| Quản trị viên (Admin) | Quản lý toàn bộ hệ thống, tài khoản, hội viên, gói tập, huấn luyện viên và báo cáo. |
| Nhân viên (Staff) | Quản lý hội viên, đăng ký gói tập, thanh toán và các hoạt động vận hành hằng ngày. |
| Huấn luyện viên (Trainer) | Quản lý lịch làm việc và các buổi tập được phân công. |
| Hội viên (Member) | Xem thông tin gói tập, đặt lịch tập và theo dõi lịch sử điểm danh. |

## 5. Công nghệ sử dụng
Các công nghệ được sử dụng trong quá trình phát triển hệ thống:
| Thành phần | Công nghệ |
|---|---|
| Frontend | Next.js, TypeScript |
| Giao diện người dùng | Tailwind CSS, Shadcn UI |
| Backend | [Công nghệ Backend] |
| Cơ sở dữ liệu | [Công nghệ Database] |
| Quản lý mã nguồn | Git, GitHub |
*Lưu ý: Cập nhật các công nghệ theo đúng cấu hình thực tế của dự án.*
## 6. Yêu cầu hệ thống

Để cài đặt và chạy dự án, máy tính cần đáp ứng các yêu cầu sau:

- Node.js (khuyến nghị phiên bản LTS).
- npm.
- Git.
- Trình duyệt web hiện đại.
- Các dịch vụ Backend và Database cần thiết đã được cấu hình.

## 7. Hướng dẫn cài đặt và chạy dự án

### Bước 1: Sao chép repository

```bash
git clone <repository-url>
```

### Bước 2: Di chuyển vào thư mục dự án

```bash
cd <ten-thu-muc-du-an>
```

### Bước 3: Cài đặt các thư viện cần thiết

```bash
npm install
```

### Bước 4: Cấu hình biến môi trường

Tạo file `.env.local` tại thư mục gốc của dự án và khai báo các biến môi trường cần thiết.

Ví dụ:

```env
NEXT_PUBLIC_API_URL=
DATABASE_URL=
```

Cập nhật giá trị phù hợp với cấu hình thực tế của hệ thống.

### Bước 5: Khởi chạy dự án

```bash
npm run dev
```

### Bước 6: Truy cập hệ thống

Mở trình duyệt và truy cập địa chỉ:

```text
http://localhost:3000
```

## 8. Cấu trúc thư mục dự án

Cấu trúc thư mục tham khảo:

```text
GymX/
├── public/                 # Chứa các tài nguyên tĩnh
├── src/
│   ├── app/                # Các trang và định tuyến
│   ├── components/         # Các thành phần giao diện
│   ├── hooks/              # Các React Hooks tùy chỉnh
│   ├── lib/                # Các hàm tiện ích và cấu hình
│   ├── services/           # Xử lý các dịch vụ và API
│   └── types/              # Khai báo kiểu dữ liệu TypeScript
├── .env.example            # Mẫu cấu hình biến môi trường
├── .gitignore
├── package.json
├── tsconfig.json
└── README.md
```

*Lưu ý: Cấu trúc trên mang tính minh họa, cần điều chỉnh theo cấu trúc mã nguồn thực tế.*

## 9. Thành viên thực hiện

Dự án được thực hiện bởi nhóm sinh viên trong khuôn khổ học phần phát triển phần mềm.

| STT | Họ và tên | Vai trò |
|---|---|---|
| 1 | [Họ và tên] | [Vai trò / Công việc] |
| 2 | [Họ và tên] | [Vai trò / Công việc] |
| 3 | [Họ và tên] | [Vai trò / Công việc] |
| 4 | [Họ và tên] | [Vai trò / Công việc] |

## 10. Giấy phép

Dự án được xây dựng phục vụ mục đích học tập và nghiên cứu trong khuôn khổ học phần tại trường đại học.

Mọi quyền đối với mã nguồn và tài liệu thuộc về nhóm phát triển.
