Về Kaggle:
- Đây là công ty con của Google LLC. Đây được xem là 1 cộng đồng dành cho những người đam mê nghiên cứu về khoa học dữ liệu và học máy. 
- Có rất nhiều cuộc thi về data thường được tổ chức mỗi năm nên đây là nơi rèn luyện, học hỏi lẫn nhau cho người mới bắt đầu đến master.
Về Kaggle favorita:
Cuộc thi có tên gọi: the Corporacion Favorita grocery sales prediction competition.
Mục đích: dựa trên data có sẵn từ đó dự báo doanh thu của mỗi item trong mỗi cửa hàng mỗi ngày từ ngày 16/08/2017 đến 31/08/2017 và tối ưu hóa hàm loss function trong ML.
Data: 54 cửa hàng được đặt tại 22 thành phố khác nhau trong 16 bang của Ecuador. Gồm 4400 mặt hàng từ 33 họ và 337 lớp.
Gồm 7 file: 
1.Train: bao gồm các cột là id, date, store_nbr, item_nbr, unit_sales, onpromotion
_Cột id là số thứ tự
_Cột date là ngày tháng
_Cột unit_sales là đại diện cho lợi nhuận của mặt hàng cụ thể
_Cột onpromotion là cho biết items_nbr đó có được khuyến mãi trong một ngày cụ thể ở cột date và cửa hàng cụ thể ở cột store_nbr.
2.Test: bao gồm các cột id, date, store_nbr, item_nbr, onpromotion
_Các cột data, store_nbr, item_nbr kết hợp để dự đoán cùng với thông tin khuyến mãi ở cột onpromotion
3.Stores: bao gồm các cột store_nbr, city, state, type, cluster
_Cột city tên thành phố ở bang cụ thể ở cột state
_Cột cluster là mọt nhóm các của hàng tương tự
_Cột type là các loại cửa hàng
4.Items: bao gồm các cột item_nbr, family, class, perishable
_Cột
5.Transaction: bao gồm các cột date, store_nbr, transaction
Cột transaction là số lượng giao dịch mỗi ngày của các store
6.Oil: bao gồm các cột là date, dcoilwtico
Cột dcoilwtico: giá dầu hằng ngày
7.Holidays_events: bao gồm các cột 

