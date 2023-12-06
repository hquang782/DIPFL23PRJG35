# Wild animal reg
## Cài Đặt

1. Mở terminal/command line.
2. Di chuyển đến thư mục "src":
    ```bash
    cd đường dấn đến dự án/DIPFL23PRJG35/src
    ```
3. Cài đặt các thư viện cần thiết bằng cách chạy lệnh sau:
    ```bash
    pip install -r requirements.txt
    ```

## Sử Dụng

### 1. Chuẩn Bị Video Đầu Vào

Đặt các tệp video bạn muốn xử lý trong thư mục "videos". Hai video demo, `Demo1.mp4` và `Demo2.mp4`, đã được cung cấp sẵn.

### 2. Chạy Chương Trình

1. Mở terminal/command line.
2. Di chuyển đến thư mục "src":
    ```bash
    cd đường dấn đến dự án/DIPFL23PRJG35/src
    ```
3. Chạy lệnh sau để thực hiện nhận diện đối tượng trên một video cụ thể:
    ```bash
    python yolo_video.py --input videos/[tên_video].mp4 --output output/[tên_video].avi
    ```
    Ví dụ:
    ```bash
    python yolo_video.py --input videos/Demo2.mp4 --output output/Demo2.avi
    ```

Thay thế `[tên_video]` bằng tên của tệp video cần xử lý. Video đầu ra sẽ được lưu trong thư mục "output".

