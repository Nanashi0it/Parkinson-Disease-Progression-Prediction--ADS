# **ADS_Final_Project**
Đồ án cuối kì - Khoa học dữ liệu ứng dụng

Nhóm **Data Lord** gồm 4 thành viên:
- 19120625 - Nguyễn Hữu Phương 
- 18120278 - Phạm Hoàng Nam Anh
- 19120543 - Hoàng Mạnh Khiêm
- 19120522 - Phạm Quốc Hưng

# **Về đề tài**
Đề tài mà nhóm lựa chọn là Dự đoán tiến triển của bệnh Parkinson (Parkinson's Disease Progression Prediction).

Bệnh Parkinson là một bệnh gây rối loạn não làm ảnh hưởng đến khả năng đi lại, nhận thức, giấc ngủ và các chức năng bình thường khác. Hiện nay vẫn chưa có phương pháp nào có thể chữa trị hiệu quả căn bệnh này và bệnh sẽ ngày càng trầm trọng hơn theo thời gian. Các nghiên cứu cho thấy các đột biến protein và peptide đóng một vai trò quan trọng trong sự khởi phát và trầm trọng hóa của căn bệnh này.

**Bài toán:** Mục tiêu của đề tài này là dự đoán điểm MDS-UPDRS thông qua dữ liệu đo lường protein và peptide để xác định tiến triển của bệnh Parkinson. Thang điểm này gồm có 4 phần:
- **Phần 1:** Đánh giá các trải nghiệm không chuyển động trong cuộc sống hàng ngày của bệnh nhân Parkinson. Gồm 13 câu hỏi.
- **Phần 2:** Đánh giá các trải nghiệm chuyển động trong cuộc sống hàng ngày của bệnh nhân Parkinson. Gồm 13 câu hỏi.
- **Phần 3:** Đánh giá các khía cạnh chuyển động của bệnh Parkinson trong khi thực hiện các hoạt động hàng ngày. Gồm 18 câu hỏi.
- **Phần 4:** Đánh giá các biến chứng chuyển động của bệnh Parkinson. Gồm 6 câu hỏi.

Mỗi câu hỏi được đánh giá trên thang điểm 0 - 4: 0 (bình thường - normal), 1 (nhẹ - slight), 2 (trung bình - mild), 3 (nặng - moderate) và 4 (rất nặng - severe).

**Ứng dụng, ý nghĩa khoa học và thực tiễn:**

Việc thực hiện đề tài này sẽ giúp dự đoán tiến triển của bệnh Parkinson thông qua dữ liệu đo lường protein và peptide. Điều này sẽ hỗ trợ các bác sĩ và các nhà nghiên cứu trong việc tìm hiểu, nghiên cứu chuyên sâu hơn về căn bệnh này. 

Bên cạnh đó, có thể tìm được các giải pháp để làm chậm tiến triển, hạn chế ảnh hưởng của căn bệnh tới người mắc phải. Thậm chí chữa trị dứt điểm bệnh Parkinson.

# **Hướng dẫn chạy code**
## Chạy code trên nền tảng Kaggle của cuộc thi.
Về cơ bản đây là một cuộc thi trên Kaggle nên để đánh giá thì sẽ cần submit để nhận kết quả.
- Bước 1: Đăng nhập tài khoản trên trang Kaggle.
- Bước 2: Tham gia vào cuộc thi https://www.kaggle.com/competitions/amp-parkinsons-disease-progression-prediction
- Bước 3: Có thể chạy code trên Kaggle theo một trong 2 cách sau:
 + Có thể vào notebook của nhóm https://www.kaggle.com/code/nanashi0it/parkinson-s-disease-progression-prediction chọn `Copy & Edit`
 + Tạo notebook mới trên cuộc thi sau đó import notebook `Kaggle_ADS_Final_Project.ipynb` trên GitHub của nhóm.
 Sau đó có thể tiến hành chạy notebook và submit để nhận kết quả dánh giá. 

## Chạy code trên môi trường Google Colab.
Việc chạy trên Colab sẽ có một vài lưu ý sau:
- Code trong notebook `ADS_Final_Project.ipynb` đã được điều chỉnh lại, do đó có thể tải xuống và upload lên Colab để chạy.
- Chạy trên Colab sẽ không có đánh giá kết quả cuối cùng (chỉ có kết quả đánh giá từ hàm đánh giá nhóm tự cài đặt). Do đó muốn đánh giá điểm số chính xác cần sử dụng API của cuộc thi trên Kaggle.
- Khi chạy, dữ liệu sẽ được lấy từ Drive mà nhóm đã tải lên trước đó nên không cần upload dữ liệu lên Colab.
- Nếu muốn xem dữ liệu có thể tải xuống bằng đường dẫn Drive trong Notebook hoặc tải dữ liệu từ GitHub.

Các bước thực hiện như sau:
- Bước 1: Tải file `ADS_Final_Project.ipynb` trong GitHub của nhóm.
- Bước 2: Upload file đã tải lên Colab và tiến hành chạy như bình thường.
