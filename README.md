## Phần 1: Phân tích cơ chế In-Context Learning
In-Context Learning là cơ chế giúp AI học cách thực hiện nhiệm vụ thông qua các ví dụ được cung cấp ngay trong Prompt mà không cần huấn luyện lại mô hình hoặc cập nhật trọng số (Weights).
Khi nhận được các ví dụ Few-shot, AI phân tích mối quan hệ giữa dữ liệu đầu vào (Input) và kết quả đầu ra (Output), từ đó nhận diện quy luật, ngữ cảnh và cách phân loại cảm xúc.
Nhờ vậy, AI có thể hiểu được những câu nói mỉa mai, nghĩa bóng và tiếng lóng công nghệ thay vì chỉ dựa vào nghĩa bề mặt của từ ngữ.

## Phần 2: Sửa lỗi bằng Few-shot
Prompt Few-shot hoàn chỉnh:
Bạn là chuyên viên Đảm bảo Chất lượng của TechShop. Hãy phân loại cảm xúc đánh giá sản phẩm thành TÍCH CỰC hoặc TIÊU CỰC.
Hãy chú ý nhận diện cách nói mỉa mai, khen đểu và nghĩa bóng. Không chỉ dựa vào những từ ngữ tích cực xuất hiện trong câu.

### 3 ví dụ mẫu
Ví dụ 1:
Input: "Máy chơi game mà CPU lên 98 độ C, đúng là có thể sưởi ấm cả căn phòng!"
Output: TIÊU CỰC
Ví dụ 2:
Input: "Pin dùng được đúng 2 tiếng, tuyệt vời thật, đi đâu cũng phải mang theo sạc!"
Output: TIÊU CỰC
Ví dụ 3:
Input: "Shop giao hàng nhanh quá, đặt từ tuần trước mà tuần này mới nhận được, thật không thể tin nổi!"
Output: TIÊU CỰC

Chỉ trả lời một trong hai nhãn: TÍCH CỰC hoặc TIÊU CỰC.

Output: TIÊU CỰC
