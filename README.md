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
- Cần có tài khoản Kaggle để tham gia vào cuộc thi https://www.kaggle.com/competitions/amp-parkinsons-disease-progression-prediction
- Có thể copy, chạy sau đó submit notebook của nhóm https://www.kaggle.com/code/nanashi0it/parkinson-s-disease-progression-prediction để thu được kết quả.
 - Hoặc một cách khác là tạo notebook mới trên cuộc thi sau đó import notebook `Kaggle_ADS_Final_Project.ipynb` trên GitHub của nhóm sau đó tiến hành chạy và submit để thu được kết quả.
 - Kết quả tốt nhất mà nhóm thu được là **Private Score = 72.246** và **Public Score = 62.287**

## Chạy code trên môi trường Google Colab.
- Code trong notebook `ADS_Final_Project.ipynb` đã được điều chỉnh lại, do đó có thể tải xuống và upload lên Colab để chạy.
-  Chạy trên Colab sẽ không có đánh giá kết quả cuối cùng do muốn đánh giá điểm số chính xác cần sử dụng API của cuộc thi trên Kaggle.
- Khi chạy dữ liệu sẽ được lấy từ Drive mà nhóm đã tải lên trước đó nên không cần upload dữ liệu lên Colab.
- Nếu muốn xem dữ liệu có thể tải xuống bằng đường dẫn Drive trong Notebook hoặc tải dữ liệu từ GitHub.
- - Có thể chạy code tại `Thời gian chạy` -> `Chạy tất cả` hoặc bất cứ phương thức chạy nào khác.
