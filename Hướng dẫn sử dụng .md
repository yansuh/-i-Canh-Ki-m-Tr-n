# 🗡️ Thanh Trúc Phong Vân Kiếm Trận (The Sword Array)

## 🎮 Cách chơi (Cốt lõi)

Hãy bật camera lên và đưa tay ra! Hệ thống sẽ nhận diện thủ ấn (cử chỉ tay) của bạn để điều khiển kiếm trận:

| Thủ ấn (Cử chỉ) | Mô tả động tác | Hiệu quả kỹ năng |
|:---|:---|:---|
| **👈 Kiếm Quyết** | Ngón trỏ duỗi ra (hoặc tay hình súng) | **Du Long Tùy Hành**: Phi kiếm hóa thành rồng, bay lượn theo đầu ngón tay bạn. |
| **✋ Chưởng Pháp** | Xòe 5 ngón tay tự nhiên | **Liên Hoa Hiện Thế**: Vạn kiếm quy tông, tụ lại thành đóa sen kiếm nở rộ. |
| **✊ Nắm Đấm** | Nắm chặt 5 ngón tay | **Kiếm Thuẫn Hộ Thể**: Phi kiếm xoay tròn tốc độ cao, tạo bức tường phòng thủ tuyệt đối. |
| **🤘 Rock/Metal** | Ngón trỏ + Ngón út duỗi thẳng | **Đại Canh Kiếm Trận**: 【Cảnh báo năng lượng cao】 Triệu hồi pháp trận thông thiên và Cự Kiếm giáng lâm! |

> **💡 Mẹo nhỏ cho Đạo hữu**:
> * Hãy đảm bảo ánh sáng phòng đủ tốt để Camera nhìn rõ "thủ ấn" của bạn.
> * Nếu chơi trên điện thoại, hãy **xoay ngang màn hình** để có trải nghiệm phê nhất! (Hỗ trợ tự động thích nghi dọc/ngang).

## 🚀 Cách khởi chạy (Hướng dẫn siêu dễ)

Nếu bạn muốn chạy dự án này trên máy tính cá nhân (Localhost):

1.  **Cài đặt tài nguyên (Install dependencies)**:
    Mở Terminal (cửa sổ lệnh), đi vào thư mục dự án và gõ:
    ```bash
    npm install
    ```
2.  **Khai mở trận pháp (Start Project)**:
    Gõ lệnh:
    ```bash
    npm run dev
    ```
3.  **Nhập trận**:
    Khi thấy Terminal hiện `http://localhost:5173/`, hãy giữ phím `Command` (Mac) hoặc `Ctrl` (Win) và click vào link đó. Bay lên nào! 🛫
4.  **Đóng gói (Tùy chọn)**:
    Nếu muốn xuất file tĩnh để deploy:
    ```bash
    npm run build
    ```
    Sau khi build xong, file thành phẩm sẽ nằm trong thư mục `dist`.

## 📱 Điện thoại có chơi được không?

**Chắc chắn là được!**
Dự án đã được tối ưu hóa tận răng:
* Trên mobile: Tự động giảm số lượng phi kiếm (để tránh giật lag/nóng máy).
* Màn hình dọc: Tự động kéo xa camera (để không bị mất hình).
* Dù nằm chơi hay ngồi chơi, trải nghiệm vẫn mượt mà như Sunsilk.

## 🛠️ Tech Stack (Dành cho dân kỹ thuật)
* **React** + **Vite**
* **Three.js** (@react-three/fiber) - Lõi render 3D
* **Mediapipe** - Thư viện nhận diện cử chỉ tay của Google
* **Zustand** - Quản lý trạng thái (State management)
* **Postprocessing** - Hiệu ứng phát sáng (Bloom)

---
