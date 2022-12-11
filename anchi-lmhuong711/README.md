
# AnChi
> **_Mobile development course Project [UET_2122II_INT3120_3]_** <br/>
> Vietnamese below: Tiếng Việt bên dưới <br/>
> Demo at the last of this page
<br/>

## 1. Introduction

### About project

- The app suggests dishes/restaurants randomly. Used to answer the questions "An chi?", "What to eat this afternoon?", "What to eat when hungry?", ...
- Filter dishes by ingredients, tags, and for restaurants by tag.

### About development team

- Include 3 members:
  + Dang Thi Thanh Hoa    https://github.com/dangthanhhoa
  + Le Minh Huong         https://github.com/lmhuong711
  + Nguyen Trong Thinh    https://github.com/ngtrthinh

<br/>

## 2. Clone project

### Requirements

- _Basic tools to run React Native_
- Nodejs
- Java SDK
- Android Studio
- Mobile emulator or mobile device

### Steps

- Clone project from github link:
  <br/>
  ```
  git clone https://github.com/lmhuong711/anchi
  ```
- On bash/Linux command line: (just run when first build on device)
  <br/>
  ```
  yarn || npm install
  npx react-native run-android || npm run android
  ```
- Wait a few minutes for the device to build AnChi app the first time.

- If there is any problem when building the app [this link](https://reactnative.dev/docs/environment-setup) should be enough to help you check it up.

- Run `npx react-native start || npm start` to start Metro. Metro will connect the code to the app on the device.

<br/>

## 3. Details

### The functions

Includes 05 main screens:
- Home page: Display random dishes || restaurants, click "See more" to see details.<br/>
  Press "❤️" to add to favorites list. Press "❎" to skip.<br/>
  Pressing and holding "❤️" will show a message dialog to add to favorites and move to the details page.<br/>
  Pressing and holding "❎" will show a message dialog to add to blacklist and switch to new dish || new restaurant.
- Add page: Add dishes || restaurants, add tags, ingredients, can add photos, can add multiple addresses for 01 dish.
- Favorite page: Show list of dishes || restaurants have been clicked "❤️". Can delete dishes || restaurants from the list.
- Filter page: filter dishes || restaurants by tags or ingredients.
- Menu page: Show user information, settings option and logout option.<br/>
  User information can be edited on this page.<br/>
  When choosing settings, will go to the settings page.

### Summary

- Currently the application can operate relatively stable.
- The application will pause development until at least 1 in 3 members have the passion for continuing.
- Development:
   + Login + registration + data storage in the cloud + synchronization between devices.
   + Dark screen mode setting.
   + ...

---
> **_Note:_** runs on Android is oke, on iOS, I haven't tried <(")
---

<br/>
<br/>
<br/>
<br/>
<br/>
<br/>

# AnChi
> **_Bài tập lớn môn Phát triển ứng dụng di động [UET_2122II_INT3120_3]_** <br/>
> Demo ở dưới cùng trang này

<br/>

## 1. Giới thiệu

### Về ứng dụng

- Ứng dụng gợi ý món ăn/quán ăn một cách ngẫu nhiên. Dùng để trả lời câu hỏi "Ăn chi?", "Trưa nay ăn gì?", "Đói quá ăn gì giờ?", ... 
- Lọc món ăn theo nguyên liệu, thẻ tag, lọc quán ăn theo thẻ tag.

### Về nhóm phát triển

- Gồm 3 thành viên:
  + Đặng Thị Thanh Hoa    https://github.com/dangthanhhoa
  + Lê Minh Hương         https://github.com/lmhuong711
  + Nguyễn Trọng Thịnh    https://github.com/ngtrthinh

<br/>

## 2. Clone lại project

### Yêu cầu

- _Các công cụ cơ bản để chạy React Native_
- Nodejs
- Java SDK
- Android Studio
- Thiết bị Giả lập di động hoặc 1 thiết bị di động

### Các bước thực hiện

- Clone project về máy:
  <br/>
  ```
  git clone https://github.com/lmhuong711/anchi
  ```
- Trên bash/Linux command line: (chỉ cần chạy khi lần đầu build trên thiết bị)
  <br/>
  ```
  yarn || npm install
  npx react-native run-android || npm run android
  ```
- Chờ vài phút để thiết bị build phần mềm lần đầu.

- Nếu gặp vấn đề khi build app, làm theo [đường dẫn này](https://reactnative.dev/docs/environment-setup) để kiểm tra lại xem bạn đã bỏ sót điểm nào.

- Chạy `npx react-native start || npm start` để khởi động Metro. Metro sẽ kết nối code với app trên thiết bị.

<br/>

## 3. Thông tin chi tiết

### Chức năng

Gồm 5 màn chính:
- Trang chủ: Hiện ngẫu nhiên món ăn || quán ăn, bấm "Xem thêm" để xem chi tiết.<br/>
  Bấm "❤️" để thêm vào danh sách yêu thích. Bấm "❎" để bỏ qua.<br/>
  Bấm và giữ "❤️" sẽ hiện thông báo thêm vào danh sách yêu thích và chuyển trang chi tiết.<br/>
  Bấm và giữ "❎" sẽ hiện thông báo thêm vào danh sách đen và chuyển món ăn || quán ăn mới.
- Trang thêm: Thêm món ăn || quán ăn, thêm thẻ tag, nguyên liệu, có thể thêm ảnh, có thể thêm nhiều địa chỉ cho 1 món ăn.
- Trang yêu thích: Hiện danh sách món ăn || quán ăn đã được bấm "❤️". Có thể xóa món ăn || quán ăn khỏi danh sách.
- Trang lọc: lọc món ăn || quán ăn theo thẻ tag hoặc nguyên liệu.
- Trang tùy chỉnh: Hiện thông tin người dùng, thanh cài đặt và đăng xuất.<br/>
  Có thể sửa thông tin người dùng ở trang này.<br/>
  Khi chọn cài đặt, sẽ chuyển sang trang cài đặt.

### Tổng kết

- Hiện tại ứng dụng đã có thể hoạt động tương đối ổn định.
- Ứng dụng sẽ tạm dừng phát triển cho đến khi 1 trong 3 thành viên có đam mê tiếp tục.
- Hướng phát triển:
  + Đăng nhập + đăng ký + lưu trữ dữ liệu trên cloud + đồng bộ hóa giữa các thiết bị.
  + Cài đặt chế độ màn hình tối.
  + ...

---
> **_Ghi chú:_**  chạy trên Android oke, iOS thì mình chưa thử <(")
---

# Demo

https://user-images.githubusercontent.com/63858040/170712772-5b2eb990-9a78-42ca-9960-579c8da81fc9.mp4


