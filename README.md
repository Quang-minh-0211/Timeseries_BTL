**ỨNG DỤNG CÁC MÔ HÌNH HỌC SÂU DỰ BÁO MỰC NƯỚC NGẦM**

📊 Dataset


Toàn bộ dữ liệu được thu từ các trạm đo tại khu vực Hà Nội. Tuy nhiên do chưa đủ 10GB dung lượng như yêu cầu
nên nhóm đã sử dụng mạng tạo timeGAN để sinh thêm dữ liệu
Sau đây là link data được lưu ở Google Drive: https://drive.google.com/drive/folders/1LP5Ty66J7X2KvqjphutLC4VPYvZA2xNF?usp=sharing

Nhóm đã triển khai 4 mô hình là RNN, LSTM, Transformer và Autoformer.
Kịch bản của nhóm sẽ là sử dụng dữ liệu 24h trong quá khứ để dự báo cho 2h, 12h, 24h, 36h, 72h trong tương lai.
Trong quá trình train thì nhóm đã tiến hành chia nhỏ các file data để dễ dàng huấn luyện và cũng như là kiểm soát kết quả, sau quá trình train thì nhóm đã thu được các chỉ số đánh giá
như R2, MAE, MSE để đánh giá các mô hình. Nhóm đã tiến hành xuất mô hình ra các file ở định dạng .h5 và scaler, config ở dạng .pkl để tiến hành làm demo và deploy lên cho người dùng sử dụng
link website: https://deploy-6zsv.onrender.com/

Cảm ơn Thầy/Cô và các bạn.
