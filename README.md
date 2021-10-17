# React Native

## Môi trường (dành cho Windows)
- NodeJS
- JDK 11 - LTS (React Native chưa tương thích với bản JDK mới nhất)

https://www.oracle.com/java/technologies/downloads/#java11

- Visual Studio Code
- React Native Debugger (Được viết bằng ElectronJS nên dùng y hệt Chrome Devtool) 

https://github.com/jhen0409/react-native-debugger/releases

- Android Studio (để build app)

## Setup
- Mình sẽ dùng React Native Cli chứ không dùng Expo vì Expo quá hạn chế
- Docs: https://www.reactnative.dev/docs/environment-setup

## Kiến thức nền tảng

React Native thực chất chỉ là sử dụng JavaScript làm cầu nối để gọi đến các thành phần Native của hệ điều hành Android/iOS. Nên dù là 1 component vẫn sẽ xảy ra các trường hợp code chạy đúng trên Android nhưng lại chưa đúng trên iOS hoặc ngược lại. Vậy nên khi code app cần test cả 2

### Để code được React Native cần
- JavaScript (Pushsale và Cuccu đang sử dụng)
- [Optional] Typescript (KhoDuoc và Chimcat đang sử dụng)
- ReactJS cơ bản (rất quan trọng vì React Native chỉ là ReactJS + Native)
- React Native cơ bản
- CSS Flexbox từ Web
Chỉ khác là mặc định flexDirection của React Native là chiều dọc, còn trên CSS là chiều ngang. Có thể nghiên cứu Styled-component để sử dụng style y hệt như Web)
- Redux cơ bản (Pushsale và Cuccu đang sử dụng)
Redux là state-management để quản lý state toàn app. Đặc thù của React là không thể giao tiếp giữa 2 component ngang hàng, nếu muốn giao tiếp thì phải truyền dữ liệu từ component A lên component cha rồi truyền xuống component con.

*Bên Angular cũng có thư viện tương tự như Redux là NgRx*

- Redux-toolkit (KhoDuoc và Chimcat đang sử dụng)
Là cải tiến của Redux giúp code gọn hơn rất nhiều
- React Navigation

Dùng để di chuyển giữa các màn hình

- Redux-thunk

Là middleware trong Redux, thường dùng để fetch API và lưu dữ liệu vào Redux.

## Tài liệu tham khảo
- React Native: https://www.reactnative.dev/
- React Navigation: https://reactnavigation.org/
- Redux-toolkit: https://redux-toolkit.js.org/
- ReactJS Cheatsheet: https://github.com/typescript-cheatsheets/react
- React Hook Cheatsheet: https://react-hooks-cheatsheet.surge.sh/
- Redux Cheatsheet: http://www.developer-cheatsheets.com/redux
- Từ điển: https://openai.gitbook.io/code-cheatsheets/
