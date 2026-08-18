Financial Text Analysis

Financial Text Analysis là một project ứng dụng Natural Language Processing (NLP) để phân tích cảm xúc (sentiment) của các bài viết/tin tức tài chính.

Project sử dụng mô hình FinBERT (ProsusAI/finbert) — một mô hình BERT được huấn luyện chuyên biệt trên dữ liệu tài chính — để phân loại văn bản thành:

Positive — Tích cực
Neutral — Trung lập
Negative — Tiêu cực

Cài đặt

1. Clone repository
git clone https://github.com/KiuPhuong/Financial-Text-Analysis.git

cd Financial-Text-Analysis

2. Tạo môi trường Python
conda create -n financial-nlp python=3.10 -y

conda activate financial-nlp

3. Cài đặt các thư viện từ requirements.txt
pip install -r requirements.txt
