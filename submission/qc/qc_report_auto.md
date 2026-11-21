# Báo cáo QC tự động (nháp)

> **Gợi ý** do script tính; bạn xác nhận. Script chỉ đếm theo phiếu kiểm bằng mắt người.

## Mẫu
- 6 ảnh (1 ca khó + 5 ngẫu nhiên), 97 đối tượng.
- taxonomy v1.0

## Số đo
| Chỉ số | Giá trị | Mẫu số |
|---|---|---|
| Lỗi **theo đối tượng** | 1/97 = 1.0% | 97 đối tượng trong mẫu |
| **Ảnh có lỗi** (dùng cho ngưỡng) | 1/6 = 16.7% | 6 ảnh trong mẫu |
| Máy: accepted / edited / deleted | 465/536 = 86.8% / 14/536 = 2.6% / 47/536 = 8.8% | 536 box máy |
| Máy: added | 27/506 = 5.3% | 506 đối tượng sau duyệt |
| Bắt lỗi bẫy | 11/12 = 91.7% | 12 bẫy |

## Top 3 loại lỗi
| Loại lỗi | Số lỗi | Ảnh ví dụ |
|---|---|---|
| thua | 1 | img_006.jpg |

## Giới hạn thống kê
- 1 ảnh lỗi trong 6 ảnh mẫu: cận trên 95% (Wilson) của tỉ lệ ảnh lỗi thật là **56%**. Ngưỡng 2% không thể được **chứng minh** bằng mẫu nhỏ như vậy: hãy nói rõ giới hạn này trong báo cáo.

## Gợi ý quyết định
**REWORK**

- ảnh có lỗi 16.7% > 2%

Cây quyết định: Hold (guideline chưa rõ / dữ liệu hỏng) -> Rework (> ngưỡng, lỗi lặp, bắt bẫy / nhất quán thấp) -> Release.
