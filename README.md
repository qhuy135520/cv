# 🛒 E-commerce BAP Project

## 🚀 Cách chạy dự án

### 1. Clone source code

```bash
git clone https://github.com/qhuy135520/e-commerce-bap
cd e-commerce-bap
2. Cài đặt dependencies
bash
Copy code
npm install
3. Tạo file .env
Nội dung file .env sẽ được chi tiết nội bộ trong team.

Copy từ .env.example nếu có, rồi điền các giá trị thật.

4. Chạy dự án
bash
Copy code
npm run dev
👉 Mặc định frontend chạy tại:
http://localhost:5173

📅 Quy trình Daily Scrum
Mỗi ngày team thực hiện Daily Scrum với 3 câu hỏi:

Hôm qua tôi đã làm gì?

Hôm nay tôi sẽ làm gì?

Có gặp trở ngại gì không?

Tiến độ cập nhật trực tiếp trong GitHub Project Board:

vbnet
Copy code
To Do → In Progress → Review → Done
🔀 Quy tắc Git Workflow
1. Branch Naming
Tính năng mới: feature/<tên-tính-năng>
Ví dụ: feature/user-authentication

Fix bug: bugfix/<mã-bug>
Ví dụ: bugfix/login-500-error

Hotfix (fix khẩn cấp): hotfix/<mã-lỗi>
Ví dụ: hotfix/cart-price-error

2. Commit Message Format
less
Copy code
[yyyy-MM-dd][type]: [mô tả ngắn gọn]
Ví dụ:

makefile
Copy code
2025-08-29-feat: thêm chức năng đăng ký tài khoản
2025-08-29-fix: sửa lỗi không load được giỏ hàng
2025-08-29-docs: cập nhật README
3. Pull Request (PR)
Tạo PR từ branch → develop

Yêu cầu review chéo giữa các thành viên khác trong team

PR chỉ được tạo khi task đã chuyển sang Review trong Kanban Board

❌ Không được merge trực tiếp vào develop

📌 Luồng làm việc trong GitHub
Issues (Product Backlog)

Tạo issue cho mỗi task/bug/feature

Gắn label: feature, bug, priority-high…

Milestones (Sprint Backlog)

Gom các issues vào milestone theo Sprint

Projects (Scrum Board)

Quản lý tiến độ qua board:

vbnet
Copy code
To Do → In Progress → Review → Done
Branches & Code

Tạo branch theo quy tắc

Code xong → push → tạo Pull Request

Review & Merge

Reviewer xem code → approve → merge vào develop

Cuối sprint → merge develop

📷 Demo Screenshot

<img width="1919" height="962" alt="Git-Work" src="https://github.com/user-attachments/assets/c15f4c28-0fb5-480d-9822-040ed3253c8d" />

👨‍💻 Team Rules
❌ Không commit trực tiếp vào develop

✅ Luôn tạo Pull Request và yêu cầu review trước khi merge

✅ Cập nhật tiến độ mỗi ngày trong board

✅ Luôn viết commit message rõ ràng, có ý nghĩa
```
