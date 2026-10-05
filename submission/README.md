# Bài nộp Lab 18 — 2D Perception

**Học viên:** Trần Thị Như Ý

**Mã số học viên:** 2A202602372

**Repository public:** https://github.com/nhuY02/Track04-Day18-2D-perception-detection-segmentation-keypoints

## Kết quả

- Fine-tune YOLO26n-pose đủ **40 epoch** trên **Tesla T4**, `imgsz=640`, đánh giá trên 53 ảnh validation.
- Pose mAP50: **0.995**.
- Pose mAP50–95: **0.4573**.
- Box mAP50–95: **0.9303**.
- Q1–Q12 có câu trả lời trong notebook và `ket_qua.json`; Q11 dựa trên các ảnh val có OKS thấp nhất.
- Các phép kiểm tra hàm tự cài đặt và file auto-label được ghi trong báo cáo kết quả.

## Tệp nộp

- [`ket_qua.json`](ket_qua.json) — tiến độ, câu trả lời và metric.
- [`4b_results.csv`](4b_results.csv) — log đủ 40 epoch.
- [`4b_gpu_result.json`](4b_gpu_result.json) — bản ghi T4 được giữ nguyên khi chạy lại notebook trên CPU.
- [`q11_val_samples.png`](q11_val_samples.png) — GT và dự đoán trên sáu ảnh val khó nhất.
- [`autolabel/bus.txt`](autolabel/bus.txt) — nhãn YOLO-seg.
- [`../lab_2d_perception_student.ipynb`](../lab_2d_perception_student.ipynb) — notebook chính đã chạy và có output.
- [`../colab_4b.ipynb`](../colab_4b.ipynb) — notebook huấn luyện 4B độc lập trên GPU.

## Trạng thái nộp

Repository đã được push public. Còn thao tác LMS: dán URL repository ở trên vào ô nộp bài Ngày 18.
