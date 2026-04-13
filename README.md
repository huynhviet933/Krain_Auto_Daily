# Krain_Auto_Daily
HƯỚNG DẪN CÀI ĐẶT VÀ SỬ DỤNG TOOL KRAIN AI (VERSION LICENSE + PROXY)

1. YÊU CẦU HỆ THỐNG
- Cài đặt Node.js phiên bản mới nhất (Khuyên dùng v18 hoặc v20+).
- Một trình soạn thảo code (VS Code, Notepad++, v.v.)

2. DANH SÁCH THƯ VIỆN CẦN CÀI ĐẶT
Mở Terminal/CMD tại thư mục tool và chạy lệnh sau:

npm install axios chalk ethers https-proxy-agent socks-proxy-agent uuid moment-timezone p-limit node-machine-id

3. CẤU TRÚC THƯ MỤC FILE CẦN THIẾT
Bạn cần tạo các file sau trong cùng một thư mục với file p2.js:

- main2.js          : File code chính (đã tích hợp License).
- privatekey.txt : Chứa danh sách Private Key (mỗi dòng 1 key).
- proxy.txt      : Chứa danh sách Proxy (mỗi dòng 1 proxy). 
                   Định dạng: http://user:pass@ip:port hoặc socks5://ip:port
                   *Lưu ý: Tool này bắt buộc phải có Proxy.
- User_agents.txt: Chứa danh sách User Agent (mỗi dòng 1 cái).
- config.json    : File cấu hình thông số chạy tool.

4. NỘI DUNG FILE config.json (MẪU)
Tạo file config.json và dán nội dung này vào:

{
  "threads": 5,
  "delay_start_thread": 2,
  "delay_action_min": 5,
  "delay_action_max": 10,
  "delay_next_acc_min": 30,
  "delay_next_acc_max": 60,
  "auto_bind_email": true,
  "reset_hour_vn": 7
}

5. CÁCH VẬN HÀNH TOOL
Bước 1: Mở CMD/Terminal tại thư mục chứa tool.
Bước 2: Chạy lệnh: node p2.js
Bước 3: Ở lần đầu chạy, tool sẽ yêu cầu nhập "License Key". 
        Hãy nhập Key của bạn và nhấn Enter.
Bước 4: Key sẽ được lưu vào file license.txt, lần sau bạn không cần nhập lại.

6. CÁC FILE TỰ ĐỘNG SINH RA
- license.txt    : Lưu key bản quyền của bạn.
- profiles.json  : Lưu thông tin profile (Username, Bio, Email) của từng ví.
- last_index.txt : Lưu vị trí ví đang chạy để nếu tool lỗi có thể chạy tiếp.

================================================================================
LƯU Ý QUAN TRỌNG:
- Tool bắt buộc phải có Proxy để hoạt động (theo logic code main.js).
- Nếu bị lỗi "Named export 'machineIdSync' not found", hãy đảm bảo bạn đã dùng 
  bản code mới nhất tôi đã fix lỗi import cho bạn.
- Key License gắn liền với HWID máy (Mỗi máy 1 key hoặc theo quy định server).
================================================================================

Tham Gia NHóm tele : https://t.me/HVchannelss

Tham Gia Discor ( Vip ) : https://discord.gg/gKxvTNu5

Tham gia NHóm VIp Với Chi Phí 1 Tháng 4u - 15u 6thang Lợi ích tham gia nhóm ViP Sẽ được cấp keey sử dụng các tool vip trong discor hỗ trợ Và tham khao Code các tool dự án mà các bạn đề xuất

Gửi Phí tháng vào đây và chụp hình gửi trực tiếp cho tôi tại discor để xác nhận Role VIp ☕ https://huynhviet933.github.io/donate_viet_mmo/ Có thể tặng tôi ít cafe tại đây
