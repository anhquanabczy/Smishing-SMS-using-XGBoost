# IE403_DoAnCuoiKy: Smishing SMS Detection using XGBoost 🛡️📱

Đồ án cuối kỳ môn **Khai thác dữ liệu Truyền thông xã Hội (IE403)**. 
Dự án ứng dụng mô hình học máy **XGBoost** để phát hiện và phân loại các tin nhắn SMS độc hại (Spam, Lừa đảo/Smishing) thông qua việc phân tích dữ liệu văn bản và trích xuất đặc trưng. Giao diện ứng dụng được xây dựng thân thiện với người dùng bằng **Streamlit**.

---

## 🌟 Tính năng chính
* **Phân tích tin nhắn:** Đánh giá và phân loại một tin nhắn SMS xem nó là An toàn (Ham) hay Lừa đảo/Độc hại (Smishing/Spam).
* **Trích xuất đặc trưng (Feature Extraction):** Phân tích các dấu hiệu khả nghi trong tin nhắn như từ khóa đáng ngờ, độ dài văn bản, ký tự đặc biệt, và kiểm tra domain/URL.
* **Giao diện trực quan:** Tương tác trực tiếp với mô hình thông qua Web App được thiết kế bằng Streamlit.

---

## 🛠️ Yêu cầu hệ thống (Prerequisites)
Để chạy dự án này, máy tính của bạn cần cài đặt sẵn:
* [Python](https://www.python.org/downloads/) (Khuyến nghị bản 3.8 trở lên)
* [Git](https://git-scm.com/)

---

## ⚙️ Hướng dẫn cài đặt

**Bước 1: Clone dự án về máy**
Mở Terminal / Command Prompt và chạy lệnh sau:
```bash
git clone [https://github.com/anhquanabczy/Smishing-SMS-using-XGBoost.git](https://github.com/anhquanabczy/Smishing-SMS-using-XGBoost.git)
cd Smishing-SMS-using-XGBoost
