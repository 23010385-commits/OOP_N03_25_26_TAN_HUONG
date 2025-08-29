Project – Ứng dụng Quản lý Học Guitar 🎸
Yêu cầu chính

Giao diện: Java Spring Boot (REST API hoặc Web).

Chức năng: Quản lý học viên, khóa học guitar, bài học.

Dữ liệu: Quản lý trong bộ nhớ bằng Collection (ArrayList, Map, …).

Lưu trữ: Ghi & đọc từ file nhị phân (ObjectOutputStream / ObjectInputStream).
Bạn đã gửi
Chức năng chi tiết
1. Quản lý Học viên

Thêm, sửa, xóa học viên.

Liệt kê danh sách học viên.

Lọc học viên theo level (Beginner, Intermediate, Advanced).

Xem tiến độ học tập (các bài học đã hoàn thành).

2. Quản lý Khóa học Guitar

Thêm, sửa, xóa khóa học.

Mỗi khóa học có danh sách bài học (Lesson).

Xem nội dung khóa học.

3. Quản lý Bài học (Lesson)

Thêm, sửa, xóa bài học.

Bài học có: lessonId, title, duration, levelRequired.

Có thể lọc bài học theo độ khó hoặc thời lượng.

4. Gán học viên vào khóa học

Mỗi học viên có thể tham gia nhiều khóa học.

Mỗi khóa học có nhiều học viên.

Học viên được gán vào khóa học phù hợp với level.

5. Quản lý Giáo viên (tùy chọn thêm)

Thêm, sửa, xóa giáo viên.

Gán giáo viên vào khóa học.

6. Lưu trữ dữ liệu

Toàn bộ dữ liệu (học viên, khóa học, bài học, giáo viên) được lưu xuống file nhị phân.

Có chức năng backup và restore dữ liệu.

1.1 UML Class Diagram

<img width="1321" height="444" alt="Hoc_guitar-Trang-2 drawio" src="https://github.com/user-attachments/assets/978ac908-2930-475b-9ddd-966c1321e6a8" />

1.2 UML Sequence Diagram


