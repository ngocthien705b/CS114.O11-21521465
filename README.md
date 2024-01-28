# CS114.O11-21521465
## Bài toán: Phát hiện lửa

* Input: Hình ảnh chụp từ các thiết bị ghi hình.
* Output: Vị trí và phạm vi ngọn lửa trong hình ảnh nếu có.
* Ngữ cảnh ứng dụng: Giúp phát hiện sớm nguy cơ cháy nổ.

### Mô tả về bộ dữ liệu:
* Bộ dữ liệu có 753 hình ảnh. Một nửa được lấy từ bộ dữ liệu có sẵn, phần còn lại được crawl từ google và dán nhãn thủ công bằng CVAT. 
* Chia train/val: 70/30

### Mô tả thuật toán:
Huấn luyện và đánh giá mô hình YOLOv8 trên bộ dữ liệu đã thu thập được.

### Tham khảo:
* https://yolov8.com/
* https://docs.ultralytics.com/
* https://www.youtube.com/watch?v=Mpsdby8zCTY
* https://www.freecodecamp.org/news/how-to-detect-objects-in-images-using-yolov8
* https://github.com/AndreyGermanov/yolov8_pytorch_python
#### Nguồn dữ liệu:
* https://miai.vn/thu-vien-mi-ai/
