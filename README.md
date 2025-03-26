# UIT Data Science Challenge 
# Mô hình dự đoán sarcasm cho cuộc thi UIT.
Dữ liệu bao gồm ảnh, caption và label được để ở đường link dưới đây:
https://drive.google.com/drive/folders/1BcZx5DbmR_tDnSXzDjJM6PuP_gRepgxv?fbclid=IwZXh0bgNhZW0CMTEAAR1VZ0_zN7uRKRCicIFIJKUK6pNRMR1yTxOLhu8fiKj3l5gd5dTdFAYMf_w_aem_fLA_scCFZdXZ-jwyEMGFVg

## Tổng Quan
Dự án này tập trung vào việc phát hiện châm biếm trong văn bản và hình ảnh bằng các mô hình học sâu. Phát hiện châm biếm là một bài toán thách thức trong xử lý ngôn ngữ tự nhiên (NLP) và thị giác máy tính do sự tinh tế của các biểu hiện 
châm biếm. Dự án bao gồm các bước xử lý dữ liệu, trích xuất đặc trưng và huấn luyện mô hình để phân loại chính xác châm biếm.

## Dữ Liệu và Tiền Xử Lý
Bộ dữ liệu bao gồm nhiều tệp CSV, json chứa văn bản, chú thích hình ảnh và các đặc trưng hình ảnh được trích xuất. Các bước tiền xử lý bao gồm:
- Tải dữ liệu huấn luyện và kiểm tra từ các tệp CSV.
- Trích xuất đặc trưng văn bản từ chú thích hình ảnh.
- Trích xuất đặc trung văn bản từ những câu trong hình ảnh.
- Trích xuất đặc trưng hình ảnh bằng các mô hình học sâu.
- Hợp nhất các đặc trưng thành một tập dữ liệu chung.

## Huấn Luyện Mô Hình
Mô hình phân loại châm biếm được xây dựng bằng cách kết hợp các đặc trưng từ văn bản và hình ảnh. Các bước thực hiện gồm:
- Xây dựng đặc trưng cho văn bản và hình ảnh.
- Huấn luyện mô hình học sâu CNN.
- Tinh chỉnh mô hình để đạt độ chính xác cao hơn.

## Dự Đoán
Sau khi huấn luyện, mô hình có thể dự đoán châm biếm trong văn bản hoặc hình ảnh mới bằng cách xử lý đầu vào thông qua pipeline đã được huấn luyện và xuất kết quả dự đoán.

## Kết Luận
Dự án này khám phá cách phát hiện châm biếm bằng Deep Learning bằng cách kết hợp thông tin từ văn bản và hình ảnh. Các cải tiến trong tương lai có thể bao gồm các kỹ thuật trích xuất đặc trưng tốt hơn và các kiến trúc học sâu tiên tiến hơn.

