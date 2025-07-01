# DATN
# Tên Dự án của bạn (Ví dụ: Hệ thống Giám sát An ninh Tự động)

> Một mô tả ngắn gọn, súc tích về dự án (1-2 câu). Ví dụ: "Một kịch bản tự động hóa sử dụng Python để phân tích log từ Snort IDS và gửi cảnh báo qua email."

## 1. Vấn đề & Mục tiêu
* Mô tả vấn đề mà dự án giải quyết (ví dụ: "Việc kiểm tra log thủ công tốn thời gian và dễ bỏ sót cảnh báo quan trọng.").
* Nêu mục tiêu của dự án (ví dụ: "Tự động hóa hoàn toàn quy trình giám sát và cảnh báo để rút ngắn thời gian phản ứng.").

## 2. Sơ đồ Kiến trúc (Architecture Diagram)
* *Đây là phần cực kỳ quan trọng.* Hãy vẽ một sơ đồ đơn giản mô tả cách các thành phần trong dự án của bạn kết nối với nhau.
* **Công cụ gợi ý:** [draw.io](http://draw.io) (miễn phí và mạnh mẽ).
* Sau khi vẽ xong, hãy export ra ảnh và chèn vào file README.

![Sơ đồ kiến trúc](link_den_file_anh_cua_ban.png)

## 3. Các chức năng chính
* Liệt kê các chức năng chính bằng gạch đầu dòng.
    * Tự động đọc log từ thư mục `/var/log/snort`.
    * Phân tích và lọc ra các cảnh báo có độ ưu tiên cao.
    * Gửi email cảnh báo với định dạng rõ ràng.
    * Lập lịch chạy tự động mỗi 15 phút bằng Cron.

## 4. Công nghệ sử dụng
* **Ngôn ngữ:** Python 3.8
* **Công cụ:** Snort, Cronjob, Zabbix
* **Hệ điều hành:** Ubuntu Server 22.04

## 5. Hướng dẫn Cài đặt & Sử dụng
* **Yêu cầu:** Liệt kê các phần mềm cần cài đặt trước (ví dụ: `python3-pip`, `snort`).
* **Cài đặt:**
    ```bash
    # Clone repository này về
    git clone [https://github.com/your-username/your-project.git](https://github.com/your-username/your-project.git)

    # Di chuyển vào thư mục dự án
    cd your-project

    # Cài đặt các thư viện cần thiết
    pip install -r requirements.txt
    ```
* **Sử dụng:** Hướng dẫn cách chạy script hoặc cấu hình dịch vụ.
    ```bash
    # Chạy script thủ công
    python3 main.py
    ```
