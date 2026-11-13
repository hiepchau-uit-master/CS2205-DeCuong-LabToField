# Thu hẹp khoảng cách phòng thí nghiệm – thực địa trong chẩn đoán bệnh lá cây bằng mô hình nền tảng thị giác kết hợp thích ứng miền không giám sát

*Bridging the Lab-to-Field Gap in Plant Leaf Disease Diagnosis with Vision Foundation Models and Unsupervised Domain Adaptation*

Đề cương đồ án cuối kỳ môn **CS2205 – Phương pháp luận nghiên cứu khoa học** (lớp CS2205.AUG2026)
Giảng viên: PGS.TS. Lê Đình Duy
Trường Đại học Công nghệ Thông tin, ĐHQG-HCM

**Học viên:** Châu Đức Hiệp – MSHV 26848064

## Tài liệu

| Tài liệu | Tập tin |
|---|---|
| Đề cương chi tiết (Google Docs) | *đang cập nhật* |
| Slide thuyết trình (Google Slides) | *đang cập nhật* |
| Poster A3 (Google Slides) | [CS2205.AUG2026.DeCuong.Poster.pdf](CS2205.AUG2026.DeCuong.Poster.pdf) |

**Video trình bày (YouTube):** *đang cập nhật*

## Tóm tắt

Mô hình chẩn đoán bệnh lá cây học trên ảnh phòng thí nghiệm thường sụt giảm mạnh khi áp dụng cho ảnh chụp ngoài thực địa. Jeon và cộng sự (2026) thu hẹp khoảng cách này bằng ghép nền thực địa (FBR) kết hợp thích ứng miền không giám sát (UDA), nhưng chỉ thử trên backbone ResNet-18. Đề cương này đề xuất thay backbone bằng hai mô hình nền tảng thị giác là DINOv2 ViT-B/14 và SigLIP 2 ViT-B/16, rồi so sánh 3 backbone × 4 cấu hình (không thích ứng, chỉ FBR, chỉ UDA, FBR + UDA) trên hai thiết lập: PlantVillage → Plant Pathology 2020 (lá táo) và PlantVillage → PlantDoc (nhiều loại cây). Kết quả dự kiến gồm bảng so sánh, phân tích t-SNE/Grad-CAM, khuyến nghị khi nào cần FBR + UDA, và một ứng dụng web minh họa bằng Gradio.

> Đây là **đề cương** nghiên cứu, chưa phải báo cáo kết quả.
