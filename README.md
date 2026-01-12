<img width="1919" height="1078" alt="Screenshot 2026-01-05 164656" src="https://github.com/user-attachments/assets/42bcba05-c5cd-4fc4-922c-ab59639b5d14" />
#baitapkiemthuvoiJunit 
# Student Analyzer

## 📌 Giới thiệu
**Student Analyzer** là một project Java sử dụng **Maven** nhằm phân tích dữ liệu sinh viên  
(ví dụ: điểm số, xếp loại, thống kê…).  
Project có kèm **JUnit Test** để kiểm thử chức năng.

---

## 🗂️ Cấu trúc thư mục

kiemthuphanmem
├── src
│ ├── main
│ │ └── java
│ │ └── StudentAnalyzer.java
│ └── test
│ └── java
│ └── StudentAnalyzerTest.java
├── target
│ ├── classes
│ ├── test-classes
│ ├── surefire-reports
│ └── ...
├── pom.xml
└── README.md

yaml


---

## ⚙️ Công nghệ sử dụng
- Java  
- Maven  
- JUnit (kiểm thử đơn vị)
- VS Code / IntelliJ IDEA

---

## 🚀 Cách chạy project

### 1️⃣ Clone hoặc tải project
```bash
git clone <link-repo>
2️⃣ Di chuyển vào thư mục project
bash

cd kiemthuphanmem
3️⃣ Biên dịch project
bash

mvn clean compile
🧪 Chạy kiểm thử (JUnit)
bash

mvn test
📌 Kết quả test sẽ nằm trong thư mục:

bash

target/surefire-reports
📝 Mô tả các file chính
StudentAnalyzer.java
Chứa logic xử lý và phân tích dữ liệu sinh viên.

StudentAnalyzerTest.java
Chứa các test case để kiểm tra tính đúng đắn của các phương thức trong StudentAnalyzer.

📄 Yêu cầu hệ thống
JDK 8 trở lên

Maven 3.x

✨ Ghi chú
Đảm bảo đã cài Java và Maven trước khi chạy project

Có thể mở project trực tiếp bằng VS Code hoặc IntelliJ IDEA

👤 Tác giả
Sinh viên – Môn Kiểm thử phần mềm

yaml

---
