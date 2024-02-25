Covid 19 là đại dịch nghiêm trọng mà thế giới đã phải gánh chịu từ cuối năm 2019 đến nay. Nó đã cướp đi mạng sống, gây ảnh hưởng sức khỏe, tiền bạc, y tế cho mọi quốc gia nhiễm bệnh. Vì thế mình đã lựa chọn để tài trí tuệ nhân tạo "Phát hiện và khoanh vùng nhiễm bệnh covid 19 bằng kỹ thuật học sâu", sử dụng 3 mạng DenseNet 121, Inception V3, VGG 19 cho bài toán phát hiện nhiễm bệnh từ ảnh chụp phổi và sử dụng mạng UNET để khoanh vùng nhiễm bệnh nếu hình ảnh đó được phát hiện nhiễm Covid.
Theo đó kết quả cho thấy độ chính xác được sắp xếp theo thứ tự sau DenseNet 121 Accuracy : 0.9276%, Inception V3 Accuracy : 0.9074%, VGG 19 Accuracy : 0.8612% và mạng UNET có khả năng khoanh vùng nhiễm bệnh với độ chính xác cao.
Bài nghiên cứu này được xây dựng trên môi trường Google Colab với ngôn ngữ Python
Chi tiết code tại đây: 
https://colab.research.google.com/drive/1Hvg2jd0Zm-WG_Rk3s7Gg1F1dKH40aPBx#scrollTo=iM5qLza6Kfwp
https://colab.research.google.com/drive/1S5GnRpytJedSM8xzEeRr_Z2srAb-OCa0
https://colab.research.google.com/drive/1xdpsDjzD1E4YXaxS9M7Ci3FSAlsizccE

