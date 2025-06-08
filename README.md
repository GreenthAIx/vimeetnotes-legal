# 📋 ViMeetNotes Legal Documents

Các tài liệu pháp lý cho ứng dụng ViMeetNotes, sẵn sàng để deploy miễn phí.

## 📁 File Structure
```
legal-docs/
├── privacy-policy.html    # Chính sách bảo mật
├── terms-of-service.html  # Điều khoản sử dụng
└── README.md             # Hướng dẫn này
```

## 🚀 CÁCH DEPLOY MIỄN PHÍ

### Option 1: GitHub Pages (RECOMMENDED) ⭐
```bash
# 1. Tạo repo mới trên GitHub
# Tên: vimeetnotes-legal (public)

# 2. Upload files
git init
git add .
git commit -m "Add legal documents"
git remote add origin https://github.com/YOUR_USERNAME/vimeetnotes-legal.git
git push -u origin main

# 3. Enable GitHub Pages
# Vào Settings > Pages > Source: Deploy from a branch > main

# 4. URLs sẽ là:
# https://YOUR_USERNAME.github.io/vimeetnotes-legal/privacy-policy.html
# https://YOUR_USERNAME.github.io/vimeetnotes-legal/terms-of-service.html
```

### Option 2: Netlify (Drag & Drop)
```bash
# 1. Vào netlify.com
# 2. Drag folder legal-docs vào "Deploy manually"
# 3. URLs sẽ là:
# https://RANDOM-NAME.netlify.app/privacy-policy.html
# https://RANDOM-NAME.netlify.app/terms-of-service.html
```

### Option 3: Vercel
```bash
# 1. Vào vercel.com
# 2. Import GitHub repo
# 3. Deploy tự động
```

## ✏️ CUSTOMIZATION

### Cập nhật thông tin:
1. Thay `[Ngày tháng năm 2025]` bằng ngày hiện tại
2. Xác nhận email: `greenth.aix@gmail.com`
3. Thêm thông tin công ty nếu cần

### Thay đổi styling:
- Màu chủ đạo: `#007AFF` (iOS Blue)
- Font: Apple system fonts
- Responsive design cho mobile

## 📱 SỬ DỤNG TRONG APP

Sau khi deploy, cập nhật URLs trong ứng dụng:

```swift
// Trong AboutView.swift hoặc SettingsView.swift
let privacyPolicyURL = "https://YOUR_USERNAME.github.io/vimeetnotes-legal/privacy-policy.html"
let termsOfServiceURL = "https://YOUR_USERNAME.github.io/vimeetnotes-legal/terms-of-service.html"
```

## ⚖️ LEGAL COMPLIANCE

### App Store Requirements ✅
- [x] Privacy Policy URL
- [x] Terms of Service URL  
- [x] Support contact email
- [x] Vietnamese + English content
- [x] Mobile-responsive design

### GDPR Compliance ✅
- [x] Data collection transparency
- [x] User rights explanation
- [x] Data retention policy
- [x] Contact information for requests

## 🔄 MAINTENANCE

### Khi nào cập nhật:
- Thay đổi tính năng ứng dụng
- Thêm dịch vụ bên thứ ba mới
- Cập nhật chính sách Apple
- Phản hồi từ App Store Review

### Version control:
- Giữ lịch sử thay đổi trong Git
- Tag major changes
- Backup before updates

---

**📧 Contact:** greenth.aix@gmail.com  
**🇻🇳 Made in Vietnam** 