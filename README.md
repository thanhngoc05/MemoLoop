# MemoLoop

> **Học một lần, nhớ dài lâu.**

MemoLoop là nền tảng học tập trực tuyến bằng flashcard, hỗ trợ người dùng tạo bộ thẻ, ôn tập kiến thức, làm bài kiểm tra, tham gia trò chơi giáo dục và theo dõi tiến độ học tập.

Hệ thống định hướng áp dụng phương pháp lặp lại ngắt quãng để giúp người học ôn tập đúng nội dung vào đúng thời điểm, từ đó tăng khả năng ghi nhớ kiến thức trong thời gian dài.

---

## 1. Giới thiệu dự án

Trong quá trình học tập, người học thường ghi nhớ kiến thức trong thời gian ngắn nhưng dễ quên nếu không được ôn tập thường xuyên. Việc tự xác định nội dung nào cần ôn và thời điểm nào nên ôn lại cũng gây khó khăn cho nhiều người.

Các phương pháp học truyền thống đôi khi thiếu tính tương tác, khiến người học dễ mất tập trung và khó duy trì thói quen học tập lâu dài.

MemoLoop được xây dựng để giải quyết những vấn đề trên thông qua việc kết hợp:

* Học bằng flashcard.
* Ôn tập theo phương pháp lặp lại ngắt quãng.
* Làm bài kiểm tra từ nội dung đã học.
* Học tập thông qua trò chơi giáo dục.
* Theo dõi tiến độ và kết quả học tập.
* Khám phá các bộ thẻ được chia sẻ công khai.

---

## 2. Vấn đề cần giải quyết

MemoLoop tập trung giải quyết các vấn đề sau:

* Người học dễ quên kiến thức sau một thời gian nếu không ôn tập đúng lúc.
* Người học khó tự xây dựng lịch ôn tập phù hợp.
* Tài liệu học tập bị phân tán và thiếu tổ chức.
* Việc học lặp lại theo cách truyền thống dễ gây nhàm chán.
* Người học thiếu công cụ theo dõi tiến độ và khả năng ghi nhớ.
* Người học khó chuyển nội dung đã học thành bài kiểm tra.
* Người học thiếu môi trường kết hợp giữa học tập và trò chơi.
* Người dùng khó chia sẻ hoặc tái sử dụng bộ flashcard của nhau.

---

## 3. Mục tiêu dự án

### 3.1. Mục tiêu tổng quát

Xây dựng một nền tảng học tập bằng flashcard có giao diện thân thiện, hỗ trợ ôn tập thông minh, kiểm tra kiến thức và học tập thông qua trò chơi giáo dục.

### 3.2. Mục tiêu cụ thể

* Cho phép người dùng đăng ký và quản lý tài khoản cá nhân.
* Cho phép người dùng tạo và quản lý các bộ flashcard.
* Cho phép người dùng thêm, sửa, xóa và sắp xếp flashcard.
* Hỗ trợ học bằng chế độ lật thẻ.
* Hỗ trợ đánh giá mức độ ghi nhớ của từng flashcard.
* Xác định thời điểm ôn tập tiếp theo dựa trên kết quả học.
* Hiển thị danh sách flashcard cần ôn trong ngày.
* Tạo bài kiểm tra từ nội dung flashcard.
* Kết hợp trò chơi giáo dục với nội dung flashcard.
* Chấm điểm và lưu kết quả học tập.
* Theo dõi tiến độ, tỷ lệ trả lời đúng và chuỗi ngày học.
* Cho phép người dùng khám phá các bộ thẻ công khai.
* Cho phép thích, lưu và sao chép bộ thẻ.
* Xây dựng hệ thống có cấu trúc rõ ràng, dễ kiểm thử và dễ mở rộng.

---

## 4. Đối tượng sử dụng

### 4.1. Khách chưa đăng nhập

Khách là người truy cập MemoLoop nhưng chưa đăng nhập.

Khách có thể:

* Xem trang giới thiệu.
* Xem các bộ thẻ công khai.
* Tìm kiếm nội dung công khai.
* Xem thông tin cơ bản của bộ thẻ.
* Đăng ký tài khoản.
* Đăng nhập.

Khách không thể lưu tiến độ học tập hoặc tạo dữ liệu cá nhân.

### 4.2. Người dùng đã đăng nhập

Người dùng đã đăng nhập có thể:

* Quản lý hồ sơ cá nhân.
* Tạo và quản lý bộ flashcard.
* Học bằng flashcard.
* Ôn các thẻ đến hạn.
* Làm bài kiểm tra.
* Tham gia trò chơi giáo dục.
* Xem thống kê học tập.
* Thích, lưu và sao chép bộ thẻ công khai.

### 4.3. Quản trị viên

Quản trị viên có thể:

* Quản lý tài khoản người dùng.
* Khóa hoặc mở khóa tài khoản.
* Kiểm duyệt nội dung công khai.
* Xử lý báo cáo nội dung vi phạm.
* Quản lý chủ đề và danh mục.
* Theo dõi một số thống kê chung của hệ thống.

---

## 5. Chức năng dự kiến

### 5.1. Quản lý tài khoản

* Đăng ký tài khoản.
* Đăng nhập.
* Đăng xuất.
* Xem thông tin cá nhân.
* Cập nhật thông tin cá nhân.
* Thay đổi ảnh đại diện.
* Đổi mật khẩu.
* Khôi phục mật khẩu.
* Xem trạng thái tài khoản.

### 5.2. Quản lý bộ flashcard

* Tạo bộ flashcard mới.
* Nhập tên bộ thẻ.
* Nhập mô tả bộ thẻ.
* Chọn chủ đề.
* Thiết lập bộ thẻ công khai hoặc riêng tư.
* Xem danh sách bộ thẻ cá nhân.
* Cập nhật thông tin bộ thẻ.
* Xóa bộ thẻ.
* Tìm kiếm bộ thẻ.
* Lọc bộ thẻ theo chủ đề.
* Sắp xếp bộ thẻ theo ngày tạo hoặc ngày cập nhật.

### 5.3. Quản lý flashcard

* Thêm flashcard vào bộ thẻ.
* Nhập nội dung mặt trước.
* Nhập nội dung mặt sau.
* Thêm ví dụ hoặc ghi chú.
* Cập nhật flashcard.
* Xóa flashcard.
* Sắp xếp thứ tự flashcard.
* Thêm nhiều flashcard liên tiếp.
* Nhập dữ liệu flashcard từ file CSV trong giai đoạn mở rộng.

### 5.4. Học bằng flashcard

* Hiển thị nội dung mặt trước của flashcard.
* Cho phép lật thẻ để xem mặt sau.
* Chuyển sang thẻ tiếp theo hoặc thẻ trước đó.
* Đánh dấu flashcard quan trọng.
* Phát âm nội dung khi dữ liệu hỗ trợ.
* Hiển thị tiến độ của phiên học.
* Kết thúc và lưu kết quả phiên học.

### 5.5. Ôn tập theo mức độ ghi nhớ

Sau khi xem đáp án, người dùng có thể đánh giá mức độ ghi nhớ:

* **Quên:** người dùng không nhớ nội dung.
* **Khó:** người dùng nhớ nhưng mất nhiều thời gian.
* **Nhớ:** người dùng trả lời đúng với mức độ bình thường.
* **Dễ:** người dùng ghi nhớ tốt và trả lời nhanh.

Hệ thống sử dụng kết quả đánh giá để:

* Cập nhật tiến độ của flashcard.
* Tính khoảng thời gian ôn tập tiếp theo.
* Xác định ngày ôn tiếp theo.
* Hiển thị thẻ cần ôn trong ngày.
* Lưu lịch sử đánh giá của người dùng.

### 5.6. Bài kiểm tra

* Tạo bài kiểm tra từ một bộ flashcard.
* Làm bài trắc nghiệm.
* Làm bài nhập đáp án.
* Làm bài đúng hoặc sai trong giai đoạn mở rộng.
* Xáo trộn câu hỏi và đáp án.
* Hiển thị số câu đã hoàn thành.
* Chấm điểm tự động.
* Hiển thị số câu đúng và câu sai.
* Xem lại đáp án.
* Lưu lịch sử làm bài.
* Cho phép làm lại bài kiểm tra.

### 5.7. Học tập thông qua trò chơi

MemoLoop kết hợp nội dung flashcard với trò chơi giáo dục để giúp người dùng củng cố kiến thức theo cách trực quan và thú vị hơn.

Các mục tiêu của chức năng trò chơi:

* Tăng mức độ tương tác trong quá trình học.
* Hạn chế cảm giác nhàm chán khi ôn tập.
* Khuyến khích người dùng phản xạ nhanh.
* Giúp củng cố mối liên hệ giữa thuật ngữ và định nghĩa.
* Ghi nhận kết quả để người dùng theo dõi sự tiến bộ.

#### Trò chơi ghép thẻ

Đây là trò chơi được ưu tiên triển khai trong phiên bản đầu tiên.

Người dùng cần ghép thuật ngữ với định nghĩa tương ứng trong thời gian giới hạn.

Luật chơi cơ bản:

1. Người dùng chọn một bộ flashcard.
2. Hệ thống chọn ngẫu nhiên một số flashcard từ bộ thẻ.
3. Thuật ngữ và định nghĩa được tách thành các thẻ riêng.
4. Các thẻ được xáo trộn vị trí.
5. Người dùng chọn một thuật ngữ và một định nghĩa để tạo thành một cặp.
6. Nếu ghép đúng, cặp thẻ được loại khỏi khu vực chơi.
7. Nếu ghép sai, hệ thống ghi nhận một lượt sai.
8. Trò chơi kết thúc khi người dùng ghép đúng tất cả các cặp.
9. Hệ thống lưu thời gian hoàn thành, số cặp đúng và số lượt sai.
10. Người dùng có thể chơi lại để cải thiện kết quả.

Kết quả trò chơi có thể bao gồm:

* Tổng số cặp thẻ.
* Số cặp ghép đúng.
* Số lần ghép sai.
* Thời gian hoàn thành.
* Điểm số đạt được.
* Kết quả tốt nhất trước đó.

#### Các trò chơi mở rộng

Các trò chơi có thể được nghiên cứu và phát triển trong tương lai:

* Trò chơi trả lời nhanh.
* Trò chơi ghi nhớ vị trí thẻ.
* Trò chơi chọn đáp án để vượt chướng ngại vật.
* Trò chơi điền từ còn thiếu.
* Trò chơi sắp xếp nội dung theo đúng thứ tự.
* Trò chơi theo cấp độ.
* Trò chơi tích lũy điểm kinh nghiệm.
* Trò chơi thi đấu giữa nhiều người dùng.

Phiên bản đầu tiên không triển khai đồng thời quá nhiều trò chơi. Hệ thống chỉ tập trung hoàn thiện trò chơi ghép thẻ trước khi mở rộng.

### 5.8. Khám phá nội dung công khai

* Xem danh sách các bộ thẻ công khai.
* Tìm kiếm bộ thẻ theo tên.
* Lọc bộ thẻ theo chủ đề.
* Xem thông tin tác giả.
* Xem số lượng flashcard.
* Xem số lượt thích.
* Thích hoặc bỏ thích bộ thẻ.
* Lưu hoặc bỏ lưu bộ thẻ.
* Sao chép bộ thẻ vào thư viện cá nhân.
* Báo cáo nội dung không phù hợp.

### 5.9. Thư viện cá nhân

* Xem các bộ thẻ do người dùng tạo.
* Xem các bộ thẻ đã lưu.
* Xem các bộ thẻ đã sao chép.
* Xem các bộ thẻ học gần đây.
* Tìm kiếm trong thư viện.
* Lọc theo trạng thái học.
* Tiếp tục phiên học gần nhất.

### 5.10. Thống kê học tập

* Thống kê tổng số bộ thẻ.
* Thống kê tổng số flashcard.
* Thống kê số flashcard đã học.
* Thống kê số flashcard cần ôn.
* Thống kê số phiên học.
* Theo dõi tỷ lệ trả lời đúng.
* Theo dõi thời gian học.
* Theo dõi chuỗi ngày học liên tục.
* Xem kết quả bài kiểm tra gần đây.
* Xem kết quả trò chơi gần đây.
* Xem điểm cao nhất của trò chơi.
* Xem tiến độ theo từng bộ thẻ.

### 5.11. Thông báo

* Thông báo khi có flashcard đến hạn ôn.
* Thông báo khi bộ thẻ được sao chép.
* Thông báo khi nội dung nhận được lượt thích.
* Đánh dấu thông báo đã đọc.
* Xem danh sách thông báo.

Chức năng thông báo có thể được triển khai sau khi các chức năng học tập cốt lõi đã ổn định.

### 5.12. Quản trị hệ thống

* Xem danh sách người dùng.
* Xem chi tiết tài khoản.
* Khóa hoặc mở khóa tài khoản.
* Xem nội dung bị báo cáo.
* Ẩn hoặc xóa nội dung vi phạm.
* Quản lý danh mục.
* Xem thống kê tổng quan.

---

## 6. Phạm vi phiên bản đầu tiên

Phiên bản đầu tiên của MemoLoop tập trung hoàn thành các chức năng cốt lõi sau:

* Đăng ký tài khoản.
* Đăng nhập và đăng xuất.
* Xem và cập nhật hồ sơ.
* Tạo, xem, sửa và xóa bộ flashcard.
* Thiết lập bộ thẻ công khai hoặc riêng tư.
* Thêm, sửa, xóa và sắp xếp flashcard.
* Học bằng chế độ lật thẻ.
* Đánh giá mức độ ghi nhớ.
* Tính lịch ôn tập tiếp theo.
* Hiển thị flashcard cần ôn.
* Làm bài kiểm tra trắc nghiệm.
* Làm bài nhập đáp án.
* Chấm điểm và lưu kết quả bài kiểm tra.
* Xem các bộ thẻ công khai.
* Tìm kiếm bộ thẻ.
* Lưu, thích và sao chép bộ thẻ.
* Học tập qua trò chơi ghép thẻ.
* Lưu kết quả và điểm số của mỗi lượt chơi.
* Xem thống kê học tập cơ bản.
* Quản trị người dùng và kiểm duyệt nội dung ở mức cơ bản.

---

## 7. Chức năng chưa thuộc phạm vi phiên bản đầu tiên

Các chức năng sau chưa được ưu tiên trong phiên bản đầu tiên:

* Trí tuệ nhân tạo tạo flashcard tự động.
* Trí tuệ nhân tạo giải thích đáp án.
* Tạo flashcard từ tài liệu PDF.
* Tạo flashcard từ video.
* Thanh toán trực tuyến.
* Gói tài khoản trả phí.
* Tiện ích mở rộng trình duyệt.
* Ứng dụng điện thoại.
* Trò chuyện thời gian thực.
* Cộng đồng thời gian thực.
* Thi đấu trò chơi nhiều người.
* Hệ thống nhiều trò chơi phức tạp.
* Thông báo đẩy trên thiết bị.
* Đồng bộ ngoại tuyến.

Các chức năng trên được xem là hướng phát triển trong tương lai.

---

## 8. Điểm nổi bật của MemoLoop

MemoLoop hướng đến bốn giá trị chính:

### 8.1. Học tập có tổ chức

Kiến thức được tổ chức thành bộ flashcard theo từng chủ đề.

### 8.2. Ôn tập đúng thời điểm

Hệ thống xác định các flashcard cần ôn dựa trên lịch sử học tập và mức độ ghi nhớ.

### 8.3. Học kết hợp kiểm tra

Người dùng có thể chuyển nội dung flashcard thành bài kiểm tra để tự đánh giá kiến thức.

### 8.4. Vừa học vừa chơi

Nội dung flashcard được sử dụng trong trò chơi giáo dục, giúp người dùng vừa luyện phản xạ vừa củng cố kiến thức.

Thông điệp chính của sản phẩm:

> **Học bằng flashcard, ôn tập thông minh và ghi nhớ kiến thức thông qua trò chơi.**

---

## 9. Ngôn ngữ và công nghệ

### 9.1. Ngôn ngữ lập trình chính

Ngôn ngữ lập trình chính của MemoLoop là:

* **JavaScript**

JavaScript được sử dụng trong:

* Lập trình frontend.
* Lập trình backend.
* Xử lý nghiệp vụ.
* Viết kiểm thử tự động.
* Viết script khởi tạo dữ liệu.
* Viết các công cụ hỗ trợ dự án.

Các ngôn ngữ và định dạng khác chỉ đóng vai trò hỗ trợ:

* HTML dùng để xây dựng cấu trúc giao diện.
* CSS dùng để trình bày giao diện.
* SQL dùng để thao tác và tìm hiểu cơ sở dữ liệu.
* Prisma Schema dùng để mô tả mô hình dữ liệu.
* JSON dùng để truyền dữ liệu và cấu hình.
* YAML dùng cho Docker Compose và GitHub Actions.
* Markdown dùng để viết tài liệu.
* PlantUML dùng để xây dựng sơ đồ UML.

### 9.2. Frontend

* React.
* JavaScript.
* Vite.
* React Router.
* Axios.
* CSS hoặc CSS Modules.

### 9.3. Backend

* Node.js.
* Express.
* JavaScript ES Modules.
* Prisma ORM.
* JSON Web Token.
* bcrypt.
* Zod.

### 9.4. Cơ sở dữ liệu

* MySQL.

### 9.5. Kiểm thử

* Postman.
* Vitest hoặc Jest.
* Supertest.
* Playwright.

### 9.6. Công cụ phát triển

* Visual Studio Code.
* Git.
* GitHub.
* npm.
* Prisma Studio.

### 9.7. Triển khai và tự động hóa

* Docker.
* Docker Compose.
* GitHub Actions.

---

## 10. Kiến trúc tổng thể

```text
Người dùng
    |
    v
React Frontend
    |
    | HTTP Request / JSON Response
    v
Node.js + Express REST API
    |
    | Prisma ORM
    v
MySQL Database
```

### 10.1. Frontend

Frontend chịu trách nhiệm:

* Hiển thị giao diện.
* Tiếp nhận thao tác của người dùng.
* Kiểm tra dữ liệu cơ bản.
* Gửi request tới backend.
* Nhận và hiển thị kết quả từ backend.
* Quản lý trạng thái giao diện.

Frontend không kết nối trực tiếp với MySQL.

### 10.2. Backend

Backend chịu trách nhiệm:

* Tiếp nhận HTTP request.
* Kiểm tra dữ liệu đầu vào.
* Xác thực người dùng.
* Phân quyền truy cập.
* Xử lý nghiệp vụ.
* Làm việc với cơ sở dữ liệu.
* Trả response về frontend.
* Xử lý lỗi tập trung.

### 10.3. Prisma ORM

Prisma được sử dụng để:

* Mô tả mô hình dữ liệu.
* Thực hiện migration.
* Truy vấn MySQL từ JavaScript.
* Hạn chế việc viết truy vấn SQL lặp lại.
* Quản lý quan hệ giữa các bảng.

### 10.4. MySQL

MySQL lưu trữ:

* Tài khoản.
* Bộ flashcard.
* Flashcard.
* Tiến độ học.
* Lịch sử ôn tập.
* Bài kiểm tra.
* Kết quả bài kiểm tra.
* Phiên trò chơi.
* Điểm số trò chơi.
* Lượt thích.
* Bộ thẻ đã lưu.
* Thông báo.
* Báo cáo nội dung.

---

## 11. Cấu trúc dự án

```text
MemoLoop/
├── frontend/                      # Giao diện React và JavaScript
├── backend/                       # REST API Node.js và Express
├── docs/
│   ├── 01-project/                # Tổng quan và phạm vi dự án
│   ├── 02-requirements/           # Đặc tả yêu cầu phần mềm
│   ├── 03-uml/                    # Các sơ đồ UML
│   ├── 04-database/               # ERD và tài liệu database
│   ├── 05-api/                    # Đặc tả REST API
│   ├── 06-testing/                # Test plan, test case và báo cáo lỗi
│   ├── 07-deployment/             # Tài liệu Docker và triển khai
│   └── 08-report/                 # Nội dung báo cáo tốt nghiệp
├── postman/                       # Postman Collection và Environment
├── .editorconfig                  # Quy tắc định dạng chung
├── .gitignore                     # Danh sách file Git không theo dõi
└── README.md                      # Tài liệu giới thiệu dự án
```

Cấu trúc chi tiết của frontend và backend sẽ được khởi tạo ở các task tiếp theo.

---

## 12. Module nghiệp vụ dự kiến

Backend dự kiến được chia thành các module:

```text
backend/src/modules/
├── auth/
├── users/
├── decks/
├── flashcards/
├── study/
├── quizzes/
├── games/
├── explore/
├── likes/
├── saved-decks/
├── statistics/
├── notifications/
├── reports/
└── admin/
```

Mỗi module chỉ xử lý một nhóm nghiệp vụ cụ thể.

Ví dụ:

* `auth` xử lý đăng ký, đăng nhập và xác thực.
* `decks` xử lý bộ flashcard.
* `flashcards` xử lý từng flashcard.
* `study` xử lý học tập và lịch ôn.
* `quizzes` xử lý bài kiểm tra.
* `games` xử lý trò chơi giáo dục.
* `statistics` xử lý thống kê.
* `admin` xử lý chức năng quản trị.

---

## 13. Quy trình phát triển

Dự án được phát triển theo các giai đoạn:

1. Khởi tạo Git repository.
2. Tạo cấu trúc dự án.
3. Xác định vấn đề và mục tiêu.
4. Phân tích yêu cầu.
5. Xác định actor và use case.
6. Thiết kế UML.
7. Thiết kế cơ sở dữ liệu.
8. Đặc tả REST API.
9. Khởi tạo backend JavaScript.
10. Phát triển xác thực và phân quyền.
11. Phát triển quản lý bộ flashcard.
12. Phát triển chức năng học và ôn tập.
13. Phát triển bài kiểm tra.
14. Phát triển trò chơi ghép thẻ.
15. Phát triển thống kê.
16. Khởi tạo frontend JavaScript.
17. Kết nối frontend với backend.
18. Viết kiểm thử.
19. Docker hóa hệ thống.
20. Thiết lập CI/CD.
21. Triển khai sản phẩm.
22. Hoàn thiện báo cáo tốt nghiệp.

---

## 14. Tiêu chuẩn phát triển

MemoLoop áp dụng các nguyên tắc sau:

* JavaScript là ngôn ngữ lập trình chính.
* Không viết toàn bộ nghiệp vụ trong một file.
* Mỗi module có trách nhiệm rõ ràng.
* API sử dụng cấu trúc response thống nhất.
* Dữ liệu đầu vào phải được kiểm tra.
* Mật khẩu phải được mã hóa.
* API cần xác thực và phân quyền phù hợp.
* Không lưu thông tin bí mật trong source code.
* Không commit file `.env`.
* Mỗi chức năng cần có kiểm thử.
* Mỗi task được phát triển trên một branch riêng.
* Không phát triển trực tiếp trên branch `main`.
* Tài liệu phải được cập nhật cùng với source code.
* Các chức năng chưa hoàn thành không được mô tả là đã hoàn thành.

---

## 15. Quy tắc Git

Branch `main` chỉ chứa phiên bản đã được kiểm tra và tương đối ổn định.

Mỗi nhiệm vụ được thực hiện trên một branch riêng.

Ví dụ:

```text
MEMO-00-project-setup
MEMO-01-requirement-analysis
MEMO-02-uml-design
MEMO-03-database-design
MEMO-04-backend-setup
MEMO-05-authentication-api
MEMO-06-deck-management
MEMO-07-flashcard-management
MEMO-08-study-and-srs
MEMO-09-quiz-system
MEMO-10-matching-game
MEMO-11-statistics
MEMO-12-frontend-setup
```

Commit phải mô tả rõ nội dung thay đổi.

Ví dụ:

```text
MEMO-00 #done initialize MemoLoop project structure
```

Không sử dụng commit message không rõ ràng như:

```text
update
fix
done
new code
sửa lỗi
```

---

## 16. Kiểm thử dự kiến

Dự án sử dụng nhiều cấp độ kiểm thử:

### 16.1. Unit Test

Kiểm thử từng hàm hoặc từng đơn vị xử lý độc lập.

Ví dụ:

* Hàm tính lịch ôn tập.
* Hàm tính điểm trò chơi.
* Hàm kiểm tra đáp án.
* Hàm chuẩn hóa dữ liệu.

### 16.2. Integration Test

Kiểm thử sự kết hợp giữa:

* Route.
* Controller.
* Service.
* Prisma.
* Database.

### 16.3. API Test

Sử dụng Postman và Supertest để kiểm tra:

* Status code.
* Response body.
* Validation.
* Xác thực.
* Phân quyền.
* Xử lý lỗi.

Mỗi API test case được tổ chức thành một request riêng trong Postman.

### 16.4. End-to-End Test

Sử dụng Playwright để kiểm tra các luồng hoàn chỉnh:

* Đăng ký và đăng nhập.
* Tạo bộ thẻ.
* Thêm flashcard.
* Học flashcard.
* Làm bài kiểm tra.
* Chơi trò chơi ghép thẻ.

---

## 17. Định hướng thiết kế giao diện

MemoLoop sử dụng thương hiệu và giao diện riêng.

Thông tin nhận diện:

* Tên sản phẩm: **MemoLoop**
* Slogan: **Học một lần, nhớ dài lâu.**

Giao diện hướng đến:

* Đơn giản.
* Mềm mại.
* Dễ chịu.
* Dễ sử dụng.
* Tập trung vào nội dung học tập.
* Phù hợp trên máy tính và điện thoại.
* Có phản hồi rõ ràng sau mỗi thao tác.
* Có trạng thái rỗng và thông báo lỗi dễ hiểu.
* Không gây rối mắt khi người dùng học trong thời gian dài.

MemoLoop có thể tham khảo ý tưởng chung từ các nền tảng học flashcard, nhưng không sao chép nguyên mã nguồn, logo, hình ảnh, nội dung, tên trò chơi hoặc giao diện của sản phẩm khác.

---

## 18. Trạng thái hiện tại

Dự án đang ở giai đoạn:

* Khởi tạo Git repository.
* Xây dựng cấu trúc thư mục.
* Hoàn thiện tài liệu giới thiệu.
* Phân tích chức năng tham khảo.
* Chuẩn bị đặc tả yêu cầu và UML.

Các chức năng trong tài liệu này hiện là chức năng dự kiến. Chưa có phiên bản sản phẩm hoàn chỉnh được phát hành.

---

## 19. Định hướng phát triển tương lai

Sau khi hoàn thành phiên bản đầu tiên, MemoLoop có thể mở rộng:

* Tạo flashcard bằng trí tuệ nhân tạo.
* Tạo flashcard từ tài liệu.
* Hệ thống nhiều trò chơi giáo dục.
* Học nhóm.
* Thi đấu giữa người dùng.
* Bảng xếp hạng.
* Thành tích và huy hiệu.
* Điểm kinh nghiệm và cấp độ.
* Gói tài khoản nâng cao.
* Ứng dụng điện thoại.
* Tiện ích trình duyệt.
* Hỗ trợ học ngoại tuyến.
* Đồng bộ dữ liệu đa thiết bị.

---

## 20. Thông điệp của dự án

> **MemoLoop giúp người dùng biến việc học thành một vòng lặp ghi nhớ hiệu quả: học kiến thức, ôn tập đúng lúc, kiểm tra khả năng ghi nhớ và củng cố kiến thức thông qua trò chơi.**
