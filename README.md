# Tính bản đồ quân sự Gauss 🪖🧭

Chào mọi người! Mình là Khánh (K67 Computer Science). Đây là một trang web nhỏ mình tự code để hỗ trợ việc học tập và ôn thi môn **Giáo dục Quốc phòng - An ninh**, cụ thể là phần xác định các mảnh bản đồ quân sự lân cận theo hệ lưới chiếu Gauss.

Hồi đi học quân sự, phần tính toán mảnh bản đồ này khá nhức đầu và dễ nhầm lẫn khi làm bài tập hoặc thi cử. Vì thế mình quyết định làm công cụ này để check kết quả cho nhanh và chính xác hơn.

👉 **Link chạy thử (đã deploy Vercel):** [https://gauss-military.vercel.app/](https://gauss-military.vercel.app/)

---

## 🚀 Tính năng chính

Trang web giúp bạn tìm nhanh **mảnh bản đồ trung tâm** và **8 mảnh lân cận** (tổng cộng tạo thành lưới 3x3):
* Hỗ trợ nhập mã mảnh bản đồ từ 2 đến 6 cấp (từ đới/múi cho đến mảnh tỉ lệ nhỏ 1:10.000).
* Tự động validate dữ liệu khi nhập (ví dụ: đới vĩ độ phải là A-X, múi kinh độ từ 1-60, mảnh 1:100.000 từ 1-96, v.v.).
* Tự động chuyển focus sang ô tiếp theo khi nhập đủ ký tự để gõ cho nhanh.
* Giao diện responsive, dùng được cả trên điện thoại khi đang ở trên giảng đường hoặc thao trường.

---

## 🛠️ Công nghệ sử dụng

Dự án này siêu nhẹ vì mình viết hoàn toàn bằng **Vanilla HTML, CSS và JavaScript**, không dùng bất kỳ framework (React/Vue) hay thư viện ngoài nào để đỡ phải build cài đặt phức tạp:
* `index.html`: Chứa toàn bộ giao diện, style CSS (có hỗ trợ giao diện responsive, background quân sự) và logic JS xử lý thuật toán cộng trừ đới, múi, mảnh bản đồ.
* `background.jpg`: Ảnh nền quân sự.
* `vercel.json`: File cấu hình để deploy trực tiếp lên Vercel.

---

## 📖 Cách chạy local

Nếu muốn chạy offline hoặc chỉnh sửa code dưới máy:
1. Tải toàn bộ thư mục này về máy.
2. Click đúp vào file `index.html` để mở trực tiếp trên trình duyệt là xong (không cần cài `npm install` hay chạy server gì cả).

---

## 🤝 Liên hệ & Đóng góp

Vì thuật toán chia mảnh bản đồ Gauss này mình tự code dựa trên lý thuyết môn học, nếu bạn phát hiện ra trường hợp nào tính toán bị sai hoặc có lỗi giao diện, cứ thoải mái tạo Issue trên Github hoặc nhắn cho mình nhé:

* **Tác giả:** Lã Minh Khánh (K67 CS)
* **Facebook:** [Minh Khánh](https://www.facebook.com/strawberrymilktea.kelvin.0604/)
* **Linkedin:** [Lã Minh Khánh](https://www.linkedin.com/in/lakhanh231/)
* **Email:** lmkskycutehocgioi0604@gmail.com
