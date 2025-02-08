# 🏠 Fast Food Website MVC

🚀 **Fast Food Website MVC** - Backend API sử dụng **Node.js, Express.js, MongoDB**.  
---

## 📈 1. Cài đặt & Khởi chạy

### **🔹 Yêu cầu**
- Node.js `>= 14.x`
- MongoDB `>= 4.x`
- **NPM hoặc Yarn** để quản lý package

### **🔹 Cài đặt**
```bash
# Clone dự án
git clone https://github.com/phamdaiminhquan/fast-food-website.git
cd fast-food-website

# Cài đặt dependencies
npm install
```

### **🔹 Cấu hình `.env`**
Tạo file `.env` trong thư mục gốc và thêm:
```env
GOOGLE_CLIENT_ID=803563391879-011pu6ma02dc2ce2jd3sbaup51svdqgg.apps.googleusercontent.com
GOOGLE_CLIENT_SECRET=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
GOOGLE_CALLBACK_URL=http://localhost:3000/customer/login/google/callback
ACCESS_TOKEN_CUSTOMER_SECRET=abc123
SECRET_KEY=abc123
```

### **🔹 Chạy dự án**
```bash
# Chạy server
npm start
```
🚀 **Server sẽ chạy tại**: `http://localhost:3000`

---

## 📈 2. API Chính
# Trang Đăng Nhập quản lý và nhân viên
/admin/login
- Tài khoản ADMIN: buituantu171299@gmail.com MK: 123
- Tài khoản STAFF: yuutsu171299@gmail.com MK: 123
(đăng nhập đúng tài khoản sẽ chuyển đến trang staff hoặc admin)

# Trang đăng nhập dành cho khách hàng
/customer/login
- Tài khoản CUSTOMER: yuutsu230701@gmail.com MK: 123

---

📌 **Fast Food Website MVC đã sẵn sàng hoạt động! 🚀**

