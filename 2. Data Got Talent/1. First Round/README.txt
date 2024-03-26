Phân Tích Dữ Liệu Rạp Chiếu Phim
I. Mục Tiêu
Dự án này nhằm mục đích phân tích hành vi của khách hàng tại rạp chiếu phim để hiểu rõ hơn về xu hướng mua hàng, sở thích xem phim, và khả năng tiêu thụ sản phẩm bán chéo. Phân tích này sẽ giúp rạp chiếu phim hoạch định chiến lược kinh doanh hiệu quả hơn, từ việc tối ưu hóa chiến lược tiếp thị đến việc cải thiện trải nghiệm của khách hàng.
II. Sử dụng trên GG Colab
Dự án này có thể được chạy trực tiếp trên Google Colab, một môi trường Jupyter notebook miễn phí chạy hoàn toàn trên đám mây. Điều này giúp bạn có thể thực hiện phân tích dữ liệu mà không cần cài đặt môi trường Python trên máy cá nhân. 

III. Cài Đặt
Để chạy dự án này, bạn cần cài đặt các thư viện Python sau:
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Squarify
- Unidecode
Bạn có thể cài đặt tất cả các phụ thuộc bằng cách chạy lệnh sau trong terminal hoặc command prompt:
pip install pandas numpy matplotlib seaborn plotly squarify unidecode

IV. Sử Dụng
Dự án sử dụng dữ liệu từ ba bảng: Customer, Ticket, và Film, được lưu trong các file Excel. Các bảng này được đọc vào và xử lý bằng Pandas DataFrame để phân tích dữ liệu và tạo ra các biểu đồ, giúp hiển thị thông tin một cách trực quan.
1. Đọc dữ liệu từ các bảng:
- Sử dụng pd.read_excel() để đọc dữ liệu từ các sheet Excel tương ứng.
2. Kết hợp dữ liệu:
- Sử dụng pd.merge() để kết hợp các bảng dữ liệu dựa trên customerid.
3. Phân tích và trực quan hóa:
- Sử dụng Matplotlib, Seaborn, và Plotly để trực quan hóa dữ liệu và rút ra nhận định.

Tác Giả và Ghi Nhận
Tác giả: HCT Team - UEL
- Nguyễn Quốc Huy
- Nguyễn Anh Tuấn
- Nguyễn Thị Minh Châu
- Huỳnh Thị Thanh Trúc
- Võ Minh Thành
Ghi nhận: Cảm ơn tất cả những ai đã đóng góp vào dự án này.