# Financial Text Analysis

## 📌 Giới thiệu

**Financial Text Analysis** là một project ứng dụng **Natural Language Processing (NLP)** để phân tích cảm xúc (*sentiment analysis*) của các bài viết và tin tức tài chính.

Project sử dụng mô hình **FinBERT (`ProsusAI/finbert`)** — một mô hình BERT được huấn luyện chuyên biệt trên dữ liệu tài chính — để phân loại văn bản thành 3 nhóm:

* 🟢 **Positive** — Tích cực
* ⚪ **Neutral** — Trung lập
* 🔴 **Negative** — Tiêu cực

---

## ⚙️ Cài đặt

### 1. Clone repository

```bash
git clone https://github.com/KiuPhuong/Financial-Text-Analysis.git
cd Financial-Text-Analysis
```

### 2. Tạo môi trường Python

Sử dụng **Conda** để tạo môi trường:

```bash
conda create -n financial-nlp python=3.10 -y
```

Kích hoạt môi trường:

```bash
conda activate financial-nlp
```

### 3. Cài đặt các thư viện

Cài đặt toàn bộ dependencies từ file `requirements.txt`:

```bash
pip install -r requirements.txt
```

Sau khi cài đặt hoàn tất, môi trường đã sẵn sàng để chạy project.
