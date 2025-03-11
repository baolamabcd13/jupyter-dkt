# Dự án Khai phá Dữ liệu với Jupyter Notebook

## Hướng dẫn cài đặt và sử dụng

### 1. Clone repository

```bash
git clone https://github.com/baolamabcd13/jupyter-dkt.git
cd jupyter-dkt
```

### 2. Tạo môi trường ảo Python

#### Trên Windows:

```bash
python -m venv dkt_env
dkt_env\Scripts\activate
```

### 3. Cài đặt các thư viện cần thiết

Hoặc nếu có file requirements.txt:

```bash
pip install -r requirements.txt
```

### 4. Khởi động Jupyter Notebook

```bash
jupyter notebook
```

Trình duyệt web sẽ tự động mở với giao diện Jupyter Notebook. Nếu không, bạn có thể truy cập vào địa chỉ được hiển thị trong terminal (thường là http://localhost:8888).

### 5. Mở và chạy notebook

- Trong giao diện Jupyter Notebook, tìm và mở file notebook có đuôi `.ipynb`
- Để chạy toàn bộ notebook, nhấn vào "Kernel" > "Restart & Run All"
- Để chạy từng ô code, nhấn vào ô code và nhấn Shift+Enter
