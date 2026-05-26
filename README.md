# 🏥 AI-Integrated Multi-Specialty Clinic Management System
## Hệ Thống Quản Lý Phòng Khám & Bệnh Viện Thông Minh Tích Hợp AI

---

# 📌 1. Thông tin nhóm phát triển

| STT | Thành viên | Vai trò | Nhiệm vụ chính |
|---|---|---|---|
| 1 | **Nguyễn Mạnh Cường** | Project Manager / Fullstack Developer | Thiết kế kiến trúc hệ thống, phát triển API trung tâm, tích hợp AI hỗ trợ chẩn đoán và quản lý tiến độ dự án |
| 2 | **Hồ Hữu Tính** | Frontend Developer | Xây dựng giao diện Web/Mobile, tối ưu trải nghiệm người dùng, tích hợp chức năng QR Check-in |
| 3 | **Nguyễn Đình Khôi** | Business Analyst & QA | Phân tích yêu cầu, xây dựng tài liệu SRS, thiết kế Use Case và thực hiện kiểm thử hệ thống |
| 4 | **Nguyễn Huy Hoàng** | Backend Developer | Thiết kế cơ sở dữ liệu, phát triển hệ thống RBAC và quản lý hàng đợi khám bệnh |
| 5 | **Phan Đình Bản** | Backend Developer | Xây dựng EMR, quản lý hồ sơ bệnh nhân, thanh toán và xử lý dữ liệu y tế |

---

# 📖 2. Giới thiệu dự án

## 2.1 Tổng quan hệ thống

Hiện nay, nhiều bệnh viện và phòng khám vẫn còn phụ thuộc vào các quy trình thủ công như:

- Quản lý hồ sơ giấy
- Đặt lịch trực tiếp tại quầy
- Dữ liệu bệnh nhân phân tán
- Thời gian chờ khám kéo dài
- Khó đồng bộ giữa các khoa phòng

Nhằm giải quyết những hạn chế trên, nhóm phát triển hệ thống:

# **AI-Integrated Multi-Specialty Clinic Management System**

Một nền tảng quản lý bệnh viện hiện đại giúp số hóa toàn bộ quy trình khám chữa bệnh, từ tiếp nhận bệnh nhân cho đến quản trị vận hành và hỗ trợ AI.

---

## 🎯 Mục tiêu hệ thống

Hệ thống được xây dựng nhằm:

- Tối ưu hóa quy trình khám chữa bệnh
- Giảm thao tác thủ công cho nhân viên
- Nâng cao trải nghiệm bệnh nhân
- Tăng hiệu quả vận hành bệnh viện
- Ứng dụng AI trong lĩnh vực y tế thông minh

---

## 🧩 Các phân hệ chính

Hệ thống bao gồm:

- Đặt lịch khám online
- Quản lý hồ sơ bệnh án điện tử (EMR)
- QR Check-in bệnh nhân
- Quản lý hàng chờ khám
- Quản lý bác sĩ và chuyên khoa
- Thanh toán viện phí online
- Dashboard & báo cáo thống kê
- AI hỗ trợ chẩn đoán và kê đơn

---

# 💡 2.2 Lý do chọn đề tài

## Nhu cầu thực tế

Người dùng hiện đại có nhu cầu:

- Đặt lịch khám từ xa
- Theo dõi hồ sơ sức khỏe trực tuyến
- Thanh toán không tiền mặt
- Nhận kết quả xét nghiệm online

Hệ thống giúp giảm thời gian chờ và tăng tính thuận tiện cho bệnh nhân.

---

## Khả năng ứng dụng

Phần mềm có thể triển khai cho:

- Phòng khám tư nhân
- Bệnh viện đa khoa
- Trung tâm y tế
- Chuỗi phòng khám chuyên khoa

---

## Giá trị học thuật

Dự án áp dụng nhiều công nghệ và mô hình hiện đại:

- RESTful API
- RBAC (Role-Based Access Control)
- Queue Management System
- QR Code Check-in
- EMR (Electronic Medical Record)
- AI Clinical Support
- Sentiment Analysis

---

## Tích hợp AI trong y tế

AI được sử dụng để:

- Gợi ý chuyên khoa phù hợp
- Phân tích triệu chứng ban đầu
- Hỗ trợ kê đơn an toàn
- Cảnh báo tương tác thuốc
- Phân tích phản hồi bệnh nhân

---

# 👥 3. Đối tượng sử dụng hệ thống

| Tác nhân | Chức năng |
|---|---|
| Patient | Bệnh nhân sử dụng dịch vụ khám chữa bệnh |
| Doctor | Bác sĩ khám và điều trị |
| Receptionist | Nhân viên tiếp nhận |
| Admin | Quản trị viên hệ thống |
| AI Service | Dịch vụ AI hỗ trợ xử lý dữ liệu |

---

# ⚙️ 4. Chức năng hệ thống

# 4.1 Chức năng dành cho Patient

## 🔐 Xác thực tài khoản

- Đăng ký tài khoản
- Đăng nhập Email / Google
- Xác thực Email hoặc số điện thoại
- Quên mật khẩu

## 👤 Quản lý hồ sơ cá nhân

- Cập nhật thông tin cá nhân
- Quản lý BHYT
- QR Code Check-in cá nhân

## 📅 Đặt lịch khám

- Xem danh sách bác sĩ
- Chọn chuyên khoa khám
- Đặt và hủy lịch hẹn
- Theo dõi trạng thái khám realtime

## 🩺 Hồ sơ bệnh án

- Xem lịch sử khám bệnh
- Theo dõi đơn thuốc
- Xem kết quả xét nghiệm
- Tải PDF hồ sơ bệnh án

## 💳 Thanh toán

- Thanh toán online
- Quản lý lịch sử giao dịch

## 🔔 Thông báo

- Nhắc lịch khám
- Nhắc uống thuốc
- Thông báo kết quả xét nghiệm
- Email & In-App Notification

## ⭐ Đánh giá dịch vụ

- Đánh giá bác sĩ
- Gửi phản hồi chất lượng khám chữa bệnh

---

# 4.2 Chức năng dành cho Doctor

## 📋 Quản lý lịch khám

- Xem lịch làm việc
- Xác nhận hoặc hủy lịch khám
- Tạo lịch khám cá nhân
- Theo dõi trạng thái lịch hẹn

## 🧾 Quản lý bệnh án

- Xem hồ sơ bệnh nhân
- Cập nhật kết quả khám
- Upload xét nghiệm
- Kê đơn thuốc

## 🤖 Hỗ trợ AI

- AI gợi ý chẩn đoán
- AI phân tích triệu chứng
- AI cảnh báo tương tác thuốc
- AI hỗ trợ kê đơn

## 📊 Dashboard

- Thống kê bệnh nhân
- Biểu đồ khám bệnh
- Theo dõi lịch khám trong ngày

---

# 4.3 Chức năng dành cho Receptionist

## 🏥 Tiếp nhận bệnh nhân

- Tạo hồ sơ bệnh nhân
- Xác nhận lịch khám
- QR Check-in nhanh

## 💰 Quản lý thanh toán

- Tạo hóa đơn viện phí
- In hóa đơn
- Xác nhận thanh toán

## ⏳ Quản lý vận hành

- Điều phối phòng khám
- Quản lý hàng chờ khám bệnh

---

# 4.4 Chức năng dành cho Admin

## 👨‍💼 Quản lý người dùng

- Quản lý tài khoản
- Reset mật khẩu
- Khóa/Mở tài khoản
- Quản lý nhân sự

## 🔐 RBAC & Permission

- Tạo Role
- Gán Permission
- Phân quyền tài khoản

## 🏢 Quản lý bệnh viện

- Quản lý bác sĩ
- Quản lý chuyên khoa
- Quản lý phòng khám

## 📈 Dashboard & Reports

- Thống kê bệnh nhân
- Báo cáo doanh thu
- Theo dõi hoạt động hệ thống

## 📝 Audit Logs

- Theo dõi lịch sử thao tác
- Kiểm tra hoạt động người dùng

---

# 4.5 Chức năng AI

## 🤖 AI Chatbot

- Trả lời câu hỏi thường gặp
- Hỗ trợ đặt lịch khám
- Hướng dẫn sử dụng hệ thống

## 🧠 Smart Recommendation

- Gợi ý chuyên khoa
- Gợi ý bác sĩ phù hợp

## 📊 AI Health Analysis

- Phân tích triệu chứng
- Đánh giá nguy cơ sức khỏe
- Hỗ trợ bác sĩ chẩn đoán

## ⚡ AI Automation

- Gợi ý lịch khám phù hợp
- Nhắc tái khám
- Nhắc uống thuốc
- Phân loại mức độ ưu tiên bệnh nhân
- Phân tích phản hồi người dùng

---

# 🗂️ 5. Quản lý dự án bằng Jira

Dự án được phát triển theo mô hình Agile/Scrum nhằm dễ dàng quản lý tiến độ và phân chia Sprint.

## 🔗 Jira Board

- Theo dõi tiến độ task
- Quản lý Sprint
- Review & Testing workflow
- Quản lý deadline thành viên

---

## 🔄 Workflow Sprint

```text
Product Backlog
      ↓
Sprint Planning
      ↓
To Do
      ↓
In Progress
      ↓
Code Review
      ↓
Testing
      ↓
Done
```

---

# 🎨 6. Thiết kế giao diện

## Figma Design

Hệ thống giao diện được thiết kế bằng Figma với định hướng:

- Hiện đại
- Dễ sử dụng
- Tối ưu trải nghiệm người dùng
- Responsive trên nhiều thiết bị

---

# 📁 6.1 Cấu trúc thư mục Frontend

```text
frontend/
│
├── public/
│   ├── images/
│   ├── icons/
│   └── qr/
│
├── src/
│   ├── components/
│   │   ├── common/
│   │   ├── ui/
│   │   ├── tables/
│   │   ├── modals/
│   │   └── qr-scanner/
│   │
│   ├── views/
│   │   ├── patient/
│   │   ├── doctor/
│   │   ├── receptionist/
│   │   └── admin/
│   │
│   ├── services/
│   │   ├── api/
│   │   ├── auth/
│   │   ├── ai-services/
│   │   └── notifications/
│   │
│   ├── store/
│   │   ├── auth/
│   │   ├── patient/
│   │   ├── appointment/
│   │   └── queue/
│   │
│   ├── hooks/
│   ├── routes/
│   ├── layouts/
│   ├── utils/
│   ├── constants/
│   └── assets/
│
├── package.json
└── README.md
```

---

# 🛠️ 7. Công nghệ sử dụng

| Thành phần | Công nghệ áp dụng |
|---|---|
| Frontend | ReactJS / NextJS |
| Backend | NodeJS / ExpressJS |
| Database | PostgreSQL / MySQL |
| Authentication | JWT / OAuth2 |
| State Management | Redux Toolkit |
| UI Framework | TailwindCSS / Material UI |
| AI Integration | OpenAI API / Machine Learning |
| Realtime | Socket.IO |
| Cloud Storage | Firebase / AWS S3 |
| Version Control | GitHub |

---

# 📊 8. So sánh với hệ thống khác

| Tính năng | Practo | Hello Bacsi | Hệ thống nhóm |
|---|---|---|---|
| Đặt lịch khám | ✅ | ✅ | ✅ |
| Hồ sơ bệnh án điện tử | ✅ | Hạn chế | ✅ |
| AI Chatbot | Hạn chế | ✅ | ✅ |
| AI hỗ trợ chẩn đoán | ❌ | Hạn chế | ✅ |
| QR Check-in | ❌ | ❌ | ✅ |
| RBAC | ❌ | ❌ | ✅ |
| Quản lý hàng chờ | ❌ | ❌ | ✅ |
| Dashboard quản trị | Hạn chế | ❌ | ✅ |
| Tối ưu cho bệnh viện Việt Nam | Chưa tối ưu | Có | Có |

---

# ✅ 9. Kết luận

**AI-Integrated Multi-Specialty Clinic Management System** là giải pháp quản lý bệnh viện hiện đại giúp số hóa toàn diện quy trình khám chữa bệnh và tăng hiệu quả vận hành nhờ tích hợp AI.

## 🌟 Giá trị hệ thống mang lại

- Tối ưu quy trình khám chữa bệnh
- Quản lý hồ sơ bệnh án tập trung
- Hỗ trợ bác sĩ bằng AI
- Nâng cao trải nghiệm bệnh nhân
- Tăng hiệu suất vận hành bệnh viện

---

## 🚀 Hướng phát triển tương lai

Trong tương lai, hệ thống có thể mở rộng thêm:

- Telemedicine
- AI Deep Diagnosis
- IoT Medical Devices
- National Healthcare Integration
- Smart Healthcare Analytics
