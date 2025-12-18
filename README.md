# Đồ án Học Máy - Nhóm 10
## ⚠️ LƯU Ý QUAN TRỌNG (ĐỌC KỸ TRƯỚC KHI CHẠY)
1.  **Môi trường chạy:** Dự án được tối ưu hóa cho môi trường cục bộ (**Local Machine**). Vui lòng **KHÔNG** chạy trên Google Colab để tránh lỗi tương thích.
2.  **Vị trí File dữ liệu:** File dữ liệu (Database/Dataset) bắt buộc phải đặt **CÙNG THƯ MỤC** (chung folder) với file code (`.ipynb`). Không để file dữ liệu nằm trong thư mục con khác.
## 👥 Thành viên & Phân công công việc
Dự án đã được hoàn thiện với sự đóng góp của các thành viên:
### 1. Hương
* **Mô hình:** Decision Tree (Cây quyết định).
* **Đánh giá & Trực quan hóa:**
    * Confusion Matrix (Ma trận nhầm lẫn).
    * Đường cong ROC.
    * Vẽ biểu đồ cây (Tree Diagram visualization).
### 2. Tuấn
* **Mô hình:** Naive Bayes (Sử dụng cả BernoulliNB và GaussianNB).
* **Đánh giá & Trực quan hóa:**
    * Confusion Matrix.
    * Đường cong ROC.
    * Biểu đồ thể hiện sự mất cân bằng dữ liệu (Imbalance Chart).
    * Heatmap (Biểu đồ nhiệt).
## 🛠️ Cài đặt và Hướng dẫn chạy (Local)
**Bước 1: Clone dự án về máy**
"bash
git clone [https://github.com/Darrys37/Project_machine_learning.git](https://github.com/Darrys37/Project_machine_learning.git)
cd Project_machine_learning"

Bước 2: Kiểm tra file Đảm bảo cấu trúc thư mục của bạn trông như sau (File code và file data nằm cạnh nhau):
Project_machine_learning/
├── Nhom_10_do_an_hoc_may.ipynb  <-- File Code
├── ten_file_du_lieu.csv         <-- File Data (Database)
└── README.md

Bước 3: Cài đặt thư viện
pip install numpy pandas scikit-learn matplotlib seaborn jupyter
