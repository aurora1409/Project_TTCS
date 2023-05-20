# Project_TTCS: 
## Trang web ReactJS sử dụng BE kết nối CSDL MySQL tích hợp rasa chatbot về giải thuật toán BFS, UCS và trả lời các câu hỏi liên quan đến 2 thuật toán này

Project bao gồm 3 phần:
+ Giao diện react.js
+ Back-end Java Spring Boot
+ Chatbot Rasa 

### Chạy project:
1. Chạy back-end ở "D:\Data PTIT\ProjTTCS\spring-jdbc\src\main\java\com\example\springjdbc\Products"
2. Chạy rasa chatbot:
  + rasa run actions: Chạy các action
  + rasa run -m models --enable-api --cors "*" : chạy rasa chatbot
  + Nếu muốn test trên terminal chạy lệnh rasa shell thay vì lệnh trên
  + rasa train nlu: train nlu
  + rasa train nlu --config configVietnamese.yml: trong TH file config mình tự tạo chứ không dùng file mặc định
  + rasa train core: train core
  + rasa shell nlu: test nlu trên terminal
  + rasa train --force: train all dữ liệu lại từ đầu
4. Chạy React.js:
  + npm i: Tải node-modules về
  + npm start: Chạy app
