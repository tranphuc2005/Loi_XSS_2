# Bài Tập Tuần 2: Cross-Site Scripting (XSS)

## Mô Tả Bài Tập
Bài tập này nhằm mục đích tìm hiểu và khai thác lỗ hổng XSS thông qua việc nghiên cứu các writeup, thực hành khai thác trên source code bài tập, vượt qua các challenge và đánh giá các công cụ tự động phát hiện lỗ hổng XSS.

## Yêu Cầu Bài Tập

### 1. Nghiên cứu và thống kê 100 Writeup về XSS
- Tìm và liệt kê ít nhất 100 writeup khai thác lỗ hổng XSS.
- Gồm các writeup về lỗ hổng XSS tại Apple, Facebook, Microsoft,...
- Writeup từ các cuộc thi CTF trên [CTFtime](https://ctftime.org/) hoặc HackTheBox.
- Liệt kê theo dạng danh sách link tương tự như: [Facebook Bug Bounty Writeups](https://github.com/jaiswalakshansh/Facebook-BugBounty-Writeups).
- Lựa chọn 05 bài phân tích hay nhất và giải thích lý do lựa chọn.

### 2. Thực hành khai thác XSS trên source code
- **2.1. Khai thác XSS:** Sử dụng [XSS Hunter](https://xsshunter.com/) khai thác lỗ hổng trong source code web bài tập:
  - Lấy cookie của người dùng khác.
  - Chụp ảnh màn hình khi nạn nhân truy cập.
- **2.2. Fix lỗi XSS:** Triển khai các giải pháp phòng chống XSS tại vị trí bị lỗi.

### 3. Vượt qua các challenge XSS
- Hoàn thành các challenge về XSS trên [PortSwigger Web Security Academy](https://portswigger.net/web-security) và HackTheBox.

### 4. Đánh giá các công cụ tự động phát hiện XSS
- Tìm hiểu và so sánh tính năng quét lỗ hổng XSS của BurpSuite và các tool trên GitHub.
- Đánh giá đặc điểm, điểm mạnh, điểm yếu của từng công cụ.

## Cài Đặt và Cách Chạy Tool
- Các tool được sử dụng trong bài tập:
  - [XSS Hunter](https://xsshunter.com/)
  - [BurpSuite](https://portswigger.net/burp)
  - [KNOXSS](https://knoxss.me/)
  - [DalFox](https://github.com/hahwul/dalfox)
  - [XSStrike](https://github.com/s0md3v/XSStrike)

## Tài Liệu Tham Khảo
- [PortSwigger Web Security Academy](https://portswigger.net/web-security)
- [CTFtime](https://ctftime.org/)
- [OWASP XSS Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Cross_Site_Scripting_Prevention_Cheat_Sheet.html)
- [Google XSS Game](https://xss-game.appspot.com/)

