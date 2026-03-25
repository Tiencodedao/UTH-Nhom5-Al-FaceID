# 🤖 Trí tuệ Nhân tạo (Introduction to AI) - Nhóm 5

Chào mừng bạn đến với kho lưu trữ mã nguồn của **Nhóm 5**. Đây là nơi tổng hợp các bài tập thực hành, thuật toán tìm kiếm và lập trình logic trong khuôn khổ môn học Cơ sở Trí tuệ Nhân tạo.

---

## 👥 Thành viên nhóm (Nhóm 5)

| STT | Họ và Tên |
|:---:|:---|
| 1 | **Phan Quý Bảo Thành** |
| 2 | **Kim Ngọc Tiến** |
| 3 | **Võ Nguyễn Mạnh Trường** |
| 4 | **Trần Thanh Tuấn** |
| 5 | **Ứng Đỗ Thế Vinh** |

---

## 📘 Nội dung dự án

Dự án tập trung vào việc triển khai và tối ưu hóa các bài toán kinh điển trong AI:

### 1. Tìm kiếm không gian trạng thái (State Space Search)
* Triển khai các chiến lược tìm kiếm từ cơ bản đến nâng cao: **BFS**, **DFS**.
* Tối ưu hóa tìm kiếm với thuật toán **A\*** (A-Star) dựa trên hàm Heuristic.
* **Ứng dụng:** Giải bài toán 8-puzzle và tìm đường đi ngắn nhất.

### 2. Bài toán thỏa mãn ràng buộc (CSPs)
* Giải quyết các bài toán **Constraint Satisfaction Problems** bằng kỹ thuật quay lui (Backtracking).
* Áp dụng kiểm tra tính nhất quán (Forward Checking) để tăng tốc độ xử lý.
* **Ứng dụng:** Bài toán tô màu bản đồ (Map Coloring) và xếp quân Hậu.

### 3. Lập trình Logic (Prolog)
* Xây dựng **Cơ sở tri thức (Knowledge Base)** bằng ngôn ngữ Prolog.
* Thiết lập các luật suy diễn (Rules) và sự thật (Facts) để thực hiện truy vấn logic.
* **Ứng dụng:** Giải quyết bài toán quan hệ gia đình và lập luận logic hình thức.

### 4. Tìm kiếm đối kháng (Adversarial Search)
* Thuật toán **Minimax** kết hợp kỹ thuật cắt tỉa **Alpha-Beta Pruning**.
* Xây dựng trí tuệ nhân tạo cơ bản cho các trò chơi đối kháng 2 người.

---

## 🛠 Công cụ & Công nghệ

* **Ngôn ngữ chính:** `Python 3.x`, `Prolog` (SWI-Prolog).
* **Môi trường phát triển:** Visual Studio Code, Jupyter Notebook.
* **Quản lý phiên bản:** Git & GitHub.

---

## 📂 Cấu trúc thư mục

```text
├── StateSpaceSearch/     # Các thuật toán tìm kiếm (A*, BFS, DFS)
├── CSPs/                 # Bài toán thỏa mãn ràng buộc
├── Prolog_Logic/         # Lập trình logic (file .pl)
├── Adversarial/          # Tìm kiếm đối kháng (Game AI)
├── docs/                 # Báo cáo và tài liệu liên quan
└── README.md             # File hướng dẫn này
