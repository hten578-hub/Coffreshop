<div align="center">

# COFFEE SHOP MOBILE APP DESIGN

### Nguyễn Thị Huệ Minh

### MSSV: 23810310177

</div>

---

## Giới thiệu

Đây là project thực hành **Coffee Shop Mobile App Design** được xây dựng bằng **React Native (Expo)** dựa trên giao diện thiết kế Figma.

Ứng dụng mô phỏng app bán cà phê trên thiết bị di động với các màn hình chính:

* Onboarding Screen
* Home Screen
* Detail Screen

Project đáp ứng đầy đủ yêu cầu bài thực hành về giao diện, điều hướng màn hình và xử lý dữ liệu JSON.

---

## Công nghệ sử dụng

* React Native
* Expo
* React Navigation
* JavaScript
* JSON

---

## Chức năng chính

### Onboarding Screen

* Hiển thị màn hình giới thiệu ứng dụng
* Nút bắt đầu để chuyển vào trang chính

### Home Screen

* Hiển thị danh sách sản phẩm cà phê
* Lấy dữ liệu từ file `data.json`

### Detail Screen

* Hiển thị thông tin chi tiết sản phẩm
* Tên sản phẩm
* Giá tiền
* Hình ảnh minh họa

### Navigation

* Stack Navigator
* Bottom Tabs Navigator

---

## Cấu trúc thư mục

```bash id="jjlwmx"
CoffeeShopApp
│── App.js
│── data.json
│── package.json
│── navigation
│   └── BottomTabs.js
│── screens
│   ├── OnboardingScreen.js
│   ├── HomeScreen.js
│   └── DetailScreen.js
```

---

## Cài đặt và chạy project

### Clone source code

```bash id="uk3f90"
git clone <YOUR_GITHUB_LINK>
```

### Cài dependencies

```bash id="6ok6v6"
npm install
```

### Chạy ứng dụng

```bash id="n36vxh"
npx expo start
```

---

## Kết quả giao diện

### Onboarding Screen

<img width="720" height="1600" alt="image" src="https://github.com/user-attachments/assets/0d819f0d-4d7a-4f4d-ad9f-c5ec3bf8d993" />


### Home Screen

<img width="720" height="1600" alt="image" src="https://github.com/user-attachments/assets/09ad13d7-0db3-48be-b1ef-4c76ecde916c" />


### Detail Screen

<img width="720" height="1600" alt="image" src="https://github.com/user-attachments/assets/7b96f346-8478-4532-b827-2b0e545b028f" />

---

## Video Demo

https://drive.google.com/file/d/1yhegy0ZPG4-H55YXaudQPt238GnmD6h_/view?usp=drive_link

---

## Đánh giá hoàn thành

✅ Hoàn thiện layout các màn hình
✅ Sử dụng Stack Navigator
✅ Sử dụng Bottom Tabs Navigator
✅ Load dữ liệu từ `data.json`
✅ Giao diện hoạt động tốt
✅ Có ảnh chụp từng màn hình
✅ Có video demo

---

<div align="center">

### Thực hành ngày 22/04/2026

</div>
